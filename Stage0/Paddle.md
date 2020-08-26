# Paddle

## Feature

It holds the paddle size, color and position.
  
It moves the paddle according to user input

## Acceptance Criteria

### Scenario: User moves paddle

  Given the paddle is center of the edge in the beginning
  
  When user moves it up or down
  
  Then paddle moves

### Scenario: Point is scored

  Given the gameplay is on
  
  When a point is scored
  
  Then paddle moves back to center
