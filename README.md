<!-- [![CI](https://github.com/nogibjj/aws-template/actions/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/nogibjj/aws-template/actions/workflows/cicd.yml)
[![Codespaces Prebuilds](https://github.com/nogibjj/aws-template/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg?branch=main)](https://github.com/nogibjj/aws-template/actions/workflows/codespaces/create_codespaces_prebuilds) -->



[![Python application test with GitHub Actions](https://github.com/nogibjj/project-1-sunset/actions/workflows/main.yml/badge.svg)](https://github.com/nogibjj/project-1-sunset/actions/workflows/main.yml)
## IDS 721 Project 1: Cloud Continuous Delivery of Microservice - Sunrise/Sunset Info

### Intro 

the project will construct a microservice that provides users with information of sunrise, and sunset time/positions. Moreover, I hope I can combine with local weather information to suggest whether it is a good day to observe suggest sunrise and sunset. 
<!-- With extra time, probably I can recommand good locations to observe sunrise/sunset based on users' location. -->

### Usage
* First, it will require the users' geographic location (long, lat) info by user's IP.
* Second, the server will use user's location info to get the local sunrise/sunset info via APIs.
* Third, it get local weather info via APIs and build a simple algorithm to show whether it is a good day to observe suggest sunrise and sunset. (e.g., Rainy day, no sunrise/sunset; the day before an hurricane, spectacular sunset I promised)
* Finally, it will allow users to customize the timestamp (past or future).

### Project Tasks

* Create a Microservice in Flask or Fast API
* Push source code to Github
* Configure Build System to Deploy changes
* Use IaC (Infrastructure as Code) to deploy code
* Use either AWS, Azure, GCP (recommended services include Google App Engine, AWS App Runner or Azure App Services)
* Containerization is optional, but recommended

### Current Plan
* Week 4 (of Spring 23): 
  * set up GitHub Actions and AWS.
  * write up the server FlaskAPI
  
* Week 5 (of Spring 23): 
  * Modify UI design
  * Testing


### Reference Video(s):

* Data Engineering with Python and AWS Lambda: https://learning.oreilly.com/videos/data-engineering-with/9780135964330
* Building AI & ML Applications on Google Cloud Platform: https://learning.oreilly.com/videos/building-ai-applications/9780135973462
* Reference Source Code: https://github.com/noahgift/gcp-hello-ml

### Template for AWS Projects

1. First thing to do on launch is to open a new shell and verify virtualenv is sourced.

Things included are:

* `Makefile`

* `Pytest`

* `pandas`

* `Pylint`

* `Dockerfile`

* `GitHub copilot`

* `jupyter` and `ipython` 

* Most common Python libraries for ML/DL and Hugging Face

* `githubactions` 

### Used in Following Projects

* [coursera-mlops-aws-c3-step-functions](https://github.com/nogibjj/coursera-mlops-aws-c3-step-functions)
* [coursera-mlops-aws-c3-eda](https://github.com/nogibjj/coursera-mlops-aws-c3-eda)
* [coursera-mlops-aws-c3-linear-regression](https://github.com/nogibjj/coursera-mlops-aws-c3-linear-regression)
* [coursera-mlops-aws-c30fine-tune-sagemaker-studio-lab](https://github.com/nogibjj/coursera-mlops-aws-c30fine-tune-sagemaker-studio-lab)

### References

* [Watch GitHub Universe Talk:  Teaching MLOps at scale with Github](https://watch.githubuniverse.com/on-demand/ec17cbb3-0a89-4764-90a5-9debb58515f8)
* [Building Cloud Computing Solutions at Scale Specialization](https://www.coursera.org/specializations/building-cloud-computing-solutions-at-scale)
* [Python, Bash and SQL Essentials for Data Engineering Specialization](https://www.coursera.org/learn/web-app-command-line-tools-for-data-engineering-duke)
* [Implementing MLOps in the Enterprise](https://learning.oreilly.com/library/view/implementing-mlops-in/9781098136574/)
* [Practical MLOps: Operationalizing Machine Learning Models](https://www.amazon.com/Practical-MLOps-Operationalizing-Machine-Learning/dp/1098103017)
* [Coursera-Dockerfile](https://gist.github.com/noahgift/82a34d56f0a8f347865baaa685d5e98d)
