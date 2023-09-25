---
description: >-
  Learn how to use variants to create dynamic UI that adapts to the state of the
  app.
---

# Working with Variants

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption><p>Variants</p></figcaption></figure>

Variants in Codelessly represents different states and versions of a component or layout. They allow you to have more than 1 states of a component/layout and switch between them dynamically making the resulting UI more interactive and stateful.

Think of variants as alternate versions of your components. For example,

* A Button with enabled and disabled state.
* Light and dark mode for a component.
* Loading, data, error or empty view.

> Nodes with variants are highlighted with purple-pink-ish color when selected.

### Creating a variant

Creating a new variant for any layout or node is very easy.

1. Select the layout or node you want to create a variant for.
2. Click on the little arrow button <img src="../.gitbook/assets/image (21).png" alt="" data-size="line"> in the node name tooltip floating above it to reveal variants dropdown.
3. Click on create `New Variant` button at the bottom of the dropdown to initiate variant creation flow.&#x20;

<figure><img src="../.gitbook/assets/image (28).png" alt="" width="563"><figcaption></figcaption></figure>

4. This will open `Create New Variant` dialog. Fill in the name for your new variant.

<figure><img src="../.gitbook/assets/image (22).png" alt="" width="563"><figcaption><p>Create New Variant Dialog</p></figcaption></figure>

5. Check `Copy from current variant` option if you want to duplicate your current layout for your new variant as a starting point. Hit `Create` button when you finish configuring your options.

If this is the first variant you've created for your node/layout, you will see selection box changing its color to indicate a variant.

If you have not checked `Copy from current variant` option while creating a new variant, an empty variant will be created with a placeholder inside. This is how it will look once created.

<figure><img src="../.gitbook/assets/image (23).png" alt="" width="563"><figcaption><p>An empty variant</p></figcaption></figure>

You can drag & drop any node/layout inside to make it part of this variant. This allows you to build up your variant from scratch. This is helpful when your variant is a different UI than the other.

### Switching between variants

Once you have more than 1 variant for any node/layout, you can switch between those variants using the variants dropdown.

<figure><img src="../.gitbook/assets/image (24).png" alt="" width="563"><figcaption><p>Variants dropdown.</p></figcaption></figure>

All your variants will be shown in this dropdown and you can create a new one or switch betweene existing ones as you like.

To preview all the variants, click on `View All` button <img src="../.gitbook/assets/image (25).png" alt="" data-size="line"> in the variants dropdown to reveal variants dialog.

<figure><img src="../.gitbook/assets/image (27).png" alt="" width="563"><figcaption></figcaption></figure>

This will open Variants dialog where you can see all the variants with its preview for the selected node.

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption><p>Variants Dialog</p></figcaption></figure>

You can rename or delete a variant using more menu <img src="../.gitbook/assets/image (30).png" alt="" data-size="line">.

> Tip: Double click on the variant name to rename it.

Variants are identified with their name. You can switch between these variants on user interaction by setting a `Set Variant` from actions panel. Check out actions guide for more details.

<figure><img src="../.gitbook/assets/image (32).png" alt="" width="563"><figcaption><p>Set Variant Action</p></figcaption></figure>

You can define conditions to switch between variants too. Checkout Conditions guide for more.
