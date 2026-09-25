## Introduction
<i>These past few years</i> have seen the rapid proliferation of datasets for all manner of human activity, fulfilling von Neumann's and Alan Turing's dreams that the mechanical mind can do the thinkable. 
In fact, it was not so much they dreamed it than they firmly believed it so. <i>For them</i>, the notion of machines that think was an obvious thing and thought if anything, they had simply been born just a little earlier than their time, but not by much earlier. 
It took quite a bit longer than they estimated, 
necessitated by the need of datasets, the collection and creation of them, scraped together from the collective works of man from all over the internet. 
In fact, so successful have these efforts been that man little doubts if machines can think as compared with their own thinking abilities but how much further can they go in their thinking, assisting man  
in all sorts of miraculous works.  
In this technical project however, I am not concerned with if the machines can think but ponder the inverse problem. The operator of those machines. 
The fundamentally better the operator is, to whatever degree or domain of activity, the fundamentally more interesting and ambitious of activities they will engage in with exciting machines.  

  
<i>For the inverse task</i>, one cares not that a machine can be trained on a dataset. Many readers are likely familiar of the story of Alex Krizhevsky, how as a mad scientist, he employed multiple NVIDIA GPUs to train the first critical neural network in his bedroom, doing what would take hours with comparable Intel tech in minutes. No, the new question is if a human at any degree of schooling could retreat to their solace for a weekend and benefit from inverting the role and training themselves on datasets.

<i>Forgive me for the brief historical aside</i>, but it is common to knowledge that the biggest advancements to human civilization came in the form of inventions that gave a sort of persistence, compilation, crystalization and democratization to thought. The progression of development from papyrus, born from the reeds in Egypt to Project Gutenberg, the first printing machine is enormously consequential in the development of our science, arts and literature. Then came academic publications, publication mega-houses for all manner of distributing journals of annals and compiled thought. Lastingly, we have the internet. These accelerated progressions democratized knowledge, both depth and unusual breadths for all. Despite these wondrous happenings, it really does take quite some effort for one to abreast themselves of any domain. Textbooks, the compressed supposedly effective default, take quite a bit of patience and motivation to begin with. 
By this work, I hope to convince the reader that through datasets, one is able to reduce these inefficiencies and frictions to the human effort of learning.  
In short, a demonstration of a far more efficient and persistent way of learning through automated generation of problem books and glossaries<bold>*</bold> is in order.

<sub> * It has occurred to me that in order to operate at an effective speed-of-thought, glossaries for jumping around subjects become a very ingenious necessity </sub>

## Establishing the value of a problem book
To my mind there are quite a few desirable values of a problem book that make it the ideal realization of this goal.

About the only thing I regard as potentially better in some sense is teaching.
Because while problem solving evaluates ones ability to recognize and apply ideas, teaching forces one to intrinsically understand ideas learned and flexibly 
remap its formulations in the effort of communcation. In how Richard Fenyman sees it. 
However one often doesn't teach what they don't know and because of this, the sense in which teaching might be potentially better is very limited

A. <i>It is direct and efficient</i>. It is about one of the only book titles that does precisely what it says it does, precisely much of the time.  
The author doesn't have to profess an argument to claim to help you intriniscially understand. Problem books are very binary, you either solve a problem or can't.  
However the reesult of this binary is overwhelmingly beneficial and teaches all sorts of things. One can learn from the failure, one can learn from the question density, one improves from answer density.
One gets a sensible mind about what they know, don't know and their tacit limitations. Confidence gained etc.

B. <i>It gives one the necessary fluidity and confidence to go on to solve much harder degree of problems and tasks.</i> Helps patch holes in understanding one isn't aware they have because of narrow and overly-optimized readings of subject materials.  
It can be unusually diverse, or unusually precise, or the answer unusually multi-layered or non-obvious. Like I said, you can either solve a problem or can't. One can make progress, see the progress and not be fooled into over-estimating one's abilities in a 
domain. A bit more unusually unique is that it allows for very rich thought once one knows about what kind of problems are even possible, stretching one's mind and flexibility of application. For me, it helps me read all sorts of scholarly works and papers for  edifications without getting bogged down by the mathematics or unfamiliarity with various ideas. 


The next question in order of course is what would make a good problem book. I fear at this point I am inadequate in answering that thoroughly since my own notion of what makes 
a good problem book changes over time. I used to think it should be hard, but then that discourages much progress, limits what one can learn and its applicabilities. But if its too easy one's mind is easily bored and doesn't learn much but faster recognition and
rote execution. Of course, for you these may be desirable. One can say it has to be on the edge of one's abilities but one comes with all sorts of abilities and they aren't even evenly distributed by topic.
I will take the minimal invariant of these experiences and design around them, as I myself gain experience I will eventually have some well estimated answer.  

A good problem book...
1. <i>Should be spatial</i>. The user should be easily able to determine where to go and what to do. Decide what is relevant and what is irrelevant to them. Discover where to bootstrap themselves and where to jump to challenge themselves decidedly. 
2. <i>Highlights and comments</i>. The user should be able to evaluate their own progress. This for me comes in the form of highlghting.
3. <i>Contains external references</i>. This allows for targeted practices and readings in a singular domain or sub-domains as well as more broad familiarization(like linking a topic to wikipedia or grokipedia)
4. <i>Indexes and glossaries</i>. This deeply reinforces spatial navigation mention earlier, the user should extremely quickly be able to estimate what they don't know and what parts of the book to jump to, the user should
not be expected to follow it in order in the hopes of happening upon a problem of marginal interest. They should not even be expected to complete it in one sitting. It should
be such that whenver the user feels a weakness in a certain area they can quickly use the problem book as a reference to drill that specific thing. In that sense, it should be functional
to what the user happens to need to become stronger in, not necessarily the entire domain.
5. <i>Endeavors to be topically complete</i>. This is the North star and ambitious goal of anything I beleive to be an unusually good problem book. It itself should be the curriculum. That is, it isn't
impossible for one to learn the entire domain or sub-domain to practical ability simply through thorough engagement with the book. Keyword is practical ability, I have not seen cause to believe it possible
for one to establish deep and fundamental the theoretical rigor solely from a pure problem book since its very statistically updating in ones abilites rather than thoroughly telling one about a subject.
For example, in certain domains like proofs in mathematics, while practice it ultimately the more valuable thing, the formalisms and whys aren't easily learned through practice since solving a proof, even with lots of practice by no means confers on one the
efficient ability to write a proof. Often a problem book is itself most efficient when one has at least minimal contact with the domain of interest so they don't waste time and get discouraged simply by the unfamiliar language specific to that domain!






The specification is outline to accomplish three things. Functional design, comfort of use and rigour of methodology. As of right now, I feel this split as an akward way to go about it 
since the project doesnt really work till you have all of the components as a whole
For each component I believe should be tackled, i specify a hypothesis of what I beleive should be accomplished and then establish a 
specified way to go about it. The naming of course is for quick referencing. Because I believe one should keep a good hypothesis strong and short, for some of these components 
where I believe necessary I elaborate on the motivation of the hypothesis itself to constrain our thinking on what we are going for and how to go about it.  




        

<b>Project Hypothesis: One can mechanically create a high quality problem book from a sufficiently rich dataset(s).</b>

### Functional design



Project Name: Problem Book Generator (PBG) 
Specification:  
Design Hypothesis: One can mechanically create a high quality prob create an extremely high quality problem book on the order of Polya, or Foveal Rea books simply from the wealth of the AI dataset. 
Elaboration: I suppose a rigorous thing to do would be to discuss what my view of a good problem book with specific exemplary features in the scant few I've tried. Howwever, there may be not much time for that so this will be sparse. Will return with better justification later





Name: Problem Book Generator (PBG) 
Specification: Problem Book generator from dataset 
Design Hypothesis: One can mechanically create an extremely high quality problem book on the order of Polya, or Foveal Rea books simply from the wealth meant for the training of AI.

Let $D_i$ be a dataset representing a finite collection of records over a set of columns $C_i$. W.L.O.G. we may initially take $D_i$ to be a CSV dataset, as the representation format is not fundamental to the construction.
Let \\
$R = {Q, S , T}$
such that $D_i$  is a CSV. W.

Let D_i be a dataset such that D_i is a csv(W.L.O.G of course, as it is trivial to extend D_i to other data formats) such that
D_i has for example the following columns of value. Question column, answer column(with thoughts and final answer), topic etc.
Now given we obviously dont know what the column would exactly be called we should have interface I so the user U can match 
and filter them correctly.

There are three kinds of semantic columns classes that are relevant to us, we will call this relevant set R, 
for now we define a conventient R such that R has for elements {Question/Problem, Solution, Topic}. There may be more valuable stuff that 
we discover should be in R later on, if that's the case, we will return and admit it as an element to R.




Given dataset D_i, for each of its matched columns, given out elements R we will have $D_iq$, $D_is$, $D_it$, for brevity, we will
now refer to $D_i$ as the primary data set $D$. $D$ can be one dataset or multiple datasets.

So now we can extract elements $D_Q$, $D_S$, $D_T$, because it is unlikely we would be so lucky as to have a D_t to generalize this
better we shall only concern ourselves with $D_Q$ and $D_S$., of course this referes to the question set $Q$ of $D$ and solution set $S$ of 
$D$.

For each element in Q



### Rigour


Name: On the Wikipedia.  
Design Hypothesis: One can use rich knowledge bases such as wikipedia to cheaply determine topics and sub-topics for natural language texts and problems.  
Elaboration: I am of the view that wikipedia serves a simple and clever way to determine topics for natural text. Bitter tastes dealing with time optimization in previous projects have made  
me rather disagreeable to throwing linear algebraic AI methods for semantic relationships at most problems, though I understand it is incredible popular and time-saving for critical thought to do so. This is in part the reason 
for making efforts to draft up a project specification. By taking the time to outline clear motivations and answer and exposit on what is necessary, one can come up with elegant well-reasoned solutions to problems.  
Here we concern ourselves with getting an automated machine assign admissible topics to problem texts as well as grouping them while address the multitudes of forseable issues that might come up.  

Suppose from $D$ we select a problem $Q_i$ and its answer $A_i$,


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

### Comfort of Use
Ask users how to make designs better and I imagine the recommendations usually suggest adding more fanciful gizmos and gadgets, or worse, not having enough variety in option or taste to know what better even looks like, much less that there is a better.
Because of this, over the course of working on projects I've come to develop a personal set of design principles to determine what a good UI would be for a product.
The first most effective design principle* is allowing users to operate at the speed of thought. Even if the UI may look ugly compared with all the fanciful decorations enabled out there with various LLM-assissted apps.
The second design principle of course is to get the user used to something less effective than the first.

<sub>* My first effective principle for *functional design* is that it should be useful enough that it causes repeated and enduring use. </sub>  



"""
Name: PDF Creater (PDFc)  
Specification: Outlining a good pdf  
Design Hypothesis: There exists a way for a mechanical machine to design a pdf such that it is just as good as foveal rea's and szegbo's
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
#### A reference to established conventions is provided here for quick reference
