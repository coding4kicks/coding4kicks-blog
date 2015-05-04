title: "Choosing a Programming Language"
date: 2015-05-02 00:41:21
categories:
- Technology
- Programming
tags:
comments: true
---

{% asset_img Programming-Languages.jpg %}

Sometimes I wish I could talk to my past self and pass on a piece of information.  I wish I could talk to “Poof” 10 years ago and describe the differences between various programming languages.

Here, in a note to my past self I attempt to correct this failing.  While discussing programming languages can be controversial, since I am talking to myself the reception should be okay.

Please leave any comments on my unfair treatment of, fan-boy attitude toward, or general incorrectness about any particular language.  The languages are pulled from the Tiobe 20 with some modifications and additions. [{% link 1 http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html %}]

<h3 style="display: inline"><strong>C</strong></h3> – The workhorse of systems programming.  Wanna write drivers for the Linux Kernel or graphics for video games (not the Photoshop variety but the physics variety, handling game engine performance).  Pointers in all their glory and the power of memory management.  Probably a pass unless you know this is what you want to do and why.  It can power a lot, but it is the low level procedural language in all its glory (not counting Assembly).

<h3 style="display: inline"><strong>Java</strong></h3> – Possibly the blub programming language?  Ubiquitous in enterprise (aka. large corporations) and Universities.  Almost as fast as C and similar in syntax, but with safety features on things that allow programmers to shoot themselves (such as pointers and memory management).  Easy to fall into since it touches so many different things.  Hitleresque regarding the Object Oriented paradigm.  There are cool aspects (perhaps Spring and Hadoop?), but run, don’t go down this road. [{% link 1 http://www.paulgraham.com/avg.html %}]

<h3 style="display: inline"><strong>Scala</strong></h3> – Java’s cool cousin.  All the good stuff of Java (the immense infrastructure and resources), but with a cool functional twist (like smoking cigs in the parking lot with the cool kids).  If you are going to learn Java, learn it via Scala.  Pay attention to words like Map and Reduce.  Study up on recursion and pattern matching.  Think in a functional mindset, don’t forget your math: f(x) = x.  Good teams use it: Twitter, Firebase, Coursera, etc.  Good for infrastructure. [{% link 1 http://blog.redfin.com/devblog/2010/05/how_and_why_twitter_uses_scala.html#.UfABLutQ2wY %}, {% link 2 http://www.quora.com/What-are-the-backend-technologies-that-enable-Firebase %}]

<h3 style="display: inline"><strong>Objective-C / Swift</strong></h3> – IOS or Mac programming.  Probably pair with Android and go for mobile, although hope for the success of HTML5 and a merging of phone differences in similar fashion to browser differences.  It is better for all developers to be able to create an interface in one language that works on all devices.  Only choose Objective-C if you need the special features and functionality on iPhones or iPads for something like augmented reality or games. [{% link 1 http://www.businessinsider.com/html5-vs-apps-heres-why-the-debate-matters-and-who-will-win-2012-12 %}]

<h3 style="display: inline"><strong>C++</strong></h3> - The object oriented version of C, thus C plus 1.   Again, you probably shouldn’t bother with it unless you absolutely need the performance and can’t scale with more machines.  Pointers and C/C++ are more a right of passage than a viable means of rapid development, although it does power Google and many other things. [{% link 1 http://simpleprogrammer.com/2012/12/01/why-c-is-not-back/ %}, {% link 2 http://stackoverflow.com/questions/4773379/official-programming-languages-at-google %}]

<h3 style="display: inline"><strong>PHP</strong></h3> – The easiest way to do web programming.  A procedural monstrosity with new object oriented makeup (shining a turd?).  Ubiquitous for web development and nothing else.  Go with it to quickly build a website, but recognize that its potential is limited.  Tons of tools and developers, but its embedded nature makes it tough to scale.  You will be better of in the future with Ruby, Python, JavaScript, Scala, etc.  [{% link 1 http://www.codinghorror.com/blog/2012/06/the-php-singularity.html %}]

<h3 style="display: inline"><strong>C#</strong></h3> - The new Microsoft way of doing things.  Java meets C++.  If you love Microsoft, want to work in enterprise development and don’t like Java then go with C#.  Otherwise, avoid it like a deck chair on the Titanic.  F# could be interesting.  Amazing things can and have been built with it, but the choice was most likely due to team familiarity with the Microsoft ecosystem. [{% link 1 http://meta.stackoverflow.com/questions/10369/which-tools-and-technologies-are-used-to-build-the-stack-exchange-network %}]

<h3 style="display: inline"><strong>(Visual) Basic</strong></h3> – The old Microsoft way of doing things.  Don’t touch this unless you are working on a secret government computer in Iraq and are killing time building a Sudoku solving program in Excel. [{% link 1 http://iq.worldmapz.com/photo/27613_en.htm %}]

<h3 style="display: inline"><strong>Python</strong></h3> – Learn this language.  As close to pseudo code as a language can be.  Great for systems programming, web development (Django, Twisted, Tornado, Flask, etc.), or scientific research.  Plays well with C for performance.  Consuming everything in its path: lisp at MIT, R for data analysis, C for computer vision, Matlab. [{% link 1 http://cemerick.com/2009/03/24/why-mit-now-uses-python-instead-of-scheme-for-its-undergraduate-cs-program/ %}, {% link 2 http://www.johndcook.com/blog/2012/10/24/python-for-data-analysis/ %}, {% link 3 http://www.stat.washington.edu/~hoytak/blog/whypython.html %}]

<h3 style="display: inline"><strong>Perl</strong></h3> – The daddy of scripting languages.  So fantastic at string parsing and regular expressions that other languages have stolen its mojo and absorbed the best parts.  Pass unless dealing with legacy code. [{% link 1 http://programmers.stackexchange.com/a/115853 %}]

<h3 style="display: inline"><strong>JavaScript</strong></h3> – Learn this language.  The only option in the browser.  Bad parts and good parts.  Study up on prototypical inheritance and closures.  Moving from the client to the server with Node.  Some believe it will reign preeminent and eat up the world, but I think Python will triumph on the back-end due to its strength in Academia (ironic when compared to Lisp).[* see footnote]  Don’t forget to pickup HTML and CSS too. [{% link 1 http://insights.dice.com/2013/05/13/javascript-is-eating-the-world-2/ %}]

<h3 style="display: inline"><strong>Ruby</strong></h3> – Possibly learn this language.  When paired with Rails, may be the best option for rapid web development.  A syntactically-elegant, dynamic cousin to Python.   Translate your knowledge into client side development with CoffeeScript.  May get caught in a pincer movement between JavaScript on the Front-End and Python on the Back-End.  Watch out for the community. [{% link 1 http://web.archive.org/web/20080103072111/http://www.zedshaw.com/rants/rails_is_a_ghetto.html %}]

<h3 style="display: inline"><strong>SQL</strong></h3> – Not a programming language, but variants are.  The main way to communicate with relational databases.  Don’t learn this unless you need it.   Many frameworks will have wrappers.  While RDBs aren’t going anywhere, NoSQL may be the better option for a majority of your tasks.

<h3 style="display: inline"><strong>Lisp</strong></h3> – The mainstay of Academia and Artificial Intelligence.  Variants abound: Scheme, Closure, etc.  Must have a love of parenthesis.  A great language to learn about programming from a mathematical perspective.  While it has been used in production, its primarily role has been inside the glass house.  Pass, unless for pure learning. [{% link 1 http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/ %}]

<h3 style="display: inline"><strong>Matlab</strong></h3> – Another workhorse of Academia.  Capabilities in computer vision, statistical analysis, and much more, not a general purpose programming language.  For similar tasks you can use the free version: Octave, but you should really just focus on Python and IPython.

<h3 style="display: inline"><strong>Bash</strong></h3> -  Shell scripting.  Crucial to learn the Unix tools such as grep, sort, cat, pipe, etc.  Can, however, perform the exact same tasks in other more powerful general purpose scripting languages such as Python, Perl, and Ruby. [{% link 1 http://magazine.redhat.com/2008/02/07/python-for-bash-scripters-a-well-kept-secret/ %}]

<h3 style="display: inline"><strong>Pascal</strong></h3> – Avoid like the plague along with Fortran and Cobol, unless an absolute necessity for work.

<h3 style="display: inline"><strong>Assembly</strong></h3> -  Only learn if your code needs the absolute in performance and you can’t scale it with more machines.  Or if you are into NOP sleds.  Can be beneficial, like Lisp and C, for gaining a better understanding of computers, but best avoided unless you want to stab things into your eyes.

<h3 style="display: inline"><strong>Erlang</strong></h3> – A functional language for your tool chest.  Haskell and its type system may be better learning.  For concurrent server code, Go may be a better way to go.  When solid in another language or two, study these for a better grasp of functional programming, type systems, and concurrency. [{% link 1 http://www.quora.com/Erlang-Haskell-OCaml-screw-one-marry-one-kill-one-Which-and-why %}]

<h3 style="display: inline"><strong>Prolog</strong></h3> – Logic Programming.  An entirely different way of programming from from functional, object-oriented, or procedural programming.  Maybe worth studying, but practical applications are so far limited.  Who knows, maybe it’s the future and will infiltrate the mainstream just like functional programming did due to its ease of use in parallel architectures.

In conclusion: Learn Python and JavaScript for the long haul in multiple areas: client, server, sys admin, data analysis, computer vision, machine learning… Learn Ruby and Rails for a short sprint in web development.  Learn Scala if working with a team on infrastructure.  Learn Scala and Objective-C for mobile. Learn C, Lisp, Haskell, Go, Prolog, SQL, or Octave if the time, inclination, or need presents itself.

*** The first draft of this was written a few years ago.  I've since come to believe JavaScript is the only must learn language.
