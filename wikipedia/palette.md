# Wikipedia palette
<details>
    <summary>Organized (by me) (badly)</summary>
    
```css
:root,
.skin-invert,
.notheme {

    /* COLOR VARS */
    --pure-white: #fff;
    --pure-black: #000;

    --off-white-cool: #eaecf0;
    --off-white-warm: ##fee7e6;

    --grey: #72777d;
    --grey-light-cool: #c8ccd1;
    --grey-cool: #a2a9b1;
    --grey-dark: #54595d;
    --grey-black: #202122;

    --red-dusty: #b32424;
    --red-orange: #d73333;

    --orange: #ff4242;

    --yellow-pale: #ffe49c;

    --blue: #36c;
    --blue-pale: #a3d3ff;
    --blue-light: #447ff5;
    --blue-dark: #2a4b8d;

    /* NO FRIENDS */
    --color-base--hover: #404244;
    --color-destructive--visited: #a55858;
    --color-content-removed: #8b0000;
    --color-content-added: #006400;
    --color-warning: #edab00;
    --color-success: #14866d;
    --color-visited: #6b4ba1;
    --border-color-warning: #a66200;
    --border-color-success: #096450;
    --background-color-progressive-subtle: #eaf3ff;
    --background-color-inverted: #101418;
    --background-color-success-subtle: #d5fdf4;

    /* GROUPED COLORS */
    /* Pure white */
    --border-color-inverted: var(--pure-white);
    --box-shadow-color-inverted: var(--pure-white);
    --color-inverted: var(--pure-white);
    --color-inverted-fixed: var(--pure-white);
    --background-color-base: var(--pure-white);
    --background-color-base-fixed: var(--pure-white);

    /* Pure black */
    --color-emphasized: var(--pure-black);
    --box-shadow-color-base: var(--pure-black);

    --color-base: var(--grey-black);
    --color-base-fixed: var(--grey-black);
    --color-notice: var(--grey-black);

    --color-subtle: var(--grey-dark);
    --border-color-notice: var(--grey-dark);

    --color-placeholder: var(--grey);
    --color-disabled: var(--grey);
    --color-base--subtle: var(--grey);
    --border-color-interactive: var(--grey);

    --background-color-disabled-subtle: var(--off-white-cool);
    --background-color-notice-subtle: var(--off-white-cool);
    --background-color-neutral: var(--off-white-cool);
    --background-color-interactive: var(--off-white-cool);
    --border-color-muted: var(--off-white-cool);

    --background-color-destructive-subtle: var(--off-white-warm);
    --background-color-error-subtle: var(--off-white-warm);
    --background-color-warning-subtle: var(--off-white-warm);

    --background-color-content-removed: var(--yellow-pale);
    --border-color-content-removed: var(--yellow-pale);

    --background-color-content-added: var(--blue-pale);
    --border-color-content-added: var(--blue-pale);

    --background-color-disabled: var(--grey-light-cool);
    --border-color-disabled: var(--grey-light-cool);
    --border-color-subtle: var(--grey-light-cool);

    --background-color-interactive-subtle: var(--off-white-cool);
    --background-color-neutral-subtle: var(--off-white-cool);

    --border-color-divider: var(--grey-cool);
    --border-color-base: var(--grey-cool);

    --background-color-destructive--focus: var(--blue);
    --box-shadow-color-progressive--focus: var(--blue);
    --background-color-input-binary--checked: var(--blue);
    --box-shadow-color-progressive-selected: var(--blue);
    --box-shadow-color-destructive--focus: var(--blue);
    --color-progressive: var(--blue);
    --color-progressive--focus: var(--blue);
    --outline-color-progressive--focus: var(--blue);
    --border-color-progressive: var(--blue);
    --background-color-progressive: var(--blue);
    --background-color-progressive--focus: var(--blue);
    --border-color-progressive--focus: var(--blue);
    --color-destructive--focus: var(--blue);
    --border-color-destructive--focus: var(--blue);

    --border-color-progressive--hover: var(--blue-light);
    --box-shadow-color-progressive-selected--hover: var(--blue-light);
    --color-progressive--hover: var(--blue-light);
    --background-color-progressive--hover: var(--blue-light);

    --border-color-progressive--active: var(--blue-dark);
    --box-shadow-color-progressive-selected--active: var(--blue-dark);
    --color-progressive--active: var(--blue-dark);
    --box-shadow-color-progressive--active: var(--blue-dark);
    --background-color-progressive--active: var(--blue-dark);

    --background-color-destructive: var(--red-orange);
    --color-destructive: var(--red-orange);
    --border-color-destructive: var(--red-orange);
    --background-color-error: var(--red-orange);
    --color-error: var(--red-orange);

    --background-color-destructive--hover: var(--orange);
    --background-color-error--hover: var(--orange);
    --color-destructive--hover: var(--orange);
    --border-color-error--hover: var(--orange);
    --border-color-destructive--hover: var(--orange);

    --color-destructive--active: var(--red-dusty);
    --background-color-destructive--active: var(--red-dusty);
    --background-color-error--active: var(--red-dusty);
    --border-color-error: var(--red-dusty);
    --border-color-destructive--active: var(--red-dusty);


    /* TRANSPARENT / TRANSLUCENT ZONE */
    --background-color-transparent: transparent;
    --border-color-transparent: transparent;
    --box-shadow-color-transparent: transparent;

    --background-color-button-quiet--hover: rgba(0, 24, 73, 0.027);
    --background-color-button-quiet--active: rgba(0, 24, 73, 0.082);
    --background-color-tab-list-item-framed--hover: rgba(255, 255, 255, 0.3);
    --background-color-tab-list-item-framed--active: rgba(255, 255, 255, 0.65);
    --background-color-backdrop-light: rgba(255, 255, 255, 0.65);
    --background-color-backdrop-dark: rgba(0, 0, 0, 0.65);

    /* NUMERICAL ZONE */
    --filter-invert-icon: 0;
    --filter-invert-primary-button-icon: 1;

    --opacity-icon-base: 0.87;
    --opacity-icon-base--hover: 0.74;
    --opacity-icon-base--selected: 1;
    --opacity-icon-base--disabled: 0.51;
    --opacity-icon-placeholder: 0.51;
    --opacity-icon-subtle: 0.67;

    /* BASE DERIVATION ZONE */
    
    /* DERIVATIVE OF PROGRESSIVE */
    --border-color-input-binary--hover: var(--border-color-progressive--hover);
    --border-color-input-binary--active: var(--border-color-progressive--active);
    --border-color-input-binary--focus: var(--border-color-progressive--focus);
    --border-color-input-binary--checked: var(--border-color-progressive);

    /* DERIVATIVE OF DESTRUCTIVE */
    --color-link-red: var(--color-destructive);
    --color-link-red--hover: var(--color-destructive--hover);
    --color-link-red--active: var(--color-destructive--active);
    --color-link-red--focus: var(--color-destructive--focus);
    --color-link-red--visited: var(--color-destructive--visited);

    /* DERIVATIVE OF INTERACTIVE */
    --border-color-input--hover: var(--border-color-interactive);
    --border-color-input-binary: var(--border-color-interactive);
}
```
</details>

## Visuals
To show what is influenced by each color, I change that color to #4AF626 (neon green) temporarily.
_All on light mode, since even though I am making a dark theme it's just easier to edit._

<details><summary>--pure-white</summary>
    
![white](https://i.imgur.com/8KSFAfR.png)
</details>

<details><summary>--pure-black</summary>
    
![black](https://i.imgur.com/oXRzkaS.png)
</details>

<details><summary>--off-white-cool</summary>
    
![cool off white](https://i.imgur.com/qbt00tX.png)
</details>
