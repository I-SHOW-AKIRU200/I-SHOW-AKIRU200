<div align="center">
  <!-- Free Fire Logo (Top - 200px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/I-SHOW-AKIRU/main/FREE-FIRE.png" alt="Free Fire Logo" width="200">
  </a>
  
  <br> <!-- Line break between logos -->
  
  <!-- Team Akiru Logo (Bottom - 400px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/I-SHOW-AKIRU/main/TEAM-AKIRU.png" alt="Team Akiru Logo" width="400">
  </a>
</div>

<br> <!-- Space before content -->


<!-- Rest of your README content goes here -->

# 🔥 AKIRU API Suite

## 📊 Player APIs

### 1. Player Info
```http
GET https://akiru-info.vercel.app/akiru-info-api?uid=2206344781&region=ind&key={API_KEY}
```
```json
 {
  "AccountOverview": {
    "EquippedOutfit": [205041039, 211000140, 214035012, 204000055, 203046040, 211000435],
    "EquippedSkills": [16, 1806, 8, 1, 16, 6201, 8, 2, 16, 4806, 8, 3, 16, 1005]
  },
  "BasicProfileInfo": {
    "AccountEXP": 2362784,
    "AccountLikes": 21392,
    "AccountName": "꧁༒☬Ákhil༒",
    "AccountUID": "2206344781",
    "AvatarID": "902048008",
    "BannerID": "901026013",
    "BooyahPassBadge": 11,
    "BrRankPoint": "Heroic",
    "CreatedAt": "22/07/2020, 13:59:45",
    "CsRankingPoint": 78,
    "EquippedItems": [
      "907101817"
    ],
    "HasBooyahPass": "Basic",
    "LastLogin": "02/04/2025, 08:52:55",
    "Level": 68,
    "Region": "IND",
    "Title": "Terminator",
    "TitleID": "904590058"
  },
  "CreditScoreInfo": {
    "creditScore": 100
  },
  "GuildInfo": {
    "GuildID": "3039430705",
    "GuildLevel": 5,
    "GuildName": "YGㅤᎬ-ꮪꮲꭷꮢꭲꮪㅤ",
    "LiveMembers": 35
  },
  "GuildLeaderInfo": {
    "LeaderBoyaahPassBadge": 4,
    "LeaderBrRankPoint": "Heroic",
    "LeaderCreatedAt": "27/08/2020, 13:54:09",
    "LeaderCsRankingPoint": 48,
    "LeaderEXP": 1772137,
    "LeaderLastLogin": "02/04/2025, 08:04:04",
    "LeaderLevel": 65,
    "LeaderName": "YGㅤටᴍᴋꫝʀㅤƼⱮ",
    "LeaderTitle": "4 Years Old",
    "LeaderTitleID": "904090024",
    "LeaderUID": "2311867514"
  },
  "PlayerGalleryInfo": {
    "PlayerBIO": "[FFB900][b] ㅤ ✿ ㅤ ♬ ㅤ ☯︎ [/b][c]\n     999ㅤ999ㅤ999"
  },
  "PlayerPetInfo": {
    "PetExp": 540,
    "PetLevel": 4,
    "PetName": "Falco",
    "PetNickName": "Falco"
  },
  "PublicCraftlandMaps": {
    "MapCodes": []
  }
}
```

### 2. Like System
```http
GET https://akiru-like.vercel.app/like?uid=2206344781&server_name=ind
```
```json
{
  "LikesGivenByAPI": 100,
  "LikesafterCommand": 8681,
  "LikesbeforeCommand": 8581,
  "PlayerNickname": "꧁༒☬Ákhil༒",
  "UID": 5177877011,
  "status": 1
}
```

### 3. Visit Tracker
```http
GET https://akiru-visit.vercel.app/visit?uid=2206344781&region=ind
```
```json
{
  "FailedVisits": 31,
  "PlayerNickname": "꧁༒☬Ákhil༒",
  "SuccessfulVisits": 255,
  "TotalVisits": 286,
  "UID": 2206344781
}
```

## 🛠️ Utility APIs

### 1. Item Info (3 Options)
```http
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=1&items=203047001
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=2&items=Sandalwood%20Raja%20(Top)
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=3&items=Icon_Name_avatar_male_cos_top_woodcrafter
```
```json
[{
  "Icon_Name": "Icon_Name_avatar_male_cos_top_woodcrafter",
  "Icon_URL": "https://item-info-pied.vercel.app/akiru-item-info?item_id=203047001",
  "Item_ID": "203047001",
  "Name": "Sandalwood Raja (Top)"
}]
```

### 2. Rank Info
```http
GET https://akiru.vercel.app/AKIRU-rank-info?uid=2206344781&region=ind
```
```json
{
  "AccountName": "꧁༒☬Ákhil༒",
  "AccountRegion": "IND",
  "BrRankPoint": 3875,
  "Credit": "TEAM-AKIRU",
  "CsRankPoint": "Elite Master 1 Star"
}
```
```http
GET https://freefireinfo.vercel.app/map?region={REGION}&code={MAP_CODE}key={API_KEY}
```
```json
{
  "status": "success",
  "data": {
    "rule": "Shah G Creator",
    "region": "SG",
    "lang": "en",
    "Craftland Map Details": {
      "MapCode": "#FREEFIREDFEF0EE3DA3A74F700181500DD9B85AA4913",
      "Creator": "Sunset8_9v6",
      "Title": "Weapon Master",
      "Description": "Kill the most enemies with different weapons",
      "MapCover": "https://dl-sg-production.freefiremobile.com/3C124B_7104104913_10007_1726822648_MAPCOVER.JPG",
      "Subscribers": 2123365,
      "Likes": 8158152,
      "Teams": 2,
      "PlayAverage": 324,
      "Rounds": 1,
      "Tags": [
        "PvP",
        "Squad"
      ],
      "Mode": "Customize"
    }
  }
}
```
```http
https://item-info-pied.vercel.app/akiru-item-info?item_id={ITEMS_ID}&key={API_KEY}
```
<div align="center">
  <!-- Free Fire Logo (Top - 200px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://item-info-pied.vercel.app/akiru-item-info?item_id=203047001&key=FREE-FIRE" alt="Free Fire Logo" width="200">
  </a>
  
  <br> <!-- Line break between logos -->

## 🌍 Web Services

<div align="center">

| Service | URL |
|---------|-----|
| AKIRU AI | [https://akiru-ai.vercel.app/](https://akiru-ai.vercel.app/) |
| Outfit Info | [https://outfit-info-web.vercel.app/](https://outfit-info-web.vercel.app/) |
| Wishlist Manager | [https://wishlist-add-web.vercel.app/](https://wishlist-add-web.vercel.app/) |
| Emote ID Finder | [https://thachmora.site/freefire](https://thachmora.site/freefire) |
| JWT | [https://akiru-jwt.vercel.app/AKIRU-JWT-GENERATOR](https://akiru-jwt.vercel.app/AKIRU-JWT-GENERATOR) |
| PLAYER INFO | [https://akiru-info-website.vercel.app](https://akiru-info-website.vercel.app) |

</div>

## 📜 Credits
All APIs are developed and maintained by **TEAM-AKIRU**  
© 2025 AKIRU Services | [Terms of Service](https://t.me/ishowakiru5)
```
