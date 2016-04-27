DON'T use this config. It' s only here to show how `config.json` can look.  

```json
{
  "config": {
    "botName": "Cat.py bot",
    "botDescription": "A cat.py bot!",
    "prefix": "%",
    "token": "token",
    "groupMode": 0
  },
  "globGroups": {
    "owners": {
      "id": 0,
      "description": "The bot owner(s). You should probably put your user ID here.",
      "globMembers": [],
    },
    "admins": {
      "id": 1,
      "description": "Bot admins have access to most commands, except for management commands.",
      "globMembers": [],
    },
    "voiced": {
      "id": 2,
      "description": "Voiced users have access to most regular commands.",
      "globMembers": [],
    },
    "all": {
      "id": 3,
      "description": "The only purpose for this group is for the ID and description.\nEverybody is part of this group."
    }
  },
  "servers": {
    "serverID": {
      "allowedChans": [],
      "allowedChansWithoutPrefix": [],
      "asleep": False,
      "groups": {
        "admins": {
          "members": [],
          "roles": []
          }
        }
      }
    }
  }
}
```
