<div align="center">

## Make Uppercase or lowercase in Textbox


</div>

### Description

how to Make Uppercase or lowercase in Textbox
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[&amp;\#6047;&amp;\#6075;&amp;\#6017;&amp;\#6070;](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/amp-6047-amp-6075-amp-6017-amp-6070.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/amp-6047-amp-6075-amp-6017-amp-6070-make-uppercase-or-lowercase-in-textbox__1-48480/archive/master.zip)





### Source Code

```
'This to change it to Uppercase while typing
Private Sub Text1_KeyPress(KeyAscii As Integer)
  KeyAscii = Asc(UCase(Chr(KeyAscii)))
End Sub
'This to change it to Lower case while typing
Private Sub Text1_KeyPress(KeyAscii As Integer)
  KeyAscii = Asc(LCase(Chr(KeyAscii)))
End Sub
```

