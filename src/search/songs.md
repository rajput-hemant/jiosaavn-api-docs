---
order: 700
icon: play
---

# Search Songs

Search songs by query.

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/search/songs?query=ram+siya+ram&page=1&limit=2
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/search/songs?query=ram+siya+ram&page=1&limit=2' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|           **Query Parameter**            |     **Description**     | **Default** |              **Required**               |
| :--------------------------------------: | :---------------------: | :---------: | :-------------------------------------: |
| [!badge variant="contrast" text="query"] |      Search query       |      -      | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="page"]  |      Current page       |      1      | [!badge variant="primary" text="False"] |
| [!badge variant="contrast" text="limit"] | limit number of results |     10      | [!badge variant="primary" text="False"] |
