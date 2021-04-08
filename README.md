Ansible 

Playbooks to backup routers/ switches and push configs and config templates

Inventory hostnames must match the hostnames in the vars files

DYNAMIPS INFO PAGE

After Setting up the lab in GNS3, you should have a basic knowlage about the Dynamips in GNS3

GNS3 "really" recommend using the c3640, c3660, c3725, c3745 and c7200 IOS images listed in their website, because they have proven to be the most stable in GNS3 provided you.
Use the right amount of RAM and Idle-PC value.

https://docs.gns3.com/docs/emulators/cisco-ios-images-for-dynamips/


We'll use C3725#
The c3725 has 2 FastEthernet interfaces on its motherboard (GT96100-FE), 3 subslots for WICs (maximum of 6 serial ports) and 2 Network Module slots (maximum of 32 FastEthernet ports or 8 serial ports).
It needs minimum RAM of 128MB 
idle-PC value: 0x602467a4

The ios image should be downloaded, find your way to get it.
or try this: https://mega.nz/folder/nJR3BTjJ#N5wZsncqDkdKyFQLELU1wQ

IMPORT c3725 DYNAMIPS IMAGE to GNS3

---------------------

Download the Net. Auto from GNS3
https://www.gns3.com/marketplace/appliances/network-automation
