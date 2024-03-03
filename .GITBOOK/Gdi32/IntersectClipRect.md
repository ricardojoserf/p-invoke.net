## IntersectClipRect

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int IntersectClipRect(
   IntPtr hdc,
   int left,
   int top,
   int right,
   int bottom
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-intersectcliprect)
