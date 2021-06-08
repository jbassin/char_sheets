### Vin'Ralis nir Xhira

#### Backstory
Ralis is a Quori -- a formless, ageless being of pure Vitae. As a Quori has no Mana of its own it can't directly interact with the physical world. While some Quori forcibly take control of physical vessels, others make a Pact with a vessel and combine into a single entity. When a Quori made of positive quantities of Vitae makes a pact with a vessel the entity is known as a Kalashtar and when the Quori has negative quantities of Vitae the entity is known as an Inspired.

Kalashtar retain the appearance of the vessel but gain slight elven qualities (such as pointed ears), blue-glowing tattoos called glowlines appear on the skin, and the vessel's eyes begin to glow. Both the Quori and the vessel share one mind, but control of the body is usually the vessel's.

Vin was born a human on the floating isle of Xhira, one of many islands in the Glittering Sea (a demiplane embedded within the Pale). His father a fisher and his mother an acolyte of Morgion, Vin's early life was uneventful. He spent most of his time in the temple, helping his mother tend to the diseased and injured that came to Morgion for help; while there he picked up his mother's extensive knowledge of disease and poisons.

When Vin was seventeen an Inspired came to the temple in search of an artifact. When Vin's mother told him he didn't know where the artifact was, the Inspired barred the doors to the temple and burned it to the ground, killing everyone inside. Feeling powerless to stop the Inspired, Vin called out for anything that could give him power -- which attracted the attention of Ralis, who had been hunting the Inspired for their own reasons. Ralis appeared before Vin and offered a Pact. Vin agreed, but by the time the ritual completed the Inspired had already escaped. Vin'Ralis subsequently set off to find, and kill, the Inspired.

For the past five and a half decades Vin'Ralis has been hunting down the Inspired, who has always managed to stay one step ahead. During his crusade he came across the Sorrowsworn, those devoted to rooting out the undead in the name of the Raven Queen. As the Inspired are a form of undead -- the negative Vitae Quori present as necromantic energy, and the Inspired use their Quori to create thralls -- Vin'Ralis saw it fit to join up. They have continued to hunt down the undead, always in search of their first foe.
```
 ┌ Vessel name
 │    ┌ Quori name
 │    │    ┌ "from"
 │    │    │    ┌ location
┌┴┐ ┌─┴─┐ ┌┴┐ ┌─┴─┐
Vin'Ralis nir Xhira
```

#### Description
Vin is a 72-year-old Kalashtar. He has very pale skin, but he has crisscrossing tattoo-like lines that glow with a faint blue luminescence across his body due to his pact with Ralis. The patterning is heavily obscured by the heavy black and purple robes that he wears; to the point that the only evidence of the glowlines is on his hands and feet, which are uncovered. He wears a black raven mask that hides his facial features, but his eyes glow the same blue as his tattoos, bleeding through the lens of the mask.

He carries a gnarled darkwood staff -- that's as tall as he is -- which is adorned with a latched lantern. The lantern has a faint blue fire burning within, but it's source is obscured by the heavy, misshapen glass on the exterior of the lantern body.

#### Character Sheet
```ini
[character_info]
  name       = Vin’Ralis nir Xhira
  race       = Kalashtar
  level      = 11
  class      = Monk (Way of Mercy)
  background = Haunted One
[skills/proficiencies]
  [strength]
    base         = +0 ⟪10 = 10 [base]⟫
    saving_throw = +4 ⟪prof [class]⟫
    athletics    = +0
  [dexterity]
    base               = +5 ⟪20 = 14 [base] + 2 [race] + 2 [asi] + 2 [asi]⟫
    saving_throw       = +9 ⟪prof [class]⟫
    acrobatics         = +5
    sleight_of_hand    = +5
    stealth            = +9 ⟪prof [class]⟫
  [constitution]
    base         = +4 ⟪19 = 19 [amulet of health]⟫
    saving_throw = +4
  [intelligence]
    base          = +0 ⟪10 = 10 [base]⟫
    saving_throw  = +0
    arcana        = +0
    history       = +0
    investigation = +4 ⟪prof [background]⟫
    nature        = +0
    religion      = +4 ⟪prof [background]⟫
  [wisdom]
    base            = +3 ⟪16 = 15 [base] + 1 [race]⟫
    saving_throw    = +3 ⟪adv [race]⟫
    animal_handling = +3
    insight         = +7 ⟪prof [class]⟫
    medicine        = +3
    perception      = +3
    survival        = +3
  [charisma]
    base         = +2 ⟪14 = 14 [base]⟫
    saving_throw = +2
    deception    = +2
    intimidation = +2
    performance  = +2
    persuasion   = +2
  [other]
    languages = celestial, common, elvish, undercommon, quori
    weapons   = simple, shortsword
    tools     = alchemist tools
    feats     = tough
[combat]
  [stats]
    health     = 124 ⟪124 = 8 [level 1] + 50 [levels 2 - 11] + 44 [con modifier] + 22 [tough]⟫
    ac         = 18 ⟪18 = 10 [base] + 5 [dex] + 3 [wis]⟫
    initiative = +5
    movement   = 50 ft ⟪50 = 30 [race] + 20 [class]⟫
    ki_save    = 15 ⟪15 = 8 [base] + 3 [wis] + 4 [prof]⟫
    ki_total   = 11, regain on short/long rest
  [action]
    attack = x2
      lanternlight    = atk +10, dmg d8+6 ⟪+1 quarterstaff⟫
      unarmed         = atk +9 , dmg d8+5 ⟪monk die⟫
    hand_of_healing   = d8+5 healing, cure [blind, deaf, paralyze, poison, stun], cost 1 ki
    stillness_of_mind = end charmed or frightened
  [bonus]
    unarmed_strike    = 1x attack.unarmed
    flurry_of_blows   = 2x [attack.unarmed, hand_of_healing, hand_of_harm], cost 1 ki
    patient_defense   = dodge, cost 1 ki
    step_of_the_wind  = disengage/dash, cost 1 ki
  [reaction]
    deflect_missiles = subtract d10+9 from ranged attack
    slow_fall        = reduce falling damage by 55
  [conditional]
    return_missiles = on deflect_missiles to 0, return as attack.unarmed 20/60ft, cost 1 ki
    stunning_strike = on hit, force con save or stun, cost 1 ki
    focused_aim     = on miss, increase roll by 2, cost 1 ki, stack to 3
    evasion         = on dex save, half if fail, none if success
  [passive]
    hand_of_harm         = d8+3 extra damage, inflict poison, cost 1 ki
    unarmored_movement   = run on vertical surfaces and liquid
    ki_empowered_strikes = attacks are magical
    purity_of_body       = immune to disease and poison
    dual_mind            = advantage on wisdom saves
    mental_discipline    = resistance to psychic damage
    mind_link            = speak telepathically with one creature at a time within 110 feet
    severed_from_dreams  = immune to spells that require dreaming    
```
