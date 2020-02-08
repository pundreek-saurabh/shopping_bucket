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
    
    
    if money>=total_price:
        print("You have bought "+ str(input_count) + str(item_name) + "s")
        money =money-total_price
        
        if money==0:
            print("Your wallet is now empty")
        break  
        
    else:
        print("You do not have enough money")
        print("You cannot buy that man y " + str(item_name) +" s")


print('You have '+ str(money) + "dollars left")    
   
    

