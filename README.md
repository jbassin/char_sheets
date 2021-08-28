### Setsu

#### Backstory
Setsu is a Yuan-Ti Pureblood. As such, he is devoid of any real emotion and sees others
as tools to an end -- namely ascension to godhood. All Yuan-Ti believe that if they
accumulate enough power they'll be able to consume a diety and take their place of power.
Setsu thinks that the whole usurpation approach is stupid, and definitely won't work.
Instead he plans to become a god the old fashioned way: get enough people to worship him.

To that end Setsu has worked to insert himself into the best situations for gathering
followers. He's served as a squire under a famous adventurer and traveled the world
saving villages and stopping assasination attempts. Sure, he was the one who lead the
monsters to the village and hired the hitmen in the first place, but his now-devout
worshipers don't need to know that.

Now separated from the hero (a dragon attacked a caravan; while Setsu heroically staved
off the dragon long enough for the merchants to escape unfortuntely the goody-two-shoes
hero didn't make it), Setsu carries himself with a saccarine smile and fake do-good attitude
looking for new opportunities to spread his influence. 

#### Description
Setsu is a 27 year old Yuan-ti. He's 5'10" with exceptionally pale skin and jet black hair
that he's dyed blond -- as stupid peasants seem to think that's more heroic for some reason.
He has lines of green scales running up his neck and down his arms and legs that he tells
people is a curse from a dastardly hag, but is really just because he's a Yuan-Ti. He wears
elegant clothing emblazoned with whatever the locals think is the mark of a true savior.

#### Character Sheet
```ini
[character_info]
  name       = Setsu
  race       = Yuan-Ti Pureblood
  level      = 10
  class      = Warlock (The Crowd)
  background = Celebrity Adventurers Scion
  alignment  = Neutral Evil
[skills/proficiencies]
  [strength]
    base         = -1 ⟪8 = 8 [base]⟫
    saving_throw = -1
    athletics    = -1
  [dexterity]
    base               = +3 ⟪16 = 15 [base] + 1 [race]⟫
    saving_throw       = +3
    acrobatics         = +3
    sleight_of_hand    = +3
    stealth            = +3
  [constitution]
    base         = +2 ⟪14 = 14 [base]⟫
    saving_throw = +2
  [intelligence]
    base          = -1 ⟪8 = 8 [base]⟫
    saving_throw  = -1
    arcana        = -1
    history       = -1
    investigation = -1
    nature        = -1
    religion      = -1
  [wisdom]
    base            = +1 ⟪12 = 12 [base]⟫
    saving_throw    = +5 ⟪prof [class]⟫
    animal_handling = +1
    insight         = +1
    medicine        = +1
    perception      = +1
    survival        = +1
  [charisma]
    base         = +5 ⟪20 = 14 [base] + 2 [race] + 2 [asi] + 2 [asi]⟫
    saving_throw = +9 ⟪prof [class]⟫
    deception    = +13 ⟪prof [class], expr [win_over_the_masses]⟫
    intimidation = +9 ⟪prof [class]⟫
    performance  = +5 ⟪prof [background]⟫
    persuasion   = +13 ⟪prof [background], expr [win_over_the_masses]⟫
  [other]
    languages = common, abyssal, draconic, elvish, dwarvish
    weapons   = +2 rod of the pact keeper
    feats     = inspiring leader
[combat]
  [stats]
    health        = 75 ⟪75 = 8 [level 1] + 45 [levels 2 - 10] + 22 [con modifier]⟫
    ac            = 16 ⟪16 = 13 [mage_armor] + 3 [dex]⟫
    initiative    = +8 ⟪+8 = 3 [dex] + 5 [cha]⟫
    movement      = 30 ft ⟪30 = 30 [race]⟫
    spell_slots   = 2
    spell_dc      = 19 ⟪19 = 8 [base] + 4 [prof] + 5 [cha] + 2 [rod_of_the_pact_keeper]⟫
    spell_atk_mod = +11 ⟪+11 = 4 [prof] + 5 [cha] + 2 [rod_of_the_pact_keeper]⟫
  [spellcasting]
    eldritch_blast      = mod +5 
    cantrip             = friends, mage_hand, minor_illusion
    pact_of_the_tome    = guidance, message, viscious_mockery
    book_of_secrets     = detect_magic, identify
    far_scribe          = sending (to subscribers)
    first_level         = command, guiding_bold, charm_person, hellish_rebuke
    second_level        = detect_thoughts, skywrite, hold_person, misty_step
    third_level         = beacon_of_hope, spirit_guardians, counterspell, hypnotic_pattern
    fourth_level        = arcane_eye, charm_monster, blight, dimension_door
    fifth_level         = commune, modify_memory, hold_person, negative_energy_flood
    innate_spellcasting = poison_spray, suggestion x1
  [action]
    rod_of_the_pact_keeper = regain one spell slot per long rest
    inspiring_leader       = give six creatures 15 temp hitpoints
  [passive]
    darkvision            = see 60ft in darkness
    magic_resistance      = advantage on saving throws against magic
    poison_immunity       = immune to poison and poisoned condition
    cloak_of_displacement = enemies have disadvantage to attack, unless take damage
    backer_benefits       = roll d8 on backer benefits table after long rest
    crowdsourced_magic    = attempt to cast spell with roll without spending slot
    win_over_the_masses   = when ally makes cha check within 10ft add +5
    gift_of_the_protector = can automatically revive one subscriber
```
