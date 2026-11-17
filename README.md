# demo-repo

[root@ip-172-31-32-106 K8S-Project1]# tree
.
├── DEPLOYMENT.md
├── Docker-app
│   ├── Dockerfile
│   └── multistage
│       └── Dockerfile
├── Docker-db
│   ├── Dockerfile
│   └── db_backup.sql
├── Dockerfile
├── README.md
├── compose.yml
├── k8s
│   ├── 01-namespace.yaml
│   ├── 02-resourcequota.yaml
│   ├── 03-configmap.yaml
│   ├── 04-secret.yaml
│   ├── 05-storageclass.yaml
│   ├── 06-statefulset-db.yaml
│   ├── 07-service.yaml
│   ├── 08-deployment.yaml
│   ├── 09-hpa.yaml
│   ├── 10-pdb.yaml
│   ├── 11-ingress.yaml
│   └── 12-networkpolicy.yaml
├── kops
│   └── create-cluster.sh
├── manifests
│   ├── app-deployment.yml
│   └── db-deployment.yml
├── pom.xml
└── src
    ├── main
    │   ├── java
    │   │   └── com
    │   │       └── visualpathit
    │   │           └── account
    │   │               ├── beans
    │   │               │   └── Components.java
    │   │               ├── controller
    │   │               │   ├── ElasticSearchController.java
    │   │               │   ├── FileUploadController.java
    │   │               │   ├── HealthController.java
    │   │               │   └── UserController.java
    │   │               ├── model
    │   │               │   ├── Role.java
    │   │               │   └── User.java
    │   │               ├── repository
    │   │               │   ├── RoleRepository.java
    │   │               │   └── UserRepository.java
    │   │               ├── service
    │   │               │   ├── ConsumerService.java
    │   │               │   ├── ConsumerServiceImpl.java
    │   │               │   ├── ProducerService.java
    │   │               │   ├── ProducerServiceImpl.java
    │   │               │   ├── SecurityService.java
    │   │               │   ├── SecurityServiceImpl.java
    │   │               │   ├── UserDetailsServiceImpl.java
    │   │               │   ├── UserService.java
    │   │               │   └── UserServiceImpl.java
    │   │               ├── utils
    │   │               │   ├── ElasticsearchUtil.java
    │   │               │   ├── MemcachedUtils.java
    │   │               │   └── RabbitMqUtil.java
    │   │               └── validator
    │   │                   └── UserValidator.java
    │   ├── resources
    │   │   ├── application.properties
    │   │   ├── db_backup.sql
    │   │   ├── logback.xml
    │   │   └── validation.properties
    │   └── webapp
    │       ├── WEB-INF
    │       │   ├── appconfig-data.xml
    │       │   ├── appconfig-mvc.xml
    │       │   ├── appconfig-rabbitmq.xml
    │       │   ├── appconfig-root.xml
    │       │   ├── appconfig-security.xml
    │       │   ├── views
    │       │   │   ├── elasticeSearchRes.jsp
    │       │   │   ├── error.jsp
    │       │   │   ├── includes
    │       │   │   │   ├── footer.jspf
    │       │   │   │   ├── head.jspf
    │       │   │   │   └── nav.jspf
    │       │   │   ├── index_home.jsp
    │       │   │   ├── login.jsp
    │       │   │   ├── rabbitmq.jsp
    │       │   │   ├── registration.jsp
    │       │   │   ├── upload.jsp
    │       │   │   ├── user.jsp
    │       │   │   ├── userList.jsp
    │       │   │   ├── userUpdate.jsp
    │       │   │   └── welcome.jsp
    │       │   └── web.xml
    │       └── resources
    │           ├── Images
    │           │   ├── background.png
    │           │   ├── devopslogo3.png
    │           │   ├── header.jpg
    │           │   ├── mustafalogo2.png
    │           │   ├── mustafalogo3.png
    │           │   ├── technologies
    │           │   │   ├── Ansible_logo.png
    │           │   │   ├── Vagrant.png
    │           │   │   ├── aws.png
    │           │   │   ├── docker.png
    │           │   │   ├── git.jpg
    │           │   │   ├── jenkins.png
    │           │   │   ├── puppet.jpg
    │           │   │   └── python-logo.png
    │           │   └── user
    │           │       ├── giphy.gif
    │           │       ├── logo.png
    │           │       ├── user.png
    │           │       ├── user2.png
    │           │       └── user3.png
    │           ├── css
    │           │   └── app.css
    │           └── img
    │               ├── favicon.svg
    │               └── icons.svg
    └── test
        └── java
            └── com
                └── visualpathit
                    └── account
                        ├── controllerTest
                        │   ├── SampleTest.java
                        │   └── UserControllerTest.java
                        ├── modelTest
                        │   ├── RoleTest.java
                        │   └── UserTest.java
                        └── setup
                            └── StandaloneMvcTestViewResolver.java

38 directories, 96 files
