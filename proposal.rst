.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
.. 
.. http://www.sphinx-doc.org/en/master/rest.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See the [wiki:GSoCProjectIdeas ideas list] for some suggested project ideas.
.. You are also most welcome to propose a project based on your own ideas.
.. 
.. From experience the best proposals are ones that are discussed with us and
.. improved in response to feedback.  You can share draft applications with
.. us by forking the git repository containing this file, filling in where
.. it says "FILLME", committing your changes and pushing them to your fork,
.. then pointing us at the fork by giving us a link or IRC or the mailing list.
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
.. helpful - see http://www.sphinx-doc.org/en/master/rest.html#images for how
.. to do so.
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
.. http://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

======================================
Learning to Rank Clickstream Data Mining
======================================

About You
=========

 * Name: Changlin Zhang

 * E-mail address: vicky.zhangcl@outlook.com

 * IRC nickname(s): Vicky

 * Any personal websites, blogs, social media, etc: https://changlinzhang.github.io/

 * github URL: https://github.com/changlinzhang

 * Biography:

.. Tell us a bit about yourself.

I am a senior student majoring in software engineering at Zhejiang Univeristy, China and I am going to be a graduate student at University of South California in August. I want to join the work of Xapian this summer because  it is most closely related to my previous works and interests. I have experiences in developing two search engines, one recommendation system and two deep learing networks of computer vision. I am skilled in C++, Python and Git. I sincerely hope you could consider my application.

Background Information
----------------------

.. The answers to these questions help us understand you better, so that we can
.. help ensure you have an appropriately scoped project and match you up with a
.. suitable mentor or mentors.  So please be honest - it's OK if you don't have
.. much experience, but it's a problem if we aren't aware of that and propose
.. an overly ambitious project.

Have you taken part in GSoC and/or GCI (https://codein.withgoogle.com/) and/or
similar programmes before?  If so, tell us about how it went, and any areas you
would have liked more help with.

I have done a similar project in one course named "The Middleware Technology". In this project, I analyzed the source code and performance of ActiveMQ. I found that in its transferring of files part, users always has to choose between capability and usability. In detail, using ByteMessage or using JMS streams is not so capable and using ftp/http as fileserver is too complex. Thus, I provide a method of using tcp to do the transferring. As a result, the new method is more easy to use and it is a more lightweight fileserver. Users can also have one more choice (a more balanced one) to transfer files. 

I think the general idea of improving one system and the ability of source code analysis could help me with the Rank Clickstream Data Mining project.

Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.

I have developed some entry-level porjects of two search engines and one recommendation system as following.

GooDu
•	Developed a search engine over Reuters Corpus to satisfy non-professional users
•	Added advanced features (e.g. synonym query, wildcard query and spelling correction)
•	Simulated prevailing search engines with a well-designed user interface

Shakespearist
•	Developed a search engine over “The Works of William Shakespeare”
•	Identified the stop words with universal stop table and statistical way for specific Shakespeare set
•	Optimized the thresholds on query to achieve optimal results

Newly
•	Developed a news aggregator from mainstream news media websites regularly for UI integration
•	Rearranged UI presentation to learn and adapt through users’ behaviors for specific customization
•	Adapted the responsive layout to support both web and mobile clients

Do you have previous experience with Free Software and Open Source other than
Xapian?

No yet, but I am going to join in the BigDL(an open resource library) group at Intel as an intern in this coming week. Thus, I think I would have such similar experience when GSoC begin in summer.

What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?

I have completed relevant course named Data Mining and Information Retrieval at college.  In the Data Mining course, I did a lot of data mining practice, such as implementing vector quantization to do image compression, running k-means algorithm to discover patterns in given dataset, using principal component analysis to stimulate hacking the CAPTCHA system and recover the face image dataset and so on. In the Information Retrievel course, I build the systematic understanding of information retrieval and completed the project of a search engine named GooDU.

Moreover, I am experienced in coding especially c++ development. I have interned at Owtware to do iOS development and have experiences of several projects using C++ (such as MiniSQL, a painter tool and so on).  I also have been a teaching assistant of a C++ programming course to direct freshmen.

What development platforms, tools and methods do you prefer to use?

C++ and Python

Have you previously worked on a project of a similar scope?  If so, tell us
about it.

I have done a similar project in one course named "The Middleware Technology". In this project, I analyzed the source code and performance of ActiveMQ. I found that in its transferring of files part, users always has to choose between capability and usability. In detail, using ByteMessage or using JMS streams is not so capable and using ftp/http as fileserver is too complex. Thus, I provide a method of using tcp to do the transferring. As a result, the new method is more easy to use and it is a more lightweight fileserver. Users can also have one more choice (a more balanced one) to transfer files.

What timezone will you be in during the coding period?

GMT +8 Time

Will your Summer of Code project be the main focus of your time during the
program?

Yes

Expected work hours (e.g. Monday–Friday 9am–5pm UTC)

Monday–Sunday 6pm–12pm UTC

Are you applying for other projects in GSoC 2018?  If so, with which
organisation(s)?

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No

Your Project
============

Motivations
-----------

Why have you chosen this particular project?

It is most closely related to my previous works. Plus, I am trilled to facilitate traditional information retrieval to integrate with other fields and technologies as data mining.

Who will benefit from your project and in what ways?

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

Search engine developers by providing them better libraries and results.

Project Details
---------------

.. Please go into plenty of detail in this section.

Describe any existing work and concepts on which your project is based.

1. https://github.com/danielkorzekwa/tennis-rating-dbn-em-scala
It is a tennis ratings model based on Dynamic Bayesian Networks and Expectation Maximization, implemented in Scala.
I'll refer to it to estimate γ in DBN with EM in C++.

2. https://github.com/varepsilon/clickmodels
It is a set of click models implementations including Dependent Click Model and Intent Aware Models.
I'll refer to it to add DCM and IAM.

Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?

As the papers of DBN, DCM and IAM stated. 

What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?

DBN, DCM and IAM were come up many years ago. Thus, I may also want to follow investigate some recent works to improve omega results while I havent found suitable ones yet.

Please note any uncertainties or aspects which depend on further research or
investigation.

DBN, DCM and IAM were come up many years ago. Thus, I may also want to follow investigate some recent works to improve omega results while I havent found suitable ones yet.

How useful will your results be when not everything works out exactly as
planned?

The thing may not work as planned is how well my results will be improved. But they will be still useful in two ways:
1. It will improve results even little.
2. It will build the framework to  intergrate different models instead of single DBN model.

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

April 24, 2018 - May 14, 2018	familiarilize myself with xapian by doing some small changes or demoes
May 15, 2018 - June 6, 2018		improve DBN with EM and test
June 7, 2018 - June 30, 2018	implement DCM and IAM and test
July 1, 2018n - July 21, 2018	finalize letor API with omega and test
July 21, 2018n - August 6, 2018	explore more recent proposed ideas to improve

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

None.

Licensing of your contributions to Xapian
-----------------------------------------

Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1376

Use of Existing Code
--------------------

If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.

1. https://github.com/danielkorzekwa/tennis-rating-dbn-em-scala
It is a tennis ratings model based on Dynamic Bayesian Networks and Expectation Maximization, implemented in Scala.
I'll refer to it to estimate γ in DBN with EM in C++.

2. https://github.com/varepsilon/clickmodels
It is a set of click models implementations including Dependent Click Model and Intent Aware Models.
I'll refer to it to add DCM and IAM.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
