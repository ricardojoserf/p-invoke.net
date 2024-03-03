## DdeInitialize

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeInitializeA(ref uint pidInst,
   IntPtr pfncallback,
   uint afCmd,
   uint ulRes
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddeinitializea)
