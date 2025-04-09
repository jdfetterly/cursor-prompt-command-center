
# Testing & QA Prompting Cheat Sheet for Cursor (and Other AI Code Assistants)

Use this cheat sheet to generate tests, ensure app stability, and automate quality checks across your codebase—even if you're not a dedicated QA engineer.

---

## 1. Unit Testing Basics

**Prompt Examples:**
1. Write a unit test for this JavaScript function using Jest.
2. Add tests for edge cases in this utility function.
3. Mock dependencies when testing this service.
4. Ensure this function throws an error on invalid input.
5. Refactor this test to be more readable and DRY.
6. Use `beforeEach` and `afterEach` to reset state.
7. Create multiple test cases using a parameterized test.
8. Use `jest.fn()` to create a mock function.
9. Verify that a callback was called with specific arguments.
10. Group related tests using `describe` blocks.

---

## 2. Frontend Component Testing

**Prompt Examples:**
1. Write a test for this React component using React Testing Library.
2. Simulate a button click and verify it triggers a callback.
3. Assert that the loading spinner appears while data is fetching.
4. Test form input and submission behavior.
5. Mock API responses using `msw` or a mock server.
6. Check that an error message renders when the API fails.
7. Test that a modal opens and closes correctly.
8. Ensure the correct text is rendered for props passed in.
9. Use `screen.getByRole` or `getByLabelText` for accessibility.
10. Clean up after tests with `cleanup()` if needed.

---

## 3. Integration Testing

**Prompt Examples:**
1. Test that the user login flow works from form to redirect.
2. Simulate user interactions across multiple components.
3. Test a form that saves data and updates the UI.
4. Ensure that the app loads initial data from the backend.
5. Verify that protected routes redirect unauthenticated users.
6. Mock backend API calls while preserving real UI behavior.
7. Use a test database for end-to-end logic validation.
8. Set up a test environment that mimics production config.
9. Simulate a full data fetch, mutation, and UI update.
10. Add integration tests for this shopping cart workflow.

---

## 4. End-to-End (E2E) Testing

**Prompt Examples:**
1. Write a Playwright test that visits the homepage and checks for key elements.
2. Test the signup form flow with real browser automation.
3. Wait for elements to load using Playwright’s `waitFor` utilities.
4. Take a screenshot after each step for visual verification.
5. Simulate mobile device testing using viewport options.
6. Use Playwright to test login and logout flow.
7. Navigate through a multistep form and verify results.
8. Use data-testid attributes to select elements reliably.
9. Test that a user can add and remove items from a list.
10. Run the full checkout flow in staging environment.

---

## 5. Code Coverage & Reporting

**Prompt Examples:**
1. Generate a code coverage report using Jest.
2. Add coverage thresholds to ensure test completeness.
3. Highlight untested lines in the report.
4. Upload coverage reports to Codecov or Coveralls.
5. Exclude config files or mocks from coverage.
6. Show only uncovered lines in terminal output.
7. Integrate coverage checks into CI workflow.
8. Add a badge to the README for coverage status.
9. Create a summary of tested vs. untested files.
10. Track coverage changes between PRs.

---

## 6. Accessibility & Performance Testing

**Prompt Examples:**
1. Run an accessibility audit using Lighthouse or Axe.
2. Highlight all elements failing WCAG contrast requirements.
3. Test for missing `aria` labels or roles.
4. Check tab order and keyboard navigation.
5. Simulate screen reader behavior for critical components.
6. Audit image alt text and link text clarity.
7. Generate a performance report with load time breakdown.
8. Simulate throttled network and CPU environments.
9. Capture largest contentful paint and time to interactive.
10. Flag render-blocking resources or large JS bundles.

---

## 7. CI & Automation for QA

**Prompt Examples:**
1. Add test and lint steps to the GitHub Actions pipeline.
2. Run unit tests on every pull request.
3. Run Playwright tests on deploy to staging.
4. Notify the team in Slack when tests fail in CI.
5. Use a test matrix to run across multiple environments.
6. Stop deployment if coverage drops below 80%.
7. Retry flaky tests with exponential backoff.
8. Run smoke tests post-deployment automatically.
9. Include test summary in pull request description.
10. Run visual diff tests between staging and production.

---

## Quick Reference: Test Types & Tools

| Type            | Tools / Libraries                        |
|------------------|------------------------------------------|
| Unit             | Jest, Vitest, Mocha, Chai                |
| Component (UI)   | React Testing Library, Cypress           |
| Integration      | Jest, Supertest, MSW                     |
| E2E              | Playwright, Cypress                      |
| Coverage         | Istanbul, NYC, Codecov                   |
| Accessibility    | Axe, Lighthouse                          |
| Automation       | GitHub Actions, GitLab CI                |

---

This cheat sheet helps you work with AI to write better tests, catch bugs early, and ensure a smooth user experience across environments.
