# StyleContext.AddProvider method

StyleContext.AddProvider adds a CssProvider to a single style context. Note that it is only able to style the widget which owns this style context, and NOT any child widgets in the tree.

```csharp
public void AddProvider(CssProvider provider, uint priority)
```

## See Also

* class [CssProvider](../CssProvider.md)
* class [StyleContext](../StyleContext.md)
* namespace [Gtk](../../Gtk3.md)

<!-- DO NOT EDIT: generated by xmldocmd for Gtk3.dll -->