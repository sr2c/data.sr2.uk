---
schema: default
title: Currently running Tor Relays
organization: The Tor Project, Inc.
notes: |
    Details about currently running Tor Relays. This data is based on network statuses
    published by the Tor directories, server descriptors published by relays, and data published
    by the Tor network service TorDNSEL. Details documents use the most recently published
    data from these sources, which may lead to contradictions between fields based on different
    sources in rare edge cases.
resources:
- name: Tor Relays Details JSON
  url: 'https://onionoo.torproject.org/details?search=type:relay%20running:true'
  format: json
- name: Tor Relays Summary JSON
  url: 'https://onionoo.torproject.org/summary?search=type:relay%20running:true'
  format: json
  license: 'https://creativecommons.org/publicdomain/zero/1.0/'
category:
- Internet Censorship
- Internet Privacy
maintainer: Tor Metrics
maintainer_email: https://lists.torproject.org/cgi-bin/mailman/listinfo/network-health
---
