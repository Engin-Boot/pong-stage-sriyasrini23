# Display

## Feature

The module displays the screen, paddles, ball and score.

## Acceptance Criteria

### Scenario: Upon starting game

  Given players want to play
  
  When program starts
  
  Then the display starts

### Scenario: Users play

  Given players are playing
  
  When paddle or ball moves
  
  Then the display updates

### Scenario: Stop game

  Given players want to stop
  
  When player presses escape key
  
  Then the display stops
