#  Projekt: Instalace a upgrade subwooferu (JBL Club 1200P 12")

Vítejte v mém repozitáři zaměřeném na audio projekt instalace, provozu a následného předělávání 12" subwooferu **JBL Club 1200P** (400W RMS) do jiného auta. Tento projekt slouží jako můj osobní deník, návod pro ostatní a přehled technických řešení včetně problémů, se kterými jsem se během instalace potýkal.

---

##  Přehled projektu & Audio komponenty

Cílem projektu bylo dosáhnout čistého a hutného basového základu v autě bez toho, aby docházelo k přetěžování elektrické sítě vozidla.

### Specifikace hlavního komponentu
* **Model:** JBL Club 1200P
* **Typ:** Pasivní subwoofer v ozvučnici
* **Průměr:** 12" (300 mm)
* **Výkon:** 400W RMS / 1200W Peak
* **Impedance:** Technologie SSI™ (Smart Selectable Impedance) – možnost přepínání mezi **2 Ω** a **4 Ω** (klíčové pro flexibilitu při změně zesilovače!).

---

##  Teoretický základ: Anatomie subwooferu
Než se pustíte do čtení instalačního deníku, zde je rychlý přehled toho, z čeho se tento subáč skládá a proč funguje tak dobře:

1. **Koš (Basket):** Pevné šasi, které drží celou konstrukci pohromadě. U JBL je navrženo tak, aby minimalizovalo rezonance při plném výkonu 400W RMS.
2. **Membrána (Cone):** Polypropylenová kónická membrána, která tlačí vzduch a vytváří akustický tlak. Je lehká a tuhá.
3. **Závěs (Surround):** Masivní gumový lem umožňující vysokou lineární výchylku (*Xmax*) pro hluboké basy.
4. **Středící křidélko (Spider):** Textilní vlnovec, který drží kmitací cívku přesně uprostřed magnetického pole.
5. **Kmitací cívka (Voice Coil):** Srdce subwooferu. Protékající proud ze zesilovače zde vytváří elektromagnetické pole. JBL má pokročilé chlazení, aby cívka zvládla dlouhodobou zátěž.
6. **Magnet:** Masivní feritový prstenec na zadní straně, který dává subwooferu sílu a přesnou kontrolu.
7. **Prachovka (Dust Cap):** Středový kryt chránící cívku před nečistotami.
 <img src="Fotky/fotceka.jpg" alt="Memecko" width="100%">

---

##  Deník instalace (Instalační fáze)

###  První auto [Škoda Superb I]
Moje první auto vyrobeno v roce 2008, najeto 400 000km v bídném vizuálním stavu, idealní kandidát na subwoofer.

* **Příprava kabeláže:** Plusový kabel od baterky byl protáhnut u strany řidiče, kde se nacházi řídící jednotka, je tam svazek kabelu a misto pro plusový tam je. Bez pomoci svého bratrance, který se tím zabývá bych to opravdu sám nedokázal. Poté se navedl kabel po levé straně skrz interier až do kufru.
* **Uzemnění (Kostra):** Mínusový kabel byl uzemněn ke kostře na ram kufru. Musela se obrousit barva smirkovacím papírem a drátěným kartáčem.
* **Zapojení zesilovače:** Zesilovač byl přišroubován přímo na subwoofer RCA kabely (stíněné kabely k přenosu zvuku)vedou prostředkem pod sedačkami.
* **Výsledek:** Celkově to bylo náročné a sranda to moc nebyla, zabralo to celý den. ///Jak to v tomhle autě hrálo, jaké jsi měl pocity.

###  Předělávka do druhého auta [Škoda Octavia II]
*Tady popiš proces stěhování hudby do nového auta. Přestavba je málokdy stejná!*

* **Rozdíly v instalaci:** V čem to bylo jiné? Mělo nové auto lepší přístup skrz motorovou stěnu? Bylo potřeba koupit delší kabely?
* **Změna konfigurace:** Využil jsi u JBL přepínač impedance **SSI (2 vs 4 ohmy)**, protože jsi měnil nebo jinak zapojoval zesilovač?
* **Akustika:** Hraje to v tomhle autě líp nebo hůř než v tom prvním? (Např. kvůli jinému typu karoserie - sedan vs. hatchback).

---

##  Problémy během instalace a jejich řešení (Troubleshooting)

*Během montáže autohudby se vždycky něco pokazí. Tady jsou nejčastější faily, které můžeš promazat nebo doplnit o své vlastní:*

####  Problém 1: Rušení v reproduktorech (Pískání podle otáček motoru)
* **Příčina:** Napájecí kabel a signálové RCA kabely byly taženy na stejné straně auta (v jednom prahu), což indukovalo interference od alternátoru do audia.
* **Řešení:** Kompletní rozebrání prahů. Napájecí kabel tažen levým prahem, signálové RCA kabely pravým prahem. Pískání kompletně zmizelo.

####  Problém 2: Pohasínání světel / palubky při basových špičkách
* **Příčina:** Velký nárazový odběr proudu při úderech subwooferu (400W RMS už dokáže s napětím zamávat).
* **Řešení:** Posílení ukostření baterie v motorovém prostoru (tzv. *The Big Three upgrade*) / přidání kapacitoru / výměna staré autobaterie za silnější AGM baterii.

####  Problém 3: Subwoofer po zapnutí hned vypne zesilovač (Protect mode)
* **Příčina:** Špatně nastavená impedance na subwooferu vs. stabilita zesilovače. Zesilovač neuměl pracovat do 2 ohmů.
* **Řešení:** Využil jsem chytrou funkci JBL wooferu a přepnul SSI spínač na **4 ohmy**. Zesilovač přestal padat do ochrany a hraje stabilně.

####  Problém 4: [ZDE DOPLŇ SVŮJ VLASTNÍ PROBLÉM, KTERÝ TĚ POTKAL...]
* *Příčina:* ...
* *Řešení:* ...

---

##  Výsledné hodnocení & Zkušenosti
* **Přesnost basů:** Jak stíhá tenhle 12" reproduktor rychlejší žánry (Rock/Metal/DnB) vs. hluboký Rap?
* **Celkové hodnocení:** Splnil JBL Club 1200P tvoje očekávání?

---
*Pokud řešíte podobný problém s instalací autohudby, klidně otevřete **Issue** nebo nahoďte **Star**! *
