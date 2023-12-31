# Vayne

## Quick Tips

*Aggressive and Defensive mode both remove restrictions on E usage*


**Harass + Defensive mode:** * activates Q trading logic
- *Read more about this feature below*
- *Configurable keybind*

**Combo + Defensive:** uses safer movement and Q positioning
**Combo + Aggressive:** for aggressive Q spam

Make sure to configure a keybind for the **Flash + E** mechanic

hf :D

---

## Q -

### SBTW

Spacebar-To-Win is the default configuration for new Vayne. It does everything for you, modifiers provide advanced functions.

SBTW (default) will cast Q / E for many events.  Examples include repositioning yourself with Q to condemn, situationally proccing W, engaging/chasing/spacing, and many more.

Modifier keys are used to override restrictions and safety checks.

*There are several saferty options and restrictions you can configure, but it is better to use default settings, and report any issues you have.*

---

### Modifiers

Without Modifiers, Q still casts often, but will be trying to space all the time, and has certain restrictions in place to stop you inting.
Combo mode will try and keep Vayne between 100-80% of her max range, (auto-spacing).

*Aggressive* modifier removes safety checks and will use Q a lot more haphazardly. Use aggressive mode when enemies are vulnerable / for all-in, for chasing, etc.

*Defensive* modifier removes range checks for Q, meaning you will Q out of range to escape if possible. 
By default, Q will not be cast if it will result in you being out of attack range, defensive mode overrides this.

#### **Aggressive**

- Remove Angle Restrictions for E
  - (uses Q and E without safety checks)
- Override Turret safety checks 
  - (allow Q under tower)
- Enables Q spam after AA
  - Q will be cast as an AA reset, ignoring angle restrictions.

#### **Defensive**

- Will use Q defensively, and allows Q away from target
- Cast E for proc
- Remove engage restrictions

---

### Flexible (Legacy)

The Flexible preset is much more like legacy script designs. This config relies more heavily on modifier keys to instruct the script, giving the user more control. The Flexible menu is just as complex as the SBTW, and everything can be configured how you prefer.

---

### Cursor / Cursor+Keybind
Functions similarly to Mulan Vayne. Q will be cast towards cursor. Can be configured for only with keybind, (on aggressive mode, for example)

---

### Custom

Custom preset allows the user to completely change the functionality of the script. 

---

### Q Trigger / Events

Most Events/Triggers can be configured to work conditionally in advanced menu.
Listed below are the main events, and their configuration options. SBTW settings is preconfigured with optimal settings.

| Event       | Options                                 |
|-------------|-----------------------------------------|
| Engage      | - Aggro only<br>- Limiters <br>- Angles |
| Chase       | - Aggro only<br>- Angles                |
| Reset       | - Aggro only                            |
| Proc        | - Aggro only                            |
| Wall Burst  | - Aggro only                            |
| Condemn     | - Aggro only                            |
| Kill Secure | - Aggro only                            |

---

### W

There is advanced logic for W optimization, for PvP and farming.
Target override to prioritize marked units.

Target Selector Override Logic
- Smart
- Always
- Disabled

Hold Extra Range (slider)

Range multiplier (0-1)

Angle Abort (slider)

---

## E -

E should work smoothly, report any issues.

| Orb Mode              | Effect                                                       |
|-----------------------|--------------------------------------------------------------|
| Combo + Defensive     | **E to Kill**<br>Allow E to killable enemy without any stun (only to kill tho) |
| Harass + Defensive    | **E quick combo**<br>Allow E to push back enemy without any stun to proc w (no need to kill just proc) |
| Combo / Harass + Agro | **Q+E stun**<br>Less restriction to stun <br>Less restriction to Q for stun |

---

### R

Deceive
- Stealth Handler

Automatic Q when R

Ult Handler:
- Automatic
- Custom
- Disabled

**Drawings**
- Ult duration
- Stealth duration

---
