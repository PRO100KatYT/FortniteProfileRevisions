## Comparison for the campaign profile, rvn: [2630](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/2630%20campaign.json)-[2631](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/2631%20campaign.json)

Object quest_state in 18492a73-db4a-46a7-84fb-e0db746af7c2 (Quest:endurancedaily_t01_w30) has been changed from: `"Completed"` to: `"Claimed"`
<br><br>
Object last_state_change_time in 18492a73-db4a-46a7-84fb-e0db746af7c2 (Quest:endurancedaily_t01_w30) has been changed from: `"2023-04-28T07:29:55.820Z"` to: `"2023-04-28T07:31:48.038Z"`
<br><br>
Object match_accolades in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from:

```
[
  {
    "matchmakingSessionId": "625f87a180514120aaec990fe014448c",
    "totalSecondsInMatch": 42,
    "primaryMissionName": "MissionInfo_Outpost_PvE_01",
    "partyEligibility": "User",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_endurance_w30",
        "numToGrant": 1,
        "realXPGranted": 323000,
        "rawXPGranted": 328800
      }
    ],
    "totalMissionXPEarnedInMatch": 323000,
    "totalQuestXPEarnedInMatch": 0,
    "totalRestSpentInMatch": 3000
  }
]
```

to:

```
[
  {
    "matchmakingSessionId": "625f87a180514120aaec990fe014448c",
    "totalSecondsInMatch": 42,
    "primaryMissionName": "MissionInfo_Outpost_PvE_01",
    "partyEligibility": "User",
    "accoladesToGrant": [
      {
        "templateToGrant": "Accolades:accoladeid_stw_endurance_w30",
        "numToGrant": 1,
        "realXPGranted": 323000,
        "rawXPGranted": 328800
      },
      {
        "templateToGrant": "Accolades:accoladeid_stw_quest_endurance_daily_w30",
        "numToGrant": 1,
        "realXPGranted": 7000,
        "rawXPGranted": 7000
      }
    ],
    "totalMissionXPEarnedInMatch": 323000,
    "totalQuestXPEarnedInMatch": 7000,
    "totalRestSpentInMatch": 3000
  }
]
```

<br><br>
Object last_update in 36d76de6-2dda-40bb-9534-a08bb5095b6a (Token:stw_accolade_tracker) has been changed from: `"2023-04-28T07:30:26.631Z"` to: `"2023-04-28T07:31:48.038Z"`
<br><br>
Object quest_completion_session_ids in the profile's stats has been changed from:

```
{
  "Quest:endurancedaily_t01_w25": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w20": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w10": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w15": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w05": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w30": "625f87a180514120aaec990fe014448c"
}
```

to:

```
{
  "Quest:endurancedaily_t01_w25": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w20": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w10": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w15": "625f87a180514120aaec990fe014448c",
  "Quest:endurancedaily_t01_w05": "625f87a180514120aaec990fe014448c"
}
```

<br><br>
