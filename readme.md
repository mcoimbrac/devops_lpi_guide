## LPI OT - DevOps

---

### Topic 701: Software Engineering

#### 701.1 Modern Software Development (weight: 6)

##### Description:

Candidates should be able to design software solutions suitable for modern runtime environments. Candidates should understand how services handle data persistence, sessions, status information, transactions, concurrency, security, performance, availability, scaling, load balancing, messaging, monitoring and APIs. Furthermore, candidates should understand the implications of agile and DevOps on software development.

##### Key Knowledge Areas:

* Understand and design service based applications
* Understand common API concepts and standards
* Understand aspects of data storage, service status and session handling
* Design software to be run in containers
* Design software to be deployed to cloud services
* Awareness of risks in the migration and integration of monolithic legacy software
* Understand common application security risks and ways to mitigate them
* Understand the concept of agile software development
* Understand the concept of DevOps and its implications to software developers and operators

##### Files, Terms and Utilities (partial list):

* REST, JSON
    * [wikipedia/REST](https://en.wikipedia.org/wiki/Representational_state_transfer)
    * [wikipedia/JSON](https://en.wikipedia.org/wiki/JSON)
* Service Orientated Architectures (SOA)
    * [wikipedia/SOA](https://en.wikipedia.org/wiki/Service-oriented_architecture)
* Microservices
    * [wikipedia/Microservices](https://en.wikipedia.org/wiki/Microservices)
* Immutable servers
    * [What are immutable servers? - StackExchange/Devops](https://devops.stackexchange.com/questions/412/what-are-immutable-servers)
    * [What Is Immutable Infrastructure?](https://www.digitalocean.com/community/tutorials/what-is-immutable-infrastructure)
* Loose coupling
    * [wikipedia/Loose coupling](https://en.wikipedia.org/wiki/Loose_coupling)
    * [What is the difference between loose coupling and tight coupling in the object oriented paradigm?
](https://stackoverflow.com/questions/2832017/what-is-the-difference-between-loose-coupling-and-tight-coupling-in-the-object-o)
* Cross site scripting, SQL injections, verbose error reports, API authentication, consistent enforcement of transport encryption
    * [wikipedia/Cross site scripting](https://en.wikipedia.org/wiki/Cross-site_scripting)
    * [wikipedia/SQL injection](https://en.wikipedia.org/wiki/SQL_injection)
    * [Error Handling, Auditing and Logging](https://www.owasp.org/index.php/Error_Handling,_Auditing_and_Logging)
    * [REST API Authentication](https://stackoverflow.com/questions/7999295/rest-api-authentication)
    * [Basic auth for REST APIs](https://developer.atlassian.com/cloud/jira/platform/jira-rest-api-basic-authentication/)
    * [3 Common Methods of API Authentication Explained](https://nordicapis.com/3-common-methods-api-authentication-explained/)
    * [RESTful API Authentication Basics](https://blog.restcase.com/restful-api-authentication-basics/)
    * [What is SSL, TLS and HTTPS?](https://www.websecurity.symantec.com/security-topics/what-is-ssl-tls-https)
    * [wikipedia/Transport Layer Security](https://en.wikipedia.org/wiki/Transport_Layer_Security)
    * [O que é SSL / TLS? E por que é hora de atualizar para TLS 1.3](https://cryptoid.com.br/banco-de-noticias/o-que-e-ssl-tls-e-por-que-e-hora-de-atualizar-para-tls-1-3/)
* CORS headers and CSRF tokens
    * [Mozilla/Cross-Origin Resource Sharing (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
    * [Wikipedia/Cross-origin resource sharing](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)
    * [Wikipedia/Cross-site request forgery](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
    * [Owasp/Cross-Site Request Forgery (CSRF) Prevention Cheat Sheet](https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet)
* ACID properties and CAP theorem
    * [Wikipedia/ACID](https://en.wikipedia.org/wiki/ACID)
    * [Wikipedia/CAP theorem](https://en.wikipedia.org/wiki/CAP_theorem)
    * [Dzone/Understanding the CAP Theorem](https://dzone.com/articles/understanding-the-cap-theorem)


---

#### 701.2 Standard Components and Platforms for Software (weight: 2)

##### Description:

Candidates should understand services offered by common cloud platforms. They should be able to include these services in their application architectures and deployment toolchains and understand the required service configurations. OpenStack service components are used as a reference implementation.

##### Key Knowledge Areas:

* Features and concepts of object storage
* Features and concepts of relational and NoSQL databases
* Features and concepts of message brokers and message queues
* Features and concepts of big data services
* Features and concepts of application runtimes / PaaS
* Features and concepts of content delivery networks

##### Files, terms and utilities (partial list):

* OpenStack Swift
    * [openstack.org/Wiki](https://wiki.openstack.org/wiki/Swift)
    * [openstack.org/Docs](https://docs.openstack.org/swift/latest/)
* OpenStack Trove
    * [openstack.org/Wiki](https://wiki.openstack.org/wiki/Trove)
    * [openstack.org/Docs](https://docs.openstack.org/trove/latest/)
* OpenStack Zaqar
    * [openstack.org/Wiki](https://wiki.openstack.org/wiki/Zaqar)
    * [openstack.org/Docs](https://docs.openstack.org/zaqar/latest/)
* CloudFoundry
    * [wikipedia/Cloud Foundry](https://en.wikipedia.org/wiki/Cloud_Foundry)
    * [cloudfoundry.org/Cloud Foundry: Your Cloud-Native Toolbox](https://www.cloudfoundry.org/why-cloud-foundry/)
* OpenShift
    * [wikipedia/OpenShift](https://en.wikipedia.org/wiki/OpenShift)
    * [openshift.com/Introduction to OpenShift](https://www.openshift.com/about/index.html)


---

#### 701.3 Source Code Management (weight: 5)

##### Description: 

Candidates should be able to use Git to manage and share source code. This includes creating and contributing to a repository as well as the usage of tags, branches and remote repositories. Furthermore, the candidate should be able to merge files and resolve merging conflicts.

##### Key Knowledge Areas:

* Understand Git concepts and repository structure
* Manage files within a Git repository
* Manage branches and tags
* Work with remote repositories and branches as well as submodules
* Merge files and branches
* Awareness of SVN and CVS, including concepts of centralized and distributed SCM solutions

##### Files, terms and utilities:

* git
    * [git/About](https://git-scm.com/about)
    * [wikipedia/Git](https://en.wikipedia.org/wiki/Git)
    * [wikipedia/Distributed version control](https://en.wikipedia.org/wiki/Distributed_version_control)
* .gitignore
    * [git reference/gitignore](https://git-scm.com/docs/gitignore)


---

#### 701.4 Continuous Integration and Continuous Delivery (weight: 5)

##### Description: 

Candidates should understand the principles and components of a continuous integration and continuous delivery pipeline. Candidates should be able to implement a CI/CD pipeline using Jenkins, including triggering the CI/CD pipeline, running unit, integration and acceptance tests, packaging software and handling the deployment of tested software artifacts. This objective covers the feature set of Jenkins version 2.0 or later.

##### Key Knowledge Areas:

* Understand the concepts of Continuous Integration and Continuous Delivery
* Understand the components of a CI/CD pipeline, including builds, unit, integration and acceptance tests, artifact management, delivery and deployment
* Understand deployment best practices
* Understand the architecture and features of Jenkins, including Jenkins Plugins, Jenkins API, notifications and distributed builds
* Define and run jobs in Jenkins, including parameter handling
* Fingerprinting, artifacts and artifact repositories
* Understand how Jenkins models continuous delivery pipelines and implement a declarative continuous delivery pipeline in Jenkins
* Awareness of possible authentication and authorization models
* Understanding of the Pipeline Plugin
* Understand the features of important Jenkins modules such as Copy Artifact Plugin, Fingerprint Plugin, Docker Pipeline, Docker Build and Publish plugin, Git Plugin, Credentials Plugin
Awareness of Artifactory and Nexus

##### Files, terms and utilities:

* Step, Node, Stage
    * [jenkins.io/Pipeline Concepts](https://jenkins.io/doc/book/pipeline/#pipeline-concepts)
* Jenkins SDL *(???)*
    * [jenkins.io/Job DSL Plugin](https://wiki.jenkins.io/display/JENKINS/Job+DSL+Plugin)
* Jenkinsfile
    * [jenkins.io/Using a Jenkinsfile](https://jenkins.io/doc/book/pipeline/jenkinsfile/)
* Declarative Pipeline
    * [jenkins.io/Declarative Pipeline](https://jenkins.io/doc/book/pipeline/syntax/#declarative-pipeline)
    * [jenkins.io/Declarative Pipeline Syntax 1.0 is now available](https://jenkins.io/blog/2017/02/03/declarative-pipeline-ga/)
    * [jenkins.io/Parallel stages with Declarative Pipeline 1.2](https://jenkins.io/blog/2017/09/25/declarative-1/)
* Blue-green and canary deployment
    * [opensource.com/Colorful deployments: An introduction to blue-green, canary, and rolling deployments](https://opensource.com/article/17/5/colorful-deployments)
    * [stackoverflow/Canary release strategy vs. Blue/Green](https://stackoverflow.com/questions/23746038/canary-release-strategy-vs-blue-green)
    * [article/Blue-green Deployments, A/B Testing, and Canary Releases](http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/)

---

#### Other useful resources:

* [StackExchange Devops](https://devops.stackexchange.com/)