<div align="center">

## A way to input / write from/to \.txt files\_\*


</div>

### Description

This is only for beginners and the advanced guys will know it ..The following lines of code will teach you how to input from .txt files and how to write to .txt files ....

Votes and Comments are highly appreciated !

Happy Programming
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[ComputerWhiz](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/computerwhiz.md)
**Level**          |Beginner
**User Rating**    |3.2 (29 globes from 9 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/computerwhiz-a-way-to-input-write-from-to-txt-files__1-41650/archive/master.zip)





### Source Code

```
Make a label and name it lblInput1
Make a .txt file in the same folder as the project .and name it as InputFile
make a command button ,name it cmdWrite
make a textbox and name it txtInput
Now ,in the Form_load() event ,add this code -
dim txtVar1 as string
open app.path + "\inputfile.txt" for input as #1
input #1, txtvar1
txtvar1 = lblinput.caption
close #1
Now to write to .txt files
In the cmdwrite_click() event -
open app.path + "\inputfile.txt" for append as #2
write #2, txtinput
close #2
```

