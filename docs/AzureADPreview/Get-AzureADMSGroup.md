# Get-AzureADMSGroup

> /groups | /groups/{group-id}

## Data

+ AAD Command: [Get-AzureADMSGroup](https://docs.microsoft.com/en-us/powershell/module/AzureADPreview/Get-AzureADMSGroup)
+ AAD Module: AzureADPreview
+ Graph Command: [Get-MgGroup](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Groups/Get-MgGroup) ([Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgGroup))
+ Graph Module: Microsoft.Graph.Groups

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Directory.Read.All, Directory.ReadWrite.All, Group.Read.All, Group.ReadWrite.All, GroupMember.Read.All|
|Delegate|Directory.Read.All, Directory.ReadWrite.All, Group.Read.All, Group.ReadWrite.All, GroupMember.Read.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|All|All|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|Filter|Filter|System.String|System.String||
|Id||System.String|||
|SearchString||System.String|||
|Select||System.String|||
|Top|Top|System.Nullable/System.Int32|System.Int32||

