---
order: 900
icon: globe
---

# Search All

Search songs, albums, playlists, artists, shows etc with a query.

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/search/all?query=ram+siya+ram
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/search/all?query=ram+siya+ram' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|           **Query Parameter**            | **Description** |              **Required**              |
| :--------------------------------------: | :-------------: | :------------------------------------: |
| [!badge variant="contrast" text="query"] |  Search query   | [!badge variant="primary" text="True"] |
