contacts = {}

print("=== Contact Management System ===")

name = input("Enter contact name: ")
phone = input("Enter phone number: ")

contacts[name] = phone

print("\nContact Saved Successfully!")

print("\nContact List:")
for name, phone in contacts.items():
    print("Name:", name)
    print("Phone:", phone)
