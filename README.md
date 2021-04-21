# RestAPIwithAnsibleAssignment3
This Ansible YAML file performs REST API calls and fetches the required response.
It uses uri module with GET method from ansible.

User need to pass mac address and api token. These values are stored in variables.

Usage: ansible-playbook playbookName --extra-vars "api_token=api_token_value mac_addr=mac_address_value"


Description:

This YAML file collects the mac address, api token as command line arguments from the user. 

It will store all input varibles,headers for REST API GET request.

Performs REST API calls for the given url using API token authenticaiton.

The json response is parsed and required key is fetched to display the company name for the given mac address.
