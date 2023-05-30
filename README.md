# [CSGO] Customised end-of-match votes - Sourcemod plugin

## Description

This plugin allows you to exclude maps that have already been played from the vote.

## Configuration

You have some convars available to interact with this plugin :

- **sm_endmatchvote_max <number>** : Configure the number of matches an already played map must be excluded. default : 0 for infinite.
- **sm_endmatchvote_mode <1|2>** : Configure the persistant (1) or temporary (2) memory of the already played maps. default : 1
- **sm_endmatchvote_reset** : Reset the excluded maps.
- **sm_endmatchvote_list** : List the excluded maps.
