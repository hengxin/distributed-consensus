# Paxos

## Papers

## Videos
- [Consensus Algorithms in Distributed Systems](https://youtu.be/9QTcD8RrBP8)

Scale By The Bay, Yifan Xing, 2018 

- [Consensus Algorithms in Distributed Systems](https://youtu.be/8b0K53Qd1fo)

Lambda World, Yifan Xing, Nov 2018

On Paxos, Multi-Paxos, and Raft

> This talk brings the principles used in academia to the industry 
by introducing the common distributed systems protocols implemented underneath the popular services. 
In addition, this talk will compare the differences between how the protocols are used 
in both academia and the industry.

## Websites Dedicated to Paxos
- [Paxos Made Moderately Complex](http://paxos.systems/)
This website explains the infamously difficult to understand Paxos consensus protocol 
using easy to understand invariants and code.

## Blogs Explaining Paxos
- [How Paxos works](http://rystsov.info/2015/09/16/how-paxos-works.html)

By Rystsov Denis, 2016.

## Visualization
- [Visualization of a Paxos-based distributed state machine](http://rystsov.info/2016/05/01/paxos.html)

By Rystsov Denis, 2016.

## Implementations

## Uses
- [TreodeDB](http://treode.github.io/)

Across nodes, TreodeDB uses mini-transactions, 
similar to Sinfonia (ACM, PDF) and Scalaris (ACM, website), 
and it uses *single-decree Paxos* to commit or abort a transaction. 

- [basho/riak\_ensemble](https://github.com/basho/riak_ensemble)

Multi-Paxos framework in Erlang

`riak_ensemble` is a consensus library that supports creating multiple consensus groups (ensembles). 
Each ensemble is a separate Multi-Paxos instance with its own leader, set of members, and state.
