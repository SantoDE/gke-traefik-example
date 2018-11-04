# Steps to do
* gcloud init
* gcloud auth application-default login
* export GOOGLE_PROJECT=$(gcloud config get-value project)
* gcloud container clusters get-credentials meetup-cluster --zone europe-west3-a

# Places to Edit:
Sub-Domain Names setzen fürs Routing:

* traefik/sub-domain-ingress-update/06_ingress.yml
* traefik/tls/07_ingress.yml

Email Addresse eintragen für die RBAC Permissions
* traefik/default/01_permissions.yml

# Auth
Default Login fürs Webinterface ist: dashboard/meetup123