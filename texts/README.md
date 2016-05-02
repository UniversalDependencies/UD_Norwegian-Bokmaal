# Text files

## Directory contents

* `{train|dev|text}.txt`: Raw text files that match the tokenized no-ud-{train|dev|text}.conllu files
* `original/`: The raw files that the split txt files are collected from, in their original form
* `fixed/`: Fixed versions of the files in original. There were many mismatches between the strings found in the .conllu files and the original .txt files. The files in fixed/ contains token strings that match the .conllu files one-to-one, with a single exception, the token to mark sentence ends after headers, `|` .
* `diffs.txt`: Contains all the diffs between original and fixed, the result of the shell command:  
`for file in original/*.txt; do echo $file; diff -b "$file" "fixed/${file##*/}"; done` 

## Notable diffs/fixes
* Sentences ending with an abbreviation had sentence final punctuation both on the abbreviated token and on a separate token, e.g.  
  `John, jr.`  
  had corresponing treebank file  
  	`John`  
	`,`  
	`jr.`  
	`.`  
  In these cases, we duplicated the dot, so `John, jr.` => `John, jr..`
* Text with no corresponing treebank file tokens were deleted. This was true for e.g. references to News Agencies, photo credits, etc.