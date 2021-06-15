## Test "route"
Run route command to show the IP routing table:
`route`{{execute}}

## Test "ip"
Run ip link show command to know the ip adress and interfaces:
`ip link show`{{execute}}

## Test "ss"
Run ss -a list all listening and non-listening connections:
`ss -a`{{execute}}

## Test "nmcli"
Run nmcli device show command to get complete information about known devices:
`nmcli device show`{{execute}}
Press q to quit the display

## Test "brctl"
Run nmcli device show command to get complete information about known devices:
`brctl`{{execute}}


## Test "nmtui"
Run nmtui, to manage the network using user interface:
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

>>You can edit file /ETC/NSSWITCH.CONF using nano.
(*) True
() False

>>Which one is/are not include in three modes of network bonding?
[ ]Link Aggregation
[*]Network Integration
[ ]Active/Passive
[ ]Load Balancing
