# NCAAMileageTracker
Due to the massive conference realignment that took place in college football this offseason, I decided to look at which schools and conferences will be traveling the most.
This project looked at the schedules for all 134 teams, pulled the coordinates for each stadium, and determined the distance that teams would have to travel for every game.
# Assumptions
In the schedule file, the schedule for every team is mapped out based on where the game would be played (for instance, for Akron's week 1 game at Ohio State, their schedule reads 'Ohio State'.
However, for Ohio State, their week 1 game reads 'Ohio State', not 'Akron', since the game was played on Ohio State's campus).
For neutral site games, the FBS team closest in proximity to the venue was used (for example, for games in Mercedes-Benz Stadium in Atlanta, the schedule would read 'Georgia Tech').
