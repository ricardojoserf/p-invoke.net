## ColorRGBToHLS

```csharp
[DllImport("shlwapi.dll")]
public static extern uint ColorRGBToHLS(
   uint rgb,
   out ushort pwHue,
   out ushort pwLuminance,
   out ushort pwSaturation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-colorrgbtohls)
