## Comparison for the campaign profile, rvn: [3020](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/3020%20campaign.json)-[3021](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/3021%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-05-02T06:17:56.413Z",
  "dailyQuestRerolls": 0,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "endurancedailyquests_11",
        "nextRefresh": "2023-05-03T06:17:56.409Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargamestwine_01",
        "nextRefresh": "2023-05-03T06:17:56.408Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_01",
        "nextRefresh": "2023-04-12T04:23:20.609Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-05-03T06:17:56.407Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "starlightdailyquest_01",
        "nextRefresh": "2023-05-03T06:17:56.412Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-05-04T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t10"
        ]
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-05-03T06:17:56.406Z",
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
        "poolName": "weeklyquestroll_02",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t04"
        ]
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-05-03T06:17:56.404Z",
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
        "nextRefresh": "2023-05-03T06:17:56.407Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-05-04T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-05-02T06:17:56.413Z",
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
  "dailyLoginInterval": "2023-05-02T06:17:56.413Z",
  "dailyQuestRerolls": 0,
  "objectiveDeferral": {
    "key": "25676cc3f3044c20919a0ff3f7e60b14",
    "instigationTime": "2023-05-02T12:27:47.863Z"
  },
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "endurancedailyquests_11",
        "nextRefresh": "2023-05-03T06:17:56.409Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargamestwine_01",
        "nextRefresh": "2023-05-03T06:17:56.408Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "endurancedailyquests_01",
        "nextRefresh": "2023-04-12T04:23:20.609Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-05-03T06:17:56.407Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "starlightdailyquest_01",
        "nextRefresh": "2023-05-03T06:17:56.412Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-05-04T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t10"
        ]
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-05-03T06:17:56.406Z",
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
        "poolName": "weeklyquestroll_02",
        "nextRefresh": "2023-04-13T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t04"
        ]
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-05-03T06:17:56.404Z",
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
        "nextRefresh": "2023-05-03T06:17:56.407Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-05-04T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-05-02T06:17:56.413Z",
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
