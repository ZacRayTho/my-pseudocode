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
            
            
## Program Start Example:

INIT Oven, Toppings[], Dough, MozzarellaCheese, PizzaSauce, ingredientAmount, rolling pin, PizzaPan, ovenMitt, yourself, pizzaCutter

1. chooseSize(large)

       - SET ingredientAmount to 20 Grams
       - GET 390 grams of dough  
       - GET 150 grams of mozzarellaCheese  
       - GET 100 grams of pizzaSauce  
       *Update variables with appropriate amount*
       
2. chooseToppings(pepperoni,bacon)

       - If (toppings[] NOT IN input[Pepperoni, bacon])
              REMOVE topping
       *Update toppings array ,leaving only pepperoni and bacon*
       
3. retrieveIngredient(ingredientAmount)

       - FOR (topping in toppings[pepperoni, bacon])
              IF (ingredientAmount == large)
                    GET ingredientAmount of topping[]
              
4. SET oven to 400 Fahrenheit
                    
5. WHILE (dough NOT flat and round)

       - USE rollingPin on dough to flatten
  
6. PLACE dough on PizzaPan
  
7. spread (pizzaSauce)

8. spread (mozzarellaCheese)

9. spread (toppings[])

10. DO (CHECK oven temperature)

        - WHILE (oven temperature NOT 400 fahrenheit)
       
11. PLACE pizzaPan in Oven

12. WHILE (mozzarellaCheese NOT melted AND dough NOT golden brown)

        - WAIT 5 Minutes
       
13. PUT ovenMitt on Yourself

14. RETRIEVE pizzaPan from oven

15. PLACE pizzapan on oven top

16. CUT dough into 1/8 with pizzaCutter

## END PROGRAM

          


