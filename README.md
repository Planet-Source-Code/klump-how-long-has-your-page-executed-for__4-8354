<div align="center">

## How long has your page executed for??


</div>

### Description

See how long your page has run...very simple...a few lines only..
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Klump](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/klump.md)
**Level**          |Intermediate
**User Rating**    |4.4 (40 globes from 9 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/klump-how-long-has-your-page-executed-for__4-8354/archive/master.zip)

### API Declarations

Dun copy...


### Source Code

```
<%
StartTotalTime = Timer
EndTotalTime = Timer %>
Page loaded in : <%=formatnumber(EndTotalTime-StartTotalTime,2)%> seconds.
```

