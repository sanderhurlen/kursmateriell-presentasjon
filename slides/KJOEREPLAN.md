# Kjøreplan

1. Start ´create-react-app´
2. Omvisning av prosjektet som er opprettet
    - introduser index.js og App.js
    - Hva er javascript, react, html, css og jsx
    - package.json
3. Start applikasjon
    - OPPGAVE: start applikasjonen
4. Fortell om node-muligheten (npm org)
    - OPPGAVE: finn en pakke som heter react-router-dom
5. Installer react router dom
6. Sett opp SPA
    - sett opp ruting
    - Bytt ut lenke på App.js
    - OPPGAVE: sett opp en rute for join. la elementet være en div
    - EKSTRA OPPGAVE: legg til en navbar på toppen av applikasjonen 
7. Lag ny komponent
    - PRESENTER: funksjonell komponent
    - OPPGAVE: Lag en komponent som heter Join. Inne i den legger du bare et tomt div element med en tekst. sett opp rute
8. Legg til en god del HTML
9. Begynn å fortelle om state/svarhåndtering..
    - vis først en typisk tankegang med vanlig variabel
    - PRESENTER: useState
    - IMPLEMENTER: at svaret vises kondisjonelt
    - OPPGAVE: klarer dere å gjøre noe lignende for at først når svaret er avgitt så vises svaret?
10. Hva er props..
    - Vis frem hvilke deler av komponenten vi nå kopierer veldig ofte..
    - OPPGAVE: trekk ut svar-div til egen komponent. Med svar som egen prop
    - PRESENTER: props som en måte å tilrettelegge en komponent fra utsiden
    - OPPGAVE: legg til prop for rett/galt svar
11. Implementer en fasit
    - trekk ut spoersmål og fasit til variabler
12. Trekk ut svar til en liste
    - legg til eksisterende svar inn i en liste
    - vise hvordan man kan loope over verdier
    - trekk ut handleclick til aa legge til svar fra input
    - sjekk mot at man ikke har avgitt svar

PAUSE

1. Sideeffekter og lifecycle i React
    - useEffect
    - visualiser sideeffekter
2. Hente data fra API
    - PRESENTER: API
    - fortell om at quizen skal komme fra andre steder
    - https://opentdb.com/api_config.php eller https://opentdb.com/api.php?amount=1&category=21&difficulty=easy&type=multiple
    - hvordan implementere dette i useEffect
3. Skriv om spoersmaal og fasit til quiz.spm og quiz.fasit
    - sjekk at alt funker som foer
    - legg til alternativer
4. Hvordan oppdatere neste spørsmål uten å refreshe
    - legg til en state som vi kan påvirke effekten med
    - OPPGAVE: Forsøk å rydde opp svarene og svar avgitt ved nytt spørsmål

PAUSE

Lek og morro
skatteetaten designsystem?
bootstrap?
annet snacks?
Testing?
