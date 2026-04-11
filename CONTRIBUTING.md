# Contributing Snippets
Thank you for contributing. Please read our contribution guidelines to ensure that your snippets are robust & users can easily integrate them into their themes.

## 1) Use the right CSS Selectors
Don't use selectors like these:
- `.GuildsLayout.module__guildListScrollContainer___XzkwZG`: Could break between ui updates if the ending string `_XzkwZG` changes.
- `[class=*"GuildsLayout"]`: Too vague, could affect more elements than intended.

Use selectors like `[class=*"UserArea.module__userAreaContainer_"]` to target exactly what you want.

## 2) Reuse Variables
Reuse fluxer's built in css variables if applicable. This will help ensure compatibility with fluxer's default theme and make it easier to integrate for others.

## 3) Test your Snippets
Please test your snippets thoroughly to ensure they work out of the box and don't cause issues (or specify possible conflicts).

## 4) Keep it Simple
Please don't modify more than necessary to simplify the integration process. Ideally, your snippets should focus on only modifying small parts of the ui at a time. Full themes can be found in the fluxer themes community. 

## 5) Provide a Preview
Please provide a gif or screenshot of your snippet's changes so users can know what is being modified.

## 6) Don't submit Ai-Generated Content
We want to maintain a list of reliable, human-made code snippets. 
