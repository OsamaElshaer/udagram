# Pipeline Process

pipeline is the full set of processes that run when you trigger work on your projects.

## Order of process

### GitHub
- commit and push code to the GitHub repository which is linked to the CircleCI.

### Circleci
- CircleCI trigger the new gethub repo and run jobs that preconfigurd of the config.yml file.


## diagram

![Pipeline Schema](./images/circleci_pipline.png)
