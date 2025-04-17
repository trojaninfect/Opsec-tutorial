
# Beginner’s Guide to OPSEC (Operational Security)



Goal: Learn how to protect your identity, tools, and actions online so you don’t accidentally dox yourself.

# What is OPSEC?

"Operational Security (OPSEC) is the practice of keeping your identity, data, and intentions hidden — especially when doing sensitive activities like pentesting, OSINT, or anything off the grid."

# Digital Footprint 101

What can expose you:

Real name/email used on shady accounts

Reusing usernames or avatars

Posting screenshots with metadata

Accidentally leaking IP address

# Quick Fixes:

Use burner accounts

Never reuse usernames

Strip metadata from images (exiftool)

Use a custom avatar

# System & Network Safety

Hide Your IP:

VPN (paid > free)

Tor (for browsing, not everything)

Proxies (Socks5 for tools)

Clean System:

Use VMs (Kali, Tails, Whonix)

Don’t use your real desktop for ops

Disable telemetry & background sync

# Mobile OPSEC

Use a burner phone

Remove/disable location services

Avoid linking real SIM

Use apps like:

Signal (for private chat)

Session (no phone needed)

# Tool Usage OPSEC

Don’t clone or use tools without checking the source

Remove identifying strings in user agents/tools

Spoof MAC address during scanning (macchanger)

Monitor your outbound traffic with Wireshark

# Web & OSINT Safety

Don’t use real info for testing tools

Use sandboxed browsers (e.g., Brave + Tor)

Use isolated environments for OSINT (VM or Tails)

Block JavaScript (NoScript) to avoid fingerprinting

# Cleanup & Hygiene

Wipe logs regularly (logrotate, custom scripts)

Use secure delete (shred, sdelete)

Set up aliases for commands (e.g., rm → shred)

Don’t keep sensitive tools or files on your main machine

# What Not to Do

Don’t brag about things you did or pulled off

Don’t use your real accounts for research

Don’t stay logged in to things while doing *stuff*

Don’t trust random GitHub scripts

# Bonus: Tools to Help You 
macchanger:	Change MAC address

exiftool:	Remove metadata

torsocks:	Route tools through Tor

Proxychains:	Proxy your traffic

BleachBit:	System cleaner

Tails OS:	Bootable amnesic OS
## Authors

- [@conflicted](https://www.github.com/trojaninfect)

