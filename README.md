# Spring-boot 1.3.0 static resources reload issue

This repository contains simple spring-boot application that depicts the issue described above.

## Prerequisites

    * Java 8 installed on your local machine
    * Apache Maven installed on your local machine

## How to reproduce the issue

     * Run your spring boot service:  "mvn spring-boot:run"
	 * Open you browser and navigate to http://localhost:8080
	 * Try to change existing text in static/index.html file
	 * Hit Ctr+R in your browser and check if change is visible

## How to make it work

    * Open pom.xml file and change spring-boot-starter-parent version to 1.2.7
