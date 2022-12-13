# Building microservices using Go with Docker, Kubernetes and MongoDB

## Overview

An example project which demonstrates the use of microservices for a fictional movie theater.
The backend is powered by 4 microservices, all of which happen to be written in Go, using MongoDB for manage the database and Docker to isolate and deploy the ecosystem.

 * Movie Service: Provides information like movie ratings, title, etc.
 * Show Times Service: Provides show times information.
 * Booking Service: Provides booking information.
 * Users Service: Provides movie suggestions for users by communicating with other services.

The use case is based on the project written in Python by [Umer Mansoor](https://github.com/umermansoor/microservices).

The project structure is based in the knowledge learned in:

* Golang structure: <https://peter.bourgon.org/go-best-practices-2016/#repository-structure>
* Book Let's Go: <https://lets-go.alexedwards.net/>

## Deployment

The application can be deployed in both environments: **local machine** or in a **kubernetes cluster**. You can find the appropriate documentation for each case in the following links:

* [local machine (docker compose)](./docs/localhost.md)
* [kubernetes](./docs/kubernetes.md)

## How To Use Services

* [endpoints](./docs/endpoints.md)
