## Comparison for the campaign profile, rvn: [218](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/218%20campaign.json)-[220](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/220%20campaign.json)

Item d1a0ca66-4cab-4b1c-a47a-6f48bab4882c (Quest:wargames_dailyquest_meteor_with_surprise_stonewood) has been removed from the profile.
<br><br>
Item 5310111c-2328-4a01-8cbd-3dbc20b1cbf9 (Quest:wargames_completedailyquest) has been removed from the profile.
<br><br>
Item eb81fde5-3453-4a1b-9466-dfb7f9268c8a (Quest:starlightquest_daily_complete_d5science) has been removed from the profile.
<br><br>
Item 94538fe4-0f28-4f92-8413-dba1ed4790fc has been added to the profile:

```
{
  "templateId": "Quest:starlightquest_daily_complete_d4",
  "attributes": {
    "creation_time": "2023-04-09T05:57:19.584Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-09T05:57:19.584Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1,
    "quest_pool": "starlightdailyquest_01"
  },
  "quantity": 1
}
```

<br><br>
Item c61a881f-80ee-46a2-bf3a-308bca3e4c63 has been added to the profile:

```
{
  "templateId": "Quest:wargames_completedailyquest",
  "attributes": {
    "creation_time": "2023-04-09T05:57:19.583Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-09T05:57:19.583Z",
    "level": -1,
    "quest_rarity": "legendary",
    "xp_reward_scalar": 1,
    "quest_pool": "dailywargameschallenge_01"
  },
  "quantity": 1
}
```

<br><br>
Item 47bb5bc2-1975-4e75-a970-5b099e527a15 has been added to the profile:

```
{
  "templateId": "Quest:wargames_dailyquest_anomaly_with_explode_stonewood",
  "attributes": {
    "creation_time": "2023-04-09T05:57:19.584Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-09T05:57:19.584Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1,
    "quest_pool": "dailywargamesstonewood_01"
  },
  "quantity": 1
}
```

<br><br>
Item 4452a10e-2907-4c14-a66e-1de53b9f62c2 has been added to the profile:

```
{
  "templateId": "Quest:daily_discovery_industriallocations",
  "attributes": {
    "creation_time": "2023-04-09T05:57:19.586Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-09T05:57:19.586Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1
  },
  "quantity": 1
}
```

<br><br>
Item 1e5200c9-7b10-4591-890b-9b1a20518816 has been added to the profile:

```
{
  "templateId": "Quest:weeklyquest_tiered_completemissionalerts_t04",
  "attributes": {
    "creation_time": "2023-04-09T05:57:19.584Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-09T05:57:19.584Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1,
    "quest_pool": "weeklyquestroll_02"
  },
  "quantity": 1
}
```

<br><br>
Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-08T17:19:52.592Z",
  "dailyQuestRerolls": 1,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "starlightdailyquest_01",
        "nextRefresh": "2023-04-09T17:19:52.591Z",
        "rerollsRemaining": 1,
        "questHistory": []
      }
    ],
    "dailyLoginInterval": "2023-04-08T17:19:52.592Z",
    "poolLockouts": {
      "poolLockouts": []
    }
  }
}
```

to:

```
{
  "dailyLoginInterval": "2023-04-09T05:57:19.585Z",
  "dailyQuestRerolls": 1,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-10T05:57:19.582Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-10T05:57:19.583Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_02",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t04"
        ]
      },
      {
        "poolName": "starlightdailyquest_01",
        "nextRefresh": "2023-04-10T05:57:19.584Z",
        "rerollsRemaining": 1,
        "questHistory": []
      }
    ],
    "dailyLoginInterval": "2023-04-09T05:57:19.584Z",
    "poolLockouts": {
      "poolLockouts": [
        {
          "lockoutName": "Weekly"
        }
      ]
    }
  }
}
```

<br><br>
