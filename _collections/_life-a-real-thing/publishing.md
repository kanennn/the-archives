---
published: false
---

in this folder, everything will be published by default as long as output: true is on
Output: false overrides everyting
output: true can be overridden

Pages are hidden if they are

-   in a folder starting with an underscore, or
-   if published is set to false in their yaml
-   if the date in the filename is set to the future
-   if the date in set to future in yaml

subfolders in collections are also ignored.
jekyll will change the url of files in subdirectories, but subdirectories are more for user organization. 
Underscored directories can be used for unpublished files. 
For grouping with Jekyll you can use Yaml attributes in files to group files.
