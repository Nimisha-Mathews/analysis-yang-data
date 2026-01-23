# CX Device Configuration - Unreferenced Leaf Analysis

## Summary

This report identifies leafs from the PLM Consolidated Leaf List that are **NOT** referenced by `aruba-cx-device-configuration.yang` through leaf or leafref.

### Key Statistics

| Metric | Count |
|--------|-------|
| Total Leafs Analyzed | 2707 |
| Leafs Referenced by CX Device Config | 1583 |
| **Leafs NOT Referenced** | **1124** |
| Unique YANG Modules with Unreferenced Leafs | 90 |
| Total Big Cluster Customers Affected | 291368 |
| Total Small Cluster Customers Affected | 127933 |
| **Total Customers Affected** | **419301** |

## YANG Modules Imported by aruba-cx-device-configuration.yang

The following YANG modules ARE referenced:

- `aruba-aaa-profile`
- `aruba-alias`
- `aruba-app-recog-control`
- `aruba-aspath-list`
- `aruba-auth-server`
- `aruba-auth-server-global`
- `aruba-auth-server-group`
- `aruba-bfd`
- `aruba-bgp`
- `aruba-client-insight`
- `aruba-client-iptracker`
- `aruba-community-list`
- `aruba-device-configuration-common`
- `aruba-device-profile`
- `aruba-devicefingerprinting-profile`
- `aruba-dhcp-pool`
- `aruba-dhcp-relay`
- `aruba-dhcp-server`
- `aruba-dhcp-snooping`
- `aruba-dns`
- `aruba-est`
- `aruba-evpn`
- `aruba-extensions`
- `aruba-fault-monitor`
- `aruba-flow-tracking`
- `aruba-http-proxy`
- `aruba-interface-loopback`
- `aruba-interface-management`
- `aruba-interface-profile`
- `aruba-interface-vlan`
- `aruba-ip-source-interface`
- `aruba-local-management`
- `aruba-logging`
- `aruba-management-user`
- `aruba-mirror`
- `aruba-msdp`
- `aruba-multicast-dns`
- `aruba-multicast-static-route`
- `aruba-ntp`
- `aruba-ospfv2`
- `aruba-ospfv3`
- `aruba-pim`
- `aruba-policy`
- `aruba-prefix-list`
- `aruba-qos-global`
- `aruba-remote-management`
- `aruba-role`
- `aruba-routemap`
- `aruba-sflow`
- `aruba-snmp`
- `aruba-static-route`
- `aruba-stp`
- `aruba-sw-port-profile`
- `aruba-switch-certificate-usage`
- `aruba-switch-system`
- `aruba-ubt`
- `aruba-vlan`
- `aruba-vrf`
- `aruba-vrrp`
- `aruba-vrrp-interface`

## Unreferenced Leafs by YANG Module

The following table shows leafs grouped by their YANG module that are NOT referenced:

### aruba-interface-ethernet

- **Leaf Count:** 264
- **Big Cluster Customers:** 118984
- **Small Cluster Customers:** 51272
- **Total Customers Affected:** 170256

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-ethernet:ethernet-interfaces.interface.name` | 12284 | 4723 | 17007 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.enable` | 10512 | 4716 | 15228 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.interface-mode` | 10276 | 4673 | 14949 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.access-vlan` | 9950 | 4352 | 14302 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.native-vlan` | 8663 | 3848 | 12511 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.description` | 6990 | 3231 | 10221 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.trunk-vlan-ranges` | 5998 | 3089 | 9087 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.routing` | 5652 | 3035 | 8687 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.trunk-vlan-all` | 6163 | 2277 | 8440 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.portchannel-lag` | 4041 | 2028 | 6069 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.enable` | 2865 | 1080 | 3945 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.admin-edge-port` | 2299 | 984 | 3283 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.bpdu-guard` | 2112 | 841 | 2953 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mtu` | 1418 | 680 | 2098 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.enable` | 1516 | 560 | 2076 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.enable` | 1506 | 563 | 2069 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.speed-duplex` | 1356 | 624 | 1980 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.client-limit` | 1349 | 464 | 1813 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4.address` | 1116 | 588 | 1704 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.enabled` | 1192 | 445 | 1637 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.root-guard` | 1071 | 370 | 1441 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.bpdu-filter` | 879 | 282 | 1161 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv4-snooping.trust` | 878 | 262 | 1140 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.concurrent-onboarding` | 863 | 232 | 1095 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.vrf-forwarding` | 637 | 360 | 997 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.eapol-max-requests` | 631 | 249 | 880 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.tcn-guard` | 615 | 247 | 862 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.max-retries` | 547 | 179 | 726 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.reauth-enable` | 555 | 147 | 702 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.reauth-enable` | 548 | 140 | 688 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.priority` | 431 | 256 | 687 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.cached-reauth-enable` | 526 | 154 | 680 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.cached-reauth-enable` | 514 | 142 | 656 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-bypass.lldp` | 472 | 161 | 633 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.eapol-timeout` | 463 | 154 | 617 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.trust` | 427 | 164 | 591 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.action` | 351 | 228 | 579 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.loop-guard` | 345 | 176 | 521 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.tag` | 328 | 141 | 469 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.rate-type` | 289 | 156 | 445 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mode` | 308 | 101 | 409 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.critical-auth-role` | 314 | 93 | 407 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-bypass.cdp` | 299 | 100 | 399 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.cached-reauth-period` | 307 | 89 | 396 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.pre-std-detect` | 272 | 117 | 389 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.cached-reauth-period` | 303 | 83 | 386 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.allow-flood-traffic` | 279 | 89 | 368 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.reauth-period` | 288 | 65 | 353 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-precedence` | 250 | 89 | 339 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.reauth-period` | 265 | 71 | 336 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.quiet-period` | 250 | 81 | 331 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.enable` | 197 | 132 | 329 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.rate-type` | 205 | 109 | 314 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.reject-role` | 214 | 98 | 312 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.bit-rate` | 208 | 92 | 300 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.quiet-period` | 232 | 57 | 289 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.client-limit` | 185 | 88 | 273 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.mode` | 178 | 87 | 265 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.allocation-method` | 169 | 83 | 252 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-priority` | 184 | 62 | 246 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.flow-control-mode` | 139 | 77 | 216 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.fault-monitor-profile` | 132 | 79 | 211 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.direction` | 133 | 74 | 207 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.bit-rate` | 146 | 61 | 207 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.discovery-period` | 140 | 61 | 201 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.update-interval` | 156 | 44 | 200 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.assigned-class` | 143 | 50 | 193 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ip.mtu` | 148 | 42 | 190 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.profile-name` | 148 | 40 | 188 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.priority` | 133 | 37 | 170 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.security-violation.action` | 119 | 48 | 167 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-mode` | 101 | 65 | 166 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.onboarding-precedence` | 111 | 54 | 165 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.initial-auth-response-timeout` | 93 | 65 | 158 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.sticky-mac-enable` | 89 | 65 | 154 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.auth-role` | 98 | 55 | 153 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.dynamic-arp-inspection.trust` | 86 | 55 | 141 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udld.enable` | 96 | 41 | 137 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.link-type` | 95 | 41 | 136 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.vlans` | 71 | 60 | 131 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.fallback-role` | 100 | 24 | 124 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.rate-type` | 75 | 42 | 117 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst-guard` | 79 | 29 | 108 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.cdp.enable` | 69 | 37 | 106 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.enable` | 95 | 10 | 105 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.pre-auth-role` | 83 | 21 | 104 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.security-violation.shutdown-recovery-enable` | 74 | 30 | 104 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv4-access-list-in` | 57 | 46 | 103 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.packet-rate` | 70 | 32 | 102 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.enable` | 83 | 15 | 98 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.macs` | 55 | 43 | 98 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst-filter` | 72 | 25 | 97 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.radius-override-enable` | 65 | 17 | 82 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.security-violation.recovery-timer` | 55 | 25 | 80 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.fast-leave-vlan` | 57 | 23 | 80 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udld.mode.compatibility-mode` | 51 | 29 | 80 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.bit-rate` | 49 | 28 | 77 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.percentage` | 35 | 41 | 76 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.pd-class-override` | 55 | 20 | 75 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.icmp-traffic-type` | 54 | 21 | 75 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.packet-rate` | 48 | 26 | 74 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.device-profile-secure` | 56 | 16 | 72 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv6-snooping.trust` | 55 | 17 | 72 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.sflow.enable` | 56 | 14 | 70 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.dpi-enable` | 35 | 32 | 67 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.rate-type` | 45 | 21 | 66 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udld.mode.rfc5171-mode` | 38 | 27 | 65 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.split-port-enable` | 38 | 22 | 60 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.split-port-count` | 36 | 22 | 58 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv4-monitor` | 27 | 30 | 57 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.cost` | 44 | 13 | 57 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.percentage` | 28 | 28 | 56 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.poe.power-pairs` | 36 | 19 | 55 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.energy-efficient` | 37 | 16 | 53 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.bit-rate` | 35 | 16 | 51 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mda-data-clients-limit` | 33 | 16 | 49 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pvlan-port-mode` | 36 | 8 | 44 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.critical-voice-role` | 32 | 11 | 43 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.macauth-server-group` | 21 | 16 | 37 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4-relay.server.ip` | 26 | 11 | 37 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4-relay.server.ip-vrf` | 26 | 11 | 37 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4-relay.server.vrf` | 26 | 11 | 37 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.cdp.mode` | 23 | 13 | 36 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv4-snooping.max-bindings` | 27 | 9 | 36 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mac-notify-traps` | 24 | 12 | 36 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1xauth-server-group` | 21 | 12 | 33 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6.addresses.address` | 29 | 4 | 33 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.version` | 27 | 3 | 30 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.poe-plus` | 17 | 12 | 29 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.sticky-macs.mac` | 19 | 10 | 29 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.sticky-macs.vlan` | 19 | 10 | 29 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv4-access-list-out` | 21 | 7 | 28 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.schedule-profile` | 17 | 11 | 28 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.packet-rate` | 17 | 9 | 26 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lacp.port-id` | 14 | 11 | 25 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.med-poe-priority-override` | 17 | 8 | 25 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.vrrp.vrrp-profile-apply` | 22 | 3 | 25 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.forward-vlan` | 18 | 6 | 24 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.portfilter.eth-ports` | 17 | 6 | 23 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.portfilter.lag-ports` | 17 | 6 | 23 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.dscp` | 16 | 6 | 22 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.split-port-speed` | 13 | 9 | 22 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.error-control` | 12 | 9 | 21 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.percentage` | 14 | 7 | 21 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.client-limit` | 15 | 5 | 20 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ip.l3-counters` | 14 | 5 | 19 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-auth.lldp` | 12 | 6 | 18 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6.enable-default-link-local` | 10 | 8 | 18 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-dense.enable` | 17 | 1 | 18 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.egress-rate` | 11 | 7 | 18 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.enable` | 14 | 2 | 16 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.source-address-any` | 16 | 0 | 16 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.policy.mac-access-list-in` | 9 | 7 | 16 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udld.mode.aruba-mode` | 13 | 3 | 16 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.trap` | 7 | 8 | 15 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.max-rate-units` | 8 | 7 | 15 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udld.retries` | 8 | 7 | 15 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.med.poe` | 8 | 6 | 14 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.trust` | 9 | 5 | 14 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-auth.mac-type` | 13 | 0 | 13 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv6-access-list-in` | 8 | 5 | 13 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.cos` | 7 | 6 | 13 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udld.interval` | 8 | 5 | 13 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.forced-fast-leave-vlan` | 5 | 7 | 12 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ip-source-lockdown.ipv4` | 6 | 6 | 12 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.macsec-policy` | 8 | 4 | 12 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mka-policy` | 8 | 4 | 12 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ptp.enable` | 8 | 4 | 12 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.bfd.detect-multiplier` | 9 | 2 | 11 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.client-limit-max` | 9 | 2 | 11 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.percentage` | 7 | 4 | 11 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.vlan-id` | 5 | 6 | 11 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.ubt-fallback-role` | 8 | 2 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.bfd.min-rx-interval` | 8 | 2 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.bfd.min-tx-interval` | 8 | 2 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lacp.port-priority` | 6 | 4 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.dcbx-disable` | 3 | 7 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.speed-downshift-enable` | 9 | 1 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.speed-override` | 6 | 4 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.cost` | 5 | 5 | 10 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.query-interval` | 9 | 0 | 9 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.static-group` | 8 | 1 | 9 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.priority-flow-control.priority-config.direction` | 6 | 3 | 9 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.priority-flow-control.priority-config.priority` | 6 | 3 | 9 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.vlan-translate.origin` | 5 | 4 | 9 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.vlan-translate.translated` | 5 | 4 | 9 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.override-negotiation` | 6 | 2 | 8 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.dr-priority` | 7 | 1 | 8 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.vsx.shutdown-on-split` | 2 | 6 | 8 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.med.network-policy` | 6 | 1 | 7 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-dense.source-address-any` | 7 | 0 | 7 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.packet-rate` | 6 | 1 | 7 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.query-max-response-time` | 6 | 0 | 6 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.bfd-enable` | 5 | 1 | 6 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.instance-id` | 4 | 2 | 6 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.client-auto-logoff-enable` | 4 | 1 | 5 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.blocked-vlan` | 3 | 2 | 5 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.hello-interval` | 5 | 0 | 5 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.canned-eap-success-enable` | 4 | 0 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.arp.timeout` | 3 | 1 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.last-member-query-interval` | 4 | 0 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.robustness` | 4 | 0 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ip-directed-broadcast-enable` | 3 | 1 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.mac-phy` | 2 | 2 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.hello-delay` | 4 | 0 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.cost` | 2 | 2 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-supp.enable` | 0 | 4 | 4 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-auth.cdp` | 1 | 2 | 3 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.policy-in` | 3 | 0 | 3 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.re-enable-timer` | 3 | 0 | 3 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.threshold-profile` | 1 | 2 | 3 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.querier-enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4.secondary-ip` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.enable` | 1 | 1 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.elin-addr` | 1 | 1 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.llfc-pool-id` | 1 | 1 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.trap` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mld.enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.registration` | 1 | 1 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim6-sparse.enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv6-access-list-out` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ptp.vlan` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.priority` | 2 | 0 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.priority` | 1 | 1 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.link-clock-narrow-tolerance` | 0 | 2 | 2 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.cached-critical-role-enable` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.arp.neighbor.address` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.arp.neighbor.mac-address` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv6-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.strict-version` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ip-unnumbered-interface-loopback` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.advertise` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.default` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.management-tlv-ipv4-addr` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.transmit-interval` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mld-snooping-eth.forward-vlan` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.join-timer` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.leaveall-timer` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.periodic-timer` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.ra-guard-policy` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pfc-watchdog` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.bsr-boundary` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.datapath-auto-include` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.source-address` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.policy.mac-access-list-out` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.qos.burst` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.ip` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.port` | 1 | 0 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ip-source-lockdown.ipv6` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.dad-attempts` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.preference` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-type` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-value` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.country-code` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.what` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.mfs` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.macsec.enable` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.cable-length` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv6-monitor` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.headroom` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.priority` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.xon-delta` | 0 | 1 | 1 |
| `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.forbidden-vlan-list` | 0 | 1 | 1 |

### aruba-interface-portchannel

- **Leaf Count:** 119
- **Big Cluster Customers:** 46925
- **Small Cluster Customers:** 23592
- **Total Customers Affected:** 70517

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-portchannel:portchannels.interface.name` | 4237 | 2130 | 6367 |
| `aruba-interface-portchannel:portchannels.interface.enable` | 4223 | 2126 | 6349 |
| `aruba-interface-portchannel:portchannels.interface.switchport.interface-mode` | 4210 | 2122 | 6332 |
| `aruba-interface-portchannel:portchannels.interface.port-list` | 4052 | 2059 | 6111 |
| `aruba-interface-portchannel:portchannels.interface.switchport.native-vlan` | 4067 | 2031 | 6098 |
| `aruba-interface-portchannel:portchannels.interface.lacp.mode` | 3882 | 1965 | 5847 |
| `aruba-interface-portchannel:portchannels.interface.trunk-type` | 3881 | 1966 | 5847 |
| `aruba-interface-portchannel:portchannels.interface.routing` | 3413 | 1815 | 5228 |
| `aruba-interface-portchannel:portchannels.interface.description` | 3508 | 1691 | 5199 |
| `aruba-interface-portchannel:portchannels.interface.switchport.trunk-vlan-all` | 3006 | 1441 | 4447 |
| `aruba-interface-portchannel:portchannels.interface.switchport.trunk-vlan-ranges` | 2371 | 1263 | 3634 |
| `aruba-interface-portchannel:portchannels.interface.switchport.access-vlan` | 1059 | 600 | 1659 |
| `aruba-interface-portchannel:portchannels.interface.switchport.tag` | 574 | 265 | 839 |
| `aruba-interface-portchannel:portchannels.interface.dhcpv4-snooping.trust` | 605 | 220 | 825 |
| `aruba-interface-portchannel:portchannels.interface.lacp.rate` | 470 | 258 | 728 |
| `aruba-interface-portchannel:portchannels.interface.loop-protect.enable` | 375 | 196 | 571 |
| `aruba-interface-portchannel:portchannels.interface.stp.root-guard` | 364 | 191 | 555 |
| `aruba-interface-portchannel:portchannels.interface.stp.admin-edge-port` | 234 | 117 | 351 |
| `aruba-interface-portchannel:portchannels.interface.stp.bpdu-filter` | 217 | 111 | 328 |
| `aruba-interface-portchannel:portchannels.interface.lacp.fallback` | 190 | 103 | 293 |
| `aruba-interface-portchannel:portchannels.interface.qos.trust` | 211 | 74 | 285 |
| `aruba-interface-portchannel:portchannels.interface.stp.loop-guard` | 180 | 85 | 265 |
| `aruba-interface-portchannel:portchannels.interface.stp.bpdu-guard` | 142 | 66 | 208 |
| `aruba-interface-portchannel:portchannels.interface.dynamic-arp-inspection.trust` | 96 | 54 | 150 |
| `aruba-interface-portchannel:portchannels.interface.ipv4.address` | 84 | 51 | 135 |
| `aruba-interface-portchannel:portchannels.interface.lacp.fallback-static` | 84 | 46 | 130 |
| `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.rate-type` | 88 | 33 | 121 |
| `aruba-interface-portchannel:portchannels.interface.mode` | 96 | 24 | 120 |
| `aruba-interface-portchannel:portchannels.interface.loop-protect.action` | 58 | 44 | 102 |
| `aruba-interface-portchannel:portchannels.interface.stp.tcn-guard` | 65 | 29 | 94 |
| `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.rate-type` | 54 | 21 | 75 |
| `aruba-interface-portchannel:portchannels.interface.hashing` | 45 | 28 | 73 |
| `aruba-interface-portchannel:portchannels.interface.stp.link-type` | 49 | 20 | 69 |
| `aruba-interface-portchannel:portchannels.interface.stp.rpvst-filter` | 31 | 38 | 69 |
| `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.bit-rate` | 51 | 14 | 65 |
| `aruba-interface-portchannel:portchannels.interface.vrf-forwarding` | 32 | 20 | 52 |
| `aruba-interface-portchannel:portchannels.interface.stp.priority` | 40 | 11 | 51 |
| `aruba-interface-portchannel:portchannels.interface.dhcpv6-snooping.trust` | 33 | 14 | 47 |
| `aruba-interface-portchannel:portchannels.interface.loop-protect.vlans` | 23 | 23 | 46 |
| `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.packet-rate` | 29 | 16 | 45 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.client-limit` | 39 | 5 | 44 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.device-profile-secure` | 32 | 9 | 41 |
| `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.bit-rate` | 29 | 8 | 37 |
| `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.rate-type` | 22 | 7 | 29 |
| `aruba-interface-portchannel:portchannels.interface.policy.ipv4-access-list-in` | 10 | 17 | 27 |
| `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.packet-rate` | 16 | 10 | 26 |
| `aruba-interface-portchannel:portchannels.interface.sflow.enable` | 20 | 6 | 26 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.bpdu-bypass.lldp` | 23 | 2 | 25 |
| `aruba-interface-portchannel:portchannels.interface.ip.mtu` | 18 | 6 | 24 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.bpdu-bypass.cdp` | 19 | 2 | 21 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.allow-flood-traffic` | 15 | 5 | 20 |
| `aruba-interface-portchannel:portchannels.interface.mac-notify-traps` | 12 | 8 | 20 |
| `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.icmp-traffic-type` | 17 | 3 | 20 |
| `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.rate-type` | 17 | 3 | 20 |
| `aruba-interface-portchannel:portchannels.interface.stp.cost` | 14 | 5 | 19 |
| `aruba-interface-portchannel:portchannels.interface.ipfix-flow-monitor-in.ipv4-monitor` | 7 | 11 | 18 |
| `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.percentage` | 11 | 7 | 18 |
| `aruba-interface-portchannel:portchannels.interface.pvlan-port-mode` | 10 | 6 | 16 |
| `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.bit-rate` | 13 | 2 | 15 |
| `aruba-interface-portchannel:portchannels.interface.policy.ipv4-access-list-out` | 9 | 5 | 14 |
| `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.percentage` | 9 | 5 | 14 |
| `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.packet-rate` | 8 | 5 | 13 |
| `aruba-interface-portchannel:portchannels.interface.igmp-snooping-lag.forward-vlan` | 6 | 6 | 12 |
| `aruba-interface-portchannel:portchannels.interface.profile-name` | 6 | 6 | 12 |
| `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.bit-rate` | 10 | 1 | 11 |
| `aruba-interface-portchannel:portchannels.interface.client-limit` | 5 | 5 | 10 |
| `aruba-interface-portchannel:portchannels.interface.update-interval` | 6 | 4 | 10 |
| `aruba-interface-portchannel:portchannels.interface.ip.l3-counters` | 7 | 2 | 9 |
| `aruba-interface-portchannel:portchannels.interface.qos.schedule-profile` | 4 | 5 | 9 |
| `aruba-interface-portchannel:portchannels.interface.nd-snooping.trust` | 4 | 4 | 8 |
| `aruba-interface-portchannel:portchannels.interface.stp.rpvst-guard` | 7 | 1 | 8 |
| `aruba-interface-portchannel:portchannels.interface.ptp.enable` | 5 | 2 | 7 |
| `aruba-interface-portchannel:portchannels.interface.macsec-policy` | 4 | 2 | 6 |
| `aruba-interface-portchannel:portchannels.interface.mka-policy` | 4 | 2 | 6 |
| `aruba-interface-portchannel:portchannels.interface.pim-sparse.enable` | 2 | 3 | 5 |
| `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.percentage` | 4 | 1 | 5 |
| `aruba-interface-portchannel:portchannels.interface.ipv6.addresses.address` | 3 | 1 | 4 |
| `aruba-interface-portchannel:portchannels.interface.ipv6.enable-default-link-local` | 4 | 0 | 4 |
| `aruba-interface-portchannel:portchannels.interface.vlan-translate.origin` | 3 | 1 | 4 |
| `aruba-interface-portchannel:portchannels.interface.vlan-translate.translated` | 3 | 1 | 4 |
| `aruba-interface-portchannel:portchannels.interface.policy.ipv6-access-list-out` | 0 | 4 | 4 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.auth-mode` | 3 | 0 | 3 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.security-violation.action` | 3 | 0 | 3 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.security-violation.recovery-timer` | 3 | 0 | 3 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.security-violation.shutdown-recovery-enable` | 3 | 0 | 3 |
| `aruba-interface-portchannel:portchannels.interface.igmp-snooping-lag.blocked-vlan` | 3 | 0 | 3 |
| `aruba-interface-portchannel:portchannels.interface.policy.ipv6-access-list-in` | 2 | 1 | 3 |
| `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.packet-rate` | 2 | 1 | 3 |
| `aruba-interface-portchannel:portchannels.interface.stp.mstp.instance-id` | 3 | 0 | 3 |
| `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.percentage` | 2 | 0 | 2 |
| `aruba-interface-portchannel:portchannels.interface.stp.mstp.priority` | 2 | 0 | 2 |
| `aruba-interface-portchannel:portchannels.interface.policy.mac-access-list-in` | 0 | 2 | 2 |
| `aruba-interface-portchannel:portchannels.interface.stp.rpvst.vlan-id` | 0 | 2 | 2 |
| `aruba-interface-portchannel:portchannels.interface.qos.dscp` | 0 | 2 | 2 |
| `aruba-interface-portchannel:portchannels.interface.qos.egress-rate` | 0 | 2 | 2 |
| `aruba-interface-portchannel:portchannels.interface.qos.max-rate-units` | 0 | 2 | 2 |
| `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.bpdu-auth.mac-type` | 0 | 2 | 2 |
| `aruba-interface-portchannel:portchannels.interface.arp.timeout` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.bfd.detect-multiplier` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.bfd.min-rx-interval` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.bfd.min-tx-interval` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.mvrp.enable` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.mvrp.forbidden-vlan-list` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.mvrp.registration` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.nd-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.portfilter.eth-ports` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.portfilter.lag-ports` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.qos.threshold-profile` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.stp.mstp.cost` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.vrrp.vrrp-profile-apply` | 1 | 0 | 1 |
| `aruba-interface-portchannel:portchannels.interface.igmp.enable` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.stp.rpvst.cost` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.stp.rpvst.priority` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.ipfix-flow-monitor-in.ipv6-monitor` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.pim-dense.enable` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.pim6-dense.enable` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.qos.cos` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.client-limit-max` | 0 | 1 | 1 |
| `aruba-interface-portchannel:portchannels.interface.pim-sparse.source-address-any` | 0 | 1 | 1 |

### aruba-switch-stack

- **Leaf Count:** 11
- **Big Cluster Customers:** 32535
- **Small Cluster Customers:** 16918
- **Total Customers Affected:** 49453

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-switch-stack:stacks.stack.name` | 5701 | 3022 | 8723 |
| `aruba-switch-stack:stacks.stack.members.id` | 5675 | 3022 | 8697 |
| `aruba-switch-stack:stacks.stack.members.sku` | 5671 | 3022 | 8693 |
| `aruba-switch-stack:stacks.stack.platform` | 5671 | 3022 | 8693 |
| `aruba-switch-stack:stacks.stack.members.links.link1.interfaces` | 3227 | 1643 | 4870 |
| `aruba-switch-stack:stacks.stack.members.links.link2.interfaces` | 3006 | 1505 | 4511 |
| `aruba-switch-stack:stacks.stack.secondary-member` | 2641 | 1374 | 4015 |
| `aruba-switch-stack:stacks.stack.split-detection-method` | 826 | 291 | 1117 |
| `aruba-switch-stack:stacks.stack.members.hw-profile` | 88 | 0 | 88 |
| `aruba-switch-stack:stacks.stack.members.links.link1.description` | 18 | 11 | 29 |
| `aruba-switch-stack:stacks.stack.members.links.link2.description` | 11 | 6 | 17 |

### aruba-vsf-template

- **Leaf Count:** 5
- **Big Cluster Customers:** 20027
- **Small Cluster Customers:** 10516
- **Total Customers Affected:** 30543

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-vsf-template:vsf-templates.template.name` | 5558 | 2963 | 8521 |
| `aruba-vsf-template:vsf-templates.template.members.id` | 5501 | 2944 | 8445 |
| `aruba-vsf-template:vsf-templates.template.members.sku` | 5501 | 2944 | 8445 |
| `aruba-vsf-template:vsf-templates.template.secondary-member` | 2641 | 1374 | 4015 |
| `aruba-vsf-template:vsf-templates.template.split-detection-method` | 826 | 291 | 1117 |

### aruba-vsx

- **Leaf Count:** 17
- **Big Cluster Customers:** 6064
- **Small Cluster Customers:** 3741
- **Total Customers Affected:** 9805

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-vsx:vsx-profiles.vsx.name` | 847 | 505 | 1352 |
| `aruba-vsx:vsx-profiles.vsx.peer1.role` | 774 | 492 | 1266 |
| `aruba-vsx:vsx-profiles.vsx.peer2.role` | 774 | 492 | 1266 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.system-mac` | 704 | 425 | 1129 |
| `aruba-vsx:vsx-profiles.vsx.peer1.keepalive-device.peer-ip` | 680 | 422 | 1102 |
| `aruba-vsx:vsx-profiles.vsx.peer1.keepalive-device.source-ip` | 680 | 422 | 1102 |
| `aruba-vsx:vsx-profiles.vsx.peer2.keepalive-device.peer-ip` | 680 | 422 | 1102 |
| `aruba-vsx:vsx-profiles.vsx.peer2.keepalive-device.source-ip` | 680 | 422 | 1102 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.linkup-delay-timer` | 138 | 102 | 240 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.hold-time` | 24 | 7 | 31 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.hello-interval` | 21 | 7 | 28 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.dead-interval` | 18 | 9 | 27 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.peer-detect-interval` | 17 | 4 | 21 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.split-recovery-disable` | 16 | 4 | 20 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.keepalive.dead-interval` | 4 | 4 | 8 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.keepalive.hello-interval` | 3 | 2 | 5 |
| `aruba-vsx:vsx-profiles.vsx.sync-features.keepalive.udp-port` | 4 | 0 | 4 |

### aruba-vlan-range

- **Leaf Count:** 21
- **Big Cluster Customers:** 6676
- **Small Cluster Customers:** 2123
- **Total Customers Affected:** 8799

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-vlan-range:layer2-vlan-range.client-ip-tracker-enable` | 2168 | 1190 | 3358 |
| `aruba-vlan-range:layer2-vlan-range.enable` | 2000 | 76 | 2076 |
| `aruba-vlan-range:layer2-vlan-range.igmp.snooping` | 958 | 347 | 1305 |
| `aruba-vlan-range:layer2-vlan-range.dhcpv4-snooping.enable` | 781 | 294 | 1075 |
| `aruba-vlan-range:layer2-vlan-range.igmp.version` | 281 | 120 | 401 |
| `aruba-vlan-range:layer2-vlan-range.voice-enable` | 301 | 0 | 301 |
| `aruba-vlan-range:layer2-vlan-range.dhcpv6-snooping.enable` | 85 | 39 | 124 |
| `aruba-vlan-range:layer2-vlan-range.policy-in` | 29 | 24 | 53 |
| `aruba-vlan-range:layer2-vlan-range.mld.snooping` | 18 | 9 | 27 |
| `aruba-vlan-range:layer2-vlan-range.igmp.static-group` | 17 | 4 | 21 |
| `aruba-vlan-range:layer2-vlan-range.policy-out` | 8 | 3 | 11 |
| `aruba-vlan-range:layer2-vlan-range.igmp.preprogram-starg-flow` | 5 | 5 | 10 |
| `aruba-vlan-range:layer2-vlan-range.igmp.policy-in` | 6 | 1 | 7 |
| `aruba-vlan-range:layer2-vlan-range.nd-snooping.nd-guard` | 4 | 2 | 6 |
| `aruba-vlan-range:layer2-vlan-range.nd-snooping.ra-drop` | 4 | 1 | 5 |
| `aruba-vlan-range:layer2-vlan-range.nd-snooping.ra-guard-log` | 3 | 2 | 5 |
| `aruba-vlan-range:layer2-vlan-range.dhcpv4-snooping.ip-binding-enable` | 4 | 0 | 4 |
| `aruba-vlan-range:layer2-vlan-range.nd-snooping.allow-bindings-on-trusted-ports` | 0 | 4 | 4 |
| `aruba-vlan-range:layer2-vlan-range.dynamic-arp-inspection.enable` | 2 | 1 | 3 |
| `aruba-vlan-range:layer2-vlan-range.destination-guard.enable` | 2 | 0 | 2 |
| `aruba-vlan-range:layer2-vlan-range.dhcpv6-snooping.allow-bindings-on-trusted-ports` | 0 | 1 | 1 |

### aruba-vsx-pair

- **Leaf Count:** 18
- **Big Cluster Customers:** 5237
- **Small Cluster Customers:** 3135
- **Total Customers Affected:** 8372

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-vsx-pair:vsx-config.vsx.name` | 866 | 513 | 1379 |
| `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-lag` | 854 | 511 | 1365 |
| `aruba-vsx-pair:vsx-config.vsx.role` | 774 | 492 | 1266 |
| `aruba-vsx-pair:vsx-config.vsx.system-mac` | 704 | 425 | 1129 |
| `aruba-vsx-pair:vsx-config.vsx.keepalive.peer-ip` | 594 | 350 | 944 |
| `aruba-vsx-pair:vsx-config.vsx.keepalive.source-ip` | 594 | 350 | 944 |
| `aruba-vsx-pair:vsx-config.vsx.keepalive.vrf-ref` | 594 | 350 | 944 |
| `aruba-vsx-pair:vsx-config.vsx.linkup-delay-timer` | 138 | 102 | 240 |
| `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.hold-time` | 24 | 7 | 31 |
| `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.hello-interval` | 21 | 7 | 28 |
| `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.dead-interval` | 18 | 9 | 27 |
| `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.peer-detect-interval` | 17 | 4 | 21 |
| `aruba-vsx-pair:vsx-config.vsx.split-recovery-disable` | 16 | 4 | 20 |
| `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-eth` | 10 | 4 | 14 |
| `aruba-vsx-pair:vsx-config.vsx.keepalive.dead-interval` | 4 | 4 | 8 |
| `aruba-vsx-pair:vsx-config.vsx.keepalive.hello-interval` | 3 | 2 | 5 |
| `aruba-vsx-pair:vsx-config.vsx.keepalive.udp-port` | 4 | 0 | 4 |
| `aruba-vsx-pair:vsx-config.vsx.linkup-delay-timer-exclude` | 2 | 1 | 3 |

### aruba-aaa-dot1xauth

- **Leaf Count:** 13
- **Big Cluster Customers:** 7010
- **Small Cluster Customers:** 771
- **Total Customers Affected:** 7781

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-aaa-dot1xauth:dot1xauth.profile.name` | 4063 | 646 | 4709 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.enable` | 2365 | 41 | 2406 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.reauth-period` | 116 | 9 | 125 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.eapol-max-requests` | 69 | 13 | 82 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.max-retries` | 69 | 11 | 80 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.eapol-timeout` | 69 | 9 | 78 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.cached-reauth-period` | 65 | 8 | 73 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.quiet-period` | 57 | 8 | 65 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.cached-reauth-enable` | 54 | 9 | 63 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.reauth-enable` | 47 | 10 | 57 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.discovery-period` | 19 | 4 | 23 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.initial-auth-response-timeout` | 15 | 3 | 18 |
| `aruba-aaa-dot1xauth:dot1xauth.profile.canned-eap-success-enable` | 2 | 0 | 2 |

### aruba-aaa-macauth

- **Leaf Count:** 7
- **Big Cluster Customers:** 6782
- **Small Cluster Customers:** 743
- **Total Customers Affected:** 7525

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-aaa-macauth:macauth.profile.name` | 4078 | 663 | 4741 |
| `aruba-aaa-macauth:macauth.profile.enable` | 2365 | 39 | 2404 |
| `aruba-aaa-macauth:macauth.profile.reauth-period` | 116 | 8 | 124 |
| `aruba-aaa-macauth:macauth.profile.cached-reauth-period` | 65 | 8 | 73 |
| `aruba-aaa-macauth:macauth.profile.quiet-period` | 57 | 8 | 65 |
| `aruba-aaa-macauth:macauth.profile.cached-reauth-enable` | 54 | 9 | 63 |
| `aruba-aaa-macauth:macauth.profile.reauth-enable` | 47 | 8 | 55 |

### aruba-qos-dscp

- **Leaf Count:** 7
- **Big Cluster Customers:** 7219
- **Small Cluster Customers:** 0
- **Total Customers Affected:** 7219

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos-dscp:qos-dscp.profile.dscp-map.dscp` | 1839 | 0 | 1839 |
| `aruba-qos-dscp:qos-dscp.profile.name` | 1839 | 0 | 1839 |
| `aruba-qos-dscp:qos-dscp.profile.dscp-map.local-priority` | 1661 | 0 | 1661 |
| `aruba-qos-dscp:qos-dscp.profile.dscp-map.color` | 1512 | 0 | 1512 |
| `aruba-qos-dscp:qos-dscp.profile.dscp-map.name` | 258 | 0 | 258 |
| `aruba-qos-dscp:qos-dscp.profile.dscp-map.cos` | 101 | 0 | 101 |
| `aruba-qos-dscp:qos-dscp.profile.dscp-map.cos-override` | 9 | 0 | 9 |

### aruba-named-condition

- **Leaf Count:** 3
- **Big Cluster Customers:** 4916
- **Small Cluster Customers:** 750
- **Total Customers Affected:** 5666

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-named-condition:named-conditions.named-condition.condition-rule.position` | 2372 | 353 | 2725 |
| `aruba-named-condition:named-conditions.named-condition.name` | 2372 | 353 | 2725 |
| `aruba-named-condition:named-conditions.named-condition.condition-rule.description` | 172 | 44 | 216 |

### aruba-loop-protect

- **Leaf Count:** 4
- **Big Cluster Customers:** 3964
- **Small Cluster Customers:** 883
- **Total Customers Affected:** 4847

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-loop-protect:loop-protect.profile.name` | 1622 | 369 | 1991 |
| `aruba-loop-protect:loop-protect.profile.re-enable-timer` | 1264 | 300 | 1564 |
| `aruba-loop-protect:loop-protect.profile.trap` | 933 | 137 | 1070 |
| `aruba-loop-protect:loop-protect.profile.transmit-interval` | 145 | 77 | 222 |

### aruba-switch-profiles

- **Leaf Count:** 2
- **Big Cluster Customers:** 2322
- **Small Cluster Customers:** 1410
- **Total Customers Affected:** 3732

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-switch-profiles:switch-profiles.profile.name` | 1161 | 705 | 1866 |
| `aruba-switch-profiles:switch-profiles.profile.selected` | 1161 | 705 | 1866 |

### aruba-switch-chassis

- **Leaf Count:** 7
- **Big Cluster Customers:** 2224
- **Small Cluster Customers:** 622
- **Total Customers Affected:** 2846

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-switch-chassis:switch-chassis.chassis.chassis-name` | 793 | 156 | 949 |
| `aruba-switch-chassis:switch-chassis.chassis.line-modules.line-module-name` | 793 | 156 | 949 |
| `aruba-switch-chassis:switch-chassis.chassis.line-modules.sku` | 313 | 155 | 468 |
| `aruba-switch-chassis:switch-chassis.chassis.platform` | 313 | 155 | 468 |
| `aruba-switch-chassis:switch-chassis.chassis.line-modules.hw-profile` | 7 | 0 | 7 |
| `aruba-switch-chassis:switch-chassis.chassis.line-modules.power-admin-state` | 4 | 0 | 4 |
| `aruba-switch-chassis:switch-chassis.chassis.line-modules.power-priority` | 1 | 0 | 1 |

### aruba-job-scheduler

- **Leaf Count:** 31
- **Big Cluster Customers:** 1700
- **Small Cluster Customers:** 968
- **Total Customers Affected:** 2668

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-job-scheduler:job-scheduler.schedule.name` | 194 | 85 | 279 |
| `aruba-job-scheduler:job-scheduler.schedule.job.job-name` | 176 | 82 | 258 |
| `aruba-job-scheduler:job-scheduler.schedule.job.entry.sequence-number` | 136 | 75 | 211 |
| `aruba-job-scheduler:job-scheduler.schedule.job.entry.cli-command` | 135 | 75 | 210 |
| `aruba-job-scheduler:job-scheduler.schedule.job.entry.type` | 135 | 75 | 210 |
| `aruba-job-scheduler:job-scheduler.schedule.trigger-type` | 117 | 68 | 185 |
| `aruba-job-scheduler:job-scheduler.schedule.schedule-entry.schedule-job` | 113 | 67 | 180 |
| `aruba-job-scheduler:job-scheduler.schedule.schedule-entry.sequence-number` | 113 | 67 | 180 |
| `aruba-job-scheduler:job-scheduler.schedule.start-date-at` | 82 | 23 | 105 |
| `aruba-job-scheduler:job-scheduler.schedule.start-time-at` | 82 | 23 | 105 |
| `aruba-job-scheduler:job-scheduler.schedule.trigger-at` | 82 | 23 | 105 |
| `aruba-job-scheduler:job-scheduler.schedule.job.description` | 53 | 34 | 87 |
| `aruba-job-scheduler:job-scheduler.schedule.frequency` | 31 | 36 | 67 |
| `aruba-job-scheduler:job-scheduler.schedule.start-time-on` | 31 | 36 | 67 |
| `aruba-job-scheduler:job-scheduler.schedule.trigger-on` | 31 | 36 | 67 |
| `aruba-job-scheduler:job-scheduler.schedule.description` | 41 | 26 | 67 |
| `aruba-job-scheduler:job-scheduler.schedule.start-date-on` | 29 | 33 | 62 |
| `aruba-job-scheduler:job-scheduler.schedule.trigger-on-weekly` | 16 | 14 | 30 |
| `aruba-job-scheduler:job-scheduler.schedule.week-day` | 16 | 14 | 30 |
| `aruba-job-scheduler:job-scheduler.schedule.trigger-every` | 12 | 13 | 25 |
| `aruba-job-scheduler:job-scheduler.schedule.start-time-every` | 12 | 12 | 24 |
| `aruba-job-scheduler:job-scheduler.schedule.start-date-every` | 11 | 10 | 21 |
| `aruba-job-scheduler:job-scheduler.schedule.job.entry.cli-delay` | 13 | 5 | 18 |
| `aruba-job-scheduler:job-scheduler.schedule.count` | 8 | 10 | 18 |
| `aruba-job-scheduler:job-scheduler.schedule.days` | 4 | 10 | 14 |
| `aruba-job-scheduler:job-scheduler.schedule.enable` | 13 | 0 | 13 |
| `aruba-job-scheduler:job-scheduler.schedule.minutes` | 7 | 3 | 10 |
| `aruba-job-scheduler:job-scheduler.schedule.trigger-on-monthly` | 2 | 6 | 8 |
| `aruba-job-scheduler:job-scheduler.schedule.month-day` | 2 | 5 | 7 |
| `aruba-job-scheduler:job-scheduler.schedule.job.enable` | 2 | 1 | 3 |
| `aruba-job-scheduler:job-scheduler.schedule.hours` | 1 | 1 | 2 |

### aruba-hardware-module-profile

- **Leaf Count:** 6
- **Big Cluster Customers:** 1531
- **Small Cluster Customers:** 1047
- **Total Customers Affected:** 2578

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-hardware-module-profile:hardware-modules.hw-profile.name` | 523 | 321 | 844 |
| `aruba-hardware-module-profile:hardware-modules.hw-profile.interface-group-speed-profile.group-id` | 470 | 305 | 775 |
| `aruba-hardware-module-profile:hardware-modules.hw-profile.interface-group-speed-profile.speed` | 468 | 305 | 773 |
| `aruba-hardware-module-profile:hardware-modules.hw-profile.member-or-slot-ids` | 0 | 94 | 94 |
| `aruba-hardware-module-profile:hardware-modules.hw-profile.always-on-poe` | 44 | 17 | 61 |
| `aruba-hardware-module-profile:hardware-modules.hw-profile.quick-poe` | 26 | 5 | 31 |

### aruba-qos

- **Leaf Count:** 3
- **Big Cluster Customers:** 1761
- **Small Cluster Customers:** 0
- **Total Customers Affected:** 1761

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos:global-qos.trust` | 1327 | 0 | 1327 |
| `aruba-qos:global-qos.q-profile` | 217 | 0 | 217 |
| `aruba-qos:global-qos.sched-profile` | 217 | 0 | 217 |

### aruba-devicefingerprinting

- **Leaf Count:** 2
- **Big Cluster Customers:** 724
- **Small Cluster Customers:** 960
- **Total Customers Affected:** 1684

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-devicefingerprinting:devicefingerprinting.profile.name` | 362 | 480 | 842 |
| `aruba-devicefingerprinting:devicefingerprinting.profile.profile-name` | 362 | 480 | 842 |

### aruba-snmp-trap

- **Leaf Count:** 5
- **Big Cluster Customers:** 771
- **Small Cluster Customers:** 789
- **Total Customers Affected:** 1560

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-snmp-trap:snmp-trap.profile.name` | 202 | 198 | 400 |
| `aruba-snmp-trap:snmp-trap.profile.trap.id` | 201 | 198 | 399 |
| `aruba-snmp-trap:snmp-trap.profile.trap.enable` | 164 | 133 | 297 |
| `aruba-snmp-trap:snmp-trap.profile.trap.snmp-server-trap` | 102 | 130 | 232 |
| `aruba-snmp-trap:snmp-trap.profile.trap.vrf` | 102 | 130 | 232 |

### aruba-qos-schedule

- **Leaf Count:** 15
- **Big Cluster Customers:** 1009
- **Small Cluster Customers:** 544
- **Total Customers Affected:** 1553

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos-schedule:qos-schedules.profile.sched-profile-name` | 253 | 136 | 389 |
| `aruba-qos-schedule:qos-schedules.profile.strict.queue` | 230 | 0 | 230 |
| `aruba-qos-schedule:qos-schedules.profile.dwrr.queue` | 201 | 0 | 201 |
| `aruba-qos-schedule:qos-schedules.profile.dwrr.weight` | 201 | 0 | 201 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.algorithm` | 0 | 131 | 131 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.queue` | 0 | 131 | 131 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.weight` | 0 | 109 | 109 |
| `aruba-qos-schedule:qos-schedules.profile.min-bandwidths.minimum-bandwidth` | 57 | 0 | 57 |
| `aruba-qos-schedule:qos-schedules.profile.min-bandwidths.queue` | 57 | 0 | 57 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.minimum-bandwidth` | 0 | 21 | 21 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.max-bandwidth-kbps` | 0 | 10 | 10 |
| `aruba-qos-schedule:qos-schedules.profile.strict.max-bandwidth-kbps` | 7 | 0 | 7 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.max-bandwidth-percent` | 0 | 5 | 5 |
| `aruba-qos-schedule:qos-schedules.profile.strict.max-bandwidth-percent` | 3 | 0 | 3 |
| `aruba-qos-schedule:qos-schedules.profile.sched-entries.burst` | 0 | 1 | 1 |

### aruba-qos-queue

- **Leaf Count:** 6
- **Big Cluster Customers:** 860
- **Small Cluster Customers:** 448
- **Total Customers Affected:** 1308

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos-queue:qos-queues.profile.q-profile-name` | 232 | 129 | 361 |
| `aruba-qos-queue:qos-queues.profile.priority.queue` | 223 | 120 | 343 |
| `aruba-qos-queue:qos-queues.profile.priority.name` | 168 | 79 | 247 |
| `aruba-qos-queue:qos-queues.profile.priority.local-priority` | 182 | 0 | 182 |
| `aruba-qos-queue:qos-queues.profile.priority.priorities` | 0 | 120 | 120 |
| `aruba-qos-queue:qos-queues.profile.priority.cos` | 55 | 0 | 55 |

### aruba-port-security

- **Leaf Count:** 4
- **Big Cluster Customers:** 727
- **Small Cluster Customers:** 464
- **Total Customers Affected:** 1191

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-port-security:port-security.policy.name` | 256 | 167 | 423 |
| `aruba-port-security:port-security.policy.enable` | 197 | 138 | 335 |
| `aruba-port-security:port-security.policy.client-limit` | 185 | 91 | 276 |
| `aruba-port-security:port-security.policy.sticky-mac-enable` | 89 | 68 | 157 |

### aruba-ip-icmp-tcp

- **Leaf Count:** 4
- **Big Cluster Customers:** 1168
- **Small Cluster Customers:** 0
- **Total Customers Affected:** 1168

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.name` | 555 | 0 | 555 |
| `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.redirect` | 530 | 0 | 530 |
| `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.unreachable` | 82 | 0 | 82 |
| `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.throttle` | 1 | 0 | 1 |

### aruba-certificate-rcp

- **Leaf Count:** 7
- **Big Cluster Customers:** 869
- **Small Cluster Customers:** 280
- **Total Customers Affected:** 1149

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-certificate-rcp:certificate-rcp.ta-profile.name` | 833 | 256 | 1089 |
| `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.vrf` | 23 | 10 | 33 |
| `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.enforcement-level` | 11 | 5 | 16 |
| `aruba-certificate-rcp:certificate-rcp.ta-profile.rcp-primary-method` | 0 | 5 | 5 |
| `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.disable-nonce` | 2 | 1 | 3 |
| `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.primary-url` | 0 | 2 | 2 |
| `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.secondary-url` | 0 | 1 | 1 |

### aruba-interface-vxlan

- **Leaf Count:** 13
- **Big Cluster Customers:** 798
- **Small Cluster Customers:** 316
- **Total Customers Affected:** 1114

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-vxlan:vxlan.profile.name` | 129 | 52 | 181 |
| `aruba-interface-vxlan:vxlan.profile.vni.id` | 124 | 51 | 175 |
| `aruba-interface-vxlan:vxlan.profile.enable` | 121 | 51 | 172 |
| `aruba-interface-vxlan:vxlan.profile.src-ipv4` | 114 | 51 | 165 |
| `aruba-interface-vxlan:vxlan.profile.vni.vlan` | 112 | 48 | 160 |
| `aruba-interface-vxlan:vxlan.profile.vni.symmetric-routing` | 79 | 24 | 103 |
| `aruba-interface-vxlan:vxlan.profile.vni.vrf` | 79 | 24 | 103 |
| `aruba-interface-vxlan:vxlan.profile.bridging-mode` | 21 | 7 | 28 |
| `aruba-interface-vxlan:vxlan.profile.enable-counters` | 14 | 4 | 18 |
| `aruba-interface-vxlan:vxlan.profile.description` | 4 | 2 | 6 |
| `aruba-interface-vxlan:vxlan.profile.loop-protect-vlans` | 0 | 1 | 1 |
| `aruba-interface-vxlan:vxlan.profile.loop-protect` | 1 | 0 | 1 |
| `aruba-interface-vxlan:vxlan.profile.mac-notify-traps` | 0 | 1 | 1 |

### aruba-ipfix-flow-record

- **Leaf Count:** 25
- **Big Cluster Customers:** 493
- **Small Cluster Customers:** 560
- **Total Customers Affected:** 1053

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.counter-bytes` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-source-address` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.transport-destination-port` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.transport-source-port` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.name` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-version` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-destination-address` | 35 | 39 | 74 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-protocol` | 35 | 39 | 74 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.counter-packets` | 35 | 39 | 74 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.timestamp-absolute-first` | 29 | 38 | 67 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.timestamp-absolute-last` | 27 | 38 | 65 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-name` | 30 | 28 | 58 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.description` | 19 | 21 | 40 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-https-url` | 19 | 17 | 36 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-dns-response-code` | 19 | 15 | 34 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-tls-attributes` | 16 | 14 | 30 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.forwarding-status` | 7 | 10 | 17 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-destination-address` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-protocol` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-source-address` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-version` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-tcp-establishment-time` | 2 | 2 | 4 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-interface` | 1 | 2 | 3 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-vlan` | 0 | 2 | 2 |
| `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-queue` | 1 | 0 | 1 |

### aruba-device-certificate

- **Leaf Count:** 16
- **Big Cluster Customers:** 682
- **Small Cluster Customers:** 356
- **Total Customers Affected:** 1038

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-device-certificate:device-certificates.device-certificate.name` | 235 | 114 | 349 |
| `aruba-device-certificate:device-certificates.device-certificate.app-usage` | 208 | 101 | 309 |
| `aruba-device-certificate:device-certificates.device-certificate.subject.common-name` | 66 | 27 | 93 |
| `aruba-device-certificate:device-certificates.device-certificate.subject.org` | 32 | 19 | 51 |
| `aruba-device-certificate:device-certificates.device-certificate.subject.state` | 27 | 19 | 46 |
| `aruba-device-certificate:device-certificates.device-certificate.subject.org-unit` | 28 | 18 | 46 |
| `aruba-device-certificate:device-certificates.device-certificate.subject.locality` | 29 | 16 | 45 |
| `aruba-device-certificate:device-certificates.device-certificate.cert-key-type` | 12 | 11 | 23 |
| `aruba-device-certificate:device-certificates.device-certificate.rsa-key-length` | 7 | 11 | 18 |
| `aruba-device-certificate:device-certificates.device-certificate.est-profile` | 8 | 6 | 14 |
| `aruba-device-certificate:device-certificates.device-certificate.subject.country` | 10 | 3 | 13 |
| `aruba-device-certificate:device-certificates.device-certificate.ext-key-usage` | 5 | 4 | 9 |
| `aruba-device-certificate:device-certificates.device-certificate.key-usage` | 5 | 4 | 9 |
| `aruba-device-certificate:device-certificates.device-certificate.ecdsa-curve-size` | 5 | 0 | 5 |
| `aruba-device-certificate:device-certificates.device-certificate.subject-alt-name-dns` | 3 | 2 | 5 |
| `aruba-device-certificate:device-certificates.device-certificate.subject-alt-name-ip` | 2 | 1 | 3 |

### aruba-object-group

- **Leaf Count:** 11
- **Big Cluster Customers:** 669
- **Small Cluster Customers:** 297
- **Total Customers Affected:** 966

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-object-group:object-groups.group.name` | 108 | 48 | 156 |
| `aruba-object-group:object-groups.group.type` | 108 | 48 | 156 |
| `aruba-object-group:object-groups.group.items.index` | 107 | 48 | 155 |
| `aruba-object-group:object-groups.group.items.address-type` | 99 | 42 | 141 |
| `aruba-object-group:object-groups.group.items.ipv4-address` | 85 | 35 | 120 |
| `aruba-object-group:object-groups.group.items.ipv4-subnet-address` | 73 | 29 | 102 |
| `aruba-object-group:object-groups.group.items.ports.operator` | 41 | 19 | 60 |
| `aruba-object-group:object-groups.group.items.ports.min` | 28 | 19 | 47 |
| `aruba-object-group:object-groups.group.items.ports.max` | 15 | 7 | 22 |
| `aruba-object-group:object-groups.group.items.ipv4-prefix` | 5 | 0 | 5 |
| `aruba-object-group:object-groups.group.vrf` | 0 | 2 | 2 |

### aruba-system-info

- **Leaf Count:** 2
- **Big Cluster Customers:** 615
- **Small Cluster Customers:** 251
- **Total Customers Affected:** 866

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-system-info:system-info.sys-description` | 575 | 229 | 804 |
| `aruba-system-info:system-info.snmpv3-local-engine-id` | 40 | 22 | 62 |

### aruba-nae-agent

- **Leaf Count:** 5
- **Big Cluster Customers:** 487
- **Small Cluster Customers:** 344
- **Total Customers Affected:** 831

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-nae-agent:nae-agents.nae-agent.agent-disable` | 119 | 88 | 207 |
| `aruba-nae-agent:nae-agents.nae-agent.agent-name` | 119 | 88 | 207 |
| `aruba-nae-agent:nae-agents.nae-agent.script-name` | 119 | 88 | 207 |
| `aruba-nae-agent:nae-agents.nae-agent.agent-parameters.name` | 65 | 40 | 105 |
| `aruba-nae-agent:nae-agents.nae-agent.agent-parameters.value` | 65 | 40 | 105 |

### aruba-lldp

- **Leaf Count:** 25
- **Big Cluster Customers:** 535
- **Small Cluster Customers:** 248
- **Total Customers Affected:** 783

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-lldp:lldp.profile.name` | 236 | 109 | 345 |
| `aruba-lldp:lldp.profile.disable` | 70 | 25 | 95 |
| `aruba-lldp:lldp.profile.management-ip-address` | 51 | 28 | 79 |
| `aruba-lldp:lldp.profile.lldp-trap-enable` | 38 | 26 | 64 |
| `aruba-lldp:lldp.profile.tlv.basic.port-descr` | 29 | 11 | 40 |
| `aruba-lldp:lldp.profile.transmit-interval` | 15 | 7 | 22 |
| `aruba-lldp:lldp.profile.reinit-delay` | 17 | 4 | 21 |
| `aruba-lldp:lldp.profile.dcbx-enable` | 11 | 9 | 20 |
| `aruba-lldp:lldp.profile.tlv.basic.management-addr` | 11 | 1 | 12 |
| `aruba-lldp:lldp.profile.tlv.basic.system-descr` | 11 | 1 | 12 |
| `aruba-lldp:lldp.profile.management-vlan` | 5 | 6 | 11 |
| `aruba-lldp:lldp.profile.tlv.dot1.port-vlan-id` | 6 | 1 | 7 |
| `aruba-lldp:lldp.profile.hold-multiplier` | 5 | 2 | 7 |
| `aruba-lldp:lldp.profile.tlv.dot1.port-vlan-name` | 5 | 1 | 6 |
| `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.port-number` | 3 | 2 | 5 |
| `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.priority` | 3 | 2 | 5 |
| `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.protocol` | 3 | 2 | 5 |
| `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.protocol-port-number` | 3 | 2 | 5 |
| `aruba-lldp:lldp.profile.dcbx-version` | 2 | 3 | 5 |
| `aruba-lldp:lldp.profile.tlv.basic.system-cap` | 3 | 1 | 4 |
| `aruba-lldp:lldp.profile.tlv.oui` | 2 | 1 | 3 |
| `aruba-lldp:lldp.profile.tlv.dot1.link-aggregation` | 2 | 1 | 3 |
| `aruba-lldp:lldp.profile.tlv.basic.system-name` | 2 | 1 | 3 |
| `aruba-lldp:lldp.profile.neighbor-last-update-enable` | 1 | 2 | 3 |
| `aruba-lldp:lldp.profile.transmit-delay` | 1 | 0 | 1 |

### aruba-cdp

- **Leaf Count:** 2
- **Big Cluster Customers:** 364
- **Small Cluster Customers:** 190
- **Total Customers Affected:** 554

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-cdp:cdp.profile.enable` | 182 | 95 | 277 |
| `aruba-cdp:cdp.profile.name` | 182 | 95 | 277 |

### aruba-management-user-group

- **Leaf Count:** 6
- **Big Cluster Customers:** 309
- **Small Cluster Customers:** 207
- **Total Customers Affected:** 516

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-management-user-group:management-user-groups.user-group.name` | 109 | 70 | 179 |
| `aruba-management-user-group:management-user-groups.user-group.rule.rbac.action` | 64 | 44 | 108 |
| `aruba-management-user-group:management-user-groups.user-group.rule.rbac.match-command` | 64 | 44 | 108 |
| `aruba-management-user-group:management-user-groups.user-group.rule.seq-number` | 64 | 44 | 108 |
| `aruba-management-user-group:management-user-groups.user-group.rule.description` | 7 | 5 | 12 |
| `aruba-management-user-group:management-user-groups.user-group.inherit-group` | 1 | 0 | 1 |

### aruba-interface-tunnel

- **Leaf Count:** 15
- **Big Cluster Customers:** 321
- **Small Cluster Customers:** 144
- **Total Customers Affected:** 465

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-tunnel:tunnel.interface.id` | 53 | 22 | 75 |
| `aruba-interface-tunnel:tunnel.interface.ip-version` | 49 | 22 | 71 |
| `aruba-interface-tunnel:tunnel.interface.mode` | 49 | 22 | 71 |
| `aruba-interface-tunnel:tunnel.interface.dst` | 48 | 22 | 70 |
| `aruba-interface-tunnel:tunnel.interface.vxlan.profile-name` | 40 | 16 | 56 |
| `aruba-interface-tunnel:tunnel.interface.vxlan.vni-list` | 40 | 16 | 56 |
| `aruba-interface-tunnel:tunnel.interface.src` | 9 | 6 | 15 |
| `aruba-interface-tunnel:tunnel.interface.ipv4-prefix` | 7 | 6 | 13 |
| `aruba-interface-tunnel:tunnel.interface.enabled` | 8 | 4 | 12 |
| `aruba-interface-tunnel:tunnel.interface.description` | 5 | 4 | 9 |
| `aruba-interface-tunnel:tunnel.interface.vrf-forwarding` | 5 | 2 | 7 |
| `aruba-interface-tunnel:tunnel.interface.mtu` | 5 | 1 | 6 |
| `aruba-interface-tunnel:tunnel.interface.l3-counters` | 2 | 0 | 2 |
| `aruba-interface-tunnel:tunnel.interface.gre.pim4-sparse.enable` | 1 | 0 | 1 |
| `aruba-interface-tunnel:tunnel.interface.ttl.value` | 0 | 1 | 1 |

### aruba-nae-script

- **Leaf Count:** 2
- **Big Cluster Customers:** 269
- **Small Cluster Customers:** 194
- **Total Customers Affected:** 463

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-nae-script:nae-scripts.nae-script.name` | 135 | 97 | 232 |
| `aruba-nae-script:nae-scripts.nae-script.script` | 134 | 97 | 231 |

### aruba-ipfix-flow-exporter

- **Leaf Count:** 10
- **Big Cluster Customers:** 180
- **Small Cluster Customers:** 195
- **Total Customers Affected:** 375

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.name` | 38 | 39 | 77 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.local-collector` | 24 | 25 | 49 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.collector-dest` | 25 | 24 | 49 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.description` | 21 | 21 | 42 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.vrf` | 14 | 20 | 34 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.ip` | 13 | 19 | 32 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.port` | 15 | 16 | 31 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.transport-protocol` | 15 | 16 | 31 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.upload-template-interval` | 13 | 14 | 27 |
| `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.hostname` | 2 | 1 | 3 |

### aruba-nexthop-group

- **Leaf Count:** 6
- **Big Cluster Customers:** 184
- **Small Cluster Customers:** 159
- **Total Customers Affected:** 343

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-nexthop-group:nexthop-groups.group.name` | 43 | 37 | 80 |
| `aruba-nexthop-group:nexthop-groups.group.nexthops.index` | 41 | 37 | 78 |
| `aruba-nexthop-group:nexthop-groups.group.nexthops.ip` | 41 | 37 | 78 |
| `aruba-nexthop-group:nexthop-groups.group.nexthops.type` | 41 | 37 | 78 |
| `aruba-nexthop-group:nexthop-groups.group.nexthops.default-host` | 14 | 8 | 22 |
| `aruba-nexthop-group:nexthop-groups.group.nexthops.null-interface` | 4 | 3 | 7 |

### aruba-copp

- **Leaf Count:** 4
- **Big Cluster Customers:** 208
- **Small Cluster Customers:** 118
- **Total Customers Affected:** 326

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-copp:copp.profile.name` | 60 | 34 | 94 |
| `aruba-copp:copp.profile.copp-policy.configured-copp-policy-entries.class` | 55 | 32 | 87 |
| `aruba-copp:copp.profile.copp-policy.configured-copp-policy-entries.priority` | 55 | 32 | 87 |
| `aruba-copp:copp.profile.copp-policy.applied` | 38 | 20 | 58 |

### aruba-traffic-insight

- **Leaf Count:** 11
- **Big Cluster Customers:** 154
- **Small Cluster Customers:** 150
- **Total Customers Affected:** 304

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-traffic-insight:traffic-insight.instance.name` | 25 | 23 | 48 |
| `aruba-traffic-insight:traffic-insight.instance.enable` | 24 | 23 | 47 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.monitor-name` | 23 | 23 | 46 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.monitor-name-type` | 23 | 23 | 46 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.type` | 23 | 23 | 46 |
| `aruba-traffic-insight:traffic-insight.instance.source` | 24 | 22 | 46 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.monitor-n-flows` | 6 | 6 | 12 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.group-by` | 4 | 5 | 9 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.parameter` | 1 | 1 | 2 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.application-id` | 1 | 0 | 1 |
| `aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.source-port` | 0 | 1 | 1 |

### aruba-interface-vni

- **Leaf Count:** 7
- **Big Cluster Customers:** 0
- **Small Cluster Customers:** 300
- **Total Customers Affected:** 300

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-vni:vxlan-vni.profile.name` | 0 | 51 | 51 |
| `aruba-interface-vni:vxlan-vni.profile.vni.id` | 0 | 51 | 51 |
| `aruba-interface-vni:vxlan-vni.profile.vni.vni-name` | 0 | 51 | 51 |
| `aruba-interface-vni:vxlan-vni.profile.vxlan-tunnel-profile` | 0 | 51 | 51 |
| `aruba-interface-vni:vxlan-vni.profile.vni.vlan` | 0 | 48 | 48 |
| `aruba-interface-vni:vxlan-vni.profile.vni.symmetric-routing` | 0 | 24 | 24 |
| `aruba-interface-vni:vxlan-vni.profile.vni.vrf` | 0 | 24 | 24 |

### aruba-ipfix-flow-monitor

- **Leaf Count:** 6
- **Big Cluster Customers:** 145
- **Small Cluster Customers:** 154
- **Total Customers Affected:** 299

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.name` | 36 | 40 | 76 |
| `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.record` | 35 | 40 | 75 |
| `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.exporter.exporter-name` | 35 | 40 | 75 |
| `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.cache-timeout-active` | 22 | 19 | 41 |
| `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.description` | 14 | 12 | 26 |
| `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.cache-timeout-inactive` | 3 | 3 | 6 |

### aruba-mgmd

- **Leaf Count:** 8
- **Big Cluster Customers:** 211
- **Small Cluster Customers:** 77
- **Total Customers Affected:** 288

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-mgmd:mgmd-global.profile.name` | 96 | 35 | 131 |
| `aruba-mgmd:mgmd-global.profile.igmp.filter-unknown-multicast` | 38 | 12 | 50 |
| `aruba-mgmd:mgmd-global.profile.igmp.fastlearn.eth-ports` | 34 | 12 | 46 |
| `aruba-mgmd:mgmd-global.profile.igmp.drop-unknown` | 26 | 6 | 32 |
| `aruba-mgmd:mgmd-global.profile.igmp.fastlearn.lag-ports` | 13 | 6 | 19 |
| `aruba-mgmd:mgmd-global.profile.delayed-refresh_enable` | 1 | 3 | 4 |
| `aruba-mgmd:mgmd-global.profile.delayed-refresh-interval` | 1 | 3 | 4 |
| `aruba-mgmd:mgmd-global.profile.mld.filter-unknown-multicast` | 2 | 0 | 2 |

### aruba-aaa-captive-portal

- **Leaf Count:** 5
- **Big Cluster Customers:** 170
- **Small Cluster Customers:** 106
- **Total Customers Affected:** 276

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-aaa-captive-portal:captive-portal.profile.external-cp-server-url` | 85 | 51 | 136 |
| `aruba-aaa-captive-portal:captive-portal.profile.name` | 85 | 51 | 136 |
| `aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-format` | 0 | 2 | 2 |
| `aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-ciphertext-value` | 0 | 1 | 1 |
| `aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-value` | 0 | 1 | 1 |

### aruba-rip

- **Leaf Count:** 43
- **Big Cluster Customers:** 143
- **Small Cluster Customers:** 133
- **Total Customers Affected:** 276

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-rip:rip.router.instance-tag` | 17 | 0 | 17 |
| `aruba-rip:rip.router.instance-tag-vrf-proto-type` | 17 | 0 | 17 |
| `aruba-rip:rip.router.proto-type` | 17 | 0 | 17 |
| `aruba-rip:rip.router.vrf` | 17 | 0 | 17 |
| `aruba-rip:rip.router.redistribute.redistribute-id` | 11 | 0 | 11 |
| `aruba-rip:rip.router.redistribute.redistribute-type` | 11 | 0 | 11 |
| `aruba-rip:rip.profile.name` | 0 | 11 | 11 |
| `aruba-rip:rip.profile.router.instance-tag` | 0 | 11 | 11 |
| `aruba-rip:rip.profile.router.instance-tag-vrf-proto-type` | 0 | 11 | 11 |
| `aruba-rip:rip.profile.router.proto-type` | 0 | 11 | 11 |
| `aruba-rip:rip.profile.router.vrf` | 0 | 11 | 11 |
| `aruba-rip:rip.router.svi-interfaces.address-family` | 9 | 0 | 9 |
| `aruba-rip:rip.router.svi-interfaces.ip-address` | 9 | 0 | 9 |
| `aruba-rip:rip.router.svi-interfaces.svi-id` | 9 | 0 | 9 |
| `aruba-rip:rip.router.svi-interfaces.svi-id-address-family` | 9 | 0 | 9 |
| `aruba-rip:rip.profile.router.redistribute.redistribute-id` | 0 | 8 | 8 |
| `aruba-rip:rip.profile.router.redistribute.redistribute-type` | 0 | 8 | 8 |
| `aruba-rip:rip.profile.description` | 0 | 8 | 8 |
| `aruba-rip:rip.profile.router.svi-interfaces.address-family` | 0 | 8 | 8 |
| `aruba-rip:rip.profile.router.svi-interfaces.ip-address` | 0 | 8 | 8 |
| `aruba-rip:rip.profile.router.svi-interfaces.svi-id` | 0 | 8 | 8 |
| `aruba-rip:rip.profile.router.svi-interfaces.svi-id-address-family` | 0 | 8 | 8 |
| `aruba-rip:rip.router.ether-interfaces.address-family` | 3 | 0 | 3 |
| `aruba-rip:rip.router.ether-interfaces.interface-name` | 3 | 0 | 3 |
| `aruba-rip:rip.router.ether-interfaces.interface-name-address-family` | 3 | 0 | 3 |
| `aruba-rip:rip.router.ether-interfaces.ip-address` | 3 | 0 | 3 |
| `aruba-rip:rip.profile.router.timers.garbage-collection` | 0 | 2 | 2 |
| `aruba-rip:rip.profile.router.timers.timeout` | 0 | 2 | 2 |
| `aruba-rip:rip.profile.router.timers.update` | 0 | 2 | 2 |
| `aruba-rip:rip.router.enable` | 2 | 0 | 2 |
| `aruba-rip:rip.profile.router.redistribute.ospf-id` | 0 | 2 | 2 |
| `aruba-rip:rip.router.redistribute.ospf-id` | 2 | 0 | 2 |
| `aruba-rip:rip.profile.router.loopback-interfaces.address-family` | 0 | 2 | 2 |
| `aruba-rip:rip.profile.router.loopback-interfaces.ip-address` | 0 | 2 | 2 |
| `aruba-rip:rip.profile.router.loopback-interfaces.loopback-id` | 0 | 2 | 2 |
| `aruba-rip:rip.profile.router.loopback-interfaces.loopback-id-address-family` | 0 | 2 | 2 |
| `aruba-rip:rip.profile.router.maximum-paths` | 0 | 1 | 1 |
| `aruba-rip:rip.profile.router.distance` | 0 | 1 | 1 |
| `aruba-rip:rip.profile.router.ether-interfaces.address-family` | 0 | 1 | 1 |
| `aruba-rip:rip.profile.router.ether-interfaces.interface-name` | 0 | 1 | 1 |
| `aruba-rip:rip.profile.router.ether-interfaces.interface-name-address-family` | 0 | 1 | 1 |
| `aruba-rip:rip.profile.router.ether-interfaces.ip-address` | 0 | 1 | 1 |
| `aruba-rip:rip.router.distance` | 1 | 0 | 1 |

### aruba-role-gpid

- **Leaf Count:** 2
- **Big Cluster Customers:** 196
- **Small Cluster Customers:** 68
- **Total Customers Affected:** 264

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-role-gpid:role-gpids.role-gpid.gpid` | 98 | 34 | 132 |
| `aruba-role-gpid:role-gpids.role-gpid.name` | 98 | 34 | 132 |

### aruba-ipsla

- **Leaf Count:** 20
- **Big Cluster Customers:** 167
- **Small Cluster Customers:** 82
- **Total Customers Affected:** 249

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ipsla:ipsla.profile.name` | 30 | 14 | 44 |
| `aruba-ipsla:ipsla.profile.source-sessions.source-name` | 30 | 14 | 44 |
| `aruba-ipsla:ipsla.profile.source-sessions.type` | 24 | 12 | 36 |
| `aruba-ipsla:ipsla.profile.source-sessions.destination-ipv4` | 22 | 12 | 34 |
| `aruba-ipsla:ipsla.profile.source-sessions.enable` | 18 | 11 | 29 |
| `aruba-ipsla:ipsla.profile.source-sessions.frequency` | 13 | 8 | 21 |
| `aruba-ipsla:ipsla.profile.source-sessions.source.ipv4-address` | 6 | 8 | 14 |
| `aruba-ipsla:ipsla.profile.source-sessions.source.interface-vlan` | 5 | 0 | 5 |
| `aruba-ipsla:ipsla.profile.source-sessions.payload-size` | 4 | 1 | 5 |
| `aruba-ipsla:ipsla.profile.source-sessions.vrf` | 3 | 0 | 3 |
| `aruba-ipsla:ipsla.profile.source-sessions.destination-hostname` | 3 | 0 | 3 |
| `aruba-ipsla:ipsla.profile.source-sessions.destination-port` | 2 | 1 | 3 |
| `aruba-ipsla:ipsla.profile.source-sessions.source.port` | 0 | 1 | 1 |
| `aruba-ipsla:ipsla.profile.source-sessions.source.interface-ethernet` | 1 | 0 | 1 |
| `aruba-ipsla:ipsla.profile.responder-sessions.responder-name` | 1 | 0 | 1 |
| `aruba-ipsla:ipsla.profile.responder-sessions.responder-port` | 1 | 0 | 1 |
| `aruba-ipsla:ipsla.profile.responder-sessions.responder-source.interface-vlan` | 1 | 0 | 1 |
| `aruba-ipsla:ipsla.profile.responder-sessions.responder-type` | 1 | 0 | 1 |
| `aruba-ipsla:ipsla.profile.source-sessions.http.request-type` | 1 | 0 | 1 |
| `aruba-ipsla:ipsla.profile.source-sessions.http.url` | 1 | 0 | 1 |

### aruba-interface-subinterface

- **Leaf Count:** 21
- **Big Cluster Customers:** 126
- **Small Cluster Customers:** 114
- **Total Customers Affected:** 240

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-subinterface:sub-interfaces.interface.id` | 21 | 16 | 37 |
| `aruba-interface-subinterface:sub-interfaces.interface.parent-name` | 21 | 16 | 37 |
| `aruba-interface-subinterface:sub-interfaces.interface.parent-name-id` | 21 | 16 | 37 |
| `aruba-interface-subinterface:sub-interfaces.interface.encapsulation-vlan-id` | 13 | 14 | 27 |
| `aruba-interface-subinterface:sub-interfaces.interface.ipv4.address` | 14 | 13 | 27 |
| `aruba-interface-subinterface:sub-interfaces.interface.description` | 14 | 7 | 21 |
| `aruba-interface-subinterface:sub-interfaces.interface.vrf-forwarding` | 9 | 11 | 20 |
| `aruba-interface-subinterface:sub-interfaces.interface.enable` | 6 | 3 | 9 |
| `aruba-interface-subinterface:sub-interfaces.interface.ip.mtu` | 2 | 1 | 3 |
| `aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.ip` | 1 | 2 | 3 |
| `aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.ip-vrf` | 1 | 2 | 3 |
| `aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.vrf` | 1 | 2 | 3 |
| `aruba-interface-subinterface:sub-interfaces.interface.pim-sparse.enable` | 0 | 2 | 2 |
| `aruba-interface-subinterface:sub-interfaces.interface.vrrp.vrrp-profile-apply` | 0 | 2 | 2 |
| `aruba-interface-subinterface:sub-interfaces.interface.ipv6.addresses.address` | 0 | 2 | 2 |
| `aruba-interface-subinterface:sub-interfaces.interface.ip.l3-counters` | 0 | 2 | 2 |
| `aruba-interface-subinterface:sub-interfaces.interface.ipv4.secondary-ip` | 1 | 0 | 1 |
| `aruba-interface-subinterface:sub-interfaces.interface.policy.ipv4-access-list-out` | 1 | 0 | 1 |
| `aruba-interface-subinterface:sub-interfaces.interface.igmp.enable` | 0 | 1 | 1 |
| `aruba-interface-subinterface:sub-interfaces.interface.arp.timeout` | 0 | 1 | 1 |
| `aruba-interface-subinterface:sub-interfaces.interface.policy.ipv4-access-list-in` | 0 | 1 | 1 |

### aruba-interface-vxlan-tunnel

- **Leaf Count:** 13
- **Big Cluster Customers:** 0
- **Small Cluster Customers:** 235
- **Total Customers Affected:** 235

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.name` | 0 | 53 | 53 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.enable` | 0 | 51 | 51 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.src-ipv4` | 0 | 51 | 51 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.dst` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.id` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.ip-version` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.vni-profile-name` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.bridging-mode` | 0 | 7 | 7 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.enable-counters` | 0 | 4 | 4 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.description` | 0 | 2 | 2 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.loop-protect-vlans` | 0 | 1 | 1 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.mac-notify-traps` | 0 | 1 | 1 |
| `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.loop-protect` | 0 | 1 | 1 |

### aruba-mirror-endpoint

- **Leaf Count:** 10
- **Big Cluster Customers:** 154
- **Small Cluster Customers:** 77
- **Total Customers Affected:** 231

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.ep-name` | 36 | 15 | 51 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.name` | 36 | 15 | 51 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.destination-ip` | 16 | 9 | 25 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.source-ip` | 16 | 9 | 25 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.tid` | 16 | 9 | 25 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.destinations.eth-interfaces` | 16 | 9 | 25 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.enable` | 12 | 8 | 20 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.comment` | 3 | 1 | 4 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.encap` | 2 | 2 | 4 |
| `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.vrf` | 1 | 0 | 1 |

### aruba-keychain

- **Leaf Count:** 12
- **Big Cluster Customers:** 127
- **Small Cluster Customers:** 89
- **Total Customers Affected:** 216

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-keychain:keychains.keychain.name` | 30 | 17 | 47 |
| `aruba-keychain:keychains.keychain.keys.key-id` | 24 | 17 | 41 |
| `aruba-keychain:keychains.keychain.keys.auth-key-info.type` | 23 | 16 | 39 |
| `aruba-keychain:keychains.keychain.keys.auth-key-info.auth-key-ciphertext` | 22 | 16 | 38 |
| `aruba-keychain:keychains.keychain.keys.crypto-algorithm` | 11 | 7 | 18 |
| `aruba-keychain:keychains.keychain.keys.accept-start` | 5 | 5 | 10 |
| `aruba-keychain:keychains.keychain.keys.send-start` | 5 | 5 | 10 |
| `aruba-keychain:keychains.keychain.keys.accept-end` | 3 | 2 | 5 |
| `aruba-keychain:keychains.keychain.keys.send-end` | 3 | 2 | 5 |
| `aruba-keychain:keychains.keychain.keys.auth-key-info.auth-key` | 1 | 0 | 1 |
| `aruba-keychain:keychains.keychain.keys.recv-id` | 0 | 1 | 1 |
| `aruba-keychain:keychains.keychain.keys.send-id` | 0 | 1 | 1 |

### aruba-dhcp-snooping-interface

- **Leaf Count:** 4
- **Big Cluster Customers:** 157
- **Small Cluster Customers:** 32
- **Total Customers Affected:** 189

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.name` | 77 | 15 | 92 |
| `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv4-snooping.trust` | 75 | 15 | 90 |
| `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv4-snooping.max-bindings` | 3 | 1 | 4 |
| `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv6-snooping.trust` | 2 | 1 | 3 |

### aruba-nae-lite

- **Leaf Count:** 26
- **Big Cluster Customers:** 105
- **Small Cluster Customers:** 61
- **Total Customers Affected:** 166

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-nae-lite:nae-lite.profile.name` | 32 | 10 | 42 |
| `aruba-nae-lite:nae-lite.profile.description` | 24 | 8 | 32 |
| `aruba-nae-lite:nae-lite.profile.agent-type` | 5 | 4 | 9 |
| `aruba-nae-lite:nae-lite.profile.conditions.condtype` | 5 | 4 | 9 |
| `aruba-nae-lite:nae-lite.profile.conditions.name-condition` | 5 | 4 | 9 |
| `aruba-nae-lite:nae-lite.profile.conditions.set-watch` | 5 | 3 | 8 |
| `aruba-nae-lite:nae-lite.profile.watches.event-id` | 5 | 3 | 8 |
| `aruba-nae-lite:nae-lite.profile.watches.watch-name` | 5 | 3 | 8 |
| `aruba-nae-lite:nae-lite.profile.conditions.cli` | 3 | 4 | 7 |
| `aruba-nae-lite:nae-lite.profile.ready` | 4 | 2 | 6 |
| `aruba-nae-lite:nae-lite.profile.conditions.status` | 3 | 1 | 4 |
| `aruba-nae-lite:nae-lite.profile.conditions.syslog` | 3 | 1 | 4 |
| `aruba-nae-lite:nae-lite.profile.conditions.include` | 1 | 3 | 4 |
| `aruba-nae-lite:nae-lite.profile.conditions.include-regex` | 1 | 3 | 4 |
| `aruba-nae-lite:nae-lite.profile.conditions.count` | 1 | 0 | 1 |
| `aruba-nae-lite:nae-lite.profile.conditions.facility` | 1 | 0 | 1 |
| `aruba-nae-lite:nae-lite.profile.conditions.operand` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.conditions.operator` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.conditions.set-monitor` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.conditions.severity` | 1 | 0 | 1 |
| `aruba-nae-lite:nae-lite.profile.disable` | 1 | 0 | 1 |
| `aruba-nae-lite:nae-lite.profile.monitors.dur-unit` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.monitors.duration` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.monitors.group-by` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.monitors.monitor-name` | 0 | 1 | 1 |
| `aruba-nae-lite:nae-lite.profile.monitors.vsf-member` | 0 | 1 | 1 |

### aruba-ip-lockdown

- **Leaf Count:** 2
- **Big Cluster Customers:** 86
- **Small Cluster Customers:** 56
- **Total Customers Affected:** 142

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ip-lockdown:ip-source-lockdown.profile.ip-source-lockdown-resource-extended` | 43 | 28 | 71 |
| `aruba-ip-lockdown:ip-source-lockdown.profile.name` | 43 | 28 | 71 |

### aruba-udp-broadcast-forwarder

- **Leaf Count:** 2
- **Big Cluster Customers:** 102
- **Small Cluster Customers:** 18
- **Total Customers Affected:** 120

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-udp-broadcast-forwarder:udp-broadcast-forwarders.profile.enable` | 51 | 9 | 60 |
| `aruba-udp-broadcast-forwarder:udp-broadcast-forwarders.profile.name` | 51 | 9 | 60 |

### aruba-firmware-management

- **Leaf Count:** 3
- **Big Cluster Customers:** 60
- **Small Cluster Customers:** 56
- **Total Customers Affected:** 116

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-firmware-management:device-firmware.site-distribution` | 53 | 50 | 103 |
| `aruba-firmware-management:device-firmware.issu.software-update-rollback-timer-enable` | 5 | 4 | 9 |
| `aruba-firmware-management:device-firmware.issu.software-update-rollback-timer` | 2 | 2 | 4 |

### aruba-lacp

- **Leaf Count:** 2
- **Big Cluster Customers:** 90
- **Small Cluster Customers:** 24
- **Total Customers Affected:** 114

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-lacp:lacp.hash` | 67 | 5 | 72 |
| `aruba-lacp:lacp.system-priority` | 23 | 19 | 42 |

### aruba-mka

- **Leaf Count:** 8
- **Big Cluster Customers:** 75
- **Small Cluster Customers:** 31
- **Total Customers Affected:** 106

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-mka:mka.policy.name` | 17 | 6 | 23 |
| `aruba-mka:mka.policy.cak-info.ckn` | 15 | 6 | 21 |
| `aruba-mka:mka.policy.cak-info.key-type` | 15 | 6 | 21 |
| `aruba-mka:mka.policy.cak-info.cak-ciphertext` | 14 | 6 | 20 |
| `aruba-mka:mka.policy.key-server-priority` | 12 | 5 | 17 |
| `aruba-mka:mka.policy.eapol-destination-mac` | 1 | 1 | 2 |
| `aruba-mka:mka.policy.cak-info.cak` | 1 | 0 | 1 |
| `aruba-mka:mka.policy.eapol-dot1q-tagged` | 0 | 1 | 1 |

### aruba-erps

- **Leaf Count:** 21
- **Big Cluster Customers:** 85
- **Small Cluster Customers:** 20
- **Total Customers Affected:** 105

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-erps:erps.profile.name` | 7 | 2 | 9 |
| `aruba-erps:erps.profile.ring.instance.instance-id` | 7 | 2 | 9 |
| `aruba-erps:erps.profile.ring.instance.protected-vlans` | 7 | 2 | 9 |
| `aruba-erps:erps.profile.ring.ring-id` | 7 | 2 | 9 |
| `aruba-erps:erps.profile.ring.instance.control-vlan` | 7 | 2 | 9 |
| `aruba-erps:erps.profile.ring.instance.protection-switching-enable` | 7 | 2 | 9 |
| `aruba-erps:erps.profile.ring.instance.role` | 7 | 1 | 8 |
| `aruba-erps:erps.profile.ring.instance.rpl` | 7 | 1 | 8 |
| `aruba-erps:erps.profile.ring.port0-eth-interface` | 6 | 0 | 6 |
| `aruba-erps:erps.profile.ring.port1-eth-interface` | 6 | 0 | 6 |
| `aruba-erps:erps.profile.ring.description` | 3 | 1 | 4 |
| `aruba-erps:erps.profile.ring.instance.instance-description` | 3 | 1 | 4 |
| `aruba-erps:erps.profile.ring.port1-portchannel` | 2 | 2 | 4 |
| `aruba-erps:erps.profile.ring.port0-portchannel` | 1 | 2 | 3 |
| `aruba-erps:erps.profile.ring.wtr-interval` | 2 | 0 | 2 |
| `aruba-erps:erps.profile.ring.meg-level` | 1 | 0 | 1 |
| `aruba-erps:erps.profile.ring.guard-interval` | 1 | 0 | 1 |
| `aruba-erps:erps.profile.ring.hold-off-interval` | 1 | 0 | 1 |
| `aruba-erps:erps.profile.ring.transmission-interval` | 1 | 0 | 1 |
| `aruba-erps:erps.profile.ring.sub-ring` | 1 | 0 | 1 |
| `aruba-erps:erps.profile.ring.parent-ring` | 1 | 0 | 1 |

### aruba-external-storage

- **Leaf Count:** 10
- **Big Cluster Customers:** 71
- **Small Cluster Customers:** 33
- **Total Customers Affected:** 104

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-external-storage:external-storage.profile.name` | 11 | 6 | 17 |
| `aruba-external-storage:external-storage.profile.store.store-name` | 11 | 6 | 17 |
| `aruba-external-storage:external-storage.profile.store.type` | 9 | 3 | 12 |
| `aruba-external-storage:external-storage.profile.store.address` | 8 | 3 | 11 |
| `aruba-external-storage:external-storage.profile.store.directory` | 8 | 3 | 11 |
| `aruba-external-storage:external-storage.profile.store.enable` | 8 | 3 | 11 |
| `aruba-external-storage:external-storage.profile.store.password-ciphertext` | 5 | 3 | 8 |
| `aruba-external-storage:external-storage.profile.store.password-type` | 5 | 3 | 8 |
| `aruba-external-storage:external-storage.profile.store.username` | 5 | 3 | 8 |
| `aruba-external-storage:external-storage.profile.store.vrf` | 1 | 0 | 1 |

### aruba-psm

- **Leaf Count:** 3
- **Big Cluster Customers:** 64
- **Small Cluster Customers:** 33
- **Total Customers Affected:** 97

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-psm:psm.psm-instance.name` | 27 | 11 | 38 |
| `aruba-psm:psm.psm-instance.psm-ips` | 27 | 11 | 38 |
| `aruba-psm:psm.psm-instance.vrf` | 10 | 11 | 21 |

### aruba-ptp

- **Leaf Count:** 8
- **Big Cluster Customers:** 65
- **Small Cluster Customers:** 32
- **Total Customers Affected:** 97

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ptp:ptp.profile.name` | 11 | 5 | 16 |
| `aruba-ptp:ptp.profile.protocol-profiles.profile` | 11 | 5 | 16 |
| `aruba-ptp:ptp.profile.protocol-profiles.clock-step` | 9 | 4 | 13 |
| `aruba-ptp:ptp.profile.protocol-profiles.delay-mechanism` | 9 | 4 | 13 |
| `aruba-ptp:ptp.profile.protocol-profiles.mode` | 9 | 4 | 13 |
| `aruba-ptp:ptp.profile.protocol-profiles.transport` | 8 | 5 | 13 |
| `aruba-ptp:ptp.profile.protocol-profiles.enable` | 8 | 4 | 12 |
| `aruba-ptp:ptp.profile.protocol-profiles.domain` | 0 | 1 | 1 |

### aruba-static-mac

- **Leaf Count:** 5
- **Big Cluster Customers:** 60
- **Small Cluster Customers:** 35
- **Total Customers Affected:** 95

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-static-mac:static-macs.profile.name` | 12 | 7 | 19 |
| `aruba-static-mac:static-macs.profile.static-mac.destination-port.l2-destination` | 12 | 7 | 19 |
| `aruba-static-mac:static-macs.profile.static-mac.mac` | 12 | 7 | 19 |
| `aruba-static-mac:static-macs.profile.static-mac.mac-vlan` | 12 | 7 | 19 |
| `aruba-static-mac:static-macs.profile.static-mac.vlan` | 12 | 7 | 19 |

### aruba-named-vlan

- **Leaf Count:** 2
- **Big Cluster Customers:** 56
- **Small Cluster Customers:** 19
- **Total Customers Affected:** 75

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-named-vlan:named-vlan.profile.name` | 39 | 18 | 57 |
| `aruba-named-vlan:named-vlan.profile.vlan.vlan-id-ranges` | 17 | 1 | 18 |

### aruba-nd-snooping

- **Leaf Count:** 5
- **Big Cluster Customers:** 47
- **Small Cluster Customers:** 27
- **Total Customers Affected:** 74

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-nd-snooping:nd-snooping.profile.name` | 21 | 13 | 34 |
| `aruba-nd-snooping:nd-snooping.profile.enable` | 20 | 13 | 33 |
| `aruba-nd-snooping:nd-snooping.profile.ra-guard-policy.ra-guard-name` | 4 | 0 | 4 |
| `aruba-nd-snooping:nd-snooping.profile.ra-guard-policy.match-list.access-list` | 2 | 0 | 2 |
| `aruba-nd-snooping:nd-snooping.profile.mac-check` | 0 | 1 | 1 |

### aruba-mvrp

- **Leaf Count:** 2
- **Big Cluster Customers:** 68
- **Small Cluster Customers:** 2
- **Total Customers Affected:** 70

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-mvrp:mvrp.profile.enable` | 34 | 1 | 35 |
| `aruba-mvrp:mvrp.profile.name` | 34 | 1 | 35 |

### aruba-mac-lockout

- **Leaf Count:** 3
- **Big Cluster Customers:** 47
- **Small Cluster Customers:** 16
- **Total Customers Affected:** 63

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-mac-lockout:mac-lockout.profile.name` | 22 | 8 | 30 |
| `aruba-mac-lockout:mac-lockout.profile.address.mac` | 20 | 6 | 26 |
| `aruba-mac-lockout:mac-lockout.profile.log` | 5 | 2 | 7 |

### aruba-ufd

- **Leaf Count:** 9
- **Big Cluster Customers:** 8
- **Small Cluster Customers:** 54
- **Total Customers Affected:** 62

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ufd:ufd.profile.enable` | 4 | 9 | 13 |
| `aruba-ufd:ufd.profile.name` | 4 | 9 | 13 |
| `aruba-ufd:ufd.profile.sessions.id` | 0 | 9 | 9 |
| `aruba-ufd:ufd.profile.sessions.links-to-disable.ethernet-ports` | 0 | 7 | 7 |
| `aruba-ufd:ufd.profile.sessions.links-to-monitor.ethernet-ports` | 0 | 7 | 7 |
| `aruba-ufd:ufd.profile.sessions.delay-up` | 0 | 6 | 6 |
| `aruba-ufd:ufd.profile.sessions.delay-down` | 0 | 4 | 4 |
| `aruba-ufd:ufd.profile.sessions.links-to-monitor.lag-ports` | 0 | 2 | 2 |
| `aruba-ufd:ufd.profile.sessions.links-to-disable.lag-ports` | 0 | 1 | 1 |

### aruba-dhcp-client

- **Leaf Count:** 3
- **Big Cluster Customers:** 34
- **Small Cluster Customers:** 22
- **Total Customers Affected:** 56

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-dhcp-client:dhcp-client.profile.name` | 17 | 11 | 28 |
| `aruba-dhcp-client:dhcp-client.profile.ip.enable-hostname` | 12 | 11 | 23 |
| `aruba-dhcp-client:dhcp-client.profile.ip.enable-broadcast-flag` | 5 | 0 | 5 |

### aruba-macsec

- **Leaf Count:** 8
- **Big Cluster Customers:** 37
- **Small Cluster Customers:** 16
- **Total Customers Affected:** 53

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-macsec:macsec.policy.name` | 17 | 6 | 23 |
| `aruba-macsec:macsec.policy.replay-window` | 13 | 4 | 17 |
| `aruba-macsec:macsec.policy.cipher-suites` | 5 | 2 | 7 |
| `aruba-macsec:macsec.policy.confidentiality-offset` | 1 | 1 | 2 |
| `aruba-macsec:macsec.policy.bypass-list` | 0 | 1 | 1 |
| `aruba-macsec:macsec.policy.clear-tag-mode` | 0 | 1 | 1 |
| `aruba-macsec:macsec.policy.replay-protect-enable` | 1 | 0 | 1 |
| `aruba-macsec:macsec.policy.include-sci-enable` | 0 | 1 | 1 |

### aruba-qos-threshold-profile

- **Leaf Count:** 15
- **Big Cluster Customers:** 23
- **Small Cluster Customers:** 28
- **Total Customers Affected:** 51

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos-threshold-profile:qos-thresholds.profile.thresh-profile-name` | 5 | 8 | 13 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.queue-num` | 4 | 6 | 10 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn-entry.thresh-units` | 3 | 0 | 3 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn-entry.threshold` | 3 | 0 | 3 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.color` | 0 | 3 | 3 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.max-threshold-percent` | 0 | 3 | 3 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.min-threshold-percent` | 0 | 3 | 3 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.threshold-percent` | 0 | 2 | 2 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.color` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.max-threshold` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.min-threshold` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.thresh-units` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.max-threshold-kbytes` | 0 | 1 | 1 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.min-threshold-kbytes` | 0 | 1 | 1 |
| `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.threshold-kbytes` | 0 | 1 | 1 |

### aruba-track-object

- **Leaf Count:** 4
- **Big Cluster Customers:** 16
- **Small Cluster Customers:** 34
- **Total Customers Affected:** 50

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-track-object:tracking-object.vrrp.identifier` | 10 | 20 | 30 |
| `aruba-track-object:tracking-object.vrrp.interface.interface-type` | 3 | 7 | 10 |
| `aruba-track-object:tracking-object.vrrp.interface.svi` | 1 | 6 | 7 |
| `aruba-track-object:tracking-object.vrrp.interface.ethernet` | 2 | 1 | 3 |

### aruba-smartlink

- **Leaf Count:** 11
- **Big Cluster Customers:** 44
- **Small Cluster Customers:** 5
- **Total Customers Affected:** 49

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-smartlink:smartlink.profile.name` | 8 | 1 | 9 |
| `aruba-smartlink:smartlink.profile.group.group-id` | 7 | 1 | 8 |
| `aruba-smartlink:smartlink.profile.group.preemption-enable` | 5 | 0 | 5 |
| `aruba-smartlink:smartlink.profile.group.protected-vlans` | 5 | 0 | 5 |
| `aruba-smartlink:smartlink.profile.group.secondary-ethernet-port` | 5 | 0 | 5 |
| `aruba-smartlink:smartlink.profile.group.primary-ethernet-port` | 5 | 0 | 5 |
| `aruba-smartlink:smartlink.profile.group.preemption-delay` | 4 | 0 | 4 |
| `aruba-smartlink:smartlink.profile.group.control-vlan` | 3 | 0 | 3 |
| `aruba-smartlink:smartlink.profile.recv-control-vlans` | 2 | 0 | 2 |
| `aruba-smartlink:smartlink.profile.group.description` | 0 | 2 | 2 |
| `aruba-smartlink:smartlink.profile.group.primary-portchannel-port` | 0 | 1 | 1 |

### aruba-qos-cos

- **Leaf Count:** 5
- **Big Cluster Customers:** 48
- **Small Cluster Customers:** 0
- **Total Customers Affected:** 48

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos-cos:qos-cos.profile.cos-map.color` | 11 | 0 | 11 |
| `aruba-qos-cos:qos-cos.profile.cos-map.cos` | 11 | 0 | 11 |
| `aruba-qos-cos:qos-cos.profile.cos-map.local-priority` | 11 | 0 | 11 |
| `aruba-qos-cos:qos-cos.profile.name` | 11 | 0 | 11 |
| `aruba-qos-cos:qos-cos.profile.cos-map.name` | 4 | 0 | 4 |

### aruba-ip-binding

- **Leaf Count:** 7
- **Big Cluster Customers:** 21
- **Small Cluster Customers:** 21
- **Total Customers Affected:** 42

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ip-binding:source-ip-bindings.static-entry.client-address` | 3 | 3 | 6 |
| `aruba-ip-binding:source-ip-bindings.static-entry.interface-ethernet` | 3 | 3 | 6 |
| `aruba-ip-binding:source-ip-bindings.static-entry.interface-types` | 3 | 3 | 6 |
| `aruba-ip-binding:source-ip-bindings.static-entry.ip-version` | 3 | 3 | 6 |
| `aruba-ip-binding:source-ip-bindings.static-entry.ip-version-vlan-client-address` | 3 | 3 | 6 |
| `aruba-ip-binding:source-ip-bindings.static-entry.mac` | 3 | 3 | 6 |
| `aruba-ip-binding:source-ip-bindings.static-entry.vlan` | 3 | 3 | 6 |

### aruba-feature-pack

- **Leaf Count:** 7
- **Big Cluster Customers:** 13
- **Small Cluster Customers:** 27
- **Total Customers Affected:** 40

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-feature-pack:management-server.profile.credentials.password-ciphertext` | 2 | 4 | 6 |
| `aruba-feature-pack:management-server.profile.credentials.user` | 2 | 4 | 6 |
| `aruba-feature-pack:management-server.profile.location` | 2 | 4 | 6 |
| `aruba-feature-pack:management-server.profile.name` | 2 | 4 | 6 |
| `aruba-feature-pack:management-server.profile.pool` | 2 | 4 | 6 |
| `aruba-feature-pack:management-server.profile.block` | 1 | 4 | 5 |
| `aruba-feature-pack:management-server.profile.vrf` | 2 | 3 | 5 |

### aruba-l3-route

- **Leaf Count:** 3
- **Big Cluster Customers:** 31
- **Small Cluster Customers:** 6
- **Total Customers Affected:** 37

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-l3-route:l3-route.profile.name` | 15 | 3 | 18 |
| `aruba-l3-route:l3-route.profile.route-redistribute` | 11 | 2 | 13 |
| `aruba-l3-route:l3-route.profile.graceful-restart` | 5 | 1 | 6 |

### aruba-nd-snooping-interface

- **Leaf Count:** 4
- **Big Cluster Customers:** 21
- **Small Cluster Customers:** 10
- **Total Customers Affected:** 31

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-nd-snooping-interface:nd-snooping-interface.profile.name` | 10 | 5 | 15 |
| `aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.trust` | 9 | 5 | 14 |
| `aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.ra-guard-policy` | 1 | 0 | 1 |
| `aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.max-bindings` | 1 | 0 | 1 |

### aruba-config-checkpoint

- **Leaf Count:** 3
- **Big Cluster Customers:** 25
- **Small Cluster Customers:** 6
- **Total Customers Affected:** 31

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-config-checkpoint:config-checkpoint.profile.name` | 12 | 3 | 15 |
| `aruba-config-checkpoint:config-checkpoint.profile.post-checkpoint-delay` | 10 | 1 | 11 |
| `aruba-config-checkpoint:config-checkpoint.profile.post-checkpoint` | 3 | 2 | 5 |

### aruba-dynamic-arp-inspection-interface

- **Leaf Count:** 2
- **Big Cluster Customers:** 18
- **Small Cluster Customers:** 6
- **Total Customers Affected:** 24

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-dynamic-arp-inspection-interface:dynamic-arp-inspection-interface.profile.dynamic-arp-inspection.trust` | 9 | 3 | 12 |
| `aruba-dynamic-arp-inspection-interface:dynamic-arp-inspection-interface.profile.name` | 9 | 3 | 12 |

### aruba-container

- **Leaf Count:** 13
- **Big Cluster Customers:** 12
- **Small Cluster Customers:** 10
- **Total Customers Affected:** 22

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-container:containers.instance.name` | 2 | 4 | 6 |
| `aruba-container:containers.instance.image-location-url` | 2 | 1 | 3 |
| `aruba-container:containers.instance.image-location-vrf` | 2 | 1 | 3 |
| `aruba-container:containers.instance.allow-unsigned-image` | 0 | 1 | 1 |
| `aruba-container:containers.instance.enable` | 0 | 1 | 1 |
| `aruba-container:containers.instance.encrypted-environment-variables.encrypted-env-type` | 1 | 0 | 1 |
| `aruba-container:containers.instance.encrypted-environment-variables.value-ciphertext` | 1 | 0 | 1 |
| `aruba-container:containers.instance.encrypted-environment-variables.variable` | 1 | 0 | 1 |
| `aruba-container:containers.instance.environment-variables.value` | 0 | 1 | 1 |
| `aruba-container:containers.instance.environment-variables.variable` | 0 | 1 | 1 |
| `aruba-container:containers.instance.runtime-constraints.cpu` | 1 | 0 | 1 |
| `aruba-container:containers.instance.runtime-constraints.memory` | 1 | 0 | 1 |
| `aruba-container:containers.instance.vrfs` | 1 | 0 | 1 |

### aruba-rmon-alarm

- **Leaf Count:** 6
- **Big Cluster Customers:** 16
- **Small Cluster Customers:** 6
- **Total Customers Affected:** 22

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-rmon-alarm:rmon-alarms.profile.name` | 3 | 1 | 4 |
| `aruba-rmon-alarm:rmon-alarms.profile.rmon.falling-threshold` | 3 | 1 | 4 |
| `aruba-rmon-alarm:rmon-alarms.profile.rmon.index` | 3 | 1 | 4 |
| `aruba-rmon-alarm:rmon-alarms.profile.rmon.rising-threshold` | 3 | 1 | 4 |
| `aruba-rmon-alarm:rmon-alarms.profile.rmon.snmp-oid` | 3 | 1 | 4 |
| `aruba-rmon-alarm:rmon-alarms.profile.rmon.interval` | 1 | 1 | 2 |

### aruba-countermon

- **Leaf Count:** 2
- **Big Cluster Customers:** 4
- **Small Cluster Customers:** 14
- **Total Customers Affected:** 18

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-countermon:countermon.profile.enable-polling` | 2 | 7 | 9 |
| `aruba-countermon:countermon.profile.name` | 2 | 7 | 9 |

### aruba-dsm

- **Leaf Count:** 4
- **Big Cluster Customers:** 7
- **Small Cluster Customers:** 6
- **Total Customers Affected:** 13

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-dsm:dsm.dsm-instance.name` | 3 | 3 | 6 |
| `aruba-dsm:dsm.dsm-instance.ipfix` | 1 | 2 | 3 |
| `aruba-dsm:dsm.dsm-instance.workload-migration` | 2 | 1 | 3 |
| `aruba-dsm:dsm.dsm-instance.uplink-to-uplink` | 1 | 0 | 1 |

### aruba-advanced-intelligent-forwarding

- **Leaf Count:** 4
- **Big Cluster Customers:** 12
- **Small Cluster Customers:** 1
- **Total Customers Affected:** 13

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-host-route-ipv4` | 5 | 0 | 5 |
| `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.name` | 5 | 0 | 5 |
| `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-exclude-nexthop-ipv4` | 2 | 0 | 2 |
| `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-ageout-time` | 0 | 1 | 1 |

### aruba-sysmon

- **Leaf Count:** 3
- **Big Cluster Customers:** 3
- **Small Cluster Customers:** 9
- **Total Customers Affected:** 12

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-sysmon:sysmon.profile.name` | 1 | 3 | 4 |
| `aruba-sysmon:sysmon.profile.poll-interval` | 1 | 3 | 4 |
| `aruba-sysmon:sysmon.profile.polling` | 1 | 3 | 4 |

### aruba-qos-pool

- **Leaf Count:** 6
- **Big Cluster Customers:** 12
- **Small Cluster Customers:** 0
- **Total Customers Affected:** 12

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-qos-pool:qos-pools.profile.name` | 2 | 0 | 2 |
| `aruba-qos-pool:qos-pools.profile.pool.headroom-size` | 2 | 0 | 2 |
| `aruba-qos-pool:qos-pools.profile.pool.index` | 2 | 0 | 2 |
| `aruba-qos-pool:qos-pools.profile.pool.priority` | 2 | 0 | 2 |
| `aruba-qos-pool:qos-pools.profile.pool.size` | 2 | 0 | 2 |
| `aruba-qos-pool:qos-pools.profile.pool.type` | 2 | 0 | 2 |

### aruba-container-network

- **Leaf Count:** 6
- **Big Cluster Customers:** 4
- **Small Cluster Customers:** 5
- **Total Customers Affected:** 9

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-container-network:container-networks.profile.name` | 1 | 1 | 2 |
| `aruba-container-network:container-networks.profile.name-vrf` | 1 | 1 | 2 |
| `aruba-container-network:container-networks.profile.vrf` | 1 | 1 | 2 |
| `aruba-container-network:container-networks.profile.port-mapping.tcp.container-port` | 0 | 1 | 1 |
| `aruba-container-network:container-networks.profile.port-mapping.tcp.host-port` | 0 | 1 | 1 |
| `aruba-container-network:container-networks.profile.preferred` | 1 | 0 | 1 |

### aruba-ip-routing

- **Leaf Count:** 5
- **Big Cluster Customers:** 5
- **Small Cluster Customers:** 3
- **Total Customers Affected:** 8

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ip-routing:ip-routing.profile.name` | 2 | 1 | 3 |
| `aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-port` | 1 | 1 | 2 |
| `aruba-ip-routing:ip-routing.profile.ip-prefix-priority-params.ip-prefix-priority` | 1 | 0 | 1 |
| `aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-ip` | 0 | 1 | 1 |
| `aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-dst-port` | 1 | 0 | 1 |

### aruba-ip-lockdown-interface

- **Leaf Count:** 3
- **Big Cluster Customers:** 0
- **Small Cluster Customers:** 7
- **Total Customers Affected:** 7

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.ip-source-lockdown.ipv4` | 0 | 3 | 3 |
| `aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.name` | 0 | 3 | 3 |
| `aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.ip-source-lockdown.ipv6` | 0 | 1 | 1 |

### aruba-multicast

- **Leaf Count:** 4
- **Big Cluster Customers:** 4
- **Small Cluster Customers:** 2
- **Total Customers Affected:** 6

| Leaf Name | Big Cluster Count | Small Cluster Count | Total |
|-----------|-------------------|---------------------|-------|
| `aruba-multicast:multicast-global.profile.name` | 2 | 1 | 3 |
| `aruba-multicast:multicast-global.profile.l3vni-source-ipv4` | 0 | 1 | 1 |
| `aruba-multicast:multicast-global.profile.multi-fabric-border-ipv4` | 1 | 0 | 1 |
| `aruba-multicast:multicast-global.profile.multipath-hash-ipv4` | 1 | 0 | 1 |

## Complete Unreferenced Leaf Table

| YANG Module | Leaf Name | Big Cluster Count | Small Cluster Count | Total Customers |
|-------------|-----------|-------------------|---------------------|----------------|
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.name` | 12284 | 4723 | 17007 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.enable` | 10512 | 4716 | 15228 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.interface-mode` | 10276 | 4673 | 14949 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.access-vlan` | 9950 | 4352 | 14302 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.native-vlan` | 8663 | 3848 | 12511 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.description` | 6990 | 3231 | 10221 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.trunk-vlan-ranges` | 5998 | 3089 | 9087 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.name` | 5701 | 3022 | 8723 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.id` | 5675 | 3022 | 8697 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.sku` | 5671 | 3022 | 8693 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.platform` | 5671 | 3022 | 8693 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.routing` | 5652 | 3035 | 8687 |
| `aruba-vsf-template` | `aruba-vsf-template:vsf-templates.template.name` | 5558 | 2963 | 8521 |
| `aruba-vsf-template` | `aruba-vsf-template:vsf-templates.template.members.id` | 5501 | 2944 | 8445 |
| `aruba-vsf-template` | `aruba-vsf-template:vsf-templates.template.members.sku` | 5501 | 2944 | 8445 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.trunk-vlan-all` | 6163 | 2277 | 8440 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.name` | 4237 | 2130 | 6367 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.enable` | 4223 | 2126 | 6349 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.switchport.interface-mode` | 4210 | 2122 | 6332 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.port-list` | 4052 | 2059 | 6111 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.switchport.native-vlan` | 4067 | 2031 | 6098 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.portchannel-lag` | 4041 | 2028 | 6069 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.lacp.mode` | 3882 | 1965 | 5847 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.trunk-type` | 3881 | 1966 | 5847 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.routing` | 3413 | 1815 | 5228 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.description` | 3508 | 1691 | 5199 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.links.link1.interfaces` | 3227 | 1643 | 4870 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.name` | 4078 | 663 | 4741 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.name` | 4063 | 646 | 4709 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.links.link2.interfaces` | 3006 | 1505 | 4511 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.switchport.trunk-vlan-all` | 3006 | 1441 | 4447 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.secondary-member` | 2641 | 1374 | 4015 |
| `aruba-vsf-template` | `aruba-vsf-template:vsf-templates.template.secondary-member` | 2641 | 1374 | 4015 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.enable` | 2865 | 1080 | 3945 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.switchport.trunk-vlan-ranges` | 2371 | 1263 | 3634 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.client-ip-tracker-enable` | 2168 | 1190 | 3358 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.admin-edge-port` | 2299 | 984 | 3283 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.bpdu-guard` | 2112 | 841 | 2953 |
| `aruba-named-condition` | `aruba-named-condition:named-conditions.named-condition.condition-rule.position` | 2372 | 353 | 2725 |
| `aruba-named-condition` | `aruba-named-condition:named-conditions.named-condition.name` | 2372 | 353 | 2725 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.enable` | 2365 | 41 | 2406 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.enable` | 2365 | 39 | 2404 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mtu` | 1418 | 680 | 2098 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.enable` | 1516 | 560 | 2076 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.enable` | 2000 | 76 | 2076 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.enable` | 1506 | 563 | 2069 |
| `aruba-loop-protect` | `aruba-loop-protect:loop-protect.profile.name` | 1622 | 369 | 1991 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.speed-duplex` | 1356 | 624 | 1980 |
| `aruba-switch-profiles` | `aruba-switch-profiles:switch-profiles.profile.name` | 1161 | 705 | 1866 |
| `aruba-switch-profiles` | `aruba-switch-profiles:switch-profiles.profile.selected` | 1161 | 705 | 1866 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.dscp-map.dscp` | 1839 | 0 | 1839 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.name` | 1839 | 0 | 1839 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.client-limit` | 1349 | 464 | 1813 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4.address` | 1116 | 588 | 1704 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.dscp-map.local-priority` | 1661 | 0 | 1661 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.switchport.access-vlan` | 1059 | 600 | 1659 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.enabled` | 1192 | 445 | 1637 |
| `aruba-loop-protect` | `aruba-loop-protect:loop-protect.profile.re-enable-timer` | 1264 | 300 | 1564 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.dscp-map.color` | 1512 | 0 | 1512 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.root-guard` | 1071 | 370 | 1441 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.name` | 866 | 513 | 1379 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-lag` | 854 | 511 | 1365 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.name` | 847 | 505 | 1352 |
| `aruba-qos` | `aruba-qos:global-qos.trust` | 1327 | 0 | 1327 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.igmp.snooping` | 958 | 347 | 1305 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.role` | 774 | 492 | 1266 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.peer1.role` | 774 | 492 | 1266 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.peer2.role` | 774 | 492 | 1266 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.bpdu-filter` | 879 | 282 | 1161 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv4-snooping.trust` | 878 | 262 | 1140 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.system-mac` | 704 | 425 | 1129 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.system-mac` | 704 | 425 | 1129 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.split-detection-method` | 826 | 291 | 1117 |
| `aruba-vsf-template` | `aruba-vsf-template:vsf-templates.template.split-detection-method` | 826 | 291 | 1117 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.peer1.keepalive-device.peer-ip` | 680 | 422 | 1102 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.peer1.keepalive-device.source-ip` | 680 | 422 | 1102 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.peer2.keepalive-device.peer-ip` | 680 | 422 | 1102 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.peer2.keepalive-device.source-ip` | 680 | 422 | 1102 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.concurrent-onboarding` | 863 | 232 | 1095 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.name` | 833 | 256 | 1089 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.dhcpv4-snooping.enable` | 781 | 294 | 1075 |
| `aruba-loop-protect` | `aruba-loop-protect:loop-protect.profile.trap` | 933 | 137 | 1070 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.vrf-forwarding` | 637 | 360 | 997 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.chassis-name` | 793 | 156 | 949 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.line-modules.line-module-name` | 793 | 156 | 949 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.keepalive.peer-ip` | 594 | 350 | 944 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.keepalive.source-ip` | 594 | 350 | 944 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.keepalive.vrf-ref` | 594 | 350 | 944 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.eapol-max-requests` | 631 | 249 | 880 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.tcn-guard` | 615 | 247 | 862 |
| `aruba-hardware-module-profile` | `aruba-hardware-module-profile:hardware-modules.hw-profile.name` | 523 | 321 | 844 |
| `aruba-devicefingerprinting` | `aruba-devicefingerprinting:devicefingerprinting.profile.name` | 362 | 480 | 842 |
| `aruba-devicefingerprinting` | `aruba-devicefingerprinting:devicefingerprinting.profile.profile-name` | 362 | 480 | 842 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.switchport.tag` | 574 | 265 | 839 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.dhcpv4-snooping.trust` | 605 | 220 | 825 |
| `aruba-system-info` | `aruba-system-info:system-info.sys-description` | 575 | 229 | 804 |
| `aruba-hardware-module-profile` | `aruba-hardware-module-profile:hardware-modules.hw-profile.interface-group-speed-profile.group-id` | 470 | 305 | 775 |
| `aruba-hardware-module-profile` | `aruba-hardware-module-profile:hardware-modules.hw-profile.interface-group-speed-profile.speed` | 468 | 305 | 773 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.lacp.rate` | 470 | 258 | 728 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.max-retries` | 547 | 179 | 726 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.reauth-enable` | 555 | 147 | 702 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.reauth-enable` | 548 | 140 | 688 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.priority` | 431 | 256 | 687 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.cached-reauth-enable` | 526 | 154 | 680 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.cached-reauth-enable` | 514 | 142 | 656 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-bypass.lldp` | 472 | 161 | 633 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.eapol-timeout` | 463 | 154 | 617 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.trust` | 427 | 164 | 591 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.action` | 351 | 228 | 579 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.loop-protect.enable` | 375 | 196 | 571 |
| `aruba-ip-icmp-tcp` | `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.name` | 555 | 0 | 555 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.root-guard` | 364 | 191 | 555 |
| `aruba-ip-icmp-tcp` | `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.redirect` | 530 | 0 | 530 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.loop-guard` | 345 | 176 | 521 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.switchport.tag` | 328 | 141 | 469 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.line-modules.sku` | 313 | 155 | 468 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.platform` | 313 | 155 | 468 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.rate-type` | 289 | 156 | 445 |
| `aruba-port-security` | `aruba-port-security:port-security.policy.name` | 256 | 167 | 423 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mode` | 308 | 101 | 409 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.critical-auth-role` | 314 | 93 | 407 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.igmp.version` | 281 | 120 | 401 |
| `aruba-snmp-trap` | `aruba-snmp-trap:snmp-trap.profile.name` | 202 | 198 | 400 |
| `aruba-snmp-trap` | `aruba-snmp-trap:snmp-trap.profile.trap.id` | 201 | 198 | 399 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-bypass.cdp` | 299 | 100 | 399 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.cached-reauth-period` | 307 | 89 | 396 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-profile-name` | 253 | 136 | 389 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.pre-std-detect` | 272 | 117 | 389 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.cached-reauth-period` | 303 | 83 | 386 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.allow-flood-traffic` | 279 | 89 | 368 |
| `aruba-qos-queue` | `aruba-qos-queue:qos-queues.profile.q-profile-name` | 232 | 129 | 361 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.reauth-period` | 288 | 65 | 353 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.admin-edge-port` | 234 | 117 | 351 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.name` | 235 | 114 | 349 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.name` | 236 | 109 | 345 |
| `aruba-qos-queue` | `aruba-qos-queue:qos-queues.profile.priority.queue` | 223 | 120 | 343 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-precedence` | 250 | 89 | 339 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.reauth-period` | 265 | 71 | 336 |
| `aruba-port-security` | `aruba-port-security:port-security.policy.enable` | 197 | 138 | 335 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.quiet-period` | 250 | 81 | 331 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.enable` | 197 | 132 | 329 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.bpdu-filter` | 217 | 111 | 328 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.rate-type` | 205 | 109 | 314 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.reject-role` | 214 | 98 | 312 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.app-usage` | 208 | 101 | 309 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.voice-enable` | 301 | 0 | 301 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.bit-rate` | 208 | 92 | 300 |
| `aruba-snmp-trap` | `aruba-snmp-trap:snmp-trap.profile.trap.enable` | 164 | 133 | 297 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.lacp.fallback` | 190 | 103 | 293 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mac-auth.quiet-period` | 232 | 57 | 289 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.trust` | 211 | 74 | 285 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.name` | 194 | 85 | 279 |
| `aruba-cdp` | `aruba-cdp:cdp.profile.enable` | 182 | 95 | 277 |
| `aruba-cdp` | `aruba-cdp:cdp.profile.name` | 182 | 95 | 277 |
| `aruba-port-security` | `aruba-port-security:port-security.policy.client-limit` | 185 | 91 | 276 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.client-limit` | 185 | 88 | 273 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.mode` | 178 | 87 | 265 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.loop-guard` | 180 | 85 | 265 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.dscp-map.name` | 258 | 0 | 258 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.job-name` | 176 | 82 | 258 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.allocation-method` | 169 | 83 | 252 |
| `aruba-qos-queue` | `aruba-qos-queue:qos-queues.profile.priority.name` | 168 | 79 | 247 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-priority` | 184 | 62 | 246 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.linkup-delay-timer` | 138 | 102 | 240 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.linkup-delay-timer` | 138 | 102 | 240 |
| `aruba-snmp-trap` | `aruba-snmp-trap:snmp-trap.profile.trap.snmp-server-trap` | 102 | 130 | 232 |
| `aruba-snmp-trap` | `aruba-snmp-trap:snmp-trap.profile.trap.vrf` | 102 | 130 | 232 |
| `aruba-nae-script` | `aruba-nae-script:nae-scripts.nae-script.name` | 135 | 97 | 232 |
| `aruba-nae-script` | `aruba-nae-script:nae-scripts.nae-script.script` | 134 | 97 | 231 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.strict.queue` | 230 | 0 | 230 |
| `aruba-loop-protect` | `aruba-loop-protect:loop-protect.profile.transmit-interval` | 145 | 77 | 222 |
| `aruba-qos` | `aruba-qos:global-qos.q-profile` | 217 | 0 | 217 |
| `aruba-qos` | `aruba-qos:global-qos.sched-profile` | 217 | 0 | 217 |
| `aruba-named-condition` | `aruba-named-condition:named-conditions.named-condition.condition-rule.description` | 172 | 44 | 216 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.flow-control-mode` | 139 | 77 | 216 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.entry.sequence-number` | 136 | 75 | 211 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.fault-monitor-profile` | 132 | 79 | 211 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.entry.cli-command` | 135 | 75 | 210 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.entry.type` | 135 | 75 | 210 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.bpdu-guard` | 142 | 66 | 208 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.direction` | 133 | 74 | 207 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.bit-rate` | 146 | 61 | 207 |
| `aruba-nae-agent` | `aruba-nae-agent:nae-agents.nae-agent.agent-disable` | 119 | 88 | 207 |
| `aruba-nae-agent` | `aruba-nae-agent:nae-agents.nae-agent.agent-name` | 119 | 88 | 207 |
| `aruba-nae-agent` | `aruba-nae-agent:nae-agents.nae-agent.script-name` | 119 | 88 | 207 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.dwrr.queue` | 201 | 0 | 201 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.dwrr.weight` | 201 | 0 | 201 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.discovery-period` | 140 | 61 | 201 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.update-interval` | 156 | 44 | 200 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.assigned-class` | 143 | 50 | 193 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ip.mtu` | 148 | 42 | 190 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.profile-name` | 148 | 40 | 188 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.trigger-type` | 117 | 68 | 185 |
| `aruba-qos-queue` | `aruba-qos-queue:qos-queues.profile.priority.local-priority` | 182 | 0 | 182 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.name` | 129 | 52 | 181 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.schedule-entry.schedule-job` | 113 | 67 | 180 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.schedule-entry.sequence-number` | 113 | 67 | 180 |
| `aruba-management-user-group` | `aruba-management-user-group:management-user-groups.user-group.name` | 109 | 70 | 179 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.vni.id` | 124 | 51 | 175 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.enable` | 121 | 51 | 172 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.priority` | 133 | 37 | 170 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.security-violation.action` | 119 | 48 | 167 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-mode` | 101 | 65 | 166 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.src-ipv4` | 114 | 51 | 165 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.onboarding-precedence` | 111 | 54 | 165 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.vni.vlan` | 112 | 48 | 160 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.initial-auth-response-timeout` | 93 | 65 | 158 |
| `aruba-port-security` | `aruba-port-security:port-security.policy.sticky-mac-enable` | 89 | 68 | 157 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.name` | 108 | 48 | 156 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.type` | 108 | 48 | 156 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.index` | 107 | 48 | 155 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.sticky-mac-enable` | 89 | 65 | 154 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.auth-role` | 98 | 55 | 153 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.dynamic-arp-inspection.trust` | 96 | 54 | 150 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.address-type` | 99 | 42 | 141 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.dynamic-arp-inspection.trust` | 86 | 55 | 141 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udld.enable` | 96 | 41 | 137 |
| `aruba-aaa-captive-portal` | `aruba-aaa-captive-portal:captive-portal.profile.external-cp-server-url` | 85 | 51 | 136 |
| `aruba-aaa-captive-portal` | `aruba-aaa-captive-portal:captive-portal.profile.name` | 85 | 51 | 136 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.link-type` | 95 | 41 | 136 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ipv4.address` | 84 | 51 | 135 |
| `aruba-role-gpid` | `aruba-role-gpid:role-gpids.role-gpid.gpid` | 98 | 34 | 132 |
| `aruba-role-gpid` | `aruba-role-gpid:role-gpids.role-gpid.name` | 98 | 34 | 132 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.algorithm` | 0 | 131 | 131 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.queue` | 0 | 131 | 131 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.vlans` | 71 | 60 | 131 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.name` | 96 | 35 | 131 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.lacp.fallback-static` | 84 | 46 | 130 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.reauth-period` | 116 | 9 | 125 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.reauth-period` | 116 | 8 | 124 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.dhcpv6-snooping.enable` | 85 | 39 | 124 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.fallback-role` | 100 | 24 | 124 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.rate-type` | 88 | 33 | 121 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.ipv4-address` | 85 | 35 | 120 |
| `aruba-qos-queue` | `aruba-qos-queue:qos-queues.profile.priority.priorities` | 0 | 120 | 120 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.mode` | 96 | 24 | 120 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.rate-type` | 75 | 42 | 117 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.weight` | 0 | 109 | 109 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst-guard` | 79 | 29 | 108 |
| `aruba-management-user-group` | `aruba-management-user-group:management-user-groups.user-group.rule.rbac.action` | 64 | 44 | 108 |
| `aruba-management-user-group` | `aruba-management-user-group:management-user-groups.user-group.rule.rbac.match-command` | 64 | 44 | 108 |
| `aruba-management-user-group` | `aruba-management-user-group:management-user-groups.user-group.rule.seq-number` | 64 | 44 | 108 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.cdp.enable` | 69 | 37 | 106 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.enable` | 95 | 10 | 105 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.start-date-at` | 82 | 23 | 105 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.start-time-at` | 82 | 23 | 105 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.trigger-at` | 82 | 23 | 105 |
| `aruba-nae-agent` | `aruba-nae-agent:nae-agents.nae-agent.agent-parameters.name` | 65 | 40 | 105 |
| `aruba-nae-agent` | `aruba-nae-agent:nae-agents.nae-agent.agent-parameters.value` | 65 | 40 | 105 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.pre-auth-role` | 83 | 21 | 104 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.security-violation.shutdown-recovery-enable` | 74 | 30 | 104 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.vni.symmetric-routing` | 79 | 24 | 103 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.vni.vrf` | 79 | 24 | 103 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv4-access-list-in` | 57 | 46 | 103 |
| `aruba-firmware-management` | `aruba-firmware-management:device-firmware.site-distribution` | 53 | 50 | 103 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.ipv4-subnet-address` | 73 | 29 | 102 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.packet-rate` | 70 | 32 | 102 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.loop-protect.action` | 58 | 44 | 102 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.dscp-map.cos` | 101 | 0 | 101 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.enable` | 83 | 15 | 98 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.macs` | 55 | 43 | 98 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst-filter` | 72 | 25 | 97 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.disable` | 70 | 25 | 95 |
| `aruba-copp` | `aruba-copp:copp.profile.name` | 60 | 34 | 94 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.tcn-guard` | 65 | 29 | 94 |
| `aruba-hardware-module-profile` | `aruba-hardware-module-profile:hardware-modules.hw-profile.member-or-slot-ids` | 0 | 94 | 94 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject.common-name` | 66 | 27 | 93 |
| `aruba-dhcp-snooping-interface` | `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.name` | 77 | 15 | 92 |
| `aruba-dhcp-snooping-interface` | `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv4-snooping.trust` | 75 | 15 | 90 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.hw-profile` | 88 | 0 | 88 |
| `aruba-copp` | `aruba-copp:copp.profile.copp-policy.configured-copp-policy-entries.class` | 55 | 32 | 87 |
| `aruba-copp` | `aruba-copp:copp.profile.copp-policy.configured-copp-policy-entries.priority` | 55 | 32 | 87 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.description` | 53 | 34 | 87 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.eapol-max-requests` | 69 | 13 | 82 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.radius-override-enable` | 65 | 17 | 82 |
| `aruba-ip-icmp-tcp` | `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.unreachable` | 82 | 0 | 82 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.max-retries` | 69 | 11 | 80 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.security-violation.recovery-timer` | 55 | 25 | 80 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.fast-leave-vlan` | 57 | 23 | 80 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udld.mode.compatibility-mode` | 51 | 29 | 80 |
| `aruba-nexthop-group` | `aruba-nexthop-group:nexthop-groups.group.name` | 43 | 37 | 80 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.management-ip-address` | 51 | 28 | 79 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.eapol-timeout` | 69 | 9 | 78 |
| `aruba-nexthop-group` | `aruba-nexthop-group:nexthop-groups.group.nexthops.index` | 41 | 37 | 78 |
| `aruba-nexthop-group` | `aruba-nexthop-group:nexthop-groups.group.nexthops.ip` | 41 | 37 | 78 |
| `aruba-nexthop-group` | `aruba-nexthop-group:nexthop-groups.group.nexthops.type` | 41 | 37 | 78 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.bit-rate` | 49 | 28 | 77 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.name` | 38 | 39 | 77 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.broadcast-rate-limit.percentage` | 35 | 41 | 76 |
| `aruba-ipfix-flow-monitor` | `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.name` | 36 | 40 | 76 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.pd-class-override` | 55 | 20 | 75 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.icmp-traffic-type` | 54 | 21 | 75 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.rate-type` | 54 | 21 | 75 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.id` | 53 | 22 | 75 |
| `aruba-ipfix-flow-monitor` | `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.record` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.counter-bytes` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-source-address` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.transport-destination-port` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.transport-source-port` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.name` | 35 | 40 | 75 |
| `aruba-ipfix-flow-monitor` | `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.exporter.exporter-name` | 35 | 40 | 75 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-version` | 35 | 40 | 75 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.packet-rate` | 48 | 26 | 74 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-destination-address` | 35 | 39 | 74 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-protocol` | 35 | 39 | 74 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.counter-packets` | 35 | 39 | 74 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.cached-reauth-period` | 65 | 8 | 73 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.cached-reauth-period` | 65 | 8 | 73 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.hashing` | 45 | 28 | 73 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.device-profile-secure` | 56 | 16 | 72 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv6-snooping.trust` | 55 | 17 | 72 |
| `aruba-lacp` | `aruba-lacp:lacp.hash` | 67 | 5 | 72 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.ip-version` | 49 | 22 | 71 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.mode` | 49 | 22 | 71 |
| `aruba-ip-lockdown` | `aruba-ip-lockdown:ip-source-lockdown.profile.ip-source-lockdown-resource-extended` | 43 | 28 | 71 |
| `aruba-ip-lockdown` | `aruba-ip-lockdown:ip-source-lockdown.profile.name` | 43 | 28 | 71 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.sflow.enable` | 56 | 14 | 70 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.dst` | 48 | 22 | 70 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.link-type` | 49 | 20 | 69 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.rpvst-filter` | 31 | 38 | 69 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.dpi-enable` | 35 | 32 | 67 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.frequency` | 31 | 36 | 67 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.start-time-on` | 31 | 36 | 67 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.trigger-on` | 31 | 36 | 67 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.description` | 41 | 26 | 67 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.timestamp-absolute-first` | 29 | 38 | 67 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.rate-type` | 45 | 21 | 66 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.quiet-period` | 57 | 8 | 65 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udld.mode.rfc5171-mode` | 38 | 27 | 65 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.bit-rate` | 51 | 14 | 65 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.timestamp-absolute-last` | 27 | 38 | 65 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.quiet-period` | 57 | 8 | 65 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.lldp-trap-enable` | 38 | 26 | 64 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.cached-reauth-enable` | 54 | 9 | 63 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.cached-reauth-enable` | 54 | 9 | 63 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.start-date-on` | 29 | 33 | 62 |
| `aruba-system-info` | `aruba-system-info:system-info.snmpv3-local-engine-id` | 40 | 22 | 62 |
| `aruba-hardware-module-profile` | `aruba-hardware-module-profile:hardware-modules.hw-profile.always-on-poe` | 44 | 17 | 61 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.split-port-enable` | 38 | 22 | 60 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.ports.operator` | 41 | 19 | 60 |
| `aruba-udp-broadcast-forwarder` | `aruba-udp-broadcast-forwarder:udp-broadcast-forwarders.profile.enable` | 51 | 9 | 60 |
| `aruba-udp-broadcast-forwarder` | `aruba-udp-broadcast-forwarder:udp-broadcast-forwarders.profile.name` | 51 | 9 | 60 |
| `aruba-copp` | `aruba-copp:copp.profile.copp-policy.applied` | 38 | 20 | 58 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.split-port-count` | 36 | 22 | 58 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-name` | 30 | 28 | 58 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.reauth-enable` | 47 | 10 | 57 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv4-monitor` | 27 | 30 | 57 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.cost` | 44 | 13 | 57 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.min-bandwidths.minimum-bandwidth` | 57 | 0 | 57 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.min-bandwidths.queue` | 57 | 0 | 57 |
| `aruba-named-vlan` | `aruba-named-vlan:named-vlan.profile.name` | 39 | 18 | 57 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.multicast-rate-limit.percentage` | 28 | 28 | 56 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.vxlan.profile-name` | 40 | 16 | 56 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.vxlan.vni-list` | 40 | 16 | 56 |
| `aruba-aaa-macauth` | `aruba-aaa-macauth:macauth.profile.reauth-enable` | 47 | 8 | 55 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.poe.power-pairs` | 36 | 19 | 55 |
| `aruba-qos-queue` | `aruba-qos-queue:qos-queues.profile.priority.cos` | 55 | 0 | 55 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.energy-efficient` | 37 | 16 | 53 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.name` | 0 | 53 | 53 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.policy-in` | 29 | 24 | 53 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.vrf-forwarding` | 32 | 20 | 52 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.bit-rate` | 35 | 16 | 51 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.priority` | 40 | 11 | 51 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject.org` | 32 | 19 | 51 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.name` | 0 | 51 | 51 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.vni.id` | 0 | 51 | 51 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.vni.vni-name` | 0 | 51 | 51 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.vxlan-tunnel-profile` | 0 | 51 | 51 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.enable` | 0 | 51 | 51 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.src-ipv4` | 0 | 51 | 51 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.ep-name` | 36 | 15 | 51 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.name` | 36 | 15 | 51 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.igmp.filter-unknown-multicast` | 38 | 12 | 50 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mda-data-clients-limit` | 33 | 16 | 49 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.local-collector` | 24 | 25 | 49 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.collector-dest` | 25 | 24 | 49 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.vni.vlan` | 0 | 48 | 48 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.name` | 25 | 23 | 48 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.dhcpv6-snooping.trust` | 33 | 14 | 47 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.ports.min` | 28 | 19 | 47 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.name` | 30 | 17 | 47 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.enable` | 24 | 23 | 47 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.loop-protect.vlans` | 23 | 23 | 46 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject.state` | 27 | 19 | 46 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject.org-unit` | 28 | 18 | 46 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.monitor-name` | 23 | 23 | 46 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.monitor-name-type` | 23 | 23 | 46 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.type` | 23 | 23 | 46 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.source` | 24 | 22 | 46 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.igmp.fastlearn.eth-ports` | 34 | 12 | 46 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.packet-rate` | 29 | 16 | 45 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject.locality` | 29 | 16 | 45 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pvlan-port-mode` | 36 | 8 | 44 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.client-limit` | 39 | 5 | 44 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.name` | 30 | 14 | 44 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.source-name` | 30 | 14 | 44 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.critical-voice-role` | 32 | 11 | 43 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.description` | 21 | 21 | 42 |
| `aruba-lacp` | `aruba-lacp:lacp.system-priority` | 23 | 19 | 42 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.name` | 32 | 10 | 42 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.device-profile-secure` | 32 | 9 | 41 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.key-id` | 24 | 17 | 41 |
| `aruba-ipfix-flow-monitor` | `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.cache-timeout-active` | 22 | 19 | 41 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.basic.port-descr` | 29 | 11 | 40 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.description` | 19 | 21 | 40 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.auth-key-info.type` | 23 | 16 | 39 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.auth-key-info.auth-key-ciphertext` | 22 | 16 | 38 |
| `aruba-psm` | `aruba-psm:psm.psm-instance.name` | 27 | 11 | 38 |
| `aruba-psm` | `aruba-psm:psm.psm-instance.psm-ips` | 27 | 11 | 38 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.macauth-server-group` | 21 | 16 | 37 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4-relay.server.ip` | 26 | 11 | 37 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4-relay.server.ip-vrf` | 26 | 11 | 37 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4-relay.server.vrf` | 26 | 11 | 37 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.bit-rate` | 29 | 8 | 37 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.id` | 21 | 16 | 37 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.parent-name` | 21 | 16 | 37 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.parent-name-id` | 21 | 16 | 37 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.cdp.mode` | 23 | 13 | 36 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv4-snooping.max-bindings` | 27 | 9 | 36 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mac-notify-traps` | 24 | 12 | 36 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-https-url` | 19 | 17 | 36 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.type` | 24 | 12 | 36 |
| `aruba-mvrp` | `aruba-mvrp:mvrp.profile.enable` | 34 | 1 | 35 |
| `aruba-mvrp` | `aruba-mvrp:mvrp.profile.name` | 34 | 1 | 35 |
| `aruba-nd-snooping` | `aruba-nd-snooping:nd-snooping.profile.name` | 21 | 13 | 34 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.vrf` | 14 | 20 | 34 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-dns-response-code` | 19 | 15 | 34 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.destination-ipv4` | 22 | 12 | 34 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1xauth-server-group` | 21 | 12 | 33 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6.addresses.address` | 29 | 4 | 33 |
| `aruba-nd-snooping` | `aruba-nd-snooping:nd-snooping.profile.enable` | 20 | 13 | 33 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.vrf` | 23 | 10 | 33 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.ip` | 13 | 19 | 32 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.igmp.drop-unknown` | 26 | 6 | 32 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.description` | 24 | 8 | 32 |
| `aruba-hardware-module-profile` | `aruba-hardware-module-profile:hardware-modules.hw-profile.quick-poe` | 26 | 5 | 31 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.port` | 15 | 16 | 31 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.transport-protocol` | 15 | 16 | 31 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.hold-time` | 24 | 7 | 31 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.hold-time` | 24 | 7 | 31 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.version` | 27 | 3 | 30 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.trigger-on-weekly` | 16 | 14 | 30 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.week-day` | 16 | 14 | 30 |
| `aruba-mac-lockout` | `aruba-mac-lockout:mac-lockout.profile.name` | 22 | 8 | 30 |
| `aruba-track-object` | `aruba-track-object:tracking-object.vrrp.identifier` | 10 | 20 | 30 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-tls-attributes` | 16 | 14 | 30 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.poe-plus` | 17 | 12 | 29 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.sticky-macs.mac` | 19 | 10 | 29 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.port-security.sticky-macs.vlan` | 19 | 10 | 29 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.rate-type` | 22 | 7 | 29 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.enable` | 18 | 11 | 29 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.links.link1.description` | 18 | 11 | 29 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv4-access-list-out` | 21 | 7 | 28 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.schedule-profile` | 17 | 11 | 28 |
| `aruba-dhcp-client` | `aruba-dhcp-client:dhcp-client.profile.name` | 17 | 11 | 28 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.hello-interval` | 21 | 7 | 28 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.bridging-mode` | 21 | 7 | 28 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.hello-interval` | 21 | 7 | 28 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.policy.ipv4-access-list-in` | 10 | 17 | 27 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.encapsulation-vlan-id` | 13 | 14 | 27 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ipv4.address` | 14 | 13 | 27 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.mld.snooping` | 18 | 9 | 27 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.upload-template-interval` | 13 | 14 | 27 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.dead-interval` | 18 | 9 | 27 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.dead-interval` | 18 | 9 | 27 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.packet-rate` | 17 | 9 | 26 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.packet-rate` | 16 | 10 | 26 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.sflow.enable` | 20 | 6 | 26 |
| `aruba-mac-lockout` | `aruba-mac-lockout:mac-lockout.profile.address.mac` | 20 | 6 | 26 |
| `aruba-ipfix-flow-monitor` | `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.description` | 14 | 12 | 26 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lacp.port-id` | 14 | 11 | 25 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.med-poe-priority-override` | 17 | 8 | 25 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.vrrp.vrrp-profile-apply` | 22 | 3 | 25 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.bpdu-bypass.lldp` | 23 | 2 | 25 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.trigger-every` | 12 | 13 | 25 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.destination-ip` | 16 | 9 | 25 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.source-ip` | 16 | 9 | 25 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.tid` | 16 | 9 | 25 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.destinations.eth-interfaces` | 16 | 9 | 25 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.forward-vlan` | 18 | 6 | 24 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ip.mtu` | 18 | 6 | 24 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.vni.symmetric-routing` | 0 | 24 | 24 |
| `aruba-interface-vni` | `aruba-interface-vni:vxlan-vni.profile.vni.vrf` | 0 | 24 | 24 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.start-time-every` | 12 | 12 | 24 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.discovery-period` | 19 | 4 | 23 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.cert-key-type` | 12 | 11 | 23 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.portfilter.eth-ports` | 17 | 6 | 23 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.portfilter.lag-ports` | 17 | 6 | 23 |
| `aruba-dhcp-client` | `aruba-dhcp-client:dhcp-client.profile.ip.enable-hostname` | 12 | 11 | 23 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.name` | 17 | 6 | 23 |
| `aruba-mka` | `aruba-mka:mka.policy.name` | 17 | 6 | 23 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.dscp` | 16 | 6 | 22 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.split-port-speed` | 13 | 9 | 22 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.transmit-interval` | 15 | 7 | 22 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.ports.max` | 15 | 7 | 22 |
| `aruba-nexthop-group` | `aruba-nexthop-group:nexthop-groups.group.nexthops.default-host` | 14 | 8 | 22 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.error-control` | 12 | 9 | 21 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.unknown-unicast-rate-limit.percentage` | 14 | 7 | 21 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.bpdu-bypass.cdp` | 19 | 2 | 21 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.description` | 14 | 7 | 21 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.minimum-bandwidth` | 0 | 21 | 21 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.start-date-every` | 11 | 10 | 21 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.igmp.static-group` | 17 | 4 | 21 |
| `aruba-mka` | `aruba-mka:mka.policy.cak-info.ckn` | 15 | 6 | 21 |
| `aruba-mka` | `aruba-mka:mka.policy.cak-info.key-type` | 15 | 6 | 21 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.reinit-delay` | 17 | 4 | 21 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.peer-detect-interval` | 17 | 4 | 21 |
| `aruba-psm` | `aruba-psm:psm.psm-instance.vrf` | 10 | 11 | 21 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.frequency` | 13 | 8 | 21 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.inter-switch-link-timers.peer-detect-interval` | 17 | 4 | 21 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.client-limit` | 15 | 5 | 20 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.allow-flood-traffic` | 15 | 5 | 20 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.mac-notify-traps` | 12 | 8 | 20 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.icmp-traffic-type` | 17 | 3 | 20 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.rate-type` | 17 | 3 | 20 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.vrf-forwarding` | 9 | 11 | 20 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.split-recovery-disable` | 16 | 4 | 20 |
| `aruba-mka` | `aruba-mka:mka.policy.cak-info.cak-ciphertext` | 14 | 6 | 20 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.dcbx-enable` | 11 | 9 | 20 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.enable` | 12 | 8 | 20 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.split-recovery-disable` | 16 | 4 | 20 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ip.l3-counters` | 14 | 5 | 19 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.cost` | 14 | 5 | 19 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.igmp.fastlearn.lag-ports` | 13 | 6 | 19 |
| `aruba-static-mac` | `aruba-static-mac:static-macs.profile.name` | 12 | 7 | 19 |
| `aruba-static-mac` | `aruba-static-mac:static-macs.profile.static-mac.destination-port.l2-destination` | 12 | 7 | 19 |
| `aruba-static-mac` | `aruba-static-mac:static-macs.profile.static-mac.mac` | 12 | 7 | 19 |
| `aruba-static-mac` | `aruba-static-mac:static-macs.profile.static-mac.mac-vlan` | 12 | 7 | 19 |
| `aruba-static-mac` | `aruba-static-mac:static-macs.profile.static-mac.vlan` | 12 | 7 | 19 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.initial-auth-response-timeout` | 15 | 3 | 18 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-auth.lldp` | 12 | 6 | 18 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6.enable-default-link-local` | 10 | 8 | 18 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-dense.enable` | 17 | 1 | 18 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.egress-rate` | 11 | 7 | 18 |
| `aruba-l3-route` | `aruba-l3-route:l3-route.profile.name` | 15 | 3 | 18 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ipfix-flow-monitor-in.ipv4-monitor` | 7 | 11 | 18 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.broadcast-rate-limit.percentage` | 11 | 7 | 18 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.crypto-algorithm` | 11 | 7 | 18 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.rsa-key-length` | 7 | 11 | 18 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.enable-counters` | 14 | 4 | 18 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.entry.cli-delay` | 13 | 5 | 18 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.count` | 8 | 10 | 18 |
| `aruba-named-vlan` | `aruba-named-vlan:named-vlan.profile.vlan.vlan-id-ranges` | 17 | 1 | 18 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.name` | 11 | 6 | 17 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.store-name` | 11 | 6 | 17 |
| `aruba-rip` | `aruba-rip:rip.router.instance-tag` | 17 | 0 | 17 |
| `aruba-rip` | `aruba-rip:rip.router.instance-tag-vrf-proto-type` | 17 | 0 | 17 |
| `aruba-rip` | `aruba-rip:rip.router.proto-type` | 17 | 0 | 17 |
| `aruba-rip` | `aruba-rip:rip.router.vrf` | 17 | 0 | 17 |
| `aruba-mka` | `aruba-mka:mka.policy.key-server-priority` | 12 | 5 | 17 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.replay-window` | 13 | 4 | 17 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.forwarding-status` | 7 | 10 | 17 |
| `aruba-switch-stack` | `aruba-switch-stack:stacks.stack.members.links.link2.description` | 11 | 6 | 17 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.enable` | 14 | 2 | 16 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.source-address-any` | 16 | 0 | 16 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.policy.mac-access-list-in` | 9 | 7 | 16 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udld.mode.aruba-mode` | 13 | 3 | 16 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.pvlan-port-mode` | 10 | 6 | 16 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.enforcement-level` | 11 | 5 | 16 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.dst` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.id` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.ip-version` | 0 | 16 | 16 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.interface.vni-profile-name` | 0 | 16 | 16 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.name` | 11 | 5 | 16 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.profile` | 11 | 5 | 16 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.trap` | 7 | 8 | 15 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.max-rate-units` | 8 | 7 | 15 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udld.retries` | 8 | 7 | 15 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.bit-rate` | 13 | 2 | 15 |
| `aruba-nd-snooping-interface` | `aruba-nd-snooping-interface:nd-snooping-interface.profile.name` | 10 | 5 | 15 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.src` | 9 | 6 | 15 |
| `aruba-config-checkpoint` | `aruba-config-checkpoint:config-checkpoint.profile.name` | 12 | 3 | 15 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.est-profile` | 8 | 6 | 14 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.med.poe` | 8 | 6 | 14 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.trust` | 9 | 5 | 14 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.policy.ipv4-access-list-out` | 9 | 5 | 14 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.multicast-rate-limit.percentage` | 9 | 5 | 14 |
| `aruba-nd-snooping-interface` | `aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.trust` | 9 | 5 | 14 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.days` | 4 | 10 | 14 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-eth` | 10 | 4 | 14 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.source.ipv4-address` | 6 | 8 | 14 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-auth.mac-type` | 13 | 0 | 13 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv6-access-list-in` | 8 | 5 | 13 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.cos` | 7 | 6 | 13 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udld.interval` | 8 | 5 | 13 |
| `aruba-l3-route` | `aruba-l3-route:l3-route.profile.route-redistribute` | 11 | 2 | 13 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.packet-rate` | 8 | 5 | 13 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.ipv4-prefix` | 7 | 6 | 13 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.enable` | 4 | 9 | 13 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.name` | 4 | 9 | 13 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.enable` | 13 | 0 | 13 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject.country` | 10 | 3 | 13 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.clock-step` | 9 | 4 | 13 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.delay-mechanism` | 9 | 4 | 13 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.mode` | 9 | 4 | 13 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.transport` | 8 | 5 | 13 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.thresh-profile-name` | 5 | 8 | 13 |
| `aruba-dynamic-arp-inspection-interface` | `aruba-dynamic-arp-inspection-interface:dynamic-arp-inspection-interface.profile.dynamic-arp-inspection.trust` | 9 | 3 | 12 |
| `aruba-dynamic-arp-inspection-interface` | `aruba-dynamic-arp-inspection-interface:dynamic-arp-inspection-interface.profile.name` | 9 | 3 | 12 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.type` | 9 | 3 | 12 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.forced-fast-leave-vlan` | 5 | 7 | 12 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ip-source-lockdown.ipv4` | 6 | 6 | 12 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.basic.management-addr` | 11 | 1 | 12 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.basic.system-descr` | 11 | 1 | 12 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.macsec-policy` | 8 | 4 | 12 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mka-policy` | 8 | 4 | 12 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ptp.enable` | 8 | 4 | 12 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.igmp-snooping-lag.forward-vlan` | 6 | 6 | 12 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.profile-name` | 6 | 6 | 12 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.enabled` | 8 | 4 | 12 |
| `aruba-management-user-group` | `aruba-management-user-group:management-user-groups.user-group.rule.description` | 7 | 5 | 12 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.enable` | 8 | 4 | 12 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.monitor-n-flows` | 6 | 6 | 12 |
| `aruba-config-checkpoint` | `aruba-config-checkpoint:config-checkpoint.profile.post-checkpoint-delay` | 10 | 1 | 11 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.address` | 8 | 3 | 11 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.directory` | 8 | 3 | 11 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.enable` | 8 | 3 | 11 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.bfd.detect-multiplier` | 9 | 2 | 11 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.client-limit-max` | 9 | 2 | 11 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.percentage` | 7 | 4 | 11 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.vlan-id` | 5 | 6 | 11 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.bit-rate` | 10 | 1 | 11 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.policy-out` | 8 | 3 | 11 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.management-vlan` | 5 | 6 | 11 |
| `aruba-qos-cos` | `aruba-qos-cos:qos-cos.profile.cos-map.color` | 11 | 0 | 11 |
| `aruba-qos-cos` | `aruba-qos-cos:qos-cos.profile.cos-map.cos` | 11 | 0 | 11 |
| `aruba-qos-cos` | `aruba-qos-cos:qos-cos.profile.cos-map.local-priority` | 11 | 0 | 11 |
| `aruba-qos-cos` | `aruba-qos-cos:qos-cos.profile.name` | 11 | 0 | 11 |
| `aruba-rip` | `aruba-rip:rip.router.redistribute.redistribute-id` | 11 | 0 | 11 |
| `aruba-rip` | `aruba-rip:rip.router.redistribute.redistribute-type` | 11 | 0 | 11 |
| `aruba-rip` | `aruba-rip:rip.profile.name` | 0 | 11 | 11 |
| `aruba-rip` | `aruba-rip:rip.profile.router.instance-tag` | 0 | 11 | 11 |
| `aruba-rip` | `aruba-rip:rip.profile.router.instance-tag-vrf-proto-type` | 0 | 11 | 11 |
| `aruba-rip` | `aruba-rip:rip.profile.router.proto-type` | 0 | 11 | 11 |
| `aruba-rip` | `aruba-rip:rip.profile.router.vrf` | 0 | 11 | 11 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.ubt-fallback-role` | 8 | 2 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.bfd.min-rx-interval` | 8 | 2 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.bfd.min-tx-interval` | 8 | 2 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lacp.port-priority` | 6 | 4 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.dcbx-disable` | 3 | 7 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.speed-downshift-enable` | 9 | 1 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.speed-override` | 6 | 4 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.cost` | 5 | 5 | 10 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.client-limit` | 5 | 5 | 10 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.update-interval` | 6 | 4 | 10 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.igmp.preprogram-starg-flow` | 5 | 5 | 10 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.max-bandwidth-kbps` | 0 | 10 | 10 |
| `aruba-track-object` | `aruba-track-object:tracking-object.vrrp.interface.interface-type` | 3 | 7 | 10 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.minutes` | 7 | 3 | 10 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.queue-num` | 4 | 6 | 10 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.accept-start` | 5 | 5 | 10 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.send-start` | 5 | 5 | 10 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.query-interval` | 9 | 0 | 9 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.static-group` | 8 | 1 | 9 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.priority-flow-control.priority-config.direction` | 6 | 3 | 9 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.priority-flow-control.priority-config.priority` | 6 | 3 | 9 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.vlan-translate.origin` | 5 | 4 | 9 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.vlan-translate.translated` | 5 | 4 | 9 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ip.l3-counters` | 7 | 2 | 9 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.schedule-profile` | 4 | 5 | 9 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.enable` | 6 | 3 | 9 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.description` | 5 | 4 | 9 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.id` | 0 | 9 | 9 |
| `aruba-qos-dscp` | `aruba-qos-dscp:qos-dscp.profile.dscp-map.cos-override` | 9 | 0 | 9 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.ext-key-usage` | 5 | 4 | 9 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.key-usage` | 5 | 4 | 9 |
| `aruba-erps` | `aruba-erps:erps.profile.name` | 7 | 2 | 9 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.instance-id` | 7 | 2 | 9 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.protected-vlans` | 7 | 2 | 9 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.ring-id` | 7 | 2 | 9 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.control-vlan` | 7 | 2 | 9 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.protection-switching-enable` | 7 | 2 | 9 |
| `aruba-firmware-management` | `aruba-firmware-management:device-firmware.issu.software-update-rollback-timer-enable` | 5 | 4 | 9 |
| `aruba-rip` | `aruba-rip:rip.router.svi-interfaces.address-family` | 9 | 0 | 9 |
| `aruba-rip` | `aruba-rip:rip.router.svi-interfaces.ip-address` | 9 | 0 | 9 |
| `aruba-rip` | `aruba-rip:rip.router.svi-interfaces.svi-id` | 9 | 0 | 9 |
| `aruba-rip` | `aruba-rip:rip.router.svi-interfaces.svi-id-address-family` | 9 | 0 | 9 |
| `aruba-countermon` | `aruba-countermon:countermon.profile.enable-polling` | 2 | 7 | 9 |
| `aruba-countermon` | `aruba-countermon:countermon.profile.name` | 2 | 7 | 9 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.name` | 8 | 1 | 9 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.agent-type` | 5 | 4 | 9 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.condtype` | 5 | 4 | 9 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.name-condition` | 5 | 4 | 9 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.group-by` | 4 | 5 | 9 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.password-ciphertext` | 5 | 3 | 8 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.password-type` | 5 | 3 | 8 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.username` | 5 | 3 | 8 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.override-negotiation` | 6 | 2 | 8 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.dr-priority` | 7 | 1 | 8 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.vsx.shutdown-on-split` | 2 | 6 | 8 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.nd-snooping.trust` | 4 | 4 | 8 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.rpvst-guard` | 7 | 1 | 8 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.trigger-on-monthly` | 2 | 6 | 8 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.role` | 7 | 1 | 8 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.keepalive.dead-interval` | 4 | 4 | 8 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.rpl` | 7 | 1 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.router.redistribute.redistribute-id` | 0 | 8 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.router.redistribute.redistribute-type` | 0 | 8 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.description` | 0 | 8 | 8 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.group-id` | 7 | 1 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.router.svi-interfaces.address-family` | 0 | 8 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.router.svi-interfaces.ip-address` | 0 | 8 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.router.svi-interfaces.svi-id` | 0 | 8 | 8 |
| `aruba-rip` | `aruba-rip:rip.profile.router.svi-interfaces.svi-id-address-family` | 0 | 8 | 8 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.set-watch` | 5 | 3 | 8 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.watches.event-id` | 5 | 3 | 8 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.watches.watch-name` | 5 | 3 | 8 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.keepalive.dead-interval` | 4 | 4 | 8 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.dot1.port-vlan-id` | 6 | 1 | 7 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.med.network-policy` | 6 | 1 | 7 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-dense.source-address-any` | 7 | 0 | 7 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.icmp-rate-limit.packet-rate` | 6 | 1 | 7 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ptp.enable` | 5 | 2 | 7 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.igmp.policy-in` | 6 | 1 | 7 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.vrf-forwarding` | 5 | 2 | 7 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.links-to-disable.ethernet-ports` | 0 | 7 | 7 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.links-to-monitor.ethernet-ports` | 0 | 7 | 7 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.month-day` | 2 | 5 | 7 |
| `aruba-nexthop-group` | `aruba-nexthop-group:nexthop-groups.group.nexthops.null-interface` | 4 | 3 | 7 |
| `aruba-track-object` | `aruba-track-object:tracking-object.vrrp.interface.svi` | 1 | 6 | 7 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.strict.max-bandwidth-kbps` | 7 | 0 | 7 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.hold-multiplier` | 5 | 2 | 7 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.bridging-mode` | 0 | 7 | 7 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.cipher-suites` | 5 | 2 | 7 |
| `aruba-mac-lockout` | `aruba-mac-lockout:mac-lockout.profile.log` | 5 | 2 | 7 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.line-modules.hw-profile` | 7 | 0 | 7 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.cli` | 3 | 4 | 7 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.query-max-response-time` | 6 | 0 | 6 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.dot1.port-vlan-name` | 5 | 1 | 6 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.bfd-enable` | 5 | 1 | 6 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.instance-id` | 4 | 2 | 6 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.macsec-policy` | 4 | 2 | 6 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.mka-policy` | 4 | 2 | 6 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.mtu` | 5 | 1 | 6 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.delay-up` | 0 | 6 | 6 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.description` | 4 | 2 | 6 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.port0-eth-interface` | 6 | 0 | 6 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.port1-eth-interface` | 6 | 0 | 6 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.nd-snooping.nd-guard` | 4 | 2 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.client-address` | 3 | 3 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.interface-ethernet` | 3 | 3 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.interface-types` | 3 | 3 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.ip-version` | 3 | 3 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.ip-version-vlan-client-address` | 3 | 3 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.mac` | 3 | 3 | 6 |
| `aruba-ip-binding` | `aruba-ip-binding:source-ip-bindings.static-entry.vlan` | 3 | 3 | 6 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.ready` | 4 | 2 | 6 |
| `aruba-dsm` | `aruba-dsm:dsm.dsm-instance.name` | 3 | 3 | 6 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-destination-address` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-protocol` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-source-address` | 2 | 4 | 6 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-version` | 2 | 4 | 6 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.credentials.password-ciphertext` | 2 | 4 | 6 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.credentials.user` | 2 | 4 | 6 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.location` | 2 | 4 | 6 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.name` | 2 | 4 | 6 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.pool` | 2 | 4 | 6 |
| `aruba-l3-route` | `aruba-l3-route:l3-route.profile.graceful-restart` | 5 | 1 | 6 |
| `aruba-container` | `aruba-container:containers.instance.name` | 2 | 4 | 6 |
| `aruba-ipfix-flow-monitor` | `aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.cache-timeout-inactive` | 3 | 3 | 6 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.client-auto-logoff-enable` | 4 | 1 | 5 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.blocked-vlan` | 3 | 2 | 5 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.ecdsa-curve-size` | 5 | 0 | 5 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.hello-interval` | 5 | 0 | 5 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.pim-sparse.enable` | 2 | 3 | 5 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.unknown-unicast-rate-limit.percentage` | 4 | 1 | 5 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.source.interface-vlan` | 5 | 0 | 5 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject-alt-name-dns` | 3 | 2 | 5 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.max-bandwidth-percent` | 0 | 5 | 5 |
| `aruba-advanced-intelligent-forwarding` | `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-host-route-ipv4` | 5 | 0 | 5 |
| `aruba-advanced-intelligent-forwarding` | `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.name` | 5 | 0 | 5 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.nd-snooping.ra-drop` | 4 | 1 | 5 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.nd-snooping.ra-guard-log` | 3 | 2 | 5 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.rcp-primary-method` | 0 | 5 | 5 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.items.ipv4-prefix` | 5 | 0 | 5 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.keepalive.hello-interval` | 3 | 2 | 5 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.port-number` | 3 | 2 | 5 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.priority` | 3 | 2 | 5 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.protocol` | 3 | 2 | 5 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.protocol-port-number` | 3 | 2 | 5 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.preemption-enable` | 5 | 0 | 5 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.protected-vlans` | 5 | 0 | 5 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.secondary-ethernet-port` | 5 | 0 | 5 |
| `aruba-config-checkpoint` | `aruba-config-checkpoint:config-checkpoint.profile.post-checkpoint` | 3 | 2 | 5 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.block` | 1 | 4 | 5 |
| `aruba-feature-pack` | `aruba-feature-pack:management-server.profile.vrf` | 2 | 3 | 5 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.dcbx-version` | 2 | 3 | 5 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.primary-ethernet-port` | 5 | 0 | 5 |
| `aruba-dhcp-client` | `aruba-dhcp-client:dhcp-client.profile.ip.enable-broadcast-flag` | 5 | 0 | 5 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.payload-size` | 4 | 1 | 5 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.accept-end` | 3 | 2 | 5 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.send-end` | 3 | 2 | 5 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.keepalive.hello-interval` | 3 | 2 | 5 |
| `aruba-dhcp-snooping-interface` | `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv4-snooping.max-bindings` | 3 | 1 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.canned-eap-success-enable` | 4 | 0 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.arp.timeout` | 3 | 1 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.last-member-query-interval` | 4 | 0 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.robustness` | 4 | 0 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ip-directed-broadcast-enable` | 3 | 1 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.mac-phy` | 2 | 2 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.hello-delay` | 4 | 0 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.cost` | 2 | 2 | 4 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.basic.system-cap` | 3 | 1 | 4 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ipv6.addresses.address` | 3 | 1 | 4 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ipv6.enable-default-link-local` | 4 | 0 | 4 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.vlan-translate.origin` | 3 | 1 | 4 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.vlan-translate.translated` | 3 | 1 | 4 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.delay-down` | 0 | 4 | 4 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-tcp-establishment-time` | 2 | 2 | 4 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-supp.enable` | 0 | 4 | 4 |
| `aruba-nd-snooping` | `aruba-nd-snooping:nd-snooping.profile.ra-guard-policy.ra-guard-name` | 4 | 0 | 4 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.description` | 3 | 1 | 4 |
| `aruba-rmon-alarm` | `aruba-rmon-alarm:rmon-alarms.profile.name` | 3 | 1 | 4 |
| `aruba-rmon-alarm` | `aruba-rmon-alarm:rmon-alarms.profile.rmon.falling-threshold` | 3 | 1 | 4 |
| `aruba-rmon-alarm` | `aruba-rmon-alarm:rmon-alarms.profile.rmon.index` | 3 | 1 | 4 |
| `aruba-rmon-alarm` | `aruba-rmon-alarm:rmon-alarms.profile.rmon.rising-threshold` | 3 | 1 | 4 |
| `aruba-rmon-alarm` | `aruba-rmon-alarm:rmon-alarms.profile.rmon.snmp-oid` | 3 | 1 | 4 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.instance.instance-description` | 3 | 1 | 4 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.delayed-refresh_enable` | 1 | 3 | 4 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.delayed-refresh-interval` | 1 | 3 | 4 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.port1-portchannel` | 2 | 2 | 4 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.enable-counters` | 0 | 4 | 4 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.status` | 3 | 1 | 4 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.syslog` | 3 | 1 | 4 |
| `aruba-firmware-management` | `aruba-firmware-management:device-firmware.issu.software-update-rollback-timer` | 2 | 2 | 4 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.dhcpv4-snooping.ip-binding-enable` | 4 | 0 | 4 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.preemption-delay` | 4 | 0 | 4 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.nd-snooping.allow-bindings-on-trusted-ports` | 0 | 4 | 4 |
| `aruba-qos-cos` | `aruba-qos-cos:qos-cos.profile.cos-map.name` | 4 | 0 | 4 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.keepalive.udp-port` | 4 | 0 | 4 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.include` | 1 | 3 | 4 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.include-regex` | 1 | 3 | 4 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.line-modules.power-admin-state` | 4 | 0 | 4 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.comment` | 3 | 1 | 4 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.encap` | 2 | 2 | 4 |
| `aruba-sysmon` | `aruba-sysmon:sysmon.profile.name` | 1 | 3 | 4 |
| `aruba-sysmon` | `aruba-sysmon:sysmon.profile.poll-interval` | 1 | 3 | 4 |
| `aruba-sysmon` | `aruba-sysmon:sysmon.profile.polling` | 1 | 3 | 4 |
| `aruba-vsx` | `aruba-vsx:vsx-profiles.vsx.sync-features.keepalive.udp-port` | 4 | 0 | 4 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.policy.ipv6-access-list-out` | 0 | 4 | 4 |
| `aruba-dhcp-snooping-interface` | `aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv6-snooping.trust` | 2 | 1 | 3 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.bpdu-auth.cdp` | 1 | 2 | 3 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.policy-in` | 3 | 0 | 3 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.re-enable-timer` | 3 | 0 | 3 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.oui` | 2 | 1 | 3 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.threshold-profile` | 1 | 2 | 3 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.dot1.link-aggregation` | 2 | 1 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.auth-mode` | 3 | 0 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.security-violation.action` | 3 | 0 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.security-violation.recovery-timer` | 3 | 0 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.security-violation.shutdown-recovery-enable` | 3 | 0 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.igmp-snooping-lag.blocked-vlan` | 3 | 0 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.policy.ipv6-access-list-in` | 2 | 1 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.packet-rate` | 2 | 1 | 3 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.mstp.instance-id` | 3 | 0 | 3 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ip.mtu` | 2 | 1 | 3 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.ip` | 1 | 2 | 3 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.ip-vrf` | 1 | 2 | 3 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.vrf` | 1 | 2 | 3 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.tlv.basic.system-name` | 2 | 1 | 3 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.port0-portchannel` | 1 | 2 | 3 |
| `aruba-ip-routing` | `aruba-ip-routing:ip-routing.profile.name` | 2 | 1 | 3 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.disable-nonce` | 2 | 1 | 3 |
| `aruba-dsm` | `aruba-dsm:dsm.dsm-instance.ipfix` | 1 | 2 | 3 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.vrf` | 3 | 0 | 3 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.control-vlan` | 3 | 0 | 3 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.strict.max-bandwidth-percent` | 3 | 0 | 3 |
| `aruba-vsx-pair` | `aruba-vsx-pair:vsx-config.vsx.linkup-delay-timer-exclude` | 2 | 1 | 3 |
| `aruba-dsm` | `aruba-dsm:dsm.dsm-instance.workload-migration` | 2 | 1 | 3 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.destination-hostname` | 3 | 0 | 3 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.destination-port` | 2 | 1 | 3 |
| `aruba-rip` | `aruba-rip:rip.router.ether-interfaces.address-family` | 3 | 0 | 3 |
| `aruba-rip` | `aruba-rip:rip.router.ether-interfaces.interface-name` | 3 | 0 | 3 |
| `aruba-rip` | `aruba-rip:rip.router.ether-interfaces.interface-name-address-family` | 3 | 0 | 3 |
| `aruba-rip` | `aruba-rip:rip.router.ether-interfaces.ip-address` | 3 | 0 | 3 |
| `aruba-track-object` | `aruba-track-object:tracking-object.vrrp.interface.ethernet` | 2 | 1 | 3 |
| `aruba-ipfix-flow-exporter` | `aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.hostname` | 2 | 1 | 3 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.job.enable` | 2 | 1 | 3 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.neighbor-last-update-enable` | 1 | 2 | 3 |
| `aruba-multicast` | `aruba-multicast:multicast-global.profile.name` | 2 | 1 | 3 |
| `aruba-container` | `aruba-container:containers.instance.image-location-url` | 2 | 1 | 3 |
| `aruba-container` | `aruba-container:containers.instance.image-location-vrf` | 2 | 1 | 3 |
| `aruba-device-certificate` | `aruba-device-certificate:device-certificates.device-certificate.subject-alt-name-ip` | 2 | 1 | 3 |
| `aruba-ip-lockdown-interface` | `aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.ip-source-lockdown.ipv4` | 0 | 3 | 3 |
| `aruba-ip-lockdown-interface` | `aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.name` | 0 | 3 | 3 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-interface` | 1 | 2 | 3 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn-entry.thresh-units` | 3 | 0 | 3 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn-entry.threshold` | 3 | 0 | 3 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.color` | 0 | 3 | 3 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.max-threshold-percent` | 0 | 3 | 3 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.min-threshold-percent` | 0 | 3 | 3 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.dynamic-arp-inspection.enable` | 2 | 1 | 3 |
| `aruba-aaa-dot1xauth` | `aruba-aaa-dot1xauth:dot1xauth.profile.canned-eap-success-enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.querier-enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv4.secondary-ip` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.enable` | 1 | 1 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.elin-addr` | 1 | 1 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.llfc-pool-id` | 1 | 1 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.trap` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mld.enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.registration` | 1 | 1 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim6-sparse.enable` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv6-access-list-out` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ptp.vlan` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.priority` | 2 | 0 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.priority` | 1 | 1 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.icmp-rate-limit.percentage` | 2 | 0 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.mstp.priority` | 2 | 0 | 2 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.l3-counters` | 2 | 0 | 2 |
| `aruba-nd-snooping` | `aruba-nd-snooping:nd-snooping.profile.ra-guard-policy.match-list.access-list` | 2 | 0 | 2 |
| `aruba-rmon-alarm` | `aruba-rmon-alarm:rmon-alarms.profile.rmon.interval` | 1 | 1 | 2 |
| `aruba-mgmd` | `aruba-mgmd:mgmd-global.profile.mld.filter-unknown-multicast` | 2 | 0 | 2 |
| `aruba-ip-routing` | `aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-port` | 1 | 1 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.policy.mac-access-list-in` | 0 | 2 | 2 |
| `aruba-advanced-intelligent-forwarding` | `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-exclude-nexthop-ipv4` | 2 | 0 | 2 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.wtr-interval` | 2 | 0 | 2 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.pim-sparse.enable` | 0 | 2 | 2 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.links-to-monitor.lag-ports` | 0 | 2 | 2 |
| `aruba-qos-pool` | `aruba-qos-pool:qos-pools.profile.name` | 2 | 0 | 2 |
| `aruba-qos-pool` | `aruba-qos-pool:qos-pools.profile.pool.headroom-size` | 2 | 0 | 2 |
| `aruba-qos-pool` | `aruba-qos-pool:qos-pools.profile.pool.index` | 2 | 0 | 2 |
| `aruba-qos-pool` | `aruba-qos-pool:qos-pools.profile.pool.priority` | 2 | 0 | 2 |
| `aruba-qos-pool` | `aruba-qos-pool:qos-pools.profile.pool.size` | 2 | 0 | 2 |
| `aruba-qos-pool` | `aruba-qos-pool:qos-pools.profile.pool.type` | 2 | 0 | 2 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.description` | 0 | 2 | 2 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.threshold-percent` | 0 | 2 | 2 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.link-clock-narrow-tolerance` | 0 | 2 | 2 |
| `aruba-mka` | `aruba-mka:mka.policy.eapol-destination-mac` | 1 | 1 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.timers.garbage-collection` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.timers.timeout` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.timers.update` | 0 | 2 | 2 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.color` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.max-threshold` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.min-threshold` | 2 | 0 | 2 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.thresh-units` | 2 | 0 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.rpvst.vlan-id` | 0 | 2 | 2 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.vrrp.vrrp-profile-apply` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.router.enable` | 2 | 0 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.dscp` | 0 | 2 | 2 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ipv6.addresses.address` | 0 | 2 | 2 |
| `aruba-job-scheduler` | `aruba-job-scheduler:job-scheduler.schedule.hours` | 1 | 1 | 2 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.confidentiality-offset` | 1 | 1 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.redistribute.ospf-id` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.router.redistribute.ospf-id` | 2 | 0 | 2 |
| `aruba-aaa-captive-portal` | `aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-format` | 0 | 2 | 2 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.primary-url` | 0 | 2 | 2 |
| `aruba-container-network` | `aruba-container-network:container-networks.profile.name` | 1 | 1 | 2 |
| `aruba-container-network` | `aruba-container-network:container-networks.profile.name-vrf` | 1 | 1 | 2 |
| `aruba-container-network` | `aruba-container-network:container-networks.profile.vrf` | 1 | 1 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.egress-rate` | 0 | 2 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.max-rate-units` | 0 | 2 | 2 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-vlan` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.loopback-interfaces.address-family` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.loopback-interfaces.ip-address` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.loopback-interfaces.loopback-id` | 0 | 2 | 2 |
| `aruba-rip` | `aruba-rip:rip.profile.router.loopback-interfaces.loopback-id-address-family` | 0 | 2 | 2 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.recv-control-vlans` | 2 | 0 | 2 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.parameter` | 1 | 1 | 2 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.destination-guard.enable` | 2 | 0 | 2 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.aaa-lag.authentication-lag.bpdu-auth.mac-type` | 0 | 2 | 2 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ip.l3-counters` | 0 | 2 | 2 |
| `aruba-object-group` | `aruba-object-group:object-groups.group.vrf` | 0 | 2 | 2 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.description` | 0 | 2 | 2 |
| `aruba-external-storage` | `aruba-external-storage:external-storage.profile.store.vrf` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authorization.cached-critical-role-enable` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.arp.neighbor.address` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.arp.neighbor.mac-address` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.dhcpv6-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.igmp.strict-version` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ip-unnumbered-interface-loopback` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.advertise` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.default` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.management-tlv-ipv4-addr` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.loop-protect.transmit-interval` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mld-snooping-eth.forward-vlan` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.join-timer` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.leaveall-timer` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.periodic-timer` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.ra-guard-policy` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pfc-watchdog` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.bsr-boundary` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.datapath-auto-include` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.source-address` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.policy.mac-access-list-out` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.qos.burst` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.ip` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.port` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.arp.timeout` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.bfd.detect-multiplier` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.bfd.min-rx-interval` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.bfd.min-tx-interval` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.mvrp.enable` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.mvrp.forbidden-vlan-list` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.mvrp.registration` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.nd-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.portfilter.eth-ports` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.portfilter.lag-ports` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.threshold-profile` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.mstp.cost` | 1 | 0 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.vrrp.vrrp-profile-apply` | 1 | 0 | 1 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.ipv4.secondary-ip` | 1 | 0 | 1 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.policy.ipv4-access-list-out` | 1 | 0 | 1 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.gre.pim4-sparse.enable` | 1 | 0 | 1 |
| `aruba-ufd` | `aruba-ufd:ufd.profile.sessions.links-to-disable.lag-ports` | 0 | 1 | 1 |
| `aruba-ip-routing` | `aruba-ip-routing:ip-routing.profile.ip-prefix-priority-params.ip-prefix-priority` | 1 | 0 | 1 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.auth-key-info.auth-key` | 1 | 0 | 1 |
| `aruba-nd-snooping-interface` | `aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.ra-guard-policy` | 1 | 0 | 1 |
| `aruba-management-user-group` | `aruba-management-user-group:management-user-groups.user-group.inherit-group` | 1 | 0 | 1 |
| `aruba-mka` | `aruba-mka:mka.policy.cak-info.cak` | 1 | 0 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.count` | 1 | 0 | 1 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.meg-level` | 1 | 0 | 1 |
| `aruba-ip-routing` | `aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-ip` | 0 | 1 | 1 |
| `aruba-ip-icmp-tcp` | `aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.throttle` | 1 | 0 | 1 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.guard-interval` | 1 | 0 | 1 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.hold-off-interval` | 1 | 0 | 1 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.transmission-interval` | 1 | 0 | 1 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.loop-protect-vlans` | 0 | 1 | 1 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.loop-protect-vlans` | 0 | 1 | 1 |
| `aruba-ip-routing` | `aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-dst-port` | 1 | 0 | 1 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.loop-protect` | 1 | 0 | 1 |
| `aruba-rip` | `aruba-rip:rip.profile.router.maximum-paths` | 0 | 1 | 1 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.sub-ring` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.source.port` | 0 | 1 | 1 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.bypass-list` | 0 | 1 | 1 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.clear-tag-mode` | 0 | 1 | 1 |
| `aruba-mka` | `aruba-mka:mka.policy.eapol-dot1q-tagged` | 0 | 1 | 1 |
| `aruba-erps` | `aruba-erps:erps.profile.ring.parent-ring` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ip-source-lockdown.ipv6` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.dad-attempts` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.preference` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-type` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-value` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.country-code` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.what` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.mfs` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.igmp.enable` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.rpvst.cost` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.stp.rpvst.priority` | 0 | 1 | 1 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.mac-notify-traps` | 0 | 1 | 1 |
| `aruba-interface-vxlan` | `aruba-interface-vxlan:vxlan.profile.mac-notify-traps` | 0 | 1 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.source.interface-ethernet` | 1 | 0 | 1 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.recv-id` | 0 | 1 | 1 |
| `aruba-keychain` | `aruba-keychain:keychains.keychain.keys.send-id` | 0 | 1 | 1 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.replay-protect-enable` | 1 | 0 | 1 |
| `aruba-multicast` | `aruba-multicast:multicast-global.profile.l3vni-source-ipv4` | 0 | 1 | 1 |
| `aruba-qos-schedule` | `aruba-qos-schedule:qos-schedules.profile.sched-entries.burst` | 0 | 1 | 1 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.max-threshold-kbytes` | 0 | 1 | 1 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.min-threshold-kbytes` | 0 | 1 | 1 |
| `aruba-qos-threshold-profile` | `aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.threshold-kbytes` | 0 | 1 | 1 |
| `aruba-rip` | `aruba-rip:rip.profile.router.distance` | 0 | 1 | 1 |
| `aruba-aaa-captive-portal` | `aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-ciphertext-value` | 0 | 1 | 1 |
| `aruba-aaa-captive-portal` | `aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-value` | 0 | 1 | 1 |
| `aruba-certificate-rcp` | `aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.secondary-url` | 0 | 1 | 1 |
| `aruba-container-network` | `aruba-container-network:container-networks.profile.port-mapping.tcp.container-port` | 0 | 1 | 1 |
| `aruba-container-network` | `aruba-container-network:container-networks.profile.port-mapping.tcp.host-port` | 0 | 1 | 1 |
| `aruba-container-network` | `aruba-container-network:container-networks.profile.preferred` | 1 | 0 | 1 |
| `aruba-container` | `aruba-container:containers.instance.allow-unsigned-image` | 0 | 1 | 1 |
| `aruba-container` | `aruba-container:containers.instance.enable` | 0 | 1 | 1 |
| `aruba-container` | `aruba-container:containers.instance.encrypted-environment-variables.encrypted-env-type` | 1 | 0 | 1 |
| `aruba-container` | `aruba-container:containers.instance.encrypted-environment-variables.value-ciphertext` | 1 | 0 | 1 |
| `aruba-container` | `aruba-container:containers.instance.encrypted-environment-variables.variable` | 1 | 0 | 1 |
| `aruba-container` | `aruba-container:containers.instance.environment-variables.value` | 0 | 1 | 1 |
| `aruba-container` | `aruba-container:containers.instance.environment-variables.variable` | 0 | 1 | 1 |
| `aruba-container` | `aruba-container:containers.instance.runtime-constraints.cpu` | 1 | 0 | 1 |
| `aruba-container` | `aruba-container:containers.instance.runtime-constraints.memory` | 1 | 0 | 1 |
| `aruba-container` | `aruba-container:containers.instance.vrfs` | 1 | 0 | 1 |
| `aruba-dsm` | `aruba-dsm:dsm.dsm-instance.uplink-to-uplink` | 1 | 0 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.macsec.enable` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.cable-length` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv6-monitor` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.headroom` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.priority` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.xon-delta` | 0 | 1 | 1 |
| `aruba-interface-ethernet` | `aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.forbidden-vlan-list` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.ipfix-flow-monitor-in.ipv6-monitor` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.pim-dense.enable` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.pim6-dense.enable` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.qos.cos` | 0 | 1 | 1 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.igmp.enable` | 0 | 1 | 1 |
| `aruba-ipfix-flow-record` | `aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-queue` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.responder-sessions.responder-name` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.responder-sessions.responder-port` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.responder-sessions.responder-source.interface-vlan` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.responder-sessions.responder-type` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.http.request-type` | 1 | 0 | 1 |
| `aruba-ipsla` | `aruba-ipsla:ipsla.profile.source-sessions.http.url` | 1 | 0 | 1 |
| `aruba-lldp` | `aruba-lldp:lldp.profile.transmit-delay` | 1 | 0 | 1 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.application-id` | 1 | 0 | 1 |
| `aruba-macsec` | `aruba-macsec:macsec.policy.include-sci-enable` | 0 | 1 | 1 |
| `aruba-mirror-endpoint` | `aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.vrf` | 1 | 0 | 1 |
| `aruba-multicast` | `aruba-multicast:multicast-global.profile.multi-fabric-border-ipv4` | 1 | 0 | 1 |
| `aruba-multicast` | `aruba-multicast:multicast-global.profile.multipath-hash-ipv4` | 1 | 0 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.facility` | 1 | 0 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.operand` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.operator` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.set-monitor` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.conditions.severity` | 1 | 0 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.disable` | 1 | 0 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.monitors.dur-unit` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.monitors.duration` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.monitors.group-by` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.monitors.monitor-name` | 0 | 1 | 1 |
| `aruba-nae-lite` | `aruba-nae-lite:nae-lite.profile.monitors.vsf-member` | 0 | 1 | 1 |
| `aruba-nd-snooping-interface` | `aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.max-bindings` | 1 | 0 | 1 |
| `aruba-ptp` | `aruba-ptp:ptp.profile.protocol-profiles.domain` | 0 | 1 | 1 |
| `aruba-rip` | `aruba-rip:rip.profile.router.ether-interfaces.address-family` | 0 | 1 | 1 |
| `aruba-rip` | `aruba-rip:rip.profile.router.ether-interfaces.interface-name` | 0 | 1 | 1 |
| `aruba-rip` | `aruba-rip:rip.profile.router.ether-interfaces.interface-name-address-family` | 0 | 1 | 1 |
| `aruba-rip` | `aruba-rip:rip.profile.router.ether-interfaces.ip-address` | 0 | 1 | 1 |
| `aruba-rip` | `aruba-rip:rip.router.distance` | 1 | 0 | 1 |
| `aruba-switch-chassis` | `aruba-switch-chassis:switch-chassis.chassis.line-modules.power-priority` | 1 | 0 | 1 |
| `aruba-traffic-insight` | `aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.source-port` | 0 | 1 | 1 |
| `aruba-advanced-intelligent-forwarding` | `aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-ageout-time` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.client-limit-max` | 0 | 1 | 1 |
| `aruba-interface-portchannel` | `aruba-interface-portchannel:portchannels.interface.pim-sparse.source-address-any` | 0 | 1 | 1 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.arp.timeout` | 0 | 1 | 1 |
| `aruba-interface-subinterface` | `aruba-interface-subinterface:sub-interfaces.interface.policy.ipv4-access-list-in` | 0 | 1 | 1 |
| `aruba-interface-tunnel` | `aruba-interface-tunnel:tunnel.interface.ttl.value` | 0 | 1 | 1 |
| `aruba-interface-vxlan-tunnel` | `aruba-interface-vxlan-tunnel:vxlan-tunnel.profile.loop-protect` | 0 | 1 | 1 |
| `aruba-ip-lockdown-interface` | `aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.ip-source-lockdown.ipv6` | 0 | 1 | 1 |
| `aruba-nd-snooping` | `aruba-nd-snooping:nd-snooping.profile.mac-check` | 0 | 1 | 1 |
| `aruba-smartlink` | `aruba-smartlink:smartlink.profile.group.primary-portchannel-port` | 0 | 1 | 1 |
| `aruba-vlan-range` | `aruba-vlan-range:layer2-vlan-range.dhcpv6-snooping.allow-bindings-on-trusted-ports` | 0 | 1 | 1 |

---
*Report generated by automated analysis script*
