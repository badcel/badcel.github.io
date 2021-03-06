# Range class

```csharp
public class Range : Widget, Orientable
```

## Public Members

| name | description |
| --- | --- |
| [Item](Range/Item.md) { set; } | Indexer to connect with a SignalHandler&lt;Range&gt; (4 indexers) |
| [Orientation](Range/Orientation.md) { get; set; } |  |
| event [OnAdjustBounds](Range/OnAdjustBounds.md) |  |
| event [OnChangeValue](Range/OnChangeValue.md) |  |
| event [OnMoveSlider](Range/OnMoveSlider.md) |  |
| event [OnValueChanged](Range/OnValueChanged.md) |  |
| static readonly [AdjustBoundsSignal](Range/AdjustBoundsSignal.md) | Signal Descriptor for OnAdjustBounds. |
| static readonly [ChangeValueSignal](Range/ChangeValueSignal.md) | Signal Descriptor for OnChangeValue. |
| static readonly [MoveSliderSignal](Range/MoveSliderSignal.md) | Signal Descriptor for OnMoveSlider. |
| static readonly [ValueChangedSignal](Range/ValueChangedSignal.md) | Signal Descriptor for OnValueChanged. |
| class [AdjustBoundsSignalArgs](Range.AdjustBoundsSignalArgs.md) | Signal (Event) Arguments for OnAdjustBounds |
| class [ChangeValueSignalArgs](Range.ChangeValueSignalArgs.md) | Signal (Event) Arguments for OnChangeValue |
| class [MoveSliderSignalArgs](Range.MoveSliderSignalArgs.md) | Signal (Event) Arguments for OnMoveSlider |

## See Also

* class [Widget](Widget.md)
* interface [Orientable](Orientable.md)
* namespace [Gtk](../Gtk3.md)

<!-- DO NOT EDIT: generated by xmldocmd for Gtk3.dll -->
