# Coffee & Vibess — Website System Brief

> Project context and implementation rules for the website development assistant.
>
> **Important:** Some business details below came from a public directory listing, not direct confirmation from the café. Treat them as provisional and do not publish them until verified.

---

## 1. Project Overview

Build the official website for **Coffee & Vibess**, a coffee brand with an Instagram presence and a distinctive visual identity built around branded takeaway cups, coffee preparation, and the message **“More Than Coffee.”**

The website should feel like a real, professionally art-directed café website—not a generic template, a static poster, or an over-decorated advertisement.

### Reference websites and assets

- Website layout inspiration: <https://zaina-cafe.com/>
  - Use only as inspiration for page structure, navigation composition, section variety, and visual storytelling.
  - Do not copy its logo, colors, images, typography, or brand identity.
- Brand/content reference: <https://www.instagram.com/coffee_and_vibess/>
- Use the user-provided screenshots and supplied brand assets as the primary visual references.

---

## 2. Brand Name and Logo

### Naming note

There is a spelling difference between the Instagram handle and the visible cup branding:

- Instagram handle: `coffee_and_vibess` (double **s** at the end of the handle).
- Visible cup wordmark in the supplied screenshots: `COFFEE & VIBES` (single **s** at the end of “Vibes”).
- Working project name used in this brief: **Coffee & Vibess**.

**Do not silently normalize or redesign the spelling.** Use the supplied original logo/wordmark asset when available, and confirm the final public-facing spelling with the owner before launch.

### Logo characteristics visible in supplied references

- A circular emblem containing the stylized letters `CAV`.
- The wordmark `COFFEE & VIBES`.
- Arabic brand lettering appears with the emblem on some cup designs.
- The mark appears in light ink on black cups and in dark ink on light cups.

### Logo rules

- Use the original supplied logo file whenever available (prefer SVG or transparent PNG).
- Do not redraw, reinterpret, regenerate, distort, crop, stretch, or substitute the original logo.
- Preserve its proportions and clear space.
- Do not treat an AI-generated approximation on a mockup as the official logo asset.

---

## 3. Brand Identity and Visual Direction

### Overall personality

- Modern
- Youthful
- Premium but approachable
- Minimal and confident
- Coffee-focused
- Atmospheric without being visually noisy

### Color direction

Use the brand direction visible in the supplied Instagram content and cup photography:

| Color family | Intended use |
|---|---|
| Pure black | Main dark backgrounds and dominant brand surfaces |
| Charcoal | Secondary dark backgrounds and depth |
| White | High-contrast text and logo treatments |
| Off-white / light cream | Light sections and supporting typography |
| Champagne gold | Very restrained accents, only where useful |
| Natural coffee brown | Coffee beans, coffee, crema, and product photography only |

**Critical color rule:** Brown must not become a dominant UI color. Do not use brown as a page background, section background, button fill, navigation color, or broad decorative surface. Brown should come from actual coffee-related imagery only.

Do not invent official HEX values. Derive exact tokens from supplied brand assets or confirm them with the owner before finalizing the palette.

### Photography direction

Prioritize authentic brand imagery:

- Actual branded cups and packaging
- Espresso extraction and coffee preparation
- Latte art
- Hot and iced drinks
- Café interior and real customer atmosphere
- Coffee beans and ingredients

Use crisp, realistic photography with controlled lighting. Avoid unrelated stock imagery and avoid turning every section into a dark cinematic poster.

---

## 4. Typography

The official brand fonts have not been confirmed.

Suggested starting pairings (recommendations only):

- English headings: **Space Grotesk** or **Plus Jakarta Sans**
- English body: **Plus Jakarta Sans**
- Arabic headings: **Alexandria**
- Arabic body: **IBM Plex Sans Arabic**

Choose a coherent pairing after reviewing the actual logo and brand materials. Do not claim these are the café's official fonts.

The website must support both Arabic and English, with correct:

- `dir="rtl"` / `dir="ltr"`
- Text alignment
- Navigation order
- Spacing and layout direction
- Font selection

---

## 5. Core Brand Message

Primary brand message visible in the supplied content:

**MORE THAN COFFEE**

Arabic rendering used in the supplied references:

**أكثر من مجرد قهوة**

Use this message naturally in the hero and brand-story sections. Avoid generic marketing claims or invented brand history.

---

## 6. Website Structure

Build a single-page website with the following sections:

1. Navigation bar
2. Hero
3. About Us
4. Menu
5. Gallery
6. Contact and Location
7. Footer

Use smooth in-page navigation and a responsive layout.

### Navigation bar

- Place the original logo centrally on desktop.
- Arrange the main navigation links around it where practical.
- Links: Home, About Us, Menu, Gallery, Contact Us.
- Include a functional Arabic/English language switcher.
- Use a clean sticky or floating treatment that remains readable while scrolling.
- On mobile, use a compact accessible menu while keeping the logo visible.

### Hero

The hero direction agreed with the owner:

- Keep the hero simple and website-like, not poster-like.
- Use a large standalone product image as the main focal point.
- Place oversized brand typography behind the product, with the product overlapping it.
- Keep the background clean and visually quiet.
- Use a black/charcoal base with off-white typography.
- Use coffee beans as photographic elements only; do not create a brown background or a floor/table full of beans.
- The intended product image is an open black branded cup, slightly tilted, containing a latte/coffee with visible latte art, with coffee beans floating behind and around it.
- Do not use a lid on the hero cup.
- Do not add a floor, table, platform, or ground shadow beneath the product.
- Preserve the actual CAV logo on the cup.

Suggested hero copy:

- `MORE THAN COFFEE`
- `أكثر من مجرد قهوة`
- Primary action: `Explore Our Menu`

Include social media icons and a location icon in the hero. Use only confirmed official URLs; do not invent destinations.

### About Us

- The owner will supply an actual café/location photograph.
- Use that photograph as the main visual feature.
- Write concise, natural Arabic and English copy based on the supplied brand identity and the message “More Than Coffee.”
- The text may describe coffee as an experience and the café atmosphere, but must not invent a founding date, origin story, number of branches, certifications, sourcing claims, or other unsupported facts.
- Do not use generic stock café interiors once the real café photo is supplied.

### Menu

- The owner will provide the actual menu as a PDF.
- Embed the supplied PDF in a usable viewer/container.
- Include `View Full Menu` and `Download Menu` actions.
- Ensure the PDF can be accessed on mobile and desktop.
- Until the PDF is supplied, use a clearly labeled placeholder.
- Do not invent menu items, descriptions, or prices.

### Gallery

Create a distinctive **stacked photo-card deck** rather than a conventional horizontal slider.

Expected behavior:

1. Several real café/product photographs appear as overlapping cards.
2. The top card moves smoothly out of the front position.
3. It rotates slightly and moves to the back of the stack.
4. The next card becomes the top card.
5. The sequence repeats in an automatic infinite loop.

Requirements:

- Use actual Coffee & Vibess photos when supplied.
- Use natural image proportions and modest corner rounding.
- Use subtle rotation and depth; avoid exaggerated shadows.
- Pause the automatic motion on hover where appropriate.
- Support touch interaction on mobile where feasible.
- Respect `prefers-reduced-motion` and provide a usable static state.
- Until real photos are supplied, use clearly named placeholders rather than unrelated stock photos.

Suggested section title: `THE VIBES` or `OUR MOMENTS`.

### Contact and Location

Include:

- Contact heading and short invitation
- Official social links
- Address (only after confirmation)
- Google Maps link or embed (only after confirmation)
- Phone number (only after confirmation)
- WhatsApp action (only after confirmation)
- Working hours (only after confirmation)

### Footer

Include:

- Original logo
- Brand tagline
- Section navigation
- Confirmed social links
- Confirmed location link
- Copyright line

Keep it minimal and consistent with the visual identity.

---

## 7. Business Information — Provisional, Must Be Verified

The following details were previously found in a public business-directory listing. They are **not confirmed directly by the café owner** and must not be treated as final website content until verified.

| Field | Provisional information | Status |
|---|---|---|
| Business name | Coffee & Vibes | Verify preferred public spelling |
| City | Mansoura, Dakahlia, Egypt | Unconfirmed |
| Area | Hay El Gama'a, Taksim Khattab | Unconfirmed |
| Address description | Gehan Street, opposite the University Gate | Unconfirmed |
| Listed phone | `0502230304` | Unconfirmed |
| Coordinates | `31.0412928, 31.3643879` | Unconfirmed |

Provisional map link:

<https://www.google.com/maps?q=31.0412928,31.3643879>

Directory reference previously consulted:

<https://egmaps.com/place?id=d000f564-9fef-4b4a-b568-52a163975cbe&lang=en>

**Implementation rule:** Keep these values in a clearly labeled configuration object with a verification flag, or leave them unset until confirmed. Do not publish provisional address/phone/map details as verified facts.

---

## 8. Social Media Links — Known and Missing

| Platform | URL | Status |
|---|---|---|
| Instagram | <https://www.instagram.com/coffee_and_vibess/> | Supplied by owner |
| Facebook | Not provided | Pending official URL |
| TikTok | Not provided | Pending official URL |
| WhatsApp | Not provided | Pending official number/link |

Rules:

- Use the supplied Instagram URL.
- Do not guess Facebook, TikTok, or WhatsApp URLs.
- Hide icons for unavailable platforms rather than linking them to fabricated pages.
- Add the remaining URLs when the owner supplies them.

---

## 9. Technical Requirements

Use only:

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)

Do not use:

- React
- Next.js
- Vue
- Angular
- Bootstrap
- Tailwind CSS
- Other frontend frameworks

Keep HTML, CSS, and JavaScript separate and organized.

Suggested structure:

```text
coffee-vibess/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── main.js
│   └── config.js
├── assets/
│   ├── images/
│   ├── logo/
│   ├── icons/
│   └── menu/
└── README.md
```

Use a central configuration file for editable business data, for example:

```js
export const siteConfig = {
  brandName: "Coffee & Vibes",
  instagram: "https://www.instagram.com/coffee_and_vibess/",
  facebook: "", // Add only after owner supplies official URL.
  tiktok: "",   // Add only after owner supplies official URL.
  whatsapp: "", // Add only after owner confirms number/link.
  phone: "",    // Do not publish provisional phone without confirmation.
  address: "",  // Add after owner confirms address.
  mapsUrl: "",  // Add after owner confirms map pin.
  workingHours: ""
};
```

If using JavaScript modules, run through a simple local development server. Keep the project easy to run and hand off.

---

## 10. Motion and Interaction Rules

Use restrained motion only:

- Smooth scrolling
- Subtle section reveal
- Gentle hero product movement, if it does not distract
- Small hover feedback for buttons and icons
- Smooth navigation transitions
- Automatic stacked-card gallery loop

Use `IntersectionObserver` for scroll-triggered reveals where useful.

Respect `prefers-reduced-motion`. Avoid flashy, rapid, or excessive animation.

---

## 11. Responsive Design and Quality

Test and support:

- Large desktop
- Laptop
- Tablet
- Mobile

Ensure:

- No horizontal overflow
- Readable Arabic and English typography
- Correct RTL and LTR layouts
- Scaled hero product image
- Functional mobile navigation
- Mobile-friendly PDF viewing
- Gallery remains usable on touch devices
- Appropriate image loading and lazy loading
- Semantic HTML and accessible controls
- No browser console errors

---

## 12. Assets Still Needed From the Owner

Do not invent or substitute these assets:

1. High-resolution original CAV logo (prefer SVG or transparent PNG).
2. Final approved hero product cutout/image.
3. Actual café/location photograph for About Us.
4. Official menu PDF.
5. Real photographs for the Gallery.
6. Official Facebook URL, if available.
7. Official TikTok URL, if available.
8. Confirmed WhatsApp number/link.
9. Confirmed address and Google Maps pin.
10. Confirmed phone number and working hours.
11. Confirmation of the official public spelling: `Coffee & Vibes` or `Coffee & Vibess`.
12. Official brand font names and exact color values, if documented.

---

## 13. Non-Negotiable Instructions

- Do not invent business facts, addresses, opening hours, product names, or prices.
- Do not create fake social media links.
- Do not redraw or replace the original logo.
- Do not use brown as a dominant UI/background color.
- Do not make the hero look like a promotional poster.
- Do not use a lidded cup in the agreed hero concept.
- Do not add a floor/table beneath the hero product.
- Do not replace owner-provided café photographs with generic stock imagery.
- Do not create a fake menu while the real PDF is unavailable.
- Keep the website bilingual, responsive, and built with plain HTML, CSS, and Vanilla JavaScript.

The final experience should express the brand message:

# More Than Coffee.
