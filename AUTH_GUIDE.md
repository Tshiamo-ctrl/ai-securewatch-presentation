# AI SecureWatch Passcodes & Auth Flow

### Active Passcodes
- **CEO:** `ceo-2026`
- **CMO:** `cmo-2026`
- **CTO:** `cto-2026`
- **Guest:** `guest-pass`

### How the Flow Works
1. **Executives (CEO, CMO, CTO):** Entering their passcode instantly unlocks the presentation. No tracking or registration required.
2. **Guests:** Entering `guest-pass` reveals an "Open Registration Form" button. 
   - They click the button, which opens the secure Google Form in a new tab.
   - After completing the form, they return to the presentation and click **"I have registered → Enter"** to unlock the site.

_Note: Passcodes can be changed at any time by editing the `PASSCODES` object at the bottom of the `securewatch-phase1-sprint-v2.html` file._
