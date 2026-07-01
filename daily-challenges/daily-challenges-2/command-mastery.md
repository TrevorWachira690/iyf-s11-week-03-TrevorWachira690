# Find command Mastery questions

## 1. Find all CSS files in your project folder
**Command:**
```Bash
find -name "*.css"
``` 
**Answer:**
```Bash
./iyf-s11-week-02-TrevorWachira690/styles.css
./iyf-s11-week-03-TrevorWachira690/daily-challenges/daily-challenge-1/src/css/styles.css
```

## 2. Find all files modified in the last 7 days.
**Command:**
```Bash
find -type f -mtime -7
```
**Answer:**
```Bash
./iyf-s11-week-01-TrevorWachira690/.git/config
./iyf-s11-week-01-TrevorWachira690/.git/description
./iyf-s11-week-01-TrevorWachira690/.git/HEAD
./iyf-s11-week-01-TrevorWachira690/.git/hooks/applypatch-msg.sample
./iyf-s11-week-01-TrevorWachira690/.git/hooks/commit-msg.sample
./iyf-s11-week-01-TrevorWachira690/.git/hooks/fsmonitor-watchman.sample
...
```

## 3. Search for the word "flex" in all CSS files
**Command:**
```Bash
grep -r "flex" --include="*.css" .
```
**Answer:**
```Bash
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-wrap: wrap;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-direction: column;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-direction: column;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-wrap: wrap;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-direction: column;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-wrap: wrap;
./iyf-s11-week-02-TrevorWachira690/styles.css:    display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:    flex-direction: column;
./iyf-s11-week-02-TrevorWachira690/styles.css:        display: flex;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex-direction: row;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex-direction: row;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex-direction: row;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex: 1;
./iyf-s11-week-02-TrevorWachira690/styles.css:        justify-content: flex-start;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex: 1;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex-direction: row;
./iyf-s11-week-02-TrevorWachira690/styles.css:        flex: 1;
```

## 4. Count occurances of "div" in your HTML files
**Command:**
```Bash
grep -roh "div" --include="*.html" . |wc -l
```
**Answer:**
```
53
```
