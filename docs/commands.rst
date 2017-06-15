Commands
========

==================================  =========================================================
Commands                            Description
==================================  =========================================================
/help cb                            Get general information about the commands of the plugin.
/cb                                 Basic plugin command; return the same as /help cb.
/cb info                            Get plugin general information
/cb give <player> <block> [amount]  Give compressed blocks to a player
==================================  =========================================================

The give command
----------------
|   This plugin injects special metadata into the skull (head) blocks. It helps to recognize it, and avoid these blocks to be created in any other way than by crafting it. Event the Essentials' /give command can not create a compressed block.
|   That's why the **/cb give** command exists. And here is some useful information about its parameters:

.. centered:: /cb give <player> <block> [amount]

.. object:: player
|   The ingame name of the player. Autocompletion is enabled by default for this field.

.. object:: block
|   The name of a compressed block, with **small caps** only.