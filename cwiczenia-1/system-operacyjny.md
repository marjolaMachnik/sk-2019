System operacyjny w środowisku sieciowym
=========================================

Charakterystyka systemu operacyjnego
------------------------------------

| Charakterystyka | wartość           | komentarzu |
| ------------- |:-------------:| -----:|
| nazwa      | Linux | Ubuntu |
| program (parametry sieci)      |Oracle VM VirtualBOX |NAT|


Konfiguracja połączenia sieciowego
----------------------------------

| Parametr | wartość           | komentarzu |
| ------------- |:-------------:| -----:|
| Adres IP      | 10.0.2.15 | przydzielony przez DHCP |
| Maska podsieci      |255.255.0.0| route -n |
| Brama      |169.254.0.0| route -n |
| DNS 1   |10.10.0.8| Network Settings |
| DNS 2   |10.10.0.4| Network Settings |

Schemat sieci
-------------
![alt schemat](https://github.com/marjolaMachnik/sk-2019/blob/master/cwiczenia-1/Untitled%20Diagram.png)

