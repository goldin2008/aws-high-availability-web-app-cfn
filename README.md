# Udacity Cloud DevOps Engineer Nanodegree Program - Project 2: Deploy a high-availability web app using CloudFormation

## Solution

### Create the stacks

To create the stacks, run the following commands:

```
./create-stack.sh <stack-name-network> network.yml network-parameters.json
./create-stack.sh <stack-name-server> server.yml server-parameters.json
```

### Update the stacks

To update the stacks, run the following commands:

```
./update-stack.sh <stack-name-network> network.yml network-parameters.json
./update-stack.sh <stack-name-server> server.yml server-parameters.json
```

## Requirements

Graded according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2556/view).

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © [Thomas Weibel](https://github.com/thom).
