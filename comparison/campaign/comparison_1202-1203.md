## Comparison for the campaign profile, rvn: [1202](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1202%20campaign.json)-[1203](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1203%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-12T04:00:42.652Z",
  "dailyQuestRerolls": 1,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
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
        "nextRefresh": "2023-04-13T04:00:42.648Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-13T04:00:42.650Z",
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
        "nextRefresh": "2023-04-13T04:00:42.651Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-04-13T04:00:42.647Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_05",
        "nextRefresh": "2023-04-13T04:00:42.651Z",
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
        "nextRefresh": "2023-04-13T04:00:42.649Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-04-12T04:00:42.652Z",
    "poolLockouts": {
      "poolLockouts": [
        {
          "lockoutName": "EnduranceDaily"
        },
        {
          "lockoutName": "Weekly"
        }
      ]
    }
  }
}
```

to:

```
{
  "dailyLoginInterval": "2023-04-12T04:00:42.652Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "0d129c807fbb4bd385b36824036955f9",
    "instigationTime": "2023-04-12T13:34:19.573Z"
  },
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
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
        "nextRefresh": "2023-04-13T04:00:42.648Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-13T04:00:42.650Z",
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
        "nextRefresh": "2023-04-13T04:00:42.651Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-04-13T04:00:42.647Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_05",
        "nextRefresh": "2023-04-13T04:00:42.651Z",
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
        "nextRefresh": "2023-04-13T04:00:42.649Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-04-12T04:00:42.652Z",
    "poolLockouts": {
      "poolLockouts": [
        {
          "lockoutName": "EnduranceDaily"
        },
        {
          "lockoutName": "Weekly"
        }
      ]
    }
  }
}
```

<br><br>
