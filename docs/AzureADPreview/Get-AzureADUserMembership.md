# Get-AzureADUserMembership

> /users/{user-id}/memberOf | /users/{user-id}/memberOf/{directoryObject-id}

## Data

+ AAD Command: [Get-AzureADUserMembership](https://docs.microsoft.com/en-us/powershell/module/AzureADPreview/Get-AzureADUserMembership)
+ AAD Module: AzureADPreview
+ Graph Command: [Get-MgUserMemberOf](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Users/Get-MgUserMemberOf) ([Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgUserMemberOf))
+ Graph Module: Microsoft.Graph.Users

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Directory.Read.All, Directory.ReadWrite.All, GroupMember.Read.All|
|Delegate|Directory.Read.All, Directory.ReadWrite.All, GroupMember.Read.All, User.Read|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|All|All|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|ObjectId||System.String|||
|Top|Top|System.Nullable/System.Int32|System.Int32||

