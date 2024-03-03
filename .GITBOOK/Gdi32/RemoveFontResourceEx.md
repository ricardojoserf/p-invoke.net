## RemoveFontResourceEx

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool RemoveFontResourceEx(
   string lpFileName,
   uint fl,
   IntPtr pdv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-removefontresourceexa)
