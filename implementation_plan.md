# Implementation Plan - Love Card

The goal is to create a web page with a "Do you love me?" card.
- "No" button runs away from the cursor.
- "Yes" button shows a video.

## Proposed Changes

### UI
- **File**: `index.html`
- **Structure**:
    - A main container for the card.
    - `h1` for the question "Do you love me?".
    - Two buttons: "Yes" and "No".
    - A hidden container for the video (or dynamic insertion).

### Styling
- **File**: `style.css`
- **Style**:
    - Centered card layout.
    - Nice typography (Google Fonts).
    - Pink/Red romantic theme.
    - Absolute positioning for the "No" button to allow movement.

### Logic
- **File**: `script.js`
- **Events**:
    - `mouseover` on "No" button: Calculate new random `top` and `left` within window bounds.
    - `click` on "Yes" button: Hide the question card/change content to show a YouTube embed or video element.

## Verification
- User will manually test the interactions.
