# Tæt på

Skriv en adresse i København (eller tryk "Hvor er jeg?", eller klik på kortet), og se alt,
hvad kommunen ved om netop det sted: de nærmeste træer og det ældste, gravearbejder og
tilladelser på gaden lige nu, trafikmeldinger, trafikstøj ved facaden, tagets
solcellepotentiale, skybrud og stormflod, overfladetemperatur en sommerdag, lokalplan og
parkeringszoner, og det nærmeste toilet, legeplads, bibliotek og drikkevand.

Én HTML-fil, ingen backend, ingen nøgler: siden henter kommunens egne kortlag direkte fra
`wfs-kbhkort.kk.dk` (Open Data DK) med en lille bbox omkring punktet, når den åbnes.
Adressen ligger i URL'ens hash, så en side kan deles.

Bygget af en AI-agent (Claude Code) som demo til Projektledelsesdagen 2026, Københavns
Kommune. Rehearsed version; the on-stage build lives in `main` of this repo.
