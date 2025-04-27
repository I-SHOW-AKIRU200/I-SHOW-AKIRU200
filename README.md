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

### 1. PLAYER INFO
```http
GET https://akiru-info.vercel.app/info?uid=2206344781&region=ind&key={API_KEY}
```
```json
{
  "basicInfo": {
    "accountId": "2206344781",
    "accountType": 1,
    "nickname": "꧁༒☬Ákhil༒",
    "region": "IND",
    "level": 68,
    "exp": 2389233,
    "bannerId": 901026013,
    "headPic": 902000189,
    "rank": 325,
    "rankingPoints": 5609,
    "badgeCnt": 110,
    "badgeId": 1001000083,
    "seasonId": 44,
    "liked": 23366,
    "lastLoginAt": "1745723700",
    "csRank": 322,
    "csRankingPoints": 115,
    "weaponSkinShows": [907136108],
    "maxRank": 325,
    "csMaxRank": 322,
    "accountPrefers": {
      "brPregameShowChoices": [1]
    },
    "createAt": "1595406585",
    "title": 904590059,
    "externalIconInfo": {
      "status": "ExternalIconStatus_NOT_IN_USE",
      "showType": "ExternalIconShowType_FRIEND"
    },
    "releaseVersion": "OB48",
    "showBrRank": true,
    "showCsRank": true,
    "socialHighLightsWithBasicInfo": {

    }
  },
  "profileInfo": {
    "avatarId": 102000004,
    "equipedSkills": [205041039, 211000041, 214035012, 204000081, 203046040],
    "pvePrimaryWeapon": 1,
    "endTime": 1,
    "clothesTailorEffects": [1]
  },
  "clanBasicInfo": {
    "clanId": "3039430705",
    "clanName": "YGㅤᎬ-ꮪꮲꭷꮢꭲꮪㅤ",
    "captainId": "2311867514",
    "clanLevel": 5,
    "capacity": 50,
    "memberNum": 45
  },
  "captainBasicInfo": {
    "accountId": "2311867514",
    "accountType": 1,
    "nickname": "YGㅤටᴍᴋꫝʀㅤƼⱮ",
    "region": "IND",
    "level": 65,
    "exp": 1784673,
    "bannerId": 901026021,
    "headPic": 902026014,
    "rank": 321,
    "rankingPoints": 3598,
    "badgeCnt": 83,
    "badgeId": 1001000083,
    "seasonId": 44,
    "liked": 11779,
    "lastLoginAt": "1745728245",
    "csRank": 318,
    "csRankingPoints": 73,
    "weaponSkinShows": [907102509, 912000001],
    "maxRank": 321,
    "csMaxRank": 318,
    "accountPrefers": {

    },
    "createAt": "1598516649",
    "title": 904090024,
    "externalIconInfo": {
      "status": "ExternalIconStatus_NOT_IN_USE",
      "showType": "ExternalIconShowType_FRIEND"
    },
    "releaseVersion": "OB48",
    "showBrRank": true,
    "showCsRank": true,
    "socialHighLightsWithBasicInfo": {

    }
  },
  "petInfo": {
    "id": 1300000091,
    "level": 4,
    "exp": 540,
    "isSelected": true,
    "skinId": 1310000099,
    "selectedSkillId": 1315000011
  },
  "socialInfo": {
    "accountId": "2206344781",
    "language": "Language_CN_TRADITIONAL",
    "signature": "[FFB900][b] ㅤ ✿ ㅤ ♬ ㅤ ☯︎ [/b][c]\n     999ㅤ999ㅤ999",
    "rankShow": "RankShow_CS"
  },
  "diamondCostRes": {
    "diamondCost": 390
  },
  "creditScoreInfo": {
    "creditScore": 100,
    "rewardState": "REWARD_STATE_UNCLAIMED",
    "periodicSummaryEndTime": "1745566485"
  }
}
```

### 2. GET LIKE
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

### 3. GET VISIT
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

### 1. ITEM INFO (3 Options)
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

### 2. RANK INFO
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
### 3. MAP INFO API
```http
GET https://freefireinfo.vercel.app/map?region={REGION}&code={MAP_CODE}key={API_KEY}
```
```json
{
  "status": "success",
  "data": {
    "rule": "TEAM-AKIRU",
    "region": "SG",
    "lang": "en",
    "Craftland Map Details": {
      "MapCode": "#FREEFIREDFEF0EE3DA3A74F700181500DD9B85AA4913",
      "Creator": "Sunset8_9v6",
      "Title": "Weapon Master",
      "Description": "Kill the most enemies with different weapons",
      "MapCover": "https://dl-sg-production.freefiremobile.com/3E9EA1_7104104913_10007_1743149154_MAPCOVER.JPG",
      "Subscribers": 2227317,
      "Likes": 8540124,
      "Teams": 2,
      "PlayAverage": 316,
      "Rounds": 1,
      "Tags": [
        "PvP",
        "Squad"
      ],
      "MiniMap": "APD//z8AAMD///8AAAD///8DAAD8//8PAADw//8/AADA////AAAAAfCAAwAAHIABDgAAcAAAOAAAwAEA4AAAAAcAgAMAABweAA4AAHB4ADgAAMDhP5AAAACH/0ACAAAc/sMPAABwAAA4AADAAQDgAAAAHwCAAwAAfAAADgAAcH74OQAAwPnh5wAAAP+HnwMAAPwffg4AAHB++zkAAMD57ecAAADnh/8DAACc3/4PAABwgAc4AADAAQzgAAAABzDgAwAAHACADwAAcAAAOAAAwAEA4AAAAD/8hwMAACTwHw4AAJDAfzgAAMAB4OEAAAAHgIcDAAAcAAAOAABwAAA4AADAAQDgAAAAB2CAAwAAHMADCAAA8P//PwAAwP///wAAAP///wMAAPz//w8AAPD//z8AAMD///8AAA==",
      "Mode": "Customize",
      "Map": "ISLE OF CHAMPS 50×50"
    }
  }
}
```
  ### 4. CHARACTER INFO API
  ```http
GET https://character-roan.vercel.app/Character_name/Id={CHARACTER_NAME/CHARACTER_ID}
```
```json
{
  "Character Name": "Alok",
  "Png Image": "https://freefiremobile-a.akamaihd.net/common/web_event/official2.ff.garena.all/img/20228/c62e709e3ad8387f5484bb12e1cc81a9.png",
  "Skill id": "2206"
}
```
### 5. ITEMS IMAGE API
```http
GET https://item-info-pied.vercel.app/akiru-item-info?item_id={ITEMS_ID}&key={API_KEY}
```
<div align="center">
  <!-- Free Fire Logo (Top - 200px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/AKIRU-ICONS/main/ICONS/710048007.png" alt="Free Fire Logo" width="200">
  </a>
  
  <br> <!-- Line break between logos -->
### 6. PET INFO API
  ```http
GET https://akiru-pet-info.vercel.app/akiru-pet-info?pet_name={PET_NAME/PET_ID}&key={KEY}
```
<div align="center">
  <!-- Free Fire Logo (Top - 200px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://akiru-pet-info.vercel.app/akiru-pet-info?pet_name=Rockie&key=AKIRU" alt="Free Fire Logo" width="200">
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
| EVENT WEBSITE | [https://event-api-inky.vercel.app/](https://event-api-inky.vercel.app/)

</div>

## 📜 Credits
All APIs are developed and maintained by **TEAM-AKIRU**  
© 2025 AKIRU Services | [Terms of Service](https://t.me/ishowakiru5)
```
