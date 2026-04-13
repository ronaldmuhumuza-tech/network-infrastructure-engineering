# Low-Level Design

## VLAN & IP Scheme

| VLAN | Department | Subnet          | Gateway      |
|------|------------|-----------------|--------------|
| 10   | Management | 192.168.10.0/24 | 192.168.10.1 |
| 20   | Sales      | 192.168.20.0/24 | 192.168.20.1 |
| 30   | IT         | 192.168.30.0/24 | 192.168.30.1 |
| 40   | Guest      | 192.168.40.0/24 | 192.168.40.1 |

## Notes

- Each VLAN is mapped to a matching subnet for clarity
- /24 subnets provide sufficient address space for this environment
- Private addressing is used for internal communication