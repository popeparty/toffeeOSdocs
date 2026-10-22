---
title: Release Lifecycle
---

We've updated our architecture codes! Read more [about the change here](/api/release-targets/#architecture-codes)!

## Currently Supported InDev Builds
| Channel | OS Version | Build | Kernel Version | Date Released | Support End Date | LTS? | Architecture |
|---------|------------|-------|----------------|---------------|------------------|------|------------|
| Alpha | 2.0.0 | 26X03 | 2610NX21 | October 21, 2026 | November 25, 2026 | No | x86_64 |
| Alpha | 2.0.0 | 26B03 | 2610NB21 | October 21, 2026 | November 25, 2026 | No | arm64 |


## Currently Supported Stable Builds
The first LTS build of 2.x will be ``2.1.x``.
| Channel | OS Version | Build | Kernel Version | Date Released | Support End Date | LTS? | Architecture |
|---------|------------|-------|----------------|---------------|------------------|------|------------|
| Stable  | 2.0.0      | 26X02 | 2610NX20 | October 21, 2026 | November 25, 2026 | No | arm64 |
| Stable  | 2.0.0      | 26B02 | 2610NB20 | October 21, 2026 | November 25, 2026 | No | arm64 |

(^) Stable LTS builds are supplemented by point releases (x.x) and are supported until at least this date, after which, you will be able to upgrade to the next LTS release (which comes out around every three months).

___

## Archived & Unsupported Builds
We are no longer showing **all** of these directly on the doc in order to reduce confusion. We plan to list the most recent **Stable** versions below (along with their support end dates) to encourage testers to upgrade.

Builds from pre-ownership reset will have a support end date of November 1, 2026, even if it is not reflected here yet.

| Channel | OS Version | Build | Date Released | Support End Date | LTS? | Architecture |
|---------|------------|------------------|---------------|------------------|------|------------|
| Alpha | 1.7.1 for ARM | 170A1 | February 6, 2022 | November 1, 2026 | No | ARM |
| Alpha | 1.7.0 | 170Y1 | February 1, 2022 | November 1, 2026 | No | x86_64 |
| Alpha | 1.6.6 (x86) LTS | 166X1 | February 1, 2022 | March 1, 2022 (^) | Yes | x86 (final release) |
| Beta | 1.6.5 (x86_64) | 165Y2 |  February 1, 2022 | November 1, 2026 | No | x86_64 |
| Beta | 1.6.5 (x86) LTS | 165X2 | February 1, 2022 | March 1, 2022 (^) | Yes | x86 |
| Stable | 1.6.4 (x86_64) | 163Y4 | January 12, 2022 | November 1, 2026 | No | x86_64 |
| Stable | 1.6.4 (x86) LTS | 163X2 | January 12, 2022 | March 1, 2022 (^) | Yes | x86 |
| Stable  | 1.6.3 (x86_64) | 163rk2b | January 12, 2022 | November 1, 2026 | No | x86_64 |
| Stable | 1.6.3 (x86) LTS | 163rl1 | January 12, 2022 | February 1, 2022 (update to 1.6.4 (x86) LTS) | Yes | x86 |
