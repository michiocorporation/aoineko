# 水彩イラストの制作記録

生成方式: built-in image_gen。Web用にWebP変換・サイズ最適化。SNSカードは1200 × 630pxにサイズ調整。

保存先（このプロジェクト内）:

- インコ: `assets/parakeet.webp`
- 犬: `assets/dog.webp`
- 風景: `assets/landscape.webp`
- OGP / LINE / SNSカード: `og.png`

参考写真が未提供のため、以下のプロンプトをもとにオリジナルの水彩画として生成しています。

## bird

```text
Use case: illustration-story
Asset type: standalone watercolor cutout for the Japanese haiku poet AOI NEKO profile website, 1024 x 1024 square.
Primary request: One elegant small blue budgerigar/parakeet perched on a single thin olive/sage leafy branch with one or two tiny muted yellow flowers.
Style/medium: authentic traditional botanical watercolor, mature Japanese literary book illustration, softly granular pigments and delicately controlled fine brushwork, anatomically believable bird, quietly sophisticated.
Composition: predominantly the bird, centered with generous clear margins. Show the entire bird including its long uncut tail. Sparse organically spaced leaves. No extraneous objects.
Color palette: blue #567C9D with lighter powder blue feathers, sage/olive #789B72, muted ochre #E5C75A accents.
Backdrop: truly transparent alpha background. Only the bird and branch are painted; no paper rectangle, no shadow box, no simulated checkerboard.
Constraints: no cartoon, no exaggerated eyes, no words, no watermark, no interface, no frame.
```

## dog

```text
Use case: illustration-story
Asset type: standalone watercolor cutout for the Japanese haiku poet AOI NEKO profile website, 1024 x 1024 square.
Primary request: One calm small tan and cream dog sitting in profile facing toward the left. Entire body fully visible, soft ears and a tiny tuft of sage grass at its feet.
Style/medium: authentic traditional botanical watercolor, mature Japanese literary book illustration, softly granular pigments and delicately controlled fine brushwork, anatomically believable small dog, quiet gentle presence.
Composition: centered full body with generous clear margins, sparse detail.
Color palette: soft tan and cream fur, subdued ochre #E5C75A in the warm pigments, grass #789B72. Cohesive with a watercolor blue budgerigar motif in #567C9D.
Backdrop: truly transparent alpha background. Only the dog and tiny grass tuft are painted; no paper rectangle, no shadow box, no simulated checkerboard.
Constraints: no accessories, no collar, no toys, no cartoons, no exaggerated eyes, no words, no watermark, no interface, no frame.
```

## landscape

```text
Use case: illustration-story
Asset type: literary editorial watercolor landscape vignette for Japanese haiku poet AOI NEKO website, landscape 1536 x 1024.
Primary request: light powder-blue wash suggesting distant sky and water, olive sage grasses and fine leafy branches with a few pale ochre flowers chiefly along the right and bottom. One small naturalistic blue budgerigar perched to the upper right and one calm small tan and cream dog seated at lower right facing toward the left.
Style/medium: authentic traditional botanical watercolor, quiet mature Japanese literary book illustration. Delicate brushwork, gentle pigment granulation, washed transparent layers.
Composition: abundant clean negative space in the entire left half for later website copy. Motifs and the two animals concentrated on right, subtle wash and organic edges fading seamlessly into very light ivory paper #FCFCF7. Show complete bird and complete dog.
Palette: sage #789B72, muted blue #567C9D with very pale powder blue wash, ochre #E5C75A, ivory #FCFCF7. Light and breathable, elegant rather than cute.
Constraints: no words, no interface, no borders, no watermark, no cartoons, no exaggerated eyes, no pet accessories.
```

## social_card

```text
Use case: ads-marketing
Asset type: finished social sharing card for Japanese haiku poet AOI NEKO profile website. Target aspect ratio 1200 x 630, landscape.
Primary request: a refined cream background #FCFCF7 and one small blue budgerigar with one small calm tan and cream dog together as a sophisticated watercolor visual in the lower left. Restrained sage green and muted blue botanical edge marks. Mature Japanese literary editorial aesthetic with true traditional watercolor granulation. Wide empty margins.
Composition: small watercolor animals at left-lower; elegant Japanese typography in the center-right with abundant spacing. Keep text crisp, very legible, and spelled exactly. Large graceful Japanese Mincho title, smaller spaced Roman serif secondary line, discreet Japanese tagline below.
Text (verbatim): title '蒼井 音呼'; secondary 'AOI NEKO'; tagline '俳句とことばのプロフィールサイト'. Render these exact three text strings and no other text. Main title largest, Roman line medium-small, tagline readable. Dark muted ink green or blue typography.
Palette: #789B72 sage green, #567C9D blue, #E5C75A muted ochre accents, #FCFCF7 cream paper.
Constraints: no cartoon, no exaggerated eyes, no pet accessories, no interface, no watermark, no frame, no invented name or extra text.
```
