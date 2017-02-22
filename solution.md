CLUE: Footage from an ATM security camera is blurry but shows that the perpetrator is a tall male, at least 6'.

CLUE: Found a wallet believed to belong to the killer: no ID, just loose change, and membership cards for AAA, Delta SkyMiles, the local library, and the Museum of Bash History. The cards are totally untraceable and have no name, for some reason.

CLUE: Questioned the barista at the local coffee shop. He said a woman left right before they heard the shots. The name on her latte was Annabel, she had blond spiky hair and a New Zealand accent.

License Plate L3375A9
Make: Honda
Color: Blue
Owner: Jeremy Bowers
Height: 6'1"
Weight: 204 lbs



//IT HAS TO BE JEREMY BOWERS!!!!
//ANNABEL IS A WITNESS...HER INTERVIEW SPILLED THE BEANS

Julians-MacBook-Pro:interviews julianireland$ cat interview-699607
Interviewed Ms. Church at 2:04 pm.  Witness stated that she did not see anyone she could identify as the shooter, that she ran away as soon as the shots were fired.

However, she reports seeing the car that fled the scene.  Describes it as a blue Honda, with a license plate that starts with "L337" and ends with "9"Julians-MacBook-Pro:interviews julianireland$

Julians-MacBook-Pro:interviews julianireland$ cd ..
Julians-MacBook-Pro:mystery julianireland$ ls
crimescene  interviews  memberships people    streets   vehicles
Julians-MacBook-Pro:mystery julianireland$ cat vehicles

//control+F (Alottt of that until the "grep" ah ha moment)


Julians-MacBook-Pro:memberships julianireland$ ls
AAA     Delta_SkyMiles    REI     Terminal_City_Library
AAdvantage    Fitness_Galaxy    Rotary_Club   United_MileagePlus
Costco      Museum_of_Bash_History  TCSU_Alumni_Association
Julians-MacBook-Pro:memberships julianireland$ cd ..
Julians-MacBook-Pro:mystery julianireland$ grep -r "Jermemy" *
Julians-MacBook-Pro:mystery julianireland$ grep -r 'Jeremy' *
memberships/AAA:Jeremy Bowers
memberships/Delta_SkyMiles:Jeremy Bowers
memberships/Museum_of_Bash_History:Jeremy Bowers
memberships/Terminal_City_Library:Jeremy Bowers
people:Jeremy Bowers  M 34  Dunstable Road, line 284
vehicles:Owner: Jeremy Bowers
Julians-MacBook-Pro:mystery julianireland$ grep -r 'Germuska' *
memberships/AAA:Joe Germuska
memberships/Terminal_City_Library:Joe Germuska
people:Joe Germuska M 65  Plainfield Street, line 275
vehicles:Owner: Joe Germuska
Julians-MacBook-Pro:mystery julianireland$
