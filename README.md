# adaptive_auctions
In this project, the goal is to obtain a sequence of auction designs that maximizes the auctioneer's revenue over the course of an episode (a specific sequence of auctions). Our adaptive approach is based on a data-driven learning process in which the seller adjusts the parameters of the auctions (i.e. the reserve price, the number of slots for the ads, etc) as the episode progresses and she observes the bidders' behavior. We define a design as a unique combination of auction parameters. In addition to varying some parameter values, we also implement the algorithm with two different auction types: GSP and VCG. We then compare the results of the adaptive mechanism with the ones of a traditional fixed mechanism.

Implementing Bandit Algorithm in: Pardoe et al, 2010, Adaptive Auction Mechanism Design and the Incorporation of Prior Knowledge, INFORMS Journal on Computing Vol. 22, No. 3, Summer 2010, pp. 353–370

Other references:

Edelman et al, 2007, Internet Advertising and the Generalized Second-Price Auction: Selling Billions of Dollars Worth of Keywords, The American Economic Review Vol. 97 No. 1

Varian et al, 2014, The VCG Auction in Theory and Practice, American Economic Review: Papers & Proceedings 2014, 104(5): 442–445


