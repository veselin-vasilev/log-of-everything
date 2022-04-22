#### 22 April 2022
* [Using Event-Driven Design with Apache Kafka Streaming Applications ft. Bobby Calderwood
](https://developer.confluent.io/podcast/using-event-driven-design-with-apache-kafka-streaming-applications-ft-bobby-calderwood)
  * It rehashes a lot of what I've already read in [[Designing Event-driven Systems]] or [[Jay Kreps]]' "The log...". 
  * The analogy of the chessboard [[Bobby Calderwood]] used was really good. Basically, the board, the pieces, and the current state are your data model. The event model is concerned with modelling how to capture each move by the players. 
  * Learned about [oNote](https://www.onote.com/) which might prove useful in the future. It's an event modelling tool. 
  * [Event modelling](https://eventmodeling.org/) itself is a new concept and process which is worth learning more about.
  * There are other useful links on the episode page!
* [List of Markdown emoji in GitHub](https://gist.github.com/rxaviers/7360908)

#### 5 April 2022
* Read [Staff Engineering at Carta](https://medium.com/building-carta/staff-engineering-at-carta-526b154fd317). It was an interesting insight into how [[Carta]]'s engineers operate at this level of seniority. It rehashed a lot of content from [[Will Larson]]'s  [staffeng.com](https://staffeng.com). 
	* *Alone, the term “staff engineer” only describes your level, not your role. A staff engineer may align with more than one of these archetypes, or change over time. It is important to recognize that **these are modes of operation that describe your work** — they are not a career path.* (emphasis is mine)
	* There was also an interesting link to a presentation: [Role and Influence: The IC trajectory beyond Staff](https://leaddev.com/leaddev-live/role-and-influence-ic-trajectory-beyond-staff). Should find the time to watch it at some point. 
	* I also liked the link to [Engineering Ladders](http://www.engineeringladders.com) and how they've defined the 5 axes for an engineer's development: 
		* Technology
		* System
		* People
		* Process
		* Influence
	* #career #staff

#### 3 April 2022
* Read the [guides](https://staffeng.com/guides) portion of [staffeng.com](https://staffeng.com) by [[Will Larson]]. It is definitely a great resource, one that I will keep coming back to as my career progresses. When the time comes to consider aiming for a Staff of Principal position (if this is still my inclination years in the future), it will definitely be reread.  
* I am still to make my way through the [Stories](https://staffeng.com/stories) section.
* As with a lot of technical books, the [resources](https://staffeng.com/guides/learning-materials) section is where *a lot* of added value can be found. I will regularly come back to it for inspiration on things to read or watch.

#### 2 April 2022
* [Fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
	* Useful to keep as a reference of things to keep in mind!
	* #engineering  #distributed-systems 
* 

#### 1 April 2022
* [Embedded Finance](https://risksave.com/news/2022/3/25/embedded-finance)
	* Article shared by [[Currencyclours]]'s [[LinkedIn]] account. 
	* Written by a partner of theirs - [[RiskSave Technologies]]
	* Outlines what embedded finance means for the fintechs of the world and how it's likely becoming a big thing in a lot of offerings, both traditionally financial and not.
	* *If you’ve used a popular ride-sharing app or taxi service or enjoyed a take-away from [Deliveroo](https://deliveroo.co.uk/), then you’ve benefited from embedded finance.*
	* #finance #fintech 
* [Embedded Finance: What It Is And How To Get It Right](https://www.forbes.com/sites/forbesfinancecouncil/2021/08/27/embedded-finance-what-it-is-and-how-to-get-it-right/?sh=6a6cb2173677)
	* A [[Forbes]] article on embedded finance.
	* *Simply put, embedded finance is the use of financial tools or services — such as lending or payment processing — by a non-financial provider. For example, an electrical shop could offer point-of-service insurance for goods sold in-store.*
	* #finance #fintech 
* [The Log: What every software engineer should know about real-time data's unifying abstraction](# The Log: What every software engineer should know about real-time data's unifying abstraction) by [[Jay Kreps]]
	* An incredible piece of technical knowledge, it is a must read!
	* It is basically a summary of the ideas presented in the [Designing Event Driven Systems] book by [[Ben Stopford]]. Though a "summary" is probably not the right word - Kreps' article predates the book. The book merely expands all that is said in the article!
	* **The resources at the end are brilliant as well, probably most of them worth reading or looking into!**
	* #software-architecture #distributed-systems #kafka
* [[Designing Event Driven Systems]] by [[Ben Stopford]]
	* In [O'Reilly](https://learning.oreilly.com/library/view/designing-event-driven-systems/9781492038252/ )
	* Can also be downloaded for free from [Confluent](https://www.confluent.io/designing-event-driven-systems/).
	* A good book, which summarizes a lot of ideas about modern software architecture and distributed systems. Definitely highly recommended!
	* #software-architecture #distributed-systems #kafka

#### 31 Mar 2022
* [Anna Karenina principle](https://en.wikipedia.org/wiki/Anna_Karenina_principle)
	* *All happy families are alike; each unhappy family is unhappy in its own way.*
	* *The **Anna Karenina principle** states that a deficiency in any [one of a number of factors](https://en.wikipedia.org/wiki/Limiting_factor "Limiting factor") dooms an endeavor to failure. Consequently, a successful endeavor (subject to this principle) is one for which every possible deficiency has been avoided.
	* I found this out from [[Jay Kreps]]'s article about logs [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying). He phrased it like this: *"Each working data pipeline is designed like a log; each broken data pipeline is broken in its own way."*
* [Atomic Broadcast]([Atomic Broadcast](https://en.wikipedia.org/wiki/Atomic_broadcast))
	* *In fault-tolerant distributed computing, an **atomic broadcast** or **total order broadcast** is a broadcast where all correct processes in a system of multiple processes receive the same set of messages in the same order; that is, the same sequence of messages. The broadcast is termed "atomic" because it either eventually completes correctly at all participants, or all participants abort without side effects. Atomic broadcasts are an important distributed computing primitive.*
	* #distributed-systems 
* [Efficient data transfer through zero copy](https://developer.ibm.com/articles/j-zerocopy/?mhsrc=ibmsearch_a&mhq=zero)
	* Didn't read the whole thing, and it seem fairly low level, but it is nice to be aware of the concept of "zero copy data transfer". As far as I understand it, it's basically a way to bypass the hop through the application layer that a piece data has to do before being written out to a web socket, by requesting the kernel to kopy the data directly from the disk file to the socket.
	* #engineering 
* [Building LinkedIn’s Real-time Activity Data Pipeline](http://sites.computer.org/debull/A12june/pipeline.pdf)
	* Kafka's paper
	* #kafka #software-architecture #engineering #distributed-systems 
* [IN-STREAM BIG DATA PROCESSING](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
	* #software-architecture #engineering #distributed-systems 

