### GPT Prompt Engineering

In prompt engineering, creating effective prompts involves considering various components to guide the AI model in generating desired outputs. Below are the key components to consider:

#### Components of the Prompts

1. **Context**
2. **Task**
3. **Exemplar**
4. **Persona**
5. **Format**
6. **Tone**

Note: Context and Task are mandatory components, while Exemplar and Persona are important but optional. Format and Tone can enhance the effectiveness of the prompt.

#### Prompt Syntax

The ideal prompt structure follows this syntax:

`Persona + Context + Task + Exemplar + Format + Tone`

Important components: Context + Task + Exemplar + Tone

#### Task

Tasks should begin with action verbs to clearly specify the desired action for the AI model. Examples include:

- Generate a 3-month Training Program
- Analyze the feedback provided by the team

#### Context

Provide necessary background information for the prompt. Consider:

- User background
- Definition of success
- User environment

#### Exemplar

Include examples within the prompt to guide the model. Use tested use case outputs or alternative solutions. For instance:

In a hiring context, specify inputs and include well-crafted job descriptions to structure the output effectively.

#### Persona

Introduce the desired persona to the model. This sets the tone and direction of the conversation. Examples include:

- Act like an Investor
- Assume the role of a Hiring Manager

#### Format

Specify the desired format for the output. This could be in JSON, plain text, or other formats such as email or markdown.

#### Tone

Indicate the tone of the conversation, whether casual or formal, to guide the model appropriately. Use keywords to convey the desired tone effectively. For example, specify keywords to help the GPT model understand the tone of the conversation.

By considering and incorporating these components effectively, you can craft prompts that yield more accurate and relevant outputs from the GPT model.

#### GPT API's Syntax

Roles in GPT API prompts

- System - Persona + context
- User - Task + Tone
- Assistant - Exemplar + Format

Key Points to consider in API Design

- Temperature.
  Low - To derive more concentrated and deterministic output
  High - To get more imaginative
- Response Length - Depends on the model
- Roles - System, user and Assistant
