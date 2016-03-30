# Format JS cli

binary to run the nuclide-format-js-base formatter

# Arguments
* `--row x` The row of the cursor position
* `--col x` The column of the cursor position
* `--builtins Promise,setTimeout` Any built-ins to ignore when adding requires. CSV.
* `--builtintypes Promise,ReactClass` Any built-in types to ignore when adding type includes. CSV.
* `--aliases Original,NewName` Pairs of types where the first in the pair is the name in code, and the second is what it will be required as. CSV pairs.
