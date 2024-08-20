+++
title = 'IRC/XMPP Update 1'
date = 2024-08-20T13:14:25-05:00
draft = false
+++

After a long while of waiting we are happy to announce the first IRC/XMPP progress update.

Here are all of the updates since the initial shutdown due to abuse.

## Discussion
A ticket has been made with multiple members of the community and system administrators to discuss the future of the IRC/XMPP servers. This is still ongoing and we will update you further when we have more information.

Currently, the discussion is focused on the following topics:
- The future of the existance of the IRC/XMPP servers
- Moderators and administrators for the servers
- Automated moderation
- Discord linking
- User registration

## IRC
Due to IRC being older and less modern than XMPP, it is possible that XMPP may gain priority. We currently rely on the [Ergo](https://github.com/ergochat/ergo) IRC server software due to its modern features and ease of use, however it is likely that we will switch to a different software in the future.

A [issue](https://github.com/ergochat/ergo/issues/2179) was made on the Ergo GitHub repository to discuss slowmode/filters.

## XMPP
XMPP runs [Prosody](https://prosody.im/) as the server software. Due to prosody's module system and being more modern than IRC, it is likely that XMPP will be easier to moderate and maintain.

## Matterbridge
We are currently using [Matterbridge](https://github.com/42wim/matterbridge) for linking IRC, XMPP and Discord. Some work may be done on this front for the automod system to avoid dealing with 2 different systems.

## Conclusion
Discussion is still ongoing but has been going fairly slow. Once more progress gets made a new update will be posted.
