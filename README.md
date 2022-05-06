# decision-tree
Creating a decision tree.

a = input('are you hungry : ')
if a == 'yes':
    print ('alright')
elif a == 'no':
    print ('go to sleep')

b = input('do you have Rs 250 : ')
if b == 'yes':
    print ('lets order food from swiggy/zomato')
elif b == 'no':
    print ('cook and eat')
if b == 'yes':
    print ('enjoy the meal')

###################################-----MODIFIED-----############################################

#if inside if
a = input('are you hungry : ')
if a == 'yes':
    b = input('do you have Rs 250 : ')
    if b == 'yes':
        print ('lets order food from swiggy/zomato')
    elif b == 'no':
        print ('cook and eat')
elif a == 'no':
    print ('go to sleep')
