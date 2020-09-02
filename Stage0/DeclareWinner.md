# Game settings

## Declare the winner after calculating the score

This module declares the winner after calculating the score.

## Acceptance Criteria

### Scenario: Declare winner

  Given the game is started and the count for hits/miss of the ball is calculated

  When one of the player's counter value becomes 50

  Then the winner is declared and score of both the players is displayed
