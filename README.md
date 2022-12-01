# GoGaurdian-Powershell-Setup
usernameinsert = read-host -prompt "what is your username (Jblog5384)"


rename-item -path "C:\Users\\$usernameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanh" -newname "haldlgldplgnggkjaafhelgiaglafanhE"; new-item -Type Directory -path "C:\Users\\$usernameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\" -name "haldlgldplgnggkjaafhelgiaglafanh"
