# Docker

### Docker run with interactive shell and local repo mount:
docker run -it -v ${PWD}:/<dockerRepo(data)> datascienceworkshops/data-science-at-the-command-line <p>
  
### Reentering Docker:
docker run -it -v ${PWD}:/data datascienceworkshops/data-science-at-the-command-line <p>
  
### for seeing installed python packages in docker:
docker exec <<container ID>> pip list
  
 
# Git

### for showing added git files: 
git diff --cached --name-only --diff-filter=A <p>
  
  
# CMD

### for moving file to directory: 
mv newColumn.csv /data/data/interim/
