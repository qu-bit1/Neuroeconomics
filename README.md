# Neuroeconomics
### Submission by Aryans - Team 2
<hr/>

#### Parameters :
* Environment Parameters 
    - HEIGHT                          : size parameter
    - WIDTH                           : size parameter
    - INITIAL_HELPUL_POP              : initial number of helpful macpen
    - INITIAL_TITTAT_POP              : initial number of tittat macpen
    - INITIAL_UNHELPFUL_POP           : initial number of unhelpful macpen
    - MOVEMENTS_PER_DAY               : the number of movements per day
    - CANTEEN_COUNT                   : the number of canteens in our world
    - CANTEED_FOOD_PER_PERSON         : the amount of food the canteen will give to a particular person
    - CANTEEN_DAILY_FOOD_LIMIT        : the daily limit of a given canteen
    - CANTEEN_REAPPEAR_TIME           : this parameter is required in case we want to change the positions of the canteens
    - GHOST_VAL                       : the amount of food the ghost gang takes away
    - FOOD_THRESHOLD_FOR_REPRODUCTION : reproduction threshold of the macpens
    - FOOD_COST_PER_MOVE              : the amount of food lost in movement
    - MIN_START_FOOD                  : the least amount of food each macpen will have at the beginning

* QLearning Parameters
    - LEARNING_RATE
    - START_EXPLORATION_PROB
    - MIN_EXPLORATION_PROB 
    - DISCOUNT 
    - EXPL_RATE_DECAY 
    - PRODUCTION_REWARD 
    - VISION_RADIUS 
    - VISION_MOVEMENT_PROB

# ``` the whole analysis of the world depends on the variation of these above parameters```

## the environment is simulated in a pygame environment:
* `red blocks = unhelpful`
* `green blocks = helpful`
* `yellow blocks = tittat`

<img width="748" alt="Screenshot 2023-04-03 at 10 47 39 AM" src="https://user-images.githubusercontent.com/99525836/229417701-7c58d635-0626-44f2-a86b-b042bcdae6b6.png">
