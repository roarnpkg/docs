# Introducing EzImport

Importing packages with Roarn may be annoying with constant going back and fourth to `roarn_modules` which is why we created something called **EzImport**.

## What is EzImport?

EzImport is a light bundled package that comes with Roarn projects to maximize your workspace when importing items. Using EzImport itself won't require that much of an effort with our VSCode extension which we will touch on more later.

## How to use EzImport?

To use EzImport you will have to first require it with the `Roarn` module on `roarn_modules`.

This is as simple as doing this:

```Lua
local import = require(game.ReplicatedStorage.roarn_modules.Roarn)

local roarnInitials = import("roarnInitials")
```

Its as simple as that!

Okay, but now you may think that its annoying to always require the Roarn module right?

Thats where our VSCode extension come in.

## Using VSCode with EzImport

With our VSCode extension you can start typing `import` on a Luau file and it will already fill it out for you!
