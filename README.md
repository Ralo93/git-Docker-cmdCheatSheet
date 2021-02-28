## Personal Use of Git, Docker and cmd functions

### Docker run with interactive shell and local repo mount:
docker run -it -v ${PWD}:/<dockerRepo(data)> datascienceworkshops/data-science-at-the-command-line <p>
  
### Reentering Docker:
docker run -it -v ${PWD}:/data datascienceworkshops/data-science-at-the-command-line <p>
  
### for seeing installed python packages in docker:
docker exec <container ID> pip list
  
  
  
