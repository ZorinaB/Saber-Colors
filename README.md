# Saber-Colors
A small project completed for fun in Python!

Saber_Colors = ["Blue", "Red", "Yellow", "Purple", "Green"] # The array list displays the color options available

print("Your fate lies upon this decision.. \nDepending on which color you choose will decide your role in the StarWars Universe\n ") #Welcome statement

Choice = input("Shall you accept this fate:\n") # gives user choice between continuing or terminating the program

if Choice=='Yes':
    print("Perfect... \nThe saber color options are:",Saber_Colors) # The array list is prompted to display if the user chooses to cont. the program

elif Choice=='No': # Program is terminated with this option
    print("So much potential wasted..\nPerhaps in another lifetime")
    exit()

Saber_Choice = input("Which color will you pick? ") # Displays every color meaning based on which is chosen!
if Saber_Choice == "Red":
    print("\nWelcome to the dark side.. You are a Sidth")
elif Saber_Choice == "Blue":
    print("\nI sense the force is strong within you\nYou are a Jedi Guardian 1 of 3 paths given to Jedi Knights, and you protect the way of the Jedi..\nA difficult task to complete, but you are indeed capable")
elif Saber_Choice == "Purple":
    print("\nHmm.. This is quite confusing indeed.\n You're Samuel L. Jackson?") #Because Samuel's character in the Phantom Meance is the only one who has a purple LightSaber :)
elif Saber_Choice == "Yellow":
    print("\n What a rare opportunity ..You are a Jedi Sentinel! \n 1 of 3 paths chosen after becoming a Jedi Knight..\n You've worked very hard to get here, Congratulations.")
elif Saber_Choice == "Green":
    print("\nAh, yes.. A Jedi Consular ..\nYet another path to take after becoming a Jedi Knight\n You have a strong connection to the Force indeed. ")
