# Task 8 – VPN Setup on Kali Linux

## Objective
Set up a VPN on Kali Linux, verify IP change, and understand VPN privacy/security.

## VPN Chosen
- Name: Windscribe
- Reason: Free tier, Linux CLI support.

## Steps Followed
1. Created free VPN account on official site.
2. Installed CLI client using `apt`.
3. Logged in via terminal.
4. Connected to fastest server.
5. Verified IP change with `curl ifconfig.me` and browser test.
6. Confirmed HTTPS encryption.
7. Disconnected and compared IP.

## Evidence
- `01-connected.png` – Terminal showing VPN connected.
- `02-ip-vpn-on.png` – New IP (VPN active).
- `03-ip-vpn-off.png` – Real IP (VPN off).

## Tech Notes
- **Protocols:** OpenVPN / WireGuard
- **Encryption:** AES-256
- **Benefits:** Hides IP, secures data, bypasses geo-blocks
- **Limitations:** Speed drop, not full anonymity

## Conclusion
Successfully configured VPN in Kali Linux, verified IP change, and tested encrypted browsing.
