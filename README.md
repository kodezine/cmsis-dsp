# cmsis-dsp
Precompiled CMSIS DSP object library for STM32H743XI processors

## Make packages

The following is an example for CPacking Clang 'STM32F031K6'
```
$ clang --preset CPack_Clang_STM32F031K6
$ clang --build preset CPack_Clang_STM32F031K6 --target package
```

The following is an example for CPacking Clang 'STM32H7A3ZI'
```
$ clang --preset CPack_Clang_STM32H7A3ZI
$ clang --build preset CPack_Clang_STM32H7A3ZI --target package
```

The following is an example for CPacking Clang 'STM32H743XI'
```
$ clang --preset CPack_Clang_STM32H743XI
$ clang --build preset CPack_Clang_STM32H743XI --target package
```
