## SetClassWord

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern ushort SetClassWord(
   IntPtr hWnd,
   int nIndex,
   ushort wNewWord
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setclassword)
