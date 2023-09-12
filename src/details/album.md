---
order: 90
icon: stack
---

# Album Details

!!! Note
<https://jiosaavn.shuttleapp.rs> is only meant to demo the API and has rate-limiting enabled to minimise bandwidth consumption.
It is recommended to deploy your own instance for personal use.
!!!

## Album details by album ID

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/album?id=25500145
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/album?id=25500145' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|          **Query Parameter**          | **Description** |              **Required**              |
| :-----------------------------------: | :-------------: | :------------------------------------: |
| [!badge variant="contrast" text="id"] |    Album ID     | [!badge variant="primary" text="True"] |

## Album details by link

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/album?link=https://www.jiosaavn.com/album/ram-siya-ram/cy9LsEw-pn0_
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/album?link=https://www.jiosaavn.com/album/ram-siya-ram/cy9LsEw-pn0_' \
 -H 'content-type: application/json'
```

+++ Response

```json

```

+++

|           **Query Parameter**           |            **Description**             |              **Required**              |
| :-------------------------------------: | :------------------------------------: | :------------------------------------: |
| [!badge variant="contrast" text="link"] | Album link from <https://jiosaavn.com> | [!badge variant="primary" text="True"] |

## Album Recommendations by album ID

+++ Request

HTTP

```bash
https://jiosaavn.shuttleapp.rs/album/recommendations?id=25500145
```

cURL

```bash
curl -X GET 'https://jiosaavn.shuttleapp.rs/album/recommendations?id=25500145' \
 -H 'content-type: application/json'
```

+++ Response

```json
{
  "status": "Success",
  "message": "✅ Successfully fetched album recommendations",
  "data": [
    {
      "id": "44249002",
      "name": "Jai Shri Ram (Hindi)",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/jai-shri-ram-hindi/-IOxFC9xlko_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/393/Jai-Shri-Ram-Hindi-Hindi-2023-20230511171009-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/393/Jai-Shri-Ram-Hindi-Hindi-2023-20230511171009-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/393/Jai-Shri-Ram-Hindi-Hindi-2023-20230511171009-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "42882472",
      "name": "Radhe Radhe",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/radhe-radhe/21KgBNjSpFc_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/716/Radhe-Radhe-Hindi-2020-20230222194734-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/716/Radhe-Radhe-Hindi-2020-20230222194734-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/716/Radhe-Radhe-Hindi-2020-20230222194734-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "33062718",
      "name": "Mahadev Ke Deewane",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/mahadev-ke-deewane/eH5hxZE6nCA_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/411/Mahadev-Ke-Deewane-Hindi-2022-20220222011001-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/411/Mahadev-Ke-Deewane-Hindi-2022-20220222011001-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/411/Mahadev-Ke-Deewane-Hindi-2022-20220222011001-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "38162579",
      "name": "Radhe Radhe Barsane Wali Radhe",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/radhe-radhe-barsane-wali-radhe/iwbvK9cuukw_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/035/Radhe-Radhe-Barsane-Wali-Radhe-Hindi-2022-20220913102408-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/035/Radhe-Radhe-Barsane-Wali-Radhe-Hindi-2022-20220913102408-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/035/Radhe-Radhe-Barsane-Wali-Radhe-Hindi-2022-20220913102408-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "21902776",
      "name": "Shri Krishna Govind Hare Murari",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/shri-krishna-govind-hare-murari/pq8zZ7GVLQg_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/021/Shri-Krishna-Govind-Hare-Murari-Hindi-2020-20200806224005-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/021/Shri-Krishna-Govind-Hare-Murari-Hindi-2020-20200806224005-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/021/Shri-Krishna-Govind-Hare-Murari-Hindi-2020-20200806224005-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "25605376",
      "name": "Krishna Bhajan - Lagan Tumse Laga Baithe",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/krishna-bhajan-lagan-tumse-laga-baithe/o21Jcy8VKZg_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/735/Krishna-Bhajan-Lagan-Tumse-Laga-Baithe-Hindi-2021-20210227002702-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/735/Krishna-Bhajan-Lagan-Tumse-Laga-Baithe-Hindi-2021-20210227002702-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/735/Krishna-Bhajan-Lagan-Tumse-Laga-Baithe-Hindi-2021-20210227002702-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "28311436",
      "name": "Shiv Tandav Stotram (Har Har Shiv Shankar)",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/shiv-tandav-stotram-har-har-shiv-shankar/ze4eTF8HXV0_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/211/Shiv-Tandav-Stotram-Har-Har-Shiv-Shankar--Hindi-2021-20210709031001-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/211/Shiv-Tandav-Stotram-Har-Har-Shiv-Shankar--Hindi-2021-20210709031001-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/211/Shiv-Tandav-Stotram-Har-Har-Shiv-Shankar--Hindi-2021-20210709031001-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "13762534",
      "name": "Shiv Tandav",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/shiv-tandav/WoQ8Ydpt3sA_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/192/Shiv-Tandav-Hindi-2018-20180831-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/192/Shiv-Tandav-Hindi-2018-20180831-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/192/Shiv-Tandav-Hindi-2018-20180831-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "36054194",
      "name": "Bholenath Ji",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/bholenath-ji/8FZMGY,9Pm0_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/490/Bholenath-Ji-Hindi-2022-20220628102254-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/490/Bholenath-Ji-Hindi-2022-20220628102254-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/490/Bholenath-Ji-Hindi-2022-20220628102254-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "24627112",
      "name": "Hare Krishna Hare",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/hare-krishna-hare/BlNWDJp4htg_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/482/Hare-Krishna-Hare-Hindi-2021-20210114031001-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/482/Hare-Krishna-Hare-Hindi-2021-20210114031001-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/482/Hare-Krishna-Hare-Hindi-2021-20210114031001-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "33019801",
      "name": "Radha Krishna Serial All Song",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/radha-krishna-serial-all-song/J,CmHE1AZvQ_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/872/Radha-Krishna-Serial-All-Song-Hindi-2022-20220218171711-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/872/Radha-Krishna-Serial-All-Song-Hindi-2022-20220218171711-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/872/Radha-Krishna-Serial-All-Song-Hindi-2022-20220218171711-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "30066271",
      "name": "Meri Maa Ke Barabar Koi Nahi",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/meri-maa-ke-barabar-koi-nahi/EIICtTXEp4k_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/832/Meri-Maa-Ke-Barabar-Koi-Nahi-Hindi-2021-20220307121001-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/832/Meri-Maa-Ke-Barabar-Koi-Nahi-Hindi-2021-20220307121001-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/832/Meri-Maa-Ke-Barabar-Koi-Nahi-Hindi-2021-20220307121001-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "45557446",
      "name": "Ram Siya Ram (From &quot;Adipurush&quot;)",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/ram-siya-ram-from-adipurush/o21EQ2PGLsk_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/916/Ram-Siya-Ram-From-Adipurush-Hindi-2023-20230530192919-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/916/Ram-Siya-Ram-From-Adipurush-Hindi-2023-20230530192919-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/916/Ram-Siya-Ram-From-Adipurush-Hindi-2023-20230530192919-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "15322610",
      "name": "Achyutam Keshavam Krishna Damodaram - Zee Music Devotional",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/achyutam-keshavam-krishna-damodaram-zee-music-devotional/GY7aMeAzR6E_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/610/Achyutam-Keshavam-Krishna-Damodaram-Zee-Music-Devotional-Hindi-2019-20190402064504-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/610/Achyutam-Keshavam-Krishna-Damodaram-Zee-Music-Devotional-Hindi-2019-20190402064504-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/610/Achyutam-Keshavam-Krishna-Damodaram-Zee-Music-Devotional-Hindi-2019-20190402064504-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "39209161",
      "name": "Mere Ghar Ram Aaye Hain",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/mere-ghar-ram-aaye-hain/dsife5uVB1k_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/946/Mere-Ghar-Ram-Aaye-Hain-Hindi-2022-20221019191009-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/946/Mere-Ghar-Ram-Aaye-Hain-Hindi-2022-20221019191009-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/946/Mere-Ghar-Ram-Aaye-Hain-Hindi-2022-20221019191009-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    },
    {
      "id": "22339081",
      "name": "Mangal Bhawan Amangal Haari",
      "subtitle": "",
      "type": "album",
      "language": "",
      "playCount": 0,
      "explicit": false,
      "year": 0,
      "url": "https://www.jiosaavn.com/album/mangal-bhawan-amangal-haari/5TFD4jjLGUQ_",
      "image": [
        {
          "quality": "50x50",
          "link": "http://c.saavncdn.com/572/Mangal-Bhawan-Amangal-Haari-Hindi-2020-20200907055635-50x50.jpg"
        },
        {
          "quality": "150x150",
          "link": "http://c.saavncdn.com/572/Mangal-Bhawan-Amangal-Haari-Hindi-2020-20200907055635-150x150.jpg"
        },
        {
          "quality": "500x500",
          "link": "http://c.saavncdn.com/572/Mangal-Bhawan-Amangal-Haari-Hindi-2020-20200907055635-500x500.jpg"
        }
      ],
      "releaseDate": null,
      "artistMap": null,
      "songCount": null,
      "copyrightText": null,
      "isDolbyContent": null,
      "songs": []
    }
  ]
}
```

+++

|          **Query Parameter**          | **Description** |              **Required**              |
| :-----------------------------------: | :-------------: | :------------------------------------: |
| [!badge variant="contrast" text="id"] |    Album ID     | [!badge variant="primary" text="True"] |
