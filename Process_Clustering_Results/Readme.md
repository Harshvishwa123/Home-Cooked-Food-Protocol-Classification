# Process Clustering on Cooking Action Verbs

This project applies multiple unsupervised machine learning algorithms to cluster **cooking process verbs** into meaningful groups based on semantic similarity. Using KMeans, Agglomerative/Minibatch KMeans, DBSCAN, and Gaussian Mixture Models (GMM), the project uncovers natural structure within 300+ cooking action terms. These clusters help categorize food preparation behaviors such as heating, mixing, cutting, assembling, seasoning, and more.

## 📌 Methods Used
- **Word Embeddings** (vectorizing process verbs)
- **KMeans Clustering**
- **Agglomerative / MiniBatch KMeans**
- **DBSCAN**
- **Gaussian Mixture Models (GMM)**
- **Visualization & Comparison of Cluster Outputs**

---

## 📊 Cluster Results

### **KMeans**
Cluster 0 (32):
absorbed, boil, braise, bubble, bubbling, check, curdle, deglaze, dissolve, evaporate, evaporated, foam, heat, meld, raise, reduce, roux, scald, scorching, settle, simmer, sit, skim, stand, steep, stew, stir, stirring, thicken, uncover, uncovered, wilt

Cluster 1 (20):
burn, caramelize, cook, fry, pan-fry, pop, saute, scramble, sizzle, smoke, smoking, soften, splutter, start, stir-fry, stop, sweat, swirl, wait, wok

Cluster 2 (38):
arrange, assemble, bake, carve, coat, dash, decorate, dip, distribute, divide, dollop, dress, dressing, drizzle, fill, fold, garnish, ladle, moisten, mound, place, pour, presentation, repeat, scatter, season, seasoning, serve, slice, smear, splash, spread, sprinkle, stack, style, taste, top, toss

Cluster 3 (19):
deflate, dust, flatten, floured, grease, knead, mould, press, punch, rise, rising, roll, shape, square, stretch, unfold, unroll, wet, wrap

Cluster 4 (29):
barbecue, baste, broil, brush, caramelized, char, charred, drip, flip, foil, glaze, grate, griddle, invert, marinade, marinate, move, preheat, roast, rotate, sear, slather, spray, thread, tilt, toast, turn, unmold, unwrap

Cluster 5 (76):
add, blanch, blot, break, butter, chop, clean, cool, cover, crockpot, crumble, defrost, dice, drain, dripping, drop, dry, dump, flake, freezing, handle, hold, immerse, lard, measure, melt, mince, minced, moist, note, open, overcook, pack, parboil, peel, pick, poach, pre-heat, prepare, pressure, push, put, reheat, remove, replace, reserve, rest, rinse, save, scoop, scrape, select, separate, set, shred, smash, snap, soak, sort, split, sprout, squash, squeeze, steam, sterilize, submerge, take, tear, test, thaw, throw, touch, transfer, warm, wipe, yield

Cluster 6 (24):
crimp, cut, devein, dredge, insert, massage, pat, pierce, poke, prick, pull, rub, scrub, seal, skin, slash, slit, strip, stuff, tie, trim, tuck, twist, wash

Cluster 7 (32):
beat, blend, blitz, chill, combine, condensed, cream, crush, flavoring, frost, grind, ice, mash, mix, muddle, overmix, powdered, process, puree, refrigerate, shake, sieve, sift, smooth, store, strain, stream, sweeten, whip, whirl, whisk, zest

---

### **Agglomerative / MiniBatch KMeans**

Cluster 0 (63):
absorbed, boil, braise, bubble, bubbling, burn, caramelize, caramelized, carve, check, cook, cover, curdle, deglaze, evaporate, evaporated, foam, fry, glaze, griddle, heat, invert, meld, overcook, overmix, pan-fry, poach, pop, pre-heat, raise, reduce, replace, roast, rotate, roux, saute, scorching, scramble, sear, settle, simmer, sizzle, skim, smoke, smoking, soften, splutter, start, steam, stir-fry, stop, sweat, swirl, test, thicken, tilt, toast, uncover, uncovered, unmold, wait, wilt, wok

Cluster 1 (30):
blanch, blot, break, chop, crumble, crush, cut, devein, dice, drain, flake, grind, handle, immerse, mash, mince, minced, parboil, pat, peel, rinse, scrub, shred, slice, slit, smash, submerge, tear, trim, wash

Cluster 2 (48):
add, beat, blend, blitz, butter, chill, combine, condensed, cream, dash, dissolve, dust, flavoring, frost, ice, lard, melt, mix, muddle, powdered, process, puree, refrigerate, scald, season, seasoning, sieve, sift, sit, smooth, soak, splash, stand, steep, sterilize, stew, stir, stirring, store, strain, stream, sweeten, taste, twist, whip, whirl, whisk, zest

Cluster 3 (24):
bake, barbecue, baste, broil, brush, char, charred, dip, dredge, drip, grate, insert, marinade, marinate, massage, pierce, poke, prick, rub, shake, slash, slather, smear, thread

Cluster 4 (6):
deflate, floured, knead, punch, rise, rising

Cluster 5 (19):
arrange, coat, decorate, distribute, divide, dollop, dress, dressing, drizzle, garnish, ladle, mound, presentation, scatter, serve, spread, sprinkle, top, toss

Cluster 6 (28):
crimp, fill, flatten, flip, foil, fold, grease, moisten, mould, pack, preheat, press, repeat, roll, seal, shape, spray, square, stack, stretch, strip, stuff, tie, tuck, unfold, unroll, unwrap, wrap

Cluster 7 (52):
assemble, clean, cool, crockpot, defrost, dripping, drop, dry, dump, freezing, hold, measure, moist, move, note, open, pick, place, pour, prepare, pressure, pull, push, put, reheat, remove, reserve, rest, save, scoop, scrape, select, separate, set, skin, snap, sort, split, sprout, squash, squeeze, style, take, thaw, throw, touch, transfer, turn, warm, wet, wipe, yield


---

### **DBSCAN**
DBSCAN categorized almost all verbs into one large cluster (-1) due to its density-based nature.

---

### **Gaussian Mixture Models (GMM)**
GMM yielded clusters almost identical to KMeans, showing stable structure in the embedding space.

Cluster 0 (31):
absorbed, boil, braise, bubble, bubbling, check, curdle, deglaze, dissolve, evaporate, evaporated, foam, heat, meld, raise, reduce, roux, scald, scorching, settle, simmer, sit, skim, stand, steep, stew, stirring, thicken, uncover, uncovered, wilt

Cluster 1 (21):
burn, caramelize, cook, fry, pan-fry, pop, saute, scramble, sizzle, smoke, smoking, soften, splutter, start, stir, stir-fry, stop, sweat, swirl, wait, wok

Cluster 2 (38):
arrange, assemble, bake, carve, coat, dash, decorate, dip, distribute, divide, dollop, dress, dressing, drizzle, fill, fold, garnish, ladle, moisten, mound, place, pour, presentation, repeat, scatter, season, seasoning, serve, slice, smear, splash, spread, sprinkle, stack, style, taste, top, toss

Cluster 3 (19):
deflate, dust, flatten, floured, grease, knead, mould, press, punch, rise, rising, roll, shape, square, stretch, unfold, unroll, wet, wrap

Cluster 4 (29):
barbecue, baste, broil, brush, caramelized, char, charred, drip, flip, foil, glaze, grate, griddle, invert, marinade, marinate, move, preheat, roast, rotate, sear, slather, spray, thread, tilt, toast, turn, unmold, unwrap

Cluster 5 (76):
add, blanch, blot, break, butter, chop, clean, cool, cover, crockpot, crumble, defrost, dice, drain, dripping, drop, dry, dump, flake, freezing, handle, hold, immerse, lard, measure, melt, mince, minced, moist, note, open, overcook, pack, parboil, peel, pick, poach, pre-heat, prepare, pressure, push, put, reheat, remove, replace, reserve, rest, rinse, save, scoop, scrape, select, separate, set, shred, smash, snap, soak, sort, split, sprout, squash, squeeze, steam, sterilize, submerge, take, tear, test, thaw, throw, touch, transfer, warm, wipe, yield

Cluster 6 (24):
crimp, cut, devein, dredge, insert, massage, pat, pierce, poke, prick, pull, rub, scrub, seal, skin, slash, slit, strip, stuff, tie, trim, tuck, twist, wash

Cluster 7 (32):
beat, blend, blitz, chill, combine, condensed, cream, crush, flavoring, frost, grind, ice, mash, mix, muddle, overmix, powdered, process, puree, refrigerate, shake, sieve, sift, smooth, store, strain, stream, sweeten, whip, whirl, whisk, zest

## 🚀 Key Insights
- Heating, frying, simmering verbs naturally grouped together.
- Cutting and chopping actions formed tight clusters due to strong semantic similarity.
- Mixing/combining verbs consistently clustered as a separate category.
- Assembling/decorating verbs formed clear presentation-focused groups.
- DBSCAN struggled due to sparse text vectors — highlighting its sensitivity.

---
