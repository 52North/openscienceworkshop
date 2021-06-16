# Course blocks

## Block 1

**Thuenen infrastructure** (20 mins, not me)

- central infrastructure
- GitLab (internal, external)
- Kanban boards
- Databases
- RocketChat
- RStudio Server
- ?VSCode in cloud?
- ?JupyterHub?
- data protection measures
- ...

**Reproducible research and Data Science**

- Intro
  - Use "Themenparkplatz": https://komfortzonen.de/bikeshedding-hauptsache-nebensache/
  - Icebreaker: https://twitter.com/CodeWisdom/status/1275473811052298242?s=09
- Terms, goals, possibilities
  - "everybody does data science now" 
  - - data science workflow: https://twitter.com/LangData/status/1221783768299638784/photo/1
- Gentleman and Lang, 2007 - es steht quasi schon alles drin!
- Reproducibility spectrum
- Journal requirements and author guidelines (TOP factor, COS)
- _Research compendia_ (focus)
- File naming (J. Bryan), https://speakerdeck.com/jennybc/how-to-name-files and http://dataabinitio.com/?p=976
- Notebook science (Open ~)
  - JupyterHub
  - RStudio
- Containerisation
- Multi-language
- Big data
  - "DB-Größen jenseits von 10 TB"
  - Caching
  - subsets for transparency and publications
- Versioning
  - `git` auf dem Niveau von dem was Einzelnutzer brauchen, siehe https://twitter.com/betatim/status/1217717432489517056
- CI
- Reproducible Maps
  - papers
  - Material Ben's workshop (mapping w/ R)
- Reading material: 10 simple rules, [Good enough..](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510), ...
- Software packaging, Antwort auf Anmerkung "häufig komplexe Scripte"
- https://espm-288.carlboettiger.info/syllabus/
- https://utrechtuniversity.github.io/workshop-computational-reproducibility/
- https://github.com/annakrystalli/rrtools-repro-research
- https://canvas.uw.edu/courses/1354201 DATA 598 A Wi 20: Special Topics In Data Science: Reproducibility for Data Science
- "A Graduate Student Perspective on Overcoming Barriers to Interacting with Open Source Software" https://bit.ly/3cfg6Qr
- Data organisation in spreadsheets - paper > https://twitter.com/seankross/status/1309956489235197952?s=09

## Block 2

**Reproducible documents and reports**

- Tipps when starting with R > https://twitter.com/DanOvand0/status/1309223235876126720?s=09
- R Markdown
  - Alison Hill - How I Teach R Markdown > https://alison.rbind.io/post/2020-05-28-how-i-teach-r-markdown/ > so wie sie eine Stunde mit Markdown praktisch machen
  - "Rmd first" > https://twitter.com/StatnMap/status/1285448971381547014?s=09
  - _R Markdown for Scientists_ > https://rmd4sci.njtierney.com/
  - _Bookdown_ (probably focus)
  - Have a **colophon**! https://twitter.com/MilesMcBain/status/1263272935197782016?s=09
  - rticles
    - https://vickysteeves.gitlab.io/repro-papers/r-markdown-in-reproducible-research.html#creating-submission-ready-articles
  - templating for rticles and Bookdown PDFs
  - Multi-language
  - R + Python integration
  - Round trip Rmd + Docx
  - Notebook format: https://bookdown.org/yihui/rmarkdown/notebook.html#notebook-format
  - Presentations: https://bookdown.org/yihui/rmarkdown/presentations.html AND XARINGAN
  - https://holtzy.github.io/Pimp-my-rmd/
  - https://vickysteeves.gitlab.io/repro-papers/
  - `rrtools` https://github.com/benmarwick/rrtools und research compendia
  - Kleine Tricks für gute Struktur: Rmd chunks importieren: https://twitter.com/robinson_es/status/1294692910537928705?s=09
- ?R + Excel??
- officedown > https://twitter.com/DavidGohel/status/1268501912518823936?s=09
- "PDF outputs high priority"
- Rendering reports on GitLab CI (geht mit R, Python, OpenOffice)
  - ooffice to PDF with CLI within CI - yes, see https://gitlab.com/nuest/forumcs-2019-osf-proceedings/-/blob/master/proceedings.Rmd#L164
  - https://vickysteeves.gitlab.io/repro-papers/
- Jupyter
  - jupytext (because better with git)
  - https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007007
  - https://github.com/nteract/papermill (because of PDF report generation)
  - https://ebp.jupyterbook.org/en/latest/ (because PDF output and for long documents?)
- Slides of https://twitter.com/cboettig/status/1220109334891220992?s=09
- Course material from...
  - https://twitter.com/LangData/status/1221679459226587141?s=09
  - https://nevrome.github.io/rrtools.tutorial.mpi2020 via https://twitter.com/benmarwick/status/1222630603985539072?s=09
- https://github.com/annakrystalli/rrtools-repro-research
- _R Markdown for Scientists_ > https://rmd4sci.njtierney.com/
- _Best Practices for Writing Reproducible Code_ > https://utrechtuniversity.github.io/workshop-computational-reproducibility/
- Kurs von Ben!
  - https://canvas.uw.edu/courses/1354201
  - DATA 598 A Wi 20: Special Topics In Data Science: Reproducibility for Data Science
  - https://twitter.com/benmarwick/status/1233340012554383361?s=09)
- Berichte generieren
  - https://github.com/nteract/papermill
  - Docker for Data Science, auch mit "complete example: Automated Report"
    - https://twitter.com/RobertMylesMc/status/1232652960305426434?s=09)
  - https://ebp.jupyterbook.org/en/latest/

## Block 3

**Summary, discussion & hands-on**

- Dot voting about most useful tools?
- Arrange tools by immediate usefulness/applicability vs. long term impact?

## Block 4

**Reproducible environments**

- Collaborative computational reproducibility
  - "the best collaborator is future you"
  - immer mehr Aufträge über regelm. Berichte die erstellt werden müssen > Personen-abhängigkeit reduzieren, Institutionalisieren
  - Wachstum > Austausch, mehr Zusammenarbeit, aufeinander aufbauen und stärker sich austauschen
- _Version pinning_
- `git` auf dem Niveau von dem was Einzelnutzer brauchen, siehe https://twitter.com/betatim/status/1217717432489517056
- Containers
  - _Ten Simple Rules ..._ - paper anreißen
  - ?Docker installieren im Computerraum?
- renv + Docker > https://environments.rstudio.com/docker
- Docker for Data Science, auch mit "complete example: Automated Report"
  - https://twitter.com/RobertMylesMc/status/1232652960305426434?s=09)
- Binder
  - https://github.com/alan-turing-institute/the-turing-way/tree/master/workshops/boost-research-reproducibility-binder
- granolarr: a reproducible resource for teaching geographic data science in R > https://t.co/E00D44dYIN


## Block 5

**Workflows**

- Talk about internal R packages: https://rstudio.com/resources/rstudioglobal-2021/organization-how-to-make-internal-r-packages-part-of-your-team/
- `renv` https://environments.rstudio.com
- `rrtools` https://github.com/benmarwick/rrtools und research compendia
  - https://twitter.com/nordholmen/status/1094730762312503296
- https://jdblischak.github.io/workflowr/ ? https://github.com/jdblischak/r-project-workflows#readme cool!
- https://github.com/cjvanlissa/worcs ist ein R Paket um den gesamten Workflow zu managen - wollen sie sowas haben?
- `drake`
  - https://gitlab.com/ecohealthalliance/drake-gitlab-docker-example
  - https://milesmcbain.xyz/the-drake-post/ ist SUPER NÜTZLICH
  - successor `targets`
- `fusen` für R package auf Basis einzelner Rmd - Datei: https://thinkr-open.github.io/fusen/
- include FAIR Data?
- "Open Source Datenmanagement-Platform auf zu ziehen"

**Reproducible publications**

- AGILE guideline content (anonymous review, ...)
- ?Code quality?
- ?Defensive programming?
- ?Reusable code?
- Code citation, data citation (tools and standards)
- Establish internal review practices
  - https://github.com/OxfordCodeReviewNet/forum
  - https://www.uni-muenster.de/Publizieren/service/r2s2/index.html

## Block 6

**Requirements and needs**

- Common needs
- What are the foundations "no one can ignore" ?
- Fernziel: "Konzept entwickeln, was für weiteren Personenbereich interessant ist" > "Thuenen Data Science Handbuch"
- Teams >10 Kollegen, auch oft mit Externen > größerer Bedarf um sich auszutauschen, wie man da sinnhaft zusammen arbeitet, aber noch kein gemeinsames Template ("offen genug bleiben sollte")

