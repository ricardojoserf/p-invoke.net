## DragQueryFile

```csharp
[DllImport("shell32.dll")]
public static extern uint DragQueryFile(
   IntPtr hDrop,
   uint iFile,
   StringBuilder lpszFile,
   uint cch
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-dragqueryfilew)
