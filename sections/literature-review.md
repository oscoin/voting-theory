# Literature review

## Voting system requirments

- accessible
- secure
- anonymous
- verifiable

## Attack vectors

- Coercion
- Bribery
- Collusion
- Censorship
- ...

## Background & terminology

[**Arrow’s Impossibility theorem**](https://en.wikipedia.org/wiki/Arrow%27s_impossibility_theorem)

No rank-order electoral system can be designed that always satisfies these three "fairness" criteria:

- If every voter prefers alternative X over alternative Y, then the group prefers X over Y.
- If every voter's preference between X and Y remains unchanged, then the group's preference between X and Y will also remain unchanged (even if voters' preferences between other pairs like X and Z, Y and Z, or Z and W change).
- There is no "dictator": no single voter possesses the power to always determine the group's preference.

Cardinal voting electoral systems are not covered by the theorem, as they convey more information than rank orders. However, Gibbard's theorem extends Arrow's theorem for that case. The theorem can also be sidestepped by weakening the notion of independence.

[**Condorcet paradox**](https://en.wikipedia.org/wiki/Condorcet_paradox)

A situation in which collective preferences can be cyclic, even if the preferences of individual voters are not cyclic. This is paradoxical, because it means that majority wishes can be in conflict with each other: Majorities prefer, for example, candidate A over B, B over C, and yet C over A. When this occurs, it is because the conflicting majorities are each made up of different groups of individuals.

Thus an expectation that transitivity on the part of all individuals' preferences should result in transitivity of societal preferences is an example of a fallacy of composition.

[**Duverger's law**](https://en.wikipedia.org/wiki/Duverger%27s_law)

[**Condorcet's jury theorem**](https://en.wikipedia.org/wiki/Condorcet%27s_jury_theorem)

[**Revelation principle**](https://en.wikipedia.org/wiki/Revelation_principle)

[**Representative democracy**](https://en.wikipedia.org/wiki/Representative_democracy)

definition: elected officials representing a group of individuals, rather than direct democracy

[**Sortition**](https://en.wikipedia.org/wiki/Sortition)

definition: selection of political officials by randomly sampling from a larger candidate pool, ex. jury selection in the U.S.

[**Proportional representation**](https://en.wikipedia.org/wiki/Proportional_representation)

definition: selection of political officials in proportion to the electorate's support of political parties.

**Condorcet efficiency**

> The Condorcet winner in an election is the candidate who would beable to defeat all other candidates in a series of pairwise elections. The Con-dorcet  e½ciency  of  a voting  procedure  is  the  conditional  probability  that  it will  elect  the  Condorcet  winner  ,given  that  a  Condorcet  winner  exists. [Gehrlein (2000)

**Chain-of-custody**

## Voting schemes

### Plurality

  - Gerrymandering
  - Strategic voting

### Ranked a.k.a. ordinal or preferential voting

  - Instant-runoff voting
  - Single transferable vote
  - Borda count
  - Positional voting

### Condorcet methods

### Cardinal voting

- Approval voting
- Score / range voting

### Delegative a.k.a. liquid democracy

### Quadratic voting

### Futarchy

**Bitcoin***

- [Paul Sztorc, The Win-Win Blocksize Solution](http://www.truthcoin.info/blog/win-win-blocksize/)
- [Paul Sztorc, Fork Futures (via the Exchanges)](http://www.truthcoin.info/blog/fork-futures/)

**Amoveo**
- [Amoveo’s First Futarchy Market](https://medium.com/@tallakt/amoveos-first-futarchy-market-233d01b9fe53)
- [Zack Hess, Futarchy for Blockchain Updates](https://github.com/zack-bitcoin/amoveo/blob/master/docs/design/futarchy_for_blockchain_updates.md)

## Ballot design

[R. Michael Alvarez, Ballot Design Options](http://vote.caltech.edu/working-papers/4)


## Electronic voting

Gritzalis (2002)

### Secret ballot

Fundemental conflict between verifiability and anonymity.

Two main secret ballot methods have been applied to design e-voting schemes: mix networkand homomorphic tallying. Both methods can protect vote privacy when thresh-old trust is assumed.

Mix networks are better suited for elections with a large number of candidates or choices (e.g. preferential voting) whereas homomorphic tallying is more suitable for elections with a small number of candidates or choices (e.g. “YES/NO” voting) as the latter’s cost is linear in the number of candidates or choices.


### Receipt vs receipt-free

Chaum (2002)


### Voter apathy

Many elections suffer from an incentive problem in which voters are unwilling to pay the 'cost' of going to the polls, instead relying on others to determine the outcome. Whether voter apathy constitutes a tragety of the commons is debatable semantically.

The philisophical underpinnings of this phenomenon are often termed the [paradox of voting](https://en.wikipedia.org/wiki/Paradox_of_voting)

- [reasons to vote](https://plato.stanford.edu/entries/voting/#1)
- compulsory voting



### Criticisms of online voting

- In order to prevent vote selling, or coersion, voters must not be able to prove how they voted.
- Denial of service attacks

> Best practices for Internet voting are like best practices for drunk driving. —Ron Rivest

Given the importance of elections and their inherent coordination complexity, the branch of systems theory dealing with high-risk technologies, natural accident theory, can be useful for understanding voting system robustness. This approach maps well to computer security analysis and works from the premise that potential for failure increases with increasing complexity when components are tightly coupled and have the potential for unpredictable feedback loops. In this regime, failures do not occur due to vulnerabilities within individual components (which should be designed in anticipation some failure distribution), but due to the unexpected interaction of errors. (Moynihan, 2004)

In this regard, we may glean some insight from the principle of least authority, defensive consistancy, and the object capabilities literature, which aims to maximally encapsulate component behaviour. Additionally, elections may be derisked with checks and balances i.e. redundancy, process transparency, and by rewarding error discovery and responsible reporting.


## References

Donald Moynihan (2004)
Building Secure Elections: E-voting, Security, and Systems Theory,
https://pdfs.semanticscholar.org/34fe/32e029ee0a2c07fd36f64a1c5095af352f2a.pdf

Mark Miller (2006), 29
Robust Composition:Towards a Unified Approach to Access Control and Concurrency Control
http://www.erights.org/talks/thesis/markm-thesis.pdf#page=47

Dimitris Gritzalis (2002)
Principles and requirementsfor a secure e-voting system
https://arena-attachments.s3.amazonaws.com/4229454/b108661f2b8d32786a4c8768cd2ea472.pdf

David Chaum (2002)
Secret Ballot Receipts and Transparent Integrity: Improving voter confidence and electronic voting at polling places
http://www.notablesoftware.com/Papers/Chaum%20Secret%20Ballot%20Receipts.pdf

William Gehrlein (2000)
Condorcet efficiency: A preference for indifference
https://arena-attachments.s3.amazonaws.com/4269946/71308f88e189a0dd459ec03319d298ef.pdf

[Democratic Mediums](https://medlabboulder.gitlab.io/democraticmediums/) - a directory of patterns for decision, deliberation, and noise maintained by Nathan Schneider
