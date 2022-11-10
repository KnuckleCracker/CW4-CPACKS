# FAQ 
- **Q:** What changed compared to the last CSM template?
- **A:**
  - New Help Bar (See No_exit CSM 03 or higher)
  - Setup as "tiny creeper" (Emitters start at 1, capture treshhold is at 0.01 AC instead of 0.4 AC, 1 wall height = 10 creeper)
  - New Animations (MultiTower, Armored Emitter, Spore Buster). There are no animations for "Evil MultiTowers". Evil MultiTowers are generally disliked by players and with the 0.01 capture treshhold, they should not be used at all.
  - Faster gameplay (capture Bridges Faster, faster Chip Factory)
  - Doors no longer lose their charge when opening
  - Absorber's death and aura modes has been split so it's more readable what they do.
  - Absorbers can respawn as an absorber after been turned into a MultiTower and being flooded by Creeper.
  - Doors easter egg if you try to destroy them. It's still possible to destroy them.
  - Moved the objects around in the Template map so it's more compact.
  - New Images to accompany the changes above.
  - Minor bug fixes (like rounding Emitters' power so they don't show stuff like 39.9999999, small performance gains)

- **Q:** How do I use the Help Bar in my level?
- **A:** Just keep the Help Bar script in the top left. It won't work in the editor but when you finalized the map you'll be able to see it working.
Not everything is implemented yet. A lot of the less popular FactoryChips and TowerChips will not have a help button yet. Let me know if there is a demand for these.
- **Q:** It looks like there are less objects in the Template Map, are some missing?
- **A:** Yes
  - The "Evil" variants of the MultiTowers. (I dislike them and with the 0.01 capture setting, it's way too easy and frustrating to accidentally capture them)
  - The Semiconductor3 (As a player I never understood how it works exactly, so I don't like making a map with it.)
  - The ConvertorBase (It's the ChipFactory without chips)
  - The Black CreepPortal (It's confusing and I never fully understood how it worked as a player and I usually tried to wall it as quickly as possible as I disliked what it did)
  
Note: you can still add them back if you really like/want them.

- **Q:** How did you make the animations? Can I also make them?
- **A:** They are made by making these animations in Unity3D and then using self-made scripts to capture and export these animations to generated CRPL code. There is no easy way for you to do this yourself or to modify existing animations.

- **Q:** Can I make any requests or suggestions or ask other questions?
- **A:** Yes, you can ping me for this.