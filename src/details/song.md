---
order: 100
icon: play
---

# Song Details

!!! Note
<https://jiosaavn-api-ts.vercel.app> or <https://jiosaavn-api-rs.vercel.app> are only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Song details by `ID`, `link` or `token`

+++ Request

**HTTP**

- **ID**

```bash
https://jiosaavn-api-ts.vercel.app/song?id=HLulXlir
```

```bash
https://jiosaavn-api-rs.vercel.app/song?id=HLulXlir
```

- **Link**

```bash
https://jiosaavn-api-ts.vercel.app/song?link=https://www.jiosaavn.com/song/ram-siya-ram/OCQeXSxcXkE
```

```bash
https://jiosaavn-api-rs.vercel.app/song?link=https://www.jiosaavn.com/song/ram-siya-ram/OCQeXSxcXkE
```

- **Token**

```bash
https://jiosaavn-api-ts.vercel.app/song?token=OCQeXSxcXkE
```

```bash
https://jiosaavn-api-rs.vercel.app/song?token=OCQeXSxcXkE
```

**cURL**

```bash
curl -X GET 'https://jiosaavn-api-ts.vercel.app/song?id=HLulXlir' \
 -H 'content-type: application/json'
```

```bash
curl -X GET 'https://jiosaavn-api-rs.vercel.app/song?id=HLulXlir' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Song(s) Details fetched successfully",
  "data": {
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
        "play_count": 64470403,
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
        "origin": "none",
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
        "position": 1,
        "source": "/song/recommend",
        "params": { "id": "HLulXlir", "lang": "hindi" }
      },
      "currently_trending": {
        "title": "Currently Trending Songs",
        "subtitle": "",
        "position": 2,
        "source": "/get/trending",
        "params": { "type": "song", "lang": "hindi" }
      },
      "songs_by_same_artists": {
        "title": "Top Songs By Same Artists",
        "subtitle": "",
        "position": 3,
        "source": "/artist/top-songs",
        "params": {
          "artist_id": "3623110",
          "song_id": "HLulXlir",
          "lang": "hindi"
        }
      },
      "songs_by_same_actors": {
        "title": "Top Songs By Same Actors",
        "subtitle": "",
        "position": 4,
        "source": "/get/actor-top-songs",
        "params": { "actor_id": "", "song_id": "HLulXlir", "lang": "hindi" }
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

|                                                        **Query Parameter**                                                         |                                                               **Description**                                                               |              **Required**               |
| :--------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
| [!badge variant="contrast" text="id"] **/** [!badge variant="contrast" text="link"] **/** [!badge variant="contrast" text="token"] | id(s) - comma seperated **/**<br>link from <https://jiosaavn.com> **/**<br>token ->https://www.jiosaavn.com/song/ram-siya-ram/`OCQeXSxcXkE` | [!badge variant="primary" text="True"]  |
|                                              [!badge variant="contrast" text="camel"]                                              |                                                          `camelCase` response keys                                                          | [!badge variant="primary" text="False"] |
|                                               [!badge variant="contrast" text="raw"]                                               |                                                      raw response from `Jiosaavn API`                                                       | [!badge variant="primary" text="False"] |

## Song Recommendations by `Song ID`

+++ Request

**HTTP**

```bash
https://jiosaavn-api-ts.vercel.app/song/recommend?id=HLulXlir
```

```bash
https://jiosaavn-api-rs.vercel.app/song/recommend?id=HLulXlir
```

**cURL**

```bash
curl -X GET 'https://jiosaavn-api-ts.vercel.app/song/recommend?id=HLulXlir' \
 -H 'content-type: application/json'
```

```bash
curl -X GET 'https://jiosaavn-api-rs.vercel.app/song/recommend?id=HLulXlir' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Song Recommendations fetched successfully",
  "data": [
    {
      "id": "utaJvgQd",
      "name": "Jai Shri Ram (Hindi)",
      "subtitle": "Ajay-Atul, Manoj Muntashir - Jai Shri Ram (Hindi)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/jai-shri-ram-hindi/BRwKewJXZlc",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/393/Jai-Shri-Ram-Hindi-Hindi-2023-20230511171009-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/393/Jai-Shri-Ram-Hindi-Hindi-2023-20230511171009-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/393/Jai-Shri-Ram-Hindi-Hindi-2023-20230511171009-500x500.jpg"
        }
      ],
      "language": "hindi",
      "year": 2023,
      "header_desc": "",
      "play_count": 6034018,
      "explicit": false,
      "list": "",
      "list_type": "",
      "list_count": 0,
      "music": "Ajay-Atul",
      "artist_map": {
        "artists": [
          {
            "id": "459381",
            "name": "Ajay-Atul",
            "url": "https://www.jiosaavn.com/artist/ajay-atul-songs/LZ,JHzGbLkY_",
            "role": "music",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_500x500.jpg"
              }
            ]
          },
          {
            "id": "459381",
            "name": "Ajay-Atul",
            "url": "https://www.jiosaavn.com/artist/ajay-atul-songs/LZ,JHzGbLkY_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_500x500.jpg"
              }
            ]
          },
          {
            "id": "473441",
            "name": "Manoj Muntashir",
            "url": "https://www.jiosaavn.com/artist/manoj-muntashir-songs/eaiDjU0BhyA_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-500x500.jpg"
              }
            ]
          },
          {
            "id": "473441",
            "name": "Manoj Muntashir",
            "url": "https://www.jiosaavn.com/artist/manoj-muntashir-songs/eaiDjU0BhyA_",
            "role": "lyricist",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-500x500.jpg"
              }
            ]
          },
          {
            "id": "458996",
            "name": "Prabhas",
            "url": "https://www.jiosaavn.com/artist/prabhas-songs/hWJzaGugKhE_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Prabhas_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Prabhas_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Prabhas_500x500.jpg"
              }
            ]
          },
          {
            "id": "455079",
            "name": "Saif Ali Khan",
            "url": "https://www.jiosaavn.com/artist/saif-ali-khan-songs/2ZH0mIXzCnI_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Saif_Ali_Khan_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Saif_Ali_Khan_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Saif_Ali_Khan_500x500.jpg"
              }
            ]
          },
          {
            "id": "701752",
            "name": "Kriti Sanon",
            "url": "https://www.jiosaavn.com/artist/kriti-sanon-songs/9UtnOColzrU_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Kriti_Sanon_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Kriti_Sanon_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Kriti_Sanon_500x500.jpg"
              }
            ]
          },
          {
            "id": "471839",
            "name": "Sunny Singh",
            "url": "https://www.jiosaavn.com/artist/sunny-singh-songs/txDp8oPSOaw_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Sunny_Singh_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Sunny_Singh_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Sunny_Singh_500x500.jpg"
              }
            ]
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "459381",
            "name": "Ajay-Atul",
            "url": "https://www.jiosaavn.com/artist/ajay-atul-songs/LZ,JHzGbLkY_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Ajay_Atul_003_20230228105414_500x500.jpg"
              }
            ]
          },
          {
            "id": "473441",
            "name": "Manoj Muntashir",
            "url": "https://www.jiosaavn.com/artist/manoj-muntashir-songs/eaiDjU0BhyA_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/259/Episode-1-Dekhte-Dekhte-From-Muntashir-Ki-Diary-Se--Hindi-2019-20190902135108-500x500.jpg"
              }
            ]
          }
        ]
      },
      "album": "Jai Shri Ram (Hindi)",
      "album_id": "44249002",
      "album_url": "https://www.jiosaavn.com/album/jai-shri-ram-hindi/-IOxFC9xlko_",
      "label": "",
      "label_url": "/label/-albums/6DLuXO3VoTo_",
      "origin": "none",
      "is_dolby_content": false,
      "320kbps": true,
      "download_url": [
        {
          "quality": "12kbps",
          "link": "https://aac.saavncdn.com/393/aaa1d27a332543220d5991e1de73e08c_12.mp4"
        },
        {
          "quality": "48kbps",
          "link": "https://aac.saavncdn.com/393/aaa1d27a332543220d5991e1de73e08c_48.mp4"
        },
        {
          "quality": "96kbps",
          "link": "https://aac.saavncdn.com/393/aaa1d27a332543220d5991e1de73e08c_96.mp4"
        },
        {
          "quality": "160kbps",
          "link": "https://aac.saavncdn.com/393/aaa1d27a332543220d5991e1de73e08c_160.mp4"
        },
        {
          "quality": "320kbps",
          "link": "https://aac.saavncdn.com/393/aaa1d27a332543220d5991e1de73e08c_320.mp4"
        }
      ],
      "duration": 64,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "has_lyrics": true,
      "lyrics_id": "",
      "lyrics_snippet": "Mantro Se Badke Tera Naam",
      "starred": false,
      "release_date": "2023-04-06",
      "triller_available": false,
      "copyright_text": "℗ 2023 Super Cassettes Industries Private Limited",
      "vcode": "010910091933654",
      "vlink": "https://jiotunepreview.jio.com/content/Converted/010910091889767.mp3"
    },
    {
      "id": "aRZbUYD7",
      "name": "Tum Hi Ho",
      "subtitle": "Arijit Singh - Aashiqui 2",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/tum-hi-ho/EToxUyFpcwQ",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/430/Aashiqui-2-Hindi-2013-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/430/Aashiqui-2-Hindi-2013-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/430/Aashiqui-2-Hindi-2013-500x500.jpg"
        }
      ],
      "language": "hindi",
      "year": 2013,
      "header_desc": "",
      "play_count": 244720093,
      "explicit": false,
      "list": "",
      "list_type": "",
      "list_count": 0,
      "music": "Mithoon",
      "artist_map": {
        "artists": [
          {
            "id": "702592",
            "name": "Mithoon",
            "url": "https://www.jiosaavn.com/artist/mithoon-songs/nQKQiNRsTKs_",
            "role": "music",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_500x500.jpg"
              }
            ]
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_500x500.jpg"
              }
            ]
          },
          {
            "id": "702592",
            "name": "Mithoon",
            "url": "https://www.jiosaavn.com/artist/mithoon-songs/nQKQiNRsTKs_",
            "role": "lyricist",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_500x500.jpg"
              }
            ]
          },
          {
            "id": "669125",
            "name": "Aditya Roy Kapur",
            "url": "https://www.jiosaavn.com/artist/aditya-roy-kapur-songs/2rYodGIZ25w_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Aditya_Roy_Kapur_20201027070801_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Aditya_Roy_Kapur_20201027070801_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Aditya_Roy_Kapur_20201027070801_500x500.jpg"
              }
            ]
          },
          {
            "id": "477854",
            "name": "Shraddha Kapoor",
            "url": "https://www.jiosaavn.com/artist/shraddha-kapoor-songs/97qRLkdq3gI_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Shraddha_Kapoor_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Shraddha_Kapoor_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Shraddha_Kapoor_500x500.jpg"
              }
            ]
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_500x500.jpg"
              }
            ]
          }
        ]
      },
      "album": "Aashiqui 2",
      "album_id": "1139549",
      "album_url": "https://www.jiosaavn.com/album/aashiqui-2/-iNdCmFNV9o_",
      "label": "",
      "label_url": "/label/-albums/6DLuXO3VoTo_",
      "origin": "none",
      "is_dolby_content": false,
      "320kbps": true,
      "download_url": [
        {
          "quality": "12kbps",
          "link": "https://aac.saavncdn.com/430/5c5ea5cc00e3bff45616013226f376fe_12.mp4"
        },
        {
          "quality": "48kbps",
          "link": "https://aac.saavncdn.com/430/5c5ea5cc00e3bff45616013226f376fe_48.mp4"
        },
        {
          "quality": "96kbps",
          "link": "https://aac.saavncdn.com/430/5c5ea5cc00e3bff45616013226f376fe_96.mp4"
        },
        {
          "quality": "160kbps",
          "link": "https://aac.saavncdn.com/430/5c5ea5cc00e3bff45616013226f376fe_160.mp4"
        },
        {
          "quality": "320kbps",
          "link": "https://aac.saavncdn.com/430/5c5ea5cc00e3bff45616013226f376fe_320.mp4"
        }
      ],
      "duration": 262,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "has_lyrics": true,
      "lyrics_id": "",
      "lyrics_snippet": "Tere Bina Kya Wajood Mera",
      "starred": false,
      "release_date": "2013-04-04",
      "triller_available": false,
      "copyright_text": "©  2013 ",
      "vcode": "010910090326333",
      "vlink": "https://jiotunepreview.jio.com/content/Converted/010910090340855.mp3"
    },
    {
      "id": "e3RSZakk",
      "name": "Radha Krishna Serial All Song",
      "subtitle": "Gaurav Pareek, Narayan Pareek, Gaurav Pandiya, Lakshminarayan Pareek, Komal Pareek, Laxmi Narayan Pareek - Radha Krishna Serial All Song",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/radha-krishna-serial-all-song/FVs5Yi5RXFg",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/872/Radha-Krishna-Serial-All-Song-Hindi-2022-20220218171711-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/872/Radha-Krishna-Serial-All-Song-Hindi-2022-20220218171711-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/872/Radha-Krishna-Serial-All-Song-Hindi-2022-20220218171711-500x500.jpg"
        }
      ],
      "language": "hindi",
      "year": 2022,
      "header_desc": "",
      "play_count": 2399024,
      "explicit": false,
      "list": "",
      "list_type": "",
      "list_count": 0,
      "music": "Gaurav Pareek",
      "artist_map": {
        "artists": [
          {
            "id": "8858542",
            "name": "Gaurav Pareek",
            "url": "https://www.jiosaavn.com/artist/gaurav-pareek-songs/NAV9iZM-7F8_",
            "role": "music",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_500x500.jpg"
              }
            ]
          },
          {
            "id": "8858542",
            "name": "Gaurav Pareek",
            "url": "https://www.jiosaavn.com/artist/gaurav-pareek-songs/NAV9iZM-7F8_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_500x500.jpg"
              }
            ]
          },
          {
            "id": "9092291",
            "name": "Narayan Pareek",
            "url": "https://www.jiosaavn.com/artist/narayan-pareek-songs/KDXq04HDrYs_",
            "role": "singer",
            "type": "artist",
            "image": ""
          },
          {
            "id": "9241993",
            "name": "Gaurav Pandiya",
            "url": "https://www.jiosaavn.com/artist/gaurav-pandiya-songs/7BVZbJ4ztvs_",
            "role": "singer",
            "type": "artist",
            "image": ""
          },
          {
            "id": "12486061",
            "name": "Lakshminarayan Pareek",
            "url": "https://www.jiosaavn.com/artist/lakshminarayan-pareek-songs/FMIg7ainYiA_",
            "role": "singer",
            "type": "artist",
            "image": ""
          },
          {
            "id": "9142839",
            "name": "Komal Pareek",
            "url": "https://www.jiosaavn.com/artist/komal-pareek-songs/CPbA4uVPKDc_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Komal_Pareek_000_20210122082030_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Komal_Pareek_000_20210122082030_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Komal_Pareek_000_20210122082030_500x500.jpg"
              }
            ]
          },
          {
            "id": "9146659",
            "name": "Laxmi Narayan Pareek",
            "url": "https://www.jiosaavn.com/artist/laxmi-narayan-pareek-songs/bBK,NFHFusg_",
            "role": "singer",
            "type": "artist",
            "image": ""
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "8858542",
            "name": "Gaurav Pareek",
            "url": "https://www.jiosaavn.com/artist/gaurav-pareek-songs/NAV9iZM-7F8_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Gaurav_Pareek_000_20210121122551_500x500.jpg"
              }
            ]
          },
          {
            "id": "9092291",
            "name": "Narayan Pareek",
            "url": "https://www.jiosaavn.com/artist/narayan-pareek-songs/KDXq04HDrYs_",
            "role": "primary_artists",
            "type": "artist",
            "image": ""
          },
          {
            "id": "9241993",
            "name": "Gaurav Pandiya",
            "url": "https://www.jiosaavn.com/artist/gaurav-pandiya-songs/7BVZbJ4ztvs_",
            "role": "primary_artists",
            "type": "artist",
            "image": ""
          },
          {
            "id": "12486061",
            "name": "Lakshminarayan Pareek",
            "url": "https://www.jiosaavn.com/artist/lakshminarayan-pareek-songs/FMIg7ainYiA_",
            "role": "primary_artists",
            "type": "artist",
            "image": ""
          },
          {
            "id": "9142839",
            "name": "Komal Pareek",
            "url": "https://www.jiosaavn.com/artist/komal-pareek-songs/CPbA4uVPKDc_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Komal_Pareek_000_20210122082030_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Komal_Pareek_000_20210122082030_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Komal_Pareek_000_20210122082030_500x500.jpg"
              }
            ]
          },
          {
            "id": "9146659",
            "name": "Laxmi Narayan Pareek",
            "url": "https://www.jiosaavn.com/artist/laxmi-narayan-pareek-songs/bBK,NFHFusg_",
            "role": "primary_artists",
            "type": "artist",
            "image": ""
          }
        ]
      },
      "album": "Radha Krishna Serial All Song",
      "album_id": "33019801",
      "album_url": "https://www.jiosaavn.com/album/radha-krishna-serial-all-song/J,CmHE1AZvQ_",
      "label": "Gaurav Pareek Studio",
      "label_url": "/label/gaurav-pareek-studio-albums/-GQfNrTi984_",
      "origin": "none",
      "is_dolby_content": false,
      "320kbps": true,
      "download_url": [
        {
          "quality": "12kbps",
          "link": "https://aac.saavncdn.com/872/d5f74a686834cbe8d346b745cebc671c_12.mp4"
        },
        {
          "quality": "48kbps",
          "link": "https://aac.saavncdn.com/872/d5f74a686834cbe8d346b745cebc671c_48.mp4"
        },
        {
          "quality": "96kbps",
          "link": "https://aac.saavncdn.com/872/d5f74a686834cbe8d346b745cebc671c_96.mp4"
        },
        {
          "quality": "160kbps",
          "link": "https://aac.saavncdn.com/872/d5f74a686834cbe8d346b745cebc671c_160.mp4"
        },
        {
          "quality": "320kbps",
          "link": "https://aac.saavncdn.com/872/d5f74a686834cbe8d346b745cebc671c_320.mp4"
        }
      ],
      "duration": 756,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "has_lyrics": false,
      "lyrics_snippet": "",
      "starred": false,
      "release_date": "2022-02-23",
      "triller_available": false,
      "copyright_text": "© 2022 Gaurav Pareek"
    },
    {
      "id": "cGByA4ik",
      "name": "Shiv Tandav",
      "subtitle": "Ananya Basu - Shiv Tandav",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/shiv-tandav/Ey8pSDUEXlg",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/192/Shiv-Tandav-Hindi-2018-20180831-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/192/Shiv-Tandav-Hindi-2018-20180831-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/192/Shiv-Tandav-Hindi-2018-20180831-500x500.jpg"
        }
      ],
      "language": "hindi",
      "year": 2018,
      "header_desc": "",
      "play_count": 14434672,
      "explicit": false,
      "list": "",
      "list_type": "",
      "list_count": 0,
      "music": "D. Sushant",
      "artist_map": {
        "artists": [
          {
            "id": "824894",
            "name": "D. Sushant",
            "url": "https://www.jiosaavn.com/artist/d.-sushant-songs/ThxCzc9YOuI_",
            "role": "music",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "http://c.saavncdn.com/660/Jai-Ho-Bankey-Bihari-Hindi-2015-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "http://c.saavncdn.com/660/Jai-Ho-Bankey-Bihari-Hindi-2015-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "http://c.saavncdn.com/660/Jai-Ho-Bankey-Bihari-Hindi-2015-500x500.jpg"
              }
            ]
          },
          {
            "id": "3896775",
            "name": "Ananya Basu",
            "url": "https://www.jiosaavn.com/artist/ananya-basu-songs/fWo1Oo2M24o_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "http://c.saavncdn.com/artists/Ananya_Basu_20190927133103_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "http://c.saavncdn.com/artists/Ananya_Basu_20190927133103_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "http://c.saavncdn.com/artists/Ananya_Basu_20190927133103_500x500.jpg"
              }
            ]
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "3896775",
            "name": "Ananya Basu",
            "url": "https://www.jiosaavn.com/artist/ananya-basu-songs/fWo1Oo2M24o_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "http://c.saavncdn.com/artists/Ananya_Basu_20190927133103_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "http://c.saavncdn.com/artists/Ananya_Basu_20190927133103_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "http://c.saavncdn.com/artists/Ananya_Basu_20190927133103_500x500.jpg"
              }
            ]
          }
        ]
      },
      "album": "Shiv Tandav",
      "album_id": "13762534",
      "album_url": "https://www.jiosaavn.com/album/shiv-tandav/WoQ8Ydpt3sA_",
      "label": "",
      "label_url": "/label/-albums/6DLuXO3VoTo_",
      "origin": "none",
      "is_dolby_content": false,
      "320kbps": true,
      "download_url": [
        {
          "quality": "12kbps",
          "link": "https://aac.saavncdn.com/192/c17461a630add311f0a9803387a919bd_12.mp4"
        },
        {
          "quality": "48kbps",
          "link": "https://aac.saavncdn.com/192/c17461a630add311f0a9803387a919bd_48.mp4"
        },
        {
          "quality": "96kbps",
          "link": "https://aac.saavncdn.com/192/c17461a630add311f0a9803387a919bd_96.mp4"
        },
        {
          "quality": "160kbps",
          "link": "https://aac.saavncdn.com/192/c17461a630add311f0a9803387a919bd_160.mp4"
        },
        {
          "quality": "320kbps",
          "link": "https://aac.saavncdn.com/192/c17461a630add311f0a9803387a919bd_320.mp4"
        }
      ],
      "duration": 261,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "has_lyrics": true,
      "lyrics_id": "",
      "lyrics_snippet": "vimohana hi dehana tu shankarasya chintnam",
      "starred": false,
      "release_date": "2018-08-31",
      "triller_available": false,
      "copyright_text": "Super Cassettes Industries Private Limited",
      "vcode": "010910090872598",
      "vlink": "https://jiotunepreview.jio.com/content/Converted/010910090828056.mp3"
    },
    {
      "id": "yc5XXdke",
      "name": "Thoda Thoda Pyaar",
      "subtitle": "Stebin Ben - Thoda Thoda Pyaar",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/thoda-thoda-pyaar/CQteaSxUXFY",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/959/Thoda-Thoda-Pyaar-Hindi-2021-20210212084501-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/959/Thoda-Thoda-Pyaar-Hindi-2021-20210212084501-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/959/Thoda-Thoda-Pyaar-Hindi-2021-20210212084501-500x500.jpg"
        }
      ],
      "language": "hindi",
      "year": 2021,
      "header_desc": "",
      "play_count": 265795934,
      "explicit": false,
      "list": "",
      "list_type": "",
      "list_count": 0,
      "music": "Nilesh Ahuja",
      "artist_map": {
        "artists": [
          {
            "id": "2029028",
            "name": "Nilesh Ahuja",
            "url": "https://www.jiosaavn.com/artist/nilesh-ahuja-songs/GrTspM8TKSs_",
            "role": "music",
            "type": "artist",
            "image": ""
          },
          {
            "id": "4670197",
            "name": "Stebin Ben",
            "url": "https://www.jiosaavn.com/artist/stebin-ben-songs/cIgvj9lx6Dc_",
            "role": "singer",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Stebin_Ben_004_20200930091339_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Stebin_Ben_004_20200930091339_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Stebin_Ben_004_20200930091339_500x500.jpg"
              }
            ]
          },
          {
            "id": "455665",
            "name": "Kumaar",
            "url": "https://www.jiosaavn.com/artist/kumaar-songs/jXhf,IMIGGs_",
            "role": "lyricist",
            "type": "artist",
            "image": ""
          },
          {
            "id": "682930",
            "name": "Sidharth Malhotra",
            "url": "https://www.jiosaavn.com/artist/sidharth-malhotra-songs/na,EAoXKSjk_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Sidharth_Malhotra_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Sidharth_Malhotra_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Sidharth_Malhotra_500x500.jpg"
              }
            ]
          },
          {
            "id": "467129",
            "name": "Neha Sharma",
            "url": "https://www.jiosaavn.com/artist/neha-sharma-songs/GTTcXpQ5vNE_",
            "role": "starring",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/573/Aaja-Tujhe-Pyar-Karu-Hindi-2107-20171026094123-50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/573/Aaja-Tujhe-Pyar-Karu-Hindi-2107-20171026094123-150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/573/Aaja-Tujhe-Pyar-Karu-Hindi-2107-20171026094123-500x500.jpg"
              }
            ]
          },
          {
            "id": "2029028",
            "name": "Nilesh Ahuja",
            "url": "https://www.jiosaavn.com/artist/nilesh-ahuja-songs/GrTspM8TKSs_",
            "role": "starring",
            "type": "artist",
            "image": ""
          },
          {
            "id": "455665",
            "name": "Kumaar",
            "url": "https://www.jiosaavn.com/artist/kumaar-songs/jXhf,IMIGGs_",
            "role": "starring",
            "type": "artist",
            "image": ""
          }
        ],
        "featured_artists": [],
        "primary_artists": [
          {
            "id": "4670197",
            "name": "Stebin Ben",
            "url": "https://www.jiosaavn.com/artist/stebin-ben-songs/cIgvj9lx6Dc_",
            "role": "primary_artists",
            "type": "artist",
            "image": [
              {
                "quality": "50x50",
                "link": "https://c.saavncdn.com/artists/Stebin_Ben_004_20200930091339_50x50.jpg"
              },
              {
                "quality": "150x150",
                "link": "https://c.saavncdn.com/artists/Stebin_Ben_004_20200930091339_150x150.jpg"
              },
              {
                "quality": "500x500",
                "link": "https://c.saavncdn.com/artists/Stebin_Ben_004_20200930091339_500x500.jpg"
              }
            ]
          }
        ]
      },
      "album": "Thoda Thoda Pyaar",
      "album_id": "25291894",
      "album_url": "https://www.jiosaavn.com/album/thoda-thoda-pyaar/7F6S84kDvPo_",
      "label": "Zee Music Co.",
      "label_url": "/label/zee-music-co.-albums/06cepoPTlhU_",
      "origin": "none",
      "is_dolby_content": false,
      "320kbps": true,
      "download_url": [
        {
          "quality": "12kbps",
          "link": "https://aac.saavncdn.com/959/943d9cecfb9ae4c1267ed7ac553e0422_12.mp4"
        },
        {
          "quality": "48kbps",
          "link": "https://aac.saavncdn.com/959/943d9cecfb9ae4c1267ed7ac553e0422_48.mp4"
        },
        {
          "quality": "96kbps",
          "link": "https://aac.saavncdn.com/959/943d9cecfb9ae4c1267ed7ac553e0422_96.mp4"
        },
        {
          "quality": "160kbps",
          "link": "https://aac.saavncdn.com/959/943d9cecfb9ae4c1267ed7ac553e0422_160.mp4"
        },
        {
          "quality": "320kbps",
          "link": "https://aac.saavncdn.com/959/943d9cecfb9ae4c1267ed7ac553e0422_320.mp4"
        }
      ],
      "duration": 244,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "has_lyrics": true,
      "lyrics_id": "",
      "lyrics_snippet": "ki thoda-thoda pyaar hua  tum se",
      "starred": false,
      "release_date": "2021-02-12",
      "triller_available": false,
      "copyright_text": "© 2021 Zee Music Company",
      "vcode": "010910441229182",
      "vlink": "https://jiotunepreview.jio.com/content/Converted/010910441185976.mp3"
    }
  ]
}
```

+++

|           **Query Parameter**            |         **Description**          |              **Required**               |
| :--------------------------------------: | :------------------------------: | :-------------------------------------: |
|  [!badge variant="contrast" text="id"]   |             Song ID              | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="camel"] |    `camelCase` response keys     | [!badge variant="primary" text="False"] |
|  [!badge variant="contrast" text="raw"]  | raw response from `Jiosaavn API` | [!badge variant="primary" text="False"] |
