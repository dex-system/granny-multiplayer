Alright, here's a full, gritty, developer-style `README.md` for a "Granny Multiplayer" project.  



It's written in a rough, "I-coded-this-at-3am" tone—no corporate polish, just straight talk about netcode, bugs, and why the hell this exists.  



\---



```markdown

\# granny-multiplayer  

\### \*because one granny wasn't enough to ruin your day\*  



!\[GitHub last commit](https://img.shields.io/github/last-commit/yourname/granny-multiplayer)  

!\[GitHub repo size](https://img.shields.io/github/repo-size/yourname/granny-multiplayer)  

!\[Discord](https://img.shields.io/discord/123456789?label=discord\&color=5865F2)  



\---



\## what the hell is this  



This is a \*\*multiplayer horror survival\*\* thing where you and up to 5 other idiots try to escape a house while a creepy old lady hunts you down.  

Inspired by that one mobile game everyone played in 2018, but now with \*\*netcode that actually works\*\* (most of the time).  



I built this because:  

\- I wanted to play Granny with friends without passing a phone around.  

\- All existing "multiplayer" mods were janky as hell.  

\- I had too much free time and not enough self-respect.  



\---



\## current state (be real)  



| Feature | Status |

|---------|--------|

| Lobby system | ✅ working (barely) |

| In-game chat | ✅ yes, with profanity filter off by default |

| Granny AI | 🟡 pathfinding works, but she gets stuck on chairs sometimes |

| Item spawns | ✅ randomized each round |

| Escape mechanics | ✅ car, boat, helicopter — all functional |

| Synced animations | 🟡 80% there, arms look weird when crouching |

| Dedicated server | ❌ not yet, uses P2P for now (sorry) |



> \*\*Known issue\*\*: If Granny clips through a wall, just run. She'll reset. Probably.  



\---



\## how to play  



\### controls (default)  



```

WASD  – move  

E     – interact / pick up  

Shift – run (makes noise – she hears you)  

Ctrl  – crouch (quiet but slow)  

Q     – drop item  

R     – reload (if you find a gun, lol)  

T     – text chat  

V     – voice chat (push-to-talk)  

```



\### objective  



1\. Find \*\*5 keys\*\* hidden somewhere in the house.  

2\. Unlock the escape route (car/boat/helicopter).  

3\. Get the hell out before Granny turns you into a rug.  



\*\*Extra\*\*: You can stun Granny with a vase or a frying pan – but only for \*\*4 seconds\*\*. Use it wisely.  



\---



\## building from source (if you're brave)  



```bash

git clone https://github.com/yourname/granny-multiplayer.git  

cd granny-multiplayer  

```



\### dependencies  

\- Unity 2022.3 LTS (or newer, but no promises)  

\- Mirror Networking (included via manifest)  

\- Steamworks.NET (if you want Steam lobbies)  



\### steps  

1\. Open in Unity.  

2\. Let it compile (go grab a coffee).  

3\. Open `Scenes/MainMenu.unity`.  

4\. Hit Play – you'll get a local host.  

5\. Build with `File > Build Settings > PC/Mac`.  



> If you get pink textures, re-import the `Assets/Textures` folder. Unity does that sometimes.  



\---



\## roadmap (things i might actually do)  



\- \[ ] Dedicated server build (so you don't rely on host's WiFi)  

\- \[ ] More maps (maybe a haunted hospital?)  

\- \[ ] Custom skins (because why not)  

\- \[ ] Replay system (to laugh at your friends dying)  

\- \[ ] Fix Granny's "moonwalk" glitch – it's funny but immersion-breaking  



\---



\## contributing  



If you want to help:  

1\. Fork it.  

2\. Make a branch with a \*\*stupid name\*\* like `fix-granny-teleport`.  

3\. Open a PR with a description that actually makes sense.  



I'll review it when I'm not busy crying over netcode.  



\---



\## credits  



\- \*\*Granny model\*\* – ripped and re-rigged (don't tell the original devs)  

\- \*\*Sound effects\*\* – from freesound.org + my own terrible voice acting for grunts  

\- \*\*Networking\*\* – Mirror docs and a lot of StackOverflow  



\---



\## license  



MIT – do whatever you want, just don't blame me if your PC catches fire.  



\---



\## last words  



This is a \*\*passion project\*\*, not a AAA title.  

If you find a bug, \*\*tell me\*\* – but also tell me how to reproduce it, or I'll ignore you.  



Join our \[Discord](https://discord.gg/yourlink) if you wanna play test or just yell at me.  



\*\*Peace.\*\*  

— \*some guy who spent way too many nights on this\*  

```

