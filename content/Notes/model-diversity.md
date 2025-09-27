---
title: Model Diversity
permalink: model-diversity
aliases: model-diversity
draft: false
date: 2025-09-25
tags:
  - data
---

*Below two stories about a cat who goes on an adventure are written by Google `gemini-2.5-flash` model with different parameters setup for diversity control.*

See related [Sampling Techniques and Parameters](/sampling-techniques-and-parameters)
### Story I:
```
model_config = types.GenerateContentConfig(
    temperature=1.0,
    top_p=0.95,
)
```
Miko was, by all accounts, a perfectly content cat. His days unfolded in a comforting rhythm of sunbeam naps, supervised kibble consumption, and the occasional spirited chase of a dust bunny. His world was soft blankets, warm laps, and the soothing hum of the refrigerator.

But Miko harbored a secret. He was a watcher. From his perch on the living room windowsill, he observed the Great Outside. He saw squirrels argue over acorns, birds flit between branches, and the occasional dog trot by with an air of immense purpose. More than anything, he *smelled* it. The Great Outside carried a million scents: damp earth after rain, sharp pine needles, the elusive, intoxicating aroma of... something wild and utterly new.

One crisp autumn morning, a gust of wind, bolder than usual, pushed open the back door a crack. It was only for a second, but it was enough. A wave of that particular scent, sweet and musky, hit Miko like a velvet hammer. It called to him. It promised adventure.

With a jolt of unprecedented courage, Miko squeezed through the narrow gap.

The world outside was a cacophony. The air thrummed with a thousand tiny sounds he’d only heard as muffled whispers through glass. Leaves crunched under his paws – real leaves, not the ones his human swept. The sun was brighter, the shadows sharper.

He took his first tentative steps onto the unknown territory of the garden path. The scent was stronger here, pulling him towards the tall, overgrown hedge at the far end. He pushed through a gap, thorns snagging gently at his fur, and found himself in an even wilder place – a forgotten corner of the neighbor’s neglected yard.

Here, the grass was knee-high, a miniature jungle. A fat bumblebee buzzed past his nose, startling him. He flattened himself, tail twitching, before remembering his mission. The scent. It was potent now, leading him deeper.

He navigated around a rusty wheelbarrow, scaled a low, crumbling wall, and finally, there it was. Not a great beast, not a hidden treasure chest, but a sprawling, ancient honeysuckle bush, its golden-white flowers dripping with dew and an almost overwhelming sweetness. This was the source of the wild, untamed perfume that had haunted his dreams.

Miko pushed his nose into a cluster of blooms, inhaling deeply. It was everything he had imagined, and more. A tiny world of nectar and velvet petals. He rolled in the leaves at the base of the bush, soaking up the intoxicating aroma, feeling a primal connection to this wild, fragrant place.

His reverie was broken by the sharp *thwack* of a screen door closing in the distance, followed by his human’s voice calling, “Miko! Kitty, kitty!”

A pang of longing, sharp and sudden, for his soft blankets and warm lap, pierced through his adventurous spirit. He had found his treasure, now it was time to return.

Retracing his steps was easier than he thought, the honeysuckle scent now a part of him, a memory etched into his fur. He slipped back through the hedge, across his own garden path, and skidded to a halt just as his human opened the back door again, a worried frown on her face.

With a casual flick of his tail, Miko sauntered inside, as if he’d merely been contemplating a particularly interesting blade of grass.

That night, curled in his favorite armchair, Miko purred with a new depth. He was still a perfectly content cat, but now, he carried a secret. A whisper of wildness, a memory of honeysuckle, and the quiet knowledge that sometimes, the greatest adventures begin with just a crack in the door.

### Story II:
```
model_config = types.GenerateContentConfig(
    temperature=0.5,
    top_p=0.5,
)
```
Jasper was, by all accounts, a perfectly content cat. His days unfolded in a predictable, comforting rhythm: sunbeam naps, strategic bird-watching from the windowsill (never *too* close, mind you), gourmet kibble, and evening cuddles with his human, Elara. His world was the cozy cottage, the manicured garden, and the sturdy wooden fence that marked the boundary of his known universe.

Until the day of the shimmering beetle.

It wasn't just any beetle. This one was a jewel-toned marvel, its carapace glinting with impossible blues and greens as it buzzed lazily over Elara's prize-winning petunias. Jasper, usually a connoisseur of the chase, felt an unfamiliar pull. This wasn't prey; it was a mystery.

The beetle, as if sensing his fascination, drifted higher, then sailed effortlessly over the wooden fence, disappearing into the wild, untamed tangle of the alley beyond.

Jasper hesitated. The fence was a barrier, a rule. But the beetle… the beetle was an invitation. With a deep breath (or what passed for one in a cat), he launched himself, claws finding purchase, and scrambled over.

The other side was a revelation. The air smelled different – sharper, wilder, a symphony of unknown plants and distant, intriguing garbage bins. The ground was uneven, a mix of cracked pavement and stubborn weeds. This was not his garden. This was the *beyond*.

He followed the faint, lingering scent of the beetle. It led him down the alley, past overflowing bins that offered a tantalizing, if slightly repulsive, array of smells. A scruffy, territorial tomcat hissed from atop a shed, but Jasper, fueled by his quest, merely flattened his ears and pressed on. He was an explorer now, not a brawler.

The alley opened into a forgotten patch of overgrown land, a mini-jungle of towering thistles and swaying grasses. Here, the beetle's scent grew stronger. Jasper pushed through the foliage, his whiskers twitching, his tail held high like a flag of discovery. A sudden rustle in the bushes made him freeze, heart thumping. A fat, oblivious robin hopped out, pecking at a berry, completely unaware of the ginger predator inches away. Jasper let it pass. The beetle was his focus.

He found it eventually, not on a leaf, but nestled in the hollow of an ancient, moss-covered oak tree. It wasn't moving. It was just… resting. Jasper nudged it gently with his nose. It was cool, smooth, and utterly captivating. He watched it for a long moment, then, satisfied, turned his attention to the tree itself.

The oak was a world unto itself. Its bark was rough, perfect for scratching. Its branches offered dizzying heights and new perspectives. From a low limb, Jasper could see beyond the overgrown patch, beyond the alley, to a distant, shimmering pond he'd never known existed. He felt a thrill, a sense of vastness he'd never imagined.

As the sun began to dip, painting the sky in hues of orange and purple, Jasper realized he was hungry. And a little tired. The adventure had been exhilarating, but the comforts of home suddenly seemed very appealing.

He retraced his steps, the journey back feeling less daunting now that he knew the way. The scruffy tomcat was gone. The alley bins seemed less mysterious. He scaled his garden fence with newfound confidence, landing softly on the familiar grass.

Elara was calling his name, her voice laced with worry. He trotted to the back door, meowing a cheerful, slightly hoarse greeting. She scooped him up, burying her face in his soft fur. "Oh, Jasper, where have you been, you naughty boy?"

Jasper purred, a deep rumble of contentment. He settled onto his favorite sunbeam, his belly full of kibble, his paws twitching with dreams of shimmering beetles and ancient oaks. He was still Jasper, Elara's beloved housecat. But he was also Jasper, the explorer, the adventurer, with a secret world beyond the fence and a heart a little wilder than before. And he knew, with a certainty only a cat can possess, that this wouldn't be his last adventure.
