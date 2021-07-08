# Physical Design

## Hosts

* 4 x [INTEL NUC8V5PN](https://www.intel.com/content/www/us/en/support/articles/000055854/intel-nuc.html)
    * Samsung 970 EVO Plus NVME
    * Samsung 870 QVO 2TB
    * HyperX Impact 64GB SO DIMM
    * 1 x 1 GbE NIC

[Technical Product Specification](https://www.intel.com/content/dam/support/us/en/documents/intel-nuc/NUC8v5PN-NUC8v7PN-TechProdSpec.pdf)

### Resources Offered

* CPU: 4 x Intel® Core™ i5-8365U Processor, total available Ghz = 4 x (4 x 1.6 Ghz) = 25,6 Ghz (Not counting HT)
* RAM: 4 x 64 GB = 256 GB
* Raw storage for vSAN = 4 x 2 TB = 8 TB (not counting cache)

## Network

### Switches

### VLANS

| VLAN Function | VLAN ID | Subnet        | Routable | Notes   |
| :------------ |:-------:|:----------------|:--------:|:---------|
| Management    | 11      | 192.168.11.0/24 | Y        | OOB?
| vMotion       | 12      | 192.168.12.0/24 | N        |
| vSAN          | 13      | 192.168.13.0/24 | N        |
| NFS           | 15      | 192.168.15.0/24 | N        |
| Clients       | 0       |192.168.5.0/24   | Y        | 
| VPN Users     | 50      |192.168.50.0/24  | N        | Exists
| IoT           | 60      |192.168.60.0/24  | N        | Exists / Internet Only
| Tenant (b38d) | 101     |192.168.101.0/24 | N        | Exists / Internet Only
| b³-julie      | 200     |192.168.200.0/24 | N        | Exists
| VM Network    | tbd     | tbd             | Y        |
| Tanzu         | tbd     | tbd             | N        |