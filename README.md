# google-serverless

This repo showcases a very simple app implemented cloud-native serverless on top of Google Cloud Platform (GCP).
The offerings as of January 2023 are:

- [Cloud Functions](google-cloud-functions/)
- [Cloud Run](google-cloud-run/)
- [App Engine](google-app-engine/)

To be able to follow these examples start by creating a new project in Google Cloud:

```
gcloud auth login # this will open up a browser windows in which you need to login to your Google Cloud account
gcloud projects create --name serverless # write down the project ID Google creates for you
gcloud config set project PROJECT_ID
```

Then dive into the respective directories for the different options and follow the instructions.

