# Registry class

```csharp
public class Registry : Object
```

## Public Members

| name | description |
| --- | --- |
| [Item](Registry/Item.md) { set; } | Indexer to connect FeatureAddedSignal with a SignalHandler&lt;Registry, FeatureAddedSignalArgs&gt; (2 indexers) |
| event [OnFeatureAdded](Registry/OnFeatureAdded.md) |  |
| event [OnPluginAdded](Registry/OnPluginAdded.md) |  |
| static readonly [FeatureAddedSignal](Registry/FeatureAddedSignal.md) | Signal Descriptor for OnFeatureAdded. |
| static readonly [PluginAddedSignal](Registry/PluginAddedSignal.md) | Signal Descriptor for OnPluginAdded. |
| class [FeatureAddedSignalArgs](Registry.FeatureAddedSignalArgs.md) | Signal (Event) Arguments for OnFeatureAdded |
| class [PluginAddedSignalArgs](Registry.PluginAddedSignalArgs.md) | Signal (Event) Arguments for OnPluginAdded |

## See Also

* class [Object](Object.md)
* namespace [Gst](../Gst.md)

<!-- DO NOT EDIT: generated by xmldocmd for Gst.dll -->