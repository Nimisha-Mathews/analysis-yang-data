# PLM Leaf Analysis Report

## Executive Summary

This report identifies YANG modules/leafs in `Consolidated_PLM_Leaf_list.xlsx` that are **NOT** referenced
by leaf or leafref in `aruba-cx-device-configuration.yang`, along with customer usage data.

### Key Findings

- **Total entries analyzed:** 2707
- **Referenced entries:** 1592 (58.8%)
- **Unreferenced entries:** 1115 (41.2%)
- **Unique YANG modules with unreferenced leafs:** 87

### Customer Impact Summary

| Metric | Count |
|--------|------:|
| Big Cluster Customers Affected | 3,616,018 |
| Small Cluster Customers Affected | 1,223,966 |
| **Total Customers Affected** | **4,839,984** |

---

## Unreferenced YANG Modules by Customer Impact

The following YANG modules are **NOT** imported or referenced in `aruba-cx-device-configuration.yang`,
sorted by total customer usage (highest to lowest):

| Rank | YANG Module | # of Leafs | Big Cluster | Small Cluster | Total Customers |
|-----:|-------------|----------:|-----------:|--------------:|---------------:|
| 1 | aruba-interface-ethernet | 264 | 1,813,255 | 593,029 | 2,406,284 |
| 2 | aruba-interface-portchannel | 119 | 545,227 | 218,052 | 763,279 |
| 3 | aruba-switch-stack | 11 | 423,626 | 141,878 | 565,504 |
| 4 | aruba-vsf-template | 5 | 278,951 | 92,092 | 371,043 |
| 5 | aruba-qos-dscp | 7 | 91,029 | 0 | 91,029 |
| 6 | aruba-vlan-range | 21 | 66,223 | 23,383 | 89,606 |
| 7 | aruba-loop-protect | 4 | 32,928 | 15,827 | 48,755 |
| 8 | aruba-aaa-macauth | 7 | 36,127 | 10,880 | 47,007 |
| 9 | aruba-aaa-dot1xauth | 13 | 35,132 | 10,423 | 45,555 |
| 10 | aruba-vsx | 17 | 24,677 | 13,843 | 38,520 |
| 11 | aruba-named-condition | 3 | 24,403 | 8,714 | 33,117 |
| 12 | aruba-vsx-pair | 18 | 20,798 | 11,405 | 32,203 |
| 13 | aruba-job-scheduler | 31 | 18,246 | 7,606 | 25,852 |
| 14 | aruba-qos-schedule | 15 | 18,619 | 6,457 | 25,076 |
| 15 | aruba-certificate-rcp | 7 | 16,139 | 3,670 | 19,809 |
| 16 | aruba-snmp-trap | 5 | 11,759 | 7,776 | 19,535 |
| 17 | aruba-port-security | 4 | 14,466 | 4,693 | 19,159 |
| 18 | aruba-ip-icmp-tcp | 4 | 18,300 | 0 | 18,300 |
| 19 | aruba-qos-queue | 6 | 13,595 | 3,628 | 17,223 |
| 20 | aruba-switch-profiles | 2 | 10,196 | 6,422 | 16,618 |
| 21 | aruba-interface-vxlan | 13 | 13,834 | 1,427 | 15,261 |
| 22 | aruba-object-group | 11 | 10,336 | 4,502 | 14,838 |
| 23 | aruba-lldp | 25 | 12,573 | 1,391 | 13,964 |
| 24 | aruba-device-certificate | 16 | 11,741 | 2,018 | 13,759 |
| 25 | aruba-hardware-module-profile | 6 | 7,861 | 4,860 | 12,721 |
| 26 | aruba-system-info | 2 | 7,020 | 3,223 | 10,243 |
| 27 | aruba-management-user-group | 6 | 5,959 | 2,561 | 8,520 |
| 28 | aruba-switch-chassis | 7 | 4,799 | 2,598 | 7,397 |
| 29 | aruba-copp | 4 | 3,258 | 2,259 | 5,517 |
| 30 | aruba-cdp | 2 | 3,516 | 1,938 | 5,454 |
| 31 | aruba-ipfix-flow-record | 25 | 1,853 | 1,787 | 3,640 |
| 32 | aruba-mgmd | 8 | 2,333 | 526 | 2,859 |
| 33 | aruba-aaa-captive-portal | 5 | 1,127 | 1,570 | 2,697 |
| 34 | aruba-ufd | 9 | 8 | 2,669 | 2,677 |
| 35 | aruba-nae-agent | 5 | 1,024 | 1,078 | 2,102 |
| 36 | aruba-nd-snooping | 5 | 1,060 | 819 | 1,879 |
| 37 | aruba-l3-route | 3 | 1,842 | 12 | 1,854 |
| 38 | aruba-ipfix-flow-exporter | 10 | 701 | 760 | 1,461 |
| 39 | aruba-interface-vni | 7 | 0 | 1,377 | 1,377 |
| 40 | aruba-interface-tunnel | 15 | 974 | 356 | 1,330 |
| 41 | aruba-interface-subinterface | 21 | 798 | 416 | 1,214 |
| 42 | aruba-nae-script | 2 | 601 | 608 | 1,209 |
| 43 | aruba-ipfix-flow-monitor | 6 | 558 | 514 | 1,072 |
| 44 | aruba-nd-snooping-interface | 4 | 625 | 404 | 1,029 |
| 45 | aruba-role-gpid | 2 | 848 | 166 | 1,014 |
| 46 | aruba-interface-vxlan-tunnel | 13 | 0 | 949 | 949 |
| 47 | aruba-nexthop-group | 6 | 595 | 303 | 898 |
| 48 | aruba-keychain | 12 | 660 | 165 | 825 |
| 49 | aruba-erps | 21 | 746 | 76 | 822 |
| 50 | aruba-traffic-insight | 11 | 477 | 248 | 725 |
| 51 | aruba-external-storage | 10 | 295 | 402 | 697 |
| 52 | aruba-rip | 43 | 412 | 234 | 646 |
| 53 | aruba-udp-broadcast-forwarder | 2 | 266 | 298 | 564 |
| 54 | aruba-named-vlan | 2 | 504 | 21 | 525 |
| 55 | aruba-ip-lockdown | 2 | 294 | 82 | 376 |
| 56 | aruba-ipsla | 20 | 228 | 122 | 350 |
| 57 | aruba-mirror-endpoint | 10 | 184 | 143 | 327 |
| 58 | aruba-dhcp-client | 3 | 226 | 74 | 300 |
| 59 | aruba-ptp | 8 | 176 | 102 | 278 |
| 60 | aruba-mka | 8 | 187 | 90 | 277 |
| 61 | aruba-rmon-alarm | 6 | 234 | 30 | 264 |
| 62 | aruba-firmware-management | 3 | 161 | 97 | 258 |
| 63 | aruba-lacp | 2 | 130 | 100 | 230 |
| 64 | aruba-mvrp | 2 | 206 | 8 | 214 |
| 65 | aruba-mac-lockout | 3 | 132 | 82 | 214 |
| 66 | aruba-track-object | 4 | 22 | 164 | 186 |
| 67 | aruba-static-mac | 5 | 110 | 55 | 165 |
| 68 | aruba-qos-cos | 5 | 154 | 0 | 154 |
| 69 | aruba-ip-binding | 7 | 119 | 28 | 147 |
| 70 | aruba-psm | 3 | 57 | 72 | 129 |
| 71 | aruba-macsec | 8 | 86 | 41 | 127 |
| 72 | aruba-nae-lite | 26 | 37 | 86 | 123 |
| 73 | aruba-advanced-intelligent-forwarding | 4 | 101 | 2 | 103 |
| 74 | aruba-smartlink | 11 | 88 | 7 | 95 |
| 75 | aruba-feature-pack | 7 | 26 | 54 | 80 |
| 76 | aruba-qos-threshold-profile | 15 | 17 | 49 | 66 |
| 77 | aruba-ip-routing | 5 | 18 | 33 | 51 |
| 78 | aruba-countermon | 2 | 16 | 34 | 50 |
| 79 | aruba-qos-pool | 6 | 42 | 0 | 42 |
| 80 | aruba-dhcp-snooping-interface | 4 | 8 | 33 | 41 |
| 81 | aruba-config-checkpoint | 3 | 24 | 8 | 32 |
| 82 | aruba-dsm | 4 | 12 | 20 | 32 |
| 83 | aruba-container | 13 | 12 | 10 | 22 |
| 84 | aruba-sysmon | 3 | 3 | 9 | 12 |
| 85 | aruba-dynamic-arp-inspection-interface | 2 | 4 | 6 | 10 |
| 86 | aruba-container-network | 6 | 4 | 5 | 9 |
| 87 | aruba-ip-lockdown-interface | 3 | 0 | 7 | 7 |

---

## Top 50 Most Impactful Unreferenced Leafs

Sorted by total customer usage:

| Rank | YANG Module | Leaf Name | Big Cluster | Small Cluster | Total |
|-----:|-------------|-----------|----------:|--------------:|------:|
| 1 | aruba-interface-ethernet | ethernet-interfaces.interface.name | 164,744 | 56,704 | 221,448 |
| 2 | aruba-interface-ethernet | ethernet-interfaces.interface.enable | 164,737 | 56,694 | 221,431 |
| 3 | aruba-interface-ethernet | ethernet-interfaces.interface.switchport.interface-mode | 163,908 | 56,173 | 220,081 |
| 4 | aruba-interface-ethernet | ethernet-interfaces.interface.switchport.access-vlan | 154,273 | 52,639 | 206,912 |
| 5 | aruba-interface-ethernet | ethernet-interfaces.interface.switchport.native-vlan | 129,706 | 45,045 | 174,751 |
| 6 | aruba-interface-ethernet | ethernet-interfaces.interface.description | 123,000 | 40,028 | 163,028 |
| 7 | aruba-interface-ethernet | ethernet-interfaces.interface.switchport.trunk-vlan-ranges | 95,978 | 28,887 | 124,865 |
| 8 | aruba-interface-ethernet | ethernet-interfaces.interface.routing | 86,377 | 29,612 | 115,989 |
| 9 | aruba-switch-stack | stacks.stack.name | 82,414 | 27,664 | 110,078 |
| 10 | aruba-switch-stack | stacks.stack.members.id | 82,414 | 27,663 | 110,077 |
| 11 | aruba-switch-stack | stacks.stack.members.sku | 82,414 | 27,663 | 110,077 |
| 12 | aruba-switch-stack | stacks.stack.platform | 82,414 | 27,663 | 110,077 |
| 13 | aruba-vsf-template | vsf-templates.template.name | 82,290 | 27,264 | 109,554 |
| 14 | aruba-vsf-template | vsf-templates.template.members.id | 82,290 | 27,226 | 109,516 |
| 15 | aruba-vsf-template | vsf-templates.template.members.sku | 82,290 | 27,226 | 109,516 |
| 16 | aruba-interface-ethernet | ethernet-interfaces.interface.switchport.trunk-vlan-all | 60,795 | 24,739 | 85,534 |
| 17 | aruba-interface-portchannel | portchannels.interface.name | 54,775 | 21,239 | 76,014 |
| 18 | aruba-interface-portchannel | portchannels.interface.enable | 54,766 | 21,229 | 75,995 |
| 19 | aruba-interface-portchannel | portchannels.interface.switchport.interface-mode | 54,723 | 21,189 | 75,912 |
| 20 | aruba-interface-portchannel | portchannels.interface.switchport.native-vlan | 54,222 | 20,767 | 74,989 |
| 21 | aruba-interface-portchannel | portchannels.interface.port-list | 52,251 | 20,639 | 72,890 |
| 22 | aruba-interface-ethernet | ethernet-interfaces.interface.portchannel-lag | 52,250 | 20,599 | 72,849 |
| 23 | aruba-interface-portchannel | portchannels.interface.trunk-type | 46,967 | 18,293 | 65,260 |
| 24 | aruba-interface-portchannel | portchannels.interface.lacp.mode | 46,966 | 18,289 | 65,255 |
| 25 | aruba-interface-ethernet | ethernet-interfaces.interface.loop-protect.enable | 49,762 | 15,098 | 64,860 |
| 26 | aruba-interface-portchannel | portchannels.interface.description | 44,587 | 16,254 | 60,841 |
| 27 | aruba-interface-ethernet | ethernet-interfaces.interface.stp.admin-edge-port | 43,951 | 14,984 | 58,935 |
| 28 | aruba-interface-portchannel | portchannels.interface.routing | 41,563 | 15,842 | 57,405 |
| 29 | aruba-interface-ethernet | ethernet-interfaces.interface.stp.bpdu-guard | 44,592 | 12,308 | 56,900 |
| 30 | aruba-interface-portchannel | portchannels.interface.switchport.trunk-vlan-all | 36,962 | 12,319 | 49,281 |
| 31 | aruba-aaa-macauth | macauth.profile.name | 34,254 | 10,761 | 45,015 |
| 32 | aruba-aaa-dot1xauth | dot1xauth.profile.name | 33,234 | 10,255 | 43,489 |
| 33 | aruba-vlan-range | layer2-vlan-range.client-ip-tracker-enable | 30,301 | 12,849 | 43,150 |
| 34 | aruba-switch-stack | stacks.stack.members.links.link1.interfaces | 31,623 | 10,851 | 42,474 |
| 35 | aruba-switch-stack | stacks.stack.members.links.link2.interfaces | 29,470 | 9,810 | 39,280 |
| 36 | aruba-interface-ethernet | ethernet-interfaces.interface.aaa.authentication.mac-auth.enable | 30,529 | 8,297 | 38,826 |
| 37 | aruba-interface-ethernet | ethernet-interfaces.interface.aaa.authentication.dot1x-auth.enable | 29,983 | 7,398 | 37,381 |
| 38 | aruba-interface-ethernet | ethernet-interfaces.interface.aaa.authentication.client-limit | 28,233 | 7,068 | 35,301 |
| 39 | aruba-vsf-template | vsf-templates.template.secondary-member | 25,713 | 8,973 | 34,686 |
| 40 | aruba-switch-stack | stacks.stack.secondary-member | 25,713 | 8,971 | 34,684 |
| 41 | aruba-interface-portchannel | portchannels.interface.switchport.trunk-vlan-ranges | 20,682 | 10,378 | 31,060 |
| 42 | aruba-interface-ethernet | ethernet-interfaces.interface.aaa.authentication.concurrent-onboarding | 20,902 | 3,231 | 24,133 |
| 43 | aruba-interface-ethernet | ethernet-interfaces.interface.stp.root-guard | 18,812 | 4,656 | 23,468 |
| 44 | aruba-interface-ethernet | ethernet-interfaces.interface.poe.enabled | 20,578 | 2,759 | 23,337 |
| 45 | aruba-qos-dscp | qos-dscp.profile.dscp-map.dscp | 22,856 | 0 | 22,856 |
| 46 | aruba-qos-dscp | qos-dscp.profile.name | 22,856 | 0 | 22,856 |
| 47 | aruba-qos-dscp | qos-dscp.profile.dscp-map.local-priority | 22,223 | 0 | 22,223 |
| 48 | aruba-interface-ethernet | ethernet-interfaces.interface.mtu | 16,397 | 5,207 | 21,604 |
| 49 | aruba-loop-protect | loop-protect.profile.name | 14,648 | 6,232 | 20,880 |
| 50 | aruba-vlan-range | layer2-vlan-range.igmp.snooping | 15,311 | 4,317 | 19,628 |

---

## Detailed Breakdown by YANG Module

### aruba-interface-ethernet

- **Total Leafs:** 264
- **Big Cluster Customers:** 1,813,255
- **Small Cluster Customers:** 593,029
- **Total Customer Impact:** 2,406,284

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ethernet-interfaces.interface.name | 164,744 | 56,704 | 221,448 |
| ethernet-interfaces.interface.enable | 164,737 | 56,694 | 221,431 |
| ethernet-interfaces.interface.switchport.interface-mode | 163,908 | 56,173 | 220,081 |
| ethernet-interfaces.interface.switchport.access-vlan | 154,273 | 52,639 | 206,912 |
| ethernet-interfaces.interface.switchport.native-vlan | 129,706 | 45,045 | 174,751 |
| ethernet-interfaces.interface.description | 123,000 | 40,028 | 163,028 |
| ethernet-interfaces.interface.switchport.trunk-vlan-ranges | 95,978 | 28,887 | 124,865 |
| ethernet-interfaces.interface.routing | 86,377 | 29,612 | 115,989 |
| ethernet-interfaces.interface.switchport.trunk-vlan-all | 60,795 | 24,739 | 85,534 |
| ethernet-interfaces.interface.portchannel-lag | 52,250 | 20,599 | 72,849 |
| ethernet-interfaces.interface.loop-protect.enable | 49,762 | 15,098 | 64,860 |
| ethernet-interfaces.interface.stp.admin-edge-port | 43,951 | 14,984 | 58,935 |
| ethernet-interfaces.interface.stp.bpdu-guard | 44,592 | 12,308 | 56,900 |
| ethernet-interfaces.interface.aaa.authentication.mac-auth.enable | 30,529 | 8,297 | 38,826 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.enable | 29,983 | 7,398 | 37,381 |
| ethernet-interfaces.interface.aaa.authentication.client-limit | 28,233 | 7,068 | 35,301 |
| ethernet-interfaces.interface.aaa.authentication.concurrent-onboarding | 20,902 | 3,231 | 24,133 |
| ethernet-interfaces.interface.stp.root-guard | 18,812 | 4,656 | 23,468 |
| ethernet-interfaces.interface.poe.enabled | 20,578 | 2,759 | 23,337 |
| ethernet-interfaces.interface.mtu | 16,397 | 5,207 | 21,604 |
| ethernet-interfaces.interface.speed-duplex | 16,914 | 2,227 | 19,141 |
| ethernet-interfaces.interface.dhcpv4-snooping.trust | 12,796 | 2,987 | 15,783 |
| ethernet-interfaces.interface.aaa.authentication.mac-auth.cached-reauth-enable | 12,391 | 2,898 | 15,289 |
| ethernet-interfaces.interface.stp.tcn-guard | 11,255 | 3,987 | 15,242 |
| ethernet-interfaces.interface.aaa.authentication.mac-auth.reauth-enable | 12,503 | 2,646 | 15,149 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.cached-reauth-enable | 11,945 | 2,632 | 14,577 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.reauth-enable | 12,496 | 2,062 | 14,558 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.eapol-max-requests | 10,877 | 2,648 | 13,525 |
| ethernet-interfaces.interface.aaa.authentication.bpdu-bypass.lldp | 10,777 | 2,008 | 12,785 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.max-retries | 8,649 | 1,690 | 10,339 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.eapol-timeout | 7,853 | 2,000 | 9,853 |
| ethernet-interfaces.interface.aaa.authentication.mac-auth.cached-reauth-period | 7,852 | 1,796 | 9,648 |
| ethernet-interfaces.interface.aaa.authentication.bpdu-bypass.cdp | 7,717 | 1,488 | 9,205 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.cached-reauth-period | 7,448 | 1,450 | 8,898 |
| ethernet-interfaces.interface.loop-protect.action | 4,821 | 3,859 | 8,680 |
| ethernet-interfaces.interface.stp.bpdu-filter | 6,567 | 1,965 | 8,532 |
| ethernet-interfaces.interface.aaa.authorization.critical-auth-role | 6,841 | 1,431 | 8,272 |
| ethernet-interfaces.interface.stp.loop-guard | 5,794 | 2,263 | 8,057 |
| ethernet-interfaces.interface.ipv4.address | 5,705 | 2,275 | 7,980 |
| ethernet-interfaces.interface.qos.trust | 6,153 | 1,414 | 7,567 |
| ethernet-interfaces.interface.aaa.authentication.mac-auth.reauth-period | 5,792 | 1,723 | 7,515 |
| ethernet-interfaces.interface.mode | 5,736 | 1,681 | 7,417 |
| ethernet-interfaces.interface.aaa.authentication.allow-flood-traffic | 5,593 | 1,611 | 7,204 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.reauth-period | 5,569 | 1,092 | 6,661 |
| ethernet-interfaces.interface.aaa.authorization.reject-role | 5,030 | 707 | 5,737 |
| ethernet-interfaces.interface.qos.broadcast-rate-limit.rate-type | 3,116 | 2,586 | 5,702 |
| ethernet-interfaces.interface.port-security.enable | 4,155 | 1,400 | 5,555 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.quiet-period | 4,364 | 1,037 | 5,401 |
| ethernet-interfaces.interface.aaa.authentication.mac-auth.quiet-period | 4,121 | 905 | 5,026 |
| ethernet-interfaces.interface.fault-monitor-profile | 3,031 | 1,833 | 4,864 |
| ethernet-interfaces.interface.port-security.client-limit | 3,666 | 1,085 | 4,751 |
| ethernet-interfaces.interface.qos.multicast-rate-limit.rate-type | 1,867 | 2,159 | 4,026 |
| ethernet-interfaces.interface.aaa.security-violation.action | 3,251 | 534 | 3,785 |
| ethernet-interfaces.interface.vrf-forwarding | 2,286 | 1,416 | 3,702 |
| ethernet-interfaces.interface.aaa.authentication.auth-precedence | 2,534 | 1,109 | 3,643 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.initial-auth-response-timeout | 3,121 | 345 | 3,466 |
| ethernet-interfaces.interface.qos.broadcast-rate-limit.bit-rate | 1,759 | 1,686 | 3,445 |
| ethernet-interfaces.interface.switchport.tag | 1,945 | 1,475 | 3,420 |
| ethernet-interfaces.interface.poe.pre-std-detect | 2,388 | 950 | 3,338 |
| ethernet-interfaces.interface.update-interval | 2,664 | 555 | 3,219 |
| ethernet-interfaces.interface.profile-name | 2,540 | 381 | 2,921 |
| ethernet-interfaces.interface.aaa.authentication.auth-priority | 2,144 | 773 | 2,917 |
| ethernet-interfaces.interface.ip.mtu | 2,566 | 244 | 2,810 |
| ethernet-interfaces.interface.poe.priority | 1,832 | 907 | 2,739 |
| ethernet-interfaces.interface.aaa.authorization.radius-override-enable | 2,533 | 162 | 2,695 |
| ethernet-interfaces.interface.dynamic-arp-inspection.trust | 2,100 | 468 | 2,568 |
| ethernet-interfaces.interface.port-security.sticky-mac-enable | 1,991 | 475 | 2,466 |
| ethernet-interfaces.interface.udld.enable | 1,280 | 1,155 | 2,435 |
| ethernet-interfaces.interface.aaa.security-violation.shutdown-recovery-enable | 1,434 | 971 | 2,405 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.discovery-period | 1,530 | 716 | 2,246 |
| ethernet-interfaces.interface.qos.multicast-rate-limit.bit-rate | 825 | 1,342 | 2,167 |
| ethernet-interfaces.interface.lldp.mode | 616 | 1,466 | 2,082 |
| ethernet-interfaces.interface.udld.mode.compatibility-mode | 999 | 1,031 | 2,030 |
| ethernet-interfaces.interface.udld.mode.rfc5171-mode | 896 | 1,000 | 1,896 |
| ethernet-interfaces.interface.aaa.authorization.fallback-role | 1,752 | 113 | 1,865 |
| ethernet-interfaces.interface.stp.link-type | 841 | 956 | 1,797 |
| ethernet-interfaces.interface.aaa.security-violation.recovery-timer | 964 | 812 | 1,776 |
| ethernet-interfaces.interface.aaa.authentication.auth-mode | 1,459 | 259 | 1,718 |
| ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.rate-type | 466 | 1,176 | 1,642 |
| ethernet-interfaces.interface.aaa.authentication.onboarding-precedence | 1,227 | 351 | 1,578 |
| ethernet-interfaces.interface.stp.rpvst-guard | 1,170 | 371 | 1,541 |
| ethernet-interfaces.interface.qos.broadcast-rate-limit.packet-rate | 1,095 | 417 | 1,512 |
| ethernet-interfaces.interface.dhcpv4-snooping.max-bindings | 1,339 | 42 | 1,381 |
| ethernet-interfaces.interface.pim-sparse.enable | 1,311 | 46 | 1,357 |
| ethernet-interfaces.interface.poe.allocation-method | 818 | 514 | 1,332 |
| ethernet-interfaces.interface.aaa.authorization.auth-role | 910 | 394 | 1,304 |
| ethernet-interfaces.interface.loop-protect.vlans | 700 | 540 | 1,240 |
| ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.bit-rate | 326 | 872 | 1,198 |
| ethernet-interfaces.interface.aaa.authorization.pre-auth-role | 790 | 397 | 1,187 |
| ethernet-interfaces.interface.qos.multicast-rate-limit.packet-rate | 828 | 346 | 1,174 |
| ethernet-interfaces.interface.igmp.enable | 1,057 | 30 | 1,087 |
| ethernet-interfaces.interface.dhcpv6-snooping.trust | 705 | 357 | 1,062 |
| ethernet-interfaces.interface.stp.priority | 581 | 352 | 933 |
| ethernet-interfaces.interface.lldp.trap | 11 | 879 | 890 |
| ethernet-interfaces.interface.flow-control-mode | 386 | 490 | 876 |
| ethernet-interfaces.interface.policy.ipv4-access-list-in | 279 | 594 | 873 |
| ethernet-interfaces.interface.llfc-flow-control.direction | 378 | 483 | 861 |
| ethernet-interfaces.interface.qos.broadcast-rate-limit.percentage | 272 | 492 | 764 |
| ethernet-interfaces.interface.udld.retries | 42 | 701 | 743 |
| ethernet-interfaces.interface.udld.interval | 30 | 680 | 710 |
| ethernet-interfaces.interface.qos.multicast-rate-limit.percentage | 215 | 480 | 695 |
| ethernet-interfaces.interface.ip.l3-counters | 532 | 14 | 546 |
| ethernet-interfaces.interface.aaa.authentication.bpdu-auth.mac-type | 537 | 0 | 537 |
| ethernet-interfaces.interface.pim-sparse.bfd-enable | 524 | 6 | 530 |
| ethernet-interfaces.interface.aaa.authentication.mda-data-clients-limit | 497 | 32 | 529 |
| ethernet-interfaces.interface.stp.rpvst.vlan-id | 7 | 494 | 501 |
| ethernet-interfaces.interface.stp.rpvst.cost | 7 | 492 | 499 |
| ethernet-interfaces.interface.nd-snooping.trust | 291 | 202 | 493 |
| ethernet-interfaces.interface.aaa.authentication.device-profile-secure | 401 | 90 | 491 |
| ethernet-interfaces.interface.port-security.macs | 312 | 178 | 490 |
| ethernet-interfaces.interface.qos.icmp-rate-limit.icmp-traffic-type | 342 | 133 | 475 |
| ethernet-interfaces.interface.qos.icmp-rate-limit.rate-type | 342 | 133 | 475 |
| ethernet-interfaces.interface.stp.rpvst-filter | 329 | 97 | 426 |
| ethernet-interfaces.interface.cdp.enable | 248 | 162 | 410 |
| ethernet-interfaces.interface.qos.icmp-rate-limit.bit-rate | 288 | 120 | 408 |
| ethernet-interfaces.interface.igmp-snooping-eth.fast-leave-vlan | 285 | 109 | 394 |
| ethernet-interfaces.interface.aaa.authentication.bpdu-auth.lldp | 370 | 19 | 389 |
| ethernet-interfaces.interface.aaa.authentication.bpdu-auth.cdp | 351 | 14 | 365 |
| ethernet-interfaces.interface.aaa.authorization.critical-voice-role | 294 | 55 | 349 |
| ethernet-interfaces.interface.poe.pd-class-override | 291 | 56 | 347 |
| ethernet-interfaces.interface.aaa.authentication.macauth-server-group | 28 | 296 | 324 |
| ethernet-interfaces.interface.poe.assigned-class | 239 | 64 | 303 |
| ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.packet-rate | 87 | 196 | 283 |
| ethernet-interfaces.interface.qos.schedule-profile | 44 | 237 | 281 |
| ethernet-interfaces.interface.sflow.enable | 223 | 52 | 275 |
| ethernet-interfaces.interface.poe.power-pairs | 164 | 91 | 255 |
| ethernet-interfaces.interface.policy.ipv6-access-list-in | 83 | 141 | 224 |
| ethernet-interfaces.interface.aaa.authorization.ubt-fallback-role | 210 | 2 | 212 |
| ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv4-monitor | 90 | 93 | 183 |
| ethernet-interfaces.interface.pvlan-port-mode | 145 | 30 | 175 |
| ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.percentage | 54 | 108 | 162 |
| ethernet-interfaces.interface.dpi-enable | 98 | 49 | 147 |
| ethernet-interfaces.interface.mac-notify-traps | 58 | 88 | 146 |
| ethernet-interfaces.interface.pim-sparse.source-address-any | 144 | 0 | 144 |
| ethernet-interfaces.interface.split-port-enable | 79 | 62 | 141 |
| ethernet-interfaces.interface.split-port-count | 76 | 62 | 138 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-supp.enable | 0 | 137 | 137 |
| ethernet-interfaces.interface.udld.mode.aruba-mode | 103 | 32 | 135 |
| ethernet-interfaces.interface.energy-efficient | 106 | 21 | 127 |
| ethernet-interfaces.interface.policy.mac-access-list-in | 76 | 49 | 125 |
| ethernet-interfaces.interface.port-security.sticky-macs.mac | 82 | 42 | 124 |
| ethernet-interfaces.interface.port-security.sticky-macs.vlan | 82 | 42 | 124 |
| ethernet-interfaces.interface.qos.dscp | 100 | 22 | 122 |
| ethernet-interfaces.interface.stp.cost | 98 | 22 | 120 |
| ethernet-interfaces.interface.client-limit-max | 112 | 2 | 114 |
| ethernet-interfaces.interface.policy.ipv4-access-list-out | 104 | 8 | 112 |
| ethernet-interfaces.interface.pim-sparse.dr-priority | 107 | 1 | 108 |
| ethernet-interfaces.interface.mvrp.enable | 90 | 10 | 100 |
| ethernet-interfaces.interface.aaa.authentication.dot1xauth-server-group | 28 | 71 | 99 |
| ethernet-interfaces.interface.speed-downshift-enable | 97 | 1 | 98 |
| ethernet-interfaces.interface.lldp.med-poe-priority-override | 78 | 19 | 97 |
| ethernet-interfaces.interface.igmp-snooping-eth.forward-vlan | 76 | 20 | 96 |
| ethernet-interfaces.interface.client-limit | 82 | 11 | 93 |
| ethernet-interfaces.interface.igmp.version | 87 | 5 | 92 |
| ethernet-interfaces.interface.qos.cos | 81 | 8 | 89 |
| ethernet-interfaces.interface.pim-sparse.hello-interval | 85 | 0 | 85 |
| ethernet-interfaces.interface.cdp.mode | 60 | 23 | 83 |
| ethernet-interfaces.interface.pim-sparse.hello-delay | 83 | 0 | 83 |
| ethernet-interfaces.interface.lacp.port-id | 52 | 26 | 78 |
| ethernet-interfaces.interface.pim-dense.enable | 76 | 1 | 77 |
| ethernet-interfaces.interface.ipv4-relay.server.ip | 64 | 11 | 75 |
| ethernet-interfaces.interface.ipv4-relay.server.ip-vrf | 64 | 11 | 75 |
| ethernet-interfaces.interface.ipv4-relay.server.vrf | 64 | 11 | 75 |
| ethernet-interfaces.interface.lldp.tlv.med.poe | 52 | 20 | 72 |
| ethernet-interfaces.interface.lldp.tlv.dot3tlv.poe-plus | 50 | 21 | 71 |
| ethernet-interfaces.interface.split-port-speed | 32 | 29 | 61 |
| ethernet-interfaces.interface.error-control | 39 | 22 | 61 |
| ethernet-interfaces.interface.qos.egress-rate | 41 | 18 | 59 |
| ethernet-interfaces.interface.portfilter.eth-ports | 39 | 10 | 49 |
| ethernet-interfaces.interface.portfilter.lag-ports | 39 | 10 | 49 |
| ethernet-interfaces.interface.ip-directed-broadcast-enable | 46 | 2 | 48 |
| ethernet-interfaces.interface.ip-source-lockdown.ipv4 | 11 | 34 | 45 |
| ethernet-interfaces.interface.qos.max-rate-units | 26 | 17 | 43 |
| ethernet-interfaces.interface.nd-snooping.ra-guard-policy | 41 | 0 | 41 |
| ethernet-interfaces.interface.qos.icmp-rate-limit.packet-rate | 34 | 4 | 38 |
| ethernet-interfaces.interface.ipv6.enable-default-link-local | 20 | 17 | 37 |
| ethernet-interfaces.interface.bfd.detect-multiplier | 20 | 15 | 35 |
| ethernet-interfaces.interface.vrrp.vrrp-profile-apply | 30 | 4 | 34 |
| ethernet-interfaces.interface.vlan-translate.origin | 15 | 19 | 34 |
| ethernet-interfaces.interface.vlan-translate.translated | 15 | 19 | 34 |
| ethernet-interfaces.interface.bfd.min-rx-interval | 18 | 15 | 33 |
| ethernet-interfaces.interface.bfd.min-tx-interval | 18 | 15 | 33 |
| ethernet-interfaces.interface.mka-policy | 23 | 8 | 31 |
| ethernet-interfaces.interface.ipv6.addresses.address | 18 | 12 | 30 |
| ethernet-interfaces.interface.macsec-policy | 23 | 7 | 30 |
| ethernet-interfaces.interface.qos.icmp-rate-limit.percentage | 20 | 9 | 29 |
| ethernet-interfaces.interface.lacp.port-priority | 23 | 5 | 28 |
| ethernet-interfaces.interface.pim-dense.source-address-any | 27 | 0 | 27 |
| ethernet-interfaces.interface.ptp.enable | 15 | 9 | 24 |
| ethernet-interfaces.interface.igmp-snooping-eth.forced-fast-leave-vlan | 4 | 17 | 21 |
| ethernet-interfaces.interface.vsx.shutdown-on-split | 4 | 17 | 21 |
| ethernet-interfaces.interface.aaa.authentication.client-auto-logoff-enable | 20 | 1 | 21 |
| ethernet-interfaces.interface.igmp.query-interval | 20 | 0 | 20 |
| ethernet-interfaces.interface.lldp.dcbx-disable | 4 | 15 | 19 |
| ethernet-interfaces.interface.speed-override | 10 | 5 | 15 |
| ethernet-interfaces.interface.priority-flow-control.priority-config.direction | 8 | 7 | 15 |
| ethernet-interfaces.interface.priority-flow-control.priority-config.priority | 8 | 7 | 15 |
| ethernet-interfaces.interface.llfc-flow-control.override-negotiation | 9 | 5 | 14 |
| ethernet-interfaces.interface.igmp.static-group | 10 | 3 | 13 |
| ethernet-interfaces.interface.lldp.tlv.med.network-policy | 10 | 2 | 12 |
| ethernet-interfaces.interface.arp.neighbor.address | 10 | 0 | 10 |
| ethernet-interfaces.interface.arp.neighbor.mac-address | 10 | 0 | 10 |
| ethernet-interfaces.interface.igmp.policy-in | 9 | 0 | 9 |
| ethernet-interfaces.interface.igmp.query-max-response-time | 7 | 0 | 7 |
| ethernet-interfaces.interface.igmp.robustness | 7 | 0 | 7 |
| ethernet-interfaces.interface.stp.mstp.instance-id | 3 | 3 | 6 |
| ethernet-interfaces.interface.igmp-snooping-eth.blocked-vlan | 2 | 3 | 5 |
| ethernet-interfaces.interface.arp.timeout | 4 | 1 | 5 |
| ethernet-interfaces.interface.lldp.tlv.dot3tlv.mac-phy | 2 | 3 | 5 |
| ethernet-interfaces.interface.llfc-flow-control.llfc-pool-id | 4 | 1 | 5 |
| ethernet-interfaces.interface.link-clock-narrow-tolerance | 0 | 5 | 5 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.canned-eap-success-enable | 4 | 0 | 4 |
| ethernet-interfaces.interface.igmp.last-member-query-interval | 4 | 0 | 4 |
| ethernet-interfaces.interface.stp.mstp.cost | 1 | 3 | 4 |
| ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.enable | 2 | 2 | 4 |
| ethernet-interfaces.interface.mvrp.registration | 3 | 1 | 4 |
| ethernet-interfaces.interface.policy.ipv6-access-list-out | 4 | 0 | 4 |
| ethernet-interfaces.interface.aaa.authorization.cached-critical-role-enable | 4 | 0 | 4 |
| ethernet-interfaces.interface.qos.threshold-profile | 1 | 2 | 3 |
| ethernet-interfaces.interface.igmp.querier-enable | 3 | 0 | 3 |
| ethernet-interfaces.interface.mld.enable | 3 | 0 | 3 |
| ethernet-interfaces.interface.pim6-sparse.enable | 3 | 0 | 3 |
| ethernet-interfaces.interface.ptp.vlan | 3 | 0 | 3 |
| ethernet-interfaces.interface.stp.rpvst.priority | 1 | 2 | 3 |
| ethernet-interfaces.interface.ip-unnumbered-interface-loopback | 3 | 0 | 3 |
| ethernet-interfaces.interface.pfc-watchdog | 3 | 0 | 3 |
| ethernet-interfaces.interface.lldp.tlv.elin-addr | 1 | 1 | 2 |
| ethernet-interfaces.interface.stp.mstp.priority | 2 | 0 | 2 |
| ethernet-interfaces.interface.pim-sparse.datapath-auto-include | 2 | 0 | 2 |
| ethernet-interfaces.interface.pim-sparse.source-address | 2 | 0 | 2 |
| ethernet-interfaces.interface.qos.burst | 2 | 0 | 2 |
| ethernet-interfaces.interface.ip-source-lockdown.ipv6 | 0 | 2 | 2 |
| ethernet-interfaces.interface.ipv6-neighbor-discovery.dad-attempts | 0 | 2 | 2 |
| ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.preference | 0 | 2 | 2 |
| ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-type | 0 | 2 | 2 |
| ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-value | 0 | 2 | 2 |
| ethernet-interfaces.interface.lldp.tlv.civic-addr.country-code | 0 | 2 | 2 |
| ethernet-interfaces.interface.lldp.tlv.civic-addr.what | 0 | 2 | 2 |
| ethernet-interfaces.interface.lldp.tlv.dot3tlv.mfs | 0 | 2 | 2 |
| ethernet-interfaces.interface.ipv4.secondary-ip | 1 | 0 | 1 |
| ethernet-interfaces.interface.dhcpv6-snooping.max-bindings | 1 | 0 | 1 |
| ethernet-interfaces.interface.igmp.strict-version | 1 | 0 | 1 |
| ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.advertise | 1 | 0 | 1 |
| ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.default | 1 | 0 | 1 |
| ethernet-interfaces.interface.lldp.tlv.management-tlv-ipv4-addr | 1 | 0 | 1 |
| ethernet-interfaces.interface.mld-snooping-eth.forward-vlan | 1 | 0 | 1 |
| ethernet-interfaces.interface.nd-snooping.max-bindings | 1 | 0 | 1 |
| ethernet-interfaces.interface.pim-sparse.bsr-boundary | 1 | 0 | 1 |
| ethernet-interfaces.interface.policy.mac-access-list-out | 1 | 0 | 1 |
| ethernet-interfaces.interface.aaa.authentication.dot1x-auth.macsec.enable | 0 | 1 | 1 |
| ethernet-interfaces.interface.cable-length | 0 | 1 | 1 |
| ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv6-monitor | 0 | 1 | 1 |
| ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.headroom | 0 | 1 | 1 |
| ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.priority | 0 | 1 | 1 |
| ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.xon-delta | 0 | 1 | 1 |
| ethernet-interfaces.interface.mvrp.forbidden-vlan-list | 0 | 1 | 1 |
| ethernet-interfaces.interface.loop-protect.re-enable-timer | 0 | 0 | 0 |
| ethernet-interfaces.interface.loop-protect.trap | 0 | 0 | 0 |
| ethernet-interfaces.interface.loop-protect.transmit-interval | 0 | 0 | 0 |
| ethernet-interfaces.interface.mvrp.join-timer | 0 | 0 | 0 |
| ethernet-interfaces.interface.mvrp.leaveall-timer | 0 | 0 | 0 |
| ethernet-interfaces.interface.mvrp.periodic-timer | 0 | 0 | 0 |
| ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.ip | 0 | 0 | 0 |
| ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.port | 0 | 0 | 0 |

</details>

### aruba-interface-portchannel

- **Total Leafs:** 119
- **Big Cluster Customers:** 545,227
- **Small Cluster Customers:** 218,052
- **Total Customer Impact:** 763,279

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| portchannels.interface.name | 54,775 | 21,239 | 76,014 |
| portchannels.interface.enable | 54,766 | 21,229 | 75,995 |
| portchannels.interface.switchport.interface-mode | 54,723 | 21,189 | 75,912 |
| portchannels.interface.switchport.native-vlan | 54,222 | 20,767 | 74,989 |
| portchannels.interface.port-list | 52,251 | 20,639 | 72,890 |
| portchannels.interface.trunk-type | 46,967 | 18,293 | 65,260 |
| portchannels.interface.lacp.mode | 46,966 | 18,289 | 65,255 |
| portchannels.interface.description | 44,587 | 16,254 | 60,841 |
| portchannels.interface.routing | 41,563 | 15,842 | 57,405 |
| portchannels.interface.switchport.trunk-vlan-all | 36,962 | 12,319 | 49,281 |
| portchannels.interface.switchport.trunk-vlan-ranges | 20,682 | 10,378 | 31,060 |
| portchannels.interface.dhcpv4-snooping.trust | 8,430 | 2,347 | 10,777 |
| portchannels.interface.lacp.rate | 2,708 | 2,284 | 4,992 |
| portchannels.interface.switchport.access-vlan | 2,515 | 1,909 | 4,424 |
| portchannels.interface.switchport.tag | 2,939 | 1,434 | 4,373 |
| portchannels.interface.loop-protect.enable | 2,045 | 1,987 | 4,032 |
| portchannels.interface.stp.loop-guard | 2,402 | 1,236 | 3,638 |
| portchannels.interface.qos.trust | 2,130 | 301 | 2,431 |
| portchannels.interface.dynamic-arp-inspection.trust | 1,413 | 503 | 1,916 |
| portchannels.interface.stp.root-guard | 1,204 | 662 | 1,866 |
| portchannels.interface.mode | 1,692 | 107 | 1,799 |
| portchannels.interface.lacp.fallback-static | 1,394 | 203 | 1,597 |
| portchannels.interface.qos.broadcast-rate-limit.rate-type | 366 | 1,147 | 1,513 |
| portchannels.interface.qos.multicast-rate-limit.rate-type | 160 | 1,086 | 1,246 |
| portchannels.interface.stp.bpdu-filter | 844 | 321 | 1,165 |
| portchannels.interface.qos.broadcast-rate-limit.bit-rate | 151 | 959 | 1,110 |
| portchannels.interface.stp.admin-edge-port | 621 | 309 | 930 |
| portchannels.interface.qos.multicast-rate-limit.bit-rate | 27 | 889 | 916 |
| portchannels.interface.dhcpv6-snooping.trust | 724 | 174 | 898 |
| portchannels.interface.stp.link-type | 820 | 59 | 879 |
| portchannels.interface.lacp.fallback | 538 | 299 | 837 |
| portchannels.interface.loop-protect.action | 244 | 579 | 823 |
| portchannels.interface.ipv4.address | 320 | 192 | 512 |
| portchannels.interface.stp.rpvst-filter | 329 | 80 | 409 |
| portchannels.interface.stp.bpdu-guard | 269 | 136 | 405 |
| portchannels.interface.qos.broadcast-rate-limit.packet-rate | 191 | 161 | 352 |
| portchannels.interface.qos.unknown-unicast-rate-limit.rate-type | 41 | 291 | 332 |
| portchannels.interface.vrf-forwarding | 209 | 89 | 298 |
| portchannels.interface.stp.tcn-guard | 171 | 87 | 258 |
| portchannels.interface.nd-snooping.trust | 227 | 29 | 256 |
| portchannels.interface.aaa-lag.authentication-lag.device-profile-secure | 202 | 40 | 242 |
| portchannels.interface.hashing | 107 | 134 | 241 |
| portchannels.interface.qos.multicast-rate-limit.packet-rate | 116 | 116 | 232 |
| portchannels.interface.loop-protect.vlans | 54 | 172 | 226 |
| portchannels.interface.qos.unknown-unicast-rate-limit.bit-rate | 11 | 181 | 192 |
| portchannels.interface.ip.mtu | 174 | 15 | 189 |
| portchannels.interface.qos.schedule-profile | 7 | 181 | 188 |
| portchannels.interface.client-limit | 130 | 41 | 171 |
| portchannels.interface.stp.priority | 126 | 15 | 141 |
| portchannels.interface.sflow.enable | 112 | 13 | 125 |
| portchannels.interface.ip.l3-counters | 106 | 3 | 109 |
| portchannels.interface.qos.multicast-rate-limit.percentage | 17 | 81 | 98 |
| portchannels.interface.mac-notify-traps | 30 | 57 | 87 |
| portchannels.interface.qos.icmp-rate-limit.icmp-traffic-type | 7 | 78 | 85 |
| portchannels.interface.qos.icmp-rate-limit.rate-type | 7 | 78 | 85 |
| portchannels.interface.qos.icmp-rate-limit.bit-rate | 4 | 75 | 79 |
| portchannels.interface.policy.ipv4-access-list-in | 47 | 29 | 76 |
| portchannels.interface.qos.unknown-unicast-rate-limit.packet-rate | 21 | 53 | 74 |
| portchannels.interface.qos.unknown-unicast-rate-limit.percentage | 9 | 57 | 66 |
| portchannels.interface.qos.broadcast-rate-limit.percentage | 24 | 28 | 52 |
| portchannels.interface.ipfix-flow-monitor-in.ipv4-monitor | 11 | 39 | 50 |
| portchannels.interface.stp.cost | 28 | 19 | 47 |
| portchannels.interface.policy.ipv6-access-list-out | 0 | 47 | 47 |
| portchannels.interface.igmp-snooping-lag.forward-vlan | 25 | 20 | 45 |
| portchannels.interface.pvlan-port-mode | 31 | 13 | 44 |
| portchannels.interface.policy.ipv4-access-list-out | 34 | 6 | 40 |
| portchannels.interface.update-interval | 12 | 24 | 36 |
| portchannels.interface.profile-name | 4 | 28 | 32 |
| portchannels.interface.aaa-lag.authentication-lag.bpdu-bypass.lldp | 16 | 15 | 31 |
| portchannels.interface.vlan-translate.origin | 29 | 1 | 30 |
| portchannels.interface.vlan-translate.translated | 29 | 1 | 30 |
| portchannels.interface.aaa-lag.authentication-lag.bpdu-bypass.cdp | 9 | 15 | 24 |
| portchannels.interface.aaa-lag.authentication-lag.client-limit | 13 | 5 | 18 |
| portchannels.interface.policy.mac-access-list-in | 0 | 16 | 16 |
| portchannels.interface.ipv6.enable-default-link-local | 15 | 0 | 15 |
| portchannels.interface.ptp.enable | 6 | 7 | 13 |
| portchannels.interface.aaa-lag.authentication-lag.allow-flood-traffic | 6 | 6 | 12 |
| portchannels.interface.macsec-policy | 8 | 2 | 10 |
| portchannels.interface.mka-policy | 8 | 2 | 10 |
| portchannels.interface.pim-sparse.enable | 0 | 8 | 8 |
| portchannels.interface.mvrp.enable | 8 | 0 | 8 |
| portchannels.interface.stp.rpvst-guard | 6 | 1 | 7 |
| portchannels.interface.ipv6.addresses.address | 6 | 1 | 7 |
| portchannels.interface.igmp-snooping-lag.blocked-vlan | 5 | 0 | 5 |
| portchannels.interface.qos.icmp-rate-limit.packet-rate | 1 | 3 | 4 |
| portchannels.interface.stp.rpvst.vlan-id | 0 | 4 | 4 |
| portchannels.interface.aaa-lag.authentication-lag.auth-mode | 3 | 0 | 3 |
| portchannels.interface.policy.ipv6-access-list-in | 2 | 1 | 3 |
| portchannels.interface.stp.mstp.instance-id | 3 | 0 | 3 |
| portchannels.interface.qos.dscp | 0 | 3 | 3 |
| portchannels.interface.pim-sparse.source-address-any | 0 | 3 | 3 |
| portchannels.interface.qos.icmp-rate-limit.percentage | 2 | 0 | 2 |
| portchannels.interface.qos.egress-rate | 0 | 2 | 2 |
| portchannels.interface.qos.max-rate-units | 0 | 2 | 2 |
| portchannels.interface.stp.mstp.cost | 2 | 0 | 2 |
| portchannels.interface.igmp.enable | 0 | 2 | 2 |
| portchannels.interface.stp.rpvst.cost | 0 | 2 | 2 |
| portchannels.interface.stp.rpvst.priority | 0 | 2 | 2 |
| portchannels.interface.aaa-lag.authentication-lag.bpdu-auth.mac-type | 0 | 2 | 2 |
| portchannels.interface.stp.mstp.priority | 1 | 0 | 1 |
| portchannels.interface.mvrp.forbidden-vlan-list | 1 | 0 | 1 |
| portchannels.interface.mvrp.registration | 1 | 0 | 1 |
| portchannels.interface.nd-snooping.max-bindings | 1 | 0 | 1 |
| portchannels.interface.portfilter.eth-ports | 1 | 0 | 1 |
| portchannels.interface.portfilter.lag-ports | 1 | 0 | 1 |
| portchannels.interface.ipfix-flow-monitor-in.ipv6-monitor | 0 | 1 | 1 |
| portchannels.interface.pim-dense.enable | 0 | 1 | 1 |
| portchannels.interface.pim6-dense.enable | 0 | 1 | 1 |
| portchannels.interface.qos.cos | 0 | 1 | 1 |
| portchannels.interface.client-limit-max | 0 | 1 | 1 |
| portchannels.interface.aaa-lag.security-violation.action | 0 | 0 | 0 |
| portchannels.interface.aaa-lag.security-violation.recovery-timer | 0 | 0 | 0 |
| portchannels.interface.aaa-lag.security-violation.shutdown-recovery-enable | 0 | 0 | 0 |
| portchannels.interface.arp.timeout | 0 | 0 | 0 |
| portchannels.interface.bfd.detect-multiplier | 0 | 0 | 0 |
| portchannels.interface.bfd.min-rx-interval | 0 | 0 | 0 |
| portchannels.interface.bfd.min-tx-interval | 0 | 0 | 0 |
| portchannels.interface.qos.threshold-profile | 0 | 0 | 0 |
| portchannels.interface.vrrp.vrrp-profile-apply | 0 | 0 | 0 |

</details>

### aruba-switch-stack

- **Total Leafs:** 11
- **Big Cluster Customers:** 423,626
- **Small Cluster Customers:** 141,878
- **Total Customer Impact:** 565,504

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| stacks.stack.name | 82,414 | 27,664 | 110,078 |
| stacks.stack.members.id | 82,414 | 27,663 | 110,077 |
| stacks.stack.members.sku | 82,414 | 27,663 | 110,077 |
| stacks.stack.platform | 82,414 | 27,663 | 110,077 |
| stacks.stack.members.links.link1.interfaces | 31,623 | 10,851 | 42,474 |
| stacks.stack.members.links.link2.interfaces | 29,470 | 9,810 | 39,280 |
| stacks.stack.secondary-member | 25,713 | 8,971 | 34,684 |
| stacks.stack.split-detection-method | 6,368 | 1,403 | 7,771 |
| stacks.stack.members.hw-profile | 451 | 0 | 451 |
| stacks.stack.members.links.link1.description | 182 | 104 | 286 |
| stacks.stack.members.links.link2.description | 163 | 86 | 249 |

### aruba-vsf-template

- **Total Leafs:** 5
- **Big Cluster Customers:** 278,951
- **Small Cluster Customers:** 92,092
- **Total Customer Impact:** 371,043

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| vsf-templates.template.name | 82,290 | 27,264 | 109,554 |
| vsf-templates.template.members.id | 82,290 | 27,226 | 109,516 |
| vsf-templates.template.members.sku | 82,290 | 27,226 | 109,516 |
| vsf-templates.template.secondary-member | 25,713 | 8,973 | 34,686 |
| vsf-templates.template.split-detection-method | 6,368 | 1,403 | 7,771 |

### aruba-qos-dscp

- **Total Leafs:** 7
- **Big Cluster Customers:** 91,029
- **Small Cluster Customers:** 0
- **Total Customer Impact:** 91,029

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-dscp.profile.dscp-map.dscp | 22,856 | 0 | 22,856 |
| qos-dscp.profile.name | 22,856 | 0 | 22,856 |
| qos-dscp.profile.dscp-map.local-priority | 22,223 | 0 | 22,223 |
| qos-dscp.profile.dscp-map.color | 19,391 | 0 | 19,391 |
| qos-dscp.profile.dscp-map.name | 2,957 | 0 | 2,957 |
| qos-dscp.profile.dscp-map.cos | 633 | 0 | 633 |
| qos-dscp.profile.dscp-map.cos-override | 113 | 0 | 113 |

### aruba-vlan-range

- **Total Leafs:** 21
- **Big Cluster Customers:** 66,223
- **Small Cluster Customers:** 23,383
- **Total Customer Impact:** 89,606

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| layer2-vlan-range.client-ip-tracker-enable | 30,301 | 12,849 | 43,150 |
| layer2-vlan-range.igmp.snooping | 15,311 | 4,317 | 19,628 |
| layer2-vlan-range.dhcpv4-snooping.enable | 12,903 | 3,812 | 16,715 |
| layer2-vlan-range.igmp.version | 4,883 | 1,435 | 6,318 |
| layer2-vlan-range.dhcpv6-snooping.enable | 1,599 | 616 | 2,215 |
| layer2-vlan-range.igmp.policy-in | 464 | 1 | 465 |
| layer2-vlan-range.policy-in | 63 | 180 | 243 |
| layer2-vlan-range.enable | 148 | 87 | 235 |
| layer2-vlan-range.mld.snooping | 152 | 21 | 173 |
| layer2-vlan-range.igmp.preprogram-starg-flow | 125 | 26 | 151 |
| layer2-vlan-range.igmp.static-group | 103 | 6 | 109 |
| layer2-vlan-range.policy-out | 65 | 4 | 69 |
| layer2-vlan-range.nd-snooping.nd-guard | 43 | 4 | 47 |
| layer2-vlan-range.nd-snooping.ra-drop | 27 | 1 | 28 |
| layer2-vlan-range.nd-snooping.ra-guard-log | 16 | 9 | 25 |
| layer2-vlan-range.dhcpv4-snooping.ip-binding-enable | 13 | 0 | 13 |
| layer2-vlan-range.nd-snooping.allow-bindings-on-trusted-ports | 0 | 10 | 10 |
| layer2-vlan-range.voice-enable | 6 | 0 | 6 |
| layer2-vlan-range.dhcpv6-snooping.allow-bindings-on-trusted-ports | 0 | 4 | 4 |
| layer2-vlan-range.dynamic-arp-inspection.enable | 0 | 1 | 1 |
| layer2-vlan-range.destination-guard.enable | 1 | 0 | 1 |

</details>

### aruba-loop-protect

- **Total Leafs:** 4
- **Big Cluster Customers:** 32,928
- **Small Cluster Customers:** 15,827
- **Total Customer Impact:** 48,755

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| loop-protect.profile.name | 14,648 | 6,232 | 20,880 |
| loop-protect.profile.re-enable-timer | 11,211 | 5,080 | 16,291 |
| loop-protect.profile.trap | 6,137 | 2,741 | 8,878 |
| loop-protect.profile.transmit-interval | 932 | 1,774 | 2,706 |

### aruba-aaa-macauth

- **Total Leafs:** 7
- **Big Cluster Customers:** 36,127
- **Small Cluster Customers:** 10,880
- **Total Customer Impact:** 47,007

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| macauth.profile.name | 34,254 | 10,761 | 45,015 |
| macauth.profile.enable | 1,594 | 68 | 1,662 |
| macauth.profile.quiet-period | 89 | 10 | 99 |
| macauth.profile.reauth-period | 88 | 10 | 98 |
| macauth.profile.cached-reauth-period | 88 | 10 | 98 |
| macauth.profile.reauth-enable | 8 | 10 | 18 |
| macauth.profile.cached-reauth-enable | 6 | 11 | 17 |

### aruba-aaa-dot1xauth

- **Total Leafs:** 13
- **Big Cluster Customers:** 35,132
- **Small Cluster Customers:** 10,423
- **Total Customer Impact:** 45,555

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| dot1xauth.profile.name | 33,234 | 10,255 | 43,489 |
| dot1xauth.profile.enable | 1,594 | 70 | 1,664 |
| dot1xauth.profile.reauth-period | 88 | 11 | 99 |
| dot1xauth.profile.quiet-period | 89 | 10 | 99 |
| dot1xauth.profile.cached-reauth-period | 88 | 10 | 98 |
| dot1xauth.profile.eapol-max-requests | 9 | 15 | 24 |
| dot1xauth.profile.reauth-enable | 8 | 12 | 20 |
| dot1xauth.profile.max-retries | 6 | 12 | 18 |
| dot1xauth.profile.eapol-timeout | 7 | 10 | 17 |
| dot1xauth.profile.cached-reauth-enable | 6 | 11 | 17 |
| dot1xauth.profile.discovery-period | 2 | 4 | 6 |
| dot1xauth.profile.initial-auth-response-timeout | 0 | 3 | 3 |
| dot1xauth.profile.canned-eap-success-enable | 1 | 0 | 1 |

### aruba-vsx

- **Total Leafs:** 17
- **Big Cluster Customers:** 24,677
- **Small Cluster Customers:** 13,843
- **Total Customer Impact:** 38,520

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| vsx-profiles.vsx.name | 3,216 | 1,821 | 5,037 |
| vsx-profiles.vsx.peer1.role | 3,216 | 1,803 | 5,019 |
| vsx-profiles.vsx.peer2.role | 3,216 | 1,803 | 5,019 |
| vsx-profiles.vsx.peer1.keepalive-device.peer-ip | 2,869 | 1,639 | 4,508 |
| vsx-profiles.vsx.peer1.keepalive-device.source-ip | 2,869 | 1,639 | 4,508 |
| vsx-profiles.vsx.peer2.keepalive-device.peer-ip | 2,869 | 1,639 | 4,508 |
| vsx-profiles.vsx.peer2.keepalive-device.source-ip | 2,869 | 1,639 | 4,508 |
| vsx-profiles.vsx.sync-features.system-mac | 2,768 | 1,492 | 4,260 |
| vsx-profiles.vsx.sync-features.linkup-delay-timer | 471 | 241 | 712 |
| vsx-profiles.vsx.sync-features.split-recovery-disable | 70 | 29 | 99 |
| vsx-profiles.vsx.sync-features.inter-switch-link-timers.hold-time | 62 | 26 | 88 |
| vsx-profiles.vsx.sync-features.inter-switch-link-timers.dead-interval | 57 | 26 | 83 |
| vsx-profiles.vsx.sync-features.inter-switch-link-timers.hello-interval | 55 | 26 | 81 |
| vsx-profiles.vsx.sync-features.inter-switch-link-timers.peer-detect-interval | 43 | 8 | 51 |
| vsx-profiles.vsx.sync-features.keepalive.dead-interval | 10 | 8 | 18 |
| vsx-profiles.vsx.sync-features.keepalive.hello-interval | 9 | 4 | 13 |
| vsx-profiles.vsx.sync-features.keepalive.udp-port | 8 | 0 | 8 |

</details>

### aruba-named-condition

- **Total Leafs:** 3
- **Big Cluster Customers:** 24,403
- **Small Cluster Customers:** 8,714
- **Total Customer Impact:** 33,117

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| named-conditions.named-condition.condition-rule.position | 10,929 | 4,097 | 15,026 |
| named-conditions.named-condition.name | 10,929 | 4,097 | 15,026 |
| named-conditions.named-condition.condition-rule.description | 2,545 | 520 | 3,065 |

### aruba-vsx-pair

- **Total Leafs:** 18
- **Big Cluster Customers:** 20,798
- **Small Cluster Customers:** 11,405
- **Total Customer Impact:** 32,203

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| vsx-config.vsx.name | 3,216 | 1,828 | 5,044 |
| vsx-config.vsx.role | 3,216 | 1,803 | 5,019 |
| vsx-config.vsx.inter-switch-link.interface-lag | 3,194 | 1,809 | 5,003 |
| vsx-config.vsx.system-mac | 2,768 | 1,492 | 4,260 |
| vsx-config.vsx.keepalive.peer-ip | 2,532 | 1,363 | 3,895 |
| vsx-config.vsx.keepalive.source-ip | 2,532 | 1,363 | 3,895 |
| vsx-config.vsx.keepalive.vrf-ref | 2,532 | 1,363 | 3,895 |
| vsx-config.vsx.linkup-delay-timer | 471 | 241 | 712 |
| vsx-config.vsx.split-recovery-disable | 70 | 29 | 99 |
| vsx-config.vsx.inter-switch-link.hold-time | 62 | 26 | 88 |
| vsx-config.vsx.inter-switch-link.dead-interval | 57 | 26 | 83 |
| vsx-config.vsx.inter-switch-link.hello-interval | 55 | 26 | 81 |
| vsx-config.vsx.inter-switch-link.peer-detect-interval | 43 | 8 | 51 |
| vsx-config.vsx.inter-switch-link.interface-eth | 17 | 15 | 32 |
| vsx-config.vsx.keepalive.dead-interval | 10 | 8 | 18 |
| vsx-config.vsx.keepalive.hello-interval | 9 | 4 | 13 |
| vsx-config.vsx.keepalive.udp-port | 8 | 0 | 8 |
| vsx-config.vsx.linkup-delay-timer-exclude | 6 | 1 | 7 |

</details>

### aruba-job-scheduler

- **Total Leafs:** 31
- **Big Cluster Customers:** 18,246
- **Small Cluster Customers:** 7,606
- **Total Customer Impact:** 25,852

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| job-scheduler.schedule.name | 1,510 | 562 | 2,072 |
| job-scheduler.schedule.job.job-name | 1,495 | 555 | 2,050 |
| job-scheduler.schedule.job.entry.sequence-number | 1,458 | 542 | 2,000 |
| job-scheduler.schedule.job.entry.cli-command | 1,458 | 542 | 2,000 |
| job-scheduler.schedule.job.entry.type | 1,458 | 542 | 2,000 |
| job-scheduler.schedule.trigger-type | 1,424 | 525 | 1,949 |
| job-scheduler.schedule.schedule-entry.schedule-job | 1,407 | 520 | 1,927 |
| job-scheduler.schedule.schedule-entry.sequence-number | 1,407 | 520 | 1,927 |
| job-scheduler.schedule.frequency | 669 | 337 | 1,006 |
| job-scheduler.schedule.start-time-on | 669 | 337 | 1,006 |
| job-scheduler.schedule.trigger-on | 669 | 337 | 1,006 |
| job-scheduler.schedule.start-date-on | 669 | 333 | 1,002 |
| job-scheduler.schedule.start-date-at | 786 | 77 | 863 |
| job-scheduler.schedule.start-time-at | 786 | 77 | 863 |
| job-scheduler.schedule.trigger-at | 786 | 77 | 863 |
| job-scheduler.schedule.trigger-on-weekly | 537 | 240 | 777 |
| job-scheduler.schedule.week-day | 537 | 240 | 777 |
| job-scheduler.schedule.description | 159 | 266 | 425 |
| job-scheduler.schedule.job.description | 183 | 175 | 358 |
| job-scheduler.schedule.trigger-on-monthly | 2 | 172 | 174 |
| job-scheduler.schedule.month-day | 2 | 171 | 173 |
| job-scheduler.schedule.trigger-every | 9 | 111 | 120 |
| job-scheduler.schedule.start-time-every | 9 | 110 | 119 |
| job-scheduler.schedule.start-date-every | 9 | 106 | 115 |
| job-scheduler.schedule.job.entry.cli-delay | 75 | 8 | 83 |
| job-scheduler.schedule.days | 5 | 70 | 75 |
| job-scheduler.schedule.count | 57 | 12 | 69 |
| job-scheduler.schedule.minutes | 3 | 39 | 42 |
| job-scheduler.schedule.enable | 4 | 0 | 4 |
| job-scheduler.schedule.job.enable | 3 | 1 | 4 |
| job-scheduler.schedule.hours | 1 | 2 | 3 |

</details>

### aruba-qos-schedule

- **Total Leafs:** 15
- **Big Cluster Customers:** 18,619
- **Small Cluster Customers:** 6,457
- **Total Customer Impact:** 25,076

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-schedules.profile.sched-profile-name | 4,708 | 1,639 | 6,347 |
| qos-schedules.profile.strict.queue | 4,611 | 0 | 4,611 |
| qos-schedules.profile.dwrr.queue | 4,260 | 0 | 4,260 |
| qos-schedules.profile.dwrr.weight | 4,260 | 0 | 4,260 |
| qos-schedules.profile.sched-entries.algorithm | 0 | 1,610 | 1,610 |
| qos-schedules.profile.sched-entries.queue | 0 | 1,610 | 1,610 |
| qos-schedules.profile.sched-entries.weight | 0 | 1,248 | 1,248 |
| qos-schedules.profile.min-bandwidths.minimum-bandwidth | 377 | 0 | 377 |
| qos-schedules.profile.min-bandwidths.queue | 377 | 0 | 377 |
| qos-schedules.profile.sched-entries.minimum-bandwidth | 0 | 253 | 253 |
| qos-schedules.profile.sched-entries.max-bandwidth-kbps | 0 | 48 | 48 |
| qos-schedules.profile.sched-entries.max-bandwidth-percent | 0 | 47 | 47 |
| qos-schedules.profile.strict.max-bandwidth-kbps | 19 | 0 | 19 |
| qos-schedules.profile.strict.max-bandwidth-percent | 7 | 0 | 7 |
| qos-schedules.profile.sched-entries.burst | 0 | 2 | 2 |

### aruba-certificate-rcp

- **Total Leafs:** 7
- **Big Cluster Customers:** 16,139
- **Small Cluster Customers:** 3,670
- **Total Customer Impact:** 19,809

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| certificate-rcp.ta-profile.name | 15,530 | 3,473 | 19,003 |
| certificate-rcp.ta-profile.ocsp.vrf | 492 | 164 | 656 |
| certificate-rcp.ta-profile.ocsp.enforcement-level | 105 | 13 | 118 |
| certificate-rcp.ta-profile.rcp-primary-method | 0 | 16 | 16 |
| certificate-rcp.ta-profile.ocsp.disable-nonce | 12 | 1 | 13 |
| certificate-rcp.ta-profile.ocsp.primary-url | 0 | 2 | 2 |
| certificate-rcp.ta-profile.ocsp.secondary-url | 0 | 1 | 1 |

### aruba-snmp-trap

- **Total Leafs:** 5
- **Big Cluster Customers:** 11,759
- **Small Cluster Customers:** 7,776
- **Total Customer Impact:** 19,535

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| snmp-trap.profile.name | 2,896 | 1,965 | 4,861 |
| snmp-trap.profile.trap.id | 2,896 | 1,965 | 4,861 |
| snmp-trap.profile.trap.enable | 2,499 | 1,130 | 3,629 |
| snmp-trap.profile.trap.snmp-server-trap | 1,734 | 1,358 | 3,092 |
| snmp-trap.profile.trap.vrf | 1,734 | 1,358 | 3,092 |

### aruba-port-security

- **Total Leafs:** 4
- **Big Cluster Customers:** 14,466
- **Small Cluster Customers:** 4,693
- **Total Customer Impact:** 19,159

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| port-security.policy.name | 4,654 | 1,719 | 6,373 |
| port-security.policy.enable | 4,155 | 1,407 | 5,562 |
| port-security.policy.client-limit | 3,666 | 1,089 | 4,755 |
| port-security.policy.sticky-mac-enable | 1,991 | 478 | 2,469 |

### aruba-ip-icmp-tcp

- **Total Leafs:** 4
- **Big Cluster Customers:** 18,300
- **Small Cluster Customers:** 0
- **Total Customer Impact:** 18,300

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ip-icmp-tcp.profile.name | 9,008 | 0 | 9,008 |
| ip-icmp-tcp.profile.ip-icmp.redirect | 9,005 | 0 | 9,005 |
| ip-icmp-tcp.profile.ip-icmp.unreachable | 278 | 0 | 278 |
| ip-icmp-tcp.profile.ip-icmp.throttle | 9 | 0 | 9 |

### aruba-qos-queue

- **Total Leafs:** 6
- **Big Cluster Customers:** 13,595
- **Small Cluster Customers:** 3,628
- **Total Customer Impact:** 17,223

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-queues.profile.q-profile-name | 3,939 | 1,150 | 5,089 |
| qos-queues.profile.priority.queue | 3,764 | 1,008 | 4,772 |
| qos-queues.profile.priority.local-priority | 3,354 | 0 | 3,354 |
| qos-queues.profile.priority.name | 2,198 | 472 | 2,670 |
| qos-queues.profile.priority.priorities | 0 | 998 | 998 |
| qos-queues.profile.priority.cos | 340 | 0 | 340 |

### aruba-switch-profiles

- **Total Leafs:** 2
- **Big Cluster Customers:** 10,196
- **Small Cluster Customers:** 6,422
- **Total Customer Impact:** 16,618

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| switch-profiles.profile.name | 5,098 | 3,211 | 8,309 |
| switch-profiles.profile.selected | 5,098 | 3,211 | 8,309 |

### aruba-interface-vxlan

- **Total Leafs:** 13
- **Big Cluster Customers:** 13,834
- **Small Cluster Customers:** 1,427
- **Total Customer Impact:** 15,261

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| vxlan.profile.name | 2,148 | 242 | 2,390 |
| vxlan.profile.src-ipv4 | 2,128 | 234 | 2,362 |
| vxlan.profile.vni.id | 2,044 | 236 | 2,280 |
| vxlan.profile.enable | 2,025 | 234 | 2,259 |
| vxlan.profile.vni.vlan | 1,792 | 191 | 1,983 |
| vxlan.profile.vni.symmetric-routing | 1,744 | 121 | 1,865 |
| vxlan.profile.vni.vrf | 1,744 | 121 | 1,865 |
| vxlan.profile.description | 81 | 6 | 87 |
| vxlan.profile.enable-counters | 65 | 18 | 83 |
| vxlan.profile.bridging-mode | 59 | 15 | 74 |
| vxlan.profile.loop-protect-vlans | 0 | 7 | 7 |
| vxlan.profile.loop-protect | 4 | 0 | 4 |
| vxlan.profile.mac-notify-traps | 0 | 2 | 2 |

### aruba-object-group

- **Total Leafs:** 11
- **Big Cluster Customers:** 10,336
- **Small Cluster Customers:** 4,502
- **Total Customer Impact:** 14,838

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| object-groups.group.name | 1,781 | 718 | 2,499 |
| object-groups.group.type | 1,781 | 718 | 2,499 |
| object-groups.group.items.index | 1,781 | 718 | 2,499 |
| object-groups.group.items.address-type | 1,532 | 699 | 2,231 |
| object-groups.group.items.ipv4-address | 1,273 | 656 | 1,929 |
| object-groups.group.items.ipv4-subnet-address | 1,108 | 564 | 1,672 |
| object-groups.group.items.ports.operator | 649 | 165 | 814 |
| object-groups.group.items.ports.min | 353 | 165 | 518 |
| object-groups.group.items.ports.max | 78 | 93 | 171 |
| object-groups.group.vrf | 0 | 6 | 6 |
| object-groups.group.items.ipv4-prefix | 0 | 0 | 0 |

### aruba-lldp

- **Total Leafs:** 25
- **Big Cluster Customers:** 12,573
- **Small Cluster Customers:** 1,391
- **Total Customer Impact:** 13,964

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| lldp.profile.name | 2,929 | 653 | 3,582 |
| lldp.profile.tlv.basic.port-descr | 1,047 | 133 | 1,180 |
| lldp.profile.tlv.basic.management-addr | 1,022 | 2 | 1,024 |
| lldp.profile.tlv.basic.system-descr | 1,021 | 2 | 1,023 |
| lldp.profile.tlv.dot1.port-vlan-id | 1,019 | 2 | 1,021 |
| lldp.profile.tlv.dot1.port-vlan-name | 1,008 | 2 | 1,010 |
| lldp.profile.tlv.oui | 941 | 2 | 943 |
| lldp.profile.lldp-trap-enable | 715 | 217 | 932 |
| lldp.profile.tlv.dot1.link-aggregation | 923 | 2 | 925 |
| lldp.profile.tlv.basic.system-cap | 831 | 2 | 833 |
| lldp.profile.management-ip-address | 303 | 156 | 459 |
| lldp.profile.transmit-interval | 415 | 36 | 451 |
| lldp.profile.disable | 303 | 71 | 374 |
| lldp.profile.reinit-delay | 37 | 14 | 51 |
| lldp.profile.dcbx-enable | 20 | 20 | 40 |
| lldp.profile.management-vlan | 10 | 29 | 39 |
| lldp.profile.hold-multiplier | 14 | 2 | 16 |
| lldp.profile.tlv-dcbx-app.app-tlv.port-number | 3 | 8 | 11 |
| lldp.profile.tlv-dcbx-app.app-tlv.priority | 3 | 8 | 11 |
| lldp.profile.tlv-dcbx-app.app-tlv.protocol | 3 | 8 | 11 |
| lldp.profile.tlv-dcbx-app.app-tlv.protocol-port-number | 3 | 8 | 11 |
| lldp.profile.dcbx-version | 1 | 9 | 10 |
| lldp.profile.neighbor-last-update-enable | 1 | 3 | 4 |
| lldp.profile.tlv.basic.system-name | 0 | 2 | 2 |
| lldp.profile.transmit-delay | 1 | 0 | 1 |

</details>

### aruba-device-certificate

- **Total Leafs:** 16
- **Big Cluster Customers:** 11,741
- **Small Cluster Customers:** 2,018
- **Total Customer Impact:** 13,759

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| device-certificates.device-certificate.name | 3,053 | 559 | 3,612 |
| device-certificates.device-certificate.app-usage | 2,908 | 523 | 3,431 |
| device-certificates.device-certificate.subject.common-name | 1,612 | 146 | 1,758 |
| device-certificates.device-certificate.cert-key-type | 1,056 | 96 | 1,152 |
| device-certificates.device-certificate.est-profile | 1,064 | 31 | 1,095 |
| device-certificates.device-certificate.ecdsa-curve-size | 1,050 | 0 | 1,050 |
| device-certificates.device-certificate.subject.org | 196 | 130 | 326 |
| device-certificates.device-certificate.subject.locality | 195 | 126 | 321 |
| device-certificates.device-certificate.subject.state | 174 | 130 | 304 |
| device-certificates.device-certificate.subject.org-unit | 174 | 124 | 298 |
| device-certificates.device-certificate.rsa-key-length | 6 | 96 | 102 |
| device-certificates.device-certificate.ext-key-usage | 73 | 23 | 96 |
| device-certificates.device-certificate.key-usage | 73 | 23 | 96 |
| device-certificates.device-certificate.subject-alt-name-dns | 70 | 5 | 75 |
| device-certificates.device-certificate.subject.country | 36 | 4 | 40 |
| device-certificates.device-certificate.subject-alt-name-ip | 1 | 2 | 3 |

</details>

### aruba-hardware-module-profile

- **Total Leafs:** 6
- **Big Cluster Customers:** 7,861
- **Small Cluster Customers:** 4,860
- **Total Customer Impact:** 12,721

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| hardware-modules.hw-profile.name | 2,980 | 1,494 | 4,474 |
| hardware-modules.hw-profile.interface-group-speed-profile.group-id | 1,825 | 1,153 | 2,978 |
| hardware-modules.hw-profile.interface-group-speed-profile.speed | 1,825 | 1,153 | 2,978 |
| hardware-modules.hw-profile.always-on-poe | 1,081 | 324 | 1,405 |
| hardware-modules.hw-profile.member-or-slot-ids | 0 | 491 | 491 |
| hardware-modules.hw-profile.quick-poe | 150 | 245 | 395 |

### aruba-system-info

- **Total Leafs:** 2
- **Big Cluster Customers:** 7,020
- **Small Cluster Customers:** 3,223
- **Total Customer Impact:** 10,243

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| system-info.sys-description | 6,653 | 2,970 | 9,623 |
| system-info.snmpv3-local-engine-id | 367 | 253 | 620 |

### aruba-management-user-group

- **Total Leafs:** 6
- **Big Cluster Customers:** 5,959
- **Small Cluster Customers:** 2,561
- **Total Customer Impact:** 8,520

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| management-user-groups.user-group.name | 1,808 | 647 | 2,455 |
| management-user-groups.user-group.rule.rbac.action | 1,339 | 588 | 1,927 |
| management-user-groups.user-group.rule.rbac.match-command | 1,339 | 588 | 1,927 |
| management-user-groups.user-group.rule.seq-number | 1,339 | 588 | 1,927 |
| management-user-groups.user-group.rule.description | 79 | 150 | 229 |
| management-user-groups.user-group.inherit-group | 55 | 0 | 55 |

### aruba-switch-chassis

- **Total Leafs:** 7
- **Big Cluster Customers:** 4,799
- **Small Cluster Customers:** 2,598
- **Total Customer Impact:** 7,397

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| switch-chassis.chassis.chassis-name | 1,196 | 650 | 1,846 |
| switch-chassis.chassis.line-modules.line-module-name | 1,196 | 650 | 1,846 |
| switch-chassis.chassis.line-modules.sku | 1,196 | 649 | 1,845 |
| switch-chassis.chassis.platform | 1,196 | 649 | 1,845 |
| switch-chassis.chassis.line-modules.hw-profile | 9 | 0 | 9 |
| switch-chassis.chassis.line-modules.power-admin-state | 5 | 0 | 5 |
| switch-chassis.chassis.line-modules.power-priority | 1 | 0 | 1 |

### aruba-copp

- **Total Leafs:** 4
- **Big Cluster Customers:** 3,258
- **Small Cluster Customers:** 2,259
- **Total Customer Impact:** 5,517

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| copp.profile.name | 852 | 578 | 1,430 |
| copp.profile.copp-policy.configured-copp-policy-entries.class | 821 | 573 | 1,394 |
| copp.profile.copp-policy.configured-copp-policy-entries.priority | 821 | 573 | 1,394 |
| copp.profile.copp-policy.applied | 764 | 535 | 1,299 |

### aruba-cdp

- **Total Leafs:** 2
- **Big Cluster Customers:** 3,516
- **Small Cluster Customers:** 1,938
- **Total Customer Impact:** 5,454

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| cdp.profile.enable | 1,758 | 969 | 2,727 |
| cdp.profile.name | 1,758 | 969 | 2,727 |

### aruba-ipfix-flow-record

- **Total Leafs:** 25
- **Big Cluster Customers:** 1,853
- **Small Cluster Customers:** 1,787
- **Total Customer Impact:** 3,640

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ipfix-flow-record.records.collect.counter-bytes | 150 | 148 | 298 |
| ipfix-flow-record.records.match.ipv4-source-address | 150 | 148 | 298 |
| ipfix-flow-record.records.match.transport-destination-port | 150 | 148 | 298 |
| ipfix-flow-record.records.match.transport-source-port | 150 | 148 | 298 |
| ipfix-flow-record.records.name | 150 | 148 | 298 |
| ipfix-flow-record.records.match.ipv4-destination-address | 150 | 147 | 297 |
| ipfix-flow-record.records.match.ipv4-protocol | 150 | 147 | 297 |
| ipfix-flow-record.records.match.ipv4-version | 150 | 146 | 296 |
| ipfix-flow-record.records.collect.counter-packets | 150 | 139 | 289 |
| ipfix-flow-record.records.collect.timestamp-absolute-first | 126 | 97 | 223 |
| ipfix-flow-record.records.collect.timestamp-absolute-last | 128 | 93 | 221 |
| ipfix-flow-record.records.collect.application-name | 109 | 67 | 176 |
| ipfix-flow-record.records.description | 43 | 47 | 90 |
| ipfix-flow-record.records.collect.application-https-url | 29 | 41 | 70 |
| ipfix-flow-record.records.collect.application-dns-response-code | 30 | 26 | 56 |
| ipfix-flow-record.records.collect.application-tls-attributes | 26 | 24 | 50 |
| ipfix-flow-record.records.collect.forwarding-status | 5 | 19 | 24 |
| ipfix-flow-record.records.match.ipv6-destination-address | 1 | 12 | 13 |
| ipfix-flow-record.records.match.ipv6-protocol | 1 | 12 | 13 |
| ipfix-flow-record.records.match.ipv6-source-address | 1 | 12 | 13 |
| ipfix-flow-record.records.match.ipv6-version | 1 | 12 | 13 |
| ipfix-flow-record.records.collect.application-tcp-establishment-time | 1 | 2 | 3 |
| ipfix-flow-record.records.collect.egress-interface | 1 | 2 | 3 |
| ipfix-flow-record.records.collect.egress-vlan | 0 | 2 | 2 |
| ipfix-flow-record.records.collect.egress-queue | 1 | 0 | 1 |

</details>

### aruba-mgmd

- **Total Leafs:** 8
- **Big Cluster Customers:** 2,333
- **Small Cluster Customers:** 526
- **Total Customer Impact:** 2,859

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| mgmd-global.profile.name | 1,030 | 260 | 1,290 |
| mgmd-global.profile.igmp.filter-unknown-multicast | 662 | 80 | 742 |
| mgmd-global.profile.igmp.drop-unknown | 412 | 54 | 466 |
| mgmd-global.profile.igmp.fastlearn.eth-ports | 198 | 114 | 312 |
| mgmd-global.profile.igmp.fastlearn.lag-ports | 24 | 10 | 34 |
| mgmd-global.profile.delayed-refresh_enable | 2 | 4 | 6 |
| mgmd-global.profile.delayed-refresh-interval | 2 | 4 | 6 |
| mgmd-global.profile.mld.filter-unknown-multicast | 3 | 0 | 3 |

### aruba-aaa-captive-portal

- **Total Leafs:** 5
- **Big Cluster Customers:** 1,127
- **Small Cluster Customers:** 1,570
- **Total Customer Impact:** 2,697

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| captive-portal.profile.name | 564 | 783 | 1,347 |
| captive-portal.profile.external-cp-server-url | 563 | 783 | 1,346 |
| captive-portal.profile.url-hash-key-format | 0 | 2 | 2 |
| captive-portal.profile.url-hash-key-ciphertext-value | 0 | 1 | 1 |
| captive-portal.profile.url-hash-key-value | 0 | 1 | 1 |

### aruba-ufd

- **Total Leafs:** 9
- **Big Cluster Customers:** 8
- **Small Cluster Customers:** 2,669
- **Total Customer Impact:** 2,677

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ufd.profile.enable | 4 | 399 | 403 |
| ufd.profile.name | 4 | 399 | 403 |
| ufd.profile.sessions.id | 0 | 399 | 399 |
| ufd.profile.sessions.links-to-disable.ethernet-ports | 0 | 395 | 395 |
| ufd.profile.sessions.links-to-monitor.ethernet-ports | 0 | 389 | 389 |
| ufd.profile.sessions.delay-up | 0 | 234 | 234 |
| ufd.profile.sessions.delay-down | 0 | 225 | 225 |
| ufd.profile.sessions.links-to-disable.lag-ports | 0 | 219 | 219 |
| ufd.profile.sessions.links-to-monitor.lag-ports | 0 | 10 | 10 |

### aruba-nae-agent

- **Total Leafs:** 5
- **Big Cluster Customers:** 1,024
- **Small Cluster Customers:** 1,078
- **Total Customer Impact:** 2,102

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| nae-agents.nae-agent.agent-disable | 274 | 282 | 556 |
| nae-agents.nae-agent.agent-name | 274 | 282 | 556 |
| nae-agents.nae-agent.script-name | 274 | 282 | 556 |
| nae-agents.nae-agent.agent-parameters.name | 101 | 116 | 217 |
| nae-agents.nae-agent.agent-parameters.value | 101 | 116 | 217 |

### aruba-nd-snooping

- **Total Leafs:** 5
- **Big Cluster Customers:** 1,060
- **Small Cluster Customers:** 819
- **Total Customer Impact:** 1,879

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| nd-snooping.profile.name | 485 | 409 | 894 |
| nd-snooping.profile.enable | 478 | 409 | 887 |
| nd-snooping.profile.ra-guard-policy.ra-guard-name | 49 | 0 | 49 |
| nd-snooping.profile.ra-guard-policy.match-list.access-list | 48 | 0 | 48 |
| nd-snooping.profile.mac-check | 0 | 1 | 1 |

### aruba-l3-route

- **Total Leafs:** 3
- **Big Cluster Customers:** 1,842
- **Small Cluster Customers:** 12
- **Total Customer Impact:** 1,854

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| l3-route.profile.name | 921 | 6 | 927 |
| l3-route.profile.route-redistribute | 917 | 2 | 919 |
| l3-route.profile.graceful-restart | 4 | 4 | 8 |

### aruba-ipfix-flow-exporter

- **Total Leafs:** 10
- **Big Cluster Customers:** 701
- **Small Cluster Customers:** 760
- **Total Customer Impact:** 1,461

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ipfix-flow-exporter.exporters.name | 155 | 147 | 302 |
| ipfix-flow-exporter.exporters.vrf | 78 | 106 | 184 |
| ipfix-flow-exporter.exporters.ip | 76 | 106 | 182 |
| ipfix-flow-exporter.exporters.port | 68 | 89 | 157 |
| ipfix-flow-exporter.exporters.transport-protocol | 68 | 89 | 157 |
| ipfix-flow-exporter.exporters.local-collector | 77 | 58 | 135 |
| ipfix-flow-exporter.exporters.collector-dest | 77 | 53 | 130 |
| ipfix-flow-exporter.exporters.upload-template-interval | 64 | 43 | 107 |
| ipfix-flow-exporter.exporters.description | 36 | 67 | 103 |
| ipfix-flow-exporter.exporters.hostname | 2 | 2 | 4 |

### aruba-interface-vni

- **Total Leafs:** 7
- **Big Cluster Customers:** 0
- **Small Cluster Customers:** 1,377
- **Total Customer Impact:** 1,377

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| vxlan-vni.profile.name | 0 | 236 | 236 |
| vxlan-vni.profile.vni.id | 0 | 236 | 236 |
| vxlan-vni.profile.vni.vni-name | 0 | 236 | 236 |
| vxlan-vni.profile.vxlan-tunnel-profile | 0 | 236 | 236 |
| vxlan-vni.profile.vni.vlan | 0 | 191 | 191 |
| vxlan-vni.profile.vni.symmetric-routing | 0 | 121 | 121 |
| vxlan-vni.profile.vni.vrf | 0 | 121 | 121 |

### aruba-interface-tunnel

- **Total Leafs:** 15
- **Big Cluster Customers:** 974
- **Small Cluster Customers:** 356
- **Total Customer Impact:** 1,330

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| tunnel.interface.id | 157 | 56 | 213 |
| tunnel.interface.ip-version | 157 | 56 | 213 |
| tunnel.interface.mode | 157 | 56 | 213 |
| tunnel.interface.dst | 155 | 56 | 211 |
| tunnel.interface.vxlan.profile-name | 140 | 46 | 186 |
| tunnel.interface.vxlan.vni-list | 140 | 46 | 186 |
| tunnel.interface.src | 15 | 10 | 25 |
| tunnel.interface.ipv4-prefix | 12 | 10 | 22 |
| tunnel.interface.enabled | 13 | 7 | 20 |
| tunnel.interface.description | 8 | 6 | 14 |
| tunnel.interface.vrf-forwarding | 7 | 4 | 11 |
| tunnel.interface.mtu | 8 | 2 | 10 |
| tunnel.interface.l3-counters | 3 | 0 | 3 |
| tunnel.interface.gre.pim4-sparse.enable | 2 | 0 | 2 |
| tunnel.interface.ttl.value | 0 | 1 | 1 |

### aruba-interface-subinterface

- **Total Leafs:** 21
- **Big Cluster Customers:** 798
- **Small Cluster Customers:** 416
- **Total Customer Impact:** 1,214

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| sub-interfaces.interface.id | 114 | 62 | 176 |
| sub-interfaces.interface.parent-name | 114 | 62 | 176 |
| sub-interfaces.interface.parent-name-id | 114 | 62 | 176 |
| sub-interfaces.interface.encapsulation-vlan-id | 113 | 60 | 173 |
| sub-interfaces.interface.ipv4.address | 114 | 59 | 173 |
| sub-interfaces.interface.vrf-forwarding | 108 | 45 | 153 |
| sub-interfaces.interface.description | 110 | 25 | 135 |
| sub-interfaces.interface.pim-sparse.enable | 0 | 12 | 12 |
| sub-interfaces.interface.ip.mtu | 3 | 2 | 5 |
| sub-interfaces.interface.enable | 0 | 4 | 4 |
| sub-interfaces.interface.ipv4-relay.server.ip | 1 | 3 | 4 |
| sub-interfaces.interface.ipv4-relay.server.ip-vrf | 1 | 3 | 4 |
| sub-interfaces.interface.ipv4-relay.server.vrf | 1 | 3 | 4 |
| sub-interfaces.interface.vrrp.vrrp-profile-apply | 0 | 4 | 4 |
| sub-interfaces.interface.policy.ipv4-access-list-out | 4 | 0 | 4 |
| sub-interfaces.interface.ipv6.addresses.address | 0 | 3 | 3 |
| sub-interfaces.interface.ip.l3-counters | 0 | 3 | 3 |
| sub-interfaces.interface.arp.timeout | 0 | 2 | 2 |
| sub-interfaces.interface.ipv4.secondary-ip | 1 | 0 | 1 |
| sub-interfaces.interface.igmp.enable | 0 | 1 | 1 |
| sub-interfaces.interface.policy.ipv4-access-list-in | 0 | 1 | 1 |

</details>

### aruba-nae-script

- **Total Leafs:** 2
- **Big Cluster Customers:** 601
- **Small Cluster Customers:** 608
- **Total Customer Impact:** 1,209

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| nae-scripts.nae-script.name | 301 | 304 | 605 |
| nae-scripts.nae-script.script | 300 | 304 | 604 |

### aruba-ipfix-flow-monitor

- **Total Leafs:** 6
- **Big Cluster Customers:** 558
- **Small Cluster Customers:** 514
- **Total Customer Impact:** 1,072

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ipfix-flow-monitor.monitors.name | 151 | 148 | 299 |
| ipfix-flow-monitor.monitors.record | 150 | 148 | 298 |
| ipfix-flow-monitor.monitors.exporter.exporter-name | 149 | 147 | 296 |
| ipfix-flow-monitor.monitors.cache-timeout-active | 83 | 41 | 124 |
| ipfix-flow-monitor.monitors.description | 23 | 26 | 49 |
| ipfix-flow-monitor.monitors.cache-timeout-inactive | 2 | 4 | 6 |

### aruba-nd-snooping-interface

- **Total Leafs:** 4
- **Big Cluster Customers:** 625
- **Small Cluster Customers:** 404
- **Total Customer Impact:** 1,029

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| nd-snooping-interface.profile.name | 292 | 202 | 494 |
| nd-snooping-interface.profile.nd-snooping.trust | 291 | 202 | 493 |
| nd-snooping-interface.profile.nd-snooping.ra-guard-policy | 41 | 0 | 41 |
| nd-snooping-interface.profile.nd-snooping.max-bindings | 1 | 0 | 1 |

### aruba-role-gpid

- **Total Leafs:** 2
- **Big Cluster Customers:** 848
- **Small Cluster Customers:** 166
- **Total Customer Impact:** 1,014

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| role-gpids.role-gpid.gpid | 424 | 83 | 507 |
| role-gpids.role-gpid.name | 424 | 83 | 507 |

### aruba-interface-vxlan-tunnel

- **Total Leafs:** 13
- **Big Cluster Customers:** 0
- **Small Cluster Customers:** 949
- **Total Customer Impact:** 949

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| vxlan-tunnel.profile.name | 0 | 245 | 245 |
| vxlan-tunnel.profile.enable | 0 | 234 | 234 |
| vxlan-tunnel.profile.src-ipv4 | 0 | 234 | 234 |
| vxlan-tunnel.profile.interface.dst | 0 | 46 | 46 |
| vxlan-tunnel.profile.interface.id | 0 | 46 | 46 |
| vxlan-tunnel.profile.interface.ip-version | 0 | 46 | 46 |
| vxlan-tunnel.profile.interface.vni-profile-name | 0 | 46 | 46 |
| vxlan-tunnel.profile.enable-counters | 0 | 18 | 18 |
| vxlan-tunnel.profile.bridging-mode | 0 | 15 | 15 |
| vxlan-tunnel.profile.loop-protect-vlans | 0 | 7 | 7 |
| vxlan-tunnel.profile.description | 0 | 6 | 6 |
| vxlan-tunnel.profile.loop-protect | 0 | 4 | 4 |
| vxlan-tunnel.profile.mac-notify-traps | 0 | 2 | 2 |

### aruba-nexthop-group

- **Total Leafs:** 6
- **Big Cluster Customers:** 595
- **Small Cluster Customers:** 303
- **Total Customer Impact:** 898

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| nexthop-groups.group.name | 133 | 68 | 201 |
| nexthop-groups.group.nexthops.index | 132 | 68 | 200 |
| nexthop-groups.group.nexthops.ip | 132 | 68 | 200 |
| nexthop-groups.group.nexthops.type | 132 | 68 | 200 |
| nexthop-groups.group.nexthops.null-interface | 45 | 10 | 55 |
| nexthop-groups.group.nexthops.default-host | 21 | 21 | 42 |

### aruba-keychain

- **Total Leafs:** 12
- **Big Cluster Customers:** 660
- **Small Cluster Customers:** 165
- **Total Customer Impact:** 825

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| keychains.keychain.name | 140 | 33 | 173 |
| keychains.keychain.keys.key-id | 132 | 32 | 164 |
| keychains.keychain.keys.auth-key-info.type | 131 | 30 | 161 |
| keychains.keychain.keys.auth-key-info.auth-key-ciphertext | 131 | 30 | 161 |
| keychains.keychain.keys.crypto-algorithm | 108 | 16 | 124 |
| keychains.keychain.keys.accept-start | 6 | 8 | 14 |
| keychains.keychain.keys.send-start | 6 | 8 | 14 |
| keychains.keychain.keys.accept-end | 3 | 2 | 5 |
| keychains.keychain.keys.send-end | 3 | 2 | 5 |
| keychains.keychain.keys.recv-id | 0 | 2 | 2 |
| keychains.keychain.keys.send-id | 0 | 2 | 2 |
| keychains.keychain.keys.auth-key-info.auth-key | 0 | 0 | 0 |

### aruba-erps

- **Total Leafs:** 21
- **Big Cluster Customers:** 746
- **Small Cluster Customers:** 76
- **Total Customer Impact:** 822

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| erps.profile.name | 72 | 8 | 80 |
| erps.profile.ring.instance.instance-id | 72 | 8 | 80 |
| erps.profile.ring.instance.protected-vlans | 72 | 8 | 80 |
| erps.profile.ring.ring-id | 72 | 8 | 80 |
| erps.profile.ring.instance.control-vlan | 71 | 8 | 79 |
| erps.profile.ring.instance.protection-switching-enable | 71 | 8 | 79 |
| erps.profile.ring.port0-eth-interface | 61 | 0 | 61 |
| erps.profile.ring.port1-eth-interface | 59 | 0 | 59 |
| erps.profile.ring.description | 40 | 5 | 45 |
| erps.profile.ring.instance.instance-description | 37 | 5 | 42 |
| erps.profile.ring.instance.role | 28 | 1 | 29 |
| erps.profile.ring.port1-portchannel | 12 | 8 | 20 |
| erps.profile.ring.port0-portchannel | 10 | 8 | 18 |
| erps.profile.ring.instance.rpl | 15 | 1 | 16 |
| erps.profile.ring.wtr-interval | 14 | 0 | 14 |
| erps.profile.ring.meg-level | 14 | 0 | 14 |
| erps.profile.ring.guard-interval | 7 | 0 | 7 |
| erps.profile.ring.hold-off-interval | 7 | 0 | 7 |
| erps.profile.ring.transmission-interval | 7 | 0 | 7 |
| erps.profile.ring.sub-ring | 3 | 0 | 3 |
| erps.profile.ring.parent-ring | 2 | 0 | 2 |

</details>

### aruba-traffic-insight

- **Total Leafs:** 11
- **Big Cluster Customers:** 477
- **Small Cluster Customers:** 248
- **Total Customer Impact:** 725

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| traffic-insight.instance.name | 90 | 39 | 129 |
| traffic-insight.instance.enable | 78 | 39 | 117 |
| traffic-insight.instance.monitor.monitor-name | 77 | 39 | 116 |
| traffic-insight.instance.monitor.monitor-name-type | 77 | 39 | 116 |
| traffic-insight.instance.monitor.type | 77 | 39 | 116 |
| traffic-insight.instance.source | 78 | 38 | 116 |
| traffic-insight.instance.monitor.monitor-n-flows | 0 | 7 | 7 |
| traffic-insight.instance.monitor.group-by | 0 | 6 | 6 |
| traffic-insight.instance.monitor.single-value-filter.parameter | 0 | 1 | 1 |
| traffic-insight.instance.monitor.single-value-filter.source-port | 0 | 1 | 1 |
| traffic-insight.instance.monitor.single-value-filter.application-id | 0 | 0 | 0 |

### aruba-external-storage

- **Total Leafs:** 10
- **Big Cluster Customers:** 295
- **Small Cluster Customers:** 402
- **Total Customer Impact:** 697

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| external-storage.profile.name | 46 | 48 | 94 |
| external-storage.profile.store.store-name | 46 | 48 | 94 |
| external-storage.profile.store.type | 45 | 44 | 89 |
| external-storage.profile.store.address | 44 | 44 | 88 |
| external-storage.profile.store.directory | 44 | 44 | 88 |
| external-storage.profile.store.enable | 44 | 42 | 86 |
| external-storage.profile.store.password-ciphertext | 8 | 44 | 52 |
| external-storage.profile.store.password-type | 8 | 44 | 52 |
| external-storage.profile.store.username | 8 | 44 | 52 |
| external-storage.profile.store.vrf | 2 | 0 | 2 |

### aruba-rip

- **Total Leafs:** 43
- **Big Cluster Customers:** 412
- **Small Cluster Customers:** 234
- **Total Customer Impact:** 646

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| rip.router.instance-tag | 48 | 0 | 48 |
| rip.router.instance-tag-vrf-proto-type | 48 | 0 | 48 |
| rip.router.proto-type | 48 | 0 | 48 |
| rip.router.vrf | 48 | 0 | 48 |
| rip.router.redistribute.redistribute-id | 36 | 0 | 36 |
| rip.router.redistribute.redistribute-type | 36 | 0 | 36 |
| rip.router.svi-interfaces.address-family | 30 | 0 | 30 |
| rip.router.svi-interfaces.ip-address | 30 | 0 | 30 |
| rip.router.svi-interfaces.svi-id | 30 | 0 | 30 |
| rip.router.svi-interfaces.svi-id-address-family | 30 | 0 | 30 |
| rip.profile.name | 0 | 19 | 19 |
| rip.profile.router.instance-tag | 0 | 19 | 19 |
| rip.profile.router.instance-tag-vrf-proto-type | 0 | 19 | 19 |
| rip.profile.router.proto-type | 0 | 19 | 19 |
| rip.profile.router.vrf | 0 | 19 | 19 |
| rip.profile.router.redistribute.redistribute-id | 0 | 16 | 16 |
| rip.profile.router.redistribute.redistribute-type | 0 | 16 | 16 |
| rip.profile.description | 0 | 15 | 15 |
| rip.profile.router.svi-interfaces.address-family | 0 | 14 | 14 |
| rip.profile.router.svi-interfaces.ip-address | 0 | 14 | 14 |
| rip.profile.router.svi-interfaces.svi-id | 0 | 14 | 14 |
| rip.profile.router.svi-interfaces.svi-id-address-family | 0 | 14 | 14 |
| rip.router.ether-interfaces.address-family | 5 | 0 | 5 |
| rip.router.ether-interfaces.interface-name | 5 | 0 | 5 |
| rip.router.ether-interfaces.interface-name-address-family | 5 | 0 | 5 |
| rip.router.ether-interfaces.ip-address | 5 | 0 | 5 |
| rip.profile.router.timers.garbage-collection | 0 | 5 | 5 |
| rip.profile.router.timers.timeout | 0 | 5 | 5 |
| rip.profile.router.timers.update | 0 | 5 | 5 |
| rip.router.enable | 4 | 0 | 4 |
| rip.profile.router.maximum-paths | 0 | 4 | 4 |
| rip.profile.router.redistribute.ospf-id | 0 | 3 | 3 |
| rip.router.redistribute.ospf-id | 3 | 0 | 3 |
| rip.profile.router.loopback-interfaces.address-family | 0 | 2 | 2 |
| rip.profile.router.loopback-interfaces.ip-address | 0 | 2 | 2 |
| rip.profile.router.loopback-interfaces.loopback-id | 0 | 2 | 2 |
| rip.profile.router.loopback-interfaces.loopback-id-address-family | 0 | 2 | 2 |
| rip.profile.router.distance | 0 | 2 | 2 |
| rip.profile.router.ether-interfaces.address-family | 0 | 1 | 1 |
| rip.profile.router.ether-interfaces.interface-name | 0 | 1 | 1 |
| rip.profile.router.ether-interfaces.interface-name-address-family | 0 | 1 | 1 |
| rip.profile.router.ether-interfaces.ip-address | 0 | 1 | 1 |
| rip.router.distance | 1 | 0 | 1 |

</details>

### aruba-udp-broadcast-forwarder

- **Total Leafs:** 2
- **Big Cluster Customers:** 266
- **Small Cluster Customers:** 298
- **Total Customer Impact:** 564

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| udp-broadcast-forwarders.profile.enable | 133 | 149 | 282 |
| udp-broadcast-forwarders.profile.name | 133 | 149 | 282 |

### aruba-named-vlan

- **Total Leafs:** 2
- **Big Cluster Customers:** 504
- **Small Cluster Customers:** 21
- **Total Customer Impact:** 525

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| named-vlan.profile.name | 266 | 20 | 286 |
| named-vlan.profile.vlan.vlan-id-ranges | 238 | 1 | 239 |

### aruba-ip-lockdown

- **Total Leafs:** 2
- **Big Cluster Customers:** 294
- **Small Cluster Customers:** 82
- **Total Customer Impact:** 376

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ip-source-lockdown.profile.ip-source-lockdown-resource-extended | 147 | 41 | 188 |
| ip-source-lockdown.profile.name | 147 | 41 | 188 |

### aruba-ipsla

- **Total Leafs:** 20
- **Big Cluster Customers:** 228
- **Small Cluster Customers:** 122
- **Total Customer Impact:** 350

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ipsla.profile.name | 34 | 21 | 55 |
| ipsla.profile.source-sessions.source-name | 34 | 21 | 55 |
| ipsla.profile.source-sessions.type | 33 | 18 | 51 |
| ipsla.profile.source-sessions.destination-ipv4 | 31 | 18 | 49 |
| ipsla.profile.source-sessions.enable | 31 | 16 | 47 |
| ipsla.profile.source-sessions.frequency | 24 | 11 | 35 |
| ipsla.profile.source-sessions.source.ipv4-address | 6 | 12 | 18 |
| ipsla.profile.source-sessions.vrf | 9 | 0 | 9 |
| ipsla.profile.source-sessions.destination-hostname | 6 | 0 | 6 |
| ipsla.profile.source-sessions.payload-size | 4 | 1 | 5 |
| ipsla.profile.source-sessions.destination-port | 3 | 2 | 5 |
| ipsla.profile.source-sessions.source.interface-vlan | 4 | 0 | 4 |
| ipsla.profile.source-sessions.source.port | 1 | 2 | 3 |
| ipsla.profile.source-sessions.source.interface-ethernet | 2 | 0 | 2 |
| ipsla.profile.responder-sessions.responder-name | 1 | 0 | 1 |
| ipsla.profile.responder-sessions.responder-port | 1 | 0 | 1 |
| ipsla.profile.responder-sessions.responder-source.interface-vlan | 1 | 0 | 1 |
| ipsla.profile.responder-sessions.responder-type | 1 | 0 | 1 |
| ipsla.profile.source-sessions.http.request-type | 1 | 0 | 1 |
| ipsla.profile.source-sessions.http.url | 1 | 0 | 1 |

</details>

### aruba-mirror-endpoint

- **Total Leafs:** 10
- **Big Cluster Customers:** 184
- **Small Cluster Customers:** 143
- **Total Customer Impact:** 327

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| mirror-endpoint.profile.endpoints.ep-name | 39 | 26 | 65 |
| mirror-endpoint.profile.name | 39 | 26 | 65 |
| mirror-endpoint.profile.endpoints.source.destination-ip | 21 | 18 | 39 |
| mirror-endpoint.profile.endpoints.source.source-ip | 21 | 18 | 39 |
| mirror-endpoint.profile.endpoints.source.tid | 21 | 18 | 39 |
| mirror-endpoint.profile.endpoints.destinations.eth-interfaces | 20 | 18 | 38 |
| mirror-endpoint.profile.endpoints.enable | 17 | 16 | 33 |
| mirror-endpoint.profile.endpoints.comment | 3 | 1 | 4 |
| mirror-endpoint.profile.endpoints.source.encap | 2 | 2 | 4 |
| mirror-endpoint.profile.endpoints.source.vrf | 1 | 0 | 1 |

### aruba-dhcp-client

- **Total Leafs:** 3
- **Big Cluster Customers:** 226
- **Small Cluster Customers:** 74
- **Total Customer Impact:** 300

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| dhcp-client.profile.name | 113 | 37 | 150 |
| dhcp-client.profile.ip.enable-hostname | 105 | 37 | 142 |
| dhcp-client.profile.ip.enable-broadcast-flag | 8 | 0 | 8 |

### aruba-ptp

- **Total Leafs:** 8
- **Big Cluster Customers:** 176
- **Small Cluster Customers:** 102
- **Total Customer Impact:** 278

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ptp.profile.name | 27 | 15 | 42 |
| ptp.profile.protocol-profiles.profile | 27 | 15 | 42 |
| ptp.profile.protocol-profiles.clock-step | 25 | 14 | 39 |
| ptp.profile.protocol-profiles.delay-mechanism | 25 | 14 | 39 |
| ptp.profile.protocol-profiles.mode | 25 | 14 | 39 |
| ptp.profile.protocol-profiles.transport | 24 | 15 | 39 |
| ptp.profile.protocol-profiles.enable | 23 | 14 | 37 |
| ptp.profile.protocol-profiles.domain | 0 | 1 | 1 |

### aruba-mka

- **Total Leafs:** 8
- **Big Cluster Customers:** 187
- **Small Cluster Customers:** 90
- **Total Customer Impact:** 277

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| mka.policy.name | 41 | 17 | 58 |
| mka.policy.cak-info.ckn | 38 | 17 | 55 |
| mka.policy.cak-info.key-type | 38 | 17 | 55 |
| mka.policy.cak-info.cak-ciphertext | 38 | 17 | 55 |
| mka.policy.key-server-priority | 30 | 16 | 46 |
| mka.policy.eapol-destination-mac | 2 | 3 | 5 |
| mka.policy.eapol-dot1q-tagged | 0 | 3 | 3 |
| mka.policy.cak-info.cak | 0 | 0 | 0 |

### aruba-rmon-alarm

- **Total Leafs:** 6
- **Big Cluster Customers:** 234
- **Small Cluster Customers:** 30
- **Total Customer Impact:** 264

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| rmon-alarms.profile.name | 39 | 5 | 44 |
| rmon-alarms.profile.rmon.falling-threshold | 39 | 5 | 44 |
| rmon-alarms.profile.rmon.index | 39 | 5 | 44 |
| rmon-alarms.profile.rmon.rising-threshold | 39 | 5 | 44 |
| rmon-alarms.profile.rmon.snmp-oid | 39 | 5 | 44 |
| rmon-alarms.profile.rmon.interval | 39 | 5 | 44 |

### aruba-firmware-management

- **Total Leafs:** 3
- **Big Cluster Customers:** 161
- **Small Cluster Customers:** 97
- **Total Customer Impact:** 258

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| device-firmware.site-distribution | 127 | 73 | 200 |
| device-firmware.issu.software-update-rollback-timer-enable | 30 | 14 | 44 |
| device-firmware.issu.software-update-rollback-timer | 4 | 10 | 14 |

### aruba-lacp

- **Total Leafs:** 2
- **Big Cluster Customers:** 130
- **Small Cluster Customers:** 100
- **Total Customer Impact:** 230

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| lacp.hash | 95 | 32 | 127 |
| lacp.system-priority | 35 | 68 | 103 |

### aruba-mvrp

- **Total Leafs:** 2
- **Big Cluster Customers:** 206
- **Small Cluster Customers:** 8
- **Total Customer Impact:** 214

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| mvrp.profile.enable | 103 | 4 | 107 |
| mvrp.profile.name | 103 | 4 | 107 |

### aruba-mac-lockout

- **Total Leafs:** 3
- **Big Cluster Customers:** 132
- **Small Cluster Customers:** 82
- **Total Customer Impact:** 214

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| mac-lockout.profile.name | 63 | 41 | 104 |
| mac-lockout.profile.address.mac | 62 | 38 | 100 |
| mac-lockout.profile.log | 7 | 3 | 10 |

### aruba-track-object

- **Total Leafs:** 4
- **Big Cluster Customers:** 22
- **Small Cluster Customers:** 164
- **Total Customer Impact:** 186

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| tracking-object.vrrp.identifier | 14 | 80 | 94 |
| tracking-object.vrrp.interface.interface-type | 4 | 42 | 46 |
| tracking-object.vrrp.interface.svi | 1 | 40 | 41 |
| tracking-object.vrrp.interface.ethernet | 3 | 2 | 5 |

### aruba-static-mac

- **Total Leafs:** 5
- **Big Cluster Customers:** 110
- **Small Cluster Customers:** 55
- **Total Customer Impact:** 165

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| static-macs.profile.name | 22 | 11 | 33 |
| static-macs.profile.static-mac.destination-port.l2-destination | 22 | 11 | 33 |
| static-macs.profile.static-mac.mac | 22 | 11 | 33 |
| static-macs.profile.static-mac.mac-vlan | 22 | 11 | 33 |
| static-macs.profile.static-mac.vlan | 22 | 11 | 33 |

### aruba-qos-cos

- **Total Leafs:** 5
- **Big Cluster Customers:** 154
- **Small Cluster Customers:** 0
- **Total Customer Impact:** 154

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-cos.profile.cos-map.color | 38 | 0 | 38 |
| qos-cos.profile.cos-map.cos | 38 | 0 | 38 |
| qos-cos.profile.cos-map.local-priority | 38 | 0 | 38 |
| qos-cos.profile.name | 38 | 0 | 38 |
| qos-cos.profile.cos-map.name | 2 | 0 | 2 |

### aruba-ip-binding

- **Total Leafs:** 7
- **Big Cluster Customers:** 119
- **Small Cluster Customers:** 28
- **Total Customer Impact:** 147

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| source-ip-bindings.static-entry.client-address | 17 | 4 | 21 |
| source-ip-bindings.static-entry.interface-ethernet | 17 | 4 | 21 |
| source-ip-bindings.static-entry.interface-types | 17 | 4 | 21 |
| source-ip-bindings.static-entry.ip-version | 17 | 4 | 21 |
| source-ip-bindings.static-entry.ip-version-vlan-client-address | 17 | 4 | 21 |
| source-ip-bindings.static-entry.mac | 17 | 4 | 21 |
| source-ip-bindings.static-entry.vlan | 17 | 4 | 21 |

### aruba-psm

- **Total Leafs:** 3
- **Big Cluster Customers:** 57
- **Small Cluster Customers:** 72
- **Total Customer Impact:** 129

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| psm.psm-instance.name | 19 | 24 | 43 |
| psm.psm-instance.psm-ips | 19 | 24 | 43 |
| psm.psm-instance.vrf | 19 | 24 | 43 |

### aruba-macsec

- **Total Leafs:** 8
- **Big Cluster Customers:** 86
- **Small Cluster Customers:** 41
- **Total Customer Impact:** 127

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| macsec.policy.name | 41 | 17 | 58 |
| macsec.policy.replay-window | 31 | 14 | 45 |
| macsec.policy.cipher-suites | 10 | 2 | 12 |
| macsec.policy.confidentiality-offset | 2 | 1 | 3 |
| macsec.policy.bypass-list | 0 | 3 | 3 |
| macsec.policy.clear-tag-mode | 0 | 3 | 3 |
| macsec.policy.replay-protect-enable | 2 | 0 | 2 |
| macsec.policy.include-sci-enable | 0 | 1 | 1 |

### aruba-nae-lite

- **Total Leafs:** 26
- **Big Cluster Customers:** 37
- **Small Cluster Customers:** 86
- **Total Customer Impact:** 123

<details>
<summary>Click to expand all leafs</summary>

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| nae-lite.profile.name | 8 | 14 | 22 |
| nae-lite.profile.description | 0 | 10 | 10 |
| nae-lite.profile.agent-type | 3 | 6 | 9 |
| nae-lite.profile.conditions.condtype | 3 | 6 | 9 |
| nae-lite.profile.conditions.name-condition | 3 | 6 | 9 |
| nae-lite.profile.conditions.set-watch | 3 | 5 | 8 |
| nae-lite.profile.watches.event-id | 3 | 5 | 8 |
| nae-lite.profile.watches.watch-name | 3 | 5 | 8 |
| nae-lite.profile.conditions.cli | 1 | 6 | 7 |
| nae-lite.profile.conditions.include | 1 | 5 | 6 |
| nae-lite.profile.conditions.include-regex | 1 | 5 | 6 |
| nae-lite.profile.ready | 2 | 3 | 5 |
| nae-lite.profile.conditions.syslog | 2 | 1 | 3 |
| nae-lite.profile.conditions.status | 1 | 1 | 2 |
| nae-lite.profile.conditions.facility | 1 | 0 | 1 |
| nae-lite.profile.conditions.operand | 0 | 1 | 1 |
| nae-lite.profile.conditions.operator | 0 | 1 | 1 |
| nae-lite.profile.conditions.set-monitor | 0 | 1 | 1 |
| nae-lite.profile.conditions.severity | 1 | 0 | 1 |
| nae-lite.profile.disable | 1 | 0 | 1 |
| nae-lite.profile.monitors.dur-unit | 0 | 1 | 1 |
| nae-lite.profile.monitors.duration | 0 | 1 | 1 |
| nae-lite.profile.monitors.group-by | 0 | 1 | 1 |
| nae-lite.profile.monitors.monitor-name | 0 | 1 | 1 |
| nae-lite.profile.monitors.vsf-member | 0 | 1 | 1 |
| nae-lite.profile.conditions.count | 0 | 0 | 0 |

</details>

### aruba-advanced-intelligent-forwarding

- **Total Leafs:** 4
- **Big Cluster Customers:** 101
- **Small Cluster Customers:** 2
- **Total Customer Impact:** 103

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| advanced-intelligent-forwarding.profile.fib-optimization-host-route-ipv4 | 43 | 0 | 43 |
| advanced-intelligent-forwarding.profile.name | 43 | 0 | 43 |
| advanced-intelligent-forwarding.profile.fib-optimization-exclude-nexthop-ipv4 | 15 | 0 | 15 |
| advanced-intelligent-forwarding.profile.fib-optimization-ageout-time | 0 | 2 | 2 |

### aruba-smartlink

- **Total Leafs:** 11
- **Big Cluster Customers:** 88
- **Small Cluster Customers:** 7
- **Total Customer Impact:** 95

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| smartlink.profile.name | 13 | 2 | 15 |
| smartlink.profile.group.group-id | 13 | 2 | 15 |
| smartlink.profile.group.preemption-enable | 11 | 0 | 11 |
| smartlink.profile.group.protected-vlans | 11 | 0 | 11 |
| smartlink.profile.group.secondary-ethernet-port | 11 | 0 | 11 |
| smartlink.profile.group.preemption-delay | 11 | 0 | 11 |
| smartlink.profile.group.primary-ethernet-port | 10 | 0 | 10 |
| smartlink.profile.group.control-vlan | 8 | 0 | 8 |
| smartlink.profile.group.description | 0 | 2 | 2 |
| smartlink.profile.group.primary-portchannel-port | 0 | 1 | 1 |
| smartlink.profile.recv-control-vlans | 0 | 0 | 0 |

### aruba-feature-pack

- **Total Leafs:** 7
- **Big Cluster Customers:** 26
- **Small Cluster Customers:** 54
- **Total Customer Impact:** 80

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| management-server.profile.credentials.password-ciphertext | 4 | 8 | 12 |
| management-server.profile.credentials.user | 4 | 8 | 12 |
| management-server.profile.location | 4 | 8 | 12 |
| management-server.profile.name | 4 | 8 | 12 |
| management-server.profile.pool | 4 | 8 | 12 |
| management-server.profile.block | 2 | 8 | 10 |
| management-server.profile.vrf | 4 | 6 | 10 |

### aruba-qos-threshold-profile

- **Total Leafs:** 15
- **Big Cluster Customers:** 17
- **Small Cluster Customers:** 49
- **Total Customer Impact:** 66

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-thresholds.profile.thresh-profile-name | 4 | 15 | 19 |
| qos-thresholds.profile.queue.queue-num | 3 | 13 | 16 |
| qos-thresholds.profile.queue.ecn.threshold-percent | 0 | 6 | 6 |
| qos-thresholds.profile.queue.ecn-entry.thresh-units | 3 | 0 | 3 |
| qos-thresholds.profile.queue.ecn-entry.threshold | 3 | 0 | 3 |
| qos-thresholds.profile.queue.wred-resp.entry.color | 0 | 3 | 3 |
| qos-thresholds.profile.queue.wred-resp.entry.max-threshold-percent | 0 | 3 | 3 |
| qos-thresholds.profile.queue.wred-resp.entry.min-threshold-percent | 0 | 3 | 3 |
| qos-thresholds.profile.queue.ecn.max-threshold-kbytes | 0 | 2 | 2 |
| qos-thresholds.profile.queue.ecn.min-threshold-kbytes | 0 | 2 | 2 |
| qos-thresholds.profile.queue.ecn.threshold-kbytes | 0 | 2 | 2 |
| qos-thresholds.profile.queue.wred-resp-entry.color | 1 | 0 | 1 |
| qos-thresholds.profile.queue.wred-resp-entry.max-threshold | 1 | 0 | 1 |
| qos-thresholds.profile.queue.wred-resp-entry.min-threshold | 1 | 0 | 1 |
| qos-thresholds.profile.queue.wred-resp-entry.thresh-units | 1 | 0 | 1 |

### aruba-ip-routing

- **Total Leafs:** 5
- **Big Cluster Customers:** 18
- **Small Cluster Customers:** 33
- **Total Customer Impact:** 51

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ip-routing.profile.name | 6 | 11 | 17 |
| ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-port | 6 | 11 | 17 |
| ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-ip | 0 | 11 | 11 |
| ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-dst-port | 6 | 0 | 6 |
| ip-routing.profile.ip-prefix-priority-params.ip-prefix-priority | 0 | 0 | 0 |

### aruba-countermon

- **Total Leafs:** 2
- **Big Cluster Customers:** 16
- **Small Cluster Customers:** 34
- **Total Customer Impact:** 50

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| countermon.profile.enable-polling | 8 | 17 | 25 |
| countermon.profile.name | 8 | 17 | 25 |

### aruba-qos-pool

- **Total Leafs:** 6
- **Big Cluster Customers:** 42
- **Small Cluster Customers:** 0
- **Total Customer Impact:** 42

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| qos-pools.profile.name | 7 | 0 | 7 |
| qos-pools.profile.pool.headroom-size | 7 | 0 | 7 |
| qos-pools.profile.pool.index | 7 | 0 | 7 |
| qos-pools.profile.pool.priority | 7 | 0 | 7 |
| qos-pools.profile.pool.size | 7 | 0 | 7 |
| qos-pools.profile.pool.type | 7 | 0 | 7 |

### aruba-dhcp-snooping-interface

- **Total Leafs:** 4
- **Big Cluster Customers:** 8
- **Small Cluster Customers:** 33
- **Total Customer Impact:** 41

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| dhcp-snooping-interface.profile.name | 4 | 16 | 20 |
| dhcp-snooping-interface.profile.dhcpv4-snooping.trust | 4 | 15 | 19 |
| dhcp-snooping-interface.profile.dhcpv4-snooping.max-bindings | 0 | 1 | 1 |
| dhcp-snooping-interface.profile.dhcpv6-snooping.trust | 0 | 1 | 1 |

### aruba-config-checkpoint

- **Total Leafs:** 3
- **Big Cluster Customers:** 24
- **Small Cluster Customers:** 8
- **Total Customer Impact:** 32

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| config-checkpoint.profile.name | 11 | 4 | 15 |
| config-checkpoint.profile.post-checkpoint | 8 | 2 | 10 |
| config-checkpoint.profile.post-checkpoint-delay | 5 | 2 | 7 |

### aruba-dsm

- **Total Leafs:** 4
- **Big Cluster Customers:** 12
- **Small Cluster Customers:** 20
- **Total Customer Impact:** 32

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| dsm.dsm-instance.name | 5 | 10 | 15 |
| dsm.dsm-instance.ipfix | 2 | 8 | 10 |
| dsm.dsm-instance.workload-migration | 4 | 2 | 6 |
| dsm.dsm-instance.uplink-to-uplink | 1 | 0 | 1 |

### aruba-container

- **Total Leafs:** 13
- **Big Cluster Customers:** 12
- **Small Cluster Customers:** 10
- **Total Customer Impact:** 22

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| containers.instance.name | 2 | 4 | 6 |
| containers.instance.image-location-url | 2 | 1 | 3 |
| containers.instance.image-location-vrf | 2 | 1 | 3 |
| containers.instance.allow-unsigned-image | 0 | 1 | 1 |
| containers.instance.enable | 0 | 1 | 1 |
| containers.instance.encrypted-environment-variables.encrypted-env-type | 1 | 0 | 1 |
| containers.instance.encrypted-environment-variables.value-ciphertext | 1 | 0 | 1 |
| containers.instance.encrypted-environment-variables.variable | 1 | 0 | 1 |
| containers.instance.environment-variables.value | 0 | 1 | 1 |
| containers.instance.environment-variables.variable | 0 | 1 | 1 |
| containers.instance.runtime-constraints.cpu | 1 | 0 | 1 |
| containers.instance.runtime-constraints.memory | 1 | 0 | 1 |
| containers.instance.vrfs | 1 | 0 | 1 |

### aruba-sysmon

- **Total Leafs:** 3
- **Big Cluster Customers:** 3
- **Small Cluster Customers:** 9
- **Total Customer Impact:** 12

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| sysmon.profile.name | 1 | 3 | 4 |
| sysmon.profile.poll-interval | 1 | 3 | 4 |
| sysmon.profile.polling | 1 | 3 | 4 |

### aruba-dynamic-arp-inspection-interface

- **Total Leafs:** 2
- **Big Cluster Customers:** 4
- **Small Cluster Customers:** 6
- **Total Customer Impact:** 10

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| dynamic-arp-inspection-interface.profile.dynamic-arp-inspection.trust | 2 | 3 | 5 |
| dynamic-arp-inspection-interface.profile.name | 2 | 3 | 5 |

### aruba-container-network

- **Total Leafs:** 6
- **Big Cluster Customers:** 4
- **Small Cluster Customers:** 5
- **Total Customer Impact:** 9

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| container-networks.profile.name | 1 | 1 | 2 |
| container-networks.profile.name-vrf | 1 | 1 | 2 |
| container-networks.profile.vrf | 1 | 1 | 2 |
| container-networks.profile.port-mapping.tcp.container-port | 0 | 1 | 1 |
| container-networks.profile.port-mapping.tcp.host-port | 0 | 1 | 1 |
| container-networks.profile.preferred | 1 | 0 | 1 |

### aruba-ip-lockdown-interface

- **Total Leafs:** 3
- **Big Cluster Customers:** 0
- **Small Cluster Customers:** 7
- **Total Customer Impact:** 7

| Leaf Name | Big Cluster | Small Cluster | Total |
|-----------|----------:|--------------:|------:|
| ip-source-lockdown-interface.profile.ip-source-lockdown.ipv4 | 0 | 3 | 3 |
| ip-source-lockdown-interface.profile.name | 0 | 3 | 3 |
| ip-source-lockdown-interface.profile.ip-source-lockdown.ipv6 | 0 | 1 | 1 |

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

## Recommendations

Based on this analysis, the following YANG modules have the highest customer impact and should be prioritized:

1. **aruba-interface-ethernet** - 2,406,284 total customers (264 leafs)
2. **aruba-interface-portchannel** - 763,279 total customers (119 leafs)
3. **aruba-switch-stack** - 565,504 total customers (11 leafs)
4. **aruba-vsf-template** - 371,043 total customers (5 leafs)
5. **aruba-qos-dscp** - 91,029 total customers (7 leafs)
6. **aruba-vlan-range** - 89,606 total customers (21 leafs)
7. **aruba-loop-protect** - 48,755 total customers (4 leafs)
8. **aruba-aaa-macauth** - 47,007 total customers (7 leafs)
9. **aruba-aaa-dot1xauth** - 45,555 total customers (13 leafs)
10. **aruba-vsx** - 38,520 total customers (17 leafs)

### Action Items

1. Review each unreferenced YANG module to determine if it should be added to `aruba-cx-device-configuration.yang`
2. Prioritize modules with highest customer usage for integration
3. Verify if any unreferenced leafs are intentionally excluded or deprecated
