# PINDeL
Protein Interaction Network-based Deep Learning Framework for Identifying Disease-Associated Human Proteins

Please download and unzip 'Executable.zip'.

The extracted folder 'Executable' consists of the following files:


Input:
------
1) hplg.features --> File storing the topological features' measures for all the nodes/proteins of the HPLG.
2) label.pkl --> File storing the labels (Control/Disease) corresponding to each protein.
3) network_wcc.pkl --> File storing the HPLG network.
4) nodes.pkl --> File containing the list of proteins present in the HPLG.
5) pindel.pt --> Our trained model.
6) pbd.yml --> Conda environment file.
7) pbd.py --> Source code.


Requirements:
-------------
1) Anaconda


Create environment:
-------------------
For execution, we recommend to create a separate environment in Anaconda. The image of the required environment (`pbd.yml`) is given in this package. 
First create the environment and activate it by executing the following commands,

`conda env create -f pbd.yml`

`conda activate pbd`


Run:
----
Run the pbd.py file.


For any doubts or suggestions please contact
barnali.das@iitkgp.ac.in
pralay@cse.iitkgp.ac.in
