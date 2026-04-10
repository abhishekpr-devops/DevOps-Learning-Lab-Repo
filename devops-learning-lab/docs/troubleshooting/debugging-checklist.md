# Debugging Checklist

## Website Down
- check DNS resolution
- ping the server
- check web server status
- check application status
- check firewall rules
- check open ports
- check logs

## SSH Not Working
- verify public IP
- verify key pair permissions
- verify username
- verify security group allows port 22
- test network connectivity

## Container Not Starting
- check container logs
- verify image exists
- check command and port mapping
- check environment variables
- check whether port is already in use

## Port Not Open
- check service is listening
- check firewall rules
- check security groups
- verify correct port number
- test with ss, netstat, or nc

## My notes
A checklist prevents random guessing and makes troubleshooting more systematic.

