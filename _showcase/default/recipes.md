---
show: true
width: 8
date: 2029-01-01 00:01:00 +0800
height: 400px
images:
  - src: assets/images/recipes/ketchup-milk-maggi.jpeg
    title: Ketchup + Milk Noodles
    desc: "Boil 1 brick of noodles in 3:1 milk to water. Add ketchup, kashmiri + byadgi chilli powder, chilli flakes, salt, basil."
  - src: assets/images/recipes/pandoras-noodles.jpeg
    title: Pandora's Noodles
    desc: "Boil noodles with green peas. Make 'sauce': peanut butter, soy sauce, kashmiri + byadgi chilli powder, chilli flakes, salt, ketchup, honey-roasted peanuts, chilli oil, tabasco, lime juice, garlic + onion powder. Garnish with sesame oil, sesame seeds, spring onion."
---

<div class="p-4">
  <h3>Cool Recipes</h3>
  <p class="text-muted fst-italic mb-3">Measuring is for science - cooking is magic.</p>
  {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
</div>
