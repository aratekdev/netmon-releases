# NetMon Community Edition

NetMon is a distributed network monitoring platform designed to give centralized visibility into network health across multiple sites, endpoints, and targets.

It combines lightweight monitoring agents with a central dashboard to track latency, packet loss, incidents, alerts, and operational reports in one self-hosted system.

This repository distributes the **NetMon Community Edition** release packages.
Commercial editions and expanded licensing are managed separately.

## What NetMon Does

At a high level:
- the **server package** provides the dashboard, API, storage, alerts, and reporting
- the **agent package** runs on monitored endpoints and sends heartbeat, ping, and traceroute data back to the server

This allows teams to monitor network health from real endpoints across different locations instead of relying on checks from only one central point.

## Key Features

- Distributed monitoring with lightweight agents
- Central dashboard for multi-agent visibility
- Multi-target monitoring per agent
- Real-time latency and packet loss tracking
- Aligned multi-target graphing
- Incident detection for agent down, target down, intermittent loss, high latency, route changes, and system degradation
- Traceroute collection and route-change visibility
- Email alerts and scheduled reports
- TXT and PDF reporting
- Windows and Linux agent support
- Linux server deployment with systemd support
- Memory or SQLite storage
- Offline queue resiliency for agents

## Why NetMon

NetMon is built for practical self-hosted monitoring in real environments.

It is well suited for:
- branch and site monitoring
- internal network visibility
- endpoint-to-target performance checks
- lightweight Linux server deployments
- teams that want centralized visibility without a heavy monitoring stack

Compared with more complex monitoring platforms, NetMon focuses on:
- lightweight deployment
- simple operational model
- real endpoint visibility
- centralized incident and reporting workflow
- practical self-hosted operation

## Community Edition

This repository is used to distribute official NetMon Community Edition release packages.

Download the latest deployment assets from the **Releases** page.

## Current Release Assets

- `netmon-server-20260406-195615Z.zip`
- `netmon-agent-20260406-195615Z.zip`
- `SHA256SUMS.txt`
- `RELEASE_INFO.txt`

## Included Documentation

Deployment and operations documentation is bundled inside `netmon-server-20260406-195615Z.zip`.

Included guides:
- `docs/client/START-HERE.md`
- `docs/client/SERVER-DEPLOYMENT.md`
- `docs/client/AGENT-WINDOWS.md`
- `docs/client/AGENT-LINUX.md`
- `docs/client/DAILY-USE.md`
- `docs/client/TROUBLESHOOTING.md`
- `docs/client/SOFTWARE-UPDATES.md`
- `docs/client/RESET.md`
- `docs/client/FULL-DEPLOYMENT-NO-VARS.md`

## Commercial Editions

This repository distributes the NetMon Community Edition.

Commercial editions with expanded licensing, deployment options, and support are managed separately.

For commercial inquiries, plan availability, or licensing requests, contact: `aratek.dev@gmail.com`

## Notes

- These ZIPs are prebuilt runtime artifacts.
- Target machines do not need `npm run build` just to run the packaged release.
- Deployment documentation is bundled inside the server package.
- Verify downloaded files against `SHA256SUMS.txt` before deployment.

This repository is for release distribution only.
