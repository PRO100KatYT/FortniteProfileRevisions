## Comparison for the campaign profile, rvn: [3436](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/3436%20campaign.json)-[3437](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/3437%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-05-26T14:38:46.601Z",
  "dailyQuestRerolls": 1,
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
        "nextRefresh": "2023-05-27T14:38:46.592Z",
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
        "nextRefresh": "2023-05-27T14:38:46.591Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "starlightdailyquest_01",
        "nextRefresh": "2023-05-27T14:38:46.599Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-06-01T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t10",
          "Quest:weeklyquest_tiered_completemissionalerts_t10"
        ]
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-05-27T14:38:46.590Z",
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
        "poolName": "endurancedailyquests_15",
        "nextRefresh": "2023-05-27T14:38:46.593Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "hordev3dailyquests_01",
        "nextRefresh": "2023-05-27T14:38:46.597Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-05-27T14:38:46.588Z",
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
        "nextRefresh": "2023-05-27T14:38:46.591Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-06-01T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06",
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-05-26T14:38:46.601Z",
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
  "dailyLoginInterval": "2023-05-26T14:38:46.601Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "19480abae11b4b6790fc38f24d6684cb",
    "instigationTime": "2023-05-26T14:53:34.232Z"
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
        "nextRefresh": "2023-05-27T14:38:46.592Z",
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
        "nextRefresh": "2023-05-27T14:38:46.591Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "starlightdailyquest_01",
        "nextRefresh": "2023-05-27T14:38:46.599Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_09",
        "nextRefresh": "2023-06-01T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t10",
          "Quest:weeklyquest_tiered_completemissionalerts_t10"
        ]
      },
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-05-27T14:38:46.590Z",
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
        "poolName": "endurancedailyquests_15",
        "nextRefresh": "2023-05-27T14:38:46.593Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "hordev3dailyquests_01",
        "nextRefresh": "2023-05-27T14:38:46.597Z",
        "rerollsRemaining": 0,
        "questHistory": []
      },
      {
        "poolName": "dailywargamescanny_01",
        "nextRefresh": "2023-05-27T14:38:46.588Z",
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
        "nextRefresh": "2023-05-27T14:38:46.591Z",
        "rerollsRemaining": 1,
        "questHistory": []
      },
      {
        "poolName": "weeklyquestroll_04",
        "nextRefresh": "2023-06-01T00:00:00.000Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:weeklyquest_tiered_completemissionalerts_t06",
          "Quest:weeklyquest_tiered_completemissionalerts_t06"
        ]
      }
    ],
    "dailyLoginInterval": "2023-05-26T14:38:46.601Z",
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
