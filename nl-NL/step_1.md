Controleren of een item in een lijst staat, is eenvoudig in Python: je kunt het trefwoord `in` gebruiken zoals in het voorbeeld hier. Als het item in de lijst staat, wordt het bericht "Gevonden!" afgedrukt.

```python
zoek_item = "papier"
items = ["steen", "papier", "schaar"]

if zoek_item in items:
    print("Gevonden!")
```

Je kunt ook een lus gebruiken om een beetje code uit te voeren totdat een item in een bepaalde lijst blijkt te staan. Dit is handig voor het valideren van invoer. Hieronder gebruiken we het tegenovergestelde van het `in` trefwoord: `not in`.

```python
richting = ""
while richting not in ["N", "Z", "O", "W"]:
    richting = input("Voer een richting in (N, Z, O of W): ")
print(richting)
```

Deze lus blijft vragen om een richting totdat de gebruiker er een invoert die in de lijst staat. Nadat ze een van de mogelijke richtingen hebben ingevoerd, wordt die richting afgedrukt.
