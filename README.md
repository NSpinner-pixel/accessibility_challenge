# Accessibility Challenge – Final Project

This repo includes both parts of my final accessibility challenge. I went through the original broken code and fixed all the major accessibility issues using what I’ve learned.

---

## 🔧 Final Challenge 1

This was a contact page that had a lot of problems like:
- Bad color contrast
- No alt text on the image
- Inputs with no labels
- Button text wasn’t clear
- The layout used generic tags instead of real HTML5 tags

I cleaned it up by using semantic HTML (like section, main, etc.), added proper labels to the inputs, made sure color contrast was readable, and added alt text to the image.

---

## 🔧 Final Challenge 2

The second challenge was a broken CSS and HTML file that needed fixing. It had:
- Messed up syntax (extra colons, wrong spacing)
- Inconsistent font settings
- Placeholder text with poor contrast
- Inputs with no real styling
- Units like `px` where `rem` would be better

I fixed all that, made it accessible, and now it looks cleaner and works better for all users — including screen reader users.

---

## 🧠 Reflection Questions

**What accessibility enhancements were the most challenging to implement, and why?**  
Making sure everything had the right contrast and worked for screen readers was a little tricky at first. Also getting used to semantic tags and remembering to use them right took some focus.

**How do ARIA attributes improve the experience for users relying on assistive technologies?**  
ARIA gives extra information to screen readers and helps people understand what each element is supposed to do — like buttons, forms, etc.

**What tools did you use to check color contrast, and how did they help?**  
I used the WebAIM Contrast Checker. It helped me find which colors needed to be changed so the text stood out better for people with low vision or color blindness.
