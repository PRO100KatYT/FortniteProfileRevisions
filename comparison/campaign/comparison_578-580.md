## Comparison for the campaign profile, rvn: [578](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/578%20campaign.json)-[580](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/580%20campaign.json)

Item 94538fe4-0f28-4f92-8413-dba1ed4790fc (Quest:starlightquest_daily_complete_d4) has been removed from the profile.
<br><br>
Item c61a881f-80ee-46a2-bf3a-308bca3e4c63 (Quest:wargames_completedailyquest) has been removed from the profile.
<br><br>
Item 47bb5bc2-1975-4e75-a970-5b099e527a15 (Quest:wargames_dailyquest_anomaly_with_explode_stonewood) has been removed from the profile.
<br><br>
Object quest_pool in 1e5200c9-7b10-4591-890b-9b1a20518816 (Quest:weeklyquest_tiered_completemissionalerts_t04) has been changed from: `"weeklyquestroll_02"` to: `"weeklyquestroll_03"`
<br><br>
Item 80453adc-504c-44da-abae-77651283f7e6 has been added to the profile:

```
{
  "templateId": "Quest:starlightquest_daily_complete_d3",
  "attributes": {
    "creation_time": "2023-04-10T04:58:56.291Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-10T04:58:56.291Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1,
    "quest_pool": "starlightdailyquest_01"
  },
  "quantity": 1
}
```

<br><br>
Item 5905f092-aead-4d6f-a51a-1b503dcb8e56 has been added to the profile:

```
{
  "templateId": "Quest:daily_discovery_urbanlocations",
  "attributes": {
    "creation_time": "2023-04-10T04:58:56.293Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-10T04:58:56.293Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1
  },
  "quantity": 1
}
```

<br><br>
Item 47a0660e-d7c4-47d0-81ce-dadd0c2df4ff has been added to the profile:

```
{
  "templateId": "Quest:wargames_dailyquest_lava_with_explode_stonewood",
  "attributes": {
    "creation_time": "2023-04-10T04:58:56.290Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-10T04:58:56.290Z",
    "level": -1,
    "quest_rarity": "uncommon",
    "xp_reward_scalar": 1,
    "quest_pool": "dailywargamesstonewood_01"
  },
  "quantity": 1
}
```

<br><br>
Item d322c3a1-825b-4809-b1f1-55c1748a235d has been added to the profile:

```
{
  "templateId": "Quest:wargames_completedailyquest",
  "attributes": {
    "creation_time": "2023-04-10T04:58:56.289Z",
    "quest_state": "Active",
    "last_state_change_time": "2023-04-10T04:58:56.289Z",
    "level": -1,
    "quest_rarity": "legendary",
    "xp_reward_scalar": 1,
    "quest_pool": "dailywargameschallenge_01"
  },
  "quantity": 1
}
```

<br><br>
Object quest_manager in the profile's stats has been changed from:

```
{
  "dailyLoginInterval": "2023-04-09T05:57:19.585Z",
  "dailyQuestRerolls": 1,
  "objectiveDeferral": {
    "key": "952669711f4544519a7df949d30ef632",
    "instigationTime": "2023-04-09T18:25:53.179Z"
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

to:

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

<br><br>
