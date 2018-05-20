# Go API client for Bitbucket (bitbucket-server V1)


## Overview
This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

- API version: 
- Package version: 1.0.0

## Documentation for API Endpoints

All URIs are relative to *http://example.com/rest/*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**AddGroupToUser**](docs/DefaultApi.md#addgrouptouser) | **Post** /api/1.0/admin/users/add-group | 
*DefaultApi* | [**AddUserToGroup**](docs/DefaultApi.md#addusertogroup) | **Post** /api/1.0/admin/groups/add-user | 
*DefaultApi* | [**AddUserToGroups**](docs/DefaultApi.md#addusertogroups) | **Post** /api/1.0/admin/users/add-groups | 
*DefaultApi* | [**AddUsersToGroup**](docs/DefaultApi.md#adduserstogroup) | **Post** /api/1.0/admin/groups/add-users | 
*DefaultApi* | [**Approve**](docs/DefaultApi.md#approve) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/approve | 
*DefaultApi* | [**AssignParticipantRole**](docs/DefaultApi.md#assignparticipantrole) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants | 
*DefaultApi* | [**CanMerge**](docs/DefaultApi.md#canmerge) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/merge | 
*DefaultApi* | [**ClearSenderAddress**](docs/DefaultApi.md#clearsenderaddress) | **Delete** /api/1.0/admin/mail-server/sender-address | 
*DefaultApi* | [**ClearUserCaptchaChallenge**](docs/DefaultApi.md#clearusercaptchachallenge) | **Delete** /api/1.0/admin/users/captcha | 
*DefaultApi* | [**CountPullRequestTasks**](docs/DefaultApi.md#countpullrequesttasks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/tasks/count | 
*DefaultApi* | [**Create**](docs/DefaultApi.md#create) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests | 
*DefaultApi* | [**CreateBranch**](docs/DefaultApi.md#createbranch) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches | 
*DefaultApi* | [**CreateComment**](docs/DefaultApi.md#createcomment) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments | 
*DefaultApi* | [**CreateComment_0**](docs/DefaultApi.md#createcomment_0) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments | 
*DefaultApi* | [**CreateGroup**](docs/DefaultApi.md#creategroup) | **Post** /api/1.0/admin/groups | 
*DefaultApi* | [**CreateProject**](docs/DefaultApi.md#createproject) | **Post** /api/1.0/projects | 
*DefaultApi* | [**CreateRepository**](docs/DefaultApi.md#createrepository) | **Post** /api/1.0/projects/{projectKey}/repos | 
*DefaultApi* | [**CreateTag**](docs/DefaultApi.md#createtag) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/tags | 
*DefaultApi* | [**CreateTask**](docs/DefaultApi.md#createtask) | **Post** /api/1.0/tasks | 
*DefaultApi* | [**CreateUser**](docs/DefaultApi.md#createuser) | **Post** /api/1.0/admin/users | 
*DefaultApi* | [**CreateWebhook**](docs/DefaultApi.md#createwebhook) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks | 
*DefaultApi* | [**Decline**](docs/DefaultApi.md#decline) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/decline | 
*DefaultApi* | [**Delete**](docs/DefaultApi.md#delete) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId} | 
*DefaultApi* | [**DeleteAvatar**](docs/DefaultApi.md#deleteavatar) | **Delete** /api/1.0/users/{userSlug}/avatar.png | 
*DefaultApi* | [**DeleteComment**](docs/DefaultApi.md#deletecomment) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments/{commentId} | 
*DefaultApi* | [**DeleteComment_0**](docs/DefaultApi.md#deletecomment_0) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments/{commentId} | 
*DefaultApi* | [**DeleteGroup**](docs/DefaultApi.md#deletegroup) | **Delete** /api/1.0/admin/groups | 
*DefaultApi* | [**DeleteMailConfig**](docs/DefaultApi.md#deletemailconfig) | **Delete** /api/1.0/admin/mail-server | 
*DefaultApi* | [**DeleteProject**](docs/DefaultApi.md#deleteproject) | **Delete** /api/1.0/projects/{projectKey} | 
*DefaultApi* | [**DeleteRepository**](docs/DefaultApi.md#deleterepository) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | 
*DefaultApi* | [**DeleteRepositoryHook**](docs/DefaultApi.md#deleterepositoryhook) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey} | 
*DefaultApi* | [**DeleteTask**](docs/DefaultApi.md#deletetask) | **Delete** /api/1.0/tasks/{taskId} | 
*DefaultApi* | [**DeleteUser**](docs/DefaultApi.md#deleteuser) | **Delete** /api/1.0/admin/users | 
*DefaultApi* | [**DeleteWebhook**](docs/DefaultApi.md#deletewebhook) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId} | 
*DefaultApi* | [**DisableHook**](docs/DefaultApi.md#disablehook) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/enabled | 
*DefaultApi* | [**DisableHook_0**](docs/DefaultApi.md#disablehook_0) | **Delete** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/enabled | 
*DefaultApi* | [**EditFile**](docs/DefaultApi.md#editfile) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/browse/{path} | 
*DefaultApi* | [**EnableHook**](docs/DefaultApi.md#enablehook) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/enabled | 
*DefaultApi* | [**EnableHook_0**](docs/DefaultApi.md#enablehook_0) | **Put** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/enabled | 
*DefaultApi* | [**FindGroupsForUser**](docs/DefaultApi.md#findgroupsforuser) | **Get** /api/1.0/admin/users/more-members | 
*DefaultApi* | [**FindOtherGroupsForUser**](docs/DefaultApi.md#findothergroupsforuser) | **Get** /api/1.0/admin/users/more-non-members | 
*DefaultApi* | [**FindUsersInGroup**](docs/DefaultApi.md#findusersingroup) | **Get** /api/1.0/admin/groups/more-members | 
*DefaultApi* | [**FindUsersNotInGroup**](docs/DefaultApi.md#findusersnotingroup) | **Get** /api/1.0/admin/groups/more-non-members | 
*DefaultApi* | [**FindWebhooks**](docs/DefaultApi.md#findwebhooks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks | 
*DefaultApi* | [**ForkRepository**](docs/DefaultApi.md#forkrepository) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | 
*DefaultApi* | [**Get**](docs/DefaultApi.md#get) | **Get** /api/1.0/admin/license | 
*DefaultApi* | [**GetActivities**](docs/DefaultApi.md#getactivities) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/activities | 
*DefaultApi* | [**GetApplicationProperties**](docs/DefaultApi.md#getapplicationproperties) | **Get** /api/1.0/application-properties | 
*DefaultApi* | [**GetArchive**](docs/DefaultApi.md#getarchive) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/archive | 
*DefaultApi* | [**GetAvatar**](docs/DefaultApi.md#getavatar) | **Get** /api/1.0/hooks/{hookKey}/avatar | 
*DefaultApi* | [**GetBranches**](docs/DefaultApi.md#getbranches) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches | 
*DefaultApi* | [**GetChanges**](docs/DefaultApi.md#getchanges) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/changes | 
*DefaultApi* | [**GetChanges_0**](docs/DefaultApi.md#getchanges_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/changes | 
*DefaultApi* | [**GetComment**](docs/DefaultApi.md#getcomment) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments/{commentId} | 
*DefaultApi* | [**GetComment_0**](docs/DefaultApi.md#getcomment_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments/{commentId} | 
*DefaultApi* | [**GetComments**](docs/DefaultApi.md#getcomments) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments | 
*DefaultApi* | [**GetComments_0**](docs/DefaultApi.md#getcomments_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments | 
*DefaultApi* | [**GetCommit**](docs/DefaultApi.md#getcommit) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId} | 
*DefaultApi* | [**GetCommits**](docs/DefaultApi.md#getcommits) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits | 
*DefaultApi* | [**GetCommits_0**](docs/DefaultApi.md#getcommits_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/commits | 
*DefaultApi* | [**GetContent**](docs/DefaultApi.md#getcontent) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/browse | 
*DefaultApi* | [**GetContent_0**](docs/DefaultApi.md#getcontent_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/browse/{path} | 
*DefaultApi* | [**GetContent_1**](docs/DefaultApi.md#getcontent_1) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/raw | 
*DefaultApi* | [**GetContent_2**](docs/DefaultApi.md#getcontent_2) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/raw/{path} | 
*DefaultApi* | [**GetDefaultBranch**](docs/DefaultApi.md#getdefaultbranch) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches/default | 
*DefaultApi* | [**GetForkedRepositories**](docs/DefaultApi.md#getforkedrepositories) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/forks | 
*DefaultApi* | [**GetGroups**](docs/DefaultApi.md#getgroups) | **Get** /api/1.0/admin/groups | 
*DefaultApi* | [**GetGroupsWithAnyPermission**](docs/DefaultApi.md#getgroupswithanypermission) | **Get** /api/1.0/admin/permissions/groups | 
*DefaultApi* | [**GetGroupsWithAnyPermission_0**](docs/DefaultApi.md#getgroupswithanypermission_0) | **Get** /api/1.0/projects/{projectKey}/permissions/groups | 
*DefaultApi* | [**GetGroupsWithAnyPermission_1**](docs/DefaultApi.md#getgroupswithanypermission_1) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups | 
*DefaultApi* | [**GetGroupsWithoutAnyPermission**](docs/DefaultApi.md#getgroupswithoutanypermission) | **Get** /api/1.0/admin/permissions/groups/none | 
*DefaultApi* | [**GetGroupsWithoutAnyPermission_0**](docs/DefaultApi.md#getgroupswithoutanypermission_0) | **Get** /api/1.0/projects/{projectKey}/permissions/groups/none | 
*DefaultApi* | [**GetGroupsWithoutAnyPermission_1**](docs/DefaultApi.md#getgroupswithoutanypermission_1) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups/none | 
*DefaultApi* | [**GetGroups_0**](docs/DefaultApi.md#getgroups_0) | **Get** /api/1.0/groups | 
*DefaultApi* | [**GetInformation**](docs/DefaultApi.md#getinformation) | **Get** /api/1.0/admin/cluster | 
*DefaultApi* | [**GetLatestInvocation**](docs/DefaultApi.md#getlatestinvocation) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId}/latest | 
*DefaultApi* | [**GetLevel**](docs/DefaultApi.md#getlevel) | **Get** /api/1.0/logs/logger/{loggerName} | 
*DefaultApi* | [**GetMailConfig**](docs/DefaultApi.md#getmailconfig) | **Get** /api/1.0/admin/mail-server | 
*DefaultApi* | [**GetMergeConfig**](docs/DefaultApi.md#getmergeconfig) | **Get** /api/1.0/admin/pull-requests/{scmId} | 
*DefaultApi* | [**GetPage**](docs/DefaultApi.md#getpage) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests | 
*DefaultApi* | [**GetProject**](docs/DefaultApi.md#getproject) | **Get** /api/1.0/projects/{projectKey} | 
*DefaultApi* | [**GetProjectAvatar**](docs/DefaultApi.md#getprojectavatar) | **Get** /api/1.0/projects/{projectKey}/avatar.png | 
*DefaultApi* | [**GetProjects**](docs/DefaultApi.md#getprojects) | **Get** /api/1.0/projects | 
*DefaultApi* | [**GetPullRequestCount**](docs/DefaultApi.md#getpullrequestcount) | **Get** /api/1.0/inbox/pull-requests/count | 
*DefaultApi* | [**GetPullRequestSettings**](docs/DefaultApi.md#getpullrequestsettings) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/pull-requests | 
*DefaultApi* | [**GetPullRequestSettings_0**](docs/DefaultApi.md#getpullrequestsettings_0) | **Get** /api/1.0/projects/{projectKey}/settings/pull-requests/{scmId} | 
*DefaultApi* | [**GetPullRequestSuggestions**](docs/DefaultApi.md#getpullrequestsuggestions) | **Get** /api/1.0/dashboard/pull-request-suggestions | 
*DefaultApi* | [**GetPullRequestTasks**](docs/DefaultApi.md#getpullrequesttasks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/tasks | 
*DefaultApi* | [**GetPullRequests**](docs/DefaultApi.md#getpullrequests) | **Get** /api/1.0/dashboard/pull-requests | 
*DefaultApi* | [**GetPullRequests_0**](docs/DefaultApi.md#getpullrequests_0) | **Get** /api/1.0/inbox/pull-requests | 
*DefaultApi* | [**GetRelatedRepositories**](docs/DefaultApi.md#getrelatedrepositories) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/related | 
*DefaultApi* | [**GetRepositories**](docs/DefaultApi.md#getrepositories) | **Get** /api/1.0/projects/{projectKey}/repos | 
*DefaultApi* | [**GetRepositoriesRecentlyAccessed**](docs/DefaultApi.md#getrepositoriesrecentlyaccessed) | **Get** /api/1.0/profile/recent/repos | 
*DefaultApi* | [**GetRepositories_0**](docs/DefaultApi.md#getrepositories_0) | **Get** /api/1.0/repos | 
*DefaultApi* | [**GetRepository**](docs/DefaultApi.md#getrepository) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | 
*DefaultApi* | [**GetRepositoryHook**](docs/DefaultApi.md#getrepositoryhook) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey} | 
*DefaultApi* | [**GetRepositoryHook_0**](docs/DefaultApi.md#getrepositoryhook_0) | **Get** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey} | 
*DefaultApi* | [**GetRepositoryHooks**](docs/DefaultApi.md#getrepositoryhooks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks | 
*DefaultApi* | [**GetRepositoryHooks_0**](docs/DefaultApi.md#getrepositoryhooks_0) | **Get** /api/1.0/projects/{projectKey}/settings/hooks | 
*DefaultApi* | [**GetRootLevel**](docs/DefaultApi.md#getrootlevel) | **Get** /api/1.0/logs/rootLogger | 
*DefaultApi* | [**GetSenderAddress**](docs/DefaultApi.md#getsenderaddress) | **Get** /api/1.0/admin/mail-server/sender-address | 
*DefaultApi* | [**GetSettings**](docs/DefaultApi.md#getsettings) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/settings | 
*DefaultApi* | [**GetSettings_0**](docs/DefaultApi.md#getsettings_0) | **Get** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/settings | 
*DefaultApi* | [**GetStatistics**](docs/DefaultApi.md#getstatistics) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId}/statistics | 
*DefaultApi* | [**GetStatisticsSummary**](docs/DefaultApi.md#getstatisticssummary) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId}/statistics/summary | 
*DefaultApi* | [**GetTag**](docs/DefaultApi.md#gettag) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/tags/{name} | 
*DefaultApi* | [**GetTags**](docs/DefaultApi.md#gettags) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/tags | 
*DefaultApi* | [**GetTask**](docs/DefaultApi.md#gettask) | **Get** /api/1.0/tasks/{taskId} | 
*DefaultApi* | [**GetUser**](docs/DefaultApi.md#getuser) | **Get** /api/1.0/users/{userSlug} | 
*DefaultApi* | [**GetUserSettings**](docs/DefaultApi.md#getusersettings) | **Get** /api/1.0/users/{userSlug}/settings | 
*DefaultApi* | [**GetUsers**](docs/DefaultApi.md#getusers) | **Get** /api/1.0/admin/users | 
*DefaultApi* | [**GetUsersWithAnyPermission**](docs/DefaultApi.md#getuserswithanypermission) | **Get** /api/1.0/admin/permissions/users | 
*DefaultApi* | [**GetUsersWithAnyPermission_0**](docs/DefaultApi.md#getuserswithanypermission_0) | **Get** /api/1.0/projects/{projectKey}/permissions/users | 
*DefaultApi* | [**GetUsersWithAnyPermission_1**](docs/DefaultApi.md#getuserswithanypermission_1) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users | 
*DefaultApi* | [**GetUsersWithoutAnyPermission**](docs/DefaultApi.md#getuserswithoutanypermission) | **Get** /api/1.0/admin/permissions/users/none | 
*DefaultApi* | [**GetUsersWithoutPermission**](docs/DefaultApi.md#getuserswithoutpermission) | **Get** /api/1.0/projects/{projectKey}/permissions/users/none | 
*DefaultApi* | [**GetUsersWithoutPermission_0**](docs/DefaultApi.md#getuserswithoutpermission_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users/none | 
*DefaultApi* | [**GetUsers_0**](docs/DefaultApi.md#getusers_0) | **Get** /api/1.0/users | 
*DefaultApi* | [**GetWebhook**](docs/DefaultApi.md#getwebhook) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId} | 
*DefaultApi* | [**Get_0**](docs/DefaultApi.md#get_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId} | 
*DefaultApi* | [**HasAllUserPermission**](docs/DefaultApi.md#hasalluserpermission) | **Get** /api/1.0/projects/{projectKey}/permissions/{permission}/all | 
*DefaultApi* | [**ListParticipants**](docs/DefaultApi.md#listparticipants) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants | 
*DefaultApi* | [**Merge**](docs/DefaultApi.md#merge) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/merge | 
*DefaultApi* | [**ModifyAllUserPermission**](docs/DefaultApi.md#modifyalluserpermission) | **Post** /api/1.0/projects/{projectKey}/permissions/{permission}/all | 
*DefaultApi* | [**Preview**](docs/DefaultApi.md#preview) | **Post** /api/1.0/markup/preview | 
*DefaultApi* | [**RemoveGroupFromUser**](docs/DefaultApi.md#removegroupfromuser) | **Post** /api/1.0/admin/users/remove-group | 
*DefaultApi* | [**RemoveUserFromGroup**](docs/DefaultApi.md#removeuserfromgroup) | **Post** /api/1.0/admin/groups/remove-user | 
*DefaultApi* | [**RenameUser**](docs/DefaultApi.md#renameuser) | **Post** /api/1.0/admin/users/rename | 
*DefaultApi* | [**Reopen**](docs/DefaultApi.md#reopen) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/reopen | 
*DefaultApi* | [**RetryCreateRepository**](docs/DefaultApi.md#retrycreaterepository) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/recreate | 
*DefaultApi* | [**RevokePermissionsForGroup**](docs/DefaultApi.md#revokepermissionsforgroup) | **Delete** /api/1.0/admin/permissions/groups | 
*DefaultApi* | [**RevokePermissionsForGroup_0**](docs/DefaultApi.md#revokepermissionsforgroup_0) | **Delete** /api/1.0/projects/{projectKey}/permissions/groups | 
*DefaultApi* | [**RevokePermissionsForGroup_1**](docs/DefaultApi.md#revokepermissionsforgroup_1) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups | 
*DefaultApi* | [**RevokePermissionsForUser**](docs/DefaultApi.md#revokepermissionsforuser) | **Delete** /api/1.0/admin/permissions/users | 
*DefaultApi* | [**RevokePermissionsForUser_0**](docs/DefaultApi.md#revokepermissionsforuser_0) | **Delete** /api/1.0/projects/{projectKey}/permissions/users | 
*DefaultApi* | [**RevokePermissionsForUser_1**](docs/DefaultApi.md#revokepermissionsforuser_1) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users | 
*DefaultApi* | [**Search**](docs/DefaultApi.md#search) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/participants | 
*DefaultApi* | [**SetDefaultBranch**](docs/DefaultApi.md#setdefaultbranch) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches/default | 
*DefaultApi* | [**SetLevel**](docs/DefaultApi.md#setlevel) | **Put** /api/1.0/logs/logger/{loggerName}/{levelName} | 
*DefaultApi* | [**SetMailConfig**](docs/DefaultApi.md#setmailconfig) | **Put** /api/1.0/admin/mail-server | 
*DefaultApi* | [**SetMergeConfig**](docs/DefaultApi.md#setmergeconfig) | **Post** /api/1.0/admin/pull-requests/{scmId} | 
*DefaultApi* | [**SetPermissionForGroup**](docs/DefaultApi.md#setpermissionforgroup) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups | 
*DefaultApi* | [**SetPermissionForGroups**](docs/DefaultApi.md#setpermissionforgroups) | **Put** /api/1.0/admin/permissions/groups | 
*DefaultApi* | [**SetPermissionForGroups_0**](docs/DefaultApi.md#setpermissionforgroups_0) | **Put** /api/1.0/projects/{projectKey}/permissions/groups | 
*DefaultApi* | [**SetPermissionForUser**](docs/DefaultApi.md#setpermissionforuser) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users | 
*DefaultApi* | [**SetPermissionForUsers**](docs/DefaultApi.md#setpermissionforusers) | **Put** /api/1.0/admin/permissions/users | 
*DefaultApi* | [**SetPermissionForUsers_0**](docs/DefaultApi.md#setpermissionforusers_0) | **Put** /api/1.0/projects/{projectKey}/permissions/users | 
*DefaultApi* | [**SetRootLevel**](docs/DefaultApi.md#setrootlevel) | **Put** /api/1.0/logs/rootLogger/{levelName} | 
*DefaultApi* | [**SetSenderAddress**](docs/DefaultApi.md#setsenderaddress) | **Put** /api/1.0/admin/mail-server/sender-address | 
*DefaultApi* | [**SetSettings**](docs/DefaultApi.md#setsettings) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/settings | 
*DefaultApi* | [**SetSettings_0**](docs/DefaultApi.md#setsettings_0) | **Put** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/settings | 
*DefaultApi* | [**Stream**](docs/DefaultApi.md#stream) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/last-modified | 
*DefaultApi* | [**StreamChanges**](docs/DefaultApi.md#streamchanges) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/compare/changes | 
*DefaultApi* | [**StreamChanges_0**](docs/DefaultApi.md#streamchanges_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/changes | 
*DefaultApi* | [**StreamCommits**](docs/DefaultApi.md#streamcommits) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/compare/commits | 
*DefaultApi* | [**StreamDiff**](docs/DefaultApi.md#streamdiff) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/diff | 
*DefaultApi* | [**StreamDiff_0**](docs/DefaultApi.md#streamdiff_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/diff/{path} | 
*DefaultApi* | [**StreamDiff_1**](docs/DefaultApi.md#streamdiff_1) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/compare/diff{path} | 
*DefaultApi* | [**StreamDiff_2**](docs/DefaultApi.md#streamdiff_2) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/diff | 
*DefaultApi* | [**StreamDiff_3**](docs/DefaultApi.md#streamdiff_3) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/diff/{path} | 
*DefaultApi* | [**StreamDiff_4**](docs/DefaultApi.md#streamdiff_4) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/diff | 
*DefaultApi* | [**StreamDiff_5**](docs/DefaultApi.md#streamdiff_5) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/diff/{path} | 
*DefaultApi* | [**StreamFiles**](docs/DefaultApi.md#streamfiles) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/files | 
*DefaultApi* | [**StreamFiles_0**](docs/DefaultApi.md#streamfiles_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/files/{path} | 
*DefaultApi* | [**Stream_0**](docs/DefaultApi.md#stream_0) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/last-modified/{path} | 
*DefaultApi* | [**TestWebhook**](docs/DefaultApi.md#testwebhook) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/test | 
*DefaultApi* | [**UnassignParticipantRole**](docs/DefaultApi.md#unassignparticipantrole) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants | 
*DefaultApi* | [**UnassignParticipantRole_0**](docs/DefaultApi.md#unassignparticipantrole_0) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug} | 
*DefaultApi* | [**Unwatch**](docs/DefaultApi.md#unwatch) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/watch | 
*DefaultApi* | [**Unwatch_0**](docs/DefaultApi.md#unwatch_0) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/watch | 
*DefaultApi* | [**Update**](docs/DefaultApi.md#update) | **Post** /api/1.0/admin/license | 
*DefaultApi* | [**UpdateComment**](docs/DefaultApi.md#updatecomment) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments/{commentId} | 
*DefaultApi* | [**UpdateComment_0**](docs/DefaultApi.md#updatecomment_0) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments/{commentId} | 
*DefaultApi* | [**UpdateProject**](docs/DefaultApi.md#updateproject) | **Put** /api/1.0/projects/{projectKey} | 
*DefaultApi* | [**UpdatePullRequestSettings**](docs/DefaultApi.md#updatepullrequestsettings) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/pull-requests | 
*DefaultApi* | [**UpdatePullRequestSettings_0**](docs/DefaultApi.md#updatepullrequestsettings_0) | **Post** /api/1.0/projects/{projectKey}/settings/pull-requests/{scmId} | 
*DefaultApi* | [**UpdateRepository**](docs/DefaultApi.md#updaterepository) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | 
*DefaultApi* | [**UpdateSettings**](docs/DefaultApi.md#updatesettings) | **Post** /api/1.0/users/{userSlug}/settings | 
*DefaultApi* | [**UpdateStatus**](docs/DefaultApi.md#updatestatus) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug} | 
*DefaultApi* | [**UpdateTask**](docs/DefaultApi.md#updatetask) | **Put** /api/1.0/tasks/{taskId} | 
*DefaultApi* | [**UpdateUserDetails**](docs/DefaultApi.md#updateuserdetails) | **Put** /api/1.0/admin/users | 
*DefaultApi* | [**UpdateUserDetails_0**](docs/DefaultApi.md#updateuserdetails_0) | **Put** /api/1.0/users | 
*DefaultApi* | [**UpdateUserPassword**](docs/DefaultApi.md#updateuserpassword) | **Put** /api/1.0/admin/users/credentials | 
*DefaultApi* | [**UpdateUserPassword_0**](docs/DefaultApi.md#updateuserpassword_0) | **Put** /api/1.0/users/credentials | 
*DefaultApi* | [**UpdateWebhook**](docs/DefaultApi.md#updatewebhook) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId} | 
*DefaultApi* | [**Update_0**](docs/DefaultApi.md#update_0) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId} | 
*DefaultApi* | [**UploadAvatar**](docs/DefaultApi.md#uploadavatar) | **Post** /api/1.0/projects/{projectKey}/avatar.png | 
*DefaultApi* | [**UploadAvatar_0**](docs/DefaultApi.md#uploadavatar_0) | **Post** /api/1.0/users/{userSlug}/avatar.png | 
*DefaultApi* | [**Watch**](docs/DefaultApi.md#watch) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/watch | 
*DefaultApi* | [**Watch_0**](docs/DefaultApi.md#watch_0) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/watch | 
*DefaultApi* | [**WithdrawApproval**](docs/DefaultApi.md#withdrawapproval) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/approve | 


## Documentation For Models



## Documentation For Authorization
 Endpoints do not require authorization.


## Author

George Fleury 

