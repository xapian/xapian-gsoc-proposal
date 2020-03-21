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
GSOC 2020 - PROPOSAL
======================================

About You
=========

 * Name: S SRINIVAS YADAV

 * E-mail address: vasu.srinivasvasu.14@gmail.com

 * IRC nickname(s): srinivasyadav227

 * Any personal websites, blogs, social media, etc: NIL

 * github URL: https://github.com/srinivasyadav18

 * Biography:

.. Tell us a bit about yourself.

I am srinivas , an 18 year old second year undergraduate student from Keshav Memorital Institute of Technology ,Hyderabad, India.
I am a tech enthusiast and a person who loves sports.

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

No

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I dont not have any previous experience with xapian or any other indexed text search.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

There is a software Barrier,an Open source KVM Software where you can use one keyboard and mouse 
on different computers nearby when all are connected to same network..I was trying their source code 
and have implemented few small c programs in linux for capturing device events from one computer and 
sending to other system in the local network with known IP address.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I have taken course on Machine Learning and its science applications where I have learnt the basics of machine learning 
and deep learning and have worked with Convolutional Neural Networks and facial recongnition,
a course on C programming and assembly language where I have learnt how C code gets compiled and 
to use inline assembly in C for 8086 microcontroller, I am familiar with cuda and parallel programming. 
I have worked with small scale electronics  and IoT projects(with raspberry,arduino).
I love problem solving and I keep learning different algorithms and datastructures.
My hobbies are playing cricket and exploring new places. 



**What development platforms, tools and methods do you prefer to use?**

I prefer Visual Studio Code when I'm learning a new language becuase it provides auto-completion and gives information like 
what that particular class or function is about, when I get the basics I switch 
to vim ,the editor I use for more focus , speed and accuracy. 
I use Docker for testing in linux and recently started using Travis CI . 
I prefer Guake terminal for fast switching between code and terminal.


**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

No 

**What timezone will you be in during the coding period?**

.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.

GMT+5.30 (IST) 

**Will your Summer of Code project be the main focus of your time during the
program?**

.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.

Yes , Summer of Code is my main focus this summer.

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

Monday–Saturday 5am-4pm UTC 

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No

Implement Bindings for Go
==========================

Motivations
-----------

**Why have you chosen this particular project?**

My main areas of interest includes C++ and Go. They provide greater flexibility and concurrency.
I have previously  used cgo and swig in small projects.
So I feel I am elgible for this project.

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

As Go lang is emerging now a days rapidly and its being used in servers and distributed systems,
providing a Go API for the people who want to use xapian search engine in thier servers would be a huge benefit. 

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

I have done some intial implementation of go bindings for xapian which are available in my git repository (currently working on linux and unix systems).

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

Yes, my intial work on bindings definitly show that bindings can be implementend in go with c++ shared libraries.
For time being they are working on Linux and Unix systems. I consider expanding them to work on other platforms is not a difficult job. 

**What other approaches have you considered, and why did you reject those in
favour of your chosen approach?**

Initially I was able to provide bindings after installation of the shared library on the host system
, but then I have realised that before installing the core we need to build the bindings and I was using 
pkg-config , later I started using flags from configure as one of my mentor (olly) suggested.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

I need to have a closer look at iterator classes of xapian for Implementing bindings in go.

**How useful will your results be when not everything works out exactly as
planned?**

I am confident enough that the project would be implemented and completed properly on time.
If in case some thing goes wrong , I would continue my work after GSoC timeline as I am very much 
interested in this project and love to contribute to xapian. 

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
In this summer I would like to do three things:

    1. Make the go bindings compatible with the xapian build system.

    2.  Provide bindings in go and complete API reference (as it is provided for C++)
        using godoc,Go lang's official documentation tool where any one can look at the 
        documentation if they just have go installed.The user can view the xapian 
        documentation by just running go doc xapian from the terminal or command prompt.
        And the documentation would be providied in godoc official website 
        and xapian.org.
        I have divided this part of work into to 10 weeks.

    3.  Provide the go get feature for using xapian bindings in go with 
        proper guide lines regarding whether the xapian core is installed
        or not.


Before May 18,2020 :
I would finish up the build system part of work for go bindings that 
are generated purely from xapian-headers.i and xapian-head.i such that
these can be used like any other bindings and in any platform that other xapian bindings can be used in.

Each week for first 3 days I would work on provding API , that is writing swig interface 
for the functions and classes which aren't generated from 
existing swig interfaces(xapian-headers.i and xapian-head.i) with typemaps and other features of swig in go.i.
Next 2 days documenting the code with examples and the last day for testing.
I have grouped different classes for each week.


First Month : 

  Week1 :
        Work on Document , Registry , Query , Stem implementation , Stem classes.
  Week2 :
        Work on PositionIterators , PostingIterator , TermTterator , ValueIterators
        
  Week3 :
        Work Eset , Mset , Rset , EsetIterator , MsetIterator classes.
       
  Week4 :
        Work on MatchDecider , Enquire , ExapandDecider , ExapandDeciderAnd ,
        ExapandDeciderFilterPrefix , ExapandDeciderFilterTerms , KeyMaker ,MultiValueKeyMaker ,
        Stopper classes.
     
Second Month :
  Week5 :
        Work on all the Derived classes on RangeProcessor.
  Week6 :
        Work on all Weight classes.
  Week7 :
        Work on all the Derived classes of Posting Source.
  Week8 :
        Work on all the Derived classes of Matchspy classes and classes related to Latlong.

Third Month : 
  Week9 :
        Work on Database class.
  Week10 :
        Work on Exceptions.
  Week11 :
        Implementing go get feature.
  Week12 :
        Windup everything and Testing. 

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

So far we have discussed mainly about the build system of xapian for bindings in go.
And a feature, go get to install xapian-bindings.I have made a PR (https://github.com/xapian/xapian/pull/292) where one of my mentor (olly)
suggested for somechanges
and I have done most of it.

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

Yes, I agree.

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

I am using the existing xapian-headers.i and xapian-head.i from xapian ,
apart from them I am not using any other.