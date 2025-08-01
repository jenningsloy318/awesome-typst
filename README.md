<p align=center>
  <a href="README.md" hreflang="en" lang="en">English</a>
  | <a href="README_ZH.md" hreflang="zh" lang="zh">简体中文</a>
</p>

# Awesome Typst

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme)

Curated collection of useful links for [Typst](https://github.com/typst/typst) users.

PRs welcomed!

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
## Contents

- [Official Project Links](#official-project-links)
- [Unofficial Project Links](#unofficial-project-links)
- [Integrations & Tools](#integrations--tools)
  - [Browser Extensions](#browser-extensions)
  - [Chatbots](#chatbots)
  - [CI/CD](#cicd)
  - [CLI Tools](#cli-tools)
  - [Editors](#editors)
  - [Editor Integrations](#editor-integrations)
  - [Online Tools](#online-tools)
  - [Programming](#programming)
  - [Typst As A Service](#typst-as-a-service)
- [Templates & Libraries](#templates--libraries)
  - [Official](#official)
  - [General](#general)
  - [Assignments](#assignments)
  - [CV](#cv)
    - [Examples](#examples)
    - [Templates](#templates)
  - [Calendar / Timetable](#calendar--timetable)
  - [Footnotes & Endnotes](#footnotes--endnotes)
  - [Formatting](#formatting)
  - [Graphics](#graphics)
  - [Letters](#letters)
  - [Linguistics](#linguistics)
  - [Mathematics](#mathematics)
  - [Music](#music)
  - [Physics](#physics)
    - [Conferences](#conferences)
    - [Journals](#journals)
    - [Grants/Proposals](#grantsproposals)
  - [Engineering](#engineering)
  - [Plotting](#plotting)
  - [Posters](#posters)
  - [Scripting](#scripting)
  - [Slides](#slides)

<!-- markdown-toc end -->

## Official Project Links

- [typst.app](https://typst.app) - The Typst web app
- [Typst Documentation](https://typst.app/docs)
- [GitHub](https://github.com/typst/typst)
- [Blog](https://typst.app/blog/)
- Social - [Discord] [Instagram] [LinkedIn] [Mastodon] [X]

[discord]: https://discord.com/invite/2uDybryKPe
[instagram]: https://www.instagram.com/typstapp/
[linkedin]: https://www.linkedin.com/company/typst/
[mastodon]: https://mastodon.social/@typst
[X]: https://twitter.com/typstapp/

## Unofficial Project Links

- [Typst-telegram-russian-chat](https://t.me/typst_ru) - chat about Typst in Telegram in russian
- [#typst:matrix.org](https://matrix.to/#/%23typst:matrix.org) - matrix room for Typst
- [Typst Examples Book](https://sitandr.github.io/typst-examples-book/book/) - An online book with Typst snippets, including extended tutorial and useful hacks

## Integrations & Tools

### Browser Extensions

- (FireFox) [bib-kit](https://github.com/MordragT/bib_kit) - Retrieve website information to create citations in the hayagriva format
- (FireFox) [yank](https://addons.mozilla.org/en-US/firefox/addon/yank/) - Yank URL and title of current tab, format to a chosen markup language, and copy to clipboard (supports typst link format)

### Chatbots

- [typst-bot](https://github.com/mattfbacon/typst-bot) - A discord bot to render Typst code
- [typst-bot-telegram](https://t.me/ru_rend_bot) - A telegram bot to render Typst code
- [typst-telegram-bot](https://github.com/daskol/typst-telegram-bot) - A [telegram bot](https://t.me/TypstBot) with focus in rendering math expression in Typst.

### CI/CD

- [gitlab-ci-typst](https://gitlab.com/IvanSanchez/gitlab-ci-typst) - Build Typst documents using GitLab CI pipelines
- [setup-typst](https://github.com/typst-community/setup-typst) - 📑 Install Typst for use in GitHub Actions
- [typst-action](https://github.com/lvignoli/typst-action) - Build Typst documents using GitHub actions

### CLI Tools

- [typstyle](https://github.com/Enter-tainer/typstyle) - Opinionated typst code formatter focusing on aesthetic, convergence and correctness.
- [typst-live](https://github.com/ItsEthra/typst-live) - Hot reloading of pdf in web browser
- [typst-pandoc](https://github.com/lvignoli/typst-pandoc) - Typst custom reader and writer for Pandoc
- [utpm](https://github.com/typst-community/utpm) - _Package manager_ for **[local](https://github.com/typst/packages#local-packages)** and **[remote](https://github.com/typst/packages)** Typst packages.
- [Tyler](https://github.com/mkpoli/tyler) - Package compiler for the ease of packaging and publishing Typst libraries and templates.
- [textlint-plugin-typst](https://github.com/textlint/textlint-plugin-typst) - [textlint](https://textlint.github.io/) plugin to lint Typst

### Editors

- [typstudio](https://github.com/Cubxity/typstudio) - An in development desktop editor built using Tauri.
- [Katvan](https://github.com/IgKh/katvan) - A bare-bones editor for Typst files, with a bias for Right-to-Left editing.
- [Typstwriter](https://github.com/Bzero/typstwriter) - An integrated desktop editor for typst projects.
- [BeauTyXT](https://github.com/soupslurpr/BeauTyXT) - A private, secure, minimalistic Text, Markdown, and Typst editor for Android
- [AcademicID](https://github.com/Academic-ID/sapienAI) - A self-hosted academic-focused AI chatbot and research workspace with a Typst, Markdown, and Text editor.

### Editor Integrations

- [SeniorMars/tree-sitter-typst](https://github.com/SeniorMars/tree-sitter-typst) - A TreeSitter parser for the Typst File Format
- [Tinymist VS Code Extension](https://marketplace.visualstudio.com/items?itemName=myriad-dreamin.tinymist) - A vscode extension for Tinymist integration
- [Tinymist](https://github.com/Myriad-Dreamin/tinymist) - A language server for typst with integrations for Emacs, Helix, NeoVim, Sublime Text, VsCode/VsCodium, and Zed
- [Typst Sync](https://github.com/OrangeX4/vscode-typst-sync) - A vscode extension for Typst local packages management and synchronization.
- [frozolotl/tree-sitter-typst](https://github.com/frozolotl/tree-sitter-typst) - A tree-sitter grammar with a focus on correctness.
- [inktyp](https://github.com/herlev/inktyp) - An Inkscape plugin to insert and edit Typst equations
- [obsidian-typst](https://github.com/fenjalien/obsidian-typst) - Renders typst code blocks in Obsidian into images using Typst through the power of WASM!
- [org-typst-preview](https://github.com/remimimimimi/org-typst-preview.el) - Typst preview in org-mode
- [typstar](https://github.com/arne314/typstar) - Neovim plugin providing autosnippets, excalidraw integration and \[standalone\] Anki flashcard export
- [typst-conceal.vim](https://github.com/MrPicklePinosaur/typst-conceal.vim) - Vim/Nvim plugin for replacing long typst symbol names with unicode characters
- [typst-math](https://marketplace.visualstudio.com/items?itemName=surv.typst-math) - A VS Code extension to simplify math writing in Typst
- [typst-sympy-calculator](https://github.com/OrangeX4/vscode-typst-sympy-calculator) - VS Code extension for Typst math calculating, includes Arithmetic, Calculus, Matrix, Custom Variances and Functions by yourself
- [typst-ts-mode](https://git.sr.ht/~meow_king/typst-ts-mode) - Typst tree sitter major mode for Emacs
- [typst.nvim](https://github.com/SeniorMars/typst.nvim) - WIP. Goals: Treesitter highlighting, snippets, and a smooth integration with neovim
- [typst.vim](https://github.com/kaarmu/typst.vim) - Vim plugin for Typst
- [typstd](https://github.com/daskol/typstd) - Yet another Typst language server.
- [uben0/tree-sitter-typst](https://github.com/uben0/tree-sitter-typst) - A TreeSitter grammar for the Typst language, used by Helix

### Online Tools

- [Detypify](https://github.com/QuarticCat/detypify) - Typst symbol classifier
- [excel-to-typst](https://github.com/hongjr03/excel-to-typst) - A tool that convert Excel tables to Typst table, can work in uploading .xlsx file or pasting.

### Programming

- [leetcode.typ](https://github.com/lucifer1004/leetcode.typ) - Solving Leetcode problems in Typst
- [Typix](https://github.com/loqusion/typix) - Deterministic Typst compilation with Nix
- [typst-py](https://github.com/messense/typst-py) - Python binding to typst
- [typst-rb](https://github.com/actsasflinn/typst-rb) - Ruby binding to typst
- [typst.ts](https://github.com/Myriad-Dreamin/typst.ts) - JavaScript binding to typst
- [Typstry.jl](https://github.com/jakobjpeters/Typstry.jl) - The Julia to Typst interface
- [mpl-typst](https://github.com/daskol/mpl-typst) - A Typst backend for Matplotlib.

### Typst As A Service

- [typst-http-api](https://github.com/slashformotion/typst-http-api) - An simple docker containing an API to compile typst markup
- [typst-telegram-bot](https://github.com/daskol/typst-telegram-bot) - A plain and simple HTTP API for rendering math with Typst.

## Templates & Libraries

### Official

- [typst/templates](https://github.com/typst/templates) - The templates that ship with the Typst web app

### General

- [Data Thinking Report Template](https://github.com/onefact/datathinking.org-report-template) - a template for artificial intelligence whitepapers with collaborative bibliographies using Zotero
- [HSOS-PTP-Typst-Template](https://github.com/mst2k/HSOS-PTP-Typst-Template) - A German template for writing papers, overfitted for the Osnabrück University of Applied Scien
- [INSA Typst Template](https://github.com/SkytAsul/INSA-Typst-Template) - A template for INSA (Institut National des Sciences Appliquées), a french public engineering school.
- [LaPreprint](https://github.com/LaPreprint/typst) - Beautiful preprints for Typst
- [Mantys](https://github.com/jneug/typst-mantys) - A template for writing manuals for Typst packages.
- [Project-Report-Typst](https://github.com/aurghya-0/Project-Report-Typst) - A simple template for college or university level project report.
- [SimplePaper](https://github.com/jinhao-huang/SimplePaper) - A Chinese template for writing simple paper
- [Typst-Paper-Template](https://github.com/jxpeng98/Typst-Paper-Template) - Typst template for Working Paper
- [aiaa-typst-template](https://gitlab.com/waterlubber/aiaa-typst-template) - A template for AIAA (American Institute of Aeronautics and Astronautics) papers.
- [bubble-template](https://github.com/hzkonor/bubble-template) - A simple and colorful template for reports
- [french-association-status](https://github.com/coco33920/typst-association-statuts) - A Template to write status for french associations.
- [gloss-awe](https://github.com/RolfBremer/gloss-awe) - Automatically Generated Glossary Page (renamed from typst-glossary)
- [in-dexter](https://github.com/RolfBremer/in-dexter) - Automatically Generated Index Page (renamed from typst-index)
- [mcm-icm-typst-template](https://github.com/DawnEver/mcm-icm-typst-template) - A template for Mathematical Contest in Modeling (MCM) and the Interdisciplinary Contest in Modeling(ICM).
- [simple-typst-thesis](https://github.com/zagoli/simple-typst-thesis) - A template useful for writing simple thesis in Typst
- [thesis-template-typst](https://github.com/ls1intum/thesis-template-typst) - Technical University of Munich thesis Template with cover, titlepage, tables, figures, appendix, etc.
- [tufte-typst](https://github.com/fredguth/tufte-typst) - A Tufte-inspired template for Typst
- [tufte-memo](https://github.com/nogula/tufte-memo) - A memo document template inspired by the design of Edward Tufte's books.
- [typst-bioinfo-thesis](https://github.com/lkndl/typst-bioinfo-thesis) - Flexible section headers and page numbers; pretty outlines and a `wrapfig`
- [typst-invoice](https://github.com/erictapen/typst-invoice) - Generate invoices from TOML files
- [typst-mla9-template](https://github.com/wychwitch/typst-mla9-template) - An MLA 9th edition template
- [typst-orange-template](https://github.com/flavio20002/typst-orange-template) - A Typst book template inspired by The Legrand Orange Book
- [typst-palettes](https://github.com/kaarmu/splash) - A library of color palettes for Typst
- [typst-templates](https://github.com/daskol/typst-templates) - A templates collection for major venues in machine learning and AI.
- [typst-templates](https://github.com/eigenein/typst-templates) - Templates for Typst
- [typst-templates](https://github.com/haxibami/haxipst) - My typst templates
- [typst-uwthesis](https://github.com/yangwenbo99/typst-uwthesis) - A typst template for writing thesis, featuring a working abbreviation lists.
- [typstry](https://github.com/qjcg/typstry) - A Tapestry of Typst Templates & Examples
- [writable-gm-screen-inserts](https://github.com/LLBlumire/writable-gm-screen-inserts) - Writable Game Master Screen Insertsces

### Assignments

- [OpenBoard](https://github.com/diquah/OpenBoard) - Easily build clean assessments in the style of the College Board.
- [assignment-template](https://github.com/AntoniosBarotsis/typst-assignment-template) - A simple assignment template
- [typst-assignment-template](https://github.com/astrale-sharp/typst-assignement-template) - Yet another simple assignment template
- [typst-assignment-template](https://github.com/gRox167/typst-assignment-template) - Yet another simple assignment template with a cover and several useful math symbols.
- [typst-homework-template](https://github.com/OriginCode/typst-homework-template) - A simple homework template inspired by the LaTeX homework template by Adam Blank
- [typst-teacher-template](https://github.com/jomaway/typst-teacher-templates) - A collection of typst templates. Mainly used to create worksheets and exams for my classes.

- [tinyset](https://github.com/sylvanfranklin/tinyset) - A lightweight and opinionated problem set package designed with pure math proofs in mind.

### CV

#### Examples

- [bare-bones-cv](https://github.com/caffeinatedgaze/bare-bones-cv) – A single-page minimalistic CV comprising essentials only.
- [cv.typ](https://github.com/jskherman/imprecv) - A no-frills curriculum vitae (CV) template for Typst that uses a YAML file for data input in order to version control CV data easily.
- [chicv](https://github.com/skyzh/chicv) - A minimal and fully-customizable CV template.

#### Templates

- [NNJR](https://github.com/tzx/NNJR) - A resume template inspired by `Jake's Resume` LaTeX template. Uses Typst and YAML.
- [alta-typst](https://github.com/GeorgeHoneywood/alta-typst) - A simple Typst CV template, inspired by AltaCV by LianTze Lim
- [attractive-typst-resume](https://github.com/Harkunwar/attractive-typst-resume) - A modern looking, attractive CV/Resume template by Harkunwar Kochar
- [billryan-typst](https://github.com/gvariable/billryan-typst) - A simple and minimalist resume template, inspired by Resume by Billryan.
- [brilliant-CV](https://github.com/mintyfrankie/brilliant-CV) - Another CV template for your job application, yet powered by Typst and more
- [caidan](https://github.com/cu1ch3n/caidan) - A clean and minimal food menu template.
- [cv.typ](https://github.com/jskherman/imprecv) - A no-frills curriculum vitae (CV) template using Typst and YAML to version control CV data.
- [friggeri-cv](https://github.com/olligobber/friggeri-cv) - A slightly modified version of the Friggeri CV, originally created by Adrien Friggeri in LaTeX, ported to Typst.
- [modern-cv](https://github.com/peterpf/modern-typst-resume) - A modern resume and coverletter template based on `Awesome CV`
- [modern-typst-template](https://github.com/peterpf/modern-typst-resume) - A modern resume/CV template.
- [moderncv.typst](https://github.com/giovanniberti/moderncv.typst) - A CV template inspired by LaTeX's `moderncv`
- [resume.typ](https://github.com/wusyong/resume.typ) - Simple and ergonomic template to generate resume and CV
- [simplecv](https://github.com/LaurenzV/simplecv) - SimpleCV is a simple and elegant CV template written in Typst
- [typst-academic-cv](https://github.com/DawnEver/typst-academic-cv) - Typst Template for Academic CV
- [typst-blue-header-cv](https://github.com/cammellos/typst-blue-header-cv) - Customizable Typst two-columns CV template with a top header.
- [typst-cv-miku](https://github.com/ice-kylin/typst-cv-miku) - A simple, elegant, academic style CV template for typst. Support for English and Chinese (and more)
- [typst-cv-resume](https://github.com/jxpeng98/Typst-CV-Resume) - A CV template with Sans font inspired by LaTeX `Deedy-Resume`
- [typst-cv-template1](https://github.com/vaibhavjhawar/typst-cv-template1) - A CV template inspired by Alessandro Plasmati's Graduate CV LaTex template
- [typst-cv-template](https://github.com/JCGoran/typst-cv-template) - A CV template inspired by LaTeX's `Awesome CV`
- [typst-cv-template](https://github.com/skyzh/chicv) - Chi CV Template (For Typst)
- [typst-mixed-resume](https://github.com/titaneric/typst-mixed-resume) - A casual and elegant resume template inspired by multiple templates.
- [typst-neat-cv](https://github.com/UntimelyCreation/typst-neat-cv) - A Typst template for modern, minimal and elegant CVs, inspired by mintyfrankie's `Brilliant CV`
- [typst-resume-sans](https://github.com/mizlan/typst-resume-sans) - A sleek and unadorned sans-serif resume template.
- [typst-resume-template](https://github.com/bamboovir/typst-resume-template) - Aesthetic style inspired by the Awesome-CV project
- [typst-resume-template](https://github.com/hexWars/resume) - A pretty resume template designed using typst.
- [typst-twentysecondcv](https://github.com/tomowang/typst-twentysecondcv) - A CV template inspired by LaTeX's `Twenty Seconds Resume/CV`
- [typst-yaml-cv](https://github.com/daxartio/cv) - A simple cv template designed using typst and yaml.
- [vercanard](https://github.com/elegaanz/vercanard) - A colorful resume template for Typst

### Calendar / Timetable

- [typst-timetable](https://github.com/ludwig-austermann/typst-timetable) - A template for timetables
- [october](https://github.com/extua/october) - A simple printable month calendar

### Footnotes & Endnotes

- [notes.typ](https://github.com/tudborg/notes.typ) - A library for notes with deduplication and customizability.

### Formatting

- [metro](https://github.com/fenjalien/metro) - A typst package to add typsetting to units!
- [ruby-typ](https://github.com/rinmyo/ruby-typ) - A library to add ruby text
- [showybox](https://github.com/Pablo-Gonzalez-Calderon/showybox-package) - A Typst package for creating colorful and customizable boxes.
- [simple-poem-typst](https://github.com/asibahi/simple-poem-typst) - An application of the `measure` function to set Arabic poetry.
- [syntastica-typst](https://github.com/RubixDev/syntastica-typst/) - Tree-sitter syntax highlighting for code blocks.
- [term](https://github.com/qo/term) - A Typst package for creating figures that emulate terminal screenshots.
- [typst-ansi_render](https://github.com/8LWXpg/typst-ansi-render) - A library to render text with ANSI escape sequences
- [typst-boxes](https://github.com/lkoehl/typst-boxes) - A library to draw colorful boxes.
- [typst-codelst](https://github.com/jneug/typst-codelst) - A Typst package to render source code.
- [typst-diagbox](https://github.com/PgBiel/typst-diagbox) - A library for diagonal line dividers in Typst tables
- [typst-gentle-clues](https://github.com/jomaway/typst-gentle-clues) - A typst package to simply add admonitions.
- [typst-tablem](https://github.com/OrangeX4/typst-tablem) - Write markdown-like tables easily.
- [typst-tablex](https://github.com/PgBiel/typst-tablex) - More powerful and customizable tables in Typst!

### Graphics

- [CeTZ](https://github.com/cetz-package/cetz) - CeTZ (CeTZ, ein Typst Zeichenpacket) is a library for drawing with [Typst](https://typst.app) with an API inspired by TikZ and [Processing](https://processing.org/). It comes with modules for drawing plots, graphs and charts.
- [typst-raytracer](https://github.com/SeniorMars/typst-raytracer) - raytracer in typst

### Letters

- [typst-letter-pro](https://github.com/Sematre/typst-letter-pro) - DIN 5008 letter template for Typst
- [typst-letter](https://github.com/dvdvgt/typst-letter) - A typst letter template inspired by the DIN 5008 norm
- [typst-letter-template](https://github.com/pascal-huber/typst-letter-template) - A customizable typst letter template with different presets (DIN 5008, Swiss C5)

### Linguistics

- [leipzig-gloss](https://gitea.everydayimshuflin.com/greg/typst-lepizig-glossing) - A library that provides primitives for creating glossing rules according to Leipzig.
- [typst-ipa](https://github.com/imatpot/typst-ascii-ipa) - 🔄 ASCII / IPA conversion for Typst
- [typst-dictionary-template](https://kianting.info/wiki/w/Tan_Kian-ting%E7%9A%84%E7%B6%AD%E5%9F%BA:Typst-dictionary-template) - 📕  a template for lexical dictionary/glossary in Typst
- [typst-syntree](https://github.com/lynn/typst-syntree) - Syntax trees for typst

### Mathematics

- [commute](https://gitlab.com/giacomogallina/commute) - A library for creating commutative diagrams
- [typst-algorithms](https://github.com/platformer/typst-algorithms) - A library for writing algorithms
- [typst-himcm-template](https://github.com/EvanLuo42/typst-himcm-template) - An HiMCM template for Typst
- [typst-math-template](https://github.com/matthiasGmayer/typst-math-template) - A simple math template that allows for numbered, referenceable theorems and compilation of subfiles that use references.
- [typst-pf3](https://github.com/maxwell-thum/typst-pf3) - A small package for creating "structured proofs." Essentially a port of Leslie Lamport's [`pf2.sty`](https://web.archive.org/web/20240419130400/https://lamport.azurewebsites.net/latex/pf2.sty)
- [typst-theorems](https://github.com/sahasatvik/typst-theorems) - A library for creating numbered theorem environments
- [typst-undergradmath](https://github.com/johanvx/typst-undergradmath) - A Typst port of [undergradmath](https://gitlab.com/jim.hefferon/undergradmath)

### Music

- [conchord](https://github.com/sitandr/conchord) - Typst package to easily write lyrics with chords and generate colorful fretboard diagrams
- [typst-chords](https://github.com/ljgago/typst-chords) - A library to write song lyrics with chord diagrams in Typst

### Physics

- [physica](https://github.com/Leedehai/typst-physics) - A library for usual physics notations, e.g. vectors and vector fields, matrices, differentials, derivatives, Dirac brackets, tensors, isotopes, and digital signal sequences.

#### Conferences

- [aiaa-typst](https://github.com/isaacew/aiaa-typst) - A template for creating conference papers in the style of the American Institute of Aeronautics and Astronautics.
- [ieee-conference-typst-template](https://github.com/DawnEver/ieee-conference-typst-template) A template to write IEEE Conference in Typst.
- [ieee-typst-template](https://github.com/bsp0109/ieee-typst-template) - A template to write IEEE Papers in Typst
- [ifacconf-typst](https://github.com/avonmoll/ifacconf-typst) - A template for creating conference papers in the style of the International Federation of Automatic Control

#### Journals

- [ieee-trans-typst](https://github.com/p4perf4ce/typst-ieee-trans-template) - A template that mimic LaTeX IEEE Transaction template (`ieee-trans.cls`)

#### Grants/Proposals

- [typst-nsf-templates](https://github.com/ntjess/typst-nsf-templates) - National Science Foundation (NSF) general template and outlines for popular proposal types.

### Engineering

- [circuitypst](https://github.com/fenjalien/cirCeTZ) - A library for drawing electronic circuit schematics
- [typst-bytefield](https://github.com/jomaway/typst-bytefield) - A library for drawing (network) protocol headers
- [tids](https://github.com/oldrev/tids) - A TI-style datasheet template for electronic component

### Plotting

- [typst-cd](https://gitlab.com/giacomogallina/commute) - Proof of Concept for tikz-like commutative diagrams
- [typst-plot](https://github.com/johannes-wolf/typst-plot) - A library for plotting line charts (deprecated in favor of CeTZ)
- [typst-plotting](https://github.com/Pegacraft/typst-plotting) - A library for drawing a variety of charts and plots like line charts, histograms, and pie charts

### Posters

- [typst-poster](https://github.com/pncnmnp/typst-poster) - An academic poster template
- [peace-of-posters](https://github.com/jonaspleyer/peace-of-posters) - A package for creating academic posters in block style

### Scripting

- [typst-oxifmt](https://github.com/PgBiel/typst-oxifmt) - Convenient Rust-like string formatting in Typst
- [typst-tools4typst](https://github.com/jneug/typst-tools4typst) - Tools for package and template authors.

### Slides

- [diapo](https://github.com/lvignoli/diapo) - A minimal and simplistic presentation template.
- [polylux](https://github.com/andreasKroepelin/polylux) - Create presentation slides in Typst
- [clean-polylux-typst](https://github.com/marcothms/clean-polylux-typst) - A clean and dynamic polylux presentation slide template
- [pinit](https://github.com/OrangeX4/typst-pinit) - Pin things as you like, especially useful for creating slides in typst.
- [touying](https://github.com/touying-typ/touying) - A powerful package for creating presentation slides in Typst
