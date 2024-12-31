# PHP Silent File Reading Failure

This repository demonstrates a common, yet easily missed, error in PHP: the silent failure of `file_get_contents()` when the specified file does not exist. The function returns `false` in this case, but this is not always explicitly checked, leading to potential runtime errors or unexpected program behavior.

The `bug.php` file shows the problematic code. The `bugSolution.php` provides a corrected version with proper error handling.