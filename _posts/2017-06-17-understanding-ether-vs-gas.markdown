---
layout:	post
title:	"Understanding Ether vs Gas"
date:	2017-06-17
image: /images/medium/1*5fEH_VaGc31odyrn9wmEMQ.png
imagehero: true
tags: Blockchain
---

Within Ethereum, there are two native “tokens”, Ether and Gas. But the complex relationship between them often causes some confusion as to their distinction and differing purposes and so this post tries to clear up some of the confusion.

Think of Ether and gas as two different things. Ether is a currency. It *needs* to have intrinsic value as that is the purpose of currency (also *something* needs to have intrinsic value in order to mint as a reward to incentivize people to secure the system). Gas on the other hand is a commodity, like oil. It is essentially a cost of using the system. In this way, it can be thought of as the oil to run your car.

Gas could potentially have no intrinsic monetary value other than allowance to use the system. However, because this isn’t an ideal world where distribution of system operation (whether its through mining or stake) isn’t the same as the system usage (making of transactions), it is necessary for the gas to have intrinsic value as well so those who have gas (from helping operate the system) can trade it to people who need gas (those who use the system) in exchange for something of equivalent intrinsic value. This is the same reason why oil has a price as well.

Now, this is where the difference with oil arises. Ethereum could have implemented Gas as a separate token from Ether (oil is something completely separate from dollars). However, then *every time* you needed to make a transaction and don’t have the gas for it, you’d have to exchange something of value (could be Ether or anything else) for gas. This is massively inefficient. So instead, they implemented Gas as an interface on top of Ether. That way a certain amount of Ether *IS* a unit of gas. With oil, this would be the difference between one barrel of oil costing $50 and one barrel of oil being physically made of $50. Now you can just turn any Ether you have laying around into Gas. It’s essentially an immediate two way peg between Ether and gas.

But the important thing is that these are still two different things. This is why there is a separate Ether market and Gas market. The price of Gas can fluctuate without affecting the price of Ether. The price of Ether can fluctuate without affecting the *real price* of Gas because the Gas/Eth market can react to counteract changes in the Eth/USD market (real value is defined by USD cause it’s the best unit of measure we have).

The value of Ether can still grow based on the increase in adoption of the overall Ethereum system (or speculation of said adoption), even if gas costs went down. As a real world analogy: even though oil refining has become more efficient over time, the explosion of oil use by consumers hasn’t resulted in a decline in the price of a barrel of oil. The real price of oil still grows. Effectively, the growth of the market outpaces the impact of technological gains in efficiency on the price of the oil.

  