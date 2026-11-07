# echo-video

Lettore YouTube minimo per il pannello Home Assistant di un Echo Show 5 di casa.

Il pannello gira su un indirizzo locale e YouTube non permette di incorporare i video delle case discografiche
in pagine locali: questa pagina pubblica (GitHub Pages) incorpora il video in modo normale e il pannello la mostra
in un iframe, comandandola con `postMessage` (play, pausa, posizione) per tenerla a tempo con la musica.

Uso: `https://cafedo.github.io/echo-video/#v=<id video>&t=<secondi di partenza>`

Non contiene né riceve dati di casa.
