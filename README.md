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
 

