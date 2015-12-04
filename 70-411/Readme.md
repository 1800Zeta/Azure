# 70-411 Test Lab

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2F1800Zeta%2FAzure%2Fmaster%2F70-411%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template will create 4 Virtual Machines, configure the subnet, configure the required IP addresses and a basic security group so you can spin up a test lab for the 70-411 Training.

Although only the parameters in [azuredeploy.parameters.json](./azuredeploy.parameters.json) are necessary, you can override the defaults of any of the template parameters.

## YOU ARE RESPONSIBLE FOR ALL COSTS OF RUNNING THESE MACHINES IN THE AZURE ENVIRONMENT They use the smallest (cheapest) options but you are still looking at around £40 a month if you leave all machines on all the time. 
