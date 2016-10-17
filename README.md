== Requirements & Instructions on Using the Ansible Ravello Module

:numbered:

== Overview

The purpose of the Ravello Ansible module is to provide a way to interact with Ravello using their SDK.  The goal is to be able to query, build and deploy Ravello applications using Ansible without having to interact with the Ravello UI.

== Requirements

. First and foremost obtain the Ravello SDK. 
+
----
# Install Ravello Python SDK
sudo pip install ravello-sdk

# Get to a good working directory
cd

# Clone the git repo
git clone https://github.com/ravello/python-sdk.git

# Get into the repo
cd python-sdk/examples

# Set up credentials file for Ravello
./set-creds
Enter username: yourlogin@redhat.com
Enter a Password:

# Run an example
./bp-get-all

# Get APP JSON (-a is for a full JSON dump)
./app-get-data -a myapp-bp-i > app.json
----

