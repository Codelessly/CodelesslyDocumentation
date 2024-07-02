---
description: Learn how to embed your own widget into Codelessly's layout.
---

# Using External Components

Codelessly offers a wide range of components that can be the building blocks for most of your layouts. However, there can be times when you want to use a very specific widget that is not yet available in Codelessly or you want to use a widget from a third-party package into your codelessly layout.

To fulfill this use-case, we have a component called `External Component` in the components library.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (15) (1).png" alt=""><figcaption><p>External Component</p></figcaption></figure>

</div>

As the name implies, this component behaves like an iFrame and allows you to hook your own widget into it programmatically. You can pass this widget from `CodelesslyWidget` using our Cloud UI SDK.

Any custom widget can be rendered inside this external component as long as it can respect its constraints.

### Usage

1. Like other components, you can drag and drop this component in any of your layouts.
2. Open the settings panel for this component by clicking on the floating Settings button <img src="../.gitbook/assets/image (16) (1).png" alt="" data-size="line"> next to it.
3. Provide a unique identifier for this component. This `id` will used to identify the component from `CodelesslyWidget` in the SDK to map it to a widget builder.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (19) (1).png" alt="" width="563"><figcaption><p>External Component configuration</p></figcaption></figure>

</div>

4. From the SDK side, where you are using `CodelesslyWidget`, pass your widget using the `externalComponentBuilders` constructor parameter.

```dart
return CodelesslyWidget(
  config: CodelesslyConfig(authToken: '<auth_token>'),
  layoutID: '<layout_id>',
  externalComponentBuilders: {
    'my_custom_widget': (context) {
      return const Placeholder();
    },
  },
)
```

> Note that the `key` needs to match exactly to the unique external ID provided in the Editor.

You can have as many external components as you want. You can pass any widget including `StatefulWidget` and manage its state yourself. You can provide all of them in `CodelesslyWidget` by using their unique ids.

```dart
return CodelesslyWidget(
  config: CodelesslyConfig(authToken: '<auth_token>'),
  layoutID: '<layout_id>',
  externalComponentBuilders: {
    'widget1': (context) {
      return const Placeholder();
    },
    'widget2': (context) {
      return const Placeholder();
    },
  },
)
```
