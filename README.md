## Index

- [Haskell for beginners](#haskell-for-beginners)
- [Parts of language](#parts-of-language)
  - [Synthax](#synthax)
  - [IO](#io)
  - [Type Classes](#type-classes)
  - [Types](#types)
  - [Monads](#monads)
  - [Monoids](#monoids)
  - [Applicative Functors](#applicative-functors)
  - [Lenses](#lenses)
  - [Data Structures](#data-structures)
  - [Concurrent Haskell](#concurrent-haskell)
  - [Parallel Haskell](#parallel-haskell)
  - [Distribute Haskell](#distribute-haskell)
  - [Foreign Function Interface](#foreign-function-interface-ffi)
  - [Other](#other)
- [Design patterns and architecture](#design-patterns-and-architecture)
- [Spedical Purposes](#special-purposes)
  - [Web Programming](#web-programming)
- [Tools and Libraries](#tools-and-libraries)
  - [GHC and GHC-specific](#ghc-and-ghc-specific)
  - [GHCi](#ghci)
  - [Cabal](#cabal)
  - [QuickCheck](#quickcheck)
  - [Hlint](#hlint)
  - [Hoopl](#hoopl)
  - [Profiling](#profiling)
- [Ecosystem](#ecosystem)
  - [Books](#books)
  - [Tutorials and articles](#tutorials-and-articles)
  - [Style Guide](#style-guide)
  - [University Cources](#university-cources)
  - [Blogs](#blogs)
  - [Planets](#planets)
  - [Community](#community)
  - [Videos](#videos)
  - [Libraries](#libraries)
  - [Editors](#editors)
  - [Projects using Haskell and Haskell in production](#projects-using-haskell-and-haskell-in-production)
  - [Jobs](#jobs)
  - [Events](#events)

## Haskell for beginners

* [Why the world needs Haskell](http://www.devalot.com/articles/2013/07/why-haskell.html)
* [Learn Haskell Fast and Hard](http://yannesposito.com/Scratch/en/blog/Haskell-the-Hard-Way/)
* [Hello Haskell, Goodbye Scala](http://joshbassett.info/2013/hello-haskell-goodbye-scala/)
* [Why Haskell?](http://net.tutsplus.com/tutorials/other/why-haskell/)
* [Haskell for kids](http://cdsmith.wordpress.com/2011/08/03/haskell-for-kids-introduction/)
* [How to Start a New Haskell Project](http://jabberwocky.eu/2013/10/24/how-to-start-a-new-haskell-project/)
* [What I Wish I Knew When Learning Haskell 2.0](http://dev.stephendiehl.com/hask/)
* [Haskeleton: A Haskell Project Skeleton](http://taylor.fausak.me/2014/03/04/haskeleton-a-haskell-project-skeleton/)
* [Haskell Packages for Development](https://wunki.org/posts/2014-05-17-haskell-packages-development.html)


## Parts of the language

#### Syntax

* [Let vs. Where](http://www.haskell.org/haskellwiki/Let_vs._Where)
* [Basic Syntax Extensions](https://www.fpcomplete.com/school/pick-of-the-week/guide-to-ghc-extensions/basic-syntax-extensions)

#### IO

* [Explaining Haskell IO without Monads](http://neilmitchell.blogspot.com/2010/01/haskell-io-without-monads.html)
* [Avoiding IO](http://www.haskell.org/haskellwiki/Avoiding_IO)

#### Type Classes

* [Typeclassopedia](http://www.haskell.org/haskellwiki/Typeclassopedia)
* [School of Haskell > Type Classes](https://www.fpcomplete.com/school/introduction-to-haskell/5-type-classes)
* [Полиморфия и классы в Haskell (in russian)](http://habrahabr.ru/post/166353/)

#### Types
* [Newtype](http://www.haskell.org/haskellwiki/Newtype)

#### Monads

* [Why Do Monads Matter?](https://github.com/0xAX/erlang-bookmarks)
* [Three Useful Monads](http://adit.io/posts/2013-06-10-three-useful-monads.html)
* [A tour of the Haskell Monad functions](http://members.chello.nl/hjgtuyl/tourdemonad.html)
* [You Could Have Invented Monads! (And Maybe You Already Have.)](http://blog.sigfpe.com/2006/08/you-could-have-invented-monads-and.html)
* [Micro-tutorial: liftM by accident](http://www.reddit.com/r/haskell/comments/1pd1ep/microtutorial_liftm_by_accident/)
* [Monads, Arrows, and Idioms - Collection of papers](http://homepages.inf.ed.ac.uk/wadler/topics/monads.html)
* [Monad Transformers Step by Step (pdf)](http://www.cs.virginia.edu/~wh5a/personal/Transformers.pdf)

#### Monoids

* [Haskell Monoids and their Uses](http://blog.sigfpe.com/2009/01/haskell-monoids-and-their-uses.html)
* [Random thoughts on Haskell](http://blog.enfranchisedmind.com/2009/01/random-thoughts-on-haskell/)

#### Applicative functors

* [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)
* [Applicative Functors @ WikiBooks](http://en.wikibooks.org/wiki/Haskell/Applicative_Functors)
* [Why do we have map, fmap and liftM? (StackOverflow)](http://stackoverflow.com/questions/7463500/why-do-we-have-map-fmap-and-liftm)

#### Lenses

* [Lenses In Pictures](http://adit.io/posts/2013-07-22-lenses-in-pictures.html)
* [Lenses, Folds, and Traversals (youtube)](http://www.youtube.com/watch?v=cefnmjtAolY)

#### Data structures

* [Zippers: Making Functional “Updates” Efficient](http://scienceblogs.com/goodmath/2010/01/13/zippers-making-functional-upda/)

#### Concurrent Haskell

* [Introduction to Concurrent Haskell](http://www.infoq.com/presentations/Concurrent-Haskell)
* [Locks, Actors, And STM In Pictures](http://adit.io/posts/2013-05-15-Locks,-Actors,-And-STM-In-Pictures.html)

#### Parallel Haskell

#### Distribute Haskell

* [Cloud Haskell @ Haskell Wiki](http://www.haskell.org/haskellwiki/Cloud_Haskell)
* [Distributive Haskell](http://haskell-distributed.github.io)
* [The New Cloud Haskell @ Well Typed](http://www.well-typed.com/blog/70)
* [Towards Haskell in the Cloud - Microsoft Research (pdf)](http://research.microsoft.com/~simonpj/papers/parallel/remote.pdf)
* [distributed-process library @ github](https://github.com/haskell-distributed/distributed-process)

#### Foreign Function Interface (FFI)

* [GHC/Using the FFI](http://www.haskell.org/haskellwiki/GHC/Using_the_FFI)
* [Real World Haskell > Interfacing with C: the FFI](http://book.realworldhaskell.org/read/interfacing-with-c-the-ffi.html)
* [Haskell/FFI Wikibook](http://en.wikibooks.org/wiki/Haskell/FFI)
* [Haskell foreign import stdcall on DLL function (StackOverflow)](http://stackoverflow.com/questions/1027246/haskell-foreign-import-stdcall-on-dll-function)
* [GHC 7.8′s -staticlib flag](http://maxs.io/ghc-78-static-lib-flag/)


#### Other

* [Hidden features of Haskell](http://stackoverflow.com/questions/211216/hidden-features-of-haskell)
* [Making Haskell programs faster and smaller](http://users.aber.ac.uk/afc/stricthaskell.html)
* [High-Performance Haskell (slides)](http://www.slideshare.net/tibbe/highperformance-haskell)

### Design patterns and architecture

* [Haskell application architecture best practices [SO]](http://www.reddit.com/r/haskell/comments/223i80/haskell_application_architecture_best_practices/)
* [Large-scale design in Haskell? [SO]](http://stackoverflow.com/questions/3077866/large-scale-design-in-haskell)
* [Engineering Large Projects in Haskell: A Decade of FP at Galois](http://corp.galois.com/blog/2009/4/27/engineering-large-projects-in-haskell-a-decade-of-fp-at-galo.html)
* [The Design and Implementation of XMonad](http://xmonad.wordpress.com/2009/09/09/the-design-and-implementation-of-xmonad/)
* [The functor design pattern](http://www.haskellforall.com/2012/09/the-functor-design-pattern.html)
* [The category design pattern](http://www.haskellforall.com/2012/08/the-category-design-pattern.html)
* [Patterns in Functional Programming](http://patternsinfp.wordpress.com)
* [Дизайн и архитектура в ФП. Введение и Часть 1 [Russian]](http://habrahabr.ru/post/211871/)
* [Дизайн и архитектура в ФП. Часть 2 [Russian]](http://habrahabr.ru/post/215161/)



## Special purposes

### Web programming

* [Yesod Web Framework](http://www.yesodweb.com)
* [Making A Website With Haskell](http://adit.io/posts/2013-04-15-making-a-website-with-haskell.html)
* [Working With HTML In Haskell](http://adit.io/posts/2012-04-14-working_with_HTML_in_haskell.html)
* [Yesod = Haskell $ Web (in russian)](http://habrahabr.ru/post/184058/)
* [http-conduit Overview](http://www.yesodweb.com/book/http-conduit)
* [Hakyll для начинающих (in russian)](http://habrahabr.ru/post/175877/)
* [Haskell for Web Developers](http://www.stephendiehl.com/posts/haskell_web.html)
* [Pronk. A small command line application for load testing web servers. ](https://github.com/bos/pronk)

#### Happstack vs Yesod vs Snap

* [Comparing Haskell's Snap and Yesod web frameworks](http://stackoverflow.com/questions/5645168/comparing-haskells-snap-and-yesod-web-frameworks)
* [A Hopefully Fair and Useful Comparison of Haskell Web Frameworks](http://softwaresimply.blogspot.co.uk/2012/04/hopefully-fair-and-useful-comparison-of.htm)

#### Yesod

* [Building a File Hosting Service in Yesod](https://www.fpcomplete.com/school/advanced-haskell/building-a-file-hosting-service-in-yesod)
* [Haskell web programming - A Yesod tutorial](http://yannesposito.com/Scratch/en/blog/Yesod-tutorial-for-newbies/)
* [Yesod: Learning Through Doing](https://www.fpcomplete.com/user/twoolie/yesod-learning-through-doing)
* [Yesod Tutorial 1. My First Web Site](https://www.fpcomplete.com/blog/2012/10/yesod-tutorial-1-my-first-web-site)
* [Yesod Tutorial 2. Playing with Routes and Links](https://www.fpcomplete.com/blog/2012/10/yesod-tutorial-2-playing-with-routes-and-links)
* [Yesod Routing](https://www.fpcomplete.com/user/chad/snippets/yesod-routing)
* [Web application with concurrency](https://www.fpcomplete.com/school/to-infinity-and-beyond/pick-of-the-week/web-application-with-concurrency)
* [Database access](https://www.fpcomplete.com/school/starting-with-haskell/libraries-and-frameworks/persistent-db)
* [Typesafe URLs in client-side code](https://www.fpcomplete.com/user/snoyberg/yesod/typesafe-urls-in-client-side-code)
* [Snipp.IO: A pastebin made out of Haskell, Yesod and mongodb](http://charlieharvey.org.uk/page/yesod_mongodb_snippio_pastebin_howto)
* [Yesod Mongo DB and JSON](http://stackoverflow.com/questions/18808393/yesod-mongo-db-and-json)
* [Non scaffolded MongoDB App](https://github.com/yesodweb/yesod/wiki/Non-scaffolded-MongoDB-App)
* [Allowing cross-origin requests in Yesod](http://programmers.fbgamehack.com/1202975/allowing-cross-origin-requests-in-yesod)

#### Snap

* [Snap tutorial](https://github.com/J-Hannes/snap-tutorial)
* [WHAT ARE SNAPLETS?](http://snapframework.com/docs/tutorials/snaplets-tutorial)
* [Tutorial: Building a Sample Application with Haskell Snap, PostgreSQL, and the PostgreSQL Simple Snaplet](http://janrain.com/blog/tutorial-building-a-sample-application-with-haskell-snap-postgresql-and-the-postgresql-simple-snaplet/)
* [A Haskell newbie's guide to the Snap framework](http://learnmeahaskell.blogspot.com/2011/05/few-notes-on-learning-snap-framework.html)
* [A Haskell newbie's guide to Snap, Part 2](http://learnmeahaskell.blogspot.com/2011/07/haskell-newbies-guide-to-snap-part-2.html)
* [/r/snapframework](http://www.reddit.com/r/snapframework/)
* [The Pragmatic Haskeller > Episode 2. Snap](https://www.fpcomplete.com/user/adinapoli/the-pragmatic-haskeller/episode-2-snap)
* [24 Days of Hackage: snap](http://ocharles.org.uk/blog/posts/2012-12-19-24-days-of-hackage-snap.html)
* [AngularJS with Haskell](http://nurpax.github.io/posts/2013-01-13-angularjs-and-haskell.html)
* [Snap Framework: Compiled splices and processing forms with digestive functors](http://stackoverflow.com/questions/16245119/snap-framework-compiled-splices-and-processing-forms-with-digestive-functors)

##### Project, written with Snap

* [Building a Link Shortener with Haskell (and Snap) with Ryan Trinkle](http://vimeo.com/59109358)
* [ryantrinkle/memoise](https://github.com/ryantrinkle/memoise)
* [dikmax/haskell-blog](https://github.com/dikmax/haskell-blog/)
* [nurpax/snap-example (Snap + AngularJS)](https://github.com/nurpax/snap-examples)

## Tools and Libraries

#### GHC and GHC-specific

* [The Glorious Glasgow Haskell Compilation System User's Guide, Version 6.4.2](http://www.haskell.org/ghc/docs/6.4.2/html/users_guide/index.html)
* [Pragmas](http://www.haskell.org/ghc/docs/7.0.3/html/users_guide/pragmas.html)
* [Interactive evaluation at the prompt](http://www.haskell.org/ghc/docs/7.4.1/html/users_guide/interactive-evaluation.html)
* [GHC Core by Example, Episode 1: Hello, Core!](http://alpmestan.com/2013/06/27/ghc-core-by-example-episode-1/)
* [GHC Core by Example, Episode 2: Evaluation](http://alpmestan.com/2013/10/01/ghc-core-by-example-episode-2-evaluation/)

#### GHCi

* [GHCi: More Awesome Than You Thought with Richard Minerich (video)](https://vimeo.com/68669612)
* [GHCi's Debugger - Haskell from Scratch #2 (video)](http://www.youtube.com/watch?v=1OYljb_3Cdg)

#### Cabal

* [The Haskell Cabal](http://www.haskell.org/cabal/)
* [Cabal all the things! with Josh Hawkins (video)](https://vimeo.com/67171757)
* [How to make a Cabal package](http://www.haskell.org/haskellwiki/How_to_write_a_Haskell_program)
* [An Introduction to Cabal sandboxes](http://coldwa.st/e/blog/2013-08-20-Cabal-sandbox.html)
* [Information Generation With Cabal And Git](http://www.hyperedsoftware.com/blog/entries/build-info-gen.html)

#### QuickCheck

* [Introduction to QuickCheck2](http://www.haskell.org/haskellwiki/Introduction_to_QuickCheck2)
* [Some ideas for practical QuickCheck](http://koweycode.blogspot.com/2009/07/some-ideas-for-practical-quickcheck.html)


#### Hlint

* [HLint Manual](http://community.haskell.org/~ndm/darcs/hlint/hlint.htm)
* [HLint and Flymake - Haskell from Scratch #9 (video)](http://www.youtube.com/watch?v=aj7WF_Zm9zY)

#### Hoopl

* [The hoopl package @ hackage](http://hackage.haskell.org/package/hoopl)
* [A Hoopl Experience](http://nochair.net/posts/2013/02-20-a-hoopl-experience.html)
* [Hoopl-related blogposts @ ezyang.com](http://blog.ezyang.com/category/ghc/hoopl/)
* [Hoopl: A Modular, Reusable Library for Dataflow Analysis and Transformation (video)](https://vimeo.com/16753485)

#### Profiling
* [How to profile a Haskell program](http://www.haskell.org/haskellwiki/How_to_profile_a_Haskell_program)
* [Tools for analyzing performance of a Haskell program (StackOverflow)](http://stackoverflow.com/questions/3276240/tools-for-analyzing-performance-of-a-haskell-program)
* [Real World Haskell > Chapter 25. Profiling and optimization](http://book.realworldhaskell.org/read/profiling-and-optimization.html)


## Ecosystem

#### Books

* [Learn You a Haskell for a Great Good](http://learnyouahaskell.com)
* [Real World Haskell](http://book.realworldhaskell.org)
* [Programming in Haskell](http://www.cs.nott.ac.uk/~gmh/book.html)
* [Haskell: the Craft of Functional Programming](http://www.haskellcraft.com/craft3e/Home.html)
* [The Haskell School of Expression](http://www.cs.yale.edu/homes/hudak/SOE/)
* [Parallel and Concurrent Programming in Haskell](http://shop.oreilly.com/product/0636920026365.do)
* [Developing Web Applications with Haskell and Yesod](http://shop.oreilly.com/product/0636920023142.do)
* [The Fun of Programming](http://www.cs.ox.ac.uk/publications/books/fop/)
* [List of Books @ haskell.org](http://www.haskell.org/haskellwiki/Books)
* [Haskell Tutorial for C Programmers](http://www.haskell.org/haskellwiki/Haskell_Tutorial_for_C_Programmers)
* [The Haskell Road to Logic, Math and Programming](http://homepages.cwi.nl/~jve/HR/)
* [The Haskell School of Music](http://www.cs.yale.edu/homes/hudak/Papers/HSoM.pdf)
* [The Haskell School of Expression: Learning Functional Programming through Multimedia](http://www.amazon.com/The-Haskell-School-Expression-Programming/dp/0521644089)
* [Beginning Haskell A Project-Based Approach](http://www.apress.com/9781430262503)
* [Pearls of Functional Algorithm Design](http://www.cambridge.org/us/academic/subjects/computer-science/programming-languages-and-applied-logic/pearls-functional-algorithm-design?format=HB)
* [Purely Functional Data Structures](https://www.cs.cmu.edu/~rwh/theses/okasaki.pdf)
* [Haskell Financial Data Modeling and Predictive Analytics](http://www.packtpub.com/haskell-financial-data-modeling-and-predictive-analytics/book)
* [Haskell Data Analysis Cookbook](http://haskelldata.com/)

#### Tutorials and articles

* [School of Haskell published content](https://www.fpcomplete.com/recent-content)

#### Style guide

* [A style guide for Haskell code](https://github.com/tibbe/haskell-style-guide)
* [Good Haskell Style](http://urchin.earth.li/~ian/style/haskell.html)

#### University cources

* [CS240h: Functional Systems in Haskell @ Stenford](http://www.scs.stanford.edu/11au-cs240h/)
* [Advanced Functional Programming @ Chalmers](http://www.cse.chalmers.se/edu/course/afp/)

#### Blogs

* [Neil Mitchell's Haskell Blog](http://neilmitchell.blogspot.com/)
* [Contemplating code AKA Haskell Weekly News](http://contemplatecode.blogspot.com)
* [Haskell for all](http://www.haskellforall.com)
* [Communicating Haskell Processes](http://chplib.wordpress.com)
* [Yesod Web Framework > Blog](http://www.yesodweb.com/blog/)
* [Sententia cdsmithus](http://cdsmith.wordpress.com/category/haskell/)
* [Conal Elliott](http://conal.net/blog/)
* [О Haskell по-русски (in russian)](http://haskell-ru.tumblr.com)
* [Alp Mestanogullari](http://alpmestan.com/)
* [Control.Monad.Writer](http://donsbot.wordpress.com/)
* [24 days of hackage](http://ocharles.org.uk/blog/)
* [Just Testing](http://justtesting.org)
* [Chris Done](http://chrisdone.com/tags/haskell)
* [Chtomatic Leaves](http://chromaticleaves.com)
* [Inside 206-105](http://blog.ezyang.com/category/haskell/)
* [Haskelier - Haskell for the Advanced Layman](http://haskelier.tumblr.com)
* [osa1 ](http://osa1.nets)


#### Planets
* [russian lambda planet](http://fprog.ru/planet/)
* [Haskell News](http://haskellnews.org)

#### Community

#### Videos

* [Haskell channel @ Vimeo](http://vimeo.com/channels/haskell/6678470)
* [YOW 2011 Simon Peyton Jones - Closer to Nirvana](http://www.youtube.com/watch?v=xmjvOLlCdFU)
* [A history of Haskell : being lazy with class](http://www.youtube.com/watch?v=7NPBrWDzO2A&list=PLUWfjhrIRed8X8CbKbiIab6gfzqfqJmux)
* [HaskellCasts](http://www.haskellcast.com)
* [Haskell Live - Episode 1: The Chess Board](http://www.youtube.com/watch?v=ScS8Q32lMxA)
* [Haskell Live - Episode 2: Time To Refactor](http://www.youtube.com/watch?v=6KkF5-_erns)

#### Libraries

* [Recommended libraries](https://www.fpcomplete.com/school/ide-tutorials/recommended-libraries)

#### Editors

* [A Vim + Haskell Workflow](http://www.stephendiehl.com/posts/vim_haskell.html)


#### Projects using Haskell and Haskell in production

* [Running a Startup on Haskell (Brian O'Sullivan)](http://www.infoq.com/presentations/Running-a-Startup-on-Haskell)
* [Combinatorrent - Writing Haskell Code for Fun and Profit](http://www.infoq.com/presentations/Combinatorrent-Haskell-casestudy)
* [Haskell in Production @ ApiEngine](http://mth.io/talks/haskell-in-production/)
* [Haskell in production](http://www.shimweasel.com/hs_gbu/#1.0)
* [Infrastructure for Commercial Haskell with Gregg Lebovitz of FP Complete (video)](https://vimeo.com/63626614)

#### Jobs

* [Functional Jobs](http://functionaljobs.com/)
* [functionaljobs@identi.ca](http://functionaljobs.com/)


#### Events

* [Commercial Users Of Functional Programming](http://cufp.org/conference)
* [Code Mesh: The Altenative Programming Conference](http://codemesh.io)
