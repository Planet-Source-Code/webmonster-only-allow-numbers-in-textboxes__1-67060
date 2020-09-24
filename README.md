<div align="center">

## Only allow numbers in textboxes


</div>

### Description

Stops letters from being typed in a textbox
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Webmonster](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/webmonster.md)
**Level**          |Beginner
**User Rating**    |4.0 (12 globes from 3 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/webmonster-only-allow-numbers-in-textboxes__1-67060/archive/master.zip)





### Source Code

```
This will stop letters being put in a textbox named text1
private sub text1_keypress(keyascii as integer)
select case keyascil
case is < 42
case 48 To 57
case else
keyascil = 0
end select
end sub
```

