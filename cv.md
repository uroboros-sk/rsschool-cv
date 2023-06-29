-----
# [rsschool-cv](https://uroboros-sk.github.io/rsschool-cv/)
-----

## Sergey Kim
**C# Developer**

-----
## Contacts:
- Location: Uzbekistan, Tashkent
- E-mail: sergey.e.kim@gmail.com
-----
## Skills:
- C#, Microsoft .NET Framework 4.5 
- Windows Forms
- ADO.NET
- T-SQL
-----
## Code Example:
```
    private void StartWsServer(string serverIp, int serverPort)
    {
        try
        {
            _serverWs = new WatsonWsServer(serverIp, serverPort);
            _serverWs.ClientConnected += ServerWs_ClientConnected;
            _serverWs.ClientDisconnected += ServerWs_ClientDisconnected;
            _serverWs.MessageReceived += ServerWs_MessageReceived;
            _serverWs.Start();
            _isBusy = false;
        }
        catch (Exception ex)
        {
            MessageBox.Show(ex.Message);
            Logger.Error(ex, ex.Message);
            ExitApp();
        }
    }
```
-----
## Experience:
- 7+ years of experience in design, development and implementation of Windows Forms application using Microsoft .NET Framework, C#
-----
## Education:
- Tashkent University of Information Technologies named after Muhammad al-Khwarizmi (Radio communication, Radio broadcasting and Television), Bachelor's degree
- English level - basic
-----