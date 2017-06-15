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
The ingame name of the player. This field is case sensitive, and autocompletion is enabled by default.

.. object:: block
The **raw name** of a compressed block, with **small caps** only. Here is the list of the raw names:

==================  ==============================
Raw name            Name
==================  ==============================
**Woods blocks**
------------------  ------------------------------
oakwood             Compressed Oak Wood (Log)
sprucewood          Compressed Spruce Wood (Log)
birchwood           Compressed Birch Wood (Log)
junglewood          Compressed Jungle Wood (Log)
acaciawood          Compressed Acacia Wood (Log)
darkoakwood         Compressed Dark Oak Wood (Log)
------------------  ------------------------------
**Planks blocks**
------------------  ------------------------------
oakplank            Compressed Oak Planks
spruceplank         Compressed Spruce Planks
birchplank          Compressed Birch Planks
jungleplank         Compressed Jungle Planks
acaciaplank         Compressed Acacia Planks
darkoakplank        Compressed Dark Oak Planks
------------------  ------------------------------
**Falling blocks**
------------------  ------------------------------
gravel              Compressed Gravel
sand                Compressed Sand
redsand             Compressed Red Sand
------------------  ------------------------------
**Stone blocks**
------------------  ------------------------------
stone               Compressed Stone
granite             Compressed Granite
diorite             Compressed Diorite
andesite            Compressed Andesite
------------------  ------------------------------
**Other blocks**
------------------  ------------------------------
dirt                Compressed Dirt
cobblestone         Compressed Cobblestone
soulsand            Compressed Soul Sand
netherrack          Compressed Netherrack
==================  ==============================
.. object:: amount
Optional field: the amount of given blocks. It need to be a number between 1 and 2305. By default, if the amount is omitted or has a wrong value, it give 1 compressed block.

