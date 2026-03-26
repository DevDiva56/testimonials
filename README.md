# Frontend Mentor - Testimonials Grid Section Solution

This is my solution to the Testimonials Grid Section challenge on Frontend Mentor. This project helped me practice CSS Grid, layout structuring, and responsive design.

---

## 📌 Overview

### The Challenge

Users should be able to:
- View the optimal layout depending on their device screen size

---

### 📸 Screenshot

![Screenshot](images/Testimonal%20Screenshot.png)

---

### 🔗 Links

- Solution URL:  https://github.com/DevDiva56/testimonials
- Live Site URL: 

---

## 🚀 My Process
I started by structuring the HTML using reusable card components. Each testimonial was built as a `.card` with consistent internal sections like `.profile`, `.title`, and `.quote`.

Next, I set up a CSS Grid layout using a 4-column system to match the design. I used grid spanning to position the cards correctly, such as making some cards span multiple columns or rows.

For internal alignment, I used Flexbox to align profile images and text within each card.

After the layout was working, I focused on styling — adding colors, spacing, typography, and shadows to match the design closely.

Finally, I refined the UI by improving text hierarchy, positioning decorative elements like the quotation background, and ensuring consistency across all cards.

### 🛠 Built With

- Semantic HTML5
- CSS Grid
- Flexbox
- Mobile-first workflow
- Google Fonts

---

### 🧠 What I Learned

This project helped me better understand how to structure layouts using CSS Grid and how to combine it with Flexbox for internal alignment.

One key thing I learned was how to position elements using grid spanning:

```css
.card--purple {
  grid-column: span 2;
}

.card--wheat {
  grid-row: span 2;
}
```
I also learned how to properly structure reusable components using classes like .card and modifier classes like .card--purple.

📈Continued Development

Going forward, I want to:

Improve my responsiveness skills
Get more comfortable with complex CSS Grid layouts
Write cleaner and more scalable CSS

👩🏽Author
Name: Emeri Lopua
Frontend Mentor: https://www.frontendmentor.io/profile/DevDiva56

