# How to contribute
This organization has open source projects of SDK for LINE APIs or sample products using LINE APIs.

## Pull request and review
Both core members and external contributors contribute by sending pull requests that go through the same review process.

## Branch
The master branch is always stable and deployable.
All tests must pass on master at all times.
If you send a pull request, please do it against the master branch. 

## Coding rules
If you create new repository on this organization, need to follow the rules below.

### Languages or libraries
You need to use the latest stable version of languages and libraries.

### Naming for packages or namespaces
You should name "LineDC" (or "line-dc") to the top level package name or namespace.

### Repository Rules
- All lowercase.
- Multiple words should be separated by hypen. 
- The SDK name should be the target api name and language name. An example is "line-messaging-api-csharp".
- Do not include "sdk" in the repository name of SDK.
- In the case of repositories for SDK's sample projects, append "-samples" at the end of repository name.
- Include a sample project just to show how to use a single SDK in the repository of that SDK.

## Community SDKs
### C#
- [LINE Messaging API](https://github.com/line-developer-community/line-messaging-api-csharp)
- [LINE Login](https://github.com/line-developer-community/line-login-csharp)
- [Clova Extensions Kit](https://github.com/line-developer-community/clova-extensions-kit-csharp)


