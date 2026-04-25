# Top Articles

My "to read" notes translated into a list of articles

## Contents

- [Smalltalk](#smalltalk)
- [JVM, Java, and the Java Ecosystem](#jvm-java-and-the-java-ecosystem)
- [Kotlin, Compose, and JetBrains-related Notes](#kotlin-compose-and-jetbrains-related-notes)
- [Collections](#collections)
- [Linux, Systems, and Operating Systems](#linux-systems-and-operating-systems)
- [Rare, Experimental, and Niche Languages](#rare-experimental-and-niche-languages)
- [Functional Programming, Effects, and Type Systems](#functional-programming-effects-and-type-systems)
- [Language Development, Compilers, Interpreters, and VMs](#language-development-compilers-interpreters-and-vms)
- [Unison, Distributed Systems, and Architecture](#unison-distributed-systems-and-architecture)
- [Go](#go)
- [Web, UI, Flutter, Android, and Tooling](#web-ui-flutter-android-and-tooling)
- [Logic Programming, Formal Methods, and Verification](#logic-programming-formal-methods-and-verification)
- [Security, Static Analysis, and Code Quality](#security-static-analysis-and-code-quality)
- [Books and Classic Papers](#books-and-classic-papers)
- [Other Articles and Discussions](#other-articles-and-discussions)
- [Project Ideas and Personal TODOs](#project-ideas-and-personal-todos)
- [To Sort Later](#to-sort-later)


---

## Smalltalk

* [Why Smalltalk instead of Ruby](https://blog.arkency.com/2017/01/why-smalltalk-instead-of-ruby/)
  A comparison of Smalltalk and Ruby, with emphasis on Smalltalk’s object model and development environment.

* [The Rise and Fall of Commercial Smalltalk](https://wirfs-brock.com/allen/posts/914)
  A historical overview of commercial Smalltalk systems and why they declined in popularity.

* [Gilad Bracha — videos on Smalltalk and language design](https://www.youtube.com/@GiladBracha/videos)
  Talks and lectures by Gilad Bracha on Smalltalk, Newspeak, object-oriented programming, and language design.

* [Zag Smalltalk — IWST 2018 paper](https://github.com/Zag-Research/Zag-Smalltalk/blob/main/Documentation/papers/IWST-2018.pdf)
  A paper about Zag Smalltalk and implementation techniques for Smalltalk systems.

* [SOMns](https://github.com/smarr/SOMns)
  A research Smalltalk implementation with a collection of whitepapers and references on language implementation.

* [Objective-Smalltalk](https://objective.st/)
  A Smalltalk-inspired language and environment focused on messaging, objects, and system integration.

---

## JVM, Java, and the Java Ecosystem

* [How Netflix uses Java YT](https://youtu.be/XpunFFS-n8I)
  A talk about Java usage at Netflix, including engineering practices and JVM-scale production systems.

* [Project Valhalla in Java](https://www.baeldung.com/java-valhalla-project)
  An overview of Project Valhalla and its impact on Java value types and performance.

* [Flattened Values — John Rose](https://cr.openjdk.org/~jrose/values/flattened-values.html)
  A deeper technical note on flattened values and Project Valhalla’s memory-layout direction.

* [Java on iOS](https://www.infoq.com/news/2025/11/java-on-ios/)
  News and discussion about running Java on iOS.

* [Java Strings Internals](https://tanis.codes/posts/java-strings-internals/)
  An explanation of how Java strings are represented internally and what that means for performance.

* [Java 1.4 Compiler Talk YT](https://www.youtube.com/watch?v=GEqgkaiBPdA&t=1251s)
  A talk about the Kotlin 1.4 compiler and related compiler architecture.

* [CRaC JVM](https://openjdk.org/projects/crac/)
  A JVM project for coordinated checkpoint/restore, useful for reducing application startup time.

* [Intro to Java io_uring and FFM](https://www.roray.dev/blog/java-io-uring-ffm/)
  An introduction to using Linux `io_uring` from Java through the Foreign Function & Memory API.

* [Rating 26 Years of Java Changes](https://www.reddit.com/r/java/comments/1nheyte/rating_26_years_of_java_changes/)
  A Reddit discussion rating Java language and platform changes across its history.

* [How Would You Fix Checked Exceptions in Java?](https://www.reddit.com/r/java/comments/1nbo50r/how_would_you_fix_checked_exceptions_in_java/)
  A Reddit discussion about checked exceptions and possible alternative designs.

* [Things I Miss About Java / Spring Boot After Switching](https://www.reddit.com/r/java/comments/1rla7ax/thins_i_miss_about_java_spring_boot_after/)
  A Reddit discussion about Java and Spring Boot features that developers miss when working in other ecosystems.

* [For Java Developers Transitioning to Go](https://www.reddit.com/r/golang/comments/1r850zm/i_wrote_this_for_java_devs_transitioning_to_go/)
  A Reddit post aimed at Java developers moving to Go.

* [Java-related Reddit discussion](https://www.reddit.com/r/java/s/ywsuQYcStU)
  A Java discussion thread to review and categorize later.

* Tagir Valeev Java course
  TODO: find the course from 2022 connected to Yandex, JetBrains, or Computer Science Center.

---

## Kotlin, Compose, and JetBrains-related Notes

* [How Compose Works YT](https://youtu.be/6BRlI5zfCCk?si=DrjV524u2mnCRUdg)
  A talk explaining Jetpack Compose internals.

* [Compose from Notebooks YT](https://www.youtube.com/watch?v=bkd6EAPIVe0)
  A talk or demo related to using Compose from notebook-style environments.

* [CMP-8764 — Compose Navigation Version Investigation](https://youtrack.jetbrains.com/issue/CMP-8764#focus=Comments-27-12589679.0-0)
  TODO: understand how the commenter detected that the application loads two versions of Compose Navigation.

* [KT-80557](https://youtrack.jetbrains.com/issue/KT-80557)
  TODO: understand which tricks or compiler/language behavior are involved.

* [KEEP — Refinement Classes Proposal](https://jetbrains.team/p/kt/repositories/KEEP/files/7400197c3e36561ee74528cd575764d600e48ad1/proposals/refinement-classes.md)
  Internal Kotlin proposal about refinement classes.

* [Mini Kotlin?](https://www.reddit.com/r/Kotlin/s/0wWRUt9wa0)
  A Reddit discussion about a smaller Kotlin-like language or subset.

* [PSI Talk](https://drive.google.com/file/d/1rMzdennyJ_jhIUfVtF6N93jBuDvLvsVX/view)
  TODO: watch and summarize the talk about PSI.

---

## Collections

* [Collection Iterators — Squeak by Example](https://eng.libretexts.org/Bookshelves/Computer_Science/Programming_Languages/Book%3A_Squeak_by_Example_%28Black_Ducasse_Nierstrasz_and_Pollet%29/09%3A_Collections/9.05%3A_Collection_Iterators)
  A chapter about collection iterators in Squeak Smalltalk.

* [Listy Things in Smalltalk](http://web.cecs.pdx.edu/~black/AdvancedProgramming/Lectures/Listy%20things%20in%20Smalltalk/Listy%20things.pdf)
  A comparison of list-processing ideas in functional languages and Smalltalk.

* [GNU Smalltalk — Collection Methods](http://gnu.ist.utl.pt/software/smalltalk/gst-manual/gst_74.html)
  A reference page listing collection-related methods in GNU Smalltalk.

---

## Linux, Systems, and Operating Systems

* [Distrobox in Practice](https://hackeryarn.com/post/distrobox/)
  Practical notes on using Distrobox for containerized Linux environments.

* [OS Endowment](https://kvinogradov.com/osendowment/)
  An essay about operating systems, software sustainability, or long-term platform maintenance.

* [No Graphics API](https://www.sebastianaaltonen.com/blog/no-graphics-api)
  An article about graphics APIs, abstraction, and the cost of low-level rendering interfaces.

---

## Rare, Experimental, and Niche Languages

* [Effekt](https://github.com/effekt-lang/effekt)
  A research language focused on algebraic effects and effect handlers.

* [OxCaml](https://oxcaml.org/)
  An OCaml variant focused on performance, memory layout, and systems-level extensions.

* [Features of D That I Love](https://bradley.chatha.dev/blog/dlang-propaganda/features-of-d-that-i-love/)
  A personal overview of useful and interesting features in the D programming language.

* [Zig Devlog — 2025-06-08](https://ziglang.org/devlog/2025/#2025-06-08)
  Development updates from the Zig programming language project.

* [Zig Devlog — 2026-03-10](https://ziglang.org/devlog/2026/#2026-03-10)
  A newer Zig development update.

* [Comptime is Bonkers](https://noelwelsh.com/posts/comptime-is-bonkers/)
  An article about Zig’s `comptime` and why compile-time execution is a powerful language feature.

* [Zig Comptime — Part 1](https://0x44.xyz/blog/comptime-1/)
  A practical introduction to Zig compile-time programming.

* [How Zig Parallelizes Work](https://github.com/ziglang/zig/issues/89#issuecomment-382474320)
  A GitHub issue comment about parallelism, compilation strategy, or build behavior in Zig.

* [On Zig](https://blueberrywren.dev/blog/on-zig/)
  A personal article discussing Zig’s design, trade-offs, and developer experience.

* [Zig Reddit Discussion](https://www.reddit.com/r/Zig/s/8r3G99Rhat)
  A Reddit thread about Zig to review and categorize later.

* [Andrew Kelley’s Zig Writing](https://andrewkelley.me/)
  Articles and talks by Zig’s creator.

* [Jank — Next Phase of Interop](https://jank-lang.org/blog/2025-06-06-next-phase-of-interop/)
  A post about interoperability work in Jank, a Clojure-inspired language.

* [Jank — A Great Start](https://jank-lang.org/blog/2026-03-06-great-start/)
  A Jank project update about recent progress and the next development phase.

* [Pkl](https://pkl-lang.org/index.html)
  Apple’s configuration language for typed, programmable configuration.

* [Grace in One Page](http://gracelang.org/applications/documentation/grace-in-one-page/)
  A compact overview of the Grace programming language.

* [Yap](https://github.com/tiansivive/yap)
  An interesting programming language project to inspect.

* [Mun](https://github.com/mun-lang/mun)
  A programming language with hot reloading as a major design goal.

* [Janet](https://github.com/janet-lang/janet)
  A small Lisp-like language designed for embedding and scripting.

* [P](https://p-org.github.io/P/)
  An event-driven programming language for modeling and verifying asynchronous systems.

* [Ante — Why Effects?](https://antelang.org/blog/why_effects/)
  An explanation of why algebraic effects can be useful in language design.

* [C3 — Some Language Design Lessons Learned](https://c3.handmade.network/blog/p/8682-some_language_design_lessons_learned)
  Lessons learned from designing the C3 programming language.

* [A New Era of Programming Languages](https://wyrhta.bearblog.dev/new-era-of-pls/)
  An essay about recent programming language design trends.

* [Design Mistakes in Rust](https://soc.me/languages/design-mistakes-in-rust)
  A critical article about Rust’s language design choices.

* [Ada/SPARK or Rust over C/C++?](https://www.adacore.com/blog/should-i-choose-ada-spark-or-rust-over-c-c)
  A comparison of Ada, SPARK, Rust, C, and C++ for safer systems programming.

* [Nim 2 Review](https://miguel-martin.com/blog/nim2-review)
  A review of Nim 2 with examples and design discussion.

* [Nim 2 Review — Lobsters Discussion](https://lobste.rs/s/ocmdra/review_nim_2_good_bad_with_example_code)
  Comments and discussion around the Nim 2 review.

* [Go is Still Not Good](https://blog.habets.se/2025/07/Go-is-still-not-good.html)
  A critical article about Go’s design and ecosystem problems.

* [If You Could Add Features to Go](https://www.reddit.com/r/golang/comments/1mkps74/if_you_could_add_some_features_to_go_what_would/)
  A Reddit discussion about desired features in Go.

* [Go Reddit Discussion](https://www.reddit.com/r/golang/s/ueo7akbDVT)
  A Go thread to review and categorize later.

* [Why Gleam Wins Over F#](https://peakd.com/softwareengineering/@simplestack/why-gleam-wins-over-f)
  A comparison-style article arguing for Gleam’s strengths.

* [We Rewrote Our Startup from PHP to Gleam in 3 Weeks](https://www.radical-elements.com/minor-epiphanies/we-rewrote-our-startup-from-php-to-gleam-in-3-weeks)
  A migration story about moving a startup codebase from PHP to Gleam.

* [Oberon Repository](https://github.com/rochus-keller/Oberon/tree/master)
  Oberon language resources and implementation materials.

* [Influential Dead Languages](https://www.hillelwayne.com/post/influential-dead-languages/)
  An article about historical programming languages that influenced modern language design.

---

## Functional Programming, Effects, and Type Systems

* [Typing is Hard](https://3fx.ch/typing-is-hard.html)
  An article about the complexity and trade-offs of type systems.

* [Demystifying Functional Effect Systems in Scala](https://medium.com/wix-engineering/demystifying-functional-effect-systems-in-scala-14419039a423)
  An introduction to functional effect systems in Scala, using ZIO as a reference point.

* [Clojure and Types](https://ericnormand.me/article/clojure-and-types)
  An article about the relationship between Clojure and static type systems.

* [Are Algebraic Effects Worth Their Weight?](https://www.reddit.com/r/ProgrammingLanguages/comments/1mh3ba8/are_algebraic_effects_worth_their_weight/)
  A Reddit discussion about whether algebraic effects are worth their complexity.

* [Why I’m Excited About Effect Systems](https://www.reddit.com/r/ProgrammingLanguages/comments/1lmjub0/why_im_excited_about_effect_systems/)
  A discussion about effect systems and their practical value.

* [Bidirectional Type Checking Discussion](https://www.reddit.com/r/ProgrammingLanguages/s/zT3CdjGjZF)
  A Reddit thread about bidirectional type checking.

* [How Should I Read Type System Notation?](https://langdev.stackexchange.com/questions/2692/how-should-i-read-type-system-notation/2693#2693)
  A practical explanation of reading formal type-system notation.

* [A Practitioner’s Guide to Reading Programming Languages Papers](https://web.archive.org/web/20250114215239/https://blog.acolyer.org/2018/01/26/a-practitioners-guide-to-reading-programming-languages-papers/)
  A guide to reading PL papers without getting lost in notation and formalism.

* [Why ML Needs a New Programming Language — Chris](https://www.reddit.com/r/ProgrammingLanguages/comments/1n8mpxt/why_ml_needs_a_new_programming_language_chris/)
  A Reddit discussion about ML-family languages and why a new one might be needed.

* [Niche and Interesting Language Features / Ideas Catalog](https://www.reddit.com/r/ProgrammingLanguages/comments/1lch7dt/niche_and_interesting_featuresideas_catalog/)
  A catalog-style Reddit discussion of niche language ideas.

* [Programming Languages Discussion](https://www.reddit.com/r/ProgrammingLanguages/s/DP4kip2koG)
  A PL discussion thread to review and categorize later.

* [Programming Languages Discussion](https://www.reddit.com/r/ProgrammingLanguages/s/XIVqjhhMjo)
  A PL discussion thread to review and categorize later.

* [Programming Languages Discussion](https://www.reddit.com/r/ProgrammingLanguages/s/nTZ7JLMSxh)
  A PL discussion thread to review and categorize later.
---

## Language Development, Compilers, Interpreters, and VMs

* [Otto — JavaScript interpreter in Go](https://github.com/robertkrimen/otto)
  A JavaScript interpreter written in Go.

* [Explaining JavaScript VMs in JavaScript — Inline Caches](https://mrale.ph/blog/2012/06/03/explaining-js-vms-in-js-inline-caches.html)
  Vyacheslav Egorov’s explanation of inline caches and JavaScript VM internals.

* [Template Interpreters](https://zackoverflow.dev/writing/template-interpreters/)
  An article about template interpreters and interpreter implementation techniques.

* [Backend Basics](https://eblog.fly.dev/backendbasics.html)
  A “backend from scratch” article covering basic backend engineering concepts.

* [Writing a JVM in Rust](https://andreabergia.com/series/writing-a-jvm-in-rust/)
  A series of articles about implementing a small JVM in Rust.

* [KarinaC](https://github.com/Plixo2/KarinaC)
  A compiler project that can be used as a reference for JVM bytecode generation.

* [Crafting Interpreters](https://craftinginterpreters.com/contents.html)
  Bob Nystrom’s book about building interpreters and implementing the Lox language.

* [Resilient LL Parsing Tutorial](https://matklad.github.io/2023/05/21/resilient-ll-parsing-tutorial.html#Why-Resilience-is-Needed)
  An article explaining why parser error recovery matters and how resilient parsing works.

* [Supercompilation Resources](https://github.com/etiams/supercompilation-resources)
  A curated list of resources about supercompilation.

* [PLT Resources](https://github.com/steshaw/plt?tab=readme-ov-file)
  A programming language theory resource list.

* [Plank](https://github.com/aripiprazole/plank/tree/main)
  study how type inference works in this project

* [V8 Notes](https://t.me/xufostation/1017)
  A Telegram post or thread about V8 internals.

* [Nekrolm Blog](https://nekrolm.github.io/blog.html)
  Blog with low-level programming, compiler, and VM-related notes.

* [Native Compilation Talk](https://www.youtube.com/watch?v=5lkZj4v4-ks)
  A talk related to native compilation or runtime implementation.

* Douglas Crockford — Top Down Operator Precedence
  https://github.com/douglascrockford/TDOP

* Bob Nystrom — Pratt Parsers: Expression Parsing Made Easy
  https://journal.stuffwithstuff.com/2011/03/19/pratt-parsers-expression-parsing-made-easy/

* Rob Pike — Lexical Scanning in Go
  https://youtu.be/HxaD_trXwRE

* Peter Norvig — How to Write a Lisp Interpreter in Python
  https://norvig.com/lispy.html

* Jack W. Crenshaw — Let’s Build a Compiler!
  https://compilers.iecc.com/crenshaw/

* Matt Might — Closure Conversion - How to compile lambda 
  https://matt.might.net/articles/closure-conversion/

* chibicc — A Small C Compiler
  https://github.com/rui314/chibicc https://news.ycombinator.com/item?id=33581704

---

## Unison, Distributed Systems, and Architecture

* [Unison Article — February 2026](https://github.com/ThomasAlexandre/programming/blob/main/unison-article-feb-2026.md)
  An article about Unison and its programming model.

* [Unison: The Language That Makes Microservices Feel Like a Monolith](https://medium.com/@thomas_alexandre/unison-the-language-that-makes-microservices-feel-like-a-monolith-64fa9cc5072c)
  An article about Unison’s approach to distributed programming and microservices.

* The First Law of Distributed Object Design: Don’t Distribute Your Objects

* Architectural Styles and the Design of Network-based Software Architectures

* No Silver Bullet — Fred Brooks

* Out of the Tar Pit

* Command Query Separation
  TODO: find good article about “asking a question should not change the answer”.

---

## Go

* [Go Language Design](https://go.dev/talks/2012/splash.article#TOC_5.)
  A classic article/talk about Go’s design principles.

* [Five Things That Make Go Fast](https://dave.cheney.net/2014/06/07/five-things-that-make-go-fast)
  Dave Cheney’s article about performance-related design choices in Go.

* [For Java Developers Transitioning to Go](https://www.reddit.com/r/golang/comments/1r850zm/i_wrote_this_for_java_devs_transitioning_to_go/)
  A Reddit discussion targeted at Java developers learning Go.

* [Go is Still Not Good](https://blog.habets.se/2025/07/Go-is-still-not-good.html)
  A critique of Go’s design and ecosystem.

* [If You Could Add Features to Go](https://www.reddit.com/r/golang/comments/1mkps74/if_you_could_add_some_features_to_go_what_would/)
  A Reddit discussion about which features Go users would like to add.

* [Go Reddit Discussion](https://www.reddit.com/r/golang/s/ueo7akbDVT)
  A Go discussion thread to review and categorize later.

---

## Web, UI, Flutter, Android, and Tooling

* [Maintaining an Android App](https://ashishb.net/programming/maintaining-android-app/)
  Practical notes on the long-term maintenance of an Android application.

* [Flutter Impeller Rendering Engine — Official Docs](https://docs.flutter.dev/perf/impeller)
  Official Flutter documentation for Impeller, Flutter’s newer rendering engine.

* [Flutter Will Use Impeller Instead of Skia](https://medium.com/@gauravswarankar/flutter-will-use-an-impeller-instead-of-skia-a5c645b83cc8)
  An article explaining Flutter’s transition toward the Impeller rendering engine.

* [PVS-Studio Blog Post 1348](https://pvs-studio.com/en/blog/posts/1348/)
  A PVS-Studio article to review and categorize later.

* [Use Obsidian Canvas and Dataview Plugins to Manage Projects Visually](https://www.xda-developers.com/use-obsidian-canvas-dataview-plugins-manage-projects-visually/)
  A practical guide to managing projects visually in Obsidian.

---

## Logic Programming, Formal Methods, and Verification

* [Logic Programming Talk](https://youtu.be/0AAronqrQV0)
  A talk about a logic programming language or logic programming concepts.

* [Some Logic / Programming Languages Discussion](https://www.reddit.com/r/programming/s/GWJd1sKtcr)
  A programming discussion thread to review and categorize later.

* [Game of Life in PocketML](https://0bmerlin.github.io/PocketML/GameOfLife.html)
  A Game of Life implementation in a small ML-like language.

* [P — Event-driven Programming Language](https://p-org.github.io/P/)
  A language for modeling and verifying event-driven systems.

---

## Security, Static Analysis, and Code Quality

* [PVS-Studio Blog Post 1348](https://pvs-studio.com/en/blog/posts/1348/)
  Static analysis article from the PVS-Studio team.

---

## Books and Classic Papers

* Leviathan — Thomas Hobbes
* No Silver Bullet — Fred Brooks
* Out of the Tar Pit https://youtu.be/napR0cCRdh4
* Architectural Styles and the Design of Network-based Software Architectures https://dl.acm.org/doi/10.5555/932295

---

## Other Articles and Discussions

* [Why DeGoogle?](https://www.reddit.com/r/degoogle/comments/1l5p3b7/why_degoogle_this_learn_how_pichai_and_team_helps/)
  A Reddit discussion about reasons for reducing dependence on Google services.

* [Арканум](https://habr.com/ru/companies/timeweb/articles/784950/)
  A Russian-language article on Habr about Arcanum.

* [Habr Article 337880](https://habr.com/ru/articles/337880/)
  A Habr article to review and categorize later.

* [The Programmers Who Live in Flatland](https://blog.redplanetlabs.com/2025/11/24/the-programmers-who-live-in-flatland/)
  An essay about how programmers model complexity and abstraction.

* [Tonksy / Grumpy Website Articles](https://tonsky.me/)
  TODO: find the exact articles on Tonsky’s site.

---

## Project Ideas and Personal TODOs

* [ ] Write a “coffee factory” in Gleam, Elixir, Niva, Clojure, or another interesting language.
* [ ] Move the GUI into a full Compose Multiplatform application with Android support.
* [ ] Save notes locally in the same SQLite database.
* [ ] Build an APK.
* [ ] Try unstyled Compose.
* [x] Experiment with Elixir.
* [ ] Make a Niva example for “passing around a vector everywhere”: use an object with a union-typed field, put different values into it at construction time, and show that this gives a form of polymorphism.
* [x] Look at Nim concepts and sketch how they could work in Niva.
* [x] Find a model or framework for building a website.

---

## To Sort Later

* [Reddit PL discussion](https://www.reddit.com/r/ProgrammingLanguages/s/DP4kip2koG)
* [Reddit PL discussion](https://www.reddit.com/r/ProgrammingLanguages/s/XIVqjhhMjo)
* [Reddit PL discussion](https://www.reddit.com/r/ProgrammingLanguages/s/nTZ7JLMSxh)
* [Reddit programming discussion](https://www.reddit.com/r/programming/s/GWJd1sKtcr)
* [Reddit Java discussion](https://www.reddit.com/r/java/s/ywsuQYcStU)
* [Reddit Go discussion](https://www.reddit.com/r/golang/s/ueo7akbDVT)
* [Reddit Zig discussion](https://www.reddit.com/r/Zig/s/8r3G99Rhat)
