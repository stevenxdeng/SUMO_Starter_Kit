# SUMO Starter Kit
Author: ***Hsien-wen "Steven" Deng***\
This is a starter kit for **[Simulation Urban MObility](https://sumo.dlr.de/docs/index.html)** (**SUMO**) with **[Traffic Control Interface](https://sumo.dlr.de/docs/TraCI.html)** (**TraCI**). \
**SUMO** is a traffic engineering simulator to simulate different traffics in macroscopic or microscopic view. \
**TraCI** is a python-based platform to engage interactions (control, feedback) between user's scripts and SUMO.

## Prerequisite
1. [Python 3.8](https://www.python.org/downloads/)
2. Python IDE, recommend [Pyzo](https://pyzo.org/start.html)
3. [SUMO](https://sumo.dlr.de/docs/Downloads.php)\

## Deploy Application
1. Install **SUMO**
2. Click **Create stack**
3. Select **Upload a template file** and upload *CV_Surveillance_Template.json*
4. Input a name and click **Create stack**

## Test Application
1. Install boto3: `python -m pip install boto3`
2. Run *CV_Surveillance_Client.py*: `python CV_Surveillance_Client.py`\
*If errors show up, check names of resources (DynamoDB, Kinesis)*

## Destroy Application
After deletion of CloudFormation, resources are still in usage, **deletions** of these resources are needed to reduce cost impacts:\
**DynamoDB**\
**Kinesis Data Stream**
