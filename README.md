# CI/CD pipeline training

Should be a presentation that is limited to **40 minutes**. This can also be
converted into a workshop that should not take longer than **60 minutes**.

## Docker
- Docker overview and its importance from the overall pipeline view.
  * Talk about containerisation and why we use it.

## Jenkins
- Using only Docker containers for Jenkins builds.
- Jenkins overview and the declarative pipeline syntax.

## Kubernetes
- Kubernetes overview (nodes, pods, namespaces, deployments and services).
- Kubernetes manifest (deployment resource) structure.
  * Generally, developers only need to worry about the deployment manifest.

## Demo
Demo / Workshop in the following order...

### Docker
(The below should be shown on local)
- Show running unit tests through a docker container.
- Show packaging of tested (or compiled) artifact into Docker image.
- Show the running of the application using the Docker image.
- Show uploading the image into Kubernetes.

### Kubernetes
- Go through the layout of a deployment manifest.
- Change the image spec to the one that was pushed in the previous section.
- Apply the manifest.
- Show the dashboard.
- Access the service.

### Jenkins
- Talk about how the process in the previous 2 sections can be automated using Jenkins.
- Go through the layout of a Jenkinsfile (talk about the 2 stages).
- Run the Jenkins pipeline by pushing some code.
- See the updated service.
