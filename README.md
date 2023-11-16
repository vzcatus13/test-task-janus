# Description

### Task:

Develop a class CancelablePromise that behaves similarly to the native Promise class in JavaScript but with the capability to cancel the entire promise chain before execution.

### What has been done:

Was written [CancelablePromise](./cancelable-promise.js) class which:

1. Ensures the constructor handles incorrect arguments and throws errors.
2. Implements the creation of a cancelable promise with the provided callback function.
3. Implements then() method.
4. Implements cancel() method.
5. Implements catch() method.
6. Implements the isCanceled property and ensures it reflects the cancellation state.
7. Utilizes the provided test cases to verify the correctness of implementation.

# How to Test Locally

### Requirements:

- Node.js v.20 or above

---

1. Install dependencies

   > npm i

2. Run Jest test

   > npx jest
