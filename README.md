# wiki for Vuetify Material Design Framework & VueJs

Indice:

<ul>
    <li>
    <a href="#info-sul-progetto">Info sul progetto</a>
      <ul>
    <li><a href="#basato-su">Basato su</a></li>
      </ul>
    </li>
    </li>
    <li>
    <a href="#per-cominciare">Per Cominciare</a>
  <ul>
    <li><a href="#requisiti">Requisiti</a></li>
  </ul>
    </li>
    <li><a href="#sintassi">
    Sintassi</a></li>

</ul>

## Info sul progetto

<p>L'obiettivo di questo progetto è quello di rifare il frontend (la parte che vede l'utente finale) di un portale usato per la distribuzione dell'energia. Il nostro compito è quello di ricreare le pagine del sito attuale, usando i componenti del workframe scelto, in questo caso, Vuetify. Altre persone (più esperte) si occuperanno della parte di backend del progetto, probabilmente alcune saranno nella vostra stessa stanza. Se avete dubbi, domande o perplessità, non abbiate paura a fargli domande.</p>

### Basato su

<a href="https://vuetifyjs.com/en/">Vuetify</a> framework per frontend, <a href="https://vuejs.org/">VueJs</a> e <a href="https://nuxtjs.org/">NuxtJs</a> per backend

## Per Cominciare

<p>
Bisogna aver installato NodeJs, Git (da usare insieme ad un account github) e 
infine un editor che supporti la sintassi di javascript. Di seguito troverai tutto il necessario

</p>

### Requisiti

<ul>
  <li><a href="https://nodejs.org/it/">NodeJs</a>- versione LTS</li>
  <li><a href="https://git-scm.com/downloads">Git</a>- Windows/Linux</li>
  <li>Editor Generico o IDE:
<ul>
  <li><a href="https://code.visualstudio.com/Download">Visual Studio Code</a> (consigliato perchè possiede molte estensioni per JS/VueJS)
  </li>
  <li>
    <a href="https://visualstudio.microsoft.com/it/vs/community/">Visual Studio Community</a>
  </li>
  <li><a href="https://www.jetbrains.com/products/#lang=js">Jetbrains IDE</a> come <a href="https://www.jetbrains.com/webstorm/">Webstorm</a>, 
    <a href="https://www.jetbrains.com/phpstorm/">PhpStorm</a> ecc. (non gratuiti ma disponibili in versione studente)
  </li>
  </ul>
  </li>
 </ul>
 
# Sintassi
<p>
    La sintassi di Vuetify è simil-HTML, ovvero con tag di apertura e chiusura, tra i quali va il contenuto del tag.
    In questa documentazione verranno citati solo i componenti che abbiamo usato più spesso; per l'elenco di tutti i componenti e le loro proprietà guardate la
    documentazione ufficiale.
</p>
<p align="center">
  <img 
    width="300"
    height="300"
    src="https://picsum.photos/300/300"
  >
</p>

### <a href="https://github.com/DavideReale/iD3-wiki-VueJs/blob/master/vuetify-logo-dark-text.svg">v-card</a>
<p>
    Le v-card sono dei componenti versatili, possono contenere molti elementi al loro interno, quali bottoni, icone, tabelle e molti altri.
    Hanno tre sottocomponenti principali (se vengono usati deve per forza essere all'interno della v-card), che sono il v-card-title, v-card-subtitle e il v-card-text, 
    che servono ad impostare rispettivamente il titolo, il sottotitolo e il testo (corpo) della v-card.
    Una proprietà che abbiamo spesso usato è la proprietà flat, che non crea ombra sulla pagina nella posizione della v-card.
</p>
