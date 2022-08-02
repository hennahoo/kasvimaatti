# Kasvimaatti

Kasvimaatti on kotiprojekti jonka tarkoituksena on luoda automaatio kasvihuoneeseen.
https://koodinkutoja.com/raspi-muuttaa-kasvihuoneeseen/
https://koodinkutoja.com/ilmankosteusanturin-ja-lcd-nayton-liittaminen-rpihin/

Kasvimaatin avulla voidaan tarkkailla lämpötilaa, kosteutta ja ohjata kastelua erilaisten antureitden ja Raspberry Pi -tietokoneen avulla.
Idea lähti vuonna 2016, kun pihaan ilmestyi kasvihuone. Kasvimaatti vol 1.0 sai alkusysäyksen. 


## Kasvimaatin historia


Ensimmäisessä versiossa toteutettiin nettisivu, wordpress sivun sisään upotettiin php- sivu joka keräsi lämpötiloja. Yksinkertaisella IO -kytkimellä pystyttiin 
kontrolloimaan pumppua. Tietoturvaa varten, nettisivut olivat https/tsl suojattu/salattu protokolla, ja sivuille piti
syöttää käyttäjätunnus ja salasana ennenkuin pääsi pumppaamaan vettä ja katsomaan kuvaa.

Raspiin kytkettiin pi -kamera. Kameralla saatiin striimattua vesiastiaa johon vettä pumpattiin. Idea oli alunpitäen tuottaa suoraa striimiä siitä mitä kasvihuoneessa tapahtui, 
tylsää katseltavaahan se olisi ollut, koska huoneessa ei muuten tapahtunut muuta. Yksi idea oli toteuttaa timelapse tyyppinen kollaasi siitä kuinka siemenet itävät, niistä kasvaa pieniä
taimia ja kehittyvät kasveiksi.


# Nyt ja tulevaisuus

Uudempi ja parempi toteutus 2.0 on tekeillä.



# Kasvimaatti

Kasvimaatti is a homemade project which was developed started in 2016. Small greenhouse was raised on the yard also we get idea to have a project to collect some temperatures.
The idea was to make automation on home greenhouse. First version was only a try out what could Raspberry Pi
computer can handle. Storing the measured temperature and humidity and other sensor values to the Database.
Then visualizing the data to the web - page.


## History


First version included website was made with wordpress.  Inside of wordpress was embbed php site which collected temperatures.  With simple IO switch we were able to controlling waterpump.
It was not so glorious or practical but it was a good start point. web site included security like https protocol and login. But it wasn't very mobilefriendly or handy at all. The idea was 
only make a demo and afterwards make improvements and develop it further. 

Pi camera was attached to Raspberry Pi it was on streaming purpose. The main idea was to produce live stream from the greenhouse but it would have been so boring that we decide
not to do it. One idea was to stream and commit a timelapse where could see how does seed grow on plant. 

