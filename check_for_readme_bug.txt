## check all repo's for the readme bug
for d in ./*/ ; do (cd "$d" && cat readme.md | grep "\[object" && echo "$d") >> output.txt; done; cat output.txt | grep -v "Sav\|sav\|compl" > output2.txt
## zero results found for master branch.
