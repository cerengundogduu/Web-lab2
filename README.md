# HTML and CSS Assignment

## File Organization
- `index.html`: The main page containing the 6 boxes (A to F).
- `styleA.css`: Styles for Version A (vertical layout with dynamic spacing).
- `styleB.css`: Styles for Version B (horizontal layout with a fixed box in the corner).

## Challenges Faced
- **Vertical Spacing in Style A:** It was a bit tricky to make the boxes spread out evenly across the screen while stopping them from squishing or resizing when I changed the browser window size. I solved this by using `justify-content: space-between` and `flex-shrink: 0`.
- **Centering the Text:** Boxes A through E only needed the text centered horizontally, but box F had to be centered both horizontally and vertically. I used flexbox properties on `:last-child` to center F correctly.
- **Positioning in Style B:** Keeping the first five boxes on a single line without wrapping when the screen got smaller was a challenge, which I fixed using `white-space: nowrap`. I also had to make sure the F box stayed stuck to the bottom right using `position: fixed`.
## Testing
Verified Version A and Version B responsiveness on Chrome.
