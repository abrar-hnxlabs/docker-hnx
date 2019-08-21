# Docker configs

## Decrypting the env file
```
base64 -d transmission.b64 > t.enc
go-myubuntu decrypt --in=t.enc --out=transmission.env --p=password
```
Note: password is regular non complex

## Apps
- Plex
- Handbrake
- Transmission with OpenVpn
- Letsencrypt