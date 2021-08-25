<h5>A. How many different ways are there to put 4 balls of different color into 3 different bins? No limit on number of balls each bin can get.</h5>

<h6>Answer: 81</h6>
<p>Each ball's assignment is independent event, and there are 3 possible ways(bins) for each ball. So total combinations are 3^4=81</p>

<h5>A. How many different ways are there to put 4 balls of different color into 3 different bins? So that bin1,2 gets 1 each,bin3 gets 2?</h5>

<h6>Answer: 12</h6>
<p>(4!)/(2!)=12</p>

<h5>B. How many different ways are there to put 4 identical balls into 3 different bins? Each bin gets at least one ball.</h5>
<h6>Answer: 3</h6>
<p>This is a <a href="https://en.wikipedia.org/wiki/Stars_and_bars_(combinatorics)#Theorem_one">stars and bars problem</a> theorem 1.
It's equivalent to have 4 stars, and draw 2 bars to separate them, bars can't be next to each other. Total number of ways=C(4-1,3-1)<br/>
For this particular case, since each bin at least gets one, we only need to decide where the 4th ball goes, there are only 3 bins to choose.
</p>

<h5>C. How many different ways are there to put 4 identical balls into 3 different bins? No limit on number of balls each bin can get.</h5>
<h6>Answer: 30</h6>
<p>This is a <a href="https://en.wikipedia.org/wiki/Stars_and_bars_(combinatorics)#Theorem_two">stars and bars problem</a> theorem 2.
It's equivalent to have 4 stars, and draw 2 bars to separate them. Total number of ways=C(4+3-1,3-1)</p>

<h5>A. How many different ways are there to put 4 balls of different color into 3 identical bins? Each bin gets at least one ball.</h5>

<h6>Answer: 6</h6>
<p>This is <a href="https://en.wikipedia.org/wiki/Stirling_numbers_of_the_second_kind">Sterling number of 2nd kind</a>. S(4,3)=6<br/>
List of all posibilies: 1,2,34; 1,3,24; 1,4,23; 2,3,14; 2,4,13; 3,4,12<br/>
For this particular case, since each bin at least gets one, there will be one bin getting 2 balls, the number of combination of these two balls are C(4,2)=6
</p>
