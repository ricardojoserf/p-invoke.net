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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleidl/nf-oleidl-dodragdrop)
