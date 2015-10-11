# Github Maid
Scripts, Tools and Utilities to help maintain an Organization in Github.

## Commons Module
* All API calls should ask for authentication
  * Personal Access Tokens is a preferred method of authentication.
  * Username, Password is the secondary method of authentication.

## Repository State Module
* Repository can have two states: Active or Inactive
* Criteria for identifying an inactive Repository
  * No commits on the repository (all branches included) in the last 90 days.
  * The inactivity period (eg:90 days) has to be configurable. The user should be able to set it through a parameter. Default is 90 days.
* The Repository can be a Public or Private Repository.  

## Collaborators List Module
* Get a list of collaborators who have write access to the repository.
* The list should contain first_name, last_name and email for each collaborator.
* The output of the list should be in a CSV format.


## Development Tools & Stack
* Python (https://www.python.org/)
* Fabric (http://www.fabfile.org/)
