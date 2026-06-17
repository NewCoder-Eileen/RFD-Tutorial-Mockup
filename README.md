# RFD-Tutorial-Mockup
This is a simple python project to plan out the tutorial for RFD.

Planning Stages:

# Notes:
Not everything should be introduced at first. Only the core loop should be introduced. The tutorial should be easy to understand,
straight forward, and fairly quick.

Although, it's important to remark that there needs to be a good balance of length for the tutorial.

## Short Onboarding Loop
If it's very short, there is a good chance that the player won't be immersed in the environment, won't get a good sense of the game, are less likely of getting a valid sense of the game, and have a chance of not staying in the game for as long.

## Long Onboarding Loop
On the other side, if the tutorial is too long, the player will be overwhelmed by the amount of content. Though they would technically be introduced to a lot of topics, it is hard for the player to retain all of the information, especially when it's all compacted and efficient as possible.

### So, what is the right balance?
Let's get the obvious things over with first. The onboarding loop should be easy to understand, simple, and concise.
Ideas:
* A long tutorial that's good basically guarantees that the player will stay in the game until the tutorial is over
    * (Not guaranteed but more retention overall)
* Can start with a quick and easy tutorial to understand the main point of the game (dining), it can progress from there


## 1. Onboarding Loop
    a. Loading screen
        Animation of 2 people (RoyaleFineDining and RoyalFineAlt) sitting at a table outside, with a beautiful view
        of buildings behind them. Should be cinematic, energetic music.

    b. Welcome to Royal Fine Dining
        First view of the game, curious about buildings and see the light and path of the main restaurant.
        Leading path and light gives the player a good sense of direction, they won't be confused.
        Overwhelmed in a good way?
        Player gets a sense of the vibe of the game

    c. Tutorial
        PHASE 1
        Loading screen starts, ends when they click the play 
            If first time, then could be a starting animation before loading screen
        Options: Dining first, dress up first, role first
            Choice: Role first
            Roles: Customer, Host, Server, Chef (options on ScreenGui at the beginning after joined)
            ScreenGui appears after the loading screen
            When game is first released, all roles are available, then it will be limited (capacities, maximums)
                After some time, there will be enough of each role (ideally) so then the options will be limited and there will have to be trainings
                    Maybe trainings??
        
        PHASE 2 --> Have role now
        Dedicated tutorials for each role

        Customer/first time:
        Should be very short
        1. Guidance to walk straight into restaurant
        2. Player should choose to either do solo dining or group dining
            --> not everybody is playing with friends/wants to dine with friends
        3. If group dining/live choice:
            Walk into group lane and interact with a host
                Host should have automatic interaction (not with chat, fast)

                Issue: What if a group is waiting for too long?
                    Are there enough hosts?
                        Balancing the roles could help balance it out, but then another questions arrives:
                        What if the hosts leave? Then what?
                            Lets just hope they handle that themselves for now, not sure about exact solutions
                            Possible solution: Robot host, or they can do it themselves after a timer
                                Warning: Doing it themselved does not mean that they claim their group from the waiting list, as they do not have training for that and could possibly prevent other groups from dining
                             
            Choose options on HostGUI (ScreenGui), for table/group
                Number of people
                Location
                People
            Submit form
            Invitation sent to people in group
                --> To see if they want to be in the group
                This an issue: People might take too long to accept
                    Solution: Add a timer for 20 seconds
                After all players chose an option or after 20 seconds:
                    Information is send to Waiting List (SurfaceGui)
            Host claims group from Waiting List (most long, on top)
                Host takes group to their table
                    With arrows
                    ScreenGui (for info about the group)
                    Then, give guidance to host to return back to their station
                        Timer, teleportation after 20 seconds
                Players take a seat at their table
                    Their ScreenGui disappears
            Server claims group from Tables List (SurfaceGui), (ASAP)
                Table gets added to their Claimed Tables Menu
                They get guidance to take a certain amount of menus (depends on number of people in the group, modules)
                Once menus are taken, the table they have to be delivered to becomes highlighted
            Server gives menus to players
                --> Guidance if its their first time or if taking too long or idk
                

                
                
                    
                        
                        
            



        

                


        


