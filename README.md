# Cyptocurrency-Blockchain
Cryptography Team project<br>
Tried to implement a basic version of Crypto Currency. The project implements the basic idea of any blockchain that are
1) P2P network
2) Mining of Block using a valid proof of work
3) Creating new users 
4) View User
5) Consensus Protocol
6) Verify Transaction 
7) Valid Chain
## Team
1) Rishab Nahar
2) Rohan Sinha
3) Thakur Shivank Singh
4) Vamsi Krishna
<h3>Structure of Source Code</h3>
• The folder "blockchain_demo" contains the source code. The code is divided into 2 subfolders named "blockchain" and "blockchain_client", and two other folders named ".idea" and "venv" (these will be created automatically) which will help in building the virtual environment in the PyCharm. These files will help replicate the environment of the project in any system.
<br>
• The folder "blockchain" consists of scripts from the server side. It is further divided into 3 sub directories. One which has the HTML and Javascript(templates) which is used for UI.The static folder contains the custom CSS and bootstrap frameworks. The "blockchain.py" consists of the python script which is used to implement various functionalities like create block,verify transaction, Proof of work etc. 
<br>
• The  folder blockchain_client consists of the scripts from the user side. It is further divided into 3 sub parts. One which has the HTML and Javascript(templates) which is used for UI for the user. The static folder contains 
  the custom CSS part and bootstrap frameworks. The blockchain_client.py consists of the python script which is used to implement various functionalities like create signing transaction, generating transaction, view user etc. 
<br>
<h3>Dependencies</h3>
<p>For running our project following dependencies would be required:
<br>
1)Python compiler (preferably 3.7.x)<br>
2)Installing Pyton libraries such as Flask, Crypto, requests.hashlib,urllib,json, other UI libraries<br>
3)Use any one from Pycharm or Annaconda.
</p>
<h3>Running The Project</h3>
In the PyCharm IDE,<br>
1) Firstly assemble all the scripts in the same order they have been arranged in blockchain_demo project.<br>
2)Configure diffrent nodes according to their need. If you are making a node then you have to configure it on blockchain.py and give 5000 port series to it.
  For creating a user client we have to configure it on blockchain_client.py and give 8000 series port to it.<br>
3)And finally run all these configruations to get a running project.<br>
<br>
