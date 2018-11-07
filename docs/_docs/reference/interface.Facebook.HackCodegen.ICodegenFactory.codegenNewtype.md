
***

layout: docs
title: codegenNewtype
permalink: /docs/reference/interface.Facebook.HackCodegen.ICodegenFactory.codegenNewtype.md
---







# Facebook\\HackCodegen\\ICodegenFactory::codegenNewtype()




Generate a ` newtype ` declaration




``` Hack
public function codegenNewtype(
  string $name,
): Facebook\HackCodegen\CodegenType;
```




This is an opaque type alias, with the underlying type only visible
to the current file.




## Parameters




- ` string $name `




## Returns




+ [` Facebook\HackCodegen\CodegenType `](<class.Facebook.HackCodegen.CodegenType.md>)