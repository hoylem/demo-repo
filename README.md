# Demo 

class Item:
    def calculate_total_price(self, skeet, repeat):
        return skeet * repeat
    	

item1 = Item()
item1.name = "Phone"
item1.price = 100
item1.quantity = 5

print(item1.calculate_total_price(item1.price, item1.quantity))
