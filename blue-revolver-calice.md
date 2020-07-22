---
layout: default
title: Blue Revolver Calice FAQ
---

Since BLUE REVOLVER is one of the games on [Calice Cup Special 2020](https://calice.snowcrash.fun/tournaments/4), I thought I'd write a FAQ going over some gameplay intricacies. A great companion read from the perspective of a WR-paced player is [marus' system11 guide](https://shmups.system11.org/viewtopic.php?f=5&t=59055), so give that a look too. This is focused on small gameplay insights I can give as the programmer.

### What are the scoring fundamentals?

The "Flourish" system is the bread and butter scoring mechanic. Your standard/autofire builds up to an 8-hit chain. When you have a chain of any value active, using the Special Weapon activates what is internally called "Flourish Mode". The chain timer is instantly reset to full and the value is locked -- all enemies destroyed with Special Weapon during this period yield up to 64 times their value depending on the value of your chain. *Simply put, build up a chain with your regular shot and cash it in with your special weapon on lucrative targets. More dangerous enemies are generally more lucrative.*

The "Break" system is the main scoring mechanic for bosses. There are 32 Break bonuses which are small, bespoke "tricks" - generally destroying things in quick succession, destroying specific targets or avoiding them entirely. The game hints at them and offers an in-game video tutorial - I have also supplied a plain-language guide [here](http://bluerevolvergame.com/breakguide/).

A tertiary scoring mechanic is boss cancels. On completion of a boss phase, all bullets on screen are turned into point items. This actually follows the special weapon rules, so if you can somehow build an 8-chain, you will be rewarded. 

### How does rank work? (Hyper)

Rank has an internal variable and one of five Rank Levels that is derived from that. Enemy patterns become harder based on the Rank Level.

Rank increases more or less linearly with scoring, and there is a per-frame rank increase depending on the stage the player is on. On player death, it is either halved or reset to RL3, whichever is higher. **Badly Explained Mechanic:** At Rank Level 5 on Hyper mode, the rank slowly drains back down to RL4, then fills back up to 5. This drain is faster if the player has less than 3 lives remaining, and faster still if the player is on their last life.

On default settings, the Rank appears on the top of the screen as a small bar which changes colour with Rank Level. It is intended to be a mechanic that "eases up" on the player and adds variance rather than something you should manage.

Rank only affects enemy patterns and has no bearing on things like health, though with high rank comes a higher scoring potential due to boss phase cancels and generating ammo with bombs.

### What are the recommended loadouts?

* Val-Follow is the meta shot type due to its flexibility and its DPS being 10% higher than it was intended to be.
* Mae's follow shot is quite strange but can be extremely accurate for small targets.
* Either Power shot is fine. The wide shots are rather weak in unfocused mode, but have similar DPS to Power shot in focused fire. (This was the wrong way to balance these...)

* Val-Cluster is the meta special weapon. It deals solid damage and takes advantage of a small scoring trick, but is relatively hard to use. It's sliiightly better than Mae's Cluster, but not by a massive amount.
* Mae-Laser is easy to use and has surprising scoring potential, but ammo management is difficult.
* High damage special weapons are preferred by players due to the last stage featuring multiple midbosses. WR pace speedkills these bad boys so that more enemies are spawned in their place, you may not have the resources to do that.
* Val-Caster is very safe and easy to use, but has somewhat limited potential.
* Val-Stasis has surprising potential if you're a psycho.
* I'll give you a big kiss if you play the game with the comparatively weak Mae-Lancer weapon. It is quite flexible, and certainly efficient, but the damage is generally regarded as being a bit too low.

### Bombs? Suicides?

Bombs are an incredibly powerful tool in BLUE REVOLVER, and I have a philosophy of no stage bonuses rewarding you for hoarding such things. They can be used defensively for 6 entire seconds of invulnerability. They generate special ammo by cancelling enemy bullets. They can be used to reset the chain timer in and out of Flourish mode, and act like special weapons for the sake of generating point items without activating Flourish Mode. They even have a Touhou-style 2-frame counterbomb window, though the game doesn't acknowledge this unless you have a debug window up.

Your lives are a resource to spend. Dying will grant two bombs (without discarding whatever bombs you had in stock), half a bar of ammo and the standard 6 seconds of invuln. You should consider taking a death before key moments to refill resources and make the rank go easy on you.

### Tell me some things I don't know about the game?

* All bullets in the game have a 2x2 collision box, the same size as your own hitbox. I aimed to tune the collision for such things as forgiving as it could possibly be without being completely ridiculous.
* The stage 1 midboss doesn't actually move when it recoils from a wing being destroyed, the sprite is just offset from the collision data. This was to make it fairly easy to score the first Break bonus and feel like a king, but man I feel like a damn fraud every time I look at those hitboxes.
* Mae-Laser is the most complicated special weapon in terms of weird mechanics. It grants the player additional item suction power, every enemy constantly tracks and worries about whether the laser will pierce it, etc etc.
* It was truly and utterly intentional to not give the player basically any ammo during stages 3 and 5. I am unrepentant.
* My favourite boss phase is boss 3's final phase, "OVERTIME". I am a big fan of gravity bullets and straight beams.
* The names for boss phases VDM-86 and MDR-720 are derived from my poor understanding of French internet slang. VDM = fuck my life, MDR = dying of laughter.
* While I will not say here the various horrible phrases that the scoreboard will censor, "DSP" is among them. 
* One enemy in stage 2 used to do something really goofy if you let it time out, now it simply immediately disappears.
* I tried to very carefully tune the game s.t. it would have a 150 million point score potential, since I thought it was a nice number. However, the actual score potential of the game turned out to be somewhere between 190-200 million points. Take from this what you will.
* If you can somehow score about 100 septillion points, the game will grant you infinite lives due to inelegant programming. がんばって！
* When woof asked what stage 1 should look like, I told him to do the first stage of DoDonPachi. The prevalence of ground enemies and the very clear "paths" through the stage through which to anticipate enemies make it very beginner friendly.

### DOUBLE ACTION?

Delayed due to mental health issues. I'm sorry. Please enjoy the OST we patched into the game recently at least.