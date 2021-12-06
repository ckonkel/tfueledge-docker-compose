# tfueledge-docker-compose
Using docker compose to run multiple theta tfuel edge nodes

Curent State - Manual

Desired State - Automated, with uptime, downtime reporting, web interface... more things.

## Migration of data from existing

### Windows

If you already have a single edge node running or multple nodes running in Windows using multiple VMs with something like Hyper-V or Virtual Box

for each instance copy this directory/file from:

C:\Users\Someuser\AppData\Roaming\Theta Edge Node\ThetaEdgeNode\edgecast\ldb
C:\Users\Someuser\AppData\Roaming\Theta Edge Node\ThetaEdgeNode\edgecast\key

to this folder that hosts your continer volume:

./tfuel-edge-docker/node001-0xPARTIALADDRESSHASHGOESHERE1-mainnet/anycast

AND

for each instance copy these directories from:

C:\Users\Someuser\AppData\Roaming\Theta Edge Node\ThetaEdgeNode\edgecore\mainnet\db
C:\Users\Someuser\AppData\Roaming\Theta Edge Node\ThetaEdgeNode\edgecore\mainnet\key

to this folder that hosts your continer volume:

./tfuel-edge-docker/node001-0xPARTIALADDRESSHASHGOESHERE1-mainnet/edgecore

### Mac

Should be similar to Windows version, will stub out, if I get a chance to test MacOS.

