# File Definition
The content taxonomy tab separated value (.tsv) file includes three columns
1. UniqueID - varchar(??) 
2. Parent - varchar(??) when the category is a child, its parent is listed. Empty parent is top-level category.
3. Name - varchar(??) Name of the category.

Using the UniqueID and Parent columns a mulit-level hierarchy can be determined. 

# Example for building model in RDBMS
## this was written for Postgres YMMV
https://github.com/catda/iab-taxo/blob/main/content/iab_content_ddl.sql
