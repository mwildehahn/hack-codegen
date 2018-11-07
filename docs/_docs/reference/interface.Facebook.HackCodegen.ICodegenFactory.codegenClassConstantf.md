
***

layout: docs
title: codegenClassConstantf
permalink: /docs/reference/interface.Facebook.HackCodegen.ICodegenFactory.codegenClassConstantf.md
---







# Facebook\\HackCodegen\\ICodegenFactory::codegenClassConstantf()




Create a class constant using a %-placeholder format string for the
constant name




``` Hack
public function codegenClassConstantf(
  HH\Lib\Str\SprintfFormatString $format,
  mixed ...$args,
): Facebook\HackCodegen\CodegenClassConstant;
```




## Parameters




- ` HH\Lib\Str\SprintfFormatString $format `
- ` mixed ...$args `




## Returns




+ [` Facebook\HackCodegen\CodegenClassConstant `](<class.Facebook.HackCodegen.CodegenClassConstant.md>)