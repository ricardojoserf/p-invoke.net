## GetStringType

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetStringType(
   uint Locale,
   uint dwInfoType,
   string lpSrcStr,
   int cchSrc,
   out ushort lpCharType
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/ms960833(v=msdn.10))
