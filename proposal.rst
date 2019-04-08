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

======================================
FILLME WITH THE TITLE OF YOUR PROPOSAL
======================================

About You
=========

 * Name: Prithi Pal Singh

 * E-mail address: prithipal.singh285@gmail.com

 * IRC nickname(s): jugnu

 * Any personal websites, blogs, social media, etc: LinkedIn : www.linkedin.com/in/prithipal-285
 * github URL: github.com/PrithiPal

 * Biography:

Hello to you people reading this. I am Prithi, 5th BSc. Computer science undergrad @ Simon Fraser University, Burnaby, BC Canada. Talking about my academic experience, there are couple of courses that I enjoyed includes ones on Comparative Programming Languages (Go,Haskell,Clojure), NLP, Computer Vision, Compiler Design and why not Machine learning. On top of the school, I participated in two Co-ops with data-centric roles encompassing analytics and back-end building. In school, I also hold onto two different research assistant positions in Bioinformatics and Computational Linguistics for Reddit Sub-thread where I proposed and implemented solutions as per the requirements. I guess My linked will summarize stuff better. 

Now Apart from school and work, I participated in competition to create a drawing robot where I designed and implemented an interactive Image-processing/segmentation application on MATLAB. To be honest, that was one of the biggest project I took which tooks months to make. On the non-technical note, I started volunteering starting the second year and carried on front-end roles such as advisor, peer-mentor and workshop facilitation.  

Okay, So if we go at my home(because my home is anti-work, anti-school place) and a total mental vacation place, I pursue certain topics based on my interest in those days. For instance, my current fascination is about the realm of investment where I am reading/read books on Mutualfunds, financial-due-diligence, economics etc. If you're interested, you can find my book bucket here : https://www.goodreads.com/user/show/55557115-prithipal-singh. In sports, I like racket sports especially  Badminton and squash more than anything but too bad I haven't been active in few weeks.

FILLME

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

I do not have prior experience with Xapian specifically. However I have rough understanding about indexing data-set/websites and how they serve behind search-engines. For instance, I created web-scraping programs while back using Python open source Scrapy framework and selenium to automate download-data from specific websites and store locally. Scrapy in particular have robust data-pipeline where user can fix things and prevent from re-inventing stuff. 

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have not contributed directly into a open-source codebase but I have utilised the open-source libraries/programs(python,matlab etc) to achieve tasks at hand.


**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

COURSES : 

- NLP (project on context sensitive lexicons for sentiment analysis, assignments such as weighted-context-free-grammer, beam-search for scoring, HMM or vitebri, text-chunking model)
- Research Assistant project on Evaluation methods for Topic Models (LDA-type). Read some papers on evaluation metrics, implemented them and also designed some metrics to quantify real-world variables from collected Reddit sub-thread data such as level of expertise of user towards the topic-being discussed.

**What development platforms, tools and methods do you prefer to use?**

Language : Python (Famous library included), C++/C for custom code inside xapian-core/xapian-letor for ranking,scoring schemes etc.
Language Platform : Atom,nano,jupyter
Automation : Awk, Shell scripts, selenium (If webUI is involved)
Testing environment : Vagrant (manual testing platform), Docker (testing for front-ends, data-pipelines if needed[multiple containers with interaction in a network]), Language specific tests (Unittests for python) and make tests in C++ codes.
Testing strategy : test individual functions, test collective interaction packages
Documentation : Latex, Jupiter-notebooks
Some Useful Backends I know : Flask, Django, RabbitMQ, Celery, Scrapy, networkx.  

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

At one of my internships, I worked on a data-pipeline for versioning of data-involved. The code-base involved lots of moving parts so the testing was dominated by Docker with multiple containers interacting. My strategy was to identify places with code change, change/test one file(if independent), test with few data examples and then scale for full testing on Docker (replicate the actual workflow including data-entering, Going through stages for processing, Storage, Sync with Kubernetes). 


**What timezone will you be in during the coding period?**

West Coast Canada

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes. I have one course enrolled but can drop if selected for full-time attention towards GSOC.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

M-F 10-6 including some weekends if I have no prior engagements. 

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

No. As I am working full-time these days, I decided to invest my time in One proposal which is with you xapian.

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No Backup.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**



Initially I went through all organisations and their briefly projects. Then I narrowed my search down to five which aligns my interests and expertise. Further I narrowed down to Xapian(Because I want to work on both analyitcal prospect (Algorithms, Metrics etc.) and Engineering prospect (Code-base, testing, writing wrappers)).

Thus, I am interested in Issues/sub-tasks involved in two Xapian's GSOC project : Weighting Schemes 

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.






Project Details
---------------

.. Please go into plenty of detail in this section.

[NEW-SETUP] : As I stated above, this component of my project involves developing tools like front-end for Omega (Subtask on Xapian for Support). In addition to this, another subtask which involves additional support for Xapian as a Backend on TracAdvancedSearchPlugin which currently supports only ApacheSlur. In addition to this, 

Although I have bit fluid objectives now, however I have clear-vision of my end-goals : 

- [DOCUMENTATION STEP] : New users who are getting started with Xapian development in Letor. This may include project setup(documentation for newbies), simple cli/front-end tool to actually see stuff happening. This is important in order to develop curiosity for new developers looking into Xapian as a whole. As actionable steps, this includes building good tutorial documentation for Omega , Xapian and more use-cases that may even combine all three : Xapian-Core, omega and letor. Some actionable steps include : 

	- [EQUIVALENT GSOC TASKNAME] : 
		- This component can be thought of as solution to the first three points in ProjectSummary (https://trac.xapian.org/wiki/GSoCProjectIdeas/LearningtoRankStabilisation) "Create practical code examples that use the core features and API, fleshing out the ​user guide" 
		- " Get PDF building " under Documentation and Examples.

	- [DOC]-medium : Update or add a new page regarding installing whole xapian package (https://getting-started-with-xapian.readthedocs.io/en/latest/overview.html#installation) especially for vagrant. Currently there is not enough code that demonstrate install procedure on main doc. I would also try to cover all edge-cases for different OS, path problems (python etc..). All The documentation code and corresponding tests can be stored in xapian-docsprint/api/python3. I also look forward to fixing VagrantFile to ensure that the setup can be done(I failed because of some problematic raring while downloading some packages). I hope to combine the information in xapian-letor/INSTALL, xapain-core/HACKING for this maybe.

	- [TESTING]-medium : 
		- Higher-level API (python) : Add the unit tests for all the commands done in the xapian docs 	
		- Lower-level API (C++) : Add the test for any new code involved in the xapian/xapian-core/tests/api_[test_name].cc
	
This component can be thought of as solution to the first three points in ProjectSummary (https://trac.xapian.org/wiki/GSoCProjectIdeas/LearningtoRankStabilisation) "Create practical code examples that use the core features and API, fleshing out the ​user guide"


- [REPORTING SYSTEM STEP] : If people want to compare and evaluate models (unsupervised weighting-schemes or supervised learning-to-rank or LETOR) by changing datasets, model definition, feature definition or evaluation metric, there should be an easy way for this. some actionable steps to achieve this would be :   

	
	- [INDEX FRONT-END]-large : Get Front-end setup for searching. This will include working on "Xapian backend for advanced trac search" GSOC sub-task. This will be a huge comparatively and will be 1/3 of my project or one full month including testing. Requires little more research. 

	- [INDEX FRONT-END]-small : Mini-version of front-end problem will include working on "Rework Omega templates to use more modern web techniques" and GSOC sub-task : "Improve Omega's testsuite" for some testing. This is just supporting omega with cgi supportive files. 

	- [BECHMARK SYSTEM]-medium : this is the point 5 in ProjectSummary (https://trac.xapian.org/wiki/GSoCProjectIdeas/LearningtoRankStabilisation) "Create an evaluation and performance reporting system ... ". This is rather a big project in itself. So some subtasks may involve : 
		- Work on the xapian-evaluate, improve on the local documentation and add the documentation to main Xapian doc.
		- Small Front end to illustrate numbers using charts and graphs. Store the results into files and import those files to make graph on them(jupyter notebook is a good starting point).
		- If the previous is done, incorporate a small web-server(like a docker) which shows the interactive illustrations. For instance something like this one : https://pyldavis.readthedocs.io/en/latest/readme.html
		- Cover all the code with the unit tests and component-testing. 

At this point of time, the first option is more time consuming w.r.t just setting Omega up with templates. In the
	

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**


[DOCUMENTATION STEP] : 
	- there are few chances that something will fail on massive scale. Actually the work can be divided into iteration such as "Practical Examples", "How to", "Core concepts". So for instance, I can develop and post user-friendly code for Practical examples, then how tos, then core-concepts. For the new user-friend API, 
	 
	- As of now, the project to support the front-end for Xapian is a big chunk of task. If however, something happens along the way, the "Rework Omega templates to use more modern web techniques" will ensure that we have some good front-end working. 

	- Also for the benchmarking system, I can begin with a small prototype of front-end in python(such as )


**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**



FILLME

**Please note any uncertainties or aspects which depend on further research or
investigation.**

FILLME

**How useful will your results be when not everything works out exactly as
planned?**

FILLME

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

MONTH 1  : 

BIG TASK NAME : DOCUMENTATION STEP

Week 1 
	- Read and understand code-base further. 
	- Create a new VagrantFile and make sure that it installs all the xapian dependencies. I have a doc where I have all commands which helped me with my Xapian setup.
	- Update the "Installation" page with vagrant walk through tutorial.

Week 2 
	- Re-work on "Practical Example" tutorial to make it more user-friendly. 
	- Add Omega documentation (in Xapian docs) for indexing, and how to obtain a front-end html(omindex, omega "query" [arguments])
	- Start working on GSOC task:  "Rework Omega templates to use more modern web techniques"

Week 3 
	- Continue working on Omega templates.
	- Identify areas that requires change user-end APIs, consult with mentors about this.
	- Continue working on the user-end APIs.

Week 4
	- Continue working on the user-end APIs.
	- Add tests to see consistency of new API(). 

MONTH 1 DELVERABLE : 
	[MINUMUM] : New "Practical Example" and "Installation" on Xapian Docs. Omega supporting templates (Subtask completed)	
	[SATISFACTORY] : Above + New-API prototype + API-testing. Such that API is fully covered with unittests and use-cases.
	

MONTH 2  : 

BIG TASK NAME : DOCUMENTATION STEP + REPORTING-SYSTEM
DELEVARABLE OR SUBMITTABLE : 

Week 1 
	- Buffer week if things are not completed from previous month otherwise continue. 

Week 2 
	- Identify the requirements of a good reporting system(metrics, benchmarks, which algorithms etc..) as consulted by the developers on IRC and mentors
	- Read and go through xapian-letor/tests and ranker/scorer where actual examples are given of Marching-Learning Pipeline(data-grabbing,training,storing Qrel..,scoring)

Week 3 
	- Develop a basic prototype of the charts and graph using a Jupyter notebook. This is good to see what types of visualisations suits the numbers produced
	- Study the comparison and benchmarking strategies between different ranking algs include in the front-end(xapian-evaluate a good place to start)
	- Test the implementation with INEX and see the number matching to "IR Evaluation of Letor Ranking Scheme" in https://trac.xapian.org/wiki/GSoC2011/LTR/Notes#IREvaluationofLetorrankingscheme. 

Week 4
	- Document the new Algorithm Benchmarking system on Xapian Docs
	- Explore the feasibility of "Xapian backend for advanced trac search" with TracAdvancedSearchPlugin
	- If due-diligence succeeds, work for next two weeks on it. 

MONTH 2 DELEVERABLE : 
	[MINIMUM] : basic front-end ready for visualizing benchmark numbers + tested the implementation of benchmark system on cli.
	[SATISFIABLE] : Above + some progress in TracAdvancedSearchPlugin

MONTH 3  : 

BIG TASK NAME : REPORTING-SYSTEM + FINISHING/CONCLUSION 

Week 1 
	- Buffer week if things are not completed from previous month otherwise continue. 
	- Xapian backend support in TracAdvancedSearchPlugin

Week 2 
	- Xapian backend support in TracAdvancedSearchPlugin
	- Start investigation make dist for letor, to ensure and get first release version.

Week 3 
	-  Buffer week if things are not completed from previous month otherwise continue.

Week 4
	-  Buffer week if things are not completed from previous month otherwise continue.
	

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

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
