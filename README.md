# Report Writing Templates

This repo contains a collection of prompt templates to assist with writing high-quality vulnerability reports using AI language models like GPT-4. The templates are designed to produce reports that are easy to generate, easy to follow, use organic language, and maintain good writing quality.

The recommended setup is [Cursor](https://www.cursor.com/) with [Claude 3 Opus](https://docs.cursor.com/advanced/model-toggle) (you'll need a Pro subscription for that).

## Templates

### Cantina
- `Minimal.md`: Standard minimal template for Low severity issues
- `Minimal with POC.md`: Minimal template for simple High/Medium severity issues that require a PoC
- `Detailed with POC.md`: Detailed template for more complex High/Medium severity issues
  
### Code4rena
- `HM.md`: Template for High/Medium severity issues 
- `QA.md`: Template for Low severity / QA issues

### Codehawks
- `Report.md`: Standard template for vulnerability reports

### Immunefi
- `Report.md`: Standard template for vulnerability reports

### Sherlock
- `HM.md`: Template for High/Medium severity issues

### Follow-up Templates 
- `Follow-up list steps in test.md`: Summarize a coded POC into a list of steps
- `Block comments follow-up.md`: Get the previous LLM reply formatted in a code block

## Usage

1. Leave detailed inline comments on potential vulnerabilities during your code review
2. In your IDE, select the comment and use an AI assistant tool to start a new chat 
3. Copy-paste the appropriate template and add any additional context the AI may need
4. Iterate on the AI's output to refine the report details
5. Manually review and edit the final report, adding missing context and correcting any errors

Treat the AI's output as a starting point, not a final product. Always verify the reasoning, POC, and other details yourself before submitting.

See [this X thread](https://x.com/0xEV_om/status/1803303530213810639) for more details.

## Contributing 

Contributions to improve these templates or add new ones are welcome! Please open a pull request with your changes.
