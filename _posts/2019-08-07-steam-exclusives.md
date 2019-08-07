---
layout: post
title: Steam exclusives
---

*Steam takes too much of my money. Every month, I see that big fat 30% revenue split go into the pockets of the company that ruined Team Fortress 2 and made the most overrated game of all time (Half-Life 2, fight me) and I can barely hold the tears back - tears that shall, truly, never hit them leather Bugatti seats at this rate.* 

For small teams, that 30% could well be what keeps them going. For Valve, it is pure ivory backscratcher money. The news that they write off part of that split for games that make $10m or more is a damned slap in the face, too - if they can give the games that surely cost their infrastructure the most some nice mates' rates, that split is obviously completely illusory at this point, and has no relationship with Steam's infrastructure costs or the value it provides.

### Epic

So I was pretty happy to hear news about the Epic Games Store's announcement. Steam's a monopoly, and as developers we have no way of even opening a conversation about this kind of thing with them. It ain't 2010 anymore, being on Steam is now simply the bare minimum expected as opposed to something that actively brings you the kind of audience you can feed yourself with.

I don't really have an interest in working with EGS (I'd prefer to work with fewer DLC launcher apps and unaccountable companies, not more), but it was my hope that their big-dick presence would give some leverage in this kind of discussion. Instead, well, obviously the worst possible thing happens -- EGS keeps poaching games and buying exclusives for a platform that's not all that great, and Valve do the big nothing in response. Since it's a fair bet that Valve want as many games as possible on their platform in order to make the most money, I believe they are relying on their userbase to, ahem, *convince developers of the value in their platform* by creating massive negative publicity - and in some rare and extreme cases, harassing/bullying folk into line.

One of the points that I see coming up is that storefront exclusivity, even timed exclusivity, is really bad for the PC games market. I don't disagree. Therefore, I have had an attempt at compiling a rough list of PC games exclusive to Steam. What's really bizarre is that it seems there hasn't ever been too much of a contemporary stink about most of these games being exclusive to a locked-down DRM platform - hell, one that's no stranger to security issues and dodgy practices. I wonder why? Surely this is anti-consumer too? Is there something I'm missing here?

### The List

Here is, at rough estimation, a list of about 3,480 PC games exclusive to the Steam platform: [Link](//danbo.vg/list-of-steam-exclusives.html)

### Methodology

I used the IsThereAnyDeal.com API - looking up all games on Steam, filtering out DLC and packages, as well as games with under 100 reviews (probably isn't fair but I wanted the list to be mostly games people might have heard of). Any game where all the "prices" the API shows are Steam-only gets in the list. This site seems to deal with every digital storefront I've heard of and tons more, and hell tons of those simply sell Steam keys, so if anything this list should be way bigger. The site naturally can't account for physical stores (and if they did, often you end up just buying a box with a Steam key inside) or direct sales via a game's homepage. Also, it seems like quite a few games have multiple seperate pages on ITAD. I don't know exactly how ITAD does its scraping, but it seems robust enough.

This is obviously not a pinpoint accurate list, but I hope it expresses my point well enough. [Python script is here if you think I bungled it](https://gist.github.com/tinydanbo/9a58e1affdba4ec390f7d5604c7f9f04). I'm not a great programmer.

### Give me the damned point already you nerd

To some small degree, the backlash about EGS is justified[^1]. Being forced to use yet another launcher app is the bad shit, and we should be shooting for none of those, not more. But, if you have to have one, there must be multiple - welcome to capitalism, it sucks, please take a seat, yes we are aware that competition doesn't actually solve much, do you prefer Pepsi or Coke? 

Valve have very carefully cultivated the image of their platform as being synonymous with the PC; the default and forever option - and they've made sure just about everyone who plays games on PC is locked into their ecosystem as much as possible. This makes it a bit of a blind spot when people start to question/criticise how they buy and play games - if a game's exclusive to Steam, then whatever, who cares, Steam is the PC, and the PC is Steam. Your friends are on Steam. All the games you bought over the last 10-15 years are on Steam. Your saves are on Steam. Your game reviews are on Steam. Your streams are on Steam. Your mods are on Steam. Your forums are on Steam. You will report to Steam every July and December for your standard-issue 30% off deals on games you don't actually want but will buy anyway. 

I don't think this is a good thing even just now, but it only gets worse down the road - Valve have the popular image of being wholly stable and idly benevolent, but eventually they will either go bust or properly turn heel, and then we're all in big trouble.

As a final note, I really dislike how small teams like the Ooblets folk are made to be the punching bag in this heavyweight bout between two massive storefronts. They bungled the hell out of their announcement, they posted cringe. Very unfortunate. Even smart, kind people can look like evil dipshits if they fuck up / overthink their PR. EGS really should provide some temporary community managers / PR staff to handle this sort of thing better. This is a fairly basic resource to provide that would curtail untold amounts of harassment and abuse -- nobody deserves [the shit that got slung](https://medium.com/@perplamps/regarding-whats-been-happening-3af0f27d863c). But I suspect EGS don't really care either - the big kerfuffle is publicity, after all. 

The gods will not save you. Stuff like itch.io might, though.

### BONUS

Here's a mystery screenshot of something I'm fucking about with. I've been wrestling with one real motherfucker of a black dog this year mentally - easily been the worst year of my life - and I'm truly sorry that Double Action is still delayed. I'm immensely grateful for everyone's patience - as the people close to me all know, I'm a paper cup filled with organic mercury; I fold under the slightest pressure, and I'm immensely poisonous when I do. 

<div class="post-image text-center">
<a href="{{ site.url }}/images/mystery.png"><img src="{{ site.url }}/images/mystery_th.jpg" /></a>
</div>

I want to put this tiny little project out there to get my confidence back before resuming work on DA, so please look forward to it!

[^1]: The stuff I saw about it being "malware" looked like pure bunk to me though, and I don't buy the "ooooh china scary" angle either. Sorry.[^2]

[^2]: for a fleeting, tender moment, i shall speak with candour. who the fuck actually needs a shopping cart, yes its the most basic thing in the world and theres no excuse but if i'm buying something - don't matter whether its a game store, a clothes store, a hardware store, i'm in and out like the SAS, laser sight MP5SDs and rappelint rhough witnodws and shit, i am not here to fill a cart i am here to buy the game i want you dunces, don't try to upsell me bithc i aint at papa johns