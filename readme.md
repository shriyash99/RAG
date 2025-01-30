# Installation of python environment

conda create -p venv python==3.10
conda activate venv/
pip install -r requirements.txt

# create .env file or aws 
(venv)CLI > aws configure
    AWS Access Key ID [************************]: "paste access key here"
    AWS Secret Access Key [********************]: "paste secret key here"
    Default region name [None]: us-east-1
    Default output format [None]: <enter>

# aws credentials are now within local venv folder integrated with boto3 python library
# Now we are ready to use jupyter-notebook with chat-request api 