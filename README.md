# docker-containers

Exercises and notes for the [docker-containers](https://elifesciences.udemy.com/course/docker-containers) course on [udemy](https://elifesciences.udemy.com)

# Refelection

Overall the course was OK, too basic for me but the other team members I feel would benefit from it. There were some issues with some of the course content, notably...

## Chapter 3 Section 15

The default `Dockerfile` has an error and will fail to work due to a node/npm path issue. You can resolve it by using a tagged release instead, e.g.1

```Dockerfile
FROM node:lts
```