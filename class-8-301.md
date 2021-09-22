# API design best practice 

## What does REST stand for?

REST stands for representational state transfer and was created by computer scientist Roy Fielding.

## REST APIs are designed around a ____.

Around recources such as: object, data and service that can be accessed by the client.

## What is an identifier of a resource? Give an example.

URLs example: http://www.w3.org

## What are the most common HTTP verbs? 

The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are **POST, GET, PUT, PATCH, and DELETE.** These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.

## What should the URLs be based on?

Collections of data 

## Give an example of a good URL.

https://www.computerhope.com

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? 

chatty web API: Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.

**bad thing** Reason why chatty APIs are considered poor quality is because requiring multiple network calls will slow down an application. This is because each call contains data overhead (i.e. sender information, headers, authentication) which will slow down an application as well as network latency per each request.

## What status code does a successful GET request return?

The HTTP 200 OK success status response code indicates that the request has succeeded.

## What status code does an unsuccessful GET request return?

404 Error not found

## What status code does a successful POST request return?

201

## What status code does a successful DELETE request return? 

204