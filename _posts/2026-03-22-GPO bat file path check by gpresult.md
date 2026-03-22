在該台電腦上執行：

gpresult /h C:\temp\gpo.html
start C:\temp\gpo.html

👉 打開報告後：

找到：

User Configuration → Windows Settings → Scripts (Logon/Logoff)

或

Computer Configuration → Windows Settings → Scripts (Startup/Shutdown)
點進去會看到：
Script Name（bat 名稱）
Script Path（重點）

通常會看到像這種：

\\domain.local\SYSVOL\domain.local\Policies\{GUID}\User\Scripts\Logon\xxx.bat

