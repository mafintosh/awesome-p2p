# Awesome P2P

A list of great resources on p2p things.
The content here is curated by me, [@mafintosh](https://github.com/mafintosh) but please open PRs with suggestions.

## Protocols

Existing systems that I really like for the simplicity and ingenuity

* [BitTorrent - no nonsense specification. Easy to read and implement](https://wiki.theory.org/BitTorrentSpecification)
* [PPSP - one of the papers that has inspired me the most in terms of making a modern file sharing network](https://datatracker.ietf.org/doc/rfc7574/?include_text=1)
* [Scuttlebutt replication - Simple/efficient way of replicating append-only logs](http://www.cs.cornell.edu/home/rvr/papers/flowgossip.pdf)

## Data integrity / authentication

Ways of securing / verifying data when receiving it from untrusted peers

* [Dominic Tarr on asymmetric crypto](http://dominictarr.com/post/106497926352/asymmetric-cryptography-works-like-magic)
* [Dominic Tarr on hashes](http://dominictarr.com/post/154769946347/fairly-tale-cryptography-2-hashes)

## DHT / Peer discovery

In a distributed system finding other peers interested in the same topic as you is usually an important step.

* [Kademlia. Probably the simplest DHT out and a very well written paper. Use the key value store to point p2p key -> ip:port for discovery](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf)

## Connectivity

How to connect to other peers

* [ZeroTier blog post about hole punching](https://www.zerotier.com/blog/?p=226)
* [pwnat - two-way hole punching with no 3rd Party](https://samy.pl/pwnat/)
