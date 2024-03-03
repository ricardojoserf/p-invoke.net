## RegisterDragDrop

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int RegisterDragDrop(
   IntPtr hwnd,
   IDropTarget pDropTarget
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-registerdragdrop)
