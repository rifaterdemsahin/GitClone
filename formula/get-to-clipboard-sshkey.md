To add to the bitbucket get the public key 
```powershell
Get-Content C:\users\rifat.sahin\.ssh\id_rsa.pub | clip
```

```powershell
Get-Content C:\users\rifat.sahin\.ssh\id_rsa | clip
```

Alternatively, you can use the `Set-Clipboard` cmdlet, which is more straightforward and doesn't require piping:

```powershell
Get-Content C:\users\rifat.sahin\.ssh\id_rsa | Set-Clipboard
```

This should copy the contents of your SSH key file to the clipboard without any issues[1](https://adamtheautomator.com/powershell-copy-to-clipboard/)[2](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/set-clipboard?view=powershell-7.4).

If you have any other questions or need further assistance, feel free to ask!
