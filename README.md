# Playcoin
P2P exchange for digital content, distribution and payment

- Author: Richard Caetano, caetano@gmail.com
- Date: July 1st, 2013

## Abstract

Playcoin is a crypto-currency, similar to Bitcoin, which can be used to purchase digital media directly from the content creator.  Playcoins are earned by mining or purchased from an exchange and can be used to purchase media files.  Those who purchase the media are then able to host the media for sale to others while earning a small download fee thus creating an incentive to not pirate the media.  

## Introduction

Media distribution has transitioned from a product in physical space to a commodity in digital space.  Markets, copyright law and ownership of the media had clear and well defined boundaries with physical products (CD, DVD, etc) as a distribution medium.  However, in the digital domain, sharing in an inherent attribute of the digital product, the media file.

This of course has caused much disruption for the music and film industries.  These industries were established by selling ownership to physical products.

Yet, grasping at a paradigm that supports products in a physical space will limit the opportunities of what’s possible with emerging and unstoppable technologies such as BitTorrent and Bitcoins.

What is needed is a built-in mechanism to compensate digital content creators directly for usage of their content rather than selling ownership of a product.  

With a payment mechanism built in, content creators can encourage sharing of the media while expecting direct payment from from the consumer.


## Concepts

- Virtual Property 
- Playcoins
- Content Creator
- Media Hosts
- Mining
- Storage
- Streaming
- Consumers
- Economics

## Virtual Property

Virtual property are digital objects, or media files, that are not controlled by a central authority, can be exchanged between peers and yet can only have a single owner for direct royalties and payments.

[Bitcoin Wiki Contracts](https://en.bitcoin.it/wiki/Contracts)


## Playcoins

A new unit of currency is introduced to enable specific operations. Playcoins are earned by these operations:

- *Mining*: Confirming blocks of transactions (a la Bitcoin)
- *Storage*: By hosting media files, miners earn a download fee.
- *Streaming*: By serving streaming access, miners earn a streaming fee.

## Content Creator

**Content Creators** are entities who wish to release a digital media file into the Playcoin ecosystem.  

Content Creators set the Playcoin purchase price and an optional streaming price which is signed and timestamped on the block chain.  Price changes can be posted at any time and cost a small listing fee.  The fee is collected by the miner who confirms the listing.

The media file and price update are described as a **Media File Listing**.  Hosts broadcast queries for media file listings between each other.

When a media file is purchased, it is encrypted with the buyer's public key and made available for download over the P2P network 

## Media Hosts

Media files on the network are distributed via **Media Hosts**.  Media hosts connect to the P2P network and can do the following:  

- Connect and interact with other hosts on the Playcoin network to search for content or other social networking aspects.
- Earn Playcoins by mining
- Purchase media from content creators stored by other hosts
- Earn **Download Fee** for storing content purchased by other hosts
- Earn fees for streaming content

## Mining

Mining is the process of using computation power to secure Playcoin transactions against reversal and introducing new Playcoins to the system.

See [Bitcoin Mining](https://en.bitcoin.it/wiki/FAQ#Mining)

## Storage

Playcoins can be used to purchase a copy of a media file from any **Storage Host** who has previously purchased the file.  

The purchase price is set/updated by the content creator while the media host sets and keeps a small **Download Fee**.

[DRAFT] When a media file is purchased from a storage host, the file must be encrypted with the purchasing host's public key and include a chain of purchases originating back to the original content creator.

Media file integrity is validated by the hash of the original content creators signature.

## Streaming

[Draft Proposal]  Media Hosts may "friend" another host and stream their content paying an optional fee.  Availability is subject to the media host's uptime.  The server Media Host may set some restrictions, 30 sec clips only, 0 or more repeats, etc to encourage the purchase of the media.

## Consumers

Consumers who wish to listen/watch a media may pay the Playcoin price to obtain a copy or pay a smaller price to stream.

Consumers who have a catalog of media automatically become storage hosts who can earn Playcoins for storage or streaming.

For immediate use, consumers may purchase Playcoins on open digital exchanges.  Or, consumers may choose to earn Playcoins by mining them over time.

## Economics 

- *Playcoins are limited and distributed over time* at the inverse of computing power.  Playcoin price discovery happens through open exchanges (Playcoin/Bitcoin, Playcoin/USD, etc)

- *Playcoins have a built in demurrage of 5% a year* to encourage spending rather than hoarding.

- *Playcoins are rewarded to miners* for confirming transactions.

- *Content creators provide media content* with a purchase price set in play coins.

- *Content Creators exchange their Playcoins for other currencies* through open exchanges.

- *To earn Playcoin download fees, Storage Hosts store purchased copies* of media file.  This is the incentive to purchase and store content rather than sharing it.



