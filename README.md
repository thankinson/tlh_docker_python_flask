# Docker Python Flask

## What this dose
This will configure your docker container and install required flask componants

## to build

run this in the directory the Dockerfiel is located :
- docker build -t <username>/python:<yourtag> .
example
  
-- docker build -t someuser/python:tagexample .
  
to run:
- docker run -d -p 5000:5000 thankinson/python:test
