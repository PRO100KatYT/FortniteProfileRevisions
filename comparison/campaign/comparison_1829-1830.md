## Comparison for the campaign profile, rvn: [1829](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1829%20campaign.json)-[1830](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/1830%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-21T04:04:38.761Z",
  "dailyQuestRerolls": 0,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-04-27T00:00:00.000Z",
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
        "nextRefresh": "2023-04-22T04:04:38.756Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
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
        "nextRefresh": "2023-04-22T04:04:38.758Z",
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
        "nextRefresh": "2023-04-22T04:04:38.760Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-04-22T04:04:38.755Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_05",
        "nextRefresh": "2023-04-22T04:04:38.759Z",
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
        "nextRefresh": "2023-04-22T04:04:38.757Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-04-27T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-04-21T04:04:38.760Z",
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
  "dailyLoginInterval": "2023-04-21T04:04:38.761Z",
  "dailyQuestRerolls": 0,
  "objectiveDeferral": {
    "key": "299465b3c08641ef812db7998e7a08bb",
    "instigationTime": "2023-04-21T17:32:20.386Z"
  },
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-04-27T00:00:00.000Z",
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
        "nextRefresh": "2023-04-22T04:04:38.756Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest",
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
        "nextRefresh": "2023-04-22T04:04:38.758Z",
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
        "nextRefresh": "2023-04-22T04:04:38.760Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-04-22T04:04:38.755Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_05",
        "nextRefresh": "2023-04-22T04:04:38.759Z",
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
        "nextRefresh": "2023-04-22T04:04:38.757Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-04-27T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-04-21T04:04:38.760Z",
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
