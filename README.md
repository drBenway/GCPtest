test repo for GCP deployment


npm tasks
 "test" will run mocha and trigger all tests in the test/unit folder 
 "lint" will run eslint on your code
 "lint:fix" will run eslint on your code and let it autofix when possible
 "dockerize" will create a docker image and tag it with the version in the package.json
 "build" will run lint:fix, lint, test and then dockerize
