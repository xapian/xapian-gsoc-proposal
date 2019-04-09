.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
.. 
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See our GSoC Project Ideas List for some suggested project ideas:
.. https://trac.xapian.org/wiki/GSoCProjectIdeas
..
.. You are also most welcome to propose a project based on your own ideas.
.. 
.. From experience the best proposals are ones that are discussed with us and
.. improved in response to feedback.  You can share draft applications with
.. us by forking the git repository containing this file, filling in where
.. it says "FILLME", committing your changes and pushing them to your fork,
.. then opening a pull request to request us to review your draft proposal.
.. You can do this even before applications officially open.
.. 
.. IMPORTANT: Your application is only valid is you upload a PDF of your
.. proposal to the GSoC website at https://summerofcode.withgoogle.com/ - you
.. can generate a PDF of this proposal using "make pdf".  You can update the
.. PDF proposal right up to the deadline by just uploading a new file, so don't
.. leave it until the last minute to upload a version.  The deadline is
.. strictly enforced by Google, with no exceptions no matter how creative your
.. excuse.
.. 
.. If there is additional information which we haven't explicitly asked for
.. which you think is relevant, feel free to include it. For instance, since
.. work on Xapian often draws on academic research, it's important to cite
.. suitable references both to support any position you take (such as
.. 'algorithm X is considered to perform better than algorithm Y') and to show
.. which ideas underpin your project, and how you've had to develop them
.. further to make them practical for Xapian.
.. 
.. You're welcome to include diagrams or other images if you think they're
.. helpful - for how to do this see:
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html#images
.. 
.. Please take care to address all relevant questions - attention to detail
.. is important when working with computers!
.. 
.. If you have any questions, feel free to come and chat with us on IRC, or
.. send a mail to the mailing lists.  To answer a very common question, it's
.. the mentors who between them decide which proposals to accept - Google just
.. tell us HOW MANY we can accept (and they tell us that AFTER student
.. applications close).
.. 
.. Here are some useful resources if you want some tips on putting together a
.. good application:
.. 
.. "Writing a Proposal" from the GSoC Student Guide:
.. https://google.github.io/gsocguides/student/writing-a-proposal
.. 
.. "How to write a kick-ass proposal for Google Summer of Code":
.. https://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

====================================================
Reporting system for easier algorithmic development
====================================================

About You
=========

 * Name: Prithi Pal Singh

 * E-mail address: prithipal.singh285@gmail.com

 * IRC nickname(s): jugnu

 * Any personal websites, blogs, social media, etc: LinkedIn : www.linkedin.com/in/prithipal-285
 * github URL: github.com/PrithiPal

 * Biography:

Hello to you people reading this. I am Prithi, 5th BSc. Computer science undergrad @ Simon Fraser University, Burnaby, BC Canada. Talking about my academic experience, there are couple of courses that I enjoyed includes ones on Comparative Programming Languages (Go,Haskell,Clojure), NLP, Computer Vision, Compiler Design and also Machine Learning. On top of the school, I participated in two Co-ops with data-centric where in the first one I worked on financial data and developed Customer-attrition models. For my second Co-op, I added features such as support for GRPC server and Automated script for Kubernetes deployment into company's data-pipeline backend.

In school, I also hold onto two different research assistant positions. One is Bioinformatics based where I primarily wrote code for finding sequences in Proteins, producing statistics, and rough-pipeline for experimental/theoretical data comparisons. My second RA was based on Computational Linguistics where I focused on researching and implementing Evaluation metrics for LDA Topic-models based on Reddit data and wrote metric to quantify some real-time variables such as knowledge of user etc.  

Now Apart from school and work, I participated in competition to create a drawing robot where I designed and implemented an interactive Image-processing/segmentation application on MATLAB. To be honest, that was one of the biggest project which took months to develop and our team placed first for robot which drew a photograph given on spot. You can find our mention here : https://www.sfu.ca/computing/newsandevents/2017/inaugural-robotics-competition.html

On the non-technical note, I started volunteering starting the second year and carried on front-end roles such as advisor, peer-mentor and workshop facilitation. 

While at home, I pursue certain topics based on my interest. For instance, my current fascination is about the realm of investment where I am reading/read books on Mutualfunds, financial-due-diligence, economics etc. If you're interested, you can find my book bucket here : https://www.goodreads.com/user/show/55557115-prithipal-singh. In sports, I like racket sports especially  Badminton and squash more than anything but too bad I haven't been active in few weeks.

Background Information
----------------------

.. The answers to these questions help us understand you better, so that we can
.. help ensure you have an appropriately scoped project and match you up with a
.. suitable mentor or mentors.  So please be honest - it's OK if you don't have
.. much experience, but it's a problem if we aren't aware of that and propose
.. an overly ambitious project.

**Have you taken part in GSoC and/or GCI (https://codein.withgoogle.com/) and/or
similar programmes before?  If so, tell us about how it went, and any areas you
would have liked more help with.**

I have not participated in GSOC or any other equivalent platform. 

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I do not have prior experience with Xapian specifically. However I developed rough understanding about indexing data-set/websites and how they serve behind search-engines. For instance, I created web-scraping programs while back using Python open source Scrapy framework and selenium to automate download-data from specific websites and store locally. Scrapy in particular have robust data-pipeline where user can fix things and prevent from re-inventing stuff. 

For understanding the Actual algorithms, I went through the letor and Yahoo research paper as suggested in the project's resources. This on top of "Core-concepts" of Xapian docs, I established a thorough understanding of the indexers, ranking algorithms ,scoring function. 

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have not contributed directly into an open-source codebase but I have utilised the open-source libraries/programs(python, etc) to achieve tasks at hand.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

**Courses** : 
- NLP (project on context sensitive lexicons for sentiment analysis, assignments such as weighted-context-free-grammer, beam-search for mul, HMM or vitebri, text-chunking model)

**Experience** : 
- Research Assistant project on Evaluation methods for Topic Models (LDA-type). Read some papers on evaluation metrics, implemented them and also designed some metrics to quantify real-world variables from collected Reddit sub-thread data such as level of expertise of user towards the topic-being discussed.
- Research Assistant project on sequence detection, profiling, producing statistics(graphs etc..) using Python/C++/Awk. 

**What development platforms, tools and methods do you prefer to use?**

- **Language** : Python (Famous library included), C++/C for custom code inside xapian-core/xapian-letor for ranking,scoring schemes etc.
- **Language Platform** : Atom,nano,jupyter
- **Automation** : Awk, Shell scripts, selenium (If webUI is involved)
- **Testing environment** : Vagrant (manual testing platform), Docker (testing for front-ends, data-pipelines if needed[multiple containers with interaction in a network]), language specific tests (Unittests for python) and make tests in C++ codes.
- **Testing strategy** : test individual functions, test collective interaction packages
- **Documentation** : Latex, Jupiter-notebooks

Other useful backends I know : Flask, Django, RabbitMQ, Celery, Scrapy, networkx.  

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

At one of my internships, I worked on a data-pipeline for versioning of data-involved. The code-base involved lots of moving parts so the testing was dominated by Docker with multiple containers interacting. My strategy was to identify places with code change, change/test one file(if independent), test with few data examples and then scale for full testing on Docker (replicate the actual workflow including data-entering, Going through stages for processing, BSON Storage, Sync with Kubernetes). 

I used Flask, Celery, RabbitMQ, Docker, OpenStack, Kubernetes, Redis. 


**What timezone will you be in during the coding period?**

West Coast Canada

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes. I have one course enrolled but can drop if selected for full-time attention towards GSOC.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

M-F 10-6 including some weekends if I have no prior engagements. 

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

No. As I am working full-time these days, I decided to invest my time in One proposal which is with you xapian. No other Backup.

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.


Your Project
============

Motivations
-----------


**Why have you chosen this particular project?**

Initially I went through all organisations and their briefly projects. Then I narrowed my search down to five which aligns my interests and expertise. Further I narrowed down to Xapian(Because I want to work on both analytical prospect (Algorithms, Metrics etc.) and Engineering prospect (Code-base, testing, writing wrappers)).


**Who will benefit from your project and in what ways?**

I expect to benefit people who are first joining the Xapian through improving front-end documentation and User-friendly API. Secondly, it would be people working on improving algorithms in weighting-schemes or ranking by implementing a reporting-system for easier model-testing and evaluation(to focus on actual algorithms instead of logistical issues) 


Project Details
---------------

**Describe any existing work and concepts on which your project is based.**

.. Please go into plenty of detail in this section.

I can break down my project into two big components : Reporting system for algorithm development and testing and support for TracApplicationSoftwarePlugin. 

**Reporting system**  :
This is the point 5 in ProjectSummary (https://trac.xapian.org/wiki/GSoCProjectIdeas/LearningtoRankStabilisation) "Create an evaluation and performance reporting system ... ".

If people want to compare and evaluate models (unsupervised weighting-schemes or supervised learning-to-rank or LETOR) by changing datasets, model definition, feature definition or evaluation metric, there should be an easy way for this. some actionable steps to achieve this would be :   
		- Types of algorithm : There are currently different families of algorithms inside Xapian. Namely they can be classified as Weight-scheme , Letor , cluster, spelling-algorithms, stemming-algorithms and many other (people who developed and not merged in master).
		- Benchmark type : For starter this can start from time taken. Now theoretically each family should be benchmarked separately because of different in their types (supervised vs unsupervised or types of dataset accepted). Another important benchmark will be actual evaluation (xapian-evaluate is a good place to look into).
		- Develop a python-api (to execute a CLI command) : This is the way to get a single ClI command to take dataset, choose algorithm, set algorithm params (specific to algorithm), train and evaluate (choose evaluation type). Again this will be different for weight-schemes and LETOR based.
		- Currenly xapian-evaluate(https://github.com/xapian/xapian-evaluation), only supports the weighting-scheme algorithm. So the API is already developed in weight-scheme case so I can directly make visualisations. However, I have to see a central Api for evaluations for other families of algorithms.  
		- There is currently some work done for evaluation of Letor family of algorithms here : https://trac.xapian.org/wiki/GSoC2011/LTR/Notes#IREvaluationofLetorrankingscheme. This could be a good start.
		- Basic Reporting front-end : Jupyter notebook is a good starting point where the CLI in previous point will gather all numbers in one file (score for all algorithms and params used), and visualise.
		- Probably a small web-server which broadcasts the visualisations (consult with mentors which visualisations are good). Actually the visualisation should be for benchmarks. For instance bar-graph for evaluation-scores, or scatter-plots for k-means (cluster), or heat maps for coorelation/evaluation-scores. There are many possibilities here. 
	

**Documentation**
New users who are getting started with Xapian development in Letor. This may include project setup(documentation for newbies), simple cli/front-end tool to actually see stuff happening. This is important in order to develop curiosity for new developers looking into Xapian as a whole. As actionable steps, this includes building good tutorial documentation for Omega , Xapian and more use-cases that may even combine all three : Xapian-Core, omega and letor.

This component can be thought of as solution to the first three points in ProjectSummary (https://trac.xapian.org/wiki/GSoCProjectIdeas/LearningtoRankStabilisation) "Create practical code examples that use the core features and API, fleshing out the ​user guide"

	- New users who are getting started with Xapian development in Letor. This may include project setup(documentation for newbies), simple cli/front-end tool to actually see stuff happening. This is important in order to develop curiosity for new developers looking into Xapian as a whole. As actionable steps, this includes building good tutorial documentation for Omega , Xapian and more use-cases that may even combine all three : Xapian-Core, omega and letor.
	- Add the documentation of visualisations on comparing algorithms from ReportingSystem milestone.

	- Testing : 
		- Higher-level API (python) : Add the unit tests for all the commands done in the xapian docs 	
		- Lower-level API (C++) : Add the test for any new code involved in the xapian/xapian-core/tests/api_[test_name].cc


Small GSOC bite size/ tickets issues to start with (Before GSOC results.) : 
	- "Rework Omega templates to use more modern web techniques"
	- "get PDF building" : 
	- " https://trac.xapian.org/ticket/778"  : sphinx documentation
	

This component can be thought of as solution to the first three points in ProjectSummary (https://trac.xapian.org/wiki/GSoCProjectIdeas/LearningtoRankStabilisation) "Create practical code examples that use the core features and API, fleshing out the ​user guide"

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

- In the reporting system, the important components are understanding algorithm types, evaluation types, quick way of changing parameters (dataset, algorithm-specific option) and visuals for comparison. 

- I have went through BM25 algorithm for weight-scheme, Yahoo and LETOR paper for training algorithms. 
- I have experience with analytical algorithmic testing from my Research assistant and Co-op experience. Usually using Jupyter for visualisations and then shifting to third-party plugins which specialises in visualisations.

- I broke down the project like this ; 

	For family-algorithm in [weight-scheme, letor, spell-check, stemming ..] : 
		For different algorithm parameters : 
			
			Use existing API or make one to quickly change params, dataset, feature-list etc..
			score or rank or evaluate 

		Make visuals (different for family of algorithms) for rank/evaluation scores


**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

- Earlier I thought of pursuing more analytical project (such as  Click-stream model, new weighting-schemes), however I decided in favour of documentation because I felt it took a considerable amount of time setting things up. I want to make other people be able to build, configure things in less time so that they can focus on functional stuff. So I put Documentation as first project component.

- With the reporting system, because there are lot of breakable steps (obtain results (relevance judgment), make visualisations, scale to other ranking/scoring functions, data-set), I am sure this is more agile and not ending up in situation with "not know what to do". 

**Please note any uncertainties or aspects which depend on further research or
investigation.**

- I would like to do more research on TracAdvanceSearchPlugin as I gave some buffer days in my Project timeline below.
- Little more advanced data-profiling tools(for benchmarking visualization) even though I know how to make a basic one with a web-server.

**How useful will your results be when not everything works out exactly as
planned?**

I attempt to break the project into ultra-small breakable steps with appropriate documentation to ensure to leave a trail for future developers. Also I make sure all my changes will be tested in and out.

Project Timeline
----------------

.. We want you to think about the order you will work on your project, and
.. how long you think each part will take.  The parts should be AT MOST a
.. week long, or else you won't be able to realistically judge how long
.. they might take.  Even a week is too long really.  Try to break larger
.. tasks down into sub-tasks.
.. 
.. The timeline helps both you and us to know what you should do next, and how
.. on track you are.  Your plan certainly isn't set in stone - as you work on
.. your project, it may become clear that it is better to work on aspects in a
.. different order, or you may some things take longer than expected, and the
.. scope of the project may need to be adjusted.  If you think that's the
.. case during the project, it's better to talk to us about it sooner rather
.. than later.
.. 
.. You should strive to break your project down into a series of stages each of
.. which is in turn divided into the implementation, testing, and documenting of
.. a part of your project. What we're ideally looking for is for each stage to
.. be completed and merged in turn, so that it can be included in a future
.. release of Xapian. Even if you don't manage to achieve everything you
.. planned to, the stages you do complete are more likely to be useful if
.. you've structured your project that way. It also allows us to reliably
.. determine your progress, and should be more satisfying for you - you'll be
.. able to see that you've achieved something useful much sooner!
.. 
.. Look at the dates in the timeline:
.. https://summerofcode.withgoogle.com/how-it-works/
.. 
.. There are about 3 weeks of "community bonding" after accepted students are
.. announced.  During this time you should aim to complete any further research
.. or other issues which need to be done before you can start coding, and to
.. continue to get familiar with the code you'll be working on.  Your mentors
.. are there to help you with this.  We realise that many students have classes
.. and/or exams in this time, so we certainly aren't expecting full time work
.. on your project, but you should aim to complete preliminary work such that
.. you can actually start coding at the start of the coding period.
.. 
.. The coding period is broken into three blocks of about 4 weeks each, with
.. an evaluation after each block.  The evaluations are to help keep you on
.. track, and consist of brief evaluation forms sent to GSoC by both the
.. student and the mentor, and a chance to explicitly review how your project
.. is going with Xapian mentors.
.. 
.. If you will have other commitments during the project time (for example,
.. any university classes or exams, vacations, etc), make sure you include them
.. in your project timeline.

**Month 1 Theme** : *DOCUMENTATION AND RESEARCH*

**Week 1** 
	- Read and understand code-base further. 
	- Identify the families of algorithms inside the code. Currently known to me are weighting-scheme, letor, spelling-checking, cluster, stemming

**Week 2** 
	- solve "Rework Omega templates to use more modern web techniques"
 	- Add Omega documentation (in Xapian docs) for indexing, and how to obtain a front-end html(omindex, omega "query" [arguments]) with cgi.

**Week 3** 
	- Identify areas that requires change user-end python APIs, consult with mentors about this.
	- Add more coding examples in "Core Concepts" and "Installation" with wrapper user-end (discussed in previous proposals) and install setups.

**Week 4**
	- Buffer week to complete the above. 

**Deliverable** : 
	- Some documentation changes on Xapian Docs. New user-end python API created 

**Month 2 Theme**  : **WEIGHT-SCHEME REPORTING**

**Week 1** 
	- Read and understand algorithm code specifically xapian-core/weights/*,  xapian-core/tests/* and xapian-core/cluster/* , that defines and uses weight-schemes algorithms.
	- Implement the xapian-evaluate(Bash CLI) with different values of data-set, and algorithm-parameters. 

**Week 2** 
 	- Identify the requirements of a good reporting system(metrics, benchmarks, which algorithms etc..) as consulted by the developers on IRC and mentors
	- Ensure that evaluation works for weight-schemes on CLI (xapian-evaluate for this).

**Week 3** 
	- Continue implementing xapian-letor/tests for different algorithms. 
	- Start working on the visualisations for comparing algorithms for Weighting-schemes.
	- Develop a basic prototype of the charts and graph using a Jupyter notebook. This is good to see what types of visualisations suits the numbers produced

**Week 4**
	- Read relevant papers about the evaluation for weighting-schemes and decide which metrics to choose.
 	- Implement an automated script (probably python or shell) which produces charts and graphs.

**Deliverable** : reporting system for weighting-scheme completed with appropriate documentation. 

**Month 3 Theme**  : **LETOR REPORTING**

**Week 1** 
	- Read and go through xapian-letor/tests and ranker/scorer where actual examples are given of Marching-Learning Pipeline(data-grabbing,training,storing Qrel..,scoring).
	- Good place to begin is xapian-letor/tests/api_letor.cc. They make call to letor algorithms defined in xapian-letor/ranker|scorer. 
**Week 2** 
	- Study the comparison and benchmarking strategies between different ranking algs include in the front-end(xapian-evaluate a good place to start)
	- Test the implementation with INEX and see the number matching to "IR Evaluation of Letor Ranking Scheme" in https://trac.xapian.org/wiki/GSoC2011/LTR/Notes#IREvaluationofLetorrankingscheme. 

**Week 3** 
	- polishing the project (docs or tests). Work on extending this to stemming algorithms or spell-check algorithms and reporting system for them.

**Week 4**
	- polishing the project (docs or tests)


**Deliverable** : reporting system for letor completed with appropriate documentation. 


Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

I regularly check with the @olly on IRC for any problems with building as well as some project ideas with their feasibility. I used the alias @jugnu. 

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1399

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

I have cited the code-base references (folders, git-repo) above as they were relevant to the context. However still for my background research I went through all documentation on Xapian docs (from xapian-docsprint), Omega (Overview and few other ones), Letor(the ML workflow), Yahoo and Letor research paper(to understand ML theory including dataset-creation , feature-selection)

Still, 

- weight-scheme algorithm definition : xapian-core/weight
- weight-scheme algorithm calling API : xapian-core/bin/*
- weight-scheme algorithm workflow example : xapian-core/tests/api_backend.cc and others.
- weight-scheme evaluation : xapian-evalution

- letor algorithm definition : xapian-letor/scorer, xapian-letor/feature
- letor algorithm calling API : xapian-letor/bin/xapian-train and xapian-letor/bin/xapian-rank.cc
- letor algorithm workflow example : xapian-letor/tests/api_letor.cc 
- letor algorithm evaluation : xapian-letor/ranker. 
- letor docs : xapian-letor/docs

- Omega templates : xapian-applications/omega/templates..
- Stemming data : xapian-data/stemming




.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.

