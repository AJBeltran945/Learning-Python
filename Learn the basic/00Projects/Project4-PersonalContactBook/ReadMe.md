Project 4 — Personal Contact Book 📇
Difficulty: Beginner to intermediate
Concepts: Dictionaries, sets, lists, tuples, functions, loops, exceptions, type casting.

Build an application that manages a collection of contacts.

This project is particularly useful because it teaches you how to represent real-world information in Python.
Features to implement
1. Add a contact.
2. View all contacts.
3. Search for a contact.
4. Update contact information.
5. Delete a contact.
6. Display all unique cities represented in the contact book.
7. Count the total number of contacts.
A contact might contain:
- Name.
- Phone number.
- Email address.
- City.
- Age.
Example data structure
contacts = {    "Alex": {        "phone": "600123456",        "email": "alex@example.com",        "city": "Palma",        "age": 21    },    "Maria": {        "phone": "611987654",        "email": "maria@example.com",        "city": "Madrid",        "age": 24    }}


Why this project is useful
You'll learn how to work with nested dictionaries, update existing data, and check whether information exists before accessing it.

For example, before retrieving a contact, you should verify that the requested name exists.

You'll also practise exception handling when users provide invalid input.
Additional challenges
- Prevent duplicate email addresses.
- Allow searching by phone number.
- Display contacts alphabetically.
- Group contacts by city.
- Find the oldest and youngest contacts.
- Validate the age using type casting and exceptions.
An important lesson: Phone numbers should generally be stored as strings, not integers. You don't perform arithmetic on them, and strings preserve leading zeros and symbols such as +.
GitHub repository
Suggested name: python-contact-book

Suggested description:
A command-line contact management application built with Python, featuring CRUD operations, nested dictionaries, search functionality, and input validation.