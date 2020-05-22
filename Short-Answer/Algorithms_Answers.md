#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a):
O(n)

b):
O(n log n)

c):
O(n)

## Exercise II

    n story building
     you have eggs
     eggs get broken if yeeted off of floor higher than F
     eggs surive if yeeted from floor equal to or less than F
     where did you get so many eggs bro?


    f = bottom/ 0           #F is set to lowest floor
    while f <= N:           #while F is not greater or equal to run loop
        drop egg            #Drop our boy
        if egg breaks :     #if he breaks, the last floor is our answere
            return f - 1
        else:               #if he survives we go up a floor
            f ++
