# TivuStreamList


![Screenshot](https://raw.githubusercontent.com/Belfagor2005/TivuStreamList/refs/heads/list/logo-tivustream.png)


Questo repository contiene playlist M3U generate automaticamente con canali **gratuiti e pubblici**, raccolti da fonti aperte su internet.  
Non viene fornito alcun canale a pagamento (es. Sky, Netflix, DAZN, ecc.) né contenuti protetti da copyright in violazione di licenze.

I file vengono aggiornati quotidianamente.

## 📁 Struttura del branch `list`

```
list/
├── ios/
│   ├── estero_list.m3u          # Canali esteri (per paese)
│   ├── news_list.m3u            # Canali news (Italia + internazionale)
│   ├── music_list.m3u           # Canali musicali TV
│   ├── radio_country.m3u        # Radio per paese
│   ├── radio_genre.m3u          # Radio per genere
│   ├── playlist.m3u             # Playlist principale (tutti i canali)
│   ├── startend.avi             # Segnaposto per i separatori
│   └── local/                   # File regionali italiani
└── logoz/                       # Loghi e immagini
```

## 📥 Utilizzo

Punta il tuo lettore IPTV (VLC, Kodi, ecc.) a:

```
https://raw.githubusercontent.com/Belfagor2005/TivuStreamList/list/ios/playlist.m3u
```

Oppure usa le liste specializzate:

- `estero_list.m3u` → canali esteri
- `news_list.m3u` → solo news
- `music_list.m3u` → musica TV
- `radio_country.m3u` → radio per paese
- `radio_genre.m3u` → radio per genere

## ⚠️ Note

- Tutti gli stream sono **pubblici e gratuiti**.  
  Se trovi un canale che ritieni violi i diritti d’autore, **segnalalo** e verrà rimosso.
- I canali possono non essere sempre funzionanti; le liste vengono aggiornate ogni giorno.
- Per segnalazioni o richieste, apri una issue in questo repository.

*Repository mantenuto con ❤️ da [Belfagor2005](https://github.com/Belfagor2005)* e da [Buio2005](https://github.com/buio2005)*
