The code shows how to use Cloud Build to build a Docker image and push the image to Container Registry.
1) Run the following command to make quickstart.sh executable: chmod +x quickstart.sh
2) Start the Cloud Build by running the following command: gcloud builds submit --config cloudbuild.yaml .
3) Run the Docker image that you built before, where [PROJECT_ID] is your GCP project ID: docker run gcr.io/[PROJECT_ID]/quickstart-image
