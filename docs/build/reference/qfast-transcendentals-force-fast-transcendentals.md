---
title: "/Qfast_transcendentals (Force Fast Transcendentals)"
ms.date: "11/04/2016"
f1_keywords: ["/Qfast_transcendentals"]
helpviewer_keywords: ["/Qfast_transcendentals", "Force Fast Transcendentals"]
ms.assetid: 4de24bd1-38e6-49d4-9a05-04c9937d24ac
---
# /Qfast_transcendentals (Force Fast Transcendentals)

Generates inline code for transcendental functions.

## Syntax

```
/Qfast_transcendentals
```

## Remarks

This compiler option forces transcendental functions to be converted to inline code to improve execution speed. This option has an effect only when paired with **/fp:except** or **/fp:precise**. Generating inline code for transcendental functions is already the default behavior under **/fp:fast**.

This option is incompatible with **/fp:strict**. See [/fp (Specify Floating-Point Behavior)](../../build/reference/fp-specify-floating-point-behavior.md) for more information about floating point compiler options.

### To set this compiler option in the Visual Studio development environment

1. Open the project's **Property Pages** dialog box. For details, see [Working with Project Properties](../../ide/working-with-project-properties.md).

1. Click the **C/C++** folder.

1. Click the **Command Line** property page.

1. Type the compiler option in the **Additional Options** box.

### To set this compiler option programmatically

- See <xref:Microsoft.VisualStudio.VCProjectEngine.VCCLCompilerTool.AdditionalOptions%2A>.

## See Also

[/Q Options (Low-Level Operations)](../../build/reference/q-options-low-level-operations.md)<br/>
[Compiler Options](../../build/reference/compiler-options.md)<br/>
[Setting Compiler Options](../../build/reference/setting-compiler-options.md)