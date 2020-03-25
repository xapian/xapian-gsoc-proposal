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
WEIGHTING SCHEMES
======================================

About You
=========

 * Name: DIPANSHU GARG

 * E-mail address: dipanshu@iitk.ac.in , dipanshugargbnl@gmail.com

 * IRC nickname(s): dipanshu

 * Any personal websites, blogs, social media, etc: FILLME

 * github URL: dipanshu124@github.com

 * Biography:

.. Tell us a bit about yourself.

I am a Computer Science student of Indian Institute of Technology ,Kanpur,INDIA.I am proficient in C and C++ .As a hobby ,I practice Competitive Programming . Apart from programming, I am also very fond of Mathematics.

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

No,This is the first time.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

Before intending to apply for gsoc,I didn't have much experience.Now I have been using Xapian since the past 2 months.I am familiar with its indexed text search and also with the implementation of current Weighting schemes(the part where I intend to work).

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

No prior experience other than Xapian.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I have taken courses in C and C++ .I have also taken mathematics course in Linear Algebra and Number Theory. 

**What development platforms, tools and methods do you prefer to use?**

I use Ubuntu 18.10 as my OS .I am familiar with github.

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

No,this is the first time.

**What timezone will you be in during the coding period?**

.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.

IST(GMT+5:30)

**Will your Summer of Code project be the main focus of your time during the
program?**

.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.

YES,I won't have any other major activity during the program.

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

Monday-Friday 9am-5pm IST

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

NO.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

This project is suitable for my skills.Moreover,I am also eager to compare the effectiveness of using different weighting schemes. 

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

Anybody using Xapian will have more choices regarding which weighting scheme to use .There are many other Weighting Schemes which are worth implementing in Xapian some because they're potentially more effective than BM25(the default scheme for Xapian), others because they're of interest for Information Retrieval students and academics.

The use of Weight::create() in Xapian-evaluation would  help to establish a standard format for specifying the weighting scheme, which is helpful for users.

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

Xapian already supports the Vector space model used in Tf-idf Weighting Schemes.It has some normalisation (described by SMART) already implemented by sub classing WEIGHT.We can add more normalizations if we made some more statistics available to our Weighting Schemes. For example ,getting the max-tf would enable us to implement the "aug-norm" and "max-norm" described in SMART normalisation.

I would also be implementing the following normalizations (described in the below mentioned research papers http://www.kolda.net/publication/ornl-tm-13756.pdf)- Entropy,Global frequency IDF,Changed-coefficient ATF1,Augmented average term frequency,Augmented log,Square root,Log-global frequency IDF,Incremented global frequency IDF,Square root global frequency IDF.These normalisations have proven to be more effective than other popular weighting schemes in certain cases.(For details ,please refer the research paper.)

The above mentioned normalizations dont need any other extra statistics,i.e, all the required stats are already available.So, only a small patch is required for each.

I would also be implemented the "aug-norm" and "max-norm" described in SMART normalisation.For that we need "max-tf" to be made visible to our Weighting Scheme.This can be done By using the Weight ::Internal subclass.It has a map  (named termfreqs) which has the required information.

It would also be very useful to see how the different schemes compare for speed and retrieval effectiveness, so can offer solid advice to users wondering which to use.So, for this we can use https://github.com/samuelharden/xapian-evaluation to evaluate and compare modified weighting functions with their counterparts to access their speed and retrieval effectiveness.

Currently the code in xapian evaluations requires some cleanup.Currently we need to provide separate information for different weighting schemes and their parameters.This is a lot of extra work.All of this can be avoided by using Weight::create().For using Weight::create(),we can change the config_value  string  input.Instead of providing just the name of Weighting scheme ,we can use a string with weight scheme name followed by its parameters (same as used in Weight ::create()).Then we wont require to write extra code for parameters.We will also make changes in trec_search.Now it would be simple as we won't need to make separate checks for implementing different schemes.We would simple use Weight::create() and feed it with the string used earlier.

Then I would be adding support for the newly inplemented normalistions in Weight::create().This requires some changes in Registry .A few additions in the map implemented there would do.

 Finally I would be comparing the effectiveness of different normalisations using Xapian evaluations. 

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

1) http://www.kolda.net/publication/ornl-tm-13756.pdf 
2) http://www.iaeng.org/publication/IMECS2010/IMECS2010_pp690-692.pdf
3) http://people.csail.mit.edu/jrennie/ecoc-svm/smart.html

Th first paper suggests that the new normalisations are more effective than other popular weighting schemes in certain cases.Since this paper is a little too old, for that I have mentioned the second paper which is more recent. It also talks about the Weighting schemes mentioned in the previos paper.Third paper is about the SMART normalisations which are popular.

The implementation of new normalisations and evaluation is similar to those already implemented ,So that won't be a problem either.

**What other approaches have you considered, and why did you reject those in favour of your chosen approach?**

I also wanted to implement the "sum","cosine","max" and "fourth" normalization described by SMART for 3rd parameter.But unlike those I have chosen to implement ,these require the visibility of the weights of other terms.Since the other term weight are internal to the scheme ,these stats can't be directly fed to our Weighting scheme.So these can't be implemented in our current weighting framework AFAICS.

Another approach to add support in xapian-evaluation was to simply add code without using Weight::create().That would not be useful as the information of separate weighting schemes and parameters can be avoided.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

I don't think there are any possibilities of uncertainties in this project.

**How useful will your results be when not everything works out exactly as planned?**

Just in case things don't go as planned,the work would still be useful.This project involves the implementation of different normalisations.Their implementation is not dependent directly on each other.Even if some normalisations are left, those implemented will be in perfect working conditions.

Also the changes in Xapian evaluation to use Weight::create() is an independent sub project as well.

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

FILLME

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

I have discussed it at IRC.

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

I have already agreed to that when I made my first contribution with Xapian.

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

I would be using Weight.h ,Weight::Internal ,tfidfweight subclass.I would also be using xapian-evaluation .
