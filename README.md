# Objective-C Memory Management Bug: Improper retain/release

This repository demonstrates a common Objective-C bug related to memory management.  Specifically, improper use of `retain` and `release` within the `dealloc` method can lead to memory leaks or crashes.

The `bug.m` file shows the buggy code, while `bugSolution.m` provides the corrected version.

## Bug Description
The bug arises from an incorrect handling of memory allocation for `myString`. The fix is shown in `bugSolution.m`.