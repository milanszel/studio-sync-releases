# Studio Sync 0.11.1

Studio Sync updates itself from here. To install it the first time:

* Mac: [Studio-Sync-0.11.1-Mac-x86_64.dmg](https://github.com/milanszel/studio-sync-releases/raw/main/downloads/Studio-Sync-0.11.1-Mac-x86_64.dmg)
* Windows: [Studio-Sync-Setup-0.11.1.exe](https://github.com/milanszel/studio-sync-releases/raw/main/downloads/Studio-Sync-Setup-0.11.1.exe)

## What's new

* A laptop whose clock was set more than 30 seconds off couldn't stay connected; it kept rejoining until the host blocked it with "keeps trying to join". Every laptop now uses the host's clock for its packets, so clock settings no longer matter.
* A laptop that has already proved the room code is never blocked for rejoining. Only real wrong guesses count toward the limit.
