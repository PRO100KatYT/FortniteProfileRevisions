## Comparison for the campaign profile, rvn: [8](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/8%20campaign.json)-[10](https://github.com/PRO100KatYT/FortniteProfileRevisions/tree/main/profiles/campaign/10%20campaign.json)

Object quest_state in 69efee8b-ea9d-44d9-81c5-07de692358c2 (Quest:achievement_craftfirstweapon) has been changed from: `"Completed"` to: `"Claimed"`
<br><br>
Object last_state_change_time in 69efee8b-ea9d-44d9-81c5-07de692358c2 (Quest:achievement_craftfirstweapon) has been changed from: `"2023-04-08T17:09:50.314Z"` to: `"2023-04-08T17:09:55.523Z"`
<br><br>
Object quest_state in b7680072-1ad8-46bc-b446-ea996bb33240 (Quest:achievement_protectthesurvivors) has been changed from: `"Completed"` to: `"Claimed"`
<br><br>
Object last_state_change_time in b7680072-1ad8-46bc-b446-ea996bb33240 (Quest:achievement_protectthesurvivors) has been changed from: `"2023-04-08T17:09:50.314Z"` to: `"2023-04-08T17:09:55.523Z"`
<br><br>
Item d353f5a4-d33c-41e2-8be2-dfefc1bc37e2 has been added to the profile:

```
{
  "templateId": "ConditionalAction:generic_instance",
  "attributes": {
    "alt_profile_types": [
      "athena"
    ],
    "_private": true,
    "devName": "MAJOR: Spring - Lobby",
    "conditions": {
      "event": {
        "instanceId": "h8f6km3ecc38jgl88ok8qs690q[0]0",
        "eventName": "CalendarEvent_Persistent_LobbyStW_Adventure",
        "eventStart": "2023-04-06T00:00:00.000Z",
        "eventEnd": "2023-06-22T00:00:00.000Z",
        "startActions": {
          "hasRun": true,
          "conversions": [],
          "itemsToGrant": [],
          "questsToUnpause": []
        },
        "endActions": {
          "hasRun": false,
          "conversions": [],
          "itemsToRemove": [],
          "questsToPause": []
        },
        "metaData": {}
      }
    }
  },
  "quantity": 1
}
```

<br><br>
Item 487e9d5b-790a-4cd3-945c-23b21da9c81d has been added to the profile:

```
{
  "templateId": "ConditionalAction:generic_instance",
  "attributes": {
    "alt_profile_types": [
      "athena"
    ],
    "_private": true,
    "devName": "STORE: Spring - Event - Campaign Currency",
    "conditions": {
      "event": {
        "instanceId": "pfl4nvop92r8fa801837fl1k1m[0]0",
        "eventName": "CalendarEvent_Persistent_Pirate_EventCurrency",
        "eventStart": "2023-04-06T00:00:00.000Z",
        "eventEnd": "2023-06-22T00:00:00.000Z",
        "startActions": {
          "hasRun": true,
          "conversions": [],
          "itemsToGrant": [],
          "questsToUnpause": [],
          "eventCurrencyToSet": {
            "templateId": "AccountResource:eventcurrency_adventure",
            "cf": 1.0
          }
        },
        "endActions": {
          "hasRun": false,
          "conversions": [
            {
              "recipe": {
                "static_results": [
                  {
                    "templateId": "CardPack:cardpack_event_persistent_pirate",
                    "quantity": 1
                  }
                ],
                "static_costs": [
                  {
                    "templateId": "AccountResource:eventcurrency_adventure",
                    "quantity": 500
                  }
                ],
                "static_catalysts": []
              },
              "quantity": -1,
              "convert_remainder_up": true
            }
          ],
          "itemsToRemove": [],
          "questsToPause": [],
          "eventCurrencyToUnset": "AccountResource:eventcurrency_adventure"
        },
        "metaData": {}
      }
    }
  },
  "quantity": 1
}
```

<br><br>
Item 384b6443-66f3-470d-82b2-624e042b4e74 has been added to the profile:

```
{
  "templateId": "ConditionalAction:generic_instance",
  "attributes": {
    "alt_profile_types": [
      "athena"
    ],
    "_private": true,
    "devName": "MAJOR: Spring - Phoenix",
    "conditions": {
      "event": {
        "instanceId": "5eaheh65uclrj0bkuscljchdec[0]0",
        "eventName": "CalendarEvent_Persistent_Phoenix_Adventure",
        "eventStart": "2023-04-06T00:00:00.000Z",
        "eventEnd": "2023-06-22T00:00:00.000Z",
        "startActions": {
          "hasRun": true,
          "conversions": [],
          "itemsToGrant": [
            {
              "templateId": "Weapon:wid_edged_sword_light_c_ore_t01",
              "quantity": 1
            },
            {
              "templateId": "Weapon:wid_pistol_sixshooter_c_ore_t01",
              "quantity": 1
            },
            {
              "templateId": "Ammo:ammodatabulletsmedium",
              "quantity": 40
            }
          ],
          "questsToUnpause": []
        },
        "endActions": {
          "hasRun": false,
          "conversions": [],
          "itemsToRemove": [
            {
              "templateId": "AccountResource:phoenixxp",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:technology_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:resistance_team_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:fortitude_team_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:offense_team_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:technology_team_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:fortitude_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:offense_phoenix",
              "quantity": 2147483647
            },
            {
              "templateId": "Stat:resistance_phoenix",
              "quantity": 2147483647
            }
          ],
          "questsToPause": []
        },
        "metaData": {
          "grantTo": "theater2",
          "phoenixEventType": "EventFlag.Phoenix.Adventure",
          "endAction": "{\"actionClassName\":\"com.epicgames.fortnite.core.game.managers.calendareventactions.ResetSeasonalTheaterCalendarEventAction\",\"profile\":\"campaign\"}"
        }
      }
    }
  },
  "quantity": 1
}
```

<br><br>
Object event_currency has been added to the profile's stats with the following value:

```
{
  "templateId": "AccountResource:eventcurrency_adventure",
  "cf": 1.0
}
```

<br><br>
