---
label: Usenet
order: -5
description: Get Started with Usenet
image: https://user-images.githubusercontent.com/78981416/215252980-0a038d94-b05c-4e52-83b4-51948df6a591.gif

---

# Usenet

## Getting started

You will need 3 things at a basic level before you can download anything:
- A usenet provider, which will provide servers to download content from. You have to pay for one and many offer in-bulk deals (yearly) which can average out to as low as 3-4 USD a month.
- An NZB indexer, this is where you will get your `.nzb` file. An `.nzb` file is akin to a `.torrent` file in that it contains a map pointing to the location of the content that you want to download. These can be paid, free, public or private. Just like torrents, private ones are better than the public ones. Indexers usually have a heavily limited free tier and you'll have to pay for full functionality.
- [SABnzbd](https://sabnzbd.org/), which is a download client, into which you will feed your `.nzb` files in order to begin downloading your desired content. Make sure to put your SABnzbd behind a strong password.

!!!warning Warning
[NZBGet](https://github.com/nzbget/nzbget) has been deprecated by its developers. It will not receive any more updates.
!!!

## PAR

A file that contains the computed parity bits from a source file. PAR files are generated from Usenet archives that have been broken into multiple files because of file size limitations on news servers. A PAR file would allow the complete archive to be reconstructed if one of the files became corrupt. PAR files can also be used to verify the integrity of the complete archive. Your download client, such as SABnzbd, will automatically repair or attempt to repair broken files using par files after download.

## Anime Tosho

[Anime Tosho](https://animetosho.org/) is a free, completely automated service which mirrors most torrents posted on TokyoTosho's anime category, Nyaa.si's English translated anime category, and AniDex's anime category (filtered) onto various file hosting (otherwise known as 'DDL') services, as well as Usenet.

!!!
Animetosho skips uploading most torrents over 16GB in size and some specific exceptions, such as duplicates/reposts and excessively large versions of a file (e.g. BD remuxes)
!!!

Anime Tosho is an amazing source to download weeklies via usenet.
To use it, simply click the `NZB` button under the release title to download the `.nzb` file which you can then add to your SABnzbd and it'll start downloading.
![](https://user-images.githubusercontent.com/78981416/215181082-b1c273ed-9a2a-4b4f-a52d-e069df152645.png)

You can also directly copy the link and paste it in SABnzbd, similar to how magnet links work in torrent clients.
![](https://user-images.githubusercontent.com/78981416/215181096-ebc1c2ce-0187-4cf2-acb2-dcc67abeec6b.png)

## SeaDex

[SeaDex](https://releases.moe/) lists all the best releases for specific anime for you to download and enjoy. SeaDex releases which are under 16GB can be found on [Anime Tosho](https://animetosho.org/) while the rest are posted by `seadex@releases.moe` which you can find [here](https://www.nzbking.com/poster/seadex@releases.moe).

## Searching Indexers

You can use either Prowlarr or NZBHydra2 to search several Indexers together instead of searching them one by one.
- [NZBHydra 2 is a meta search for newznab indexers and torznab trackers](https://github.com/theotherp/nzbhydra2)
- [Prowlarr is an indexer manager for both torrent trackers and usenet indexers](https://github.com/Prowlarr/Prowlarr)

## Uploading to Usenet
You can use either of the following to upload to usenet.
- [ngPost is a CLI/GUI usenet poster for binaries](https://github.com/mbruel/ngPost)
- [Nyuu is a flexible CLI usenet binary posting tool](https://github.com/animetosho/Nyuu)

## Usenet Providers and Backbones

[![](https://user-images.githubusercontent.com/78981416/215181155-f6633053-4f7c-4f3b-8a0a-e35c215c7193.png)](https://upload.wikimedia.org/wikipedia/commons/7/7d/Usenet_Providers_and_Backbones.svg)

!!!
The above map is from https://commons.wikimedia.org/wiki/File:Usenet_Providers_and_Backbones.svg
!!!

## Related Subreddit
- [/r/Usenet](https://www.reddit.com/r/usenet/)