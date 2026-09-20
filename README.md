# CSSLoader-hide-demo-bar

Hides Steam's green **DEMO** badge from library grid tiles and game detail/hero views, including Big Picture mode.

The selectors intentionally cover both stable Steam UI names and the meaningful fragments retained by hashed class names. Steam client updates can still rename or restructure these elements; if the badge returns, inspect the element with the CEF debugger and add the new selector to the three CSS files.
