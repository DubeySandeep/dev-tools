# Dev-tools

Tools for developing oppia web project.

### Steps for testing:
- Create a new dir.

    ```
    mkdir test_dir
    cd test_dir
    ```
- Clone both the forked oppia and dev-tools repo

    ```
    git clone git@github.com:DubeySandeep/dev-tools.git
    git clone git@github.com:<your-username>/oppia.git
    ```
- Run the oppia web server

    ```
    make devserver
    ```

Run `make stop` to stop all the running containers and `make destroy` to stop and remove all the containers.


