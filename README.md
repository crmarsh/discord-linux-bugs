# discord-linux-bugs
A project that tracks some of the bugs in Discord's canary builds. There is also a [Discord server](https://discord.gg/discord-testers) for people who want to be involved with reporting bugs.

### Downloads
- [.deb file](https://discordapp.com/api/download/canary?platform=linux)
- [.tar.gz file](https://discordapp.com/api/download/canary?platform=linux&format=tar.gz)

### Changes

#### 0.0.12
- Using ALSA doesn't also use 100% of a cpu core now.
- Some other crash fixes

#### 0.0.11
- Fixed a couple splash screen bugs
- Put Discord in the window title again
- Fixed a crash or three
- Maybe get volume right more often
- Wonder how many bullet points I can get out of a dozen lines of code
- Turns out: 6

#### 0.0.10
- Upgraded electron
- Tweaked a networking thing

#### 0.0.9
- Added back in splash screen you never knew you needed
- Like a million new versions of chrome
- Built in a new way that probably doesn't matter to you
- Initial versions of RPC and contact syncing
- Less stablility
- A crash fix for WebRTC
- Oh shit, it's been thousands of commits since the last release, I'm not reading all of this

#### 0.0.8
- Fixed [bug](https://github.com/crmarsh/discord-linux-bugs/issues/35) in more cases

#### 0.0.7
- Took another stab at crash bug
- Fixed up crash reporting so I can tell when I've failed
- upgraded webrtc

#### 0.0.6
- Revised game detection to stop trying to detect ways to crash

#### 0.0.5
- Fixed [a crash](https://github.com/crmarsh/discord-linux-bugs/issues/21)

#### 0.0.4
- Initial version of game detection
- Idle timer is watching you slack off
- Probably other stuff, who has time to `git log`?
