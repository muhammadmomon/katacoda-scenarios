## Test "route"
Run command below to show the IP routing table:
`route`{{execute}}

## Test "ip"
Run command below to know the ip adress and interfaces:
`ip link show`{{execute}}

## Test "ethtool"
Install tool first by typing command below:
`apt install ethtool`{{execute}}
then we need to check existing network interface by running command:
`ifconfig -a`{{execute}} 
then we choose one of them (e.g. ens3) after that we can run command below to check its current Speed, Auto-Negotiation, and Duplex mode settings:
`ethtool ens3`{{execute}}

## Test "ss"
Run command below to list all listening and non-listening connections:
`ss -a`{{execute}}

## Test "iwconfig"
Install tools first by typing command below:
`apt install wireless-tools`{{execute}}
then Run command below to show existing ethernet bridge:
`iwconfig`{{execute}}

## Test "nmcli"
Run command below to get complete information about known devices:
`nmcli device show`{{execute}}
Press q to quit the display

## Test "brctl"
Install first by typing command below:
`apt install bridge-utils`{{execute}}
then Run command below to show existing ethernet bridge:
`brctl show`{{execute}}

## Test "nmtui"
Run command below to manage the network using user interface:
`nmtui`{{execute}}
Choose "Set system hostname", change the hostname to lab01, choose OK, and Quit.
Verify now the hostname had been changed to lab01, using the command below:
`hostname`{{execute}}


## Quiz
>>What command you can use to check connection between two host? <<
( ) host
(*) ping

>>What is netstat stands for <<
(*) Network Statistics
( ) Network Status

>>Which is/are the function of command dig: <<
[ ] To discover network issues
[*] Searching for a domain name
[*] To gather and display DNS information 
[ ] To configure network interfaces
[ ] To show the IP routing table

>>You can edit file /etc/nsswitch.conf using nano. <<
(*) True
( ) False

>>Which one is/are not include in three modes of network bonding? <<
[ ]Link Aggregation
[*]Network Integration
[ ]Active/Passive
[ ]Load Balancing
