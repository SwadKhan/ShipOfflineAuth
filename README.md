# ShipOfflineAuth

Hackathon project: offline authentication between ships, ports and an issuing authority, for situations where ports fall back to paper manifests.

Forked from [AdityaMitra5102/ShipOfflineAuth](https://github.com/AdityaMitra5102/ShipOfflineAuth).

## My contribution

Built during the IACyC 2026 hackathon at Kadir Has University (team Sinking Ship, Best Collaborators award). I worked on the **Port** and **Ship** components: the port-side credential flow, where an officer enters a Ship ID and prints it as an offline QR credential, and the ship side that presents it. A standalone version of the port credential page is in [Project_conference](https://github.com/SwadKhan/Project_conference).

## Structure

| Folder | Role |
| --- | --- |
| `Authority/` | Issuing authority |
| `Port/` | Port-side verification and credential printing |
| `Ship/` | Ship-side credential |
