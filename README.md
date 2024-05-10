# README

### The script and dataset of serverless-related bugs

##### We downloaded all the data on December 19, 2023

``Dataset``  --- the dataset of GitHub projects, SO posts, and 

$\qquad$ ```selected_projects.xlsx``` -- the dataset of 2489 candidate projects and 15 selected projects in the end

$\qquad$ ```extracted_issues.xlsx``` -- the 3257 issues extracted from selected projects

$\qquad$ ```raw_so_posts.xlsx``` -- the 3370 raw posts collected from Stack Overflow

$\qquad$ ```annotated_dataset.xlsx``` -- the manually labeled 592 bugs and the result of difficulty comparison

```GitHub_Code``` --- the script to collect, filter projects and extract and filter issues

$\qquad$ ```filter.py``` -- the script to filter candidate projects by number of stars, forks, and contributors

$\qquad$ ```get_issues.py``` -- the script to extract issues from selected projects

$\qquad$ ```README.md``` -- the tutorial to collect data from GitHub

```SO_Code``` --- the script to collect SO posts

$\qquad$ ```README.md``` -- the tuorial to collect data from Stack Overflow
