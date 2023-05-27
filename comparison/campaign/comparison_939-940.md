## Comparison for the campaign profile, rvn: [939](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/939%20campaign.json)-[940](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/940%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-11T04:23:20.612Z",
  "dailyQuestRerolls": 1,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "endurancedailyquests_01",
        "nextRefresh": "2023-04-12T04:23:20.609Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-12T04:23:20.606Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-12T04:23:20.608Z",
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
        "nextRefresh": "2023-04-12T04:23:20.611Z",
        "rerollsRemaining": 1,
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
        "nextRefresh": "2023-04-12T04:23:20.607Z",
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
    "dailyLoginInterval": "2023-04-11T04:23:20.612Z",
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
  "dailyLoginInterval": "2023-04-11T04:23:20.612Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "261693b1031f44948540fcd0b9c40784",
    "instigationTime": "2023-04-11T06:21:53.950Z"
  },
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "endurancedailyquests_01",
        "nextRefresh": "2023-04-12T04:23:20.609Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-12T04:23:20.606Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-12T04:23:20.608Z",
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
        "nextRefresh": "2023-04-12T04:23:20.611Z",
        "rerollsRemaining": 1,
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
        "nextRefresh": "2023-04-12T04:23:20.607Z",
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
    "dailyLoginInterval": "2023-04-11T04:23:20.612Z",
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
