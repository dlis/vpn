# NordVPN behind Outline

## Usage

1. Create a new server based on Ubuntu and run there:

```
apt update && apt upgrade -y
curl -sSL https://github.com/dlis/vpn/raw/master/install.sh | bash -s -- some.domain.com
```

2. Bind the domain to ip of the server