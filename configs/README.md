# Configs

These files are **reconstructed from the CLI screenshots** in `../screenshots/`. They contain only what the screenshots show, so some parts are missing (noted inside each file).

| File | Device | From screenshots |
| --- | --- | --- |
| `main-campus-router.txt` | Main campus router (2911) | 05, 06, 07 |
| `branch-campus-router.txt` | Branch campus router (2911) | 08, 09 |
| `main-campus-l3-switch.txt` | Main campus 3650 | 03, 04 |
| `admin-switch.txt` | Admin access switch (2960) | 02 |
| `email-server.txt` | External email server | 10, 11 |

## To complete this folder

Export each device's full configuration from Packet Tracer with `show running-config` and save it here, replacing the reconstructed file:

- Routers: main campus, branch campus, cloud
- Multilayer switches: main campus, branch campus
- Access switches: Admin, HR, Finance, Business, E&C, A&D, Student Labs, IT, branch Staff, branch Student Labs

Before committing, replace any passwords with `<removed>`.
