---
theme: default
layout: default
transition: fade
title: Utviklerens fremtid
info: Egne tanker og meninger fra Vegard Haugland
favicon: /images/Webstep-Logotype-Negative.png
aspectRatio: 16/9
canvasWidth: 1280
fonts:
  sans: Geist
  serif: Spectral
  mono: monospace
  local: [Geist, Spectral, monospace]
  provider: none
---

<div class="deck dark title-slide">
  <div class="title-copy">
    <img class="logo" src="/images/Webstep-Logotype-Negative.png" alt="Webstep" />
    <h1>Utviklerens<br /><span class="accent">fremtid ↑</span></h1>
    <p class="presenter">Vegard Haugland</p>
    <p class="presenter-roles">Seniorkonsulent · Full-stack utvikler og Tech Lead </p>
    <p class="presentation-date"><time datetime="2026-11-13">13. november 2026</time></p>
    <p class="disclaimer">Dette er Vegards egne tanker og meninger om hvordan AI påvirker hverdagen i november 2026.</p>
  </div>
  <TitleCinemagraph />
</div>



---
transition: slide-left
---

<div class="deck dark">
  <div class="eyebrow accent">Før mitt perspektiv</div>
  <div class="rule"></div>
  <h1>Hva sier andre?</h1>
  <p class="subtitle">Erfaringer fra utviklere og designere – etterfulgt av utvalgte medieoppslag.</p>
  <div class="flow">
    <div class="flow-step"><strong>Utviklere</strong>Erfaringer delt på Reddit</div>
    <div class="flow-arrow">→</div>
    <div class="flow-step"><strong>Designere</strong>Erfaringer delt på Reddit</div>
    <div class="flow-arrow">→</div>
    <div class="flow-step"><strong>Mediene</strong>Utvalgte nyhetsoppslag</div>
  </div>
</div>



---
clicks: 2
transition: slide-left
---

<div class="deck sand">
  <div class="carousel-title">
    <div><div class="eyebrow">Dagens situasjon · Reddit</div><h2>Hva sier utviklerne?</h2></div>
    <div class="small">Enkelterfaringer, ikke statistikk</div>
  </div>
  <div class="carousel-frame">
    <div v-click.hide="1" class="carousel-item"><img src="/images/quotes/developer/dev1.png" alt="Reddit-innlegg fra en utvikler, første eksempel" /></div>
    <div v-click="[1, 2]" class="carousel-item"><img src="/images/quotes/developer/dev2.png" alt="Reddit-innlegg fra en utvikler, andre eksempel" /></div>
    <div v-click="2" class="carousel-item"><img src="/images/quotes/developer/dev3.png" alt="Reddit-innlegg fra en utvikler, tredje eksempel" /></div>
  </div>
  <div class="footer">Reddit · hovedsakelig amerikansk perspektiv</div><div class="carousel-hint">Neste eksempel →</div>
</div>



---
clicks: 2
transition: slide-left
---

<div class="deck sand">
  <div class="carousel-title">
    <div><div class="eyebrow">Dagens situasjon · Reddit</div><h2>Hva sier designerne?</h2></div>
    <div class="small">Enkelterfaringer, ikke statistikk</div>
  </div>
  <div class="carousel-frame">
    <div v-click.hide="1" class="carousel-item"><img src="/images/quotes/ux/designer1.png" alt="Reddit-innlegg om UX, første eksempel" /></div>
    <div v-click="[1, 2]" class="carousel-item"><img src="/images/quotes/ux/designer2.png" alt="Reddit-innlegg om UX, andre eksempel" /></div>
    <div v-click="2" class="carousel-item"><img src="/images/quotes/ux/designer3.png" alt="Reddit-innlegg om UX, tredje eksempel" /></div>
  </div>
  <div class="footer">Reddit · hovedsakelig amerikansk perspektiv</div><div class="carousel-hint">Neste eksempel →</div>
</div>



---
clicks: 4
transition: slide-left
---

<div class="deck">
  <div class="carousel-title">
    <div><div class="eyebrow">Dagens situasjon · mediene</div><h2>Færre jobber?</h2></div>
    <div class="small">Utvalgte medieoppslag</div>
  </div>
  <div class="carousel-frame">
    <div v-click.hide="1" class="carousel-item news"><div class="news-summary"><strong>Færre ledige IT-stillinger</strong><span><a href="https://www.digi.no/karriere/antall-ledige-it-stillinger-raser/2866087" target="_blank" rel="noopener noreferrer" @click.stop>Digi · 17. desember 2024</a></span></div><img src="/images/news_articles/few_jobs/202412_it-stillinger-raser.png" alt="Nyhetsoppslag om IT-stillinger fra desember 2024" /></div>
    <div v-click="[1, 2]" class="carousel-item news"><div class="news-summary"><strong>Få utlyste IT-jobber</strong><span><a href="https://www.digi.no/karriere/rekordfa-ledige-it-stillinger/3125395" target="_blank" rel="noopener noreferrer" @click.stop>Digi · 6. februar 2025</a></span></div><img src="/images/news_articles/few_jobs/202502_rekordfa-stillinger.png" alt="Nyhetsoppslag om få stillinger fra februar 2025" /></div>
    <div v-click="[2, 3]" class="carousel-item news"><div class="news-summary"><strong>Flere ledige, færre jobber</strong><span><a href="https://www.digi.no/karriere/it-torke-flere-arbeidsledige-faerre-jobber/3541564" target="_blank" rel="noopener noreferrer" @click.stop>Digi · 10. februar 2026</a></span></div><img src="/images/news_articles/few_jobs/202602_it-torke.png" alt="Nyhetsoppslag om IT-arbeidsmarkedet fra februar 2026" /></div>
    <div v-click="[3, 4]" class="carousel-item news"><div class="news-summary"><strong>KI og sysselsetting i IT</strong><span><a href="https://www.digi.no/debatt/it-bransjen-bruker-mest-ki-og-krymper-mest/7142501" target="_blank" rel="noopener noreferrer" @click.stop>Digi, debatt · 4. oktober 2026</a></span></div><img src="/images/news_articles/few_jobs/202610_it-bransjen-bruker-mest-ki.png" alt="Debattinnlegg om KI i IT-bransjen fra oktober 2026" /></div>
    <div v-click="4" class="carousel-item news"><div class="news-summary"><strong>Kraftig økning av arbeidsledige IT-folk</strong><span><a href="https://www.kode24.no/artikkel/kraftig-okning-av-arbeidsledige-it-folk/277720" target="_blank" rel="noopener noreferrer" @click.stop>kode24 · 10. november 2026</a></span></div><img src="/images/news_articles/layoffs/20261110_kraftig_okning_av_arbeidsledige.png" alt="kode24-oppslag om kraftig økning av arbeidsledige IT-folk, 10. november 2026" /></div>
  </div>
  <div class="carousel-hint">Neste oppslag →</div>
</div>



---
clicks: 2
transition: slide-left
---

<div class="deck">
  <div class="carousel-title">
    <div><div class="eyebrow">Dagens situasjon · mediene</div><h2>Oppsigelser og sluttpakker</h2></div>
    <div class="small">Utvalgte medieoppslag</div>
  </div>
  <div class="carousel-frame">
    <div v-click.hide="1" class="carousel-item news"><div class="news-summary"><strong>DNB varsler kutt</strong><span><a href="https://www.dn.no/marked/dnb-vil-kutte-400-arsverk/2-1-2054096" target="_blank" rel="noopener noreferrer" @click.stop>Dagens Næringsliv · 6. oktober 2026</a></span></div><img src="/images/news_articles/layoffs/20261006_dnb_kutter_400_arsverk.png" alt="Oppslag om kutt i DNB, 6. oktober 2026" /></div>
    <div v-click="[1, 2]" class="carousel-item news"><div class="news-summary"><strong>Barclays kutter stillinger</strong><span><a href="https://www.cnbc.com/2026/10/22/barclays-ai-jobs-cuts.html" target="_blank" rel="noopener noreferrer" @click.stop>CNBC · 22. oktober 2026</a></span></div><img src="/images/news_articles/layoffs/20261022_barclays_kutter_5000_stillinger.png" alt="CNBC-oppslag om Barclays, 22. oktober 2026" /></div>
    <div v-click="2" class="carousel-item news"><div class="news-summary"><strong>Microsoft tilbyr sluttpakker</strong><span><a href="https://www.reuters.com/technology/microsoft-is-offering-buyouts-around-60000-employees-business-insider-reports-2026-10-26/" target="_blank" rel="noopener noreferrer" @click.stop>Reuters · 26. oktober 2026</a></span></div><img src="/images/news_articles/layoffs/20261026_microsoft_sluttpakke_til_60000.png" alt="Reuters-oppslag om Microsoft, 26. oktober 2026" /></div>
  </div>
  <div class="carousel-hint">Neste oppslag →</div>
</div>



---
---

<div class="deck sand">
  <div class="eyebrow">Et menneske bak overskriftene</div>
  <h2>IT eller helse?</h2>
  <div class="student-frame"><img class="student-image" src="/images/quotes/student/it-eller-helse.png" alt="Reddit-innlegg fra en 27-åring som ber om råd om IT- eller helseutdanning" /></div>
  <div class="footer">Reddit · et spørsmål om veien videre</div>
</div>



---
---

<div class="deck dark">
  <div class="grim-copy">
    <div class="eyebrow accent">Når vi ser alt på én gang</div>
    <div class="big-statement" style="margin-top: 30px">Det ser<br />ganske<br /><span class="accent">dystert ut.</span></div>
  </div>
  <img class="grim-image" src="/images/grim_reaper.webp" alt="Illustrasjon av en dyster skikkelse" />
</div>



---
---

<script setup>
const assetBase = import.meta.env.BASE_URL
</script>

<div class="deck">
  <div class="eyebrow">Nye muligheter · ett eksempel</div>
  <h2>Apper bygget på nytt</h2>
  <p class="subtitle">ArtCraft-teamet bruker AI for å lage reimplementasjoner.</p>
  <div class="app-grid">
    <div class="app-card"><img src="/images/craft/photocraft.png" alt="" /><div><strong>PhotoCraft</strong><span>Bilderedigering · Photoshop</span></div></div>
    <div class="app-card"><img src="/images/craft/wordcraft.png" alt="" /><div><strong>WordCraft</strong><span>Tekstbehandling · Word</span></div></div>
    <div class="app-card"><img src="/images/craft/gridcraft.png" alt="" /><div><strong>GridCraft</strong><span>Regneark · Excel</span></div></div>
    <div class="app-card"><img src="/images/craft/cadcraft.png" alt="" /><div><strong>CADCraft</strong><span>CAD · AutoCAD</span></div></div>
    <div class="app-card"><img src="/images/craft/figcraft.png" alt="" /><div><strong>FigCraft</strong><span>Grensesnittdesign · Figma</span></div></div>
  </div>
  <p class="app-note">OBS: Tidlige prosjekter. Ikke dokumenterte fullverdige erstatninger (enda).</p>
  <div class="footer source">Kilder: <a href="https://github.com/storytold/photocraft">PhotoCraft</a> · <a href="https://github.com/storytold/wordcraft">WordCraft</a> · <a href="https://github.com/storytold/gridcraft">GridCraft</a> · <a href="https://github.com/storytold/cadcraft">CADCraft</a> · <a href="https://github.com/storytold/figcraft">FigCraft</a> · <a href="https://news.ycombinator.com/item?id=50029110">utviklerens forklaring</a> · <a :href="`${assetBase}images/craft/SOURCES.txt`">ikonlisenser</a></div>
</div>



---
clicks: 1
---

<div class="deck sand">
  <div class="eyebrow">Fra observasjon til ny programvare</div>
  <h2>Hvordan gjøres det?</h2>
  <div class="diagram">
    <div class="diagram-step"><span>Observer<br />funksjonalitet</span><span v-show="$clicks >= 1" v-click="1" class="diagram-detail" :aria-hidden="$clicks < 1">Original kjørbar fil (.exe)</span></div><div class="diagram-arrow">→</div>
    <div class="diagram-step"><span>AI-assistert<br />utvikling</span><span v-show="$clicks >= 1" v-click="1" class="diagram-detail" :aria-hidden="$clicks < 1">AI reverse engineering med ghidra</span></div><div class="diagram-arrow">→</div>
    <div class="diagram-step"><span>Ny<br />kildekode</span><span v-show="$clicks >= 1" v-click="1" class="diagram-detail" :aria-hidden="$clicks < 1">Rekonstruert kildekode, typisk i Rust</span></div><div class="diagram-arrow">→</div>
    <div class="diagram-step"><span>Ny<br />app ↑</span><span v-show="$clicks >= 1" v-click="1" class="diagram-detail" :aria-hidden="$clicks < 1">Ny .exe fil</span></div>
  </div>
  <br v-show="$clicks === 1" />
  <ul v-show="$clicks === 1" v-click="1" :aria-hidden="$clicks !== 1">
    <li>Alternativt - Reverse Engineering (også kalt "decompiling" eller "recompiling")
      <ul><li>ArtCraft hevder de har laget appene gjennom observer funksjonalitet og ikke decompiling (<a href="https://news.ycombinator.com/item?id=50029110">kilde</a>)</li></ul>
    </li>
    <li><a href="https://github.com/morluto/rea">REA - Reverse Engineer Everything</a></li>
    <li><a href="https://www.youtube.com/watch?v=KC31K-CUC5Y">David Plummer - Demonstrerer recompiling av `calc.exe`</a></li>
  </ul>

  <div class="footer">Prinsippskisse · ikke en påstand om dekompilering</div>
</div>





---
transition: slide-up
---

<div class="deck dark doompop-slide">
  <DoomPopAtmosphere />
  <div class="eyebrow accent">Et annet blikk på tiden vi står i</div>
  <h2>AI Doompop</h2>
  <p class="subtitle">AI-genererte musikkvideoer som treffer mye av det vi opplever nå.</p>
  <DoomPopPlayer />
</div>



---
clicks: 1
---

<div class="deck dark">
  <div class="eyebrow accent">Fra situasjonsbilde til egne tanker</div>
  <div class="rule"></div>
  <h1>Mitt perspektiv</h1>
  <p class="big-statement" style="margin-top: 70px">Er jeg bekymret?<br /><span v-click="1" class="accent" :aria-hidden="$clicks < 1">Nei.</span></p>
  <p v-click="1" class="subtitle" :aria-hidden="$clicks < 1">La meg fortelle hvorfor.</p>
</div>



---
clicks: 1
---

<div class="deck sand journey">
  <div class="eyebrow">Min vei til konsulentyrket</div>
  <h2>1990–1996<br />Nysgjerrighet, spill og support</h2>
  <div class="journey-copy">
    <p><strong>1990:</strong> Brother 386 PC og Commodore Amiga 500. Jeg begynner å utforske.</p>
    <p v-click="1"><strong>1996:</strong> IT-support for familie, venner og naboer.</p>
  </div>
  <SkillPanel :stage="$clicks + 1" />
  <div class="footer">Neste steg: programmering →</div>
</div>



---
clicks: 1
---

<div class="deck journey">
  <div class="eyebrow">Min vei til konsulentyrket</div>
  <h2>1996–2002<br />Fra bruker til skaper</h2>
  <div class="journey-copy">
    <p>QBasic, HTML, JavaScript, IRC, spill og LAN.</p>
    <p v-click="1"><strong>2002:</strong> Delphi og mine egne programmer.</p>
    <img v-click="1" class="journey-image" src="/images/delphi_made_simple.jpg" alt="Boken Delphi Made Simple" />
  </div>
  <SkillPanel :stage="$clicks + 3" />
  <div class="footer">Neste steg: mennesker og fag →</div>
</div>



---
clicks: 2
---

<div class="deck sand journey">
  <div class="eyebrow">Min vei til konsulentyrket</div>
  <h2>2004–2011<br />Mennesker og fag</h2>
  <div class="journey-copy">
    <p><strong>2004:</strong> Samhandling og presentasjonsteknikk.</p>
    <p v-click="1"><strong>2006:</strong> Dataingeniør, Nettverksdrift- og sikkerhet</p>
    <p v-click="2"><strong>2011:</strong> Master IKT (Sivilingeniør) - Masteroppgave om AI og IT-sikkerhet.</p>
  </div>
  <SkillPanel :stage="$clicks + 5" />
  <div class="footer">Neste steg: erfaring i praksis →</div>
</div>



---
clicks: 2
---

<div class="deck journey">
  <div class="eyebrow">Min vei til konsulentyrket</div>
  <h2>2011–2020<br />Flere bransjer, flere verktøy</h2>
  <div class="journey-copy">
    <p>Olje og gass: domene, testing, leveransepress, commissioning.</p>
    <p v-click="1">Transport: nettverk, SCADA og teknisk ledelse.</p>
    <p v-click="2"><strong>2020:</strong> Webstep. Senere Azure, C# og React.</p>
  </div>
  <SkillPanel :stage="$clicks + 8" />
  <div class="footer">Bredde + nysgjerrighet →</div>
</div>



---
clicks: 4
---

<div class="deck">
  <div class="eyebrow">Hvorfor forteller jeg dette?</div>
  <h2>Jobben min var allerede bred</h2>
  <div class="task-grid">
    <div class="task-column" :class="{ 'task-active': $clicks === 1 }" :aria-current="$clicks === 1 ? 'step' : undefined"><h3>AI overtar mye av</h3><ul><li>Koding</li><li>Testing</li></ul></div>
    <div class="task-column" :class="{ 'task-active': $clicks === 2 }" :aria-current="$clicks === 2 ? 'step' : undefined"><h3>AI bidrar til</h3><ul><li>Code review</li><li>Faglig oppdatering</li></ul></div>
    <div class="task-column" :class="{ 'task-active': $clicks >= 3 }" :aria-current="$clicks >= 3 ? 'step' : undefined"><h3>Mine ferdigheter trengs fortsatt</h3><ul><li>Software Development Life Cycle (SDLC)</li><li>Være god rådgiver</li><li>Support og administrasjon</li><li>Infrastructure as code</li><li>Azure og devops</li><li>Compliance</li><li>Samhandling med andre team</li><li>Holde presentasjoner</li><li>Forstå domenet</li><li>Trusselmodellering</li></ul></div>
  </div>
  <p v-click="4" class="task-t-shaped" :aria-hidden="$clicks < 4">Bredde på tvers + dybde i ett fagfelt = <strong>T-shaped skills</strong> <span class="task-t-shaped-source">Kilde: <a href="https://en.wikipedia.org/wiki/T-shaped_skills" target="_blank" rel="noopener noreferrer" :tabindex="$clicks < 4 ? -1 : undefined" @click.stop>Wikipedia ↗</a></span></p>
  <div class="footer">Min erfaring</div>
</div>



---
clicks: 5
---

<div class="deck dark">
  <div class="eyebrow accent">Slik programmerer jeg og kollegaene mine nye features kostnadseffektivt</div>
  <h2>Fra tydelig behov til arbeid · Gjennom Kanban</h2>
  <div class="flow workflow-flow">
    <div class="flow-step" :class="{ 'flow-active': $clicks === 1 }" :aria-current="$clicks === 1 ? 'step' : undefined"><strong>1 · Nytt Issue</strong>Backlog med utriagerte oppgaver.</div>
    <div class="flow-arrow">→</div>
    <div class="flow-step" :class="{ 'flow-active': $clicks === 2 }" :aria-current="$clicks === 2 ? 'step' : undefined"><strong>2 · Samarbeid</strong>Utviklere og UX-designer modner beskrivelse og utvetydige akseptanse-kriterier sammen.</div>
    <div class="flow-arrow">→</div>
    <div class="flow-step" :class="{ 'flow-active': $clicks === 3 }" :aria-current="$clicks === 3 ? 'step' : undefined"><strong>3 · Ready (klart for utvikling)</strong>Teamet godkjenner i felleskap.</div>
    <div class="flow-arrow">→</div>
    <div class="flow-step" :class="{ 'flow-active': $clicks === 4 }" :aria-current="$clicks === 4 ? 'step' : undefined"><strong>4 · AI first</strong>Avtalt arbeidsmåte. Programmering med teamets AI skill:<br /><code class="flow-code">/teamskill {url-til-issue}</code></div>
    <div class="flow-arrow">→</div>
    <div class="flow-step" :class="{ 'flow-active': $clicks === 5 }" :aria-current="$clicks === 5 ? 'step' : undefined"><strong>5 · Review</strong>Gjøres primært av mennesker</div>
    <div class="flow-arrow">→</div>
    <div class="flow-ship" role="img" aria-label="Ship godkjent kode">🚢</div>
  </div>
  <br/>
  <ul>
    <li>Vi bruker GitHub Projects, men dette kan gjøres i Azure DevOps, JIRA etc. Nøkkelen er:
    <ul>
      <li>Å ta eierskap til issueene, og </li>
      <li>Diskuter issue'ene til dere blir enige, og </li>
      <li>Ha lav terskel for å holde det ryddig.</li>
    </ul>
    </li>
  </ul>
  <div class="footer">Min erfaring · eksempler fra teamet</div>
</div>



---
---

<div class="deck sand">
  <div class="eyebrow">Hva åpner dette for?</div>
  <h2>Fra idé til noe vi kan prøve</h2>
  <div class="cards">
    <div class="card"><h3>Designutkast</h3><p>Be LLMen lage ulike designforslag fra eksisterende kode.</p></div>
    <div class="card"><h3>Bruk-og-kast-kode</h3><p>Generere migreringsskript når behovet er midlertidig.</p></div>
    <div class="card"><h3>Show and tell</h3><p>Utviklere og UXere kan lage egne designvarianter og velge sammen på standup-møte.</p></div>
    <div class="card"><h3>Hobbyprosjekter</h3><p>Lage programvare for et konkret personlig behov.</p></div>
  </div>
  <div class="footer">Min erfaring · Prøv selv</div>
</div>



---
transition: slide-up
---

<div class="deck dark">
  <div class="eyebrow accent">Refleksjon · min vurdering</div>
  <h2>Teknologi handler fortsatt om mennesker</h2>
  <div class="reflection-list">
    <div class="reflection">Kundene trenger noen som kan veilede dem til å ta rette beslutninger til forretningsproblemene.</div>
    <div class="reflection">Alle kan bruke en AI, men kundene trenger mennesker som tenker selv og kan bruke AI-verktøy for å støtte opp om egen kompetanse.</div>
    <div class="reflection">Ha en "Dette fikser jeg"-holdning</div>
    <div class="reflection">Grunnleggende ferdigheter er fortsatt verdt å investere i.</div>
  </div>
</div>



---
---

<div class="deck light-sky">
  <div class="eyebrow">Mitt neste steg til oss</div>
  <h1>Faget vårt er i endring.</h1>
  <div class="end-list">
    <div>Vær villig til å lære og endre deg.</div>
    <div>La AI ta mer av kodingen – bygg flere personlige ferdigheter og AI skills.</div>
    <div>Designere kan ta flere roller avhengig av interesse, f.eks. frontendutvikling, coaching eller teknologiledelse.</div>
    <div>Ta eierskap til problemene, ikke bare verktøyene.</div>
  </div>
  <p class="subtitle" style="margin-top: 36px !important"><strong>Jeg tror den endringsvillige seniorkonsulenten er trygg.</strong></p>
  <div class="footer">Vegard Haugland · egne tanker og meninger</div>
</div>



---
---

<div class="deck dark closing-slide">
  <h1>Takk for meg</h1>
  <div class="footer closing-link"><a href="https://v3gard.github.io/utviklernes-fremtid" target="_blank" rel="noopener noreferrer" @click.stop>https://v3gard.github.io/utviklernes-fremtid</a></div>
</div>
