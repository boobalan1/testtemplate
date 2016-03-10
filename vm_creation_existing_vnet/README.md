# Create VM in an Existing VNET.

<a href=target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Prerequisite - Need a existing VNET and storage account.

all other required details are passed by user in the parameter file.

This template creates a VM in the existing VNET.


##### Parameter
    ##  Parameter values
     
    vmName                :  "testvm1"         [Name of the VM ]
    vmSize                :  "Standard_A0"     [Size of the VM ]
    WinImageOffer         :  "WindowsServer"   [Image publisher Name]
    winImageSku           :  "2012-Datacenter" [Image Name]
    winImageVersion       :  "latest"          [Image Version]
    vmLocation"           :  "West US"         [Location]
    username"             :  "boobalanadmin"   [Username]
    password"             :  "AdminPassword1"  [Password]
    storageName"          :  "boobalanstorage" [Storage name]
    storageType"          :  "Standard_LRS"    [Storage type]
    vnetName"             :  "BBVNet1"         [Existing Vnet Name ]
    networkAddressSpace"  :  "15.0.0.0/16"     [VNet Address space]
    subnetName"           :  "Subnet2BB"       [Subnet Name]
    subnetAddressPrefix"  :  "15.0.9.0/24"     [Subnet for launching VM]
    publicDnsName"        :  "balan2"          [DNS name]
    
    All the values are user provided for creating VM in a existing VNET.
    
