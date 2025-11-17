---
show: true
width: 8
date: 2022-01-02 00:01:00 +0800
height: 400px
spreads:
  - image: /assets/images/pokemon/tapu-fini.png
    spread: |
      Tapu Fini @ Life Orb  
      Ability: Misty Surge  
      Level: 50  
      EVs: 158 HP / 252 Atk / 100 Spe  
      Adamant Nature  
      - Ice Punch  
      - Waterfall  
      - Play Rough  
      - Protect

  - image: /assets/images/pokemon/landorus-therian.png
    spread: |
      Landorus-Therian @ Assault Vest  
      Ability: Intimidate  
      Level: 50  
      EVs: 40 HP / 116 Atk / 20 Def / 140 SpA / 12 SpD / 180 Spe  
      Hasty Nature  
      - Earth Power  
      - Earthquake  
      - Rock Slide  
      - Fly

  - image: /assets/images/pokemon/charizard-gmax.png
    spread: |
      Charizard-Gmax @ Safety Goggles  
      Ability: Solar Power  
      Level: 50  
      EVs: 4 HP / 252 SpA / 252 Spe  
      Timid Nature  
      IVs: 0 Atk  
      - Heat Wave  
      - Hurricane  
      - Helping Hand  
      - Protect
---

<div class="p-4">
  <h3>Favorite Pokémon Spreads</h3>
  <p class="text-muted fst-italic mb-3">Some of my go-to competitive sets from VGC</p>
  {% include widgets/pokemon_spread.html id=page.id spreads=page.spreads height=page.height %}
</div>
