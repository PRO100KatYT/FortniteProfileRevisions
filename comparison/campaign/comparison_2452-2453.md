## Comparison for the campaign profile, rvn: [2452](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/2452%20campaign.json)-[2453](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/2453%20campaign.json)

Object quest_state in b796fdfa-2eb2-40a6-8817-e1e824dbbbd4 (Quest:endurancedaily_t01_w30) has been changed from: `"Completed"` to: `"Claimed"`
<br><br>
Object last_state_change_time in b796fdfa-2eb2-40a6-8817-e1e824dbbbd4 (Quest:endurancedaily_t01_w30) has been changed from: `"2023-04-25T08:28:28.863Z"` to: `"2023-04-25T18:17:25.271Z"`
<br><br>
Object match_accolades in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from:

```
[
  {
    "matchmakingSessionId": "bb0a039d29fe43eb888160685fafa058",
    "totalSecondsInMatch": 0,
    "partyEligibility": "None",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w25",
        "numToGrant": 1,
        "realXPGranted": 7000,
        "rawXPGranted": 7000
      }
    ],
    "totalMissionXPEarnedInMatch": 0,
    "totalQuestXPEarnedInMatch": 7000,
    "totalRestSpentInMatch": 0
  }
]
```

to:

```
[
  {
    "matchmakingSessionId": "bb0a039d29fe43eb888160685fafa058",
    "totalSecondsInMatch": 0,
    "partyEligibility": "None",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w25",
        "numToGrant": 1,
        "realXPGranted": 7000,
        "rawXPGranted": 7000
      },
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w30",
        "numToGrant": 1,
        "realXPGranted": 7000,
        "rawXPGranted": 7000
      }
    ],
    "totalMissionXPEarnedInMatch": 0,
    "totalQuestXPEarnedInMatch": 14000,
    "totalRestSpentInMatch": 0
  }
]
```

<br><br>
Object last_update in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from: `"2023-04-25T18:17:22.373Z"` to: `"2023-04-25T18:17:25.271Z"`
<br><br>
Object quest_completion_session_ids in the profile's stats has been changed from:

```
{
  "Quest:endurancedaily_t01_w20": "bb0a039d29fe43eb888160685fafa058",
  "Quest:endurancedaily_t01_w30": "bb0a039d29fe43eb888160685fafa058"
}
```

to:

```
{
  "Quest:endurancedaily_t01_w20": "bb0a039d29fe43eb888160685fafa058"
}
```

<br><br>
