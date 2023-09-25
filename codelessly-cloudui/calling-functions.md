---
description: Learn how to call custom functions in the SDK.
---

# Calling Functions

## _"Call Function"_ Action

Actions are meant to make the UI more functional. Using actions, you can navigate to a different page, change state of a widget, launch URLs, etc. In this case, we need to call a custom function in the SDK. So, we use the _Call Function_ action.

Head over to _Develop Tab_ located in the app bar.

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption><p>Develop Tab</p></figcaption></figure>

You should see the _Actions Panel_ in the right. Now, select the node you wish to add the action to.

<figure><img src="../.gitbook/assets/image (23) (1).png" alt=""><figcaption><p>Node selected</p></figcaption></figure>

To add an action, tap on the _add icon_ and select _"Call Function Action"_ from the dropdown.

<figure><img src="../.gitbook/assets/image (20) (1).png" alt=""><figcaption><p>Adding Call Function Action</p></figcaption></figure>

Next, tap on the _settings icon_ to open the settings window.

<figure><img src="../.gitbook/assets/image (37) (1).png" alt=""><figcaption><p>Action Settings Window</p></figcaption></figure>

Enter the custom function's name in the _Function Name Field_.

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption><p>Function Name Field</p></figcaption></figure>

Action to call a custom function is now added to the node. Now, we need to provide the function in the SDK.

## Functions Field

We can provide custom functions to the `CodelesslyWidget` using its `functions` parameter which is of type `Map<String, CodelesslyFunction<T>>`. Map's key is the name of the function and value is `CodelesslyFunction` class that takes in the function itself in its constructor.

`CodelesslyFunction` has a parameter `call` which is a function with generic return type `T`. Here's an example of how we can declare functions in the widget.

```dart
CodelesslyWidget(
  functions: {
    'expandForecastPage': CodelesslyFunction((context, ref, params) {...}),
  }
);
```

`ref` is an instance of `CodelesslyContext` that you may use to access data and other functions from the SDK.

`params` is a Map that contains any parameters passed by the function when it is called. These parameters can be defined on the function call from the Editor.

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Now, node can access the function and call it on relevant trigger (_click_ in this case).
