# Marble Loop

Una biglia arancione scende lungo un muro bianco, rimbalzando su tasti di xilofono piantati nel muro come chiodi:
zig-zag fra due colonne per le note veloci, scalette per quelle medie, mezzelune di filo per le pause. Ogni colpo è una
nota; il tasto colpito cede, si accende del suo colore e resta acceso. Il loop non ha fine: l'ultimo istante è il primo.

<table>
<tr>
<td width="50%"><img src="img/zigzag.webp" width="100%" alt="La biglia arancione fra due colonne di tasti colorati, sopra due mezzelune di filo"></td>
<td width="50%"><img src="img/scale.webp" width="100%" alt="Una scaletta di tasti che scende in diagonale lungo il muro, fra due mezzelune"></td>
</tr>
<tr>
<td width="50%"><img src="img/mezzaluna.webp" width="100%" alt="La biglia appena uscita da una lunga mezzaluna di filo, sopra una scala di tasti blu accesi"></td>
<td width="50%"><img src="img/accesi.webp" width="100%" alt="Tasti verde chiaro già colpiti e accesi, la biglia che rimbalza fra le due colonne"></td>
</tr>
</table>

**Guardalo:** apri `index.html` (anche dal telefono, anche dentro un'app di chat) e scegli la musica dal menu: la
scelta accende il suono. Il pulsante **♪ Musica** in alto a destra riapre il menu; un tocco fuori dal menu (o Esc) lo
chiude e lascia il brano che suona. Un altro brano riparte dall'inizio, con un muro tutto suo. In alto a sinistra:
fotogrammi al secondo, il fotogramma più lungo e la risoluzione.

## Musica

Nove brani, ognuno in un loop senza fine:

| Brano | Durata | Indirizzo |
|---|---|---|
| **Medley**: il *Rondò alla turca* di W. A. Mozart (Sonata K. 331), il *Galop infernal* di J. Offenbach e il finale dell'ouverture del *Guglielmo Tell* di G. Rossini, 241 note | 0:52 | `index.html` |
| *Rondò alla turca*, da solo, come Mozart lo ha scritto | 0:24 | `#rondo` |
| *Galop infernal*, da solo | 0:13 | `#galop` |
| *Guglielmo Tell*, da solo | 0:15 | `#tell` |
| *The Entertainer* di S. Joplin, il primo tema | 0:19 | `#entertainer` |
| *Nell'antro del re della montagna* di E. Grieg (*Peer Gynt*): il tema, che alla fine accelera | 0:44 | `#mountain-king` |
| *Danza della Fata Confetto* di P. I. Čajkovskij (*Lo schiaccianoci*): la melodia della celesta | 0:28 | `#sugar-plum` |
| *Per Elisa* di L. van Beethoven: la prima parte, ripetuta come è scritta | 0:22 | `#fur-elise` |
| *Onde del Danubio* di I. Ivanovici: il primo tema del valzer, tutto su lunghe mezzelune | 0:16 | `#danube` |

L'indirizzo apre direttamente quel brano (per esempio `index.html#danube`). Le foto qui sopra sono del medley.

Tutto è generato nel browser: la scena con three.js, i suoni con Web Audio. Nessun file esterno.

## Crediti

- [three.js](https://threejs.org) r186, licenza MIT
- Musiche di pubblico dominio, trascritte e semplificate
