## Comparison for the campaign profile, rvn: [585](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/585%20campaign.json)-[586](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/586%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-10T04:58:56.291Z",
  "dailyQuestRerolls": 1,
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-11T04:58:56.289Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-11T04:58:56.289Z",
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
        "nextRefresh": "2023-04-11T04:58:56.290Z",
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
      }
    ],
    "dailyLoginInterval": "2023-04-10T04:58:56.291Z",
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

to:

```
{
  "dailyLoginInterval": "2023-04-10T04:58:56.291Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "61d164ae4f764ce794aa3227a4b08bfc",
    "instigationTime": "2023-04-10T05:01:16.292Z"
  },
  "questPoolStats": {
    "poolStats": [
      {
        "poolName": "dailywargameschallenge_01",
        "nextRefresh": "2023-04-11T04:58:56.289Z",
        "rerollsRemaining": 1,
        "questHistory": [
          "Quest:wargames_completedailyquest",
          "Quest:wargames_completedailyquest"
        ]
      },
      {
        "poolName": "dailywargamesstonewood_01",
        "nextRefresh": "2023-04-11T04:58:56.289Z",
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
        "nextRefresh": "2023-04-11T04:58:56.290Z",
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
      }
    ],
    "dailyLoginInterval": "2023-04-10T04:58:56.291Z",
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