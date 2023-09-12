---
order: 70
icon: person
---

# Artist Details

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Artist details by artist ID

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/artist?id=459320
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/artist?id=459320' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|          **Query Parameter**          | **Description** |              **Required**              |
| :-----------------------------------: | :-------------: | :------------------------------------: |
| [!badge variant="contrast" text="id"] |    Artist ID    | [!badge variant="primary" text="True"] |

## Artist details by link

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/artist?link=https://www.jiosaavn.com/artist/arijit-singh-/LlRWpHzy3Hk_
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/artist?link=https://www.jiosaavn.com/artist/arijit-singh-/LlRWpHzy3Hk_' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|           **Query Parameter**           |            **Description**            |              **Required**              |
| :-------------------------------------: | :-----------------------------------: | :------------------------------------: |
| [!badge variant="contrast" text="link"] | Song link from <https://jiosaavn.com> | [!badge variant="primary" text="True"] |

## Artist Songs by artist ID

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/artist/songs?id=459320
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/artist/songs?id=459320' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|             **Query Parameter**             |            **Description**            |              **Required**               |
| :-----------------------------------------: | :-----------------------------------: | :-------------------------------------: |
|    [!badge variant="contrast" text="id"]    |               Artist ID               | [!badge variant="primary" text="True"]  |
|   [!badge variant="contrast" text="page"]   |              Page Number              | [!badge variant="primary" text="False"] |
| [!badge variant="contrast" text="category"] | Song type. `alphabetical` or `latest` | [!badge variant="primary" text="False"] |
|   [!badge variant="contrast" text="sort"]   |   Song sort order. `asc` or `desc`    | [!badge variant="primary" text="False"] |

## Artist Albums by artist ID

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/artist/albums?id=459320
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/artist/albums?id=459320' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|             **Query Parameter**             |            **Description**             |              **Required**               |
| :-----------------------------------------: | :------------------------------------: | :-------------------------------------: |
|    [!badge variant="contrast" text="id"]    |               Artist ID                | [!badge variant="primary" text="True"]  |
|   [!badge variant="contrast" text="page"]   |              Page Number               | [!badge variant="primary" text="False"] |
| [!badge variant="contrast" text="category"] | Album type. `alphabetical` or `latest` | [!badge variant="primary" text="False"] |
|   [!badge variant="contrast" text="sort"]   |   Album sort order. `asc` or `desc`    | [!badge variant="primary" text="False"] |

## Artist Top / Recommended Songs by artist ID and song ID

!!!
Note: Song ID is required to get the recommendations based on the song.
!!!

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/artist/recommendations?songId=_rJmbKSP&artistId=459320
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/artist/recommendations?songId=_rJmbKSP&artistId=459320' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Recommended artists songs fetched successfully!",
  "data": [
    {
      "id": "bITJbD1j",
      "name": "I Need You",
      "subtitle": "Semwal, Arijit Singh - I Need You",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/i-need-you/EiE-exZ0Blk",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/836/I-Need-You-English-2022-20220809131953-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/836/I-Need-You-English-2022-20220809131953-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/836/I-Need-You-English-2022-20220809131953-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2022,
      "playCount": 1801,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "",
      "song": null,
      "albumId": "37186319",
      "album": "I Need You",
      "label": "The Music Room",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyt/bpRjC7ZjeTgZkPAf5csYCVGpVG/rTkTE5/45Ndne8R9AKpodTeZxw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/i-need-you/dvHLXB7Q8aQ_",
      "duration": 154,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2022 Shubham Semwal",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "7790319",
            "name": "Semwal",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Semwal_001_20230118091137_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/semwal-songs/UjB9sfzgx0k_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "7790319",
            "name": "Semwal",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Semwal_001_20230118091137_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/semwal-songs/UjB9sfzgx0k_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2022-08-26",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "gSDFUxeU",
      "name": "Neki Ki Raah (Slowed &amp; Reverb)",
      "subtitle": "Rabiul Rhmn - Neki Ki Raah (Slowed &amp; Reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/neki-ki-raah-slowed-reverb/FzsvdyFIUmY",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/263/Neki-Ki-Raah-Slowed-Reverb-English-2023-20230804214125-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/263/Neki-Ki-Raah-Slowed-Reverb-English-2023-20230804214125-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/263/Neki-Ki-Raah-Slowed-Reverb-English-2023-20230804214125-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 203,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh, Mithoon",
      "song": null,
      "albumId": "47277632",
      "album": "Neki Ki Raah (Slowed &amp; Reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyVTK/14Qgu6jl8Kq/Wd0eeUWgyu2frTqYL4jwOu8GPCOMKI8d7IoX8Rw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/neki-ki-raah-slowed-reverb/3U,LpsgWsq8_",
      "duration": 195,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "702592",
            "name": "Mithoon",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/mithoon-songs/nQKQiNRsTKs_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "702592",
            "name": "Mithoon",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Mithoon_002_20200908073735_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/mithoon-songs/nQKQiNRsTKs_"
          }
        ]
      },
      "releaseDate": "2023-08-07",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "EwRPJUpy",
      "name": "Chaleya (Slowed and Reverb)",
      "subtitle": "Røbî, Rabiul Rhmn - Chaleya [Jawan] (Slowed and Reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/chaleya-slowed-and-reverb/NR85YT5lR0o",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/908/Chaleya-Jawan-Slowed-and-Reverb-English-2023-20230816045623-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/908/Chaleya-Jawan-Slowed-and-Reverb-English-2023-20230816045623-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/908/Chaleya-Jawan-Slowed-and-Reverb-English-2023-20230816045623-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 11,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Rabiul Rhmn, Arijit Singh",
      "song": null,
      "albumId": "47583682",
      "album": "Chaleya [Jawan] (Slowed and Reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyCj51k6Fm6iEdmFOSq8tZ/F+s8mfLsEM0j1ivGfnkyr7AYSSub2ehQhw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/chaleya-jawan-slowed-and-reverb/2R7qO7MZ9sE_",
      "duration": 169,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "17084702",
            "name": "Røbî",
            "role": "primary_artists",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/robi-songs/b76ag6ASlZI_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "17084702",
            "name": "Røbî",
            "role": "singer",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/robi-songs/b76ag6ASlZI_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-08-15",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "eI5DajU7",
      "name": "HUMDARD (Lofi)",
      "subtitle": "Ravi Raj - HUMDARD (Lofi)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/humdard-lofi/FSFedRVaYgQ",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/394/HUMDARD-Lofi-English-2023-20230620190837-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/394/HUMDARD-Lofi-English-2023-20230620190837-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/394/HUMDARD-Lofi-English-2023-20230620190837-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 203,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "46070322",
      "album": "HUMDARD (Lofi)",
      "label": "Independent",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDy3zvz/6+nMsRihPyUuN5KTfFSxdEmyHYrlCRQbOD2aw18ixxnFG3QABw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/humdard-lofi/PhUFqaN38AQ_",
      "duration": 148,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Ravi Raj",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "482834",
            "name": "Ravi Raj",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Ravi_Raj_000_20210518091353_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/ravi-raj-songs/bzXyneWI1dA_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "482834",
            "name": "Ravi Raj",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Ravi_Raj_000_20210518091353_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/ravi-raj-songs/bzXyneWI1dA_"
          }
        ]
      },
      "releaseDate": "2023-06-27",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "a5kj8V3s",
      "name": "Chal Wahan Jaate Hai (Slowed &amp; Reverb)",
      "subtitle": "Rabiul Rhmn - Main Dhoondne (slowed &amp; reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/chal-wahan-jaate-hai-slowed-reverb/EV0AW0xmBEA",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/225/Main-Dhoondne-slowed-reverb-English-2023-20230804211019-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/225/Main-Dhoondne-slowed-reverb-English-2023-20230804211019-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/225/Main-Dhoondne-slowed-reverb-English-2023-20230804211019-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 84,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "47276932",
      "album": "Main Dhoondne (slowed &amp; reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyiCL1fYuuI6kxzZmxdF+K0fIDlxefW6Fv69z8R1/l0WlGru1BX2kDGRw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/main-dhoondne-slowed-reverb/zZeu1IZDEK4_",
      "duration": 235,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-08-07",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "AS66ORBs",
      "name": "Zaalima - (Slowed + Reverb)",
      "subtitle": "Rabiul Rhmn, Arijit Singh - Zaalima - (Slowed + Reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/zaalima-slowed-%2b-reverb/MTtdBztidUA",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/419/Zaalima-Slowed-Reverb-English-2023-20230802052622-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/419/Zaalima-Slowed-Reverb-English-2023-20230802052622-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/419/Zaalima-Slowed-Reverb-English-2023-20230802052622-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 669,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "47196405",
      "album": "Zaalima - (Slowed + Reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyHHaQ94tg8P0j84n0kQx/3XDDJUG7x0eD8uWP8ZuDj7VGW9/QZvnJGhw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/zaalima-slowed-%2b-reverb/EEOKr6IpW7M_",
      "duration": 169,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-08-01",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "LE8Dwwrr",
      "name": "Mast Magan (Slowed &amp; Reverb)",
      "subtitle": "Rabiul Rhmn - Mast Magan (Slowed &amp; Reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/mast-magan-slowed-reverb/PC1TdQNHRUE",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/249/Mast-Magan-Slowed-Reverb-English-2023-20230804214157-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/249/Mast-Magan-Slowed-Reverb-English-2023-20230804214157-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/249/Mast-Magan-Slowed-Reverb-English-2023-20230804214157-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 124,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "47277630",
      "album": "Mast Magan (Slowed &amp; Reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDy54FmfJPX+pXtmqFsxdCPzOwYompOZlGoYbQJR7eeW16oysRzpI89hhw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/mast-magan-slowed-reverb/65Ecg9nrFHQ_",
      "duration": 123,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-08-07",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "3uBI60P4",
      "name": "Samjhawan - (Slowed + Reverb)",
      "subtitle": "Rabiul Rhmn - Samjhawan - (Slowed + Reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/samjhawan-slowed-%2b-reverb/Qx0peEIAZwc",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/426/Samjhawan-Slowed-Reverb-English-2023-20230802052554-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/426/Samjhawan-Slowed-Reverb-English-2023-20230802052554-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/426/Samjhawan-Slowed-Reverb-English-2023-20230802052554-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 181,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "47196406",
      "album": "Samjhawan - (Slowed + Reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDybDKM/ffa+ix26Xo93tNgtXxIxum54xLXWwIsh2yZXxh7EX8E9zkaaRw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/samjhawan-slowed-%2b-reverb/xu7BLT-iN7Q_",
      "duration": 152,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-08-01",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "J9kOubms",
      "name": "Shayad Lo-Fi",
      "subtitle": "Praveen Pratap Singh, Arijit Singh - Shayad Lo-Fi",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/shayad-lo-fi/OlEAfgFSWkA",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/998/Shayad-Lo-Fi-English-2022-20220610131437-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/998/Shayad-Lo-Fi-English-2022-20220610131437-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/998/Shayad-Lo-Fi-English-2022-20220610131437-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2022,
      "playCount": 364,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Praveen Pratap Singh",
      "song": null,
      "albumId": "35635083",
      "album": "Shayad Lo-Fi",
      "label": "Factdarshan Times",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyHxccA5Z98YDPRjNWzdHXPWa9/e8yrcyAIarkeNMoqBkQQ1+hQOlRKBw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/shayad-lo-fi/Trs0njTYK3Q_",
      "duration": 311,
      "rights": {
        "code": "1",
        "cacheable": "false",
        "delete_cached_object": "true",
        "reason": "Unavailable"
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2022 Factdarshan Times",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "13317192",
            "name": "Praveen Pratap Singh",
            "role": "primary_artists",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/praveen-pratap-singh-songs/1fTrNocf-qw_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "13317192",
            "name": "Praveen Pratap Singh",
            "role": "music",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/praveen-pratap-singh-songs/1fTrNocf-qw_"
          },
          {
            "id": "13317192",
            "name": "Praveen Pratap Singh",
            "role": "singer",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/praveen-pratap-singh-songs/1fTrNocf-qw_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2022-04-09",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "JLW1uN-L",
      "name": "Shaami Mildi",
      "subtitle": "Roop Ghuman, Vibhuti Joshi, Arijit Singh - Shaami Mildi",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/shaami-mildi/OiQ8AAF,Gn8",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/911/Shaami-Mildi-English-2020-20200904094744-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/911/Shaami-Mildi-English-2020-20200904094744-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/911/Shaami-Mildi-English-2020-20200904094744-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2020,
      "playCount": 4655,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Rupinder Singh, Vibhuti Joshi, Arijit Singh",
      "song": null,
      "albumId": "22302822",
      "album": "Shaami Mildi",
      "label": "Roop Ghuman",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDy0x/80CIhnOK1RP5c+57fjtHk+DoNI1nL0FIZ7IdI8mvEiyb1TMDOVBw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/shaami-mildi/fJbmRXuGLng_",
      "duration": 210,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "© 2020 Roop Ghuman",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "5857160",
            "name": "Roop Ghuman",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Roop_Ghuman_000_20210629053314_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/roop-ghuman-songs/mB8VLCH2mys_"
          },
          {
            "id": "8606340",
            "name": "Vibhuti Joshi",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Vibhuti_Joshi_000_20230212184902_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/vibhuti-joshi-songs/7o18UfG4HaE_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "2927841",
            "name": "Rupinder Singh",
            "role": "music",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rupinder-singh-songs/VhSRgONelqQ_"
          },
          {
            "id": "8606340",
            "name": "Vibhuti Joshi",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Vibhuti_Joshi_000_20230212184902_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/vibhuti-joshi-songs/7o18UfG4HaE_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "5857160",
            "name": "Roop Ghuman",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Roop_Ghuman_000_20210629053314_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/roop-ghuman-songs/mB8VLCH2mys_"
          },
          {
            "id": "8606340",
            "name": "Vibhuti Joshi",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Vibhuti_Joshi_000_20230212184902_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/vibhuti-joshi-songs/7o18UfG4HaE_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2020-09-12",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "DZv7esWz",
      "name": "Arijit Singh - Naina [Slowed+ Reverb]",
      "subtitle": "Rabiul Rhmn, Arijit Singh - Arijit Singh - Naina [Slowed+ Reverb]",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/arijit-singh-naina-slowed%2b-reverb/NDIdBhFDYEk",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/915/Arijit-Singh-Naina-Slowed-Reverb-English-2023-20230725052654-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/915/Arijit-Singh-Naina-Slowed-Reverb-English-2023-20230725052654-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/915/Arijit-Singh-Naina-Slowed-Reverb-English-2023-20230725052654-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 1316,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Rabiul Rhmn",
      "song": null,
      "albumId": "46977887",
      "album": "Arijit Singh - Naina [Slowed+ Reverb]",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyIzjEWuCtREmZL5N9DlsEnJePeXM0/X7sBQK65Iin8ZGOxUjPFLGKAhw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/arijit-singh-naina-slowed%2b-reverb/GbwvHIe8XFw_",
      "duration": 176,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ]
      },
      "releaseDate": "2023-07-25",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "ddOAWDSC",
      "name": "Bollywood Mashup",
      "subtitle": "Raghav Sehgal - Bollywood Mashup",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/bollywood-mashup/FAwkcCN0ZHA",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/014/Bollywood-Mashup-English-2021-20230122124642-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/014/Bollywood-Mashup-English-2021-20230122124642-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/014/Bollywood-Mashup-English-2021-20230122124642-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2021,
      "playCount": 203,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Raghav Sehgal, Arijit Singh, Pritam, Jagjit Singh, Sameer, Amitabh Bhattacharya, Faaiz Anwar",
      "song": null,
      "albumId": "41903053",
      "album": "Bollywood Mashup",
      "label": "Raghav Sehgal",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyGdrg7Cu0z9vUS4NWWNPfi7Ud3qJpOv0NudLw+UkcplMKeAbyWTb02xw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/bollywood-mashup/yFPqC12P-zk_",
      "duration": 166,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "© 2021 Raghav Sehgal",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "8619700",
            "name": "Raghav Sehgal",
            "role": "primary_artists",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/raghav-sehgal-songs/ZeFwH,avACw_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "8619700",
            "name": "Raghav Sehgal",
            "role": "music",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/raghav-sehgal-songs/ZeFwH,avACw_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "456323",
            "name": "Pritam",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Pritam_Chakraborty-20170711073326_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/pritam-songs/OaFg9HPZgq8_"
          },
          {
            "id": "455948",
            "name": "Jagjit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Jagjit_Singh_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/jagjit-singh-songs/EMskk1sVOtM_"
          },
          {
            "id": "455415",
            "name": "Sameer",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Sameer-20170714064856_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/sameer-songs/zbXOIZIhW-8_"
          },
          {
            "id": "458681",
            "name": "Amitabh Bhattacharya",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Amitabh_Bhattacharya_000_20220916184017_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/amitabh-bhattacharya-songs/hsNRL6ZmJmo_"
          },
          {
            "id": "468469",
            "name": "Faaiz Anwar",
            "role": "music",
            "image": "https://c.saavncdn.com/437/Dil-Ke-Sau-Tukde-Har-Tukde-Pe-Tera-Naam-Hai-2013-150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/faaiz-anwar-songs/r7yeO0G3Mps_"
          },
          {
            "id": "8619700",
            "name": "Raghav Sehgal",
            "role": "singer",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/raghav-sehgal-songs/ZeFwH,avACw_"
          }
        ]
      },
      "releaseDate": "2021-02-03",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "F4wOecK8",
      "name": "Humdard (Slowed &amp; Reverb)",
      "subtitle": "Rabiul Rhmn - Humdard (Slowed &amp; Reverb)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/humdard-slowed-reverb/NlwcfhFTfAs",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/256/Humdard-Slowed-Reverb-English-2023-20230804214228-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/256/Humdard-Slowed-Reverb-English-2023-20230804214228-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/256/Humdard-Slowed-Reverb-English-2023-20230804214228-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 101,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "47277631",
      "album": "Humdard (Slowed &amp; Reverb)",
      "label": "Rabiul Records",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDy5PlH99yt7P7zT98M/M0BFxosJTJyCxvxU9is5hIcTaEyDDk2wBYgMhw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/humdard-slowed-reverb/,H8F88xNqNI_",
      "duration": 166,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Rabiul Records",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "14829828",
            "name": "Rabiul Rhmn",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Rabiul_Rhmn_000_20230130081647_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rabiul-rhmn-songs/4CGhDGjVOEI_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-08-07",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "gvZMEhjA",
      "name": "kill the show",
      "subtitle": "Arijit Singh - kill the show",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/kill-the-show/Fx4xfDFYXXI",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/371/kill-the-show-English-2023-20230310061839-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/371/kill-the-show-English-2023-20230310061839-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/371/kill-the-show-English-2023-20230310061839-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2023,
      "playCount": 831,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Arijit Singh",
      "song": null,
      "albumId": "43383922",
      "album": "kill the show",
      "label": "Arijit entertainment",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDy+vXP4MuO+3DkR/2qMARMoJYydl7s19HexMz+yUg6+SvAbGzQDf0MBhw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/kill-the-show/KmeNYfGKNnQ_",
      "duration": 109,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2023 Arijit Entertainment india , Exclusive Licensed Under Arena Music",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "lyricist",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2023-03-23",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "AMSeR6SO",
      "name": "Dua Karo - Reprise",
      "subtitle": "Shivesh Dwivedi, Arijit Singh - Dua Karo - Reprise",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/dua-karo-reprise/MSU4VCYGZHw",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/285/Dua-Karo-Reprise-English-2020-20200501014729-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/285/Dua-Karo-Reprise-English-2020-20200501014729-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/285/Dua-Karo-Reprise-English-2020-20200501014729-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2020,
      "playCount": 2528,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "",
      "song": null,
      "albumId": "20145686",
      "album": "Dua Karo - Reprise",
      "label": "",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDyPeyEZPYv9AkEIzMfBAYKguTI4tlLrIO95zShN3gDZ4ZRscLIKLQCVRw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/dua-karo-reprise/2nQy3Sc28pQ_",
      "duration": 156,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "℗ 2020 T-Series",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "7876106",
            "name": "Shivesh Dwivedi",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Shivesh_Dwivedi_001_20210928060941_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/shivesh-dwivedi-songs/IVeNU1fdugo_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "7876106",
            "name": "Shivesh Dwivedi",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Shivesh_Dwivedi_001_20210928060941_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/shivesh-dwivedi-songs/IVeNU1fdugo_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2020-02-04",
      "trillerAvailable": false,
      "lyricsId": null
    },
    {
      "id": "gU-yuSTf",
      "name": "Saare Chann Te Taare (Revisited)",
      "subtitle": "Roop Ghuman, Vibhuti Joshi, Arijit Singh - Saare Chann Te Taare (Revisited)",
      "type": "song",
      "url": "https://www.jiosaavn.com/song/saare-chann-te-taare-revisited/Fz1GSAFjY1U",
      "image": [
        {
          "quality": "50x50",
          "link": "https://c.saavncdn.com/841/Saare-Chann-Te-Taare-Revisited--English-2021-20210422202357-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "https://c.saavncdn.com/841/Saare-Chann-Te-Taare-Revisited--English-2021-20210422202357-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "https://c.saavncdn.com/841/Saare-Chann-Te-Taare-Revisited--English-2021-20210422202357-500x500.jpg"
        }
      ],
      "language": "english",
      "year": 2021,
      "playCount": 4432,
      "explicitContent": false,
      "listCount": 0,
      "listType": "",
      "list": "",
      "music": "Rupinder Singh, Vibhuti Joshi, Arijit Singh",
      "song": null,
      "albumId": "26736337",
      "album": "Saare Chann Te Taare (Revisited)",
      "label": "Roop Ghuman",
      "origin": "none",
      "isDolbyContent": false,
      "320kbps": true,
      "downloadUrl": "ID2ieOjCrwfgWvL5sXl4B1ImC5QfbsDysVlyeiF+N3A8pfOMsXpUmyk1pg6IyfYnqe7A+qcnE8jHnKRJlvGNOxw7tS9a8Gtq",
      "albumUrl": "https://www.jiosaavn.com/album/saare-chann-te-taare-revisited/IJYJMuYzWVU_",
      "duration": 212,
      "rights": {
        "code": "0",
        "cacheable": "true",
        "delete_cached_object": "false",
        "reason": ""
      },
      "cacheState": "false",
      "hasLyrics": false,
      "lyricsSnippet": "",
      "starred": false,
      "copyrightText": "© 2021 Roop Ghuman",
      "artistMap": {
        "primaryArtists": [
          {
            "id": "5857160",
            "name": "Roop Ghuman",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Roop_Ghuman_000_20210629053314_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/roop-ghuman-songs/mB8VLCH2mys_"
          },
          {
            "id": "8606340",
            "name": "Vibhuti Joshi",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Vibhuti_Joshi_000_20230212184902_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/vibhuti-joshi-songs/7o18UfG4HaE_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "primary_artists",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ],
        "featuredArtists": [],
        "artists": [
          {
            "id": "2927841",
            "name": "Rupinder Singh",
            "role": "music",
            "image": "",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/rupinder-singh-songs/VhSRgONelqQ_"
          },
          {
            "id": "8606340",
            "name": "Vibhuti Joshi",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Vibhuti_Joshi_000_20230212184902_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/vibhuti-joshi-songs/7o18UfG4HaE_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "music",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          },
          {
            "id": "5857160",
            "name": "Roop Ghuman",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Roop_Ghuman_000_20210629053314_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/roop-ghuman-songs/mB8VLCH2mys_"
          },
          {
            "id": "8606340",
            "name": "Vibhuti Joshi",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Vibhuti_Joshi_000_20230212184902_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/vibhuti-joshi-songs/7o18UfG4HaE_"
          },
          {
            "id": "459320",
            "name": "Arijit Singh",
            "role": "singer",
            "image": "https://c.saavncdn.com/artists/Arijit_Singh_002_20230323062147_150x150.jpg",
            "type": "artist",
            "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_"
          }
        ]
      },
      "releaseDate": "2021-05-05",
      "trillerAvailable": false,
      "lyricsId": null
    }
  ]
}
```

+++

|             **Query Parameter**             | **Description** |              **Required**               |
| :-----------------------------------------: | :-------------: | :-------------------------------------: |
|    [!badge variant="contrast" text="id"]    |     Song ID     | [!badge variant="primary" text="True"]  |
|    [!badge variant="contrast" text="id"]    |    Artist ID    | [!badge variant="primary" text="True"]  |
| [!badge variant="contrast" text="language"] | Songs language  | [!badge variant="primary" text="False"] |
