## [Week 1](https://www.youtube.com/watch?v=Q3ar5nFVuiQ)

probability has been a field for like hundreds and hundreds of years since people got addicted to gambling basically. but it wasnt until like 1900s that people realized it and proved it was actually a part of mathematics and people started to rigorously show why everything in probability was true. and there's this wonderful mathematician, his name is kolmogorov and he came up with what we called the axioms of probability. he said, "hey guys, if you assume these three things are true, I'm going to be able to prove every rule that you see in probability for AI". him and his friends were able to prove that. and it's true. mathematially, if you agree with these three things, I would be able to prove anything in probability theory just from these three assumptions

S = all ossible outcomes, E = the event

- **Axiom 1**: 0 <= P(E) <= 1

it says that if you have any event E, the probability of E, it's got to be between 0 and 1. you cant have a probability of 2 or a negative probability

- **Axiom 2**: P(S) = 1

if S is all possible outcomes in the universe, the probability of S is 1. so if you have some experiment and S is everything that could happen, the probability that something will happen is 1

- **Axiom 3**: if mutually exclusive, P(E or F) = P(E) + P(F)

Kolmogorov said, he's gonna assume that if you want to know the probability that E or F happens, and it's not possible for both E and F to occur at the same time, you can just add probabilities

P(E or F) = P(E) + P(F)

- **Complement**: the chance E does not happen, denoted by P(E<sup>c</sup>)

P(E) + P(E<sup>c</sup>) = 1
<br>
P(E<sup>c</sup>) = 1 - P(E)

    **Proof of Complement (Using Axioms)**: P(E<sup>c</sup>) = 1 - P(E)

  => P(E or E<sup>c</sup>) = P(E) + P(E<sup>c</sup>) [by axiom 3, E and E<sup>c</sup> can't both happen]
  <br>
  => P(S) = P(E) + P(E<sup>c</sup>)
  => 1 = P(E) + P(E<sup>c</sup>) [by axiom 2]
  => P(E<sup>c</sup>) = 1 - P(E)

3. P(E and F): if E and F are not mutually exclusive
