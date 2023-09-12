---
order: 1000
icon: package
---

# Homepage Data

Get launch data from <https://jiosaavn.com> homepage for different modules such as `songs`, `albums`, `trending`, `charts`, `playlists`, `artists`, `new-releases`, `podcasts`, `radio` and `featured-playlists`, etc.

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

+++ Request

HTTP

```sh
https://jiosaavn.shuttleapp.rs/modules?language=hindi,english
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/modules?language=hindi,english' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|           **Query** **Parameter**           |                                                                                                    **Description**                                                                                                    |              **Required**               |
| :-----------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
| [!badge variant="contrast" text="language"] | one or more comma separated languages</br>`hindi`, `english`, `punjabi`, `tamil`, `telugu`, `marathi`,`gujarati`, `bengali`, `kannada`, `bhojpuri`, `malayalam`, `urdu`, `haryanvi`, `rajasthani`, `odia`, `assamese` | [!badge variant="primary" text="False"] |
