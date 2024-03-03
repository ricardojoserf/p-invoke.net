## SelectObject

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr SelectObject(
   IntPtr hdc,
   IntPtr hgdiobj
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-selectobject)
