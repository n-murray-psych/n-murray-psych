---
title: "What Makes An Abductive Argument (Un-)Persuasive?"
date: 2024-02-09
tags:
  - On Things Psychological
  - Philosophy of science
  - Metaphysics
  - Epistemology
---

[*An image of the American philosopher Charles Sanders Peirce, sourced from Wikipedia](https://en.wikipedia.org/wiki/Charles_Sanders_Peirce)

Formally, arguments can take on one of three forms: deduction, induction, and abduction.

Deductive arguments operate such that necessarily, if the premises are true, then the conclusion must be true. To use a cliche’d example:

Premise 1: Socrates is a man.

Premise 2: All men are mortal.

Conclusion: Socrates is mortal.

As you can see, the conclusion is completely obvious from the premises. So as long as the premises are true, the conclusion must be true as a matter of logic. If Socrates were actually a god, for example, then we could doubt the conclusion that Socrates is mortal because the second premise no longer applies to Socrates.

Inductive arguments operate such that, from an observed regularity in the world, we infer some fact about the stability of that regularity. For example:

Premise: Every time I drop my pen, it falls to the ground.

Conclusion: Whenever I drop my pen again, it will fall to the ground.

For inductive arguments, we assume, as [David Hume](https://plato.stanford.edu/entries/hume/) explained, that *nature is uniform* – i.e., that regular occurrences are regular because there is something about the world that makes them so. (Just to be clear, Hume was an inductive skeptic and didn’t believe we were justified in assuming nature is uniform, but I digress).

Abductive arguments, as identified by the American philosopher [Charles Sanders Peirce](https://plato.stanford.edu/entries/peirce/), are different from both deduction and induction: like induction, conclusions in abductive arguments   do not necessarily follow from their premises. Rather, abduction is a form of probabilistic inference, where instead of inferring an observed pattern of regularity that the regularity will remain stable, we infer a particular explanation for an observed event based on how well it fits some criteria for what makes a “good” explanation. An example will help clarify this convoluted definition: 

Suppose you’re playing cards with someone, let’s call him Abe. Abe manages to pull five royal straight flushes in a row! If you were to make an inductive inference, you might say that Abe is likely to keep pulling royal straight flushes (however poor that inference may actually be). If, on the other hand, you sought to make an abductive inference, you may ask yourself: “How could it be that Abe managed to pull off such a startlingly improbable set of poker victories?”

Let’s assess the theories for how Abe pulled off his five lucky hands: he could have (1) cheated, or (2) got lucky. Under the latter theory, it is extremely improbable that Abe would draw five royal straight flushes in a row. Under the former theory, however, Abe could have stacked the deck (assuming he shuffled) to pull five royal straight flushes, and so you may feel justified in inferring that Abe cheated on the basis that cheating “better explains” this incredibly improbable set of poker hands.

The form of abduction I’ve just introduced to you is called *inference to the best explanation*. Inferences to the best explanation involve choosing an explanation which maximizes the probability of an observed event(s). In statistics, there is a closely related principle called the *maximum likelihood principle*, where the model function chosen to fit a predictive regression line is the function with the parameters *w* which maximize the probability of the data labels *y* with the data points *x*. [(For a detailed introduction to the maximum likelihood principle, see chapters 5-7 of Thomas Trappenberg’s *Fundamentals of Machine Learning*)](https://global.oup.com/academic/product/fundamentals-of-machine-learning-9780198828044?cc=ca&lang=en&).

There are other criteria for making an abductive inference: to extend our example, suppose that you accept Abe cheated. How could he have cheated? Perhaps he stacked the deck while he was shuffling it in front of you. Perhaps he has pulled off some sort of magic trick where, instead of stacking the deck, he actually just swapped out the deck in-between shuffles with one he’d stacked in advance. We can assume, for argument’s sake, that Abe is also a skilled magician. The “better” explanation for *how* Abe cheated remains that he stacked the deck, because even though magicians are skilled both at stacking and at swapping items in front of your eyes, simply stacking doesn’t require the additional assumption that Abe has multiple other poker decks on hand that he set up. In other words, the “simple-stacking” theory is better than the “pre-stacked-deck-swapping” theory, because it does not include the additional assumption that Abe has multiple decks on hand. More abstractly, the probability of A will always be higher than the (joint) probability of A and B, and the probability of B will always be higher than the (joint) probability of A and B. This is the *principle of parsimony*, whereby explanations are preferred in abductive inference which posit fewer assumptions for the explanation being inferred to work.

I could go into more detail about the mechanics of abduction, but to be honest, we’ve reached the limit of the utility of abstract argumentative principles. So, instead, we’ll use the two principles we’ve already defined (inference to the best explanation and the principle of parsimony) to answer the following question: 

# What Makes An Abductive Argument Un-Persuasive?

Let’s extend our Abe example once more: suppose that Abe is, in fact, “Honest Abe”. People call him “Honest Abe” because they truly believe he’s honest, all the time, in every situation – *he’d never tell a lie*. Suppose further that you believe this too. In this case, you’re still left with two possible theories for how Abe managed to pull five royal straight flushes: (1) cheating or (2) luck. So, even though it is much, much more likely on the “cheating” theory that Abe pulls five royal straight flushes, you infer that he got lucky, because you just can’t accept that Honest Abe would ever cheat you.

Clearly, then, there is more that makes an abductive inference un-persuasive than being un-parsimonious: when our prior knowledge of the world stands against a theory, it is possible that we reject the theory over our prior knowledge, no matter how probable the theory makes the event(s) we’re trying to explain. This intuition about “prior knowledge” is a key part of Bayesian inference which, for the sake of simplicity, I am not going to discuss more technically than I already have.

There is a so-called “minimal facts” argument from Christian apologetics, which says that there is some set of historical facts about Christ’s crucifixion and the ensuing events which are best explained by the theory that Christ actually was resurrected on the third day. Christian apologists, like [Gary Habermas](https://rationalwiki.org/wiki/Minimal_facts_argument), use this argument all the time. But in my opinion, they’re never going to persuade atheists like Alex O’Connor, Richard Dawkins, and so on, because the atheists simply do not assign a sufficiently high prior probability to theistic assumptions. They will always reject the minimal facts argument on the basis that the theory itself (belief in the God of Abraham) is so unlikely to be true that other explanations, even if they don’t fit the minimal facts as well, are better anyways. *Explanations themselves have a probability which can be assigned to them, subjectively or objectively, which is independent from the probabilities they assign to events they are attempting to explain.*

One topic where I’ve applied this criticism about priors is in the metaphysics of the laws of nature. Actually, to be honest, I took the Honest Abe example from Tyler Hildebrand’s 2020/21 Dalhousie Philosophy seminar, *Topics in Metaphysics*, which was based on his book, [*Laws of Nature*](https://www.cambridge.org/core/books/laws-of-nature/C347C591B6764EF30B64BABBEF1B8AAA). At the time, we were reading the work of philosophers who argued that the best explanation for the observed uniformity of nature is that there is some set of metaphysical laws which necessitate it's uniformity. I argued, however, that probabilistic natural laws which assign a probability less than 1 to any particular regularity can still explain the observed regularity of the natural world while still being, *a priori*, as likely explanations as natural necessity. To quote from my essay: 

“Is necessity [(*N*)] the best explanation for observed regularity? . . . As long as there is a probabilistic version of nomic necessity, *N*_p, and the probability is high enough to explain [all past observed regularities] without committing to the claim that [all future observations must be perfectly regular], then *N*_p will be at least as good an explanation for observed regularity *N*. The difference between the two hypotheses is simple: The former says that ‘the next [event] *must* be [the same as the last]’. The latter says that ‘the next [event] *might* be [the same as the last]’. Both are sufficient for explaining why all observed [events] have been [regular], but *N*_p is humbler than *N* in its future predictions.”

Ok, that’s a bit of a technical flex and detour, to be honest. But the principle has, in my opinion, a very practical application in science:

# Why Scientists Should Not Abuse Abduction to Win Prestige

One issue scientists run into is this: grant money, prizes, and other opportunities are really hard to come by. It’s hard to convince funders to fund your project. It’s hard to convince people to *care* about your project, particularly if you’re doing basic research that doesn’t have any obvious real-world implications.

I’ve been there, and I’ve been encouraged (not by my supervisors, thankfully) to “speculate” about the implications of my research project. Not for prizes or for money, but simply to “wow” people, which, frankly, I think is manipulative. Maybe, for example, I could’ve written in some prize proposal that knowing whether facial cues trigger reflexive or deliberate shift of attention [(the subject of my first paper)](https://doi.org/10.1037/cep0000315) could tell us “something” about schizophrenia, since people with schizophrenia could have some sort of difficulty paying attention to emotional faces. Could I tell you what that “something” is? No! I have no idea! And the possibility of that “something” never once was a motivation for pursuing the project! I pursued the project because it was theoretically interesting and controversial – a good subject for an honours thesis and a first paper. Not because it had some spectacular real-world implications which were obvious from the research question.

The issue here is I could’ve come up with some wildly speculative theory, under which I could somehow explain the relevance of my project to schizophrenia by arguing that the results I found somehow maximized the probability of the observed deficit for attention to faces in people with schizophrenia. But why would I do that? The only reason I could see was to impress people. I knew from my prior knowledge of the gaze-cuing literature that such an explanation would be so far-fetched that to invoke it for prestige would *actually* be dishonest. And I try my best to be an honest man.

I’ll end on a non-personal example: Karl Deisseroth is a psychiatrist and professor at Stanford University. Dr. Deisseroth is also one of the inventors of optogenetics, which, in his own words, he describes as follows: [“Optogenetics is a technology that allows targeted, fast control of precisely defined events in biological systems as complex as freely moving mammals. By delivering optical control at the speed (millisecond-scale) and with the precision (cell type–specific) required for biological processing, optogenetic approaches have opened new landscapes for the study of biology, both in health and disease.”](https://doi.org/10.1038/nmeth.f.324)

In Dr. Deisseroth’s *fantastic* 2021 book, [*Projections: A Story of Human Emotions*](https://www.penguinrandomhouse.com/books/600209/projections-by-karl-deisseroth/), he opens by discussing how optogenetics was made possible by some basic research on algae – yes, you read that right, *algae*. What an amazing thing to come from that research! Would it have mattered, then, if any scientist who contributed to algae science ever knew what incredible medical insight would come out of their work? No! And it’s not just because their work contributed to something great. It’s because *knowledge is a good and an end in and of itself.* Unless the mode of knowledge acquisition [(e.g., an unethical experiment, of which there have been many)](https://en.wikipedia.org/wiki/Unethical_human_experimentation) is inherently evil, we can pursue basic research for the good that it produces – knowledge. We, as scientists, should pursue ethical research, even if that is basic research, not to manipulate people and play power games, but to contribute to the ever-expanding horizon of human understanding. We have no need to use the uninformed prior experiences of others to mislead them about our motivations for pursuing the scientific enterprise.

# Conclusion

As I’ve argued here, abductive inferences can be un-persuasive when, despite the inferred theory’s capacity to maximize the probability of an observed event, the postulated theory is deemed sufficiently improbable so as to be disregarded. I further argued that it’s all too easy to manipulate others through their perceived lack of prior knowledge to obtain power and privilege. As scientists, we must ethically pursue the truth for the sake of obtaining it. Full stop.

Thank you for reading the ramblings of a young psychological scientist,

Nicholas E. Murray