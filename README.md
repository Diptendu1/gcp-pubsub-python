# GCP-pubsub-python

To run the code you need to have GCP account.

Create a topic and a subscription in google pub/sub.

Launch 2 VMs(Ubuntu 16.04). one for pushing the data another for pulling the data.

Install nessesary python packages for script to work. 

sudo apt-get -y install python python-dev python3 python3-dev

sudo apt-get update

Install PIP:

wget https://bootstrap.pypa.io/get-pip.py

sudo python get-pip.py

Install PIP3:

sudo apt-get -y install python3-pip

Update the repository

sudo apt-get update

Install google-cloud with pip3: 
sudo pip3 install google-cloud


Install google-cloud with pip:

sudo pip install --upgrade google-cloud

Install google-cloud-pubsub:
sudo pip install --upgrade google-cloud-pubsub

Install google-api-python-client:
sudo pip install --upgrade google-api-python-client


These commands should be executed on both VMS before running the scripts. 



