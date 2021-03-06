---exportedFrom: 97d4ab6c344d331392441434764ea6dbd11a338a---# Dataviz readme

<!--
This subtree produces the readme markdown file that is used to produce the page you see when visiting:

http://mutabit.com/repos.fossil/grafoscopio/doc/tip/Packages/Dataviz/readme.html
-->

<p>
  <a href="http://mutabit.com/offray/blog/en/entry/ds-twitter-mockup">
    <img 
      src="https://offray.withknown.com/file/e9cc5646d905a316c2cce14402aa5a05/thumb.png" 
      alt="Starting avatar wheel" 
      width="30%"
    />
  </a>
  <a href="http://mutabit.com/offray/blog/en/entry/sdv-infomed">
    <img 
    margin-right: 1%; 
    margin-bottom: 0.5em;" 
    src="http://mutabit.com/repos.fossil/offray-blog/doc/tip/user/pages/entry/sdv-infomed/omeprazol-by-property.png" 
    alt="Ranibizumab's matrix sunburst for prescription and use data by country"
    width="30%"
    >
  </a>
  <a href="http://mutabit.com/offray/blog/en/entry/panama-papers-1">
    <img 
    src="http://mutabit.com/repos.fossil/offray-blog/doc/tip/user/pages/entry/panama-papers-1/minisite.png" 
    alt="Panama Papers minisite"
    width="30%"
    >
  </a>    
</p>

<p><small>
<b>^ Up |</b> 
Screenshots of the visualizations contained in the Dataviz package. 
From left to right: Twitter dataselfies, medical information and Panama Papers. 
Click on each image for more details.
</small></p>

Dataviz is a companion package for [Grafoscopio][grafoscopio-en] that puts together several examples of Domain
Specific Visualizations and Domain Specific Languages (DSV, DSL, respectively) developed with the 
[Roassal agile visualization engine][roassal].
Included prototypes approach several themes like:  
Panama Papers as reproducible Research [@luna-pp], Twitter Data Selfies [@luna-tds]
and published medicine access [@luna-infomed] and are presented via blog post and internal 
interactive documentation via Grafoscopio notebooks.
The classes in the package and their documentation show several levels of maturity from pretty mature 
(Panama Papers) to early coder practices (Infomed) and on going developments (Twitter Data Selfies) and 
are offered as examples and excersises to learners in our recurrent Dataviz workshop+hackathon, for code 
testing and refactoring.

It is suposed that you have familiarity with Grafoscopio and that you are in the same audience, as stated
in its manual:

> Grafoscopio and its companion package, Dataviz, are intended to be used by learners and researchers 
in several fields: academia, journalism, activism, hacktivism and for anyone interested in open reproducible 
research and data storytelling backed by data and agile visualizations [@bergel_agile_2016].
This document assumes that you are such person.

Here are some other quick entry points for Dataviz:

  - The Dataviz paper for [JOSS][joss] will give you a quick scholar view for the software: 
    abstract, metatada and links and to dig deeper:
    [[source](./JOSS/paper.md)] | 
    [[LaTeX](./paper.tex)] | 
    [[PDF](./paper.pdf)].
  - The [Dataviz source code repository][grafoscopio-sthub] on SmalltalkHub.

### Instalation instructions

Dataviz package is installed by default with the installation of Grafoscopio, but you can
install it separately by using Monticello Pharo package manager configurations. 
To install and load Dataviz, simply run:



~~~{.numberLines}
"Start by loading the configuration of Dataviz"
  Gofer new
    url: 'http://smalltalkhub.com/Offray/Dataviz/main';
    package: 'ConfigurationOfDataviz';
  load.

"After that load Datavi"
ConfigurationOfDataviz load.

~~~

### Usage instructions & Examples

As we said, Dataviz is a set of packaged exmaples of Domain Specific Visualizations and Domain Specific
Language (DSV and DSL) using Roassal agile visualization engine and/or documented with Grafoscopio
notebook, so the usage instructions is related with how to use and explore such examples.

Dataviz presents a main notebook (from which this  ̀readme ̀ file was generated), that introduce
its Domain Specific Visualizations & Languages.
To open the notebook go to the Grafoscopio docking bar and select `Help > Dataviz` or execute
the following code:;



~~~{.numberLines}
GrafoscopioDocumentation openDatavizIntro 
~~~

### API documentation

Dataviz, like Grafoscopio, inhabits the Pharo full live coding environment,
and we follow the custom of making the API documentation available
inside a dynamic environment, instead in some static web page.

Instructions for opening different parts of the Dataviz API  inside the system browser,
and see the objects and  messages organized by protocols, are provided in the companion interactive
notebook, with other contextual information, so we recoment to refer to the notebook API documentation.


### Community Guidelines

Because the community that makes/uses Grafoscopio is the same for Dataviz,
we follow the same community guidelines for contributing to the community,
reporting bugs and other ways of collaboration.
It is supposed that you are familiar with Grafoscopio and its manual, if you are using Dataviz.
But, just for reference, plese see the Community Guidelines section in the 
[Grafoscopio manual][grafoscopio-manual] for more detailed information about the above subjects.

[agileviz-quickstart]: https://dl.dropboxusercontent.com/u/31543901/AgileVisualization/QuickStart/0101-QuickStart.html
[beaker]: http://beakernotebook.com/
[bibtex]: https://en.wikipedia.org/wiki/BibTeX
[chocolatey]: https://chocolatey.org/
[citezen]: http://people.untyped.org/damien.pollet/software/citezen/
[d3js]: https://d3js.org/
[dataviz-sthub]: http://smalltalkhub.com/#!/~Offray/Dataviz 
[dataweek]: http://mutabit.com/dataweek/
[etherpad]: https://en.wikipedia.org/wiki/Etherpad
[flare]: http://flare.prefuse.org/
[floor-function]: https://en.wikipedia.org/wiki/Floor_and_ceiling_functions
[fuel]: http://rmod.inria.fr/web/software/Fuel
[fossil]: http://fossil-scm.org/
[joss]: http://joss.theoj.org/
[grafoscopio-en]: http://mutabit.com/grafoscopio/index.en.html
[grafoscopio-fossil]: http://mutabit.com/repos.fossil/grafoscopio/
[grafoscopio-manual]: http://mutabit.com/repos.fossil/grafoscopio/doc/tip/Docs/En/Books/Manual/manual.pdf
[grafoscopio-tickets]: http://mutabit.com/repos.fossil/grafoscopio/ticket
[grafoscopio-tickets-current]: http://mutabit.com/repos.fossil/grafoscopio/rptview?rn=1
[grafoscopio-sthub]: http://smalltalkhub.com/#!/~Offray/Grafoscopio
[git]: https://en.wikipedia.org/wiki/Git
[github]: https://en.wikipedia.org/wiki/GitHub
[gogs]: https://gogs.io/
[gt-tools]: http://gtoolkit.org/
[hackbo]: http://hackbo.co/
[json]: http://en.wikipedia.org/wiki/JavaScript_Object_Notation
[jupyter]: http://jupyter.org/
[jupyterlab]: http://jupyterlab.github.io/jupyterlab/
[latex]: https://en.wikipedia.org/wiki/LaTeX
[leo]: http://leoeditor.com
[light-markup-languages]: https://en.wikipedia.org/wiki/Light_markup_language
[manual-tip]: http://mutabit.com/repos.fossil/grafoscopio/dir?tip&name=Docs/En/Books/Manual
[markdown]: http://pandoc.org/MANUAL.html#pandocs-markdown
[mooc]: https://siemenbaader.github.io/PharoMooc-website/
[mooc-spotter1]: http://rmod-pharo-mooc.lille.inria.fr/MOOC/Videos/W3/C019-Videos-Spotter1-BrowsingAClassWithSpotter-V2-HD_720p_4Mbs.m4v
[mooc-spotter2]: http://rmod-pharo-mooc.lille.inria.fr/MOOC/Videos/W3/C019-Videos-Spotter2-Categories-V2-HD_720p_4Mbs.m4v
[mooc-w3-14]: http://amara.org/en/videos/04UWGMwnrdXz/info/rmod-pharo-mooclilleinriafrc019-videos-redo-dsl-hd_720p_4mbsm4v/
[neojson]: https://ci.inria.fr/pharo-contribution/job/EnterprisePharoBook/lastSuccessfulBuild/artifact/book-result/NeoJSON/NeoJSON.html
[nix]: http://nixos.org/nix/
[nosql]: https://en.wikipedia.org/wiki/NoSQL
[nteract]: https://nteract.io/
[oop-pharo-2017]: https://ci.inria.fr/pharo-contribution/view/Books/job/LearningObjectOrientedProgramming/98/artifact/book.pdf
[org-mode]: http://orgmode.org/
[pastebin]: https://en.wikipedia.org/wiki/Pastebin
[pandoc]: http://pandoc.org/
[pharo]: http://pharo.org/
[pharo-download]: http://pharo.org/download
[pollen]: http://docs.racket-lang.org/pollen/
[processing]: https://processing.org/
[raphaeljs]: https://dmitrybaranovskiy.github.io/raphael/
[roassal]: http://agilevisualization.com/
[rolling-release]: https://en.wikipedia.org/wiki/Rolling_release
[spec]: http://files.pharo.org/books/spec-tutorial/
[spotter]: http://gtoolkit.org/#spotter
[sqlite]: http://sqlite.org/
[ston]: https://github.com/svenvc/ston/blob/master/ston-paper.md
[texmacs]: http://texmacs.org/
[udbc]: http://www.smalltalkhub.com/#!/~TorstenBergmann/UDBC 
[zeppling]: http://zeppelin-project.org/
[zotero]: https://www.zotero.org/
[zotero-manual]: https://www.zotero.org/groups/diseo_y_creacion_phd_msc_universidad_de_caldas/items/collectionKey/PHGTCZVT

### Licences

Dataviz is licensed under MIT license and the readme and the Dataviz 
documentation downloaded with the package installation is licensed under a 
modified P2P license.
To see a full copy of such respective licenses, please visit the files under this repository:

  - [Dataviz source code and software MIT license](../../Docs/En/Licenses/grafoscopio-mit.md)
  - [Dataviz documentation P2P modified license](../../Docs/En/Licenses/documents-p2p-ismb.md)


