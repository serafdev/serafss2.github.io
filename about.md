---
layout: page
title: About
permalink: /about/
tags: about
---

### Summary

Passionate Developer offering experience in Back-End Development to deliver highly scalable products. Highly organized and have a good sense of architectural planning. Extensive experience in the full cycle of the software design process including requirements definition, prototyping, proof of concept, design, interface implementation, testing, deployment, maintenance and all the blablabla that you end up googling anyway.

----------------------------

### Technical tools

Python, Scala, Docker, Kubernetes, Cloud environment, Linux, etc

---------------------------


###  Professional experience 
#### Bell (Nov 2019 - Present)

#### Desjardins (Jan 2019 - Nov 2019)
Software Consultant (Network Automation)

###### Infrastructure
Put in place our application's network infrastructure (Gunicorn/Nginx + Nginx/Vue.js static files) and contributed in the deployment automation using the ansible-cli.

Contributed in the Continuous Testing using Jenkins.
###### F5 BigIP Automation (LTM)
Creation of Virtual Servers and sub-tree, aka pools, pool-members, ssl certificate objects, etc. Worked mostly on the backend side using Python.

Created validations for our end-user's form with real-time queries to the BigIPs on the clusters. Helped design the network configuration file injected by ansible to create the LTM objects on the BigIP.

###### OpenTrust SSL Certificates Enrollment Automation (IDnomic)
Automated the SSL Certificates enrollment using the OpenTrustRA (Registration Authority) SOAP api. Created an app that uses the RA SOAP api. Designed the buffer database to keep security logs and rollbacks easily queried (revokes, renewals, etc).

The automation took care of creating the private key on the server and generating the public SSL Certificate on the machine. In the case of the BigIP the application would go and create an SSL Certificate on the BigIP and enrolled a signed public certificate using the OpenTrust APIs.

#### Faimdata (Dec 2016 - Dec 2018)
Software Engineer (Back-end, DevOps / Scala, Python, BigQuery, Postgresql, Docker, Kubernetes)
 
Worked as a Backend developer using Scala, Python and BigQuery to build a highly scalable CI tool in a data environment. Moved the legacy network architecture from manual deployments to Nginx, Docker and Kubernetes with continuous integration and delivery with Jenkins, saved the developers a * ton of time. Built a Micro-Queries library that took care of reccurent logic in our Data Scientist's Queries, it helped the performance of APIs from >1min to <10 seconds, also added a Memcached server to our APIs which enhanced most requests to <.2second, pretty satisfying if you ask me.

---------------------------

### Education
#### Université de Montréal
Computer Science Major

A lot of algorithmics, data structures, software engineering, mathematics, statistics, etc. Same as everyone else
