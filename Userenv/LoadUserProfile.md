## LoadUserProfile

```csharp
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool LoadUserProfile(
   IntPtr hToken,
   ref PROFILEINFO lpProfileInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-loaduserprofilew)
