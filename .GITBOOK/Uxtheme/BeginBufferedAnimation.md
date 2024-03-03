## BeginBufferedAnimation

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT BeginBufferedAnimation(
   HWND hwnd,
   HDC hdcTarget,
   ref RECT prcTarget,
   BP_BUFFERFORMAT dwFormat,
   ref BP_ANIMATIONPARAMS pAnimationParams,
   out IntPtr phdcFrom,
   out IntPtr phdcTo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-beginbufferedanimation)
