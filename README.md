# cssrem

Converts between `px` and `rem` units in VSCode

[中文版](README.zh-CN.md)

![](demo.gif)

# Install

```bash
ext install cssrem
```

# How To Use

+ Auto snippet
+ CLI: Press `F1`, enter `cssrem`

# Support Language

html vue css less scss sass stylus tpl（php smarty3）

# Configuration

The `.cssrem` file in the root directory has the highest priority, and it's format is as follows:

```json
{
  "rootFontSize": 18,
  "fixedDigits": 3
}
```

Secondly, you can also configure the global. Open your user and workspace settings (`File > Preferences > Settings`):

Name | Description | Default
---- | ----------- | -------
`cssrem.rootFontSize` | root font-size (Unit: `px`) | `16`
`cssrem.fixedDigits` | `px` to `rem` decimal point maximum length | `6`
`cssrem.autoRemovePrefixZero` | Automatically remove prefix 0 | `true`
`cssrem.ingoresViaCommand` | Ignores `px` to `rem` when trigger command (Unit: `string[]`), can be set `[ "1px", "0.5px" ]` | `[]`

**NOTE:** Muse be restart vscode after modification
