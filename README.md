# clock
analog clock using CSS and  Javascript

Explanation of Code

<div class="clock">
<div class="hours-container">
    <div class="hours"></div>
  </div>
  <div class="minutes-container">
    <div class="minutes"></div>
  </div>
  <div class="seconds-container">
    <div class="seconds"></div>
  </div>
</div>

making the background of the div with class clock as "clock.svg" and child div represents each hand in the clock and all the divs are absolute in position so that they can overlap
after getting a static representation use keyframes to rotate the div so that the hand is rotating and rotate each div based on their rotation.
