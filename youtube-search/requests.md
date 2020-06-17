# YouTube Search API Requests & Responses

## Request first page of YouTube Search Results

| Parameter |              Description               |
| --------- | :------------------------------------: |
| q         | The search query (must be URL Encoded) |

```bash
curl --request GET \
	--url 'https://youtube-search-results.p.rapidapi.com/sr?q=justin%252Bbieber' \
	--header 'x-rapidapi-host: youtube-search-results.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXX'
```

### Response

```json
{
  "query": "justin bieber",
  "items": [
    {
      "id": "8EJ3zbKTWQ8",
      "type": "video",
      "title": "Justin Bieber - Yummy (Official Video)",
      "link": "https://www.youtube.com/watch?v=8EJ3zbKTWQ8",
      "thumbnail": "https://i.ytimg.com/vi/8EJ3zbKTWQ8/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAUi04-Pq8KGONBi6bIjg2hu1hQxA",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
      "views": 411969057,
      "duration": "3:51",
      "uploaded_at": "5 months ago"
    },
    {
      "type": "channel",
      "name": "Justin Bieber",
      "channel_id": "UCIwFjwMjI0y7PDBVEO9-bkQ",
      "link": "https://www.youtube.com/user/kidrauhl",
      "avatar": "https://lh3.googleusercontent.com/a-/AOh14GjLNDp0_qd6-QiVBZqlrz0JAySMB41MXgIRrt691w=s176-c-k-c0x00ffffff-no-rj-mo",
      "verified": false,
      "followers": 0,
      "description_short": "Help change the world. http://stuckwithu.lnk.to/agjb.",
      "videos": 172
    },
    {
      "type": "shelf-vertical",
      "title": "Latest from Justin Bieber",
      "items": [
        {
          "id": "TiK7QtIHy_Y",
          "type": "video",
          "title": "Justin Bieber - E.T.A. (Nature Visual)",
          "link": "https://www.youtube.com/watch?v=TiK7QtIHy_Y",
          "thumbnail": "https://i.ytimg.com/vi/TiK7QtIHy_Y/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCpPLGO0u1uGx51SmzxLGBOkGn0Pw",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 4512497,
          "duration": "2:56",
          "uploaded_at": "2 weeks ago"
        },
        {
          "id": "nrJTtH3cw0o",
          "type": "video",
          "title": "Ariana Grande, Justin Bieber - Stuck with U (Mother's Day Edition)",
          "link": "https://www.youtube.com/watch?v=nrJTtH3cw0o",
          "thumbnail": "https://i.ytimg.com/vi/nrJTtH3cw0o/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLA3sjgAqRsW5r7_21Kw9wK7IZY9uA",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "This is a special moment in time and for Mother's Day we wanted to give you all this memory. Thank you for sending in your stuck ...",
          "views": 5686812,
          "duration": "4:32",
          "uploaded_at": "1 month ago"
        },
        {
          "id": "16j_6JPr8m4",
          "type": "video",
          "title": "Justin Bieber & Ariana Grande  - Stuck with U (Prom Scenes)",
          "link": "https://www.youtube.com/watch?v=16j_6JPr8m4",
          "thumbnail": "https://i.ytimg.com/vi/16j_6JPr8m4/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLC67E_D9vhcSXoHJBWv7R_jCVsMNA",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": false
          },
          "description": "Watch Official Video: http://stuckwithu.lnk.to/video Shop Stuck with U bundles: https://shop.justinbiebermusic.com Love this.",
          "views": 2694815,
          "duration": "3:44",
          "uploaded_at": "1 month ago"
        },
        {
          "id": "h2jvHynuMjI",
          "type": "video",
          "title": "Ariana Grande, Justin Bieber - Stuck with U (Lyric Video)",
          "link": "https://www.youtube.com/watch?v=h2jvHynuMjI",
          "thumbnail": "https://i.ytimg.com/vi/h2jvHynuMjI/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCsXaHO4hJoJHGi6of8cOL0hM1-_w",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Watch Official Video: http://stuckwithu.lnk.to/video SB Projects along with longtime clients Ariana Grande and Justin Bieber ...",
          "views": 14428651,
          "duration": "3:50",
          "uploaded_at": "1 month ago"
        },
        {
          "id": "lpcOokegspU",
          "type": "video",
          "title": "Justin Bieber - Available (Nature Visual)",
          "link": "https://www.youtube.com/watch?v=lpcOokegspU",
          "thumbnail": "https://i.ytimg.com/vi/lpcOokegspU/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLDhrJNbI2mY0EY6_iABYq2v544IHA",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 4364334,
          "duration": "4:18",
          "uploaded_at": "1 month ago"
        },
        {
          "id": "yKnt8dsFiO0",
          "type": "video",
          "title": "Justin Bieber - Habitual (Nature Visual)",
          "link": "https://www.youtube.com/watch?v=yKnt8dsFiO0",
          "thumbnail": "https://i.ytimg.com/vi/yKnt8dsFiO0/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAyo-xQq8GrYRyBALm8tfKw78Dz0Q",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 5601513,
          "duration": "2:54",
          "uploaded_at": "2 months ago"
        },
        {
          "id": "hUz4yCmwH74",
          "type": "video",
          "title": "Justin Bieber, Summer Walker - Yummy (Summer Walker Remix / CHANGES: The Movement)",
          "link": "https://www.youtube.com/watch?v=hUz4yCmwH74",
          "thumbnail": "https://i.ytimg.com/vi/hUz4yCmwH74/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLB8W1PXzJIILH0Es8G6XJofqJa_vA",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 1432706,
          "duration": "3:49",
          "uploaded_at": "2 months ago"
        },
        {
          "id": "PcbrKsAcwn4",
          "type": "video",
          "title": "Justin Bieber - At Least For Now (CHANGES: The Movement)",
          "link": "https://www.youtube.com/watch?v=PcbrKsAcwn4",
          "thumbnail": "https://i.ytimg.com/vi/PcbrKsAcwn4/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLDrwFn8Pc6ug3Otd97hkeiTb405rw",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 1804163,
          "duration": "2:53",
          "uploaded_at": "2 months ago"
        },
        {
          "id": "AUnypjWNa7Q",
          "type": "video",
          "title": "Justin Bieber - Changes (Nature Visual)",
          "link": "https://www.youtube.com/watch?v=AUnypjWNa7Q",
          "thumbnail": "https://i.ytimg.com/vi/AUnypjWNa7Q/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCVnnKJHrf_nQqhU2yDLL9cG4slrQ",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 4644815,
          "duration": "2:19",
          "uploaded_at": "2 months ago"
        },
        {
          "id": "_uOnmHaDmMQ",
          "type": "video",
          "title": "Justin Bieber - That's What Love Is (CHANGES: The Movement)",
          "link": "https://www.youtube.com/watch?v=_uOnmHaDmMQ",
          "thumbnail": "https://i.ytimg.com/vi/_uOnmHaDmMQ/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAUvSmg2-ddSxg0t8At7A9aeaYd6g",
          "author": {
            "name": "Justin Bieber",
            "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
            "verified": true
          },
          "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
          "views": 3348436,
          "duration": "2:51",
          "uploaded_at": "2 months ago"
        }
      ]
    },
    {
      "id": "3AyMjyHu1bA",
      "type": "video",
      "title": "Justin Bieber - Intentions (Official Video (Short Version)) ft. Quavo",
      "link": "https://www.youtube.com/watch?v=3AyMjyHu1bA",
      "thumbnail": "https://i.ytimg.com/vi/3AyMjyHu1bA/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLB9qnFat3M-TDwnmJMQNdgGPiv0BQ",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Changes: https://justinbieber.lnk.to/Changes Watch Official Video: https://justinbieber.lnk.to/IntentionsVideo Join Justin Bieber in ...",
      "views": 109107197,
      "duration": "3:45",
      "uploaded_at": "4 months ago"
    },
    {
      "id": "ekDJcs4ywXQ",
      "type": "video",
      "title": "Ed Sheeran, Adele, Shawn Mendes, Maroon 5, Taylor Swift, Charlie Puth, Sam Smith 🍑 Top Hits 2020",
      "link": "https://www.youtube.com/watch?v=ekDJcs4ywXQ",
      "thumbnail": "https://i.ytimg.com/vi/ekDJcs4ywXQ/hqdefault_live.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLB53rvbYO8nfzPkSOCJjc1EAEM8Fg",
      "author": {
        "name": "Music Collection 2020",
        "ref": "https://www.youtube.com/channel/UCq8sNODw9D-5qN6o8ougOXA",
        "verified": false
      },
      "description": "Video Ed Sheeran, Adele, Shawn Mendes, Maroon 5, Taylor Swift, Charlie Puth, Sam Smith - Top Hits 2020. The compilation of ...",
      "views": null,
      "duration": "",
      "uploaded_at": "729 watching"
    },
    {
      "id": "DK_0jXPuIr0",
      "type": "video",
      "title": "Justin Bieber - What Do You Mean? (Official Music Video)",
      "link": "https://www.youtube.com/watch?v=DK_0jXPuIr0",
      "thumbnail": "https://i.ytimg.com/vi/DK_0jXPuIr0/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLB9PzjWOE0-KfXEIX6ifFfbswiuow",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "'Purpose' Available Everywhere Now! iTunes: http://smarturl.it/PurposeDlx?IQid=VEVO1113 Stream & Add To Your Spotify ...",
      "views": 2093136555,
      "duration": "4:58",
      "uploaded_at": "4 years ago"
    },
    {
      "id": "pE49WK-oNjU",
      "type": "video",
      "title": "Ariana Grande & Justin Bieber - Stuck with U (Official Video)",
      "link": "https://www.youtube.com/watch?v=pE49WK-oNjU",
      "thumbnail": "https://i.ytimg.com/vi/pE49WK-oNjU/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLD4iHpCs4ty9-sqwcU-8cwXPanP_Q",
      "author": {
        "name": "Ariana Grande",
        "ref": "https://www.youtube.com/channel/UC9CoOnJkIBMdeijd9qYoT_g",
        "verified": true
      },
      "description": "SB Projects along with longtime clients Ariana Grande and Justin Bieber release “Stuck with U” to benefit First Responders ...",
      "views": 63516472,
      "duration": "4:18",
      "uploaded_at": "1 month ago"
    },
    {
      "id": "kffacxfA7G4",
      "type": "video",
      "title": "Justin Bieber - Baby ft. Ludacris (Official Music Video)",
      "link": "https://www.youtube.com/watch?v=kffacxfA7G4",
      "thumbnail": "https://i.ytimg.com/vi/kffacxfA7G4/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLB4F4tsQRIVSf8K9Oqn3cUwxZNx-w",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Music video by Justin Bieber performing Baby feat. Ludacris. #VEVOCertified on April 25, 2010.",
      "views": 2248215458,
      "duration": "3:45",
      "uploaded_at": "10 years ago"
    },
    {
      "id": "9p2wMpVVtXg",
      "type": "video",
      "title": "Justin Bieber - Intentions ft. Quavo (Official Video)",
      "link": "https://www.youtube.com/watch?v=9p2wMpVVtXg",
      "thumbnail": "https://i.ytimg.com/vi/9p2wMpVVtXg/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLD_vLuHCsg5j4GBwaDAvacefd5QLQ",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Changes: https://justinbieber.lnk.to/Changes Join Justin Bieber in supporting Alexandria House's mission to help women and ...",
      "views": 51275223,
      "duration": "6:40",
      "uploaded_at": "4 months ago"
    },
    {
      "id": "fRh_vgS2dFE",
      "type": "video",
      "title": "Justin Bieber - Sorry (PURPOSE : The Movement)",
      "link": "https://www.youtube.com/watch?v=fRh_vgS2dFE",
      "thumbnail": "https://i.ytimg.com/vi/fRh_vgS2dFE/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLC8_TsrvrKIVO5uSffH33hArkC_0w",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "'Purpose' Available Everywhere Now! iTunes: http://smarturl.it/PurposeDlx?IQid=VEVO1113 Stream & Add To Your Spotify ...",
      "views": 3298170207,
      "duration": "3:26",
      "uploaded_at": "4 years ago"
    }
  ],
  "nextpageRef": "/results?search_query=justin+bieber&sp=SBSYAQE%253D",
  "results": 0,
  "filters": [
    {
      "ref": null,
      "name": "Relevance",
      "active": true
    }
  ],
  "currentRef": null,
  "status": true
}
```

## Pagination Example

| Parameter |                                   Description                                   |
| --------- | :-----------------------------------------------------------------------------: |
| q         |                     The search query (must be URL Encoded)                      |
| next      | Use the value from `nextpageRef` from the previous request to get the next page |

```bash
curl --request GET \
	--url 'https://youtube-search-results.p.rapidapi.com/sr?next=%252Fresults%253Fsearch_query%253Djustin%252Bbieber%2526sp%253DSBSYAQE%2525253D&q=justin%252Bbieber' \
	--header 'x-rapidapi-host: youtube-search-results.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXX'
```

### Response

```json
{
  "query": "justin bieber",
  "items": [
    {
      "id": "TiK7QtIHy_Y",
      "type": "video",
      "title": "Justin Bieber - E.T.A. (Nature Visual)",
      "link": "https://www.youtube.com/watch?v=TiK7QtIHy_Y",
      "thumbnail": "https://i.ytimg.com/vi/TiK7QtIHy_Y/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCpPLGO0u1uGx51SmzxLGBOkGn0Pw",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
      "views": 4604123,
      "duration": "2:56",
      "uploaded_at": "2 weeks ago"
    },
    {
      "id": "cAVgKdbDlRY",
      "type": "video",
      "title": "Leaving the Spotlight - Justin Bieber: Seasons",
      "link": "https://www.youtube.com/watch?v=cAVgKdbDlRY",
      "thumbnail": "https://i.ytimg.com/vi/cAVgKdbDlRY/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLDsSaPeCJvAPc26KZd3IBSGiI3cCA",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": false
      },
      "description": "A look back at Justin’s life after cancelling the last leg of his Purpose Tour.\n\nYou choose how you want to watch - get early ...",
      "views": 66383590,
      "duration": "11:11",
      "uploaded_at": "4 months ago"
    },
    {
      "id": "e6OqbtLjxvU",
      "type": "video",
      "title": "Justin Bieber - Never Say Never ft. Jaden Smith (Live)",
      "link": "https://www.youtube.com/watch?v=e6OqbtLjxvU",
      "thumbnail": "https://i.ytimg.com/vi/e6OqbtLjxvU/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAfeAHcDZVKepajVOWJzs9MenPhOg",
      "author": {
        "name": "Anonymous Belieber",
        "ref": "https://www.youtube.com/user/AnonymousBelieberGuy",
        "verified": true
      },
      "description": "From the Movie Justin Bieber: Never Say Never",
      "views": 143561932,
      "duration": "3:44",
      "uploaded_at": "7 years ago"
    },
    {
      "id": "SOI4OF7iIr4",
      "type": "video",
      "title": "Justin Bieber - Somebody To Love Remix ft. Usher (Official Music Video)",
      "link": "https://www.youtube.com/watch?v=SOI4OF7iIr4",
      "thumbnail": "https://i.ytimg.com/vi/SOI4OF7iIr4/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLBuifllZV5DAH4Pl0qQPmj0HRs0kg",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Music video by Justin Bieber performing Somebody To Love Remix. (C) 2010 The Island Def Jam Music Group #VEVOCertified ...",
      "views": 433885445,
      "duration": "3:39",
      "uploaded_at": "9 years ago"
    },
    {
      "id": "BU25ROnZaKk",
      "type": "video",
      "title": "Justin Bieber - Confirmation (CHANGES: The Movement)",
      "link": "https://www.youtube.com/watch?v=BU25ROnZaKk",
      "thumbnail": "https://i.ytimg.com/vi/BU25ROnZaKk/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAjvN5YeEjzwfrRLWCwj8ZQ3Zd-zg",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": true
      },
      "description": "Changes Out Now: https://justinbieber.lnk.to/Changes Follow Justin: http://facebook.com/justinbieber http://twitter.com/justinbieber ...",
      "views": 2898980,
      "duration": "3:02",
      "uploaded_at": "2 months ago"
    },
    {
      "id": "6VF0GEf3S0I",
      "type": "video",
      "title": "SURPRISING PEOPLE WITH JUSTIN BIEBER!!",
      "link": "https://www.youtube.com/watch?v=6VF0GEf3S0I",
      "thumbnail": "https://i.ytimg.com/vi/6VF0GEf3S0I/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAqNN8PJuFSsyQHwcxyWO0A3IzmQA",
      "author": {
        "name": "David Dobrik",
        "ref": "https://www.youtube.com/channel/UCmh5gdwCx6lN7gEC20leNVA",
        "verified": true
      },
      "description": "We surprise some students with Justin Bieber!! Yummy music video: https://www.youtube.com/watch?v=8EJ3zbKTWQ8 Yummy ...",
      "views": 23013218,
      "duration": "4:21",
      "uploaded_at": "5 months ago"
    },
    {
      "id": "SMs0GnYze34",
      "type": "video",
      "title": "DJ Snake ft. Justin Bieber - Let Me Love You [Lyric Video]",
      "link": "https://www.youtube.com/watch?v=SMs0GnYze34",
      "thumbnail": "https://i.ytimg.com/vi/SMs0GnYze34/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLDJ3gsTWKPW6f8TzmxwC-Xr4Z7xlw",
      "author": {
        "name": "Proximity",
        "ref": "https://www.youtube.com/user/PandoraMuslc",
        "verified": true
      },
      "description": "DJ Snake ft. Justin Bieber - Let Me Love You [Lyric Video] SPOTIFY! - http://spoti.fi/Proximity NEW MERCH: ...",
      "views": 813732883,
      "duration": "3:27",
      "uploaded_at": "3 years ago"
    },
    {
      "id": "G-4tJ63X5vo",
      "type": "video",
      "title": "The Wedding: Officially Mr. & Mrs. Bieber - Justin Bieber: Seasons",
      "link": "https://www.youtube.com/watch?v=G-4tJ63X5vo",
      "thumbnail": "https://i.ytimg.com/vi/G-4tJ63X5vo/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLDcp1P7OBHuE5LBIpffM4y4LsI14w",
      "author": {
        "name": "Justin Bieber",
        "ref": "https://www.youtube.com/channel/UCIwFjwMjI0y7PDBVEO9-bkQ",
        "verified": false
      },
      "description": "A look inside Hailey and Justin's intimate wedding ceremony in South Carolina (complete with a few surprise guests). As the ...",
      "views": null,
      "duration": "10:57",
      "uploaded_at": "4 months ago"
    },
    {
      "id": "1Ts9_XOHFuw",
      "type": "video",
      "title": "Justin Bieber Carpool Karaoke 2020",
      "link": "https://www.youtube.com/watch?v=1Ts9_XOHFuw",
      "thumbnail": "https://i.ytimg.com/vi/1Ts9_XOHFuw/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCv7NqsAHyy5y_Mjm9_qIV_BYIARQ",
      "author": {
        "name": "The Late Late Show with James Corden",
        "ref": "https://www.youtube.com/user/TheLateLateShow",
        "verified": true
      },
      "description": "James Corden and Justin Bieber are reunited in the carpool lane where they quickly get into an argument about Tom Cruise ...",
      "views": 19431598,
      "duration": "14:21",
      "uploaded_at": "3 months ago"
    },
    {
      "id": "ukl8R1Vesew",
      "type": "video",
      "title": "Spill Your Guts or Fill Your Guts w/ Justin Bieber",
      "link": "https://www.youtube.com/watch?v=ukl8R1Vesew",
      "thumbnail": "https://i.ytimg.com/vi/ukl8R1Vesew/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLATNlrkiXN9_pGhOXNO0GNw79yhCQ",
      "author": {
        "name": "The Late Late Show with James Corden",
        "ref": "https://www.youtube.com/user/TheLateLateShow",
        "verified": true
      },
      "description": "James and Justin Bieber take turns asking personal questions and are given a choice: answer truthfully or eat whatever food is ...",
      "views": 21223170,
      "duration": "13:23",
      "uploaded_at": "3 months ago"
    }
  ],
  "nextpageRef": "/results?search_query=justin+bieber&sp=SCiYAQE%253D",
  "results": 0,
  "filters": [
    {
      "ref": null,
      "name": "Relevance",
      "active": true
    }
  ],
  "currentRef": "/results?search_query=justin bieber&sp=SBSYAQE%3D",
  "status": true
}
```
