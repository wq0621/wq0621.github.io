VISUAL BASIC (VB) 编程

输出 1 至 9999 的同构数。

Private Sub Form _Click()

Dim i as Integer , N as Long

For i = 1 to 9999

N = i ^ 2

If (N-i) Mod 10 ^ (Len(Trim(i))) = 0 Then 

Print i;

End if

Next i

Print

End sub


要求输入一个数可以判断是否是同构数

Private Sub Form_Click()

Dim i = Inputbox (" 请输入一个数 " ）

N = i ^ 2

If ( N - i ) mod 10 ^ ( Len (Trim(i))) = 0 Then

Print "i" ; "是同构数"

Else

Print "i" ; "不是同构数"

End If

Print

End Sub
