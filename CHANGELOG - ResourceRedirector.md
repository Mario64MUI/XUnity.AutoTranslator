﻿### 1.2.1
 * MISC - Improved logging statements for redirection subscriptions allowing for less spam

### 1.2.0
 * FEATURE - Support callbacks for asset bundles loaded from streams

### 1.1.3
 * BUG FIX - Fixed bug that caused the GetBuiltinResource to not be found on later versions of the Unity Engine. Thanks to aqie13 on GitHub

### 1.1.2
 * MISC - Internal API changes - some code moved to XUnity.Common

### 1.1.1
 * BUG FIX - Development-time fix to the nuget package
 * BUG FIX - Fixed bug in method 'LoadFromFileWithRandomizedCabIfRequired' where offset was ignored if the initial load attempt failed

### 1.1.0
 * FEATURE - Added method to load an asset from a file, with fallback to loading it from an in-memory stream with randomized CAB
 * FEATURE - Added support for postfix hooks on AssetBundle loads
 * FEATURE - Added hook for 'LoadFromMemory' and 'LoadFromMemoryAsync' when loading asset bundles

### 1.0.1
 * MISC - Support for UnityEngine version 2018.2 and lower

### 1.0.0
 * Initial release
