# Go API client for functions

null

## Overview
This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

- API version: 0.0.13
- Package version: 0.0.13
- Build date: 2016-11-09T19:57:14.058Z
- Build package: class io.swagger.codegen.languages.GoClientCodegen

## Installation
Put the package under your project folder and add the following in import:
```
    "./functions"
```

## Documentation for API Endpoints

All URIs are relative to *https://127.0.0.1:8080/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AppsApi* | [**AppsAppGet**](docs/AppsApi.md#appsappget) | **Get** /apps/{app} | Get information for a app.
*AppsApi* | [**AppsAppPut**](docs/AppsApi.md#appsappput) | **Put** /apps/{app} | Create/update a app.
*AppsApi* | [**AppsGet**](docs/AppsApi.md#appsget) | **Get** /apps | Get all app names.
*AppsApi* | [**AppsPost**](docs/AppsApi.md#appspost) | **Post** /apps | Post new app
*RoutesApi* | [**AppsAppRoutesGet**](docs/RoutesApi.md#appsapproutesget) | **Get** /apps/{app}/routes | Get route list by app name.
*RoutesApi* | [**AppsAppRoutesPost**](docs/RoutesApi.md#appsapproutespost) | **Post** /apps/{app}/routes | Create new Route
*RoutesApi* | [**AppsAppRoutesRouteDelete**](docs/RoutesApi.md#appsapproutesroutedelete) | **Delete** /apps/{app}/routes/{route} | Deletes the route
*RoutesApi* | [**AppsAppRoutesRouteGet**](docs/RoutesApi.md#appsapproutesrouteget) | **Get** /apps/{app}/routes/{route} | Gets route by name
*TasksApi* | [**TasksGet**](docs/TasksApi.md#tasksget) | **Get** /tasks | Get next task.


## Documentation For Models

 - [App](docs/App.md)
 - [AppWrapper](docs/AppWrapper.md)
 - [AppsWrapper](docs/AppsWrapper.md)
 - [ErrorBody](docs/ErrorBody.md)
 - [ModelError](docs/ModelError.md)
 - [NewTask](docs/NewTask.md)
 - [Route](docs/Route.md)
 - [RouteWrapper](docs/RouteWrapper.md)
 - [RoutesWrapper](docs/RoutesWrapper.md)
 - [Task](docs/Task.md)
 - [TaskWrapper](docs/TaskWrapper.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author



