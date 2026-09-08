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


## Establishing the value of a problem book
To my mind there are quite a few values of a problem book that make it the idea realization of this goal.

It is direct and effecient. The author doesnt have to profess and argument to claim to help you intriniscially understand. It is very binary, either you can solve a problem or you can't.
However the reesult of this binary is overwhelmingly benefiical and teaches all sorts of things. One can learn from the failure, one can learn from the question density, one improves from answer density.
One gets a sensible mind about what they know, don't know and their tacit limitations. Confidence gained etc.


Establish the value of a problem book, for example for me, it gives one the necessary fluidity to go on and solve much harder degree of problems and tasks
and read all sorts of papers for ones edifications. Also patches holes one isnt aware they have from a narrow, overly-optimized readding of the subject material.
One can make progress, see the progress and not be fooled into over estimating their abilites.
Allows for very rich though once one knows about what kind of problems are even possible, stretching one's mind. 



The next question in order of course is what would make a good problem book. I fear at this point I may be inadequate in answering that sufficiently since my own notion of what makes 
a good problem book changes over time. I used to think it should be hard, but that discourages much progress. But if its too easy one is bored and doesn't learn much but faster recognition.
One can say it has to be on the edge of one's abilites but one has all sorts of abilties and they aren't even evenly distributed by topic.
I will take the minimal invariant of these experiences and design around them, as I myself gain experience I will hopefully have some well estimated answer

1. It should be spatial. The user should be easily able to determine where to go and what to do.
2. Highlights and comments. The user should be able to evaluate their own progress. This for me comes in the form of highlghting.
3. Extra references, this allows targeted practice in a very singled out domain.
4. Index, this deeply reinforces 1, the user should extremely quickly be able to estimate what they don't know and what parts of the book to jump to, the user should
not be expected to follow it in order in the hopes of happening upon a problem of marginal interest. They should not even be expected to complete it in one sitting. It should
be such that whenver the user feels a weakness in a certain area they can quickly use the problem book as a reference to drill that specific thing. In that sense, it should be functional
to what the user happens to need to become stronger in, not necessarily the entire domain.
5. Completeness: This is the North star and ambitious goal of anything i beleive to be a good problem book. It itself should be a curriculm. That is, it isnt
impossible for one to learn the entire domain or sub-domain to practical ability simply with the book. The key is practical ability, I don't beleive one can establish the theoretical rigour
fro a problem book since its very statistically updating in ones abilites rather than thoroughly telling one about a subject. For example, in certain domains like proofs in mathematics, while
practice it ultimately the more valuable thing, the formalism and whys aren't easily learned through practice since solving a proof, even with lots of practice by no means confers on one the
efficient ability to write a proof. Often a problem book is itself most effecient when one has minimal contact with the domain of interest so they dont waste time and get discourage simply by the
unfamiliar laguage specific to that domain!





The specification is outline to accomplish three main things at this point, functional design, comfort of use and rigour of methodology. As of right now, I feel this split as an akward way to go about it 
since the project doesnt really work till you have all of the components as a whole
For each component I beleive should be tackled, i specify a hypothesis of what I beleive should be accomplished and then establish a 
specified way to go about it. The naming of course is for quick referencing. Because I believe one should keep a good hypothesis strong and short, for some of these components 
where I beleive necessary I elaborate on the motivation of the hypothesis itself to constrain our thinking on what we are going for and how to go about it.



### Functional design



Project Name: Problem Book Generator (PBG)
Specification: 
Hypothesis: One can create an extremely high quality problem book on the order of Polya, or Foveal Rea books simply from the wealth of the AI dataset.
Elaboration: I suppose a rigorous thing to do would be to discuss what my view of a good problem book with specific exemplary features in the scant few I've tried. Howwever, there may be not much time for that so this will be sparse. Will return with better justification later


Let $D_i$ be a dataset representing a finite collection of records over a set of columns $C_i$. W.L.O.G. we initially take $D_i$ to be a CSV dataset, as the representation format is not fundamental to the construction.
Let \\
$R = {Q, S , T}$
such that $D_i$  is a CSV. W.



#### Name: Problem Book Generator (PBG)
#### Specification: Problem Book generator from dataset
#### Hypothesis: One can create an extremely high quality problem book on the order of Polya, or Foveal Rea books simply for the wealth
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

# Rigour
"""
Name: On the Wikipedia.
A simple and clever way to determine topics for natural text. I have come to detest throwing AI and semantic relationship tools at everything, just because it can be done and its out there 
That's part of the reason for creating this specification. By taking the time to outline the clear motivations and what is necessary, one can come up with elegant solutions rather than throwing 
overly powerful but slower and unncessary solutions at the problem
Specification: Proper problem topical classification
Elaboration: Here we concern ourselves with how one should get an automated machine to classify problem from
 natural language text correctly while address the multitudes of forseeable issues that come up



"""

Name: On Filtering the noise
There are some 
To this extent I bleive its necessary to clue in the user to evaluate and remove the remaining noise. Our goal is not to be magical but to give a thorougly wholesome final product that the user might 
be sufficienty pleased with
There are two kinds of noise, numerical and text.
It has come to me that numerical noise should be normalized rather than simply occluded as it might itself contain valuable info such as matrices, partial differential equations etc. A possible problem is the messiness and 
varince of latex getting in the way of properly normalizing this noise. More on that later/

"""
Specification: A user interface so better high level decisions can be made according to taste
Hypothesis: There will be some pathological issues and ambiguity that will inevitably come up and require decisions 
from the human operator
"""

# Comfort of Use
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








Of course, I will fail to one cannot write down every implementation detail beforehand. 
Rather, I attempt to slow myself down an pen my thoughts to demonstrate to myself sufficient understanding of the problem. One this has been done, implementation would simply be a matter of mechanical realization. If in writing up the program I discover some important part that was omitted or underspecified, I shall first try to justify it through the intents of the written up specification before addition.





Motivations
I suppose before one goes on about starting a project one must give clear motivating reasons why on its motivations, intent and perhaps most importantly what success would look like. This would help to direct energies where they need to be directed and preventadding on increasingly marvelous features that do no see their due sunlight of consistent use.


Reverse the AI motvation

A success would like like frequent use of the pdf, highlights. Particulalry one important thing is that its high quality enough that i come back to review previous work time and time again





## Index 
### A reference to established conventions is provided here for quick reference
