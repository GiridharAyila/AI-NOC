# VLAN Configuration

## VLAN Details

| VLAN ID | Name       |
| ------- | ---------- |
| 10      | ADMIN      |
| 20      | FACULTY    |
| 30      | STUDENTS   |
| 40      | SERVERS    |
| 99      | MANAGEMENT |

## Port Assignments

### SW2

* Fa0/2 → VLAN 10
* Fa0/3 → VLAN 10
* Fa0/4 → VLAN 10

### SW3

* Fa0/2 → VLAN 20
* Fa0/3 → VLAN 20
* Fa0/4 → VLAN 20

### SW4

* Fa0/2 → VLAN 30
* Fa0/3 → VLAN 30
* Fa0/4 → VLAN 30
* Fa0/5 → VLAN 30

### SW1

* Fa0/3 → VLAN 40 (Server)

## Verification

Command used:

show vlan brief

All VLANs were successfully created and assigned to the appropriate ports.
