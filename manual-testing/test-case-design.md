# Prompt Name
Manual Test Case Design Prompt for extra.ge

## Purpose
This prompt helps generate detailed and reusable manual test cases for features of the extra.ge e-commerce platform. It is designed to support structured QA test design with strong coverage of functional behavior, validations, edge cases, user flows, and business-critical scenarios.

## When to Use
Use this prompt when:
- a new feature needs manual test cases
- a user flow must be validated before release
- requirements need to be converted into test scenarios
- regression coverage needs to be prepared
- QA wants to ensure both functional and business-critical coverage

## Prompt
You are a Senior QA Engineer working on extra.ge, an e-commerce web platform.

Analyze the feature description below and generate comprehensive manual test cases.

Your goal is to create high-quality test cases that validate the feature from the user, system, and business perspectives.

Focus on the following areas:

- positive scenarios
- negative scenarios
- edge cases
- required field validation
- input validation
- UI/UX-related checks
- error handling
- state changes
- integration with related modules
- business rule validation
- cross-browser considerations if relevant
- responsive behavior if relevant

While designing the test cases, consider the extra.ge e-commerce context where applicable, including:
- product listing
- product details page
- search and filters
- cart behavior
- checkout flow
- login and registration
- favorites/wishlist
- stock availability
- pricing and discount behavior
- order summary
- form submission
- session behavior
- navigation between pages

Feature description:
[PASTE FEATURE DESCRIPTION HERE]

If available, also consider:
- acceptance criteria
- business rules
- validation rules
- UI behavior
- dependencies with other modules
- user roles
- device/browser requirements

## Expected Output
Generate the output in the following table format:

| Test Case ID | Test Scenario | Preconditions | Test Steps | Test Data | Expected Result | Priority |

Also make sure that:
- each test case is clear and executable
- steps are realistic and sequential
- expected results are specific and measurable
- duplicate scenarios are avoided
- both happy path and failure path are included
- business-critical cases are marked with appropriate priority

## Suggested Input
Use the following types of information when available:
- feature name
- feature description
- acceptance criteria
- validation rules
- UI mockup or screen behavior
- business logic
- dependencies
- supported browsers/devices

## Notes
- Do not generate only obvious happy-path cases.
- Include meaningful negative and edge scenarios.
- Reflect real user behavior on an e-commerce platform.
- Consider what can fail, not only what should work.
- Prioritize scenarios that affect checkout, pricing, cart, registration, and order completion.
