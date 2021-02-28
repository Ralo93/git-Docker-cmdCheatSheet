# Docker

### Docker run with interactive shell and local repo mount:
> docker run -it -v ${PWD}:/<dockerRepo(data)> datascienceworkshops/data-science-at-the-command-line <p>
  
### Reentering Docker:
> docker exec -it dockerId bash
  
### for seeing installed python packages in docker:
> docker exec container ID pip list

### show docker images:
> docker ps -a
  
 
# Git

### for showing added git files: 
> git diff --cached --name-only --diff-filter=A <p>

### Usual git stuff:
> git branch, git branch -d BranchName, git branch -M newBranchName, git tree, 
  
  
# Cmd

### for moving file to directory: 
> mv newColumn.csv /data/data/interim/

### drop columns:
> file.csv csvcut -C columnname

### sqlQuery:
> file.csv csvsql --query "SELECT * FROM stdin WHERE Age > 70 AND Survived = 1" > newFile.csv

### merging columns:
> file.csv csvsql --query "SELECT id, firstName || ' ' || lastName AS full_name, born, city FROM stdin" > newFile.csv

### copying folder structure into new project:
> cp -r ./structure ./newProject

### remove dir:
rm -r drake
