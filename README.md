# Red Hat OpenShift Advanced Application Deployment homework
This project is an example of a Jenkins pipeline which builds a Java app in a container, deploys and tests it in a development namespace, deploys a new version to the production namespace, tests it and switches the ingress to the new version.

The project provides shell scripts helping to setup the project, Jenkins instance and stages namespaces. The project assumes that external resources like Nexus and SonarQube are available and accessible.
