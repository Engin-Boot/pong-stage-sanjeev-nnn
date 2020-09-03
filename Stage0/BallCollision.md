# Ball Hit and Miss

## Feature

This module explains the procedure to allocate score for each player.

## Acceptance Criteria

### Scenario: Collision of ball with the wall

  Given the game is started

  When the player miss the ball and the ball strikes the wall

  Then the opposite player gets one point.
  
### Scenario: Collision of ball with the paddle

  Given the game is started

  When the player hits the ball and the ball strikes the paddle

  Then the player gets one point.
