---
layout: page
title: Home
nav_order: -10
---

🌐 **Frontend Development**
- Basic - [HTML](html), [CSS](css), [Javascript](js), [SASS](sass)
- CSS Frameworks - [Bootstrap](bootstrap)
- Frameworks - [Vue.js](vue), [Angular](angular)
- Testing - [Jest](jest)
- libraries - webpack, node.js

📙 **Backend Development (Java Ecosystem)**

- ☕ [Java](java/)
- ☘️[Spring](spring/)
- Hibernate
- Testing - JUnit, Mockito, Cucumber
- Libraries - Object Mapper, JSON/XML, Lombok, Logger (SLF4J), Feign
- API Docs - Swagger

🔁 **APIs & Microservices**
- [Http](http)
- [WebServices](webservices)
- [CORS](cors)
- REST
- Microservices
- API Docs - Swagger / OpenAPI
- Messaging - Apache Kafka, RabbitMQ, SQS
- Security - [OWASP](owasp)

🛠️  **DevOps & CI/CD Tools**

- [Git](git) - version control system
- Build Tool - Gradle, Maven
- Automation - Jenkins, Ansible, Checf
- Containerization - Docker
- Puppet
- Nginx
- Container Orchestration - Kubernetes, Openshift (RedHat), Hasicorp Nomad, Docker Swarm, etc…
- [16 Best Container Orchestration Tools and Services](https://devopscube.com/docker-container-clustering-tools/){:target=""_blank}

☁️ **Cloud and Platforms**
- Cloud Fundamentals
- AWS
- Authentication - Auth0

📊 **Monitoring & Observability**
- ELK
- Grafana
- Metrics
- Monitoring
- Alerts
- Logs

📚 **Software Engineering Concepts**
- Design Patterns
- Software Architecture
- Testing Strategies
- Object-Oriented Principles
- Security Principles
- Cloud Design Patterns

📕 **Best Practices**

- [Clean Code](clean-code)
- [Design Patterns](design-patterns)

🧠 **Computer Science Core**
- [Data Structures](ds)
- [Algorithms](algo)
- [Operating Systems (OS)](os)
- [DBMS](dbms) and [SQL](sql)
- [Computer Networks](networks)
- Programming Basics : [Programming](programming-basics), [Cheat Sheet](cheatsheet), [Puzzles](puzzles)

> Cross-linking posts via tags like `#spring`, `#auth`, `#monitoring`.


💁 **Contributors**

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>
