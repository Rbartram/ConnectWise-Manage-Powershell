# New-CWMCompanyTypeAssociation
## SYNOPSIS
Creates a new type association for a company
## SYNTAX
```powershell
New-CWMCompanyTypeAssociation [-CompanyID] <Int32> [[-Type] <Object>] [<CommonParameters>]
```
## PARAMETERS
### -CompanyID &lt;Int32&gt;

```
Required                    true
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -Type &lt;Object&gt;

```
Required                    false
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>New-CWMCompanyTypeAssociation -CompanyID 4385 -Type @{type = @{id = 68}}

Adds the type 68 to company 4385
```

## NOTES
Author: Chris Taylor

Date: 8/22/2018 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/products/manage/rest?a=Company&e=CompanyCompanyTypeAssociations&o=CREATE
