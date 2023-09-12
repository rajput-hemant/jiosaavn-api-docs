---
order: 1
icon: note
---

# Lyrics

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Song lyrics by song ID

!!! Note
Lyrics are only available for a limited set of songs.
!!!

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/lyrics?id=mPTrDSun
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/lyrics?id=mPTrDSun' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|          **Query Parameter**          | **Description** |              **Required**              |
| :-----------------------------------: | :-------------: | :------------------------------------: |
| [!badge variant="contrast" text="id"] |     Song ID     | [!badge variant="primary" text="True"] |
