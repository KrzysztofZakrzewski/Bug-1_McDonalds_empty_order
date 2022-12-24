# Bug-1_McDonalds_empty_order


Error found in McDonald's cash register. Error allows to create and sell empty order for 0 PLN (zero PLN).


Reproduction steps:

1.	Create a new order adding eny product (cheeseburger, french fries, etc.) from "classic menu" ("oferta klasyczna"). 
1.1.	 For this example we use cheeseburger
2.	Add eny " ("Promocje") (Drwal, Veggie Warp, etc.)
3.	Remove standart produckt from "classic menu" (cheeseburger).
4.	Push "Breakfasts" ("Śniadania") button to get in to breakfests menu
5.	Push "Menu PW" buton ("Zestaw PW") or "Menu SR" ("Zestaw SR") to create any menu with Promotion burger.


The Real result: 
All position in the order will disappear. This should not happen. We can push empty order for sell pushing „take away” („Na wynos”) or „Here” („Na miejscu”) button. After click  „Zgodna kwota” („matching amount”) we can sell empty order for 0 PLN (ZERO PLN)


The Expected result:
1.	Last product on the list should not disaper.
2.	Should appear a grey POPup with information: "Nie można anulować tej pozycji" witch "Ok" button to close it and "NP^6" orange logo.
