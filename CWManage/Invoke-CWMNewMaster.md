# Invoke-CWMNewMaster
## SYNOPSIS
This will be basis of all create calls to the ConnectWise Manage API.
## SYNTAX
```powershell
Invoke-CWMNewMaster [[-Arguments] <Object>] [[-URI] <String>] [[-Skip] <String[]>] [<CommonParameters>]
```
## DESCRIPTION
This will insure that all create requests are handled correctly.
## PARAMETERS
### -Arguments &lt;Object&gt;
A hash table of parameters
```
Required                    false
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -URI &lt;String&gt;
The URI of the create endpoint
```
Required                    false
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Skip &lt;String[]&gt;

```
Required                    false
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>Invoke-CWMPatchMaster -Arguments $Arguments -URI $URI
```

## NOTES
Author: Chris Taylor

Date: 10/10/2018 
