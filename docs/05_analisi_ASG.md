Membre 2: [Alejandro Josue Marquez Holguin] — [rol per completar]
Membre 3: [Jesús Atset Moreno] — Identificació dels aspectes ASG, matriu, selecció de prioritats i canvis al projecte

**Repte:** reduir els residus no reciclables i millorar la recollida selectiva als barris de L'Hospitalet de Llobregat.

**Idea inicial del projecte:** una web/app senzilla per al veïnat i els comerços («on va això?», calendari i punts de recollida, mapa de contenidors) i un tauler de dades per a l'Ajuntament, acompanyada d'una campanya de sensibilització amb les AAVV i les escoles (vegeu `04_grups_interes.md`).

---

## 1. Identificació dels aspectes ASG

| # | Categoria | Aspecte | Tipus | Explicació breu |
| :-: | :--- | :--- | :--- | :--- |
| A1 | Ambiental | Augment de la recollida selectiva i reducció del rebuig | Oportunitat | Si el veïnat separa millor (causa D1), es recupera més material i la ciutat s'acosta a l'objectiu del 55% de la UE (ara és inferior al 30%). |
| A2 | Ambiental | Impacte digital i material del projecte (servidors, mòbils, fullets impresos) | Risc | L'app i la campanya també consumeixen energia i generen residus (paper, cartells). És un impacte petit, però existeix. |
| S1 | Social | Bretxa digital | Risc | Gent gran, famílies amb menys recursos i persones que no parlen català ni castellà poden quedar fora si la informació només és a l'app. |
| S2 | Social | Carrers més nets i millor convivència als barris | Oportunitat | Menys contenidors desbordats i menys olors (conseqüència C2). Les AAVV hi poden participar directament. |
| S3 | Social | Incentius o canvis en la taxa de residus | Risc i oportunitat | Un sistema de bonificacions motiva a reciclar (causa I2), però si es penalitza qui recicla menys pot perjudicar les llars més vulnerables. |
| G1 | Governança | Protecció de dades personals | Risc | Si l'app guarda l'adreça, l'ús o dades per habitatge, cal complir l'RGPD. Una filtració afectaria la confiança de tot el projecte. |
| G2 | Governança | Col·laboració i dades obertes entre Ajuntament, AMB i empresa de recollida | Risc i oportunitat | Compartir dades per barris permet decisions millors i transparència, però depenem que aquests actors les vulguin cedir i que siguin fiables. |
| G3 | Governança | Continuïtat i responsabilitat del servei | Risc | El projecte el fan estudiants: si no hi ha un responsable clar (Ajuntament o entitat), l'app pot quedar desactualitzada o abandonada. |

---

## 2. Matriu de riscos i oportunitats ASG

Llegenda: 🔴 Risc · 🟢 Oportunitat · 🟡 Risc i oportunitat

| Impacte \ Freqüència | Improbable | Ocasional | Freqüent |
| :--- | :---: | :---: | :---: |
| **Catastròfic o alt** | | 🔴 G1 Protecció de dades <br> 🟢 A1 Més recollida selectiva | |
| **Moderat** | | 🟢 S2 Carrers més nets <br> 🟡 S3 Incentius / taxa <br> 🟡 G2 Dades i col·laboració | 🔴 S1 Bretxa digital <br> 🔴 G3 Continuïtat del servei |
| **Insignificant o baix** | 🔴 A2 Impacte digital i material | | |

Les caselles de la part superior dreta són les prioritàries. Els elements més rellevants són **S1**, **G3**, **G1** i **A1**.

---

## 3. Justificació de la probabilitat i de l'impacte

| Aspecte | Freqüència | Impacte | Justificació |
| :--- | :---: | :---: | :--- |
| A1 Més recollida selectiva | Ocasional | Alt | No passarà automàticament: depèn que el veïnat canviï d'hàbits. Si passa, afecta tota la ciutat, el cost de gestió (C3) i les emissions (C4). |
| A2 Impacte digital i material | Improbable | Baix | Una web senzilla consumeix poc i els materials impresos es poden limitar. Es corregeix fàcilment. |
| S1 Bretxa digital | Freqüent | Moderat | Passarà segur en part de la població, sobretot en barris densos i amb menys recursos. Es pot compensar amb canals no digitals. |
| S2 Carrers més nets | Ocasional | Moderat | Depèn també de la ubicació dels contenidors i de les rutes de recollida, no només del projecte. |
| S3 Incentius / taxa | Ocasional | Moderat | Només passarà si l'Ajuntament decideix aplicar-los. Afectaria l'economia de moltes famílies, però es pot dissenyar de manera justa. |
| G1 Protecció de dades | Ocasional | Alt | Una filtració no és habitual si l'app està ben feta, però les conseqüències serien greus: sanció, pèrdua de confiança i fi del projecte. |
| G2 Dades i col·laboració | Ocasional | Moderat | Les administracions publiquen algunes dades, però no sempre per barris ni actualitzades. Sense elles el projecte perd valor, però pot continuar. |
| G3 Continuïtat del servei | Freqüent | Moderat | És molt habitual que els projectes acadèmics s'aturin quan s'acaba el curs. El problema es pot gestionar si s'acorda un responsable des del principi. |

---

## 4. Risc i oportunitat prioritaris

### Risc prioritari: S1. Bretxa digital

**Per què l'escollim:** és freqüent i afecta precisament el grup que la Part 4 de `04_grups_interes.md` considera protagonista, el veïnat, i en especial les famílies amb menys recursos i la gent gran. Si aquestes persones no s'informen, no separaran millor, i la solució no funcionarà on més es necessita. L'hem triat per davant de G1 perquè, tot i que una filtració seria més greu, la bretxa digital és molt més probable i passarà des del primer dia.

**Mesures per reduir-lo:**
- **Canals no digitals:** cartells amb codi QR i dibuixos als contenidors, i fulls informatius a les escales de veïns, fets amb les AAVV.
- **Accessibilitat i idiomes:** web adaptable (bon contrast, text gran i icones, segons les pautes WCAG) i versions en les llengües més parlades als barris.
- **Punts d'informació presencials:** xerrades a les AAVV i parades als mercats municipals, on l'alumnat expliqui com separar i com fer servir l'app.
- **Escoles com a pont:** l'alumnat de les escoles explica a la família què va a cada contenidor.

### Oportunitat prioritària: A1. Augment de la recollida selectiva

**Per què l'escollim:** és l'objectiu principal del repte i té l'impacte més alt. Beneficia el veïnat (carrers més nets), l'Ajuntament (menys cost de tractament del rebuig) i l'AMB (menys pressió sobre els ecoparcs).

**Mesures per aprofitar-la:**
- **Retorn de dades per barri:** publicar al tauler el percentatge de recollida selectiva de cada barri, perquè el veïnat vegi l'efecte del seu esforç (causa I2).
- **Prova pilot mesurable:** començar en un o dos barris amb la taxa més baixa, mesurar abans i després amb dades de l'AMB i l'empresa de recollida, i ampliar si funciona.
- **Reptes entre barris o escoles:** petits reconeixements (no econòmics) per als barris o centres que més millorin.

---

## 5. Canvis que introduirem al projecte

1. **De «només app» a solució mixta:** l'app serà una eina més, no l'única. La campanya presencial i en paper amb AAVV, escoles i mercats passa a ser part central del projecte.
2. **Privacitat des del disseny:** l'app no demanarà registre per consultar informació. Si cal recollir dades, seran anònimes i agregades per barri, mai per habitatge, i informarem clarament de per a què es fan servir (RGPD).
3. **Accessibilitat i multilingüisme:** disseny segons WCAG i textos en diverses llengües des de la primera versió.
4. **Incentius justos:** proposarem a l'Ajuntament bonificacions o reconeixements per participar, no penalitzacions que perjudiquin les famílies vulnerables.
5. **Responsable i continuïtat:** abans de començar acordarem amb l'Ajuntament o una entitat qui mantindrà l'app i les dades quan acabi el curs.
6. **Transparència en els resultats:** explicarem com calculem els indicadors (percentatge de selectiva, quilos evitats) i amb quines dades oficials, perquè es puguin comprovar.
7. **Menys impacte propi:** web lleugera, allotjament amb energia renovable si és possible i poc material imprès, reutilitzable o en paper reciclat.

---

## Fonts d'informació consultades

- Agència de Residus de Catalunya. *Estadístiques de residus municipals*. https://residus.gencat.cat/ca/consultes_i_tramits_-_nou/estadistiques/
- Ajuntament de L'Hospitalet. *Moció pel foment del reciclatge a L'Hospitalet* (Ple de 25 de febrer de 2025). https://seuelectronica.l-h.cat/mocions/doc/1933.pdf
- AMB. *Compartim un Futur – Aprenentatge servei ambiental*. https://www.amb.cat/s/web/ecologia/sostenibilitat/educacio-ambiental/aps.html
- Comissió Europea, CORDIS. *MUV – Mobility Urban Values* (exemple d'app amb gamificació i dades anonimitzades). https://cordis.europa.eu/project/id/723521
- Reglament (UE) 2016/679, General de Protecció de Dades (RGPD). https://eur-lex.europa.eu/eli/reg/2016/679/oj
- W3C. *Web Content Accessibility Guidelines (WCAG) 2.2*. https://www.w3.org/TR/WCAG22/
- Treballs previs de l'equip: `01_necessitats.md`, `02_repte_i_ODS.md`, `03_causes_i_impactes.md` i `04_grups_interes.md`.
