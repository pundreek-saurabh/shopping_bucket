# shopping_bucket
#Python glimpse
money=20

items = {'apple': 2, 'banana': 4, 'orange': 6}


for item_name in items:
    
    print('--------------------------------------------------')
   
    print("You have " + str(money) + " dollars in tour wallet ")
    
    print('Each ' + item_name + ' costs ' + str(items[item_name]) + ' dollars')
    
    input_count = input('How many ' + item_name + 's do you want?: ')
    print('You will buy ' + input_count + ' ' + item_name + 's')
    
    count = int(input_count)
    total_price = items[item_name] * count
    print('The total price is ' + str(total_price) + ' dollars')
    
   
    
