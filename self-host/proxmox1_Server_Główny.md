# PROXMOX1
## Jest to mój pierwszy serwer domowy, na którym mam najważniejsze rzeczy.

## Jakie mam programy?

### [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV?tab=readme-ov-file)
Świetne rozwiązanie dla osób upratych jak ja, które powiedziało sobie że nigdy nie zapłaci Youtubowi.
Instalujecie mały program, najlepiej w dokerze, załączacie skanowanie, wskazujecie urządzenie np. PS4 i gotowe.
Teraz kiedy wyskoczy wam reklama, skrypt ją wyciszy a kiedy tylko będzie możliwość skipuje.

####### **drobna uwaga**
program ten działa przez mDNS (unicast) więc w moim wypadku kiedy strukture miałem taką:
proxmox -> LAN1 <--bridge na opnsense --> LAN2 -> PS4
to niestety miał problem że znalezieniem PS4 (przeszkadzał proxmox ze swoim GIMP snooping).
Najlepiej to połączyć program przez kod jaki można wyciągnąć z PS4 (ten sam do łączenia np. z telefonem) - wtedy niestety działa to tylko do pierwszego restartu.
Dajdzie na 'uklepanie' się wszystkiego dzień, a wtedy (jak w moim wypadku) PS4 wskoczy wam do listy urządzeń, dodajecie, kod usuwanie i gotowe.
