# wiki for Vuetify Material Design Framework & VueJs

<h2> Indice:</h2>

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
    Sintassi</a>
    <ul><li><a href="#componenti">Componenti</a> </li>
    </ul>
</li>
</ul>

## Info sul progetto

<p>L'obiettivo di questo progetto è quello di rifare il frontend (la parte che vede l'utente finale) di un portale usato per la distribuzione dell'energia. Il nostro compito è quello di ricreare le pagine del sito attuale, usando i componenti già pronti dal framework scelto, in questo caso, Vuetify. Altre persone (più esperte) si occuperanno della parte di backend del progetto, probabilmente alcune saranno nella vostra stessa stanza. Se avete dubbi, domande o perplessità, non abbiate paura a fargli domande.</p>

### Basato su

<a href="https://vuetifyjs.com/en/">Vuetify</a> framework per frontend, <a href="https://vuejs.org/">VueJs</a> e <a href="https://nuxtjs.org/">NuxtJs</a> per backend

## Per Cominciare

<p>
Bisogna aver installato NodeJs, Git (da usare insieme ad un account github) e 
infine un editor che supporti la sintassi di javascript. Di seguito trovi tutto il necessario

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
    La sintassi di Vuetify non è altro che quella html, ovvero con tag di apertura e/o chiusura, tra i quali va il contenuto del tag. Il vantaggio di questo framework ui rispetto al html è che non bisogna scrivere ogni singola cosa da zero, ma si possono utilizzare componenti e stili già presenti in Vuetify o crearne dei nuovi personalizzati (sempre attenendosi alla documentazione), quindi troverai dei tag che non esistono in html e che iniziano tutti con <code>v-nometag</code>, ovviamente questo non impedisce di usare i tag "stock" di html.
 In questa wiki verranno citati solo i componenti che abbiamo usato più spesso; per l'elenco di tutti i componenti e le loro proprietà fate riferimento alla
    documentazione ufficiale disponibile cliccando sull'immagine sottostante.
</p>
<p align="center">
    <a href="https://vuetifyjs.com/en/introduction/why-vuetify/">
  <img 
    width="300"
    height="300"
    src="https://raw.githubusercontent.com/DavideReale/iD3-wiki-VueJs/master/vuetify-logo-dark-text.svg?token=GHSAT0AAAAAABVTC3P37CMD3KU5CEPKOODGYVTGNBQ"
  >
    </a>
</p>

## Componenti

### <a href="https://vuetifyjs.com/en/components/cards/">v-card</a>
<p>
    Le <code>v-card</code> sono dei componenti versatili, possono contenere molti elementi al loro interno, quali bottoni, icone, testo, tabelle e molti altri.
    Hanno tre sottocomponenti principali (se vengono usati deveno per forza essere all'interno della v-card), che sono v-card-title, v-card-subtitle e v-card-text, 
    che servono ad impostare rispettivamente il titolo, il sottotitolo e il testo (corpo) della v-card.
    Una proprietà che abbiamo spesso usato è la proprietà flat, che rimuove ombra(elevation in vuetify) della v-card.
</p>

### <a href="https://vuetifyjs.com/en/components/data-tables/">v-data-table</a>

<p>
    Le <code>v-data-table</code> sono fondamentali per mostrare dati sottoforma di tabelle.
    Il loro utilizzo è relativemente semplice; nella tag di apertura vanno inserite le prop,ovvero properties, (Ad esempio con i : davanti alla prop questa assumerà il valore della variabile indicata, altrimenti assumerà valore di stringa) la prop <code>:headers</code>, e <code>:items</code> sono fondamentali per caricare le intestazioni che devono essere usate (headers) e i dati che la tabella dovrà mostrare (items).
 Talvolta può capitare che in una colonna della tabella vogliate mostrare più di una cosa oppure vorrete inserire dei bottoni o delle icone ecc. Per fare ciò
  dovrete usare un uno slot. Quando si usa <code>v-slot</code>, questo viene passato nell'ambito degli slot, come da documentazione. Tuttavia, ci sono altri componenti più complessi, per i quali è necessario legare gli attributi ai componenti corretti, per garantire un supporto adeguato, andando poi a dire cosa mettere in quella colonna/e.
</p>
