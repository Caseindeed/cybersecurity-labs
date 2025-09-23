# Day 1 — SOC Lab Setup

## Goal
Set up a virtual SOC lab environment with Windows (victim) and Kali (attacker) VMs on the same NAT network.

## Steps Completed
1. Created a NAT Network (`SOC-NAT`) with DHCP enabled.
2. Attached both Windows 10 VM and Kali VM to `SOC-NAT`.
3. Verified both machines received `10.0.2.x` addresses.
4. Confirmed internet connectivity from both machines.
5. Created baseline snapshots: `Baseline-Day1`.

## IPs
- Windows 10 VM → 10.0.2.4
- Kali VM → 10.0.2.5

## Screenshots
- NAT Network setup  
- Windows IP (`ipconfig`)  
- Kali IP (`ip a`)  
- Windows internet ping (`ping 8.8.8.8`)  
- Kali internet ping (`ping -c 3 8.8.8.8`)

## Next Steps (Day 2)
- Install Sysmon on Windows
- Install Splunk
- Forward logs to Splunk
- Verify log ingestion
