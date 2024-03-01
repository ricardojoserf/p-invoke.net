## DoDragDrop

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int DoDragDrop(
   IDataObject pDataObj,
   IDropSource pDropSource,
   uint dwOKEffects,
   out uint pdwEffect
);
```

[Microsoft documentation](TODO)
