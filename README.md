# AI-Framework

A prompt injection architecture that transforms AI assistants from solution generators into collaborative problem-solving partners.

## Overview

The AI-Framework operates as a behavioral enhancement layer that injects collaboration rules without modifying underlying AI systems. It uses file-based rule placement to transform AI behavior into thoughtful, collaborative problem-solving.

## Architecture

### Prompt Injection Pattern
- **Injection Vector**: File-based rule placement (`00-rules.md`)
- **Behavioral Payload**: Rule-driven modification specifications
- **Activation**: Automatic loading by AI systems
- **Scope**: Complete behavioral transformation to collaborative partner

### Core Features
- **Confidence-Based Interaction**: Evidence-based confidence assessment (70% baseline)
- **Solution Optimization**: Multiple alternatives exploration before implementation
- **Chain-of-Thought Cycles**: Systematic problem-solving approach
- **Context Preservation**: Maintains state across iterations
- **Quality Validation**: Built-in validation framework

## Installation

### Cross-Platform Support
Place `00-rules.md` in the appropriate directory for your AI tool:

- **Roo Code**: `.roo/rules/00-rules.md`
- **Cline**: `.clinerules/00-rules.md`
- **Cursor**: `.cursor/rules/00-rules.md`
- **Claude**: `claude.md`

## Usage

Once installed, the framework automatically modifies AI behavior to:

1. **Collaborative Problem-Solving**: AI becomes a thinking partner, not just solution provider
2. **Confidence-Based Interaction**: 
   - ≥90%: Proceed independently
   - 70-89%: Seek clarity, provide reasoning
   - <70%: Require human collaboration
3. **Solution Optimization**: Explore alternatives before implementing
4. **Quality Focus**: Validate solutions against requirements

## Framework Evolution

- **V1**: Verbose foundation with basic collaboration patterns
- **V2**: Conciseness focus, streamlined communication
- **V3**: Evidence-based confidence assessment
- **V4**: Solution optimization factors, over-engineering prevention
- **Current**: Refined cycle system, natural confidence integration

## Philosophy

**Thoughtful collaboration over rapid solution generation**

The framework emphasizes exploring alternatives and optimizing solutions before implementation, preventing the common AI tendency to rush to the first viable solution.

## License

MIT License - see LICENSE file for details.

## Contributing

This framework evolves through real-world usage and feedback. Contributions that improve collaboration effectiveness are welcome.