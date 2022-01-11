# gitlab
Gitlab &amp; CI/C


Tackle stage 1 first and the last stage last, but the others can be completed in
any order you prefer.

## Stage 0: Create and commit to the module

1. [x] Make sure that the issue title follows the `GitLab CI - [your name]` format.
1. [x] Assign the issue to yourself if it isn't already.
1. [x] Ping your manager to let them know you've started.
1. [x] Join the [`#gitlab` channel on Slack](https://slack.com/archives/TESTOU). This is a helpful Slack channel for all your Git and GitLab questions.
1. [x] Optional: Set a due date to help motivate yourself!

## Stage 1: Become familiar with what GitLab CI is

- [ ] **Done with Stage 1**

1. [ ] GitLab University
   1. [x] [Getting started with GitLab and GitLab CI](https://docs.gitlab.com/ee/ci/README.html#introduction-to-gitlab-cicd). Read the articles from Introduction to GitLab CI/CD section.
   1. [x] [The Basics of GitLab CI](https://about.gitlab.com/blog/2020/12/10/basics-of-gitlab-ci-updated/)
   1. [ ] [Continuous Integration, Delivery, and Deployment with GitLab](https://about.gitlab.com/blog/2016/08/05/continuous-integration-delivery-and-deployment-with-gitlab/)
   1. [ ] [Get more efficient with GitLab CI/CD](https://www.youtube.com/watch?v=id9klDUrGN8)

## Stage 2: Basic CI

- [ ] **Done with Stage 2**

1. [ ] Read the Table Of Contents for the [.gitlab-ci.yml docs](https://docs.gitlab.com/ee/ci/yaml/README.html)
   and make sure you know the meaning of every heading.
1. [ ] Set up a repository on GitLab.com and create a .gitlab-ci.yml file to
   get a pipeline running using the free shared runners on GitLab.com (this can
   be a basic toy project).
1. [ ] Note that your builds may show as **Pending** until a shared runner becomes
   available (the next step will solve this).
1. [ ] Install your own Runner (locally or hosted somewhere) following the [Setup Instructions](https://docs.gitlab.com/runner/install/)
1. [ ] Read about the different [Executors](https://docs.gitlab.com/runner/executors/)
1. [ ] Register your runner as a [Specific Runner](https://docs.gitlab.com/ee/ci/runners/README.html#registering-a-specific-runner)
   on your project, and test that it now runs the builds for your project.
1. [ ] Create an example project on your own GitLab instance.
1. [ ] Register a shared runner on your GitLab instance and make sure it can
   successfully run the build for your project.

## Stage 3: Intermediate CI

- [ ] **Done with Stage 3**

1. [ ] Read about [Pipelines and Jobs](https://docs.gitlab.com/ee/ci/pipelines.html).
1. [ ] Check how to [see the status of Pipeline and Jobs](https://docs.gitlab.com/ee/ci/quick_start/README.html#seeing-the-status-of-your-pipeline-and-jobs).
1. [ ] Read about using [Docker Images](https://docs.gitlab.com/ee/ci/docker/using_docker_images.html) with GitLab CI.
1. [ ] [Register a Docker Runner](https://docs.gitlab.com/ee/ci/docker/using_docker_images.html#register-docker-runner)
   and change your `.gitlab-ci.yml` to use a Docker image for your language of
   choice.
1. [ ] Read about [Artifacts](https://docs.gitlab.com/ee/user/project/pipelines/job_artifacts.html).
1. [ ] Change `.gitlab-ci.yml` to [create artifacts](https://docs.gitlab.com/ee/user/project/pipelines/job_artifacts.html#defining-artifacts-in-gitlab-ci-yml).
1. [ ] Set the Maximum Artifacts size in Admin and create artifacts above the limit, then check the build log for errors.
1. [ ] Read about [Multi-project pipelines](https://about.gitlab.com/2018/10/31/use-multiproject-pipelines-with-gitlab-cicd/).
1. [ ] Change your `.gitlab-ci.yml` to trigger a pipeline in another project.
1. [ ] Review the Runner [Troubleshooting guide and try to reproduce issues where possible](https://docs.gitlab.com/runner/faq/).
1. [ ] Read the rest of the [GitLab CI Documentation](https://docs.gitlab.com/ee/ci/README.html).
1. [ ] Set up a project with a basic web application that has some tests. Your CI script should deploy it to Heroku automatically when all the tests pass.
1. [ ] Create a basic GitLab Pages project on GitLab.com and make sure the CI script builds it and that the website is visible afterwards.

## Stage 4: Advanced CI

Please ensure that you review with your trainer/manager if they would like you to do all the tasks in this stage.

- [ ] **Done with Stage 4**

1. [ ] Set up a [container registry](https://docs.gitlab.com/ee/user/project/container_registry.html) for your project.
1. [ ] [Build a Docker image and upload it](https://docs.gitlab.com/ee/user/project/container_registry.html#build-and-push-images) to the project registry as part of the CI pipeline.
1. [ ] [Add or integrate a Kubernetes cluster](https://docs.gitlab.com/ee/user/project/clusters/) to your project.
1. [ ] Deploy your [application to Kubernetes](https://medium.com/john-lewis-software-engineering/deploying-to-google-kubernetes-engine-from-gitlab-ci-feaf51dae0c1) via GitLab CI using the Docker container you built. One option is to [customize the Auto DevOps template](https://docs.gitlab.com/ee/topics/autodevops/#customizing).
1. [ ] Set up [Review Apps](https://docs.gitlab.com/ee/topics/autodevops/#customizing) to be deployed to Kubernetes.
1. [ ] Set up a [manual deploy step](https://docs.gitlab.com/ee/ci/yaml/#whenmanual), so that it does not deploy to production unless someone clicks the button to do so.
1. [ ] Speed up a pipeline using [caching](https://docs.gitlab.com/ee/ci/yaml/#cache).

## Final Stage: Review

Any updates or improvements needed? If there are any dead links, out of date or inaccurate content, missing content whether in this module or in other documentation, list it below as tasks for yourself!

- [ ] Update ...
