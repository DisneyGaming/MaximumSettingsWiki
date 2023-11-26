---
hide:
  - navigation
---
# FAQ
This page will act as a place for questions which are asked frequently which have answers set in stone with little to no change in the answer.

## What is a MaximumSettings Machine?
---
A MaximumSettings machine is a machine which you can access over the cloud via Moonlight to play all your games on a mobile device or a less powered computer at a cheaper cost than buying a computer.

## How does it Work?
---
MaximumSettings Hosts the machines in Ontario, Canada where the machines are all linked together via a virtualisation software called Proxmox. Proxmox is what assigns a user their machine for the time as you use different machines whilst keeping all your data.

## Whats the Difference between Bare Metal and Virtualisation?
---
With bare metal your computer is its own, all the hardware is what it is reported to be and will act as if its a computer you have purchased from the internet to your door. Virtualisation allows for computers to pool together to make a node in which a user can pick any one computer and boot from it. This allows for users to use different Computers at MaximumSettings. This can lead to differences between performance as a virtualised computer will use less negligible performance as it is running an operating system within an operating system. And allows for more freedom with a virtualised computer as you have the ability to install different operating systems without risking damage to the host itself.

### Does this impact my gaming performance?
---
Using a virtualised cloud machine does cause performance issues but not in the way you may think. The primary problem with gaming on a Virtualised Gaming Cloud service is Anti-Cheats. Anti-Cheats use different tools and checks to make sure a player isn't exploiting a game to benefit themselves at the cost of other players enjoyment. They can do this by scanning the computer for cheat files to checking windows itself to see if its been tampered with to load cheats. The problem with virtualisation is that as the hardware is virtualised it becomes difficult to verify the legitimacy of the software and hardware. This is why most anti-cheats don't and won't support virtualised computers and some are made to go against virtualised software. This stops certain games from working with MXS and other cloud computing companies.
