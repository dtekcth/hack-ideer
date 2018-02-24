# Chalmerstenta Reborn

## Bakgrund

Chalmerstenta ([chalmerstenta.se][1]) är en
sida där man kan ladda upp tentor med lösningar. Tyvärr är inte
uppdateras inte sidan i realtid eftersom varje uppladdning måste
granskas av den som driftar sidan. Vem eller vilka som driver sidan är
oklart och garantierna för att de orkar driva den vidare är oklara.

## Projektbeskrivning

Bygga en liknande tentabas som i grund och botten är ett git(hub)-repo
som generar en statisk hemsida (exv Github Pages). Varje uppladdning
skulle då skapa en pull-request i vilken de som driftar databasen kan
granska och kontrollera att allt är korrekt, men där man också kan
komma åt de tentor man nyss laddat upp innan de godkänns. Något som
inte är möjligt i dagsläget. Administreringen skulle också vara mer
transparent.

## Krav

- Det ska vara lätt att ladda upp tentor, även för folk som inte har
  så bra koll på Git(hub).
- Det ska vara lätt att navigera på sidan och hitta sina kurser (se
  [chalmersstenta.se][1]).
- Databasen skall uppdateras efter att tentor är godkända och
  integrerats med resten av databasens innehåll.

## Kategori

Webb

[1]: http://www.chalmerstenta.se
