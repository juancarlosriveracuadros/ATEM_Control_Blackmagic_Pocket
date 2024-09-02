Hello :) 

Ich dachte mir, ich mach mal ne Gruppe, damit Marcus das auch noch mitbekommt. Er hat ja auch schon Erfahrungen damit, zumindest Tally Infos Kabellos zu übertragen.

Nochmal als Recap:
Wir haben jetzt eine Mobile Kamera die das Bild Signal über Funk an unsere Videoregie überträgt. Diese Funkverbindung ist unidirektional. Die anderen Kameras sind mit 2 Kabeln verbunden und können Bidirectional arbeiten. Dadurch kann das Livestream Team von der Regie aus, die Kameras steuern mit Berlichtung, Weissabgleich, Fokus etc.

Hier jetzt der Scope von diesem Projekt: 
- Damit die Person die die Mobile Kamera trägt, sich voll auf die Perspektive und das laufen konzentrieren kann, wollen wir es ermöglichen, dass die Belichtung dafür auch von der Regie aus gesteuert wird.
- Das ganze muss dann natürlich auch Wireless funktionieren.
- Das System sich selbstständig aktivieren und jederzeit bereit sein
- Das System sollte so Robust sein, dass man keine Einschaltreihenfolge etc. beachten muss --> Idiontensicher ist das Stichwort
- Das System sollte nicht mehr als ca. 150€ in Hardware kosten
- Jeder Code muss so dokumentiert werden, dass auch andere in Zukunft daran arbeiten können
- Es wäre cool, wenn wir das in 4 Wochen hin bekommen, bevor du dann wegziehst

Noch eine Info, Marcus korrigiere gerne wenn ich falsch liege. Wir haben aktuell schon etwas im Einsatz, das eine ähnlich Funktion ausführt. (Das lässt sich aber nicht weiterentwickeln, um dieses Projekt zu realisieren.) Dabei handelt es sich um dieses Projekt: https://github.com/AronHetLam/ATEM_tally_light_with_ESP8266?tab=readme-ov-file Dabei geht es aber nur um die Funktion des Tally Lights. Es gibt einen Master und 3 Tally Units. An den Tally Units sind LEDs angebracht die dann einfach leuchten, wenn die Kamera live ist. Der dort verwendete Microcontroller kann nur Wifi und kein Bluetooth, deswegen lässt sich damit unser Projekt nicht realisieren. Wir könnten aber überlegen, das mit den LEDs auch ins neue Projekt zu nehmen, damit wir nicht 2 solcher System parallel laufen haben (und ggfs. warten müssen)

Am besten wir schauen uns das am Sonntag nochmal kurz zusammen an :) 
Ich vermute nicht, dass für dich hiermit alles klar ist, also stelle gerne alle Fragen 🙌🏼


example with LED:
https://github.com/AronHetLam/ATEM_tally_light_with_ESP8266?tab=readme-ov-file

Emulator ATEM:
https://github.com/DylanSpeiser/BM-Camera-Control-WebUI
