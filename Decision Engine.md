---
tags:
 - Tac-Talk
---
# Overview
In Tac Talk any time an [[Game Rules#Operator|Operator]] enters a situation with an uncertain outcome it's called a **Mechanical Decision** and gets decided by the **Decision Engine**. All **Mechanical Decisions** in Tac Talk are made by rolling a 100 sided die or **D100**; more on that later. The [[Game Rules#Dispatcher|Dispatcher]] will decide when an action results in a **Mechanical Decision** and therefore a roll. Rolls fall into one of two categories:

1. [[#Challenge Rolls]]
2. [[#Outcome Rolls]]

Except in specific circumstances which are covered in [[#Resolving Contests]], the [[Game Rules#Dispatcher|Dispatcher]] always decides which type of roll applies to an action and the specifics surrounding that roll. Players may never petition the [[Game Rules#Dispatcher|Dispatcher]] for specific rolls.

> [!Warning] The [[Game Rules#Dispatcher|Dispatcher]] will often need to use the **Decision Engine** for situations involving other non-player characters. The [[Game Rules#Dispatcher|Dispatcher]] should use the same rules detailed for [[Game Rules#Operator|Operators]] except when noted by these yellow warning blocks.

## Rolling A D100
A **D100** can be rolled legally in any of three ways.
1. Rolling an actual **D100**
2. Rolling a **D%** (a **D10** from 00-90) and a **D10**
3. Rolling two **D10**, called **2D10** separately; the first roll is always the tens place while the second is always the ones place.

Because a **D100** is numbered 1-100, a result of all zeroes on any **2D10** or **D%/D10** roll is always a 100.

## Challenge Rolls
**Challenge Rolls** exist to test an [[Game Rules#Operator|Operator's]] [[System Rules#Skills|Skills]] when attempting to carry out a specific action. The outcome of a **Challenge Roll** is used to determine if an [[Game Rules#Operator|Operator]] succeeds or fails at a stated action. However, **Challenge Rolls** are not used to determine how that success or failure happens; the player and [[Game Rules#Dispatcher|Dispatcher]] should agree on outcomes before the roll happens.

**Challenge Rolls** should only be made when an [[Game Rules#Operator|Operator]] takes an action with a clear intent and a stated outcome. If a player can't explain either of these components for their [[Game Rules#Operator|Operator]] the [[Game Rules#Dispatcher|Dispatcher]] should press the player to come up with them and not allow a roll until that point.

Players should understand the consequences of failing a **Challenge Roll** before they decide to take it, and may decide not to perform that action. They don't need to know the specifics, but they should fully understand how the outcome will affect their [[Game Rules#Operator|Operator]].
> *Mike wants his Operator Troy to scale the side of the building and reach a balcony on the 3rd floor. The Dispatcher tells Mike that his action will require a Climbing Skill Challenge Roll and failing the roll means Troy will have to make an Outcome Roll against the Fall Damage Table. Since this could result in death, Mike decides Troy should take the stairs instead.*

**Challenge Rolls** only test [[System Rules#Skills|Skills]] when the outcome is uncertain. If an [[Game Rules#Operator|Operator]] is guaranteed to succeed or fail there is no reason to roll. This is covered in more depth below.

> [!Warning] The [[Game Rules#Dispatcher|Dispatcher]] may ignore this restriction when performing **Challenge Rolls** for non-player characters. You might use this to impart a sense of randomness on predetermined decisions or increase tension at a crucial moment in your story.

Each **Challenge Roll** should only test one [[System Rules#Skills|Skill]] at a time. If an [[Game Rules#Operator|Operator]] attempts to perform an action the [[Game Rules#Dispatcher|Dispatcher]] believes is too complicated to be tested by a single skill they may call for a **Linked Challenge Roll**. A **Linked Challenge Roll** is a series of **Challenge Rolls** which each test a single [[System Rules#Skills|Skill]] required to perform the complex action. Each roll in a **Linked Challenge Roll** will determine the degree to which the [[Game Rules#Operator|Operator]] succeeds or fails their action.
  > *Mike's Operator Troy attempts to shoot his pistol at the thugs in the van he is pursuing. The Dispatcher determines that this is a complex action which will require Challenge Rolls against Troy's Handgun Handling and Driving Skills. He succeeds at his Handgun Handling Roll, but fails his Driving Roll. The Dispatcher tells Mike that while Troy was able to shoot one thug, he falls out of the van and Troy can not move the car out of the way in time. Troy crashes the car, potentially ending the pursuit.*

The [[Game Rules#Dispatcher|Dispatcher]] should never change the outcome of a successful **Challenge Roll**, even if the roll was part of a **Linked Challenge Roll**. If an [[Game Rules#Operator|Operator]] attempts an action and succeeds, their success is sacred and should occur exactly as the player described.
> *Recall in the earlier example that even though Troy failed his Linked Challenge Roll for Handgun Handling and Driving, because he succeeded the Handgun Handling portion of the roll, he still managed to shoot the thug.*

### How To Make A Challenge Roll
All **Challenge Rolls** are made against a **Challenge Level**. **Challenge Level** is a number between 0 and 200 which represents the base amount of difficulty associated with an action and varies depending on what the [[Game Rules#Operator|Operator]] is attempting. Each [[System Rules#Skills|Skill]] details how to select an appropriate **Challenge Level** for actions which check against it.

The [[Game Rules#Dispatcher|Dispatcher]] should always tell players the **Challenge Level** of an action; except in cases where the [[Game Rules#Operator|Operator]] performing the action would not reasonably understand the difficulty involved before attempting the action. In these cases, a player may have their [[Game Rules#Operator|Operator]] make an **Outcome Roll** against the **Investigation Outcome Table** for the [[System Rules#Skills|Skill]] being tested by the **Challenge Roll** as long as the **Challenge Roll** is not part of a **Linked Challenge Roll**.

All **Challenge Rolls** are decided according to the following formula:

>[!info] Result = D100 + [[System Rules#Skills|Skill Level]] + [[System Rules#^archetype-modifier|Archetype Modifiers]]

The [[Game Rules#Dispatcher|Dispatcher]] will tell players which [[System Rules#^archetype-modifier|Archetype Modifiers]] - if any - to add to their roll. The [[System Rules#Archetypes|Archetypes]] selected will depend on the [[System Rules#Skills|Skill]] being used and how the [[System Rules#Skills|Skill]] is being utilized.
> *Mike's Operator Troy is attempting to shoot a moving target two blocks away with his sniper rifle. The Dispatcher tells Mike to make a Rifle Handling Challenge Roll. The Dispatcher also tells Mike that because the shot is quite far, he should use his Acuity Archetype Modifiers as Troy calculates the angle to aim.*

A single **Challenge Roll** may use [[System Rules#^bb3f38|Archetype Modifiers]] from multiple [[System Rules#Archetypes|Archetypes]] if the [[Game Rules#Dispatcher|Dispatcher]] determines there is good reason.
> *Troy is attempting to pick a self correcting lock, a tricky mechanism which rotates the lock to avoid picking attempts. The Dispatcher determines that while Troy only needs to roll a Lock Picking Challenge Roll, Mike should add both Troy's Acuity and Dexterity Archetype Modifiers to the Challenge Level of the roll.*

If the result of the roll after adding [[System Rules#^bb3f38|Archetype Modifiers]] is more than the **Challenge Level** of the roll, the [[Game Rules#Operator|Operator]] succeeds. Ties always go to the [[Game Rules#Operator|Operator]].

Because [[Game Rules#Operator|Operator]] [[System Rules#Skills|Skills]] have a maximum value of 100 and **Challenge Level** has a maximum value of 200 there will be times that an [[Game Rules#Operator|Operator]] can not succeed a **Challenge Roll** no matter the result of their **D100**. Conversely, if an [[Game Rules#Operator|Operator's]] [[System Rules#Skills|Skill Level]] and [[System Rules#^bb3f38|Archetype Modifiers]] total to be higher than the **Challenge Level** of a roll, there is no way that [[Game Rules#Operator|Operator]] can fail the **Challenge Roll**.

In these cases, the player should not make a **Challenge Roll**. However, this is only the case when the player knows the **Challenge Level** of a given roll.

The [[Game Rules#Dispatcher|Dispatcher]] should always tell the player making the **Challenge Roll** what the **Challenge Level** of the roll is, except in cases where the player's [[Game Rules#Operator|Operator]] would not reasonably know how difficult the task is before attempting it. In these cases, the player may ask to have their [[Game Rules#Operator|Operator]] make an **Outcome Roll** against the [[System Rules#Skills|Skill's]] **Investigation Outcome Table** in order to ascertain the **Challenge Level**.

### Resolving Contests
A **Contest** is any action a player takes against another player's [[Game Rules#Operator|Operator]] which results in a **Challenge Roll**. **Contests** are variants of **Challenge Rolls** where some special rules apply.

Before a **Contest** both players must willingly agree to enter the contest by clearly stating an intent and an outcome, similarly to **Challenge Rolls**. However, if either player does not agree to the outcomes then the player who called for the **Contest** must choose a different course of action. There is no bargaining for outcomes, this helps avoid situations where one player feels they have been cheated or unfairly attacked by another.
> *Troy enters a room, Sasha's Operator Kat doesn't recognize Troy and attempts to Disarm him. Sasha tells Mike: "Kat doesn't recognize you as you enter, I'd like to enter a contest, if I win you'll be disarmed". Mike responds: "I'll enter the contest but if I win Troy will kick you and you'll have to roll a Blunt Damage Outcome Roll, is that fair?". Since Kat agrees to the outcome the Contest continues.*

After agreeing to a **Contest** each player decides if their [[Game Rules#Operator|Operator]] is an attacker or defender in the **Contest**. The attacker is usually the [[Game Rules#Operator|Operator]] who calls for the **Contest** and is taking the action against another [[Game Rules#Operator|Operator]].
> *Since Kat is attempting to disarm Troy - who would not otherwise have engaged her - Kat is considered to be the attacker in this Contest and Troy the defender.*

It is also possible for both [[Game Rules#Operator|Operators]] to be attackers in a **Contest**. This typically happens in situations where both parties have the same to gain or lose by succeeding or failing.
> *Troy and Kat hit the boxing gym after a shift and start to spar, since both Operators are aiming to win the sparring match they are both considered attackers for the Contest.*

If both players believe their [[Game Rules#Operator|Operators]] are defenders in a **Contest**, there is no reason for the **Contest** to happen, and the player who called for the **Contest** should choose a different course of action.

Determining a defending [[Game Rules#Operator|Operator]] - if any - will help decide the outcome of the **Contest** after each player has completed their **Challenge Roll**.

In a **Contest** both players roll **Challenge Rolls** against relevant [[System Rules#Skills|Skills]] to determine if they succeed or fail. When a **Contest** is entered each player picks the [[System Rules#Skills|Skill]] they will use and tells the other player what their [[System Rules#Skills|Skill Aptitude]] is; this will be the **Challenge Level** of the Roll. The [[Game Rules#Dispatcher|Dispatcher]] is free to dispute the [[System Rules#Skills|Skill]] choice of each player if they believe a more fitting [[System Rules#Skills|Skill]] can be used or a **Linked Challenge Roll** should be made instead.
> *As Kat moves to Troy and begins to disarm him a Contest is started. Sasha tells Mike she'll be using her CQC Skill with an Aptitude of 37 to attempt to disarm Troy. Mike tells Sasha that he will also use his CQC Skill but the Dispatcher feels Mike should use his Shotgun Handling Skill instead since he is holding a shotgun. Mike tells Sasha his Shotgun Handling Aptitude is 35.*

Just like normal **Challenge Rolls**, the [[Game Rules#Dispatcher|Dispatcher]] notifies each player in a **Contest** which [[System Rules#^bb3f38|Archetype Modifiers]] to add to their **Challenge Level** in order to determine the **Challenge Difficulty** of the roll. The [[System Rules#^bb3f38|Archetype Modifiers]] used may differ between players.

Finally, both players roll their respective **Challenge Rolls**. The player who succeeds their **Challenge Roll** wins the **Contest**. If both players succeed the victory is given to the defending player. If there is no defending [[Game Rules#Operator|Operator]] in this **Contest** both players must either choose new [[System Rules#Skills|Skills]] to continue the **Contest** or accept the tie and mutually decide on the outcome. Players are not allowed to undo or ignore the results of a **Contest**, nor are they allowed to roll the same [[System Rules#Skills|Skills]] twice when resolving a **Contest**.
> *Both Mike and Sasha succeed at their Challenge Rolls. Since Troy is the defender in this Contest, the victory goes to him. Therefore, Kat fails to disarm Troy and must roll against the Blunt Damage Outcome Table after Troy kicks her.*

## Outcome Rolls
**Outcome Rolls** exist to select a single outcome from a list of possibilities. They are usually rolled to determine the consequence of a [[#Challenge Rolls|Challenge Roll]], either by the player or a non-player character.

**Outcome Rolls** roll against tables for specific [[System Rules#Skills|Skills]], [[System Rules#Archetypes|Archetypes]], and scenarios. The [[Game Rules#Dispatcher|Dispatcher]] will tell the player which **Outcome Table** they are rolling against. An **Outcome Table** will also detail any modifiers to make to the roll in order to select the outcome.
> *Mike's Operator Troy is reloading his machine gun. The Dispatcher tells Mike to make an Outcome Roll against the Reload Outcome Table. Mike rolls a 48 and adds his Machine Gun Handling Aptitude of 36, as instructed by the table. His result of 84 means his reload succeeded with no complications.*
