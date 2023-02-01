# How to make a pizza!

## INIT: 
- Toppings = [pepperoni, ham, bacon, sausage, mushroom, bell pepper, olive, pineapple]
- Dough 
- Pizza Sauce
- Shredded Mozzarella Cheese
- Oven


## Functions:
- chooseSize(size):

       CASE size of
           - Large: SET ingredientAmount to large  
                   get 390 grams of dough  
                   get 150 grams of mozzarellaCheese  
                   get 100 grams of pizzaSauce
           - Medium: SET ingredientAmount to medium  
                   get 300 grams of dough  
                   get 110 grams of mozzarellaCheese  
                   get 70 grams of pizzaSauce  
           - Small: SET ingredientAmount to small  
                   get 220 grams of dough  
                   get 70 grams of mozzarellaCheese  
                   get 50 grams of pizzaSauce  
            
- chooseToppings(input) 
 
        IF (toppings NOT in input)  
            Remove topping from toppings array  
        
- retrieveIngredient(ingredientAmount) 
 
        FOR (topping in toppings)  
            IF (ingredientAmount == large)   
                get 20 grams of topping  
            ELSE IF (ingredientAmount == medium)  
                get 16 grams of topping  
            ELSE  
                get 12 grams of topping  
             
- spread(topping)
  
        WHILE (grams of topping > 0)
            continue spreading topping accross top of dough
          


