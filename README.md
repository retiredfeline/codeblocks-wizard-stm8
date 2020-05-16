# stm8 wizard for code::blocks

Copy the directory stm8 to the wizard directory of code::blocks.

Add this entry:


```
RegisterWizard(wizProject,     _T("stm8"),         _T("STM8 Project"),         _T("Embedded Systems"));
```

after the entry for mcs51.
