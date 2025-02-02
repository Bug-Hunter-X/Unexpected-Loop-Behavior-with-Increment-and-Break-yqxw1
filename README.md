# Java Loop Bug: Increment Operator Placement and Break Statement

This repository demonstrates a common subtle bug in Java loops involving the increment operator's placement and the use of a `break` statement.

The `BuggyLoop.java` file contains the buggy code.  The `FixedLoop.java` file provides the corrected version.

The problem lies in the interaction between the post-increment operator (`i++`) and the `break` statement. The unexpected behavior is demonstrated in the `BuggyLoop.java` file's output.