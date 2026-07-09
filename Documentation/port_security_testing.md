# Port Security Testing

## Objective

Validate that Cisco Port Security protects access ports from unauthorized devices.

## Test Procedure

1. Enabled sticky MAC learning on access ports.
2. Learned the authorized MAC address from Admin-PC1.
3. Disconnected the authorized PC.
4. Connected an unauthorized PC (PC5) to the same switch port.
5. Verified that the switch placed the interface into an **err-disabled** state because of a port security violation.
6. Recovered the port using the `shutdown` / `no shutdown` procedure and reconnected the authorized device.

## Result

The switch successfully blocked the unauthorized device and protected the enterprise network from unauthorized access.
