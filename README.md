# [Notes on Jen Simmons' Layout Land](https://www.youtube.com/channel/UC7TizprGknbDalbHplROtag)

This is a practice repo for learning how best to use CSS Grid in combination with Flexbox and Floats (yes, Floats!) to make interesting custom layouts without importing a framework

## Intro
[Flexbox vs. CSS Grid](https://www.youtube.com/channel/UC7TizprGknbDalbHplROtag)  
Takeaway: CSS Grid does not **replace** Flexbox (like Flexbox did not **replace** floats). There is overlap in what they can do, but there are specific things each is particularly good at, so you should never feel like you have to use one or the other 100% of the time. Pick the tool that suits the need.

**IMPORTANT** Both CSS Grid and Flexbox have the ability to shuffle an item's visual order regardless of source order. This has consequences for keyboard and screenreader users. It is a potential failure of WCAG Level A [1.3.2 Meaningful Sequence](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence).

Adrian Roselli has made a [feature request for developer tools to include a DOM reading order viewer](https://www.youtube.com/watch?v=UjXCAuWuXdk). Tabbing through a site will indicate the focus order of interactive elements but you will need a tool like [Roselli's bookmarklet](https://adrianroselli.com/2019/04/reading-order-bookmarklet.html) or the [Accessibility Insights](https://accessibilityinsights.io/en/) Tab Stops Checker to check non-interactive elements for now.