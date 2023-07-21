Dir
`cd /etc/netplan`

example.
`cp ~/src/$this/50-cloud-wifi.yaml .`

Permissions
`sudo chmod 600 *.yaml`

Apply
`sudo netplan apply 50-cloud-wifi.yaml`
