# difficulty
DCSS with difficulty option and some other changes.

1) monster_hp_difficulty=100

Possible values are 1-1000. Monster HP is changed as hp = hp * monster_hp_difficulty / 100;
Default is 100.

1a) monster_xp_difficulty=100

Possible values are 1-1000. Allows to control XP from killing monsters.
XP part which depends on max HP is calculated as maxHP*100/monster_xp_difficulty.
If you want to get the same XP as before, it should have the same value as monster_hp_difficulty. 
For example:
monster_xp_difficulty = 200
monster_hp_difficulty = 200
and you will have monster with 200% HP but the same XP as normal monsters.

2) turns_for_comes_into_view_again = 10

Default is -1 i.e. the message is disabled.

3) Damage dealt to monster is displayed for most sources

Cannot be hidden

4) To_hit for damaging spells (success chance similar to hexes)

Cannot be hidden

5) confirm_action += Borg

confirm_action += Death's Door

You will get confirmation dialog before casting the spells. This option is case-sensitive.
Default is none


Full Windows 64 bit version can be downloaded at https://www.dropbox.com/s/7ufdv1a2qbn6bvt/crawl_full_20150619.zip?dl=0
