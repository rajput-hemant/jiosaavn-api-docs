---
order: 90
icon: stack
---

# Album Details

!!! Note
<https://jiosaavn-api-ts.vercel.app> or <https://jiosaavn-api-rs.vercel.app> are only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Album details by `ID`, `link` or `token`

+++ Request

**HTTP**

- **ID**

```bash
https://jiosaavn-api-ts.vercel.app/album?id=25500145
```

```bash
https://jiosaavn-api-rs.vercel.app/album?id=25500145
```

- **Link**

```bash
https://jiosaavn-api-ts.vercel.app/album?link=https://www.jiosaavn.com/album/ram-siya-ram/cy9LsEw-pn0_
```

```bash
https://jiosaavn-api-rs.vercel.app/album?link=https://www.jiosaavn.com/album/ram-siya-ram/cy9LsEw-pn0_
```

- **Token**

```bash
https://jiosaavn-api-ts.vercel.app/album?token=cy9LsEw-pn0_
```

```bash
https://jiosaavn-api-rs.vercel.app/album?token=cy9LsEw-pn0_
```

**cURL**

```bash
curl -X GET 'https://jiosaavn-api-ts.vercel.app/album?id=25500145' \
 -H 'content-type: application/json'
```

```bash
curl -X GET 'https://jiosaavn-api-rs.vercel.app/album?id=25500145' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Album Details fetched successfully",
  "data": {
    "id": "25500145",
    "name": "Ram Siya Ram",
    "subtitle": "Sachet Tandon",
    "type": "album",
    "language": "hindi",
    "play_count": 0,
    "explicit": false,
    "year": 2021,
    "url": "https://www.jiosaavn.com/album/ram-siya-ram/cy9LsEw-pn0_",
    "header_desc": "2021 · Hindi Album · Sachet Tandon",
    "list_count": 1,
    "list_type": "song",
    "image": [
      {
        "quality": "50x50",
        "link": "https://c.saavncdn.com/215/Ram-Siya-Ram-Hindi-2021-20210222031001-50x50.jpg"
      },
      {
        "quality": "150x150",
        "link": "https://c.saavncdn.com/215/Ram-Siya-Ram-Hindi-2021-20210222031001-150x150.jpg"
      },
      {
        "quality": "500x500",
        "link": "https://c.saavncdn.com/215/Ram-Siya-Ram-Hindi-2021-20210222031001-500x500.jpg"
      }
    ],
    "artist_map": {
      "artists": [
        {
          "id": "3623110",
          "name": "Sachet Tandon",
          "url": "https://www.jiosaavn.com/artist/sachet-tandon-songs/wVwhaAx3x6c_",
          "role": "",
          "type": "artist",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_500x500.jpg"
            }
          ]
        }
      ],
      "featured_artists": [],
      "primary_artists": [
        {
          "id": "3623110",
          "name": "Sachet Tandon",
          "url": "https://www.jiosaavn.com/artist/sachet-tandon-songs/wVwhaAx3x6c_",
          "role": "",
          "type": "artist",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_500x500.jpg"
            }
          ]
        }
      ]
    },
    "song_count": 1,
    "is_dolby_content": false,
    "copyright_text": "© 2021 Super Cassettes Industries Private Limited",
    "label_url": "/label/-albums/6DLuXO3VoTo_",
    "songs": [
      {
        "id": "HLulXlir",
        "name": "Ram Siya Ram",
        "subtitle": "Sachet Tandon - Ram Siya Ram",
        "type": "song",
        "url": "https://www.jiosaavn.com/song/ram-siya-ram/OCQeXSxcXkE",
        "image": [
          {
            "quality": "50x50",
            "link": "https://c.saavncdn.com/215/Ram-Siya-Ram-Hindi-2021-20210222031001-50x50.jpg"
          },
          {
            "quality": "150x150",
            "link": "https://c.saavncdn.com/215/Ram-Siya-Ram-Hindi-2021-20210222031001-150x150.jpg"
          },
          {
            "quality": "500x500",
            "link": "https://c.saavncdn.com/215/Ram-Siya-Ram-Hindi-2021-20210222031001-500x500.jpg"
          }
        ],
        "language": "hindi",
        "year": 2021,
        "header_desc": "",
        "play_count": 64474183,
        "explicit": false,
        "list": "",
        "list_type": "",
        "list_count": 0,
        "music": "Poonam Thakkar",
        "artist_map": {
          "artists": [
            {
              "id": "9521286",
              "name": "Poonam Thakkar",
              "url": "https://www.jiosaavn.com/artist/poonam-thakkar-songs/K9zFVB-gAME_",
              "role": "music",
              "type": "artist",
              "image": ""
            },
            {
              "id": "3623110",
              "name": "Sachet Tandon",
              "url": "https://www.jiosaavn.com/artist/sachet-tandon-songs/wVwhaAx3x6c_",
              "role": "singer",
              "type": "artist",
              "image": [
                {
                  "quality": "50x50",
                  "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_50x50.jpg"
                },
                {
                  "quality": "150x150",
                  "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_150x150.jpg"
                },
                {
                  "quality": "500x500",
                  "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_500x500.jpg"
                }
              ]
            },
            {
              "id": "461011",
              "name": "Shabbir Ahmed",
              "url": "https://www.jiosaavn.com/artist/shabbir-ahmed-songs/CUgZ-dg1Y9w_",
              "role": "lyricist",
              "type": "artist",
              "image": [
                {
                  "quality": "50x50",
                  "link": "https://c.saavncdn.com/artists/Shabbir_Ahmed_50x50.jpg"
                },
                {
                  "quality": "150x150",
                  "link": "https://c.saavncdn.com/artists/Shabbir_Ahmed_150x150.jpg"
                },
                {
                  "quality": "500x500",
                  "link": "https://c.saavncdn.com/artists/Shabbir_Ahmed_500x500.jpg"
                }
              ]
            }
          ],
          "featured_artists": [],
          "primary_artists": [
            {
              "id": "3623110",
              "name": "Sachet Tandon",
              "url": "https://www.jiosaavn.com/artist/sachet-tandon-songs/wVwhaAx3x6c_",
              "role": "primary_artists",
              "type": "artist",
              "image": [
                {
                  "quality": "50x50",
                  "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_50x50.jpg"
                },
                {
                  "quality": "150x150",
                  "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_150x150.jpg"
                },
                {
                  "quality": "500x500",
                  "link": "https://c.saavncdn.com/artists/Sachet_Tandon_001_20191130070910_500x500.jpg"
                }
              ]
            }
          ]
        },
        "album": "Ram Siya Ram",
        "album_id": "25500145",
        "album_url": "https://www.jiosaavn.com/album/ram-siya-ram/cy9LsEw-pn0_",
        "label": "",
        "label_url": "/label/-albums/6DLuXO3VoTo_",
        "origin": "album",
        "is_dolby_content": false,
        "320kbps": true,
        "download_url": [
          {
            "quality": "12kbps",
            "link": "https://aac.saavncdn.com/215/5a6134d5860b9b47cc9fb2e058e22a18_12.mp4"
          },
          {
            "quality": "48kbps",
            "link": "https://aac.saavncdn.com/215/5a6134d5860b9b47cc9fb2e058e22a18_48.mp4"
          },
          {
            "quality": "96kbps",
            "link": "https://aac.saavncdn.com/215/5a6134d5860b9b47cc9fb2e058e22a18_96.mp4"
          },
          {
            "quality": "160kbps",
            "link": "https://aac.saavncdn.com/215/5a6134d5860b9b47cc9fb2e058e22a18_160.mp4"
          },
          {
            "quality": "320kbps",
            "link": "https://aac.saavncdn.com/215/5a6134d5860b9b47cc9fb2e058e22a18_320.mp4"
          }
        ],
        "duration": 265,
        "rights": {
          "code": "1",
          "cacheable": "true",
          "delete_cached_object": "false",
          "reason": "Pro Only"
        },
        "has_lyrics": true,
        "lyrics_id": "",
        "lyrics_snippet": "Lyrics",
        "starred": false,
        "release_date": "2021-02-22",
        "triller_available": false,
        "copyright_text": "℗ 2021 Super Cassettes Industries Private Limited",
        "vcode": "010910091238843",
        "vlink": "https://jiotunepreview.jio.com/content/Converted/010910091195734.mp3"
      }
    ],
    "modules": {
      "recommend": {
        "title": "You Might Like",
        "subtitle": "",
        "position": 2,
        "source": "/album/recommend",
        "params": { "id": "25500145" }
      },
      "currently_trending": {
        "title": "Currently Trending Albums",
        "subtitle": "",
        "position": 3,
        "source": "/get/trending",
        "params": { "type": "album", "lang": "hindi" }
      },
      "top_albums_from_same_year": {
        "title": "Top Albums from Same Year",
        "subtitle": "",
        "position": 4,
        "source": "/album/same-year",
        "params": { "year": "2021", "lang": "hindi" }
      },
      "artists": {
        "title": "Artists",
        "subtitle": "",
        "position": 5,
        "source": "artists"
      }
    }
  }
}
```

+++

|                                                        **Query Parameter**                                                         |                                                                **Description**                                                                |              **Required**               |
| :--------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
| [!badge variant="contrast" text="id"] **/** [!badge variant="contrast" text="link"] **/** [!badge variant="contrast" text="token"] | id(s) - comma seperated **/**<br>link from <https://jiosaavn.com> **/**<br>token ->https://www.jiosaavn.com/album/ram-siya-ram/`cy9LsEw-pn0_` | [!badge variant="primary" text="True"]  |
|                                              [!badge variant="contrast" text="camel"]                                              |                                                           `camelCase` response keys                                                           | [!badge variant="primary" text="False"] |
|                                               [!badge variant="contrast" text="raw"]                                               |                                                       raw response from `Jiosaavn API`                                                        | [!badge variant="primary" text="False"] |

## Album Recommendations by `Album ID`

+++ Request

**HTTP**

```bash
https://jiosaavn-api-ts.vercel.app/album/recommend?id=25500145
```

```bash
https://jiosaavn-api-rs.vercel.app/album/recommend?id=25500145
```

**cURL**

```bash
curl -X GET 'https://jiosaavn-api-ts.vercel.app/album/recommend?id=25500145' \
 -H 'content-type: application/json'
```

```bash
curl -X GET 'https://jiosaavn-api-rs.vercel.app/album/recommend?id=25500145' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Album Recommendations fetched successfully",
  "data": [
    {
      "id": "45557446",
      "name": "Ram Siya Ram (From &quot;Adipurush&quot;)",
      "subtitle": "",
      "type": "album",
      "language": "",
      "play_count": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/ram-siya-ram-from-adipurush/o21EQ2PGLsk_",
      "header_desc": "",
      "list_count": 0,
      "list_type": "",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/916/Ram-Siya-Ram-From-Adipurush-Hindi-2023-20230530192919-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/916/Ram-Siya-Ram-From-Adipurush-Hindi-2023-20230530192919-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/916/Ram-Siya-Ram-From-Adipurush-Hindi-2023-20230530192919-500x500.jpg"
        }
      ],
      "songs": []
    },
    {
      "id": "30066271",
      "name": "Meri Maa Ke Barabar Koi Nahi",
      "subtitle": "",
      "type": "album",
      "language": "",
      "play_count": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/meri-maa-ke-barabar-koi-nahi/EIICtTXEp4k_",
      "header_desc": "",
      "list_count": 0,
      "list_type": "",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/832/Meri-Maa-Ke-Barabar-Koi-Nahi-Hindi-2021-20220307121001-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/832/Meri-Maa-Ke-Barabar-Koi-Nahi-Hindi-2021-20220307121001-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/832/Meri-Maa-Ke-Barabar-Koi-Nahi-Hindi-2021-20220307121001-500x500.jpg"
        }
      ],
      "songs": []
    },
    {
      "id": "25605376",
      "name": "Krishna Bhajan - Lagan Tumse Laga Baithe",
      "subtitle": "",
      "type": "album",
      "language": "",
      "play_count": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/krishna-bhajan-lagan-tumse-laga-baithe/o21Jcy8VKZg_",
      "header_desc": "",
      "list_count": 0,
      "list_type": "",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/735/Krishna-Bhajan-Lagan-Tumse-Laga-Baithe-Hindi-2021-20210227002702-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/735/Krishna-Bhajan-Lagan-Tumse-Laga-Baithe-Hindi-2021-20210227002702-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/735/Krishna-Bhajan-Lagan-Tumse-Laga-Baithe-Hindi-2021-20210227002702-500x500.jpg"
        }
      ],
      "songs": []
    },
    {
      "id": "39209161",
      "name": "Mere Ghar Ram Aaye Hain",
      "subtitle": "",
      "type": "album",
      "language": "",
      "play_count": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/mere-ghar-ram-aaye-hain/dsife5uVB1k_",
      "header_desc": "",
      "list_count": 0,
      "list_type": "",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/946/Mere-Ghar-Ram-Aaye-Hain-Hindi-2022-20221019191009-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/946/Mere-Ghar-Ram-Aaye-Hain-Hindi-2022-20221019191009-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/946/Mere-Ghar-Ram-Aaye-Hain-Hindi-2022-20221019191009-500x500.jpg"
        }
      ],
      "songs": []
    },
    {
      "id": "42882472",
      "name": "Radhe Radhe",
      "subtitle": "",
      "type": "album",
      "language": "",
      "play_count": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/radhe-radhe/21KgBNjSpFc_",
      "header_desc": "",
      "list_count": 0,
      "list_type": "",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/716/Radhe-Radhe-Hindi-2020-20230222194734-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/716/Radhe-Radhe-Hindi-2020-20230222194734-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/716/Radhe-Radhe-Hindi-2020-20230222194734-500x500.jpg"
        }
      ],
      "songs": []
    }
  ]
}
```

+++

|             **Query Parameter**             |                                                                                                    **Description**                                                                                                    |              **Required**               |
| :-----------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
|    [!badge variant="contrast" text="id"]    |                                                                                                       Album ID                                                                                                        | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="language"] | one or more comma separated languages</br>`hindi`, `english`, `punjabi`, `tamil`, `telugu`, `marathi`,`gujarati`, `bengali`, `kannada`, `bhojpuri`, `malayalam`, `urdu`, `haryanvi`, `rajasthani`, `odia`, `assamese` | [!badge variant="primary" text="False"] |
|  [!badge variant="contrast" text="camel"]   |                                                                                               `camelCase` response keys                                                                                               | [!badge variant="primary" text="False"] |
|   [!badge variant="contrast" text="raw"]    |                                                                                           raw response from `Jiosaavn API`                                                                                            | [!badge variant="primary" text="False"] |

## Albums from `Same year`

+++ Request
**HTTP**

```bash
https://jiosaavn-api-ts.vercel.app/album/recommend?id=25500145
```

```bash
https://jiosaavn-api-rs.vercel.app/album/recommend?id=25500145
```

**cURL**

```bash
curl -X GET 'https://jiosaavn-api-ts.vercel.app/album/same-year?year=2023' \
 -H 'content-type: application/json'
```

```bash
curl -X GET 'https://jiosaavn-api-rs.vercel.app/album/same-year?year=2023' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Albums from 2023 fetched successfully",
  "data": [
    {
      "id": "48109521",
      "name": "Layover",
      "subtitle": "V",
      "type": "album",
      "language": "english",
      "play_count": 0,
      "explicit": false,
      "year": 2023,
      "url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
      "header_desc": "2023 · English Album · V",
      "list_count": 6,
      "list_type": "song",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
        }
      ],
      "artist_map": {
        "artists": [
          {
            "id": "838690",
            "name": "V",
            "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
            "role": "",
            "type": "artist",
            "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "838690",
            "name": "V",
            "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
            "role": "",
            "type": "artist",
            "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
          }
        ]
      },
      "song_count": 6,
      "is_dolby_content": false,
      "copyright_text": "© 2023 BIGHIT MUSIC",
      "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
      "songs": [
        {
          "id": "ImJhW3qC",
          "name": "Rainy Days",
          "subtitle": "V - Layover",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/rainy-days/OQUhWSMDRnA",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 80530,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Freekind., Frankie Scoca",
          "artist_map": {
            "artists": [
              {
                "id": "7819367",
                "name": "Freekind.",
                "url": "https://www.jiosaavn.com/artist/freekind.-songs/Z3gDUO0nywQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "9160091",
                "name": "Frankie Scoca",
                "url": "https://www.jiosaavn.com/artist/frankie-scoca-songs/o1cPORPgys4_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "singer",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "primary_artists",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ]
          },
          "album": "Layover",
          "album_id": "48109521",
          "album_url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "label": "BIGHIT MUSIC",
          "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/031/42f69f5f9094fc3289a22b64ac7e5fbd_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/031/42f69f5f9094fc3289a22b64ac7e5fbd_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/031/42f69f5f9094fc3289a22b64ac7e5fbd_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/031/42f69f5f9094fc3289a22b64ac7e5fbd_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/031/42f69f5f9094fc3289a22b64ac7e5fbd_320.mp4"
            }
          ],
          "duration": 179,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "Rainy days, I'm thinking 'bout you",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "© 2023 BIGHIT MUSIC"
        },
        {
          "id": "LufmI_PU",
          "name": "Blue",
          "subtitle": "V - Layover",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/blue/PB0NXD1vZ2Y",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 1420,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Catharina Stoltenberg, Henriette Motzfeldt, Jinsu Park, Absent Chronicles",
          "artist_map": {
            "artists": [
              {
                "id": "2166009",
                "name": "Catharina Stoltenberg",
                "url": "https://www.jiosaavn.com/artist/catharina-stoltenberg-songs/-L2utgkoaqk_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2166008",
                "name": "Henriette Motzfeldt",
                "url": "https://www.jiosaavn.com/artist/henriette-motzfeldt-songs/P6AuQxs0sO4_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2073929",
                "name": "Jinsu Park",
                "url": "https://www.jiosaavn.com/artist/jinsu-park-songs/C4f1Xdr0JWE_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "4900358",
                "name": "Absent Chronicles",
                "url": "https://www.jiosaavn.com/artist/absent-chronicles-songs/8zvYJ6IPaqk_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "singer",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "primary_artists",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ]
          },
          "album": "Layover",
          "album_id": "48109521",
          "album_url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "label": "BIGHIT MUSIC",
          "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/031/18060dd2ab5bf1c4a29cc0f424b99d40_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/031/18060dd2ab5bf1c4a29cc0f424b99d40_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/031/18060dd2ab5bf1c4a29cc0f424b99d40_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/031/18060dd2ab5bf1c4a29cc0f424b99d40_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/031/18060dd2ab5bf1c4a29cc0f424b99d40_320.mp4"
            }
          ],
          "duration": 149,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "Green, yellow, red, blue",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "© 2023 BIGHIT MUSIC"
        },
        {
          "id": "jaJ4ylJ5",
          "name": "Love Me Again",
          "subtitle": "V - Layover",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/love-me-again/GgkhBQ1cfQY",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 96265,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Freekind., Jinsu Park",
          "artist_map": {
            "artists": [
              {
                "id": "7819367",
                "name": "Freekind.",
                "url": "https://www.jiosaavn.com/artist/freekind.-songs/Z3gDUO0nywQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2073929",
                "name": "Jinsu Park",
                "url": "https://www.jiosaavn.com/artist/jinsu-park-songs/C4f1Xdr0JWE_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "singer",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "primary_artists",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ]
          },
          "album": "Layover",
          "album_id": "48109521",
          "album_url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "label": "BIGHIT MUSIC",
          "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/031/0a0abb428a1573982bad9ee6a8c78db6_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/031/0a0abb428a1573982bad9ee6a8c78db6_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/031/0a0abb428a1573982bad9ee6a8c78db6_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/031/0a0abb428a1573982bad9ee6a8c78db6_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/031/0a0abb428a1573982bad9ee6a8c78db6_320.mp4"
            }
          ],
          "duration": 182,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "I wish you would love me again, no, I don't want nobody else",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "© 2023 BIGHIT MUSIC"
        },
        {
          "id": "LyxHnzOp",
          "name": "Slow Dancing",
          "subtitle": "V - Layover",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/slow-dancing/PBETeRpKeEM",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 3993,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Freekind., Jinsu Park",
          "artist_map": {
            "artists": [
              {
                "id": "7819367",
                "name": "Freekind.",
                "url": "https://www.jiosaavn.com/artist/freekind.-songs/Z3gDUO0nywQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2073929",
                "name": "Jinsu Park",
                "url": "https://www.jiosaavn.com/artist/jinsu-park-songs/C4f1Xdr0JWE_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "singer",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "primary_artists",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ]
          },
          "album": "Layover",
          "album_id": "48109521",
          "album_url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "label": "BIGHIT MUSIC",
          "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/031/06af60be1a66b40a0c7c698ef542cac6_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/031/06af60be1a66b40a0c7c698ef542cac6_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/031/06af60be1a66b40a0c7c698ef542cac6_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/031/06af60be1a66b40a0c7c698ef542cac6_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/031/06af60be1a66b40a0c7c698ef542cac6_320.mp4"
            }
          ],
          "duration": 187,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "Slow dancing until the morning",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "© 2023 BIGHIT MUSIC"
        },
        {
          "id": "Wp8IbZiW",
          "name": "For Us",
          "subtitle": "V - Layover",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/for-us/JxhTeBZqXmQ",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 1294,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Freekind., Monro",
          "artist_map": {
            "artists": [
              {
                "id": "7819367",
                "name": "Freekind.",
                "url": "https://www.jiosaavn.com/artist/freekind.-songs/Z3gDUO0nywQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2916299",
                "name": "Monro",
                "url": "https://www.jiosaavn.com/artist/monro-songs/fdrR9usDTPY_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/252/Baman-English-2019-20190717072608-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/252/Baman-English-2019-20190717072608-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/252/Baman-English-2019-20190717072608-500x500.jpg"
                  }
                ]
              },
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "singer",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "primary_artists",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ]
          },
          "album": "Layover",
          "album_id": "48109521",
          "album_url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "label": "BIGHIT MUSIC",
          "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/031/99a688a28ba2d40f4d854c11e0f55d0e_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/031/99a688a28ba2d40f4d854c11e0f55d0e_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/031/99a688a28ba2d40f4d854c11e0f55d0e_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/031/99a688a28ba2d40f4d854c11e0f55d0e_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/031/99a688a28ba2d40f4d854c11e0f55d0e_320.mp4"
            }
          ],
          "duration": 171,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "Ooooh I wish I could stay with you",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "© 2023 BIGHIT MUSIC"
        },
        {
          "id": "zEVNa2Q7",
          "name": "Slow Dancing (Piano Ver.)",
          "subtitle": "V - Layover",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/slow-dancing-piano-ver./Ci09fxUCZgQ",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/031/Layover-English-2023-20230908093137-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 915,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Freekind., Jinsu Park",
          "artist_map": {
            "artists": [
              {
                "id": "7819367",
                "name": "Freekind.",
                "url": "https://www.jiosaavn.com/artist/freekind.-songs/Z3gDUO0nywQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2073929",
                "name": "Jinsu Park",
                "url": "https://www.jiosaavn.com/artist/jinsu-park-songs/C4f1Xdr0JWE_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "singer",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "838690",
                "name": "V",
                "url": "https://www.jiosaavn.com/artist/v-songs/r11IdHYX7Jw_",
                "role": "primary_artists",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/V_000_20230104102421.jpg"
              }
            ]
          },
          "album": "Layover",
          "album_id": "48109521",
          "album_url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "label": "BIGHIT MUSIC",
          "label_url": "/label/bighit-music-albums/G4mK,OUP0Lo_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/031/fed5953222c3fd531b334fb56d3b7bce_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/031/fed5953222c3fd531b334fb56d3b7bce_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/031/fed5953222c3fd531b334fb56d3b7bce_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/031/fed5953222c3fd531b334fb56d3b7bce_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/031/fed5953222c3fd531b334fb56d3b7bce_320.mp4"
            }
          ],
          "duration": 188,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "© 2023 BIGHIT MUSIC"
        }
      ]
    },
    {
      "id": "48090436",
      "name": "GUTS",
      "subtitle": "Olivia Rodrigo",
      "type": "album",
      "language": "english",
      "play_count": 0,
      "explicit": true,
      "year": 2023,
      "url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
      "header_desc": "2023 · English Album · Olivia Rodrigo",
      "list_count": 12,
      "list_type": "song",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
        }
      ],
      "artist_map": {
        "artists": [
          {
            "id": "2255753",
            "name": "Olivia Rodrigo",
            "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
              }
            ]
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "2255753",
            "name": "Olivia Rodrigo",
            "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
              }
            ]
          }
        ]
      },
      "song_count": 12,
      "is_dolby_content": false,
      "copyright_text": "© 2023 Olivia Rodrigo",
      "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
      "songs": [
        {
          "id": "3rVgXIDh",
          "name": "all-american bitch",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/all-american-bitch/Qxo9Vix5c1s",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 1797,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/477099587c622dcfef5b0a41438d31e1_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/477099587c622dcfef5b0a41438d31e1_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/477099587c622dcfef5b0a41438d31e1_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/477099587c622dcfef5b0a41438d31e1_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/477099587c622dcfef5b0a41438d31e1_320.mp4"
            }
          ],
          "duration": 166,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "I know my age and I act like it",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "ZECdkNmy",
          "name": "bad idea right?",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/bad-idea-right/Ki0oVR9,Wko",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 4145,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/01db3e87687b74945c87e110d17135be_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/01db3e87687b74945c87e110d17135be_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/01db3e87687b74945c87e110d17135be_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/01db3e87687b74945c87e110d17135be_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/01db3e87687b74945c87e110d17135be_320.mp4"
            }
          ],
          "duration": 184,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records",
          "vcode": "010912292073368",
          "vlink": "https://jiotunepreview.jio.com/content/Converted/010912292030489.mp3"
        },
        {
          "id": "Lm5aiJdI",
          "name": "vampire",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/vampire/PAVeUB16U3o",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 131825,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/a8b888da831d4509da1e7094ecfa7f4d_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/a8b888da831d4509da1e7094ecfa7f4d_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/a8b888da831d4509da1e7094ecfa7f4d_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/a8b888da831d4509da1e7094ecfa7f4d_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/a8b888da831d4509da1e7094ecfa7f4d_320.mp4"
            }
          ],
          "duration": 220,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "wxWWVIY6",
          "name": "lacy",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/lacy/BxA8ZiJ5bgU",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 1076,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/fa653f215e3f66a74af390f3b77630ed_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/fa653f215e3f66a74af390f3b77630ed_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/fa653f215e3f66a74af390f3b77630ed_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/fa653f215e3f66a74af390f3b77630ed_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/fa653f215e3f66a74af390f3b77630ed_320.mp4"
            }
          ],
          "duration": 177,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "Lacy, oh, Lacy, skin like puff pastry",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "3_hfCtOV",
          "name": "ballad of a homeschooled girl",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/ballad-of-a-homeschooled-girl/QzcDVzdEeGU",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 859,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/d176d256809d12376b3ade3de98374c8_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/d176d256809d12376b3ade3de98374c8_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/d176d256809d12376b3ade3de98374c8_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/d176d256809d12376b3ade3de98374c8_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/d176d256809d12376b3ade3de98374c8_320.mp4"
            }
          ],
          "duration": 203,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "It's social suicide, wanna curl up and die",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "_xwMfPK1",
          "name": "making the bed",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/making-the-bed/LxAcfBJgfAI",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 733,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/61a642a97bd323ea53f2419ad37f1b94_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/61a642a97bd323ea53f2419ad37f1b94_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/61a642a97bd323ea53f2419ad37f1b94_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/61a642a97bd323ea53f2419ad37f1b94_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/61a642a97bd323ea53f2419ad37f1b94_320.mp4"
            }
          ],
          "duration": 199,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "But it's me who's been making the bed",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "EF1cA_TF",
          "name": "logical",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/logical/NS5aUjVvY3U",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 810,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo, Julia Michaels",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "672852",
                "name": "Julia Michaels",
                "url": "https://www.jiosaavn.com/artist/julia-michaels-songs/OboBJBVTzgs_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Julia_Michaels_20200220103730_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Julia_Michaels_20200220103730_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Julia_Michaels_20200220103730_500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "672852",
                "name": "Julia Michaels",
                "url": "https://www.jiosaavn.com/artist/julia-michaels-songs/OboBJBVTzgs_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Julia_Michaels_20200220103730_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Julia_Michaels_20200220103730_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Julia_Michaels_20200220103730_500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/1eec4dd91fbc67b79e1bb9a99b3c22b6_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/1eec4dd91fbc67b79e1bb9a99b3c22b6_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/1eec4dd91fbc67b79e1bb9a99b3c22b6_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/1eec4dd91fbc67b79e1bb9a99b3c22b6_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/1eec4dd91fbc67b79e1bb9a99b3c22b6_320.mp4"
            }
          ],
          "duration": 232,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "Love is never logical",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "SSov3ZGf",
          "name": "get him back!",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/get-him-back/IzsER0dqcFU",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 385,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/8534153e0147839d10b689921834c6fa_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/8534153e0147839d10b689921834c6fa_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/8534153e0147839d10b689921834c6fa_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/8534153e0147839d10b689921834c6fa_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/8534153e0147839d10b689921834c6fa_320.mp4"
            }
          ],
          "duration": 211,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "I wanna make him really jealous, wanna make him feel bad",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "4ja0Wa_p",
          "name": "love is embarrassing",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/love-is-embarrassing/RAIKASNRaEM",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 306,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/4e446876f82619aaec95f34255b91811_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/4e446876f82619aaec95f34255b91811_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/4e446876f82619aaec95f34255b91811_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/4e446876f82619aaec95f34255b91811_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/4e446876f82619aaec95f34255b91811_320.mp4"
            }
          ],
          "duration": 155,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "God, love's fuckin' embarrassin'",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "684bGJEi",
          "name": "the grudge",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/the-grudge/RlBfUzN6clo",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 363,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/9b4558e5154ba820d77273703ed1a32c_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/9b4558e5154ba820d77273703ed1a32c_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/9b4558e5154ba820d77273703ed1a32c_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/9b4558e5154ba820d77273703ed1a32c_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/9b4558e5154ba820d77273703ed1a32c_320.mp4"
            }
          ],
          "duration": 189,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "But you know I can't let it go, I've tried, I've tried, I've tried",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "NgOhICNW",
          "name": "pretty isn’t pretty",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/pretty-isn%e2%80%99t-pretty/Pg8kWT1zeWQ",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 280,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo, Amy Allen",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "1662162",
                "name": "Amy Allen",
                "url": "https://www.jiosaavn.com/artist/amy-allen-songs/LU1I9axzjRI_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/966/Love-Won-English-2015-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/966/Love-Won-English-2015-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/966/Love-Won-English-2015-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "1662162",
                "name": "Amy Allen",
                "url": "https://www.jiosaavn.com/artist/amy-allen-songs/LU1I9axzjRI_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/966/Love-Won-English-2015-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/966/Love-Won-English-2015-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/966/Love-Won-English-2015-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/91742d5bc29977ccb79efde354e44912_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/91742d5bc29977ccb79efde354e44912_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/91742d5bc29977ccb79efde354e44912_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/91742d5bc29977ccb79efde354e44912_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/91742d5bc29977ccb79efde354e44912_320.mp4"
            }
          ],
          "duration": 199,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "When pretty isn't pretty enough",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        },
        {
          "id": "NYl64U4k",
          "name": "teenage dream",
          "subtitle": "Olivia Rodrigo - GUTS",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/teenage-dream/PjEHB0BlA1g",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 585,
          "explicit": true,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Daniel Nigro, Olivia Rodrigo",
          "artist_map": {
            "artists": [
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              },
              {
                "id": "716139",
                "name": "Daniel Nigro",
                "url": "https://www.jiosaavn.com/artist/daniel-nigro-songs/-MQQztYc7bQ_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/064/All-I-Want-From-High-School-Musical-The-Musical-The-Series--English-2019-20191125230736-500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "GUTS",
          "album_id": "48090436",
          "album_url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "label": "Olivia Rodrigo PS",
          "label_url": "/label/olivia-rodrigo-ps-albums/6y2HNhCZivg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/538/c2fc553186d993aaa88432baeaa582b9_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/538/c2fc553186d993aaa88432baeaa582b9_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/538/c2fc553186d993aaa88432baeaa582b9_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/538/c2fc553186d993aaa88432baeaa582b9_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/538/c2fc553186d993aaa88432baeaa582b9_320.mp4"
            }
          ],
          "duration": 222,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_id": "",
          "lyrics_snippet": "They all say that it gets better, it gets better the more you grow",
          "starred": false,
          "release_date": "2023-09-08",
          "triller_available": false,
          "copyright_text": "℗ 2023 Olivia Rodrigo, under exclusive license to Geffen Records"
        }
      ]
    },
    {
      "id": "44138980",
      "name": "Desperado",
      "subtitle": "Raghav,  Tesher",
      "type": "album",
      "language": "english",
      "play_count": 0,
      "explicit": false,
      "year": 2023,
      "url": "https://www.jiosaavn.com/album/desperado/75-fkt,nFZw_",
      "header_desc": "2023 · English Album · Raghav and Tesher",
      "list_count": 1,
      "list_type": "song",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-500x500.jpg"
        }
      ],
      "artist_map": {
        "artists": [
          {
            "id": "466247",
            "name": "Raghav",
            "url": "https://www.jiosaavn.com/artist/raghav-songs/nuMA8KkXk9w_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_500x500.jpg"
              }
            ]
          },
          {
            "id": "7679801",
            "name": " Tesher",
            "url": "https://www.jiosaavn.com/artist/-tesher-songs/qarvRHrHaks_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_500x500.jpg"
              }
            ]
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "466247",
            "name": "Raghav",
            "url": "https://www.jiosaavn.com/artist/raghav-songs/nuMA8KkXk9w_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_500x500.jpg"
              }
            ]
          },
          {
            "id": "7679801",
            "name": " Tesher",
            "url": "https://www.jiosaavn.com/artist/-tesher-songs/qarvRHrHaks_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_500x500.jpg"
              }
            ]
          }
        ]
      },
      "song_count": 1,
      "is_dolby_content": false,
      "copyright_text": "© 2023 MATHURMATICS RECORDS LTD",
      "label_url": "/label/raghav-albums/gg3CAj8HAMg_",
      "songs": [
        {
          "id": "S1Fct7_v",
          "name": "Desperado",
          "subtitle": "Raghav, Tesher - Desperado",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/desperado/I1ktUgAHaEU",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 1240986,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "RD Burman, Raghav, Hitesh Sharma, Majrooh Sultanpuri, Mushtaq Uddin",
          "artist_map": {
            "artists": [
              {
                "id": "2056463",
                "name": "RD Burman",
                "url": "https://www.jiosaavn.com/artist/rd-burman-songs/utS6iVi7lFk_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "466247",
                "name": "Raghav",
                "url": "https://www.jiosaavn.com/artist/raghav-songs/nuMA8KkXk9w_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_500x500.jpg"
                  }
                ]
              },
              {
                "id": "5933149",
                "name": "Hitesh Sharma",
                "url": "https://www.jiosaavn.com/artist/hitesh-sharma-songs/pW8rqCeb4Xo_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/297/Tujhe-Pana-Chahta-Hoon-Hindi-2019-20190610064006-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/297/Tujhe-Pana-Chahta-Hoon-Hindi-2019-20190610064006-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/297/Tujhe-Pana-Chahta-Hoon-Hindi-2019-20190610064006-500x500.jpg"
                  }
                ]
              },
              {
                "id": "456075",
                "name": "Majrooh Sultanpuri",
                "url": "https://www.jiosaavn.com/artist/majrooh-sultanpuri-songs/wPaYGJ5wYc4_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Majrooh_Sultanpuri_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Majrooh_Sultanpuri_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Majrooh_Sultanpuri_500x500.jpg"
                  }
                ]
              },
              {
                "id": "1010962",
                "name": "Mushtaq Uddin",
                "url": "https://www.jiosaavn.com/artist/mushtaq-uddin-songs/loE4ciyofC4_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "466247",
                "name": "Raghav",
                "url": "https://www.jiosaavn.com/artist/raghav-songs/nuMA8KkXk9w_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_500x500.jpg"
                  }
                ]
              },
              {
                "id": "7679801",
                "name": "Tesher",
                "url": "https://www.jiosaavn.com/artist/tesher-songs/qarvRHrHaks_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_500x500.jpg"
                  }
                ]
              },
              {
                "id": "466247",
                "name": "Raghav",
                "url": "https://www.jiosaavn.com/artist/raghav-songs/nuMA8KkXk9w_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_500x500.jpg"
                  }
                ]
              },
              {
                "id": "5933149",
                "name": "Hitesh Sharma",
                "url": "https://www.jiosaavn.com/artist/hitesh-sharma-songs/pW8rqCeb4Xo_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/297/Tujhe-Pana-Chahta-Hoon-Hindi-2019-20190610064006-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/297/Tujhe-Pana-Chahta-Hoon-Hindi-2019-20190610064006-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/297/Tujhe-Pana-Chahta-Hoon-Hindi-2019-20190610064006-500x500.jpg"
                  }
                ]
              },
              {
                "id": "456075",
                "name": "Majrooh Sultanpuri",
                "url": "https://www.jiosaavn.com/artist/majrooh-sultanpuri-songs/wPaYGJ5wYc4_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Majrooh_Sultanpuri_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Majrooh_Sultanpuri_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Majrooh_Sultanpuri_500x500.jpg"
                  }
                ]
              },
              {
                "id": "1010962",
                "name": "Mushtaq Uddin",
                "url": "https://www.jiosaavn.com/artist/mushtaq-uddin-songs/loE4ciyofC4_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "466247",
                "name": "Raghav",
                "url": "https://www.jiosaavn.com/artist/raghav-songs/nuMA8KkXk9w_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Raghav_001_20180924121542_500x500.jpg"
                  }
                ]
              },
              {
                "id": "7679801",
                "name": "Tesher",
                "url": "https://www.jiosaavn.com/artist/tesher-songs/qarvRHrHaks_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Tesher_000_20210426103258_500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "Desperado",
          "album_id": "44138980",
          "album_url": "https://www.jiosaavn.com/album/desperado/75-fkt,nFZw_",
          "label": "Raghav",
          "label_url": "/label/raghav-albums/gg3CAj8HAMg_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/036/c37bff30ff4f81ccfcdd1902696ec583_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/036/c37bff30ff4f81ccfcdd1902696ec583_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/036/c37bff30ff4f81ccfcdd1902696ec583_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/036/c37bff30ff4f81ccfcdd1902696ec583_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/036/c37bff30ff4f81ccfcdd1902696ec583_320.mp4"
            }
          ],
          "duration": 247,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-04-12",
          "triller_available": false,
          "copyright_text": "© 2023 MATHURMATICS RECORDS LTD"
        }
      ]
    },
    {
      "id": "47458503",
      "name": "Humko Tere Bina Jeena Toh Sikha",
      "subtitle": "Atikur Rahman Himel,  Himel,  Atikur Rahman Himel &amp; HIMEL",
      "type": "album",
      "language": "english",
      "play_count": 0,
      "explicit": false,
      "year": 2023,
      "url": "https://www.jiosaavn.com/album/humko-tere-bina-jeena-toh-sikha/kZDXQhu5e68_",
      "header_desc": "2023 · English Album · Atikur Rahman Himel, Himel, and Atikur Rahman Himel &amp; HIMEL",
      "list_count": 1,
      "list_type": "song",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/628/Humko-Tere-Bina-Jeena-Toh-Sikha-English-2023-20230811012226-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/628/Humko-Tere-Bina-Jeena-Toh-Sikha-English-2023-20230811012226-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/628/Humko-Tere-Bina-Jeena-Toh-Sikha-English-2023-20230811012226-500x500.jpg"
        }
      ],
      "artist_map": {
        "artists": [
          {
            "id": "14053764",
            "name": "Atikur Rahman Himel",
            "url": "https://www.jiosaavn.com/artist/atikur-rahman-himel-songs/arigqBul-hY_",
            "role": "",
            "type": "artist",
            "image": ""
          },
          {
            "id": "3008790",
            "name": " Himel",
            "url": "https://www.jiosaavn.com/artist/-himel-songs/tl1yoN9-RIQ_",
            "role": "",
            "type": "artist",
            "image": ""
          },
          {
            "id": "17038496",
            "name": " Atikur Rahman Himel &amp; HIMEL",
            "url": "https://www.jiosaavn.com/artist/-atikur-rahman-himel-himel-songs/rjPz7prxZm8_",
            "role": "",
            "type": "artist",
            "image": ""
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "14053764",
            "name": "Atikur Rahman Himel",
            "url": "https://www.jiosaavn.com/artist/atikur-rahman-himel-songs/arigqBul-hY_",
            "role": "",
            "type": "artist",
            "image": ""
          },
          {
            "id": "3008790",
            "name": " Himel",
            "url": "https://www.jiosaavn.com/artist/-himel-songs/tl1yoN9-RIQ_",
            "role": "",
            "type": "artist",
            "image": ""
          },
          {
            "id": "17038496",
            "name": " Atikur Rahman Himel &amp; HIMEL",
            "url": "https://www.jiosaavn.com/artist/-atikur-rahman-himel-himel-songs/rjPz7prxZm8_",
            "role": "",
            "type": "artist",
            "image": ""
          }
        ]
      },
      "song_count": 1,
      "is_dolby_content": false,
      "copyright_text": "© 2023 Himel Music",
      "label_url": "/label/arh-albums/sx4bWGTvzHw_",
      "songs": [
        {
          "id": "X8Aj8AUE",
          "name": "Humko Tere Bina Jeena Toh Sikha (Slowed + Reverb)",
          "subtitle": "Atikur Rahman Himel, Himel - Humko Tere Bina Jeena Toh Sikha",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/humko-tere-bina-jeena-toh-sikha-slowed-%2b-reverb/KFAqW0xxYnY",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/628/Humko-Tere-Bina-Jeena-Toh-Sikha-English-2023-20230811012226-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/628/Humko-Tere-Bina-Jeena-Toh-Sikha-English-2023-20230811012226-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/628/Humko-Tere-Bina-Jeena-Toh-Sikha-English-2023-20230811012226-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 137442,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Denny, Richard Cruze Brunton",
          "artist_map": {
            "artists": [
              {
                "id": "604352",
                "name": "Denny",
                "url": "https://www.jiosaavn.com/artist/denny-songs/UBz-eCigU6Q_",
                "role": "music",
                "type": "artist",
                "image": "https://c.saavncdn.com/artists/Denny_20200811085741.jpg"
              },
              {
                "id": "16295170",
                "name": "Richard Cruze Brunton",
                "url": "https://www.jiosaavn.com/artist/richard-cruze-brunton-songs/8eXXmxy5ddo_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "14053764",
                "name": "Atikur Rahman Himel",
                "url": "https://www.jiosaavn.com/artist/atikur-rahman-himel-songs/arigqBul-hY_",
                "role": "singer",
                "type": "artist",
                "image": ""
              },
              {
                "id": "3008790",
                "name": "Himel",
                "url": "https://www.jiosaavn.com/artist/himel-songs/tl1yoN9-RIQ_",
                "role": "singer",
                "type": "artist",
                "image": ""
              },
              {
                "id": "710601",
                "name": "Kunaal Vermaa",
                "url": "https://www.jiosaavn.com/artist/kunaal-vermaa-songs/DGLdKvhUtpU_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Kunaal_Vermaa_001_20230613121244_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Kunaal_Vermaa_001_20230613121244_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Kunaal_Vermaa_001_20230613121244_500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "14053764",
                "name": "Atikur Rahman Himel",
                "url": "https://www.jiosaavn.com/artist/atikur-rahman-himel-songs/arigqBul-hY_",
                "role": "primary_artists",
                "type": "artist",
                "image": ""
              },
              {
                "id": "3008790",
                "name": "Himel",
                "url": "https://www.jiosaavn.com/artist/himel-songs/tl1yoN9-RIQ_",
                "role": "primary_artists",
                "type": "artist",
                "image": ""
              }
            ]
          },
          "album": "Humko Tere Bina Jeena Toh Sikha",
          "album_id": "47458503",
          "album_url": "https://www.jiosaavn.com/album/humko-tere-bina-jeena-toh-sikha/kZDXQhu5e68_",
          "label": "ARH",
          "label_url": "/label/arh-albums/sx4bWGTvzHw_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/628/5341c10b95d25983d06ab78a935999cb_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/628/5341c10b95d25983d06ab78a935999cb_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/628/5341c10b95d25983d06ab78a935999cb_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/628/5341c10b95d25983d06ab78a935999cb_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/628/5341c10b95d25983d06ab78a935999cb_320.mp4"
            }
          ],
          "duration": 234,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-08-06",
          "triller_available": false,
          "copyright_text": "℗ 2023 Himel Music"
        }
      ]
    },
    {
      "id": "43109186",
      "name": "Maan Meri Jaan (Afterlife)",
      "subtitle": "King,  Nick Jonas",
      "type": "album",
      "language": "english",
      "play_count": 0,
      "explicit": false,
      "year": 2023,
      "url": "https://www.jiosaavn.com/album/maan-meri-jaan-afterlife/x6CjkgbR9w8_",
      "header_desc": "2023 · English Album · King and Nick Jonas",
      "list_count": 1,
      "list_type": "song",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/184/Maan-Meri-Jaan-Afterlife-English-2023-20230310134919-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/184/Maan-Meri-Jaan-Afterlife-English-2023-20230310134919-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/184/Maan-Meri-Jaan-Afterlife-English-2023-20230310134919-500x500.jpg"
        }
      ],
      "artist_map": {
        "artists": [
          {
            "id": "14327531",
            "name": "King",
            "url": "https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/King_002_20221012124722_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/King_002_20221012124722_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/King_002_20221012124722_500x500.jpg"
              }
            ]
          },
          {
            "id": "603639",
            "name": " Nick Jonas",
            "url": "https://www.jiosaavn.com/artist/-nick-jonas-songs/m5y4QjA4x,I_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_500x500.jpg"
              }
            ]
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "14327531",
            "name": "King",
            "url": "https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/King_002_20221012124722_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/King_002_20221012124722_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/King_002_20221012124722_500x500.jpg"
              }
            ]
          },
          {
            "id": "603639",
            "name": " Nick Jonas",
            "url": "https://www.jiosaavn.com/artist/-nick-jonas-songs/m5y4QjA4x,I_",
            "role": "",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_500x500.jpg"
              }
            ]
          }
        ]
      },
      "song_count": 1,
      "is_dolby_content": false,
      "copyright_text": "© 2023 Warner Music India",
      "label_url": "/label/warner-music-india-albums/4j6ISMnao78_",
      "songs": [
        {
          "id": "OHRIh6w3",
          "name": "Maan Meri Jaan (Afterlife)",
          "subtitle": "King, Nick Jonas - Maan Meri Jaan (Afterlife)",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/maan-meri-jaan-afterlife/PyA5eBwGQAA",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/184/Maan-Meri-Jaan-Afterlife-English-2023-20230310134919-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/184/Maan-Meri-Jaan-Afterlife-English-2023-20230310134919-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/184/Maan-Meri-Jaan-Afterlife-English-2023-20230310134919-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 2170356,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "David Arkwright, King, Miranda Glory, Natania, Paris Carney",
          "artist_map": {
            "artists": [
              {
                "id": "1142411",
                "name": "David Arkwright",
                "url": "https://www.jiosaavn.com/artist/david-arkwright-songs/LbPK-Q,HLj8_",
                "role": "music",
                "type": "artist",
                "image": ""
              },
              {
                "id": "14327531",
                "name": "King",
                "url": "https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_500x500.jpg"
                  }
                ]
              },
              {
                "id": "3372836",
                "name": "Miranda Glory",
                "url": "https://www.jiosaavn.com/artist/miranda-glory-songs/J5TeCH7Cc,A_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/485/With-U-2-English-2019-20190212150435-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/485/With-U-2-English-2019-20190212150435-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/485/With-U-2-English-2019-20190212150435-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2737681",
                "name": "Natania",
                "url": "https://www.jiosaavn.com/artist/natania-songs/08-ViIgdTvw_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Natania_Lalwani_001_20191128084944_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Natania_Lalwani_001_20191128084944_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Natania_Lalwani_001_20191128084944_500x500.jpg"
                  }
                ]
              },
              {
                "id": "1315821",
                "name": "Paris Carney",
                "url": "https://www.jiosaavn.com/artist/paris-carney-songs/gAKlBTZMCKI_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/955/Riot-English-2015-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/955/Riot-English-2015-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/955/Riot-English-2015-500x500.jpg"
                  }
                ]
              },
              {
                "id": "14327531",
                "name": "King",
                "url": "https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_500x500.jpg"
                  }
                ]
              },
              {
                "id": "603639",
                "name": "Nick Jonas",
                "url": "https://www.jiosaavn.com/artist/nick-jonas-songs/m5y4QjA4x,I_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_500x500.jpg"
                  }
                ]
              },
              {
                "id": "1142411",
                "name": "David Arkwright",
                "url": "https://www.jiosaavn.com/artist/david-arkwright-songs/LbPK-Q,HLj8_",
                "role": "lyricist",
                "type": "artist",
                "image": ""
              },
              {
                "id": "14327531",
                "name": "King",
                "url": "https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_500x500.jpg"
                  }
                ]
              },
              {
                "id": "3372836",
                "name": "Miranda Glory",
                "url": "https://www.jiosaavn.com/artist/miranda-glory-songs/J5TeCH7Cc,A_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/485/With-U-2-English-2019-20190212150435-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/485/With-U-2-English-2019-20190212150435-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/485/With-U-2-English-2019-20190212150435-500x500.jpg"
                  }
                ]
              },
              {
                "id": "2737681",
                "name": "Natania",
                "url": "https://www.jiosaavn.com/artist/natania-songs/08-ViIgdTvw_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Natania_Lalwani_001_20191128084944_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Natania_Lalwani_001_20191128084944_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Natania_Lalwani_001_20191128084944_500x500.jpg"
                  }
                ]
              },
              {
                "id": "603639",
                "name": "Nick Jonas",
                "url": "https://www.jiosaavn.com/artist/nick-jonas-songs/m5y4QjA4x,I_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_500x500.jpg"
                  }
                ]
              },
              {
                "id": "1315821",
                "name": "Paris Carney",
                "url": "https://www.jiosaavn.com/artist/paris-carney-songs/gAKlBTZMCKI_",
                "role": "lyricist",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/955/Riot-English-2015-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/955/Riot-English-2015-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/955/Riot-English-2015-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "14327531",
                "name": "King",
                "url": "https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/King_002_20221012124722_500x500.jpg"
                  }
                ]
              },
              {
                "id": "603639",
                "name": "Nick Jonas",
                "url": "https://www.jiosaavn.com/artist/nick-jonas-songs/m5y4QjA4x,I_",
                "role": "primary_artists",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Nick_Jonas_002_20230816145821_500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "Maan Meri Jaan (Afterlife)",
          "album_id": "43109186",
          "album_url": "https://www.jiosaavn.com/album/maan-meri-jaan-afterlife/x6CjkgbR9w8_",
          "label": "Warner Music India",
          "label_url": "/label/warner-music-india-albums/4j6ISMnao78_",
          "origin": "album",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/184/7b57e1555824e21d5694c6ba50ae63c6_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/184/7b57e1555824e21d5694c6ba50ae63c6_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/184/7b57e1555824e21d5694c6ba50ae63c6_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/184/7b57e1555824e21d5694c6ba50ae63c6_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/184/7b57e1555824e21d5694c6ba50ae63c6_320.mp4"
            }
          ],
          "duration": 186,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "false",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-03-10",
          "triller_available": false,
          "copyright_text": "℗ 2023 Warner Music India",
          "vcode": "010912581913174",
          "vlink": "https://jiotunepreview.jio.com/content/Converted/010912581869667.mp3"
        }
      ]
    }
  ]
}
```

+++

|             **Query Parameter**             |                                                                                                    **Description**                                                                                                    |              **Required**               |
| :-----------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
|   [!badge variant="contrast" text="year"]   |                                                                                                         Year                                                                                                          | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="language"] | one or more comma separated languages</br>`hindi`, `english`, `punjabi`, `tamil`, `telugu`, `marathi`,`gujarati`, `bengali`, `kannada`, `bhojpuri`, `malayalam`, `urdu`, `haryanvi`, `rajasthani`, `odia`, `assamese` | [!badge variant="primary" text="False"] |
|  [!badge variant="contrast" text="camel"]   |                                                                                               `camelCase` response keys                                                                                               | [!badge variant="primary" text="False"] |
|   [!badge variant="contrast" text="raw"]    |                                                                                           raw response from `Jiosaavn API`                                                                                            | [!badge variant="primary" text="False"] |

```

```
