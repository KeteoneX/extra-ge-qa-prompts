
# Prompt Name
Exploratory Testing Prompt for extra.ge

## Purpose
This prompt helps generate structured exploratory testing ideas for features and user flows in the extra.ge e-commerce platform. It is designed to support risk-based investigation, uncover unexpected issues, and identify usability, functional, and integration problems that may not be covered by predefined test cases.

## When to Use
Use this prompt when:
- a new feature needs exploratory testing
- you want to investigate a page or flow without relying only on predefined test cases
- you need to identify hidden risks and unexpected behaviors
- regression testing needs additional exploratory coverage
- you want to validate real user behavior across connected flows

## Prompt
You are a Senior QA Engineer performing exploratory testing on extra.ge, an e-commerce web application.

Analyze the feature, page, or user flow described below and create a structured exploratory testing charter.

Your goal is to think like a real user and an experienced QA engineer at the same time. Do not only focus on expected behavior. Focus on discovering hidden issues, risky areas, inconsistent states, weak validations, broken flows, and usability problems.

Focus on the following areas:

- unusual user behavior
- invalid and unexpected inputs
- incomplete actions
- interrupted flows
- navigation issues
- session-related issues
- UI/UX inconsistencies
- data inconsistencies
- error handling
- page refresh behavior
- browser back/forward behavior
- responsive behavior
- integration with connected features
- edge cases and state transitions

While analyzing, consider the extra.ge e-commerce context where applicable, including:
- product listing
- product details page
- search and filters
- cart behavior
- checkout flow
- login and registration
- favorites/wishlist
- pricing and discounts
- stock-related behavior
- form validation
- order summary
- user session state

Feature, page, or flow to explore:
[PASTE FEATURE OR PAGE DESCRIPTION HERE]

If available, also consider:
- user type
- test environment
- browser/device
- known issues
- acceptance criteria
- dependencies with other modules

## Expected Output
Provide the result in the following structure:

### 1. Testing Mission
Define the main exploratory goal.

### 2. Key Risk Areas
List the most important risky areas that need investigation.

### 3. Exploratory Scenarios
Provide practical exploratory scenarios to execute, covering normal, negative, and edge behaviors.

### 4. Questions to Investigate
List important questions a QA engineer should answer during testing.

### 5. Potential Bugs to Watch For
List the types of issues that are likely to appear in this area.

### 6. Related Functional Areas to Check
Mention connected modules or pages that may also be affected.

### 7. Recommended Follow-Up Actions
Suggest what should be tested next if issues are found.

## Suggested Input
Use the following information when available:
- feature name
- page name
- user flow
- acceptance criteria
- environment
- browser/device
- related modules
- known risks

## Notes
- Think beyond predefined test cases.
- Focus on realistic user behavior and risky interactions.
- Consider both functional defects and usability issues.
- Treat the feature as part of a larger e-commerce journey, not as an isolated page.
- Pay special attention to flows that affect cart, checkout, pricing, and user decisions.
