# ME.Macros
Unity 3D Macros System

## Features

1. Source macros in scripts files
2. Source macros in text files

## Using

In any file (text or script) declare macros:
```C#
#region source macros MACROSNAME
var anyCode = 0;
++anyCode;
#endregion
```

In any file (where you want to use it):
```C#
#region macros MACROSNAME
#endregion
```

Result:
```C#
#region macros MACROSNAME
/* This code is auto-generated
 * Do not change it
 */
var anyCode = 0;
++anyCode;
#endregion
```
