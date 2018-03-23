## Find regexes that match the following. (e.g. find a single regex that matches
both `antelope` and `antelopes`.)

# Single regex that matches either of these: 

    antelope rocks out
    antelopes rock out


* /antelopes? rocks? out/g 

(antelope matches the characters antelope literally s? suggests that the s is optional )
## Regex that matches either of: 

    goat
    moat

  but not:

    boat

* /[^b]oat/g
(this is taking the option of any word ending in oat to not be boat by removing the b from the matching possiblities)
## Regex that matches dates in YYYY-MM-DD format. (Year can be 1-4 digits, and
  month and day can each be 1-2 digits). This does not need to verify the date
  is correct (e.g 33333-33-33 can match).

  2000-10-12
  1999-1-20
  1999-01-20
  812-2-10

* \d\d?\d?\d?-\d\d?-\d\d?
(any digits with any digit being optional separated by - )

* A lion can be sleeping, eating, hunting, or preening. Draw a state
  machine diagram for the lion and label the transition events that
  cause state transitions.

  open file lion.png for answer

  