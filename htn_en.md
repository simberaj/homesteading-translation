# Homesteading the Noosphere

Eric Steven Raymond, 2000

## An Introductory Contradiction

Anyone who watches the busy, tremendously productive world of Internet
open-source software for a while is bound to notice an interesting
contradiction between what open-source hackers say they believe and the way
they actually behave—between the official ideology of the open-source culture
and its actual practice.

Cultures are adaptive machines. The open-source culture is a response to an
identifiable set of drives and pressures. As usual, the culture's adaptation
to its circumstances manifests both as conscious ideology and as implicit,
unconscious or semi-conscious knowledge. And, as is not uncommon, the
unconscious adaptations are partly at odds with the conscious ideology.

In this essay, I will dig around the roots of that contradiction, and use it
to discover those drives and pressures. I will deduce some interesting things
about the hacker culture and its customs. I will conclude by suggesting ways
in which the culture's implicit knowledge can be leveraged better.

## The Varieties of Hacker Ideology

The ideology of the Internet open-source culture (what hackers say they
believe) is a fairly complex topic in itself. All members agree that open
source (that is, software that is freely redistributable and can readily
evolved and be modified to fit changing needs) is a good thing and worthy
of significant and collective effort. This agreement effectively defines
membership in the culture. However, the reasons individuals and various
subcultures give for this belief vary considerably.

One degree of variation is zealotry; whether open source development is
regarded merely as a convenient means to an end (good tools and fun toys
and an interesting game to play) or as an end in itself.

A person of great zeal might say "Free software is my life! I exist to
create useful, beautiful programs and information resources, and then give
them away." A person of moderate zeal might say "Open source is a good thing,
which I am willing to spend significant time helping happen." A person of
little zeal might say "Yes, open source is okay sometimes. I play with it
and respect people who build it."

Another degree of variation is in hostility to commercial software and/or the
companies perceived to dominate the commercial software market.

A very anticommercial person might say "Commercial software is theft and
hoarding. I write free software to end this evil." A moderately anticommercial
person might say "Commercial software in general is OK because programmers
deserve to get paid, but companies that coast on shoddy products and throw
their weight around are evil." An un-anticommercial person might say
"Commercial software is okay, I just use and/or write open-source software
because I like it better." (Nowadays, given the growth of the open-source part
of the industry since the first public version of this essay, one might also
hear "Commercial software is fine, as long as I get the source or it does
what I want it to do.")

All nine of the attitudes implied by the cross-product of the categories
mentioned earlier are represented in the open-source culture. It is worthwhile
to point out the distinctions because they imply different agendas, and
different adaptive and cooperative behaviors.

Historically, the most visible and best-organized part of the hacker culture
has been both very zealous and very anticommercial. The Free Software
Foundation founded by Richard M. Stallman (RMS) supported a great deal of
open-source development from the early 1980s forward, including tools like
Emacs and GCC which are still basic to the Internet open-source world, and
seem likely to remain so for the forseeable future.

For many years the FSF was the single most important focus of open-source
hacking, producing a huge number of tools still critical to the culture. The
FSF was also long the only sponsor of open source with an institutional
identity visible to outside observers of the hacker culture. They effectively
defined the term *free software*, deliberately giving it a confrontational
weight (which the newer label *open source* just as deliberately avoids).

Thus, perceptions of the hacker culture from both within and without it tended
to identify the culture with the FSF's zealous attitude and perceived
anticommercial aims. RMS himself denies he is anticommercial, but his program
has been so read by most people, including many of his most vocal partisans.
The FSF's vigorous and explicit drive to "Stamp Out Software Hoarding!"
became the closest thing to a hacker ideology, and RMS the closest thing to
a leader of the hacker culture.

The FSF's license terms, the *General Public License* (GPL), expresses the
FSF's attitudes. It is very widely used in the open-source world. North
Carolina's Metalab (formerly Sunsite) is the largest and most popular software
archive in the Linux world. In July 1997 about half the Sunsite software
packages with explicit license terms used GPL.

But the FSF was never the only game in town. There was always a quieter, less
confrontational and more market-friendly strain in the hacker culture. The
pragmatists were loyal not so much to an ideology as to a group of engineering
traditions founded on early open-source efforts which predated the FSF. These
traditions included, most importantly, the intertwined technical cultures of
Unix and the pre-commercial Internet.

The typical pragmatist attitude is only moderately anticommercial, and its
major grievance against the corporate world is not "hoarding" per se. Rather
it is that world's perverse refusal to adopt superior approaches incorporating
Unix and open standards and open-source software. If the pragmatist hates
anything, it is less likely to be "hoarders" in general than the current King
Log of the software establishment; formerly IBM, now Microsoft.

To pragmatists the GPL is important as a tool, rather than as an end in itself.
Its main value is not as a weapon against "hoarding", but as a tool for
encouraging software sharing and the growth of bazaar-mode
development communities. The pragmatist values having good tools and toys more
than he dislikes commercialism, and may use high-quality commercial software
without ideological discomfort. At the same time, his open-source experience
has taught him standards of technical quality that very little closed software
can meet.

For many years, the pragmatist point of view expressed itself within the hacker
culture mainly as a stubborn current of refusal to completely buy into the GPL
in particular or the FSF's agenda in general. Through the 1980s and early
1990s, this attitude tended to be associated with fans of Berkeley Unix, users
of the BSD license, and the early efforts to build open-source Unixes from the
BSD source base. These efforts, however, failed to build bazaar communities of
significant size, and became seriously fragmented and ineffective.

Not until the Linux explosion of early 1993–1994 did pragmatism find a real
power base. Although Linus Torvalds never made a point of opposing RMS, he set
an example by looking benignly on the growth of a commercial Linux industry,
by publicly endorsing the use of high-quality commercial software for specific
tasks, and by gently deriding the more purist and fanatical elements in the
culture.

A side effect of the rapid growth of Linux was the induction of a large number
of new hackers for which Linux was their primary loyalty and the FSF's agenda
primarily of historical interest. Though the newer wave of Linux hackers might
describe the system as "the choice of a GNU generation", most tended to
emulate Torvalds more than Stallman.

Increasingly it was the anticommercial purists who found themselves in a
minority. How much things had changed would not become apparent until the
Netscape announcement in February 1998 that it would distribute Navigator 5.0
in source. This excited more interest in *free software* within the corporate
world. The subsequent call to the hacker culture to exploit this unprecedented
opportunity and to re-label its product from *free software* to *open source*
was met with a level of instant approval that surprised everybody involved.

In a reinforcing development, the pragmatist part of the culture was itself
becoming polycentric by the mid-1990s. Other semi-independent communities with
their own self-consciousness and charismatic leaders began to bud from the
Unix/Internet root stock. Of these, the most important after Linux was the Perl
culture under Larry Wall. Smaller, but still significant, were the traditions
building up around John Osterhout's Tcl and Guido van Rossum's Python
languages. All three of these communities expressed their ideological
independence by devising their own, non-GPL licensing schemes.

## Promiscuous Theory, Puritan Practice

Through all these changes, nevertheless, there remained a broad consensus
theory of what "free software" or "open source" is. The clearest expression
of this common theory can be found in the various open-source licenses, all
of which have crucial common elements.

In 1997 these common elements were distilled into the Debian Free Software
Guidelines, which became the Open Source Definition. Under the guidelines
defined by the OSD, an open-source license must protect an unconditional right
of any party to modify (and redistribute modified versions of) open-source
software.

Thus, the implicit theory of the OSD (and OSD-conformant licenses such as the
GPL, the BSD license, and Perl's Artistic License) is that anyone can hack
anything. Nothing prevents half a dozen different people from taking any given
open-source product (such as, say the Free Software Foundations's gcc C
compiler), duplicating the sources, running off with them in different
evolutionary directions, but all claiming to be the product.

This kind of divergence is called a fork. The most important characteristic of
a fork is that it spawns competing projects that cannot later exchange code,
splitting the potential developer community. (There are phenomena that look
superficially like forking but are not, such as the proliferation of different
Linux distributions. In these pseudo-forking cases there may be separate
projects, but they use mostly common code and can benefit from each other's
development efforts completely enough that they are neither technically nor
sociologically a waste, and are not perceived as forks.)

The open-source licenses do nothing to restrain forking, let alone
pseudo-forking; in fact, one could argue that they implicitly encourage both.
In practice, however, pseudo-forking is common but forking almost never
happens. Splits in major projects have been rare, and are always accompanied
by re-labeling and a large volume of public self-justification. It is clear,
in such cases as the GNU Emacs/XEmacs split, or the gcc/egcs split, or the
various fissionings of the BSD splinter groups, that the splitters felt they
were going against a fairly powerful community norm [BSD].

In fact (and in contradiction to the anyone-can-hack-anything consensus theory)
the open-source culture has an elaborate but largely unadmitted set of
ownership customs. These customs regulate who can modify software, the
circumstances under which it can be modified, and (especially) who has the
right to redistribute modified versions back to the community.

The taboos of a culture throw its norms into sharp relief. Therefore, it will
be useful later on if we summarize some important ones here:

- There is strong social pressure against forking projects. It does not happen
  except under plea of dire necessity, with much public self-justification, and
  requires a renaming.
- Distributing changes to a project without the cooperation of the moderators
  is frowned upon, except in special cases like essentially trivial porting
  fixes.
- Removing a person's name from a project history, credits, or maintainer list
  is absolutely not done without the person's explicit consent.

In the remainder of this essay, we shall examine these taboos and ownership
customs in detail. We shall inquire not only into how they function but what
they reveal about the underlying social dynamics and incentive structures of
the open-source community.

## Ownership and Open Source

What does "ownership" mean when property is infinitely reduplicable, highly
malleable, and the surrounding culture has neither coercive power relationships
nor material scarcity economics?

Actually, in the case of the open-source culture this is an easy question to
answer. The owner of a software project is the person who has the exclusive
right, recognized by the community at large, to distribute modified versions.

(In discussing "ownership" in this section I will use the singular, as though
all projects are owned by some one person. It should be understood, however,
that projects may be owned by groups. We shall examine the internal dynamics
of such groups later on.)

According to the standard open-source licenses, all parties are equals in the
evolutionary game. But in practice there is a very well-recognized distinction
between "official" patches, approved and integrated into the evolving software
by the publicly recognized maintainers, and "rogue" patches by third parties.
Rogue patches are unusual, and generally not trusted [RP].

That public redistribution is the fundamental issue is easy to establish.
Custom encourages people to patch software for personal use when necessary.
Custom is indifferent to people who redistribute modified versions within a
closed user or development group. It is only when modifications are posted to
the open-source community in general, to compete with the original, that
ownership becomes an issue.

There are, in general, three ways to acquire ownership of an open-source
project. One, the most obvious, is to found the project. When a project has
had only one maintainer since its inception and the maintainer is still active,
custom does not even permit a question as to who owns the project.

The second way is to have ownership of the project handed to you by the
previous owner (this is sometimes known as `passing the baton'). It is well
understood in the community that project owners have a duty to pass projects
to competent successors when they are no longer willing or able to invest
needed time in development or maintenance work.

It is significant that in the case of major projects, such transfers of
control are generally announced with some fanfare. While it is unheard of
for the open-source community at large to actually interfere in the owner's
choice of succession, customary practice clearly incorporates a premise that
public legitimacy is important.

For minor projects, it is generally sufficient for a change history included
with the project distribution to note the change of ownership. The clear
presumption is that if the former owner has not in fact voluntarily transferred
control, he or she may reassert control with community backing by objecting
publicly within a reasonable period of time.

The third way to acquire ownership of a project is to observe that it needs
work and the owner has disappeared or lost interest. If you want to do this,
it is your responsibility to make the effort to find the owner. If you don't
succeed, then you may announce in a relevant place (such as a Usenet newsgroup
dedicated to the application area) that the project appears to be orphaned, and
that you are considering taking responsibility for it.

Custom demands that you allow some time to pass before following up with an
announcement that you have declared yourself the new owner. In this interval,
if someone else announces that they have been actually working on the project,
their claim trumps yours. It is considered good form to give public notice of
your intentions more than once. You get more points for good form if you
announce in many relevant forums (related newsgroups, mailing lists), and
still more if you show patience in waiting for replies. In general, the more
visible effort you make to allow the previous owner or other claimants to
respond, the better your claim if no response is forthcoming.

If you have gone through this process in sight of the project's user community,
and there are no objections, then you may claim ownership of the orphaned
project and so note in its history file. This, however, is less secure than
being passed the baton, and you cannot expect to be considered fully legitimate
until you have made substantial improvements in the sight of the user
community.

I have observed these customs in action for 20 years, going back to the pre-FSF
ancient history of open-source software. They have several very interesting
features. One of the most interesting is that most hackers have followed them
without being fully aware of doing so. Indeed, this may be the first conscious
and reasonably complete summary ever to have been written down.

Another is that, for unconscious customs, they have been followed with
remarkable (even astonishing) consistency. I have observed the evolution of
literally hundreds of open-source projects, and I can still count the number
of significant violations I have observed or heard about on my fingers.

Yet a third interesting feature is that as these customs have evolved over
time, they have done so in a consistent direction. That direction has been to
encourage more public accountability, more public notice, and more care about
preserving the credits and change histories of projects in ways that (among
other things) establish the legitimacy of the present owners.

These features suggest that the customs are not accidental, but are products of
some kind of implicit agenda or generative pattern in the open-source culture
that is utterly fundamental to the way it operates.

An early respondent pointed out that contrasting the Internet hacker culture
with the cracker/pirate culture (the "warez d00dz" centered around
game-cracking and pirate bulletin-board systems) illuminates the generative
patterns of both rather well. We'll return to the d00dz for contrast later
in this essay.


## Locke and Land Title

To understand this generative pattern, it helps to notice a historical analogy
for these customs that is far outside the domain of hackers' usual concerns.
As students of legal history and political philosophy may recognize, the theory
of property they imply is virtually identical to the Anglo-American common-law
theory of land tenure!

In this theory, there are three ways to acquire ownership of land:

- On a frontier, where land exists that has never had an owner, one can acquire
  ownership by homesteading, mixing one's labor with the unowned land, fencing
  it, and defending one's title.

- The usual means of transfer in settled areas is transfer of title—that is,
  receiving the deed from the previous owner. In this theory, the concept of
  *chain of title* is important. The ideal proof of ownership is a chain of
  deeds and transfers extending back to when the land was originally
  homesteaded.

- Finally, the common-law theory recognizes that land title may be lost or
  abandoned (for example, if the owner dies without heirs, or the records
  needed to establish chain of title to vacant land are gone). A piece of land
  that has become derelict in this way may be claimed by adverse possession -
  one moves in, improves it, and defends title as if homesteading.

This theory, like hacker customs, evolved organically in a context where
central authority was weak or nonexistent. It developed over a period of
a thousand years from Norse and Germanic tribal law. Because it was
systematized and rationalized in the early modern era by the English political
philosopher John Locke, it is sometimes referred to as the Lockean theory of
property.

Logically similar theories have tended to evolve wherever property has high
economic or survival value and no single authority is powerful enough to force
central allocation of scarce goods. This is true even in the hunter-gatherer
cultures that are sometimes romantically thought to have no concept
of "property". For example, in the traditions of the !Kung San bushmen
of the Kgalagadi (formerly *Kalahari*) Desert, there is no ownership of hunting
grounds. But there is ownership of waterholes and springs under a theory
recognizably akin to Locke's.

The !Kung San example is instructive, because it shows that Lockean property
customs arise only where the expected return from the resource exceeds the
expected cost of defending it. Hunting grounds are not property because the
return from hunting is highly unpredictable and variable, and (although highly
prized) not a necessity for day-to-day survival. Waterholes, on the other hand,
are vital to survival and small enough to defend.

The *noosphere* of this essay's title is the territory of ideas, the space of
all possible thoughts [N]. What we see implied in hacker ownership customs is
a Lockean theory of property rights in one subset of the noosphere, the space
of all programs. Hence *homesteading the noosphere*, which is what every
founder of a new open-source project does.

Faré Rideau <fare@tunes.org> correctly points out that hackers do not exactly
operate in the territory of pure ideas. He asserts that what hackers own is
programming projects—intensional focus points of material labor (development,
service, etc), to which are associated things like reputation, trustworthiness,
etc. He therefore asserts that the space spanned by hacker projects, is not the
noosphere but a sort of dual of it, the space of noosphere-exploring program
projects. (With an apologetic nod to the astrophysicists out there, it would
be etymologically correct to call this dual space the *ergosphere* or
"sphere of work".)

In practice, the distinction between noosphere and ergosphere is not important
for the purposes of our present argument. It is dubious whether the *noosphere*
in the pure sense on which Faré insists can be said to exist in any meaningful
way; one would almost have to be a Platonic philosopher to believe in it. And
the distinction between noosphere and ergosphere is only of practical
importance if one wishes to assert that ideas (the elements of the noosphere)
cannot be owned, but their instantiations as projects can. This question leads
to issues in the theory of intellectual property which are beyond the scope
of this essay (but see [DF]).

To avoid confusion, however, it is important to note that neither the noosphere
nor the ergosphere is the same as the totality of virtual locations
in electronic media that is sometimes (to the disgust of most hackers)
called *cyberspace*. Property there is regulated by completely different rules
that are closer to those of the material substratum - essentially, he who owns
the media and machines on which a part of *cyberspace* is hosted owns that
piece of cyberspace as a result.

The Lockean logic of custom suggests strongly that open-source hackers observe
the customs they do in order to defend some kind of expected return from their
effort. The return must be more significant than the effort of homesteading
projects, the cost of maintaining version histories that document
*chain of title*, and the time cost of making public notifications and waiting
before taking adverse possession of an orphaned project.

Furthermore, the "yield" from open source must be something more than simply
the use of the software, something else that would be compromised or diluted
by forking. If use were the only issue, there would be no taboo against
forking, and open-source ownership would not resemble land tenure at all.
In fact, this alternate world (where use is the only yield, and forking is
unproblematic) is the one implied by existing open-source licenses.

We can eliminate some candidate kinds of yield right away. Because you can't
coerce effectively over a network connection, seeking power is right out.
Likewise, the open-source culture doesn't have anything much resembling money
or an internal scarcity economy, so hackers cannot be pursuing anything very
closely analogous to material wealth (e.g. the accumulation of scarcity
tokens).

There is one way that open-source activity can help people become wealthier,
however - a way that provides a valuable clue to what actually motivates it.
Occasionally, the reputation one gains in the hacker culture can spill over
into the real world in economically significant ways. It can get you a better
job offer, or a consulting contract, or a book deal.

This kind of side effect, however, is at best rare and marginal for most
hackers; far too much so to make it convincing as a sole explanation, even
if we ignore the repeated protestations by hackers that they're doing what
they do not for money but out of idealism or love.

However, the way such economic side effects are mediated is worth examination.
Next we'll see that an understanding of the dynamics of reputation within
the open-source culture itself has considerable explanatory power.

