# Ground Shipping Project
#Variable

type_of_shipment = 1
weight = 41.5
weight_GSP = 0
weight_D = 0
flat_charge = 20.0
flat_charge_premium = 125.0

if type_of_shipment == 0:
  print ("Comparision of prices: GroundShipping, GroundShipping Premium, and DroneShipping below >")
# Shipping Strings
type_of_ship_1 = " a Ground Shipping is "
type_of_ship_2 = " a Ground Shipping Premium is "
type_of_ship_3 = " a Drone Shipping is "
total_text = "Your total for"

# Shipping
if type_of_shipment == 1:
  print (total_text + type_of_ship_1) 
if type_of_shipment == 2:
  print (total_text + type_of_ship_2 )
if type_of_shipment == 3:
  print (total_text + type_of_ship_3)

# Ground shipping
if weight == 0:
  print("")
elif weight <= 2.0:
  print ( weight* 1.50 + flat_charge )
elif weight >= 2.0 and weight <= 6.0:
  print ( weight* 3.0 + flat_charge)
elif weight >= 6.0 and weight <= 10.0:
  print ( weight* 4.0 + flat_charge)
elif weight >= 10.0:
  print ( weight* 4.75 + flat_charge)

# Ground Shipping Premium
if weight_GSP == 0:
  print("")
else:
  print (125.0)

# Drone Shipping 
if weight_D == 0:
  print("")
elif weight_D <= 2.0:
  print ( weight_D * 4.50)
elif weight_D >= 2.0 and weight <= 6.0:
  print (weight_D * 9.0 )
elif weight_D >= 6.0 and weight <= 10.0:
  print (weight_D * 12.0 )
elif weight_D >= 10.0:
  print (weight_D * 14.25)

Signature = """
-----ll---ll-----
-----l-0-0-l-----
-----l-www-l-----
"""
print (Signature)
