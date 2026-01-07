# DJ Mustard Homage Site

## Project Overview

Build a single-page website that's a humorous homage to [baconbeercan.com](https://www.baconbeercan.com/). 

**The concept:** "Mustard on a beat" (DJ Mustard's famous producer tag) sounds exactly like "Mother on a beach" when said quickly. This site lets users discover that fun linguistic coincidence.

## Design Requirements

### Visual Style
- Bold, playful design with a hip-hop/producer vibe
- Yellow/mustard color scheme (`#FFDB58`, `#E1A95F`, or similar) as primary accent
- Dark background for contrast (black or very dark gray)
- Large, prominent buttons that are satisfying to click
- Clean, centered layout
- Mobile-responsive (works great on phones - this is shareable meme content)
- Fun typography - bold, impactful fonts (consider Google Fonts like Bebas Neue, Oswald, or similar)

### Layout Structure
```
┌─────────────────────────────────┐
│                                 │
│      MUSTARD OR MOTHER?         │  ← Fun header/title
│                                 │
│   ┌─────────────────────────┐   │
│   │   MUSTARD ON A BEAT     │   │  ← Big clickable button
│   └─────────────────────────┘   │
│                                 │
│   ┌─────────────────────────┐   │
│   │   MOTHER ON A BEACH     │   │  ← Big clickable button
│   └─────────────────────────┘   │
│                                 │
│      say it fast 🔊             │  ← Hint text
│                                 │
│   inspired by baconbeercan.com  │  ← Footer credit
└─────────────────────────────────┘
```

## Functionality

### Button Behavior
When clicked, each button should:
1. Display prominent visual feedback (scale up, glow, color pulse)
2. Optionally show the text animated/emphasized somewhere
3. Have a satisfying tactile feel (CSS transitions, maybe a subtle shake)

### Interactive Features
- Buttons should have hover states with visual feedback
- Click/tap feedback should feel satisfying
- Consider adding a subtle "sound wave" or "beat" animation on click
- Mobile touch feedback

### Nice-to-Have Enhancements
- Alternating highlight effect encouraging users to click both
- Subtle background pattern or animation (sound waves, vinyl record, etc.)
- Share button for social media
- Easter egg: clicking both buttons rapidly does something fun

## Technical Requirements

### Stack
- **Single HTML file** with embedded CSS and JavaScript
- No frameworks - vanilla HTML/CSS/JS only
- Must work as a static site (deployable to GitHub Pages, Netlify, Vercel, etc.)
- No build step required

### Browser Support
- All modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome for Android)

### Performance
- Fast loading (minimal assets)
- No external dependencies except Google Fonts (optional)
- Should work offline after initial load

## File Structure

Keep it simple:
```
/
├── index.html          # Everything in one file
├── CLAUDE.md           # This file
└── README.md           # Basic project description
```

Or if we want to separate concerns:
```
/
├── index.html
├── styles.css
├── script.js
├── CLAUDE.md
└── README.md
```

## Content

### Text Content
- **Title:** "Mustard or Mother?" (or similar playful header)
- **Button 1:** "MUSTARD ON A BEAT"
- **Button 2:** "MOTHER ON A BEACH"
- **Hint:** "say it fast 🔊" or "try saying both quickly"
- **Footer:** "inspired by baconbeercan.com" with link

### Tone
Fun, silly, meme-worthy. This should make people smile and want to share it. Think viral content energy.

## Design Inspiration

- The original [baconbeercan.com](https://www.baconbeercan.com/) - simple, direct, funny
- DJ Mustard's aesthetic - bold, confident, hip-hop culture
- Meme sites that are instantly shareable
- Big bold buttons like arcade games

## Color Palette Suggestion

```css
--mustard-yellow: #FFDB58;
--mustard-dark: #E1A95F;
--background: #1a1a1a;
--text-light: #ffffff;
--text-muted: #888888;
--accent-glow: rgba(255, 219, 88, 0.4);
```

## Development Notes

### Priority Order
1. Get the basic layout working with two buttons
2. Add satisfying click interactions
3. Style it to look good
4. Add responsive design for mobile
5. Polish with animations and extra touches

### Testing
- Test on mobile devices (this will be shared on phones)
- Test button click feedback feels good
- Verify the joke lands (show someone unfamiliar with it)

## Example User Flow

1. User receives link from friend, opens site
2. Sees two big buttons with "MUSTARD ON A BEAT" and "MOTHER ON A BEACH"
3. Reads "say it fast" hint
4. Says both phrases out loud quickly
5. Realizes they sound identical
6. Laughs, shares with friends

## Attribution

- Concept inspired by [baconbeercan.com](https://www.baconbeercan.com/)
- "Mustard on the beat" is DJ Mustard's producer tag
- This is a fan/parody site for entertainment purposes
