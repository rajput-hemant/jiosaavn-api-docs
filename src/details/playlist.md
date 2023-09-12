---
order: 80
icon: log
---

# Playlist Details

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Playlist details by ID

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/playlist?id=159144718
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/playlist?id=159144718' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|          **Query Parameter**          | **Description** |              **Required**              |
| :-----------------------------------: | :-------------: | :------------------------------------: |
| [!badge variant="contrast" text="id"] |   Playlist ID   | [!badge variant="primary" text="True"] |
