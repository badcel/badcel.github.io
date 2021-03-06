# Object class

```csharp
public class Object : IDisposable, IHandle, INotifyPropertyChanged, IObject
```

## Public Members

| name | description |
| --- | --- |
| [Handle](Object/Handle.md) { get; } |  |
| [Item](Object/Item.md) { set; } | Indexer to connect NotifySignal with a SignalHandler&lt;Object, NotifySignalArgs&gt; |
| event [OnNotify](Object/OnNotify.md) |  |
| event [PropertyChanged](Object/PropertyChanged.md) | Event triggered when a property value changes. |
| [Dispose](Object/Dispose.md)() |  |
| static readonly [NotifySignal](Object/NotifySignal.md) | Signal Descriptor for OnNotify. |
| static [TryWrapHandle&lt;T&gt;](Object/TryWrapHandle.md)(…) | A variant of [`WrapHandle`](Object/WrapHandle.md) which fails gracefully if the pointer cannot be wrapped. |
| static [WrapHandle&lt;T&gt;](Object/WrapHandle.md)(…) | This function returns the proxy object to the provided handle if it already exists, otherwise creates a new wrapper object and returns it. Note that *T* is the type the object should be returned. It is independent of the object's actual type and is provided purely for convenience. |
| static [WrapNullableHandle&lt;T&gt;](Object/WrapNullableHandle.md)(…) |  |
| class [NotifySignalArgs](Object.NotifySignalArgs.md) | Signal (Event) Arguments for OnNotify |
| class [TypeDescriptor](Object.TypeDescriptor.md) | Describes a wrapper type. |

## See Also

* interface [IObject](IObject.md)
* namespace [GObject](../GObject.md)

<!-- DO NOT EDIT: generated by xmldocmd for GObject.dll -->
