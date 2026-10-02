---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
artist: ""                       # subtitel / naam van de maker(s)
date: {{ .Date }}                # datum + starttijd van de avond, bv 2026-11-21T20:00:00+01:00
end_date: ""                     # optioneel, alleen invullen bij meerdaagse evenementen
time_start: "20:00"
time_end: "21:30"
venue: ""                        # bv "Het Klooster, Rotterdam"
address: ""                      # optioneel: volledig adres, voor als het afwijkt van de standaardlocatie
price: ""                        # weergave, bv "€ 16,50"
price_amount: 0                  # numerieke prijs voor zoekmachines, bv 16.50
price_currency: "EUR"
ticket_url: ""                   # laat leeg om terug te vallen op de algemene Stager-shop
type_label: ""                   # bv "KLEINKUNST / COMEDY"
accent: "red"                    # red / black / yellow
poster_title: ""                 # optioneel: titel met <br> voor de poster, anders wordt de titel gebruikt
poster_script_word: ""           # optioneel: schuingedrukt "handgeschreven" woord op de poster
pinned: false                    # forceer deze avond als uitgelicht op de homepage
sold_out: false
image: ""                        # foto van de artiest(en), getoond op de detailpagina en gedeeld op social media
image_alt: ""
program_note: ""                 # korte toelichting onder "Het programma"
draft: true
---

Beschrijving van de avond.
