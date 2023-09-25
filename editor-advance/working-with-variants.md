---
description: >-
  Learn how to use variants to create dynamic UI that adapts to the state of the
  app.
---

# Working with Variants

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption><p>Variants</p></figcaption></figure>

</div>

Variants in Codelessly are different states and variations of a component or layout. Variants allow you to switch between them dynamically, making the resulting UI more interactive and stateful.

Think of variants as alternate versions of your components. For example,

* A Button with an enabled and a disabled state.
* Light and dark modes for a component.
* Loading, data, error, or empty sections of your UI.

> Nodes with variants are highlighted with a pink color when selected.

### Creating a variant

1. Select the node you want to create a variant for.
2. Click on the little arrow button <img src="../.gitbook/assets/image (21).png" alt="" data-size="line"> in the selected node's name tooltip floating above it to reveal variants dropdown.
3. Click on the `New Variant` button at the bottom of the dropdown to go into the variant creation flow.&#x20;

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (28).png" alt="" width="563"><figcaption><p>Creating a new variant from the node's tooltip.</p></figcaption></figure>

</div>

4. This will open the `Create New Variant`dialog. Fill in the name for your new variant.

<figure><img src="../.gitbook/assets/image (22).png" alt="" width="563"><figcaption><p>Create New Variant Dialog</p></figcaption></figure>

5. Check the `Copy from current variant` option if you want to duplicate your current layout for your new variant as a starting point. You may want to do this if you want to keep any parts of your original layout structure and just modify some elements instead of recreating it from scratch. Alternatively if the entire layout is going to be different in its new state, you may want to keep this checked off, allowing you to start with a blank placeholder instead of your last layout as its variant.
6. Click on the `Create` button when you finish configuring your options and you will immediately see the new variant you've created.

If this is the first variant you've created for your selected node and all the children inside of it, The selection box will have changed its color to indicate that it's a variant.

If you have not checked the `Copy from current variant` option while creating the new variant, an empty variant will be created with a placeholder inside.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (23).png" alt="" width="563"><figcaption><p>An empty variant</p></figcaption></figure>

</div>

You can drag & drop any node/layout inside to make it part of this variant. This allows you to build up your variant from scratch.

If you did check the `Copy from current variant` button, you will see the exact same node layout structure you had before but with the pink highlight. In fact, your original node structure got duplicated and you now have two variants that look identical. One is the original, and the currently visible one is the duplicate that you can freely modify without affecting the original.

### Switching between variants

Once you've created your variant, you can switch between it and your original creation using the variants dropdown chevron in the node's name tooltip.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (24).png" alt="" width="563"><figcaption><p>Variants dropdown.</p></figcaption></figure>

</div>

All your variants will be shown in this dropdown and you can create a new one or switch between existing ones as you like.

To preview all the variants, click on `View All` button <img src="../.gitbook/assets/image (25).png" alt="" data-size="line"> in the variants dropdown to reveal variants dialog.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (27).png" alt="" width="563"><figcaption></figcaption></figure>

</div>

This will open Variants dialog where you can see all the variants with each one's associated preview.

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption><p>Variants Dialog</p></figcaption></figure>

You can rename or delete a variant by clicking on the triple-dots <img src="../.gitbook/assets/image (30).png" alt="" data-size="line">.

> Tip: Double click on the variant name to rename it.

Variants are identifiable via their names. You can switch between these variants on user interaction by setting a `Set Variant` action from actions panel. Check out the upcoming actions guide for more details.

<figure><img src="../.gitbook/assets/image (32).png" alt="" width="563"><figcaption><p>Set Variant Action</p></figcaption></figure>

You can define conditions to switch between variants too. Checkout the upcoming Conditions guide for more information.
