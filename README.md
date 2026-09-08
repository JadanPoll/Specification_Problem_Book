## Introduction
These past few years have seen the rapid proliferation of all sorts of datasets for every sort of human activity for fulfilling von Neumann's and Alan Turing's dreams. In fact, it was not so much they dreamed it than 
they firmly beleived it was so. For them, the notion of machines that think was an obvious thing to them and they had simply been born just a little ahead of that time. It took quite a bit longer than they estimated, 
necessitated by the need of datasets, the collection and creation of them, scraped together from the collective humanities works from all over the internet. 
In fact, so successful have these efforts been that man no longer doubt if machines can think in the sense of reaching their own sensibilites but how much further can they go in their thinking in assisting themselves 
in miracles of all sorts of activity. However in this technical project I am not concerned with if the machines can think but the inverse problem. The operator of those machines. 
I beleive that the fundamentally better the operator is, to whatever degree or domain of activity, the fundamentally more interesting activities they will be able to engage with these machines in. 
Hence the inverse task is not if a machine can be trained on a dataset but if a human at any degree of schooling could benefit from inverting the role and training themselves on datasets.

After all it is no secret that the biggest advancements to human civilization came in the form of inventions that gave a sort of persistence and democratization to thought. A short follow through 
would be papyrus, as developed from the reeds in Egypt to Project Gutenberg, the first printing machine. Then came academic publications, the establishment of publication megahouses and the internet which 
democraticed knowledge for all. However up to now its no secret that despite the wonderful happenings, it does take quite some effort for one to abreast themself of any domain. 
It still does take textbooks and quite a bit of patience and motivation to begin with. 
However, I beleive and hope to convince the reader that with datasets, one is able to reduce these inefficeints and frictions created by the own human effort. 
A far more effecient and persistent way of learning.


"""
Name: Problem Book Generator (PBG)
Specification: Problem Book generator from dataset
Hypothesis: One can create an extremely high quality problem book on the order of Polya, or Foveal Rea books simply for the wealth
of AI datasets

Let D_i be a dataset such that D_i is a csv(W.L.O.G of course, as it is trivial to extend D_i to other data formats) such that
D_i has for example the following columns of value. Question column, answer column(with thoughts and final answer), topic etc.
Now given we obviously dont know what the column would exactly be called we should have interface I so the user U can match 
and filter them correctly.

There are three kinds of semantic columns classes that are relevant to us, we will call this relevant set R, 
for now we define a conventient R such that R has for elements {Question/Problem, Solution, Topic}. There may be more valuable stuff that 
we discover should be in R later on, if that's the case, we will return and admit it as an element to R.

Given dataset D_i, for each of its matched columns, given out elements R we will have D_iq, D_is, D_it, for brevity, we will
now refer to D_i as the primary data set D. D can be one dataset or multiple datasets.

So now we can extract elements D_Q, D_S, D_T, because it is unlikely we would be so lucky as to ahve a D_t to generalize this
better we shall only concern ourselves with D_Q and D_S., of course this referes to the question set Q of D and solution set S of 
D.

For each element in Q


"""


"""
Name: On the Wikipedia
Specification: Proper problem topical classification
Elaboration: Here we concern ourselves with how one should get an automated machine to classify problem from
 natural language text correctly while address the multitudes of forseeable issues that come up
"""

"""
Name: PDF Creater (PDFc)
Specification: Outlining a good pdf
Hypothesis: There exists a way for a mechanical machine to design a pdf such that it is just as good as foveal rea's and szegbo's
given the method described in  PBG is sufficient.

First, we will consider the toy model of this hypothesis, it contains no image or complex stuff to render, we will simply concern
ourself with text.

Suppose one must design a problem book P, for the avid student S. It should be noted that in the interest of good design, when we 
refer to S, we should probably think about many students who we collectively refer to as S. This will help us better reason and constrain
the design of a good problem book

We need a lightweight set of libraries L, that allow us to triivally add content as well as latex/katex as there will likely be 
problems of that form. Due to the fragility of latex, we must specify entscheidungsproblem user function F_Latex, F_L for short
that allows the person running this machine to quickly look through all the identified latex renderings to certify it operated correctly,
not only rendered but rendered where it was supposed to.

For this we will break our problems into two halfs Q_T, and Q_L, which stand in for quality functions on the text and the latex

Concerning Q_T, we must avoid awkward page breaks. Latex interspersed with the text should not interfere with the normal rendering.
It should contain clickable links to jump to the topic quickly(reference PBG and other excerpts on this).

Concerning Q_L, part of this has already been address but this is the most sensitive part of the application to get right as
it is a key deciding factor in the quality of the problem book

"""

"""
Specification: A user interface so better high level decisions can be made according to taste
Hypothesis: There will be some pathological issues and ambiguity that will inevitably come up and require decisions 
from the human operator
"""







Of course, I will fail to one cannot write down every implementation detail beforehand. 
Rather, I attempt to slow myself down an pen my thoughts to demonstrate to myself sufficient understanding of the problem. One this has been done, implementation would simply be a matter of mechanical realization. If in writing up the program I discover some important part that was omitted or underspecified, I shall first try to justify it through the intents of the written up specification before addition.





Motivations
I suppose before one goes on about starting a project one must give clear motivating reasons why on its motivations, intent and perhaps most importantly what success would look like. This would help to direct energies where they need to be directed and preventadding on increasingly marvelous features that do no see their due sunlight of consistent use.


Reverse the AI motvation

A success would like like frequent use of the pdf, highlights. Particulalry one important thing is that its high quality enough that i come back to review previous work time and time again

Project Name: Problem Book Generator (PBG)
Specification: 
Hypothesis: One can create an extremely high quality problem book on the order of Polya, or Foveal Rea books simply from the wealth of the AI dataset.
Elaboration: I suppose a rigorous thing to do would be to discuss what my view of a good problem book with specific exemplary features in the scant few I've tried. Howwever, there may be not much time for that so this will be sparse. Will return with better justification later


Let $D_i$ be a dataset representing a finite collection of records over a set of columns $C_i$. W.L.O.G. we initially take $D_i$ to be a CSV dataset, as the representation format is not fundamental to the construction.
Let \\
$R = {Q, S , T}$
such that $D_i$  is a CSV. W.





## Index 
### A reference to established conventions is provided here for quick reference
