# Tech Stack

We need something, that allows people to create data that is private. 
Like aims (mprnc) or interaction reports (repeer). 

This private data should 
1. persist web app shutdown 
2. sync across devices

Furthermore we need something, that allows people to publish data. 
Like aims (mprnc) that you want to make public. 
For sharing aims, a blockchain would be nice. 

Furthermore we need something like RPCs or messages that allows peoples (or webapps on behalf of them) to send requests. 
For example if you want to decide whether to do business with an agent you don't know yet, you might want to request experience that trusted agents of yours have made with this yet unknown agent. 

## Private storage providers
tbd: research 
should be end to end encrypted

It would be optimal, if you could simply specify a private storage providers in the webapp. 
All the aims (let's stick to the use case mprnc) would be stored only in your private storage provider. From there, you can as well publish them to the blockchain. You can connect aims from your private data to aims on the blockchain. 

This would allow 2 visibilities: private and public. 

Now, it would be nice, if it would also be possible to share data with certain other people.
Sharing data like this should be intended by both parties similar. 

The concept of groups can be realized subjectively. 

Maybe matrix is the right protocol for aimparency as well. 
Maybe we put contracts on blockchain but leave contract establishment and reputation systems on messaging protocols. 


## Messaging protocols 
\[matrix\]

is matrix end to end encrypted? 

## aber nochmal ohne recherche. Was wäre perfekt? 

Clients connect to servers. 
The server code is open source such that everyone can deploy his own server. 

Clients store private data on these servers. 

The servers connect p2p. Layout is calculated on 

Ok, here is the best way how to go about it: 
Implement a public only version on blockchain first in order to ICO. 
Then work on private and sharing data using e.g. the [matrix] protocol. 


There should be a solution for syncing any vue application state across devices. 
Using pinia we can also have some stores that are synced and others which are not. 

Is it reasonable to implement encrypted aims on chain? That only someone with a certain key can decrypt?

A non crypto-approach I am considering is CouchDB and PouchDB to store private data and group private data. Every communication is a group and works using a shared data base. Even 1 on 1 sharing is realized by groups. Read only is realized by groups as well. Not sure how to go about connections though. 
Maybe save connections along nodes. And store connection data (like "reasoning") at the benefitting node. Yes, I like that. 

I'll start with this. 

Blockchain is nice, but a lot of communication can be handled off chain. 
What falls away is the investment possibility. It's not anymore possible to invest in projects. This is something I liked as well. 

I like, that token holders basically define, what should be done next. Serving as some kind of voting system for the organism, where money is multidimensional, because it can be tied to "ideas" that may become more or less relevant. 

I like both approaches. So. How can I combine them? Everything on chain? Nobody cares about your goals as long as they are small. At the frontier of innovation, there is no competition, because noone knows which of all those ideas will make it. 

I do want to build it on blockchain. 
Techstack: webApp (graph) blockchain. Ich bleibe mal dabei und mache diesen ICO. 
