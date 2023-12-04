---
title:
layout: default
permalink: /backlog/
published: true
---

# Backlog of Ideas

the content in /thoughts/ are more public things that I would say and feel confident would be good. 
This is more for myself, poorly worded and isn't really "validated". Hence this is backlog.

### 2023-04-23

continue to watch YT. fun concept : 禅宗祖师跟你说话，话不多，每一句话都在逼你，把你逼到没有立足之地的时候，没退路的时候，在这一刻，有一种可能性，达到不可言说的那一刻。禅宗跟我们说话的目的，就是让我们，尽可能快的达到不可说。

this is opposite to how we view knowledge as encoded in the text itself. it is very pragmatic. the meaning is not in what is being said, but in what is remaining, of what cannot be said. language is not used to construct truth (理解), but used to rule out what truth _cannot be_ (悟性).

### 2023-04-23

today a thought occured to me . . it seems symbolic reasonings, imposed by humans and taught to machines, will _never_ go away (in face of AI advances), as long as humans continue to observe the world best.

humans are the best observers of this universe - the best simulator there is. symbols are result, or summary, of this simulation. symbols are born of observations of the simulation.

armando says APIs for classroom, or for laundry, works really well. however, making an API for a "cellphone washing service" will cause it to break. for instance, the cost of washing a cellphone will return the cost of the cellphone instead. this is a class of attacks, where logical relationship is required, but it has such a strong statistical bias that cannot be overcome.

some random youtube video: one difference between chinese and western philosophy is that western is concerned with change. there is a platonic ideal for every concept, and everything in real life is only an approximation - thus, much effort is used to change the real life toward this ideal. there is a _diff_, which must be overcome. chinese philosophy the ideal is within this world 佛法在世间，不离世间觉。离世觅菩提，恰如求兔角.

### 2023-04-20 judy

IV - what is independent variable, what are we manipulating?
DV - what is we're measuring, what are we making inference about?

we want an interface that is natural enough that people will use, yet easy enough to break into ppl's mind on what they're thinking about.

### 2023-04-14 cleaning up post-it 

in rebuttal a paper, where reviewer suggest a poor fit to the venue, the best thing is to find nearest-neighbor work to yours that were accepted to the venue.

there's always a trade-off between automation and flexibility. fully automated systems tends to be brittle, and flexible systems tends to require human efforts to intervene. hopefully natural programming can solve this trade-off.

chatgpt is good at generating bibtex from just copy-pasted latex info in the paper

is there a book on just data collection for ML? should I write one?


### 2023-04-12 visit to stanford ideas

debugging is like autonomous driving. it is a horrible problem. if you can generate 98% of the code, and you had to debug on the 2%, all pretense of "code free" is lost. the end-user would still have to debug the 2%, which, if they're not trained programmers, can't do. they would also have to reason about the rest 98% of the software, which at this point, they've been happily ignoring

### 2023-04-10 cleaning up post-it ideas

using cycle consistency: hypothesis -> 20 questions -> recover hypothesis, or hypothesis -> svg -> hypothesis is a super good way to validate LLMs.

judy uses the notion of "latent axis" a lot. so whenever scientist have a "hunch" on how the underlying structure is, those are the latent axis. for instance, people communicate search problems (in LARC) was a latent axis, which we made explicit. good experiments should expose these latent axis.

judy also likes the idea of validation using action sequences or execution of natural programs. as it gives a very "high resolution" on what language meant. as compared to 1 of 2 decision tests, which is very low resolution on what language can do.

### 2023-04-08 cleaning up some notes for recycle

The boundary of what humans can do and waht machines can do is blurry rn. it is the job of a scientist to figure out what the boundary is again. 

optmization is awful for a soft body system if the deformity has high restitution, it is like learning a controller deforming a rubberband from one shape to another, it is likely to not have a solution. -- andrew spielberg



### 2023 04-04 daniel fried / saujas how to do research

In a setting where the agent is generating its own training data, and is not working, it is important to separate out what the problem is: do we have a data generation problem (i.e. data not generated the same way as human would have generated them)? or do we have a learning problem (i.e. the data is good and there, but the model can't learn it)? isolate and kill one at a time.

research, all research, you have to fix a number of decision points. ideally these decision points can be fixed deductively, i.e. it _has to be_ certain value. however, all research will devolve, at some point, to a search problem, where you have some number of decision points, and there's no good way other than "try and find out". 

during the "try and find out" phase of research, it is important to maximize two aspects: 1. better signal (are one attempt better than another? what is good?) and 2. faster iteration speed, so you can try a lot cheaply. I mean good intuition on what to try first goes without saying. but you should have a _goal_ of "try and find out", or a stopping condition: we're going to stop try and find out as soon as X becomes true. specify what X is.

### 2023-04-03 judy on how to mentor

keep the collection between low-level operations and high-level aspiration very clear, you want to connect the dots in your collaborations, and be clear of this with your junior collaborator so everyone sees what they're working on is a path toward this high level aspiration at all times.

few more notes on that day

Karl : there needs to be better automation with these design tools. Isn't it surprising that, photoshop, fusion, autocad, none of the design tool _know_ what is actually being designed? it's just boxes and lines, but not wheels and knobs.

Judy studies how people make things, and use objects to think and communicate.

### 2023-04-01 research ideas with daniel friend

it seems easier for open source community to catch up in code models as opposed to open ended dialogue in a race against openAI. this is useful because code models have the most "utility" for the things I care about.

RL is compiled search -- taking a multi-step action sequence and compressing it down to 1 step. That view is fairly widely accepted. However, what is not widely appreciated is that even for alphaZero, it _still_ has to perform search and compute at inference time, playing many games over to decide the best move. This _strongly_ implies that reward model plus search is better than memorizing the solution for each problem -- that the _process_ of doing a search is more efficient (literally, cram-able into a NN sense) than the _solution_ of memorizing a right move at every board state.

### 2023-04-02 overall development stuff

We know accomplishment is the best thing for external validation, for people who have no time to judge if "you're worth it". Internal validation can be build with time between collaborators, but external one the best is through accomplishment. i.e. if I can say "I've built a dataset worth of 1mil dollars", that would be cool.

Thus in collaboration one very important consideration is to "actually get stuff done". If you can accomplish a goal in a collaboration, everyone is happy.

Sometimes the best way to benefit your collaborator is not to talk and talk, but to listen. Sometimes it is paying instead of rewarding when you're listening. For people with strong personality and want to "emit ideas" (like myself), they want listeners. I need to be better listeners, this is good way to help.

The best way to collaborate is to _just ask them_ what they need help with. If you can give people what they actually need (i.e. they can tell you ffs), you're being helpful. You should just ask, don't guess -- I'm terrible at guessing what people need. I should just ask.

### 2023-03-29 ideas

The following are technologies compliant with _existing_ capabilities. These are not research ideas, but can spin into start-ups if someone's willing.

Web will change. Ads as we know it will dissapear. There will first be an APP where it'll render the web in sandbox mode, and then re-render it for you, ignoring all the parts that are not of interests. You will have in front of your face a "personalized renderer" that interface you to the "information web", that actively filter and curate information. Once this personalized renderer becomes commonplace, most websites will devolve to just ChatAPIs, like how ChatGPT is already thinking how it should be, and provide only functionalities, sending easily digestable jsons -- you render them however you want.

One immediate move (as of today) in response to ChatGPT is the creation of a shell, or public persona. Multiple can be created. It can ingest data that you generated, and can act (chat, etc) on your behalf. So interactions of buying grocery, booking flights, etc, will be done with this shell.

Observation: Humans did not evolve well to socialize with so many different other humans. We are not designed for it. We prefer few interactions, smaller groups. Most of the socialization nowaday are _forced and unnatural_ and will have a strong incentive to be optimized away. Thus day to day social interactions, of the mundane, unpleasurable kind, will reduce. That will be done with shells.

Observation: There are way too much information available, no human can ingest them all. We badly need a curator of sorts.

Observation (combining the previous 2): Society is best run by statistical averages. Humans are fundamentally novelty seeking and work horribly with averages -- we're unfit to govern ourselves in a sense. Society should be organized by AI, which cannot be malicious as it can only reason in averages, and individual humans will focus on pushing the boundaries of knowledge/civilization. Statistical methods that train these AI will be incapable of becoming malicious in a "sUdDeNlY iT's EvIl!" fashion, as it is an average of opinions, capable of speaking on our (our = humanity) behalf fairly.

AI safety thus is primarily about whom and what thoughts can be uploaded online, to prevent these statistical learners from learning a "skewed" worldview. Perhaps this process itself is the new "review" critiera in a academic conference sense. If your work pass the review, it gets to be uploaded into the collective. I have no idea how this will work in a good way.

Observation: The best communicative system is human body, where cells work together in highly complex and capable ways that we have _no clue_ how it work tbh. As society progress we'll have to improve our communication. Bad news is that current communication, i.e. going to work, mandatory zoom bullshit meetings, booking calendar so both can be there, is HORRIBLE. Good news is that we've only been doing the communication problem for what, 2000 years as a civilization? There's a room for improvement, lots of room.

There will be a new social media set up where all actors are "shells". You can have a new kind of market place of buyer/seller, but all shells, and dating, and scientists. The shells will generate, curate, and relay information to you in a nice form that you can digest. 

data format is pain. we massage data from one form to another all the freaking time. this reasults in a lot of training data for transformation of data between formats. thus different formats will go away because it killed itself.