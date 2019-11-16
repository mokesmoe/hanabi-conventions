## Null Conventions

* These conventions apply to any variant with an null (touched by no clues) suit.

### Hard Variant

* Any variant with a null suit is treated as a *Hard Variant*, meaning that *Loaded Play Clues* are "turned on" and so forth.

### Null Positional Clues

#### What is a *Positional Clue*?

* *Positional Clues* correspond to a slot number:
  * A number positional clue corresponds directly to the slot number. For example, a number 3 clue means to play slot 3.
  * A color positional clue corresponds to the stack order. For example, green (the second stack from the left) means to play slot 2.

#### Do I discard cards touched as a *Positional Clue*?

* *Good Touch Principle* does **not** apply to cards touched as *Positional Clues*. They should be discarded exactly like an unclued card would.
  * The exception to this is if the card is known to be useful to the team (e.g. a 3 when no 3's are currently played).

#### What kinds of clues count as a *Positional Clue*?

* Any clue that looks like one of the following is now a *Positional Clue* instead:
  * a *Double Finesse* or a *Triple Finesse* where one player has to blind-play **two or more** cards
  * a *Double Bluff* or a *Triple Bluff*
  * an *Ejection* or a *Discharge*
  * a *Rank Choice Finesse* or a *Rank Choice Bluff*
  * a *5 Pull* or a *Trash Pull*
  * a *Trash Push*
  * a *Black 4 Bluff* (with black)
  * a clue that has no "normal" conventional interpretation

#### How do the clues map to the slot numbers in the different types of null variants?

* In certain game types, the slot may not be clear:
  * If there is an extra number available (e.g. if there are only 4 cards in the hand), then a positional 5 means to save the chop and the other numbers are always *Play Clues*.
  * If there are not enough colors available for each slot, then the colors map to the lowest slot numbers. For example, in a 3-player game with only blue and green available, blue would map to slot 4 and green would map to slot 5.
  * If there are one or more extra colors available (e.g. a 3-player 6-suit game), then the extra colors wrap around to being slot 1, slot 2, and so forth.

#### Are *Positional Clues* both *Save Clues* and *Play Clues*?

* A *Positional Clue* can be either a *Save Clue* or a *Play Clue*:
  * If the slot corresponds to the chop of a player, then they have to respect that it could be a *Save Clue*. In other words, it could be a *2 Save* on a null 2, a *5 Save* on a null 5, or a save on a critical null 3 or null 4 (if the other copy is in the trash).
  * If the slot corresponds to a slot that is not on the chop, then it is a *Play Clue*.

#### Can I use *Positional Clues* to get non-null cards?

* *Positional Clues* are **only** allowed to get null cards.
* Subsequently, *Positional Clues* are "turned off" once all of the null cards have been played.

#### How about an example?

* For example, in a 3-player null game:
  * On the first turn of the game, Alice clues Cathy about one 4.
  * Bob knows that normally, this would be a *4's Double Bluff*. But *Double Bluffs* are turned off in variants with a null suit.
  * Bob instead knows that this is a *Positional Clue*, indicating that someone should play their slot 4 card.
  * Bob sees that Cathy's slot 4 card is not a null card, so he plays his slot 4 card as the null 1.

#### Do you have to be in *Bluff Seat* to give a *Positional Clue*?

* *Positional Clues* do **not** have to be given in *Bluff Seat*. They can be given by anyone, since the other players will see that the clue does not apply to them.
* Subsequently, *Positional Clues* must be played into as soon as possible, similar to a *Finesse*. If one player ignores the *Positional Clue*, then the next player will blind-play something as an *Ambiguous Positional Clue*.
* For example, in a 3-player null game:
  * On the first turn of the game, Alice clues Cathy about one 4.
  * Bob knows that normally, this would be a *4's Double Bluff*. But *Double Bluffs* are turned off in variants with a null suit.
  * Bob instead knows that this is a *Positional Clue*, indicating that someone should play their slot 4 card.
  * Bob sees that Cathy's slot 4 card is a null 1, so he knows that this is a positional clue on Cathy.
  * Bob discards.
  * Cathy blind-plays her slot 4 card.

### The Positional Finesse

* *Positional Clues* can also be used to *Finesse* a null card.
* For example, in a 3-player game:
  * Nothing is played on the stacks.
  * Bob's hand is completely unclued.
  * Alice gives a *Positional Clue* to Bob indicating that he should play his slot 3.
  * Bob sees that Cathy has a null 1 on her *Finesse Position*. Thus, he marks his slot 3 card as either null 1 or null 2. Bob discards.
  * Cathy sees that Bob has a null 2 on his slot 3 and that Cathy has indicated that it is playable. Cathy blind-plays her *Finesse Position* card as null 1.
  * Bob now knows that he has a null 2 on his slot 3.

### The Positional Layered Finesse

* Normally, *Positional Clues* are only allowed to "get" null cards.
* Thus, if a player plays a card from a *Positional Clue* and it is not a null card, then they know to keep playing their next slot over as a *Positional Layered Finesse*.

### The Positional Inverted Layered Finesse

* Normally, if a *Positional Clue* gets a non-null card, then the player knows to keep playing their next slot as a *Positional Layered Finesse*.
* However, what if the *Positional Clue* already indicated the right-most unclued slot? In this situation, the *Layered Finesse* is supposed to go backwards, and the player should playing cards upwards.

### The Positional Bounce Finesse

* This convention only applies to variants with a null suit.
* Normally, in a *Positional Layered Finesse*, a player will blind-play cards in a rightward direction until they find the null target card.
* However, what if a player in the middle of a *Positional Layered Finesse* plays their chop and it successfully plays but it is not be a null card?
* In this circumstance, the player should **not** stop blind-playing. They should go on to play their new chop card, similar to a *Positional Inverted Layered Finesse*.
* This is called a *Bounce Finesse* because it drops all the way down and then bounces back up.