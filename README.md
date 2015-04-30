# ME.Macros
Unity 3D Macros System

## Features

1. Source macros in scripts files
2. Source macros in text files

## Using

In any file (text or script) declare macros:
'''
#region source macros MACROSNAME
var anyCode = 0;
++anyCode;
#endregion
'''

In any file (where you want to use it):
'''
#region macros MACROSNAME
#endregion
'''