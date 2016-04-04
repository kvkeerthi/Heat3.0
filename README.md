# Contrail Heat 3.0

# YAML Templates

# VN's and Policy Templates

contrail-vn-v4v6.yaml

    - Will allow to create IPAM
    - Will allow to create v4 & v6 Subnets with DHCP ranges and Gateway

contrail-left-nw-policy.yaml   

    - Will allow to add NW Policy to the exiting Virtual Network

contrail-right-nw-policy.yaml  

    - Will allow to add NW Policy to the exiting Virtual Network

contrail-nw.yaml	             

     - Will allow to create Virtual Network

contrail-vn-policy-v0.1.yaml     

    - Will create a NW policy

vn-with-policy.yaml             

    - Will create Virtual Network with Network Policy

# V1 and V2 Templates

contrail-sc-v1.yaml            

    - Will create Service Template V1
    - Will create Service Instance
    - Will attach static route prefix

contrail-vm-sc-template-V2.yaml 

    - Will create 2 VM's using exiting Virtual Network
    - Will create Service Template V2
    - Will create Port Tuple based SI
                         
contrail-vm-si-left-subnet-V2.yaml 

    - Will create 2 VM's using exiting Virtual Network and bringing up left port on a specific Subnet using UUID
    - Will create Service Template V2
    - Will create Port Tuple based SI

contrail-vm-si-v2-template.yaml  

    - Will create a VM using exiting Virtual Network
    - Will create Service Template V2
    - Will create Port Tuple based SI

contrail-vm-port-mirror.yaml

    - Will creates 2 nova VM using existing VN’s 
    - Will enables port mirroring for left interface to and existing analyzer as SI with shared IP

contrail-mirror-sc-template-V2.yaml

    - Will creates nova vm using existing VN's
    - Will creates v2 template
    - Will creates SI with shared IP using v2 Template for Left interface

contrail-sc-static-route-v2.yaml

    - Will creates 2 nova vm using existing VN's
    - Will creates v2 template
    - Will creates SI with shared IP using v2 Template
    - Will create Interface Route Tables Route Prefix and route will be attached to right interface of the SI

contrail-sc-staticIP-v2.env

    - Will creates 2 nova vm using existing VN's and Static IP for Management Port
    - Will creates v2 template
    - Will creates SI with shared IP using v2 Template

contrail-sc.env

    - Will creates Mangement,Left,Right VN's
    - Will creates v1 template
    - Will creates SI with shared IP & Static-Route using v1 Template
    - Will create and attach NW Policy for LEFT and RIGHT VN's.
