# DevConf 2026 – Landing Page

Hi! This is my assignment project. I built a landing page for a fake
tech conference called **DevConf 2026** using only basic **HTML** and
**CSS**. No JavaScript, no frameworks — just plain code so I could
practice the fundamentals.

## What's inside the page

- **Navbar** – logo on the left, menu links in the middle, a
  "Register Now" button on the right
- **Hero section** – big heading, short paragraph, and a button on top
  of a background image
- **Speakers section** – a 2x2 grid of speaker cards (photo, tag,
  name, title)
- **Pricing section** – three plans (Standard, Pro, Team) with the
  Pro plan highlighted
- **Hackathon section** – my own bonus section idea (the assignment's
  "AI challenge" part). I used AI to help me brainstorm and write this
  one, prompts are in `PROMPTS.md`
- **Footer** – logo, social links with icons, a divider line, and a
  copyright line

## Files

```
index.html      -> all the page content
style.css       -> all the styling
PROMPTS.md      -> AI prompts used for the hackathon section
Images/         -> logo, speaker photos, icons, background image
```

## How to open it

1. Download or clone this repo
2. Open `index.html` in your browser (or use Live Server in VS Code)

That's it, no installs, no build steps.

## What I learned

- Using `nav`, `section`, and `article` tags to structure a page
  instead of just `div` everywhere
- Flexbox (`display: flex`, `justify-content`, `align-items`) for
  lining things up
- CSS Grid (`display: grid`) for a clean 2-column speaker layout
- Keeping class names consistent between HTML and CSS (I broke my
  page more than once from a single typo here!)
- Making one section look "featured" just by changing its background
  color

## Notes

- Built for learning, so the code is kept simple on purpose.
- Not mobile-perfect yet, still improving that part.