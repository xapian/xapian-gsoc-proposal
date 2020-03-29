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
Improve estimated total number of results
======================================

About You
=========

 * Name: Abdelrahman Atef Mohamed

 * E-mail address: boda998@yahoo.com

 * IRC nickname(s): Boda

 * Any personal websites, blogs, social media, etc: https://www.facebook.com/boda.sadala

 * github URL: https://github.com/BodaSadalla98

 * Biography:



Hey, I am Boda, Computer Engineering student from Egypt.
I have a great passion for Competitive programming, I have participated in many
`ACM  <https://en.wikipedia.org/wiki/International_Collegiate_Programming_Contest/>`_ contests
Last year we came in third in local contest and qualified to next round. I participated in Google Hash Code this year, and came in #31 on Egypt.


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

No, I haven't.


**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

My first encounter with Xapian was when I installed xapian to index search results on synaptic package manger.
After I grew interest to take part in Xapian project for Gsoc, I started by building xapian and getting familiar with the code base.
I started working on adding `two new range operators <https://github.com/xapian/xapian/pull/289/>`_ (OP_VALUE_LT and OP_VALUE_GT), then I built two new testcases for them, and once these
changes commited, I will start on writing a documentation for them.
I also added a `minor optimization <https://github.com/xapian/xapian/commit/3c56e5db5b8f3696fd8f311793c62921eb413ef8/>`_ for "OP_VALUE_GE".

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

There was a small project which is a `command line interface for spotify on Linux <https://github.com/pwittchen/spotify-cli-linux/>`_
which is written in python3, and it uses a `python2 api <https://github.com/enricobacis/lyricwikia/>`_ to get songs lyrics, but the two
didn't build for me due to combatibility issues, so I `adapted them and get them to fully work <https://github.com/BodaSadalla98/spotify-cli-linux/>`_.


|

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I took many Software related Courses in college like:

	* MIPS processor and its assembly.
 	* c, c++, OOP with c++. I did some college projects like `Equations-solver <https://github.com/BodaSadalla98/Equations-Solver/>`_.
	* Data structures and algorithms.
	I have dived a little bit deeper in DS and algorithms due to my interest in compettive programming.

**What development platforms, tools and methods do you prefer to use?**

Right now, I develope on Ubuntu, I use vscode and geany.

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

I have worked on many projects, but not related to information retrieval nor indexed search.

**What timezone will you be in during the coding period?**



GMT+2, Cairo,Egypt


.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.



**Will your Summer of Code project be the main focus of your time during the
program?**

Yes.
.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.



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


Sunday-Thursday 8am-4pm UTC.

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

I am not, this is the only project I am applying to this year!

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

As I worked on implementing `new operators <https://github.com/xapian/xapian/pull/289/>`_, I got more familiar with operators, and queryinternal
code. Also, This project is more suitable for me, as I prefer working on backend stuff.

**Who will benefit from your project and in what ways?**

Pretty much anyone uses Xapian, as giving more accurate estimation for the number of the matches, can help in many ways.

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.


Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**


The core idea about this optimization, is to make use of the new last, and first docids for each term in the query tree.
Utilizing that, we can get better estimated results, as we reduces the search range from the total db_size to shorter range.


**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

There's approach addressed in a `patch <https://oligarchy.co.uk/xapian/patches/docid-ranges-in-matcher.patch/>`_ by Olly,
that make use of the fact that we have the ids for the first and last documents now.
Example: for the "MultiAndPostList", we would mutiply the probability of each term independantly, and we would do that by
divide the term frequnecy(from term_freq_est() function) by the database size. But now we can get the range from the first docid to the last docid
(last - first +1), and we use that range instead of the whole database size.

Take for example AND_NOT:

	Let's say  L AND_NOT R

	now thanks to the new implementation, we have the range for L and R.

	The range which we sould consider is only (L range - overlapped range between L and R)




**What other approaches have you considered, and why did you reject those in
favour of your chosen approach?**


To store the count of term pairs in the database, but this can pretty huge
(ie 10k terms would be (10k C 2) entries which around 50 million).
This would give us an accurate number of the results, but it can grow exponentially
and take huge space.


**Please note any uncertainties or aspects which depend on further research or
investigation.**

If the first and last docids happend to be the first and last in the db, then our range would be same (db_size), and the estimate would be the same.

we can try to use some data on correlated terms, but not sure if that would be efficient in respect to data size.

**How useful will your results be when not everything works out exactly as
planned?**

It would still produce better estimates as we reduced the number of documents we divide by.

Project Timeline
----------------

The main goal of this project is to improve the estimation of the total number of results buy making use of the
the new feature that gives the first and last docids for each term.

The task is to improve the Xapian::MSet::get_matches_estimated() method for the PostList subclasses , but OP_AND and OP_OR are almost done.


multiandpostlist, orpostlist, postlisttree :

	Almost done by Olly.
boolorpostlist:

	Same as OP_OR.
AND_NOT(andnotpostlist) :

	implementing get_used_docid_range().

	let's say  L AND_NOT R :

	if L and R doesn't overlap, then we can just return estimated number for L.

	if they do overlap, then our range would be (L range - intersection of L and R).

	then we calculate the probability.

XOR(multixorpostlist) :

	implementing get_used_docid_range().

	let's say L XOR R :

	if l and R doesn't overlap then it would be like OP_OR.

	if they do, then we would add the two ranges and  then subtract the overlapped range

	then we calculate according to that range.

AND_MAYBE(andmaybepostlist) :

	implementing get_used_docid_range().

	This is treated like AND

	let's say L AND_MAYBE Right

	then we just return the estimated number of L

FILTER :

	implementing get_used_docid_range().

	This is treated like MULTI_AND

	let's say L FILTER Right

	then we just return probability of L times the probability of R times the total range, which would be the union of the two ranges.

NEAR(nearpostlist), PHRASE(phrasepostlist), and exactphrasepostlist :

	Most of the work done by MultiAndPostList. Based on the last three weeks' research, we would know, if we can calculate better estimate.

VALUE_RANGE(valuerangepostlist) :

	We can make use of the fact that we have the first and last docids, to reduce the total range to be the overlapped range of the
	begin and end ranges, instead of the slot_freq reange.

VALUE_GT(valuegtpostlist), VALUE_LT(valueltpostlist), VALUE_LE, VALUE_GE(valuegepostlist) :

	implementing get_used_docid_range().

	We can just return the range of the first, and last docids.

ELITE_SET :

	implementing get_used_docid_range().

	Get the elite set of N terms, then treat it like MULTI_OR

SYNONYM :

	implementing get_used_docid_range().

	treated like OP_OR

MAX(maxpostlist) :

	implementing get_used_docid_range();

	treated like OP_OR

WILDCARD, EDIT_DISTANCE :

	implementing get_used_docid_range().

	This would return the matches terms along with them ranges,then we can calucate as MULTI_OR;

INVALID, LEAF_TERM, LEAF_POSTING_SOURCE, LEAF_MATCH_ALL,LEAF_MATCH_NOTHING, OP_SCALE_WEIGHT(extraweightpostlist),
deciderpostlist, externalpostlist, orpospostlist, selectpostlist, wrapperpostlist  :

	Unrelated.

|

My initial plan is as follow:

	**Every week would be 3 days of coding, 2 days of testing and documenting.**

	**BY the end of every week, new edits should be ready to be merged.**
|

First three weeks of bonding :

	week one and two : get familiar with the Xapian::matcher code base.

	week three : setup debug environment, and how to test project parts, read c++ concepts on developers guide.
week 1 : Work on OP_AND_NOT

week 2 : Work on OP_XOR,  boolorpostlist.

week 3 : Work on OP_AND_MAYBE

week 4 : Work on OP_FILTER

10 June : Final exams (this is an estimate,official schedule isn't announced yet.)

First Evaluation

week 5 : Work on OP_ELITE_SET

week 6 : Work on OP_SYNONYM, OP_MAX

week 7 : Work on OP_WILDCARD, and OP_EDIT_DISTANCE

week 8 : Work on OP_VALUE_RANGE

Second Evaluation

week 9 : Work on OP_VALUE_GT, OP_VALUE_GE, OP_VALUE_LT, and OP_VALUE_LE

week 10, 11 , 12 : stretch goal : start a research on whether we can use a standard language datasets to calculate correlation between terms
and use it to tweak the estimates. Initial idea, to start with only strong correlated terms, and see how much improvement would that make.

I think,we would finish the main goal before the tenth week, and we would have more time for the stretch goal. I think we would't be able to finish this stretch goals
by Gsoc end date, but by then if we found positive feedback from this approach, we can continue work on it.

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

I discussed it with Olly and James on IRC channel

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.


I do!


.. For more details, including the rationale for this with respect to code,
.. please see the "License grant" section of our developer guide:
.. https://xapian-developer-guide.readthedocs.io/en/latest/contributing/contributing-changes.html#license-grant



Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**


I don't know yet.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
