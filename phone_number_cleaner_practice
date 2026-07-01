phone_number = input("please enter your number: ")

cleaned_number = ""

for character in phone_number:
    if character.isdigit():
        cleaned_number += character 
    elif character.isalpha():
        raise ValueError("Letters not allowed.")
    elif character in " () - . +":
        pass
    else:
        raise ValueError("punctuations not permitted")
print(cleaned_number)