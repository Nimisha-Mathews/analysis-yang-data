# PLM Leaf Analysis Report (Enhanced)

## Executive Summary

This report identifies YANG modules/leafs in `Consolidated_PLM_Leaf_list.xlsx` that are **NOT** referenced
by leaf or leafref in `aruba-cx-device-configuration.yang`, along with customer usage data.

**Important:** This enhanced report traces each leaf to its **actual source YANG module** where it is defined,
rather than just the context module where it appears in the data tree.

### Key Findings

- **Total entries analyzed:** 2707
- **Referenced entries:** 1788 (66.1%)
- **Unreferenced entries:** 919 (33.9%)
- **Unique context modules (from Excel):** 87
- **Unique actual source modules:** 118

### Customer Impact Summary

| Metric | Count |
|--------|------:|
| Big Cluster Customers Affected | 2,921,293 |
| Small Cluster Customers Affected | 1,003,084 |
| **Total Customers Affected** | **3,924,377** |

---

## Top 50 Unreferenced Leafs in Device Configuration Profile

The following table shows individual leafs that are **NOT** referenced in `aruba-cx-device-configuration.yang`,
along with their **actual source module** (where the leaf is defined) and customer impact.

| Rank | Leaf Name | Actual Source Module | Big Cluster | Small Cluster | Total |
|-----:|-----------|---------------------|------------:|--------------:|------:|
| 1 | ethernet-interfaces.interface.name | aruba-aaa-via | 12,284 | 4,723 | 17,007 |
| 2 | ethernet-interfaces.interface.enable | aruba-aaa-lma | 10,512 | 4,716 | 15,228 |
| 3 | ethernet-interfaces.interface.switchport.interface-mode | aruba-interface-common | 10,276 | 4,673 | 14,949 |
| 4 | ethernet-interfaces.interface.switchport.access-vlan | aruba-interface-common | 9,950 | 4,352 | 14,302 |
| 5 | ethernet-interfaces.interface.switchport.native-vlan | aruba-interface-common | 8,663 | 3,848 | 12,511 |
| 6 | ethernet-interfaces.interface.description | aruba-aaa-via | 6,990 | 3,231 | 10,221 |
| 7 | ethernet-interfaces.interface.switchport.trunk-vlan-ranges | aruba-interface-common | 5,998 | 3,089 | 9,087 |
| 8 | stacks.stack.name | aruba-aaa-via | 5,701 | 3,022 | 8,723 |
| 9 | stacks.stack.members.id | aruba-uplink | 5,675 | 3,022 | 8,697 |
| 10 | stacks.stack.members.sku | aruba-device-info | 5,671 | 3,022 | 8,693 |
| 11 | ethernet-interfaces.interface.routing | aruba-interface-common | 5,652 | 3,035 | 8,687 |
| 12 | vsf-templates.template.name | aruba-aaa-via | 5,558 | 2,963 | 8,521 |
| 13 | vsf-templates.template.members.id | aruba-uplink | 5,501 | 2,944 | 8,445 |
| 14 | vsf-templates.template.members.sku | aruba-device-info | 5,501 | 2,944 | 8,445 |
| 15 | ethernet-interfaces.interface.switchport.trunk-vlan-all | aruba-interface-common | 6,163 | 2,277 | 8,440 |
| 16 | portchannels.interface.name | aruba-aaa-via | 4,237 | 2,130 | 6,367 |
| 17 | portchannels.interface.enable | aruba-aaa-lma | 4,223 | 2,126 | 6,349 |
| 18 | portchannels.interface.switchport.interface-mode | aruba-interface-common | 4,210 | 2,122 | 6,332 |
| 19 | portchannels.interface.port-list | aruba-snmp-trap | 4,052 | 2,059 | 6,111 |
| 20 | portchannels.interface.switchport.native-vlan | aruba-interface-common | 4,067 | 2,031 | 6,098 |
| 21 | ethernet-interfaces.interface.portchannel-lag | aruba-interface-ethernet | 4,041 | 2,028 | 6,069 |
| 22 | portchannels.interface.lacp.mode | aruba-uplink | 3,882 | 1,965 | 5,847 |
| 23 | portchannels.interface.trunk-type | aruba-interface-common | 3,881 | 1,966 | 5,847 |
| 24 | portchannels.interface.routing | aruba-interface-common | 3,413 | 1,815 | 5,228 |
| 25 | portchannels.interface.description | aruba-aaa-via | 3,508 | 1,691 | 5,199 |
| 26 | stacks.stack.members.links.link1.interfaces | aruba-ap-device-configuration | 3,227 | 1,643 | 4,870 |
| 27 | macauth.profile.name | aruba-aaa-via | 4,078 | 663 | 4,741 |
| 28 | dot1xauth.profile.name | aruba-aaa-via | 4,063 | 646 | 4,709 |
| 29 | stacks.stack.members.links.link2.interfaces | aruba-ap-device-configuration | 3,006 | 1,505 | 4,511 |
| 30 | portchannels.interface.switchport.trunk-vlan-ranges | aruba-interface-common | 3,006 | 1,441 | 4,447 |
| 31 | stacks.stack.secondary-member | aruba-switch-stack | 2,641 | 1,374 | 4,015 |
| 32 | vsf-templates.template.secondary-member | aruba-switch-stack | 2,641 | 1,374 | 4,015 |
| 33 | ethernet-interfaces.interface.loop-protect.enable | aruba-aaa-lma | 2,865 | 1,080 | 3,945 |
| 34 | portchannels.interface.switchport.trunk-vlan-all | aruba-interface-common | 2,371 | 1,263 | 3,634 |
| 35 | ethernet-interfaces.interface.stp.admin-edge-port | aruba-interface-common | 2,299 | 984 | 3,283 |
| 36 | ethernet-interfaces.interface.stp.bpdu-guard | aruba-interface-common | 2,112 | 841 | 2,953 |
| 37 | named-conditions.named-condition.condition-rule.position | aruba-policy-group | 2,372 | 353 | 2,725 |
| 38 | named-conditions.named-condition.name | aruba-aaa-via | 2,372 | 353 | 2,725 |
| 39 | dot1xauth.profile.enable | aruba-aaa-lma | 2,365 | 41 | 2,406 |
| 40 | macauth.profile.enable | aruba-aaa-lma | 2,365 | 39 | 2,404 |
| 41 | ethernet-interfaces.interface.mtu | aruba-interface-common | 1,418 | 680 | 2,098 |
| 42 | ethernet-interfaces.interface.aaa.authentication.mac-auth.enable | aruba-aaa-lma | 1,516 | 560 | 2,076 |
| 43 | layer2-vlan-range.enable | aruba-aaa-lma | 2,000 | 76 | 2,076 |
| 44 | ethernet-interfaces.interface.aaa.authentication.dot1x-auth.enable | aruba-aaa-lma | 1,506 | 563 | 2,069 |
| 45 | loop-protect.profile.name | aruba-aaa-via | 1,622 | 369 | 1,991 |
| 46 | ethernet-interfaces.interface.speed-duplex | aruba-interface-common | 1,356 | 624 | 1,980 |
| 47 | switch-profiles.profile.name | aruba-aaa-via | 1,161 | 705 | 1,866 |
| 48 | switch-profiles.profile.selected | aruba-switch-profiles | 1,161 | 705 | 1,866 |
| 49 | qos-dscp.profile.dscp-map.dscp | aruba-qos-dscp | 1,839 | 0 | 1,839 |
| 50 | qos-dscp.profile.name | aruba-aaa-via | 1,839 | 0 | 1,839 |

*Total unreferenced leafs: 979*

---

## Unreferenced Leafs by ACTUAL Source Module

This section shows where each leaf is **actually defined** in the YANG hierarchy,
tracing through `uses` statements and groupings.

| Rank | Actual Source Module | # of Leafs | Big Cluster | Small Cluster | Total Customers |
|-----:|----------------------|----------:|-----------:|--------------:|---------------:|
| 1 | aruba-interface-common | 122 | 765,425 | 267,472 | 1,032,897 |
| 2 | aruba-aaa-via-web | 78 | 574,037 | 189,352 | 763,389 |
| 3 | aruba-switch-stack | 19 | 379,240 | 127,612 | 506,852 |
| 4 | aruba-br-port-profile | 5 | 221,315 | 77,817 | 299,132 |
| 5 | aruba-device-properties | 19 | 171,239 | 57,798 | 229,037 |
| 6 | aruba-device-info | 4 | 167,096 | 56,188 | 223,284 |
| 7 | aruba-aaa-webauth | 16 | 71,458 | 17,103 | 88,561 |
| 8 | aruba-snmp-trap | 5 | 60,133 | 25,617 | 85,750 |
| 9 | aruba-interface-tunnel | 11 | 55,493 | 21,800 | 77,293 |
| 10 | aruba-interface-ethernet | 5 | 52,440 | 20,752 | 73,192 |
| 11 | aruba-aaa-macauth | 8 | 49,363 | 10,282 | 59,645 |
| 12 | aruba-dynamic-arp-inspection-interface | 14 | 35,266 | 9,003 | 44,269 |
| 13 | aruba-vsx-common | 27 | 25,013 | 13,721 | 38,734 |
| 14 | aruba-qos-cos | 3 | 25,615 | 0 | 25,615 |
| 15 | aruba-qos-schedule | 13 | 18,123 | 6,215 | 24,338 |
| 16 | aruba-inbound-firewall | 3 | 22,956 | 25 | 22,981 |
| 17 | aruba-interface-qos | 32 | 10,632 | 11,089 | 21,721 |
| 18 | aruba-mgmd-interface | 12 | 15,977 | 4,516 | 20,493 |
| 19 | aruba-qos-threshold-profile | 15 | 19,443 | 43 | 19,486 |
| 20 | aruba-aaa-dot1xauth | 8 | 15,544 | 3,731 | 19,275 |
| 21 | aruba-management-user-group | 8 | 12,388 | 6,736 | 19,124 |
| 22 | aruba-job-scheduler | 23 | 12,031 | 4,997 | 17,028 |
| 23 | aruba-wan-dps-policy | 3 | 10,930 | 4,099 | 15,029 |
| 24 | aruba-mirror-endpoint | 9 | 8,376 | 4,724 | 13,100 |
| 25 | aruba-cx-device-configuration | 4 | 8,086 | 3,256 | 11,342 |
| 26 | aruba-uplink | 9 | 8,001 | 2,840 | 10,841 |
| 27 | aruba-aaa-lma | 5 | 8,664 | 1,962 | 10,626 |
| 28 | aruba-aaa-via-connection | 9 | 7,829 | 2,732 | 10,561 |
| 29 | aruba-aaa-dot1xsupp | 2 | 7,860 | 2,010 | 9,870 |
| 30 | aruba-app-bandwidth-contract | 8 | 3,391 | 6,124 | 9,515 |
| ... | *(88 more modules)* | | | | |

---

## Unreferenced Entries by Context Module (from Excel)

This shows the grouping based on the Excel file's `Yang name` column (where the leaf appears in the data tree):

| Rank | Context Module | # of Leafs | Big Cluster | Small Cluster | Total Customers |
|-----:|----------------|----------:|-----------:|--------------:|---------------:|
| 1 | aruba-interface-ethernet | 202 | 1,260,220 | 424,600 | 1,684,820 |
| 2 | aruba-interface-portchannel | 94 | 483,433 | 192,296 | 675,729 |
| 3 | aruba-switch-stack | 11 | 423,626 | 141,878 | 565,504 |
| 4 | aruba-vsf-template | 5 | 278,951 | 92,092 | 371,043 |
| 5 | aruba-qos-dscp | 7 | 91,029 | 0 | 91,029 |
| 6 | aruba-loop-protect | 4 | 32,928 | 15,827 | 48,755 |
| 7 | aruba-aaa-macauth | 6 | 34,533 | 10,812 | 45,345 |
| 8 | aruba-aaa-dot1xauth | 12 | 33,538 | 10,353 | 43,891 |
| 9 | aruba-vsx | 16 | 24,615 | 13,817 | 38,432 |
| 10 | aruba-named-condition | 3 | 24,403 | 8,714 | 33,117 |
| 11 | aruba-vsx-pair | 17 | 20,736 | 11,379 | 32,115 |
| 12 | aruba-vlan-range | 14 | 21,258 | 6,018 | 27,276 |
| 13 | aruba-qos-schedule | 14 | 18,619 | 6,455 | 25,074 |
| 14 | aruba-job-scheduler | 27 | 15,374 | 6,543 | 21,917 |
| 15 | aruba-certificate-rcp | 6 | 15,647 | 3,506 | 19,153 |
| 16 | aruba-qos-queue | 6 | 13,595 | 3,628 | 17,223 |
| 17 | aruba-switch-profiles | 2 | 10,196 | 6,422 | 16,618 |
| 18 | aruba-object-group | 10 | 10,336 | 4,496 | 14,832 |
| 19 | aruba-port-security | 3 | 10,311 | 3,286 | 13,597 |
| 20 | aruba-lldp | 23 | 12,270 | 1,318 | 13,588 |
| 21 | aruba-snmp-trap | 3 | 7,526 | 5,288 | 12,814 |
| 22 | aruba-hardware-module-profile | 6 | 7,861 | 4,860 | 12,721 |
| 23 | aruba-interface-vxlan | 11 | 10,065 | 1,072 | 11,137 |
| 24 | aruba-system-info | 2 | 7,020 | 3,223 | 10,243 |
| 25 | aruba-device-certificate | 5 | 8,811 | 1,389 | 10,200 |
| 26 | aruba-ip-icmp-tcp | 1 | 9,008 | 0 | 9,008 |
| 27 | aruba-management-user-group | 6 | 5,959 | 2,561 | 8,520 |
| 28 | aruba-switch-chassis | 7 | 4,799 | 2,598 | 7,397 |
| 29 | aruba-copp | 4 | 3,258 | 2,259 | 5,517 |
| 30 | aruba-ipfix-flow-record | 25 | 1,853 | 1,787 | 3,640 |
| 31 | aruba-mgmd | 8 | 2,333 | 526 | 2,859 |
| 32 | aruba-cdp | 1 | 1,758 | 969 | 2,727 |
| 33 | aruba-aaa-captive-portal | 5 | 1,127 | 1,570 | 2,697 |
| 34 | aruba-ufd | 8 | 4 | 2,270 | 2,274 |
| 35 | aruba-nae-agent | 5 | 1,024 | 1,078 | 2,102 |
| 36 | aruba-l3-route | 3 | 1,842 | 12 | 1,854 |
| 37 | aruba-interface-tunnel | 12 | 951 | 347 | 1,298 |
| 38 | aruba-ipfix-flow-exporter | 9 | 623 | 654 | 1,277 |
| 39 | aruba-interface-vni | 6 | 0 | 1,256 | 1,256 |
| 40 | aruba-nae-script | 2 | 601 | 608 | 1,209 |
| 41 | aruba-interface-subinterface | 15 | 793 | 391 | 1,184 |
| 42 | aruba-ipfix-flow-monitor | 6 | 558 | 514 | 1,072 |
| 43 | aruba-nd-snooping-interface | 4 | 625 | 404 | 1,029 |
| 44 | aruba-role-gpid | 2 | 848 | 166 | 1,014 |
| 45 | aruba-nd-snooping | 3 | 534 | 410 | 944 |
| 46 | aruba-nexthop-group | 6 | 595 | 303 | 898 |
| 47 | aruba-erps | 21 | 746 | 76 | 822 |
| 48 | aruba-interface-vxlan-tunnel | 12 | 0 | 715 | 715 |
| 49 | aruba-keychain | 10 | 528 | 133 | 661 |
| 50 | aruba-traffic-insight | 10 | 399 | 209 | 608 |
| 51 | aruba-external-storage | 7 | 241 | 316 | 557 |
| 52 | aruba-ip-lockdown | 2 | 294 | 82 | 376 |
| 53 | aruba-dhcp-client | 3 | 226 | 74 | 300 |
| 54 | aruba-rip | 19 | 172 | 123 | 295 |
| 55 | aruba-ipsla | 18 | 188 | 106 | 294 |
| 56 | aruba-named-vlan | 1 | 266 | 20 | 286 |
| 57 | aruba-udp-broadcast-forwarder | 1 | 133 | 149 | 282 |
| 58 | aruba-rmon-alarm | 6 | 234 | 30 | 264 |
| 59 | aruba-firmware-management | 3 | 161 | 97 | 258 |
| 60 | aruba-mirror-endpoint | 7 | 145 | 109 | 254 |
| 61 | aruba-ptp | 6 | 153 | 87 | 240 |
| 62 | aruba-lacp | 2 | 130 | 100 | 230 |
| 63 | aruba-mka | 7 | 149 | 73 | 222 |
| 64 | aruba-mac-lockout | 2 | 125 | 79 | 204 |
| 65 | aruba-static-mac | 5 | 110 | 55 | 165 |
| 66 | aruba-qos-cos | 5 | 154 | 0 | 154 |
| 67 | aruba-ip-binding | 7 | 119 | 28 | 147 |
| 68 | aruba-macsec | 8 | 86 | 41 | 127 |
| 69 | aruba-nae-lite | 25 | 36 | 86 | 122 |
| 70 | aruba-mvrp | 1 | 103 | 4 | 107 |
| 71 | aruba-advanced-intelligent-forwarding | 4 | 101 | 2 | 103 |
| 72 | aruba-smartlink | 11 | 88 | 7 | 95 |
| 73 | aruba-psm | 2 | 38 | 48 | 86 |
| 74 | aruba-qos-threshold-profile | 13 | 14 | 43 | 57 |
| 75 | aruba-ip-routing | 5 | 18 | 33 | 51 |
| 76 | aruba-countermon | 2 | 16 | 34 | 50 |
| 77 | aruba-track-object | 1 | 4 | 42 | 46 |
| 78 | aruba-feature-pack | 4 | 14 | 32 | 46 |
| 79 | aruba-qos-pool | 6 | 42 | 0 | 42 |
| 80 | aruba-dhcp-snooping-interface | 4 | 8 | 33 | 41 |
| 81 | aruba-config-checkpoint | 3 | 24 | 8 | 32 |
| 82 | aruba-dsm | 4 | 12 | 20 | 32 |
| 83 | aruba-container | 12 | 12 | 9 | 21 |
| 84 | aruba-sysmon | 3 | 3 | 9 | 12 |
| 85 | aruba-dynamic-arp-inspection-interface | 2 | 4 | 6 | 10 |
| 86 | aruba-ip-lockdown-interface | 3 | 0 | 7 | 7 |
| 87 | aruba-container-network | 5 | 3 | 4 | 7 |

---

## Detailed Analysis: Context vs Actual Source

This section shows each context module and traces where its leafs are actually defined.

### aruba-interface-ethernet

- **Total Leafs in this context:** 202
- **Total Customer Impact:** 1,684,820

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-common | ethernet-interfaces.interface.switchport.native... | 129,706 | 45,045 | 174,751 |
| aruba-interface-common | ethernet-interfaces.interface.switchport.trunk-... | 95,978 | 28,887 | 124,865 |
| aruba-interface-common | ethernet-interfaces.interface.routing | 86,377 | 29,612 | 115,989 |
| aruba-interface-common | ethernet-interfaces.interface.switchport.trunk-... | 60,795 | 24,739 | 85,534 |
| aruba-interface-common | ethernet-interfaces.interface.stp.admin-edge-port | 43,951 | 14,984 | 58,935 |
| aruba-interface-common | ethernet-interfaces.interface.stp.bpdu-guard | 44,592 | 12,308 | 56,900 |
| aruba-interface-common | ethernet-interfaces.interface.stp.root-guard | 18,812 | 4,656 | 23,468 |
| aruba-interface-common | ethernet-interfaces.interface.speed-duplex | 16,914 | 2,227 | 19,141 |
| aruba-interface-common | ethernet-interfaces.interface.stp.tcn-guard | 11,255 | 3,987 | 15,242 |
| aruba-interface-common | ethernet-interfaces.interface.stp.bpdu-filter | 6,567 | 1,965 | 8,532 |
| aruba-interface-common | *... 58 more leafs* | | | |
| aruba-br-port-profile | ethernet-interfaces.interface.switchport.interf... | 163,908 | 56,173 | 220,081 |
| aruba-br-port-profile | ethernet-interfaces.interface.profile-name | 2,540 | 381 | 2,921 |
| aruba-aaa-via-web | ethernet-interfaces.interface.name | 164,744 | 56,704 | 221,448 |
| aruba-device-properties | ethernet-interfaces.interface.description | 123,000 | 40,028 | 163,028 |
| aruba-aaa-webauth | ethernet-interfaces.interface.aaa.authenticatio... | 28,233 | 7,068 | 35,301 |
| aruba-aaa-webauth | ethernet-interfaces.interface.aaa.authenticatio... | 8,649 | 1,690 | 10,339 |
| aruba-aaa-webauth | ethernet-interfaces.interface.aaa.authenticatio... | 7,852 | 1,796 | 9,648 |
| aruba-aaa-webauth | ethernet-interfaces.interface.aaa.authenticatio... | 7,448 | 1,450 | 8,898 |
| aruba-aaa-webauth | ethernet-interfaces.interface.aaa.authenticatio... | 5,792 | 1,723 | 7,515 |
| aruba-aaa-webauth | ethernet-interfaces.interface.aaa.authenticatio... | 5,569 | 1,092 | 6,661 |
| aruba-aaa-webauth | ethernet-interfaces.interface.port-security.cli... | 3,666 | 1,085 | 4,751 |
| aruba-aaa-webauth | ethernet-interfaces.interface.client-limit | 82 | 11 | 93 |
| aruba-interface-ethernet (same) | ethernet-interfaces.interface.portchannel-lag | 52,250 | 20,599 | 72,849 |
| aruba-interface-ethernet (same) | ethernet-interfaces.interface.split-port-enable | 79 | 62 | 141 |
| aruba-interface-ethernet (same) | ethernet-interfaces.interface.split-port-count | 76 | 62 | 138 |
| aruba-interface-ethernet (same) | ethernet-interfaces.interface.split-port-speed | 32 | 29 | 61 |
| aruba-interface-ethernet (same) | ethernet-interfaces.interface.ip-unnumbered-int... | 3 | 0 | 3 |
| aruba-aaa-macauth | ethernet-interfaces.interface.aaa.authenticatio... | 12,391 | 2,898 | 15,289 |
| aruba-aaa-macauth | ethernet-interfaces.interface.aaa.authenticatio... | 12,503 | 2,646 | 15,149 |
| aruba-aaa-macauth | ethernet-interfaces.interface.aaa.authenticatio... | 11,945 | 2,632 | 14,577 |
| aruba-aaa-macauth | ethernet-interfaces.interface.aaa.authenticatio... | 12,496 | 2,062 | 14,558 |
| aruba-dynamic-arp-inspection-interface | ethernet-interfaces.interface.dhcpv4-snooping.t... | 12,796 | 2,987 | 15,783 |
| aruba-dynamic-arp-inspection-interface | ethernet-interfaces.interface.qos.trust | 6,153 | 1,414 | 7,567 |
| aruba-dynamic-arp-inspection-interface | ethernet-interfaces.interface.dynamic-arp-inspe... | 2,100 | 468 | 2,568 |
| aruba-dynamic-arp-inspection-interface | ethernet-interfaces.interface.dhcpv6-snooping.t... | 705 | 357 | 1,062 |
| aruba-dynamic-arp-inspection-interface | ethernet-interfaces.interface.nd-snooping.trust | 291 | 202 | 493 |
| aruba-aaa-dot1xauth | ethernet-interfaces.interface.aaa.authenticatio... | 10,877 | 2,648 | 13,525 |
| aruba-aaa-dot1xauth | ethernet-interfaces.interface.aaa.authenticatio... | 3,121 | 345 | 3,466 |
| aruba-aaa-dot1xauth | ethernet-interfaces.interface.aaa.authenticatio... | 1,530 | 716 | 2,246 |
| aruba-aaa-dot1xauth | ethernet-interfaces.interface.aaa.authenticatio... | 4 | 0 | 4 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.broadcast-rat... | 3,116 | 2,586 | 5,702 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.multicast-rat... | 1,867 | 2,159 | 4,026 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.unknown-unica... | 466 | 1,176 | 1,642 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.broadcast-rat... | 1,095 | 417 | 1,512 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.multicast-rat... | 828 | 346 | 1,174 |
| aruba-interface-qos | ethernet-interfaces.interface.flow-control-mode | 386 | 490 | 876 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.icmp-rate-lim... | 342 | 133 | 475 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.icmp-rate-lim... | 342 | 133 | 475 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.unknown-unica... | 87 | 196 | 283 |
| aruba-interface-qos | ethernet-interfaces.interface.qos.schedule-profile | 44 | 237 | 281 |
| aruba-interface-qos | *... 8 more leafs* | | | |
| aruba-management-user-group | ethernet-interfaces.interface.loop-protect.action | 4,821 | 3,859 | 8,680 |
| aruba-management-user-group | ethernet-interfaces.interface.aaa.security-viol... | 3,251 | 534 | 3,785 |
| aruba-aaa-lma | ethernet-interfaces.interface.aaa.authenticatio... | 4,364 | 1,037 | 5,401 |
| aruba-aaa-lma | ethernet-interfaces.interface.aaa.authenticatio... | 4,121 | 905 | 5,026 |
| aruba-aaa-lma | ethernet-interfaces.interface.ipv6-neighbor-dis... | 1 | 0 | 1 |
| aruba-aaa-dot1xsupp | ethernet-interfaces.interface.aaa.authenticatio... | 7,853 | 2,000 | 9,853 |
| aruba-interface-tunnel | ethernet-interfaces.interface.mode | 5,736 | 1,681 | 7,417 |
| aruba-interface-tunnel | ethernet-interfaces.interface.lldp.mode | 616 | 1,466 | 2,082 |
| aruba-interface-tunnel | ethernet-interfaces.interface.cdp.mode | 60 | 23 | 83 |
| aruba-aaa-via-connection | ethernet-interfaces.interface.ipv4.address | 5,705 | 2,275 | 7,980 |
| aruba-aaa-via-connection | ethernet-interfaces.interface.ipv6.addresses.ad... | 18 | 12 | 30 |
| aruba-aaa-via-connection | ethernet-interfaces.interface.arp.neighbor.address | 10 | 0 | 10 |
| aruba-app-bandwidth-contract | ethernet-interfaces.interface.qos.broadcast-rat... | 1,759 | 1,686 | 3,445 |
| aruba-app-bandwidth-contract | ethernet-interfaces.interface.qos.multicast-rat... | 825 | 1,342 | 2,167 |
| aruba-app-bandwidth-contract | ethernet-interfaces.interface.qos.unknown-unica... | 326 | 872 | 1,198 |
| aruba-app-bandwidth-contract | ethernet-interfaces.interface.qos.icmp-rate-lim... | 288 | 120 | 408 |
| aruba-location | ethernet-interfaces.interface.switchport.tag | 1,945 | 1,475 | 3,420 |
| aruba-location | ethernet-interfaces.interface.udld.interval | 30 | 680 | 710 |
| aruba-qos-dscp | ethernet-interfaces.interface.poe.priority | 1,832 | 907 | 2,739 |
| aruba-qos-dscp | ethernet-interfaces.interface.stp.priority | 581 | 352 | 933 |
| aruba-qos-dscp | ethernet-interfaces.interface.priority-flow-con... | 8 | 7 | 15 |
| aruba-qos-dscp | ethernet-interfaces.interface.stp.rpvst.priority | 1 | 2 | 3 |
| aruba-qos-dscp | ethernet-interfaces.interface.stp.mstp.priority | 2 | 0 | 2 |
| aruba-qos-dscp | ethernet-interfaces.interface.lossless-buffer-b... | 0 | 1 | 1 |
| aruba-port-security | ethernet-interfaces.interface.port-security.sti... | 1,991 | 475 | 2,466 |
| aruba-port-security | ethernet-interfaces.interface.port-security.macs | 312 | 178 | 490 |
| aruba-aaa-bandwidth-contract | ethernet-interfaces.interface.qos.broadcast-rat... | 272 | 492 | 764 |
| aruba-aaa-bandwidth-contract | ethernet-interfaces.interface.qos.multicast-rat... | 215 | 480 | 695 |
| aruba-aaa-bandwidth-contract | ethernet-interfaces.interface.qos.unknown-unica... | 54 | 108 | 162 |
| aruba-aaa-bandwidth-contract | ethernet-interfaces.interface.qos.icmp-rate-lim... | 20 | 9 | 29 |
| aruba-nd-snooping-interface | ethernet-interfaces.interface.dhcpv4-snooping.m... | 1,339 | 42 | 1,381 |
| aruba-nd-snooping-interface | ethernet-interfaces.interface.dhcpv6-snooping.m... | 1 | 0 | 1 |
| aruba-nd-snooping-interface | ethernet-interfaces.interface.nd-snooping.max-b... | 1 | 0 | 1 |
| aruba-vlan-common | ethernet-interfaces.interface.policy.ipv4-acces... | 279 | 594 | 873 |
| aruba-vlan-common | ethernet-interfaces.interface.policy.ipv6-acces... | 83 | 141 | 224 |
| aruba-vlan-common | ethernet-interfaces.interface.policy.mac-access... | 76 | 49 | 125 |
| aruba-vlan-common | ethernet-interfaces.interface.policy.ipv4-acces... | 104 | 8 | 112 |
| aruba-vlan-common | ethernet-interfaces.interface.igmp.policy-in | 9 | 0 | 9 |
| aruba-vlan-common | ethernet-interfaces.interface.policy.ipv6-acces... | 4 | 0 | 4 |
| aruba-vlan-common | ethernet-interfaces.interface.policy.mac-access... | 1 | 0 | 1 |
| aruba-wlan-security | ethernet-interfaces.interface.aaa.authorization... | 790 | 397 | 1,187 |
| aruba-snmp-trap | ethernet-interfaces.interface.lldp.trap | 11 | 879 | 890 |
| aruba-snmp-trap | ethernet-interfaces.interface.loop-protect.trap | 0 | 0 | 0 |
| aruba-udld | ethernet-interfaces.interface.udld.retries | 42 | 701 | 743 |
| aruba-mgmd-interface | ethernet-interfaces.interface.igmp-snooping-eth... | 285 | 109 | 394 |
| aruba-mgmd-interface | ethernet-interfaces.interface.igmp-snooping-eth... | 76 | 20 | 96 |
| aruba-mgmd-interface | ethernet-interfaces.interface.igmp-snooping-eth... | 4 | 17 | 21 |
| aruba-mgmd-interface | ethernet-interfaces.interface.igmp.static-group | 10 | 3 | 13 |
| aruba-mgmd-interface | ethernet-interfaces.interface.igmp-snooping-eth... | 2 | 3 | 5 |
| aruba-mgmd-interface | ethernet-interfaces.interface.igmp.querier-enable | 3 | 0 | 3 |
| aruba-mgmd-interface | ethernet-interfaces.interface.mld-snooping-eth.... | 1 | 0 | 1 |
| aruba-pim-interface | ethernet-interfaces.interface.pim-sparse.source... | 144 | 0 | 144 |
| aruba-pim-interface | ethernet-interfaces.interface.pim-sparse.dr-pri... | 107 | 1 | 108 |
| aruba-pim-interface | ethernet-interfaces.interface.pim-sparse.hello-... | 83 | 0 | 83 |
| aruba-pim-interface | ethernet-interfaces.interface.pim-dense.source-... | 27 | 0 | 27 |
| aruba-pim-interface | ethernet-interfaces.interface.pim-sparse.datapa... | 2 | 0 | 2 |
| aruba-pim-interface | ethernet-interfaces.interface.pim-sparse.bsr-bo... | 1 | 0 | 1 |
| aruba-ipfix-flow-monitor | ethernet-interfaces.interface.ipfix-flow-monito... | 90 | 93 | 183 |
| aruba-ipfix-flow-monitor | ethernet-interfaces.interface.ipfix-flow-monito... | 0 | 1 | 1 |
| aruba-uplink | ethernet-interfaces.interface.port-security.sti... | 82 | 42 | 124 |
| aruba-uplink | ethernet-interfaces.interface.ptp.vlan | 3 | 0 | 3 |
| aruba-mac-lockout | ethernet-interfaces.interface.port-security.sti... | 82 | 42 | 124 |
| aruba-inbound-firewall | ethernet-interfaces.interface.qos.dscp | 100 | 22 | 122 |
| aruba-mgmd | ethernet-interfaces.interface.portfilter.eth-ports | 39 | 10 | 49 |
| aruba-mgmd | ethernet-interfaces.interface.portfilter.lag-ports | 39 | 10 | 49 |
| aruba-mgmd | ethernet-interfaces.interface.igmp.query-max-re... | 7 | 0 | 7 |
| aruba-mgmd | ethernet-interfaces.interface.igmp.robustness | 7 | 0 | 7 |
| aruba-mgmd | ethernet-interfaces.interface.igmp.last-member-... | 4 | 0 | 4 |
| aruba-mgmd | ethernet-interfaces.interface.igmp.strict-version | 1 | 0 | 1 |
| aruba-cellular | ethernet-interfaces.interface.qos.egress-rate | 41 | 18 | 59 |
| aruba-cellular | ethernet-interfaces.interface.qos.max-rate-units | 26 | 17 | 43 |
| aruba-ipsla | ethernet-interfaces.interface.igmp.version | 87 | 5 | 92 |
| aruba-vsx-common | ethernet-interfaces.interface.pim-sparse.hello-... | 85 | 0 | 85 |
| aruba-ap-uplink | ethernet-interfaces.interface.ipv4-relay.server.ip | 64 | 11 | 75 |
| aruba-ap-uplink | ethernet-interfaces.interface.udp-broadcast-for... | 0 | 0 | 0 |
| aruba-ap-uplink | ethernet-interfaces.interface.udp-broadcast-for... | 0 | 0 | 0 |
| aruba-hotspot2-anqp-ip-addr-avail | ethernet-interfaces.interface.ip-source-lockdow... | 11 | 34 | 45 |
| aruba-hotspot2-anqp-ip-addr-avail | ethernet-interfaces.interface.ip-source-lockdow... | 0 | 2 | 2 |
| aruba-nd-snooping | ethernet-interfaces.interface.nd-snooping.ra-gu... | 41 | 0 | 41 |
| aruba-airgroup-system | ethernet-interfaces.interface.igmp.query-interval | 20 | 0 | 20 |
| aruba-net-service | ethernet-interfaces.interface.arp.timeout | 4 | 1 | 5 |
| aruba-router-discovery | ethernet-interfaces.interface.ipv6-neighbor-dis... | 0 | 2 | 2 |
| aruba-router-discovery | ethernet-interfaces.interface.ipv6-neighbor-dis... | 0 | 2 | 2 |
| aruba-router-discovery | ethernet-interfaces.interface.ipv6-neighbor-dis... | 1 | 0 | 1 |
| aruba-wan-dps-policy | ethernet-interfaces.interface.qos.threshold-pro... | 1 | 2 | 3 |
| aruba-loop-protect | ethernet-interfaces.interface.loop-protect.tran... | 0 | 0 | 0 |

### aruba-interface-portchannel

- **Total Leafs in this context:** 94
- **Total Customer Impact:** 675,729

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-common | portchannels.interface.switchport.native-vlan | 54,222 | 20,767 | 74,989 |
| aruba-interface-common | portchannels.interface.trunk-type | 46,967 | 18,293 | 65,260 |
| aruba-interface-common | portchannels.interface.routing | 41,563 | 15,842 | 57,405 |
| aruba-interface-common | portchannels.interface.switchport.trunk-vlan-all | 36,962 | 12,319 | 49,281 |
| aruba-interface-common | portchannels.interface.switchport.trunk-vlan-ra... | 20,682 | 10,378 | 31,060 |
| aruba-interface-common | portchannels.interface.stp.loop-guard | 2,402 | 1,236 | 3,638 |
| aruba-interface-common | portchannels.interface.stp.root-guard | 1,204 | 662 | 1,866 |
| aruba-interface-common | portchannels.interface.stp.bpdu-filter | 844 | 321 | 1,165 |
| aruba-interface-common | portchannels.interface.stp.admin-edge-port | 621 | 309 | 930 |
| aruba-interface-common | portchannels.interface.stp.link-type | 820 | 59 | 879 |
| aruba-interface-common | *... 24 more leafs* | | | |
| aruba-aaa-via-web | portchannels.interface.name | 54,775 | 21,239 | 76,014 |
| aruba-br-port-profile | portchannels.interface.switchport.interface-mode | 54,723 | 21,189 | 75,912 |
| aruba-br-port-profile | portchannels.interface.profile-name | 4 | 28 | 32 |
| aruba-snmp-trap | portchannels.interface.port-list | 52,251 | 20,639 | 72,890 |
| aruba-interface-tunnel | portchannels.interface.lacp.mode | 46,966 | 18,289 | 65,255 |
| aruba-interface-tunnel | portchannels.interface.mode | 1,692 | 107 | 1,799 |
| aruba-device-properties | portchannels.interface.description | 44,587 | 16,254 | 60,841 |
| aruba-dynamic-arp-inspection-interface | portchannels.interface.dhcpv4-snooping.trust | 8,430 | 2,347 | 10,777 |
| aruba-dynamic-arp-inspection-interface | portchannels.interface.qos.trust | 2,130 | 301 | 2,431 |
| aruba-dynamic-arp-inspection-interface | portchannels.interface.dynamic-arp-inspection.t... | 1,413 | 503 | 1,916 |
| aruba-dynamic-arp-inspection-interface | portchannels.interface.dhcpv6-snooping.trust | 724 | 174 | 898 |
| aruba-dynamic-arp-inspection-interface | portchannels.interface.nd-snooping.trust | 227 | 29 | 256 |
| aruba-firewall | portchannels.interface.lacp.rate | 2,708 | 2,284 | 4,992 |
| aruba-location | portchannels.interface.switchport.tag | 2,939 | 1,434 | 4,373 |
| aruba-interface-qos | portchannels.interface.qos.broadcast-rate-limit... | 366 | 1,147 | 1,513 |
| aruba-interface-qos | portchannels.interface.qos.multicast-rate-limit... | 160 | 1,086 | 1,246 |
| aruba-interface-qos | portchannels.interface.qos.broadcast-rate-limit... | 191 | 161 | 352 |
| aruba-interface-qos | portchannels.interface.qos.unknown-unicast-rate... | 41 | 291 | 332 |
| aruba-interface-qos | portchannels.interface.qos.multicast-rate-limit... | 116 | 116 | 232 |
| aruba-interface-qos | portchannels.interface.qos.schedule-profile | 7 | 181 | 188 |
| aruba-interface-qos | portchannels.interface.qos.icmp-rate-limit.icmp... | 7 | 78 | 85 |
| aruba-interface-qos | portchannels.interface.qos.icmp-rate-limit.rate... | 7 | 78 | 85 |
| aruba-interface-qos | portchannels.interface.qos.unknown-unicast-rate... | 21 | 53 | 74 |
| aruba-interface-qos | portchannels.interface.qos.icmp-rate-limit.pack... | 1 | 3 | 4 |
| aruba-interface-qos | *... 1 more leafs* | | | |
| aruba-app-bandwidth-contract | portchannels.interface.qos.broadcast-rate-limit... | 151 | 959 | 1,110 |
| aruba-app-bandwidth-contract | portchannels.interface.qos.multicast-rate-limit... | 27 | 889 | 916 |
| aruba-app-bandwidth-contract | portchannels.interface.qos.unknown-unicast-rate... | 11 | 181 | 192 |
| aruba-app-bandwidth-contract | portchannels.interface.qos.icmp-rate-limit.bit-... | 4 | 75 | 79 |
| aruba-management-user-group | portchannels.interface.loop-protect.action | 244 | 579 | 823 |
| aruba-management-user-group | portchannels.interface.aaa-lag.security-violati... | 0 | 0 | 0 |
| aruba-aaa-via-connection | portchannels.interface.ipv4.address | 320 | 192 | 512 |
| aruba-aaa-via-connection | portchannels.interface.ipv6.addresses.address | 6 | 1 | 7 |
| aruba-aaa-bandwidth-contract | portchannels.interface.qos.multicast-rate-limit... | 17 | 81 | 98 |
| aruba-aaa-bandwidth-contract | portchannels.interface.qos.unknown-unicast-rate... | 9 | 57 | 66 |
| aruba-aaa-bandwidth-contract | portchannels.interface.qos.broadcast-rate-limit... | 24 | 28 | 52 |
| aruba-aaa-bandwidth-contract | portchannels.interface.qos.icmp-rate-limit.perc... | 2 | 0 | 2 |
| aruba-aaa-webauth | portchannels.interface.client-limit | 130 | 41 | 171 |
| aruba-aaa-webauth | portchannels.interface.aaa-lag.authentication-l... | 13 | 5 | 18 |
| aruba-vlan-common | portchannels.interface.policy.ipv4-access-list-in | 47 | 29 | 76 |
| aruba-vlan-common | portchannels.interface.policy.ipv6-access-list-out | 0 | 47 | 47 |
| aruba-vlan-common | portchannels.interface.policy.ipv4-access-list-out | 34 | 6 | 40 |
| aruba-vlan-common | portchannels.interface.policy.mac-access-list-in | 0 | 16 | 16 |
| aruba-vlan-common | portchannels.interface.policy.ipv6-access-list-in | 2 | 1 | 3 |
| aruba-qos-dscp | portchannels.interface.stp.priority | 126 | 15 | 141 |
| aruba-qos-dscp | portchannels.interface.stp.rpvst.priority | 0 | 2 | 2 |
| aruba-qos-dscp | portchannels.interface.stp.mstp.priority | 1 | 0 | 1 |
| aruba-ipfix-flow-monitor | portchannels.interface.ipfix-flow-monitor-in.ip... | 11 | 39 | 50 |
| aruba-ipfix-flow-monitor | portchannels.interface.ipfix-flow-monitor-in.ip... | 0 | 1 | 1 |
| aruba-mgmd-interface | portchannels.interface.igmp-snooping-lag.forwar... | 25 | 20 | 45 |
| aruba-mgmd-interface | portchannels.interface.igmp-snooping-lag.blocke... | 5 | 0 | 5 |
| aruba-cellular | portchannels.interface.qos.egress-rate | 0 | 2 | 2 |
| aruba-cellular | portchannels.interface.qos.max-rate-units | 0 | 2 | 2 |
| aruba-inbound-firewall | portchannels.interface.qos.dscp | 0 | 3 | 3 |
| aruba-pim-interface | portchannels.interface.pim-sparse.source-addres... | 0 | 3 | 3 |
| aruba-mgmd | portchannels.interface.portfilter.eth-ports | 1 | 0 | 1 |
| aruba-mgmd | portchannels.interface.portfilter.lag-ports | 1 | 0 | 1 |
| aruba-nd-snooping-interface | portchannels.interface.nd-snooping.max-bindings | 1 | 0 | 1 |
| aruba-net-service | portchannels.interface.arp.timeout | 0 | 0 | 0 |
| aruba-wan-dps-policy | portchannels.interface.qos.threshold-profile | 0 | 0 | 0 |

### aruba-switch-stack

- **Total Leafs in this context:** 11
- **Total Customer Impact:** 565,504

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-switch-stack (same) | stacks.stack.members.id | 82,414 | 27,663 | 110,077 |
| aruba-switch-stack (same) | stacks.stack.platform | 82,414 | 27,663 | 110,077 |
| aruba-switch-stack (same) | stacks.stack.members.links.link1.interfaces | 31,623 | 10,851 | 42,474 |
| aruba-switch-stack (same) | stacks.stack.members.links.link2.interfaces | 29,470 | 9,810 | 39,280 |
| aruba-switch-stack (same) | stacks.stack.secondary-member | 25,713 | 8,971 | 34,684 |
| aruba-switch-stack (same) | stacks.stack.split-detection-method | 6,368 | 1,403 | 7,771 |
| aruba-switch-stack (same) | stacks.stack.members.hw-profile | 451 | 0 | 451 |
| aruba-aaa-via-web | stacks.stack.name | 82,414 | 27,664 | 110,078 |
| aruba-device-info | stacks.stack.members.sku | 82,414 | 27,663 | 110,077 |
| aruba-device-properties | stacks.stack.members.links.link1.description | 182 | 104 | 286 |
| aruba-device-properties | stacks.stack.members.links.link2.description | 163 | 86 | 249 |

### aruba-vsf-template

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 371,043

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-switch-stack | vsf-templates.template.members.id | 82,290 | 27,226 | 109,516 |
| aruba-switch-stack | vsf-templates.template.secondary-member | 25,713 | 8,973 | 34,686 |
| aruba-switch-stack | vsf-templates.template.split-detection-method | 6,368 | 1,403 | 7,771 |
| aruba-aaa-via-web | vsf-templates.template.name | 82,290 | 27,264 | 109,554 |
| aruba-device-info | vsf-templates.template.members.sku | 82,290 | 27,226 | 109,516 |

### aruba-qos-dscp

- **Total Leafs in this context:** 7
- **Total Customer Impact:** 91,029

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | qos-dscp.profile.name | 22,856 | 0 | 22,856 |
| aruba-aaa-via-web | qos-dscp.profile.dscp-map.name | 2,957 | 0 | 2,957 |
| aruba-inbound-firewall | qos-dscp.profile.dscp-map.dscp | 22,856 | 0 | 22,856 |
| aruba-qos-cos | qos-dscp.profile.dscp-map.local-priority | 22,223 | 0 | 22,223 |
| aruba-qos-threshold-profile | qos-dscp.profile.dscp-map.color | 19,391 | 0 | 19,391 |
| aruba-interface-qos | qos-dscp.profile.dscp-map.cos | 633 | 0 | 633 |
| aruba-qos-dscp (same) | qos-dscp.profile.dscp-map.cos-override | 113 | 0 | 113 |

### aruba-loop-protect

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 48,755

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | loop-protect.profile.name | 14,648 | 6,232 | 20,880 |
| aruba-interface-common | loop-protect.profile.re-enable-timer | 11,211 | 5,080 | 16,291 |
| aruba-snmp-trap | loop-protect.profile.trap | 6,137 | 2,741 | 8,878 |
| aruba-loop-protect (same) | loop-protect.profile.transmit-interval | 932 | 1,774 | 2,706 |

### aruba-aaa-macauth

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 45,345

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | macauth.profile.name | 34,254 | 10,761 | 45,015 |
| aruba-aaa-webauth | macauth.profile.reauth-period | 88 | 10 | 98 |
| aruba-aaa-webauth | macauth.profile.cached-reauth-period | 88 | 10 | 98 |
| aruba-aaa-lma | macauth.profile.quiet-period | 89 | 10 | 99 |
| aruba-aaa-macauth (same) | macauth.profile.reauth-enable | 8 | 10 | 18 |
| aruba-aaa-macauth (same) | macauth.profile.cached-reauth-enable | 6 | 11 | 17 |

### aruba-aaa-dot1xauth

- **Total Leafs in this context:** 12
- **Total Customer Impact:** 43,891

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | dot1xauth.profile.name | 33,234 | 10,255 | 43,489 |
| aruba-aaa-webauth | dot1xauth.profile.reauth-period | 88 | 11 | 99 |
| aruba-aaa-webauth | dot1xauth.profile.cached-reauth-period | 88 | 10 | 98 |
| aruba-aaa-webauth | dot1xauth.profile.max-retries | 6 | 12 | 18 |
| aruba-aaa-lma | dot1xauth.profile.quiet-period | 89 | 10 | 99 |
| aruba-aaa-macauth | dot1xauth.profile.reauth-enable | 8 | 12 | 20 |
| aruba-aaa-macauth | dot1xauth.profile.cached-reauth-enable | 6 | 11 | 17 |
| aruba-aaa-dot1xauth (same) | dot1xauth.profile.eapol-max-requests | 9 | 15 | 24 |
| aruba-aaa-dot1xauth (same) | dot1xauth.profile.discovery-period | 2 | 4 | 6 |
| aruba-aaa-dot1xauth (same) | dot1xauth.profile.initial-auth-response-timeout | 0 | 3 | 3 |
| aruba-aaa-dot1xauth (same) | dot1xauth.profile.canned-eap-success-enable | 1 | 0 | 1 |
| aruba-aaa-dot1xsupp | dot1xauth.profile.eapol-timeout | 7 | 10 | 17 |

### aruba-vsx

- **Total Leafs in this context:** 16
- **Total Customer Impact:** 38,432

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-vsx-common | vsx-profiles.vsx.peer1.role | 3,216 | 1,803 | 5,019 |
| aruba-vsx-common | vsx-profiles.vsx.peer2.role | 3,216 | 1,803 | 5,019 |
| aruba-vsx-common | vsx-profiles.vsx.peer1.keepalive-device.peer-ip | 2,869 | 1,639 | 4,508 |
| aruba-vsx-common | vsx-profiles.vsx.peer2.keepalive-device.peer-ip | 2,869 | 1,639 | 4,508 |
| aruba-vsx-common | vsx-profiles.vsx.sync-features.system-mac | 2,768 | 1,492 | 4,260 |
| aruba-vsx-common | vsx-profiles.vsx.sync-features.linkup-delay-timer | 471 | 241 | 712 |
| aruba-vsx-common | vsx-profiles.vsx.sync-features.split-recovery-d... | 70 | 29 | 99 |
| aruba-vsx-common | vsx-profiles.vsx.sync-features.inter-switch-lin... | 57 | 26 | 83 |
| aruba-vsx-common | vsx-profiles.vsx.sync-features.inter-switch-lin... | 55 | 26 | 81 |
| aruba-vsx-common | vsx-profiles.vsx.sync-features.inter-switch-lin... | 43 | 8 | 51 |
| aruba-vsx-common | *... 3 more leafs* | | | |
| aruba-mirror-endpoint | vsx-profiles.vsx.peer1.keepalive-device.source-ip | 2,869 | 1,639 | 4,508 |
| aruba-mirror-endpoint | vsx-profiles.vsx.peer2.keepalive-device.source-ip | 2,869 | 1,639 | 4,508 |
| aruba-aaa-via-web | vsx-profiles.vsx.name | 3,216 | 1,821 | 5,037 |

### aruba-named-condition

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 33,117

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-wan-dps-policy | named-conditions.named-condition.condition-rule... | 10,929 | 4,097 | 15,026 |
| aruba-aaa-via-web | named-conditions.named-condition.name | 10,929 | 4,097 | 15,026 |
| aruba-device-properties | named-conditions.named-condition.condition-rule... | 2,545 | 520 | 3,065 |

### aruba-vsx-pair

- **Total Leafs in this context:** 17
- **Total Customer Impact:** 32,115

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-vsx-common | vsx-config.vsx.role | 3,216 | 1,803 | 5,019 |
| aruba-vsx-common | vsx-config.vsx.system-mac | 2,768 | 1,492 | 4,260 |
| aruba-vsx-common | vsx-config.vsx.keepalive.peer-ip | 2,532 | 1,363 | 3,895 |
| aruba-vsx-common | vsx-config.vsx.linkup-delay-timer | 471 | 241 | 712 |
| aruba-vsx-common | vsx-config.vsx.split-recovery-disable | 70 | 29 | 99 |
| aruba-vsx-common | vsx-config.vsx.inter-switch-link.dead-interval | 57 | 26 | 83 |
| aruba-vsx-common | vsx-config.vsx.inter-switch-link.hello-interval | 55 | 26 | 81 |
| aruba-vsx-common | vsx-config.vsx.inter-switch-link.peer-detect-in... | 43 | 8 | 51 |
| aruba-vsx-common | vsx-config.vsx.keepalive.dead-interval | 10 | 8 | 18 |
| aruba-vsx-common | vsx-config.vsx.keepalive.hello-interval | 9 | 4 | 13 |
| aruba-vsx-common | *... 1 more leafs* | | | |
| aruba-aaa-via-web | vsx-config.vsx.name | 3,216 | 1,828 | 5,044 |
| aruba-ip-binding | vsx-config.vsx.inter-switch-link.interface-lag | 3,194 | 1,809 | 5,003 |
| aruba-vsx-pair (same) | vsx-config.vsx.keepalive.vrf-ref | 2,532 | 1,363 | 3,895 |
| aruba-vsx-pair (same) | vsx-config.vsx.inter-switch-link.interface-eth | 17 | 15 | 32 |
| aruba-vsx-pair (same) | vsx-config.vsx.linkup-delay-timer-exclude | 6 | 1 | 7 |
| aruba-mirror-endpoint | vsx-config.vsx.keepalive.source-ip | 2,532 | 1,363 | 3,895 |

### aruba-vlan-range

- **Total Leafs in this context:** 14
- **Total Customer Impact:** 27,276

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-mgmd-interface | layer2-vlan-range.igmp.snooping | 15,311 | 4,317 | 19,628 |
| aruba-mgmd-interface | layer2-vlan-range.mld.snooping | 152 | 21 | 173 |
| aruba-mgmd-interface | layer2-vlan-range.igmp.static-group | 103 | 6 | 109 |
| aruba-ipsla | layer2-vlan-range.igmp.version | 4,883 | 1,435 | 6,318 |
| aruba-vlan-common | layer2-vlan-range.igmp.policy-in | 464 | 1 | 465 |
| aruba-vlan-common | layer2-vlan-range.policy-in | 63 | 180 | 243 |
| aruba-vlan-common | layer2-vlan-range.policy-out | 65 | 4 | 69 |
| aruba-vlan-common | layer2-vlan-range.voice-enable | 6 | 0 | 6 |
| aruba-mgmd | layer2-vlan-range.igmp.preprogram-starg-flow | 125 | 26 | 151 |
| aruba-nd-snooping | layer2-vlan-range.nd-snooping.nd-guard | 43 | 4 | 47 |
| aruba-nd-snooping | layer2-vlan-range.nd-snooping.ra-drop | 27 | 1 | 28 |
| aruba-nd-snooping | layer2-vlan-range.nd-snooping.ra-guard-log | 16 | 9 | 25 |
| aruba-nd-snooping | layer2-vlan-range.nd-snooping.allow-bindings-on... | 0 | 10 | 10 |
| aruba-nd-snooping | layer2-vlan-range.dhcpv6-snooping.allow-binding... | 0 | 4 | 4 |

### aruba-qos-schedule

- **Total Leafs in this context:** 14
- **Total Customer Impact:** 25,074

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-qos-schedule (same) | qos-schedules.profile.sched-profile-name | 4,708 | 1,639 | 6,347 |
| aruba-qos-schedule (same) | qos-schedules.profile.strict.queue | 4,611 | 0 | 4,611 |
| aruba-qos-schedule (same) | qos-schedules.profile.dwrr.queue | 4,260 | 0 | 4,260 |
| aruba-qos-schedule (same) | qos-schedules.profile.sched-entries.algorithm | 0 | 1,610 | 1,610 |
| aruba-qos-schedule (same) | qos-schedules.profile.sched-entries.queue | 0 | 1,610 | 1,610 |
| aruba-qos-schedule (same) | qos-schedules.profile.min-bandwidths.minimum-ba... | 377 | 0 | 377 |
| aruba-qos-schedule (same) | qos-schedules.profile.min-bandwidths.queue | 377 | 0 | 377 |
| aruba-qos-schedule (same) | qos-schedules.profile.sched-entries.minimum-ban... | 0 | 253 | 253 |
| aruba-qos-schedule (same) | qos-schedules.profile.sched-entries.max-bandwid... | 0 | 48 | 48 |
| aruba-qos-schedule (same) | qos-schedules.profile.sched-entries.max-bandwid... | 0 | 47 | 47 |
| aruba-qos-schedule | *... 2 more leafs* | | | |
| aruba-uplink | qos-schedules.profile.dwrr.weight | 4,260 | 0 | 4,260 |
| aruba-uplink | qos-schedules.profile.sched-entries.weight | 0 | 1,248 | 1,248 |

### aruba-job-scheduler

- **Total Leafs in this context:** 27
- **Total Customer Impact:** 21,917

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-job-scheduler (same) | job-scheduler.schedule.job.job-name | 1,495 | 555 | 2,050 |
| aruba-job-scheduler (same) | job-scheduler.schedule.job.entry.cli-command | 1,458 | 542 | 2,000 |
| aruba-job-scheduler (same) | job-scheduler.schedule.trigger-type | 1,424 | 525 | 1,949 |
| aruba-job-scheduler (same) | job-scheduler.schedule.schedule-entry.schedule-job | 1,407 | 520 | 1,927 |
| aruba-job-scheduler (same) | job-scheduler.schedule.frequency | 669 | 337 | 1,006 |
| aruba-job-scheduler (same) | job-scheduler.schedule.start-time-on | 669 | 337 | 1,006 |
| aruba-job-scheduler (same) | job-scheduler.schedule.trigger-on | 669 | 337 | 1,006 |
| aruba-job-scheduler (same) | job-scheduler.schedule.start-date-on | 669 | 333 | 1,002 |
| aruba-job-scheduler (same) | job-scheduler.schedule.start-date-at | 786 | 77 | 863 |
| aruba-job-scheduler (same) | job-scheduler.schedule.start-time-at | 786 | 77 | 863 |
| aruba-job-scheduler | *... 12 more leafs* | | | |
| aruba-aaa-via-web | job-scheduler.schedule.name | 1,510 | 562 | 2,072 |
| aruba-feature-pack | job-scheduler.schedule.job.entry.type | 1,458 | 542 | 2,000 |
| aruba-device-properties | job-scheduler.schedule.description | 159 | 266 | 425 |
| aruba-device-properties | job-scheduler.schedule.job.description | 183 | 175 | 358 |
| aruba-ipsla | job-scheduler.schedule.count | 57 | 12 | 69 |

### aruba-certificate-rcp

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 19,153

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | certificate-rcp.ta-profile.name | 15,530 | 3,473 | 19,003 |
| aruba-certificate-rcp (same) | certificate-rcp.ta-profile.ocsp.enforcement-level | 105 | 13 | 118 |
| aruba-certificate-rcp (same) | certificate-rcp.ta-profile.rcp-primary-method | 0 | 16 | 16 |
| aruba-certificate-rcp (same) | certificate-rcp.ta-profile.ocsp.disable-nonce | 12 | 1 | 13 |
| aruba-certificate-rcp (same) | certificate-rcp.ta-profile.ocsp.primary-url | 0 | 2 | 2 |
| aruba-certificate-rcp (same) | certificate-rcp.ta-profile.ocsp.secondary-url | 0 | 1 | 1 |

### aruba-qos-queue

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 17,223

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-qos-queue (same) | qos-queues.profile.q-profile-name | 3,939 | 1,150 | 5,089 |
| aruba-qos-queue (same) | qos-queues.profile.priority.priorities | 0 | 998 | 998 |
| aruba-qos-schedule | qos-queues.profile.priority.queue | 3,764 | 1,008 | 4,772 |
| aruba-qos-cos | qos-queues.profile.priority.local-priority | 3,354 | 0 | 3,354 |
| aruba-aaa-via-web | qos-queues.profile.priority.name | 2,198 | 472 | 2,670 |
| aruba-interface-qos | qos-queues.profile.priority.cos | 340 | 0 | 340 |

### aruba-switch-profiles

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 16,618

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | switch-profiles.profile.name | 5,098 | 3,211 | 8,309 |
| aruba-switch-profiles (same) | switch-profiles.profile.selected | 5,098 | 3,211 | 8,309 |

### aruba-object-group

- **Total Leafs in this context:** 10
- **Total Customer Impact:** 14,832

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | object-groups.group.name | 1,781 | 718 | 2,499 |
| aruba-feature-pack | object-groups.group.type | 1,781 | 718 | 2,499 |
| aruba-dpi-error-page-url | object-groups.group.items.index | 1,781 | 718 | 2,499 |
| aruba-role-acl | object-groups.group.items.address-type | 1,532 | 699 | 2,231 |
| aruba-ip-authorized-manager | object-groups.group.items.ipv4-address | 1,273 | 656 | 1,929 |
| aruba-object-group (same) | object-groups.group.items.ipv4-subnet-address | 1,108 | 564 | 1,672 |
| aruba-object-group (same) | object-groups.group.items.ports.max | 78 | 93 | 171 |
| aruba-object-group (same) | object-groups.group.items.ipv4-prefix | 0 | 0 | 0 |
| aruba-policy-condition | object-groups.group.items.ports.operator | 649 | 165 | 814 |
| aruba-device-constraints | object-groups.group.items.ports.min | 353 | 165 | 518 |

### aruba-port-security

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 13,597

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | port-security.policy.name | 4,654 | 1,719 | 6,373 |
| aruba-aaa-webauth | port-security.policy.client-limit | 3,666 | 1,089 | 4,755 |
| aruba-port-security (same) | port-security.policy.sticky-mac-enable | 1,991 | 478 | 2,469 |

### aruba-lldp

- **Total Leafs in this context:** 23
- **Total Customer Impact:** 13,588

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-common | lldp.profile.tlv.basic.port-descr | 1,047 | 133 | 1,180 |
| aruba-interface-common | lldp.profile.tlv.basic.management-addr | 1,022 | 2 | 1,024 |
| aruba-interface-common | lldp.profile.tlv.basic.system-descr | 1,021 | 2 | 1,023 |
| aruba-interface-common | lldp.profile.tlv.dot1.port-vlan-id | 1,019 | 2 | 1,021 |
| aruba-interface-common | lldp.profile.tlv.dot1.port-vlan-name | 1,008 | 2 | 1,010 |
| aruba-interface-common | lldp.profile.tlv.basic.system-cap | 831 | 2 | 833 |
| aruba-interface-common | lldp.profile.dcbx-version | 1 | 9 | 10 |
| aruba-aaa-via-web | lldp.profile.name | 2,929 | 653 | 3,582 |
| aruba-lldp (same) | lldp.profile.tlv.oui | 941 | 2 | 943 |
| aruba-lldp (same) | lldp.profile.lldp-trap-enable | 715 | 217 | 932 |
| aruba-lldp (same) | lldp.profile.tlv.dot1.link-aggregation | 923 | 2 | 925 |
| aruba-lldp (same) | lldp.profile.management-ip-address | 303 | 156 | 459 |
| aruba-lldp (same) | lldp.profile.reinit-delay | 37 | 14 | 51 |
| aruba-lldp (same) | lldp.profile.dcbx-enable | 20 | 20 | 40 |
| aruba-lldp (same) | lldp.profile.management-vlan | 10 | 29 | 39 |
| aruba-lldp (same) | lldp.profile.hold-multiplier | 14 | 2 | 16 |
| aruba-lldp (same) | lldp.profile.tlv-dcbx-app.app-tlv.protocol-port... | 3 | 8 | 11 |
| aruba-lldp (same) | lldp.profile.neighbor-last-update-enable | 1 | 3 | 4 |
| aruba-lldp | *... 1 more leafs* | | | |
| aruba-loop-protect | lldp.profile.transmit-interval | 415 | 36 | 451 |
| aruba-gw-idps | lldp.profile.tlv-dcbx-app.app-tlv.port-number | 3 | 8 | 11 |
| aruba-qos-dscp | lldp.profile.tlv-dcbx-app.app-tlv.priority | 3 | 8 | 11 |
| aruba-policy-condition | lldp.profile.tlv-dcbx-app.app-tlv.protocol | 3 | 8 | 11 |

### aruba-snmp-trap

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 12,814

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | snmp-trap.profile.name | 2,896 | 1,965 | 4,861 |
| aruba-switch-stack | snmp-trap.profile.trap.id | 2,896 | 1,965 | 4,861 |
| aruba-snmp-trap (same) | snmp-trap.profile.trap.snmp-server-trap | 1,734 | 1,358 | 3,092 |

### aruba-hardware-module-profile

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 12,721

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | hardware-modules.hw-profile.name | 2,980 | 1,494 | 4,474 |
| aruba-smartlink | hardware-modules.hw-profile.interface-group-spe... | 1,825 | 1,153 | 2,978 |
| aruba-uplink | hardware-modules.hw-profile.interface-group-spe... | 1,825 | 1,153 | 2,978 |
| aruba-hardware-module-common | hardware-modules.hw-profile.always-on-poe | 1,081 | 324 | 1,405 |
| aruba-hardware-module-common | hardware-modules.hw-profile.quick-poe | 150 | 245 | 395 |
| aruba-hardware-module-profile (same) | hardware-modules.hw-profile.member-or-slot-ids | 0 | 491 | 491 |

### aruba-interface-vxlan

- **Total Leafs in this context:** 11
- **Total Customer Impact:** 11,137

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-vxlan-tunnel | vxlan.profile.src-ipv4 | 2,128 | 234 | 2,362 |
| aruba-interface-vxlan-tunnel | vxlan.profile.enable-counters | 65 | 18 | 83 |
| aruba-interface-vxlan-tunnel | vxlan.profile.bridging-mode | 59 | 15 | 74 |
| aruba-interface-vxlan-tunnel | vxlan.profile.loop-protect-vlans | 0 | 7 | 7 |
| aruba-interface-vxlan-tunnel | vxlan.profile.loop-protect | 4 | 0 | 4 |
| aruba-aaa-via-web | vxlan.profile.name | 2,148 | 242 | 2,390 |
| aruba-switch-stack | vxlan.profile.vni.id | 2,044 | 236 | 2,280 |
| aruba-uplink | vxlan.profile.vni.vlan | 1,792 | 191 | 1,983 |
| aruba-interface-vni | vxlan.profile.vni.symmetric-routing | 1,744 | 121 | 1,865 |
| aruba-device-properties | vxlan.profile.description | 81 | 6 | 87 |
| aruba-interface-common | vxlan.profile.mac-notify-traps | 0 | 2 | 2 |

### aruba-system-info

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 10,243

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-cx-device-configuration | system-info.sys-description | 6,653 | 2,970 | 9,623 |
| aruba-cx-device-configuration | system-info.snmpv3-local-engine-id | 367 | 253 | 620 |

### aruba-device-certificate

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 10,200

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | device-certificates.device-certificate.name | 3,053 | 559 | 3,612 |
| aruba-device-certificate (same) | device-certificates.device-certificate.app-usage | 2,908 | 523 | 3,431 |
| aruba-aaa-via-connection | device-certificates.device-certificate.subject.... | 1,612 | 146 | 1,758 |
| aruba-cx-device-configuration | device-certificates.device-certificate.est-profile | 1,064 | 31 | 1,095 |
| aruba-location | device-certificates.device-certificate.subject.... | 174 | 130 | 304 |

### aruba-ip-icmp-tcp

- **Total Leafs in this context:** 1
- **Total Customer Impact:** 9,008

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | ip-icmp-tcp.profile.name | 9,008 | 0 | 9,008 |

### aruba-management-user-group

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 8,520

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-management-user-group (same) | management-user-groups.user-group.rule.rbac.action | 1,339 | 588 | 1,927 |
| aruba-management-user-group (same) | management-user-groups.user-group.rule.rbac.mat... | 1,339 | 588 | 1,927 |
| aruba-management-user-group (same) | management-user-groups.user-group.rule.seq-number | 1,339 | 588 | 1,927 |
| aruba-management-user-group (same) | management-user-groups.user-group.inherit-group | 55 | 0 | 55 |
| aruba-aaa-via-web | management-user-groups.user-group.name | 1,808 | 647 | 2,455 |
| aruba-device-properties | management-user-groups.user-group.rule.description | 79 | 150 | 229 |

### aruba-switch-chassis

- **Total Leafs in this context:** 7
- **Total Customer Impact:** 7,397

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-device-info | switch-chassis.chassis.line-modules.line-module... | 1,196 | 650 | 1,846 |
| aruba-device-info | switch-chassis.chassis.line-modules.sku | 1,196 | 649 | 1,845 |
| aruba-switch-stack | switch-chassis.chassis.platform | 1,196 | 649 | 1,845 |
| aruba-switch-stack | switch-chassis.chassis.line-modules.hw-profile | 9 | 0 | 9 |
| aruba-switch-chassis (same) | switch-chassis.chassis.chassis-name | 1,196 | 650 | 1,846 |
| aruba-switch-chassis (same) | switch-chassis.chassis.line-modules.power-admin... | 5 | 0 | 5 |
| aruba-switch-chassis (same) | switch-chassis.chassis.line-modules.power-priority | 1 | 0 | 1 |

### aruba-copp

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 5,517

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-copp (same) | copp.profile.copp-policy.configured-copp-policy... | 821 | 573 | 1,394 |
| aruba-copp (same) | copp.profile.copp-policy.applied | 764 | 535 | 1,299 |
| aruba-aaa-via-web | copp.profile.name | 852 | 578 | 1,430 |
| aruba-qos-dscp | copp.profile.copp-policy.configured-copp-policy... | 821 | 573 | 1,394 |

### aruba-ipfix-flow-record

- **Total Leafs in this context:** 25
- **Total Customer Impact:** 3,640

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.collect.counter-bytes | 150 | 148 | 298 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.match.ipv4-source-add... | 150 | 148 | 298 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.match.transport-desti... | 150 | 148 | 298 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.match.transport-sourc... | 150 | 148 | 298 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.match.ipv4-destinatio... | 150 | 147 | 297 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.match.ipv4-protocol | 150 | 147 | 297 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.match.ipv4-version | 150 | 146 | 296 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.collect.counter-packets | 150 | 139 | 289 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.collect.timestamp-abs... | 126 | 97 | 223 |
| aruba-ipfix-flow-record (same) | ipfix-flow-record.records.collect.timestamp-abs... | 128 | 93 | 221 |
| aruba-ipfix-flow-record | *... 13 more leafs* | | | |
| aruba-aaa-via-web | ipfix-flow-record.records.name | 150 | 148 | 298 |
| aruba-device-properties | ipfix-flow-record.records.description | 43 | 47 | 90 |

### aruba-mgmd

- **Total Leafs in this context:** 8
- **Total Customer Impact:** 2,859

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-mgmd (same) | mgmd-global.profile.igmp.filter-unknown-multicast | 662 | 80 | 742 |
| aruba-mgmd (same) | mgmd-global.profile.igmp.drop-unknown | 412 | 54 | 466 |
| aruba-mgmd (same) | mgmd-global.profile.igmp.fastlearn.eth-ports | 198 | 114 | 312 |
| aruba-mgmd (same) | mgmd-global.profile.igmp.fastlearn.lag-ports | 24 | 10 | 34 |
| aruba-mgmd (same) | mgmd-global.profile.delayed-refresh_enable | 2 | 4 | 6 |
| aruba-mgmd (same) | mgmd-global.profile.delayed-refresh-interval | 2 | 4 | 6 |
| aruba-mgmd (same) | mgmd-global.profile.mld.filter-unknown-multicast | 3 | 0 | 3 |
| aruba-aaa-via-web | mgmd-global.profile.name | 1,030 | 260 | 1,290 |

### aruba-cdp

- **Total Leafs in this context:** 1
- **Total Customer Impact:** 2,727

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | cdp.profile.name | 1,758 | 969 | 2,727 |

### aruba-aaa-captive-portal

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 2,697

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-captive-portal (same) | captive-portal.profile.external-cp-server-url | 563 | 783 | 1,346 |
| aruba-aaa-captive-portal (same) | captive-portal.profile.url-hash-key-format | 0 | 2 | 2 |
| aruba-aaa-captive-portal (same) | captive-portal.profile.url-hash-key-ciphertext-... | 0 | 1 | 1 |
| aruba-aaa-captive-portal (same) | captive-portal.profile.url-hash-key-value | 0 | 1 | 1 |
| aruba-aaa-via-web | captive-portal.profile.name | 564 | 783 | 1,347 |

### aruba-ufd

- **Total Leafs in this context:** 8
- **Total Customer Impact:** 2,274

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-namedfilter | ufd.profile.sessions.links-to-disable.ethernet-... | 0 | 395 | 395 |
| aruba-namedfilter | ufd.profile.sessions.links-to-monitor.ethernet-... | 0 | 389 | 389 |
| aruba-ufd (same) | ufd.profile.sessions.delay-up | 0 | 234 | 234 |
| aruba-ufd (same) | ufd.profile.sessions.delay-down | 0 | 225 | 225 |
| aruba-aaa-via-web | ufd.profile.name | 4 | 399 | 403 |
| aruba-switch-stack | ufd.profile.sessions.id | 0 | 399 | 399 |
| aruba-mgmd | ufd.profile.sessions.links-to-disable.lag-ports | 0 | 219 | 219 |
| aruba-mgmd | ufd.profile.sessions.links-to-monitor.lag-ports | 0 | 10 | 10 |

### aruba-nae-agent

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 2,102

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-nae-agent (same) | nae-agents.nae-agent.agent-disable | 274 | 282 | 556 |
| aruba-nae-agent (same) | nae-agents.nae-agent.agent-name | 274 | 282 | 556 |
| aruba-nae-agent (same) | nae-agents.nae-agent.script-name | 274 | 282 | 556 |
| aruba-aaa-via-web | nae-agents.nae-agent.agent-parameters.name | 101 | 116 | 217 |
| aruba-interface-tunnel | nae-agents.nae-agent.agent-parameters.value | 101 | 116 | 217 |

### aruba-l3-route

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 1,854

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | l3-route.profile.name | 921 | 6 | 927 |
| aruba-interface-common | l3-route.profile.route-redistribute | 917 | 2 | 919 |
| aruba-l3-route (same) | l3-route.profile.graceful-restart | 4 | 4 | 8 |

### aruba-interface-tunnel

- **Total Leafs in this context:** 12
- **Total Customer Impact:** 1,298

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-tunnel (same) | tunnel.interface.mode | 157 | 56 | 213 |
| aruba-interface-tunnel (same) | tunnel.interface.vxlan.vni-list | 140 | 46 | 186 |
| aruba-interface-tunnel (same) | tunnel.interface.ttl.value | 0 | 1 | 1 |
| aruba-interface-vxlan-tunnel | tunnel.interface.dst | 155 | 56 | 211 |
| aruba-interface-vxlan-tunnel | tunnel.interface.src | 15 | 10 | 25 |
| aruba-switch-stack | tunnel.interface.id | 157 | 56 | 213 |
| aruba-compositekey-sample | tunnel.interface.ip-version | 157 | 56 | 213 |
| aruba-br-port-profile | tunnel.interface.vxlan.profile-name | 140 | 46 | 186 |
| aruba-object-group | tunnel.interface.ipv4-prefix | 12 | 10 | 22 |
| aruba-device-properties | tunnel.interface.description | 8 | 6 | 14 |
| aruba-interface-common | tunnel.interface.vrf-forwarding | 7 | 4 | 11 |
| aruba-interface-common | tunnel.interface.l3-counters | 3 | 0 | 3 |

### aruba-ipfix-flow-exporter

- **Total Leafs in this context:** 9
- **Total Customer Impact:** 1,277

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ipfix-flow-exporter (same) | ipfix-flow-exporter.exporters.transport-protocol | 68 | 89 | 157 |
| aruba-ipfix-flow-exporter (same) | ipfix-flow-exporter.exporters.local-collector | 77 | 58 | 135 |
| aruba-ipfix-flow-exporter (same) | ipfix-flow-exporter.exporters.collector-dest | 77 | 53 | 130 |
| aruba-ipfix-flow-exporter (same) | ipfix-flow-exporter.exporters.upload-template-i... | 64 | 43 | 107 |
| aruba-ap-uplink | ipfix-flow-exporter.exporters.ip | 76 | 106 | 182 |
| aruba-ap-uplink | ipfix-flow-exporter.exporters.port | 68 | 89 | 157 |
| aruba-aaa-via-web | ipfix-flow-exporter.exporters.name | 155 | 147 | 302 |
| aruba-device-properties | ipfix-flow-exporter.exporters.description | 36 | 67 | 103 |
| aruba-cx-device-configuration | ipfix-flow-exporter.exporters.hostname | 2 | 2 | 4 |

### aruba-interface-vni

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 1,256

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-vni (same) | vxlan-vni.profile.vni.vni-name | 0 | 236 | 236 |
| aruba-interface-vni (same) | vxlan-vni.profile.vxlan-tunnel-profile | 0 | 236 | 236 |
| aruba-interface-vni (same) | vxlan-vni.profile.vni.symmetric-routing | 0 | 121 | 121 |
| aruba-aaa-via-web | vxlan-vni.profile.name | 0 | 236 | 236 |
| aruba-switch-stack | vxlan-vni.profile.vni.id | 0 | 236 | 236 |
| aruba-uplink | vxlan-vni.profile.vni.vlan | 0 | 191 | 191 |

### aruba-nae-script

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 1,209

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | nae-scripts.nae-script.name | 301 | 304 | 605 |
| aruba-nae-script (same) | nae-scripts.nae-script.script | 300 | 304 | 604 |

### aruba-interface-subinterface

- **Total Leafs in this context:** 15
- **Total Customer Impact:** 1,184

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-subinterface (same) | sub-interfaces.interface.parent-name | 114 | 62 | 176 |
| aruba-interface-subinterface (same) | sub-interfaces.interface.parent-name-id | 114 | 62 | 176 |
| aruba-interface-subinterface (same) | sub-interfaces.interface.encapsulation-vlan-id | 113 | 60 | 173 |
| aruba-switch-stack | sub-interfaces.interface.id | 114 | 62 | 176 |
| aruba-aaa-via-connection | sub-interfaces.interface.ipv4.address | 114 | 59 | 173 |
| aruba-aaa-via-connection | sub-interfaces.interface.ipv6.addresses.address | 0 | 3 | 3 |
| aruba-interface-common | sub-interfaces.interface.vrf-forwarding | 108 | 45 | 153 |
| aruba-interface-common | sub-interfaces.interface.vrrp.vrrp-profile-apply | 0 | 4 | 4 |
| aruba-interface-common | sub-interfaces.interface.ip.l3-counters | 0 | 3 | 3 |
| aruba-interface-common | sub-interfaces.interface.ipv4.secondary-ip | 1 | 0 | 1 |
| aruba-device-properties | sub-interfaces.interface.description | 110 | 25 | 135 |
| aruba-vlan-common | sub-interfaces.interface.policy.ipv4-access-lis... | 4 | 0 | 4 |
| aruba-vlan-common | sub-interfaces.interface.policy.ipv4-access-lis... | 0 | 1 | 1 |
| aruba-ap-uplink | sub-interfaces.interface.ipv4-relay.server.ip | 1 | 3 | 4 |
| aruba-net-service | sub-interfaces.interface.arp.timeout | 0 | 2 | 2 |

### aruba-ipfix-flow-monitor

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 1,072

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ipfix-flow-monitor (same) | ipfix-flow-monitor.monitors.record | 150 | 148 | 298 |
| aruba-ipfix-flow-monitor (same) | ipfix-flow-monitor.monitors.cache-timeout-active | 83 | 41 | 124 |
| aruba-ipfix-flow-monitor (same) | ipfix-flow-monitor.monitors.cache-timeout-inactive | 2 | 4 | 6 |
| aruba-aaa-via-web | ipfix-flow-monitor.monitors.name | 151 | 148 | 299 |
| aruba-flow-telemetry-common | ipfix-flow-monitor.monitors.exporter.exporter-name | 149 | 147 | 296 |
| aruba-device-properties | ipfix-flow-monitor.monitors.description | 23 | 26 | 49 |

### aruba-nd-snooping-interface

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 1,029

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | nd-snooping-interface.profile.name | 292 | 202 | 494 |
| aruba-dynamic-arp-inspection-interface | nd-snooping-interface.profile.nd-snooping.trust | 291 | 202 | 493 |
| aruba-nd-snooping | nd-snooping-interface.profile.nd-snooping.ra-gu... | 41 | 0 | 41 |
| aruba-nd-snooping-interface (same) | nd-snooping-interface.profile.nd-snooping.max-b... | 1 | 0 | 1 |

### aruba-role-gpid

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 1,014

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-role-gpid (same) | role-gpids.role-gpid.gpid | 424 | 83 | 507 |
| aruba-aaa-via-web | role-gpids.role-gpid.name | 424 | 83 | 507 |

### aruba-nd-snooping

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 944

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | nd-snooping.profile.name | 485 | 409 | 894 |
| aruba-nd-snooping (same) | nd-snooping.profile.ra-guard-policy.ra-guard-name | 49 | 0 | 49 |
| aruba-nd-snooping (same) | nd-snooping.profile.mac-check | 0 | 1 | 1 |

### aruba-nexthop-group

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 898

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | nexthop-groups.group.name | 133 | 68 | 201 |
| aruba-dpi-error-page-url | nexthop-groups.group.nexthops.index | 132 | 68 | 200 |
| aruba-ap-uplink | nexthop-groups.group.nexthops.ip | 132 | 68 | 200 |
| aruba-feature-pack | nexthop-groups.group.nexthops.type | 132 | 68 | 200 |
| aruba-nexthop-group (same) | nexthop-groups.group.nexthops.null-interface | 45 | 10 | 55 |
| aruba-nexthop-group (same) | nexthop-groups.group.nexthops.default-host | 21 | 21 | 42 |

### aruba-erps

- **Total Leafs in this context:** 21
- **Total Customer Impact:** 822

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-erps (same) | erps.profile.ring.ring-id | 72 | 8 | 80 |
| aruba-erps (same) | erps.profile.ring.instance.protection-switching... | 71 | 8 | 79 |
| aruba-erps (same) | erps.profile.ring.port0-eth-interface | 61 | 0 | 61 |
| aruba-erps (same) | erps.profile.ring.port1-eth-interface | 59 | 0 | 59 |
| aruba-erps (same) | erps.profile.ring.instance.instance-description | 37 | 5 | 42 |
| aruba-erps (same) | erps.profile.ring.port1-portchannel | 12 | 8 | 20 |
| aruba-erps (same) | erps.profile.ring.port0-portchannel | 10 | 8 | 18 |
| aruba-erps (same) | erps.profile.ring.instance.rpl | 15 | 1 | 16 |
| aruba-erps (same) | erps.profile.ring.wtr-interval | 14 | 0 | 14 |
| aruba-erps (same) | erps.profile.ring.meg-level | 14 | 0 | 14 |
| aruba-erps | *... 4 more leafs* | | | |
| aruba-smartlink | erps.profile.ring.instance.protected-vlans | 72 | 8 | 80 |
| aruba-smartlink | erps.profile.ring.instance.control-vlan | 71 | 8 | 79 |
| aruba-aaa-via-web | erps.profile.name | 72 | 8 | 80 |
| aruba-interface-common | erps.profile.ring.instance.instance-id | 72 | 8 | 80 |
| aruba-device-properties | erps.profile.ring.description | 40 | 5 | 45 |
| aruba-vsx-common | erps.profile.ring.instance.role | 28 | 1 | 29 |
| aruba-radio | erps.profile.ring.guard-interval | 7 | 0 | 7 |

### aruba-interface-vxlan-tunnel

- **Total Leafs in this context:** 12
- **Total Customer Impact:** 715

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.src-ipv4 | 0 | 234 | 234 |
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.interface.dst | 0 | 46 | 46 |
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.interface.vni-profile-name | 0 | 46 | 46 |
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.enable-counters | 0 | 18 | 18 |
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.bridging-mode | 0 | 15 | 15 |
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.loop-protect-vlans | 0 | 7 | 7 |
| aruba-interface-vxlan-tunnel (same) | vxlan-tunnel.profile.loop-protect | 0 | 4 | 4 |
| aruba-aaa-via-web | vxlan-tunnel.profile.name | 0 | 245 | 245 |
| aruba-switch-stack | vxlan-tunnel.profile.interface.id | 0 | 46 | 46 |
| aruba-compositekey-sample | vxlan-tunnel.profile.interface.ip-version | 0 | 46 | 46 |
| aruba-device-properties | vxlan-tunnel.profile.description | 0 | 6 | 6 |
| aruba-interface-common | vxlan-tunnel.profile.mac-notify-traps | 0 | 2 | 2 |

### aruba-keychain

- **Total Leafs in this context:** 10
- **Total Customer Impact:** 661

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-keychain (same) | keychains.keychain.keys.auth-key-info.auth-key-... | 131 | 30 | 161 |
| aruba-keychain (same) | keychains.keychain.keys.crypto-algorithm | 108 | 16 | 124 |
| aruba-keychain (same) | keychains.keychain.keys.accept-start | 6 | 8 | 14 |
| aruba-keychain (same) | keychains.keychain.keys.send-start | 6 | 8 | 14 |
| aruba-keychain (same) | keychains.keychain.keys.accept-end | 3 | 2 | 5 |
| aruba-keychain (same) | keychains.keychain.keys.send-end | 3 | 2 | 5 |
| aruba-keychain (same) | keychains.keychain.keys.recv-id | 0 | 2 | 2 |
| aruba-keychain (same) | keychains.keychain.keys.send-id | 0 | 2 | 2 |
| aruba-aaa-via-web | keychains.keychain.name | 140 | 33 | 173 |
| aruba-feature-pack | keychains.keychain.keys.auth-key-info.type | 131 | 30 | 161 |

### aruba-traffic-insight

- **Total Leafs in this context:** 10
- **Total Customer Impact:** 608

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-traffic-insight (same) | traffic-insight.instance.monitor.monitor-name-type | 77 | 39 | 116 |
| aruba-traffic-insight (same) | traffic-insight.instance.monitor.monitor-n-flows | 0 | 7 | 7 |
| aruba-traffic-insight (same) | traffic-insight.instance.monitor.group-by | 0 | 6 | 6 |
| aruba-traffic-insight (same) | traffic-insight.instance.monitor.single-value-f... | 0 | 1 | 1 |
| aruba-traffic-insight (same) | traffic-insight.instance.monitor.single-value-f... | 0 | 1 | 1 |
| aruba-traffic-insight (same) | traffic-insight.instance.monitor.single-value-f... | 0 | 0 | 0 |
| aruba-aaa-via-web | traffic-insight.instance.name | 90 | 39 | 129 |
| aruba-dsm | traffic-insight.instance.monitor.monitor-name | 77 | 39 | 116 |
| aruba-feature-pack | traffic-insight.instance.monitor.type | 77 | 39 | 116 |
| aruba-interface-common | traffic-insight.instance.source | 78 | 38 | 116 |

### aruba-external-storage

- **Total Leafs in this context:** 7
- **Total Customer Impact:** 557

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-external-storage (same) | external-storage.profile.store.store-name | 46 | 48 | 94 |
| aruba-external-storage (same) | external-storage.profile.store.directory | 44 | 44 | 88 |
| aruba-external-storage (same) | external-storage.profile.store.password-ciphertext | 8 | 44 | 52 |
| aruba-aaa-via-web | external-storage.profile.name | 46 | 48 | 94 |
| aruba-feature-pack | external-storage.profile.store.type | 45 | 44 | 89 |
| aruba-aaa-via-connection | external-storage.profile.store.address | 44 | 44 | 88 |
| aruba-internal-user | external-storage.profile.store.username | 8 | 44 | 52 |

### aruba-ip-lockdown

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 376

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ip-lockdown (same) | ip-source-lockdown.profile.ip-source-lockdown-r... | 147 | 41 | 188 |
| aruba-aaa-via-web | ip-source-lockdown.profile.name | 147 | 41 | 188 |

### aruba-dhcp-client

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 300

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | dhcp-client.profile.name | 113 | 37 | 150 |
| aruba-dhcp-client (same) | dhcp-client.profile.ip.enable-hostname | 105 | 37 | 142 |
| aruba-dhcp-client (same) | dhcp-client.profile.ip.enable-broadcast-flag | 8 | 0 | 8 |

### aruba-rip

- **Total Leafs in this context:** 19
- **Total Customer Impact:** 295

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-rip (same) | rip.router.instance-tag-vrf-proto-type | 48 | 0 | 48 |
| aruba-rip (same) | rip.router.proto-type | 48 | 0 | 48 |
| aruba-rip (same) | rip.router.redistribute.redistribute-id | 36 | 0 | 36 |
| aruba-rip (same) | rip.router.svi-interfaces.svi-id-address-family | 30 | 0 | 30 |
| aruba-rip (same) | rip.profile.router.instance-tag-vrf-proto-type | 0 | 19 | 19 |
| aruba-rip (same) | rip.profile.router.proto-type | 0 | 19 | 19 |
| aruba-rip (same) | rip.profile.router.redistribute.redistribute-id | 0 | 16 | 16 |
| aruba-rip (same) | rip.profile.router.svi-interfaces.svi-id-addres... | 0 | 14 | 14 |
| aruba-rip (same) | rip.router.ether-interfaces.interface-name | 5 | 0 | 5 |
| aruba-rip (same) | rip.router.ether-interfaces.interface-name-addr... | 5 | 0 | 5 |
| aruba-rip | *... 5 more leafs* | | | |
| aruba-aaa-via-web | rip.profile.name | 0 | 19 | 19 |
| aruba-device-properties | rip.profile.description | 0 | 15 | 15 |
| aruba-net-service | rip.profile.router.timers.timeout | 0 | 5 | 5 |
| aruba-vsx-common | rip.profile.router.loopback-interfaces.loopback-id | 0 | 2 | 2 |

### aruba-ipsla

- **Total Leafs in this context:** 18
- **Total Customer Impact:** 294

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ipsla (same) | ipsla.profile.source-sessions.source-name | 34 | 21 | 55 |
| aruba-ipsla (same) | ipsla.profile.source-sessions.destination-ipv4 | 31 | 18 | 49 |
| aruba-ipsla (same) | ipsla.profile.source-sessions.destination-hostname | 6 | 0 | 6 |
| aruba-ipsla (same) | ipsla.profile.source-sessions.payload-size | 4 | 1 | 5 |
| aruba-ipsla (same) | ipsla.profile.source-sessions.destination-port | 3 | 2 | 5 |
| aruba-ipsla (same) | ipsla.profile.source-sessions.source.interface-... | 4 | 0 | 4 |
| aruba-ipsla (same) | ipsla.profile.source-sessions.source.interface-... | 2 | 0 | 2 |
| aruba-ipsla (same) | ipsla.profile.responder-sessions.responder-name | 1 | 0 | 1 |
| aruba-ipsla (same) | ipsla.profile.responder-sessions.responder-port | 1 | 0 | 1 |
| aruba-ipsla (same) | ipsla.profile.responder-sessions.responder-sour... | 1 | 0 | 1 |
| aruba-ipsla | *... 3 more leafs* | | | |
| aruba-aaa-via-web | ipsla.profile.name | 34 | 21 | 55 |
| aruba-feature-pack | ipsla.profile.source-sessions.type | 33 | 18 | 51 |
| aruba-job-scheduler | ipsla.profile.source-sessions.frequency | 24 | 11 | 35 |
| aruba-ip-authorized-manager | ipsla.profile.source-sessions.source.ipv4-address | 6 | 12 | 18 |
| aruba-ap-uplink | ipsla.profile.source-sessions.source.port | 1 | 2 | 3 |

### aruba-named-vlan

- **Total Leafs in this context:** 1
- **Total Customer Impact:** 286

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | named-vlan.profile.name | 266 | 20 | 286 |

### aruba-udp-broadcast-forwarder

- **Total Leafs in this context:** 1
- **Total Customer Impact:** 282

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | udp-broadcast-forwarders.profile.name | 133 | 149 | 282 |

### aruba-rmon-alarm

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 264

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-rmon-alarm (same) | rmon-alarms.profile.rmon.falling-threshold | 39 | 5 | 44 |
| aruba-rmon-alarm (same) | rmon-alarms.profile.rmon.rising-threshold | 39 | 5 | 44 |
| aruba-rmon-alarm (same) | rmon-alarms.profile.rmon.snmp-oid | 39 | 5 | 44 |
| aruba-aaa-via-web | rmon-alarms.profile.name | 39 | 5 | 44 |
| aruba-dpi-error-page-url | rmon-alarms.profile.rmon.index | 39 | 5 | 44 |
| aruba-location | rmon-alarms.profile.rmon.interval | 39 | 5 | 44 |

### aruba-firmware-management

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 258

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| device-firmware.site-distribution | 127 | 73 | 200 |
| device-firmware.issu.software-update-rollback-timer-enable | 30 | 14 | 44 |
| device-firmware.issu.software-update-rollback-timer | 4 | 10 | 14 |

### aruba-mirror-endpoint

- **Total Leafs in this context:** 7
- **Total Customer Impact:** 254

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-mirror-endpoint (same) | mirror-endpoint.profile.endpoints.ep-name | 39 | 26 | 65 |
| aruba-mirror-endpoint (same) | mirror-endpoint.profile.endpoints.source.source-ip | 21 | 18 | 39 |
| aruba-mirror-endpoint (same) | mirror-endpoint.profile.endpoints.source.tid | 21 | 18 | 39 |
| aruba-mirror-endpoint (same) | mirror-endpoint.profile.endpoints.destinations.... | 20 | 18 | 38 |
| aruba-mirror-endpoint (same) | mirror-endpoint.profile.endpoints.comment | 3 | 1 | 4 |
| aruba-mirror-endpoint (same) | mirror-endpoint.profile.endpoints.source.encap | 2 | 2 | 4 |
| aruba-aaa-via-web | mirror-endpoint.profile.name | 39 | 26 | 65 |

### aruba-ptp

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 240

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ptp (same) | ptp.profile.protocol-profiles.clock-step | 25 | 14 | 39 |
| aruba-ptp (same) | ptp.profile.protocol-profiles.delay-mechanism | 25 | 14 | 39 |
| aruba-ptp (same) | ptp.profile.protocol-profiles.transport | 24 | 15 | 39 |
| aruba-aaa-via-web | ptp.profile.name | 27 | 15 | 42 |
| aruba-radio | ptp.profile.protocol-profiles.profile | 27 | 15 | 42 |
| aruba-interface-tunnel | ptp.profile.protocol-profiles.mode | 25 | 14 | 39 |

### aruba-lacp

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 230

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| lacp.hash | 95 | 32 | 127 |
| lacp.system-priority | 35 | 68 | 103 |

### aruba-mka

- **Total Leafs in this context:** 7
- **Total Customer Impact:** 222

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-mka (same) | mka.policy.cak-info.ckn | 38 | 17 | 55 |
| aruba-mka (same) | mka.policy.cak-info.cak-ciphertext | 38 | 17 | 55 |
| aruba-mka (same) | mka.policy.key-server-priority | 30 | 16 | 46 |
| aruba-mka (same) | mka.policy.eapol-destination-mac | 2 | 3 | 5 |
| aruba-mka (same) | mka.policy.eapol-dot1q-tagged | 0 | 3 | 3 |
| aruba-aaa-via-web | mka.policy.name | 41 | 17 | 58 |
| aruba-macsec | mka.policy.cak-info.cak | 0 | 0 | 0 |

### aruba-mac-lockout

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 204

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | mac-lockout.profile.name | 63 | 41 | 104 |
| aruba-mac-lockout (same) | mac-lockout.profile.address.mac | 62 | 38 | 100 |

### aruba-static-mac

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 165

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-static-mac (same) | static-macs.profile.static-mac.destination-port... | 22 | 11 | 33 |
| aruba-static-mac (same) | static-macs.profile.static-mac.mac-vlan | 22 | 11 | 33 |
| aruba-aaa-via-web | static-macs.profile.name | 22 | 11 | 33 |
| aruba-mac-lockout | static-macs.profile.static-mac.mac | 22 | 11 | 33 |
| aruba-uplink | static-macs.profile.static-mac.vlan | 22 | 11 | 33 |

### aruba-qos-cos

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 154

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | qos-cos.profile.name | 38 | 0 | 38 |
| aruba-aaa-via-web | qos-cos.profile.cos-map.name | 2 | 0 | 2 |
| aruba-qos-threshold-profile | qos-cos.profile.cos-map.color | 38 | 0 | 38 |
| aruba-interface-qos | qos-cos.profile.cos-map.cos | 38 | 0 | 38 |
| aruba-qos-cos (same) | qos-cos.profile.cos-map.local-priority | 38 | 0 | 38 |

### aruba-ip-binding

- **Total Leafs in this context:** 7
- **Total Customer Impact:** 147

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ip-binding (same) | source-ip-bindings.static-entry.client-address | 17 | 4 | 21 |
| aruba-ip-binding (same) | source-ip-bindings.static-entry.interface-types | 17 | 4 | 21 |
| aruba-ip-binding (same) | source-ip-bindings.static-entry.ip-version-vlan... | 17 | 4 | 21 |
| aruba-ipsla | source-ip-bindings.static-entry.interface-ethernet | 17 | 4 | 21 |
| aruba-compositekey-sample | source-ip-bindings.static-entry.ip-version | 17 | 4 | 21 |
| aruba-mac-lockout | source-ip-bindings.static-entry.mac | 17 | 4 | 21 |
| aruba-uplink | source-ip-bindings.static-entry.vlan | 17 | 4 | 21 |

### aruba-macsec

- **Total Leafs in this context:** 8
- **Total Customer Impact:** 127

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-macsec (same) | macsec.policy.replay-window | 31 | 14 | 45 |
| aruba-macsec (same) | macsec.policy.cipher-suites | 10 | 2 | 12 |
| aruba-macsec (same) | macsec.policy.confidentiality-offset | 2 | 1 | 3 |
| aruba-macsec (same) | macsec.policy.bypass-list | 0 | 3 | 3 |
| aruba-macsec (same) | macsec.policy.clear-tag-mode | 0 | 3 | 3 |
| aruba-macsec (same) | macsec.policy.replay-protect-enable | 2 | 0 | 2 |
| aruba-macsec (same) | macsec.policy.include-sci-enable | 0 | 1 | 1 |
| aruba-aaa-via-web | macsec.policy.name | 41 | 17 | 58 |

### aruba-nae-lite

- **Total Leafs in this context:** 25
- **Total Customer Impact:** 122

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-nae-lite (same) | nae-lite.profile.agent-type | 3 | 6 | 9 |
| aruba-nae-lite (same) | nae-lite.profile.conditions.condtype | 3 | 6 | 9 |
| aruba-nae-lite (same) | nae-lite.profile.conditions.name-condition | 3 | 6 | 9 |
| aruba-nae-lite (same) | nae-lite.profile.conditions.set-watch | 3 | 5 | 8 |
| aruba-nae-lite (same) | nae-lite.profile.watches.event-id | 3 | 5 | 8 |
| aruba-nae-lite (same) | nae-lite.profile.watches.watch-name | 3 | 5 | 8 |
| aruba-nae-lite (same) | nae-lite.profile.conditions.cli | 1 | 6 | 7 |
| aruba-nae-lite (same) | nae-lite.profile.conditions.include | 1 | 5 | 6 |
| aruba-nae-lite (same) | nae-lite.profile.conditions.include-regex | 1 | 5 | 6 |
| aruba-nae-lite (same) | nae-lite.profile.ready | 2 | 3 | 5 |
| aruba-nae-lite | *... 7 more leafs* | | | |
| aruba-aaa-via-web | nae-lite.profile.name | 8 | 14 | 22 |
| aruba-device-properties | nae-lite.profile.description | 0 | 10 | 10 |
| aruba-dynamic-assignment | nae-lite.profile.conditions.operand | 0 | 1 | 1 |
| aruba-policy-condition | nae-lite.profile.conditions.operator | 0 | 1 | 1 |
| aruba-br-system | nae-lite.profile.conditions.severity | 1 | 0 | 1 |
| aruba-traffic-insight | nae-lite.profile.monitors.group-by | 0 | 1 | 1 |
| aruba-dsm | nae-lite.profile.monitors.monitor-name | 0 | 1 | 1 |
| aruba-ipsla | nae-lite.profile.conditions.count | 0 | 0 | 0 |

### aruba-mvrp

- **Total Leafs in this context:** 1
- **Total Customer Impact:** 107

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | mvrp.profile.name | 103 | 4 | 107 |

### aruba-advanced-intelligent-forwarding

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 103

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-advanced-intelligent-forwarding (same) | advanced-intelligent-forwarding.profile.fib-opt... | 43 | 0 | 43 |
| aruba-advanced-intelligent-forwarding (same) | advanced-intelligent-forwarding.profile.fib-opt... | 15 | 0 | 15 |
| aruba-advanced-intelligent-forwarding (same) | advanced-intelligent-forwarding.profile.fib-opt... | 0 | 2 | 2 |
| aruba-aaa-via-web | advanced-intelligent-forwarding.profile.name | 43 | 0 | 43 |

### aruba-smartlink

- **Total Leafs in this context:** 11
- **Total Customer Impact:** 95

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-smartlink (same) | smartlink.profile.group.group-id | 13 | 2 | 15 |
| aruba-smartlink (same) | smartlink.profile.group.preemption-enable | 11 | 0 | 11 |
| aruba-smartlink (same) | smartlink.profile.group.protected-vlans | 11 | 0 | 11 |
| aruba-smartlink (same) | smartlink.profile.group.secondary-ethernet-port | 11 | 0 | 11 |
| aruba-smartlink (same) | smartlink.profile.group.preemption-delay | 11 | 0 | 11 |
| aruba-smartlink (same) | smartlink.profile.group.primary-ethernet-port | 10 | 0 | 10 |
| aruba-smartlink (same) | smartlink.profile.group.control-vlan | 8 | 0 | 8 |
| aruba-smartlink (same) | smartlink.profile.group.primary-portchannel-port | 0 | 1 | 1 |
| aruba-aaa-via-web | smartlink.profile.name | 13 | 2 | 15 |
| aruba-device-properties | smartlink.profile.group.description | 0 | 2 | 2 |
| aruba-interface-common | smartlink.profile.recv-control-vlans | 0 | 0 | 0 |

### aruba-psm

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 86

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | psm.psm-instance.name | 19 | 24 | 43 |
| aruba-psm (same) | psm.psm-instance.psm-ips | 19 | 24 | 43 |

### aruba-qos-threshold-profile

- **Total Leafs in this context:** 13
- **Total Customer Impact:** 57

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-thresholds.profile.thresh-profile-name | 4 | 15 | 19 |
| qos-thresholds.profile.queue.queue-num | 3 | 13 | 16 |
| qos-thresholds.profile.queue.ecn-entry.thresh-units | 3 | 0 | 3 |
| qos-thresholds.profile.queue.wred-resp.entry.color | 0 | 3 | 3 |
| qos-thresholds.profile.queue.wred-resp.entry.max-threshol... | 0 | 3 | 3 |
| qos-thresholds.profile.queue.wred-resp.entry.min-threshol... | 0 | 3 | 3 |
| qos-thresholds.profile.queue.ecn.max-threshold-kbytes | 0 | 2 | 2 |
| qos-thresholds.profile.queue.ecn.min-threshold-kbytes | 0 | 2 | 2 |
| qos-thresholds.profile.queue.ecn.threshold-kbytes | 0 | 2 | 2 |
| qos-thresholds.profile.queue.wred-resp-entry.color | 1 | 0 | 1 |
| qos-thresholds.profile.queue.wred-resp-entry.max-threshold | 1 | 0 | 1 |
| qos-thresholds.profile.queue.wred-resp-entry.min-threshold | 1 | 0 | 1 |
| qos-thresholds.profile.queue.wred-resp-entry.thresh-units | 1 | 0 | 1 |

### aruba-ip-routing

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 51

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-ip-routing (same) | ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-... | 6 | 11 | 17 |
| aruba-ip-routing (same) | ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-... | 0 | 11 | 11 |
| aruba-ip-routing (same) | ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-... | 6 | 0 | 6 |
| aruba-ip-routing (same) | ip-routing.profile.ip-prefix-priority-params.ip... | 0 | 0 | 0 |
| aruba-aaa-via-web | ip-routing.profile.name | 6 | 11 | 17 |

### aruba-countermon

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 50

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-countermon (same) | countermon.profile.enable-polling | 8 | 17 | 25 |
| aruba-aaa-via-web | countermon.profile.name | 8 | 17 | 25 |

### aruba-track-object

- **Total Leafs in this context:** 1
- **Total Customer Impact:** 46

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| tracking-object.vrrp.interface.interface-type | 4 | 42 | 46 |

### aruba-feature-pack

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 46

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-external-storage | management-server.profile.credentials.password-... | 4 | 8 | 12 |
| aruba-ap-system | management-server.profile.location | 4 | 8 | 12 |
| aruba-aaa-via-web | management-server.profile.name | 4 | 8 | 12 |
| aruba-feature-pack (same) | management-server.profile.block | 2 | 8 | 10 |

### aruba-qos-pool

- **Total Leafs in this context:** 6
- **Total Customer Impact:** 42

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-qos-pool (same) | qos-pools.profile.pool.headroom-size | 7 | 0 | 7 |
| aruba-qos-pool (same) | qos-pools.profile.pool.size | 7 | 0 | 7 |
| aruba-aaa-via-web | qos-pools.profile.name | 7 | 0 | 7 |
| aruba-dpi-error-page-url | qos-pools.profile.pool.index | 7 | 0 | 7 |
| aruba-qos-dscp | qos-pools.profile.pool.priority | 7 | 0 | 7 |
| aruba-feature-pack | qos-pools.profile.pool.type | 7 | 0 | 7 |

### aruba-dhcp-snooping-interface

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 41

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-aaa-via-web | dhcp-snooping-interface.profile.name | 4 | 16 | 20 |
| aruba-dynamic-arp-inspection-interface | dhcp-snooping-interface.profile.dhcpv4-snooping... | 4 | 15 | 19 |
| aruba-dynamic-arp-inspection-interface | dhcp-snooping-interface.profile.dhcpv6-snooping... | 0 | 1 | 1 |
| aruba-nd-snooping-interface | dhcp-snooping-interface.profile.dhcpv4-snooping... | 0 | 1 | 1 |

### aruba-config-checkpoint

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 32

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-config-checkpoint (same) | config-checkpoint.profile.post-checkpoint | 8 | 2 | 10 |
| aruba-config-checkpoint (same) | config-checkpoint.profile.post-checkpoint-delay | 5 | 2 | 7 |
| aruba-aaa-via-web | config-checkpoint.profile.name | 11 | 4 | 15 |

### aruba-dsm

- **Total Leafs in this context:** 4
- **Total Customer Impact:** 32

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-dsm (same) | dsm.dsm-instance.ipfix | 2 | 8 | 10 |
| aruba-dsm (same) | dsm.dsm-instance.workload-migration | 4 | 2 | 6 |
| aruba-dsm (same) | dsm.dsm-instance.uplink-to-uplink | 1 | 0 | 1 |
| aruba-aaa-via-web | dsm.dsm-instance.name | 5 | 10 | 15 |

### aruba-container

- **Total Leafs in this context:** 12
- **Total Customer Impact:** 21

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-container (same) | containers.instance.image-location-url | 2 | 1 | 3 |
| aruba-container (same) | containers.instance.image-location-vrf | 2 | 1 | 3 |
| aruba-container (same) | containers.instance.allow-unsigned-image | 0 | 1 | 1 |
| aruba-container (same) | containers.instance.encrypted-environment-varia... | 1 | 0 | 1 |
| aruba-container (same) | containers.instance.encrypted-environment-varia... | 1 | 0 | 1 |
| aruba-container (same) | containers.instance.encrypted-environment-varia... | 1 | 0 | 1 |
| aruba-container (same) | containers.instance.environment-variables.variable | 0 | 1 | 1 |
| aruba-container (same) | containers.instance.runtime-constraints.cpu | 1 | 0 | 1 |
| aruba-container (same) | containers.instance.runtime-constraints.memory | 1 | 0 | 1 |
| aruba-container (same) | containers.instance.vrfs | 1 | 0 | 1 |
| aruba-aaa-via-web | containers.instance.name | 2 | 4 | 6 |
| aruba-interface-tunnel | containers.instance.environment-variables.value | 0 | 1 | 1 |

### aruba-sysmon

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 12

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-sysmon (same) | sysmon.profile.poll-interval | 1 | 3 | 4 |
| aruba-sysmon (same) | sysmon.profile.polling | 1 | 3 | 4 |
| aruba-aaa-via-web | sysmon.profile.name | 1 | 3 | 4 |

### aruba-dynamic-arp-inspection-interface

- **Total Leafs in this context:** 2
- **Total Customer Impact:** 10

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-dynamic-arp-inspection-interface (same) | dynamic-arp-inspection-interface.profile.dynami... | 2 | 3 | 5 |
| aruba-aaa-via-web | dynamic-arp-inspection-interface.profile.name | 2 | 3 | 5 |

### aruba-ip-lockdown-interface

- **Total Leafs in this context:** 3
- **Total Customer Impact:** 7

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-hotspot2-anqp-ip-addr-avail | ip-source-lockdown-interface.profile.ip-source-... | 0 | 3 | 3 |
| aruba-hotspot2-anqp-ip-addr-avail | ip-source-lockdown-interface.profile.ip-source-... | 0 | 1 | 1 |
| aruba-aaa-via-web | ip-source-lockdown-interface.profile.name | 0 | 3 | 3 |

### aruba-container-network

- **Total Leafs in this context:** 5
- **Total Customer Impact:** 7

**⚠️ Leafs inherited from other modules:**

| Actual Source Module | Leaf Name | Big Cluster | Small Cluster | Total |
|---------------------|-----------|----------:|--------------:|------:|
| aruba-container-network (same) | container-networks.profile.name-vrf | 1 | 1 | 2 |
| aruba-container-network (same) | container-networks.profile.port-mapping.tcp.con... | 0 | 1 | 1 |
| aruba-container-network (same) | container-networks.profile.port-mapping.tcp.hos... | 0 | 1 | 1 |
| aruba-container-network (same) | container-networks.profile.preferred | 1 | 0 | 1 |
| aruba-aaa-via-web | container-networks.profile.name | 1 | 1 | 2 |

---

## Referenced YANG Modules (For Reference)

The following YANG modules **ARE** imported in `aruba-cx-device-configuration.yang`:

- `aruba-aaa-profile` (prefix: `ac-aaa-profile`)
- `aruba-alias` (prefix: `ac-alias`)
- `aruba-app-recog-control` (prefix: `ac-app-recog-control`)
- `aruba-aspath-list` (prefix: `ac-aspath-list`)
- `aruba-auth-server` (prefix: `ac-auth-server`)
- `aruba-auth-server-global` (prefix: `ac-auth-server-global`)
- `aruba-auth-server-group` (prefix: `ac-auth-server-group`)
- `aruba-bfd` (prefix: `ac-bfd`)
- `aruba-bgp` (prefix: `ac-bgp`)
- `aruba-client-insight` (prefix: `ac-client-insight`)
- `aruba-client-iptracker` (prefix: `ac-client-iptracker`)
- `aruba-community-list` (prefix: `ac-community-list`)
- `aruba-device-configuration-common` (prefix: `ac-dc-types`)
- `aruba-device-profile` (prefix: `ac-device-profile`)
- `aruba-devicefingerprinting-profile` (prefix: `ac-dfp`)
- `aruba-dhcp-pool` (prefix: `ac-dhcp-pool`)
- `aruba-dhcp-relay` (prefix: `ac-dhcp-relay`)
- `aruba-dhcp-server` (prefix: `ac-dhcp-server`)
- `aruba-dhcp-snooping` (prefix: `ac-dhcp-snooping`)
- `aruba-dns` (prefix: `ac-dns`)
- `aruba-est` (prefix: `ac-est`)
- `aruba-evpn` (prefix: `ac-evpn`)
- `aruba-extensions` (prefix: `ac-ext`)
- `aruba-fault-monitor` (prefix: `ac-fault-monitor`)
- `aruba-flow-tracking` (prefix: `ac-flow-tracking`)
- `aruba-http-proxy` (prefix: `ac-http-proxy`)
- `aruba-interface-loopback` (prefix: `ac-if-loopback`)
- `aruba-interface-management` (prefix: `ac-if-mgmt`)
- `aruba-interface-profile` (prefix: `ac-interface-profile`)
- `aruba-interface-vlan` (prefix: `ac-if-vlan`)
- `aruba-ip-source-interface` (prefix: `ac-ip-src-interface`)
- `aruba-local-management` (prefix: `ac-local-mgmt`)
- `aruba-logging` (prefix: `ac-logging`)
- `aruba-management-user` (prefix: `ac-mgmt-user`)
- `aruba-mirror` (prefix: `ac-mirror`)
- `aruba-msdp` (prefix: `ac-msdp`)
- `aruba-multicast-dns` (prefix: `ac-multicast-dns`)
- `aruba-multicast-static-route` (prefix: `ac-multicast-static-route`)
- `aruba-ntp` (prefix: `ac-ntp`)
- `aruba-ospfv2` (prefix: `ac-ospfv2`)
- `aruba-ospfv3` (prefix: `ac-ospfv3`)
- `aruba-pim` (prefix: `ac-pim`)
- `aruba-policy` (prefix: `ac-policy`)
- `aruba-prefix-list` (prefix: `ac-prefix-list`)
- `aruba-qos-global` (prefix: `ac-qos`)
- `aruba-remote-management` (prefix: `ac-remote-mgmt`)
- `aruba-role` (prefix: `ac-role`)
- `aruba-routemap` (prefix: `ac-routemap`)
- `aruba-sflow` (prefix: `ac-sflow`)
- `aruba-snmp` (prefix: `ac-snmp`)
- `aruba-static-route` (prefix: `ac-static-route`)
- `aruba-stp` (prefix: `ac-stp`)
- `aruba-sw-port-profile` (prefix: `ac-sw-port-profile`)
- `aruba-switch-certificate-usage` (prefix: `ac-switch-certificate-usage`)
- `aruba-switch-system` (prefix: `ac-switch-system`)
- `aruba-ubt` (prefix: `ac-ubt`)
- `aruba-vlan` (prefix: `ac-vlan`)
- `aruba-vrf` (prefix: `ac-vrf`)
- `aruba-vrrp` (prefix: `ac-vrrp`)
- `aruba-vrrp-interface` (prefix: `ac-vrrp-interface`)

---

## Understanding the Data

### Why Context Module ≠ Actual Source Module?

YANG uses `grouping` and `uses` statements to share common definitions across modules:

```
aruba-vlan-range.yang
  └── uses ac-vlan-cmn:vlan-config (from aruba-vlan-common.yang)
        ├── uses ac-cipt:vlan-config → client-ip-tracker-enable (from aruba-client-iptracker.yang)
        ├── uses ac-mgmd:igmp-vlan-config → igmp.* leafs (from aruba-mgmd.yang)
        ├── uses ac-dsnoop:dhcpv4-snooping-vlan → dhcpv4-snooping.* (from aruba-dhcp-snooping.yang)
        └── etc.
```

The Excel file shows leafs under their **context** (where they appear in the data path),
but the leaf is **actually defined** in a different source module.

### Implications for aruba-cx-device-configuration.yang

To include a leaf that appears under `aruba-vlan-range` context but is defined in `aruba-client-iptracker`,
you would need to import `aruba-client-iptracker` (or a module that uses its groupings).

---

## Recommendations

Based on actual source module analysis:

1. **aruba-interface-common** - 1,032,897 total customers (122 leafs)
2. **aruba-aaa-via-web** - 763,389 total customers (78 leafs)
3. **aruba-switch-stack** - 506,852 total customers (19 leafs)
4. **aruba-br-port-profile** - 299,132 total customers (5 leafs)
5. **aruba-device-properties** - 229,037 total customers (19 leafs)
6. **aruba-device-info** - 223,284 total customers (4 leafs)
7. **aruba-aaa-webauth** - 88,561 total customers (16 leafs)
8. **aruba-snmp-trap** - 85,750 total customers (5 leafs)
9. **aruba-interface-tunnel** - 77,293 total customers (11 leafs)
10. **aruba-interface-ethernet** - 73,192 total customers (5 leafs)

### Action Items

1. Review each **actual source module** to determine if it should be added to `aruba-cx-device-configuration.yang`
2. Note that adding the source module may automatically include all leafs that use its groupings
3. Prioritize modules with highest customer usage for integration
4. Verify if any unreferenced leafs are intentionally excluded or deprecated
