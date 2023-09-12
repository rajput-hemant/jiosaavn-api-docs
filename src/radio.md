---
order: 10
icon: rss
---

# Radio

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Create a radio station

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/radio/create?name=arijit+singh&type=artist&language=hindi
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/radio/create?name=arijit+singh&type=artist&language=hindi' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|             **Query Parameter**             |                                                                                                    **Description**                                                                                                     |              **Required**               |
| :-----------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
|   [!badge variant="contrast" text="name"]   |                                                                                                          Name                                                                                                          | [!badge variant="primary" text="True"]  |
|   [!badge variant="contrast" text="type"]   |                                                                                   Radio Station Type `Artist`, `Featured`, `Entity`                                                                                    | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="language"] | one or more comma separated languages </br>`hindi`, `english`, `punjabi`, `tamil`, `telugu`, `marathi`,`gujarati`, `bengali`, `kannada`, `bhojpuri`, `malayalam`, `urdu`, `haryanvi`, `rajasthani`, `odia`, `assamese` | [!badge variant="primary" text="False"] |

## Get radio station songs

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/radio/songs?id=554BiiZWBhKTnGFN8gtibAo-jpD3W13NJhephHpVFm,Pt2PDx7fzVA__~^~artist_radio~^~459320
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/radio/songs?id=554BiiZWBhKTnGFN8gtibAo-jpD3W13NJhephHpVFm,Pt2PDx7fzVA__~^~artist_radio~^~459320' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|           **Query Parameter**            | **Description** |              **Required**               |
| :--------------------------------------: | :-------------: | :-------------------------------------: |
|  [!badge variant="contrast" text="id"]   |   Station ID    | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="count"] | Count of songs  | [!badge variant="primary" text="False"] |
| [!badge variant="contrast" text="next"]  |   Next Index    | [!badge variant="primary" text="False"] |
