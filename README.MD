gcloud auth login

gcloud config set project extended-inn-331606

gcloud container clusters resize cluster-1 --zone us-central1-c --num-nodes=1 

gcloud container clusters get-credentials cluster-1 --zone us-central1-c

sudo service jenkins status
sudo service jenkins stop
sudo service jenkins start