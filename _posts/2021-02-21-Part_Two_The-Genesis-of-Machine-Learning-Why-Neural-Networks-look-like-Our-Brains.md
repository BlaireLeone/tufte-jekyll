---
layout: post
title:  "Part two: The Genesis of Machine Learning: Why Neural Networks look like Our Brains"
date:   2020-02-21 10:46:04
categories: jekyll css
---
{% newthought ''Connectionism! Brains learn iteratively, perhaps not quite so logically, and perhaps after trying the same thing multiple times" %}.
{% maincolumn 'assets/img/ML Brains 1.png'  ''%}

<!--more-->

**Dogs again**

So why would a growling dog prompt a fight/flight reaction, when previously we wanted to pet them? Perhaps we saw a gruesome attach scene in a movie, or we were bit by a dog in the past, or we were taught to give dogs their space. Regardless, at one point, we didn’t understand the potential of a growling dog, and now we do. We learned – and our brains adjusted. At the outset of learning that a growling dog might be harmful, our brains created new neurons, connecting them with the old ones that represent ‘dog’. Our brains may even have reformed the concept of ‘dog’ entirely.

*Original feelings towards dogs:*

{% maincolumn 'assets/img/ML flow chart 1.png' "" %}                            

*After getting bit by dog:*

{% maincolumn 'assets/img/ML flow chart 2.png' "" %}                            

Originally, this flow of decision making just included ‘pet’, but now it has ‘harmful’ and ‘run. Our next interaction with a dog may find them to be not harmful, but also totally unresponsive to petting, and thus we add ‘ignore’ to our responses.

{% fullwidth 'assets/img/ML flow chart 3.png' "" %}                            

As stated, this is an oversimplified example. Our brains are so complex and well-optimized that contextual variability is added to the equation in an instant. At the same time the chain of decisions is made, outside information is simultaneously considered. {% marginfigure 'troyandabed' 'assets/img/fluffy_the_three_headed_dog.jpg' 'Lots of information to glean from Fluffy.' %} The dog may be attached to a leash, it may be growling at the other dog we happen to have with us, it may not be growling at all, but have its lips pulled back in a permanent snarl. We may also see a fence within running distance or perhaps its owner assures us it’s friendly, something we may be likely to believe because the owner is a trusted friend. Our brains process and respond to all of this information in an instant. And we add it to our decision tree.

**Frequent vs Infrequent experiences**

Over time, the more experiences we have with dogs (whether on tv, in person, or through a story), the better we can fine-tune our decision making. We may start to notice correlations between breeds, sizes, hair length, geographic location, emaciation, age, or nearby animals. The more information we attend to and add to our system, the more adept will be at responding to future experiences.

As these experiences accumulate, they simultaneously create new connections for new information, and strengthen connections from previous experiences. And these [neural connections get stronger](http://scienceoflearning.jhu.edu/research/how-does-learning-impact-neural-networks-in-the-primary-visual-cortex) according to the frequency of the results we get. And the stronger the connection, the more often our brains will visit that cluster to make an “informed” decision; or what one might call logic. Thus, if the neural connection between ‘dog’ and ‘run’ is stronger than ‘dog’ and ‘pet’, we will run. 

On the flip side, for those experiences that happen infrequently, we probably will still remember, but due to their infrequency, we don't visit the connection very often to influence our decisions. Take the example of running into a low hanging/descending doorway, perhaps in a corridor we are unfamiliar with. If this doorway is one we don't frequent very often, than we are unlikely to take it very seriously within the grand scheme of doorways. We may run into the doorway a few times while visiting the corridor, and after a few times, we may, subconsciously or otherwise, get into the habit of ducking for this particular doorway. But take the corridor away and replace it with the normal doorways we are apt to come across, and we no longer duck. The habit of ducking was unable to be ingrained because this is not a situation we normally find ourselves. Thus, the connection we made between doorway and duck while we visited the corridor dies, as we no longer need it. Thus, neuron connections also get weaker, the less frequently we visit them.

**Recency, Common Sense, and Emotions Oh My!**

It's important to note, that our decisions don't always go through the chain of reasoning as described in the dog example above. We can override them for a variety of reasons: perhaps the last experience we had was unlike the majority and the recency of that event stands out to us more clearly than the strongest neuron cluster. Or perhaps we are in search of the Philosopher’s Stone and must bypass the three-headed dog standing over the trap door we must enter by mustering up the gumption to face our ‘common sense’ (or in this case, what our brains tell us we should avoid).

{% marginfigure 'troyandabed' 'assets/img/Troy_and_abed.jpg' 'Troy and Abed' %}
Our decision making is often influenced by our emotions as well. As anyone with even a hint of a phobia can attest to, we can be influenced to avoid something due to an extreme emotional experience, even if we logically understand that we aren't in danger. Likewise, but to a much lesser degree, how many decisions are made whilst trying to calculate every angle, but in the end, finding this to be a tedious task, and instead picking the one that feels the best? Take the grade school example of making a pros and cons list of the people we want to be our boy/girl friend? Let’s call our potential relationship candidates Troy and Abed. If, through the pros/cons process, they come out even, how do we decide who to pick? Mostly likely: Feeling. 

**Heuristic Learning**

In terms of the learning process, what is important in this example, is that we calculated our options. We knew that some decisions require thorough assessment, and thus weighed all the variables and at least attempted a logically sound choice. We can call this method of decision making *heuristics*, (AKA 'cognitive shortcuts' or 'rules of thumb') a practical, and sometimes more efficient, approach to [problem solving](http://www.sfu.ca/~jeffpell/papers/RomanyciaPelletierHeuristics85.pdf), whereby we may employ a commonly successful technique or model in assisting our own hunt for answers.

[^Ftn]: Also check out the oft nefarious [cognitive biases](https://projects.iq.harvard.edu/expose/book/interactions-heuristics-and-biases-making-decisions) imbedded heuristics especially the availability heuristic!

 In this example, we attempted to root out for ourselves who the optimal boyfriend was using the timeless pros and cons list.

All the boxes on the pros and cons checklist are weighted the same way, or that is to say, the characteristics we were judging Troy and Abed on have equally strong connections, so they came out even. Thus, some might say that the deciding factor, the "feeling" we used in grade school to make a final call, was in actuality the product of a stronger neural connection between where Troy’s conceptual reality lives in our heads and where Abed’s lives. This connection was fed via a simple emotional pull. But we'll end this train of thought here, as emotional influences on neurological behavior goes beyond the scope of this series. 

Heuristic learning however, does not always use the same approach to solve a problem. Take for example, trying to locate Miso soup at a grocery store. How would you look for it? There are multiple options, perhaps the easiest of which is asking an employee, however if left to our own devices what do we do? Two other methods are 1.) Look in all the seemingly relevant aisles - oriental cooking, soup, sauces/condiments, shelf-stable items etc. 2.) Traverse every aisle, scanning up and down every shelf, until it's located. While the first method is more efficient and usually successful, the second method guarantees success (that is if we know the store carries Miso), however it's far more time-consuming. In the interest of heuristics, both of these processes work, and both show a logical effort. 

And what does this mean in terms of our brain's learning? We decide how to proceed based on the information we have stored. But heuristics goes beyond the need to make a simple decision, it involves a process of logical reasoning in which we decipher how best to proceed according to relevant experience and current situations. And over time, we get better at calculating the correct method based on time after time of improving our odds with every cumulative experience.

**Conclusion**

It’s not hard to believe that we would rely on the wisdom of past experience, especially our own, though how often have we repeated something we regret because we forgot what happened the first time, or else it seemed like a one time thing? But perhaps after the second time, we learn; and if not, than we remember that we should have. Even the insanity witticism, ever misattributed to Einstein, applies: “Insanity is doing the same thing over and over again, but expecting a different result". While insanity is certainly an exaggeration of say, hitting your head on a low hanging doorway four times in a row, this aphorism implies that learning from these experiences over time is the more natural outcome; not learning, and thereby not changing our behavior, is thus illogical and unsustainable. If we don't add these experiences up, and transcribe them into additional connections in our brains, than we can't make better decisions in the future. And as it turns out, neural networks learn in much the same way.

And thus, we come to Machine Learning.

Part 3 (coming soon) will discuss how machine learning compares to this human form of heuristic learning. 