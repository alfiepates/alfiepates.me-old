+++
categories = []
date = "2015-09-09T00:17:59+01:00"
description = ""
keywords = []
title = "AlotBot Reference Guide"

+++

Hey! Here's the (unofficial) reference for [SN4T14's AlotBot](http://github.com/SN4T14/AlotBot), the resident IRC bot of #DataHoarder on Freenode.  AlotBot was originally meant to be a joke, to provide tongue-in-cheek corrections when users typed "alot" and meant "a lot". From there, it spiralled out into the wonderfully useful tool you use today.

*Note: [Testing this bot was real fun](http://i.imgur.com/crsoi5U.png).*

Plugins
========

`alot.js` / `allot.js`
----------------------

Corrects users who type 'alot' or 'allot' when they mean 'a lot'.

### Usage

Send a message containing the word 'alot' or 'allot'.

```
alfiepates: i just ate alot of food
  AlotBot: Oi! alfiepates! "alot" is not a word! "a lot" is the correct term!
```
```
alfiepates: there sure are allot of spelling mistakes in this channel
  AlotBot: Oi! alfiepates! "allot" is not a word! "a lot" is the correct term!
```

`xbmc.js`
---------

Makes users aware that the XBMC project is now called Kodi.

### Usage

Send a message containing the word 'XBMC'.

```
alfiepates: my HTPC runs XBMC
   AlotBot: Oi! alfiepates! "XBMC" is the old name! It's now called "Kodi"!
```

`zol.js`
--------

Points users towards [SN4T14's ZFS on Linux stability rant](http://sn4t14.com/zol/).

### Usage

Send a message starting with 'AlotBot' and containing either 'ZOL' or 'ZFS on Linux'.

```
alfiepates: AlotBot, tell me about ZOL
   AlotBot: Here you go: http://sn4t14.com/zol/
```
```
alfiepates: AlotBot, why is ZFS on Linux unstable?
   AlotBot: Here you go: http://sn4t14.com/zol/
```

`datahoarderWiki.js`
--------------------

Fetches a link to the [/r/DataHoarder wiki](http://reddit.com/r/DataHoarder/wiki).

### Usage

Send a message starting with 'AlotBot' and containing the phrase 'datahoarder wiki'.

```
alfiepates: AlotBot, where's the datahoarder wiki at?
   AlotBot: Here you go: http://reddit.com/r/datahoarder/wiki
```
