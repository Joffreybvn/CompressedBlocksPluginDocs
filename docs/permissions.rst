Permissions
===========

General
-------
By default, the general permissions are not given.

====================  =======  ===================================================
Permission Node       Default  Description
====================  =======  ===================================================
compressedblocks.*    False    Give all Compressed Blocks permissions.
compressedblocks.all  False    Compatibility Node. Same as **compressedblocks.\***
====================  =======  ===================================================

Commands
--------

By default, the command permission is given to OP. By this way, the command.give and command.info are given too.

=============================  =======  ===========================================================================
Permission Node                Default  Description
=============================  =======  ===========================================================================
compressedblocks.command       OP       Give all child commands permissions
compressedblocks.command.*     False    Compatibility Node. Same as **compressedblocks.command**
compressedblocks.command.all   False    Compatibility Node. Same as **compressedblocks.command**
-----------------------------  -------  ---------------------------------------------------------------------------
-----------------------------  -------  ---------------------------------------------------------------------------
compressedblocks.command.give  False    Allow to give compressed blocks to you and other players with **/cb give**.
compressedblocks.command.info  False    Allow to get general information about the plugin with **/cb info**.
=============================  =======  ===========================================================================

Compressing
-----------

A player must have a compressing permission (of a specific block or of all blocks) to be able to compress. Players that have not the compressing permission can still receive compressed blocks by the **/cb give** command.

======================================  =======  =========================================================
Permission Node                         Default  Description
======================================  =======  =========================================================
compressedblocks.compress               False    Allow to compressed all kind of blocks
compressedblocks.compress.*             False    Compatibility Node. Same as **compressedblocks.compress**
compressedblocks.compress.all           False    Compatibility Node. Same as **compressedblocks.compress**
--------------------------------------  -------  ---------------------------------------------------------
--------------------------------------  -------  ---------------------------------------------------------
compressedblocks.compress.oakwood       False    Allow to compressed Oak Wood (Logs)
compressedblocks.compress.sprucewood    False    Allow to compressed Spruce Wood
compressedblocks.compress.birchwood     False    Allow to compressed Birch Wood
compressedblocks.compress.junglewood    False    Allow to compressed Jungle Wood
compressedblocks.compress.acaciawood    False    Allow to compressed Acacia Wood
compressedblocks.compress.darkoakwood   False    Allow to compressed Dark Oak Wood
--------------------------------------  -------  ---------------------------------------------------------
--------------------------------------  -------  ---------------------------------------------------------
compressedblocks.compress.oakplank      False    Allow to compressed Oak Plank
compressedblocks.compress.spruceplank   False    Allow to compressed Spruce Plank
compressedblocks.compress.birchplank    False    Allow to compressed Birch Plank
compressedblocks.compress.jungleplank   False    Allow to compressed Jungle Plank
compressedblocks.compress.acaciaplank   False    Allow to compressed Acacia Plank
compressedblocks.compress.darkoakplank  False    Allow to compressed Dark Oak Plank
--------------------------------------  -------  ---------------------------------------------------------
--------------------------------------  -------  ---------------------------------------------------------
compressedblocks.compress.gravel        False    Allow to compressed Gravel
compressedblocks.compress.sand          False    Allow to compressed Sand
compressedblocks.compress.redsand       False    Allow to compressed Red Sand
--------------------------------------  -------  ---------------------------------------------------------
--------------------------------------  -------  ---------------------------------------------------------
compressedblocks.compress.stone         False    Allow to compressed Stone
compressedblocks.compress.granite       False    Allow to compressed Granite
compressedblocks.compress.diorite       False    Allow to compressed Diorite
compressedblocks.compress.andesite      False    Allow to compressed Andesite
--------------------------------------  -------  ---------------------------------------------------------
--------------------------------------  -------  ---------------------------------------------------------
compressedblocks.compress.dirt          False    Allow to compressed Dirt
compressedblocks.compress.cobblestone   False    Allow to compressed Cobblestone
compressedblocks.compress.soulsand      False    Allow to compressed Soul Sand
compressedblocks.compress.netherrack    False    Allow to compressed Netherrack
======================================  =======  =========================================================

Uncompressing
-------------