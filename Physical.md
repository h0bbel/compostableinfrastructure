# Physical Design

## Network

### VLANS

| VLAN Function | VLAN ID | Subnet        | Routable | Notes   |
| :------------ |:-------:|:----------------|:--------:|:---------|
| Management    | 11      | 192.168.11.0/24 | Y        | OOB?
| vMotion       | 12      | 192.168.12.0/24 | N        |
| vSAN          | 13      | 192.168.13.0/24 | N        |
| NFS           | 15      | 192.168.15.0/24 | N        |
| Clients       | 0       |192.168.5.0/24   | Y        | 
| VPN Users     | 50      |192.168.50.0/24  | N        | Exists
| IoT           | 60      |192.168.60.0/24  | N        | Exists
| Tenant (b38d) | 101     |192.168.101.0/24 | N        | Exists / Internet Only
| b³-julie      | 200     |192.168.200.0/24 | N        | Exists
| VM Network    | tbd     | tbd             | Y        |
| Tanzu         | tbd     | tbd             | N        |