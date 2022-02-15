# Maintain your AWS CodeCommit Code Repository
In this project we will give a proper guideline about the maintaining your AWS CodeCommit repository

## Table of Content
  * [Demo](#demo)
  * [What is code repository?](#what-is-code-repository?)
  * [Benefits of having a code repository](#Benefits-of-having-a-code-repository)
  * [Why AWS CodeCommit?](#Why-AWS-CodeCommit?)
  * [Installation](#installation)
  * [Run](#run)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Contributing](#Contributing)
  * [License](#license)
  * [Credits](#credits)

## Demo

## What is code repository?
A code repository is a place to store codes,documents, notes,scripts and other items related to your project. In other word we can say code storage. Usually code repositories are handled by VCS (Version Control System) softwares such as git. If you need to success your software development project, you must maintain a good code repository.


## Benefits of having a code repository


* High security
Repositories facilitate a good security of our codes. If something happen to main version of the code, we can revert the changes or retrive older version of the code. And also some repository providers automattically encrypts our repo’s files and allow us tom cutomize user specific access to our repository. (ex: AWS Identity and Access Management (IAM))
* 	Always have a backup
Lets say you store your all the codes inside your local computer. Accidently your laptop has attacked by a malware and your files were removed by that virus. What happened your files are gone forever. But if you store your all the codes inside a code repository you always have a backup.
*	Collaboration
Code repositories help you to collaborate on code with numerous other developers or teammates on your company via commiting, pull requests, branching and merging. They can easily review your code and give feedbacks. And also they can easily control project remotely.
*	Version controlling
Easily maintain and keep track of the latest and different versions of the scripts. It also offers simplified debugging option using side-by-side comparison, which highlited the difference between two versions. 
*	Proper documentation
By using readme file of a any repository, you can easily orgnize your project properly. You can add table of contents, demos, screenshots, guidelines, etc.
*	Showcase your talent
Code repositories are great digital portfolios or resumes. Are you looking for a new job or do you need to show your work expereince? Code reporsitory is the best way to do that. You can build an attractive profile with include all the project you done have so far and include that repository link into your cv as well. 
*	Faster development lifecycle
You can push incremental changes instead of the entire project. This allows you to reduce the time and increase the speed and frequency of your software development lifecycle.

## Why AWS CodeCommit?

<p>There are a lot of code repository providers in the marketplace and among them Github, Gitlab, Bitbucket and AWS CodeCommit are the leading service providers in the industry. With the rapid development of the Cloud indsutry,they produce <b> code free and easy maintanable repositories(anyone can maintain their repositories without any git knowledge)</b>. As a result of that AWS produced CodeCommit and if you are using AWS services (Specially CodePipelines) easily clone this code repo to your service.</p>
<p>In this article we will talk about the breif introduction and the capabilities of AWS CodeCommit.</p>

## Installation
#### Requirements
Only thing you need to satisfy in this list is you must have an AWS account. If you don't have an account you can create it free, using below link:
https://aws.amazon.com/free/

## Run

## Directory Tree
```
├── inferencing 
│   ├── model
|       ├── nginx.conf
|       ├── predictor.py
|       ├── serve.py
|       └── wsgi.py
│   ├── Dockerfile
├── preprocessing
│   ├── Dockerfile
|   └── preprocessing.py
├── training
│   ├── model
|       └──train.py
|   ├── Dockerfile
├── build_docker.ipynb
├── sagemaker_pipeline.ipynb
├── aws_helper.py
├── CONTRIBUTING.md
├── LICENSE
├── setup.py
├── tox.ini
└──WA_Fn-UseC_-Telco-Customer-Churn.csv
```

## Bug / Feature Requests
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/Data-Fenix/maintain-aws-codecommit-repository/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/Data-Fenix/maintain-aws-codecommit-repository/issues/new). Please include sample queries and their corresponding results.

## Technologies Used
[<img target="_blank" src="https://www.vickalp.com/wp-content/uploads/2021/03/image-35-1024x275.png" width=200>](https://www.vickalp.com/wp-content/uploads/2021/03/image-35-1024x275.png) 
## Contributing

<p><b> ML Enginner </b> : Lahiru Dissanayake </p>
<p><b> Data Scientist </b>: Shashi Withanage </p>

## License
Copyright 2022 Lahiru Dissanayake and Shashi Withange

## Credits
https://docs.aws.amazon.com/codecommit/latest/userguide/getting-started-cc.html
