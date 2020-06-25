# Amazon Search API Requests & Responses

## Search for Products

| Parameter |                                            Description                                            |
| --------- | :-----------------------------------------------------------------------------------------------: |
| search    |                                The searchterm you are looking for                                 |
| page      |                             On what page you want to search (1 to 10)                             |
| region    | In what region do you want to search - Use Amazon domain endings (com, de, it, es, fr, co.uk, jp) |

```bash
curl --request GET \
	--url 'https://amazon-product-search.p.rapidapi.com/amazon-search/search.php?search=bluetooth%252520headset&page=1&region=com' \
	--header 'x-rapidapi-host: amazon-product-search.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
  "totalProducts": "2584",
  "category": "all",
  "result": [
    {
      "asin": "B085416JSF",
      "discounted": false,
      "price": "16.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 24,
      "rating": 4.2,
      "score": "100.80",
      "sponsored": true,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Earpiece RIYO Wireless Handsfree Headset HD Stereo Ultralight 22Hrs Talktime Driving Headset with Noise Cancelling Mic for iPhone Samsung Android Trucker Driver",
      "thumbnail": "https://m.media-amazon.com/images/I/71VSZOyXPjL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=pa_sp_atf_aps_sr_pg1_1?ie=UTF8&adId=A0606764AQI6QP539D9E&url=%2FAuriculares-inal%25C3%25A1mbricos-ultraligeros-conducci%25C3%25B3n-cancelaci%25C3%25B3n%2Fdp%2FB085416JSF%2Fref%3Dsr_1_1_sspa%3Fdchild%3D1%26keywords%3DBluetooth%2BHeadset%26qid%3D1592570795%26sr%3D8-1-spons%26psc%3D1&qualifier=1592570795&id=6987151159169974&widgetName=sp_atf"
    },
    {
      "asin": "B081Q5RCMV",
      "discounted": false,
      "price": "49.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 1132,
      "rating": 4.5,
      "score": "5094.00",
      "sponsored": true,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "TaoTronics Trucker Bluetooth Headset with Microphone, Wireless Cell Phone Headset Noise Cancelling Mic, On Ear Bluetooth Headphones Bluetooth 5.0 34H for Home Office Online Class PC Call Center Skype",
      "thumbnail": "https://m.media-amazon.com/images/I/51f69IpWGhL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=pa_sp_atf_aps_sr_pg1_2?ie=UTF8&adId=A07666421XCKDE8R43KX7&url=%2FTaoTronics-Bluetooth-Microphone-Cancelling-Headphones%2Fdp%2FB081Q5RCMV%2Fref%3Dsr_1_2_sspa%3Fdchild%3D1%26keywords%3DBluetooth%2BHeadset%26qid%3D1592570795%26sr%3D8-2-spons%26psc%3D1&qualifier=1592570795&id=6987151159169974&widgetName=sp_atf"
    },
    {
      "asin": "B07FMJ29WH",
      "discounted": false,
      "price": "39.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 3169,
      "rating": 3.9,
      "score": "12359.10",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Jabra Talk 25 Bluetooth Headset for High Definition Hands-Free Calls with Clear Conversations and Streaming Multimedia",
      "thumbnail": "https://m.media-amazon.com/images/I/51d2qrFtYHL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Jabra-Definition-Hands-Free-Conversations-Multimedia/dp/B07FMJ29WH/ref=sr_1_3?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-3"
    },
    {
      "asin": "B07HBTYBMB",
      "discounted": false,
      "price": "39.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 3265,
      "rating": 4.4,
      "score": "14366.00",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headset, Wireless Bluetooth Earpiece V4.1 8-10 Hours Talktime Stereo Noise Cancelling Mic, Compatible for iPhone Android Cell Phones Driving/Business/Office (Black)",
      "thumbnail": "https://m.media-amazon.com/images/I/61syidOm4vL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Bluetooth-Wireless-Earpiece-Cancelling-Compatible/dp/B07HBTYBMB/ref=sr_1_4?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-4"
    },
    {
      "asin": "B01H2RBQUG",
      "discounted": false,
      "price": "119.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 3722,
      "rating": 4,
      "score": "14888.00",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Plantronics Voyager 5200 - Bluetooth Headset, Silver",
      "thumbnail": "https://m.media-amazon.com/images/I/61u5yynCsyL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Plantronics-Voyager-Wireless-Bluetooth-Headset/dp/B01H2RBQUG/ref=sr_1_5?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-5"
    },
    {
      "asin": "B07WDRPXLB",
      "discounted": true,
      "price": "69.99",
      "beforeDiscount": "99.99",
      "savings": "30.00",
      "reviews": 229,
      "rating": 4.1,
      "score": "938.90",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "LG Tone Style HBS-SL5 Bluetooth Wireless Stereo Neckband Earbuds Tuned by Meridian Audio",
      "thumbnail": "https://m.media-amazon.com/images/I/71lj3EH9f1L._AC_UY218_.jpg",
      "url": "https://www.amazon.com/LG-HBS-SL5-Bluetooth-Wireless-Neckband/dp/B07WDRPXLB/ref=sr_1_7?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-7"
    },
    {
      "asin": "B0811SQ8KM",
      "discounted": false,
      "price": "36.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 536,
      "rating": 4.2,
      "score": "2251.20",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headset 5.0 with CVC8.0 Dual Mic Noise Cancelling Bluetooth Earpiece 16Hrs Talktime Wireless Headset Hands-Free Earphone for Truck Driver iPhone Android Cell Phones",
      "thumbnail": "https://m.media-amazon.com/images/I/61Wd0v-93kL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Bluetooth-Cancelling-Earpiece-Talktime-Hands-Free/dp/B0811SQ8KM/ref=sr_1_8?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-8"
    },
    {
      "asin": "B07R5XVZ53",
      "discounted": false,
      "price": "20.56",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 1757,
      "rating": 4.5,
      "score": "7906.50",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "LETSCOM Bluetooth Headphones IPX7 Waterproof, Wireless Sport Earphones, HiFi Bass Stereo Sweatproof Earbuds w/Mic, Noise Cancelling Headset for Workout, Running, Gym, 8 Hours Play Time, Black",
      "thumbnail": "https://m.media-amazon.com/images/I/618439xhCIL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Bluetooth-Headphones-LETSCOM-Waterproof-Cancelling/dp/B07R5XVZ53/ref=sr_1_9?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-9"
    },
    {
      "asin": "B083V273S9",
      "discounted": false,
      "price": "43.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 214,
      "rating": 4.1,
      "score": "877.40",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headset, Willful BT 5.0 Wireless Headset with Microphone (Flexible Noise Cancelling Mic) Mute Button 30Hrs Clear Talk Time Pro for Car Truck Driver Business Home Office Cell Phones PC",
      "thumbnail": "https://m.media-amazon.com/images/I/51FDvBODh1L._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Bluetooth-Willful-Wireless-Microphone-Cancelling/dp/B083V273S9/ref=sr_1_10?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-10"
    },
    {
      "asin": "B086X3LB4C",
      "discounted": false,
      "price": "26.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 72,
      "rating": 4.6,
      "score": "331.20",
      "sponsored": true,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Wireless Earbuds, Bluetooth 5.0 Earbuds IPX7 Waterproof in Ear True Wireless Stereo Headphones,40H Cycle Playtime, Bluetooth Earbuds Sport Headsets Built-in Mic for Work/Running/Travel/Gym",
      "thumbnail": "https://m.media-amazon.com/images/I/51nM4rMnHAL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=pa_sp_mtf_aps_sr_pg1_1?ie=UTF8&adId=A01337571D9CV5UN1Q1Y2&url=%2FWireless-Bluetooth-Waterproof-Headphones-Playtime%2Fdp%2FB086X3LB4C%2Fref%3Dsr_1_11_sspa%3Fdchild%3D1%26keywords%3DBluetooth%2BHeadset%26qid%3D1592570795%26sr%3D8-11-spons%26psc%3D1&qualifier=1592570795&id=6987151159169974&widgetName=sp_mtf"
    },
    {
      "asin": "B07FQC92FZ",
      "discounted": false,
      "price": "45.89",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 985,
      "rating": 3.7,
      "score": "3644.50",
      "sponsored": true,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headphones with Microphone, YAMAY Bluetooth Headset Wireless Headphones on Ear with Noise Cancelling Boom Mic Mute Key Clear Sound, Foldable Headset for Cell Phones PC Tablet Home Office",
      "thumbnail": "https://m.media-amazon.com/images/I/41srzfxYpXL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=pa_sp_mtf_aps_sr_pg1_2?ie=UTF8&adId=A0304073D1QXU0PPZEMO&url=%2FBluetooth-Headphones-YAMAY-Wireless-Cancelling%2Fdp%2FB07FQC92FZ%2Fref%3Dsr_1_12_sspa%3Fdchild%3D1%26keywords%3DBluetooth%2BHeadset%26qid%3D1592570795%26sr%3D8-12-spons%26psc%3D1&qualifier=1592570795&id=6987151159169974&widgetName=sp_mtf"
    },
    {
      "asin": "B01M3MMFA5",
      "discounted": true,
      "price": "129.00",
      "beforeDiscount": "149.99",
      "savings": "20.99",
      "reviews": 3226,
      "rating": 4.5,
      "score": "14517.00",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "BlueParrott B450-XT Noise Cancelling Bluetooth Headset – Industry Leading Sound with Long Wireless Range, Extreme Comfort and Up to 24 Hours of Talk Time",
      "thumbnail": "https://m.media-amazon.com/images/I/71y0HJNZFPL._AC_UL320_.jpg",
      "url": "https://www.amazon.com/BlueParrott-B450-XT-Canceling-Bluetooth-Headset/dp/B01M3MMFA5/ref=sxin_11_sk-bs-v2-na_5003abb5e9aa411cd56263e9880e35c7b2687e62?cv_ct_cx=Bluetooth+Headset&dchild=1&keywords=Bluetooth+Headset&pd_rd_i=B01M3MMFA5&pd_rd_r=4d3b0149-da86-436a-b6ae-1b35c298bdbd&pd_rd_w=AB0AV&pd_rd_wg=RQ2qV&pf_rd_p=b645b828-1778-4255-896f-d398a7e9c026&pf_rd_r=RN9HMD4TGR3V0038WWYN&qid=1592570795&sr=1-2-db39674d-a3a5-4ccf-88e3-f4fdf0022c7a"
    },
    {
      "asin": "B07T352HQC",
      "discounted": false,
      "price": "34.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 2224,
      "rating": 4.4,
      "score": "9785.60",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headset, FimiTech Wireless Earpiece V5.0 Ultralight Hands Free Business Earphone with Mic for Business/Office/Driving",
      "thumbnail": "https://m.media-amazon.com/images/I/61YzlcRqJnL._AC_UL320_.jpg",
      "url": "https://www.amazon.com/Bluetooth-FimiTech-Wireless-Earpiece-Ultralight/dp/B07T352HQC/ref=sxin_9_lp-trr-1-na_6f606104f630cc970966503f1edc835a0044dce8?cv_ct_cx=Bluetooth+Headset&dchild=1&keywords=Bluetooth+Headset&pd_rd_i=B07T352HQC&pd_rd_r=4d3b0149-da86-436a-b6ae-1b35c298bdbd&pd_rd_w=czjNx&pd_rd_wg=RQ2qV&pf_rd_p=143c53c7-070c-404f-9dbf-1087199a702d&pf_rd_r=RN9HMD4TGR3V0038WWYN&qid=1592570795&sr=1-4-e2650614-163c-483e-9cc8-c2098b28068f"
    },
    {
      "asin": "B07ZLTPVX2",
      "discounted": false,
      "price": "49.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 218,
      "rating": 3.8,
      "score": "828.40",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Mpow HC5 V5.0 Bluetooth Headset with Microphone, CVC8.0 Noise Canceling, 22+Hrs Talk Time, Soft Leatherette Ear Pad, Wireless Business Office Headset for Calling, Music (Wired Optional)",
      "thumbnail": "https://m.media-amazon.com/images/I/61amFRisTsL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Mpow-Bluetooth-Microphone-Canceling-Leatherette/dp/B07ZLTPVX2/ref=sr_1_15?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-15"
    },
    {
      "asin": "B00DQ5NU76",
      "discounted": true,
      "price": "74.72",
      "beforeDiscount": "99.99",
      "savings": "25.27",
      "reviews": 12544,
      "rating": 4.2,
      "score": "52684.80",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Plantronics Voyager Legend Wireless Bluetooth Headset - Compatible with iPhone, Android, and Other Leading Smartphones - Black- Frustration Free Packaging",
      "thumbnail": "https://m.media-amazon.com/images/I/51sc6e37-DL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Plantronics-Voyager-Wireless-Bluetooth-Headset/dp/B00DQ5NU76/ref=sr_1_17?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-17"
    },
    {
      "asin": "B07L4THGR1",
      "discounted": false,
      "price": "41.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 523,
      "rating": 4,
      "score": "2092.00",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Trucker Bluetooth Headset,Willful Wireless Headset with Microphone,Charging Station,Noise Cancelling Hands Free Phone Headset for Truck Driver Call Center Office PC Skype",
      "thumbnail": "https://m.media-amazon.com/images/I/51LiYk4U4vL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Bluetooth-Willful-Wireless-Microphone-Cancelling/dp/B07L4THGR1/ref=sr_1_18?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-18"
    },
    {
      "asin": "B07Z393DWN",
      "discounted": true,
      "price": "17.99",
      "beforeDiscount": "29.99",
      "savings": "12.00",
      "reviews": 1205,
      "rating": 4.4,
      "score": "5302.00",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headset, Kendir V5.0 Wireless Headphone Cell Phone Earpiece 8 Hrs Talking Time with Mic, Volume Control, Handsfree Earbud for iPhone, Android, Smartphone (One Piece, Black)",
      "thumbnail": "https://m.media-amazon.com/images/I/61y3Vagmk1L._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Bluetooth-Wireless-Headphone-Handsfree-Smartphone/dp/B07Z393DWN/ref=sr_1_19?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-19"
    },
    {
      "asin": "B082TXCCV7",
      "discounted": false,
      "price": "24.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 259,
      "rating": 4.3,
      "score": "1113.70",
      "sponsored": false,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Bluetooth Headset, HonShoop Wireless Bluetooth Earpiece V5.0 Hands-Free Earphones with Stereo Mic, Compatible iPhone Android Cell Phones Driving/Business/Office (Red) (Red)",
      "thumbnail": "https://m.media-amazon.com/images/I/511QPR+6iSL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/Auriculares-auriculares-inal%C3%A1mbricos-compatible-Conducci%C3%B3n/dp/B082TXCCV7/ref=sr_1_20?dchild=1&keywords=Bluetooth+Headset&qid=1592570795&sr=8-20"
    },
    {
      "asin": "B088D595C7",
      "discounted": true,
      "price": "36.99",
      "beforeDiscount": "42.99",
      "savings": "6.00",
      "reviews": 87,
      "rating": 4.8,
      "score": "417.60",
      "sponsored": true,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "Wireless Earbuds, ssouwao Bluetooth 5.0 Headphones, IPX7 Waterproof Bluetooth Earphones, TWS Stereo in-Ear Earphones, Sports Headsets with Mic, Touch Control, Noise Cancelling, Mini Charging Case",
      "thumbnail": "https://m.media-amazon.com/images/I/51fGz+aA7DL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=pa_sp_btf_aps_sr_pg1_1?ie=UTF8&adId=A04392511OFZTAPVL8CEW&url=%2Fssouwao-Bluetooth-Headphones-Waterproof-Cancelling%2Fdp%2FB088D595C7%2Fref%3Dsr_1_21_sspa%3Fdchild%3D1%26keywords%3DBluetooth%2BHeadset%26qid%3D1592570795%26sr%3D8-21-spons%26psc%3D1&qualifier=1592570795&id=6987151159169974&widgetName=sp_btf"
    },
    {
      "asin": "B07X37JJ7G",
      "discounted": false,
      "price": "22.99",
      "beforeDiscount": 0,
      "savings": 0,
      "reviews": 250,
      "rating": 4.3,
      "score": "1075.00",
      "sponsored": true,
      "amazonChoice": false,
      "bestSeller": false,
      "amazonPrime": false,
      "title": "HonShoop Bluetooth Headset Handsfree Wireless Bluetooth Earpiece V5.0 in Ear with Stereo Mic for Compatible iPhone Android Cell Phones Business/Workout/Driving, Great Gift for Father's Day",
      "thumbnail": "https://m.media-amazon.com/images/I/51959526JCL._AC_UY218_.jpg",
      "url": "https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=pa_sp_btf_aps_sr_pg1_2?ie=UTF8&adId=A0988190I0Z5R1QQNDKF&url=%2FBluetooth-Handsfree-Wireless-Earpiece-Reduction%2Fdp%2FB07X37JJ7G%2Fref%3Dsr_1_22_sspa%3Fdchild%3D1%26keywords%3DBluetooth%2BHeadset%26qid%3D1592570795%26sr%3D8-22-spons%26psc%3D1&qualifier=1592570795&id=6987151159169974&widgetName=sp_btf"
    }
  ]
}
```

## Product Reviews

| Parameter |                                            Description                                            |
| --------- | :-----------------------------------------------------------------------------------------------: |
| asin      |                                      The ASIN of the Product                                      |
| region    | In what region do you want to search - Use Amazon domain endings (com, de, it, es, fr, co.uk, jp) |

```bash
curl --request GET \
	--url 'https://amazon-product-search.p.rapidapi.com/amazon-search/reviews.php?asin=B081Q5RCMV&region=com' \
	--header 'x-rapidapi-host: amazon-product-search.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
    "result": [
        {
            "id": "R9XGT3QT55SBS",
            "review_data": "Reviewed in the United States on March 9, 2020",
            "name": "Patrick H",
            "rating": 5,
            "title": "Super comfortable and easy connect and function",
            "review": " The first thing that stands out is the comfort factor, even after hours of use. It fits snugly but not so much that it's irritating. The sound is crisp and clear, and the connection is strong with no stutter or missed communication. I'm happy to have this as part of my office gear and willing to give it a strong recommendation."
        },
        {
            "id": "R1VBWTYLY1TPWK",
            "review_data": "Reviewed in the United States on January 10, 2020",
            "name": "Tennessee ",
            "rating": 5,
            "title": "Love it",
            "review": "I'm a truck driver and over the years have had several different headsets and these are the most comfortable and best sounding of all the ones I've had before. The sound quality is stellar the noise canceling is top notch my wife says she can actually hear me over my truck engine and road noise. I would recommend these to anyone looking for a good quality headset at a very reasonable price. Well done"
        },
        {
            "id": "RZCRHNNBL05IV",
            "review_data": "Reviewed in the United States on March 10, 2020",
            "name": "YonitO",
            "rating": 5,
            "title": "Práctico y barato.",
            "review": "La batería dura bastante y es muy práctico. A veces no escucho con nitidez la voz de mi interlocutor pero eso puede ser por la parte de ellos."
        },
        {
            "id": "R3INL99CKLW52N",
            "review_data": "Reviewed in the United States on February 8, 2020",
            "name": "Dirk Da Silva",
            "rating": 5,
            "title": "Don’t let the price fool you",
            "review": "This is my first time trying a product from taotronics and what a surprise. I went in thinking it would be a gamble buying a headset for such a low price and the quality would suffer because of it but it’s the furthest thing from the truth.I went through two other headset around the $35-40 range and both had their issues. Mainly comfort and build quality. The taotronic headset is superior in every way with the softest ear piece and best build quality. I was truly surprised how nice it felt when I tried it for the first time. The controls are nice also. The other headset had a weird setting where you need to hold the buttons to adjust the volume and that really irked me. This one you can adjust it by pressing once and the hold function skips to the next or previous track. Another nice feature is you can use it while it’s charging.I have to see how the battery holds up the longer I use it but so far so good. 5 stars. A good first impression will keep me as a repeat customer."
        },
        {
            "id": "R3EFRE7S03GTZB",
            "review_data": "Reviewed in the United States on April 13, 2020",
            "name": "elsuchnsuch",
            "rating": 5,
            "title": "Fed up with most autos' hands-free mics - trucker's style headset can fix this",
            "review": "4.5 Stars IF I COULD!I am really really glad I made this purchase!Pros:excellent sound quality, easy controls, build quality, dedicated mute button, good codecsCons:noise-cancelling artifacts; want higher max volumeHow I use this:Primary-Use- pair media audio with auto stereo - phone and contacts are NOT paired- pair headset to android phone for calls, contacts, voice commands - media audio is NOT paired with headset (in the device settings on the phone)Secondary-Use- manually toggle media audio ON (on android PHONE in the device settings), when away from my auto to listen to podcasts/audio books- when getting back into the auto, manually toggle media audio OFF (on the android PHONE settings)I use the Android Auto app (run ONLY on my phone, NOT connected to an Android Auto compatible car system) to make safer-use of my phone while driving, mostly using Google Maps, and audio player apps (mostly spoken word media players).Sending SMS messages via voice command is highly desirable.I got tired of people telling me they could not understand me or that here was too much background noise when using the factory microphones in two new-ish vehicles (2017 Honda and 2019 Toyota).I have a lengthy commute, and recovering some of that travel time is important to me. Then the universe asked, haven't truckers been using headsets with noise cancelling microphones for years?I had some experience with a stereo headset w/boom mic (issued by my employer) for conference calls, so that was tried first.It solved the problem for my callers, but the stereo ear cups were too isolating, it didn't feel safe.I could not come up with a comfortable and safe way to wear the headset when I wasn't on a call, I needed a mono headset.The quality of this stereo headset did set a very high bar for audio quality, and so I was on a quest to find an affordable mono headset.This TaoTronics model was the 3rd mono headset I tried.I called an answering machine service so I could leave messages under different road noise conditions, to evaluate the call quality of different headsets by direct comparison.This TaoTronics mono headset is nearly identical to the more expensive model, supplied by my employer.You said 4.5 stars, why not 5 ?Noise cancelling artifacts are canbe noticeable.Occasionally, when I'm speaking into the microphone, I feel and hear a low frequency vibration in the ear cup that comes and goes.It was annoying at first, but I've become accustomed to it.I hope that this is fixed in the future by a firmware upgrade.I'm only taking 1/2 a star off for this.(That more expensive headset provided by my employer, it does the same thing, in the same way.They may even use the same chipsets...)Besides the vibration/artifact, the only other thing I wish for: little be higher max volume.If this were a stereo headset, with 2 earcups, at the present volume, it would be all I could ask for, but since there is only 1, it leaves me a bit, wanting.Is my primary-use setup satisfying/fool-proof?Like most tech solutions, it is not fool-proof.There are occasions when BT pairing with the phone will be less than perfect.When this happens, I restart the phone.The phone will dual pair best when, the auto media is allowed to pair first, followed by the headset.The easiest way to accomplish this is to keep the headset off, while the auto pairing is done, then power-up the headset.This is easily done, by long-pressing the multi-function button to cycle the headset on/off.How do I perform voice searches while in the auto?When the headset is connected to the phone, pressing the multi-function button for a short time, will activate the Google Assistant and you can perform voice commands.(This bypasses the limitations of your auto's voice command system built into the vehicle.)What phone do I use:Pixel 3A XL"
        },
        {
            "id": "R1EHSQLQV5VLLQ",
            "review_data": "Reviewed in the United States on April 21, 2020",
            "name": "Steven Kisor",
            "rating": 5,
            "title": "Great Battery Life, from an actual Trucker",
            "review": "I drive a truck every day.I have tried multiple bluetooth headsets, with none able to overcome the truck's noise.Then I ordered this Taotronics headset, and I'm very happy with it!First of all, the battery life is fantastic!I've used it 4-5 hours/day for a week, and only charged once.And I use it at a rather high volume.Pairing is quick and easy with my Samsung Galaxy S9 Plus.It stays connected, versus other headsets.And it shows the battery life remaining in the bluetooth settings on the phone.Thats nice, although I wish it showed on the notification line of the phone, like iPhones do, but thats an Android/iOS debacle, not the headsets fault.Sound quality is good for voice, or podcasts, or talk radio, but not for music.Listening to music is very much like listening to music on AM radio, there's no fidelity.But that may be a result of the noise cancelling.I have asked many people what the sound quality from me is like, and most people say it sounds like I'm sitting still, instead of 65 mph truck.And thats a really good thing.The only negative after a couple weeks of use, is that the VERY small charge indicator light is almost hidden down inside the little hole.You really have to search for the tiny red LED inside headset to see if its charging.It's not a big deal, as the headset lasts for a long time on a charge.I've not had it go dead yet.I charge it on Monday mornings, and it lasts the whole week.Conclusion:Buy it!"
        },
        {
            "id": "RZU6O4NK81Z7W",
            "review_data": "Reviewed in the United States on May 4, 2020",
            "name": "Mark D. Schnittman",
            "rating": 5,
            "title": "Great Bluetooth headset",
            "review": "I am a professor, and have been forced to teach remotely for the past 2 months as a result of COVID-19. This is the second Bluetooth headset that I've purchased. The first one, although well made and worked well, just wasn't comfortable to wear for 5 hours continuously. I came to the conclusion that the ear pad was too small in diameter, concentrating the pressure in too small of an area on my ear. My ear would begin to bother me almost immediately after putting them one, but I dealt with it, not wanting to buy another pair unless necessary. Well, I couldn't take it anymore and bought these instead. These are perfect, and were well worth the money paid. They seem to be well made, the materials are good quality, the sound quality is excellent with ample volume, the noise cancelling feature works well, and most importantly for me -- they are very comfortable. The ear pad is thicker and larger in diameter, sitting on the ear, and can be worn for long periods of time without fatigue. I can't comment on the battery life, as I only received these 2 days ago, but so far, so good. Pairing was smooth and without any trouble, and they can be paired with up to 2 devices simultaneously. Highly recommended."
        },
        {
            "id": "R3JW60O3NC20Q3",
            "review_data": "Reviewed in the United States on March 9, 2020",
            "name": "Jeremy Wong",
            "rating": 5,
            "title": "🎧🎧🎧🎧 out of five",
            "review": "I bought this headset for use on the couch. I keep my desktop PC next to my television so I can play PC games on the big screen, and I wanted to use this with Discord.PRO: Excellent quality of build. It's really lightweight and cozy and it actually feels quite sturdy. It feels like a $60 headset, and it only costs like $30.PRO: Easy to pair - it's linked with bluetooth and it's easy to use to pair with a desktop or phone.CON: The sound quality is butts. I was trying to get it to sound better but it just... didn't. Discord calls were VERY sensitive so every little shudder or judder was audible, and the audio honestly sounded like AM radio. Just... did not like it.OVERALL: If you're using this for phone calls, like if you work from home in a call center, this is the perfect item. I don't know if I recommend it as a gaming headset of any kind."
        },
        {
            "id": "R2J260L5637TP3",
            "review_data": "Reviewed in the United States on June 2, 2020",
            "name": "H. Hansen",
            "rating": 5,
            "title": "TaoTronics headset w/mic improves audio for my virtual classes and meetings",
            "review": "When I had to begin teaching classes online from my home office, I was using a webcam with built-in microphone that I had not had a chance to test in the virtual classroom. Students kept telling me they could not hear me well during class, and even when I adjusted volume settings to the maximum, the audio quality was never good enough. I tried to stay as close to the webcam mic as possible and not turn my head while teaching, and I also added much more text to my slides than I usually would as a way to compensate for what the students may not have been able to hear. The poor performance of my webcam microphone made every virtual class session even more difficult for me and my students!During a virtual meeting with colleagues I saw that many other faculty members were using headsets with microphones, and I could generally hear everyone quite well. I decided to research headsets, which led me to the TaoTronics bluetooth headset, marketed for use by truckers. I didn't start out with an idea of exactly what I was looking for, but as I read various product descriptions and customer reviews, I was optimistic that this device would provide the audio quality upgrade I needed to deliver online classes and participate in virtual meetings.My headset arrived on Memorial Day, just two days after I placed the order, and after giving it a couple of hours to charge, I put it on, powered it up, and paired it with my computer. Quick and easy! I asked my son to help me test it in virtual meetings using both WebEx and Zoom, and it worked as expected--good quality sound all-around through the TaoTronics mic and the headphone. I was especially pleased to have a wireless connection that did not require me to speak extra-loud and keep my face close to the camera.I have been using the TaoTronics headset for about a week now, and I am happy to report that it continues to perform well. Though I don't have to wear it for longer than an hour, I think it would remain comfortable for more extended wear. It is simple to set up and use, and I no longer worry about whether students and colleagues can hear me. If I happen to look like someone who works in a customer care call center, well, I can live with that, since this headset gets the job done! I wish I had made the purchase two months ago."
        },
        {
            "id": "R3547PGKV2MP3R",
            "review_data": "Reviewed in the United States on March 14, 2020",
            "name": "Norkie",
            "rating": 5,
            "title": "Finally a hands-free that works.",
            "review": "I've tried a couple of other styles of hands-free bluetooth headsets and been pretty disappointed. One was a Plantronics brand and was simply too quiet for me to hear, and the person on the other end couldn't hear me. I'd have to cup my hand around the mic for them to hear me and there would have to be no ambient noise for me to hear them. I tried a random chinese thathad a small boom and a larger body, presumably more battery so more powerful, but had the same issues. I started looking at the full size \"trucker style\" that go over the ear and have a great big boom out in front of my mouth, I ended up settling on this one. I drive an older car with loud tires and no real sound isolation in the cabin, so ambient noise is a big problem. This one performed great! My grandma can hear me just fine (no small feat, her cordless phone is garbage but she won't replace it) and I could hear her just fine. This is my first foray into the world of noise cancelling and I can tell that, whichever ear it is on, I can't hear the roar of my tires. it does what I wanted this to do and so far does well. I haven't used it enough to run through the battery, so I can't speak to battery life. So far, it's a keeper!"
        },
        {
            "id": "R7QN9Q0DP6UU2",
            "review_data": "Reviewed in the United States on March 7, 2020",
            "name": "JoeE",
            "rating": 5,
            "title": "I Finally Have a Headset I Love",
            "review": "In-ear bluetooth headsets never stay on me. The big DJ-style ones feel silly. THIS headset is great, though! It's quick to connect and pairing is a breeze. The volume buttons are sensibly placed and I don't have to take the headset off to look at the buttons in order to remember where they are or what they do.The volume is good, too. I DID have an odd quirk where my laptop reduced the input audio to 50%, so my first few tests had issues with volume, but that was 100% the computer, not the headset. Once I was able to reset the input volume, everyone could hear me very easily. Several people likened the audio to the same sound from my much larger headsets that cost three and four times as much, so that tells me that this one is a good buy."
        },
        {
            "id": "R2OC7R74YEG4VL",
            "review_data": "Reviewed in the United States on March 21, 2020",
            "name": "Maritza",
            "rating": 5,
            "title": "Great quality",
            "review": "Great product long lasting very clear sound perfect for wat i need.. connects to phone through bluetooth great for work from home and office use"
        },
        {
            "id": "RERKQIZ7BGGEQ",
            "review_data": "Reviewed in the United States on May 9, 2020",
            "name": "House of Jensens",
            "rating": 5,
            "title": "Awesome driving headset!",
            "review": "Awesome driving headset!This thing checks all the boxes for me:-Boom mic with noise cancellation.-Modern Bluetooth chip for extremely fast connection to phone and long range for BT.-Long battery life.I drive a class B paper shredding truck and it is very noisy when driving or when standing in the same parking lot when it's shredding. Being able to communicate with my company or customers is important and I can honestly say when I'm on this headset people don't even know I'm driving or near a truck! They think I'm at home in a closet it is so quiet from my end. Amazing! That means I don't have to raise my voice and can just talk normally even with a lot of background going on.I also connect and disconnect frequently because I don't want to wear it inside the businesses I shred for, and having a fast connect speed is important to me. Works great!I only have to change it once a week at my usage, if you talk all day you'll have to charge it every day. But it has great battery life, and doesn't take long to charge.I cannot compare it to a Blue Parrot(never bought one) but I have used or owned many other headsets in 14 years driving and this is the best of them. I can't imagine how even a blue parrot would be better, this headset is worth far more than I paid for it!"
        },
        {
            "id": "RJP0T120U6LAY",
            "review_data": "Reviewed in the United States on April 27, 2020",
            "name": "Tim",
            "rating": 5,
            "title": "Best off brand headset I have used",
            "review": "TL;DR: great headset for the money.I'm not a truck driver, but I have bought a cheap generic headset before and it was not loud enough to overcome road noise in my car.This one is definitely loud enough and covers your ear to physicaly block out noise. What better is that I have been around an accelerating semi while on the phone and the person I was talking to was unable to hear the truck.No complaints about this, Ihave not used it in the heat enough to know how sweaty my ear will get. But with a design like this any brand can cause that.One final note, I recently returned a different headset due to poor sound quality on both end of the call."
        },
        {
            "id": "R2P13RJYFDP6XV",
            "review_data": "Reviewed in the United States on April 21, 2020",
            "name": "Patrick J Dunn",
            "rating": 5,
            "title": "Great for home office use",
            "review": "I work from home (even before the pandemic) and spend quite a lot of time on the phone - but I do not have a landline; only a mobile phone.I have tried several different bluetooth headsets and have been mostly disappointed.I've been very pleased with this TaoTronics trucker headset.They seem to be well built.The ear cushion is larger than others I've tried and much more comfortable.Pairing and connection to my Pixel 4 phone via bluetooth is quick and easy.Battery life and sound quality are both better than expected.I have recommended these to a couple of friends and would buy again if I lost or broke mine."
        },
        {
            "id": "R22FLWGUJ4Y2CN",
            "review_data": "Reviewed in the United States on February 22, 2020",
            "name": "PakitaB",
            "rating": 5,
            "title": "Thumbs up!",
            "review": "The headset is teen approved, I bought it for my daughter and she is been using it with no problems, good sound quality, battery seems to last for a very long time and the best part is that it’s pretty light on her head. Thumbs up!"
        },
        {
            "id": "R1LUF1VXQ8A90D",
            "review_data": "Reviewed in the United States on March 9, 2020",
            "name": "Bob57",
            "rating": 5,
            "title": "Very happy with this purchase",
            "review": "The headset arrived on time and in a very sturdy box.It arrived partially charged but I put it on to charge while reading through the manual.Register it on the manufacturer website and get an 18 month extended warranty. I was impressed with the confidence the manufacturer had in their product by offering the extra warranty time.The product has excellent noise cancelling. I drive a truck and it is old and noisy. People had complained with having problems hearing me over the engine noise with my old headset. One day I was talking with this headset and the person I was talking with heard me clearly and the microphone boom was all the way up over my head. Very sensitive mic, I can even talk and be heard if the windows are down.Lightweight and comfortable enough to wear all day."
        },
        {
            "id": "R1Q8368S964PCQ",
            "review_data": "Reviewed in the United States on April 16, 2020",
            "name": "R J Stah",
            "rating": 5,
            "title": "Solve problem with no bluetooth while driving an older vehicle, plus home office use",
            "review": "Originally I got this headset to use with my phone's Bluetooth while driving as my 2005 vehicle does not have it.However I found it even more valuable to use in my home office as I'm always setting the phone down \"somewhere\" and while wearing this I didn't have to care so much where I left it last.I suppose air buds would do the same thing but this headset allows for one ear to be completely uncovered.I was concerned whether it had the advertised comfort level for extended periods of wear but it does.I wear it about 6 hours/day - no issues and no recharging needed during that time period.Full recharge only takes about 10-15 minutes!Only drawback I have noticed is that sometimes I have to repeat myself when trying to connect to a Siri command.But the volume while driving is great plus people tell me they can hear me just fine, which in the past has been a concern with other devices."
        },
        {
            "id": "R156WA32S5NRZU",
            "review_data": "Reviewed in the United States on May 13, 2020",
            "name": "Suresh V",
            "rating": 5,
            "title": "Great trucker Bluetooth headset!",
            "review": "Amazing trucker Bluetooth headset!Highly recommended.Quality is good. The one iam looking for.... Comfortable"
        }
    ]
}
```

## Product Information

| Parameter |                                            Description                                            |
| --------- | :-----------------------------------------------------------------------------------------------: |
| asin      |                                      The ASIN of the Product                                      |
| region    | In what region do you want to search - Use Amazon domain endings (com, de, it, es, fr, co.uk, jp) |

```bash
curl --request GET \
	--url 'https://amazon-product-search.p.rapidapi.com/amazon-search/product.php?asin=B081Q5RCMV&region=com' \
	--header 'x-rapidapi-host: amazon-product-search.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
    "result": [
        {
            "title": "Bluetooth Headset mit Microfon TaoTronics PC Headset kabellos Kopfhörer Smart AI Noise Cancellation 34Std. Spielzeit für LKW Fahrer Computer Office Call Center Skype",
            "url": "https://www.amazon.de/dp/B081Q5RCMV",
            "reviews": {
                "total_reviews": 680,
                "rating": "4,6",
                "answered_questions": 4
            },
            "price": {
                "current_price": 45,
                "discounted": false,
                "before_price": 45,
                "savings_amount": 0,
                "savings_percent": 0
            },
            "images": [
                "https://images-na.ssl-images-amazon.com/images/I/31URF%2B3G-HL._AC_SY879_.jpg",
                "https://images-na.ssl-images-amazon.com/images/I/51W2v-uaMbL._AC_SY879_.jpg",
                "https://images-na.ssl-images-amazon.com/images/I/51oKw7I3SrL._AC_SY879_.jpg",
                "https://images-na.ssl-images-amazon.com/images/I/41OUJZmjpxL._AC_SY879_.jpg",
                "https://images-na.ssl-images-amazon.com/images/I/41f1erEC%2BSL._AC_SY879_.jpg",
                "https://images-na.ssl-images-amazon.com/images/I/41xaBJ%2BRjwL._AC_SY879_.jpg",
                "https://images-na.ssl-images-amazon.com/images/I/21LlmxUCtTS._AC_SY879_.jpg"
            ],
            "storeID": "",
            "brand": "TaoTronics",
            "soldBy": "",
            "fulfilledBy": "",
            "qtyPerOrder": 30,
            "badges": {
                "amazonChoice": true,
                "amazonPrime": false
            }
        }
    ]
}
```