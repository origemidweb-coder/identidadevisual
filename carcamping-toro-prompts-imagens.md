# Prompts de imagem — Car Camping Fiat Toro

Prompts em inglês (os modelos de imagem respondem melhor), prontos pra colar no Gemini
(Nano Banana / Imagen). Cada cena corresponde a uma prancha técnica do projeto.

---

## Como usar

1. **Cole o BLOCO A (âncora) + o prompt da cena** numa mensagem só. A âncora mantém o mesmo
   carro, mesma cor e mesmo acampamento em todas as imagens.
2. Gere a **cena 1 primeiro**. Depois, nas próximas, anexe a imagem da cena 1 e escreva:
   *"same vehicle, same build, same campsite as the reference image"* — é assim que o Nano
   Banana mantém consistência de verdade.
3. Se quiser fidelidade ao layout, anexe também o print da prancha técnica correspondente e
   peça: *"follow the layout in this technical drawing"*.
4. Aspect ratio: peça no final do prompt (`16:9`, `4:3`, `1:1`).

---

## BLOCO A — âncora de consistência (cole em toda cena)

```
Vehicle: a 2018 Fiat Toro double-cab compact pickup, dark graphite grey, black steel roof
rack, all-terrain tyres, converted into a car camping rig. Build style: marine plywood with
a warm natural finish, matte black aluminium hardware, olive-green canvas. Photorealistic
editorial photograph, full-frame camera, 35mm lens, natural light, clean realistic materials,
no visible text, no brand logos, no watermarks.
```

---

## Cena 1 — Hero externo, fim de tarde (prancha 01)

```
Wide three-quarter rear side view of the converted pickup parked on a grassy clearing at a
Brazilian mountain campsite, golden hour, low warm sunlight raking across the body. The 2.5 m
side awning is extended over a folding table and two camp chairs; warm LED string lights hang
along the awning edge; the tailgate is folded down with a mattress visible inside the bed.
Distant blue mountains and eucalyptus trees in the background, soft haze. Shot at f/5.6,
everything sharp, cinematic warm colour grade. 16:9
```

## Cena 2 — Cama montada, traseira aberta (prancha 01 e 04)

```
Rear view of the pickup at blue hour, tailgate folded down, showing the finished sleeping
area: a marine plywood platform running the full length of the bed, a 12 cm double mattress
with grey fitted sheet and two pillows, a mosquito net closing the rear opening, warm dimmable
LED strip lighting along the inner walls, a small USB port and a book on a side ledge. Cosy
interior glow contrasting with the cool dusk outside. Low camera angle, tripod, f/4. 4:3
```

## Cena 3 — Planta do layout, vista de cima (prancha 02)

```
Top-down overhead view straight into the open pickup bed with the mattress removed, showing
the finished conversion layout: a tall narrow wardrobe module with a hanging rail and two
drawers on the left wall, a pantry module with shelves and clear airtight food boxes on the
right wall, a 45 L water tank secured behind the cab, and a lithium battery in a sealed box on
the opposite side. Everything in marine plywood with black hardware, straps and rails visible.
Flat overcast daylight, no harsh shadows, documentary style. 1:1
```

## Cena 4 — Estrado retrátil aberto (prancha 03)

```
Close detail shot of the marine plywood bed platform with one half lifted open on a full-length
piano hinge, held up by a gas strut, revealing the storage compartment underneath: a folded
camping mat, a toolbox, a sealed battery box and two plastic crates. A hand rests on the raised
panel edge. Warm afternoon light entering the open tailgate, visible wood grain and hinge
detail, shallow depth of field on the background. 3:2
```

## Cena 5 — Cozinha modular aberta (prancha 07)

```
The slide-out kitchen module pulled fully out from the side of the pickup bed, under the
extended awning: a marine plywood drawer with a built-in two-burner camp stove, a folding sink
with a small tap, a chopping board, a cast iron pan with vegetables, and a 12 V fridge visible
inside the fixed cabinet below. Late afternoon light, steam rising from the pan, a camp mug on
the corner. Documentary food-and-travel photography, f/2.8, natural colours. 3:2
```

## Cena 6 — Sistema elétrico instalado (prancha 05)

```
Tight technical close-up of the auxiliary electrical system installed under the bed platform of
the pickup: a lithium battery inside a sealed black box, a DC-DC charger and an MPPT controller
mounted on a plywood panel, a small distribution panel with labelled circuit breakers and
blade fuses, tidy loomed red and black cabling with cable ties and heat-shrink, a battery
monitor screen showing a charge readout. Clean workshop-grade wiring, cool neutral light,
sharp focus across the panel. 4:3
```

## Cena 7 — Solar e autonomia (prancha 05)

```
The converted pickup parked beside a lake on a bright clear morning, a portable folding solar
panel unfolded on the grass next to the vehicle, cable running to the bed, roof rack loaded
with a rolled awning and a jerry can. Wide landscape framing with the vehicle in the left
third, still water and hills behind, crisp midday light, deep blue sky with a few clouds.
Adventure-travel editorial look. 16:9
```

## Cena 8 — Água e ducha externa (prancha 06)

```
Detail of the water system in use at the campsite: a folding sink mounted on the open kitchen
drawer with running water from a 12 V pump tap, a 45 L water tank strapped behind the cab
visible in the background, and a simple outdoor shower hose with a black solar heating bag
hanging from the awning frame at the far end. Late morning light, water droplets caught in the
sun, realistic plumbing hardware and hose clamps. 3:2
```

## Cena 9 — Área de convivência à noite (prancha 08)

```
Night scene at the campsite from a low wide angle: the pickup with its awning extended, warm
LED string lights strung along the awning, a folding table with two enamel mugs and a lantern,
two camp chairs, a hammock slung between the awning frame and a tree, and the interior of the
bed glowing softly through the open tailgate. Deep blue night sky with visible stars, long
exposure look, warm-versus-cool colour contrast, no light pollution. 16:9
```

## Cena 10 — Estrada de terra (opcional)

```
The fully loaded converted pickup driving on a red dirt road through Brazilian countryside,
seen from a low front three-quarter angle, dust trailing behind the rear wheels, roof rack with
rolled awning and solar panel case, awning closed, late afternoon side light. Motion blur on
the wheels and background, vehicle sharp, panning shot at 1/60s. 16:9
```

---

## Ajustes que costumam ser necessários

- **Cama grande demais:** o modelo tende a desenhar uma caçamba de picape grande. Acrescente
  *"compact pickup with a short cargo bed, roughly 1.35 m long with the tailgate closed"*.
- **Logos tortos:** se aparecer emblema deformado, acrescente *"no badges, no emblems, plain
  grille"*.
- **Cozinha dentro do carro:** o fogareiro tem que aparecer **fora** da estrutura fechada —
  reforce *"stove fully outside the vehicle, under the awning"*.
- **Fios bagunçados na cena 6:** peça *"professionally loomed wiring, every circuit fused"*.
