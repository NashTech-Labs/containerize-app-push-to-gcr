# containerize web app, dockerize it and push to GCR
- This techhub contains a simple web application, a Dockerfile which containerizes this and an script which pushes this image Google's container registry.
- This techhub is useful for simple deployments to GCP from GCR.

# Enable Google Container Registry API
``` gcloud config set project <GCP_PROJECT_ID> ``` </br>
![image](https://user-images.githubusercontent.com/76727343/220054521-fd5bae2f-d7c5-4a27-9156-2947b4c26deb.png)
</br>
``` gcloud services list ``` must list gcr.io API enabled. </br>

# How to use?
``` sh containerize-push-to-gcr.sh ```

# Configure gcloud cli
Make sure ``` gcloud projects list ``` results your GCP project on which you have enabled gcr.io API. </br>

# index.js
Simple node.js app that servers "Hello from Knoldus !" </br>
