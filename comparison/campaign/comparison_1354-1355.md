## Comparison for the campaign profile, rvn: [1354](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1354%20campaign.json)-[1355](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1355%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-14T03:58:23.450Z",
  "dailyQuestRerolls": 1,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-04-20T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t10"
        ]
      },
      {
        "poolName": "endurancedailyquests_01",
        "nextRefresh": "2023-04-12T04:23:20.609Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-15T03:58:23.446Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-15T03:58:23.448Z",
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
        "nextRefresh": "2023-04-15T03:58:23.449Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-04-15T03:58:23.445Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_05",
        "nextRefresh": "2023-04-15T03:58:23.449Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_03",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t04"
        ]
      },
      {
        "poolName": "dailywargamesplankerton_01",
        "nextRefresh": "2023-04-15T03:58:23.447Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-04-20T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-04-14T03:58:23.450Z",
    "poolLockouts": {
      "poolLockouts": [
        {
          "lockoutName": "EnduranceDaily"
        }
      ]
    }
  }
}
```

to:

```
{
  "dailyLoginInterval": "2023-04-14T03:58:23.450Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "cae3a50ba7f34d2796f322e2b73fa86b",
    "instigationTime": "2023-04-14T15:56:20.291Z"
  },
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-04-20T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t10"
        ]
      },
      {
        "poolName": "endurancedailyquests_01",
        "nextRefresh": "2023-04-12T04:23:20.609Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-15T03:58:23.446Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-15T03:58:23.448Z",
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
        "nextRefresh": "2023-04-15T03:58:23.449Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-04-15T03:58:23.445Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_05",
        "nextRefresh": "2023-04-15T03:58:23.449Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_03",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t04"
        ]
      },
      {
        "poolName": "dailywargamesplankerton_01",
        "nextRefresh": "2023-04-15T03:58:23.447Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-04-20T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-04-14T03:58:23.450Z",
    "poolLockouts": {
      "poolLockouts": [
        {
          "lockoutName": "EnduranceDaily"
        }
      ]
    }
  }
}
```

<br><br>
