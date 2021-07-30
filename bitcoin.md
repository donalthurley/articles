## Bitcoin's Proof of Work is Causing Substantial and Unnecessary Environmental Damage and Should Be Banned
_written by_ **Donal Hurley** 

_'Look at mother nature on the run'\
Neil Young - After the Goldrush_

**Disclaimer:** _I don't own any cryptocurrencies and have never worked in the cryptocurrency space._

We know that fifty-one billion tons of greenhouse gases are being pumped into the atmosphere every year and
that the world needs to eliminate as much unnecessary waste as possible if we are to have any chance of getting to zero.
We also know that the environmental cost of the Bitcoin network is now equivalent to that of a moderate sized country.
We need to understand why the Bitcoin network is so wasteful.
We need to do this with urgency as Bitcoin has already achieved considerable market adoption and critical mass.

Lex Fridman [1] has recently conducted a valuable series of podcast interviews on YouTube with the leaders of the cryptocurrency industry.
From listening to these discussions it is clear that the unnecessary waste is due to Bitcoin using an algorithm called Proof of Work.
This is causing substantial energy waste with no apparent gain and this flaw is already being addressed
with an alternative approach called Proof of Stake in the second and third generation cryptocurrency platforms.

Before explaining these two approaches let us look at the core features of cryptocurrencies.

Firstly the main goal is to replace traditional currencies like the dollar or euro with a digital currency.
Secondly they use a new data storage concept, this now famous blockchain, for ensuring that currency transactions are secure and can never be altered.
Each new block in the chain is cryptographically linked to all previous blocks in the chain, meaning no block can be altered without invalidating the whole chain.
And thirdly the goal of these currencies is to remove the need for intermediaries.
This is achieved by large scale distribution of the blockchain data store with every participant using the currency having their own copy.

This large scale distribution or decentralization concept is the core driving force behind cryptocurrencies and the platforms that are emerging in this space.
Decentralization is challenging and more expensive to implement than centralization.
Without a central authority, when new currency transactions occur between participants how can they trust each other and successfully keep their own data copies in sync?

In the distributed computing academic literature this is a known problem for which there are several documented solutions.
It is referred to as the _Byzantine Generals Problem_ the name coming from the allegory which Lamport, Shostak and Pease proposed in their paper in 1982 [2].

The idea is that there is a number of generals who need to decide whether to attack or retreat from a city and they must come to a common agreement.
They can communicate their decision with each other using messengers.
But these messengers could be unreliable and fail to deliver the messages or even deliver false messages.
In cryptocurrency terms the computer nodes would represent the generals and the communication system links would represent the messengers.

To resolve this problem the generals come up with a way to show a sign of good faith.
They do this by showing that they are willing to sacrifice some resource of value if they are caught cheating.
This allows them to come to an agreement even if nearly half of the generals are trying to cheat.

In the case of Proof of Work that resource is a work resource and in the case of Proof of Stake it is an economic resource.

In Bitcoin the Proof of Work task is a cryptographic puzzle that is given to special _miner_ nodes that can take several minutes to solve.
In terms of the Byzantine Generals allegory it would be equivalent to each general asking his infantry to perform some time consuming task,
a useless task like the ones given to Sysyphus, but one that can then be checked by the other generals and will prove his good intentions.

Second and third generation cryptocurrency platforms are moving to the more efficient Proof of Stake approach.
This is where participants put a deposit of some crypto coins down and are prepared to lose them if they are not considered trustworthy.
In the allegory this would be like the generals staking some of their own physical gold coins as a sign of good will.

It is very obvious that Proof of Stake is a far superior approach because it doesn't incur the high energy cost of Proof of Work.
And Proof of Work is wasting energy because the task is doing nothing useful.

So why then was Proof of Work the approach proposed in the famous Bitcoin white paper [3] and subsequently adopted?

To understand this we need to go back to the literature to where the idea for Proof of Work first arose.
The original idea comes from a paper which suggested it as a solution for combating junk mail [4].
In it Dwork and Naor clearly state why they chose a computational pricing model rather than charging a fee.

    Usage fees may be a deterrent; however, we do not want a system
    in which to send a letter or note between friends should have a cost similar to that of
    a postage stamp; similarly we do not wish to charge a high fee to transmit long files
    between professional collaborators. Such an approach could lead to underutilization
    of the electronic medium

They didn't want to deter any one from using the system. Their view was if you charged for email people wouldn't use email.
Only bad actors, those spamming the system, would incur the Proof of Work.
It was never intended as a solution for normal system usage as it has been applied in cryptocurrency.

Remember Bitcoin was the very first cryptocurrency. 
In the early days the developers would have wanted to attract people to use this new technology.
I think it makes sense that they would have considered using computing resources as a better incentive rather than charging fees.
But I don't think they would ever have anticipated the exponential growth in usage that has led to the problems in today's Bitcoin network.

In software engineering, mistakes are nearly always made in the first implementations.
The second and third generation cryptocurrency platforms are addressing many of these mistakes.

The IEEE, the world's largest technical professional organization,
in their code of ethics [5] state that professionals should "strive to comply with ethical design and sustainable development practices".
Correspondingly, the ACM, who award the Turing prize, computer science's Nobel prize, 
in their code of ethics booklet [6] section 1.2 state we should avoid harming the environment and 
"when that harm is unintended, those responsible are obliged to undo or mitigate the harm as much as possible".
It is our duty as computer professionals to correct what we have done wrong.
But since Proof Of Work is already widely used by many cryptocurrency platforms I think some regulation will be needed.
There is a significant development cost to move to the better solution and that will not be done without encouragement.      

There is much hype around Bitcoin, many have invested before understanding these technical flaws and there is a lot of speculation in the market.
But it is technically possible for any cryptocurrency to migrate from a Proof of Work to a Proof of State model which will substantially reduce the enivironmental cost.   

And what we do know is that Proof of Work is causing unnecessary pollution to our environment. We wouldn't allow this in any other industry. So WHY should we tolerate it in the IT industry?

Eliminating this unecessary environmental cost would be a great first step forward in the world's battle with climate change.
I think the time is now right for the US and EU regulatory bodies, and other regulatory bodies around the world to ban Proof of Work from use in any existing or future cryptocurrency platforms.

[1] Lex Fridman. "Lex Fridman Podcast and other videos."\
https://www.youtube.com/user/lexfridman

[2] Leslie Lamport, Robert Shostak, Marshall Pease. "The Byzantine Generals Problem"\
https://dl.acm.org/doi/10.1145/357172.357176

[3] Satoshi Nakamoto. "Bitcoin: A Peer-to-Peer Electronic Cash System"\
https://bitcoin.org/bitcoin.pdf

[4] Cynthia Dwork and Noni Naor (1993). “Pricing via Processing, Or, Combating Junk Mail, Advances in Cryptology”.\
https://web.cs.dal.ca/~abrodsky/7301/readings/DwNa93.pdf

[5] IEEE "IEEE Policies, Section 7 - Professional Activities"
https://www.ieee.org/about/corporate/governance/p7-8.html

[6] ACM Association for Computing Machinery. "ACM Code of Ethics and Professional Conduct"
https://www.acm.org/binaries/content/assets/about/acm-code-of-ethics-booklet.pdf

_Donal Hurley is a Software Engineer in Dublin. He currently works on a contract with the IBM Security Services team. He can be found on Twitter at_ **@donalthurley**.
