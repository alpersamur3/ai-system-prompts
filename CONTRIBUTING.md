# Contributing to AI System Prompts

Thank you for your interest in contributing to this repository! This project archives leaked system prompts from AI models for research and educational purposes.

## 🚨 Important Notice

This repository deals with sensitive information. Please ensure you:
- Have obtained the system prompts through legitimate means
- Are not violating any terms of service
- Understand the legal implications in your jurisdiction
- Are contributing for research/educational purposes only

## 📋 Contribution Guidelines

### Required Elements for All Submissions

Every contribution must include:

1. **Valid Proof** (at least one of the following):
   - Direct chat URL that can be accessed publicly
   - Clear screenshots showing the prompt extraction
   - Verifiable evidence of the system prompt leak

2. **Complete Information**:
   - AI model name and version (if known)
   - Date of extraction
   - Method used to obtain the prompt
   - Any relevant context

3. **Proper Organization**:
   - Follow the existing directory structure
   - Use appropriate file naming conventions
   - Include README.md updates

### Submission Process

1. **Fork the Repository**
   ```bash
   git fork https://github.com/alpersamur3/ai-system-prompts
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b add-[company]-[model]
   ```

3. **Follow the Directory Structure**
   ```
   CompanyName/
   ├── README.md
   ├── model-name.md
   └── proof-image.jpg (if applicable)
   ```

4. **File Naming Conventions**
   - Use kebab-case for filenames: `model-name.md`
   - Company directories use PascalCase: `CompanyName/`
   - Proof images should be descriptive: `model-proof.jpg`

### Content Standards

#### System Prompt Files (.md)
```markdown
# [Model Name] System Prompt

**Date Extracted:** YYYY-MM-DD
**Method:** [How the prompt was obtained]
**Verified:** [Yes/No - if independently verified]

## System Prompt

[The actual system prompt content here]

## Proof

[Link to proof or reference to accompanying evidence]

## Notes

[Any additional context or observations]
```

#### README.md in Company Directories
- List all models with brief descriptions
- Include verification status
- Provide context about extraction methods
- Link to proof materials

### Adding New Companies

When adding a new AI company directory:

1. Create the directory with PascalCase naming
2. Add a comprehensive README.md
3. Update the main repository README.md
4. Ensure the company has publicly known AI models

### Proof Requirements

#### Acceptable Proof Types:
- **Chat URLs**: Must be publicly accessible and show the prompt extraction
- **Screenshots**: Must clearly show the AI model responding with its system prompt
- **Screen Recordings**: For complex extraction methods
- **API Responses**: If obtained through legitimate API access

#### Unacceptable Submissions:
- ❌ No proof provided
- ❌ Proof that can't be independently verified
- ❌ Content that violates terms of service
- ❌ Fabricated or modified prompts
- ❌ Incomplete or unclear evidence

### Review Process

1. **Initial Review**: Maintainers check for required elements
2. **Verification**: Proof is validated when possible
3. **Technical Review**: Content is checked for accuracy
4. **Approval**: Pull request is merged or feedback is provided

### Quality Standards

- **Accuracy**: Prompts must be exact and unmodified
- **Completeness**: Include full context and metadata
- **Clarity**: Documentation should be clear and well-formatted
- **Originality**: No duplicate submissions

## 🔒 Security Considerations

- Never include personal information in submissions
- Redact any sensitive data from screenshots
- Be mindful of potential security implications
- Report any concerning findings responsibly

## 📞 Getting Help

- Open an issue for questions about the contribution process
- Use discussions for general questions about AI system prompts
- Contact maintainers for sensitive security-related matters

## 📜 Legal Disclaimer

Contributors are responsible for ensuring their submissions comply with:
- Applicable laws in their jurisdiction
- Terms of service of the respective AI providers
- Ethical guidelines for AI research

By contributing, you confirm that:
- You have the right to submit the content
- Your submission is for research/educational purposes
- You understand the potential legal implications

## 🙏 Recognition

All contributors are appreciated! Significant contributions will be acknowledged in the repository.

---

*This project is for research and educational purposes only. Please use responsibly.*