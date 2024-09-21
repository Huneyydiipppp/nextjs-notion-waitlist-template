# NEW WAITING LIST FOR TYLER'S HOME TEXAS RUSTIC DESIGN GROUP
# Collect customer information
customer_name = input("Enter customer's name: ")
customer_email = input("Enter customer's email: ")
customer_phone = input("Enter customer's phone number: ")

# Store customer information in a tuple
customer_info = (customer_name, customer_email, customer_phone)

# Add customer information to the waiting list
waiting_list.append(customer_info)

print("Customer added to the waiting list.")
# Sign up for "Are You Home Yet?" updates
signup_choice = input("Would you like to sign up for 'Are You Home Yet?' updates? (yes/no): ").lower()

if signup_choice == 'yes':
    print("Great! You've been signed up for 'Are You Home Yet?' updates.")
    # Here you would typically add code to handle the signup process,
    # such as adding the customer to a mailing list or database
else:
    print("No problem. You can always sign up for updates later.")

