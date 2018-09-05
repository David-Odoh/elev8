# Continuous Integration with CircleCI [![Circle CI](https://circleci.com/gh/surge-sh/example-circleci.svg?style=svg)](https://circleci.com/gh/David-Odoh/elev8)

## Ready... Set... Code!!

Continuous Deployment services like [CircleCI](https://circleci.com) make it possible to run publish your project on Surge each time you push to a GitHub repository.

This mini project addresses the portion on the diagram enclosed in a square with brown borders. Subsequently, we will push our project to AWS.

![CI flow diagram](http://dynamicflakesltd.com/image_exports/circleci.jpg)

Ok, let's play around with it and build it further together. Here's how it should go:

# Step 1
So clone the project

```
$ git clone https://github.com/David-Odoh/elev8.git
```
# Step 2
Run

```
$ npm install
```

# Step 3
Improve or propose new features and tests. Push to the branch 'aside', as the master is protected and I will merge the changes.

```
$ git push origin master:aside
```
