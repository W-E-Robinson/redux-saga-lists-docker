# redux-lists-docker

This is the docker-compose repo that runs [redux-lists-frontend](https://github.com/W-E-Robinson/redux-lists-frontend) and [redux-lists-backend](https://github.com/W-E-Robinson/redux-lists-backend).

Redux-lists is a simple frontend to-do list app that serves as a template/reference for Typescript Redux Saga.
## Implementation

Required file structure:

```
PARENT_DIRECTORY
└──redux-lists-frontend
└──redux-lists-backend
└──redux-lists-docker
```
Navigate to redux-lists-docker and run (requires ports 3000 and 8080 to be free):
```
docker-compose up
```
