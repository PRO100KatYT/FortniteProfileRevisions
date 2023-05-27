## Comparison for the campaign profile, rvn: [1323](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1323%20campaign.json)-[1324](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1324%20campaign.json)

Object quest_state in 14161d74-3b68-4834-a89c-b282234562d7 (Quest:endurancedaily_t01_w05) has been changed from: `"Completed"` to: `"Claimed"`
<br><br>
Object last_state_change_time in 14161d74-3b68-4834-a89c-b282234562d7 (Quest:endurancedaily_t01_w05) has been changed from: `"2023-04-13T07:22:16.307Z"` to: `"2023-04-13T07:24:03.199Z"`
<br><br>
Object match_accolades in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from:

```
[
  {
    "matchmakingSessionId": "c199a7d6439347b3b44465af2f17b3ff",
    "totalSecondsInMatch": 56,
    "primaryMissionName": "MissionInfo_Outpost_PvE_01",
    "partyEligibility": "User",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_endurance_w30",
        "numToGrant": 1,
        "realXPGranted": 321000,
        "rawXPGranted": 328800
      }
    ],
    "totalMissionXPEarnedInMatch": 321000,
    "totalQuestXPEarnedInMatch": 0,
    "totalRestSpentInMatch": 1000
  }
]
```

to:

```
[
  {
    "matchmakingSessionId": "c199a7d6439347b3b44465af2f17b3ff",
    "totalSecondsInMatch": 56,
    "primaryMissionName": "MissionInfo_Outpost_PvE_01",
    "partyEligibility": "User",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_endurance_w30",
        "numToGrant": 1,
        "realXPGranted": 321000,
        "rawXPGranted": 328800
      },
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w05",
        "numToGrant": 1,
        "realXPGranted": 5000,
        "rawXPGranted": 5000
      }
    ],
    "totalMissionXPEarnedInMatch": 321000,
    "totalQuestXPEarnedInMatch": 5000,
    "totalRestSpentInMatch": 1000
  }
]
```

<br><br>
Object last_update in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from: `"2023-04-13T07:22:49.660Z"` to: `"2023-04-13T07:24:03.199Z"`
<br><br>
Object quest_completion_session_ids in the profile's stats has been changed from:

```
{
  "Quest:endurancedaily_t01_w25": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w20": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w10": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w15": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w05": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w30": "c199a7d6439347b3b44465af2f17b3ff"
}
```

to:

```
{
  "Quest:endurancedaily_t01_w25": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w20": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w10": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w15": "c199a7d6439347b3b44465af2f17b3ff",
  "Quest:endurancedaily_t01_w30": "c199a7d6439347b3b44465af2f17b3ff"
}
```

<br><br>
