# PLM Leaf CNXUI Analysis Report

## Executive Summary

This report analyzes the PLM leaf entries from `Consolidated_PLM_Leaf_list.xlsx` to identify:
1. Leafs present in CNXUI
2. Leafs NOT present in CNXUI and their customer usage

## Summary Statistics

| Metric | Count |
|--------|-------|
| **Total Leaf Entries** | 2707 |
| **Leafs Present in UI** | 1328 |
| **Leafs NOT Present in UI** | 1379 |
| **Leafs NOT in UI - With Customer Usage** | 1367 |
| **Leafs NOT in UI - Without Customer Usage** | 12 |

## Customer Usage Breakdown for Leafs NOT in UI

| Category | Count |
|----------|-------|
| Leafs with Big Cluster customers | 1101 |
| Leafs with Small Cluster customers | 1110 |
| Leafs with customers in both clusters | 844 |
| Leafs with NO customers | 12 |

---

## Detailed Analysis: Leafs NOT Present in UI

### Top 50 Most Used Leafs (by Total Customer Count)

These leafs are NOT in the UI but have significant customer usage:

| Yang Name | Leaf Name | Big Cluster Customers | Small Cluster Customers | Total Customers |
|-----------|-----------|----------------------|------------------------|-----------------|
| aruba-management-user | aruba-management-user:management-users.user.ciphertext-password | 8719 | 4510 | 13229 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.kex-algorithms.algorithm | 3916 | 2403 | 6319 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.kex-algorithms.priority | 3916 | 2403 | 6319 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv4.address | 3748 | 89 | 3837 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.client-ip-tracker-enable | 2168 | 1190 | 3358 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv6.addresses.address | 2757 | 3 | 2760 |
| aruba-named-condition | aruba-named-condition:named-conditions.named-condition.condition-rule.position | 2372 | 353 | 2725 |
| aruba-named-condition | aruba-named-condition:named-conditions.named-condition.name | 2372 | 353 | 2725 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.access-type | 2301 | 399 | 2700 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.record-type | 2301 | 399 | 2700 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.acct-instances.accounting-method | 2299 | 399 | 2698 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.acct-instances.seq-id | 2299 | 399 | 2698 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.acct-instances.mgmt-server-group | 2193 | 355 | 2548 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.shared-secret-config.ciphertext-value | 2505 | 0 | 2505 |
| aruba-snmp | aruba-snmp:snmp.profile.user.auth-pass-text | 1771 | 586 | 2357 |
| aruba-snmp | aruba-snmp:snmp.profile.user.auth-pass-cypher | 1613 | 571 | 2184 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.access-type | 1885 | 296 | 2181 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.authz-instances.authorization-method | 1881 | 294 | 2175 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.authz-instances.seq-id | 1881 | 294 | 2175 |
| aruba-snmp | aruba-snmp:snmp.profile.user.priv-pass-cypher | 1564 | 549 | 2113 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.enable | 2000 | 76 | 2076 |
| aruba-loop-protect | aruba-loop-protect:loop-protect.profile.name | 1622 | 369 | 1991 |
| aruba-switch-profiles | aruba-switch-profiles:switch-profiles.profile.name | 1161 | 705 | 1866 |
| aruba-switch-profiles | aruba-switch-profiles:switch-profiles.profile.selected | 1161 | 705 | 1866 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.dscp | 1839 | 0 | 1839 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.name | 1839 | 0 | 1839 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.client-event-log-enable | 701 | 995 | 1696 |
| aruba-client-insight | aruba-client-insight:client-insight.profile.name | 683 | 986 | 1669 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.local-priority | 1661 | 0 | 1661 |
| aruba-client-insight | aruba-client-insight:client-insight.profile.onboarding-event-log | 659 | 974 | 1633 |
| aruba-logging | aruba-logging:logging.profile.module.process | 1145 | 482 | 1627 |
| aruba-logging | aruba-logging:logging.profile.module.subcategory | 1145 | 482 | 1627 |
| aruba-logging | aruba-logging:logging.profile.module.type | 1145 | 482 | 1627 |
| aruba-logging | aruba-logging:logging.profile.module.type-process-subcategory | 1145 | 482 | 1627 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.accounting-mode | 1191 | 408 | 1599 |
| aruba-loop-protect | aruba-loop-protect:loop-protect.profile.re-enable-timer | 1264 | 300 | 1564 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.acct-server-group | 1163 | 392 | 1555 |
| aruba-snmp | aruba-snmp:snmp.profile.community.policy-ipv4 | 1432 | 97 | 1529 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.color | 1512 | 0 | 1512 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.name | 866 | 513 | 1379 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-lag | 854 | 511 | 1365 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.allow-list.ipv4-allow-list | 1278 | 61 | 1339 |
| aruba-qos | aruba-qos:global-qos.trust | 1327 | 0 | 1327 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.interim-update-enable | 984 | 340 | 1324 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.allow-list.allow-list-enable | 1270 | 50 | 1320 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.igmp.snooping | 958 | 347 | 1305 |
| aruba-mirror | aruba-mirror:mirrors.profile.name | 836 | 464 | 1300 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-id | 836 | 464 | 1300 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.role | 774 | 492 | 1266 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.destination-type | 784 | 438 | 1222 |

---

### Leafs NOT in UI with ZERO Customer Usage

These leafs are not in the UI and have no customer usage (potential candidates for deprecation):

| Yang Name | Leaf Name | Big Cluster Customers | Small Cluster Customers |
|-----------|-----------|----------------------|------------------------|
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.lag-interfaces.ciphertext-password | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.priority | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.tunnel-interfaces.passive | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.tunnel-interfaces.priority | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.tunnel-interfaces.tunnel-id | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.default-information-origin.always-metric | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.graceful-restart-cfg.helper-strict-lsa-check | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.rfc1583-compatibility | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.ether-interfaces.dead-interval | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.ether-interfaces.hello-interval | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.svi-interfaces.dead-interval | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.svi-interfaces.hello-interval | 0 | 0 |

---

## Complete List: All Leafs NOT Present in UI (Sorted by Customer Usage)

| Yang Name | Leaf Name | Big Cluster Customers | Small Cluster Customers | Total Customers |
|-----------|-----------|----------------------|------------------------|-----------------|
| aruba-management-user | aruba-management-user:management-users.user.ciphertext-password | 8719 | 4510 | 13229 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.kex-algorithms.priority | 3916 | 2403 | 6319 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.kex-algorithms.algorithm | 3916 | 2403 | 6319 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv4.address | 3748 | 89 | 3837 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.client-ip-tracker-enable | 2168 | 1190 | 3358 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv6.addresses.address | 2757 | 3 | 2760 |
| aruba-named-condition | aruba-named-condition:named-conditions.named-condition.condition-rule.position | 2372 | 353 | 2725 |
| aruba-named-condition | aruba-named-condition:named-conditions.named-condition.name | 2372 | 353 | 2725 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.access-type | 2301 | 399 | 2700 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.record-type | 2301 | 399 | 2700 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.acct-instances.accounting-method | 2299 | 399 | 2698 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.acct-instances.seq-id | 2299 | 399 | 2698 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.accounting-group.acct-instances.mgmt-server-group | 2193 | 355 | 2548 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.shared-secret-config.ciphertext-value | 2505 | 0 | 2505 |
| aruba-snmp | aruba-snmp:snmp.profile.user.auth-pass-text | 1771 | 586 | 2357 |
| aruba-snmp | aruba-snmp:snmp.profile.user.auth-pass-cypher | 1613 | 571 | 2184 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.access-type | 1885 | 296 | 2181 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.authz-instances.authorization-method | 1881 | 294 | 2175 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.authz-instances.seq-id | 1881 | 294 | 2175 |
| aruba-snmp | aruba-snmp:snmp.profile.user.priv-pass-cypher | 1564 | 549 | 2113 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.enable | 2000 | 76 | 2076 |
| aruba-loop-protect | aruba-loop-protect:loop-protect.profile.name | 1622 | 369 | 1991 |
| aruba-switch-profiles | aruba-switch-profiles:switch-profiles.profile.selected | 1161 | 705 | 1866 |
| aruba-switch-profiles | aruba-switch-profiles:switch-profiles.profile.name | 1161 | 705 | 1866 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.dscp | 1839 | 0 | 1839 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.name | 1839 | 0 | 1839 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.client-event-log-enable | 701 | 995 | 1696 |
| aruba-client-insight | aruba-client-insight:client-insight.profile.name | 683 | 986 | 1669 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.local-priority | 1661 | 0 | 1661 |
| aruba-client-insight | aruba-client-insight:client-insight.profile.onboarding-event-log | 659 | 974 | 1633 |
| aruba-logging | aruba-logging:logging.profile.module.type | 1145 | 482 | 1627 |
| aruba-logging | aruba-logging:logging.profile.module.type-process-subcategory | 1145 | 482 | 1627 |
| aruba-logging | aruba-logging:logging.profile.module.subcategory | 1145 | 482 | 1627 |
| aruba-logging | aruba-logging:logging.profile.module.process | 1145 | 482 | 1627 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.accounting-mode | 1191 | 408 | 1599 |
| aruba-loop-protect | aruba-loop-protect:loop-protect.profile.re-enable-timer | 1264 | 300 | 1564 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.acct-server-group | 1163 | 392 | 1555 |
| aruba-snmp | aruba-snmp:snmp.profile.community.policy-ipv4 | 1432 | 97 | 1529 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.color | 1512 | 0 | 1512 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.name | 866 | 513 | 1379 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-lag | 854 | 511 | 1365 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.allow-list.ipv4-allow-list | 1278 | 61 | 1339 |
| aruba-qos | aruba-qos:global-qos.trust | 1327 | 0 | 1327 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.interim-update-enable | 984 | 340 | 1324 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.allow-list.allow-list-enable | 1270 | 50 | 1320 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.igmp.snooping | 958 | 347 | 1305 |
| aruba-mirror | aruba-mirror:mirrors.profile.name | 836 | 464 | 1300 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-id | 836 | 464 | 1300 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.role | 774 | 492 | 1266 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.destination-type | 784 | 438 | 1222 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.system-mac | 704 | 425 | 1129 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.name | 833 | 256 | 1089 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.dhcpv4-snooping.enable | 781 | 294 | 1075 |
| aruba-loop-protect | aruba-loop-protect:loop-protect.profile.trap | 933 | 137 | 1070 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.loop-protect.trap | 933 | 136 | 1069 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.enable | 676 | 376 | 1052 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.name | 506 | 520 | 1026 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.interim-update-interval | 777 | 244 | 1021 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.dhcp-default | 490 | 508 | 998 |
| aruba-client-insight | aruba-client-insight:client-insight.profile.enable | 0 | 986 | 986 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.http-parameters | 455 | 501 | 956 |
| aruba-remote-management | aruba-remote-management:remote-management.profile.name | 733 | 222 | 955 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.chassis-name | 793 | 156 | 949 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.line-modules.line-module-name | 793 | 156 | 949 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.keepalive.source-ip | 594 | 350 | 944 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.keepalive.vrf-ref | 594 | 350 | 944 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.keepalive.peer-ip | 594 | 350 | 944 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.source.subnet-address.network-subnet-address | 580 | 354 | 934 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.eth-interfaces.eth-interface | 587 | 336 | 923 |
| aruba-dhcp-pool | aruba-dhcp-pool:dhcp-pool.profile.ipv4-pool.v4pool-name | 442 | 421 | 863 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.lldp-tlv-names | 372 | 488 | 860 |
| aruba-hardware-module-profile | aruba-hardware-module-profile:hardware-modules.hw-profile.name | 523 | 321 | 844 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.cdp-tlv-names | 344 | 484 | 828 |
| aruba-hardware-module-profile | aruba-hardware-module-profile:hardware-modules.hw-profile.interface-group-speed-profile.group-id | 470 | 305 | 775 |
| aruba-hardware-module-profile | aruba-hardware-module-profile:hardware-modules.hw-profile.interface-group-speed-profile.speed | 468 | 305 | 773 |
| aruba-remote-management | aruba-remote-management:remote-management.profile.central-location | 560 | 204 | 764 |
| aruba-remote-management | aruba-remote-management:remote-management.profile.central-location-vrf | 556 | 203 | 759 |
| aruba-ntp | aruba-ntp:ntp.profile.servers.version | 598 | 144 | 742 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.name | 0 | 737 | 737 |
| aruba-snmp | aruba-snmp:snmp.profile.user.access-level | 546 | 163 | 709 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.cppm-password-config.ciphertext-value | 535 | 137 | 672 |
| aruba-snmp | aruba-snmp:snmp.profile.enable-snmpv3-only | 485 | 156 | 641 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.destination.subnet-address.network-subnet-address | 341 | 296 | 637 |
| aruba-local-management | aruba-local-management:local-management.profile.banner-exec.message-delimiter | 446 | 189 | 635 |
| aruba-local-management | aruba-local-management:local-management.profile.banner-exec.text | 446 | 189 | 635 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.authorization-group.authz-instances.mgmt-server-group | 431 | 201 | 632 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-sources.eth-interfaces.direction | 296 | 325 | 621 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-sources.eth-interfaces.eth-interface | 296 | 325 | 621 |
| aruba-role | aruba-role:roles.role.policies.name | 419 | 179 | 598 |
| aruba-ip-icmp-tcp | aruba-ip-icmp-tcp:ip-icmp-tcp.profile.name | 555 | 0 | 555 |
| aruba-vrf | aruba-vrf:vrfs.vrf.ipv4-access-list | 353 | 183 | 536 |
| aruba-snmp | aruba-snmp:snmp.profile.community.access-level | 316 | 215 | 531 |
| aruba-ip-icmp-tcp | aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.redirect | 530 | 0 | 530 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv4-relay.server.ip | 518 | 2 | 520 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv4-relay.server.ip-vrf | 518 | 2 | 520 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv4-relay.server.vrf | 518 | 2 | 520 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.dscp-map.dscp | 0 | 511 | 511 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.dscp-map.priority | 0 | 511 | 511 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.line-modules.sku | 313 | 155 | 468 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.platform | 313 | 155 | 468 |
| aruba-device-profile | aruba-device-profile:device-profile.profile.lldp-group-entries.vendor-oui-subtype.value | 356 | 108 | 464 |
| aruba-auth-server-global | aruba-auth-server-global:auth-server-global-config.profile.shared-secret-config.ciphertext-value | 317 | 145 | 462 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-trap-source.vrf | 289 | 139 | 428 |
| aruba-port-security | aruba-port-security:port-security.policy.name | 256 | 167 | 423 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.dscp-map.color | 0 | 415 | 415 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.igmp.version | 281 | 120 | 401 |
| aruba-snmp-trap | aruba-snmp-trap:snmp-trap.profile.name | 202 | 198 | 400 |
| aruba-snmp-trap | aruba-snmp-trap:snmp-trap.profile.trap.id | 201 | 198 | 399 |
| aruba-sflow | aruba-sflow:sflow.profile.name | 247 | 148 | 395 |
| aruba-sflow | aruba-sflow:sflow.profile.session.session-id | 247 | 148 | 395 |
| aruba-dns | aruba-dns:dns.profile.static-host.vrf | 306 | 86 | 392 |
| aruba-dns | aruba-dns:dns.profile.static-host.host-ip.host-ip | 306 | 86 | 392 |
| aruba-dns | aruba-dns:dns.profile.static-host.host-ip.hostname | 306 | 86 | 392 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-profile-name | 253 | 136 | 389 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.policy.ipv4-access-list-in | 177 | 201 | 378 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.trust | 0 | 371 | 371 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.trust | 0 | 371 | 371 |
| aruba-qos-queue | aruba-qos-queue:qos-queues.profile.q-profile-name | 232 | 129 | 361 |
| aruba-sflow | aruba-sflow:sflow.profile.session.collector.col-name | 229 | 132 | 361 |
| aruba-sflow | aruba-sflow:sflow.profile.session.collector.ip-address | 229 | 132 | 361 |
| aruba-logging | aruba-logging:logging.profile.remote-syslog.transport | 246 | 113 | 359 |
| aruba-logging | aruba-logging:logging.profile.console.enable | 200 | 149 | 349 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.name | 235 | 114 | 349 |
| aruba-logging | aruba-logging:logging.profile.facility | 222 | 125 | 347 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-sources.lag-interfaces.direction | 215 | 131 | 346 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-sources.lag-interfaces.lag-interface | 215 | 131 | 346 |
| aruba-lldp | aruba-lldp:lldp.profile.name | 236 | 109 | 345 |
| aruba-qos-queue | aruba-qos-queue:qos-queues.profile.priority.queue | 223 | 120 | 343 |
| aruba-port-security | aruba-port-security:port-security.policy.enable | 197 | 138 | 335 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.sflow.enable | 198 | 123 | 321 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.app-usage | 208 | 101 | 309 |
| aruba-sflow | aruba-sflow:sflow.profile.session.agent-address | 186 | 119 | 305 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.voice-enable | 301 | 0 | 301 |
| aruba-snmp-trap | aruba-snmp-trap:snmp-trap.profile.trap.enable | 164 | 133 | 297 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.name | 194 | 85 | 279 |
| aruba-cdp | aruba-cdp:cdp.profile.enable | 182 | 95 | 277 |
| aruba-cdp | aruba-cdp:cdp.profile.name | 182 | 95 | 277 |
| aruba-port-security | aruba-port-security:port-security.policy.client-limit | 185 | 91 | 276 |
| aruba-snmp | aruba-snmp:snmp.profile.context.context-name | 216 | 57 | 273 |
| aruba-snmp | aruba-snmp:snmp.profile.context.vrf | 216 | 57 | 273 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.transport-fields.source-port.operator | 158 | 114 | 272 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-response-source.vrf | 189 | 83 | 272 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.transport-fields.source-port.min | 156 | 113 | 269 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.name | 258 | 0 | 258 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.job-name | 176 | 82 | 258 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.ciphers.algorithm | 168 | 90 | 258 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.ciphers.priority | 168 | 90 | 258 |
| aruba-local-management | aruba-local-management:local-management.profile.max-sessions-per-user | 153 | 103 | 256 |
| aruba-aaa-profile | aruba-aaa-profile:aaa-profile.profile.authentication.auth-priority | 184 | 64 | 248 |
| aruba-qos-queue | aruba-qos-queue:qos-queues.profile.priority.name | 168 | 79 | 247 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.auth-priority | 184 | 62 | 246 |
| aruba-role | aruba-role:roles.role.vlan-parameters.access-vlan-name | 179 | 64 | 243 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.comment | 173 | 69 | 242 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.linkup-delay-timer | 138 | 102 | 240 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-sources.vlans.direction | 159 | 79 | 238 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-sources.vlans.vlan-id | 159 | 79 | 238 |
| aruba-snmp-trap | aruba-snmp-trap:snmp-trap.profile.trap.snmp-server-trap | 102 | 130 | 232 |
| aruba-snmp-trap | aruba-snmp-trap:snmp-trap.profile.trap.vrf | 102 | 130 | 232 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.strict.queue | 230 | 0 | 230 |
| aruba-loop-protect | aruba-loop-protect:loop-protect.profile.transmit-interval | 145 | 77 | 222 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-trap-source.vlan-interface | 160 | 60 | 220 |
| aruba-qos | aruba-qos:global-qos.q-profile | 217 | 0 | 217 |
| aruba-qos | aruba-qos:global-qos.sched-profile | 217 | 0 | 217 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.flow-control-mode | 139 | 77 | 216 |
| aruba-dhcp-snooping | aruba-dhcp-snooping:dhcp-snooping.profile.ipv4.allow-overwrite-binding | 145 | 71 | 216 |
| aruba-named-condition | aruba-named-condition:named-conditions.named-condition.condition-rule.description | 172 | 44 | 216 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.entry.sequence-number | 136 | 75 | 211 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-trap-source.source-ipv4 | 132 | 79 | 211 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.entry.cli-command | 135 | 75 | 210 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.entry.type | 135 | 75 | 210 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.direction | 133 | 74 | 207 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.flow-control-mode | 133 | 74 | 207 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.llfc-flow-control.direction | 133 | 74 | 207 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.port-access-keepalive | 126 | 77 | 203 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.dwrr.weight | 201 | 0 | 201 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.dwrr.queue | 201 | 0 | 201 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.poe.assigned-class | 143 | 50 | 193 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.ipv4-access-list-in | 114 | 77 | 191 |
| aruba-snmp | aruba-snmp:snmp.profile.context.community | 132 | 57 | 189 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.trigger-type | 117 | 68 | 185 |
| aruba-qos-queue | aruba-qos-queue:qos-queues.profile.priority.local-priority | 182 | 0 | 182 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.name | 129 | 52 | 181 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.schedule-entry.schedule-job | 113 | 67 | 180 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.schedule-entry.sequence-number | 113 | 67 | 180 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.macs.algorithm | 102 | 77 | 179 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.macs.priority | 102 | 77 | 179 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv6.autoconfig | 176 | 0 | 176 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.vni.id | 124 | 51 | 175 |
| aruba-bgp | aruba-bgp:bgp.profile.router.log-neighbor-state-changes | 113 | 59 | 172 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.cdp-default | 145 | 27 | 172 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.enable | 121 | 51 | 172 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.internal-vlan-range | 98 | 73 | 171 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.max-auth-attempts | 99 | 69 | 168 |
| aruba-management-user | aruba-management-user:management-users.user.authorized-key.public-key | 104 | 62 | 166 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.src-ipv4 | 114 | 51 | 165 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-response-source.source-ipv4 | 114 | 50 | 164 |
| aruba-sflow | aruba-sflow:sflow.profile.session.collector.udp-port | 102 | 61 | 163 |
| aruba-auth-server-global | aruba-auth-server-global:auth-server-global-config.profile.tracking-password-config.ciphertext-value | 132 | 31 | 163 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.vni.vlan | 112 | 48 | 160 |
| aruba-local-management | aruba-local-management:local-management.profile.webservers.session-timeout | 94 | 66 | 160 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.lldp-default | 130 | 28 | 158 |
| aruba-port-security | aruba-port-security:port-security.policy.sticky-mac-enable | 89 | 68 | 157 |
| aruba-logging | aruba-logging:logging.profile.remote-syslog.include-auditable-events | 106 | 51 | 157 |
| aruba-object-group | aruba-object-group:object-groups.group.name | 108 | 48 | 156 |
| aruba-object-group | aruba-object-group:object-groups.group.type | 108 | 48 | 156 |
| aruba-object-group | aruba-object-group:object-groups.group.items.index | 107 | 48 | 155 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ip.l3-counters | 106 | 47 | 153 |
| aruba-sflow | aruba-sflow:sflow.profile.session.polling-interval | 93 | 55 | 148 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.host-key-algorithms.priority | 84 | 60 | 144 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.host-key-algorithms.algorithm | 84 | 60 | 144 |
| aruba-object-group | aruba-object-group:object-groups.group.items.address-type | 99 | 42 | 141 |
| aruba-sflow | aruba-sflow:sflow.profile.session.mode | 96 | 43 | 139 |
| aruba-local-management | aruba-local-management:local-management.profile.console.baud-rate | 105 | 33 | 138 |
| aruba-role-gpid | aruba-role-gpid:role-gpids.role-gpid.gpid | 98 | 34 | 132 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.algorithm | 0 | 131 | 131 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.queue | 0 | 131 | 131 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.window-duration | 102 | 24 | 126 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.dhcpv6-snooping.enable | 85 | 39 | 124 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.dot1x-auth.eap-tls-fragment-size-towards-server | 100 | 23 | 123 |
| aruba-management-user | aruba-management-user:management-users.user.interface.telnet | 55 | 68 | 123 |
| aruba-local-management | aruba-local-management:local-management.profile.webservers.access-mode | 83 | 39 | 122 |
| aruba-local-management | aruba-local-management:local-management.profile.console.serviceos-password-prompt | 83 | 38 | 121 |
| aruba-object-group | aruba-object-group:object-groups.group.items.ipv4-address | 85 | 35 | 120 |
| aruba-qos-queue | aruba-qos-queue:qos-queues.profile.priority.priorities | 0 | 120 | 120 |
| aruba-logging | aruba-logging:logging.profile.filter.lf-name | 78 | 42 | 120 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.q-profile | 0 | 119 | 119 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.sched-profile | 0 | 119 | 119 |
| aruba-sflow | aruba-sflow:sflow.profile.session.sampling-rate | 77 | 40 | 117 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.pubkey-algorithms.algorithm | 62 | 51 | 113 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.pubkey-algorithms.priority | 62 | 51 | 113 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.policy.ipv4-access-list-out | 47 | 65 | 112 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.source.address-group | 73 | 37 | 110 |
| aruba-snmp | aruba-snmp:snmp.profile.user.context | 93 | 17 | 110 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.weight | 0 | 109 | 109 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.destination-ip | 66 | 42 | 108 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.source-ip | 66 | 42 | 108 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-broadcasts.threshold-units | 64 | 42 | 106 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.trigger-at | 82 | 23 | 105 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.lacp-lag.fallback | 0 | 105 | 105 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.start-time-at | 82 | 23 | 105 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.start-date-at | 82 | 23 | 105 |
| aruba-dns | aruba-dns:dns.profile.domain-list.name | 71 | 33 | 104 |
| aruba-dns | aruba-dns:dns.profile.domain-list.vrf | 71 | 33 | 104 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.vni.symmetric-routing | 79 | 24 | 103 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.vni.vrf | 79 | 24 | 103 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv4-access-list-in | 57 | 46 | 103 |
| aruba-firmware-management | aruba-firmware-management:device-firmware.site-distribution | 53 | 50 | 103 |
| aruba-object-group | aruba-object-group:object-groups.group.items.ipv4-subnet-address | 73 | 29 | 102 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-response-source.vlan-interface | 71 | 30 | 101 |
| aruba-role | aruba-role:roles.role.session-parameters.device-traffic-class | 69 | 32 | 101 |
| aruba-local-management | aruba-local-management:local-management.profile.telnet-server.vrf | 51 | 50 | 101 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.cos | 101 | 0 | 101 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-l2vpn-evpn.redistribute.route-type | 72 | 29 | 101 |
| aruba-logging | aruba-logging:logging.profile.filter.entry.action | 63 | 37 | 100 |
| aruba-logging | aruba-logging:logging.profile.filter.entry.sequence-number | 63 | 37 | 100 |
| aruba-snmp | aruba-snmp:snmp.profile.auth-security-level | 73 | 24 | 97 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.private-vlan-type | 78 | 18 | 96 |
| aruba-lldp | aruba-lldp:lldp.profile.disable | 70 | 25 | 95 |
| aruba-snmp | aruba-snmp:snmp.profile.view.view-name-oid-tree-mask | 57 | 37 | 94 |
| aruba-snmp | aruba-snmp:snmp.profile.view.oid-tree | 57 | 37 | 94 |
| aruba-snmp | aruba-snmp:snmp.profile.view.type | 57 | 37 | 94 |
| aruba-snmp | aruba-snmp:snmp.profile.view.view-name | 57 | 37 | 94 |
| aruba-snmp | aruba-snmp:snmp.profile.view.mask | 57 | 37 | 94 |
| aruba-copp | aruba-copp:copp.profile.name | 60 | 34 | 94 |
| aruba-hardware-module-profile | aruba-hardware-module-profile:hardware-modules.hw-profile.member-or-slot-ids | 0 | 94 | 94 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject.common-name | 66 | 27 | 93 |
| aruba-dhcp-snooping-interface | aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.name | 77 | 15 | 92 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.interim-update-onreauth-enable | 72 | 20 | 92 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.destination.address-group | 65 | 26 | 91 |
| aruba-dhcp-snooping-interface | aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv4-snooping.trust | 75 | 15 | 90 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.dscp-map.name | 0 | 88 | 88 |
| aruba-role | aruba-role:roles.role.vlan-parameters.trunk-allowed-vlan-names | 63 | 25 | 88 |
| aruba-switch-stack | aruba-switch-stack:stacks.stack.members.hw-profile | 88 | 0 | 88 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.description | 53 | 34 | 87 |
| aruba-copp | aruba-copp:copp.profile.copp-policy.configured-copp-policy-entries.priority | 55 | 32 | 87 |
| aruba-copp | aruba-copp:copp.profile.copp-policy.configured-copp-policy-entries.class | 55 | 32 | 87 |
| aruba-ip-icmp-tcp | aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.unreachable | 82 | 0 | 82 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.enable | 31 | 51 | 82 |
| aruba-vrf | aruba-vrf:vrfs.vrf.ipv6-access-list | 80 | 1 | 81 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.fast-leave-vlan | 57 | 23 | 80 |
| aruba-nexthop-group | aruba-nexthop-group:nexthop-groups.group.name | 43 | 37 | 80 |
| aruba-lldp | aruba-lldp:lldp.profile.management-ip-address | 51 | 28 | 79 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.failthrough | 36 | 42 | 78 |
| aruba-nexthop-group | aruba-nexthop-group:nexthop-groups.group.nexthops.type | 41 | 37 | 78 |
| aruba-nexthop-group | aruba-nexthop-group:nexthop-groups.group.nexthops.ip | 41 | 37 | 78 |
| aruba-nexthop-group | aruba-nexthop-group:nexthop-groups.group.nexthops.index | 41 | 37 | 78 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.replay-protection | 69 | 9 | 78 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.default | 75 | 3 | 78 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.advertise | 75 | 2 | 77 |
| aruba-logging | aruba-logging:logging.profile.filter.enable | 47 | 30 | 77 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.name | 38 | 39 | 77 |
| aruba-ipfix-flow-monitor | aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.name | 36 | 40 | 76 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.minimum-length | 32 | 44 | 76 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.transport-source-port | 35 | 40 | 75 |
| aruba-logging | aruba-logging:logging.profile.module.severity | 54 | 21 | 75 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-version | 35 | 40 | 75 |
| aruba-ipfix-flow-monitor | aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.exporter.exporter-name | 35 | 40 | 75 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.name | 35 | 40 | 75 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-source-address | 35 | 40 | 75 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.transport-destination-port | 35 | 40 | 75 |
| aruba-ipfix-flow-monitor | aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.record | 35 | 40 | 75 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.poe.pd-class-override | 55 | 20 | 75 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.counter-bytes | 35 | 40 | 75 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.counter-packets | 35 | 39 | 74 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.private-vlan-association | 60 | 14 | 74 |
| aruba-logging | aruba-logging:logging.profile.filter.entry.event-id-range | 47 | 27 | 74 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-protocol | 35 | 39 | 74 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv4-destination-address | 35 | 39 | 74 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.hashing | 45 | 28 | 73 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.cached-critical-role.cache-replace-mode | 61 | 12 | 73 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.name | 39 | 33 | 72 |
| aruba-lacp | aruba-lacp:lacp.hash | 67 | 5 | 72 |
| aruba-role | aruba-role:roles.role.vlan-parameters.trunk-native-vlan-name | 58 | 14 | 72 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.fastboot | 61 | 11 | 72 |
| aruba-ip-lockdown | aruba-ip-lockdown:ip-source-lockdown.profile.ip-source-lockdown-resource-extended | 43 | 28 | 71 |
| aruba-ip-lockdown | aruba-ip-lockdown:ip-source-lockdown.profile.name | 43 | 28 | 71 |
| aruba-ntp | aruba-ntp:ntp.profile.authenticate | 38 | 32 | 70 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.sflow.enable | 56 | 14 | 70 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-broadcasts.threshold-percent | 41 | 27 | 68 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.frequency | 31 | 36 | 67 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.start-time-on | 31 | 36 | 67 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.trigger-on | 31 | 36 | 67 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.description | 41 | 26 | 67 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.timestamp-absolute-first | 29 | 38 | 67 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.dhcp-options-list | 46 | 20 | 66 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.timestamp-absolute-last | 27 | 38 | 65 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.enable | 35 | 30 | 65 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lldp.trap | 38 | 26 | 64 |
| aruba-lldp | aruba-lldp:lldp.profile.lldp-trap-enable | 38 | 26 | 64 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-multicasts.threshold-units | 41 | 22 | 63 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.start-date-on | 29 | 33 | 62 |
| aruba-ntp | aruba-ntp:ntp.profile.conductor.stratum | 44 | 18 | 62 |
| aruba-ntp | aruba-ntp:ntp.profile.conductor.vrf | 44 | 18 | 62 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.mac-age-time | 56 | 6 | 62 |
| aruba-hardware-module-profile | aruba-hardware-module-profile:hardware-modules.hw-profile.always-on-poe | 44 | 17 | 61 |
| aruba-local-management | aruba-local-management:local-management.profile.webservers.max-sessions-per-client | 31 | 30 | 61 |
| aruba-udp-broadcast-forwarder | aruba-udp-broadcast-forwarder:udp-broadcast-forwarders.profile.name | 51 | 9 | 60 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.gbp.enable | 46 | 14 | 60 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.transport-fields.source-port.max | 32 | 28 | 60 |
| aruba-udp-broadcast-forwarder | aruba-udp-broadcast-forwarder:udp-broadcast-forwarders.profile.enable | 51 | 9 | 60 |
| aruba-object-group | aruba-object-group:object-groups.group.items.ports.operator | 41 | 19 | 60 |
| aruba-copp | aruba-copp:copp.profile.copp-policy.applied | 38 | 20 | 58 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-name | 30 | 28 | 58 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv4-monitor | 27 | 30 | 57 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.min-bandwidths.minimum-bandwidth | 57 | 0 | 57 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.min-bandwidths.queue | 57 | 0 | 57 |
| aruba-interface-tunnel | aruba-interface-tunnel:tunnel.interface.vxlan.profile-name | 40 | 16 | 56 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.poe.power-pairs | 36 | 19 | 55 |
| aruba-qos-queue | aruba-qos-queue:qos-queues.profile.priority.cos | 55 | 0 | 55 |
| aruba-logging | aruba-logging:logging.profile.console.min-severity | 21 | 33 | 54 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.policy-in | 29 | 24 | 53 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.policy-in | 29 | 24 | 53 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.energy-efficient | 37 | 16 | 53 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject.org | 32 | 19 | 51 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.ep-name | 36 | 15 | 51 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.name | 36 | 15 | 51 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.accounting.local-accounting | 39 | 12 | 51 |
| aruba-aaa-profile | aruba-aaa-profile:aaa-profile.profile.authentication.mda-data-clients-limit | 33 | 17 | 50 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.mda-data-clients-limit | 33 | 16 | 49 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.local-collector | 24 | 25 | 49 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.collector-dest | 25 | 24 | 49 |
| aruba-remote-management | aruba-remote-management:remote-management.profile.central-enable | 34 | 15 | 49 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.md-cipherpassword | 0 | 48 | 48 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.name | 25 | 23 | 48 |
| aruba-object-group | aruba-object-group:object-groups.group.items.ports.min | 28 | 19 | 47 |
| aruba-keychain | aruba-keychain:keychains.keychain.name | 30 | 17 | 47 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.enable | 24 | 23 | 47 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.redistribute-routes.route-map | 0 | 47 | 47 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.transport-fields.destination-port.group | 33 | 14 | 47 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.source | 24 | 22 | 46 |
| aruba-snmp | aruba-snmp:snmp.profile.community.policy-ipv6 | 46 | 0 | 46 |
| aruba-mgmd | aruba-mgmd:mgmd-global.profile.igmp.fastlearn.eth-ports | 34 | 12 | 46 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.type | 23 | 23 | 46 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject.state | 27 | 19 | 46 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.monitor-name-type | 23 | 23 | 46 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.monitor-name | 23 | 23 | 46 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject.org-unit | 28 | 18 | 46 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject.locality | 29 | 16 | 45 |
| aruba-sflow | aruba-sflow:sflow.profile.session.collector.vrf | 34 | 11 | 45 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pvlan-port-mode | 36 | 8 | 44 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.name | 30 | 14 | 44 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.source-name | 30 | 14 | 44 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pvlan-port-mode | 36 | 8 | 44 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.name | 32 | 10 | 42 |
| aruba-lacp | aruba-lacp:lacp.system-priority | 23 | 19 | 42 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.description | 21 | 21 | 42 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.key-id | 24 | 17 | 41 |
| aruba-ipfix-flow-monitor | aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.cache-timeout-active | 22 | 19 | 41 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-broadcasts.threshold-rate | 25 | 15 | 40 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.basic.port-descr | 29 | 11 | 40 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.description | 19 | 21 | 40 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.interface.sub-interface | 28 | 12 | 40 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.ipv4-access-list-out | 24 | 15 | 39 |
| aruba-ntp | aruba-ntp:ntp.profile.authentication-profile.key-hash | 18 | 21 | 39 |
| aruba-ntp | aruba-ntp:ntp.profile.authentication-profile.key-identifier | 18 | 21 | 39 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-multicasts.threshold-percent | 25 | 14 | 39 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.auth-key-info.type | 23 | 16 | 39 |
| aruba-dhcp-relay | aruba-dhcp-relay:dhcp-relay.profile.ipv4.smart-relay | 24 | 15 | 39 |
| aruba-auth-server-global | aruba-auth-server-global:auth-server-global-config.profile.service-type-in-access-request | 27 | 12 | 39 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.auth-key-info.auth-key-ciphertext | 22 | 16 | 38 |
| aruba-psm | aruba-psm:psm.psm-instance.name | 27 | 11 | 38 |
| aruba-psm | aruba-psm:psm.psm-instance.psm-ips | 27 | 11 | 38 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.mac-notify-traps | 24 | 14 | 38 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.link-flap.threshold | 32 | 5 | 37 |
| aruba-ntp | aruba-ntp:ntp.profile.authentication-profile.ciphertext.key-value | 16 | 21 | 37 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-https-url | 19 | 17 | 36 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.type | 24 | 12 | 36 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.cdp.mode | 23 | 13 | 36 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mac-notify-traps | 24 | 12 | 36 |
| aruba-mvrp | aruba-mvrp:mvrp.profile.enable | 34 | 1 | 35 |
| aruba-mvrp | aruba-mvrp:mvrp.profile.name | 34 | 1 | 35 |
| aruba-ntp | aruba-ntp:ntp.profile.dhcp-disable | 18 | 17 | 35 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-dns-response-code | 19 | 15 | 34 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.destination-ipv4 | 22 | 12 | 34 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.querier-enable | 34 | 0 | 34 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.vrf | 14 | 20 | 34 |
| aruba-nd-snooping | aruba-nd-snooping:nd-snooping.profile.name | 21 | 13 | 34 |
| aruba-nd-snooping | aruba-nd-snooping:nd-snooping.profile.enable | 20 | 13 | 33 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.vrf | 23 | 10 | 33 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse.source-address-any | 18 | 14 | 32 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.ip | 13 | 19 | 32 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.description | 24 | 8 | 32 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.bfd.min-tx-interval | 16 | 16 | 32 |
| aruba-logging | aruba-logging:logging.profile.filter.entry.match-regex | 19 | 12 | 31 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.ip-header.icmp.icmp-type | 13 | 18 | 31 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.trap-enable | 0 | 31 | 31 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.hello-interval | 0 | 31 | 31 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.dead-interval | 0 | 31 | 31 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.port | 15 | 16 | 31 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.hold-time | 24 | 7 | 31 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.transport-protocol | 15 | 16 | 31 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.icmp.unreachable | 0 | 31 | 31 |
| aruba-hardware-module-profile | aruba-hardware-module-profile:hardware-modules.hw-profile.quick-poe | 26 | 5 | 31 |
| aruba-client-iptracker | aruba-client-iptracker:client-iptracker.profile.enable-probe | 27 | 4 | 31 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-tls-attributes | 16 | 14 | 30 |
| aruba-management-user | aruba-management-user:management-users.user.interface.console | 11 | 19 | 30 |
| aruba-logging | aruba-logging:logging.profile.console.log-type | 13 | 17 | 30 |
| aruba-track-object | aruba-track-object:tracking-object.vrrp.identifier | 10 | 20 | 30 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.arp.timeout | 19 | 11 | 30 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.week-day | 16 | 14 | 30 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.trigger-on-weekly | 16 | 14 | 30 |
| aruba-mac-lockout | aruba-mac-lockout:mac-lockout.profile.name | 22 | 8 | 30 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.enable | 18 | 11 | 29 |
| aruba-bgp | aruba-bgp:bgp.profile.router.route-selection-options.as-path-multipath-relax | 15 | 14 | 29 |
| aruba-bgp | aruba-bgp:bgp.profile.router.route-selection-options.deterministic-med | 14 | 15 | 29 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.poe-plus | 17 | 12 | 29 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.igmp.robustness | 21 | 8 | 29 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.lldp-tlv-numbers | 21 | 8 | 29 |
| aruba-local-management | aruba-local-management:local-management.profile.tracking-range | 10 | 19 | 29 |
| aruba-snmp | aruba-snmp:snmp.profile.user.view-name | 23 | 6 | 29 |
| aruba-switch-stack | aruba-switch-stack:stacks.stack.members.links.link1.description | 18 | 11 | 29 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.bfd.min-rx-interval | 16 | 12 | 28 |
| aruba-logging | aruba-logging:logging.profile.remote-syslog.filter-name | 19 | 9 | 28 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.nd-snooping.enable | 21 | 7 | 28 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.bridging-mode | 21 | 7 | 28 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.min-char-difference | 11 | 17 | 28 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.hello-interval | 21 | 7 | 28 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.udp-broadcast-forwarder-server.servers.port | 24 | 4 | 28 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.udp-broadcast-forwarder-server.servers.ip | 24 | 4 | 28 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.qos.schedule-profile | 17 | 11 | 28 |
| aruba-dhcp-client | aruba-dhcp-client:dhcp-client.profile.name | 17 | 11 | 28 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv4-access-list-out | 21 | 7 | 28 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.upload-template-interval | 13 | 14 | 27 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.policy.ipv4-access-list-in | 10 | 17 | 27 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ipv4.address | 14 | 13 | 27 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.mld.snooping | 18 | 9 | 27 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.hashing | 0 | 27 | 27 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.dead-interval | 18 | 9 | 27 |
| aruba-snmp | aruba-snmp:snmp.profile.auth-privacy-security-level | 18 | 9 | 27 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.bfd.detect-multiplier | 13 | 14 | 27 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.enable | 27 | 0 | 27 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ip-directed-broadcast-enable | 26 | 0 | 26 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-trap-source.loopback-interface | 16 | 10 | 26 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lacp.port-id | 14 | 12 | 26 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.tag | 16 | 10 | 26 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-sparse.enable | 25 | 1 | 26 |
| aruba-ipfix-flow-monitor | aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.description | 14 | 12 | 26 |
| aruba-mac-lockout | aruba-mac-lockout:mac-lockout.profile.address.mac | 20 | 6 | 26 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.sflow.enable | 20 | 6 | 26 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-multicasts.threshold-rate | 18 | 8 | 26 |
| aruba-bgp | aruba-bgp:bgp.profile.router.route-selection-options.always-compare-med | 15 | 11 | 26 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.source-ip | 16 | 9 | 25 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.version | 25 | 0 | 25 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.destinations.eth-interfaces | 16 | 9 | 25 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.tid | 16 | 9 | 25 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lacp.port-id | 14 | 11 | 25 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.destination-ip | 16 | 9 | 25 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.arp.proxy | 13 | 12 | 25 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.med-poe-priority-override | 17 | 8 | 25 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.trigger-every | 12 | 13 | 25 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.forward-vlan | 18 | 6 | 24 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv4-relay.bootp-gateway | 13 | 11 | 24 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.start-time-every | 12 | 12 | 24 |
| aruba-local-management | aruba-local-management:local-management.profile.accounting.failthrough | 10 | 14 | 24 |
| aruba-role | aruba-role:roles.role.vlan-parameters.private-vlan-port-type | 21 | 3 | 24 |
| aruba-dhcp-client | aruba-dhcp-client:dhcp-client.profile.ip.enable-hostname | 12 | 11 | 23 |
| aruba-ntp | aruba-ntp:ntp.profile.trusted-key | 8 | 15 | 23 |
| aruba-mka | aruba-mka:mka.policy.name | 17 | 6 | 23 |
| aruba-macsec | aruba-macsec:macsec.policy.name | 17 | 6 | 23 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.portfilter.eth-ports | 17 | 6 | 23 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-dense.source-address-any | 14 | 9 | 23 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.portfilter.lag-ports | 17 | 6 | 23 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.cert-key-type | 12 | 11 | 23 |
| aruba-object-group | aruba-object-group:object-groups.group.items.ports.max | 15 | 7 | 22 |
| aruba-management-user | aruba-management-user:management-users.user.interface.ssh | 6 | 16 | 22 |
| aruba-nexthop-group | aruba-nexthop-group:nexthop-groups.group.nexthops.default-host | 14 | 8 | 22 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6.autoconfig | 16 | 6 | 22 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6.enable-default-link-local | 11 | 11 | 22 |
| aruba-lldp | aruba-lldp:lldp.profile.transmit-interval | 15 | 7 | 22 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.local-as | 10 | 11 | 21 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.error-control | 12 | 9 | 21 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.description | 14 | 7 | 21 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.minimum-bandwidth | 0 | 21 | 21 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.start-date-every | 11 | 10 | 21 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.igmp.static-group | 17 | 4 | 21 |
| aruba-mka | aruba-mka:mka.policy.cak-info.ckn | 15 | 6 | 21 |
| aruba-mka | aruba-mka:mka.policy.cak-info.key-type | 15 | 6 | 21 |
| aruba-lldp | aruba-lldp:lldp.profile.reinit-delay | 17 | 4 | 21 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.peer-detect-interval | 17 | 4 | 21 |
| aruba-psm | aruba-psm:psm.psm-instance.vrf | 10 | 11 | 21 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.frequency | 13 | 8 | 21 |
| aruba-ntp | aruba-ntp:ntp.profile.servers.key-identifier | 11 | 10 | 21 |
| aruba-routemap | aruba-routemap:route-maps.route-map.route-map-entry.description | 16 | 4 | 20 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.enable | 12 | 8 | 20 |
| aruba-logging | aruba-logging:logging.profile.filter.entry.match-severity.match-severity-value | 14 | 6 | 20 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.dot1x-supp.enable | 15 | 5 | 20 |
| aruba-vrrp-interface | aruba-vrrp-interface:vrrp.profile.virtual-router.sec-address | 12 | 8 | 20 |
| aruba-lldp | aruba-lldp:lldp.profile.dcbx-enable | 11 | 9 | 20 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.arp.neighbor.address | 10 | 10 | 20 |
| aruba-logging | aruba-logging:logging.profile.filter.entry.match-severity.match-severity-key | 14 | 6 | 20 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.split-recovery-disable | 16 | 4 | 20 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.arp.neighbor.mac-address | 10 | 10 | 20 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.mac-notify-traps | 12 | 8 | 20 |
| aruba-mka | aruba-mka:mka.policy.cak-info.cak-ciphertext | 14 | 6 | 20 |
| aruba-static-mac | aruba-static-mac:static-macs.profile.static-mac.destination-port.l2-destination | 12 | 7 | 19 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.hello-interval | 0 | 19 | 19 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.dead-interval | 0 | 19 | 19 |
| aruba-static-mac | aruba-static-mac:static-macs.profile.static-mac.vlan | 12 | 7 | 19 |
| aruba-static-mac | aruba-static-mac:static-macs.profile.static-mac.mac-vlan | 12 | 7 | 19 |
| aruba-static-mac | aruba-static-mac:static-macs.profile.static-mac.mac | 12 | 7 | 19 |
| aruba-static-mac | aruba-static-mac:static-macs.profile.name | 12 | 7 | 19 |
| aruba-mgmd | aruba-mgmd:mgmd-global.profile.igmp.fastlearn.lag-ports | 13 | 6 | 19 |
| aruba-management-user | aruba-management-user:management-users.user.interface.https-server | 6 | 13 | 19 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.pubkey-authentication | 16 | 3 | 19 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.uppercase-count | 12 | 7 | 19 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.special-char-count | 11 | 8 | 19 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.enable | 7 | 12 | 19 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ip.l3-counters | 14 | 5 | 19 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.entry.cli-delay | 13 | 5 | 18 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.auto-vlan-enable | 13 | 5 | 18 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.lowercase-count | 12 | 6 | 18 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.history-count | 7 | 11 | 18 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.count | 8 | 10 | 18 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.enable-counters | 14 | 4 | 18 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.rsa-key-length | 7 | 11 | 18 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.crypto-algorithm | 11 | 7 | 18 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.ipfix-flow-monitor-in.ipv4-monitor | 7 | 11 | 18 |
| aruba-l3-route | aruba-l3-route:l3-route.profile.name | 15 | 3 | 18 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipv6.enable-default-link-local | 10 | 8 | 18 |
| aruba-macsec | aruba-macsec:macsec.policy.replay-window | 13 | 4 | 17 |
| aruba-switch-stack | aruba-switch-stack:stacks.stack.members.links.link2.description | 11 | 6 | 17 |
| aruba-snmp | aruba-snmp:snmp.profile.snmp-response-source.loopback-interface | 10 | 7 | 17 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.vrf | 10 | 7 | 17 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.forwarding-status | 7 | 10 | 17 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.allow-list.ipv6-allow-list | 6 | 11 | 17 |
| aruba-rip | aruba-rip:rip.router.vrf | 17 | 0 | 17 |
| aruba-mka | aruba-mka:mka.policy.key-server-priority | 12 | 5 | 17 |
| aruba-rip | aruba-rip:rip.router.proto-type | 17 | 0 | 17 |
| aruba-rip | aruba-rip:rip.router.instance-tag-vrf-proto-type | 17 | 0 | 17 |
| aruba-rip | aruba-rip:rip.router.instance-tag | 17 | 0 | 17 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.cdp-tlv-numbers | 12 | 5 | 17 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ip.mtu | 16 | 0 | 16 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.reject | 14 | 2 | 16 |
| aruba-ptp | aruba-ptp:ptp.profile.name | 11 | 5 | 16 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.udld.retries | 9 | 7 | 16 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.multicast-rate-limit.bit-rate | 0 | 16 | 16 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.profile | 11 | 5 | 16 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.enable | 14 | 2 | 16 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.server-port | 3 | 13 | 16 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.pvlan-port-mode | 10 | 6 | 16 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.policy.mac-access-list-in | 9 | 7 | 16 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.source-address-any | 16 | 0 | 16 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.enforcement-level | 11 | 5 | 16 |
| aruba-est | aruba-est:est-profiles.profile.ciphertext-password | 9 | 7 | 16 |
| aruba-logging | aruba-logging:logging.profile.console.filter-regex | 6 | 9 | 15 |
| aruba-config-checkpoint | aruba-config-checkpoint:config-checkpoint.profile.name | 12 | 3 | 15 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.ciphertext-password | 0 | 15 | 15 |
| aruba-local-management | aruba-local-management:local-management.profile.password-complexity.numeric-count | 9 | 6 | 15 |
| aruba-nd-snooping-interface | aruba-nd-snooping-interface:nd-snooping-interface.profile.name | 10 | 5 | 15 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.udld.retries | 8 | 7 | 15 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.trap | 7 | 8 | 15 |
| aruba-dhcp-snooping | aruba-dhcp-snooping:dhcp-snooping.profile.ipv4.flash-storage.flash-storage-enable | 14 | 1 | 15 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-l2vpn-evpn.network.prefix | 9 | 6 | 15 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.timeout | 6 | 8 | 14 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.port-security.traps-enable | 10 | 4 | 14 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.udld.interval | 9 | 5 | 14 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.source.ipv4-address | 6 | 8 | 14 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.inter-switch-link.interface-eth | 10 | 4 | 14 |
| aruba-logging | aruba-logging:logging.profile.local-file.rotation.maxsize | 3 | 11 | 14 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.trust | 9 | 5 | 14 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.days | 4 | 10 | 14 |
| aruba-nd-snooping-interface | aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.trust | 9 | 5 | 14 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.policy.ipv4-access-list-out | 9 | 5 | 14 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.med.poe | 8 | 6 | 14 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.est-profile | 8 | 6 | 14 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-crc-errors.threshold | 14 | 0 | 14 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-ipv4-unicast.redistribute.ospfv2-id | 6 | 8 | 14 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.delay-mechanism | 9 | 4 | 13 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.query-interval | 13 | 0 | 13 |
| aruba-snmp | aruba-snmp:snmp.profile.unique-req-id-enable | 6 | 7 | 13 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.transport-fields.source-port.group | 9 | 4 | 13 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.lag-interfaces.lag-interface | 8 | 5 | 13 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.thresh-profile-name | 5 | 8 | 13 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.transport | 8 | 5 | 13 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.mode | 9 | 4 | 13 |
| aruba-ufd | aruba-ufd:ufd.profile.enable | 4 | 9 | 13 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.clock-step | 9 | 4 | 13 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.enable | 13 | 0 | 13 |
| aruba-ufd | aruba-ufd:ufd.profile.name | 4 | 9 | 13 |
| aruba-l3-route | aruba-l3-route:l3-route.profile.route-redistribute | 11 | 2 | 13 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.udld.interval | 8 | 5 | 13 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv6-access-list-in | 8 | 5 | 13 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-tx-drops.threshold | 12 | 1 | 13 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject.country | 10 | 3 | 13 |
| aruba-bgp | aruba-bgp:bgp.profile.router.graceful-restart.restart-time | 10 | 3 | 13 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mka-policy | 8 | 4 | 12 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.monitor-n-flows | 6 | 6 | 12 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.enable | 8 | 4 | 12 |
| aruba-remote-management | aruba-remote-management:remote-management.profile.central-alternative-location-vrf | 6 | 6 | 12 |
| aruba-remote-management | aruba-remote-management:remote-management.profile.central-alternative-location | 6 | 6 | 12 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ptp.enable | 8 | 4 | 12 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.igmp-snooping-lag.forward-vlan | 6 | 6 | 12 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.macsec-policy | 8 | 4 | 12 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.basic.management-addr | 11 | 1 | 12 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.forced-fast-leave-vlan | 5 | 7 | 12 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.type | 9 | 3 | 12 |
| aruba-dynamic-arp-inspection-interface | aruba-dynamic-arp-inspection-interface:dynamic-arp-inspection-interface.profile.name | 9 | 3 | 12 |
| aruba-dynamic-arp-inspection-interface | aruba-dynamic-arp-inspection-interface:dynamic-arp-inspection-interface.profile.dynamic-arp-inspection.trust | 9 | 3 | 12 |
| aruba-dhcp-snooping | aruba-dhcp-snooping:dhcp-snooping.profile.ipv4.client-attribute-caching | 10 | 2 | 12 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.basic.system-descr | 11 | 1 | 12 |
| aruba-rip | aruba-rip:rip.profile.router.instance-tag | 0 | 11 | 11 |
| aruba-qos-cos | aruba-qos-cos:qos-cos.profile.cos-map.local-priority | 11 | 0 | 11 |
| aruba-rip | aruba-rip:rip.router.redistribute.redistribute-id | 11 | 0 | 11 |
| aruba-rip | aruba-rip:rip.router.redistribute.redistribute-type | 11 | 0 | 11 |
| aruba-rip | aruba-rip:rip.profile.name | 0 | 11 | 11 |
| aruba-rip | aruba-rip:rip.profile.router.vrf | 0 | 11 | 11 |
| aruba-rip | aruba-rip:rip.profile.router.instance-tag-vrf-proto-type | 0 | 11 | 11 |
| aruba-rip | aruba-rip:rip.profile.router.proto-type | 0 | 11 | 11 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.md-cipherpassword | 0 | 11 | 11 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.unsupported-transceiver-logging-interval | 6 | 5 | 11 |
| aruba-qos-cos | aruba-qos-cos:qos-cos.profile.cos-map.color | 11 | 0 | 11 |
| aruba-qos-cos | aruba-qos-cos:qos-cos.profile.cos-map.cos | 11 | 0 | 11 |
| aruba-qos-cos | aruba-qos-cos:qos-cos.profile.name | 11 | 0 | 11 |
| aruba-lldp | aruba-lldp:lldp.profile.management-vlan | 5 | 6 | 11 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.managed-config | 4 | 7 | 11 |
| aruba-logging | aruba-logging:logging.profile.event-trap | 9 | 2 | 11 |
| aruba-config-checkpoint | aruba-config-checkpoint:config-checkpoint.profile.post-checkpoint-delay | 10 | 1 | 11 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.directory | 8 | 3 | 11 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.enable | 8 | 3 | 11 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.arp.local-proxy | 5 | 6 | 11 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.address | 8 | 3 | 11 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.policy-out | 8 | 3 | 11 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.cos-map.color | 0 | 11 | 11 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.cos-map.cos | 0 | 11 | 11 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.cos-map.local-priority | 0 | 11 | 11 |
| aruba-logging | aruba-logging:logging.profile.accounting-format-native | 4 | 7 | 11 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.radius.instance | 6 | 4 | 10 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.igmp.preprogram-starg-flow | 5 | 5 | 10 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.vrf-forwarding | 9 | 1 | 10 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lacp.port-priority | 6 | 4 | 10 |
| aruba-role | aruba-role:roles.role.session-parameters.poe-allocate-by-class | 8 | 2 | 10 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.send-start | 5 | 5 | 10 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.accept-start | 5 | 5 | 10 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.queue-num | 4 | 6 | 10 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.minutes | 7 | 3 | 10 |
| aruba-track-object | aruba-track-object:tracking-object.vrrp.interface.interface-type | 3 | 7 | 10 |
| aruba-local-management | aruba-local-management:local-management.profile.authorization.radius.access-type | 6 | 4 | 10 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.igmp.preprogram-starg-flow | 5 | 5 | 10 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.other-config | 3 | 7 | 10 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.stp.rpvst.cost | 5 | 5 | 10 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.speed-override | 6 | 4 | 10 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.speed-downshift-enable | 9 | 1 | 10 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.dcbx-disable | 3 | 7 | 10 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lacp.port-priority | 6 | 4 | 10 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.max-bandwidth-kbps | 0 | 10 | 10 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distribute-filter.prefix-name | 0 | 9 | 9 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.name | 8 | 1 | 9 |
| aruba-countermon | aruba-countermon:countermon.profile.name | 2 | 7 | 9 |
| aruba-countermon | aruba-countermon:countermon.profile.enable-polling | 2 | 7 | 9 |
| aruba-rip | aruba-rip:rip.router.svi-interfaces.address-family | 9 | 0 | 9 |
| aruba-rip | aruba-rip:rip.router.svi-interfaces.svi-id-address-family | 9 | 0 | 9 |
| aruba-rip | aruba-rip:rip.router.svi-interfaces.svi-id | 9 | 0 | 9 |
| aruba-rip | aruba-rip:rip.router.svi-interfaces.ip-address | 9 | 0 | 9 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distribute-filter.direction | 0 | 9 | 9 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.protection-switching-enable | 7 | 2 | 9 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.summary-address.prefix | 0 | 9 | 9 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.agent-type | 5 | 4 | 9 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.condtype | 5 | 4 | 9 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.name-condition | 5 | 4 | 9 |
| aruba-routemap | aruba-routemap:route-maps.route-map.route-map-entry.match-ipv6-prefix-list | 6 | 3 | 9 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.mac-auth.macauth-password.ciphertext-password | 9 | 0 | 9 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.mac-auth.macauth-password.type | 9 | 0 | 9 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.group-by | 4 | 5 | 9 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.ipv6-access-list-in | 5 | 4 | 9 |
| aruba-firmware-management | aruba-firmware-management:device-firmware.issu.software-update-rollback-timer-enable | 5 | 4 | 9 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.vlan-translate.origin | 5 | 4 | 9 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.control-vlan | 7 | 2 | 9 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.dns-server.dns-address | 3 | 6 | 9 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-collisions.threshold | 8 | 1 | 9 |
| aruba-erps | aruba-erps:erps.profile.ring.ring-id | 7 | 2 | 9 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-oversize-packets.threshold | 9 | 0 | 9 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.priority-flow-control.priority-config.direction | 6 | 3 | 9 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.priority-flow-control.priority-config.priority | 6 | 3 | 9 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.vlan-translate.translated | 5 | 4 | 9 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.ip.l3-counters | 7 | 2 | 9 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.qos.schedule-profile | 4 | 5 | 9 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.enable | 6 | 3 | 9 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-fragments.threshold | 9 | 0 | 9 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.prefixes.prefix | 5 | 4 | 9 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.key-usage | 5 | 4 | 9 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.id | 0 | 9 | 9 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.protected-vlans | 7 | 2 | 9 |
| aruba-erps | aruba-erps:erps.profile.name | 7 | 2 | 9 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.instance-id | 7 | 2 | 9 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.ext-key-usage | 5 | 4 | 9 |
| aruba-qos-dscp | aruba-qos-dscp:qos-dscp.profile.dscp-map.cos-override | 9 | 0 | 9 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.dscp-map.cos-override | 0 | 9 | 9 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.group-id | 7 | 1 | 8 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.ip-header.vlan | 4 | 4 | 8 |
| aruba-rip | aruba-rip:rip.profile.router.svi-interfaces.address-family | 0 | 8 | 8 |
| aruba-rip | aruba-rip:rip.profile.router.svi-interfaces.ip-address | 0 | 8 | 8 |
| aruba-rip | aruba-rip:rip.profile.router.svi-interfaces.svi-id | 0 | 8 | 8 |
| aruba-rip | aruba-rip:rip.profile.router.svi-interfaces.svi-id-address-family | 0 | 8 | 8 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.ciphertext-password | 0 | 8 | 8 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.keychain-key | 0 | 8 | 8 |
| aruba-snmp | aruba-snmp:snmp.profile.agent-port | 3 | 5 | 8 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.set-watch | 5 | 3 | 8 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.watches.event-id | 5 | 3 | 8 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.watches.watch-name | 5 | 3 | 8 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.llfc-flow-control.override-negotiation | 6 | 2 | 8 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.disable-factory-reset | 7 | 1 | 8 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.mac-access-list-in | 4 | 4 | 8 |
| aruba-rip | aruba-rip:rip.profile.router.redistribute.redistribute-type | 0 | 8 | 8 |
| aruba-rip | aruba-rip:rip.profile.description | 0 | 8 | 8 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.static-group | 8 | 0 | 8 |
| aruba-rip | aruba-rip:rip.profile.router.redistribute.redistribute-id | 0 | 8 | 8 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.override-negotiation | 6 | 2 | 8 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.max-prefix-options.action | 5 | 3 | 8 |
| aruba-dhcp-snooping | aruba-dhcp-snooping:dhcp-snooping.profile.ipv4.trust-vxlan-tunnel | 7 | 1 | 8 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.password-type | 5 | 3 | 8 |
| aruba-auth-server-global | aruba-auth-server-global:auth-server-global-config.profile.status-server-interval | 6 | 2 | 8 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.username | 5 | 3 | 8 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-jabbers.threshold | 8 | 0 | 8 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-late-collisions.threshold | 8 | 0 | 8 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.password-ciphertext | 5 | 3 | 8 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.dr-priority | 7 | 1 | 8 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.ciphertext-password | 0 | 8 | 8 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.vsx.shutdown-on-split | 2 | 6 | 8 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.keepalive.dead-interval | 4 | 4 | 8 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.role | 7 | 1 | 8 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.rpl | 7 | 1 | 8 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse.dr-priority | 4 | 4 | 8 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.nd-snooping.trust | 4 | 4 | 8 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.trigger-on-monthly | 2 | 6 | 8 |
| aruba-track-object | aruba-track-object:tracking-object.vrrp.interface.svi | 1 | 6 | 7 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.cli | 3 | 4 | 7 |
| aruba-lldp | aruba-lldp:lldp.profile.hold-multiplier | 5 | 2 | 7 |
| aruba-macsec | aruba-macsec:macsec.policy.cipher-suites | 5 | 2 | 7 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.sub-interface-name | 0 | 7 | 7 |
| aruba-mac-lockout | aruba-mac-lockout:mac-lockout.profile.log | 5 | 2 | 7 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.line-modules.hw-profile | 7 | 0 | 7 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.udp-broadcast-forwarder-server.servers.ip | 7 | 0 | 7 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.bfd.disable-echo | 1 | 6 | 7 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.udp-broadcast-forwarder-server.servers.port | 7 | 0 | 7 |
| aruba-ubt | aruba-ubt:ubt.profile.zone.papi-security-key.cipher-password | 5 | 2 | 7 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.igmp.policy-in | 6 | 1 | 7 |
| aruba-vrrp-interface | aruba-vrrp-interface:vrrp.profile.virtual-router.ciphertext-password | 5 | 2 | 7 |
| aruba-ubt | aruba-ubt:ubt.profile.zone.papi-security-key.type | 5 | 2 | 7 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.strict.max-bandwidth-kbps | 7 | 0 | 7 |
| aruba-logging | aruba-logging:logging.profile.notification-threshold.event-log | 4 | 3 | 7 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.igmp.policy-in | 6 | 1 | 7 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.certificate-as-authorized-key | 2 | 5 | 7 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.local-as-mode | 3 | 4 | 7 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.ttl-security-hops | 3 | 4 | 7 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.med.network-policy | 6 | 1 | 7 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-dense.source-address-any | 7 | 0 | 7 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.ptp.enable | 5 | 2 | 7 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.dot1.port-vlan-id | 6 | 1 | 7 |
| aruba-interface-tunnel | aruba-interface-tunnel:tunnel.interface.vrf-forwarding | 5 | 2 | 7 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse-vlan.vsx-virtual-neighbor-ipv4 | 5 | 2 | 7 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.links-to-disable.ethernet-ports | 0 | 7 | 7 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.links-to-monitor.ethernet-ports | 0 | 7 | 7 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.month-day | 2 | 5 | 7 |
| aruba-nexthop-group | aruba-nexthop-group:nexthop-groups.group.nexthops.null-interface | 4 | 3 | 7 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.name | 2 | 4 | 6 |
| aruba-dsm | aruba-dsm:dsm.dsm-instance.name | 3 | 3 | 6 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-destination-address | 2 | 4 | 6 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-protocol | 2 | 4 | 6 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-source-address | 2 | 4 | 6 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.match.ipv6-version | 2 | 4 | 6 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.credentials.password-ciphertext | 2 | 4 | 6 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.credentials.user | 2 | 4 | 6 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.location | 2 | 4 | 6 |
| aruba-ipfix-flow-monitor | aruba-ipfix-flow-monitor:ipfix-flow-monitor.monitors.cache-timeout-inactive | 3 | 3 | 6 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.pool | 2 | 4 | 6 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.reference-bandwidth | 0 | 6 | 6 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.ip-header.icmp.icmp-code | 1 | 5 | 6 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.broadcast-rate-limit.rate-type | 0 | 6 | 6 |
| aruba-l3-route | aruba-l3-route:l3-route.profile.graceful-restart | 5 | 1 | 6 |
| aruba-container | aruba-container:containers.instance.name | 2 | 4 | 6 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.nd-snooping.nd-guard | 4 | 2 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.vlan | 3 | 3 | 6 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.ready | 4 | 2 | 6 |
| aruba-logging | aruba-logging:logging.profile.notification-threshold.audit-log | 3 | 3 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.mac | 3 | 3 | 6 |
| aruba-erps | aruba-erps:erps.profile.ring.port1-eth-interface | 6 | 0 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.ip-version-vlan-client-address | 3 | 3 | 6 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.dot1.port-vlan-name | 5 | 1 | 6 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.macsec-policy | 4 | 2 | 6 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.mka-policy | 4 | 2 | 6 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.dns-search-list-enable | 3 | 3 | 6 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.delay-up | 0 | 6 | 6 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.description | 4 | 2 | 6 |
| aruba-erps | aruba-erps:erps.profile.ring.port0-eth-interface | 6 | 0 | 6 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.rdnss-enable | 3 | 3 | 6 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.nd-snooping.nd-guard | 4 | 2 | 6 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.l2vpn-evpn.inbound-soft-reconfiguration | 4 | 2 | 6 |
| aruba-logging | aruba-logging:logging.profile.remote-syslog.rate-limit.burst | 4 | 2 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.client-address | 3 | 3 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.interface-ethernet | 3 | 3 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.interface-types | 3 | 3 | 6 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.password-authentication | 6 | 0 | 6 |
| aruba-ip-binding | aruba-ip-binding:source-ip-bindings.static-entry.ip-version | 3 | 3 | 6 |
| aruba-config-checkpoint | aruba-config-checkpoint:config-checkpoint.profile.post-checkpoint | 3 | 2 | 5 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.block | 1 | 4 | 5 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.ethernet-header.source-mac-mask | 4 | 1 | 5 |
| aruba-policy | aruba-policy:policies.policy.security-policy.policy-rule.condition.ethernet-header.destination-mac-mask | 3 | 2 | 5 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.protocol-port-number | 3 | 2 | 5 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.protected-vlans | 5 | 0 | 5 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.preemption-enable | 5 | 0 | 5 |
| aruba-lldp | aruba-lldp:lldp.profile.dcbx-version | 2 | 3 | 5 |
| aruba-feature-pack | aruba-feature-pack:management-server.profile.vrf | 2 | 3 | 5 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.nd-snooping.ra-guard-log | 3 | 2 | 5 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.primary-ethernet-port | 5 | 0 | 5 |
| aruba-sflow | aruba-sflow:sflow.profile.session.maximum-datagram-size | 4 | 1 | 5 |
| aruba-dhcp-client | aruba-dhcp-client:dhcp-client.profile.ip.enable-broadcast-flag | 5 | 0 | 5 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.payload-size | 4 | 1 | 5 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.accept-end | 3 | 2 | 5 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.send-end | 3 | 2 | 5 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.bfd | 3 | 2 | 5 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.macsec.selftest-enable | 3 | 2 | 5 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.priority | 3 | 2 | 5 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.protocol | 3 | 2 | 5 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.secondary-ethernet-port | 5 | 0 | 5 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv-dcbx-app.app-tlv.port-number | 3 | 2 | 5 |
| aruba-advanced-intelligent-forwarding | aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-host-route-ipv4 | 5 | 0 | 5 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.sha-cipher-password | 0 | 5 | 5 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-l2vpn-evpn.redistribute.route-map | 4 | 1 | 5 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.orf.direction | 3 | 2 | 5 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.orf.prefix-list | 3 | 2 | 5 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.igmp-snooping-eth.blocked-vlan | 3 | 2 | 5 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.ecdsa-curve-size | 5 | 0 | 5 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.source.interface-vlan | 5 | 0 | 5 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject-alt-name-dns | 3 | 2 | 5 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.max-bandwidth-percent | 0 | 5 | 5 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group._DoNotDuplicate | 5 | 0 | 5 |
| aruba-advanced-intelligent-forwarding | aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.name | 5 | 0 | 5 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.interface-flow-limit | 3 | 2 | 5 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.flow-statistics-enable | 1 | 4 | 5 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.nd-snooping.ra-drop | 4 | 1 | 5 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.nd-snooping.ra-guard-log | 3 | 2 | 5 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.rcp-primary-method | 0 | 5 | 5 |
| aruba-object-group | aruba-object-group:object-groups.group.items.ipv4-prefix | 5 | 0 | 5 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.keepalive.hello-interval | 3 | 2 | 5 |
| aruba-logging | aruba-logging:logging.profile.local-file.rotation.period | 1 | 4 | 5 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.network | 0 | 5 | 5 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.keepalive.udp-port | 4 | 0 | 4 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.comment | 3 | 1 | 4 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.line-modules.power-admin-state | 4 | 0 | 4 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.include-regex | 1 | 3 | 4 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.include | 1 | 3 | 4 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.multicast-rate-limit.rate-type | 0 | 4 | 4 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.nd-snooping.allow-bindings-on-trusted-ports | 0 | 4 | 4 |
| aruba-dhcp-snooping | aruba-dhcp-snooping:dhcp-snooping.profile.ipv4.flash-storage.delay | 0 | 4 | 4 |
| aruba-qos-cos | aruba-qos-cos:qos-cos.profile.cos-map.name | 4 | 0 | 4 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.nd-snooping.allow-bindings-on-trusted-ports | 0 | 4 | 4 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.preemption-delay | 4 | 0 | 4 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.dhcpv4-snooping.ip-binding-enable | 4 | 0 | 4 |
| aruba-mirror | aruba-mirror:mirrors.profile.session.session-destination.dscp | 2 | 2 | 4 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.encap | 2 | 2 | 4 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.nd-snooping.ra-drop | 4 | 0 | 4 |
| aruba-sysmon | aruba-sysmon:sysmon.profile.name | 1 | 3 | 4 |
| aruba-sysmon | aruba-sysmon:sysmon.profile.poll-interval | 1 | 3 | 4 |
| aruba-sysmon | aruba-sysmon:sysmon.profile.polling | 1 | 3 | 4 |
| aruba-routemap | aruba-routemap:route-maps.route-map.route-map-entry.continue | 2 | 2 | 4 |
| aruba-sflow | aruba-sflow:sflow.profile.session.maximum-header-size | 3 | 1 | 4 |
| aruba-snmp | aruba-snmp:snmp.profile.community.view-name | 1 | 3 | 4 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.interface.tunnel-id | 4 | 0 | 4 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ip.l3-counters | 4 | 0 | 4 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.qos.schedule-profile | 3 | 1 | 4 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.dhcpv4-snooping.ip-binding-enable | 4 | 0 | 4 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.qinq-svlan | 4 | 0 | 4 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.syslog | 3 | 1 | 4 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.policy.ipv6-access-list-out | 0 | 4 | 4 |
| aruba-firmware-management | aruba-firmware-management:device-firmware.issu.software-update-rollback-timer | 2 | 2 | 4 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.ipv6.enable-default-link-local | 4 | 0 | 4 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.status | 3 | 1 | 4 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.dns-search.dns-search-list | 1 | 3 | 4 |
| aruba-erps | aruba-erps:erps.profile.ring.port1-portchannel | 2 | 2 | 4 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.local-as | 1 | 3 | 4 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.ttl-security-hops | 4 | 0 | 4 |
| aruba-dhcp-pool | aruba-dhcp-pool:dhcp-pool.profile.ipv4-pool.netbios-node | 2 | 2 | 4 |
| aruba-dhcp-snooping-interface | aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv4-snooping.max-bindings | 3 | 1 | 4 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.arp.timeout | 3 | 1 | 4 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.igmp.robustness | 4 | 0 | 4 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.hello-delay | 4 | 0 | 4 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.stp.mstp.cost | 2 | 2 | 4 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.basic.system-cap | 3 | 1 | 4 |
| aruba-bgp | aruba-bgp:bgp.profile.router.default-bgp-attributes.local-preference | 4 | 0 | 4 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.vlan-translate.origin | 3 | 1 | 4 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.vlan-translate.translated | 3 | 1 | 4 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.mac-phy | 2 | 2 | 4 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.preference | 3 | 1 | 4 |
| aruba-rmon-alarm | aruba-rmon-alarm:rmon-alarms.profile.rmon.falling-threshold | 3 | 1 | 4 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.delay-down | 0 | 4 | 4 |
| aruba-mgmd | aruba-mgmd:mgmd-global.profile.delayed-refresh_enable | 1 | 3 | 4 |
| aruba-mgmd | aruba-mgmd:mgmd-global.profile.delayed-refresh-interval | 1 | 3 | 4 |
| aruba-erps | aruba-erps:erps.profile.ring.instance.instance-description | 3 | 1 | 4 |
| aruba-rmon-alarm | aruba-rmon-alarm:rmon-alarms.profile.rmon.snmp-oid | 3 | 1 | 4 |
| aruba-rmon-alarm | aruba-rmon-alarm:rmon-alarms.profile.rmon.index | 3 | 1 | 4 |
| aruba-rmon-alarm | aruba-rmon-alarm:rmon-alarms.profile.rmon.rising-threshold | 3 | 1 | 4 |
| aruba-rmon-alarm | aruba-rmon-alarm:rmon-alarms.profile.name | 3 | 1 | 4 |
| aruba-erps | aruba-erps:erps.profile.ring.description | 3 | 1 | 4 |
| aruba-nd-snooping | aruba-nd-snooping:nd-snooping.profile.ra-guard-policy.ra-guard-name | 4 | 0 | 4 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-supp.enable | 0 | 4 | 4 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.application-tcp-establishment-time | 2 | 2 | 4 |
| aruba-ipfix-flow-exporter | aruba-ipfix-flow-exporter:ipfix-flow-exporter.exporters.hostname | 2 | 1 | 3 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.pool.type | 0 | 3 | 3 |
| aruba-track-object | aruba-track-object:tracking-object.vrrp.interface.ethernet | 2 | 1 | 3 |
| aruba-rip | aruba-rip:rip.router.ether-interfaces.ip-address | 3 | 0 | 3 |
| aruba-rip | aruba-rip:rip.router.ether-interfaces.interface-name-address-family | 3 | 0 | 3 |
| aruba-rip | aruba-rip:rip.router.ether-interfaces.interface-name | 3 | 0 | 3 |
| aruba-rip | aruba-rip:rip.router.ether-interfaces.address-family | 3 | 0 | 3 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.destination-hostname | 3 | 0 | 3 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.pool.size | 0 | 3 | 3 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.pool.index | 0 | 3 | 3 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.pool.headroom-size | 0 | 3 | 3 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.destination-port | 2 | 1 | 3 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.broadcast-rate-limit.percentage | 0 | 3 | 3 |
| aruba-dsm | aruba-dsm:dsm.dsm-instance.workload-migration | 2 | 1 | 3 |
| aruba-lldp | aruba-lldp:lldp.profile.neighbor-last-update-enable | 1 | 2 | 3 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.job.enable | 2 | 1 | 3 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.aaa.client-move | 1 | 2 | 3 |
| aruba-container | aruba-container:containers.instance.image-location-url | 2 | 1 | 3 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.max-threshold-percent | 0 | 3 | 3 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.icmp-rate-limit.bit-rate | 0 | 3 | 3 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.dynamic-arp-inspection.enable | 2 | 1 | 3 |
| aruba-snmp | aruba-snmp:snmp.profile.notification-receiver.notification-type | 0 | 3 | 3 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-sparse.source-address-any | 3 | 0 | 3 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.use-forwarding-address | 2 | 1 | 3 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.min-threshold-percent | 0 | 3 | 3 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp.entry.color | 0 | 3 | 3 |
| aruba-container | aruba-container:containers.instance.image-location-vrf | 2 | 1 | 3 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn-entry.threshold | 3 | 0 | 3 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn-entry.thresh-units | 3 | 0 | 3 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-interface | 1 | 2 | 3 |
| aruba-ip-lockdown-interface | aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.name | 0 | 3 | 3 |
| aruba-ip-lockdown-interface | aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.ip-source-lockdown.ipv4 | 0 | 3 | 3 |
| aruba-device-certificate | aruba-device-certificate:device-certificates.device-certificate.subject-alt-name-ip | 2 | 1 | 3 |
| aruba-vsx-pair | aruba-vsx-pair:vsx-config.vsx.linkup-delay-timer-exclude | 2 | 1 | 3 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.tcp-ageout | 2 | 1 | 3 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.strict.max-bandwidth-percent | 3 | 0 | 3 |
| aruba-dhcp-snooping-interface | aruba-dhcp-snooping-interface:dhcp-snooping-interface.profile.dhcpv6-snooping.trust | 2 | 1 | 3 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.ip | 1 | 2 | 3 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ip.mtu | 2 | 1 | 3 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.policy.ipv6-access-list-in | 2 | 1 | 3 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.igmp-snooping-lag.blocked-vlan | 3 | 0 | 3 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.dot1.link-aggregation | 2 | 1 | 3 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.qos.threshold-profile | 1 | 2 | 3 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.oui | 2 | 1 | 3 |
| aruba-dhcp-server | aruba-dhcp-server:dhcp-server.profile.external-storage.ip-version-es-name | 1 | 2 | 3 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.vrf | 1 | 2 | 3 |
| aruba-dhcp-server | aruba-dhcp-server:dhcp-server.profile.external-storage.ip-version | 1 | 2 | 3 |
| aruba-dhcp-server | aruba-dhcp-server:dhcp-server.profile.external-storage.filename | 1 | 2 | 3 |
| aruba-dhcp-server | aruba-dhcp-server:dhcp-server.profile.external-storage.delay | 1 | 2 | 3 |
| aruba-dhcp-pool | aruba-dhcp-pool:dhcp-pool.profile.ipv6-pool.v6pool-name | 1 | 2 | 3 |
| aruba-dhcp-pool | aruba-dhcp-pool:dhcp-pool.profile.ipv6-pool.lease-time | 1 | 2 | 3 |
| aruba-bgp | aruba-bgp:bgp.profile.router.graceful-restart.stale-routes-time | 2 | 1 | 3 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.vsx.shutdown-on-split | 0 | 3 | 3 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ipv4-relay.server.ip-vrf | 1 | 2 | 3 |
| aruba-dhcp-server | aruba-dhcp-server:dhcp-server.profile.external-storage.es-name | 1 | 2 | 3 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.arp.process-grat | 1 | 2 | 3 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.passive | 0 | 3 | 3 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.control-vlan | 3 | 0 | 3 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.igmp.querier-wait-time | 2 | 1 | 3 |
| aruba-bgp | aruba-bgp:bgp.profile.router.route-reflector-cluster-id | 0 | 3 | 3 |
| aruba-dsm | aruba-dsm:dsm.dsm-instance.ipfix | 1 | 2 | 3 |
| aruba-pim | aruba-pim:pim-router.profile.router.rpf-override.source-prefix | 2 | 1 | 3 |
| aruba-pim | aruba-pim:pim-router.profile.router.rpf-override.nexthop-address | 2 | 1 | 3 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distance.route-type | 0 | 3 | 3 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.vrf | 3 | 0 | 3 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.disable-nonce | 2 | 1 | 3 |
| aruba-erps | aruba-erps:erps.profile.ring.port0-portchannel | 1 | 2 | 3 |
| aruba-ntp | aruba-ntp:ntp.profile.authentication-profile.key-value | 2 | 1 | 3 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.dns-server.lifetime | 2 | 1 | 3 |
| aruba-lldp | aruba-lldp:lldp.profile.tlv.basic.system-name | 2 | 1 | 3 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.dad-attempts | 1 | 2 | 3 |
| aruba-ip-routing | aruba-ip-routing:ip-routing.profile.name | 2 | 1 | 3 |
| aruba-rip | aruba-rip:rip.profile.router.timers.timeout | 0 | 2 | 2 |
| aruba-macsec | aruba-macsec:macsec.policy.confidentiality-offset | 1 | 1 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.loopback-interfaces.address-family | 0 | 2 | 2 |
| aruba-local-management | aruba-local-management:local-management.profile.nae.cli-authorization | 0 | 2 | 2 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-vlan | 0 | 2 | 2 |
| aruba-mka | aruba-mka:mka.policy.eapol-destination-mac | 1 | 1 | 2 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.tracked-protocol.track-icmp | 1 | 1 | 2 |
| aruba-flow-tracking | aruba-flow-tracking:flow-tracking.profile.tracked-protocol.protocol-name | 1 | 1 | 2 |
| aruba-container-network | aruba-container-network:container-networks.profile.vrf | 1 | 1 | 2 |
| aruba-container-network | aruba-container-network:container-networks.profile.name-vrf | 1 | 1 | 2 |
| aruba-container-network | aruba-container-network:container-networks.profile.name | 1 | 1 | 2 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.primary-url | 0 | 2 | 2 |
| aruba-rip | aruba-rip:rip.router.redistribute.ospf-id | 2 | 0 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.redistribute.ospf-id | 0 | 2 | 2 |
| aruba-job-scheduler | aruba-job-scheduler:job-scheduler.schedule.hours | 1 | 1 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.timers.update | 0 | 2 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse.source-address | 0 | 2 | 2 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ipv6.addresses.address | 0 | 2 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.loopback-interfaces.loopback-id | 0 | 2 | 2 |
| aruba-rip | aruba-rip:rip.router.enable | 2 | 0 | 2 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.pool.priority | 0 | 2 | 2 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.vrrp.vrrp-profile-apply | 0 | 2 | 2 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.thresh-units | 2 | 0 | 2 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.min-threshold | 2 | 0 | 2 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.max-threshold | 2 | 0 | 2 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.wred-resp-entry.color | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.multicast-rate-limit.percentage | 0 | 2 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.loopback-interfaces.ip-address | 0 | 2 | 2 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.parameter | 1 | 1 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.loopback-interfaces.loopback-id-address-family | 0 | 2 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-sparse.hello-interval | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.vsx.shutdown-on-split | 0 | 2 | 2 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.description | 0 | 2 | 2 |
| aruba-role | aruba-role:roles.role.object-group-ipv4 | 0 | 2 | 2 |
| aruba-object-group | aruba-object-group:object-groups.group.vrf | 0 | 2 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse.datapath-auto-include | 0 | 2 | 2 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ip.l3-counters | 0 | 2 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-l2vpn-evpn.aggregate-address.summary-only | 0 | 2 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-l2vpn-evpn.aggregate-address.address | 0 | 2 | 2 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.destination-guard.enable | 2 | 0 | 2 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.destination-guard.enable | 2 | 0 | 2 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.unsupported-transceiver-logging | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.poe.power-pairs | 1 | 1 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-sparse.dr-priority | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.broadcast-rate-limit.packet-rate | 0 | 2 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-dense.enable | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.mld.enable | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.llfc-flow-control.llfc-pool-id | 1 | 1 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv4-relay.bootp-gateway | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipfix-flow-monitor-in.ipv4-monitor | 1 | 1 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.query-max-response-time | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.energy-efficient | 2 | 0 | 2 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv6.source-interface.svi | 2 | 0 | 2 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv6.source-interface.source-interface-type | 2 | 0 | 2 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.recv-control-vlans | 2 | 0 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.unknown-unicast-rate-limit.rate-type | 0 | 2 | 2 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.multicast-rate-limit.packet-rate | 0 | 2 | 2 |
| aruba-rip | aruba-rip:rip.profile.router.timers.garbage-collection | 0 | 2 | 2 |
| aruba-advanced-intelligent-forwarding | aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-exclude-nexthop-ipv4 | 2 | 0 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.link-clock-narrow-tolerance | 0 | 2 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.llfc-flow-control.llfc-pool-id | 1 | 1 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6.link-local | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.prefixes.prefix-option.valid-lifetime | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.prefixes.prefix-option.preferred-lifetime | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.min-interval | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.max-interval | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv4-tcp-mss | 1 | 1 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv4-router-discovery.enable | 1 | 1 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ip-neighbor-flood-enable | 2 | 0 | 2 |
| aruba-interface-tunnel | aruba-interface-tunnel:tunnel.interface.l3-counters | 2 | 0 | 2 |
| aruba-interface-loopback | aruba-interface-loopback:loopback-interfaces.interface.enable-default-link-local | 2 | 0 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ptp.vlan | 2 | 0 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.policy.ipv6-access-list-out | 2 | 0 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.registration | 1 | 1 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.elin-addr | 1 | 1 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.policy.ipv6-access-list-out | 1 | 1 | 2 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.enable | 1 | 1 | 2 |
| aruba-fault-monitor | aruba-fault-monitor:fault-monitor.profile.excessive-alignment-errors.threshold | 2 | 0 | 2 |
| aruba-auth-server-global | aruba-auth-server-global:auth-server-global-config.profile.single-connection-mode | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-l2vpn-evpn.redistribute.ospfv2-id | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.default-originate.route-map | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.max-prefix-options.threshold | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.l2vpn-evpn.default-originate.default-originate-enable | 1 | 1 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.graceful-shutdown.local-preference | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.graceful-shutdown.timer | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.remove-private-as | 1 | 1 | 2 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.threshold-percent | 0 | 2 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.graceful-shutdown.local-preference | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.graceful-shutdown.timer | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-dense.source-address | 1 | 1 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv6-unicast.max-prefix-options.action | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.vrrp.dual-active-forwarding | 2 | 0 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.spf-throttle.start-time | 0 | 2 | 2 |
| aruba-logging | aruba-logging:logging.profile.notification-threshold.security-log | 0 | 2 | 2 |
| aruba-qos-pool | aruba-qos-pool:qos-pools.profile.name | 2 | 0 | 2 |
| aruba-qos-pool | aruba-qos-pool:qos-pools.profile.pool.size | 2 | 0 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.next-hop-unchanged | 0 | 2 | 2 |
| aruba-nd-snooping | aruba-nd-snooping:nd-snooping.profile.ra-guard-policy.match-list.access-list | 2 | 0 | 2 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.links-to-monitor.lag-ports | 0 | 2 | 2 |
| aruba-pim | aruba-pim:pim-router.profile.router.register-source-port.interface-vlan | 2 | 0 | 2 |
| aruba-qos-pool | aruba-qos-pool:qos-pools.profile.pool.headroom-size | 2 | 0 | 2 |
| aruba-pim | aruba-pim:pim-router.profile.router.register-source-port.interface-type | 2 | 0 | 2 |
| aruba-qos-pool | aruba-qos-pool:qos-pools.profile.pool.index | 2 | 0 | 2 |
| aruba-qos-pool | aruba-qos-pool:qos-pools.profile.pool.priority | 2 | 0 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.timer-id | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.spf-throttle.max-wait-time | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.spf-throttle.hold-time | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distance.all | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.default-information-origin.metric | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.backbone-stub-default-route | 0 | 2 | 2 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.pim-sparse.enable | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.lag-interfaces.md-cipherpassword | 0 | 2 | 2 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.keychain-key | 0 | 2 | 2 |
| aruba-erps | aruba-erps:erps.profile.ring.wtr-interval | 2 | 0 | 2 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.policy.mac-access-list-in | 0 | 2 | 2 |
| aruba-ip-routing | aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-port | 1 | 1 | 2 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.local-as-mode | 0 | 2 | 2 |
| aruba-logging | aruba-logging:logging.profile.remote-syslog.rate-limit.interval | 2 | 0 | 2 |
| aruba-rmon-alarm | aruba-rmon-alarm:rmon-alarms.profile.rmon.interval | 1 | 1 | 2 |
| aruba-qos-pool | aruba-qos-pool:qos-pools.profile.pool.type | 2 | 0 | 2 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.ra-routes.lifetime | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.ra-routes.route | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.xon-delta | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.valid-lifetime | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.preferred-lifetime | 0 | 1 | 1 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.igmp.enable | 0 | 1 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.ipfix-flow-monitor-in.ipv6-monitor | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.forbidden-vlan-list | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.priority | 0 | 1 | 1 |
| aruba-ipfix-flow-record | aruba-ipfix-flow-record:ipfix-flow-record.records.collect.egress-queue | 1 | 0 | 1 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.application-id | 1 | 0 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.responder-sessions.responder-name | 1 | 0 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.responder-sessions.responder-port | 1 | 0 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.responder-sessions.responder-source.interface-vlan | 1 | 0 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.responder-sessions.responder-type | 1 | 0 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.http.request-type | 1 | 0 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.http.url | 1 | 0 | 1 |
| aruba-lldp | aruba-lldp:lldp.profile.transmit-delay | 1 | 0 | 1 |
| aruba-local-management | aruba-local-management:local-management.profile.ssh-server-global-configs.file-transfer | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipfix-flow-monitor-in.ipv6-monitor | 0 | 1 | 1 |
| aruba-logging | aruba-logging:logging.profile.local-file.rotation.target | 0 | 1 | 1 |
| aruba-macsec | aruba-macsec:macsec.policy.include-sci-enable | 0 | 1 | 1 |
| aruba-mirror-endpoint | aruba-mirror-endpoint:mirror-endpoint.profile.endpoints.source.vrf | 1 | 0 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.facility | 1 | 0 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.operand | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.operator | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lossless-buffer-based-priority-flow-control.thresholds.headroom | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.runtime-constraints.memory | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.cable-length | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.encrypted-environment-variables.value-ciphertext | 1 | 0 | 1 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv6.interface.sub-interface | 0 | 1 | 1 |
| aruba-vrf | aruba-vrf:vrfs.vrf.l3-route-vrf.recursive-lookup-ipv4 | 0 | 1 | 1 |
| aruba-aaa-captive-portal | aruba-aaa-captive-portal:captive-portal.profile.url-hash-key-ciphertext-value | 0 | 1 | 1 |
| aruba-certificate-rcp | aruba-certificate-rcp:certificate-rcp.ta-profile.ocsp.secondary-url | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.severity | 1 | 0 | 1 |
| aruba-container-network | aruba-container-network:container-networks.profile.port-mapping.tcp.container-port | 0 | 1 | 1 |
| aruba-container-network | aruba-container-network:container-networks.profile.port-mapping.tcp.host-port | 0 | 1 | 1 |
| aruba-container-network | aruba-container-network:container-networks.profile.preferred | 1 | 0 | 1 |
| aruba-container | aruba-container:containers.instance.allow-unsigned-image | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.enable | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.encrypted-environment-variables.encrypted-env-type | 1 | 0 | 1 |
| aruba-container | aruba-container:containers.instance.encrypted-environment-variables.variable | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.aaa.authentication.dot1x-auth.macsec.enable | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.environment-variables.value | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.environment-variables.variable | 0 | 1 | 1 |
| aruba-container | aruba-container:containers.instance.runtime-constraints.cpu | 1 | 0 | 1 |
| aruba-container | aruba-container:containers.instance.vrfs | 1 | 0 | 1 |
| aruba-dsm | aruba-dsm:dsm.dsm-instance.uplink-to-uplink | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pfc-watchdog | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-sparse.bfd-enable | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.pim-sparse.hello-delay | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.poe.pd-class-override | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.stp.mstp.instance-id | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.stp.mstp.priority | 1 | 0 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.set-monitor | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lossless-buffer-based-priority-flow-control.thresholds.priority | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.disable | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.robustness | 1 | 0 | 1 |
| aruba-switch-chassis | aruba-switch-chassis:switch-chassis.chassis.line-modules.power-priority | 1 | 0 | 1 |
| aruba-switch-system | aruba-switch-system:switch-system.profile.icmp.throttle | 0 | 1 | 1 |
| aruba-traffic-insight | aruba-traffic-insight:traffic-insight.instance.monitor.single-value-filter.source-port | 0 | 1 | 1 |
| aruba-advanced-intelligent-forwarding | aruba-advanced-intelligent-forwarding:advanced-intelligent-forwarding.profile.fib-optimization-ageout-time | 0 | 1 | 1 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.rfc5176-enforcement-mode | 0 | 1 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.global-afi-safi.global-ipv6-unicast.redistribute.ospfv2-id | 0 | 1 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.l2vpn-evpn.minimum-advertisement-interval | 0 | 1 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.afi-safi.l2vpn-evpn.inbound-soft-reconfiguration | 0 | 1 | 1 |
| aruba-devicefingerprinting-profile | aruba-devicefingerprinting-profile:devicefingerprinting-profile.profile.dhcp-options | 0 | 1 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.pim-sparse.source-address-any | 0 | 1 | 1 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.arp.timeout | 0 | 1 | 1 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.policy.ipv4-access-list-in | 0 | 1 | 1 |
| aruba-interface-tunnel | aruba-interface-tunnel:tunnel.interface.ttl.value | 0 | 1 | 1 |
| aruba-ip-lockdown-interface | aruba-ip-lockdown-interface:ip-source-lockdown-interface.profile.ip-source-lockdown.ipv6 | 0 | 1 | 1 |
| aruba-nd-snooping | aruba-nd-snooping:nd-snooping.profile.mac-check | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.lag-interfaces.keychain-key | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.lag-interfaces.sha-cipher-password | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.authentication-key-id | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.sha-cipher-password | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.sha-password-type | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.transit-delay | 0 | 1 | 1 |
| aruba-smartlink | aruba-smartlink:smartlink.profile.group.primary-portchannel-port | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.unknown-unicast-rate-limit.packet-rate | 0 | 1 | 1 |
| aruba-vlan-range | aruba-vlan-range:layer2-vlan-range.dhcpv6-snooping.allow-bindings-on-trusted-ports | 0 | 1 | 1 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.dhcpv6-snooping.allow-bindings-on-trusted-ports | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lossless-buffer-based-priority-flow-control.thresholds.xon-delta | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lossless-buffer-based-priority-flow-control.thresholds.headroom | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.monitors.dur-unit | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.unknown-unicast-rate-limit.percentage | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.monitors.duration | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.monitors.group-by | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.monitors.monitor-name | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.monitors.vsf-member | 0 | 1 | 1 |
| aruba-nd-snooping-interface | aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.max-bindings | 1 | 0 | 1 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.sub-interfaces.network | 0 | 1 | 1 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.sub-interfaces.sub-interface-name | 0 | 1 | 1 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.trap-enable | 0 | 1 | 1 |
| aruba-ptp | aruba-ptp:ptp.profile.protocol-profiles.domain | 0 | 1 | 1 |
| aruba-rip | aruba-rip:rip.profile.router.ether-interfaces.address-family | 0 | 1 | 1 |
| aruba-rip | aruba-rip:rip.profile.router.ether-interfaces.interface-name | 0 | 1 | 1 |
| aruba-rip | aruba-rip:rip.profile.router.ether-interfaces.interface-name-address-family | 0 | 1 | 1 |
| aruba-rip | aruba-rip:rip.profile.router.ether-interfaces.ip-address | 0 | 1 | 1 |
| aruba-rip | aruba-rip:rip.router.distance | 1 | 0 | 1 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.mac-access-list-out | 1 | 0 | 1 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv6.tag | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.cable-length | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp-snooping-eth.forward-vlan | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.igmp-snooping-lag.forward-vlan | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.broadcast-rate-limit.bit-rate | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.cos | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.icmp-rate-limit.icmp-traffic-type | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.icmp-rate-limit.percentage | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.icmp-rate-limit.rate-type | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.unknown-unicast-rate-limit.bit-rate | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.ipv6-relay.ucast-server | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.country-code | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp.last-member-query-interval | 1 | 0 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.prefixes.prefix-option.autoconfig | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.mvrp.forbidden-vlan-list | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.mvrp.registration | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.nd-snooping.max-bindings | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.portfilter.eth-ports | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.portfilter.lag-ports | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.qos.threshold-profile | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.stp.mstp.cost | 1 | 0 | 1 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.ipv4.secondary-ip | 1 | 0 | 1 |
| aruba-interface-subinterface | aruba-interface-subinterface:sub-interfaces.interface.policy.ipv4-access-list-out | 1 | 0 | 1 |
| aruba-interface-tunnel | aruba-interface-tunnel:tunnel.interface.gre.pim4-sparse.enable | 1 | 0 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.active-gateway.extended-mac-address-v4 | 1 | 0 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv4-router-discovery.ra-type | 1 | 0 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.lifetime | 1 | 0 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse.bsr-boundary | 1 | 0 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.cost | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.policy.ipv6-access-list-in | 1 | 0 | 1 |
| aruba-ufd | aruba-ufd:ufd.profile.sessions.links-to-disable.lag-ports | 0 | 1 | 1 |
| aruba-ip-routing | aruba-ip-routing:ip-routing.profile.ip-prefix-priority-params.ip-prefix-priority | 1 | 0 | 1 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.auth-key-info.auth-key | 1 | 0 | 1 |
| aruba-local-management | aruba-local-management:local-management.profile.webservers.mgmt-auth | 1 | 0 | 1 |
| aruba-nd-snooping-interface | aruba-nd-snooping-interface:nd-snooping-interface.profile.nd-snooping.ra-guard-policy | 1 | 0 | 1 |
| aruba-mka | aruba-mka:mka.policy.cak-info.cak | 1 | 0 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.remove-private-as | 0 | 1 | 1 |
| aruba-nae-lite | aruba-nae-lite:nae-lite.profile.conditions.count | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp-snooping-eth.forced-fast-leave-vlan | 1 | 0 | 1 |
| aruba-erps | aruba-erps:erps.profile.ring.meg-level | 1 | 0 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.ciphertext-password | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.retransmit-interval | 0 | 1 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.mvrp.enable | 1 | 0 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.arp.timeout | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.port | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.udp-broadcast-forwarder-server.servers.ip | 1 | 0 | 1 |
| aruba-auth-server | aruba-auth-server:auth-servers.auth-server.tls-initial-connection-timeout | 1 | 0 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.ipv4-unicast.max-prefix-options.restart-time | 1 | 0 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.l2vpn-evpn.max-prefix-options.action | 1 | 0 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.afi-safi.l2vpn-evpn.max-prefix-options.limit | 1 | 0 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.neighbor.transport.passive | 1 | 0 | 1 |
| aruba-bgp | aruba-bgp:bgp.profile.router.peer-group.afi-safi.ipv4-unicast.max-prefix-options.action | 1 | 0 | 1 |
| aruba-dns | aruba-dns:dns.profile.resolver.priority.ip | 1 | 0 | 1 |
| aruba-dns | aruba-dns:dns.profile.resolver.priority.priority | 1 | 0 | 1 |
| aruba-external-storage | aruba-external-storage:external-storage.profile.store.vrf | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.arp.neighbor.address | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.arp.neighbor.mac-address | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ip-unnumbered-interface-loopback | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.advertise | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.default-prefix.default | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.management-tlv-ipv4-addr | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mld-snooping-eth.forward-vlan | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.join-timer | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.leaveall-timer | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.mvrp.periodic-timer | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.max-bindings | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.nd-snooping.ra-guard-policy | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pfc-watchdog | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.bsr-boundary | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.datapath-auto-include | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.pim-sparse.source-address | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.policy.mac-access-list-out | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.qos.burst | 1 | 0 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.authentication | 0 | 1 | 1 |
| aruba-qos-global | aruba-qos-global:qos-global.profile.cos-map.name | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.dead-interval | 0 | 1 | 1 |
| aruba-mka | aruba-mka:mka.policy.eapol-dot1q-tagged | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.preference | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.ipv6-neighbor-discovery.dad-attempts | 0 | 1 | 1 |
| aruba-erps | aruba-erps:erps.profile.ring.parent-ring | 1 | 0 | 1 |
| aruba-routemap | aruba-routemap:route-maps.route-map.route-map-entry.match-ethernet-interface | 1 | 0 | 1 |
| aruba-routemap | aruba-routemap:route-maps.route-map.route-map-entry.match-community-list.exact-match | 1 | 0 | 1 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv4.interface.tunnel | 0 | 1 | 1 |
| aruba-macsec | aruba-macsec:macsec.policy.clear-tag-mode | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-value | 0 | 1 | 1 |
| aruba-macsec | aruba-macsec:macsec.policy.bypass-list | 0 | 1 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.source.port | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.igmp.router-alert-check | 0 | 1 | 1 |
| aruba-erps | aruba-erps:erps.profile.ring.sub-ring | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.mvrp.enable | 0 | 1 | 1 |
| aruba-rip | aruba-rip:rip.profile.router.maximum-paths | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.ca-pair.ca-type | 0 | 1 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.civic-addr.what | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.hello-interval | 0 | 1 | 1 |
| aruba-macsec | aruba-macsec:macsec.policy.replay-protect-enable | 1 | 0 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.igmp-snooping-eth.fast-leave-vlan | 1 | 0 | 1 |
| aruba-rip | aruba-rip:rip.profile.router.distance | 0 | 1 | 1 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.threshold-kbytes | 0 | 1 | 1 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.min-threshold-kbytes | 0 | 1 | 1 |
| aruba-qos-threshold-profile | aruba-qos-threshold-profile:qos-thresholds.profile.queue.ecn.max-threshold-kbytes | 0 | 1 | 1 |
| aruba-qos-schedule | aruba-qos-schedule:qos-schedules.profile.sched-entries.burst | 0 | 1 | 1 |
| aruba-static-route | aruba-static-route:static-route.profile.ipv6.reject | 1 | 0 | 1 |
| aruba-interface-ethernet | aruba-interface-ethernet:ethernet-interfaces.interface.lldp.tlv.dot3tlv.mfs | 0 | 1 | 1 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.send-id | 0 | 1 | 1 |
| aruba-keychain | aruba-keychain:keychains.keychain.keys.recv-id | 0 | 1 | 1 |
| aruba-ipsla | aruba-ipsla:ipsla.profile.source-sessions.source.interface-ethernet | 1 | 0 | 1 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.mac-notify-traps | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.pim-sparse.hello-delay | 0 | 1 | 1 |
| aruba-interface-portchannel | aruba-interface-portchannel:portchannels.interface.stp.rpvst.cost | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.ether-interfaces.sha-cipher-password | 0 | 1 | 1 |
| aruba-vlan | aruba-vlan:layer2-vlan.l2-vlan.ipv6-access-list-out | 0 | 1 | 1 |
| aruba-erps | aruba-erps:erps.profile.ring.transmission-interval | 1 | 0 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.lsa-throttle.max-wait-time | 0 | 1 | 1 |
| aruba-ip-routing | aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-src-ip | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.bfd | 0 | 1 | 1 |
| aruba-ip-icmp-tcp | aruba-ip-icmp-tcp:ip-icmp-tcp.profile.ip-icmp.throttle | 1 | 0 | 1 |
| aruba-erps | aruba-erps:erps.profile.ring.guard-interval | 1 | 0 | 1 |
| aruba-erps | aruba-erps:erps.profile.ring.hold-off-interval | 1 | 0 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.lsa-throttle.hold-time | 0 | 1 | 1 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.loop-protect-vlans | 0 | 1 | 1 |
| aruba-interface-vlan | aruba-interface-vlan:vlan-interfaces.interface.ipv6-neighbor-discovery.router-advertisement.prefixes.prefix-option.advertise | 0 | 1 | 1 |
| aruba-ip-routing | aruba-ip-routing:ip-routing.profile.ip-ecmp-params.ip-ecmp-hash-params.enable-lb-dst-port | 1 | 0 | 1 |
| aruba-logging | aruba-logging:logging.profile.notification-threshold.auth-log | 0 | 1 | 1 |
| aruba-logging | aruba-logging:logging.profile.notification-threshold.commands-log | 0 | 1 | 1 |
| aruba-logging | aruba-logging:logging.profile.notification-threshold.https-server-log | 0 | 1 | 1 |
| aruba-sw-port-profile | aruba-sw-port-profile:sw-port-profiles.profile.lag.qos-lag.schedule-profile | 0 | 1 | 1 |
| aruba-interface-vxlan | aruba-interface-vxlan:vxlan.profile.loop-protect | 1 | 0 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.lsa-arrival | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.graceful-restart-cfg.ignore-lost-interface | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distance.intra-area | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distance.inter-area | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.distance.external | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.svi-interfaces.retransmit-interval | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.md-password-type | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.md-key-id | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.md-cipherpassword | 0 | 1 | 1 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.timers.lsa-throttle.start-time | 0 | 1 | 1 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.ether-interfaces.dead-interval | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.rfc1583-compatibility | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.lag-interfaces.ciphertext-password | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.sub-interfaces.priority | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.tunnel-interfaces.passive | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.tunnel-interfaces.priority | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.areas.tunnel-interfaces.tunnel-id | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.default-information-origin.always-metric | 0 | 0 | 0 |
| aruba-ospfv2 | aruba-ospfv2:ospfv2.profile.routers.graceful-restart-cfg.helper-strict-lsa-check | 0 | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.svi-interfaces.hello-interval | 0 | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.svi-interfaces.dead-interval | 0 | 0 | 0 |
| aruba-ospfv3 | aruba-ospfv3:ospfv3.profile.routers.areas.ether-interfaces.hello-interval | 0 | 0 | 0 |

---

## Summary by Yang Module (Leafs NOT in UI)

Aggregated customer usage by Yang module for leafs not present in UI:

| Yang Module | Total Leafs Not in UI | Max Customer Count | Avg Customer Count |
|-------------|----------------------|--------------------|--------------------|
| aruba-management-user | 6 | 13229 | 2265 |
| aruba-local-management | 53 | 6319 | 757 |
| aruba-sw-port-profile | 86 | 3837 | 131 |
| aruba-vlan-range | 21 | 3358 | 419 |
| aruba-named-condition | 3 | 2725 | 1889 |
| aruba-auth-server | 7 | 2505 | 512 |
| aruba-snmp | 32 | 2357 | 408 |
| aruba-loop-protect | 4 | 1991 | 1212 |
| aruba-switch-profiles | 2 | 1866 | 1866 |
| aruba-qos-dscp | 7 | 1839 | 1031 |
| aruba-switch-system | 26 | 1696 | 311 |
| aruba-client-insight | 3 | 1669 | 1429 |
| aruba-logging | 34 | 1627 | 251 |
| aruba-vsx-pair | 18 | 1379 | 465 |
| aruba-qos | 3 | 1327 | 587 |
| aruba-mirror | 17 | 1300 | 512 |
| aruba-certificate-rcp | 7 | 1089 | 164 |
| aruba-devicefingerprinting-profile | 11 | 1026 | 465 |
| aruba-remote-management | 6 | 955 | 425 |
| aruba-switch-chassis | 7 | 949 | 407 |
| aruba-policy | 14 | 934 | 178 |
| aruba-dhcp-pool | 4 | 863 | 218 |
| aruba-hardware-module-profile | 6 | 844 | 430 |
| aruba-ntp | 11 | 742 | 103 |
| aruba-qos-global | 18 | 737 | 163 |
| aruba-role | 8 | 598 | 142 |
| aruba-ip-icmp-tcp | 4 | 555 | 292 |
| aruba-vrf | 3 | 536 | 206 |
| aruba-device-profile | 1 | 464 | 464 |
| aruba-auth-server-global | 5 | 462 | 135 |
| aruba-port-security | 4 | 423 | 298 |
| aruba-snmp-trap | 5 | 400 | 312 |
| aruba-sflow | 12 | 395 | 203 |
| aruba-dns | 7 | 392 | 198 |
| aruba-qos-schedule | 15 | 389 | 104 |
| aruba-interface-vlan | 60 | 378 | 21 |
| aruba-qos-queue | 6 | 361 | 218 |
| aruba-device-certificate | 16 | 349 | 65 |
| aruba-lldp | 25 | 345 | 31 |
| aruba-job-scheduler | 31 | 279 | 86 |
| aruba-cdp | 2 | 277 | 277 |
| aruba-aaa-profile | 2 | 248 | 149 |
| aruba-interface-ethernet | 102 | 246 | 21 |
| aruba-dhcp-snooping | 5 | 216 | 51 |
| aruba-vlan | 19 | 191 | 26 |
| aruba-interface-vxlan | 13 | 181 | 86 |
| aruba-bgp | 47 | 172 | 12 |
| aruba-object-group | 11 | 156 | 88 |
| aruba-role-gpid | 1 | 132 | 132 |
| aruba-fault-monitor | 15 | 106 | 30 |
| aruba-firmware-management | 3 | 103 | 39 |
| aruba-copp | 4 | 94 | 82 |
| aruba-dhcp-snooping-interface | 4 | 92 | 47 |
| aruba-switch-stack | 3 | 88 | 45 |
| aruba-nexthop-group | 6 | 80 | 57 |
| aruba-ipfix-flow-exporter | 10 | 77 | 38 |
| aruba-ipfix-flow-monitor | 6 | 76 | 50 |
| aruba-ipfix-flow-record | 25 | 75 | 42 |
| aruba-interface-portchannel | 33 | 73 | 9 |
| aruba-flow-tracking | 7 | 72 | 22 |
| aruba-lacp | 2 | 72 | 57 |
| aruba-ip-lockdown | 2 | 71 | 71 |
| aruba-udp-broadcast-forwarder | 2 | 60 | 60 |
| aruba-interface-tunnel | 5 | 56 | 13 |
| aruba-mirror-endpoint | 10 | 51 | 23 |
| aruba-traffic-insight | 11 | 48 | 28 |
| aruba-ospfv2 | 62 | 48 | 6 |
| aruba-keychain | 12 | 47 | 18 |
| aruba-mgmd | 4 | 46 | 18 |
| aruba-ipsla | 20 | 44 | 12 |
| aruba-nae-lite | 26 | 42 | 6 |
| aruba-static-route | 12 | 40 | 8 |
| aruba-dhcp-relay | 1 | 39 | 39 |
| aruba-psm | 3 | 38 | 32 |
| aruba-mvrp | 2 | 35 | 35 |
| aruba-nd-snooping | 5 | 34 | 15 |
| aruba-client-iptracker | 1 | 31 | 31 |
| aruba-track-object | 4 | 30 | 12 |
| aruba-mac-lockout | 3 | 30 | 21 |
| aruba-dhcp-client | 3 | 28 | 19 |
| aruba-interface-subinterface | 16 | 27 | 5 |
| aruba-mka | 8 | 23 | 13 |
| aruba-macsec | 8 | 23 | 7 |
| aruba-vrrp-interface | 2 | 20 | 14 |
| aruba-routemap | 5 | 20 | 7 |
| aruba-static-mac | 5 | 19 | 19 |
| aruba-l3-route | 3 | 18 | 12 |
| aruba-rip | 43 | 17 | 6 |
| aruba-ptp | 8 | 16 | 12 |
| aruba-est | 1 | 16 | 16 |
| aruba-nd-snooping-interface | 4 | 15 | 8 |
| aruba-config-checkpoint | 3 | 15 | 10 |
| aruba-ufd | 9 | 13 | 7 |
| aruba-qos-threshold-profile | 15 | 13 | 3 |
| aruba-dynamic-arp-inspection-interface | 2 | 12 | 12 |
| aruba-external-storage | 8 | 12 | 9 |
| aruba-qos-cos | 5 | 11 | 10 |
| aruba-countermon | 2 | 9 | 9 |
| aruba-smartlink | 11 | 9 | 4 |
| aruba-erps | 21 | 9 | 5 |
| aruba-ubt | 2 | 7 | 7 |
| aruba-dsm | 4 | 6 | 3 |
| aruba-container | 13 | 6 | 2 |
| aruba-feature-pack | 7 | 6 | 6 |
| aruba-ip-binding | 7 | 6 | 6 |
| aruba-advanced-intelligent-forwarding | 4 | 5 | 3 |
| aruba-sysmon | 3 | 4 | 4 |
| aruba-rmon-alarm | 6 | 4 | 4 |
| aruba-dhcp-server | 5 | 3 | 3 |
| aruba-ip-lockdown-interface | 3 | 3 | 2 |
| aruba-ip-routing | 5 | 3 | 2 |
| aruba-pim | 4 | 3 | 2 |
| aruba-interface-loopback | 1 | 2 | 2 |
| aruba-container-network | 6 | 2 | 2 |
| aruba-qos-pool | 6 | 2 | 2 |
| aruba-ospfv3 | 7 | 1 | 0 |
| aruba-aaa-captive-portal | 1 | 1 | 1 |
