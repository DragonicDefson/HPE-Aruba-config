# HPE Aruba Config

A little configuration I wrote for an HPE Aruba Enterprise switch,
Decided to post it on GitHub for people bouncing their heads against HPE switches.

#### Important fixes (UPDATED AS OF 10/07/2022:1:19).

- Adds SNTP Support. (works after reboot, but you'll have to find a NTPS service for it, normally your ISP provides one).
- Disables Aruba Central.
- Disables Aruba software updates.
- Disables Aruba provisioning.
- Adds DNS server support with fallback DNS.
- Adds a Denial of Service filter.
- Minimum password length of 60 characters. (Which is for now enough, you can change it to your likings if you please to do so).
- Adds IPv6 support.
- Adds L4 load balancing.
- Adds security for all SNMP traps.
- Changes the default VLAN to a less widely known name.
- Masks the switch's hostname to a less recognizable name.

#### Explanatory information

- Tested on: HP 2530-48 Switch (J9781A)
