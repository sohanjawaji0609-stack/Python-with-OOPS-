class Product:
    Product_ID = 101
    Product_name = "Laptop"
    Price = 50000


class Product2:
    Product_ID = 102
    Product_name = "Mouse"
    Price = 800


class Customer:
    Customer_name = "Ravi"
    Customer_ID = 1
    Shopping_cart = []

    def Add_Product(self):
        Customer.Shopping_cart.append(Product.Product_name)
        Customer.Shopping_cart.append(Product2.Product_name)
        print("Products added to cart")

    def Remove_Product(self):
        Customer.Shopping_cart.remove("Laptop")
        print("Product removed from cart")

    def Display_Cart(self):
        print("Shopping Cart:", Customer.Shopping_cart)

    def Calculate_Total(self):
        Total = Product.Price + Product2.Price
        print("Total Amount:", Total)


P = Product()
P2 = Product2()
C = Customer()

C.Add_Product()
C.Display_Cart()
C.Calculate_Total()
C.Remove_Product()
C.Display_Cart()
