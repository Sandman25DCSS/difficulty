# difficulty
DCSS with difficulty option and some other changes.

1) monster_hp_difficulty=100
Possible values are 1-1000
Monster HP is changed as
hp = hp * monster_hp_difficulty / 100;
Default is 100.
2) turns_for_comes_into_view_again = 10
Default is -1 i.e. the message is disabled.
3) Damage dealt to monster is displayed for most sources
Cannot be hidden
4) To_hit for damaging spells (success chance similar to hexes)
Cannot be hidden
5) confirm_action += Borg
confirm_action += Death's Door
You will get confirmation dialog before casting the spells
Default is none
