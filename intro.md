# The Dataviz package

<!--
---exportedFrom: 97d4ab6c344d331392441434764ea6dbd11a338a----->

<!--
This subtree produces the intro file that is the default page you see when visiting:

http://mutabit.com/repos.fossil/grafoscopio/doc/tip/Packages/Dataviz/intro.md
-->

<p>
  <a href="https://mutabit.com/offray/blog/en/entry/ds-twitter-mockup">
    <img 
      src="https://offray.withknown.com/file/e9cc5646d905a316c2cce14402aa5a05/thumb.png" 
      alt="Starting avatar wheel" 
      width="30%"
    />
  </a>

  <a href="https://mutabit.com/offray/blog/en/entry/sdv-infomed">
    <img 
    margin-right: 1%; 
    margin-bottom: 0.5em;" 
    src="https://mutabit.com/repos.fossil/offray-blog/doc/tip/user/pages/entry/sdv-infomed/omeprazol-by-property.png" 
    alt="Ranibizumab's matrix sunburst for prescription and use data by country"
    width="30%"
    >
  </a>

  <a href="https://mutabit.com/offray/blog/en/entry/panama-papers-1">
    <img 
    src="https://mutabit.com/repos.fossil/offray-blog/doc/tip/user/pages/entry/panama-papers-1/minisite.png" 
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

Dataviz, is a companion package for [Grafoscopio][grafoscopio-en] that puts together several examples of Domain
Specific Visualizations and Domain Specific Languages (DSV, DSL, respectively) developed with the 
[Roassal agile visualization engine][roassal].
Included prototypes approach several themes like:
[Panama Papers as reproducible Research][panama-papers], [Twitter Data Selfies][twitter-ds]
and [published medicine information access][infomed] and are presented using blog post and/or internal 
interactive documentation, via Grafoscopio notebooks.
The classes in the package and their documentation show several levels of maturity from pretty mature 
(Panama Papers) to early coder practices (Infomed) and on going developments (Twitter Data Selfies) and 
are offered as examples and excersises to learners in our recurrent [Data Week][dataweek] workshop+hackathon, 
for code testing and refactoring.

It is suposed that you have familiarity with Grafoscopio and that you are in the same audience, as stated
in its [manual][grafoscopio-manual]:

> Grafoscopio and its companion package, Dataviz, are intended to be used by learners and researchers 
in several fields: academia, journalism, activism, hacktivism and for anyone interested in open reproducible 
research and data storytelling backed by data and agile visualizations.
This document assumes that you are such person.

Here are some other quick entry points for Dataviz:

  - The [Dataviz readme](./readme.html) file.
  - The Dataviz paper for [JOSS][joss] will give you a quick scholar view for the software: 
    abstract, metatada and links and to dig deeper:
    [[source](./JOSS/paper.md)] | 
    [[PDF](./JOSS/paper.pdf)].
  - The [Dataviz source code repository][dataviz-sthub] on SmalltalkHub.


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
[infomed]: http://mutabit.com/offray/blog/en/entry/sdv-infomed
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
[panama-papers]: http://mutabit.com/offray/blog/en/entry/panama-papers-1
[pandoc]: http://pandoc.org/
[pastebin]: https://en.wikipedia.org/wiki/Pastebin
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
[twitter-ds]: http://mutabit.com/offray/blog/en/entry/ds-twitter-mockup
[udbc]: http://www.smalltalkhub.com/#!/~TorstenBergmann/UDBC 
[zeppling]: http://zeppelin-project.org/
[zotero]: https://www.zotero.org/
[zotero-manual]: https://www.zotero.org/groups/diseo_y_creacion_phd_msc_universidad_de_caldas/items/collectionKey/PHGTCZVT

