# FirstFlutterAPP

First Flutter App (Basically a Startup Name Generator) from [GoogleCodeLab](https://codelabs.developers.google.com/codelabs/first-flutter-app-pt1/index.html?index=..%2F..index#0)

## Getting Started

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.io/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.io/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.

### CodeLab Part1
##### What I'll Learn:
[x] How to write a Flutter app that looks natural on both iOS and Android.
[x] Basic structure of a Flutter app.
[x] Finding and using packages to extend functionality.
[x] Using hot reload for a quicker development cycle.
[x] How to implement a stateful widget.
[x] How to create an infinite, lazily loaded list.

##### Observations
- This example creates a Material app. Material is a visual design language that is standard on mobile and the web. Flutter offers a rich set of Material widgets.
- The main() method uses arrow (=>) notation. Use arrow notation for one-line functions or methods.
- The app extends StatelessWidget which makes the app itself a widget. In Flutter, almost everything is a widget, including alignment, padding, and layout.
- The Scaffold widget, from the Material library, provides a default app bar, title, and a body property that holds the widget tree for the home screen. The widget subtree can be quite complex.
- A widget’s main job is to provide a build() method that describes how to display the widget in terms of other, lower level widgets.
- For example, the body for this example consists of a Center widget containing a Text child widget. The Center widget aligns its widget subtree to the center of the screen.
- Stateless widgets are immutable, meaning that their properties can’t change — all values are final.
- Stateful widgets maintain state that might change during the lifetime of the widget. Implementing a stateful widget requires at least two classes: 
  1. a StatefulWidget class that creates an instance of 
  2. a State class.