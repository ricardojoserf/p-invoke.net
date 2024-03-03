## DoDragDrop

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int DoDragDrop(
   IDataObject pDataObj,
   IDropSource pDropSource,
   uint dwOKEffects,
   out uint pdwEffect
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/dotnet/api/system.windows.forms.control.dodragdrop?view=windowsdesktop-8.0)
