<!--
Copyright (c) 2023 Boston Dynamics, Inc.  All rights reserved.

Downloading, reproducing, distributing or otherwise using the SDK Software
is subject to the terms and conditions of the Boston Dynamics Software
Development Kit License (20191101-BDSDK-SL).
-->

# Boston Dynamics API - C++

The C++ SDK includes C++ libraries and examples.

## Coding standards and dependencies.

The C++ implementation follows these requirements:

- A modern C++14 compiler toolchain.
- Does not make use of exceptions or RTTI.
- Generally complies with the Google C++ style guide.
- Doxygen-friendly comments, particularly in header files.

Library Dependencies:

- C++14 standard library. Many advanced features, such as functional programming and concurrency support are used.
- Google's gRPC C++ library, as well as it's transitive dependencies.
- Unit tests depend on gTest.
- Eigen for math operations

## Contents

- [Client](https://github.com/bdaiinstitute/spot-cpp-sdk/tree/ros2/cpp/bosdyn/client)
- [Common](https://github.com/bdaiinstitute/spot-cpp-sdk/tree/ros2/cpp/bosdyn/common)
- [Math](https://github.com/bdaiinstitute/spot-cpp-sdk/tree/ros2/cpp/bosdyn/math)
