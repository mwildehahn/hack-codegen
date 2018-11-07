
***

layout: docs
title: appendToBuilderBase
permalink: /docs/reference/class.Facebook.HackCodegen.CodegenFunctionish.appendToBuilderBase.md
---







# Facebook\\HackCodegen\\CodegenFunctionish::appendToBuilderBase()




$is_abstract and $containing_class_name
only valid for CodegenMethodX for code reuse purposes




``` Hack
protected function appendToBuilderBase(
  Facebook\HackCodegen\HackBuilder $builder,
  string $func_declaration,
  bool $is_abstract = false,
  string $containing_class_name = '',
): Facebook\HackCodegen\HackBuilder;
```




## Parameters




- [` Facebook\HackCodegen\HackBuilder `](<class.Facebook.HackCodegen.HackBuilder.md>)`` $builder ``
- ` string $func_declaration `
- ` bool $is_abstract = false `
- ` string $containing_class_name = '' `




## Returns




+ [` Facebook\HackCodegen\HackBuilder `](<class.Facebook.HackCodegen.HackBuilder.md>)