# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- #### Clone the repository into your local machine using the following link:

    [https://github.com/ObelusFamily/Anythink-Market-nbz86](https://github.com/ObelusFamily/Anythink-Market-nbz86)

```bash
git clone https://github.com/ObelusFamily/Anythink-Market-nbz86
 ```


- #### Install Docker from the following link:

    [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

    - for linux install from package managers or tar
    - for Windows and Mac users install Docker desktop



- #### Verify docker installation using the following command:

    ```bash
    docker -v
    ``` 
    and
    ```bash
    docker-compose -v
    ```
    _`#` for any problems refer to docs_
    _[https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)_


- #### Kick start the frontend, backend and database containers using the following command:

    ```bash
    docker-compose-up 
    ```


