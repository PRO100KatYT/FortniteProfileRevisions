## Comparison for the campaign profile, rvn: [2273](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/2273%20campaign.json)-[2274](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/2274%20campaign.json)

Object match_accolades in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from:

```
[
  {
    "matchmakingSessionId": "4b52e3d3d1b64db08c689ea8155cb198",
    "totalSecondsInMatch": 0,
    "primaryMissionName": "MissionInfo_Outpost_PvE_01",
    "partyEligibility": "User",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_endurance_w30",
        "numToGrant": 1,
        "realXPGranted": 288850,
        "rawXPGranted": 328800
      },
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w05",
        "numToGrant": 1,
        "realXPGranted": 5000,
        "rawXPGranted": 5000
      }
    ],
    "totalMissionXPEarnedInMatch": 288850,
    "totalQuestXPEarnedInMatch": 5000,
    "totalRestSpentInMatch": 0
  }
]
```

to:

```
[
  {
    "matchmakingSessionId": "4b52e3d3d1b64db08c689ea8155cb198",
    "totalSecondsInMatch": 0,
    "primaryMissionName": "MissionInfo_Outpost_PvE_01",
    "partyEligibility": "User",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_endurance_w30",
        "numToGrant": 1,
        "realXPGranted": 288850,
        "rawXPGranted": 328800
      },
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w05",
        "numToGrant": 1,
        "realXPGranted": 5000,
        "rawXPGranted": 5000
      },
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w20",
        "numToGrant": 1,
        "realXPGranted": 8000,
        "rawXPGranted": 8000
      }
    ],
    "totalMissionXPEarnedInMatch": 288850,
    "totalQuestXPEarnedInMatch": 13000,
    "totalRestSpentInMatch": 0
  }
]
```

<br><br>
Object last_update in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from: `"2023-04-23T09:26:22.472Z"` to: `"2023-04-23T09:26:49.471Z"`
<br><br>
Object quest_state in 2f178a20-6862-4797-a95b-50a4c048fcc1 (Quest:endurancedaily_t01_w20) has been changed from: `"Completed"` to: `"Claimed"`
<br><br>
Object last_state_change_time in 2f178a20-6862-4797-a95b-50a4c048fcc1 (Quest:endurancedaily_t01_w20) has been changed from: `"2023-04-23T09:22:11.352Z"` to: `"2023-04-23T09:26:49.471Z"`
<br><br>
Object quest_completion_session_ids in the profile's stats has been changed from:

```
{
  "Quest:endurancedaily_t01_w25": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w20": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w10": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w15": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w30": "4b52e3d3d1b64db08c689ea8155cb198"
}
```

to:

```
{
  "Quest:endurancedaily_t01_w25": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w10": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w15": "4b52e3d3d1b64db08c689ea8155cb198",
  "Quest:endurancedaily_t01_w30": "4b52e3d3d1b64db08c689ea8155cb198"
}
```

<br><br>
