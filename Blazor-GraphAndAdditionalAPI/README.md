Example Blazor App that calls Graph API on behalf of the user as well as an additional downstream API, also on behalf of the user. If you need to call a downstream API as the application itself, a different approach is needed.

An example of where you may use this approach is to have a Blazor web app that users login to that needs to call a back-end API in the context of the user, such as a ToDo list API. You can then authenticate additional clients such as a MAUI app against the same back-end.

This example was created from the default "Blazor Web App"" template in visual studio with the following options:

- Framework: .NET 8.0
- Authentication Type: None
- Configure for HTTPS: True
- Interactive render mode: Server (WASM and Auto modes require different approaches)
- Interactivity Location: Per page/component
- Include sample pages: True
- Do not use top-level statements: False

# Prerequisites

- A Microsoft Azure subscription
- App Registration for the Blazor App			
- App Registration for the Downstream API

## App Registration for the Blazor App

_Details to be added_

### Expose API Scope

### Set Client Secrets in the Blazor Project

_Details to be added_

## App Registration for the Downstream API

_Details to be added_

### Add Downstream API Permissions

### Set Client Secrets in the Downstream API Project

_Details to be added_

## Set the Downstream API Registration to Trust the Blazor Registration