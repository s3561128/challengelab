---
title: "Instruction"
date: 2021-04-13T14:30:42+10:00
draft: false
image: "sunset.jpeg"
tags: ["blogs"]
---
# How I build the website/Blog from scratch
<h8>First I installed Homebrew in mac and then I used hugo to build the website. To use Hugo we need to run the command</h8>

#### brew install hugo

<h8>After Installing Hugo, we need implement a theme as well which can be found on hugo.com. once we finished implementing a theme. To, launch the website, enter the cmd **hugo server** in terminal and enter **localhost1313** in safari.

My next step is to create a GCP project for firebase. To access the firebase from CLI, We need to install the firebase by running the cmd **npm install -g firebase-tools** Now, initialise the firebase by running **firebase init** Now, select hosting>use an existing project. If asked to overwrite any existing files select Y. Now, we are ready to deploy the website and just enter **firebase deploy** After the application has been deployed, I received a hosting URL. Click on it and we will see the same website being served from the Firebase CDN (content delivery network).</h8>

#### Automate the process from end to end using Cloud Build
###### Perform the initial commit

<h8> The goal of building the pipeline is to be able to trigger builds when changes are made to the repository. We will start by performing an initial commit to the repository so that we can validate our ability to make future changes.</h8>

#### Configure the build

<h8> Cloud Build uses a file named cloudbuild.yaml in the root directory of the repository to perform the build. The file is in YAML format. </h8>




