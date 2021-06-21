## 2021-06-21 testing setup on macOS

1. Git previously installed from a .dmg file (need to find source for that)
2. GitHub Desktop installed; signed in; repo cloned
3. try to Push from Obsidian (to see what happens)
	- erased the system gitconfig that specified credential.helper = oskeychain

testing now ....

Failed as expected with could not read username error

4. Downloaded the MSFT Git-Credential-Manager-core package.
   - the .pkg file needs to be opened explicitly to over-ride the macOS security block
5. This works the same way GCM-core works in Windows10: it brings up a dialog box directing user to GitHub in the browser to enable authorization.
6.  Once completed Obsidian:Git is able to push changes.





