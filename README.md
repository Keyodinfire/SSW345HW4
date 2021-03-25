Hello! This is where I will be putting my code for the answers to Homework 4. 

The first task to complete in Homework 4 was to write code to list branches in Git. 

The following code will list pertinent information for all branches in the specified user's specified repo:

$ curl \
> -H "Accept: application/vnd.github.v3+json" \
> https://api.github.com/repos/{username}/{repoName}/branches/

