This script was created in collaboration with <a href="https://forums.macrumors.com/members/croaker_1.1272537/">@croaker_1</a> and <a href="https://forums.macrumors.com/members/prbsparx.1272724/">@prbsparx</a> on the MacRumors forum:
https://forums.macrumors.com/threads/mojave-security-update-2021-004.2297615

It is intended as a temporary workaround to the AD Authentication issue introduced by Mojave Security Update 2021-004 and Catalina Security Update 2021-003.
The update appears to have caused an issue with accessing the Heimdal Credential Cache Server.
According to <a href="https://tidbits.com/watchlist/security-update-2021-003-catalina-and-2021-004-mojave/">commenter @stottm on tidbits.com</a>, symptoms of this issue include:
  - System Prefs Unlock Hangs
  - SMB / AFP Shares will hang
  - Screen cannot be unlocked force reboot required
  - Azure login may not work
  - NoMAD won’t load

This script was written to be deployed as a payloadless pkg through Munki, but it should work with other deployment methods.
