
# HEROES

- **TOLLYWOOD**
  - ~~ALLU ARJUN~~
  - ~~PAWAN KALYAN~~
  - PRABHAS

- **BOLLYWOOD**
  - *RANBHIR* (underlined in HTML)
  - RANVEER
  - DEEPIKA

- **MARVEL STUDIO**
  - **AVENGERS**
    - **IRONMAN**
    - *THOR*
    - CAPTAIN AMERICA
  - **X-MEN**
    - <sub>WOLVERINE</sub> (small text in HTML)
    - <sup>VAMSHI</sup> (big text in HTML)
    - MAGNETO
```

### HTML Structure:
- The `<!DOCTYPE html>` declaration defines the document as an HTML5 document.
- The `<html lang="en">` tag specifies that the language of the document is English.
- The `<head>` section contains metadata:
  - `<meta charset="UTF-8">` defines the character encoding as UTF-8, ensuring proper display of characters.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` makes the webpage responsive, scaling well on all devices.
  - `<title>Document</title>` defines the title of the webpage displayed in the browser tab.

### `<body>` Content:
The `<body>` contains a nested list structure representing three main categories (`HEROS`, `BOLLYWOOD`, and `MARVEL STUDIO`). Each category is styled with various HTML tags for emphasis.

1. **Main Category: HEROS**
   - `<mark>HEROS</mark>`: "HEROS" is highlighted using the `<mark>` tag.
   - **Subcategory: TOLLYWOOD**
     - Nested items under TOLLYWOOD include:
       - `<strike>ALLU ARJUN</strike>`: Displays "ALLU ARJUN" with a strike-through line.
       - `<del>PAWAN KALYAN</del>`: Shows "PAWAN KALYAN" as deleted (similar to strike-through).
       - Plain text "PRABHAS" without extra formatting.

2. **Main Category: BOLLYWOOD**
   - **Subcategory items**:
     - `<u>RANBHIR</u>`: Underlines "RANBHIR".
     - Plain text "RANVEER".
     - Plain text "DEEPIKA".

3. **Main Category: MARVEL STUDIO**
   - **Subcategory: AVENGERS**
     - Nested items under AVENGERS include:
       - `<b>IRONMAN</b>`: Bold text "IRONMAN".
       - `<i>THOR</i>`: Italicized text "THOR".
       - Plain text "CAPTAIN AMERICA".
   - **Subcategory: X-MAN**
     - Nested items under X-MAN include:
       - `<small>WOLWAREN</small>`: Displays "WOLWAREN" in smaller text.
       - `<big>VAMSHI</big>`: Displays "VAMSHI" in larger text.
       - Plain text "MAGNETOO".

### Visual Hierarchy & Styling:
- The structure is mainly a nested list, but some mistakes are made with `<ul>` nesting. Proper `<ul>` and `<li>` nesting should be ensured.
- Different HTML tags like `<mark>`, `<strike>`, `<del>`, `<b>`, `<i>`, `<u>`, `<small>`, and `<big>` are used to add emphasis or style.
