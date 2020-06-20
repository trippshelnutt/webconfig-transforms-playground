# webconfig-transforms-playground
Quick example project to play with Web.config transforms.

This project has a default ASP.NET MVC Application with modified Web configs.

The main publish profile to use is the `Debug Folder` publish. This will trigger the transforms to execute and will publish the website to the `bin\Debug\Publish` directory. The `Web.config` file in that directory should have the transforms applied from `Web.Debug.config` to the main `Web.config` file.

Examples:

- Replace
- SetAttributes (multiple)
- SetAttributes (single)
- RemoveAttribute
- InsertBefore (uses XPath)
- InsertAfter (uses XPath)
- RemoveAll
- Locator (used for most of the above to select which element should be transformed)
