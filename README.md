# Expo build ios error

Issue: <https://github.com/expo/expo/issues/26942>

```bash
Compiling react-native Pods/React-rendererdebug » DebugStringConvertible.cpp

❌  (ios/Pods/Headers/Public/RCT-Folly/folly/functional/Invoke.h:22:10)

  20 | #include <type_traits>
  21 | 
> 22 | #include <boost/preprocessor/control/expr_iif.hpp>
     |          ^ 'boost/preprocessor/control/expr_iif.hpp' file not found
  23 | #include <boost/preprocessor/facilities/is_empty_variadic.hpp>
  24 | #include <boost/preprocessor/list/for_each.hpp>
  25 | #include <boost/preprocessor/logical/not.hpp>

› Compiling react-native Pods/React-perflogger » BridgeNativeModulePerfLogger.cpp
› Executing react-native Pods/hermes-engine » [CP] Copy XCFrameworks
› Packaging react-native Pods/React-perflogger » libReact-perflogger.a
› Packaging react-native Pods/React-debug » libReact-debug.a
› Compiling react-native Pods/ReactCommon » TurboModuleUtils.cpp
› Compiling react-native Pods/ReactCommon » TurboModulePerfLogger.cpp
› Compiling react-native Pods/ReactCommon » TurboModuleBinding.cpp
› Compiling react-native Pods/ReactCommon » TurboModule.cpp
› Packaging react-native Pods/React-nativeconfig » libReact-nativeconfig.a
› Compiling react-native Pods/Yoga » event.cpp
› Compiling react-native Pods/Yoga » Yoga.cpp
› Compiling react-native Pods/Yoga » YGValue.cpp
› Compiling react-native Pods/Yoga » YGEnums.cpp

› 1 error(s), and 0 warning(s)

CommandError: Failed to build iOS project. "xcodebuild" exited with error code 65.
error Command failed with exit code 1.
```
