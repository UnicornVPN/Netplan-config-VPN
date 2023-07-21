# Test
Works on:
- Ubuntu 23.04!
wifi: `lshw -C network`
>description: Wireless interface
>product: QCA6174 802.11ac Wireless Network Adapter
>vendor: Qualcomm Atheros
>logical name: wlp2s0


Dir
`cd /etc/netplan`

example.
`cp ~/src/$this/50-bridge-wifi.(NetworkManager).yaml .`

Permissions
`sudo chmod 600 *.yaml`

Apply
`sudo netplan apply 50-bridge-wifi.(NetworkManager).yaml`
