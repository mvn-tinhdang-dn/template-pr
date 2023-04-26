##  I. Description
### 1. Spec or Requirement  (REQUIRED)

_* Please describe the task and attack requirement or spec if we have:_ 
 + [ ] Link jira /  task : 
 + [ ] Link google driver /  figma /Confluence : 
 + [ ] Link or Message slack   : https://monstarlab.slack.com/xxxxx

###  2.  Sort Description  (REQUIRED)
_*  Write  detail description about your task_ 

## II.  Check list (Dev) 
_* For developer tracking all list below before send to reviewer_

### 1. Impacted ranges  ( Optional) 
_* List all impact range if affect to other function_ 

| Method/file changes | Referenced by methods | Affected features |
| --- | --- | --- |
| `path/To/file.extension` | List of: `Path\To\ClassName - methodName` | Feature name |

### 2. Sql list (Optional)
 - [ ] List **all of sql query related with query your change** on file **query.txt**
-  [ ] Default if don't have query : N/A 
### 3.  `explain` each sql query (Optional)
- [ ] Run **explain** command for each sql query and attack the images **your change** .
- [ ] Default if don't have query : N/A 

### 4. Test List  (REQUIRED)
- [ ] Check all source code pass CI 
- [ ] Check all source code pass UT 
- [ ] List all test cases you have
- Case 1: 
- Case 2: 
- [ ]  Self-review of my code
- [ ]  Self-test of my code

## V. Track List (Reviewer) 
_* For reviewer tracking all list above before merge_

- [ ] Review source code 
- [ ] Check description
- [ ] Check impact range
- [ ] Check SQL list
- [ ] Check Explains
- [ ] Check Test list 
- [ ] Check working function
