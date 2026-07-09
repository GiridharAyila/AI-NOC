# Access Control Lists (ACL)

## Objective

Implemented Extended Access Control Lists to enforce communication policies between enterprise VLANs.

## Security Policy

| Source VLAN | Destination | Action |
|-------------|-------------|--------|
| Student | Admin | Deny |
| Student | Faculty | Deny |
| Student | Server | Permit |
| Student | Other Networks | Permit |

## ACL Name

STUDENT_POLICY

## Applied Interface

GigabitEthernet0/0.30 (Inbound)

## Verification

- Verified that Student VLAN cannot access Admin VLAN.
- Verified that Student VLAN cannot access Faculty VLAN.
- Verified that Student VLAN can still access the Server VLAN.
