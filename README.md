# Assignment2-Ranga
# PRUDHVIRAJU
###### Albert Hall Museum

 Situated in the Ram Niwas Garden of Jaipur, the Albert Hall Museum is the oldest museum in **Rajasthan**. Built in 1876, it was initially envisioned to be a concert hall and resembles the architecture of the Victoria and Albert Hall Museum in London, hence, the name. It is a standing example of the Indo-Saracenic architecture and is **also known as Government Central Museum**.
 - - -
 # Directions To Museum
 Jaipur International Airport.
1. Continue to Surajpura
2. Follow Jawahar Lal Nehru Marg to Rina Rd in Ashok Nagar
3. At Jawahar Circle, exit onto Jawahar Lal Nehru Marg/Malviya Nagar Rd
4. Keep right to stay on Jawahar Lal Nehru Marg
5. At Gandhi Cir, take the 3rd exit and stay on Jawahar Lal Nehru Marg
6. Use any lane to turn left after the park 

# Places Near By
- Peacock Garden
- Gems Paradise
- Bapu Bazar
- Ellora Arts
- Fort

[AbutMefile](AbutMe.md)
- - - 
# City to visit
Intro:-In This Table we are going to create a table with cities and 
recommendation to someone visit.


| CITY      | LOCATION TO VISIT | TIME TO SPEND |        
| ---       | ---               |  ---          |
| HYDERABAD | CHARMINAR         |   3H          |
| MUMBAI    | TAJ HOTEL         |   2H          |
| DELHI     | TAJMAHAL          |   4H          |  
| CHENNAI    | TEMPLE    | 2h|

***

# PITHY QUOTES

> Imitation is suicide  -- *Ralph Waldo Emerson*

> Flatter yourself critically -- *Willis Goth Regier*

***
# CODE FENCING

How to write code get Latest Twitter Status?

[Question](https://stackoverflow.com/questions/19653695/java-how-do-i-get-the-latest-tweet-for-a-particular-user)

```
<?php

function getTwitterStatus($userid){
$url = "https://api.twitter.com/1/statuses/user_timeline/$userid.xml?count=1&include_rts=1callback=?";

$xml = simplexml_load_file($url) or die("could not connect");

       foreach($xml->status as $status){
       $text = $status->text;
       }
       echo $text;
 }

// USAGE
getTwitterStatus("chriscoyier");

?>

```

[code snippet](https://css-tricks.com/snippets/php/get-latest-twitter-status/)

***









