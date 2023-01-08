# ButterSus's Language Grammar Syntax Highlighting

Visual Studio Code extension, that provides you basic syntax highlighting for your code. 🖌

> **Note:** This extension is still in development and can cause some unexpected bugs.

<pre style="overflow-x: scroll; width: 50%; color: #bbbbbb;background-color: #282c34;font-family: Monocraft, 'Droid Sans Mono', 'monospace', monospace;font-weight: normal;font-size: 18px;line-height: 24px;white-space: pre;">
<span style="color: #e06c75;">start:</span>
<span style="color: #98c379;">statements</span><span style="color: #bbbbbb;"> </span><span style="color: #56b6c2;">&lt;ENDMARKER&gt;</span>
<br />
<span style="color: #676f7d;"># GENERAL STATEMENTS</span>
<span style="color: #676f7d;"># ==================</span>
<br />
<span style="color: #61afef;">statements:</span>
<span style="color: #98c379;">statement</span><span style="color: #e06c75;">+</span>
<br />
<span style="color: #61afef;">statement:</span>
<span style="color: #e06c75;">.</span><span style="color: #98c379;">simple_statement</span><span style="color: #bbbbbb;"> </span><span style="color: #e06c75;">!</span><span style="color: #bbbbbb;">(</span><span style="color: #56b6c2;">&lt;NEWLINE&gt;</span><span style="color: #bbbbbb;"> </span><span style="color: #e06c75;">|</span><span style="color: #bbbbbb;"> </span><span style="color: #56b6c2;">&lt;;&gt;</span><span style="color: #bbbbbb;">) </span><span style="color: #e06c75;">-&gt;</span><span style="color: #bbbbbb;"> </span><span style="color: #e5c07b;">&quot;</span><span style="color: #56b6c2;">${</span><span style="color: #e06c75;">ERROR</span><span style="color: #56b6c2;">}</span><span style="color: #e5c07b;">Expected newline after statement:</span><span style="color: #56b6c2;">\n${</span><span style="color: #e06c75;">REASON</span><span style="color: #56b6c2;">}</span><span style="color: #e5c07b;">&quot;</span><span style="color: #bbbbbb;"> </span><span style="color: #d19a66;font-style: italic;">=&gt; ast.statement</span>
<span style="color: #e06c75;">.</span><span style="color: #98c379;">compound_statement</span>
</pre>

## License

Licensed under of

* [MIT License](LICENSE)
