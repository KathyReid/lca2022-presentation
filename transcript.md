
# Communities are systems: and the lessons we can draw for creating, caring and concluding them

A keynote presentation for linux.conf.au 2021:
https://linux.conf.au/schedule/presentation/34/

 _Kaya Theatre | Fri 14 Jan 5:45 p.m.–6:45 p.m._

Talk time: 45 minutes, plus 15 mins for questions, 1 hour total

## Introduction

SLIDE: Title slide with my affiliations and logos

Thanks so much for the introduction, HOST. I'm Kathy Reid, and as HOST mentioned,

SLIDE: School of Cybernetics

I'm currently a PhD candidate at the School of Cybernetics at the Australian National University, where I'm investigating voice data used in machine learning - and its implications for systems that use language technologies - like voice assistants and smart speakers, so I have a strong interest in computing systems, and the people who use them, or are used by them.

SLIDE: Blank, no content

And before I start the talk proper today, there are three things that I'd like to do.

- FIRST, I'd like to acknowledge that I'm presenting today from the unceded lands of the Wadawurrung people of the Kulin nation, here in Geelong - which is itself a Wadawurrung word, and I pay my respects to elders past and present, and to leaders emerging.

- SECONDLY, I'd like to acknowledge that linux.conf.au is a community-produced event, and I'd like to recognise the organisers and volunteers for their time and their labour. Without you, this conference - and the benefits it yields like connections across communities and the spread of new ideas and techniques - wouldn't happen as readily. Thank you.

- FINALLY, I want to acknowledge the toll that the last two years has taken on everyone. Since I last saw many of you on the Gold Coast, back in the Before Times of early 2020, many of us have been through lengthy lockdowns, and dealt with the background anxiety of case numbers, testing shortages, and upended economies, labour markets and supply chains. So I want to say thank you for choosing to be here, at an online event, delivered over video, and I'm really looking forward to the time when we can all see each other, alive, well, in person again. So thank you for locking down, for wearing masks, for home schooling, for isolating, for testing, for getting vaccinated. Because those actions don't just help keep us safe as individuals, they help safeguard us **all** as a _community_.

And _that_ takes me to the keynote proper.

## Outline

Many of us work with systems in our professional lives. And when we think of **systems**, we might think of some variant of these:

SLIDE: Gadi

That's the Gadi super computer in Canberra, one of the top 500 super computers in the world

Or we might think of something like this:

SLIDE: Dingo car from open hardware

That's a photo by Jaime Schmidt of the Dingo car from the open hardware miniconf at LCA2020.

Or, when we think of systems, we might think of something like this:

SLIDE: Arpanet topology 1976

That's a slide of the Arpanet topology - the predecessor to today's internet - circa about 1976 - probably fewer nodes than some of us have on our home networks today.

So when we think of **systems**, we tend to think of computing systems, cyber-physical systems. They can be as simple and as small as a single LED with a power source, or at the other extreme of scale, have millions of intangible and physical components, interconnected through different networking protocols, running myriad pieces of intertwined and interdependent software, all across the globe.

These systems can be _orchestrated_ - deliberately and carefully planned and designed - or - as we all know - they can grow _organically_ as box after box is provisioned for some prototype or pilot project - that never seems to be _entirely_ decommissioned. Over time, these systems grow in complexity, intertangled, interwined, until no one person can really know the _whole_ picture. They can exist for a brief period of time - how many containers have you spun up and spun down today - or for much longer - do we have any COBOL programmers in the house?! Then, at their end of life, they are disassembled, disaggregated and decommissioned, and hopefully, recycled.

So, many of us are conversant and comfortable thinking about computing and networking infrastructure as systems and systems of systems that have lifecycles, and connections, and components, and characteristics.

SLIDE: Definition of system from von Bertanlanffy

But at their most fundamental, **systems** are simply defined as "a set of elements in mutual interaction". And we can apply systems thinking to many different fields.

SLIDE: von Bertanlanffy General Systems theory

In his ground-breaking work on General Systems Theory, published in 1968, this chap - Ludwig von Bertanlanffy - set out principles for systems that apply to fields as diverse as biology, chemistry, ecology and sociology. You might have heard of some of these principles before - hierarchy, entropy, complexity. von Bertanlanffy held the view that the world itself was an organisation, comprised of many different systems, interacting and influencing each other. And he held the view that by thinking about _systems_, we would have better tools to explore, explain, and predict various phenomena.

So, systems, and systems thinking, is very widely applicable. And in fact, **communities**,  - like these

SLIDE: #lca2016 volunteers

the excellent volunteers at LCA 2016 in Geelong

SLIDE: #lca2012 volunteers

and these - the incredible volunteer team at LCA2012 in Ballarat

SLIDE: linux.conf.au community at LCA2014 in Perth

and these - I believe that's unPDNS in Perth in 2014

SLIDE: linux.conf.au 2008 Melbourne Penguin dinner

and these - that's the 2008 LCA Penguin dinner at the Bazaar - the night market

SLIDE: linux.conf.au lca2019 Christchurch

and these - the 2019 LCA Christchurch volunteers

all of these communities - and the community that you're a part of today by attending this conferencing online - can be considered as systems too!

So, the key tenet of my talk today is deceptively simple.

SLIDE: Communities are systems

Communities are systems, and the concepts we use for thinking about computing systems can also be used for thinking about the communities who develop, use and are affected by them. That is, by approaching the concept of community through the lens of _systems thinking_, we have a different toolbox - a set of concepts and ways that help us to create, care for, and conclude communities.

And I don't think I need to make the argument to _this_ audience about how vitally important communities are to computing and software systems - this entire conference is centred around a set of software designed, developed, distributed and adopted by a community of millions around the world. That software - and its world-changing impact - wouldn't exist without _communities_. So I'll take that argument as assumed.

However, one more nuanced point that I want to make - that perhaps isn't so readily evident - is that computing systems and community systems - social systems are closely coupled - they **influence** each other.

Sometimes when we design computing and cyber-physical systems, we view people and communities as distinct and separate elements of those systems.

SLIDE: Communities and users as separate

In this view, people or the community provide **inputs** - such as instructions, data, code contributions, or configurations or programs, and the computing system provided **outputs** - reports, calculations, predictions, new and so on. So this type of interaction can be thought of as primarily _transactional_. Inputs go in, the computing system does some processing or computation, and outputs come out.

Another view - for anyone who's done soft systems methodology - sees communities as a key, integral part of an overall system - as one of many interconnected components that make up a technology system,

SLIDE: Communities as part of the system

such as hardware, software, documentation, business models, user experience and so on. Again, this component-based view is primarily _transactional_ - the community is a part, a component that provides services or functionality or benefits to other parts of the system - such as adoption, community contributed code or documentation and so on, and in return receives benefits, such as easier to use products, peer support, increased functionality and so on.

Instead of this _transactional_ approach, when we think about technical systems and communities, I want us to start to think about _transformation_; not just about inputs or outputs or components that provide services and functions.

SLIDE: Communities and systems intertwined

I want us to think about how, by interacting with each other - influencing each other -  reciprocally and continually - through design decisions, path dependencies, competing drivers, emerging standards and many other factors - technical systems and people systems - **communities** - transform each other. Communities shape the computing systems that are built, and in turn, those systems influence and change the communities they interact with.

SLIDE: Values Sensitive Design

This view - that people and communities shape, and are shaped by the systems they interact with - is - not surprisingly - called an _interactionist_ view. And it's also the view taken in this book by Batya Friedman and David G. Hendry - called _Values Sensitive Design_. It's a fantastic read - and the overarching takeaway is that technology is imbued with the values of the people who create it.

And that's not always a **good** thing. For example -

SLIDE: Gender Shades

We have facial recognition technology, used in ever-increasing contexts and "capabilities"- that doesn't recognise people of colour, and especially women of colour -  as well as white people. _Gender Shades_ is the incredible work of Joy Buolamwini - who earlier this week submitted her PhD thesis - so please do congratulate her on Twitter - she's `@jovialjoy` - and in _Gender Shades_ she outlines how common facial recognition models just don't work for some people.

And there are clear reasons for this.

SLIDE: Discriminating systems

Firstly, we have far fewer women and people of colour working in Artificial intelligence to begin with. For example, this report by the team at AI Now in 2019 found that just 18% of authors at conferences in the field of artificial intelligence and machine learning - such as NeurIPS - are women. And less than 6% of people in large technical companies - that's fewer than one in 16 - identify as Black or Hispanic. If the people building systems are predominantly white men, then there are a narrower range of values represented in design decisions, in testing. Fewer people to say - "will this work for people **like me**".

And we also need to think about the data upon which our systems are built. There are fewer images and photographs of people of colour in the datasets on which facial recognition datasets are trained. Again, there is less _representation_ from women and communities of colour in these datasets.

SLIDE: Koenecke

And we see this also in speech recognition technology that doesn't recognise the speech of Black people as well as white people. This is the work of Alison Koenecke and her colleagues at Stanford, who investigated cloud automatic speech recognition algorithms, showing that the error rate in speech recognition - a measure of how well a model recognises what someone is saying - is nearly double for Black speakers compared to white speakers.

And when you think about where the data that is used to train these models comes from - mobile phones, voice assistants - generally expensive pieces of technology - then we start to see how **communities** who can afford technology, communities who use that technology - shape how that technology is built for _everyone_ - even when not _everyone_ is part of that community.

But wait! There's more!

SLIDE: Shoshana Zuboff - Surveillance capitalism

Big data has become big business, and many of us will be familiar with the work of Shoshana Zuboff and her concept of _Surveillance capitalism_ - in which reality - our everyday interactions with data platforms, is commodified, extracted, and sold to the highest bidder. And we see how technical platforms exploit that - encouraging us to interact, to post, to engage. We doomscroll while unseen bots harvest our every click, and use every like to better target advertising to us - because that's the way the technology system was designed, And by creating a technical system that values popularity and impressions - to drive more engagement, and collect more data about us, we feel inadequate if we don't get enough likes, or hearts, or karma or followers. Communities and technology systems shape each other.

SLIDE: ABC Data sharing with Facebook and Google

And if you thought that surveillance capitalism was just for giants like Facebook, and Cambridge Analytica, try logging on to iView - the streaming site of the Australian Broadcasting Corporation - our public, and taxpayer-funded broadcaster. By mandating that viewers must log in to iView, and then sharing or selling - _we're not quite sure which because the ABC won't tell us_ - sharing or selling that viewer data with Facebook and Google by default - until the viewer explicitly opts out, our very own Aunty is now a surveillance capitalist. Again, technology systems shape communities - if you or your kids, watch lots of Bluey, will you only ever be recommended similar content, diminishing the agency you have to choose what you consume?

SLIDE: Ring light that listens to neighbours

Speaking of privacy and surveillance capitalism, we also have doorbells that infringe the privacy of neighbours by listening and watching constantly - or at least when `us-east-1` is up - with their surveillance covering an area greater than just that belonging to the owner of the device. And we've frequently seen requests from law enforcement to have access to this data - so data, surveillance, used by an individual or household, being used to police the community in which that household is situated. That is, the technical system's reach is increased beyond the individual purchaser, _to_ the broader community.

And here, in this article on Gizmodo, we see how at least one of those neighbours is reacting - responding to this technical system - by having it ruled illegal. Technology systems shape communities and community reaction.

SLIDE: Robodebt

Speaking of things that have been ruled illegal, we have governments who **tried** to match income and social benefit datasets - poorly - and **unlawfully** - issuing debt notices to people who could least afford to pay. And I think that hints at the values of the government that created that system.

On the flipside, we also have a community which fought, and campaigned, and advocated and launched legal action and eventually got #robodebt overturned - people like Asher Wolf, and Lyndsey Jackson - who I think is speaking tomorrow, and several others. Communities do have agency to shape technical systems.

[pause]

There are also incredible examples of technical systems imbued with exemplary, community-focused values.

SLIDE: Find a RAT

I suspect many of us have used Matt Hayward's Find a Rat site in recent days. It's not perfect - crowdsourced data never is - but it's leveraged the power of the community, to provide a much-needed scarce resource, for all of those who aren't mates with the CEO of Chemist warehouse.

SLIDE: Chris Fryer and Jon Oxer's work with wheelchairs

And many of us are familiar with the work of Chris Fryer and Jon Oxer in creating accessibly-controlled wheelchairs that aim to give more freedom and independence to wheelchair users. Communities, and their values, help shape technical systems.

SLIDE: Better systems better communities

So, if we take the view that communities - social systems - influence how technical systems are designed, developed, directed and deployed, and in turn, technical systems help shape communities, then it's not too far of a leap for me to argue that thinking about communities as systems is vitally important. If we shape communities for the better, we might just shape technical systems for the better, and in turn, build better communities - and so on - in a positive feedback loop.

So today, I'm going to outline some principles from systems thinking, and apply these principles to open source communities. What we're going to uncover is not necessarily novel, or ground-breaking, but my intent here is to present it through an unexpected lens - that of connected, complicated, co-evolving systems. And through this framing, I want to encourage us all to reflect on the suggestion that every commit, every design decision, every choice - is part of shaping and reshaping **both** communities and technical systems - and that we, as individuals, have some agency, and power, to determine what that shape might be.

## Creating communities

What can systems thinking teach us about creating communities?

### Purposeful systems - complex adaptive systems and change

SLIDE - Emery and Ackhoff _On purposeful systems_

And to start with I'm going to explore the work of these folks - Russell L. Ackhoff and Fred Emery. Fred Emery was an Australian psychologist, and for any psychology people watching, his work was particularly influential in the area of organisational development. And Russell Ackhoff was world-renowned for his expertise in management science and operations research. In 1976 Emery and Ackhoff  authored this book - _On purposeful systems_. In it, they explain human behaviour as a system of _purposeful events_, and their intent in outlining this view, was to help us understand how to build not just better social systems, but how understanding social systems could help us build better social systems that had _machines_ in them - technical and cyber-physical systems.

In this book, Emery and Ackhoff cover many different types of systems, but a key concept, a key takeaway from this book is that many systems are _purposeful or _goal-seeking_ systems. That is, the system is structured around a particular objective. The system might have little agency about how it achieves this goal - such as say a flower whose goal is to be pollinated by a bee - or alternatively, the actors within a system might have a lot of choice, a lot of _agency_, about how they achieve that goal, that objective. For example, in a game of chess, the goal of the system is to move such a way that your opponent is forced into a position of checkmate - and there are literally millions of ways in which that goal can be achieved.

And the implications here for communities - people systems - are clear.

SLIDE: Communities are purposive (goal-seeking) systems

Communities have purposes, they have objectives and goals. A sporting community exists to participate and further the adoption of a particular sport. An academic community exists to further the body of knowledge around a particular topic.

The Linux Australia community - OHAI! - has the purpose, the objective, of fostering open source software, open hardware, open data, open content and open culture throughout Australia and the broader region. There are many ways in which that _could_ be achieved, but typically the _choice_ that the community has made has been to achieve this through Linux User Groups, and by all meeting face to face once a year, and wearing the t-shirt to prove it ;-)

Values are also important here - because the behaviour used to achieve goals, is an expression of the values of the community and the people in it. For example, the Linux Conf AU community _could_ choose to write manifestos and flame various mailing lists, _or_ choose to partner with other organisations -  other systems - to achieve shared goals.

SLIDE: Takeaways

So, in _creating communities_, we need to be very clear about the goals that the community should seek, and importantly, the **values** and the **choices** that will be made in pursuit of those goals. We have choice, and agency about **how** and **how not** we pursue our goals.

### Boundaries - who is in and out of a system

SLIDE: Boundaries

Another concept from systems thinking that is useful when we're creating communities is that of **boundaries** - that is, where does a system begin and end? What elements are considered inside or outside of a system? Where is that line drawn? And what might need to happen for the boundary to be permeated, to be crossed? That is, how easy is it for new elements to enter or to leave the system?

SLIDE: Midgley

One of the key thinkers around boundaries is Gerald Midgley, who's written several books on systems and intervening in systems, but I've highlighted one of his most famous books here - systemic intervention. In this book, Midgley makes the case for a technique he calls _boundary critique_. I won't go into the details here - but in essence he argues that we need to critically evaluate where the boundaries of systems are, and where different interpretations of boundaries might conflict.

There are several questions that he recommends we ask of systems to identify their boundaries - such as who are the decision makers in a system, and who is affected by a system? That is, where does _power_ lie within a system, and what mechanisms are there for people within a system to express their choices and agency?

And the key point I want to make here is that boundaries and barriers around a community may not be what we think they are. For example, we have Newcomers session for linux.conf.au - that provides an introduction on what to expect, the lingo, the lay of the land. It helps to make newcomers feel welcome. LCA and PyConAU both have equity and diversity programs to help with the cost of attendance, again, reducing barriers to participation. Standards and norms of behaviour - such as the Code of Conduct - exist and are explained, and, generally upheld, helping to reduce concerns people may have about attending.

But consider this example. Imagine that you want to attend a watch party for an awesome conference, and that the watch party is on a university campus. Imagine that you use a wheelchair. And that, thanks to ride-sharing companies establishing in your city, there is one wheelchair accessible taxi available for the whole of your city. Thanks, technical systems! You persist. You choose - use agency - to book the taxi in advance, and they surprisingly show up on time. But when they take you to the university campus, they can't actually drop you off close to the building, because the University has tried to discourage parking near buildings, so they drop you off about 800m from where you need to be, on a 30 plus degree day. Thank goodness the watch party's on the ground floor, and there are accessible toilets in the building.

SLIDE: Boundaries aren't always where we think they are

My point is this - sometimes we don't know what the barriers to entering, and fully participating in our community are. That is, there is boundary conflict because of the variety of needs in our community. So, to build better communities, we need to get better at identifying where those hidden boundaries lie.

## Curating communities

So we've explored how systems thinking principles like purposeful systems, and agency and choice, and boundaries can be useful for _creating_ communities. But how might systems thinking tools help us _curate_, and _care_ for an existing community?

### Stocks and flows

SLIDE: Meadows Systems Thinking

And here I want to draw on the work of Donella Meadows, a very famous systems thinker. This is an excellent book - _Thinking in Systems_, and it outlines many different ways to intervene, and to make change in systems. And I want to focus on one particular concept that Donella Meadows uses - which she refers to as _stocks and flows_.

SLIDE: Stocks and flows

We're all familiar with the concept of stocks and flows - think of say, money in and money out of your bank account each month. Money in this case is a stock - and where it comes from, and where it goes - is considered a flow. And you might have stores of this stock - such as savings. And thinking about finances in communities, and keeping communities financially viable is important, but there are many _other_ types of stocks and flows in communities.

Consider for example _volunteer labour_. This is a finite resource - a stock - and it can flow in different directions. Flows enter the system when volunteers feel energised, and committed, and have free time to donate. And that stock of volunteer labour can be consumed in many ways - on productive tasks, on achieving the goals and objectives of the community, of the system. Alternatively, they can be squandered, and misdirected - in dealing with unnecessary conflict and burning out the volunteer - consuming the stock of passion and commitment and time.

SLIDE: Stocks and flows principles

So, to build stronger communities, we need to understand their stocks - their resources, and where they flow in, out, and are consumed in the community.

### Cardinality and Connection

SLIDE: Cardinality and connection

Another systems thinking tool that can help us curate communities is that of _cardinality_ or _connection_. Those of you from a networking or database background will recognise this concept straight away. Cardinality refers to the strength, or the bonds of connections between elements in a system. In a database context, it refers to how entities are related. In a network system, it refers to how many paths, or edges there are between nodes in a network. And it can be a measure of how tightly a system is connected - and how resilience it is to nodes being removed.

The parallels with communities are obvious - if we think about cardinality and connection, we can think about how closely our community is bonded. For example, what would a map of Linux Australia members look like?

GO TO: https://kathyreid.com.au/la-membership-map/

Well, it just so happens that I prepared this map earlier, and it shows some interesting patterns. To be clear, this data is at the postcode level, so no actual addresses are used. And it shows, as expected, clusters of members in urban locations - Melbourne, Sydney, Brisbane, and regional cities where there have been LCA events before - Geelong, Ballarat, the Gold Coast. But we also see clusters here - in Albury Wodonga, in Mount Gambier, and northern Tasmania -of folks who may not have a local LUG, or ways of getting to local meetups. And folks for whom it might be harder to make and maintain connections.

SLIDE: Cardinality principles

And so the lessons here are again clear - understand the connections in your community, and what you might be able to do to strengthen them and bring people closer together.

### Requisite variety

SLIDE: Requisite variety

One last tool that I'm going to mention for helping to curate communities is that of _requisite variety_. Remember how we met Russell Ackhoff back in the slide about purposeful systems, and how systems have goals, and how we have agency and choice about how we pursue those goals?

Right, well Ackhoff took that concept a step further, and thought about how systems use choice and agency to choose how to reach goals. And he thought about how these systems _adapted_ to challenges to those goals. And one of the things he found about systems, was that the more _variety_ the systems had - the greater the range of values and dimensions that the elements in a system took - the more _resilient_ the system was to shocks, and to challenges.

SLIDE: Variety principles

And again, the implications for communities are clear. The greater the variety of people, the greater the variety of skills they bring to bear, the greater the range of viewpoints and values, the greater the range of resources, the better positioned the community will be to withstand shocks and unexpected occurrences.

And a key example of this, that many in the room will be familiar with, is from PyCon in the US back in 2020. PyCon was scheduled for just after the COVID-19 pandemic started, and had to cancel. That single event - much like LCA and PyconAU for Linux Australia - was the key source of revenue for the Python Software Foundation, and they were staring down a loss of over $USD 1 million. Luckily, donations flowed in to ameliorate the size of the loss, but it's a good lesson - both for the PSF and for Linux Australia - about the need for _requisite variety_ in revenue.

## Concluding communities

So, we've looked at systems thinking concepts for _creating_ and for _curating_ communities, but how can systems thinking help us in _concluding_ communities?

### Entropy

SLIDE: Entropy

Although _requisite variety_ gives us a tool for thinking about how a system can respond to unexpected shocks, it's less useful for helping us to combat a characteristic of many systems - that of _entropy_. The concept of entropy has specific meaning in fields such as physics, and thermodynamics, but here I'm taking the very broad, general definition of _entropy_ - to mean the general deterioration and decline of a system.

Over time, systems have a tendency to move toward chaos, and disorder, until they no longer exist. Communities - because they are systems - are similar. They will always need to deal with the constant force of entropy. And when there are large stocks - remember stocks and flows - of resources like volunteer time, and clear purpose and objectives, and clear ideas about how to achieve those objectives - those forces will tend to outweigh the force of entropy. But over time, as those resources are consumed and not replenished - for example if your volunteers are burnt out, or you don't have the financial revenue to continue operating, then the community will be dealing with entropy.

SLIDE: Entropy principles  

And there will come a time when the community needs to make a difficult call - how much entropy, how much disorder, how much inactivity is needed, before the community can be considered defunct? Or can the entropy be recognised, and a decision made to gently end the community in a managed, and careful way. So, building better communities also means ending communities thoughtfully, and carefully.

SLIDE: Rebirth

But I don't want to end my talk on that note. Yes, systems decline and decay over time and sometimes the right decision is to gracefully end the community. But remember how systems interact with each other, influence each other? The decline of one community can often sow the seeds of another, in a pattern of regeneration. Without the Australian Unix Users Group, there would probably be no LCA, and no Linux Australia. Without LUGs like LUV and SLUG and TasLuG and Humbug, there would be no LCA. And we can choose, deliberately, what we bring from one community to another.

## Conclusion

So, in conclusion, my talk today started out with a deceptively simple premise. _Communities are systems_. And as I've unpacked this concept, we've seen how communities and technical systems shape each other - for better and worse. And from this, I've argued that if we build better communities, we will shape better technical systems. And drawing from many different authors, I've highlighted _several systems thinking_ concepts - such as purpose and choice, boundaries, cardinality and requisite variety - that provide tools for thinking about, and improving communities.

And the astute viewer will recognise, that along the way, I've created a reading list by stealth, because I sincerely hope to have piqued your intellectual interest.

So on that note, I would like to leave you with one final thought to ponder.

Communities shape technical systems, and technical systems shape communities. Every contribution we make, every code commit, every design decision, helps influence the communities we're part of, and, in turn the technical systems those communities build. So, let's use our choice, our agency, and all our available systems thinking tools - to actively, deliberately, shape our systems - because otherwise, those systems will shape _us_.

Thank you very much.
