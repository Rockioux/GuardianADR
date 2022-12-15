# Requirements
Required plugins:
* Guardian 
* Auto Demo Record (https://lone.design/product/auto-demo-record/)

# Features
Records demos for the following Guardian's Violations:
* Gravity
* Melee Rate
* NoClip
* Inside Terrain

# Configuration
Each violation config has three configurable values:
* Enable Demo Recordings for this hook: whether or not the hook is enabled and will trigger a demo recording.
* Demo Duration in minutes: duration of the demo to record.
* Discord Webhook: Webhook to use for the demo recording, if not specified it will use the default location for Auto Demo Record. 

# Default Configuration
```
{
  "Gravity Violation Demo Config": {
    "Enable Demo Recordings for this hook": true,
    "Demo Duration in minutes": 2,
    "Discord Webhook": ""
  },
  "Melee Rate Violation Demo Config": {
    "Enable Demo Recordings for this hook": true,
    "Demo Duration in minutes": 2,
    "Discord Webhook": ""
  },
  "NoClip Violation Demo Config": {
    "Enable Demo Recordings for this hook": false,
    "Demo Duration in minutes": 2,
    "Discord Webhook": ""
  },
  "InsideTerrain Violation Demo Config": {
    "Enable Demo Recordings for this hook": false,
    "Demo Duration in minutes": 2,
    "Discord Webhook": ""
  }
}
```

Credit to Pickle Brine for the awesome logo!