# Formatting
A list of file formats you can save from Word.

All files are in the `/FORMATTING/` directory. You can open any of these files with **Microsoft Word**, and some files you can open with your browser.

# Viewing the Files
How do I open these files?

### With GitHub
Currently, you can only open two files.
[Plain Text], and [PDF].

### With your browser
__

### With Word
First, you have to check your version of word.

You can use `reg`, but my school blocked it, so maybe it's blocked for you
<br>
`reg query "HKEY_CLASSES_ROOT\Word.Application\CurVer"`

Otherwise, run these two commands, and ***IT MUST BE IN POWERSHELL***
```powershell
$ol = New-Object -ComObject Word.Application
$ol.Version
```

Now, just [download the source code](/DaCuteRaccoon/Formatting/archive/refs/heads/main.zip)

[PDF]: /FORMATTING/PDF.pdf
[Plain Text]: /FORMATTING/Plain%20Text.txt
