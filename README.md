# IOC (Indicator Of Compromise) - Check
# IP Address Reputation 
A Python script to automate the process of checking the reputation of all IP addresses present in a CSV files against the AbuseIPDB API. 
This tool scans CSV files, extracts IP addresses, checks their reputation, and generates an Excel report highlighting IP reputation scores


# Features
* Scan multiple CSV files for IP addresses and tokenize them.
* Checks All/User selected IP addresses against the AbuseIPDB API.
* Generate an Excel report with abuse confidence scores and other information.
* Apply color coding to indicate the IP reputation level.
* Creats copies for non-CSV files and converts these copies into CSV format.
* Organize files by moving CSV files to a sub folder.
* original form of the file are maintained if required.

# Files
* The repository has two files 
1.  ioc_ip_add_check_rand.ipynb : Randomly Extracts 100 IP Addresses from the CSV files And Check the reputation of the extracted IP addresses using the AbuseIPDB API.
2.  IoC_IP_Add_check.ipynb : Check the reputation of all the extracted IP addresses available in the CSV file using the AbuseIPDB API.

# Acknowledgements
* AbuseIPDB for providing the API service to check IP reputation.

