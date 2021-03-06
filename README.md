# SAS Language Definition for VSCode

 Syntax highlighting for the SAS files in VsCode, with precise syntax match, SAS like theme and code snippets. 
 The syntax highlighting uses tmLanguage files sourced from https://raw.githubusercontent.com/martinring/tmlanguage/master/tmlanguage.json. 


## Features
#### Data Step
![](feature1.jpg)
#### Proc SQL
![](feature2.jpg)
#### Inside Macro
![](feature3.jpg)
#### Statistical Procedure
![](feature4.png)


## Extension Settings
Firstly, change syntax engine to SAS
* toggle `CTRL+SHIFT+P` to open the command panel
* enter `change language mode`
* select SAS
![](setup1.png)

Secondly, change theme to SAS
* toggle `CTRL+SHIFT+P` to open the command panel
* enter `color theme`
* select SAS
![](setup2.png)

## Known Issues
Syntax parse error if there are unmatched `'` or `"` even if being marked by macro mask
![](issue1.jpg)

## For more information

**Enjoy!**

## TO-DO
- [x] Add code snippets
- [ ] More proc grammer into syntax and the corresponding snippets
    - [x] CATALOG
    - [x] CONTENTS
    - [x] DATASETS
    - [x] EXPORT
    - [x] IMPORT
    - [x] SGPLOT
    - [ ] TEMPLATE
    - [x] PRINT
    - [x] RANK
    - [x] FREQ
    - [x] CORR
    - [x] UNIVARIATE
    - [x] ANOVA
    - [x] CLUSTER
    - [x] FACTOR
    - [x] REG
    - [x] SURVEYSELECT
    - [x] LOGISTIC
    - [x] LIFETEST
    - [x] TRANSPOSE
    - [x] APPEND 
    - [x] CPORT
    - [x] FASTCLUS
    - [x] GLM
    - [x] MIXED
    - [x] NPAR1WAY
    - [x] TTEST