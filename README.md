# Rock Paper Scissors

A proposed enhancement to the application, specifically in the score screen (Score). The idea is to replace the current score presentation with a more visual and organized presentation using a UITableView.

The implementation will include the following:
- **Score in Table Format:** The score screen, instead of displaying the score in plain text, will be redesigned to use a UITableView. Each entry in the table will represent a game turn and will include details such as the player's choice, the opponent's choice, and the turn result.

Each cell must have
- The name of the player
- The score value in that turn
- The option that were played in that turn
- The background should be:
  - green if the user won the turn
  - red if the user lost the turn
  - brown if the user tied
