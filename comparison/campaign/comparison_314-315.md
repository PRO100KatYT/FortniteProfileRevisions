## Comparison for the campaign profile, rvn: [314](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/314%20campaign.json)-[315](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/315%20campaign.json)

Object quest_manager in the profile's stats has been changed from:

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

to:

```
{
  "dailyLoginInterval": "2023-04-09T05:57:19.585Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "c223cf9c488b46db85364dcc726357a6",
    "instigationTime": "2023-04-09T07:18:23.042Z"
  },
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