# Product Images Directory

This directory stores the high-resolution product packshot photography files for all **90 products** in the **AuraVital Essentials** demo catalog.

## Image Requirements
- **Format:** `.png` (Lossless RGB)
- **Dimensions:** `1200 x 1200 px`
- **Aspect Ratio:** `1:1 (Square)`
- **Background:** Crisp studio white (`#FFFFFF`) or soft neutral off-white/beige gradient
- **Lighting:** Soft diffused commercial studio light with natural soft drop shadow
- **Total Images:** **90 files** (Exactly 1 primary packshot image per product: `<handle>.png`)

---

## File Naming Convention
For every product handle:
- **Primary Product Image:** `<handle>.png` (Hero front packaging view)

---

## Automated Verification
Run the image checker script from the repository root at any time:
```bash
node scripts/check-images.js
```
The script reads `demo-assets/products_import.csv`, checks that all 90 referenced images exist in this directory, and reports any missing or unreferenced extra files.

---

## Complete List of Product Image Files (90 Files)

### 1. Baby & Mom (`baby-mom`)
1. `soothing-baby-lotion-250ml.png`
2. `organic-baby-shampoo-wash-300ml.png`
3. `soothing-diaper-barrier-balm-100g.png`
4. `postnatal-comfort-stretch-oil-120ml.png`
5. `natural-nursing-nipple-butter-50g.png`
6. `gentle-baby-massage-oil-200ml.png`
7. `soft-bamboo-baby-wipes-pack.png`

### 2. Skin Care (`skin-care`)
8. `vitamin-c-glow-antioxidant-serum-30ml.png`
9. `hyaluronic-acid-hydra-plump-serum-50ml.png`
10. `ceramide-barrier-repair-moisturizer-60ml.png`
11. `gentle-foaming-botanical-cleanser-150ml.png`
12. `soothing-rosewater-balancing-toner-200ml.png`
13. `retinol-rejuvenating-night-treatment-30ml.png`
14. `peptide-firming-under-eye-cream-15ml.png`
15. `clarifying-green-clay-detox-mask-100g.png`

### 3. Supplements & Herbal Teas (`supplements-herbal-teas`)
16. `calming-chamomile-lavender-tea-25-bags.png`
17. `organic-pure-matcha-green-tea-powder-100g.png`
18. `digestive-peppermint-fennel-infusion-20-bags.png`
19. `spiced-golden-turmeric-ginger-blend-150g.png`
20. `marine-collagen-peptide-powder-300g.png`
21. `high-potency-vitamin-d3-k2-drops-60ml.png`
22. `organic-ashwagandha-root-extract-60-capsules.png`
23. `triple-magnesium-complex-glycinate-90-capsules.png`

### 4. Health & Wellness (`health-wellness`)
24. `aromatherapy-essential-oil-relief-roll-on-10ml.png`
25. `herbal-heating-pad-neck-shoulder-wrap.png`
26. `pure-epsom-magnesium-bath-soak-1kg.png`
27. `rechargeable-deep-tissue-percussion-massage-gun.png`
28. `organic-cold-pressed-black-seed-oil-100ml.png`
29. `acupressure-mat-pillow-wellness-set.png`
30. `air-purifying-himalayan-pink-salt-lamp.png`
31. `organic-herbal-immunity-elderberry-syrup-250ml.png`

### 5. Makeup & Beauty (`makeup-beauty`)
32. `velvet-matte-liquid-lipstick-6ml.png`
33. `dewy-glow-multi-tint-cheek-lip-balm-15g.png`
34. `mineral-hydra-setting-translucent-powder-12g.png`
35. `waterproof-precision-felt-tip-eyeliner-1ml.png`
36. `lash-lift-volumizing-peptide-mascara-10ml.png`
37. `nourishing-tinted-hydra-lip-oil-8ml.png`
38. `illuminating-liquid-strobe-highlighter-30ml.png`
39. `organic-dual-phase-micellar-eye-makeup-remover-150ml.png`

### 6. Hair Care (`hair-care`)
40. `botanical-biotin-strengthening-shampoo-350ml.png`
41. `nourishing-argan-deep-repair-conditioner-350ml.png`
42. `reparative-keratin-hair-mask-250ml.png`
43. `rosemary-mint-scalp-root-stimulating-oil-60ml.png`
44. `anti-frizz-heat-protectant-smoothing-spray-200ml.png`
45. `clarifying-orchard-cider-scalp-scrub-200g.png`
46. `organic-flaxseed-curl-defining-gel-250ml.png`

### 7. Oral Care (`oral-care`)
47. `natural-activated-charcoal-whitening-toothpaste-100ml.png`
48. `sensitive-enamel-repair-mineral-toothpaste-100ml.png`
49. `biodegradable-bamboo-toothbrush-pack-4.png`
50. `botanical-oil-pulling-swish-mint-250ml.png`
51. `alcohol-free-soothing-herbal-mouthwash-500ml.png`
52. `biodegradable-cornstarch-dental-floss-picks-50pk.png`
53. `portable-cordless-smart-water-dental-flosser.png`

### 8. Personal Care (`personal-care`)
54. `natural-aluminum-free-eucalyptus-deodorant-75g.png`
55. `exfoliating-coffee-sugar-body-polish-300g.png`
56. `nourishing-raw-shea-body-butter-200g.png`
57. `soothing-aloe-cucumber-cooling-gel-250ml.png`
58. `refreshing-botanical-body-wash-citrus-400ml.png`
59. `rejuvenating-hand-cuticle-balm-75ml.png`
60. `natural-loofah-sisal-body-scrub-sponge-duo.png`
61. `botanical-hand-sanitizer-spray-lavender-60ml.png`

### 9. Men's Grooming (`mens-grooming`)
62. `cedarwood-conditioning-beard-oil-50ml.png`
63. `sandalwood-nourishing-beard-balm-60g.png`
64. `cooling-aloe-menthol-aftershave-lotion-100ml.png`
65. `charcoal-exfoliating-mens-face-wash-150ml.png`
66. `double-edge-safety-razor-stainless-steel.png`
67. `energizing-caffeine-daily-mens-moisturizer-75ml.png`
68. `matte-finish-natural-styling-hair-clay-85g.png`

### 10. Home & Cleaning (`home-cleaning`)
69. `all-purpose-citrus-eco-cleaning-spray-500ml.png`
70. `ultra-concentrated-plant-laundry-detergent-1l.png`
71. `natural-dishwashing-liquid-aloe-lemon-650ml.png`
72. `antibacterial-tea-tree-surface-wipes-75ct.png`
73. `mineral-toilet-bowl-cleaner-pine-750ml.png`
74. `microfiber-zero-scratch-cleaning-cloths-6pk.png`
75. `pure-cotton-reusable-wool-dryer-balls-set-6.png`

### 11. Electronics & Gadgets (`electronics-gadgets`)
76. `ultrasonic-ambient-wood-grain-oil-diffuser-400ml.png`
77. `rechargeable-sonic-silicone-facial-cleansing-brush.png`
78. `high-frequency-facial-wand-skin-therapy.png`
79. `smart-led-makeup-mirror-magnifying-light.png`
80. `cordless-heated-eyelash-curler-rechargeable.png`
81. `compact-smart-water-bottle-uv-purifier-600ml.png`
82. `smart-digital-food-kitchen-scale-usb.png`

### 12. Bundles & Combos (`bundles-and-combos`)
83. `complete-radiant-glow-skincare-ritual-bundle.png`
84. `restful-sleep-evening-unwind-wellness-set.png`
85. `pure-organic-baby-welcome-starter-kit.png`
86. `mens-executive-beard-shave-grooming-kit.png`
87. `eco-friendly-clean-home-essentials-pack.png`
88. `botanical-hair-strengthening-repair-duo.png`
89. `complete-flawless-beauty-glam-collection.png`
90. `head-to-toe-botanical-self-care-spa-chest.png`

---

## Hosting and Importing
1. Push these 90 PNG image files to your public GitHub repository under `demo-assets/products/`.
2. Verify image integrity with:
   ```bash
   node scripts/check-images.js
   ```
3. Update `BASE_URL` in `scripts/build-products-csv.js` to point to:
   `https://raw.githubusercontent.com/<YOUR_USER>/<YOUR_REPO>/main/demo-assets`
4. Run `node scripts/build-products-csv.js` to build the CSV.
5. Import `demo-assets/products_import.csv` into Shopify Admin. Shopify will automatically download and assign these images to each product!
