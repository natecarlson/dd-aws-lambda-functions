# lambda-rds-enhanced-to-graphite
Lambda function that processes the AWS Log Streams created by RDS Enhanced Monitoring and sends the
data to a Graphite Carbon instance, either publicly or via a VPC

# How to use this code

TODO.

* Modify rds_enhanced_monitoring/main.py, and set your CARBON_SERVER, CARBON_PORT, and CARBON_NAMESPACE
* Create a zip file with the contents of rds_enhanced_monitoring (not including the folder)
* Upload the zip file as a lambda function
