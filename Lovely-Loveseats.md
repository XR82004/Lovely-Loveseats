# Lovely-Loveseats
Client trying to buy furniture
# Lovely Loveseats for Neat Suites on Fleet Street PROJECT

# Items descriptions
lovely_loveseat_description = "Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."

stylish_settee_description =  "Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."

luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."

# Items prices
lovely_loveseat_price = 254.00
stylish_settee_price = 180.50
luxurious_lamp_price = 52.15

# Description 
customer_one_itemization = "Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white." " Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."
sales_tax = .088

customer_one_ = lovely_loveseat_price + luxurious_lamp_price 

customer_one_tax = customer_one_ * sales_tax

customer_one_total = customer_one_tax + customer_one_

print ("Customer One Items:")
print (customer_one_itemization)
print (customer_one_total)
