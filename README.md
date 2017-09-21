# GeekBot

## Description
The GeekBot is an advanced discord bot, made with discord-rs.
The core feature of this bot that sets it appart from other bots is that
the bot manages membership and registrations.

## Behaviour

## Implemented

### Not yet implemented
  - Greeting (on join)      - Gives a random greeting message for new users
  - Greeting (on register)  - Gives a random welcome message for new members
  
  - Logging                 - Logs registered user activity (each registered user gets a unique ID which is hidden for [EVERYONE] except for 
                              the user him/her self. This ID is used to among other things, anonymously track the user activity.
                              The data can be used by the staff in order to check the progress of the server but it will be used
                              by the bot in order to reward the user for beeing active. [Spamming is not a valid activity].
                              (Unregistered users wont be tracked but will also have limited privileges)
  
   - Spam detection          - The bot will check the channels on the server and apply anti-spam algorithms and will silence and warn
                               users if they are cought spamming. 
                               After 3 warnings, the staff will be notified.  
 
### Disabled/Removed

## Features

### Implemented:


### Not yet implemented:
   - Register                                                     - Gives you a unique ID and a registering URL for registering your account 
                                                                    (Registering within discord would be a terrible security hazard)

   - Reset password                                               - Sends a reset code to your email adress. Note, resetting the password will 
                                                                    reset the entire account since the encrypted data will no longer be accessable.
   
   - Add   Challange                                              - Creates a new challange to the Challanges pool (staff only)
   - Edit  Challange  [Challange id/index]                        - Edits a challange (staff only)
   - Stats Challange  [Challange id/index]                        - Gives a url for the stats for a given challange (only members and above)
   
   - Add Role [USER] [ROLE,/s]                                    - Give a user a specific role or roles.
    

### Disables/Removed:


## Credits
- @Estrobeda


/The Geek Corner Community


## Major changes
2017/09/21 - Estrobeda changed the language of choice from nodejs to rust due to optimization, curriousity and safety.
             The geek portal is still planned to be based on NodeJS but is subject to change.
