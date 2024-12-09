# JavaScript Loose Equality with Null and Undefined

This repository demonstrates a common error in JavaScript: using loose equality (`==`) when comparing for `null` or `undefined`.  The use of loose equality can lead to unexpected behavior.  The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version using strict equality (`===`).

**Problem:** In JavaScript, `null == 0` evaluates to `false`, but `null == null` evaluates to `true`. This inconsistency can make null checks unreliable.

**Solution:** Use strict equality (`===`) for comparisons.  Strict equality checks both the value and the type, avoiding unexpected type coercion.

This example highlights the importance of understanding JavaScript's type system and choosing appropriate comparison operators to prevent subtle and hard-to-find errors. 