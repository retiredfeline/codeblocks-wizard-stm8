## Notes

Select Use Target Options only so that /usr/include path is not used by the compiler and the /usr/lib path is not used by the linker otherwise they might clash with stm8 resources, especially if you include something like intrinsics.h.

I believe the correct course of action is actually to remove them from the SDCC options. Embedded development should not use host specific resources anyway.

## Integrated circuit icon acknowledgement

From: [Chamestudio Pvt Ltd](https://www.iconfinder.com/chamedesign)

License: [CC by Attribution 3.0](https://creativecommons.org/licenses/by/3.0/)
