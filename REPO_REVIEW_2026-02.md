# GitHub Repository Review - February 2026

Review of all 80 repositories in the BadgerOps GitHub account with recommendations for archiving, deleting, or updating.

## Actively Maintained - Keep (5 repos)

| Repo | Notes |
|---|---|
| **grapheon** | Active (Feb 2026), 18 releases, network analysis tool |
| **WOTSapp** | Active (Feb 2026), 13 releases, military class comm platform |
| **cloudpam** | Active, 114 commits, 36 open issues, Go/React IPAM tool |
| **salt-workspace** | Most popular (16 stars, 10 forks), companion to blog series |
| **badgerops** | Personal/profile repo |

## Worth Updating (4 repos)

| Repo | Action Needed |
|---|---|
| **network-trainer** | Add a GitHub description (currently blank) |
| **scripts** | Clean up/organize, address 1 open issue |
| **rust-learning** | Keep if still learning Rust, otherwise archive |
| **badgerlab** | Flesh out or merge docker-compose/setup into `scripts` |

## Archive - Conference Talks (3 repos)

| Repo | Notes |
|---|---|
| **bsides-if-2022** | 2022 mTLS talk, historical value only |
| **grrcon-talk-2021** | 2021 talk, no activity since |
| **cloudflare-connect-2025** | **Empty repo** - delete or archive |

## Archive - Work/OCP Tools (5 repos)

| Repo | Last Activity |
|---|---|
| **ocpsync** | Jun 2024, stale |
| **epel-offline-sync** | Sep 2024, niche tool |
| **scanner2cpe** | Jun 2024, PoC only |
| **OCImageContentSourceMerge** | Dec 2023, stale |
| **dlserver** | Jul 2024, no description, 6 commits |

## Archive - Learning Repos (4 repos)

| Repo | Notes |
|---|---|
| **golang-learning** | Udemy course exercises, no recent activity |
| **ansible-learning** | No activity since Jul 2023 |
| **openai_scripts** | Last touched Jan 2023 |
| **rust-rpm-sync** | Last Oct 2023 |

## Archive or Delete - Forked Repos (~30 repos)

Unless you have active changes to contribute upstream, these add clutter:

- vmware-horizon-docker (keep only if actively using Horizon)
- parsnip, actions-batch, mirror-registry, oc-mirror
- keycloak, vm-bhyve, linkerd2, telepresence
- mTLS-workshop, minibadge, enterprise-grade-k8s-local
- wazuh-kubernetes, helm-charts, kubernetes-formula
- kustomize-examples, vault-cockroach, uuidaas, saltshaker
- karate, saltstack-vulcan, couchbase-k8, salt (fork)
- digikey-kicad-library, qmk_firmware, salt-formula-prometheus
- yact, BadgeLifeTable2017, vagrant-hostmanager
- kubernetes-the-hard-way, resin-octoprint, vagrant
- routersploit, salt-formula-grafana, openshift-installer

## Archive - Ancient Personal Projects (~20 repos)

| Repo | Last Activity |
|---|---|
| badgerops.github.io | Dec 2023 (archive unless still blogging) |
| synctool | Apr 2024 |
| rpm-builder | Oct 2023 |
| openshift-scratchpad | Oct 2023 |
| RHEL8-STIG | Nov 2023 |
| singlehop-deployer | May 2023 |
| docker-registry-k3os | May 2020 |
| concourse-test | Jun 2017 |
| site-index | Oct 2017 |
| CarParkinator | Jan 2017 |
| elasticsearch-metrics | Jan 2017 |
| ELK-prime | Oct 2016 |
| pepper | Jun 2016 |
| cloudflare-ddns | May 2016 |
| WiFiServer | Nov 2014 |
| cassyaml | Nov 2014 |
| vimrc | Aug 2014 |
| pyapp-framework | Jan 2014 |
| WeatherAlerts | Jan 2014 |
| JiraClient | Sep 2013 |
| rpi-speedtest | May 2017 |
| resin-speedtest | May 2017 |

## Summary

| Action | Count |
|---|---|
| Keep active | 5 |
| Update/improve | 4 |
| Archive | ~55 |
| Delete (empty/useless forks) | ~16 |

### Top Priorities

1. **Delete** `cloudflare-connect-2025` - completely empty
2. **Bulk archive** all 30+ forks not contributed to upstream
3. **Archive** conference talks, learning repos, and ancient projects
4. **Focus** on 5 active projects: grapheon, WOTSapp, cloudpam, salt-workspace, badgerops
5. **Add descriptions** to repos missing them: network-trainer, dlserver, grapheon
