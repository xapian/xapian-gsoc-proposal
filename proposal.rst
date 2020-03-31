.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introduction to reStructuredText see:
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
.. For academic research, it's helpful to include a URL if the paper is
.. freely available online (via an author's website or preprint server,
.. for instance). Not all Xapian contributors have free access to academic
.. publishers. You should still provide all the normal information used
.. when citing academic papers.
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
Evaluation Suite
======================================

About You
=========

 * Name: Alexander Slesarev

 * E-mail address: alexander.g.slesarev@gmail.com

 * IRC nickname(s): alexander_slesarev

 * Any personal websites, blogs, social media, etc: -

 * github URL: https://github.com/slesarev-hub

 * Biography:

I am a third course bachelor student at Saint-Petersburg State University. Involved into the `PosDB <https://dbdb.io/db/posdb>`_ project (not open source) as a coursework. Co-author of an `article <http://ceur-ws.org/Vol-2372/SEIM_2019_paper_52.pdf>`_ on DBMS architecture. 
Besides databases I am interested in Machine learning.

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

`Russian Association for Artificial Intelligence Summer School <http://school-raai.org/>`_ 2019 

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I have tried to enroll in Xapian project last year, but I found GSoC for several days before deadline.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

Only as a user.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I worked with Xapian test harness in `#758 <https://trac.xapian.org/ticket/758>`_, it allowed to get acquainted with Xapian architecture.

I had Information retrieval and Data science basic courses at University.

**What development platforms, tools and methods do you prefer to use?**

Ubuntu, VSCode

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

During my work with PosDB I got some experience with data storages and Unix api.

**What timezone will you be in during the coding period?**

.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.

Saint Petersburg, Russia is GMT/UTC + 3

**Will your Summer of Code project be the main focus of your time during the
program?**

.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.

Yes

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

.. A common mistake is to think you can work a huge number of hours per week
.. for the entire duration of Summer of Code. If you try, you run the risk of
.. making yourself exhausted or ill, which may mean you are unable to keep
.. working right the way through. It's important to take good care of
.. yourself. Make sure you leave adequate time for other commitments, as well
.. as for eating, exercising, sleeping and socialising. Summer of Code
.. doesn't have to take over your life; it's better to think of it as you
.. would a job, leaving time to do other things.
..
.. If you have commitments for particular periods of Summer of Code, such as
.. exams or personal or family events, then please note in your timeline
.. (further down) when you'll be unable to work on your project. Providing
.. these are few, it is usually possible to get enough done across Summer of
.. Code to make for a worthwhile project.

Monday–Friday 7am-1pm UTC, but I can move it if needed.

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

I am applying only for Xapian.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

Information Retrieval is interesting to me as application of statistics. This project allows me to broaden horizons with practical examples. Also programming practice and communicating with mentors are very important to me.

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

Project I want to do assumes that there will be tool for evaluating Letor ranking algorithms with different weighting schemes on real-world datasets and compare its performance. It is useful not only for future developers, but for participants IR contests like TREC. Also it is possible to implement automated configuration choose using score classes.  

Project Details
---------------

**Describe any existing work and concepts on which your project is based.**

This articles suggest methods for determining a more effective search engine of the two given:

`A Comparison of Statistical Significance Tests for Information Retrieval Evaluation <https://ciir-publications.cs.umass.edu/getpdf.php?id=744>`_ 

`Information Retrieval System Evaluation:
Effort, Sensitivity, and Reliability <https://www.researchgate.net/profile/Mark_Sanderson3/publication/221300214_Information_retrieval_system_evaluation_effort_sensitivity_and_reliability/links/0c96052044b5291d08000000/Information-retrieval-system-evaluation-effort-sensitivity-and-reliability.pdf>`_

`Statistical Significance Testing in Information Retrieval:
An Empirical Analysis of Type I, Type II and Type III Errors <https://julian-urbano.info/files/publications/076-statistical-significance-testing-information-retrieval-empirical-analysis-type-i-type-ii-type-iii-errors.pdf>`_

There are several ranking algorithms with pretty same api implemented in xapian-letor. Also tools for preparing data and evaluation metric in xapian-evaluate, I want to expand xapian-evaluate by adding metrics and datasets at first, then implement test cases from papers above using rankers from xapian-letor. More detailed:

* Implement class for preparing data. The most convenient dataset is `FIRE <http://fire.irsi.res.in/fire/static/data>`_ and `TREC <https://trec.nist.gov/data/t2002_filtering.html>`_. There are already done tools for TREC (parse HTML, index, get qrel, etc), so will not hard to also use FIRE dataset here, because of similar form of data and English language corpus in it since Xapian has English stemmer. Also I want to add corpus from `https://dumps.wikimedia.org/enwiki/20191201/ <Wikipedia dumps>`_, but there are some difficulties here: I have to add plain text `extractor <https://github.com/RaRe-Technologies/gensim/blob/develop/gensim/corpora/wikicorpus.py>`_ and fabricate about 50 queries with qrels, this amount is required by the algorithms from the articles.

* Add metrics. Academical papers requires availability of AP, MAP, P@N, NDCG and ERR. Some of them already implemented in xapian-letor or xapian-evaluate. It is good to have them more generalized as they are now, e.g. make template which will suite both inputs std::vector<FeatureVector> and (Xapian::MSet, Xapian::Query, Xapian::Database).

* Add support of ranking. Currently rankers calsses implemented in xapian-letor, they needed in xapian-evaluate too. Evaluation algorithms suggests benchmark of two rankers, so config file should be restructured to have two rankers with weights specified for single run. 

* Implement testing algorithms from papers: 
   - Randomization test. Involves the calculation of the MAP for the mixed result of two systems. All count of cases equals to :math:`2^{|Q|}`, which could be time consuming, so this should be parameter in config file.
   - Student’s Paired t-test. This approach also requires calculation of vector standart deviation and mean, which is not hard to implement.

* Output valuation output as pivot table. Since it is not known exactly which ranker configuration is preferable for particular dataset, I would like to evaluate each possible pair for dataset and create table with results for both testing algorithms.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

Selection of testing algorithms based on results from papers.

**What other approaches have you considered, and why did you reject those in
favour of your chosen approach?**

I have discussed the possibility of using web datasets, but there are several reasons to store dataset locally:

* Most of Web-API datasets requires an account creation, which is not suitable for Xapian users.

* All data should be stored locally at least in parts to be indexed.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

I have a dialog in IRC about how to test xapian-evaluate. Fully integrate test harness to it seem ambiguous. Another way is to put harness in a separate project, but it is does not fit with my project. Maybe I prefer to write tests without harness.
 
Current state of SVM ranker is not clear, tests from master branch passes with valgrind and no bugs mentioned in pr #278.

Fixing SVM ranker bugs can take indefinite time.
 
**How useful will your results be when not everything works out exactly as
planned?**

If the utilities cannot be integrated sufficiently, there will be at least new evaluation cases.

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


* Weeks of bonding: Get more familiar with ranking algorithms, select specific suitable parts of the above datasets, discuss what is wrong with `#278 <https://github.com/xapian/xapian/pull/278>`_.

* 1 Week - FIRE dataset integration. Each user have to download it by themself, because of 
registration required. Implement training process using Letor API.  

* 2 Weeks of exams. This does not mean that I would not work at all, so I prefer mix exams days with doing stuff from case above (situation with exams is very unstable now in my University, so I timeline may change in this case).

* 1 Week - improve existing xapian-evaluate metrics, add AP.

* 1 Week - re implement NDCG and ERR from xapian-letor, add P@N.

* 1 Week - implement Randomization test.

* 1 Week - implement t-test.

* 1 Week - update configure file structure, add test cases for metrics and evaluation algorithms using small hand made datasets.

* 1 Week - implement Wikipedia data loader and parser, writing queries and qrels.

* 1 Week - finish task above, add pivot table case to build system.

* 2 Weeks - extra time if something goes wrong.

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).
..
.. One of the things we've discovered sets apart many of the best applications
.. is that the students in question have discussed the project with us before
.. submitting their proposal.

I had discuss with James Aylett and Olly Betts in IRC.

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

.. For more details, including the rationale for this with respect to code,
.. please see the "License grant" section of our developer guide:
.. https://xapian-developer-guide.readthedocs.io/en/latest/contributing/contributing-changes.html#license-grant

I agree.

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.

Third-party tools not needed.
