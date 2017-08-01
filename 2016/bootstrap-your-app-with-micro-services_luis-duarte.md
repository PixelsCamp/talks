Bootstrap your app using Microservices
========================

* Speaker   : Luís Duarte
* Length    : 30-45 mins
* Language  : English

Description
-----------

In this presentation i will demonstrate how to Bootstrap an App with Microservices using Java (Spring Boot and Spring Cloud), Kong, Consul and Docker.
I'll implement 2 very simple services using Spring Boot, show you how to register them, fetch their configuration from Consul (A KMS service should be used for this, but it would make this presentation longer and more complex) and transform each of the components into Docker Containers.

The purpose of this presentation is to show you a development cycle so that you can easily deploy it to services using Kubernetes, Amazon ECS, OpenShift NextGen, etc...

Overview:
	- Create 2 simple Spring Boot + Jersey Services
	- Generate Docker images for each service.
	- Integrate Spring Boot with Consul.
	- Configure Local API Gateway (Kong) to act as reverse proxy.

If there is time left, i'll demonstrate how to deploy the components to Amazon ECS (Elastic Container Service), replacing Kong with Amazon's API Gateway, which will most likely be the provider being used for the App Hosting.

Video
-----

[![Video](https://img.youtube.com/vi/_3ujgUZz-NU/maxresdefault.jpg)](https://www.youtube.com/watch?v=_3ujgUZz-NU)

_Click the thumbnail above to watch the video from this talk on Youtube_

Speaker Bio
-----------

![Speaker Image](https://avatars1.githubusercontent.com/u/1164534?v=3&s=400)

A Sofware Engineer with 2 years of experience as Sys Admin and 5 years of experience as a Developer. I consider myself a "techie" that loves to keep up to date with latest trends in Software Architecture.

With a BSc Degree in Computer Science and Computer Engineering from Instituto Superior de Engenharia de Lisboa (ISEL).

Links
-----

* Blog: http://www.luisduarte.net
* Github: http://github.com/driverpt
* LinkedIn: https://pt.linkedin.com/in/driverpt

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
