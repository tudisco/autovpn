This script assumes theat all aws credentails and tools are already setup on system.

1. Clone rep to system.
2. Execute the deploy_aws_vpn.sh script supplying the name of AWS keypair as an argument
   place quotes around key name if it contains spaces.
	ex. deploy_aws_vpn.sh macbook 
3. OpenVPN config files are downloaded to ~/Downloads
4. Import the aws_vpn.ovpn config file into VPN client
