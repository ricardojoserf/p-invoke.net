## GetCurrentObject

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr GetCurrentObject(
   IntPtr hdc,
   uint uObjectType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcurrentobject)
