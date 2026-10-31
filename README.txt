OUTERLY — Jacket Boutique (static site)

PAANO BUKSAN
  I-double-click ang index.html. Walang kailangang i-install.

MGA FILE
  index.html            ang buong page (HTML, CSS, JS)
  assets/wall-bg.jpg    background na wall at rail
  assets/jacket-side.webp / jacket-front.webp / jacket-back.webp
                        mga larawan ng hoodie (transparent background, walang hook)

PAANO MAG-ADD / MAGPALIT NG JACKET
  1. Sa index.html, hanapin ang  const IMG={...}  at ang  const P=[...]
  2. Ang P ay listahan ng produkto: n = pangalan, p = presyo, d = description.
  3. Palitan ang tatlong larawan sa assets/ ng sarili mong side/front/back
     (transparent PNG/WEBP, parehong sukat 720x975, nakaharap sa kaliwa ang side).
  4. Ang "v" ("v2","v3","v4") ay preview colorway lang; alisin kapag may sariling larawan na.

TIP: Para i-host, i-upload ang buong folder sa Netlify, Vercel, GitHub Pages, o kahit anong hosting.
