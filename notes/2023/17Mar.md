# ICT Lesson, 17 March notes #

### 0. Quick recap ###
- Tests for programs
  - System Test
    - Test if intergrated functions work properly
    - e.g. Storage Test, Volume test, Performance Time Test    
  - User Acceptance Test
    - See whether user accepts the test

### 1. System Conversion ###
- Convert old system to new (sort of code rewrite for updating)
- Methods:
  - Direct Cutover
    - Directly convert and use new system
    - Is the new feature fully done? If yes then it's direct cutover
    - Advantages:
      - Save cost, time, manpower
    - Disadvantages
      - Direct cutover may have weird issues because people are dumb (high risk)
      - If a problem occurs, everything gets affected
    - e.g. Update of RPG Game
  - Parallel Conversion
    - Use old and new system at the same time and compare if new system have any issues
    - Advantages:
      - Much lower risk 
      - Can restore back to old system if anything goes west
    - Disadvantages:
      - Much higher manpower and cost requirement (both systems need to run at the same time)
  - Pilot Conversion 
    - Only find a small part of people to try new system and let others keep on using old system
    - e.g. Closed Beta /  Open Beta of games
    - Advantages:
      - Has impact if things go wrong, but low impact in terms of coverage as compared to others
    - Disadvantages:
      - Much higher manpower and cost requirement (both systems need to run at the same time)
      - Needs more time
  - Phased Conversion
    - Functions by Functions (part by part)
    - Advantages:
      - Lower impact
      - Can quickly respond to impact
    - Disadvantages:
      - Needs more time
