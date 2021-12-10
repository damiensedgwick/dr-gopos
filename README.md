# Docker React Go PostreSQL

Just somewhere for me to experiment with the above technologies in a Dockerized environment.

## TODO
- [] Dockerize PostgreSQL
    * Make sure that this is accessible from TablePlus.

- [] Dockerize Golang Server
    * Must be accessible on local host so that it can be visiting in the browser / accessed from the frontend
    can serve requests to the frontend.

- [] Dockerize React Frontend
    * This might not be necessary. If not, use pnpm. Undecided on create-react-app or roll your own.

- [] Connect the 3 Dockerized applications together
    * All 3 parts of the application should be able to communicate with each other without issue.