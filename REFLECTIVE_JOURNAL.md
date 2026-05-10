\# Reflective Journal, BOSC Community Library



\## A Week of Building Something Real



I want to be honest about how this project started. I knew what an open-source

repository was supposed to look like, I had seen GitHub profiles of serious

projects, read articles about contribution workflows, sat through lectures on

licensing. But knowing what something looks like from the outside and actually

building it are not the same experience. The gap between those two things is

what this week turned out to be about.



\---



\## Planning, or the Illusion of It



I started Day 1 with more confidence than I should have had. Setting up the

repository felt straightforward, folder structure, README, templates. But

the moment I tried to write the CONTRIBUTING.md with a tone that sounded like

a real maintainer rather than a student following a checklist, I understood

something I hadn't expected: the hardest part of an open-source project isn't

the code or the structure. It's the voice. Real projects have a voice. They

have a reason to exist that isn't "this is my assignment."



I had to find a reason this project existed before I could write about it

convincingly. And once I found it that students in places like where I study

genuinely don't have easy access to organized, free, beginner-friendly learning

materials the writing became easier. The project started to feel like mine

rather than a task I was completing.



\---



\## Governance Decisions I Didn't Expect to Matter



I made a rule for myself early: nothing goes directly to `main`. Every change

goes through a branch and a pull request, even working alone. I thought this

would feel mechanical. It didn't.



Working through branches forced me to think about changes as units of intent

rather than units of work. A branch isn't just "the thing I'm changing right

now" it's a defined purpose with a beginning, a middle, and a point where

it either merges or doesn't. That shift in thinking changed how I structured

my commits. Instead of saving when I'd done enough, I committed when I'd done

something specific. The difference sounds subtle. It isn't.



By Day 3, the commit history had started to tell a story. You could read it

top to bottom and understand not just what changed, but why, and in what order.

I hadn't planned for that. It happened because the process created the conditions

for it.



\---



\## The Collaboration Problem



Working alone on a project that is designed for collaboration creates a specific

kind of tension that I hadn't fully anticipated. When I opened issues, I was

both the person who discovered the problem and the person who would fix it.

When I wrote peer review comments on pull requests, I was commenting on my own

work from a different perspective.



I tried to take that seriously rather than treating it as a formality. When I

wrote a review comment suggesting that a changes to the low-bandwidth guide

should include a note about Anki setup, I wrote it as if I had genuinely just

noticed a gap because I had. The comment was real even if the reviewer was

me. That's the only way the simulation becomes useful rather than hollow.



What it taught me: good collaboration isn't really about having multiple people.

It's about creating the conditions for multiple perspectives on the same work.

The branch-issue-PR workflow does that, even for a single contributor, because

it creates natural pause points where you switch from maker to reviewer.



\---



\## The Hostile Fork Scenario



One of the questions I thought about during the licensing decision was what

would happen if someone took this repository and published it elsewhere under

a different name, without acknowledgment.



Under the MIT License, that is technically allowed. They would need to keep

the copyright notice but they could build a commercial product on top of

this work, charge for it, and never send anything back to this community.



I chose MIT anyway. Here is why.



If someone takes this content and reaches students who wouldn't otherwise

have found it even if they profit from doing so the students benefit.

The mission of the project is not to protect its own credit. It is to get

useful materials to people who need them. A restrictive license that

prevents commercial reuse might feel like it protects the community.

In practice, it often just limits reach.



The correct response to someone misusing the spirit of an open license

is not a legal one. It is a community one: maintain a better, more

trusted, more actively developed version. Open source wins through

quality and momentum, not through restriction.



\---



\## Documentation as Product



Somewhere around Day 2, I stopped thinking of the documentation files as

supporting material and started thinking of them as the actual product.



For a software library, the product is the code. For a resource library,

the product is the content. But in both cases, the documentation is what

determines whether anyone else can use it. A perfectly organized repository

with no explanation of how to contribute is as closed as one with no license.



The README is not a description of the project. It is the project's first

conversation with every person who arrives. Getting that right matters more

than getting any individual resource file right.



\---



\## What I Would Do Differently



I would establish file standards on Day 1. The metadata footer inconsistency

I fixed on Day 5 would have been a five-minute decision on Day 1 and a

three-hour refactoring pass later. I knew what kind of project I was building

from the start. I should have made the conventions explicit immediately.



I would also have written the RESOURCE\_HUB earlier. It should have been part

of the initial architecture, not something added in Day 4 as a feature. A

library without an index is a room of unsorted books. That should have been

obvious from the beginning.



\---



\## What Open Source Actually Means



I came into this project thinking open source was primarily about licenses

and public code. I'm finishing it thinking it is primarily about process

visibility.



What makes an open-source project trustworthy is not that anyone can read the

code. It is that anyone can read the decisions. The issues show what problems

were identified. The PRs show how they were addressed. The commit history shows

the order of thinking. The documentation shows what the community decided

to value.



That visibility is what separates a public repository from an open-source project.

I have a better understanding now of which one I was trying to build.



\---



\*Mwesigwa Josiah, May 2026\*

