---
title: Ante Mihalj
date: 2017-10-11T14:27:44+02:00
draft: false
layout: wba-cv
meta:
  title: Ante Mihalj - curriculum vitae
  keywords: senior developer, software architect, team lead, freelancer
  description: Ante Mihalj is the most experienced team member of WeBringApps team. With more than 15 year experience he covered a large field in technologies and development
h1: Ante Mihalj - CV
subtitle: software engineer, consultant, software architect
tags: blank
social:
  twitter: https://twitter.com/ante_mihalj
  facebook: https://www.facebook.com/ante.mihalj.94
  linkedin: https://www.linkedin.com/in/ante-mihalj-a3558050/
  github: https://github.com/amihalj

headings:
  personal: Personal information
  education: Education
  hobbies: Hobbies

personal: 
  name: Ante Mihalj
  title: M.Sc. Engineer of telecommunications and electronics
  dob: Feb 18th 1981
  responsive_image:
    alt: Ante Mihalj
    image_xs: /img/ante-s.png
    image_l: /img/ante-m.png
    class: no_shift
  intro: >-
    My name is Ante, I am a software engineer with 20+Y working experience in software development. 


    
    During that time I have worked through different roles and technologies during which time I have acquired knowledge and skills to successfully deliver them into practice. My experience includes software development with an understanding of complex business domains, team leadership, team education and technology consultancy. I am not afraid to take on new challenges and adapt to situations.



    I value hard work, team spirit and constant search for knowledge.



    If you want to know a bit more please feel free to go to my [personal site](/) 
    
work_experience:
- employer: We Bring Apps
  link: http://www.webringapps.com
  period: Jan 2018 - present
  occupation: Founder, Technical consultant, Software architect
  responsibilities:  Enforcing best practices in software development, team leader, technical consultant, senior developer, freelancer
  projects:
  - name: Stockex
    anchor: stockex
  - name: IBM cloud
    anchor: ibm
  - name: EDHP
    anchor: edhp
  - name: Betting platform
    anchor: betting
- employer: Zeraxo
  link: http://www.zeraxo.com
  period: Jan 2016 - Jan 2018
  occupation: Principal technical consultant
  responsibilities:  Enforcing best practices in software development. Product development advisement
  projects:
  - name: Winq
    anchor: winq
  - name: Budgeteer
    anchor: budgeteer
- employer: Cloudsense
  link: http://www.cloudsense.com
  period: Jan 2015 - Jan 2017
  occupation: Principal consultant, senior developer
  responsibilities:  Salesforce product and technology consultancy, Heroku cloud computing and development, product development. Lead developer on cloud computing service that integrates Salesforce (as a CRM andService cloud) and CMS (as a web shop and B2C channel)
  projects:
  - name: Basket as a Service
    anchor: elastic-api
- employer: Amphinicy Technologies
  link: http://www.amphinicy.com
  period: Nov 2013 - Jan 2015
  occupation: Senior software engineer, UX expert
  responsibilities:  Front end development, visual web design, UX (user) interaction design
  projects:
  - name: Monica
    anchor: monica
  - name: EDRS
    anchor: edrs
- employer: Repsly.com
  link: https://www.repsly.com
  period: June 2010 - Nov 2013
  occupation: Software engineer, Web lead manager
  responsibilities: Saas product development, front-enc & backend, integrations and 
  projects:
  - name: Repsly
    anchor: repsly
  - name: VIP “Sales surveillance“
  - name: VIP “Working time surveillance”
- employer: Raiffeisenbank Austria 
  link: https://www.rba.hr/
  period: June 2006 - June 2010
  occupation: Senior software developer
  responsibilities: Bank core system development, integrations with bank sub-systems and modules, use case analysis, communication protocol design and implementation, scheduled calculations and system optimization
  projects:
  - name: Sirius RBA
    anchor: sirius
  - name: MQ router
- employer: Freelancer
  period: June 2005 - June 2006
  occupation: Freelancer
  responsibilities:  Web and desktop development
- employer: Combis
  link: http://www.combis.hr
  period: Oct 2004 - June 2005
  occupation: Junior software engineer
  responsibilities: IT internship
  projects:
  - name: NPC Collections

projects:
- name: Stockex
  year: "> 2023"
  anchor: stockex
  desc: Stockex is a software service to support company auction/bidding system. This is a microservice architecture system with external integrations, runs in containers and is monitored through prometheus metrics and grafana dashboards.
  role: Lead developer, freelancer
  tags:
  - Rust Actix
  - Postgres
  - OAuth
  - JWT
  - Docker
  - push notifications
  - github workflows
  - Svelte
  - Prometheus
  - Grafana
  - Alert manager

- name: IBM Cloud storage systems
  year: 2021 - 2022
  anchor: ibm
  desc: Microservice oriented API to support cluster storage. 
  role: Senior developer, freelancer
  tags:
  - Kubernetes
  - etch
  - Go-lang
  - k3d
  - NodeJS
  - bash
  - Docker
  - IBM cloud
  - encryption at transit
  - encryption at rest


- name: EDHP
  year: 2017 - 2023
  anchor: edhp
  desc: EDHP is AWS serverless lambda based integration API build on Amazon services and integrated with Azure. It is an integration API because it handles several systems and allows interaction and data sharing between them
  role: Lead developer, freelancer
  tags:
  - Amazon web services
  - AWS Cloud Formation
  - AWS lambda function
  - AWS EC2
  - AWS API Gateway
  - AWS Cognito
  - Azure
  - NodeJS
  - Postgres
  - Mocha
  - OAuth
  - JWT
  - Docker
  - crypto
  - React

- name: Betting platform
  year: 2019 - 2021
  anchor: betting
  desc: This betting platform is a micro-service eco system, built (mostly) in Golang , communicating asynchronously through Kafka and gRPC, caching with Redis and Mongo. Since it's micro-service architecture it is highly available and scalable
  role: Senior developer, freelancer
  tags:
  - Kubernetes cluster
  - Helm
  - Go-lang
  - NodeJS
  - Mongo
  - Kafka
  - OAuth
  - JWT
  - Docker
  - github workflows

- name: Basket as a Service
  anchor: elastic-api
  year: 2015 - 2016
  desc: BaaS (Basket as a Service) is cloud based e-commerce system designed as a highly-available micro-service that integrates CMS webshop and Salesforce CRM. Project includes Salesforce component development, Heroku cloud development(NodeJS) and CMS (Drupal) integration
  role: Web lead manager, senior developer (both back and frontend)
  tags:
  - Salesforce.com
  - Salesforce Apex
  - NodeJS
  - Heroku
  - Postgres
  - Mongo
  - Gulp
  - Grunt
  - Mocha
  - OAuth
  - JWT
  - Docker
  - crypto

- name: Repsly
  anchor: repsly
  year: 2010 - 2013
  desc: Repsly is a service for surveillance and coordination of mobile teams, merchandisers and field workers that spend their work hours outside office. System is made of core system, web application for back office users, mobile applications for field workers, API and integration modules for 3rd party ERP systems and billing system.
  role: Web lead manager, senior developer (both back and frontend)
  tags:
  - ASP.NET
  - C#
  - Java
  - MSSQLServer
  - jQuery
  - HTML5
  - CSS3
  - Javascript
  

- name: VIP Sales surveillance
  year: 2010 - 2011
  desc: Lightweight Repsly version as stand-alone cloud application integrated with VIP telecom cloud services.
  role: Web lead manager, senior developer (both back and frontend)
  tags:
  - ASP.NET
  - C#
  - Java
  - MSSQLServer
  - jQuery
  - HTML5
  - CSS3
  - Javascript

- name: VIP Working time surveillancesly
  year: 2010 - 2011
  desc: Service for working time surveillance according to laws of Republic of Croatia.
  role: Web lead manager, senior developer (both back and frontend)
  tags:
  - ASP.NET
  - C#
  - Java
  - MSSQLServer
  - jQuery
  - HTML5
  - CSS3
  - Javascript

- name: Monica
  year: 2013 - 2014
  anchor: monica
  desc: Web based monitoring and controlling app for satellite ground stations. System contains several modules that are interconnected and presented through one UI concepted as a dashboard, action center. My main focus was UI development (SPA) and UX guidelines
  role: Web lead developer, UX expert
  tags:
  - Angular
  - D3
  - jQuery
  - SVG
  - HTML5
  - CSS
  - NodeJS
  - Gulp
  - Grunt
  - Mocha

- name: Sirius RBA
  year: 2006 - 2010
  anchor: sirius
  desc: RBA core banking system and integration with external and secondary modules through MQ Websphere Messaging
  role: Senior developer
  tags:
  - Java
  - DB2
  - JMS
  - WebSphere
  - MQ
  - SOAP
  - XML

education:
- title: Software engineer
  organization: University of Zagreb, Faculty of Electrical Engineering and Computing, Department of Telecommunication (Croatia)
  years: 1999- 2004
  degree: Engineer of telecommunications and electronics
  level: M. Sc. in computer science

- title: High-school graduate
  organization: Mathematical gymnasium in Zagreb, Croatia (MIOC)
  years: 1995- 1999
  degree: High school


skills:
- title: Server side technologies
  points:
  - __Microsoft__ - Server, ASP.NET, Webforms, MVC, WebApi, ASP.NET Core
  - __Java__ - Java EE, Java Beans, Spring Framework, ...
  - __NodeJS__ - ExpressJS, Restify, AWS SDK, ...
  - __Linux__ - nginx, bash
  - __Other popular languages__ - Go, Rust, bash

- title: Cloud and related technologies
  points:
  - __AWS__ - S3, API Gateway, CloudFormation, Lambda functions, Cognito, CloudWatch, SNS, SQS ...
  - __Heroku__ - deployed several apps (personal and commercial) on that platform
  - __Containers__ - Docker, Dokku, Kubernetes, ...
  - __Cloud web services__ - Redis, Memcache, AQMP, ...


- title: Front end technologies
  points:
  - __General__ - HTML5, CSS3, SCSS, SASS
  - __Javascript__ - VanillaJS, jQuery, Angular, React
  - __Tools__ - grunt, gulp, webpack

- title: Databases
  points:
  - __Microsoft__
  - __IBM DB2__
  - __Amazon DynamoDB__
  - __Oracle__ 
  - __MySQL__
  - __PostgreSQL__
  - __MongoDB__

- title: Content managment systems
  points:
  - __Umbraco CMS__ - created a dozen of umbraco backed-up websites
  - __KeystoneJS__ - NodeJS based CMS
  - __Hugo__ - static website generator
  - __Netlify CMS__ - static website CMS and host

- title: CRM
  points:
  - __Salesforce.com__ - development, integration, testing
  - __ZohoCRM__ - personal use

- title: Other
  points:
  - __Design__ - UX, paper prototyping, AB testing
  - __Versioning systems__ - git, mercurial, svn
  - __Hosting__ - Heroku, AWS, Azure, .NET, Netlify 
---