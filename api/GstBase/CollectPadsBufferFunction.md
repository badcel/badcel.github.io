# CollectPadsBufferFunction delegate

```csharp
public delegate FlowReturn CollectPadsBufferFunction(IntPtr pads, IntPtr data, IntPtr buffer, 
    IntPtr user_data);
```

| parameter | description |
| --- | --- |
| pads | Transfer ownership: none |
| data | Transfer ownership: none |
| buffer | Transfer ownership: full |
| user_data | Transfer ownership: none; Nullable: true |

## Return Value

Transfer ownership: none

## See Also

* namespace [GstBase](../Gst.Base.md)

<!-- DO NOT EDIT: generated by xmldocmd for Gst.Base.dll -->
