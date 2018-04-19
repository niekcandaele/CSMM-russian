In-game features
=================

Country ban
-----------

Select countries that you do not wish on your server. CSMM will automatically kick anyone joining from an IP in these countries.

**Note** This is very naive protection. Users can get around this with VPN/proxies. 

Commands
--------

calladmin
^^^^^^^^^^
Create a support ticket. CSMM will collect some data such as your inventory and location to display along the ticket.

Custom commands
^^^^^^^^^^^^^^^^

Admins can create custom ingame commands. You can set delay, timeout, cost of the command.

For example: 

$discord::

    say linkToDiscord

You can execute multiple commands by separating with ";"::

    say "Here is one message";say "Here is the second!"

You have access to the players steam and entity ID with "${steamId}" and "${entityId}"::

    sayplayer ${entityId} "WAZAAAAAAAAAAAAA"


Examples

$safehouse::

    teleportplayer ${entityId} 15 85 -53; sayplayer ${steamId} "You are safe now."





Message of the day
------------------

Set a message to be sent to players when they join the server and/or show this message periodically to all players.

This is useful to advertise your discord server, remind people to abide by the rules etc



Support tickets
-----------------

Players can create support tickets with the corresponding command (if enabled). This is a great way for players to ask admins for some assistance, even when there is no admin currently online.

Economy
---------

Currently in beta - donator only

The economy module allows admins to set a cost to multiple actions (teleports, custom commands, ...). Players can earn money by being ingame