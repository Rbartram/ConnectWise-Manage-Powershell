# Remove-CWMTicket
## SYNOPSIS
This function will remove the supplied ticket.
## SYNTAX
```powershell
Remove-CWMTicket [-TicketID] <Int32> [<CommonParameters>]
```
## PARAMETERS
### -TicketID &lt;Int32&gt;
The ticket ID of the ticket you want to remove
```
Required                    true
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>Remove-CWMTicket -TicketID 1

Will remove ticket 1
```

## NOTES
Author: Chris Taylor

Date: 11/7/2018 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/products/manage/rest?a=Service&e=Tickets&o=DELETE
