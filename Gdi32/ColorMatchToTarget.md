## ColorMatchToTarget

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ColorMatchToTarget(
   IntPtr hdc,
   IntPtr hdcTarget,
   uint action
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-colormatchtotarget)
