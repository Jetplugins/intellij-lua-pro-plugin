# Lua Pro issue tracker

This is the public issue tracker for **Lua Pro**, the Lua and Luau development plugin for JetBrains IDEs.
The commercial plugin's source code is maintained separately and is not published in this repository.

## Report a problem or suggest an improvement

- [Report a bug](https://github.com/Jetplugins/intellij-lua-pro-plugin/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/Jetplugins/intellij-lua-pro-plugin/issues/new?template=feature_request.yml)
- [Browse existing issues](https://github.com/Jetplugins/intellij-lua-pro-plugin/issues)

Before opening an issue, search for an existing report and update Lua Pro to the latest available version. Include the Lua Pro version, IDE name and full build, operating system, selected Lua/Luau runtime, language-server provider and version, steps to reproduce, and a minimal Lua or Luau example. Include the LSP4IJ version and formatter, linter, or debug-adapter versions when relevant. For Remote Development, include both client and backend details.

Source files, configuration, screenshots and IDE logs can contain confidential project information. Remove credentials, license keys, proprietary code, personal information and other sensitive data before attaching material to a public issue.

For security vulnerabilities, use [GitHub's private vulnerability reporting](https://github.com/Jetplugins/intellij-lua-pro-plugin/security/advisories/new) instead of creating a public issue. See the [security policy](SECURITY.md).

## About Lua Pro

Lua Pro supports IntelliJ Platform IDEs 2025.2 and newer:

- Lua 5.1–5.4, LuaJIT and Luau editing, syntax and semantic highlighting, completion, documentation, navigation and inlay hints.
- Independent Lua and Luau language-server settings through Red Hat LSP4IJ: LuaLS, EmmyLuaLS, luau-lsp or custom servers.
- Native inspections and intentions, optional Luacheck, built-in or StyLua formatting, and refactorings with previews and Undo/Redo.
- Module and library resolution, LuaRocks packages, and toolchain discovery, selection and installation.
- Script run configurations, Lua/LuaJIT debugging through lua-debug, and a Lua-aware REPL with a native toolbar and searchable persistent history.

Native editing works without a language server. Language-server features require a compatible configured server; running code and using the REPL require an interpreter. Debugging supports Lua and LuaJIT in IntelliJ IDEA Ultimate, CLion, PyCharm Professional, GoLand and RubyMine. Luau VM debugging is not currently supported. Local attach requires an instrumented Lua host.
