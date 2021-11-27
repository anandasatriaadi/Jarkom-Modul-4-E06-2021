# VLSM dengan CPT

## Mengatur interface pada router
| INTERFACE FOOSHA | IPv4 Address |   Subnet Mask   |
|:----------------:|:------------:|:---------------:|
| CLOUD            |              |                 |
| DORIKI           | 10.32.27.161 | 255.255.255.252 |
| BLUENO           | 10.32.8.1    | 255.255.252.0   |
| WATER7           | 10.32.27.149 | 255.255.255.252 |
| GUANHAO          | 10.32.27.153 | 255.255.255.252 |

| INTERFACE WATER7 | IPv4 Address |   Subnet Mask   |
|:----------------:|:------------:|:---------------:|
| FOOSHA           | 10.32.27.150 | 255.255.255.252 |
| CIPHER           | 10.32.16.1   | 255.255.252.0   |
| PUCCI            | 10.32.27.145 | 255.255.255.252 |

| INTERFACE PUCCI | IPv4 Address |   Subnet Mask   |
|:---------------:|:------------:|:---------------:|
| WATER7          | 10.32.27.146 | 255.255.255.252 |
| COURT/CALM      | 10.32.0.1    | 255.255.248.0   |
| JIPANGU         | 10.32.27.1   | 255.255.255.128 |

| INTERFACE GUANHAO | IPv4 Address |   Subnet Mask   |
|:-----------------:|:------------:|:---------------:|
| FOOSHA            | 10.32.27.154 | 255.255.255.252 |
| JABRA             | 10.32.20.1   | 255.255.252.0   |
| ALAB/MAIN         | 10.32.24.1   | 255.255.254.0   |
| OIMO              | 10.32.27.157 | 255.255.255.252 |

| INTERFACE ALABASTA | IPv4 Address |   Subnet Mask   |
|:------------------:|:------------:|:---------------:|
| GUANHAO            | 10.32.24.2   | 255.255.255.252 |
| JORGE              | 10.32.27.129 | 255.255.255.240 |

| INTERFACE OIMO | IPv4 Address |   Subnet Mask   |
|:--------------:|:------------:|:---------------:|
| GUANHAO        | 10.32.27.158 | 255.255.255.252 |
| SEA/ENIES      | 10.32.26.1   | 255.255.255.0   |
| FUKUROU        | 10.32.27.165 | 255.255.255.252 |

| INTERFACE SEASTONE | IPv4 Address |  Subnet Mask  |
|:------------------:|:------------:|:-------------:|
| OIMO               | 10.32.26.2   | 255.255.255.0 |
| ELENA              | 10.32.12.1   | 255.255.252.0 |

## Mengatur interface pada client
| INTERFACE BLUENO | IPv4 Address |  GATEWAY  |    NETMASK    |
|:----------------:|:------------:|:---------:|:-------------:|
| FOOSHA           | 10.32.8.2    | 10.32.8.1 | 255.255.252.0 |

| INTERFACE DORIKI | IPv4 Address |    GATEWAY   |     NETMASK     |
|:----------------:|:------------:|:------------:|:---------------:|
| FOOSHA           | 10.32.27.162 | 10.32.27.161 | 255.255.255.252 |

| INTERFACE CIPHER | IPv4 Address |   GATEWAY  |    NETMASK    |
|:----------------:|:------------:|:----------:|:-------------:|
| WATER7           | 10.32.16.2   | 10.32.16.1 | 255.255.252.0 |

| INTERFACE COURTYARD | IPv4 Address |  GATEWAY  |    NETMASK    |
|:-------------------:|:------------:|:---------:|:-------------:|
| PUCCI               | 10.32.0.2    | 10.32.0.1 | 255.255.248.0 |

| INTERFACE CALMBELT | IPv4 Address |  GATEWAY  |    NETMASK    |
|:------------------:|:------------:|:---------:|:-------------:|
| PUCCI              | 10.32.0.3    | 10.32.0.1 | 255.255.248.0 |

| INTERFACE JIPANGU | IPv4 Address |   GATEWAY  |     NETMASK     |
|:-----------------:|:------------:|:----------:|:---------------:|
| PUCCI             | 10.32.27.2   | 10.32.27.1 | 255.255.255.128 |

| INTERFACE JABRA | IPv4 Address |   GATEWAY  |    NETMASK    |
|:---------------:|:------------:|:----------:|:-------------:|
| GUANHAO         | 10.32.20.2   | 10.32.20.1 | 255.255.252.0 |

| INTERFACE MAINGATE | IPv4 Address |   GATEWAY  |    NETMASK    |
|:------------------:|:------------:|:----------:|:-------------:|
| GUANHAO            | 10.32.24.3   | 10.32.24.1 | 255.255.254.0 |

| INTERFACE JORGE | IPv4 Address |    GATEWAY   |     NETMASK     |
|:---------------:|:------------:|:------------:|:---------------:|
| ALABASTA        | 10.32.27.130 | 10.32.27.129 | 255.255.255.240 |

| INTERFACE ENIES | IPv4 Address |   GATEWAY  |    NETMASK    |
|:---------------:|:------------:|:----------:|:-------------:|
| OIMO            | 10.32.26.3   | 10.32.26.1 | 255.255.255.0 |

| INTERFACE FUKUROU | IPv4 Address |    GATEWAY   |     NETMASK     |
|:-----------------:|:------------:|:------------:|:---------------:|
| OIMO              | 10.32.27.166 | 10.32.27.165 | 255.255.255.252 |

| INTERFACE ELENA | IPv4 Address |   GATEWAY  |    NETMASK    |
|:---------------:|:------------:|:----------:|:-------------:|
| SEASTONE        | 10.32.12.2   | 10.32.12.1 | 255.255.252.0 |

### Routing

# CIDR dengan GNS3
## Membuat Topologi

![topologi](https://user-images.githubusercontent.com/43901559/143678143-695e2576-4aef-4411-b2e4-3555330a5618.png)

## Penggabungan Subnet
### Step 0

![step0](https://user-images.githubusercontent.com/43901559/143678171-d3a65586-280e-49e6-8505-74ad53ce3f51.png)

### Step 1

![step1](https://user-images.githubusercontent.com/43901559/143678185-fbe8149e-65fd-4d5a-a299-9fc75cbedc11.png)

### Step 2

![step2](https://user-images.githubusercontent.com/43901559/143678197-80c604e0-bc11-4e7a-b5b9-52837865b26d.png)

### Step 3

![step3](https://user-images.githubusercontent.com/43901559/143678202-90fad959-0581-4b95-b7db-85b2328f5d71.png)

### Step 4

![step4](https://user-images.githubusercontent.com/43901559/143678210-ab7962c7-5fde-4eaa-bb3e-448258a9cf35.png)

## Tabel Penggabungan Subnet

| **Subnet** | **Asal Subnet** |
| --- | --- |
| B1 | A1 + A2 |
| B2 | A3 + A14 |
| B3 | A4 + A7 |
| B4 | A5 + A6 |
| B5 | A12 + A13 |
| B6 | A10 + A11 |
| B7 | A8 + A9 |
| C1 | B1 + B2 |
| C2 | B3 + B4 |
| C3 | B5 + B6 |
| C4 | B7 + A15 |
| D1 | C1 + C2 |
| D2 | C3 + C4 |
| E1 | D1 + D2 |

## Tabel Netmask

| **Subnet** | **Netmask** |
| --- | --- |
| A1 | /22 |
| A2 | /24 |
| A3 | /30 |
| A4 | /22 |
| A5 | /28 |
| A6 | /23 |
| A7 | /30 |
| A8 | /30 |
| A9 | /22 |
| A10 | /22 |
| A11 | /30 |
| A12 | /21 |
| A13 | /25 |
| A14 | /30 |
| A15 | /30 |
| B1 | /21 |
| B2 | /29 |
| B3 | /21 |
| B4 | /22 |
| B5 | /20 |
| B6 | /21 |
| B7 | /21 |
| C1 | /20 |
| C2 | /20 |
| C3 | /19 |
| C4 | /20 |
| D1 | /19 |
| D2 | /18 |
| E1 | /17 |

## Tabel CIDR

| **Subnet** | **Network ID** | **Netmask** | **Broadcast ID** |
| --- | --- | --- | --- |
| A1 | 10.32.0.0 | 255.255.252.0 | 10.32.3.255 |
| A2 | 10.32.4.0 | 255.255.255.0 | 10.32.4.255 |
| A3 | 10.32.8.0 | 255.255.255.252 | 10.32.8.3 |
| A4 | 10.32.16.0 | 255.255.252.0 | 10.32.19.255 |
| A5 | 10.32.26.0 | 255.255.255.240 | 10.32.26.15 |
| A6 | 10.32.24.0 | 255.255.254.0 | 10.32.25.255 |
| A7 | 10.32.20.0 | 255.255.255.252 | 10.32.20.3 |
| A8 | 10.32.68.0 | 255.255.255.252 | 10.32.68.3 |
| A9 | 10.32.64.0 | 255.255.252.0 | 10.32.252.0 |
| A10 | 10.32.48.0 | 255.255.252.0 | 10.32.51.255 |
| A11 | 10.32.52.0 | 255.255.255.252 | 10.32.52.3 |
| A12 | 10.32.32.0 | 255.255.248.0 | 10.32.39.255 |
| A13 | 10.32.40.0 | 255.255.255.128 | 10.32.40.127 |
| A14 | 10.32.8.4 | 255.255.255.252 | 10.32.8.7 |
| A15 | 10.32.72.0 | 255.255.255.252 | 10.32.72.3 |

## Tree CIDR
https://miro.com/app/board/o9J_lhFuRKU=/?invite_link_id=749360710143

## Konfigurasi
### Router

Foosha
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.32.64.1
	netmask 255.255.252.0
	broadcast 10.32.67.255

auto eth2
iface eth2 inet static
	address 10.32.72.1
	netmask 255.255.255.252
	broadcast 10.32.72.3

auto eth3
iface eth3 inet static
	address 10.32.68.1
	netmask 255.255.255.252
	broadcast 10.32.68.3

auto eth4
iface eth4 inet static
	address 10.32.20.1
	netmask 255.255.255.252
	broadcast 10.32.20.3
```

Water7
```
auto eth0
iface eth0 inet static
	address 10.32.68.2
	netmask 255.255.255.252
	broadcast 10.32.68.3
	gateway 10.32.68.1

auto eth1
iface eth1 inet static
	address 10.32.48.1
	netmask 255.255.252.0
	broadcast 10.32.67.255
	gateway 10.32.68.1

auto eth2
iface eth2 inet static
	address 10.32.52.1
	netmask 255.255.255.252
	broadcast 10.32.52.3
	gateway 10.32.68.1
```

Guanhao
```
auto eth0
iface eth0 inet static
	address 10.32.20.2
	netmask 255.255.255.252
	broadcast 10.32.20.3
	gateway 10.32.20.1

auto eth1
iface eth1 inet static
	address 10.32.16.1
	netmask 255.255.252.0
	broadcast 10.32.19.255
	gateway 10.32.20.1

auto eth2
iface eth2 inet static
	address 10.32.24.1
	netmask 255.255.254.0
	broadcast 10.32.25.255
	gateway 10.32.20.1

auto eth3
iface eth3 inet static
	address 10.32.8.1
	netmask 255.255.255.252
	broadcast 10.32.8.3
	gateway 10.32.20.1
```

Pucci
```
auto eth0
iface eth0 inet static
	address 10.32.40.1
	netmask 255.255.255.128
	broadcast 10.32.40.127
	gateway 10.32.52.1

auto eth1
iface eth1 inet static
	address 10.32.52.2
	netmask 255.255.255.252
	broadcast 10.32.52.3
	gateway 10.32.52.1

auto eth2
iface eth2 inet static
	address 10.32.32.1
	netmask 255.255.248.0
	broadcast 10.32.39.255
	gateway 10.32.52.1
```

Alabasta
```
auto eth0
iface eth0 inet static
	address 10.32.24.2
	netmask 255.255.254.0
	broadcast 10.32.25.255
	gateway 10.32.24.1

auto eth1
iface eth1 inet static
	address 10.32.26.1
	netmask 255.255.255.240
	broadcast 10.32.26.15
	gateway 10.32.24.1
```

Oimo
```
auto eth0
iface eth0 inet static
	address 10.32.8.2
	netmask 255.255.255.252
	broadcast 10.32.8.3
	gateway 10.32.8.1

auto eth1
iface eth1 inet static
	address 10.32.8.5
	netmask 255.255.255.252
	broadcast 10.32.8.7
	gateway 10.32.8.1

auto eth2
iface eth2 inet static
	address 10.32.4.1
	netmask 255.255.255.0
	broadcast 10.32.4.255
	gateway 10.32.8.1
```

Seastone
```
auto eth0
iface eth0 inet static
	address 10.32.4.2
	netmask 255.255.255.0
	broadcast 10.32.4.255
	gateway 10.32.4.1

auto eth1
iface eth1 inet static
	address 10.32.0.1
	netmask 255.255.252.0
	broadcast 10.32.3.255
	gateway 10.32.4.1
```

### Host & Server

Blueno
```
auto eth0
iface eth0 inet static
	address 10.32.64.2
	netmask 255.255.252.0
	gateway 10.32.64.1
```

Doriki
```
auto eth0
iface eth0 inet static
	address 10.32.72.2
	netmask 255.255.255.252
	gateway 10.32.72.1
```

Cipher
```
auto eth0
iface eth0 inet static
	address 10.32.48.2
	netmask 255.255.252.0
	gateway 10.32.48.1
```

Jipangu
```
auto eth0
iface eth0 inet static
	address 10.32.40.2
	netmask 255.255.255.128
	gateway 10.32.40.1
```

Calmbelt
```
auto eth0
iface eth0 inet static
	address 10.32.32.2
	netmask 255.255.248.0
	gateway 10.32.32.1
```

Courtyard
```
auto eth0
iface eth0 inet static
	address 10.32.32.3
	netmask 255.255.248.0
	gateway 10.32.32.1
```

Jabra
```
auto eth0
iface eth0 inet static
	address 10.32.16.2
	netmask 255.255.252.0
	gateway 10.32.16.1
```

Maingate
```
auto eth0
iface eth0 inet static
	address 10.32.24.3
	netmask 255.255.254.0
	gateway 10.32.24.1
```

Jorge
```
auto eth0
iface eth0 inet static
	address 10.32.26.2
	netmask 255.255.255.240
	gateway 10.32.26.1
```

Fukurou
```
auto eth0
iface eth0 inet static
	address 10.32.8.6
	netmask 255.255.255.252
	gateway 10.32.8.5
```

Enieslobby
```
auto eth0
iface eth0 inet static
	address 10.32.4.3
	netmask 255.255.255.0
	gateway 10.32.4.1
```

Elena
```
auto eth0
iface eth0 inet static
	address 10.32.0.2
	netmask 255.255.252.0
	gateway 10.32.0.1
```

## Routing
### Foosha
```
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 10.32.0.0/17
```
```
# CIPHER
route add -net 10.32.48.0 netmask 255.255.252.0 gw 10.32.68.2

# PUCCI
route add -net 10.32.52.0 netmask 255.255.255.252 gw 10.32.68.2

# CALMBELT dan COURTYARD
route add -net 10.32.32.0 netmask 255.255.248.0 gw 10.32.68.2

# JIPANGU
route add -net 10.32.40.0 netmask 255.255.255.128 gw 10.32.68.2

# JABRA
route add -net 10.32.16.0 netmask 255.255.252.0 gw 10.32.20.2

# MAINGATE
route add -net 10.32.24.0 netmask 255.255.254.0 gw 10.32.20.2

# JORGE
route add -net 10.32.26.0 netmask 255.255.255.240 gw 10.32.20.2

# OIMO
route add -net 10.32.8.0 netmask 255.255.255.252 gw 10.32.20.2

# FUKUROU
route add -net 10.32.8.4 netmask 255.255.255.252 gw 10.32.20.2

# ENIESLOBBY
route add -net 10.32.4.0 netmask 255.255.255.0 gw 10.32.20.2

# ELENA
route add -net 10.32.0.0 netmask 255.255.252.0 gw 10.32.20.2
```

### Water7
```
# CALMBELT dan COURTYARD
route add -net 10.32.32.0 netmask 255.255.248.0 gw 10.32.52.2

# JIPANGU
route add -net 10.32.40.0 netmask 255.255.255.128 gw 10.32.52.2
```

### Guanhao
```
# JORGE
route add -net 10.32.26.0 netmask 255.255.255.240 gw 10.32.24.2

# FUKUROU
route add -net 10.32.8.4 netmask 255.255.255.252 gw 10.32.8.2

# ENIESLOBBY
route add -net 10.32.4.0 netmask 255.255.255.0 gw 10.32.8.2

# ELENA
route add -net 10.32.0.0 netmask 255.255.252.0 gw 10.32.8.2
```

### Oimo
```
# ELENA
route add -net 10.32.0.0 netmask 255.255.252.0 gw 10.32.4.2
```

### `resolv.conf`
Pada semua node selain **Foosha**, run
```
echo nameserver 192.168.122.1 > /etc/resolv.conf
```
