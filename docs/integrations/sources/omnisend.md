# Omnisend

## Sync overview

This source can sync data from the [Omnisend API](https://api-docs.omnisend.com/reference/intro). At present this connector only supports full refresh syncs meaning that each time you use the connector it will sync all available records from scratch. Please use cautiously if you expect your API to have a lot of records.

## This Source Supports the Following Streams

- contacts
- campaigns
- carts
- orders
- products

### Features

| Feature           | Supported?\(Yes/No\) |
|:------------------|:---------------------|
| Full Refresh Sync | Yes                  |
| Incremental Sync  | No                   |

### Performance considerations

The connector has a rate limit of 400 requests per 1 minute.

## Getting started

### Requirements

- Omnisend API Key

## Changelog

<details>
  <summary>Expand to review</summary>

| Version | Date       | Pull Request                                             | Subject        |
|:--------|:-----------| :------------------------------------------------------- | :------------- |
| 0.3.11 | 2025-05-10 | [60078](https://github.com/airbytehq/airbyte/pull/60078) | Update dependencies |
| 0.3.10 | 2025-05-03 | [59470](https://github.com/airbytehq/airbyte/pull/59470) | Update dependencies |
| 0.3.9 | 2025-04-27 | [59086](https://github.com/airbytehq/airbyte/pull/59086) | Update dependencies |
| 0.3.8 | 2025-04-19 | [58483](https://github.com/airbytehq/airbyte/pull/58483) | Update dependencies |
| 0.3.7 | 2025-04-12 | [57871](https://github.com/airbytehq/airbyte/pull/57871) | Update dependencies |
| 0.3.6 | 2025-04-05 | [57341](https://github.com/airbytehq/airbyte/pull/57341) | Update dependencies |
| 0.3.5 | 2025-03-29 | [56802](https://github.com/airbytehq/airbyte/pull/56802) | Update dependencies |
| 0.3.4 | 2025-03-22 | [56170](https://github.com/airbytehq/airbyte/pull/56170) | Update dependencies |
| 0.3.3 | 2025-03-08 | [55057](https://github.com/airbytehq/airbyte/pull/55057) | Update dependencies |
| 0.3.2 | 2025-02-23 | [54561](https://github.com/airbytehq/airbyte/pull/54561) | Update dependencies |
| 0.3.1 | 2025-02-15 | [53999](https://github.com/airbytehq/airbyte/pull/53999) | Update dependencies |
| 0.3.0 | 2025-02-07 | [53208](https://github.com/airbytehq/airbyte/pull/53208) | update schemas and make dynamic |
| 0.2.11 | 2025-02-08 | [53487](https://github.com/airbytehq/airbyte/pull/53487) | Update dependencies |
| 0.2.10 | 2025-02-03 | [52699](https://github.com/airbytehq/airbyte/pull/52699) | Fix pagination |
| 0.2.9 | 2025-02-01 | [52987](https://github.com/airbytehq/airbyte/pull/52987) | Update dependencies |
| 0.2.8 | 2025-01-25 | [52478](https://github.com/airbytehq/airbyte/pull/52478) | Update dependencies |
| 0.2.7 | 2025-01-18 | [51859](https://github.com/airbytehq/airbyte/pull/51859) | Update dependencies |
| 0.2.6 | 2025-01-11 | [51205](https://github.com/airbytehq/airbyte/pull/51205) | Update dependencies |
| 0.2.5 | 2024-12-28 | [50291](https://github.com/airbytehq/airbyte/pull/50291) | Update dependencies |
| 0.2.4 | 2024-12-14 | [49674](https://github.com/airbytehq/airbyte/pull/49674) | Update dependencies |
| 0.2.3 | 2024-12-12 | [49365](https://github.com/airbytehq/airbyte/pull/49365) | Update dependencies |
| 0.2.2 | 2024-12-11 | [48284](https://github.com/airbytehq/airbyte/pull/48284) | Starting with this version, the Docker image is now rootless. Please note that this and future versions will not be compatible with Airbyte versions earlier than 0.64 |
| 0.2.1 | 2024-10-29 | [47474](https://github.com/airbytehq/airbyte/pull/47474) | Update dependencies |
| 0.2.0 | 2024-08-19 | [44411](https://github.com/airbytehq/airbyte/pull/44411) | Refactor connector to manifest-only format |
| 0.1.13 | 2024-08-17 | [44307](https://github.com/airbytehq/airbyte/pull/44307) | Update dependencies |
| 0.1.12 | 2024-08-12 | [43727](https://github.com/airbytehq/airbyte/pull/43727) | Update dependencies |
| 0.1.11 | 2024-08-10 | [43581](https://github.com/airbytehq/airbyte/pull/43581) | Update dependencies |
| 0.1.10 | 2024-08-03 | [42745](https://github.com/airbytehq/airbyte/pull/42745) | Update dependencies |
| 0.1.9 | 2024-07-20 | [42325](https://github.com/airbytehq/airbyte/pull/42325) | Update dependencies |
| 0.1.8 | 2024-07-13 | [41697](https://github.com/airbytehq/airbyte/pull/41697) | Update dependencies |
| 0.1.7 | 2024-07-10 | [41454](https://github.com/airbytehq/airbyte/pull/41454) | Update dependencies |
| 0.1.6 | 2024-07-09 | [41319](https://github.com/airbytehq/airbyte/pull/41319) | Update dependencies |
| 0.1.5 | 2024-07-06 | [40969](https://github.com/airbytehq/airbyte/pull/40969) | Update dependencies |
| 0.1.4 | 2024-06-28 | [38664](https://github.com/airbytehq/airbyte/pull/38664) | Make connector compatible with Builder |
| 0.1.3 | 2024-06-25 | [40440](https://github.com/airbytehq/airbyte/pull/40440) | Update dependencies |
| 0.1.2 | 2024-06-22 | [40167](https://github.com/airbytehq/airbyte/pull/40167) | Update dependencies |
| 0.1.1 | 2024-05-30 | [38533](https://github.com/airbytehq/airbyte/pull/38533) | [autopull] base image + poetry + up_to_date |
| 0.1.0 | 2022-10-25 | [18577](https://github.com/airbytehq/airbyte/pull/18577) | Initial commit |

</details>
