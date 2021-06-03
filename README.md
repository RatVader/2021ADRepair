This script was created in collaboration with @croaker_1 and @prbsparx on the MacRumors forum:
https://forums.macrumors.com/threads/mojave-security-update-2021-004.2297615

It is intended as a temporary workaround to the AD Authentication issue introduced by Mojave Security Update 2021-004 and Catalina Security Update 2021-003.
The update appears to have caused an issue with accessing the Heimdal Credential Cache Server.
According to commenter @stottm on tidbits.com, symptoms of this issue include:
  - System Prefs Unlock Hangs
  - SMB / AFP Shares will hang
  - Screen cannot be unlocked force reboot required
  - Azure login may not work
  - NoMAD won’t load

This script was written to be deployed as a payloadless pkg through Munki, but it should work with other deployment methods.
