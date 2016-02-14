# Awesome Competitive Programming [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome competitive programming / algorithm / data structure resources.

This list was created with a view to connect more people to information. It's aimed to cover a wide range of aspects and be a useful list for all.

*[![Build Status](https://travis-ci.org/lnishan/awesome-competitive-programming.svg?branch=master)](https://travis-ci.org/lnishan/awesome-competitive-programming) (link status powered by [dkhamsing/awesome_bot](https://github.com/dkhamsing/awesome_bot))*


## Contributing
Please kindly follow [CONTRIBUTING.md](CONTRIBUTING.md) to get started (including TODOs).


## Table of Contents
* [Awesome Reference Materials](#awesome-reference-materials)
    * [Knowledge](#knowledge)
        * [Syllabuses](#syllabuses)
        * [List of Lists](#list-of-lists)
        * [Articles](#articles)
    * [Implementations / Notebooks](#implementations--notebooks)
    * [Language Specifics](#language-specifics)
        * [C/C++](#cc)
        * [Java](#java)
        * [Miscellaneous](#miscellaneous)
* [Awesome Learning Materials](#awesome-learning-materials)
    * [Open Courses](#open-courses)
    * [Books](#books)
        * [Books for Algorithms](#books-for-algorithms)
        * [Books for Mathematics](#books-for-mathematics)
    * [Sites to Practice](#sites-to-practice)
        * [Problem Classifiers](#problem-classifiers)
        * [Contest Calendars](#contest-calendars)
    * [Sites to ask Questions](#sites-to-ask-questions)
    * [Other Awesome Websites](#other-awesome-websites)
* [Social Media](#social-media)
	* [Blogs](#blogs)
	* [Team Wikis](#team-wikis)
	* [Youtube and Livestreams](#youtube-and-livestreams)
	* [Quora](#quora)
* [Appendix](#appendix)
    * [Other Awesome Articles and FAQs](#other-awesome-articles-and-faqs)
* [License](#license)


## Awesome Reference Materials

### Knowledge

#### Syllabuses
What to learn / What to look for.

- [IOI Syllabus](https://people.ksp.sk/~misof/ioi-syllabus/)  
A detailed syllabus on which IOI contestants will be tested. This is still somewhat relevant to ACM-ICPC.
- [Programming Camp Syllabus](https://docs.google.com/document/d/1_dc3Ifg7Gg1LxhiqMMmE9UbTsXpdRiYh4pKILYG2eA4/edit)  
It was said to be an unofficial syllabus for ACM-ICPC.

#### List of Lists
A list of awesome curated lists.

- [Good Blog Post Resources about Algorithm and Data Structures - Codeforces](http://codeforces.com/blog/entry/13529)  
A collection of fantastic tutorial blog posts written by Codeforces users. Some intriguing ones include Palindromic Trees, Policy Based Data Structures, and a lot more.
- [Data Structures and Algorithms - CodeChef Discuss](https://discuss.codechef.com/questions/48877/data-structures-and-algorithms)  
A very complete list of competitive programming resources. A must-have in your browser bookmark.
- [hkirat/awesome-competitive-coding](https://github.com/hkirat/awesome-competitive-coding)  
This list collected materials for some relevant topics in competitive programming.

#### Articles
Sites with awesome articles.

In addition to the [List of Lists](#list-of-lists) section above,  
Here are some additional ones:

- [topcoder Data Science Tutorials](https://www.topcoder.com/community/data-science/data-science-tutorials/)  
This is a list of tutorials written by respected topcoder members. Many top programmers started learning data sciences from here.
- [E-Maxx (Russian)](http://e-maxx.ru/algo/), [(English)](http://e-maxx-eng.github.io/)  
Emaxx is widely used in the Russian-speaking competitive programming scene. Only a small fraction of the original site is translated into English, but Google Translate would work okay.
- [Algorithms | GeeksforGeeks](http://www.geeksforgeeks.org/fundamentals-of-algorithms/)  
Geeksforgeeks has a large amount of nicely written articles on different topics. It is a great complimentary resource for algorithm courses.
- [PEGWiki](http://wcipeg.com/wiki/Special:AllPages)   
PEGWiki is arguably much better than Wikipedia. It houses amazing in-depth wiki-like writeups on many topics.
- [algolist (Russian)](http://algolist.manual.ru/)  
algolist is a website devoted to algorithms of all sorts.
- [演算法筆記 (Algorithm Notes) (Chinese)](http://www.csie.ntnu.edu.tw/~u91029/)  
演算法筆記 is one of the most popular tutorial websites among the Taiwanese competitive programming community. The maintainer for this website spends immense efforts on researching algorithms.
- [国家集训队论文 1999-2015 (Papers from Chinese IOI training camps) (Chinese)](http://download.csdn.net/album/detail/657/1/1)  
These are papers from the Chinese IOI training camps. It's interesting for the fact that one can tell different regions emphasize different things.
- [LeetCode Video Tutorials](https://www.youtube.com/playlist?list=PLvHc59peqCbM43SNkoQpk59Ys05kHbHjH)  
A set of videos explaining LeetCode problems.
- [数据结构与算法/leetcode/lintcode题解 (LeetCode tutorials) (Chinese)](http://algorithm.yuanbin.me/zh-hans/index.html)  
This site offers tutorials on popular interview topics.

### Implementations / Notebooks
Algorithm / Data structure implementations.  
It is advised that you write your own ones before looking at others'.

- [CodeLibrary](http://www.codelibrary.ml/), by Andrey Naumenko ([user:indy256])  
This site contains a large amount of implementations for algorithms and data structures in Java and C++. You may also visit his [GitHub Repository](https://github.com/indy256/codelibrary).
- [Stanford University ACM Team Notebook (2014-15)](http://stanford.edu/~liszt90/acm/notebook.html)  
Stanford's team notebook is well maintained and the codes within are high-quality.
- [SuprDewd/CompetitiveProgramming](https://github.com/SuprDewd/CompetitiveProgramming), by team viRUs from Reykjavik University  
One of the very few notebooks to include a tester (even integration with Travis CI). A great notebook to learn from.
- [bobogei81123/bcw_codebook](https://github.com/bobogei81123/bcw_codebook), by team bcw0x1bd2 from National Taiwan University  
bcw0x1bd2 is the team representing National Taiwan University for the 2016 ACM-ICPC World Finals. Nice implementations for advanced data structures and algorithms.
- [foreverbell/acm-icpc-cheat-sheet](https://github.com/foreverbell/acm-icpc-cheat-sheet)  
A notebook with some advanced data structures and algorithms.
- [Spaghetti Source - 各種アルゴリズムの C++ による実装 (Japanese)](http://www.prefield.com/algorithm/)  
A neatly categorized notebook in Japanese. This website is no longer being updated, but the topics discussed here are still relevant.
- [igor's code archive](http://shygypsy.com/tools/)  
A good notebook by Igor Naverniouk who is currently a software engineer at Google and part of the Google Code Jam team.

### Language Specifics
This section mainly focuses on languages and other miscellaneous knowledge.

#### C/C++

- [Power up C++ with the Standard Template Library: Part 1 – topcoder](https://www.topcoder.com/community/data-science/data-science-tutorials/power-up-c-with-the-standard-template-library-part-1/)  
[Power up C++ with the Standard Template Library: Part 2 – topcoder](https://www.topcoder.com/community/data-science/data-science-tutorials/power-up-c-with-the-standard-template-library-part-2/)  
Learn how to use basic C++ standard template libraries.
- [Yet again on C++ input/output - Codeforces](http://codeforces.com/blog/entry/5217)  
Learn more about C++ I/O optimizations.
- [C++ Tricks - Codeforces](http://codeforces.com/blog/entry/15643)  
[What are some cool C++ tricks to use in a programming contest? - Quora](https://www.quora.com/Competitive-Programming/What-are-some-cool-C++-tricks-to-use-in-a-programming-contest)  
Plentiful C++ tricks for competitive programming. Note that some should be used with care.
- [C++ STL: Policy based data structures - Codeforces](http://codeforces.com/blog/entry/11080)  
[C++ STL: Policy based data structures. Part 2 - Codeforces](http://codeforces.com/blog/entry/13279)  
Detailed introduction to the extra data structures implemented in GNU C++.  
The official documentation can be found [here](https://gcc.gnu.org/onlinedocs/libstdc++/ext/pb_ds/).
- [C++11 FAQ (English, Chinese, Russian, Japanese, Korean)](http://www.stroustrup.com/C++11FAQ.html)  
A list of FAQs regarding C++11 collected and written by Bjarne Stroustrup, the creator of C++.

#### Java

- [How to read input in Java — tutorial - Codeforces](http://codeforces.com/blog/entry/7018)  
Learn how to read input faster. This is a must-read for those who intend to use Java for competitive programming.
- [How to sort arrays in Java and avoid TLE - Codeforces](http://codeforces.com/blog/entry/7108)  
Some tips on how to avoid hitting the worst case of quick sort.
- [Java.math.BigInteger Class - TutorialPrint](http://www.tutorialspoint.com/java/math/java_math_biginteger.htm)  
A quick reference for the famous BigInteger class in Java. 
- [BigNum arithmetic in Java — Let's outperform BigInteger! - Codeforces](http://codeforces.com/blog/entry/17235)  
A basic but faster custom BigInteger class.
- [EZ Collections, EZ Life (new Java library for contests) - Codeforces](http://codeforces.com/blog/entry/14328)  
A Java library for contests written by Alexey Dergunov ([user:dalex]). ArrayList, ArrayDeque, Heap, Sort, HashSet, HashMap, TreeSet, TreeMap, TreeList and pair classes are implemented.

#### Miscellaneous

- [Bit Twiddling Hacks](https://graphics.stanford.edu/~seander/bithacks.html)  
A huge compiled list of bit manipulation tricks.
- [Comparing Floating Point Numbers, 2012 Edition | Random ASCII](https://randomascii.wordpress.com/2012/02/25/comparing-floating-point-numbers-2012-edition/)  
This post teaches everything one needs to know about floating point numbers. A must read especially for geometry topics.
- [你应该知道的浮点数基础知识 • cenalulu's Tech Blog (Chinese)](http://cenalulu.github.io/linux/about-denormalized-float-number/)  
Similar post on floating point numbers.
- [Object-Oriented C Style Languages: C++, Objective-C, Java, C# - a side-by-side reference sheet](http://hyperpolyglot.org/cpp)  
A detailed side-by-side reference sheet. This is very helpful for a C++ programmer who wants to learn Java (for BigInteger mostly).


## Awesome Learning Materials

### Open Courses
It's highly recommended that you begin your competitive programming journey with these awesome courses!

- [Stanford CS 97SI: Introduction to Competitive Programming Contests](http://web.stanford.edu/class/cs97si/)  
This course offers comprehensive lecture slides and a short list of exercise problems.
- [Reykjavik T-414-ÁFLV: A Competitive Programming Course](https://algo.is/competitive-programming-course/)  
An awesome course taught by [Bjarki Ágúst Guðmundsson ([user:SuprDewd])](https://algo.is). These lectures feature neat slides and a nice list of problems to practice.
- [NCTU DCP4631: Problem Solving and Programming Techniques](https://sites.google.com/site/mzshieh/courses/problem-solving-and-programming-techniques-spring-2014)  
A course on basic topics featuring good lecture slides.
- [建國中學資訊科培訓 (CKHS Training) (Chinese)](http://pisces.ck.tp.edu.tw/~peng/index.php?year=2012)  
Good lecture materials made by CKHS Infor Club.

### Books
A list of recommended books for competitive programming.

- [Competitive Programming](http://cpbook.net/), by Steven and Felix Halim  
This book contains a collection of relevant data structures, algorithms, and programming tips. It's a well-received book.  
The first edition is free for [download](http://www.comp.nus.edu.sg/~stevenha/myteaching/competitive_programming/cp1.pdf).
- [Programming Challenges: The Programming Contest Training Manual](http://www.amazon.com/Programming-Challenges-Contest-Training-Computer/dp/0387001638), by Steven Skiena and Miguel Revilla  
This book includes more than 100 programming challenges, as well as the theory and key concepts necessary for approaching them. Problems are organized by topic, and supplemented by complete tutorial material.
- [Looking for a Challenge](http://www.lookingforachallengethebook.com/), written by a group of authors associated with the Polish Olympiads  
Most of the problems described in the book are really hard but they are explained in such a way that even beginners can understand.  
It appears to be out of stock (as of Feb 10, 2016), but you can reserve one on their [official website](http://www.lookingforachallengethebook.com). 
- [The Hitchhiker’s Guide to the Programming Contests](http://comscigate.com/Books/contests/icpc.pdf), by Nite Nimajneb  
This book is free for [download](http://comscigate.com/Books/contests/icpc.pdf). This book covered various topics relevant to competitive programming.
- [プログラミングコンテストチャレンジブック (Japanese)](http://goo.gl/M4yfbr), by 秋葉拓哉, 岩田陽一, 北川宜稔  
培養與鍛鍊程式設計的邏輯腦：世界級程式設計大賽的知識、心得與解題分享 (Chinese Traditional)
- [算法竞赛入门经典 (Chinese)](http://www.tup.com.cn/booksCenter/book_05568701.html), by 刘汝佳  
The Art of Algorithms and Programming Contests (English)  
打下好基礎：程式設計與演算法競賽入門經典 (Chinese Traditional)
- [算法竞赛入门经典——训练指南 (Chinese)](http://www.amazon.cn/算法竞赛入门经典-训练指南-刘汝佳/dp/B009SJJGOU), by 刘汝佳, 陈锋  
提升程式設計的解題思考力─國際演算法程式設計競賽訓練指南 (Chinese Traditional)
- [算法艺术与信息学竞赛 (Chinese)](http://goo.gl/O1tr8v), by 刘汝佳, 黄亮

#### Books for Algorithms
- [Introduction to Algorithms](https://mitpress.mit.edu/books/introduction-algorithms), by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest and Clifford Stein  
Also known as CLRS (taken from name initials), this book is often referred to as the "bible" for algorithms and data structures. It's one of the most popular textbooks for university algorithm courses. This book covered various algorithms and data structures in great detail. The writing is more rigorous and can be difficult to some.
- [Algorithm Design](http://www.aw-bc.com/info/kleinberg/), by Jon Kleinberg and Éva Tardos  
This book revolves around techniques for designing algorithms. It's well-organized and written in a clear, understandable language. Each chapter is backed with practical examples and helpful exercises. The chapter on network flow is highly praised by lots.  
The lecture slides that accompany the textbook are available on its [official website](http://www.cs.princeton.edu/~wayne/kleinberg-tardos/).
- [The Algorithm Design Manual](http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693), by Steven S. Skiena  
The book is written in more readable text. Some find it comprehensive than other books. You can also find some good resources (including the author's own video lectures) on its [official website](http://www.algorist.com).
- [Algorithms](http://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X), by Robert Sedgewick and Kevin Wayne  
This book is neatly categorized, coupled with elaborate explanations and fantastic illustrations.

#### Books for Mathematics
- [Discrete Mathematics and Its Applications](http://www.amazon.com/Discrete-Mathematics-Applications-Kenneth-Rosen/dp/0072899050), by Kenneth H. Rosen  
Discrete Mathematics is closely relevant to competitive programming. This book provides comprehensive materials on a wide range of topics including: Logics and Proofs, Sets, Functions, Sequences, Matrices, Number Theory, Recursion, Counting, Probablity, Graphs, Trees and Boolean Alegra to name but a few.
- [Concrete Mathematics: A Foundation for Computer Science](http://www.amazon.com/Concrete-Mathematics-Foundation-Computer-Science/dp/0201558025), by Ronald L. Graham, Donald E. Knuth, Oren Patashnik  
The book offers a deeper look into Discrete Mathematics with more stresses on number-related topics.
- [Linear Algebra and Its Applications](http://www.amazon.com/Linear-Algebra-Its-Applications-5th/dp/032198238X/ref=sr_1_1?ie=UTF8&qid=1455475253&sr=8-1&keywords=Linear+Algebra+and+Its+Applications), by David C. Lay, Steven R. Lay, Judi J. McDonald  
The book does a good job at bridging the gap between a physical system (for scientists and engineers) and an abstract system (for mathematicians).
- [How to Solve It: A New Aspect of Mathematical Method](http://www.amazon.com/How-Solve-It-Mathematical-Princeton/dp/069111966X), by G. Polya  
An old-time classic. Overall, the author provides a systematic way to creatively solve problems.

### Sites to Practice
Good online judges / contest platforms to practice.

- [Codeforces](http://codeforces.com/)  
Codeforces is one of the most popular contest platforms in the world. Currently maintained by Saratov State University, it features regular contests and numerous awesome original problems. Every contest provides immediate helpful tutorials. Furthermore, many warm-hearted Codeforces members kindly answers questions on Codeforces. One would indeed learn and improve tremendously here.
- [TopCoder](https://www.topcoder.com/)  
TopCoder has been around since 2001. Rich in history, It's considered to be one of the most prestigious organizations when it comes to technology competitions. Hundreds of SRMs gave birth to an abundant problemset. Problems here are typically more challenging than others. Hence, TopCoder draws many elite programmers to compete and practice here. It has arguably been on a decline, but it still is a superb platform to practice. The annual TopCoder Open is also a widely-discussed event.
- [Google Code Jam](https://code.google.com/codejam)  
Google Code Jam is certainly one of the most highly-esteemed programming competitions. The competition consists of unique programming challenges which must be solved in a fixed amount of time. Competitors may use any programming language and development environment to obtain their solutions.
- [CodeChef](https://www.codechef.com/)  
CodeChef is a non-profit educational initiative of Directi. It's a global competitive programming platform and has a large community of programmers that helps students and professionals test and improve their coding skills. Its objective is to provide a platform for practice, competition and improvement for both students and professional software developers. Apart from this, it aims to reach out to students while they are young and inculcate a culture of programming in India.
- [SPOJ](http://www.spoj.com/)  
The SPOJ platform is centered around an online judge system. It holds a staggering amount of problems prepared by its community of problem setters or taken from previous programming contests, some of which are great problems for practice (refer to the [Problem classifiers](#problem-classifiers) section). SPOJ also allows advanced users to organize contests under their own rules.
- [Timus](http://acm.timus.ru/)  
Timus Online Judge is the largest Russian archive of programming problems with automatic judging system. Problems are mostly collected from contests held at the Ural Federal University, Ural Championships, Ural ACM ICPC Subregional Contests, and Petrozavodsk Training Camps.
- [SGU](http://acm.sgu.ru/)  
SGU is an old-school online judge maintained by Saratov State University. A high-rated competitive programmer - Huang I-Wen ([user:doreamon], dreamoon) thinks that it's the hardest online judge because its problems require unusual skills.
- [HDU](http://acm.hdu.edu.cn/)  
HDU is an online judge maintained by Hangzhou Dianzi University. It holds a pretty nice problemset. Users can also run virtual contests on this platform.
- [UVa](https://uva.onlinejudge.org/)  
An old-school problem archive / online judge with rich history. Thousands of problems, including many classic ones, are featured here. However, it is strongly advised that you practice with [uHunt](http://uhunt.felix-halim.net/id/0) following its "Competitive Programming Exercise" section.
- [HackerRank](https://www.hackerrank.com)  
HackerRank is a company that focuses on competitive programming challenges for both consumers and businesses. HackerRank's programming challenges can be solved in a variety of programming languages (including, but not limited to, Java, C++, PHP, SQL) and span multiple computer science domains.
- [POJ](http://poj.org/)  
POJ is an online judge maintained by Peking University. It holds a large amount of great problems.
- [Project Euler](https://projecteuler.net/)  
There are lots of good math problems on this site. You may also discuss with others on its forum.
- [Hackerearth](https://www.hackerearth.com/)  
HackerEarth is a startup technology company based in Bangalore, India that provides recruitment solutions. Its clients include Adobe, Altimetrik, Citrix Systems, InMobi, Symantec and Wipro.
- [Aizu Online Judge](http://judge.u-aizu.ac.jp/onlinejudge/index.jsp)  
Aizu online judge is a contest platform and problem archive hosted by The University of Aizu. It has a lot of great problems from programming competitions in Japan.

#### Problem Classifiers
Sites classifying programming problems.  
Choose a category (eg. DP) of interest and practice problems on that topic.

- [A2 Online Judge (Mixed)](http://a2oj.com/Categories.jsp)
- [Problem Classifier (SPOJ)](http://problemclassifier.appspot.com/)
- [UVa Online Judge (Competitive Programming Book)](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8)
- [Codeforces Tags (DP as an example)](http://codeforces.com/problemset/tags/dp)
- [HackerRank](https://www.hackerrank.com/domains/algorithms/warmup)
- [Lucky貓的 UVA（ACM）園地 (Chinese)](http://luckycat.kshs.kh.edu.tw/)

#### Contest Calendars
Calendars for impending programming contests.  
Never miss another contest!

- [Programming Contest Calendar | HackerRank](https://www.hackerrank.com/calendar)
- [clist.by](http://clist.by/)
- [Coding Calendar (Android App)](https://play.google.com/store/apps/details?id=com.limitskyapps.CodingCalendar)
- [Coder's Calendar](https://github.com/nishanthvijayan/CoderCalendar): [Android App](https://play.google.com/store/apps/details?id=com.corphots.coderscalendar), [Chrome Extension](https://chrome.google.com/webstore/detail/coders-calendar/bageaffklfkikjigoclfgengklfnidll), [Firefox Add-on](https://addons.mozilla.org/en-US/firefox/addon/coder-calendar/)
- [CodeHorizon](http://www.star-lord.me/CodeHorizon/): [iOS App](https://itunes.apple.com/in/app/codehorizon/id925056167?mt=8), [Android App](https://play.google.com/store/apps/details?id=com.chintanghate.CodeHorizon)

### Sites to ask Questions
These are great sites to ask questions.  
It is suggested that you paste your codes at [ideone](http://ideone.com) or [pastebin](http://pastebin.com).

- [Codeforces](http://codeforces.com/)
- [Competitive Programming - Quora](https://www.quora.com/topic/Competitive-Programming)
- [Theoretical Computer Science Stack Exchange](http://cstheory.stackexchange.com/)

### Other Awesome Websites
- [Virtual Judge (vjudge)](http://vjudge.net)  
Virtual Judge (vjudge) allows users to create virtual contests with problems from notable problem archives such as: Codeforces, SPOJ, UVa, POJ, Codechef ... etc..
- [BNU Online Judge](http://www.bnuoj.com/v3/)  
BNU Online Judge also allows users to create virtual contests. The interface is quite nice but it isn't as widely used as the previous one (vjudge).
- [VisuAlgo](http://visualgo.net)  
VisuAlgo features a large collection of visualization tools for algorithms and data structures.
- [USA Computing Olympiad (USACO)](http://www.usaco.org/)  
USACO contains several training pages on its website which are designed to develop one's skills in programming solutions to difficult and varied algorithmic problems at one's own pace.
- [The On-Line Encyclopedia of Integer Sequences (OEIS)](https://oeis.org/)  
A stunning encyclopedia with a database of countless integer sequences. It also features a powerful search engine. Sometimes a seemingly difficult combinatorics problem can be equivalent to a simple or known and studied integer sequence.

## Social Media
Meet the god-like competitive programmers!  
Learn helpful tips, tutorials and insights from these people :)

### Blogs
- [Codeforces blogs](http://codeforces.com/)
- Petr Mitrichev ([user:Petr]): [Algorithms Weekly](http://petr-mitrichev.blogspot.com/)
- Bruce Merry ([user:bmerry]): [Entropy always increases](http://blog.brucemerry.org.za/)
- Przemysław Dębiak ([user:SomeGuyTookMyHandle], Psyho): [Psyho's blog](http://psyho.gg/)
- Anudeep Nekkanti ([user:anudeep2011]): [Namespace Anudeep ;)](http://blog.anudeep2011.com/)
- vexorian ([user:vexorian]): [vexorian's blog](http://www.vexorian.com/)
- Ashar Fuadi ([user:fushar]): [Fushar's blog](http://fusharblog.com/)
- LiJie Chen ([user:WJMZBMR]): [WJMZBMR (Chinese)](http://wjmzbmr.com/)
- Huang I-Wen ([user:doreamon], dreamoon): [小月的耍廢日誌 (Chinese)](http://dreamoon4.blogspot.tw/)
- Po-Jui Chen ([user:a00012025]): [code倉庫 (Chinese)](http://cbdcoding.blogspot.tw/)
- Shiang-Yun Yang (morris1028): [Morris' Blog (Chinese)](http://morris821028.github.io/)
- Yuhao Du ([user:TooDifficuIt], TooSimple, xudyh): [xudyh (Chinese, Emptied)](http://xudyh.github.io/)

### Team Wikis
- Dreadnought ([user:TankEngineer], [user:rowdark], [user:AngryBacon]): [Dreadnought's Wiki (Chinese)](http://dreadnought.icpc-camp.org/)

### Youtube and Livestreams
- [HackerRank Live Youtube](https://www.youtube.com/channel/UCmyXobPA1T5Vsf28lrBkiSw)
- Petr Mitrichev ([user:Petr]): [Youtube](https://www.youtube.com/channel/UCdmeooqNtlN7IhrKlq7hGDA)
- Egor Kulikov ([user:Egor]): [Youtube](https://www.youtube.com/channel/UCjlLfxSPkYluCDetlwbLpjQ)
- Adam Bardashevich ([user:subscriber]): [Youtube](https://www.youtube.com/channel/UCc4jWVeWjUfpUo8z4PHfopw)
- Bohdan Pryshchenko ([user:I_love_Tanya_Romanova]): [Twitch](http://www.twitch.tv/lebron_stream), [Youtube](https://www.youtube.com/channel/UCWqqnonyL7aVeUYl5Yp8TrQ)
- Vladimir Smykalov ([user:enot.1.10]): [Twitch](http://www.twitch.tv/enot110), [Youtube](https://www.youtube.com/channel/UCWEVsnIXiD5mgWM0LFwZBzA)

### Quora
Visit [Competitive Programming - Quora](https://www.quora.com/topic/Competitive-Programming) ([Top 10 Most Viewed Writers](https://www.quora.com/topic/Competitive-Programming/writers)).

Awesome people to follow (Too many people to list, separated by commas and in groups of 3's thus):  
[Michal Forišek ([user:misof])](https://www.quora.com/profile/Michal-Fori%C5%A1ek), 
[Brian Bi ([user:bbi5291])](https://www.quora.com/profile/Brian-Bi), 
[Jonathan Paulson ([user:jonathanpaulson])](https://www.quora.com/profile/Jonathan-Paulson),   
[Miguel Oliveira ([user:mogers])](https://www.quora.com/profile/Miguel-Oliveira-2), 
[Egor Suvorov ([user:yeputons])](https://www.quora.com/profile/Egor-Suvorov), 
[Michal Danilák ([user:Mimino])](https://www.quora.com/profile/Michal-Danil%C3%A1k),   
[Bohdan Pryshchenko ([user:I_love_Tanya_Romanova])](https://www.quora.com/profile/Bohdan-Pryshchenko), 
[Vladimir Novakovski ([user:vnovakovski])](https://www.quora.com/profile/Vladimir-Novakovski), 
[Nick Wu ([user:xiaowuc1])](https://www.quora.com/profile/Nick-Wu-4),   
[Cosmin Negruseri](https://www.quora.com/profile/Cosmin-Negruseri), 
[Lalit Kundu ([user:darkshadows])](https://www.quora.com/profile/Lalit-Kundu), 
[Ashish Kedia ([user:ashish1294])](https://www.quora.com/profile/Ashish-Kedia),   
[Johnny Ho ([user:random.johnnyh])](https://www.quora.com/profile/Johnny-Ho), 
[Thanh Trung Nguyen ([user:I_love_Hoang_Yen])](https://www.quora.com/profile/Thanh-Trung-Nguyen), 
[Anudeep Nekkanti ([user:anudeep2011])](https://www.quora.com/profile/Anudeep-Nekkanti),   
[Steven Hao ([user:stevenkplus])](https://www.quora.com/profile/Steven-Hao), 
[Raziman T.V. ([user:razimantv])](https://www.quora.com/profile/Raziman-T-V), 
[Joshua Pan ([user:lonerz])](https://www.quora.com/profile/Joshua-Pan-1).


## Appendix

### Other Awesome Articles and FAQs

- [The 'science' of training in competitive programming - Codeforces](http://codeforces.com/blog/entry/17842), by Thanh Trung Nguyen ([user:I_love_Hoang_Yen])
- [If you ask me how to improve your algorithm competition skill, I will give you the link of this blog. - Codeforces](http://codeforces.com/blog/entry/16599), by Huang I-Wen ([user:doreamon], dreamoon)

- [How do I start competitive programming? - Quora](https://www.quora.com/How-do-I-start-competitive-programming-5)
- [How can I become good at competitive programming? - Quora](https://www.quora.com/How-can-I-become-good-at-competitive-programming-Are-there-any-courses-that-will-take-me-one-step-forward-before-I-start-doing-SPOJ-or-TopCoder-problems)  
[What is the best strategy to improve my skills in competitive programming in 2-3 months? - Quora](https://www.quora.com/What-is-the-best-strategy-to-improve-my-skills-in-competitive-programming-in-2-3-months)  
[What is a good 6 month plan to start and progress through competitive programming? - Quora](https://www.quora.com/What-is-a-good-6-month-plan-to-start-and-progress-through-competitive-programming)
- [How is competitive programming different from real-life programming? - Quora](https://www.quora.com/How-is-competitive-programming-different-from-real-life-programming)
- [What have you gained from competitive programming? - Quora](https://www.quora.com/What-have-you-gained-from-competitive-programming)


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jasmine Chen](https://github.com/lnishan) has waived all copyright and related or neighboring rights to this work.
