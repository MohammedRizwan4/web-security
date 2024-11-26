# web-security

SQL injections tools
https://github.com/vivek3141/sql-injection-demo

No sql injection tools
https://github.com/codingo/NoSQLMap
Easy : https://github.com/FrostyLabs/NoSQL-Injection

Xpath Injection
https://github.com/r0oth3x49/Xpath

LDAP Injection
https://github.com/Atsika/lbi
https://github.com/EmreOvunc/eLdap-Ldap-Search-and-Filter

XML Injection
https://github.com/luisfontes19/xxexploiter

Sql injection using tool
Tool : https://sqlmap.org/

Mail service Injection
https://github.com/Email-Analysis-Toolkit/command-injection-tester


Create a macro document which opens command prompt while opening document. And try to execute some basic commands like IPCONFIG, windows version etc.
Sub AutoOpen()
    ' This will run when the document is opened
    Call RunCommands
End Sub

Sub RunCommands()
    Dim shell As Object
    Set shell = CreateObject("WScript.Shell")

    ' Run command prompt commands
    shell.Run "cmd.exe /c ipconfig"
    shell.Run "cmd.exe /c ver"
End Sub



