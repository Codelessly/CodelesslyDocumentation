---
description: Learn how to connect data to the layouts and make them dynamic.
---

# Connecting Data

## JSON Paths

The first step to connect data to a node is to declare the data's path in the node itself. We do it by placing the JSON path in between `${ }`. It looks something like this:

```dart
${books.chapters.titles[0]}
```

In case of the example weather app, we declare the JSON path that points to a temperature.

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption><p>Dynamic Temperature</p></figcaption></figure>

Next up, providing the data to the layout in the SDK.

## Data Field

`CodelesslyWidget` takes in data using the `data` parameter which is of type `Map<String, dynamic>`. You can provide the data in the form of a JSON and the widget will be able to use its values internally.

```dart
CodelesslyWidget(
  data: const {
    'weather': {
      'temp': 20,
      'humidity': 34,
      'wind': 6,
    },
  }
);
```

Run the app. It should retrieve `temp`'s value from the data and substitute it in place of the JSON path.

<figure><img src="../.gitbook/assets/image (29) (1).png" alt=""><figcaption><p>Dynamic data used in widget</p></figcaption></figure>

Currently, the editor supports adding dynamic data to text and image URLs.
