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

By default it will be vertical but you can pass in the `axis` to flip it to horizontal, it will take care of the constraints for you.

There is also a `StackView` component that works the same way but doesn't allow for scrolling.
