## Daily Puzzle 1 (October 13)

In the trial of the Pfizer COVID-19 vaccine, among people aged 16 to 55, 78% had a sore arm after the second dose and 59% felt tired. Suppose the two side effects happen independently. What fraction of people had at least one of them?

**Solution 1**

keyword → at least one → OR
<br>
formula → probability of union of independent events
<br>
P(A or B) = P(A) + P(B) - P(A and B)
<br>
<br>
P(A = sore) = 0.78
<br>
P(B = tired) = 0.59
<br>
<br>
P(A and B = both sore and tired) = P(A) x P(B) = 0.78 x 0.59 = 0.4602
<br>
P(A or B = either sore or tired) = 0.78 + 0.59 - 0.4602 = **0.9098**

**Solution 2**

P(A = sore) = 0.78
<br>
P(A<sup>c</sup> = not sore) = 1 - 0.78 = 0.22
<br>
<br>
P(B = tired) = 0.59
<br>
P(B<sup>c</sup> = not tired) = 1 - 0.59 = 0.41
<br>
<br>
P(A<sup>c</sup> and B<sup>c</sup> = niether sore nor tired) = 0.22 x 0.41 = 0.0902
<br>
1 - P(A<sup>c</sup> and B<sup>c</sup>) = P(A or B) [De Morgan's Law]
<br>
1 - 0.0902 = **0.9098**

## Daily Puzzle 2 (October 14)

"For a successful technology, reality must take precedence over public relations, for nature cannot be fooled." Richard Feynman, 1986". After the Challenger disaster in 1986, the physicist Richard Feynman asked how likely a space shuttle was to be lost on a single flight. The working engineers said about 1 in 100. NASA management said 1 in 100,000. Suppose the engineers were right, and each flight succeeds or fails independently of the others. What is the chance of losing at least one shuttle in 100 flights?

**Solution**

P(S = any single flight failure) = 0.01
<br>
P(S<sup>c</sup> = any single flight success) = 1 - 0.01 = 0.99
<br>
since each flight behaves independently, for 100 flights,
<br>
<br>
P(100 safe flights) = (0.99)<sup>100</sup> ≈ 0.3660
<br>
P(failing atleast 1 flight) = 1 - 0.37 = **0.63**
