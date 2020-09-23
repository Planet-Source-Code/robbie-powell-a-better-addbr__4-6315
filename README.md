<div align="center">

## A Better AddBR


</div>

### Description

A better, more efficient way of Replacing Carriage Returns ina user form or String that the addBR found elsewhere on this site.
 
### More Info
 
All it needs is a string which can come from a database or a form/textarea.

Nothing really, quite simple. The "& vbcrlf" is not required, this merely makes your returned html look like the users submission. you may omit this if you want the users results to appear on one line in the returned html source.

returns a string with <BR>'s in place of carriage returns.

Some users may hit enter too many times in their textboxes, can take up lots of space.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Robbie Powell](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/robbie-powell.md)
**Level**          |Beginner
**User Rating**    |3.0 (18 globes from 6 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Validation/ Processing](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/validation-processing__4-16.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/robbie-powell-a-better-addbr__4-6315/archive/master.zip)

### API Declarations

Can't copyright something this simple.


### Source Code

```
Function addbr(myString)
 addbr=Replace(myString, vbcrlf, "<BR>" & vbcrlf)
End Function
```

