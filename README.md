# ITAD2018_CodingTimeDocker
It is a repository with examples from presentation shown on IT Academic Days at Warsaw University of Technology. Title: "Docker - from zero to hero"

## How to build container
`cd docker-python`  
`docker build -t docker-python-example .`

## How to run container
`docker run -p 5000:5000 -v $PWD/src:/src docker-python-example`
