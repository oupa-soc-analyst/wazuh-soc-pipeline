# 🚨 Wazuh SOC Pipeline - Oupa Nyoni

**Production SOC monitoring:** Wazuh Rule 1001 → Discord Alerts → Splunk → iptables

## Demo Proof
![Wazuh Discord Alert](wazuh_discord_proof.png)

**Triggered:** 12 SSH brute force fails from TOR IP `185.230.122.10`
**Rule:** 1001 (5+ failed SSH logins)
**Cycle:** 5min automated alerts

## Tech Stack
