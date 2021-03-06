---
title: "Introduction"
date: 2018-04-06T23:23:16+02:00
draft: true
---

Chapter 1

# Introduction: A Programmable Web

If you are like most people I know (and, since you’re reading this book, you probably
are — at least in this respect), you use the Web. A lot. In fact, in my own personal
case, the vast majority of my days are spent reading or scanning web pages — a scroll
through my webmail client to talk with friends and colleagues, a weblog or two to
catch up on the news of the day, a dozen short articles, a flotilla of Google queries,
and the constant turn to Wikipedia for a stray fact to answer a nagging question.

All fine and good, of course; indeed, nigh indispensable. And yet, it is sobering
to think that little over a decade ago none of this existed. Email had its own
specialized applications, weblogs had yet to be invented, articles were found on
paper, Google was yet unborn, and Wikipedia not even a distant twinkle in Larry
Sanger’s eye.

And so, it is striking to consider — almost shocking, in fact — what the world
might be like when our software turns to the Web just as frequently and casually as
we do.Today, of course, we can see the faint, future glimmers of such a world.There
is software that phones home to find out if there’s an update.There is software where
part of its content — the help pages, perhaps, or some kind of catalog — is streamed
over the Web. There is software that sends a copy of all your work to be stored on
the Web. There is software specially designed to help you navigate a certain kind of
web page. There is software that consists of nothing but a certain kind of web page.
There is software — the so-called “mashups” — that consists of a web page combining
information from two other web pages. And there is software that, using “APIs,”
treats other web sites as just another part of the software infrastructure, another
function it can call to get things done.

Our computers are so small and the Web so great and vast that this last scenario
seems like part of an inescapable trend. Why wouldn’t you depend on other
web sites whenever you could, making their endless information and bountiful abilities
a seamless part of yours? And so, I suspect, such uses will become increasingly
common until, one day, your computer is as tethered to the Web as you yourself are
now.

It is sometimes suggested that such a future is impossible, that making a Web
that other computers could use is the fantasy of some (rather unimaginative, I would
think) sci-fi novelist.That it would only happen in a world of lumbering robots and
artificial intelligence and machines that follow you around, barking orders while
intermittently unsuccessfully attempting to persuade you to purchase a new pair of
shoes.

So it is perhaps unsurprising that one of the critics who has expressed something
like this view, Cory Doctorow, is in fact a rather imaginative sci-fi novelist
(amongst much else). Doctorow’s complaint is expressed in his essay “Metacrap:
Putting the torch to seven straw-men of the meta-utopia.” (Available online at http://www.well.com/˜doctorow/metacrap.htm) It is also reprinted in
his book of essays _Content: Selected Essays on Technology, Creativity, Copyright, and
the Future of the Future_ (2008, Tachyon Publications) which is likewise available
online at http://craphound.com/content/download/.

Doctorow argues that any system collect accurate “metadata” — the kind of
machine-processable data that will be needed to make this dream of computersusing-the-Web
come true — will run into seven inescapable problems: people lie,
people are lazy, people are stupid, people don’t know themselves, schemas aren’t
neutral, metrics influence results, and there’s more than one way to describe something.
Instead, Doctorow proposes that instead of trying to get people to provide
data, we should instead look at the data they produce incidentally while doing other
things (like how Google looks at the links people make when they write web pages)
and use that instead.

Doctorow is, of course, attacking a strawman. Utopian fantasies of honest,
complete, unbiased data about everything are obviously impossible. But who
was trying for that anyway? The Web is rarely perfectly honest, complete, and
unbiased — but it’s still pretty damn useful. There’s no reason making a Web for
computers to use can’t be the same way.

I have to say, however, the idea’s proponents do not escape culpability for these
utopian perceptions. Many of them have gone around talking about the “Semantic
Web” in which our computers would finally be capable of “machine understanding”.
Such a framing (among other factors) has attracted refugees from the struggling
world of artificial intelligence, who have taken it as another opportunity to promote
their life’s work.

Instead of the “let’s just build something that works” attitude that made
the Web (and the Internet) such a roaring success, they brought the formalizing
mindset of mathematicians and the institutional structures of academics and defense
contractors. They formed committees to form working groups to write drafts of
ontologies that carefully listed (in 100-page Word documents) all possible things
in the universe and the various properties they could have, and they spent hours
in Talmudic debates over whether a washing machine was a kitchen appliance or a
household cleaning device.

With them has come academic research and government grants and corporate
R&D and the whole apparatus of people and institutions that scream “pipedream”.
And instead of spending time building things, they’ve convinced people interested
in these ideas that the first thing we need to do is write standards. (To engineers, this
is absurd from the start — standards are things you write after you’ve got something
working, not before!)

And so the “Semantic Web Activity” at the Worldwide Web Consortium
(W3C) has spent its time writing standard upon standard: the Extensible Markup
Language (XML), the Resource Description Framework (RDF), the Web Ontology
Language (OWL), tools for Gleaning Resource Descriptions from Dialects
of Languages (GRDDL), the Simple Protocol And RDF Query Language
(SPARQL) (as created by the RDF Data Access Working Group (DAWG)).

Few have received any widespread use and those that have (XML) are uniformly
scourges on the planet, offenses against hardworking programmers that have
pushed out sensible formats (like JSON) in favor of overly-complicated hairballs
with no basis in reality (I’m not done yet! — more on this in chapter 5).

Instead of getting existing systems to talk to each other and writing up the
best practices, these self-appointed guarantors of the Semantic Web have spent their
time creating their own little universe, complete with Semantic Web databases and
programming languages. But databases and programming languages, while far from
perfect, are largely solved problems. People already have their favorites, which have
been tested and hacked to work in all sorts of unusual environments, and folks are
not particularly inclined to learn a new one, especially for no good reason. It’s hard
enough getting people to share data as it is, harder to get them to share it in a
particular format, and completely impossible to get them to store it and manage it
in a completely new system.

And yet this is what Semantic Webheads are spending their time on. It’s
as if to get people to use the Web, they started writing a new operating system
that had the Web built-in right at the core. Sure, we might end up there someday,
but insisting that people do that from the start would have doomed the Web to
obscurity from the beginning.

All of which has led “web engineers” (as this series’ title so cutely calls them)
to tune out and go back to doing real work, not wanting to waste their time with
things that don’t exist and, in all likelihood, never will. And it’s led many who
have been working on the Semantic Web, in the vain hope of actually building a
world where software can communicate, to burnout and tune out and find more
productive avenues for their attentions.

For an example, look at Sean B. Palmer. In his influential piece, “Ditching
the Semantic Web?”, (Available online at http://inamidst.com/whits/2008/ditching.) he proclaims “It’s not prudent, perhaps even not moral (if
that doesn’t sound too melodramatic), to work on RDF, OWL, SPARQL, RIF, the
broken ideas of distributed trust, CWM, Tabulator, Dublin Core, FOAF, SIOC,
and any of these kinds of things” and says not only will he “stop working on the
Semantic Web” but “I will, moreover, actively dissuade anyone from working on the
Semantic Web where it distracts them from working on” more practical projects.

It would be only fair here to point out that I am not exactly an unbiased
observer. For one thing, Sean, like just about everyone else I cite in the book, is a
friend. We met through working on these things together but since have kept in
touch and share emails about what we’re working on and are just generally nice to
each other. And the same goes for almost all the other people I cite and criticize.

Moreover, the reason we were working together is that I too did my time in
the Semantic Web salt mines. My first web application was a collaboratively-written
encyclopedia, but my second, aggregated news headlines from sites around the Web,
led me into a downward spiral that ended with many years spent on RDF Core
Working Groups and an ultimate decision to get out of the world of computers
altogether.

Obviously, that didn’t work out quite as planned. Jim Hendler, another friend
and one of the AI transplants I’ve just spend so much time taking a swing at, asked
me if I’d write a bit on the subject to kick off a new series of electronic books he’s
putting together. I’ll do just about anything for a little cash (just kidding; I just
wanted to get published (just kidding; I’ve been published plenty of times times
(just kidding; not that many times (just kidding; I’ve never been published (just
kidding; I have, but I just wanted more practice (just kidding; I practice plenty (just
kidding; I never practice (just kidding; I just wanted to publish a book (just kidding;
I just wanted to write a book (just kidding; it’s easy to write a book (just kidding; it’s
a death march (just kidding; it’s not so bad (just kidding; my girlfriend left me (just
kidding; I left her (just kidding, just kidding, just kidding))))))))))))))) and so here
I am again, rehashing all the old ground and finally getting my chance to complain
about what a mistake all the Semantic Web folks have made.

Yet, as my little thought experiment above has hopefully made clear, the
programmable web is anything but a pipe dream — it is today’s reality and tomorrow’s
banality. No software developer will remain content to limit themselves only to
things on the user’s own computer. And no web site developer will be content to
limit their site only to users who act with it directly.

Just as the interlinking power of the World Wide Web sucked all available
documents into its maw — encouraging people to digitize them, convert them into
HTML, give them a URL, and put them on the Internet (hell,as we speak Google is
even doing this to entire libraries) — the programmable Web will pull all applications
within its grasp.The benefits that come from being connected are just too powerful
to ultimately resist.

They will, of course, be granted challenges to business models — as new technologies
always are — especially for those who make their money off of gating up and
charging access to data. But such practices simply aren’t tenable in the long term,
legally or practically (let alone morally). Under US law, facts aren’t copyrightable
(thanks to the landmark Supreme Court decision in Feist v. RuralTelephone Service)
and databases are just collections of facts. (Some European countries have special
database rights, but such extensions have been fervently opposed in the US.)

But even if the law didn’t get in the way, there’s so much value in sharing data
that most data providers will eventually come around. Sure, providing a website
where people can look things up can be plenty valuable, but it’s nothing compared
to what you can do when you combine that information with others.

To take an example from my own career, look at the website OpenSecrets.org.
It collects information about who’s contributing money to US political candidates
and displays nice charts and tables about the industries that have funded the campaigns
of presidential candidates and members of Congress.

Similarly, the website Taxpayer.net provides a wealth of information about
Congressional earmarks — the funding requests that members of Congress slip into
bills, requiring a couple million dollars be given to someone for a particular pet
project. (The $398 million “Bridge to Nowhere” being the most famous example.)

Both are fantastic sites and are frequently used by observers of American
politics, to good effect. But imagine how much better they would be if you put them
together — you could search for major campaign contributors who had received large
earmarks.

Note that this isn’t the kind of “mashup” that can be achieved with today’s
APIs. APIs only let you look at the data in a particular way, typically the way that
the hosting site looks at it. So with OpenSecrets’ API you can get a list of the top
contributors to a candidate. But this isn’t enough for the kind of question we’re
interested in — you’d need to compare each earmark against each donor to see if
they match. It requires real access to the data.

Note also that the end result is ultimately in everyone’s best interest. OpenSecrets.org
wants people to find out about the problematic influence of money in
politics. Taxpayer.net wants to draw attention to this wasteful spending.The public
wants to know how money in politics causes wasteful spending and a site that helps
them do so would further each organization’s goals. But they can only get there if
they’re willing to share their data.

Fortunately for us, the Web was designed with this future in mind. The
protocols that underpin it are not designed simply to provide pages for human
consumption, but also to easily accommodate the menagerie of spiders, bots, and
scripts that explore its fertile soil. And the original developers of the Web, the men
and women who invented the tools that made it the life-consuming pastime that
it is today, have long since turned their sights towards making the Web safe, even
inviting, for applications.

Unfortunately, far too few are aware of this fact, leading many to reinvent — 
sloppily — the work that they have already done. (It hasn’t helped that the few who
are aware have spent their time working on the Semantic Web nonsense that I
criticized above.) So we will begin by trying to understand the architecture of the
Web — what it got right and, occasionally, what it got wrong, but most importantly
why it is the way it is. We will learn how it allows both users and search engines
to co-exist peacefully while supporting everything from photo-sharing to financial
transactions.

We will continue by considering what it means to build a program on top of
the Web — how to write software that both fairly serves its immediate users as well
as the developers who want to build on top of it. Too often, an API is bolted on top
of an existing application, as an afterthought or a completely separate piece. But,
as we’ll see, when a web application is designed properly, APIs naturally grow out
of it and require little effort to maintain.

Then we’ll look into what it means for your application to be not just another
tool for people and software to use, but part of the ecology — a section of the
programmable web. This means exposing your data to be queried and copied and
integrated, even without explicit permission, into the larger software ecosystem,
while protecting users’ freedom.

Finally, we’ll close with a discussion of that much-maligned phrase, “the
Semantic Web,” and try to understand what it would really mean.

Let’s begin.
