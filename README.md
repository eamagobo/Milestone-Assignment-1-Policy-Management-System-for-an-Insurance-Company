Create separate classes for policyholders, products, and payments.
Implement methods to register, suspend, and reactivate policyholders.
Implement methods for payment processing, reminders, and penalties.
Implement methods for creating, updating, and removing/suspending policy products.
Create at least two policyholders who have paid for one of the products and display their account details.
Creating products
life_insurance = Product(100, "Life Insurance", 500)
health_insurance = Product(101, "Health Insurance", 300)
Creating policyholders
  elisha = Policyholder(1, "Elisha Magobo", "emagobo@learner.nexford.org")
  raphael = Policyholder(2, "Raphael Wanjiku", "rwanjiku@nexford.edu")
Policyholders registering for products

  elisha.register_product(life_insurance)
  raphael.register_product(health_insurance)

Policyholders making payments

  elisha.make_payment(Payment(john, life_insurance, 500))
  raphael.make_payment(Payment(mary, health_insurance, 300))

Displaying policyholder details

  elisha.display_details()
  raphael.display_details()
