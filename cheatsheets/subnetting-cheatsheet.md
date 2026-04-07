# Subnetting Quick Reference

## CIDR to Subnet Mask
| CIDR | Subnet Mask | Usable Hosts |
|------|-------------|--------------|
| /24 | 255.255.255.0 | 254 |
| /25 | 255.255.255.128 | 126 |
| /26 | 255.255.255.192 | 62 |
| /27 | 255.255.255.224 | 30 |
| /28 | 255.255.255.240 | 14 |

## Quick Math
- Hosts = 2^(32-CIDR) - 2
- Network bits = CIDR
- Subnets = 2^(CIDR - default class bits)