# Paddle

## Feature

It holds the paddle size, color and position.
  
It moves the paddle according to user input

## Acceptance Criteria

### Scenario: User moves paddle

  Given the paddle is center of the edge in the beginning
  
  When user moves it up or down
  
  Then paddle moves

### Scenario: User scores point

  Given the game play is on
  
  When user scores a point
  
  Then paddle moves back to center
