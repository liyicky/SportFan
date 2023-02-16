# SportFan
Learned from Swift UI Animations by Tutorials [book](https://www.kodeco.com/books/swiftui-animations-by-tutorials/v1.0)


### Key Points

- GeometryReader is a SwiftUI view, which takes up all the space provided by its parent and allows accessing its size, frame and safe area insets through a GeometryProxy.
- Avoid performing state changes directly inside a view’s body, as it may cause an undesired render loop.
- Use interpolation functions to make animations feel more natural and physically realistic.
- Try not to catch a user off guard with your animations. The behavior should be expected and well placed in the app.
- Use withAnimation() to animate multiple views or properties of a view from one place explicitly.
- Use .animation(:value:) to trigger a single view animation by modifications happening in the shared state of multiple components implicitly.
- A Bézier curve is defined by a set of control points and can be helpful in various aspects of computer graphics.
- Transitions define the way a view appears and disappears from the screen.
- You can combine your transitions with .combined(with:).
- Use .matchedGeometryEffect to align one view’s frame to the other view’s frame into a seamless animation.
- A view will have different insertion and removal animations if you specify both via .asymmetric(with:).
- To implement a custom transition, you need to create a ViewModifier with the different transformations applied for the active and identity states.

![output](https://user-images.githubusercontent.com/3443810/218250468-9efe6143-e531-4cc8-b3c4-999d8ffd8b76.gif)
![output](https://user-images.githubusercontent.com/3443810/219385574-d922d4ff-fbd6-4984-a73a-0d68da2d22e7.gif)
