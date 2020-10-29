# Tennis Data Requests & Responses

## Find Tournaments

| Parameter |                        Description                         |
| --------- | :--------------------------------------------------------: |
| page      |     The page you want returned (Default: 1) (Optional)     |
| minPrize  |     The minimum Prizepool of the Tournament (Optional)     |
| type      |                ATP or ITF or WTA (Optional)                |
| year      | The year in which the Tournaments took place in (Optional) |

```bash
curl --request GET \
	--url 'https://tennis-data1.p.rapidapi.com/tennis/tournaments?minPrize=10000&year=2018&page=1&type=ATP' \
	--header 'x-rapidapi-host: tennis-data1.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
  "data": [
    {
      "id": 15390,
      "name": "Abu Dhabi - exh.",
      "date": "2018-12-27",
      "type": "ATP",
      "prize": 100000,
      "finished": true
    },
    {
      "id": 15389,
      "name": "Orlando challenger",
      "date": "2018-12-31",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 15388,
      "name": "Playford chall.",
      "date": "2018-12-31",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 15387,
      "name": "Noumea challenger",
      "date": "2018-12-31",
      "type": "ATP",
      "prize": 81240,
      "finished": true
    },
    {
      "id": 15386,
      "name": "Pune",
      "date": "2018-12-31",
      "type": "ATP",
      "prize": 589680,
      "finished": true
    },
    {
      "id": 15385,
      "name": "Doha",
      "date": "2018-12-31",
      "type": "ATP",
      "prize": 1313215,
      "finished": true
    },
    {
      "id": 14519,
      "name": "Bangkok 2 chall.",
      "date": "2018-01-01",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14518,
      "name": "Noumea challenger",
      "date": "2018-01-01",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14517,
      "name": "Pune",
      "date": "2018-01-01",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14516,
      "name": "Doha",
      "date": "2018-01-01",
      "type": "ATP",
      "prize": 1386665,
      "finished": true
    },
    {
      "id": 14515,
      "name": "Playford chall.",
      "date": "2018-01-02",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14514,
      "name": "Bangkok 3 chall.",
      "date": "2018-01-08",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14513,
      "name": "Canberra chall.",
      "date": "2018-01-08",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14512,
      "name": "Adelaide - World Tennis Chall.",
      "date": "2018-01-08",
      "type": "ATP",
      "prize": 100000,
      "finished": false
    },
    {
      "id": 14511,
      "name": "Auckland",
      "date": "2018-01-08",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14510,
      "name": "Czech Indoor Championship",
      "date": "2018-01-09",
      "type": "ATP",
      "prize": 20000,
      "finished": true
    },
    {
      "id": 14509,
      "name": "Koblenz challenger",
      "date": "2018-01-16",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14508,
      "name": "Rennes challenger",
      "date": "2018-01-22",
      "type": "ATP",
      "prize": 64000,
      "finished": true
    },
    {
      "id": 14507,
      "name": "Newport Beach chall.",
      "date": "2018-01-22",
      "type": "ATP",
      "prize": 150000,
      "finished": true
    },
    {
      "id": 14505,
      "name": "Quimper challenger",
      "date": "2018-01-29",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14504,
      "name": "Burnie challenger",
      "date": "2018-01-29",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14503,
      "name": "Dallas challenger",
      "date": "2018-01-29",
      "type": "ATP",
      "prize": 125000,
      "finished": true
    },
    {
      "id": 14502,
      "name": "Budapest 2 chall.",
      "date": "2018-02-05",
      "type": "ATP",
      "prize": 64000,
      "finished": true
    },
    {
      "id": 14501,
      "name": "Launceston chall.",
      "date": "2018-02-05",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14500,
      "name": "San Francisco chall.",
      "date": "2018-02-05",
      "type": "ATP",
      "prize": 100000,
      "finished": true
    },
    {
      "id": 14499,
      "name": "Sofia",
      "date": "2018-02-05",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14498,
      "name": "Quito",
      "date": "2018-02-05",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14497,
      "name": "Montpellier",
      "date": "2018-02-05",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14496,
      "name": "Cherbourg chall.",
      "date": "2018-02-12",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14495,
      "name": "Chennai challenger",
      "date": "2018-02-12",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14494,
      "name": "Buenos Aires",
      "date": "2018-02-12",
      "type": "ATP",
      "prize": 648180,
      "finished": true
    },
    {
      "id": 14493,
      "name": "New York",
      "date": "2018-02-12",
      "type": "ATP",
      "prize": 748450,
      "finished": true
    },
    {
      "id": 14492,
      "name": "Rotterdam",
      "date": "2018-02-12",
      "type": "ATP",
      "prize": 1996245,
      "finished": true
    },
    {
      "id": 14491,
      "name": "Delray Beach - seniors",
      "date": "2018-02-16",
      "type": "ATP",
      "prize": 100000,
      "finished": false
    },
    {
      "id": 14490,
      "name": "Morelos challenger",
      "date": "2018-02-19",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14489,
      "name": "Kyoto challenger",
      "date": "2018-02-19",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14488,
      "name": "Bergamo challenger",
      "date": "2018-02-19",
      "type": "ATP",
      "prize": 64000,
      "finished": true
    },
    {
      "id": 14487,
      "name": "Delray Beach",
      "date": "2018-02-19",
      "type": "ATP",
      "prize": 622675,
      "finished": true
    },
    {
      "id": 14486,
      "name": "Marseille",
      "date": "2018-02-19",
      "type": "ATP",
      "prize": 718810,
      "finished": true
    },
    {
      "id": 14485,
      "name": "Rio de Janeiro",
      "date": "2018-02-19",
      "type": "ATP",
      "prize": 1842475,
      "finished": true
    },
    {
      "id": 14484,
      "name": "Punta del Este chall.",
      "date": "2018-02-26",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14483,
      "name": "Yokohama chall.",
      "date": "2018-02-26",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14482,
      "name": "Wroclaw challenger",
      "date": "2018-02-26",
      "type": "ATP",
      "prize": 85000,
      "finished": false
    },
    {
      "id": 14481,
      "name": "Indian Wells chall.",
      "date": "2018-02-26",
      "type": "ATP",
      "prize": 150000,
      "finished": true
    },
    {
      "id": 14480,
      "name": "Sao Paulo",
      "date": "2018-02-26",
      "type": "ATP",
      "prize": 582870,
      "finished": true
    },
    {
      "id": 14479,
      "name": "Dubai",
      "date": "2018-02-26",
      "type": "ATP",
      "prize": 3057135,
      "finished": true
    },
    {
      "id": 14478,
      "name": "Santiago chall.",
      "date": "2018-03-05",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14477,
      "name": "Zhuhai challenger",
      "date": "2018-03-05",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14476,
      "name": "Indian Wells",
      "date": "2018-03-08",
      "type": "ATP",
      "prize": 7972535,
      "finished": true
    },
    {
      "id": 14475,
      "name": "Shenzhen chall.",
      "date": "2018-03-13",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14474,
      "name": "Drummondville chall.",
      "date": "2018-03-13",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14473,
      "name": "Irving challenger",
      "date": "2018-03-13",
      "type": "ATP",
      "prize": 150000,
      "finished": true
    },
    {
      "id": 14472,
      "name": "Lille challenger",
      "date": "2018-03-19",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14471,
      "name": "Qujing challenger",
      "date": "2018-03-19",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14470,
      "name": "Miami",
      "date": "2018-03-21",
      "type": "ATP",
      "prize": 7972535,
      "finished": true
    },
    {
      "id": 14469,
      "name": "Saint Brieuc chall.",
      "date": "2018-03-26",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14468,
      "name": "Marbella chall.",
      "date": "2018-03-26",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14467,
      "name": "San Luis Potosi chall.",
      "date": "2018-03-27",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14466,
      "name": "Le Gosier chall.",
      "date": "2018-03-27",
      "type": "ATP",
      "prize": 85000,
      "finished": true
    },
    {
      "id": 14465,
      "name": "Alicante chall.",
      "date": "2018-04-02",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14464,
      "name": "Panama City chall.",
      "date": "2018-04-02",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14463,
      "name": "Barletta chall.",
      "date": "2018-04-09",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14462,
      "name": "Mexico City chall.",
      "date": "2018-04-09",
      "type": "ATP",
      "prize": 100000,
      "finished": true
    },
    {
      "id": 14461,
      "name": "Taipei challenger",
      "date": "2018-04-09",
      "type": "ATP",
      "prize": 150000,
      "finished": true
    },
    {
      "id": 14460,
      "name": "Marrakech",
      "date": "2018-04-09",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14459,
      "name": "Houston",
      "date": "2018-04-09",
      "type": "ATP",
      "prize": 623710,
      "finished": true
    },
    {
      "id": 14458,
      "name": "Monte Carlo",
      "date": "2018-04-15",
      "type": "ATP",
      "prize": 5238735,
      "finished": true
    },
    {
      "id": 14457,
      "name": "Nanchang chall.",
      "date": "2018-04-16",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14456,
      "name": "Guadalajara chall.",
      "date": "2018-04-16",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14455,
      "name": "Tunis challenger",
      "date": "2018-04-16",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14454,
      "name": "Sarasota chall.",
      "date": "2018-04-16",
      "type": "ATP",
      "prize": 100000,
      "finished": true
    },
    {
      "id": 14453,
      "name": "Francavilla chall.",
      "date": "2018-04-23",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14452,
      "name": "Tallahassee chall.",
      "date": "2018-04-23",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14451,
      "name": "Leon challenger",
      "date": "2018-04-23",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14450,
      "name": "An-Ning challenger",
      "date": "2018-04-23",
      "type": "ATP",
      "prize": 150000,
      "finished": true
    },
    {
      "id": 14449,
      "name": "Budapest",
      "date": "2018-04-23",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14448,
      "name": "Barcelona",
      "date": "2018-04-23",
      "type": "ATP",
      "prize": 2794220,
      "finished": true
    },
    {
      "id": 14447,
      "name": "Ostrava challenger",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 64000,
      "finished": true
    },
    {
      "id": 14446,
      "name": "Savannah chall.",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14445,
      "name": "Puerto Vallarta chall.",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14444,
      "name": "Glasgow challenger",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 85000,
      "finished": true
    },
    {
      "id": 14443,
      "name": "Seoul challenger",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 100000,
      "finished": true
    },
    {
      "id": 14442,
      "name": "Istanbul",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 486145,
      "finished": true
    },
    {
      "id": 14441,
      "name": "Munich",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14440,
      "name": "Estoril",
      "date": "2018-04-30",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14439,
      "name": "Madrid - Masters",
      "date": "2018-05-06",
      "type": "ATP",
      "prize": 7190930,
      "finished": true
    },
    {
      "id": 14438,
      "name": "Braga challenger",
      "date": "2018-05-07",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14437,
      "name": "Gimcheon chall.",
      "date": "2018-05-07",
      "type": "ATP",
      "prize": 50000,
      "finished": true
    },
    {
      "id": 14436,
      "name": "Rome 2 challenger",
      "date": "2018-05-07",
      "type": "ATP",
      "prize": 64000,
      "finished": true
    },
    {
      "id": 14435,
      "name": "Karshi challenger",
      "date": "2018-05-07",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14434,
      "name": "Aix en Provence chall.",
      "date": "2018-05-07",
      "type": "ATP",
      "prize": 127000,
      "finished": true
    },
    {
      "id": 14433,
      "name": "Rome",
      "date": "2018-05-13",
      "type": "ATP",
      "prize": 5444985,
      "finished": true
    },
    {
      "id": 14432,
      "name": "Lisbon challenger",
      "date": "2018-05-14",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    },
    {
      "id": 14431,
      "name": "Heilbronn 2 chall.",
      "date": "2018-05-14",
      "type": "ATP",
      "prize": 85000,
      "finished": true
    },
    {
      "id": 14430,
      "name": "Bordeaux chall.",
      "date": "2018-05-14",
      "type": "ATP",
      "prize": 106000,
      "finished": true
    },
    {
      "id": 14429,
      "name": "Busan challenger",
      "date": "2018-05-14",
      "type": "ATP",
      "prize": 150000,
      "finished": true
    },
    {
      "id": 14428,
      "name": "Samarkand chall.",
      "date": "2018-05-15",
      "type": "ATP",
      "prize": 75000,
      "finished": true
    },
    {
      "id": 14427,
      "name": "Lyon",
      "date": "2018-05-20",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14426,
      "name": "Geneva",
      "date": "2018-05-20",
      "type": "ATP",
      "prize": 561345,
      "finished": true
    },
    {
      "id": 14425,
      "name": "Mestre challenger",
      "date": "2018-05-21",
      "type": "ATP",
      "prize": 43000,
      "finished": true
    }
  ],
  "hasNextPage": true
}
```

## Get Tournament by ID

| Parameter |             Description             |
| --------- | :---------------------------------: |
| id        | The ID of the Tournament (Required) |

```bash
curl --request GET \
	--url 'https://tennis-data1.p.rapidapi.com/tennis/tournament/{id}' \
	--header 'x-rapidapi-host: tennis-data1.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
  "id": 1,
  "name": "Masters Cup WTA",
  "date": "1995-11-13",
  "type": "WTA",
  "prize": 500000,
  "finished": true
}
```

## Get Matches

| Parameter  |                             Description                              |
| ---------- | :------------------------------------------------------------------: |
| page       |          The page you want returned (Default: 1) (Optional)          |
| player_id  |        Find matches of player with this player ID (Optional)         |
| tournament |             Find matches from this tournament (Optional)             |
| surface    | Find matches on this surface (grass, clay, indoors, hard) (Optional) |

```bash
curl --request GET \
	--url 'https://tennis-data1.p.rapidapi.com/tennis/matches?page=1&player_id=30754&tournament=15830&surface=hard' \
	--header 'x-rapidapi-host: tennis-data1.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
  "data": [
    {
      "id": 1907376,
      "match_games": "",
      "player1_id": 30754,
      "player1_sets": 0,
      "player1_games": 0,
      "player2_id": 36166,
      "player2_sets": 0,
      "player2_games": 0,
      "match_date": "2020-10-30 00:00:00",
      "match_surface": "hard",
      "match_finished": false,
      "match_round": 0,
      "match_isqualification": false,
      "tournament_id": 15830,
      "player2_injured": false
    },
    {
      "id": 1907132,
      "match_games": "6-2,6-1",
      "player1_id": 30754,
      "player1_sets": 2,
      "player1_games": 12,
      "player2_id": 32864,
      "player2_sets": 0,
      "player2_games": 3,
      "match_date": "2020-10-29 10:30:00",
      "match_surface": "hard",
      "match_finished": true,
      "match_round": 0,
      "match_isqualification": false,
      "tournament_id": 15830,
      "player2_injured": false
    }
  ],
  "hasNextPage": false
}
```

## Get Players

| Parameter |                    Description                     |
| --------- | :------------------------------------------------: |
| page      | The page you want returned (Default: 1) (Optional) |
| id        |       Get Player with certain ID (Optional)        |

```bash
curl --request GET \
	--url 'https://tennis-data1.p.rapidapi.com/tennis/players?page=1&id=40827' \
	--header 'x-rapidapi-host: tennis-data1.p.rapidapi.com' \
	--header 'x-rapidapi-key: XXXXXXXXXX'
```

### Response

```json
{
  "data": [
    {
      "id": 40827,
      "name": "Kania-Chodun Paula",
      "rank": 749,
      "hand": "right",
      "birthday": "1992-11-06",
      "link": "http://tennisexplorer.com/player/kania-chodun",
      "height": "168 cm",
      "weight": "58 kg",
      "turned_pro": "-",
      "country": null,
      "singles_current_rank": 0,
      "singles_highest_rank": 0,
      "doubles_current_rank": 0,
      "doubles_highest_rank": 0
    }
  ],
  "hasNextPage": false
}
```
