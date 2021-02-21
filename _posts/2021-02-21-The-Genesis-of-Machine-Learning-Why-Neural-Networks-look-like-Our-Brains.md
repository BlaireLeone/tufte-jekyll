---
layout: post
title:  "The Genesis of Machine Learning: Why Neural Networks look like Our Brains"
date:   2020-02-21 08:46:04
categories: jekyll css
---

{% newthought 'Machine Learning' %} is pretty wild, and here is why your brain is literally a machine.

**Biomimicry: From Brains to Machines**

Computers were originally designed to solve complex rote problems; an algorithm would follow a formulaic structure to synthesize and calculate copious amounts of data before solving for a given output. These were generally time consuming, but not altogether unusual, for a human to complete. Nonetheless, computers came to replace many of the mathematicians who tediously plodded through equation after equation, with the possibility of starting from scratch from a single misplaced decimal point. Hidden Figures, a biography of early NASA engineers[[1\]](#_ftn1), showcases some of the human side of this work through the [efforts of women](https://www.thehumancomputerproject.com/women) dedicated to calculating most of the behind the scenes engineering problems of early space travel. These women were, in fact, called computers! Now, however, that work is solved by computers of a less biological nature. 

Artificial intelligence (AI) became the natural progeny of this original computer when humans saw the potential for it to “[think](https://www.deeplearningbook.org/contents/intro.html)” for itself. If a computer can calculate all that information on its own (albeit after having been programmed by a human who continues to monitor its progress), why shouldn’t a computer make its own decisions? And what better framework than the human brain? 

It's not difficult to understand the comparison the between human cognition and computational “thinking”. After all, many machines learn in much the same way we do – hence the anthropomorphized terms of artificial *intelligence* and machine *learning*. And like their mechanical compatriots, brains are complex, but relatively predictable, and more than that, they involve a system of inputs and outputs.

Today, machine learning (ML), [a subfield of artificial intelligence](https://medium.com/swlh/deep-learning-101-artificial-intelligence-and-machine-learning-basics-5687a75212e3), has become in itself a [broad field](https://machinelearningmastery.com/types-of-learning-in-machine-learning/), with different models for different learning approaches, which are subsequently built to synthesize and analyze data differently. We have also progressed so far into the AI discipline, that for the most part ML models have dropped the brain-framed training wheels and have taken on a life of their own that no longer mimic brain functions, or at least not to the same extent. 

In the interest of comparing brain processes with ML, I will reduce our brains' processing down to a logical structure, promoted by [cognitive scientists](https://plato.stanford.edu/entries/cognitive-science/)[[2\]](#_ftn2) in illustrating cognition via [connectionism](https://plato.stanford.edu/entries/connectionism/). This will in no way represent all actions or decision-making but will explain the theory behind basic processes. For this same reason, I will stick to explaining a *neural network*, which is the ML model that finds its deepest roots in biological processes. In fact, originally known as an *artificial* neural network, this model takes its name from its ‘predecessor’, *biological* neural networks. As they have grown in societal ubiquity (from [handwriting recognition](https://www.ijedr.org/papers/IJEDR1704192.pdf) to [self-driving vehicles](https://arxiv.org/pdf/1708.08559.pdf)), we have since dropped ‘artificial’ and ‘biological’ to make simply *neural networks*. 

**So how are neural networks like neural networks? Or in other words, how is a brain like a machine?**

Our brains are comprised of billions of neurons. These are interconnected in a variety of unique ways with potentially unlimited connections. Unlike popular belief, the brain is not one big ball of neurons; instead, it has architectural symmetry and finely engineered spaces and corridors. 

In describing the brain, I’ll begin at one of the smallest units – a neuron. A neuron is essentially a relay station, set within an infinite chain of relay stations, receiving and sending forth information in the form of electrochemical signals. Each neuron has a cell body, with upwards of dozens of little tendrils shooting out called *dendrites*. One of these tendrils is much longer than the r rest and is in fact something else altogether - the *axon*. And at the end of the axon are dozens of *synapses*, which could be thought of as a pitching machine at a batting cage.  When a signal is fired, electricity received from neighboring neurons gathers in the cell body. Once enough signals have accumulated up to a certain threshold, the cell body fires an electrochemical pulse down the axon, which will in turn be rapid fire released through the synapses to neighboring cell’s dendrites which must grab them as if catching a baseball. Once those dendrites receive enough signals to pass the electrochemical threshold, they will fire an accompanying pulse down that axon. This happens instantaneously and in perpetuity through millions of other neurons until the signal reaches it goal. 

 ![image-20210220113116249](C:\Users\bleoh\AppData\Roaming\Typora\typora-user-images\image-20210220113116249.png)

​                               

When our brain is processing (thinking, remembering, reading, sensing etc.), these signals follow specialized neural pathways that are equipped to send a particular kind of information. For instance, when viewing an object, the image that appears in our eyes is deconstructed into basic info (color, shape, shading, perspective etc.) and sent to the *back* of our brains to the occipital lobe via [the Lateral Geniculate Nucleus (LGN)](https://www.ncbi.nlm.nih.gov/books/NBK482504/).[[3\]](#_ftn3) One could say that the neurons in this channel were trained to recognize and relay only visual info, as they connect to parts of the brain designed to process visual stimuli – the eyes and the occipital lobe. 

![](C:\Users\bleoh\Downloads\1200px-Human_visual_pathway.svg.png)

The occipital lobe then processes the images and sends them to other parts of our brain for further analysis. If it’s a growling dog, that information may be disseminated [through the amygdala](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3025529/), via various other lobes and channels, which will kick in a fight/flight reaction, which will engage our autonomic nervous system (ANS), which may cause us to run in a panic. This takes place in milliseconds. 

![ML flow chart 4](C:\Users\bleoh\Pictures\ML flow chart 4.png)

As a side note, stimuli, here, does not just refer to visual information. It could be somatosensory, as when touching a hot stove. It could be auditory, as when identifying a piece of music, or olfactory as when inhaling freshly made cinnamon buns. All of these coalesce into the representations in our minds that influence the decisions we make.[[4\]](#_ftn4)

**Sounds Assembly Line-ish**

This explanation is vastly oversimplified (and for this example in particular, actually skips a few steps), but it may sound like another familiar historically-relevant process – *assembly lines*, in which we see a step-by-step process that accumulates into a final product. We could say that each neuron represents a person with a specialty or task, each lobe or section of our brains represents a department, and between those is a conveyor belt that streamlines the packaged information from group to group. In other words, it has a linear orientation with one direction that starts and stops at the same place every time. 

In this way, we may prefer BF Skinner’s perspective[[5\]](#_ftn5), in that our brains are a "black box". We can’t examine the internal workings; we can only monitor what comes out as a response to what goes in. Thus, one or multiple things is fed into one side of the box and something else entirely emerges on the other side. Likewise, at each destination in an assembly line, another part is added until a whole is complete. 

**But wait – Not Quite**

To imply our brains are assembly line-ish is to have an incomplete understanding of how they work. In creating thousands of the exact same product, an assembly line does not loop back on itself, reconstruct the systematic assembly process based on a new part, or even switch the direction of the conveyor belt (this will make more sense later). The process is predetermined, and the work is the same regardless of individual variation. Our brains on the other hand, are constantly changing - renovating preexisting neuron structures, strengthening commonly used connections, removing and replacing unused ones. They have plasticity in other words. 

And while Skinner’s black box theory has largely been debunked, it does hold a key component for machine learning - inputs and outputs; stimuli go in, behavior comes out. Colloquially, ML models too are even referred to as “black boxes” in that when they are complex enough, it’s difficult to wholly understand their internal workings; although this may be [an over estimation](https://towardsdatascience.com/the-black-box-metaphor-in-machine-learning-4e57a3a1d2b0). What Skinner’s theory neglects, however, at least for what is relevant here, is the iterative chain of processes it takes to receive an output, and furthermore, how that output stems from an accumulation of information gathered over time. 

Thus, we come to the next step in the brain/computer analysis. A brain is constantly observing new information. This new information is added to the preexisting information or stimuli (stored in our brains in the form of neuron clusters), for which a new paradigm is constructed or a new response is added to the list. 

**Dogs again**

So why would a growling dog prompt a fight/flight reaction, when previously we wanted to pet them? Perhaps we saw a gruesome attach scene in a movie, or we were bit by a dog in the past, or we were taught to give dogs their space. Regardless, at one point, we didn’t understand the potential of a growling dog, and now we do. We learned – and our brains adjusted. At the outset of learning that a growling dog might be harmful, our brains created new neurons, connecting them with the old ones that represent ‘dog’. Our brains may even have reformed the concept of ‘dog’ entirely.

​     Original feelings towards dogs:     ![ML flow chart 1](C:\Users\bleoh\Pictures\ML flow chart 1.png)



​      After getting bit by dog: ![ML flow chart 2](C:\Users\bleoh\Pictures\ML flow chart 2.png)



Originally, this flow of decision making just included ‘pet’, but now it has ‘harmful’ and ‘run. Our next interaction with a dog may find them to be not harmful, but also totally unresponsive to petting, and thus we add ‘ignore’ to our responses.

![ML flow chart 3](C:\Users\bleoh\Pictures\ML flow chart 3.png)

As stated, this is an oversimplified example. Our brains are so complex and well-optimized that contextual variability is added to the equation in an instant. At the same time the chain of decisions is made, outside information is simultaneously considered. The dog may be attached to a leash, it may be growling at the other dog we happen to have with us, it may not be growling at all, but have its lips pulled back in a permanent snarl. We may also see a fence within running distance or perhaps its owner assures us it’s friendly, something we may be likely to believe because the owner is a trusted friend. Our brains process and respond to all of this information in an instant. And we add it to our decision tree. 

Over time, the more experiences we have with dogs (whether on tv, in person, or through a story), the better we can fine-tune our decision making. We may start to notice correlations between breeds, sizes, hair length, geographic location, emaciation, age, or nearby animals. The more information we attend to and add to our system, the more adept will be at responding to future experiences.

As these experiences accumulate, they simultaneously create new connections for new information, and strengthen connections from previous experiences. And these [neural connections get stronger](http://scienceoflearning.jhu.edu/research/how-does-learning-impact-neural-networks-in-the-primary-visual-cortex) according to the frequency of the results we get. And the stronger the connection, the more often our brains will visit that cluster to make an “informed” decision; or what one might call logic. Thus, if the neural connection between ‘dog’ and ‘run’ is stronger than ‘dog’ and ‘pet’, we will run. 

**Other Decision-Making Forces**

It's important to note, that our decisions don't always go through the chain of reasoning as described above. We can override them for a variety of reasons: perhaps the last experience we had was unlike the majority and the recency of that event stands out to us more clearly than the strongest neuron cluster. Or perhaps we are in search of the Philosopher’s Stone and must bypass a three-headed dog by mustering up the gumption to face our ‘common sense’ (or in this case, what our brains tell us we should avoid).[[6\]](# ftn6)

Our decision making is often influenced by our emotions as well. How many decisions are made whilst trying to calculate every angle, but in the end, finding this to be a tedious task, and instead picking the one that feels the best? Take the grade school example of making a pros and cons list of the people we want to be our boy/girl friend? Let’s call our potential relationship candidates Troy and Abed. If, through the pros/cons process, they come out even, how do we decide who to pick? Mostly likely: Feeling. 

But on the flip side, what is important here, is that we calculated our options. We assessed all the variables and at least attempted a logically sourced choice. In this example, all the boxes on the pros and cons checklist are weighted the same way, or that is to say, their neuron clusters have equally strong connections. If that's true, some might say that the "feeling" we used in grade school to make a final call was in actuality the product of a stronger neural connection between, say, where Troy’s conceptual reality lives in our heads and where Abed’s lives. But we'll end this train of thought here, as emotional decision making starts getting into territory that goes beyond the scope of this series. 

It’s not hard to believe that we would rely on the wisdom of past experiences, especially our own, though how often have we repeated something we regret because the first time seemed like a one-time thing? Or we forgot what happened last time? But perhaps after the second time, we learn; and if not, than we remember that we should have. Even the insanity witticism, ever misattributed to Einstein, applies: “Insanity is doing the same thing over and over again, but expecting different results". While insanity is an exaggeration of not having learned our lesson the first go around, this aphorism does imply that our behavior should change. And if not, than we are not learning, thus our brains don't change, and we can't make better decisions in the future.

Now to machine learning.

------

[[1\]](#_ftnref1) It’s important to note that this book was more than just a historical capsule of early human computer work; it was also intended as a testament to the race and gender discrimination of the time and to celebrate the yet unrecognized work of black women in such a white male dominated sphere. 

[[2\]](#_ftnref2) Learn more about the different subfields and criticisms of Cognitive Psychology [here](https://www.simplypsychology.org/cognitive.html).

[[3\]](#_ftnref3) [This article](https://www.neuroscientificallychallenged.com/blog/know-your-brain-primary-visual-cortex) provides an excellent breakdown of this process.

[[4\]](#_ftnref4) There are also multiple competing theories of how our perception works and especially the kinds of schema we create: check out an article that summarizes that [here](https://www.simplypsychology.org/perception-theories.html).

[[5\]](#_ftnref5) Skinner was originally from the era of behavioral psychology in which the mind (and by association the brain) was assessed by a person’s behavior, or else response to stimuli. This was also the era of Pavlov’s dog conditioning experiments – a perfect example of behavioral psychology in that Pavlov provided stimuli in the form of food (further associated with the sound of a bell) and tracked how the dogs responded (by drooling). Read more here.

[[6\]](#_ftnref6) Also, as anyone with even a hint of a phobia can attest to, decision making is not always accounted for by a logically weighted info. In the case of phobias, it can often be due to an extreme emotional experience. Thus, this example is far from complete.