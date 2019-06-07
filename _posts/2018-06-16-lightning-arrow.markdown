---
layout: post
title: "Lightning Arrow"
date: 2018-06-16T22:39:51-04:00
---

[Lightning Arrow](https://www.dndbeyond.com/spells/lightning-arrow) is a 3rd level Ranger spell from the Player's Handbook. Your Ranger gets two 3rd level spell slots per long rest at 9th level. A that level, a Ranger can know a total of 6 spells, so you need to choose your spells carefully. Should you pick Lightning Arrow over other spells?

## What does Lightning Arrow do?

Lightning Arrow takes a bonus action to cast, and changes your next ranged weapon attack to deal lightning splash damage that works whether or not your attack hits. Every creature within 10 feet of the target (including allies) take 2d8 lightning damage, halved on a successful Dexterity saving throw. And instead of taking the normal damage from your weapon, the target of your attack takes 4d8 lightning damage, halved if you miss.

## Statistical analysis

Let's analyze a scenario that might come up in the game. The 9th-level party is faced with eight [Dire Wolves](https://www.dndbeyond.com/monsters/dire-wolf), and it's the ranger's turn. She decides to cast Lightning Arrow and attack one of the wolves with her Longbow:

![Ranger casts Lightning Arrow on a Dire Wolf]({{ "/assets/direwolveslarrow.png"  }})

Let's say the ranger's attack bonus is +8. Against the Dire Wolf's AC of 14, she has a 3 in 4 chance of hitting the wolf with an arrow. She'll do damage to the wolves in the blue area whether she hits or misses.

Taking all that into account, the spell will do an average of 16.5875 points of damage to the targeted dire wolf, and 5.5 to the others. The damage has the following probability distribution:

![Lightning Arrow Damage Histogram]({{ "/assets/larrowhistogram.png"  }})

## Lightning Arrow compared with other spells

Other offensive spells available to the Ranger with 3rd level slots include [Conjure Barrage](https://www.dndbeyond.com/spells/conjure-barrage) and [Wind Wall](https://www.dndbeyond.com/spells/wind-wall). Both of those deal 3d8 damage (piercing or bludgeoning, respectively) to creatures in a much larger area, although Lightning Arrow potentially has a much longer range.

Conjure Barrage is a 60 foot cone, which would allow our ranger to damage all eight of the dire wolves:

![Ranger casts Conjure Barrage]({{ "/assets/direwolvesbarrage.png"  }})

Wind Wall allows you to shape the 50 foot long wall to take pretty much any path you want up to 120 feet away. Here's how that might look in our situation:

![Ranger casts Wind Wall]({{ "/assets/direwolveswindwall.png"  }})

Conjure Barrage and Wind Wall do more damage to more enemies, but Lightning Arrow does twice as much damage on average to a single enemy, which is generally more useful for a Ranger. The Ranger class is really optimized for taking down a single target at a time, so the AoE damage they can do is pretty feeble compared to the arcane casters. If a 9th-level party is going for AoE damage with 3rd-level spell slots, have the Wizards and Sorcerers bust out the [Fireballs](https://www.dndbeyond.com/spells/fireball):

![Conjure Barrage vs Fireball]({{ "/assets/barragevfireball.png"  }})

Lightning Arrow is very similar to [Hail of Thorns](https://www.dndbeyond.com/spells/hail-of-thorns), which can be upcast with a 3rd level slot, dealing 3d10 damage to the target and everyone within 5 feet of it. The target also suffers the normal damage from the attack. Since this happens only if your attack hits, the damage output of Hail of Thorns is sometimes zero. Even so, Lightning Arrow does only a couple of points more damage on average (against a Dire Wolf, 16.6 vs 14.3). So all things being equal, Lightning Arrow is a slight upgrade from Hail of Thorns. Compare Hail of Thorns at 3rd level against the Dire Wolves:

![Hail of Thorns]({{ "/assets/hailvlarrow.png"  }})

Fully a quarter of the 3rd level slots used to cast Hail of Thorns in this situation would be completely wasted.

[Flame Arrows](https://www.dndbeyond.com/spells/flame-arrows) (from [Princes of the Apocalypse](https://www.dndbeyond.com/compendium/adventures/pota) and [Xanathar's Guide to Everything](https://www.dndbeyond.com/compendium/rules/xgte)) is another 3rd level spell for the Ranger that could be compared to Lightning Arrow. Flame Arrows takes an action to cast, adds 1d6 damage to your next twelve attacks, and requires concentration the whole time. Using a single 3rd level slot for Flame Arrows ends up dealing maybe 4 points of damage more per turn on average over 6 turns than using that same slot for Lightning Arrow, but if the Ranger takes damage she might lose her concentration, turning those Flame Arrows into regular arrows again. So Flame Arrows is only better than Lightning Arrow in situations where you're either fighting enemies vulnerable to fire, you know you're going to have a drawn-out battle and you're pretty sure you can shield your Ranger from taking damage, or if you're up against a lot of enemies and you want to combine Flame Arrows with something like the [Hunter](https://www.dndbeyond.com/characters/classes/ranger#Hunter) archetype's Volley feature, or a [Haste](https://dndbeyond.com/spells/haste) spell.

![Lightning Arrow vs Flame Arrows]({{ "/assets/larrowvfarrow.png"  }})

## Enemy damage resistance and vulnerability

About 70 different creatures in the official D&D books are resistant to lightning damage, and more than 20 others are totally immune to it. However, many of those creatures have Good alignment, so are unlikely to be enemies in your game.

Lightning Arrow would be ridiculously good against creatures vulnerable to Lightning damage, but no creatures in the official D&D books so far have vulnerability to such damage.

It's rare for creatures to be resistant to the magical piercing and bludgeoning damage of Wind Wall, Conjure Barrage, and Hail of Thorns.

## Synergy with other Ranger features

Very importantly, Lightning Arrow is an Attack, unlike Conjure Barrage or Wind Wall. Since it's an Attack, it synergizes nicely with the Archery fighting style, your Extra Attack feature, the Hunter archetype's animal companion, the Gloom Stalker's Dread Ambusher and Stalker's Flurry features, the Horizon Walker's Planar Warrior and Distant Strike features, as well as the Hunter's Colossus Slayer, Giant Killer, and Horde Breaker features. Although Lightning Arrow only augments a single attack, these features allow you to make additional attacks either before or after your Lightning Arrow, or add more damage dice to the spell.

With that in mind, the total damage output of a 9th-level Ranger's turn when casting Lightning Arrow looks more like this:

![Ranger DPR]({{ "/assets/larrowdpr.png"  }})

## Critical Hits

Unlike Conjure Barrage, Hail of Thorns, or Wind Wall, Lightning Arrow can benefit from a critical hit. This means that 5% of the time the damage to the target will be 8d8. The splash damage will still be be 2d8. If you average the critical hits over all your uses of Lightning Arrow, it amounts to an additional 2 points of damage per casting. That's not a lot, but when you do get those critical hits they may turn the tide in any given fight.

## Compared with other classes

By 9th level, the Wizard has access to a 5th level spell slot, letting them cast [Cone of Cold](https://www.dndbeyond.com/spells/cone-of-cold), a 60-foot cone dealing 8d8 damage. But Lightning Arrow is a 3rd level spell, so let's compare it with the Wizard's 3rd level spells. Fireball does 8d6 damage in a 20-foot radius sphere, making Lightning Arrow seem pretty feeble by comparison on its own. That said, you'll usually be casting Lightning Arrow as part of a combination with multiple attacks on your turn--something that the Wizard cannot do.

![Lightning Arrow DPR vs Fireball]({{ "/assets/larrowdprvfireball.png"  }})

## When you would use this spell

Lightning Arrow is a situational combat spell. It's good for when you want to deal a lot of damage to a single enemy with its allies nearby, or when you might want to prepare an ambush. The saving throw is Dex, which a lot of creatures that fight in close formation might be fairly good at. Since this spell's splash damage doesn't discriminate between friend and foe, it's less useful if your allies are already engaging the enemy.

## Conclusion

Lightning Arrow is a strong offensive spell for the mid-tier ranger, similar to Hail of Thorns, but slightly better. It seems somewhat underpowered when you analyze it on its own, but it synergizes well with the class's other features. It's probably the best damage-dealing 3rd-level spell available to the ranger.

