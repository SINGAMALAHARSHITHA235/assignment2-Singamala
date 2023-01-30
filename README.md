# assignment2-Singamala 
# HARSHITHA SINGAMALA
###### Tennis
Tennis is a racket sport that is played either individually against a single opponent or between two teams of two players each. Each player uses a **tennis racket** that is strung with cord to **strike a hollow rubber ball** covered with felt over or around a net and into the opponent's court. 
--------------------------------------------------------------------------------------------------------------------------------------------
# Tennis Racket Play
# Tennis Sport team name is The Heatstrokes.
There are many great names in tennis. 
1. Roger Federer 
2. Serena Williams 
3. Maria Sharapova

- Alcaraz Carlos
* Nadal Rafael
+ Cilic Marin


https://github.com/SINGAMALAHARSHITHA235/assignment2-Singamala/blob/main/AboutMe.md
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ### Tables

| Country |  Reason  | Data |
|:---------:|:----------:|:------:|
| France  | The country’s beauty make it a popular destination| 1 week |
| Spain   | A cultural patchwork that continues to shape the modern nation’s | 10-13 days |
| Japan   | To see the update Version | 15 days |
| Greece  | The beauty of thw white nature | 1 week |
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Pithy Quotes 
>Gentlemen, you can't fight in here. This is the war room. (*Dr. Strangelove*) <br>
>Ned, I would love to stand here and talk with you—but I’m not going to.(*Phil Connors (Bill Murray)*)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Code Fencing
>SVG PATTERNS https://stackoverflow.com/questions/40218109/i-need-help-in-developing-a-circular-pattern

<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>