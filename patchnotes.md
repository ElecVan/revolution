# Patch Notes

 11.11.22 - v1.0 initial commit
 
 11.16.22 - v1.0.1 commit 
 
             Bug fixes:
             
              - Drivetrain not responding, moved motor velocity declarations to driver control while loop so it constantly updates
              
              - One of the flywheels on the shooter spinning the wrong direction, reversed one of the motors

11.17.22 - v1.0.2 commit
         
             Changes:
              
              - Slightly altered the way the flywheel speed adjusting works. Now you only need to hold A to do 75% speed. 
              
              - Added a beta Auton
              
             Bug fixes:
             
              - Fixed the piston so that it goes back after you release the button
              
              - added some else statements so that systems stop after releasing the buttons controlling them
