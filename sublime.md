### phpfmt个人设置参考： <Preferences.sublime-settings>

```json
{
	"autoimport": true,
	"disable_auto_align": false,
	"enable_auto_align": true,
	"format_on_save": true,
	"indent_with_space": true,
	"passes":
	[
		"NoSpaceAfterPHPDocBlocks",
		"ShortArray",
		"DoubleToSingleQuote",
		"RestoreComments",
		"LeftAlignComment",
		"RTrim",
		"UpgradeToPreg",
		"ReplaceBooleanAndOr",
		"IndentTernaryConditions",
		"AlignDoubleSlashComments",
		"EliminateDuplicatedEmptyLines",
		"RemoveUseLeadingSlash",
		"MergeElseIf",
		"ClassToSelf",
		"ClassToStatic",
		"SortUseNameSpace",
		"Reindent",
		"ReindentEqual",
		"ReindentObjOps",
		"ReindentComments",
		"ReindentAndAlignObjOps",
		"ReindentSwitchBlocks",
		"ReindentColonBlocks",
		"PSR1OpenTags",
		"PSR1ClassNames",
		"PSR1ClassConstants",
		"PSR1BOMMark",
		"PSR2AlignObjOp",
		"PSR2EmptyFunction",
		"PSR2CurlyOpenNextLine",
		"PSR2LnAfterNamespace",
		"PSR2KeywordsLowerCase",
		"PSR2IndentWithSpace",
		"PSR2SingleEmptyLineAndStripClosingTag",
		"PSR2ModifierVisibilityStaticOrder",
		"NormalizeLnAndLtrimLines",
		"StripNewlineAfterClassOpen",
		"StripNewlineWithinClassBody"
	],
	"php_bin": "/usr/local/php7/bin/php",
	"psr1": true,
	"psr1_naming": false,
	"psr2": true,
	"smart_linebreak_after_curly": false,
	"version": 4,
	"yoda": false
}
```

注意要把php_bin替换成自己安装php7的目录

### 参考安装插件列表：

工具插件：
- CTags
- DocBlockr
- JsFormat
- phpfmt
- Side Bar
- HTML/CSS/JS Beautify
- EditorConfig
- Emmet
- Git
- GitGutter
- Modific
- SublimeLinter
- Trailing spaces

语法插件：
- volt
- thrift
- Markdown
