# StackViewBuilder

This package expands on the `AutoLayoutBuilder` package by making StackViews easier to work with.

```swift
addSubview(ScrollableStackView()) {
  $0.edges == Superview()
  $0.stackedViews {
    redView
    greenView
  }
  $0.spacing(10, after: redView)
}
```
