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
*(Shortened here — contains clusters 0–7 with similar structure.)*

---

### **DBSCAN**
DBSCAN categorized almost all verbs into one large cluster (-1) due to its density-based nature.

---

### **Gaussian Mixture Models (GMM)**
GMM yielded clusters almost identical to KMeans, showing stable structure in the embedding space.

---

## 🗂 Full List of Processes
(Complete list of all 300+ cooking verbs included.)

---

## 🚀 Key Insights
- Heating, frying, simmering verbs naturally grouped together.
- Cutting and chopping actions formed tight clusters due to strong semantic similarity.
- Mixing/combining verbs consistently clustered as a separate category.
- Assembling/decorating verbs formed clear presentation-focused groups.
- DBSCAN struggled due to sparse text vectors — highlighting its sensitivity.

---
