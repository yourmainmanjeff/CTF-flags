its called WaterHot

You are an intern at the new BENU CTF company, and there is an unkown user going around and leaking flags! the main cyber team are working on reverse engineering and they decide to give you a single photo from the case for you to work on. find out who this leaker 
is and where he is so we can stop him from leaking any more flags!

the flag format is:
FLAG{facebook description-Resturaunt name-Username-Password} MAKE SURE TO PUT IT IN ALL CAPS AND USE THE DASHES

FLAG{XXXXXXXX-XXXXXXXX-XXXXXXXXXXX-XXXXXXXXXXXXXXXXXXXXXX}

they will get this photo:

whatphotoisthis.png 

this photo will contain two things:
coordinates and a username (they can find the username in the details and coordinates if they use exiftool or another image tool)

the corrdinates will have the location of the resturaunt and the name. 25.064204, -77.479442 -> AQUAFIRE

the username will lead to a facebook profile with the bio, and the facebook will expose whats been happening, it will also lead to his github page, where he accidently leaked a txt file with his passwords.
SSPSYCHS2E3 https://www.facebook.com/SSPSYCHS2E3/ GJDK564

it will also have a post, where he accidently leaked a txt file with his passwords.

the flag is FLAG{GJDK564-AQUAFIRE-SSPSYCHS2E3-IFUCANREADTHISURDUM56!}
