Permissions
===========

**Important note:** This plugin handle compatibility nodes, in order to be compatible with as many permission's plugin as possible. That's why some nodes are duplicated, like **compressedblocks.\*** and **compressedblocks.all**. Theses permissions have the same effect, and you don't need to add both. Simply write the one designed for you permission plugin.

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
compressedblocks.command.*     False    **Compatibility Node**. Same as above.
compressedblocks.command.all   False    **Compatibility Node**. Same as above.
-----------------------------  -------  ---------------------------------------------------------------------------
-----------------------------  -------  ---------------------------------------------------------------------------
compressedblocks.command.give  False    Allow to give compressed blocks to you and other players.
compressedblocks.command.info  False    Allow to get general information about the plugin.
=============================  =======  ===========================================================================

Compressing
-----------

A player must have a compressing permission (of a specific block or of all blocks) to be able to compress. Players that have not the compressing permission can still receive compressed blocks by the **/cb give** command.

======================================  =======  =========================================================
Permission Node                         Default  Description
======================================  =======  =========================================================
compressedblocks.compress               False    Allow to compressed all kind of blocks
compressedblocks.compress.*             False    **Compatibility Node**. Same as above.
compressedblocks.compress.all           False    **Compatibility Node**. Same as above.
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

The uncompressing nodes are the same than the compressing one. Just replace **compressing**  by **uncompressing**.

========================================  =======  ========================================
Permission Node                           Default  Description
========================================  =======  ========================================
compressedblocks.uncompress               False    Allow to uncompressed all kind of blocks
compressedblocks.uncompress.*             False    **Compatibility Node**. Same as above.
compressedblocks.uncompress.all           False    **Compatibility Node**. Same as above.
----------------------------------------  -------  ----------------------------------------
----------------------------------------  -------  ----------------------------------------
compressedblocks.uncompress.oakwood       False    Allow to uncompress Oak Wood
compressedblocks.uncompress.sprucewood    False    Allow to uncompress Spruce Wood
compressedblocks.uncompress.birchwood     False    Allow to uncompress Birch Wood
compressedblocks.uncompress.junglewood    False    Allow to uncompress Jungle Wood
compressedblocks.uncompress.acaciawood    False    Allow to uncompress Acacia Wood
compressedblocks.uncompress.darkoakwood   False    Allow to uncompress Dark Oak Wood
----------------------------------------  -------  ----------------------------------------
----------------------------------------  -------  ----------------------------------------
compressedblocks.uncompress.oakplank      False    Allow to uncompress Oak Plank
compressedblocks.uncompress.spruceplank   False    Allow to uncompress Spruce Plank
compressedblocks.uncompress.birchplank    False    Allow to uncompress Birch Plank
compressedblocks.uncompress.jungleplank   False    Allow to uncompress Jungle Plank
compressedblocks.uncompress.acaciaplank   False    Allow to uncompress Acacia Plank
compressedblocks.uncompress.darkoakplank  False    Allow to uncompress Dark Oak Plank
----------------------------------------  -------  ----------------------------------------
----------------------------------------  -------  ----------------------------------------
compressedblocks.uncompress.gravel        False    Allow to uncompress Gravel
compressedblocks.uncompress.sand          False    Allow to uncompress Sand
compressedblocks.uncompress.redsand       False    Allow to uncompress Red Sand
----------------------------------------  -------  ----------------------------------------
----------------------------------------  -------  ----------------------------------------
compressedblocks.uncompress.stone         False    Allow to uncompress Stone
compressedblocks.uncompress.granite       False    Allow to uncompress Granite
compressedblocks.uncompress.diorite       False    Allow to uncompress Diorite
compressedblocks.uncompress.andesite      False    Allow to uncompress Andesite
----------------------------------------  -------  ----------------------------------------
----------------------------------------  -------  ----------------------------------------
compressedblocks.uncompress.dirt          False    Allow to uncompress Dirt
compressedblocks.uncompress.cobblestone   False    Allow to uncompress Cobblestone
compressedblocks.uncompress.soulsand      False    Allow to uncompress Soul Sand
compressedblocks.uncompress.netherrack    False    Allow to uncompress Netherrack
========================================  =======  ========================================