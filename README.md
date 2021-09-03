## About
What is Dione? Excellent question! Dione is the attempt to create a simple, decentralized messaging
system that also provides maximum anonymity and security.

The backbone of Dione is a P2P-Network of servers that provide the infrastructure of the messaging system.
This includes mainly the storing and providing of messages. However, these messages are, unlike in other systems, not stored as a whole.
Instead, they are split up into several parts that all have to be retrieved and put back together in order to get the send message.

The location of these parts are determined by address ratchets, similar to encryption double ratchets. The  strings
given by the address ratchets are resolved into real nodes in the P2P network.

A more detailed description is currently WIP, as well as a standardization of the whole protocol.
