## OleSetContainedObject

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleSetContainedObject(
   IOleClientSite pClientSite,
   [MarshalAs(UnmanagedType.Bool)] bool fContained
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olesetcontainedobject)
