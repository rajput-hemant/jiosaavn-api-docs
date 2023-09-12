---
order: 1000
icon: package
---

# Homepage Data

Get launch data from <https://jiosaavn.com> homepage for different modules such as `songs`, `albums`, `trending`, `charts`, `playlists`, `artists`, `new-releases`, `podcasts`, `radio` and `featured-playlists`, etc.

!!! Note
<https://jiosaavn-api-ts.vercel.app> or <https://jiosaavn-api-rs.vercel.app> are only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

+++ Request

**HTTP**

- _Typescript_

```sh
https://jiosaavn-api-ts.vercel.app/modules
```

- _Rust_

```sh
https://jiosaavn-api-rs.vercel.app/modules
```

**cURL**

- _Typescript_

```sh
curl -X GET 'https://jiosaavn-api-ts.vercel.app/modules' \
 -H 'content-type: application/json'
```

- _Rust_

```sh
curl -X GET 'https://jiosaavn-api-rs.vercel.app/modules' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Home Data fetched successfully",
  "data": {
    "trending": {
      "title": "Trending Now",
      "subtitle": "",
      "position": 1,
      "source": "/get/trending",
      "data": [
        {
          "id": "1180899296",
          "name": " Chartbusters 2023 - English",
          "subtitle": "1.5K Followers",
          "type": "playlist",
          "header_desc": "",
          "url": "https://www.jiosaavn.com/featured/-chartbusters-2023-english/OnoB4SznwI1rxMGEuw5nRg__",
          "image": "https://c.saavncdn.com/editorial/Chartbusters2023English_20230710070658.jpg?bch=1689063694",
          "language": "",
          "explicit": false,
          "list_count": 0,
          "list_type": "",
          "firstname": "JioSaavn",
          "follower_count": 1462,
          "fan_count": 1457,
          "songs": []
        },
        {
          "id": "48090436",
          "name": "GUTS",
          "subtitle": "",
          "type": "album",
          "language": "english",
          "play_count": 0,
          "explicit": false,
          "year": 0,
          "url": "https://www.jiosaavn.com/album/guts/1H6oqdrNXR4_",
          "header_desc": "",
          "list_count": 0,
          "list_type": "",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-50x50.jpg?bch=470698"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-150x150.jpg?bch=470698"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/538/GUTS-English-2023-20230908063935-500x500.jpg?bch=470698"
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
            "primary_artists": []
          },
          "song_count": 12,
          "songs": []
        },
        {
          "id": "1134595537",
          "name": "English: India Superhits Top 50",
          "subtitle": "40.3K Followers",
          "type": "playlist",
          "header_desc": "",
          "url": "https://www.jiosaavn.com/featured/english-india-superhits-top-50/aXoCADwITrUCObrEMJSxEw__",
          "image": "https://c.saavncdn.com/editorial/English-IndiaSuperhitsTop50_20230811090844.jpg?bch=1694158078",
          "language": "",
          "explicit": false,
          "list_count": 0,
          "list_type": "",
          "firstname": "JioSaavn",
          "follower_count": 40252,
          "fan_count": 40236,
          "songs": []
        },
        {
          "id": "45467286",
          "name": "Mexican Phonk Eki",
          "subtitle": "",
          "type": "album",
          "language": "english",
          "play_count": 0,
          "explicit": false,
          "year": 0,
          "url": "https://www.jiosaavn.com/album/mexican-phonk-eki/ot41FH5PweU_",
          "header_desc": "",
          "list_count": 0,
          "list_type": "",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/084/Mexican-Phonk-Eki-English-2023-20230522191447-50x50.jpg?bch=470698"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/084/Mexican-Phonk-Eki-English-2023-20230522191447-150x150.jpg?bch=470698"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/084/Mexican-Phonk-Eki-English-2023-20230522191447-500x500.jpg?bch=470698"
            }
          ],
          "artist_map": {
            "artists": [
              {
                "id": "10145630",
                "name": "NUEKI",
                "url": "https://www.jiosaavn.com/artist/nueki-songs/ccNzlQYC4Pg_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "11591525",
                "name": " TOLCHONOV",
                "url": "https://www.jiosaavn.com/artist/-tolchonov-songs/5x4tyWOBXX8_",
                "role": "",
                "type": "artist",
                "image": ""
              }
            ],
            "featured_artists": [],
            "primary_artists": []
          },
          "song_count": 3,
          "songs": []
        },
        {
          "id": "44138980",
          "name": "Desperado",
          "subtitle": "",
          "type": "album",
          "language": "english",
          "play_count": 0,
          "explicit": false,
          "year": 0,
          "url": "https://www.jiosaavn.com/album/desperado/75-fkt,nFZw_",
          "header_desc": "",
          "list_count": 0,
          "list_type": "",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-50x50.jpg?bch=470698"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-150x150.jpg?bch=470698"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/036/Desperado-English-2023-20230607035147-500x500.jpg?bch=470698"
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
            "primary_artists": []
          },
          "song_count": 1,
          "songs": []
        }
      ]
    },
    "charts": {
      "title": "Top Charts",
      "subtitle": "",
      "position": 2,
      "source": "/get/charts",
      "featured_text": "The top movers this week, from our editors.",
      "data": [
        {
          "id": "1134595537",
          "name": "English: India Superhits Top 50",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/english-india-superhits-top-50/aXoCADwITrUCObrEMJSxEw__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/English-IndiaSuperhitsTop50_20230811090844.jpg",
          "count": 50
        },
        {
          "id": "1134548194",
          "name": "India Superhits Top 50",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/india-superhits-top-50/VuJUPQ9ch77bB,U5Yp5iAA__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/IndiaSuperhitsTop50_20230908052235.jpg",
          "count": 50
        },
        {
          "id": "7386899",
          "name": "Weekly Top Songs",
          "listname": "weekly-top-songs",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/weekly-top-songs/LdbVc1Z5i9E_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/wt15-7386899_20230908071849.jpg?bch=1694518200",
          "count": 30
        },
        {
          "id": "110858205",
          "name": "Trending Today",
          "subtitle": "JioSaavn",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/trending_today/I3kvhipIy73uCJW60TJk1Q__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/charts_TrendingToday_134351_20230826113717.jpg",
          "first_name": "JioSaavn",
          "language": "english"
        },
        {
          "id": "845149969",
          "name": "Romantic Top 40 -  English",
          "subtitle": "JioSaavn",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/romantic_top_40____english/jVmOAc1aK2OO0eMLZZxqsA__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/charts_RomanticTop40-English_158417_20220315153203.jpg",
          "first_name": "JioSaavn",
          "language": "english"
        }
      ]
    },
    "albums": {
      "title": "New Releases",
      "subtitle": "",
      "position": 3,
      "source": "/get/albums",
      "data": [
        {
          "id": "2211vHOQ",
          "name": "Bongos (feat. Megan Thee Stallion)",
          "subtitle": "Cardi B - Bongos (feat. Megan Thee Stallion)",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/bongos-feat.-megan-thee-stallion/QlpaAAJ4eGI",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/718/Bongos-feat-Megan-Thee-Stallion-English-2023-20230908034947-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/718/Bongos-feat-Megan-Thee-Stallion-English-2023-20230908034947-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/718/Bongos-feat-Megan-Thee-Stallion-English-2023-20230908034947-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 10944,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "",
          "artist_map": {
            "artists": [
              {
                "id": "1261541",
                "name": "Cardi B",
                "url": "https://www.jiosaavn.com/artist/cardi-b-songs/hWQq3QGVd3g_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Cardi_B_001_20200921152509_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Cardi_B_001_20200921152509_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Cardi_B_001_20200921152509_500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "1261541",
                "name": "Cardi B",
                "url": "https://www.jiosaavn.com/artist/cardi-b-songs/hWQq3QGVd3g_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Cardi_B_001_20200921152509_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Cardi_B_001_20200921152509_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Cardi_B_001_20200921152509_500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "Bongos (feat. Megan Thee Stallion)",
          "album_id": "48101963",
          "album_url": "https://www.jiosaavn.com/album/bongos-feat.-megan-thee-stallion/BfLsuj8BSKk_",
          "label": "Atlantic Records",
          "label_url": "",
          "origin": "none",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/718/9b43e611083b69bde38aa62fd1cd4d72_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/718/9b43e611083b69bde38aa62fd1cd4d72_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/718/9b43e611083b69bde38aa62fd1cd4d72_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/718/9b43e611083b69bde38aa62fd1cd4d72_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/718/9b43e611083b69bde38aa62fd1cd4d72_320.mp4"
            }
          ],
          "duration": 175,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "true",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-09-07",
          "triller_available": false,
          "copyright_text": "℗ 2023 Atlantic Recording Corporation"
        },
        {
          "id": "48091318",
          "name": "GUTS",
          "subtitle": "",
          "type": "album",
          "language": "english",
          "play_count": 0,
          "explicit": false,
          "year": 0,
          "url": "https://www.jiosaavn.com/album/guts/psk6Q-2w9hk_",
          "header_desc": "",
          "list_count": 0,
          "list_type": "",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/023/GUTS-English-2023-20230908063932-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/023/GUTS-English-2023-20230908063932-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/023/GUTS-English-2023-20230908063932-500x500.jpg"
            }
          ],
          "artist_map": {
            "artists": [
              {
                "id": "2255753",
                "name": "Olivia Rodrigo",
                "url": "https://www.jiosaavn.com/artist/olivia-rodrigo-songs/B6E0EBxDcT4_",
                "role": "music",
                "type": "artist",
                "image": ""
              }
            ],
            "featured_artists": [],
            "primary_artists": []
          },
          "song_count": 0,
          "songs": []
        },
        {
          "id": "EhMy9COO",
          "name": "Last Time I Saw You",
          "subtitle": "Nicki Minaj - Last Time I Saw You",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/last-time-i-saw-you/NQAmSE1zeHw",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/276/Last-Time-I-Saw-You-English-2023-20230901103545-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/276/Last-Time-I-Saw-You-English-2023-20230901103545-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/276/Last-Time-I-Saw-You-English-2023-20230901103545-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 85991,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Alex Bak, Onika Maraj, Jacob Canady, Lesidney Ragland, Derrick Miller, Colin Franken",
          "artist_map": {
            "artists": [
              {
                "id": "5583715",
                "name": "Alex Bak",
                "url": "https://www.jiosaavn.com/artist/alex-bak-songs/3N-GhqK,oAU_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "567558",
                "name": "Onika Maraj",
                "url": "https://www.jiosaavn.com/artist/onika-maraj-songs/4JYVHWWAOW4_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "4969242",
                "name": "Jacob Canady",
                "url": "https://www.jiosaavn.com/artist/jacob-canady-songs/N8lVhpkHHjI_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "6126535",
                "name": "Lesidney Ragland",
                "url": "https://www.jiosaavn.com/artist/lesidney-ragland-songs/KtNYeiB4OBY_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "3815637",
                "name": "Derrick Miller",
                "url": "https://www.jiosaavn.com/artist/derrick-miller-songs/1DN-bknjsO8_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "5580591",
                "name": "Colin Franken",
                "url": "https://www.jiosaavn.com/artist/colin-franken-songs/CmYQbQgTjxE_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "569160",
                "name": "Nicki Minaj",
                "url": "https://www.jiosaavn.com/artist/nicki-minaj-songs/Fd967MiHu-k_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Nicki_Minaj_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Nicki_Minaj_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Nicki_Minaj_500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "569160",
                "name": "Nicki Minaj",
                "url": "https://www.jiosaavn.com/artist/nicki-minaj-songs/Fd967MiHu-k_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "https://c.saavncdn.com/artists/Nicki_Minaj_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "https://c.saavncdn.com/artists/Nicki_Minaj_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "https://c.saavncdn.com/artists/Nicki_Minaj_500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "Last Time I Saw You",
          "album_id": "47950592",
          "album_url": "https://www.jiosaavn.com/album/last-time-i-saw-you/JGuQmj--H-w_",
          "label": "Republic Records",
          "label_url": "",
          "origin": "none",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/276/a847f8ceb08de4127a442a905b2c8f5b_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/276/a847f8ceb08de4127a442a905b2c8f5b_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/276/a847f8ceb08de4127a442a905b2c8f5b_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/276/a847f8ceb08de4127a442a905b2c8f5b_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/276/a847f8ceb08de4127a442a905b2c8f5b_320.mp4"
            }
          ],
          "duration": 217,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "true",
            "reason": ""
          },
          "has_lyrics": true,
          "lyrics_snippet": "I wish I'da hugged you tighter the last time that I saw you",
          "starred": false,
          "release_date": "2023-09-01",
          "triller_available": false,
          "copyright_text": "℗ 2023 Republic Records, a division of UMG Recordings, Inc."
        },
        {
          "id": "48109521",
          "name": "Layover",
          "subtitle": "",
          "type": "album",
          "language": "english",
          "play_count": 0,
          "explicit": false,
          "year": 0,
          "url": "https://www.jiosaavn.com/album/layover/BSvqvXWwke0_",
          "header_desc": "",
          "list_count": 0,
          "list_type": "",
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
                "role": "music",
                "type": "artist",
                "image": ""
              }
            ],
            "featured_artists": [],
            "primary_artists": []
          },
          "song_count": 0,
          "songs": []
        },
        {
          "id": "VN2e0s9n",
          "name": "Single Soon",
          "subtitle": "Selena Gomez - Single Soon",
          "type": "song",
          "url": "https://www.jiosaavn.com/song/single-soon/JiZZVERDDl0",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/440/Single-Soon-English-2023-20230825103551-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/440/Single-Soon-English-2023-20230825103551-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/440/Single-Soon-English-2023-20230825103551-500x500.jpg"
            }
          ],
          "language": "english",
          "year": 2023,
          "header_desc": "",
          "play_count": 139756,
          "explicit": false,
          "list": "",
          "list_type": "",
          "list_count": 0,
          "music": "Selena Gomez, Lisa Scinta, Ammar Malik, Benjamin Levin, Jacob Kasher Hindlin, Magnus August Høiberg, Phil Shaouy, Ross Golan",
          "artist_map": {
            "artists": [
              {
                "id": "603812",
                "name": "Selena Gomez",
                "url": "https://www.jiosaavn.com/artist/selena-gomez-songs/x45oK7RJ2E4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "http://c.saavncdn.com/artists/Selena_Gomez_002_20200226073835_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "http://c.saavncdn.com/artists/Selena_Gomez_002_20200226073835_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "http://c.saavncdn.com/artists/Selena_Gomez_002_20200226073835_500x500.jpg"
                  }
                ]
              },
              {
                "id": "678554",
                "name": "Lisa Scinta",
                "url": "https://www.jiosaavn.com/artist/lisa-scinta-songs/zsWQaMSZqns_",
                "role": "",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "http://c.saavncdn.com/047/Teenage-Dream-The-Voice-Performance--English-2012-20191011064540-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "http://c.saavncdn.com/047/Teenage-Dream-The-Voice-Performance--English-2012-20191011064540-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "http://c.saavncdn.com/047/Teenage-Dream-The-Voice-Performance--English-2012-20191011064540-500x500.jpg"
                  }
                ]
              },
              {
                "id": "606411",
                "name": "Ammar Malik",
                "url": "https://www.jiosaavn.com/artist/ammar-malik-songs/ASwIkuVuqoo_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "566441",
                "name": "Benjamin Levin",
                "url": "https://www.jiosaavn.com/artist/benjamin-levin-songs/2y5eaO04Ilc_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "570206",
                "name": "Jacob Kasher Hindlin",
                "url": "https://www.jiosaavn.com/artist/jacob-kasher-hindlin-songs/anqSKuozjn0_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "841154",
                "name": "Magnus August Høiberg",
                "url": "https://www.jiosaavn.com/artist/magnus-august-hoiberg-songs/EaIOKX1zkiM_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "1279259",
                "name": "Phil Shaouy",
                "url": "https://www.jiosaavn.com/artist/phil-shaouy-songs/7-zNG1lXoNg_",
                "role": "",
                "type": "artist",
                "image": ""
              },
              {
                "id": "602315",
                "name": "Ross Golan",
                "url": "https://www.jiosaavn.com/artist/ross-golan-songs/C0BoBPjZKCQ_",
                "role": "music",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "http://c.saavncdn.com/472/The-Wrong-Man-English-2019-20190726034547-50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "http://c.saavncdn.com/472/The-Wrong-Man-English-2019-20190726034547-150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "http://c.saavncdn.com/472/The-Wrong-Man-English-2019-20190726034547-500x500.jpg"
                  }
                ]
              }
            ],
            "featured_artists": [],
            "primary_artists": [
              {
                "id": "603812",
                "name": "Selena Gomez",
                "url": "https://www.jiosaavn.com/artist/selena-gomez-songs/x45oK7RJ2E4_",
                "role": "singer",
                "type": "artist",
                "image": [
                  {
                    "quality": "50x50",
                    "link": "http://c.saavncdn.com/artists/Selena_Gomez_002_20200226073835_50x50.jpg"
                  },
                  {
                    "quality": "150x150",
                    "link": "http://c.saavncdn.com/artists/Selena_Gomez_002_20200226073835_150x150.jpg"
                  },
                  {
                    "quality": "500x500",
                    "link": "http://c.saavncdn.com/artists/Selena_Gomez_002_20200226073835_500x500.jpg"
                  }
                ]
              }
            ]
          },
          "album": "Single Soon",
          "album_id": "47807270",
          "album_url": "https://www.jiosaavn.com/album/single-soon/sjJFQ3btwdo_",
          "label": "Interscope Records",
          "label_url": "",
          "origin": "none",
          "is_dolby_content": false,
          "320kbps": true,
          "download_url": [
            {
              "quality": "12kbps",
              "link": "https://aac.saavncdn.com/440/87cf859fe5cef4997851b4c3142e1e20_12.mp4"
            },
            {
              "quality": "48kbps",
              "link": "https://aac.saavncdn.com/440/87cf859fe5cef4997851b4c3142e1e20_48.mp4"
            },
            {
              "quality": "96kbps",
              "link": "https://aac.saavncdn.com/440/87cf859fe5cef4997851b4c3142e1e20_96.mp4"
            },
            {
              "quality": "160kbps",
              "link": "https://aac.saavncdn.com/440/87cf859fe5cef4997851b4c3142e1e20_160.mp4"
            },
            {
              "quality": "320kbps",
              "link": "https://aac.saavncdn.com/440/87cf859fe5cef4997851b4c3142e1e20_320.mp4"
            }
          ],
          "duration": 171,
          "rights": {
            "code": "0",
            "cacheable": "true",
            "delete_cached_object": "true",
            "reason": ""
          },
          "has_lyrics": false,
          "lyrics_snippet": "",
          "starred": false,
          "release_date": "2023-08-25",
          "triller_available": false,
          "copyright_text": "℗ 2023 Interscope Records",
          "vcode": "010912292073374",
          "vlink": "https://jiotunepreview.jio.com/content/Converted/010912292030495.mp3"
        }
      ]
    },
    "playlists": {
      "title": "Editorial Picks",
      "subtitle": "",
      "position": 4,
      "source": "/get/featured-playlists",
      "data": [
        {
          "id": "89593838",
          "name": "So Fresh Dance Hits",
          "subtitle": "12K Followers",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/so-fresh-dance-hits/rEDxb7swgvE_",
          "image": "https://c.saavncdn.com/editorial/SoFreshDanceHits_20230908094104.jpg",
          "explicit": false,
          "user_id": "phulki_user",
          "last_updated": "2023-09-08T02:41:38.000Z",
          "firstname": "JioSaavn",
          "follower_count": 12039,
          "songs": []
        },
        {
          "id": "1180899296",
          "name": " Chartbusters 2023 - English",
          "subtitle": "1.5K Followers",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/-chartbusters-2023-english/OnoB4SznwI1rxMGEuw5nRg__",
          "image": "https://c.saavncdn.com/editorial/Chartbusters2023English_20230710070658.jpg",
          "explicit": false,
          "user_id": "phulki_user",
          "last_updated": "2023-07-11T00:51:34.000Z",
          "firstname": "JioSaavn",
          "follower_count": 1463,
          "songs": []
        },
        {
          "id": "87510850",
          "name": "Most Streamed Love Songs - English",
          "subtitle": "Just Updated",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/most-streamed-love-songs-english/wHN0Jq26XqA_",
          "image": "https://c.saavncdn.com/editorial/MostStreamedLoveSongsEnglish_20230911104647.jpg",
          "explicit": false,
          "user_id": "phulki_user",
          "last_updated": "2023-09-11T03:53:34.000Z",
          "firstname": "JioSaavn",
          "follower_count": 16450,
          "songs": []
        },
        {
          "id": "902306817",
          "name": "VIRALnation",
          "subtitle": "31.2K Followers",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/viralnation/tfVkYjaAbZJieSJqt9HmOQ__",
          "image": "https://c.saavncdn.com/editorial/VIRALnation_20230908114326.jpg",
          "explicit": false,
          "user_id": "phulki_user",
          "last_updated": "2023-09-08T04:43:50.000Z",
          "firstname": "JioSaavn",
          "follower_count": 31198,
          "songs": []
        },
        {
          "id": "442379728",
          "name": "The Sound Of Afrobeat",
          "subtitle": "2K Followers",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/the-sound-of-afrobeat/QyqPhVd4ZFhFo9wdEAzFBA__",
          "image": "https://c.saavncdn.com/editorial/TheSoundOfAfrobeat_20230906195500.jpg",
          "explicit": false,
          "user_id": "phulki_user",
          "last_updated": "2023-09-06T12:55:43.000Z",
          "firstname": "JioSaavn",
          "follower_count": 2020,
          "songs": []
        }
      ]
    },
    "radio": {
      "title": "Radio Stations",
      "subtitle": "",
      "position": 6,
      "source": "/get/featured-stations",
      "data": [
        {
          "id": "Blues",
          "name": "Blues",
          "subtitle": "English Radio",
          "type": "radio_station",
          "url": "https://www.saavn.com/s/radio/english-featured-station/Blues",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/editorial/Blues_saavn_radio_20210528084631_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/editorial/Blues_saavn_radio_20210528084631_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/editorial/Blues_saavn_radio_20210528084631_500x500.jpg"
            }
          ],
          "featured_station_type": "featured",
          "language": "english",
          "station_display_text": "Blues",
          "color": "#a16a05",
          "description": "",
          "query": ""
        },
        {
          "id": "Drivetime",
          "name": "Drivetime",
          "subtitle": "English Radio",
          "type": "radio_station",
          "url": "https://www.saavn.com/s/radio/english-featured-station/Drivetime",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/editorial/WeekendDrive_saavn_radio_20201012143301_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/editorial/WeekendDrive_saavn_radio_20201012143301_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/editorial/WeekendDrive_saavn_radio_20201012143301_500x500.jpg"
            }
          ],
          "featured_station_type": "featured",
          "language": "english",
          "station_display_text": "Drivetime",
          "color": "#cf47c4",
          "description": "Long Drive on your mind? Hit 'Play'!",
          "query": ""
        },
        {
          "id": "Pop",
          "name": "Pop",
          "subtitle": "English Radio",
          "type": "radio_station",
          "url": "https://www.saavn.com/s/radio/english-featured-station/Pop",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/editorial/Pop_saavn_radio_20201012143651_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/editorial/Pop_saavn_radio_20201012143651_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/editorial/Pop_saavn_radio_20201012143651_500x500.jpg"
            }
          ],
          "featured_station_type": "featured",
          "language": "english",
          "station_display_text": "Pop",
          "color": "#08a15e",
          "description": "Swing to your Pop favourites!",
          "query": ""
        },
        {
          "id": "Chill",
          "name": "Chill",
          "subtitle": "English Radio",
          "type": "radio_station",
          "url": "https://www.saavn.com/s/radio/english-featured-station/Chill",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/editorial/Chill_saavn_radio_20201012143915_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/editorial/Chill_saavn_radio_20201012143915_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/editorial/Chill_saavn_radio_20201012143915_500x500.jpg"
            }
          ],
          "featured_station_type": "featured",
          "language": "english",
          "station_display_text": "Chill",
          "color": "#94b7f8",
          "description": "Your Destination to Relax and Unwind. Just Chill.",
          "query": ""
        },
        {
          "id": "Hit Factory",
          "name": "Hit Factory",
          "subtitle": "English Radio",
          "type": "radio_station",
          "url": "https://www.saavn.com/s/radio/english-featured-station/Hit-Factory",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/editorial/HitFactory_saavn_radio_20210226153042_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/editorial/HitFactory_saavn_radio_20210226153042_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/editorial/HitFactory_saavn_radio_20210226153042_500x500.jpg"
            }
          ],
          "featured_station_type": "featured",
          "language": "english",
          "station_display_text": "Hit Factory",
          "color": "#0290bf",
          "description": "",
          "query": ""
        }
      ]
    },
    "artist_recos": {
      "title": "Recommended Artist Stations",
      "subtitle": "",
      "position": 7,
      "source": "artist_recos|artistRecos",
      "data": [
        {
          "id": "459320",
          "name": "Arijit Singh",
          "subtitle": "Artist Radio",
          "type": "radio_station",
          "url": "https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_",
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
          ],
          "explicit": false,
          "query": "Arijit Singh",
          "featured_station_type": "artist",
          "station_display_text": "Arijit Singh"
        },
        {
          "id": "3319750",
          "name": "Sidhu Moose Wala",
          "subtitle": "Artist Radio",
          "type": "radio_station",
          "url": "https://www.jiosaavn.com/artist/sidhu-moose-wala-songs/ylevcL-ZuH8_",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/artists/Sidhu_Moose_Wala_20190627113332_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/artists/Sidhu_Moose_Wala_20190627113332_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/artists/Sidhu_Moose_Wala_20190627113332_500x500.jpg"
            }
          ],
          "explicit": false,
          "query": "Sidhu Moose Wala",
          "featured_station_type": "artist",
          "station_display_text": "Sidhu Moose Wala"
        },
        {
          "id": "881158",
          "name": "Jubin Nautiyal",
          "subtitle": "Artist Radio",
          "type": "radio_station",
          "url": "https://www.jiosaavn.com/artist/jubin-nautiyal-songs/uGdfg6zGf4s_",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/artists/Jubin_Nautiyal_002_20180507091834_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/artists/Jubin_Nautiyal_002_20180507091834_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/artists/Jubin_Nautiyal_002_20180507091834_500x500.jpg"
            }
          ],
          "explicit": false,
          "query": "Jubin Nautiyal",
          "featured_station_type": "artist",
          "station_display_text": "Jubin Nautiyal"
        },
        {
          "id": "455127",
          "name": "Udit Narayan",
          "subtitle": "Artist Radio",
          "type": "radio_station",
          "url": "https://www.jiosaavn.com/artist/udit-narayan-songs/kLtmb7Vh8Rs_",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/artists/Udit_Narayan_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/artists/Udit_Narayan_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/artists/Udit_Narayan_500x500.jpg"
            }
          ],
          "explicit": false,
          "query": "Udit Narayan",
          "featured_station_type": "artist",
          "station_display_text": "Udit Narayan"
        },
        {
          "id": "788130",
          "name": "B Praak",
          "subtitle": "Artist Radio",
          "type": "radio_station",
          "url": "https://www.jiosaavn.com/artist/b-praak-songs/CfABr-vmQdw_",
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/artists/B_Praak_001_20191118112005_50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/artists/B_Praak_001_20191118112005_150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/artists/B_Praak_001_20191118112005_500x500.jpg"
            }
          ],
          "explicit": false,
          "query": "B Praak",
          "featured_station_type": "artist",
          "station_display_text": "B Praak"
        }
      ]
    },
    "discover": {
      "title": "",
      "subtitle": "",
      "position": -1,
      "source": "N/A",
      "data": [
        {
          "id": "27",
          "name": "Romance",
          "subtitle": "",
          "type": "channel",
          "url": "https://www.jiosaavn.com/s/channel/romance/SqI6f167Uoo_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/RPQXRCUT55-station__20221007155650.jpg",
          "badge": "",
          "is_featured": true,
          "video_thumbnail": "https://c.saavncdn.com/editorial/videos/romance_2.jpg",
          "video_url": "http://c.saavncdn.com/editorial/videos/romance_3.mp4",
          "sub_type": "mood",
          "tags": { "mood": ["Romantic"] }
        },
        {
          "id": "189",
          "name": "The College Playlists",
          "subtitle": "",
          "type": "channel",
          "url": "https://www.jiosaavn.com/s/channel/the-college-playlists/fnBZ8dFeIoM_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/i39f98BI9I-CollegePlaylists_20230515083010.jpg",
          "badge": "",
          "is_featured": true,
          "video_thumbnail": "",
          "video_url": "",
          "sub_type": "mood",
          "tags": { "situation": ["College Top 20"] }
        },
        {
          "id": "40",
          "name": "Dance",
          "subtitle": "",
          "type": "channel",
          "url": "https://www.jiosaavn.com/s/channel/dance/,06BpBddRTw_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/R627Kir5MG-station__20221007160900.jpg",
          "badge": "",
          "is_featured": true,
          "video_thumbnail": "https://c.saavncdn.com/editorial/videos/dance_2.jpg",
          "video_url": "http://c.saavncdn.com/editorial/videos/dance_3.mp4",
          "sub_type": "mood",
          "tags": { "situation": ["Dance"] }
        },
        {
          "id": "29",
          "name": "Workout",
          "subtitle": "",
          "type": "channel",
          "url": "https://www.jiosaavn.com/s/channel/workout/hR6iDdclo1Y_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/MPFnHRHXoL-station__20220317063811.jpg",
          "badge": "",
          "is_featured": true,
          "video_thumbnail": "https://c.saavncdn.com/editorial/videos/workout_2.jpg",
          "video_url": "http://c.saavncdn.com/editorial/videos/workout_3.mp4",
          "sub_type": "mood",
          "tags": { "situation": ["Workout"] }
        },
        {
          "id": "46",
          "name": "The 1990s",
          "subtitle": "",
          "type": "channel",
          "url": "https://www.jiosaavn.com/s/channel/the-1990s/USAZn3XRH3w_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/pFq3HgYvgq-station__20220317063205.jpg",
          "badge": "",
          "is_featured": true,
          "video_thumbnail": "https://c.saavncdn.com/editorial/videos/the-1990s_2.jpg",
          "video_url": "http://c.saavncdn.com/editorial/videos/1990_2.mp4",
          "sub_type": "mood",
          "tags": { "seasonality": ["1990s"] }
        }
      ]
    },
    "city_mod": {
      "title": "",
      "subtitle": "",
      "position": -1,
      "source": "city_mod|cityMod",
      "data": []
    },
    "mixes": {
      "title": "",
      "subtitle": "",
      "position": -1,
      "source": "mixes",
      "data": []
    },
    "promo0": {
      "title": "September To Remember",
      "subtitle": "",
      "position": 8,
      "source": "promo0",
      "data": [
        {
          "id": "158224044",
          "name": "Decade of 2010s - Romance - English",
          "subtitle": "Camila Cabello, Shawn Mendes, Ellie Goulding, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/decade-of-2010s-romance-english/d,HCD5HV9ODufxkxMEIbIw__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/Decadeof2010sRomanceEnglish_20230831080607.jpg"
        },
        {
          "id": "824507215",
          "name": "Best Of  80s - English",
          "subtitle": "Michael Jackson, Wham!, and Rick Astley",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-80s-english/o585,v3hDQbuCJW60TJk1Q__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestOf80sEnglish_20230830061653.jpg"
        },
        {
          "id": "114249253",
          "name": "2000s Hip Hop - English",
          "subtitle": "Eminem, 50 Cent, and Dmx",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/2000s-hip-hop-english/C-XFmFRNaVYwkg5tVhI3fw__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/2000sHipHopEnglish_20230831155150.jpg"
        },
        {
          "id": "824506610",
          "name": "Best Of 70s - English",
          "subtitle": "Aerosmith, Boney M., and The Police",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-70s-english/VO1bwwa6Vt1uOxiEGmm6lQ__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestOf70sEnglish_20230831155329.jpg"
        },
        {
          "id": "211185750",
          "name": "80s Rock Hits",
          "subtitle": "Bon Jovi, Guns N' Roses, and AC/DC",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/80s-rock-hits/nvjKc2vyim1uOxiEGmm6lQ__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/80sRockHits_20230831154331.jpg"
        }
      ]
    },
    "promo1": {
      "title": "Fresh Hits",
      "subtitle": "",
      "position": 9,
      "source": "promo1",
      "data": [
        {
          "id": "85481065",
          "name": "Fresh Tunes",
          "subtitle": "Just Updated",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/fresh-tunes/Ns2UZo9qDvI_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/FreshTunes_20230908092705.jpg",
          "editorial_language": "english"
        },
        {
          "id": "81169234",
          "name": "Now Playing Pop",
          "subtitle": "Selena Gomez, Charlie Puth, Jung Kook, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/now-playing-pop/IQO11xk800E_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/NowPlayingPop_20230906091922.jpg",
          "editorial_language": "english"
        },
        {
          "id": "86183802",
          "name": "Rap Cypher - English",
          "subtitle": "Nicki Minaj, Doja Cat, and Travis Scott",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/rap-cypher-english/nc,LQ5hFF2I_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/RapCypherEnglish_20230908105034.jpg"
        },
        {
          "id": "81399744",
          "name": "Heartbeats",
          "subtitle": "Armaan Malik, Taylor Swift, Ed Sheeran, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/heartbeats/8j,bJexTYcE_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/Heartbeats_20230809083724.jpg",
          "editorial_language": "english"
        },
        {
          "id": "84639340",
          "name": "Just Dance",
          "subtitle": "Dua Lipa, Mae Stephens, Madonna, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/just-dance/ykq09QJIZlU_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/JustDance_20230830101643.jpg"
        }
      ]
    },
    "promo2": {
      "title": "Best of 90s",
      "subtitle": "",
      "position": 10,
      "source": "promo2",
      "data": [
        {
          "id": "112817978",
          "name": "90s House Party",
          "subtitle": "Aqua, Vengaboys, and Jennifer Lopez",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/90s-house-party/Ie4aE52YW91Fo9wdEAzFBA__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/logo/90sHouseParty_20210817063300.jpg"
        },
        {
          "id": "84576165",
          "name": "90s Hip Hop",
          "subtitle": "Coolio, 2pac, and The Notorious B.I.G.",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/90s-hip-hop/rH5bbrSh6mU_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/90sHipHop_20230313063054.jpg"
        },
        {
          "id": "83538962",
          "name": "90s Rock Hits",
          "subtitle": "Nirvana, Smash Mouth, and The Cranberries",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/90s-rock-hits/Qpi9A-C6XuA_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/logo/That90sRock_20210310184208.jpg"
        },
        {
          "id": "33085749",
          "name": "90s Boy Bands",
          "subtitle": "Backstreet Boys, *nsync, and Boyzone",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/90s-boy-bands/GJYfME1bv,4_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/90sBoyBands_20230831155104.jpg"
        },
        {
          "id": "802132644",
          "name": "Best Of 90s - English",
          "subtitle": "Backstreet Boys, Britney Spears, Céline Dion, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-90s-english/dO89Ji-UF1vufxkxMEIbIw__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestOf90sEnglish_20230831071808.jpg"
        }
      ]
    },
    "promo3": {
      "title": "All Time Favourites - English",
      "subtitle": "",
      "position": 11,
      "source": "promo3",
      "data": [
        {
          "id": "1064986202",
          "name": "Chartbusters 2022 - English",
          "subtitle": "Harry Styles, Badshah, J Balvin, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/chartbusters-2022-english/RDAcxj7fTgOHzIkTq9r3nw__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/Chartbusters2022English_20221207065930.jpg",
          "editorial_language": "english"
        },
        {
          "id": "52312344",
          "name": "Let's Play - Justin Bieber",
          "subtitle": "Justin Bieber",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/lets-play-justin-bieber/fHF5W2y22Wc_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/logo/BestofBieber_20210101103129.jpg"
        },
        {
          "id": "87524772",
          "name": "Let's Play - One Direction",
          "subtitle": "One Direction",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/lets-play-one-direction/d5sEddGFWv4_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/logo/ThereisonlyOneDirection_20211110040907.jpg"
        },
        {
          "id": "158224294",
          "name": "Chartbusters 2016 - English",
          "subtitle": "Dj Snake, The Weeknd, and The Chainsmokers",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/chartbusters-2016-english/HlVm42n2zg7ufxkxMEIbIw__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/logo/2016Chartbusters_20210806095503.jpg"
        },
        {
          "id": "90522027",
          "name": "Let's Play - Alan Walker",
          "subtitle": "Alan Walker, Farruko, and Sabrina Carpenter",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/lets-play-alan-walker/277qKJrlBTo_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/Let_sPlayAlanWalker_20230809091030.jpg"
        }
      ]
    },
    "promo4": {
      "title": "Trending Podcasts",
      "subtitle": "Most heard in India",
      "position": 5,
      "source": "promo4",
      "data": [
        {
          "id": "63565",
          "name": "Shri Krishna Amritvani",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/shri-krishna-amritvani/1/q3nfP8Sr8ZM_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.sop.saavncdn.com/Shri-Krishna-Amritvani-20211001160841-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.sop.saavncdn.com/Shri-Krishna-Amritvani-20211001160841-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.sop.saavncdn.com/Shri-Krishna-Amritvani-20211001160841-500x500.jpg"
            }
          ]
        },
        {
          "id": "3087",
          "name": "Ramayan Hindi",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/ramayan-hindi/1/VrqL6MVpteI_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.sop.saavncdn.com/Ramayan-Hindi-20230806123927-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.sop.saavncdn.com/Ramayan-Hindi-20230806123927-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.sop.saavncdn.com/Ramayan-Hindi-20230806123927-500x500.jpg"
            }
          ]
        },
        {
          "id": "315650",
          "name": "IAS Prachi | आईएएस प्राची | Author- Pragati Gupta",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/ias-prachi-%7c-%e0%a4%86%e0%a4%88%e0%a4%8f%e0%a4%8f%e0%a4%b8-%e0%a4%aa%e0%a5%8d%e0%a4%b0%e0%a4%be%e0%a4%9a%e0%a5%80-%7c-author-pragati-gupta/1/4LPSiUkQxFE_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.sop.saavncdn.com/IAS-Prachi-Author-Pragati-Gupta-20221021051322-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.sop.saavncdn.com/IAS-Prachi-Author-Pragati-Gupta-20221021051322-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.sop.saavncdn.com/IAS-Prachi-Author-Pragati-Gupta-20221021051322-500x500.jpg"
            }
          ]
        },
        {
          "id": "315926",
          "name": "Hanuman Chalisa ( Explanation)",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/hanuman-chalisa-explanation/1/TkB2L7mGtQI_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.sop.saavncdn.com/Hanuman-Chalisa-Explanation-20221104123422-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.sop.saavncdn.com/Hanuman-Chalisa-Explanation-20221104123422-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.sop.saavncdn.com/Hanuman-Chalisa-Explanation-20221104123422-500x500.jpg"
            }
          ]
        },
        {
          "id": "164110",
          "name": "Bhagavad Gita (Hindi)",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/bhagavad-gita-hindi/1/ckb,X9Mcgq4_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.sop.saavncdn.com/Yatharth-Geeta-Hindi-20211207111212-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.sop.saavncdn.com/Yatharth-Geeta-Hindi-20211207111212-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.sop.saavncdn.com/Yatharth-Geeta-Hindi-20211207111212-500x500.jpg"
            }
          ]
        }
      ]
    },
    "promo5": {
      "title": "Top Albums - English",
      "subtitle": "",
      "position": 12,
      "source": "promo5",
      "data": [
        {
          "id": "1759503",
          "name": "This Is Acting",
          "subtitle": "",
          "type": "album",
          "url": "https://www.jiosaavn.com/album/this-is-acting/WvjkPt-7qiM_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/203/This-Is-Acting-English-2016-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/203/This-Is-Acting-English-2016-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/203/This-Is-Acting-English-2016-500x500.jpg"
            }
          ],
          "language": "",
          "list": "",
          "list_count": 0,
          "list_type": "",
          "release_year": 2016
        },
        {
          "id": "36493120",
          "name": "Special",
          "subtitle": "",
          "type": "album",
          "url": "https://www.jiosaavn.com/album/special/eZ1mCKwjnLQ_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/130/Special-English-2022-20220804070818-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/130/Special-English-2022-20220804070818-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/130/Special-English-2022-20220804070818-500x500.jpg"
            }
          ],
          "language": "",
          "list": "",
          "list_count": 0,
          "list_type": "",
          "release_year": 2022
        },
        {
          "id": "23241654",
          "name": "Future Nostalgia",
          "subtitle": "",
          "type": "album",
          "url": "https://www.jiosaavn.com/album/future-nostalgia/ITIyo-GDr7A_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/665/Future-Nostalgia-English-2020-20210608164518-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/665/Future-Nostalgia-English-2020-20210608164518-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/665/Future-Nostalgia-English-2020-20210608164518-500x500.jpg"
            }
          ],
          "language": "",
          "list": "",
          "list_count": 0,
          "list_type": "",
          "release_year": 2020
        },
        {
          "id": "1215569",
          "name": "FOUR (Deluxe)",
          "subtitle": "",
          "type": "album",
          "url": "https://www.jiosaavn.com/album/four-deluxe/tbBfBMWGM6E_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/851/FOUR-Deluxe--English-2014-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/851/FOUR-Deluxe--English-2014-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/851/FOUR-Deluxe--English-2014-500x500.jpg"
            }
          ],
          "language": "",
          "list": "",
          "list_count": 0,
          "list_type": "",
          "release_year": 2014
        },
        {
          "id": "30892546",
          "name": "World Of Walker",
          "subtitle": "",
          "type": "album",
          "url": "https://www.jiosaavn.com/album/world-of-walker/fiEAwejsHmQ_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "https://c.saavncdn.com/935/World-Of-Walker-Unknown-2021-20211126205629-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "https://c.saavncdn.com/935/World-Of-Walker-Unknown-2021-20211126205629-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "https://c.saavncdn.com/935/World-Of-Walker-Unknown-2021-20211126205629-500x500.jpg"
            }
          ],
          "language": "",
          "list": "",
          "list_count": 0,
          "list_type": "",
          "release_year": 2021
        }
      ]
    },
    "promo6": {
      "title": "Best of",
      "subtitle": "",
      "position": 13,
      "source": "promo6",
      "data": [
        {
          "id": "85159322",
          "name": "Best of EDM - English",
          "subtitle": "Alan Walker, Major Lazer, and Dj Snake",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-edm-english/u4jg0E7Pjt4_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestofEDMEnglish_20230703104001.jpg"
        },
        {
          "id": "410785269",
          "name": "Best of K-Pop",
          "subtitle": "BTS, Lisa, and Fifty Fifty",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-k-pop/-,-31WVKSbiO0eMLZZxqsA__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/KpopBoolgeumWeekendEDM_20230125053051.jpg"
        },
        {
          "id": "158226586",
          "name": "Best Of Latin Pop",
          "subtitle": "Daddy Yankee, Enrique Iglesias, and Don Omar",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-latin-pop/zfs3622ON9HfemJ68FuXsA__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestOfLatinPop_20230630135408.jpg"
        },
        {
          "id": "78211018",
          "name": "Best of Dance -  English",
          "subtitle": "Spice, Jain, Jason Derulo, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-dance-english/l-B,YKTNVVc_",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestofDanceEnglish_20230207045231.jpg"
        },
        {
          "id": "303128179",
          "name": "Best of Pop - English",
          "subtitle": "Justin Bieber, The Kid Laroi, Sia, and more",
          "type": "playlist",
          "url": "https://www.jiosaavn.com/featured/best-of-pop-english/oqKee-6aXESO0eMLZZxqsA__",
          "explicit": false,
          "image": "https://c.saavncdn.com/editorial/BestofPopEnglish_20230605101859.jpg"
        }
      ]
    },
    "promo7": {
      "title": "Ishq Wale Podcasts",
      "subtitle": "Pyaar bhari kahaniyan",
      "position": 14,
      "source": "promo7",
      "data": [
        {
          "id": "194661",
          "name": " लव स्टोरी ",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/-%e0%a4%b2%e0%a4%b5-%e0%a4%b8%e0%a5%8d%e0%a4%9f%e0%a5%8b%e0%a4%b0%e0%a5%80-/1/PGFMH,Db98Q_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "http://c.sop.saavncdn.com/-20230102133012-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "http://c.sop.saavncdn.com/-20230102133012-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "http://c.sop.saavncdn.com/-20230102133012-500x500.jpg"
            }
          ]
        },
        {
          "id": "71214",
          "name": "DHADKANE MERI SUN",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/dhadkane-meri-sun/1/YZxHhNAGfv0_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "http://c.sop.saavncdn.com/DHADKANE-MERI-SUN-20230517103017-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "http://c.sop.saavncdn.com/DHADKANE-MERI-SUN-20230517103017-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "http://c.sop.saavncdn.com/DHADKANE-MERI-SUN-20230517103017-500x500.jpg"
            }
          ]
        },
        {
          "id": "314998",
          "name": "Tumne Kisi Se Kabhi Pyaar Kiya Hai?",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/tumne-kisi-se-kabhi-pyaar-kiya-hai/1/vb3Z6hVFkKY_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "http://c.sop.saavncdn.com/Tumne-Kisi-Se-Kabhi-Pyaar-Kiya-Hai-20230531113515-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "http://c.sop.saavncdn.com/Tumne-Kisi-Se-Kabhi-Pyaar-Kiya-Hai-20230531113515-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "http://c.sop.saavncdn.com/Tumne-Kisi-Se-Kabhi-Pyaar-Kiya-Hai-20230531113515-500x500.jpg"
            }
          ]
        },
        {
          "id": "436644",
          "name": "Saawan Barse Dil Tarse : Monsoon Love Stories : Romantic Stories",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/saawan-barse-dil-tarse-monsoon-love-stories-romantic-stories/1/8BlbRtv8U2U_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "http://c.sop.saavncdn.com/Saawan-Barse-Dil-Tarse-Monsoon-Love-Stories-Romantic-Stories-20230901090636-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "http://c.sop.saavncdn.com/Saawan-Barse-Dil-Tarse-Monsoon-Love-Stories-Romantic-Stories-20230901090636-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "http://c.sop.saavncdn.com/Saawan-Barse-Dil-Tarse-Monsoon-Love-Stories-Romantic-Stories-20230901090636-500x500.jpg"
            }
          ]
        },
        {
          "id": "315657",
          "name": "Yeh Hain Chahtein | ये है चाहतें | Author- Vandana Sharma",
          "subtitle": "",
          "type": "show",
          "url": "https://www.jiosaavn.com/shows/yeh-hain-chahtein-%7c-%e0%a4%af%e0%a5%87-%e0%a4%b9%e0%a5%88-%e0%a4%9a%e0%a4%be%e0%a4%b9%e0%a4%a4%e0%a5%87%e0%a4%82-%7c-author-vandana-sharma/1/k0qpuv3bAC0_",
          "explicit": false,
          "image": [
            {
              "quality": "50x50",
              "link": "http://c.sop.saavncdn.com/Yeh-Hain-Chahtein-Author-Vandana-Sharma-20221021065541-50x50.jpg"
            },
            {
              "quality": "150x150",
              "link": "http://c.sop.saavncdn.com/Yeh-Hain-Chahtein-Author-Vandana-Sharma-20221021065541-150x150.jpg"
            },
            {
              "quality": "500x500",
              "link": "http://c.sop.saavncdn.com/Yeh-Hain-Chahtein-Author-Vandana-Sharma-20221021065541-500x500.jpg"
            }
          ]
        }
      ]
    },
    "global_config": {
      "weekly_top_songs_listid": {
        "english": {
          "listid": "7386899",
          "image": "https://c.saavncdn.com/editorial/wt15-7386899_20230908071849.jpg?bch=1694518200",
          "title": "Weekly Top Songs",
          "count": 30
        }
      },
      "random_songs_listid": {
        "english": {
          "listid": "2212321",
          "image": "https://pli.saavncdn.com/23/21/2212321.jpg",
          "count": 1007
        }
      },
      "phn_otp_providers": { "+91": "jio" }
    }
  }
}
```

+++

|           **Query** **Parameter**           |                                                                                                    **Description**                                                                                                    |              **Required**               |
| :-----------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------: |
| [!badge variant="contrast" text="language"] | one or more comma separated languages</br>`hindi`, `english`, `punjabi`, `tamil`, `telugu`, `marathi`,`gujarati`, `bengali`, `kannada`, `bhojpuri`, `malayalam`, `urdu`, `haryanvi`, `rajasthani`, `odia`, `assamese` | [!badge variant="primary" text="False"] |
|  [!badge variant="contrast" text="camel"]   |                                                                                               `camelCase` response keys                                                                                               | [!badge variant="primary" text="False"] |
|   [!badge variant="contrast" text="raw"]    |                                                                                           raw response from `Jiosaavn API`                                                                                            | [!badge variant="primary" text="False"] |
