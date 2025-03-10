---
title: Yes or no choice
titleTemplate: ":title · Prompts · Noora · Tuist"
description: A component that prompts the user to answer a yes or no question.
---

# Yes or no choice

This component prompts the user to answer a yes or no question.

| Property | Value |
| --- | --- |
| Interactivity | Required (fails otherwise) |

## Demo

![A gif that shows the component in action. The developer uses the key strokes left and right to change their answer from yes to no](/components/prompts/yes-or-no-choice.gif)

## API

### Example

```swift
Noora().yesOrNoChoicePrompt(
  title: "Authentication",
  question: "Would you like to authenticate?",
  defaultAnswer: true,
  description: "Authentication is required to use some CLI features."
)
```

### Options

| Attribute | Description | Required | Default value |
| --- | --- | --- | --- |
| `title` | The title of the prompt. | No | |
| `question` | The question that the user will answer. | Yes | |
| `defaultAnswer` | The default answer. | No | `true` |
| `description` | A description that provides more context about the question. | No | |
| `collapseOnSelection` | Whether the prompt should collapse after the user selects an option. | No | `true` |
