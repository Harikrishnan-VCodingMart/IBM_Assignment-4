# create a account in docker hub to post our registry
# create a repositories in the docker hub

# come to the folder and type
# create a docker file and build that file using the name of <user-name>/<repo-name>:tag
docker build . --tag harikrishnan2001/oviyaibm:latest
# push the image to the docker hub using
docker push harikrishnan2001/oviyaibm:latest