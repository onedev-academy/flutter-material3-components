```md
# TextFields – Material 3

## Design
![Filled Text Field](../images/filled_text_field.png)
![Outlined Text Field](../images/outlined_text_field.png)

---

## Filled Text Field
```dart
TextField(
  decoration: const InputDecoration(
    labelText: "Label",
    hintText: "Enter filled text field",
  ),
);

---

## Outline Text Field
```dart
TextField(
  decoration: const InputDecoration(
    labelText: "Enter outline text field",
    border: OutlineInputBorder(),
  ),
);
