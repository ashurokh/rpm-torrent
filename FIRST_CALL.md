# Introduction #

Bittorent client in JAVA. (Tool to provide better way of using P2P network)

## **About Bittorent protocol** ##

**Bit torrent** is a P2P File Sharing protocol
Torrent file contains information about the files to be shared and the tracker to contact
Tracker coordinates the peers exchanges for given torrent files

_What are we going to Do ?_

As there are lot of implementation of Bittorrent protocol and, so, many Bittorrent clients. But there are only few of them that are written in Java. Actually, the only one that we found is the Azureus client. It is an amazingly complete client, with many features, plug-in and so on. And as it is very complete, it is in the same time very complex, with many interfaces and no real API available. The idea then was to create a new client, i.e. a new implementation of the protocol, as an API with maybe less features, but with a much lower complexity, a client that can be easily understandable and updatable for future work on it and therefore easily embeddable in another application.