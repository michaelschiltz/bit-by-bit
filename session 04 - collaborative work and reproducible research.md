### Collaboration and openness as a paradigm
* [Linus's law](https://en.wikipedia.org/wiki/Linus%27s_Law): "Given enough eyeballs, all bugs are shallow"; and [The Cathedral and the Bazaar](http://www.catb.org/~esr/writings/cathedral-bazaar/).
* `open source` and `open access`
* [crowdsourcing](https://en.wikipedia.org/wiki/Crowdsourcing) and the [success of wikipedia](https://www.theguardian.com/technology/2004/oct/26/g2.onlinesupplement)
* importantly, and possibly counterintuitively, openness and transparancy have become a means for [incentivizing quality](http://www.zdnet.com/article/coverity-finds-open-source-software-quality-better-than-proprietary-code/) rather than sloppiness; however, note [predatory open access publishing](https://en.wikipedia.org/wiki/Predatory_open_access_publishing)
* professional editors, too, can be fooled: [SciGen](https://pdos.csail.mit.edu/archive/scigen/) and [MathGen](http://thatsmathematics.com/mathgen/); for a history of hoaxes, see the [wikipedia-page](https://en.wikipedia.org/wiki/SCIgen)
* [retraction watch](https://retractionwatch.com/)
* pitfalls of popular, proprietary formats:
  * Fowler, Dan. 2017. “Excel Is Threatening the Quality of Research Data — Data Packages Are Here to Help.” February 22. http://blogs.lse.ac.uk/impactofsocialsciences/2017/02/22/excel-is-threatening-the-quality-of-research-data-data-packages-are-here-to-help/.
  * Strasser, Carly. 2015. “Introduction to Open Science: Why Data Versioning and Data Care Practices Are Key for Science and Social Science.” February 9. http://blogs.lse.ac.uk/impactofsocialsciences/2015/02/09/data-versioning-open-science/.
  * a new player: [Coda](https://coda.io/welcome) - "we need a doc that can keep up with today’s super-collaborative world."

#### Tools and packages
* **general: [Github](https://www.github.com)**
  * Perkel, Jeffrey. 2016. “Democratic Databases: Science on GitHub.” *Nature News* 538 (7623): 127. doi:10.1038/538127a.
  * [Why we need a GitHub for science](http://www.slate.com/articles/technology/future_tense/2017/04/we_need_a_github_for_academic_research.html)
  * and [why don't you try it out yourself](https://try.github.io/)?

* **collaborative writing**: 
  * [Overleaf](https://www.overleaf.com/), [ShareLatex](https://www.sharelatex.com/); also, note the existence of the [ctan](https://www.ctan.org/)-pages, a library for packages you may need to install when using LaTex. 
  * [Authorea](https://www.authorea.com/) for collaborative writing
  * [Fidus Writer](https://www.fiduswriter.org/) and [Manuscripts.io](https://www.manuscripts.io/about/) 
  * these days, google docs too has a nice LaTex (or more accurately, MathJax) integration: [Auto-LaTeX-equations](https://sites.google.com/site/autolatexequations/)
  * [knitr](https://yihui.name/knitr/) with R and Latex: "The <strong>knitr</strong> package was designed to be a transparent engine for dynamic report generation with R, solve some long-standing problems in Sweave, and combine features in other add-on packages into one package (<strong>knitr</strong> &asymp; Sweave + cacheSweave + pgfSweave + weaver <code>animation::saveLatex</code> + <code>R2HTML::RweaveHTML</code> + <code>highlight::HighlightWeaveLatex</code> + 0.2 * brew + 0.1 * SweaveListingUtils + more)."
  * [Overleaf](https://www.overleaf.com/) with [CodeOcean](https://codeocean.com/); compare this [(rather long) case-study](https://www.overleaf.com/blog/529-case-study-an-introduction-to-code-ocean-creating-and-uploading-content-into-overleaf)
  * comparable to the aforementioned Ctan-pages, there exists a library for R-packages, which is called [Cran](https://cran.r-project.org).
  * [Jupyter](https://jupyter.org/): "Project Jupyter is an open source project was born out of the <a href="https://ipython.org">IPython Project</a> in 2014 as it evolved to support interactive data science and scientific computing across all programming languages. Jupyter will always be 100% open source software, free for all to use and released under the liberal terms of the <a href="https://opensource.org/licenses/BSD-3-Clause">modified BSD license</a>".
  * Since November 2017, Google made public its internal tool for data science and machine learning workflow. It's called [Colaboratory](https://www.google.ch/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi48KOgl63XAhUOC-wKHbHYAlEQFggoMAA&url=https%3A%2F%2Fresearch.google.com%2Fcolaboratory%2Funregistered.html&usg=AOvVaw12gzhEUgPt0MpBLiztHLKN), and it is based on the Jupyter notebook environment mentioned earlier. The difference is that Colaboratory allows you to use and share Jupyter notebooks with others without having to download, install, or run anything on your own computer other than a browser.
  * [Stencila](https://stenci.la/): "The calls for research to be transparent and reproducible have never been louder. But today's tools for reproducible research can be intimidating - especially if you're not a coder. We're building software for reproducible research with the intuitive, visual interfaces that you and your colleagues are used to."
  * [Julia](https://julialang.org/) and [Weave.jl](https://github.com/mpastell/Weave.jl): is this the 'dynamic documents' of the (immediate) future?
  * [Sublime Text](https://www.sublimetext.com/): "Sublime Text is a sophisticated text editor for code, markup and prose. Sublimetext has [Zotero-support](http://ww1.latexing.com/).
You'll love the slick user interface, extraordinary features and amazing performance."; for chromebook users, see [Caret](http://thomaswilburn.net/caret/) and [Zed](http://zedapp.org/).
  * I am a fan of [Atom](https://atom.io/), developed by the good people at GitHub.

* **data sharing**: [figshare](https://figshare.com/), [zenodo](https://www.zenodo.org/), and [Dryad](https://datadryad.org/); [OpenAire](https://www.openaire.eu/), and Harvard's [DataVerse](https://dataverse.org/)-project
  * as an important player, [Nature has started to take the reproducibility very seriously](https://www.nature.com/news/announcement-towards-greater-reproducibility-for-life-sciences-research-in-nature-1.22062?WT.mc_id=TWT_NatureNews&sf84509261=1).
  * the quest for transparency may even change the process of scientific publishing: see, for instance, [ScienceOpen](https://www.scienceopen.com/), "a professional networking platform for scholars to enhance their research in the open, make an impact, and receive credit for it. We provide context building services for publishers, to bring researchers closer to the content than ever before." 

* **data management tool**
  * [data management plan tool](https://dmptool.org/)

#### To watch:
* 14mech14. 2017. LaTeX Tutorial 10a: LaTeX + R, Knitr. Accessed April 10. https://www.youtube.com/watch?v=LrWBHqN3TUE.
* CEBM Oxford. 2017. John Ioannidis - Why Most Clinical Research Is Not Useful. Accessed April 10. https://www.youtube.com/watch?v=Uok-7NPFn4k.
* Talks at Google. 2017. John Ioannidis: “Reproducible Research: True or False?” | Talks at Google. Accessed April 10. https://www.youtube.com/watch?v=GPYzY9I78CI.


#### Further reading
* Aruoba, S. Borağan, and Jesús Fernández-Villaverde. 2014. “A Comparison of Programming Languages in Economics.” 20263. http://www.nber.org/papers/w20263.
* Balbaert, Ivo. 2015. *Getting Started with Julia Programming Language*. Birmingham: Packt Publishing - ebooks Account.
* Balbaert, Ivo, Avik Sengupta, and Malcolm Sherrington. 2016. *Julia: High Performance Programming*. 1 edition. Packt Publishing.
* Chambers, Chris. 2017. *The Seven Deadly Sins of Psychology: A Manifesto for Reforming the Culture of Scientific Practice*. Princeton, NJ: Princeton University Press.
* Colquhoun, David. 2017. “The Reproducibility Of Research And The Misinterpretation Of P Values.” bioRxiv, June, 144337. doi:10.1101/144337.
* Colquhoun, David. 2016. “It’s Time for Science to Abandon the Term ‘Statistically Significant’ – David Colquhoun | Aeon Essays.” Aeon. Accessed June 22, 2020. https://aeon.co/essays/it-s-time-for-science-to-abandon-the-term-statistically-significant.
* Gandrud, Christopher. 2015. *Reproducible Research with R and R Studio*, Second Edition. 2 edition. Boca Raton: Chapman and Hall/CRC.
* Kitzes, Justin, Daniel Turek, and Fatma Deniz, eds. 2017. *The Practice of Reproducible Research: Case Studies and Lessons from the Data-Intensive Sciences*. University of California Press.
* Rule, Adam, Amanda Birmingham, Cristal Zuniga, Ilkay Altintas, Shih-Cheng Huang, Rob Knight, Niema Moshiri, et al. 2019. “Ten Simple Rules for Writing and Sharing Computational Analyses in Jupyter Notebooks.” *PLOS Computational Biology* 15 (7): e1007007. https://doi.org/10.1371/journal.pcbi.1007007.
* Somers, James. 2018. “The Scientific Paper Is Obsolete.” *The Atlantic*, April 5, 2018. https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/.
* Stodden, Victoria, Friedrich Leisch, and Roger D. Peng, eds. 2014. *Implementing Reproducible Research*. Boca Raton: Chapman and Hall/CRC.
* Xie, Yihui. 2015. *Dynamic Documents with R and Knitr*, Second Edition. 2 edition. Boca Raton: Chapman and Hall/CRC.
