## CreateRectRgnIndirect

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateRectRgnIndirect(
   [In] ref RECT lprc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createrectrgnindirect)
