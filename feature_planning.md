#High level ideas
Want to be able to manage the world elements such that they are connected:
    1. NPC
    2. District location (Open area, businesses, civic areas, religious areas)
    3. Settlement district (Ghetto, guild quarter, merchants, slums, red light district,
       slaughterhouses, temples, thieves, wealthy/nobles, docks)
    3. Settlement 
    4. Region
    5. Continent
    6. World

While keeping track of the campaign:
    - Session notes
    - Players
    - Fronts
    - Campaign goal statement
    - Campaign background

For the session
    - Strong start
    - Potential scenes
    - Secrets and clues
    - Fantastic locations
    - Magic item rewards

Also want tracking for:
    1. Calendar
    2. Weather

Other things that should be considered:
    - Quick moving between different NPCs, settlements

#Thoughts on design patterns
For the world elements I think that a composite design pattern seems to make sense, the leaves would
be the NPCs. However, the upper levels of the tree also will have random functionality.


