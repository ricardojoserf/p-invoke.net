## Shell_NotifyIconGetRect

```csharp
[DllImport("shell32.dll")]
public static extern bool Shell_NotifyIconGetRect(
   ref NOTIFYICONIDENTIFIER identifier,
   out RECT iconLocation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shell_notifyicongetrect)
