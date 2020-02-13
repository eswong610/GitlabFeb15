Q1: Why are readme's in github in the .md format? What is .md and why does github
use it instead of .txt, .html .docx, or any other file format?

md is used to generate an html page for the github repo. It makes a text file look presentable on the browser without actually having to write up an html file. An md file is a markdown file and it has its own speciic syntax to make words bold, italic, or strikethroughs 

Q2: Is the keyword "fixes" the only way to auto-close an issue from a PR 
(pull request). Is there other keywords that can accomplish the same thing?

Possible keywords to auto-close a PR issue 
close
closes
closed
fix
fixes
fixed
resolve
resolves
resolved

Q3: Do you have to create a new PR EVERYTIME you want to close an issue,
or is it possible to close multiple issues within a single PR? If so, 
how?

You can close multiple issues with one pull request but they all must have the full syntax
eg. Resolves #10, resolves #123 in the body of the PR. 