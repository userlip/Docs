# YouTube Information API Requests & Responses

## Request Information of YouTube Video

| Parameter |      Description      |
| --------- | :-------------------: |
| url       | The YouTube Video URL |

```bash
curl --request GET \
	--url 'https://youtube-video-info1.p.rapidapi.com/youtube-info/?url=https%253A%252F%252Fwww.youtube.com%252Fwatch%253Fv%253D9FCRaSwU3W8' \
	--header 'x-rapidapi-host: youtube-video-info1.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXX'
```

### Response

```json
{
    "successfull": true,
    "info": {
        "id": "9FCRaSwU3W8",
        "uploader": "Fortnite",
        "uploader_id": "epicfortnite",
        "uploader_url": "http://www.youtube.com/user/epicfortnite",
        "channel_id": "UClG8odDC8TS6Zpqk9CGVQiQ",
        "channel_url": "http://www.youtube.com/channel/UClG8odDC8TS6Zpqk9CGVQiQ",
        "upload_date": "20200616",
        "license": null,
        "creator": null,
        "title": "Fortnite Chapter 2 - Season 3 | Splashdown Launch Trailer",
        "alt_title": null,
        "thumbnails": [
            {
                "url": "https://i.ytimg.com/vi/9FCRaSwU3W8/hqdefault.jpg?sqp=-oaymwEYCKgBEF5IVfKriqkDCwgBFQAAiEIYAXAB&rs=AOn4CLAzV_L6_6kXOyzge2v9qIDISKwO0g",
                "width": 168,
                "height": 94,
                "resolution": "168x94",
                "id": "0"
            },
            {
                "url": "https://i.ytimg.com/vi/9FCRaSwU3W8/hqdefault.jpg?sqp=-oaymwEYCMQBEG5IVfKriqkDCwgBFQAAiEIYAXAB&rs=AOn4CLBrtXGMELD-_smTOM_WTajra091Jw",
                "width": 196,
                "height": 110,
                "resolution": "196x110",
                "id": "1"
            },
            {
                "url": "https://i.ytimg.com/vi/9FCRaSwU3W8/hqdefault.jpg?sqp=-oaymwEZCPYBEIoBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLBVHdvObwdY-OC0sqIlShMLc9PBLg",
                "width": 246,
                "height": 138,
                "resolution": "246x138",
                "id": "2"
            },
            {
                "url": "https://i.ytimg.com/vi/9FCRaSwU3W8/hqdefault.jpg?sqp=-oaymwEZCNACELwBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLCv-swy_80pGe96179c89kkmWyQQA",
                "width": 336,
                "height": 188,
                "resolution": "336x188",
                "id": "3"
            },
            {
                "url": "https://i.ytimg.com/vi_webp/9FCRaSwU3W8/maxresdefault.webp",
                "width": 1920,
                "height": 1080,
                "resolution": "1920x1080",
                "id": "4"
            }
        ],
        "description": "The Island has flooded, there are new areas to explore, Marauders to take on and... sharks to ride?\n\nSurvive more than just the Storm. Adapt to the new flooded way of life on the Island.\n\nWatch your back! Defend yourself from new Marauders as they crash down onto the island and challenge your survival.\n\nThere's plenty more to discover in Season 3 dive in now!\n\nPlay Fortnite Battle Royale, the completely free 100-player PvP mode. One giant map, A Battle Bus, Last one standing wins. ESRB Rating: Teen with Violence.\n\nInstagram: https://www.instagram.com/fortnite/\nTwitter: https://twitter.com/FortniteGame\nFacebook: https://www.facebook.com/FortniteGame/\n\nLearn More: https://www.epicgames.com/fortnite/en-US/\n\n#FortniteSeason3",
        "categories": [
            "Gaming"
        ],
        "tags": [
            "Fortnite",
            "Epic Games",
            "PC",
            "PS4",
            "Xbox One",
            "Battle Royale",
            "Unreal Tournament",
            "Unreal Engine",
            "Fortnite Battle Royale",
            "Fortnite Creative"
        ],
        "subtitles": [],
        "automatic_captions": [],
        "duration": 92,
        "age_limit": 0,
        "annotations": null,
        "chapters": null,
        "webpage_url": "https://www.youtube.com/watch?v=9FCRaSwU3W8",
        "view_count": 3034855,
        "like_count": 227286,
        "dislike_count": 5894,
        "average_rating": 4.8988934,
        "formats": [
            {
                "format_id": "249",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=249&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=audio%2Fwebm&gir=yes&clen=455929&dur=92.061&lmt=1592322220939279&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6411222&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRAIgbmaUYyC5o4V3Uzm2dotHEQAQJd90tEfyoqBbsbOCkfgCICIxbHSX5kpZ4Knuzodd1YG5Uf-nU4SPF12zr2mcgDRh&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "format_note": "tiny",
                "acodec": "opus",
                "abr": 50,
                "asr": 48000,
                "filesize": 455929,
                "fps": null,
                "height": null,
                "tbr": 47.924,
                "width": null,
                "vcodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "249 - audio only (tiny)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "250",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=250&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=audio%2Fwebm&gir=yes&clen=605312&dur=92.061&lmt=1592322221035897&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6411222&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRQIgc7ZzoALEKGJ3AUFMjOK5U9U-nY4JgENuaPQHhxLurjECIQC9E3mQQiBW1BOvx5LDadFqASUHv1i0GLuJIgv8Oj7ScA%3D%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "format_note": "tiny",
                "acodec": "opus",
                "abr": 70,
                "asr": 48000,
                "filesize": 605312,
                "fps": null,
                "height": null,
                "tbr": 63.395,
                "width": null,
                "vcodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "250 - audio only (tiny)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "251",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=251&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=audio%2Fwebm&gir=yes&clen=1223512&dur=92.061&lmt=1592322222948019&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6411222&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAI24XIMc5gb8EW5NgKZW_BDzDmeTjT7W2rnRq7gnvWStAiEA7AmZbi2l1xdSx3djS_Xrm5wIJ6__Gk7_P_jmeId-B4E%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "format_note": "tiny",
                "acodec": "opus",
                "abr": 160,
                "asr": 48000,
                "filesize": 1223512,
                "fps": null,
                "height": null,
                "tbr": 126.718,
                "width": null,
                "vcodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "251 - audio only (tiny)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "140",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=140&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=audio%2Fmp4&gir=yes&clen=1491133&dur=92.090&lmt=1592326431969312&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6431432&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAOMUdHNTjRcDf3HThQpd67J_ZbxUwPLFzxDWYMoKnD2wAiEAqop5yKp6-OUY4OC2H0JdXaDBM4EcP2sHdym4A2lQhwM%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "m4a",
                "format_note": "tiny",
                "acodec": "mp4a.40.2",
                "abr": 128,
                "container": "m4a_dash",
                "asr": 44100,
                "filesize": 1491133,
                "fps": null,
                "height": null,
                "tbr": 130.381,
                "width": null,
                "vcodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "140 - audio only (tiny)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "278",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=278&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fwebm&gir=yes&clen=933067&dur=92.041&lmt=1592327163230498&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRQIgD9pZxDi7xJ4UOZ9ZjZNAV2bPzDZSD_hZtS5R-TcQFR8CIQCCu7K4tnZGysuP1nkJCMDM_5XvHRerhXgW7pAf7xOxMg%3D%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "height": 144,
                "format_note": "144p",
                "container": "webm",
                "vcodec": "vp9",
                "asr": null,
                "filesize": 933067,
                "fps": 24,
                "tbr": 96.616,
                "width": 256,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "278 - 256x144 (144p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "160",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=160&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=998111&dur=92.041&lmt=1592326527897286&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRAIgOAQIKkM77uNn01GpmW3GQLFO_Y5Jw8PicGLmvGgPLUsCIHpEXVo8HHB7m5AuJ8zXSsEd922IZL8yl0HQuU8H-HX4&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "mp4",
                "height": 144,
                "format_note": "144p",
                "vcodec": "avc1.4d400c",
                "asr": null,
                "filesize": 998111,
                "fps": 24,
                "tbr": 110.693,
                "width": 256,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "160 - 256x144 (144p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "242",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=242&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fwebm&gir=yes&clen=1882120&dur=92.041&lmt=1592327163225427&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAIvAwXXK2xGltvGLa9uqcRSbcQFzxW7jdLn9uLXhElmeAiEAo8U25rEZlMG40lt47Cd7RihPf870xd3QfcdgwdLoHOw%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "height": 240,
                "format_note": "240p",
                "vcodec": "vp9",
                "asr": null,
                "filesize": 1882120,
                "fps": 24,
                "tbr": 202.246,
                "width": 426,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "242 - 426x240 (240p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "133",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=133&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=2157701&dur=92.041&lmt=1592326527899343&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRAIgQ4lckE9XJHeVVPwLcCOYT0TZeY1UmMfEx3aqfOSxJt0CIB6Eep9Pmt6eex9Ea-1NKjoqRDVXoHDyh-SyJNr05WOM&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "mp4",
                "height": 240,
                "format_note": "240p",
                "vcodec": "avc1.4d4015",
                "asr": null,
                "filesize": 2157701,
                "fps": 24,
                "tbr": 244.697,
                "width": 426,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "133 - 426x240 (240p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "243",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=243&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fwebm&gir=yes&clen=3938103&dur=92.041&lmt=1592327163233805&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRAIgan_DgxlClpqq0awDSnhOznQUnH4fotuDvIJi2FlX4hQCICW5lf0y1LtTrNgbVtTFMOZyYhLbcVOpeGSeF1iMqyRa&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "height": 360,
                "format_note": "360p",
                "vcodec": "vp9",
                "asr": null,
                "filesize": 3938103,
                "fps": 24,
                "tbr": 419.953,
                "width": 640,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "243 - 640x360 (360p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "134",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=134&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=4642486&dur=92.041&lmt=1592326527896261&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRQIhAMMHmVl51GFLkneokLqVanSK6m4WFySnVlplqFf9-1o2AiA8UolKfVDGCg_KCdzOzGhM8FveOxUEmtAIaWofGz5pcg%3D%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "mp4",
                "height": 360,
                "format_note": "360p",
                "vcodec": "avc1.4d401e",
                "asr": null,
                "filesize": 4642486,
                "fps": 24,
                "tbr": 632.445,
                "width": 640,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "134 - 640x360 (360p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "244",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=244&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fwebm&gir=yes&clen=7148362&dur=92.041&lmt=1592327163227074&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRQIhANVInyLJ89PoxUUrrp_yX85Tnh1KZjIR11ECrwLHVkZ2AiB-abs91fND_GryJYvMxpPMqy0BXNbceUbFU_0SntUtag%3D%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "height": 480,
                "format_note": "480p",
                "vcodec": "vp9",
                "asr": null,
                "filesize": 7148362,
                "fps": 24,
                "tbr": 770.293,
                "width": 854,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "244 - 854x480 (480p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "135",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=135&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=7261225&dur=92.041&lmt=1592326527905109&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRAIgUnn9rYQz15-m4lGi8LsxHUtVU9p44ExsiKzQDUUqwhgCIHDj5s27ukNQQLZJrnlWokU0uMvz1oZkf25jg3BKxUoT&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "mp4",
                "height": 480,
                "format_note": "480p",
                "vcodec": "avc1.4d401e",
                "asr": null,
                "filesize": 7261225,
                "fps": 24,
                "tbr": 1156.899,
                "width": 854,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "135 - 854x480 (480p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "247",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=247&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fwebm&gir=yes&clen=13924196&dur=92.041&lmt=1592327163220834&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAKlpgHPXDTfTluDKawpCyTqhOl5-QW0a2PAFUT_G6dLnAiEA7gXdngQB9jMjLH79WZZWZ3iyNd1IBfww-S5gh_bkjY0%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "height": 720,
                "format_note": "720p",
                "vcodec": "vp9",
                "asr": null,
                "filesize": 13924196,
                "fps": 24,
                "tbr": 1516.311,
                "width": 1280,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "247 - 1280x720 (720p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "136",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=136&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=11215634&dur=92.041&lmt=1592326527905777&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAKAlvJKUgKGhkEsMcweK1yJ29-vKFgjdq6fywRsCll-qAiEA5j74cCH28cblmmnC9BPPmV9L3aayEtZJzf31P1Nz9wk%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "mp4",
                "height": 720,
                "format_note": "720p",
                "vcodec": "avc1.4d401f",
                "asr": null,
                "filesize": 11215634,
                "fps": 24,
                "tbr": 2130.448,
                "width": 1280,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "136 - 1280x720 (720p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "248",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=248&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fwebm&gir=yes&clen=23912718&dur=92.041&lmt=1592326985090555&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRAIgWvXD1gabw6SFl5Q0SBAHAxqM92L8VkTp5tLU5IIyvnICICCaZqK8DP6w-a7ErFJ-mSY_JhTde08o8CzJngJ2KNau&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "webm",
                "height": 1080,
                "format_note": "1080p",
                "vcodec": "vp9",
                "asr": null,
                "filesize": 23912718,
                "fps": 24,
                "tbr": 2660.382,
                "width": 1920,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "248 - 1920x1080 (1080p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "137",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=137&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C278&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=33817466&dur=92.041&lmt=1592326700778605&mt=1592402499&fvip=2&keepalive=yes&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAN2CBb4mPbA9y0z1KUua825LKCdvFibm6kvxfLyq_D59AiEA0W2LVQSvgw6zG5jyga8fl92BzIHVD1oNcCriO7Ks-sM%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D&ratebypass=yes",
                "player_url": null,
                "ext": "mp4",
                "height": 1080,
                "format_note": "1080p",
                "vcodec": "avc1.640028",
                "asr": null,
                "filesize": 33817466,
                "fps": 24,
                "tbr": 4335.092,
                "width": 1920,
                "acodec": "none",
                "downloader_options": {
                    "http_chunk_size": 10485760
                },
                "format": "137 - 1920x1080 (1080p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "18",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=18&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&gir=yes&clen=7476215&ratebypass=yes&dur=92.090&lmt=1592326465808426&mt=1592402499&fvip=2&c=WEB&txp=6431432&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cgir%2Cclen%2Cratebypass%2Cdur%2Clmt&sig=AOq0QJ8wRgIhAIf9fG056QgOSSm_z8zoAx6B9IGrToxpOw9v4bo9NfRCAiEA3g9qlXQCKi7oL0Tl5Ess2i0ksjE26QhGHhhB87Xp4AM%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D",
                "player_url": null,
                "ext": "mp4",
                "width": 640,
                "height": 360,
                "acodec": "mp4a.40.2",
                "abr": 96,
                "vcodec": "avc1.42001E",
                "asr": 44100,
                "filesize": 7476215,
                "format_note": "360p",
                "fps": 24,
                "tbr": 649.816,
                "format": "18 - 640x360 (360p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            },
            {
                "format_id": "22",
                "url": "https://r2---sn-4g5e6nsz.googlevideo.com/videoplayback?expire=1592424175&ei=jyLqXue1C8vD7gOO1qXoAQ&ip=217.160.43.51&id=o-APZ7sScBGMaGWaXZPauT7Ju7YZFEcgaQNB-aawxSY3Lw&itag=22&source=youtube&requiressl=yes&mh=0j&mm=31%2C29&mn=sn-4g5e6nsz%2Csn-4g5edn7y&ms=au%2Crdu&mv=m&mvi=1&pl=19&initcwndbps=3020000&vprv=1&mime=video%2Fmp4&ratebypass=yes&dur=92.090&lmt=1592326534003084&mt=1592402499&fvip=2&c=WEB&txp=6432432&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cvprv%2Cmime%2Cratebypass%2Cdur%2Clmt&sig=AOq0QJ8wRQIhAMj8pvtdWBVUmAZ4Bpe_1gQ247a5XgeleQSyBhnDZTK3AiAYfcvQenaCxjUAqTcqvUKrqpzFob5fRtqxif06q0LBxQ%3D%3D&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=AG3C_xAwRQIgOVUDLdGz2nTtl9mg8Xubhv3dUg9DGXH5FP4TdeYT-sACIQCh--b8Zkfk0hk9MZDiz5Wsf58FPpL221ywlbrpRiHA2A%3D%3D",
                "player_url": null,
                "ext": "mp4",
                "width": 1280,
                "height": 720,
                "acodec": "mp4a.40.2",
                "abr": 192,
                "vcodec": "avc1.64001F",
                "asr": 44100,
                "filesize": null,
                "format_note": "720p",
                "fps": 24,
                "tbr": 1103.993,
                "format": "22 - 1280x720 (720p)",
                "protocol": "https",
                "http_headers": {
                    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.81 Safari/537.36",
                    "Accept-Charset": "ISO-8859-1,utf-8;q=0.7,*;q=0.7",
                    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
                    "Accept-Encoding": "gzip, deflate",
                    "Accept-Language": "en-us,en;q=0.5"
                }
            }
        ],
        "is_live": null,
        "start_time": null,
        "end_time": null,
        "series": null,
        "season_number": null,
        "episode_number": null,
        "track": null,
        "artist": null,
        "album": null,
        "release_date": null,
        "release_year": null,
        "extractor": "youtube",
        "webpage_url_basename": "watch",
        "extractor_key": "Youtube",
        "playlist": null,
        "playlist_index": null,
        "thumbnail": "https://i.ytimg.com/vi_webp/9FCRaSwU3W8/maxresdefault.webp",
        "display_id": "9FCRaSwU3W8",
        "format": "137 - 1920x1080 (1080p)+140 - audio only (tiny)",
        "format_id": "137+140",
        "width": 1920,
        "height": 1080,
        "resolution": null,
        "fps": 24,
        "vcodec": "avc1.640028",
        "vbr": null,
        "stretched_ratio": null,
        "acodec": "mp4a.40.2",
        "abr": 128,
        "ext": "mp4",
        "fulltitle": "Fortnite Chapter 2 - Season 3 | Splashdown Launch Trailer",
        "_filename": ""
    },
    "used_proxy": true
}
```