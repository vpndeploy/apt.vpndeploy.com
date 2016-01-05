# APT Repo for VPN Deploy 

apt repo  for pre-built vpn related packages 

## for ubuntu 14.04

Add GPG public key

```
wget -O- http://apt.vpndeploy.com/2BB1CAF2.gpg | sudo apt-key add -
```

Add either of the following lines to your /etc/apt/sources.list:

```
# Ubuntu 14.04 or above
deb http://apt.vpndeploy.com/ubuntu trusty main
```


