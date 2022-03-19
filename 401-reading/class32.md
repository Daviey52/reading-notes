# Class 32

[Home](https://daviey52.github.io/reading-notes/)

## Permissions and Postgresql

### DRF Permissions

Alongside authentication and throttling, permissions determine if a request should be granted or denied access.

Permission checks always run at the very start of the view, before any code is executed. They typically use the authentication information I the request.user and request.auth properties to determine if the incoming request should be permitted.

The simplest style of permissions is to allows access to any authenticated user and deny access to any unauthenticated user. This corresponds to the IsAuthenticated Class in REST framework.

isAuthenticatedOrReadOnly allows restricted access to unauthenticated user in the form of read-only access.

When permission check fail, either a ‘403’ Forbidden or a ‘401’ Unauthorized response will be returned.
REST framework permissions also support object-level permissioning. This determines if a user should be allowed to act on a particular object, which typically will be a model instance.

Often when using object level permissions, you will want to filter the queryset appropriately, to ensure that users only have visibility onto instance that they are permitted to view.

Allow Any permissions will allow unrestricted access regardless if the request was authenticated or unauthenticated.
To implement custom permissions, override BasePermission
