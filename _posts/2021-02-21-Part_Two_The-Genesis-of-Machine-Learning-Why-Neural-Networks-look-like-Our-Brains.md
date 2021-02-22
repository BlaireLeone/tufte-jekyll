---
layout: post
title:  "Part two: The Genesis of Machine Learning: Why Neural Networks look like Our Brains"
date:   2020-02-21 10:46:04
categories: jekyll css
---
{% newthought 'Machine Learning' %} is pretty wild, and here is why your brain is literally a machine.
{% maincolumn 'assets/img/ML Brains 1.png'  ''%}

<!--more-->

**Sounds Assembly Line-ish**

This explanation is vastly oversimplified (and for this example in particular, actually skips a few steps), but it may sound like another familiar historically-relevant process – *assembly lines*, in which we see a step-by-step process that accumulates into a final product. We could say that each neuron represents a person with a specialty or task, each lobe or section of our brains represents a department, and between those is a conveyor belt that streamlines the packaged information from group to group. In other words, it has a linear orientation with one direction that starts and stops at the same place every time. 

In this way, we may prefer BF Skinner’s perspective{% sidenote '5' 'Skinner was originally from the era of behavioral psychology in which the mind (and by association the brain) was assessed by a person’s behavior, or else response to stimuli. This was also the era of Pavlov’s dog conditioning experiments – a perfect example of behavioral psychology in that Pavlov provided stimuli in the form of food (further associated with the sound of a bell) and tracked how the dogs responded (by drooling).' %}, in that our brains are a "black box". We can’t examine the internal workings; we can only monitor what comes out as a response to what goes in. Thus, one or multiple things is fed into one side of the box and something else entirely emerges on the other side. Likewise, at each destination in an assembly line, another part is added until a whole is complete. 

**But wait – Not Quite**

To imply our brains are assembly line-ish is to have an incomplete understanding of how they work. In creating thousands of the exact same product, an assembly line does not loop back on itself, reconstruct the systematic assembly process based on a new part, or even switch the direction of the conveyor belt (this will make more sense later). The process is predetermined, and the work is the same regardless of individual variation. Our brains on the other hand, are constantly changing - renovating preexisting neuron structures, strengthening commonly used connections, removing and replacing unused ones. They have plasticity in other words. 

{% marginfigure 'blackbox' 'assets/img/Black Box.jpg' "Skinner's idea of the human pyche." %}

And while Skinner’s black box theory has largely been debunked, it does hold a key component for machine learning - inputs and outputs; stimuli go in, behavior comes out. Colloquially, ML models too are even referred to as “black boxes” in that when they are complex enough, it’s difficult to wholly understand their internal workings; although this may be [an over estimation](https://towardsdatascience.com/the-black-box-metaphor-in-machine-learning-4e57a3a1d2b0). What Skinner’s theory neglects, however, at least for what is relevant here, is the iterative chain of processes it takes to receive an output, and furthermore, how that output stems from an accumulation of information gathered over time. 

Thus, we come to the next step in the brain/computer analysis. A brain is constantly observing new information. This new information is added to the preexisting information or stimuli (stored in our brains in the form of neuron clusters), for which a new paradigm is constructed or a new response is added to the list. 

**Dogs again**

So why would a growling dog prompt a fight/flight reaction, when previously we wanted to pet them? Perhaps we saw a gruesome attach scene in a movie, or we were bit by a dog in the past, or we were taught to give dogs their space. Regardless, at one point, we didn’t understand the potential of a growling dog, and now we do. We learned – and our brains adjusted. At the outset of learning that a growling dog might be harmful, our brains created new neurons, connecting them with the old ones that represent ‘dog’. Our brains may even have reformed the concept of ‘dog’ entirely.

*Original feelings towards dogs:*

{% maincolumn 'assets/img/ML flow chart 1.png' "" %}                            

*After getting bit by dog:*

{% maincolumn 'assets/img/ML flow chart 2.png' "" %}                            

Originally, this flow of decision making just included ‘pet’, but now it has ‘harmful’ and ‘run. Our next interaction with a dog may find them to be not harmful, but also totally unresponsive to petting, and thus we add ‘ignore’ to our responses.

{% fullwidth 'assets/img/ML flow chart 3.png' "" %}                            

As stated, this is an oversimplified example. Our brains are so complex and well-optimized that contextual variability is added to the equation in an instant. At the same time the chain of decisions is made, outside information is simultaneously considered. {% marginfigure 'troyandabed' 'assets/img/fluffy_the_three_headed_dog.jpg' 'Lots of information to glean from cerberus.' %} The dog may be attached to a leash, it may be growling at the other dog we happen to have with us, it may not be growling at all, but have its lips pulled back in a permanent snarl. We may also see a fence within running distance or perhaps its owner assures us it’s friendly, something we may be likely to believe because the owner is a trusted friend. Our brains process and respond to all of this information in an instant. And we add it to our decision tree.

Over time, the more experiences we have with dogs (whether on tv, in person, or through a story), the better we can fine-tune our decision making. We may start to notice correlations between breeds, sizes, hair length, geographic location, emaciation, age, or nearby animals. The more information we attend to and add to our system, the more adept will be at responding to future experiences.

As these experiences accumulate, they simultaneously create new connections for new information, and strengthen connections from previous experiences. And these [neural connections get stronger](http://scienceoflearning.jhu.edu/research/how-does-learning-impact-neural-networks-in-the-primary-visual-cortex) according to the frequency of the results we get. And the stronger the connection, the more often our brains will visit that cluster to make an “informed” decision; or what one might call logic. Thus, if the neural connection between ‘dog’ and ‘run’ is stronger than ‘dog’ and ‘pet’, we will run. 

**Other Decision-Making Forces**

It's important to note, that our decisions don't always go through the chain of reasoning as described above. We can override them for a variety of reasons: perhaps the last experience we had was unlike the majority and the recency of that event stands out to us more clearly than the strongest neuron cluster. Or perhaps we are in search of the Philosopher’s Stone and must bypass a three-headed dog by mustering up the gumption to face our ‘common sense’ (or in this case, what our brains tell us we should avoid.

{% marginfigure 'troyandabed' 'assets/img/Troy_and_abed.jpg' 'Troy and Abed' %}
Our decision making is often influenced by our emotions as well. As anyone with even a hint of a phobia can attest to, it can often be due to an extreme emotional experience. Likewise, how many decisions are made whilst trying to calculate every angle, but in the end, finding this to be a tedious task, and instead picking the one that feels the best? Take the grade school example of making a pros and cons list of the people we want to be our boy/girl friend? Let’s call our potential relationship candidates Troy and Abed. If, through the pros/cons process, they come out even, how do we decide who to pick? Mostly likely: Feeling. 

But on the flip side, what is important here, is that we calculated our options. We assessed all the variables and at least attempted a logically sourced choice. In this example, all the boxes on the pros and cons checklist are weighted the same way, or that is to say, their neuron clusters have equally strong connections. If that's true, some might say that the "feeling" we used in grade school to make a final call was in actuality the product of a stronger neural connection between, say, where Troy’s conceptual reality lives in our heads and where Abed’s lives. But we'll end this train of thought here, as emotional decision making starts getting into territory that goes beyond the scope of this series. 

It’s not hard to believe that we would rely on the wisdom of past experiences, especially our own, though how often have we repeated something we regret because the first time seemed like a one-time thing? Or we forgot what happened last time? But perhaps after the second time, we learn; and if not, than we remember that we should have. Even the insanity witticism, ever misattributed to Einstein, applies: “Insanity is doing the same thing over and over again, but expecting different results". While insanity is an exaggeration of not having learned our lesson the first go around, this aphorism does imply that our behavior should change. And if not, than we are not learning, thus our brains don't change, and we can't make better decisions in the future.

Part 3 (coming soon) will discuss how machine learning relates, and differs, from this human form of heuristic learning. 