## Werregisterfile

```csharp
[DllImport("wer.dll", SetLastError = true)]
public static extern HRESULT WerRegisterFile(string pwzFile,
   WER_REGISTER_FILE_TYPE regFileType,
   WER_REGISTER_FILE_ACTION regFileAction,
   out ulong pdwRequestId,
   ref WER_SUBMIT_RESULT psr
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/werapi/nf-werapi-werregisterfile)
