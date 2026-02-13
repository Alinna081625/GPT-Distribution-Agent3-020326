You will be creating a comprehensive prompt for OPAL/Google to build an application. You will receive two inputs: a user's app description and a detailed technical specification.

Here is the user's app description:

<app_description>
{{APP_DESCRIPTION}}
</app_description>

Here is the technical specification:

<technical_spec>
{{TECHNICAL_SPEC}}
</technical_spec>

Your task is to synthesize these two inputs into a clear, comprehensive prompt that OPAL/Google can use to build the application. The prompt should be structured to guide the development process effectively.

Before writing the final prompt, use the scratchpad below to:
1. Identify the core purpose and key features from the app description
2. Extract critical technical requirements from the specification
3. Identify any gaps or ambiguities that need clarification
4. Plan the structure of your prompt

<scratchpad>
[Your analysis and planning here]
</scratchpad>

Now write a comprehensive prompt for OPAL/Google. Your prompt should include:

1. **Application Overview**: A clear summary of what the app does and its primary purpose
2. **Core Requirements**: Essential features and capabilities the app must have
3. **Technical Architecture**: Key technical components, frameworks, and deployment specifications
4. **UI/UX Requirements**: Visual design, layout, user interaction patterns, and accessibility features
5. **Data Management**: How data should be handled, stored, and processed
6. **Security & Privacy**: API key management, data handling policies, and user privacy considerations
7. **Feature Specifications**: Detailed descriptions of each major feature and how it should work
8. **Integration Points**: How different components should work together
9. **Error Handling**: Expected failure scenarios and how to handle them
10. **Testing Criteria**: Key acceptance tests to validate the application works correctly
11. **Constraints & Limitations**: Known limitations and what is out of scope
12. **Implementation Priorities**: What should be built first vs. what can come later

Structure your prompt so that it is:
- Clear and unambiguous
- Actionable for developers
- Comprehensive enough to build the full application
- Organized logically with clear sections
- Specific about technical choices (frameworks, libraries, deployment targets)

Write your complete prompt inside <prompt> tags. Make sure the prompt is self-contained and provides all necessary information for OPAL/Google to build the application without needing to reference the original inputs.

Your final output should contain only the prompt itself, ready to be used by OPAL/Google to build the application.
