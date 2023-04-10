# quick_hash_comparison

This is a python function that simply verifies if the hash of an update file matches the original update file. This could be used to prevent for example supply chain attacks, if the infrastructures of the client are properly configured.

This function takes 3 arguments:

-"update_file": Which is the path to the file you want to check out.
-"original_file": The path to the original, unmodified file.
-"hash_value": The expected SHA-256 hash value of the update file

The function computes the hash of the update file and verifies if it matches the expected value. If it does not match, it returns "False".
