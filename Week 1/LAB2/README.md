# Lab 2: Manage Linux VMs with the Azure CLI

1. Create resource group: az group create --name ResourceGroupName
2. Create virtual machine: az vm create --resource-group ResourceGroupName --name NameOfTheVM --image VMImage --generate-ssh-keys
3. Connect to VM: ssh@PublicIPAddressOfVM
4. Understand VM images: az vm image list --output table
5. Understand VM sizes: az vm list-sizes --location Zone --output table
6. VM power states: az vm get-instance-view --resource-group ResourceGroupName --name VMName --query instanceView.statuses[1] --output table
7. Management tasks
Great fun this has been

### Notes:

Quickstart: Create a Linux VM
* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-vm

Quickstart for Bash in Azure Cloud Shell
* https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart
