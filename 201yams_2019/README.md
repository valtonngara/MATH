### 201yams

Subject:

Every Sunday you play Yams (a.k.a. Yahtzee) with your grandmother. You have decided to cheat your way to
victory by developing a software that will give you the chances to obtain a given combination on the next
dice roll.
The different combinations are:

• a pair (at least 2 dice of the same value),

• a three-of-a-kind (at least 3 dice of the same value),

• a four-of-a-kind (at least 4 dice of the same value),

• a full house (one pair and one three-of-a-kind),

• a straight (5 dice of sequential value),

• a yahtzee (5 dice of the same value).

A combination is defined by its kind (pair, three-of-a-kind, four-of-a-kind, full-house, straight or yahtzee)
and its value (for a full-house, the value of the three-of-a-kind then the value of the pair, for the straight,
the value of the highest die).

USAGE:

./201yams d1 d2 d3 d4 d5 c

DESCRIPTION

• d1 value of the first die (0 if not thrown)

• d2 value of the second die (0 if not thrown)

• d3 value of the third die (0 if not thrown)

• d4 value of the fourth die (0 if not thrown)

• d5 value of the fifth die (0 if not thrown)

• c expected combination

Example:

![image](https://user-images.githubusercontent.com/65818912/158598601-a166cc50-2a94-46e2-9802-b68e328e5e8d.png)
