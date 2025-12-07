---
marp: true
theme: custom-iitm
paginate: true
_paginate: true
---

<style>
/* @theme custom-iitm */
section {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  background-color: #050816;
  color: #f5f5f7;
  padding: 2.5rem;
}

section.lead {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

h1, h2, h3 {
  letter-spacing: 0.03em;
}

code, pre {
  font-family: "JetBrains Mono", Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  font-size: 0.85rem;
}

footer {
  position: absolute;
  bottom: 12px;
  right: 32px;
  font-size: 0.7rem;
  opacity: 0.7;
}

/* Page numbers in the bottom-left corner */
section::after {
  content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 12px;
  left: 32px;
  font-size: 0.7rem;
  opacity: 0.7;
}

/* Accent box style */
.accent-box {
  border-radius: 0.75rem;
  padding: 1rem 1.5rem;
  border: 1px solid rgba(255, 255, 255, 0.2);
  background: radial-gradient(circle at top left, rgba(129, 140, 248, 0.3), transparent 60%);
}

.math-box {
  font-size: 1.2rem;
}
</style>

<!-- _class: lead -->
# Marp Demo Presentation

### Custom Theming, Math & Styling

**Author:** R. Sanjit  
**Email:** <24f3002886@ds.study.iitm.ac.in>

<footer>Marp + Custom Theme Demo</footer>

---

<!-- _class: lead -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80)

# Slide with Background Image

A demo slide using a full-screen background image.  
Text is still readable using the custom theme.

<footer>Background Image Slide</footer>

---

<!-- _class: lead -->
# Custom Theme & Directives

<div class="accent-box">

- **Custom theme name:** `custom-iitm`  
- Defined via a `&lt;style&gt;` block in this file  
- Uses:
  - Dark background (`#050816`)
  - Sans-serif system fonts
  - Rounded “accent” boxes

</div>

**Marp directives used:**

- `marp: true` — enable Marp
- `theme: custom-iitm` — use the custom theme
- `paginate: true` and `_paginate: true` — enable page numbers
- Slide-level directives like `<!-- _class: lead -->`

<footer>Theme & Directives</footer>

---

# Algorithmic Complexity (Math Demo)

<div class="accent-box math-box">

Time complexity of **Merge Sort**:

$$
T(n) = 2T\left(\frac{n}{2}\right) + O(n)
$$

Solving the recurrence:

$$
T(n) = O(n \log n)
$$

</div>

Other common complexities:

- Constant time: \( O(1) \)
- Linear time: \( O(n) \)
- Quadratic time: \( O(n^2) \)
- Exponential time: \( O(2^n) \)

<footer>Mathematical Equations in Marp</footer>

---

# Another Example: Space Complexity

For an algorithm that only stores a constant number of variables:

$$
S(n) = O(1)
$$

For an algorithm using an auxiliary array of size \( n \):

$$
S(n) = O(n)
$$

> In general, we describe space and time complexities using **Big-O notation**  
> to express asymptotic upper bounds.

<footer>Space Complexity Examples</footer>

---

# Contact & Summary

- **Name:** R. Sanjit  
- **Email:** <24f3002886@ds.study.iitm.ac.in>

**This presentation showed:**

- ✅ Email included in the slides  
- ✅ Custom theme (`custom-iitm`)  
- ✅ Page numbers via CSS and `paginate`  
- ✅ A slide with a background image  
- ✅ Custom styling using Marp directives and CSS classes  
- ✅ Mathematical equations for algorithmic complexity  

<footer>Thank You!</footer>
