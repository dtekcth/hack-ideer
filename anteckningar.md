# Anteckningar.dtek.se

## Projektbeskrivning

Sidan anteckningar.dtek.se genereras i nuläget av ett pythonskript som
är lite svårläst och lite krångligt. Dessutom är hemsidan otillräcklig
för mängden kurser och anteckningar som finns att välja mellan.

## Krav

Utifrån kursantecknares synpunkt ska inget behöva förändras. Om man
har en bättre ide (kanske en uppladdningsgrej istället) är det så
klart välkommet att diskutera med oss i dHack och med SND.

## Kategori

Webb

# Wiki - Gitit

## Projektbeskrivning

Sektionen har som många vet en wiki som i nuläget är baserad på lite
olika versioner av PmWiki (en wiki-mjukvara skriven i PHP). Förutom
att PmWiki är lite småklurig att underhålla använder det sig dessutom
av ett filbaserat revisionssystem som bara de vet hur det
fungerar. Därför är tanken att gå ifrån PmWiki till en annan
wiki-mjukvara.

Gitit är en wiki-mjukvara skriven i Haskell och som dessutom använder
Git för att hålla koll på olika revisioner utav wiki-sidorna.

## Krav

Wikin ska fungera som den gamla vanliga wikin gjorde. Man ska kunna
autensiera sig mot Chalmers (alt. sektionens ldap-server) med CID och
lösenord.
