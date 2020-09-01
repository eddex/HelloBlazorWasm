# Hello Balzor Wasm :page_with_curl::globe_with_meridians:

This is a simple single page application, created with Blazor webassembly and deployed to github pages.

## Deployment

To deploy the app, use `dotnet publish -c Release` and then copy the generated files to the `docs/` folder with `cp ./bin/Release/netstandard2.1/publish/wwwroot/* ./docs`.