### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:
# Class is not initialsed

  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
  # Should be == to compare card.value to 1
  # Should be a : after else

  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  # Misspelled def to define the function
  # No comma between parameters card1 and card2
  # 'card' is not defined, should probably be card1
  # if statement should be indented


def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  # not properly indented, needs another tab forward, and return should be an indent back
  # total is not initialised with a value, should be 0
  # attempting to concatenate string with integer on line 42
```
