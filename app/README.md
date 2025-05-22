ID Generator
A package used to generate random ids of variable lengths and types.

How to use
After installing the package use following import:

from idgenerator import generate_password,generate_guid,generate_credit_card_number, generate_pin_number, generate_object_id

Then use following commands:

password = generate_password(length= 'your_desired_length')

guid = generate_guid()

credit_card_number = generate_credit_card_number(length='your_desired_length')

pin = generate_pin_number(length='your_desired_length')

objid = generate_object_id()