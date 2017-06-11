---
title: IIS Handbook and Operations Manual
author: Andrew Olney
rights:  Creative Commons Non-Commercial Share Alike 3.0
language: en-US
...


[preface]
== Contributors

This book is open source and anyone is welcome to suggest changes.
Below is a list of all of the contributors over time who have contributed.
Our thanks to everyone for their contributions to the IIS.

=== 17.05
Andrew Olney

[preface]
== Preface by Andrew Olney

Welcome to the first version of the IIS Handbook and Operations Manual.
The IIS has never had a book like this before, but as the IIS has grown in scope and complexity,
so has the need for a handbook that documents our programs and procedures.

This first version (17.05 in year/month notation) reflects my personal views that
have developed over the last 10 years as I've served as Associate Director and
eventually Director of the IIS.
Accordingly, the priorities and biases are mine and have not been endorsed by
the IIS community.

My hope is that future versions will be voted into adoption or follow some
similar consensus-building process.
By hosting this handbook on GitHub and using AsciiDoc, I've made it as easy as
I know how for this book to be improved by a distributed group of people,
potentially across many years, such that all revisions are well documented.
This approach is well-traveled by other open source books,
and I've leaned heavily on the model provided by *Pro Git* (2nd edition).
To make changes, please refer to the procedures in the README file in the root
of this repository.

[preface]
== Introduction

*Chapter 1* is for everyone.
It speaks to interdisciplinary researchers regardless of where they are in their careers.
Interdisciplinary research is hard.
To be successful, we have to step outside our disciplinary perspectives and be willing to learn and to be challenged.
This means not only learning about other disciplines, which have their own literature, methods, and approach to knowledge,
but also learning to work on teams with members of other disciplines.
We have to consider how these issues impact student milestones and professional development,
as well as tenure and career advancement for faculty.
Within a university that has traditional departments, we must all understand how
interdisciplinary research impacts typical departmental procedures from both an
academic (e.g. committee composition) and finance (e.g. course buyout) perspective.
The purpose of this chapter is to provide a common ground for everyone that is
assumed for the following chapters.

*Chapter 2* is for students.
It gives advice to students and explains IIS programs that support them.
Students it seems are often the forgotten piece of the equation in interdisciplinary research.
Issues like composing a committee, getting letters, or working with faculty become much more
difficult when the faculty you are working with are not in your field.

*Chapter 3* is for faculty.

*Chapter 4* is for staff.




[[_getting_started]]
== Getting Started

This chapter will be about getting started with the IIS.
We will begin by giving some background on the IIS and its history,
then move on to an overview of what the IIS does.

include::sections/about-iis.asc[]

include::sections/history.asc[]

include::sections/membership.asc[]

include::sections/research-events.asc[]

include::sections/resources.asc[]

include::sections/degrees.asc[]

=== Summary

You should have a basic understanding of what this IIS is and how it works.

=== About the IIS

(((version control)))
What is the The Institute for Intelligent Systems?

The Institute for Intelligent Systems (IIS) is an interdisciplinary research center at the University of Memphis.
Unlike many research centers, the IIS has historically pursued a research agenda
set by participating researchers who *self-organize around research problems*,
rather than a highly focused formal agenda.
The breadth and flexibility of the IIS is reflected in our current mission statement:

____
The Institute for Intelligent Systems is dedicated to advancing the state of knowledge and capabilities of intelligent systems, including psychological, biological, and artificial systems.

By conducting cutting-edge research and publishing our findings in peer-reviewed venues, we contribute to the discipline and, ultimately, to the public. In doing so, we are also training the next generation of scientists.

Our mission depends on an interdisciplinary approach that brings together researchers from many different backgrounds, including computer science, cognitive psychology, education, philosophy, linguistics, engineering, English, and biology.
____

TIP: Our "bottom-up" approach to forming research groups makes the IIS very accessible: if
you can find some like-minded people interested in your project, you can form a group.

Although the IIS maintains a strong tradition of bottom-up research, our recent
strategic plan adopted three focus areas:

- Language & Discourse
- Learning
- Artificial Intelligence

These focus areas represent the deepest areas of _current_ expertise at the IIS,
but they should not be regarded as an intention to exclude other areas of research or
limit what the IIS can become in the future.

=== A Short History of the IIS

The IIS was formed In 1985 as a result of informal meetings between
Dr. Stan Franklin (Computer Science), Dr. Art Graesser (Psychology),
and Dr. Terry Horgan (Philosophy), with Graesser and Franklin initially serving
as Co-Directors.
Dr. Don Franceschetti (Physics) developed a five-year plan
for the IIS which led to the recognition by the State of Tennessee of the IIS
as an Institute.
The Cognitive Science Seminar began in 1985 and continues to this day.

NOTE: The Cognitive Science Seminar has been in continuous operation since 1985.
It is now a cross-listed course with Psychology, Philosophy, and Computer Science.

In 1998, as a result of multiple major grants to faculty participating in the IIS,
the IIS received an operating budget of $25,000, 5% indirect cost recovery from grants,
and two staff positions that were both filled by 2000.

In 2003, the IIS moved to the FedEx Institute of Technology (FIT) and began hiring two
faculty with split appointments between the IIS and other departments.

Beginning in 2007, the IIS began hiring 100% faculty lines.
These lines are fully within the IIS but have tenure housed in other departments.
This development marked a number of administrative changes in the IIS as it
continued to grow into a mini-department.
An additional staff person was added to support grant submissions (i.e. pre-award support)
in recognition of the importance of grant funding to the IIS mission.

In 2010, the IIS was allocated 10 graduate assistantships, additional faculty lines,
additional staff, 20% indirect cost recovery, and the 4th floor of the FIT.
The IIS Student Organization (IISSO) was formed and tasked with managing student
travel awards.
The IIS added its first degree program, the Cognitive Science Graduate Certificate.

In 2014, the IIS launched a multi-year strategic planning process.
Many of the recommendations of the strategic planning process have already been
implemented, including a new undergraduate Minor in Cognitive Science.
However parts of the strategic plan will take years to unfold.

=== IIS Membership

For many years the IIS did not have a formal membership definition
footnote:[Stan Franklin had a retrospective method that calculated membership
based on participation over a period of time.
However this did not allow one to "sign up," which is a common attribute of memberships.].

Since 2008, the IIS has had a membership letter mechanism: faculty can join the
IIS as "IIS Affiliates" by signing the letter and returning it to the IIS Director.
The letter states what the Affiliate can expect from the IIS and vice versa.
In a nutshell, the IIS expects participation and, ultimately, grant activity that
funds IIS services.
In return the Affiliate has access to the various resources the IIS provides.

There is not a similar membership letter for students.
Students may join the IISSO according to the current policies and procedures of
that organization.
However, being a member of the IISSO does not automatically grant access to IIS
resources.
To access IIS resources, students must be "claimed" by an IIS Affiliate faculty
member as described later in this handbook.

=== Events

==== Research Meetings

Individual projects and labs schedule weekly meetings in 405 and 407 FIT,
 the IIS main meeting rooms.
Affiliates can book rooms with {book-rooms}.
 These meetings and descriptions are publicly posted to our website,
 and all IIS Affiliates and students are encouraged to drop in or participate
  in ongoing research meetings.
There are approximately 25 regularly scheduled research meetings per week for
externally funded projects.

==== Cognitive Science Seminar

The Cognitive Science Seminar is a hybrid course/public lecture.
Students who register for the course (COMP/PHIL/PSYC 7514/8514) attend a course-only
portion from 2:20pm to 4pm as well as a guest lecture portion, which is also
open to the public, from 4pm to 5:20pm.

The topic of the seminar varies semester by semester, as do the faculty leading it.
Faculty interested in leading the seminar are encouraged to contact the IIS Director.
The seminar provides an excellent venue for new faculty hires or IIS Affiliates to
engage other faculty and students in their research area, as well as cover hot
new emerging areas.

The IIS provides material and staff support for the seminar, currently {cogsci-funding}
for external speaker travel costs and support from {cogsci-travel} for travel arrangements.
This support also covers external speaker lunches with graduate students (arranged by IISSO)
and dinners with interested IIS Affiliates.

==== Guest Speakers

IIS Affiliates will often host visitors who are willing to give a talk to the
wider IIS community.
Although the IIS does not provide material support for such ad-hoc speakers, we
encourage Affiliates to make use of our meeting rooms and work with IIS staff to
promote the talk.

==== Speed Date

At the end of each semester (typically 4pm to 7pm the Friday before Study Day),
the IIS holds a Speed Date event in which 8-10 Affiliates give 5 minute
presentations of their current research interests.
The presentation portion is followed by a wine and cheese poster session,
organized by the IISSO, where students present their latest research.
Affiliates who wish to volunteer to speak at the Speed Date are always welcome to do so,
otherwise Affiliates are invited based on how much time has passed since their
last presentation, with priority given to Affiliates who recently joined.
