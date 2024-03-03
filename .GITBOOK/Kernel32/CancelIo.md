## CancelIo

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CancelIo(
   IntPtr hFile
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/fileio/cancelio#:~:text=CancelIo%20cancels%20only%20outstanding%20I,issued%20as%20overlapped%20I%2FO.)
