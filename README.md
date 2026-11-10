# Els Trens de la Llibertat: Nicholas Winton 🕊️
### Recurs Web Educatiu de Comprensió Lectora (DUA + WCAG 2.1 AA)
**Cicle Superior d'Educació Primària (5è i 6è) · Àrea de Llengua Catalana i Educació en Valors**

---

## 📌 1. Context i Objectiu Pedagògic

Aquest recurs és una aplicació web d'una sola pàgina (*Single Page Application*) dissenyada amb **criteri tecnopedagògic** per treballar la competència comunicativa lingüística (comprensió lectora) a través d'un text narratiu-històric adaptat sobre la **Segona Guerra Mundial**: la gesta real de Nicholas Winton i el rescat de 669 infants (*Kindertransport*).

### Objectius d'aprenentatge:
* Desenvolupar estratègies de comprensió lectora en quatre dimensions clau:
  1. **Comprensió literal:** localització i extracció d'informació explícita en paràgrafs delimitats `[P1] - [P4]`.
  2. **Inferència i vocabulari en context:** deducció del significat d'expressions i paraules en context (com ara l'adjectiu *titànica* o el terme *visat*).
  3. **Estructura i seqüència temporal:** ordenació cronològica dels esdeveniments històrics.
  4. **Valoració crítica i moral:** reflexió sobre la solidaritat, el coratge cívic i l'educació per a la pau.

---

## 🛡️ 2. Protecció de Dades: Anàlisi del Registre d'Aula (RGPD / LOPDGDD)

Com a **dissenyador tecnològic amb criteri pedagògic**, l'atenció al requisit de registre de l'alumnat requereix complir estrictament la legislació de protecció de dades de menors (RGPD Art. 8 i LOPDGDD, aplicable a menors de 14 anys a l'Estat espanyol i a Catalunya):

1. **Principi de minimització de dades (Privacy by Design):**
   * L'alumnat es registra mitjançant el seu **nom de pila o àlies d'aula** (p. ex., *Laia*, *Marc G.* o *Equip Blau*) i la selecció del seu **grup classe** (*5è A*, *6è B*...).
   * **Mai es sol·liciten cognoms complets, correu electrònic, contrasenyes ni dades personals sensibles.**
2. **Emmagatzematge 100% local i volàtil:**
   * La informació del registre no s'envia a cap servidor ni base de dades externa.
   * Queda guardada únicament a la sessió del navegador de l'alumne per a la personalització de l'activitat i la generació del **Diploma i Informe d'Aprofitament Lector imprimible en PDF** per al mestre/a.
3. **Transparència didàctica:**
   * S'inclou un avís visible i entenedor per a l'alumnat explicant per què es demana el nom i com es protegeix la seva intimitat.

---

## ♿ 3. Accessibilitat Web (WCAG 2.1 / 2.2 Nivell AA)

* **Contrast cromàtic certificat:** Ràtios de contrast superiors a `7:1` en encapçalaments i `4.5:1` en text de lectura sobre fons blanc.
* **Indicador de focus visible (`:focus-visible`):** Anella blau brillant de 3px amb desplaçament d'alta visibilitat per a navegació amb teclat (`Tab`, `Shift+Tab`, fletxes, `Espai`, `Intro` i `Escape`).
* **Enllaç directe (*Skip Link*):** Permet saltar directament al contingut de lectura i qüestionari per a usuaris de lectors de pantalla.
* **No dependència del color:** Les respostes correctes i incorrectes inclouen reforç gràfic (`✓` / `✕`) i missatges verbals explícits (*"Resposta encertada"* / *"Cal revisar"*).
* **Regions en directe ARIA (`aria-live="polite"`):** Notificació automàtica del resultat als lectors de pantalla sense interferir en la navegació.

---

## 🧩 4. Disseny Universal per a l'Aprenentatge (DUA)

### Múltiples formes de representació:
* **Text sempre visible al costat del qüestionari:** A les pantalles d'ordinador, la lectura i les preguntes es mostren en doble columna per afavorir la relectura constant sense perdre el fil.
* **Paràgrafs numerats `[P1]`, `[P2]`, `[P3]`, `[P4]`:** Faciliten la citació, l'orientació visual i la cerca selectiva d'informació.
* **Vocabulari enriquit:** Paraules complexes ressaltades amb definicions emergents (*tooltips*) i un **Diccionari de suport** accessible des de la barra d'eines.
* **Síntesi de veu integrada (*Web Speech API*):** Botons per escoltar tant el text de lectura sencer com cadascuna de les preguntes en català.
* **Personalització visual:** Selector de mida de lletra (A / A+ / A++), mode de tipografia d'alta llegibilitat per a alumnat amb dislèxia i mode de contrast alt.

### Múltiples formes d'acció i expressió:
* **Bastides cognitives ("💡 Pista d'ajuda"):** Cada pregunta ofereix una pista que indica quin paràgraf rellegir i quina estratègia aplicar, sense donar la resposta directa.
* **Oportunitat de reintent sense frustració:** L'alumnat pot rellegir l'explicació i tornar a provar la pregunta per consolidar l'aprenentatge.

### Múltiples formes d'implicació:
* Narrativa real d'empatia, pau i cooperació històrica.
* **Diploma d'Aprofitament Lector personalitzat:** En acabar, l'alumne/a rep un reconeixement formal amb el seu nom, puntuació, desglossament competencial i la possibilitat de desar-lo o imprimir-lo en PDF directament amb un botó.

---

## 📚 5. Rigor Didàctic i Seqüenciació de Preguntes

El recurs compta amb 6 preguntes curriculars elaborades segons la taxonomia de la comprensió lectora:
1. **Pregunta 1 (Literal):** Decisió de Winton a Praga davant els camps de refugiats.
2. **Pregunta 2 (Lèxica):** Significat figurat de l'expressió *"tasca titànica"*.
3. **Pregunta 3 (Inferencial):** Causes del secret mantingut durant 50 anys (la modèstia i el deure moral).
4. **Pregunta 4 (Estructural/Cronològica):** Ordenació temporal dels fets (1938 ➔ 1939 ➔ 1988).
5. **Pregunta 5 (Literal numèrica):** Nombre exacte d'infants salvats (669 nens i nenes).
6. **Pregunta 6 (Crítica/Valors):** Missatge ètic de la solidaritat i la memòria històrica de la Segona Guerra Mundial.

---

## 📦 6. Recursos i Dependències

* **100% Autònom:** Tot el codi HTML5, estils CSS i lògica JavaScript es troben en el fitxer `index.html`.
* **Zero dependències externes:** No requereix connexió a internet per funcionar un cop descarregat; és apte per a aules sense connexió o xarxes escolars filtrades.
* **Compatible amb `file://`:** Es pot provar immediatament fent doble clic des de qualsevol carpeta o llapis de memòria USB.

---

## 🚀 7. Com provar en local i publicar a GitHub Pages

### Prova ràpida en local:
1. Fes doble clic sobre [`index.html`](file:///C:/Users/pberrozp/.gemini/antigravity/scratch/comprensio-segona-guerra-mundial/index.html) a l'explorador de Windows per obrir-lo al teu navegador preferit (Edge, Chrome, Firefox...).
2. Introdueix un nom o àlies i tria un grup classe per iniciar la sessió.

### Publicació a GitHub Pages:
1. Crea un repositori a [GitHub](https://github.com/) (per exemple, `comprensio-segona-guerra-mundial`).
2. Puja el fitxer `index.html` i aquest `README.md` a l'arrel de la branca `main`.
3. Al repositori, ves a **Settings** ➔ **Pages**.
4. A **Build and deployment**, selecciona la branca `main` i `/ (root)`, i prem **Save**.
5. En pocs segons tindràs la URL pública (p. ex., `https://<el-teu-usuari>.github.io/comprensio-segona-guerra-mundial/`) llesta per compartir amb l'alumnat.

---

## 🤖 8. Transparència i Declaració d'Ús d'IA

* **Elaboració tecnopedagògica assistida:** Aquest recurs ha estat generat amb l'assistència de models d'Intel·ligència Artificial i dissenyat sota criteris de comprensió lectora, accessibilitat DUA i WCAG 2.1 AA.
* **Revisió docent recomanada:** S'ha verificat la idoneïtat pedagògica del text i la correcció lingüística en català normatiu. Es recomana al docent revisar prèviament l'activitat per ajustar el nivell de bastides a la realitat del seu grup aula.
