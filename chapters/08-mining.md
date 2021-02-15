# Bitcoin Mining

This book is designed to teach you how to safely and effectively store and
spend bitcoin. You don't need to know anything about mining to do this. However,
mining plays a critical role in making bitcoin function for millions of people
year after year.

What follows is an overview of bitcoin mining. It's not technical at all and
it introduces some of the major properties of Bitcoin that every Bitcoin owner
should be aware of. If any of this sparks your interest, there are plenty of
online resources that go deeper.

## What is Mining?

Bitcoin mining is how new bitcoin gets created. However, this isn't the purpose
of mining. The purpose is to provide a distributed clearing house for securely
processing bitcoin transactions. The creation of new bitcoin is just the incentive
to get people to dedicate resources toward creating a computer network that can
achieve this.

Mining is what makes bitcoin special. Its a decentralized security mechanism that
secures the bitcoin system from attack and enables computers all over the world
to come to consensus without a central authority.

Miners validate new transactions and periodically add them into a new block which
contains all the transactions that occurred since the last block was "mined".
About every 10 mins that block gets added to the blockchain where everyone can
see the transactions.

Miners are special computers that are built to only run the bitcoin mining algorithm
as efficiently as possible. Miners all over the world are competing in a game
to see who will be the first to find the needle in the haystack. All these computers
are churning away trying to guess a number that solves a complex math problem.
The miner that solves it has successfully mined the block and gets to keep the
newly created bitcoin for himself. This brute-force guessing game is called
Proof of Work (PoW) and the number of guesses a miner can make per second is called
the Hash Rate.

## Proof of Work

In the Bitcoin system, the only way for a new block to get added or for bitcoin
to move from one address to another is for a miner to guess the right number.
A miner that makes 1000 guesses per second has a much lower chance of winning
than a miner that makes 100,000 guesses per second. This means that if a
miner successfully adds a block, he has proved his ability to perform a considerable
amount of computational work compared to the other competing miners (or he just
got lucky and guessed the correct number before the others).

PoW is important because it makes it expensive to cheat. Suppose, I want to mine
a block that contains a false transaction that I've inserted. In order to insert
a false transaction, I would not only have to be the one who adds the block but
I would also have to control more than 50% of the mining power or hash rate of
the entire Bitcoin network so that my malicious miners would overrule the honest
miners by agreeing that the block is valid when it actually isn't.

PoW makes it so that an attacker would make more money by being an honest miner
and putting his computational energy towards making bitcoin more secure, than
trying to attack the network.

Bitcoin's PoW is made even stronger by a scheduled difficulty adjustment that makes
Bitcoin even more resilient in the long term.

## Difficulty Adjustment

24 hours a day, 7 days a week, 365 days a year, miners all over the world are
guessing numbers until one is granted the winner, a new block gets added to the
chain, all the transactions in that block get confirmed, and then they all start
again.

On average this whole process takes 10 minutes. When there were just a few miners,
it took 10 mins, and even today with exponential growth in the number of guesses,
it still takes about 10 mins. This is by design.

The guessing game these miners are playing gets harder or easier depending on how
quickly new blocks get added. Every two thousand and sixteen blocks (or about
every 2 weeks), the network checks the average time it took for a new block to get
added and it adjusts the difficulty of the game for the miners so that the average
block time stays close to 10 mins.

This ensures that blocks get added at a steady rate regardless of how many miners
there are. This is important because bitcoin is still very volatile and miners
are trying to run a business. Miner's usually sell the Bitcoin they earn immediately
to cover their electricity costs.

When the price of bitcoin falls, some miner's suddenly can't pay their electric
bill and are forced to turn off their miners until it becomes profitable again.
With less miners playing the guessing game, blocks take longer and longer to get
added.

After two thousand and sixteen blocks, the difficulty will be lowered. This makes
the game easier to win and more miners will come online, increasing the hash rate
of the network and thus the security provided.

When the price of bitcoin rises, more and more miner's come online to cash in.
This speeds up the rate of new blocks and is actually dangerous to the security
of the network if left unchecked.

After two thousand and sixteen blocks, the difficulty will rise making the game
harder. This will cause many miners to stop being profitable because their
electricity costs were too high. Those miners will go offline until the difficulty
lowers or they can afford better, more powerful mining machines. This causes the
miner's who are operating their businesses the most effectively to survive.

In the long term, the difficulty adjustment maintains a threshold level of incentive
for miners to continue securing the network no matter what kind of volatility
the price endures.

## Miner Payouts and Halvings

When a miner finds the golden number, it wins the ability to construct the block
of transactions. That miner gets to keep all the transaction fees for all the
transactions added to the block and the network allows the miner to insert one
transaction at the top of the block that rewards himself some Bitcoin out of thin air.

But hold on, isn't Bitcoin scarce?

Bitcoin is scarce, there will only ever be 21 Million Bitcoins. The amount a miner
is able to pay himself is fixed and about every 4 years, that amount gets cut in
half. This happens every 210K blocks and its called a "halving".

When BTC was invented in 2009, 50 BTC were created with every block. Then in 2012,
only 25 BTC were awarded for adding a block. In 2016, the mining reward was cut
again to 12.5 BTC. The last halving happened in 2020 and now only 6.25 BTC are
mined each block.

This process of halving the block reward will continue until about the year 2140
when no new bitcoin will be added, not even a single sat. At this point, the miner's
only reward will be the transaction fees paid by users of the bitcoin network.

## Should I Become a Miner

For most people, the answer is "No". Mining is incredibly competitive and only
really profitable if your electricity is nearly free. In the early years of
Bitcoin, people could be competitive miners just by running a program on their
desktop computers. Then they started using racks of graphics cards to guess
numbers even faster than a regular PC. After ASICs (Application
Specific Integrated Circuits) came on the scene, the ability to mine competitively
quickly left the consumer space. Modern ASIC miners are expensive, loud and use
lots of power. Some of the most innovative mining operations today get their power
from renewable sources or partner with oil and gas drillers to use energy that
would otherwise go to waste.

Globally, these independent mining operations compete with one another for profit,
but together, they make up the world's most powerful super computer who's sole
purpose is to back the world's largest global currency.
