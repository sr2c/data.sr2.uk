---
schema: default
title: Currently running Tor Bridges
organization: The Tor Project, Inc.
notes: |
  Details about currently running Tor Bridges. This data is based on network statuses
  published by the Tor directories, server descriptors published by bridges, and data published
  by the Tor network service BridgeDB. Details documents use the most recently published
  data from these sources, which may lead to contradictions between fields based on different
  sources in rare edge cases.
resources:
- name: Tor Bridges Details JSON
  url: 'https://onionoo.torproject.org/details?search=type:bridge%20running:true'
  format: json
- name: Tor Bridges Summary JSON
  url: 'https://onionoo.torproject.org/summary?search=type:bridge%20running:true'
  format: json
license: 'https://creativecommons.org/publicdomain/zero/1.0/'
category:
- Internet Censorship
- Internet Privacy
maintainer: Tor Metrics
maintainer_email: https://lists.torproject.org/cgi-bin/mailman/listinfo/network-health
---
