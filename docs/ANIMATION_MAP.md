# Animation Map

## Status

Planned for Sprint 2.

Sprint 1 can use simple CSS transitions if needed. Anime.js is not installed until Sprint 2.

## Motion Principle

Motion serves clarity.

Animation should help the user understand progress, attention, score, and diagnosis. It should not decorate the product for its own sake.

## Anime.js Targets

Install during Sprint 2:

```bash
npm i animejs
```

## Planned Motion Layer

Question transitions:

- move between questions smoothly
- preserve focus and readability

Progress meter:

- animate progress as questions are answered
- keep progress subtle and stable

Score reveal:

- count from 0 to final score
- land on the diagnosis band color

Leak map animation:

- reveal primary and secondary leaks after score
- show hierarchy without overwhelming the result

CTA pulse:

- make the next action visible
- keep it restrained and premium

## Accessibility

Respect `prefers-reduced-motion`.

Reduced-motion mode should:

- skip count-up effects
- avoid large movement
- preserve all content and interactions
