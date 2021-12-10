# Lab 4: Create and use an SSH public-private key pair for Linux VMs in Azure

1. Supported SSH key formats: SSH protocol 2 (SSH-2) RSA public-private key pairs with a minimum length of 2048 bits
2. Create an SSH key pair: ssh-keygen -m PEM -t rsa -b 4096
3. Provide an SSH public key when deploying a VM: --ssh-key-values
4. SSH into your VM: ssh username@ServerFQDNOrIP

### Notes:

Quickstart: SSH for Linux VMs
* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/mac-create-ssh-keys

Quickstart for Bash in Azure Cloud Shell
* https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart
