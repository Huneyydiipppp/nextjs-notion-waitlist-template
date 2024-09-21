# NEW WAITING LIST FOR TYLER'S HOME TEXAS RUSTIC DESIGN GROUP

waiting_list = []

def add_to_waiting_list(name, contact_info):
    waiting_list.append({"name": name, "contact_info": contact_info})
    print(f"{name} has been added to the waiting list.")

def remove_from_waiting_list(name):
    for customer in waiting_list:
        if customer["name"] == name:
            waiting_list.remove(customer)
            print(f"{name} has been removed from the waiting list.")
            return
    print(f"{name} was not found in the waiting list.")

def display_waiting_list():
    if not waiting_list:
        print("The waiting list is currently empty.")
    else:
        print("Current Waiting List:")
        for index, customer in enumerate(waiting_list, 1):
            print(f"{index}. {customer['name']} - {customer['contact_info']}")
      




