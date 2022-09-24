---
title: "PHP User Management System"
layout: single-project
excerpt: "A project to write a user management system in PHP using best practices"
collection: project
---

## Aims and Motivation

The aim is to create a user management system implementing registration, authentication, permissions and more in a secure way in PHP, without using frameworks.

The motivation for this is that PHP as a language has changed a lot over the last few years, yet the internet is littered with "tutorials" that teach new or inexperienced PHP programmers how to create user management systems that are largely insecure and should never be used by anyone. 
In working on the project, I intend to extensively address the issues identified by [OWASP](https://www.owasp.org) and follow the recommendations provided to ensure a secure system. 

My general musings and thoughts about related things will be posted in the blog but I will try to keep a note of my progress here too.

## Current Progress

- Database class has been completed and uses PDO parameterised queries
- Session Handler has been written to implement storing sessions in the database rather than the file system. 
- In addition a session manager has been implemented to get and set values to the current session. 
- Further work has been done to ensure that the security of sessions as outlined in OWASP's guidance has been followed.