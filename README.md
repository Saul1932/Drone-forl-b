## Drone-forløb

# Problemformulering:
Hvordan kan vi lave en spændende og unik kontroller til en drone? Vi vil prøve at lave en motionkontrollerede kontroller til en drone, altså hvor dronen styres af bestemte bevægelser og tegn fra et facecam. I projektet har vi en trello drone til rådighed.

## Ide-genering:


<img width="328" height="251" alt="image" src="https://github.com/user-attachments/assets/70f039f9-fb58-4693-b685-f5f53666e6ec" />

Som man kan se på ovenstående billede valgte vi en motionkontrollerede kontroller

## Systemets muligheder

Vi har undersøgt systemet og fundet ud af, at det er muligt at kode det vha. af det såkaldte "Tellopy"

https://github.com/damiafuentes/DJITelloPy

Vi vil så prøve at lave en kode, der kan sende nogle specifikke outputs baseret på tegn/bevægelser til vores Tellopy kode (der så instruerer selve dronen) 

## Skitse

<img width="1339" height="342" alt="image" src="https://github.com/user-attachments/assets/4384da1c-8e81-4577-a1bd-427cc567d5c0" />



## Flowchart:

<img width="164" height="346" alt="image" src="https://github.com/user-attachments/assets/a263ea02-ba71-42d3-a6a9-f288eeb61493" />

## 3-lagsmodellen

* Præsentationslag:
  Dronens kamera opfanger bestemte tegn, og sender det videre til logiklaget
* Datalaget:
  Opbevarer de forskellige tegns definitioner (f.eks. hvor mange fingre et bestemt tegn skal bruge)
* Logiklaget:
  De bestemte/specifikke tegn oversættes til bestemte bevægelser vha. definitioner, der er lagret i datalaget. Denne oversættelse sendes tilbage til præsentationslaget og udføres! 





## Blokdiagram

<img width="889" height="615" alt="image" src="https://github.com/user-attachments/assets/58677542-384e-42df-a60d-326eb40e02e3" />

## Brugertest

* Kort introduktion (uden hjælp til at lære tegnene, der instruere dronen)
* Prøver de forskellige funktioner (indtil brugeren har fundet ud af det) - noterer ned, hvis vi oplever problemer med tegnenes brugervenlighed (noterer ned hvis vi oplever problemer)
* Prøver at "skitsere" en firkant ved hjælp af de nylærte funktioner med dronen


Under brugertesten fandt brugeren hurtigt ud af kommandoerne til at flyve henholdsvist fremad, op, ned, højre og venstre. Men havde problemer med at flyve tilbage, da tegnet/kommandoen ikke var lige til. Hermed skal vi få forbedrede tegnet, og gøre det mere klart/naturligt at tegnet passer til at gå tilbage. 

Kort brugertest med Adam:











## Links:
https://miro.com/welcomeonboard/Nkd4T2lHaHVJV3BDUEt2Ui92aG5HSmE5VVE5ZzN5L3FqaWY5a2orcnB4cTZ2ay8vUVJ3SG1XRGVvTFp5aDhEVzJZMlR3eklPN1QyQjZpdnZQNUcya200Tm5XY29ZNDg3ZG5tbklJZ2RlcnVySjA5dFNnR09EWThWLzlHdDRXSHdzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=649122413320








