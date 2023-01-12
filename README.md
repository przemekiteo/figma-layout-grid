# Figma layout grid
```figma_layout_grid``` is a Flutter package which imitates Figma's layout grid and all its functionalities. It helps you determine whether your UI components match the design file and align properly.

## 

```dart
LayoutGrid(
    showColumns: GridConfig.showColumnsNotifier,
    showRows: GridConfig.showRowsNotifier,
    showGrid: GridConfig.showGridNotifier,
    child: const MyHomePage(),
)
```

```dart
class GridConfig {
  static final showColumnsNotifier = ValueNotifier(false);
  static final showRowsNotifier = ValueNotifier(false);
  static final showGridNotifier = ValueNotifier(false);
}

```