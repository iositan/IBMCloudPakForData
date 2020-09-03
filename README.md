# IBMCloudPakForData
This one contains custom template and scripts

Template CreateSubnetsIBMCPD_gh.json contains a stripped down working version of the creation of custom subnets in an exsiting aws VPC.
Before executing, you must update with your own values for VPC id, zone and CIDR
It is based on IBM source:

aws-vpc.yaml

The quick start installation located here
https://aws-quickstart.s3.amazonaws.com/quickstart-ibm-icp-for-data/doc/ibm-cloud-pak-for-data-on-the-aws-cloud.pdf
states that there is an alternative of install if the customer has its own 6 subnets created already.
Of those three are public and three are private
