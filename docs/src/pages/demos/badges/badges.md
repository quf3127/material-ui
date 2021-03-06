---
title: Badge React component
components: Badge
---

# Badges

<p class="description">Badge generates a small badge to the top-right of its child(ren).</p>

## Simple Badges

Examples of badges containing text, using primary and secondary colors. The badge is applied to its children.

{{"demo": "pages/demos/badges/SimpleBadge.js"}}

## Maximum Value

You can use the `max` property to cap the value of the badge content.

{{"demo": "pages/demos/badges/BadgeMax.js"}}

## Dot Badge

The `dot` property changes a badge into a small dot. This can be used as a notification that something has changed without giving a count.

{{"demo": "pages/demos/badges/DotBadge.js"}}

## Badge visibility

The visibility of badges can be controlled using the `invisible` property.

The badge auto hides with badgeContent is zero. You can override this with the `showZero` property.

{{"demo": "pages/demos/badges/BadgeVisibility.js"}}

## Customized badges

If you have read the [overrides documentation page](/customization/overrides/)
and you are still not confident jumping in, here are some examples of how you can customize the component.

{{"demo": "pages/demos/badges/CustomizedBadges.js"}}
