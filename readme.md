# Better Buff Bar

Track only the buffs that actually matter.

![Better Buffs Bar](./BetterBuffsBar.png)

## Installation

To install Better Buff Bar copy & paste this link into your browser:
alt1://addapp/https://nadyanayme.github.io/BetterBuffsBar/dist/appconfig.json

**Currently only works with Small Buff icons**. Alt1's BuffReader only works with small buff icons so this is unlikely to change soon.

- Drag & drop buffs into desired display order (to be sorted properly the 'Fade Inactive Buffs' setting must be toggled on)
- Select number of buffs that should appear in each row
- Decide whether buffs should disappear or turn grayscale when inactive
- Set Overlay Position
- Enable Overlay

## Features

- Track important buffs (if it isn't listed it wasn't important enough - but more seriously DM me @ NadyaNayme on Discord if you'd like to add a buff to be tracked)
- Select order that buffs should be displayed and which should be tracked. Faded buffs must first be enabled to sort them.
- Choose between fading the buff out when inactive or hiding it from the better buff bar.

## Known Issues

- Trying to update the Number of buffs per row setting can be... finnicky. :) It can take a few clicks. I'll be adding -/+ buttons instead that can be clicked to adjust reliably.
- UI Scale >100% results in it being cut off
- Rapid movement of camera can cause FSOA Buff to be detected with 120s time. FSOA detection is super fragile (matching on 15 pixels...). If someone can make a better transparent buff icon this can be improved.
- Overloads with <10s remaining can't be tracked due to the buff fading in and out. Ask a Jmod to please stop expiring buffs from doing that. Alt 1 can't track them properly. :)

If you encounter any other bugs - please submit an issue and I'll investigate it.
