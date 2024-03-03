## CreateProfile

```csharp
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool CreateProfile(
   [MarshalAs(UnmanagedType.LPWStr)] string pszUserSid,
   [MarshalAs(UnmanagedType.LPWStr)] string pszUserName,
   [Out] StringBuilder pszProfilePath,
   uint cchProfilePath
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-createprofile)
