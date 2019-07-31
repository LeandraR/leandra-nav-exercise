Hi!
[View live here](https://leandrar.github.io/leandra-nav-exercise/)

Some of my thoughts:

I chose to use vanilla JavaScript rather than jQuery as that is easier to convert to Angular (as you mentioned is the team's workflow).

I added the timeout function to the list sub menu on hover, as WCAG indicated that was better for accessibility for those with mobility issues.

I followed the WCAG specifications for fly-out menus [here](https://www.w3.org/WAI/tutorials/menus/flyout/), including the aria attributes.  I need to test this further to ensure keyboard navigation is appropriate & would test it with a screen reader to make sure it is semantically logical and easy to follow.  I would also perform cross-browser testing - I did add the Normalize code to the CSS to help ensure it wouldn't be too different, but it would be a more robust product with cross browser testing.

There are clearly some margin/padding areas that needs to be tinkered with still, especially with the on click Profile sub menu.  The flex box needs a bit of work for the overall menu, as there is a 'Link' item partially hidden by the Profile area.

I also need to format the mobile menu when it is revealed.  I would add different margins & padding to better render it to the PSD.

I think it would take me another 30-60 minutes to finish it to my liking (slightly perfectionist tendencies ;) ).


