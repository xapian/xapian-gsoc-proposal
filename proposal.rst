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

=============================================
Learning to Rank Clickstream Data Mining
=============================================

About You
=========

 * Name: Cong Ding

 * E-mail address: congding@pku.edu.cn

 * IRC nickname(s): Cong

 * Any personal websites, blogs, social media, etc: https://congding.info/blog

 * github URL: https://github.com/tson1111

 * Biography:

.. Tell us a bit about yourself.

I am a second year undergraduate student in Peking University, Beijing. I am 
majoring in computer science. I have always wanted to be a great developer 
and use my code to make the world a little better since the first day I learnt 
programming. I'm also passionate about challenges and solving problems.

When I first heard of the concept of open source, I thought it is 
super cool. I belive that computer science has been changing the world at a 
tremendous speed ever because many developers keep an open mind and are willing 
to share their thoughts with others. GSoC provides me with a chance to make 
contributions to open source projects with mentorship from great developers all 
over the world. If I have the chance to participate in GSoC and work with Xapian, 
I will try my best to complete this project.

Besides computer science, I am pursuing a double major in Chinese Language and 
Literature. I am enthusiastic about linguistics and have a deep love for world 
literature. I also enjoy running, playing tennis and fencing (mostly sabre).


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

No, I do not have any prior relevant experience.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

None. I have met with Xapian since Feburary this year.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I was working on an open source graph database named 
`gStore <https://github.com/pkumod/gStore>`_, which is developed and maintained 
by our lab. I was focusing to optimize its index 
structure.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I've taken some relevant courses in school, including but not limited to:

* basic maths (Calculus, Linear Algebra, Probability and Statistics, Discrete Math)
* programming courses (C++, Javascript, Python)
* computer science (Introduction to Computer System, Data Mining, Compiler Design, Data Structure and Algorithms)

**What development platforms, tools and methods do you prefer to use?**

* OS: Ubuntu 18.04 LTS
* Editor: VSCode
* Version Control: git

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

No. It is the first time for me to work on search engines like Xapian.

**What timezone will you be in during the coding period?**

UTC +8.

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes, I don't have other arrangement this summer.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

Monday-Saturday 10am-5pm and 8pm-11pm (UTC +8). 

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

First, I am a big fan of data-driven methods. I believe that the data never 
lies, however, sometimes we don't know how to get the truth from data. So 
this project gives me an opportunity to look into the clickstream data and 
try to mine something useful that can help us improve the performance of 
the search engine.

Click logs embed important information about user satisfaction with a 
search engine and can provide a highly valuable source of relevance 
information. Compare to editorial labels, clicks are much cheaper to obtain 
and always reflect current relevance.

I believe with a better click model and multiple model choices , 
Xapian will provide better service for users.

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

At present, users of Omega will get a document list reranked by the existing 
click model SimplifiedDBN. My work will focus on improving the user experience 
by making the search result more personalized and satisfying. I believe 
multiple well-performed click models and a detailed documentation will provide
the users with more freedom and more personalized choices.


Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

My work will be based on the GSoC 2017 Project `Clickstream Mining for 
Learning to Rank training data <https://trac.xapian.org/wiki/GSoC2017/LetorClickstream>`_. 

**Phase 1: Implementing Click Models**

The previous work has implemented the simplified DBN model for clickstream mining. 
I plan to finish the EM algorithm in order to get a better performance.


Besides DBN model, I will implement two more click models, the Dependent click Model 
(DCM) and the User Browsing Model (UBM). Both two are also highly 
effective to improve document ranking. 

I will first work on an abstract class for all click models and then try to implement 
each model according to relevant papers. 



**Phase 2: Documentation**

The second phase of my work will be a detailed documentation of each model I 
implemented. It will provide the Omega users with a brief view of click models and
pros & cons of each model. I will continue to work on the clickmodel.rst in the 
Omega documentation files.

**Phase 3: Evaluation**

The third phase is about the evaluation. With more and more models applied, I 
believe it will be necessary to provide an evaluation method for the users. I'm 
going to use CTR estimation for the evaluation of the models. For the method 
is convenient to implement and has a relatively high accuracy. Also the click logs 
is easy to acquire due to the previous GSoC project.




**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

The EM algorithm of **DBN model**: I will implement the EM algorithm for DBN model according to the appendix of 
`A dynamic bayesian network click model for web search ranking. WWW (2009). 
<https://dl.acm.org/citation.cfm?id=1526711>`_. 


The **DCM model**: I will implement the dependent click model according to the paper `Efficient 
multiple-click models in web search. WSDM (2009). 
<https://dl.acm.org/citation.cfm?id=1498818>`_.

The **UBM model**: the user browsing model is from paper `A user browsing model to predict search engine click data from past observations. SIGIR (2008).  <https://dl.acm.org/citation.cfm?id=1390392>`_.


**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

The Federated Click Model (FCM) and Vertical Click Model (VCM)are not appropiate 
for Xapian because of the SERP (search engine return pages) of Xapian do not 
provide with vertical contents.

I have also considered about the end to end model.However, I can not make sure to
develop a clear and fairly smooth process all the way through from logging clicks 
to turning the logs into relevance judgements to training the model to getting 
queries reranked. So I didn't continue to work on this idea.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

I'll go on to do some research about the evaluation of click models. I believe that 
with the help of my mentors, we will find an elegant and user-friendly way to judge 
the performance of each model and try to recommend the most appropiate model for 
each user. 

**How useful will your results be when not everything works out exactly as
planned?**

At the beginning, I'll complete the EM algorithm for the existing SimplifiedDBN 
model. So even if something went wrong when I implement other models, which is unlikely 
to happen, we would still get a better performed DBN model. 

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

**Bonding stage: Prior–May 28**

* Get to know the community and interact with mentors.
* Keep diving into Xapian and Omega's code base.
* Fix some issues to go through the code review process.
* Read more papers and have a clearer understanding of different click models.
* Have clear blueprint of the project and think about the rough implementation of click model abstract class.

**Coding Week 1: May 28–June 3**

* Discuss the details of abstract class of click model with mentors.
* Start implementing the abstract class.

**Coding Week 2: June 4–June 10**

* Final Week in unversity.
* Finish implementing the abstract class.
* Adapt the exsiting SimplifiedDBN class to the abstract class.
* Start working on the DBN class with EM algorithm.

**Coding Week 3: June 11–June 17**

* Final Week in university.
* Finish the training method for the DBN class.
* Discuss the DCM model template with mentors.
* Start writing automated test for the click models.
* **Deliverable:** DBN model with EM alogorithm

**Coding Week 4: June 18–June 24**

* Obtain the Obtain the relevance judgements dataset for training the models.
* Start testing the DBN models with click logs. 
* Implementing the DCM model.

**Coding Week 5: June 25–July 1**

* GSoC Evaluation: June 25 - 29
* Finish testing the DBN model.
* Finish implementing the DCM model.

* **Deliverable:** DCM model.

**Coding Week 6: July 2–July 8**

* Start discussing the UBM model with mentors.
* Start implementing the UBM model.
* Generate more click logs for testing.
* Testing the DCM model.

**Coding Week 7: July 9–July 15**

* Finish implementing the UBM model.
* Test the UBM model.
* Obtain the relevance judgements dataset for training the models.
* Obtain the predicted relevance judgments on the Omega click data.
* **Deliverable:** UBM model.

**Coding Week 8: July 16–July 22**

* Implement the mechanism to automatically generate Qrel file.
* Train the letor module on training file obtained from Omega click data.
* Use the letor module for displaying relevant search results on top of SERP.

**Coding Week 9: July 23–July 29**

* GSoC Evaluation: July 23 - 27
* Document various models and how to use the model.
* Discuss the CTR evaluation with mentors.
* **Deliverable:** a detailed documentation.

**Coding Week 10: July 30–August 5**

* Implementing the CTR evaluation method for click models.
* Discuss the frequency of evaluation and the threshold of accuray to change the model.

**Coding Week 11: August 5–August 11**

* Documenting how to use the evaluation method for click models.
* Decide the default click model and implement the machanism of changing the click models.
* **Deliverable:** a detailed mechanism and documentation about the evaluation methods of click models. 

**Coding Week 12: August 12–August 19**

* Buffer week to accommodate delays in the planned schedule due to unprecedented events.

**Final Evaluations: August 20–August 27**

* Polish my documentation and review the code.
* Write a summary article throughout the project.
* Do clean up work if any present.




Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

Yes. I have discussed my project via both IRC and 
`mailing list <https://lists.xapian.org/pipermail/xapian-devel/2019-March/003323.html>`_.


Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1399

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

The `clickmodels <https://github.com/varepsilon/clickmodels>`_ repository is a 
small set of Python scripts for the user click models. I may refer to it when
working on my project.

The `click models for web search <https://clickmodels.weebly.com/>`_ website 
also provides with tutorials and resources on click models. The survey on the 
website helps me a lot write this proposal.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
