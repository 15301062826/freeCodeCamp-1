---
id: 5900f3b01000cf542c50fec3
challengeType: 5
title: 'Problem 68: Magic 5-gon ring'
forumTopicId: 302180
---

## Description
<section id='description'>

Consider the following "magic" 3-gon ring, filled with the numbers 1 to 6, and each line adding to nine.

<img class="img-responsive center-block" alt="a completed example of a 3-gon ring" src="https://cdn-media-1.freecodecamp.org/project-euler/3-gon-ring.png" style="background-color: white; padding: 10px;">

Working <strong>clockwise</strong>, and starting from the group of three with the numerically lowest external node (4,3,2 in this example), each solution can be described uniquely. For example, the above solution can be described by the set: 4,3,2; 6,2,1; 5,1,3.

It is possible to complete the ring with four different totals: 9, 10, 11, and 12. There are eight solutions in total.

<div style='text-align: center;'>

  |<div style='width: 100px;'>Total</div>|<div style='width: 250px;'>Solution Set</div>|
  |--- |--- |
  |9|4,2,3; 5,3,1; 6,1,2|
  |9|4,3,2; 6,2,1; 5,1,3|
  |10|2,3,5; 4,5,1; 6,1,3|
  |10|2,5,3; 6,3,1; 4,1,5|
  |11|1,4,6; 3,6,2; 5,2,4|
  |11|1,6,4; 5,4,2; 3,2,6|
  |12|1,5,6; 2,6,4; 3,4,5|
  |12|1,6,5; 3,5,4; 2,4,6|

</div>

By concatenating each group it is possible to form 9-digit strings; the maximum string for a 3-gon ring is 432621513.

Using the numbers 1 to 10, and depending on arrangements, it is possible to form 16- and 17-digit strings. What is the maximum <strong>16-digit</strong> string for a "magic" 5-gon ring?

<img class="img-responsive center-block" alt="a blank diagram of a 5-gon ring" src="https://cdn-media-1.freecodecamp.org/project-euler/5-gon-ring.png" style="background-color: white; padding: 10px;">

</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>magic5GonRing()</code> should return a number.
    testString: assert(typeof magic5GonRing() === 'number');
  - text: <code>magic5GonRing()</code> should return 6531031914842725.
    testString: assert.strictEqual(magic5GonRing(), 6531031914842725);

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function magic5GonRing() {
  // Good luck!
  return true;
}

magic5GonRing();
```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```

</section>
