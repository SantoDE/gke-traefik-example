gcloud init
gcloud auth application-default login
export GOOGLE_PROJECT=$(gcloud config get-value project)
gcloud container clusters get-credentials meetup-cluster --zone europe-west3-a