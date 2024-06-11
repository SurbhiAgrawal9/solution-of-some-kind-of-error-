 ## the core issue: an attempt to change PowerShell's execution policy was blocked due to insufficient permissions.

Open PowerShell (without administrator privileges):

Press Win + X and select "Windows PowerShell" or "Terminal".
Set the Execution Policy for the Current User:

Run the following command:
```js
powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

```

