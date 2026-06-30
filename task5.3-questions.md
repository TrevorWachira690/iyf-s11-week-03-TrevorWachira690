## Task 5.3 questions and answers
**1. How many HTML files are in your portfolio project?** 

Command:
```Git bash
 find . -name "*.html" | wc -l
```
> Answer= 8

**2. Which files contain the word "contact"?**

Command:
```Git Bash
 grep -ril "contact"
```
>Answer= 11

**3. How many lines is your CSS file?**

Command:
```Git bash
 wc -l iyf-s11-week-02-TrevorWachira690/styles.css
```
>Answer= 654

**4. What were your last 10 terminal commands?**

Command:
```Git bash
history | tail -10
```
>Answer=
```Git bash
  345  ls
  346  cd ..
  347  find . -name "*.html"
  348  find . -name "*.html" | wc -1
  349  wc --help
  350  grep -ril "contact"
  351  find . -name "*.html" | wc -l
  352  grep -r -l "contact"
  353  wc -l iyf-s11-week-02-TrevorWachira690/styles.css
  354  history | tail -10
```
