# software-assignment1


	Research Paper Assignment: (Software Engineering) 
 
Name: Alina Rajput 
Rollno: 2k18/CSM/10 
 
01) Comprehension Challenges at the Level of Software Ecosystems and Global Software Engineering 
By: Yann-Gaël Guéhéneuc Author: Ralf Lämmel 
 
In this talk, they discuss program comprehension-related work, technologies, and challenges at Facebook from the attitude of a programmer and researcher operating within the context of developer infrastructure. This discussion will cover notably ownership management [1], work-item prediction [2], but also other areas en passant (e.g., code search and indexing, program generation, and data warehousing). 
 
Ownership management – understand what's best owned by whom. While the quality processes make sure that all products and merchandise features are owned in an accountable manner also extending to the underlying assets (tables, code artifacts, etc.), new sorts of automation can help to suggest more suitable owners for any given asset at a given point in time. Who is that the best suited indeed changes over time, e.g., thanks to reorganization and individual function changes. By such efforts on ownership health, accountability of ownership is further increased. 
 
Work-item prediction – understand who is functioning on what when. Understanding what a programmer (a developer, a production engineer, a test engineer, a knowledge scientist, etc.) is functioning on may be a challenging problem – especially when considering complex software engineering workflows: a) engineers use a myriad of loosely integrated tools coming, going, and evolving all the time; b) engineers do much context switching between different ‘work items’ (such as diffs for system changes); c) infrastructure and engineering processes aren't fully conscious of work items 
 
In these two areas and yet others in developer infrastructure, a mixture of ultra large scale processing , data processing , data extraction and cleaning, and logging integration, heuristics and ML is required . Also, we aren't simply handling individual programs, monolithic systems, or well-defined systems of systems – instead, we are handling a heterogeneous, rapidly evolving software ecosystem – as an example , in terms of how different version control systems, continuous integration approaches, language implementations, IDEs, project management and documentation tools, and data warehouse technologies are assembled to supply one infrastructure on which, in turn, the particular apps and backend services depend. Further, development is very distributed, depends on evolving team structures and responsibilities, and therefore the relevant employee workflows are rather involved, thereby also entering the realm of worldwide software 	engineering. 
 
The talk extracts a search agenda from experiences with these areas. None of the discussed challenges and problems are specific to the Facebook setting and, in fact, much of the progress are often expected to be achieved within the context of research on open-source ecosystems. 
 
[1]	John Ahlgren, Maria Eugenia Berezin, Kinga Bojarczuk, Johann George, Natalija Gucevska, Mark Harman, 
Shan He, Ralf Lämmel, Erik Meijer, Silvia Sapora, and Justin Spahr-Summers. 2020. Ownership at Large – Open Problems and Challenges in Ownership Management. In Proceedings of the 28th IEEE/ACM International Conference on Program Comprehension (ICPC Industry Track). IEEE / ACM. 
[2]	Ralf Lämmel, Alvin Kerber, and Liane Praza. 2020. Understanding What Software Engineers Are Working on – The Work-Item Prediction Challenge. In Proceedings of the 28th IEEE/ACM International Conference on Program Comprehension (ICPC Industry Track). IEEE / ACM. 
 







02) Testing of Mobile Applications in the Wild: A Large-Scale Empirical Study on Android Apps By: Dario Di Nucci 
 
Nowadays, mobile applications (a.k.a., apps) are employed by over two billion users for each sort of need, including social and emergency connectivity. Their pervasiveness in today’s world has inspired the software testing research community in devising approaches to permit developers to raised test their apps and improve the standard of the tests being developed. In spite of this attempt , we still notice a scarcity of empirical studies aiming at assessing the particular quality of test cases developed by mobile developers: this attitude could provide evidence-based findings on the present status of testing within the wild also as on the longer term research directions within the field. As such, we performed a large-scale empirical study targeting 1,780 open-source Android apps and aiming at assessing (1) the extent to which these apps are literally tested, (2) how welldesigned are the available tests, and (3) what's their effectiveness. The key results of our study show that mobile developers still tend to not properly test their apps. Furthermore, we discovered that the test cases of the considered apps have a coffee (i) design quality, both in terms of test code metrics and test smells, and (ii) effectiveness when considering code coverage also as assertion density. 
 

















03) Knowledge Transfer in Modern Code Review 
By: Hironori Washizaki 
 
Knowledge transfer is one among the most goals of recent code review, as shown by several studies that surveyed and interviewed developers. While knowledge transfer may be a clear expectation of the code review process, there are not any analytical studies using data mined from software repositories to assess the effectiveness of code review in “training” developers and improve their skills over time. We present a mining-based study investigating how and whether the code review process helps developers to enhance their contributions to open source projects over time. We analyze 32,062 peer-reviewed pull requests (PRs) made across 4,981 GitHub repositories by 728 developers who created their GitHub account in 2015. We assume that PRs performed within the past by a developer D that are subject to a code review process have “transferred knowledge” to D. Then, we verify if over time (i.e., when more and more reviewed PRs are made by D), the standard of the contributions made by D to open source projects increases (as assessed by proxies we defined, like the acceptance of PRs, or the polarity of the sentiment within the review comments left for the submitted PRs). With the above measures, we were unable to capture the positive impact played by the code review process on the standard of developers’ contributions. This could be thanks to several factors, including the alternatives we made in our experimental design. 
Additional investigations are needed to verify or contradict such a negative result. 
 

