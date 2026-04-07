# NetMon Releases

NetMon is a distributed network monitoring platform that uses lightweight agents and a central dashboard to provide visibility into latency, packet loss, incidents, alerts, and reports across multiple sites and endpoints.

This repository distributes the **NetMon Community Edition** release packages.
Commercial editions and expanded licensing are managed separately.

At a high level:
- the **server package** provides the dashboard, API, storage, alerts, and reporting
- the **agent package** runs on monitored endpoints and sends heartbeat, ping, and traceroute data back to the server

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

## Notes

- These ZIPs are prebuilt runtime artifacts.
- Target machines do not need `npm run build` just to run the packaged release.
- Deployment documentation is bundled inside the server package.
- Verify downloaded files against `SHA256SUMS.txt` before deployment.

This repository is for release distribution only.
