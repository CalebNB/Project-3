# Project-3

This project's aim has two phases...

Phase 1 INSTALL AND RUN AN OPEN SOURCE PROJECT AND REPRODUCE THEIR RESULTS

The Word document PhaSe 1 Hello World AWS EC F1 shows screen shots of the Hellow_world Custom Logic
Synthesis and deployment with HDK and AWS EC@ F! instances.  As described by https://github.com/aws/aws-fpga/blob/master/hdk/README.md

The steps are as follows:

Go to AWS login to console

Launch instance 

configure aws

clone github aws repository

source hdk setup

run build scripts 

create s3 bucket and dcp/ logs folders

copy tar file to s3 bucket

generate afi

launch f1 instance

load afi onto fpga

run test_hello_world


Phase 2 BUILD A MACHINE LEARNING NEURON

The neuron.py is a neural net that teaches itself to identify if a person will get accepted to a certain university based on three criteria
1.  Did they score high enough on the SAT
2.  Does the family have a ceratin wealth
3.  Did they maintain a high enough GPA in high school

3.
