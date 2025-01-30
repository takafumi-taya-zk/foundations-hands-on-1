# Instructions for Running Tests

## Overview
This document provides guidelines for running tests in this project. Please follow the instructions carefully to ensure consistency and accuracy in testing.

## Prerequisites
Before running the tests, ensure you have met the following requirements:
- You have installed all necessary dependencies.
- You have set up the project environment correctly.

## Test Guidelines
- **Do not use Mockito**: Ensure that no tests are written using the Mockito framework.
- **Test Method Naming Convention**: Name your test methods in the following format:

For example:
- `testCalculateSum_norm_correctInput`
- `testCalculateSum_anom_nullInput`
- `testCalculateSum_boun_lengthIs0`

## Running Tests
To run the tests, follow these steps:

1. Navigate to the project directory:
  ```bash
  cd your-project-directory
  ```

2. Execute the tests using the following command:
  ```bash
  ./tests
  ```

## Contributing to Tests
To contribute to the test suite, follow these steps:

1. Create a new branch for your test:
  ```bash
  git checkout -b add-new-test
  ```

2. Write your test cases following the guidelines mentioned above.

3. Commit your changes:
  ```bash
  git commit -m 'Add new test cases for <feature>'
  ```

4. Push to the branch:
  ```bash
  git push origin add-new-test
  ```

5. Create a pull request for review.

## Contact
If you have any questions or need further assistance, please open an issue in the repository or contact the project maintainer.
