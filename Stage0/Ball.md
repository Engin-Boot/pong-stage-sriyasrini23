# Ball

## Feature

The module holds the position and speed of the ball on screen, and moves it.
  
It can also hold color and size of the ball.

## Acceptance Criteria

### Scenario: Move ball in the beginning

  Given the ball is in the centre at the beginning of the game
  
  When the game starts
  
  Then the ball moves to the first player paddle

### Scenario: Move ball upon touching paddle

  Given a move function in the module
  
  When the ball touches paddle
  
  Then the ball moves back
  
### Scenario: Move ball upon missing paddle

  Given a move function in the module
  
  When the ball touches paddle
  
  Then the ball is moved
