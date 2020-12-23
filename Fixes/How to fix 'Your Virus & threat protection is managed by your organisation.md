# How to fix "Your Virus & threat protection is managed by your organisation"
You want to diable you anti-virus because it keeps deleting Øzark, but you can't, because it says "Your Virus & threat protection is managed by your organisation"? This should solve your problem, use the second guide if the first guide doesn't work cause "Windows can't find gpedit.msc".
___
### Option 1. (works with Windows Pro Edition & Windows Enterprise Edition):
1. Open Group Policy snap-in by pressing `Windows key + R` and then type `gpedit.msc`.
2. Go to `Computer Configuration > Administrative Templates > Windows Defender Security Center > Virus and threat protection`.
3. Set 'Hide the Virus and threat protection area' setting to Not Configured.

### Option 2. (for Windows Home Edition):
1. Press `Windows key + R` and type `regedit`.
2. Navigate to `HKEY_LOCAL_MACHINE > SOFTWARE > Policies > Microsoft > Windows Defender`.
3. Then select `DisableAntiSpyware`, right-click and press 'Delete'.
4. Confirm your change and you're done.
