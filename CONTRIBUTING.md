# Contribution Guideline
Thank you for contributing. Please read our contribution guidelines to ensure that your snippets are robust & users can easily integrate them into their themes.

## 1) Don't submit Ai-Generated Content
We want to maintain a list of reliable, human-made theme snippets. 

## 2) Test your Snippets
Please test your snippets thoroughly to ensure they work out of the box and don't cause issues (or specify possible conflicts).

## 3) Keep it Simple
Please don't modify more than necessary to simplify the integration process. Ideally, your snippets should focus on only modifying small parts of the ui at a time. Full themes can be found in the fluxer themes community. 

## 4) Provide a Preview
Please provide a gif or screenshot of your snippet's changes so users can know what is being modified.

# Contribution Tips:

### Use the right CSS Selectors
Don't use selectors like these:
- `.GuildsLayout.module__guildListScrollContainer___XzkwZG`: Could break between ui updates if the ending string `_XzkwZG` changes.
- `[class=*"GuildsLayout"]`: Too vague, could affect more elements than intended.

Make use of `[data-flx=""]` when applicable to target exactly what you want.

### Reuse Variables
Reuse fluxer's built in css variables if applicable. This will help ensure compatibility with fluxer's default theme and make it easier to integrate for others.

