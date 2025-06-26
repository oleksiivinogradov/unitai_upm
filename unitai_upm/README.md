# UnitAI for Unity Editor

AI-powered assistant for the Unity Editor, providing code generation, chat, and project-aware features directly inside Unity.

---

**⚠️ Proprietary Software: All rights reserved. Use, copying, or distribution is prohibited without written permission.**

---

## Features

- **Advanced AI Chat**: Interact with multiple AI models (Gemini, Ollama) in a dedicated Unity Editor window.
- **Codebase-Aware Context**: Attach files and entire directories via drag-and-drop. The AI can read and understand your project's code to provide highly relevant assistance.
- **Project Indexing & Search**: Create an index of your project files and use vector embeddings for semantic "codebase search" to find relevant code snippets.
- **Command Execution**: Empower the AI to run commands, such as reading GameObjects from the current scene or searching for files, to gather context dynamically.
- **Image Generation & Editing**: Use Imagen models to generate and edit images directly in the chat. Tools include cropping, color replacement, and dominant color analysis.
- **Rich Conversation History**: Save, load, and switch between conversations. Chat history can be included in prompts for follow-up questions.
- **Customizable Experience**: Configure system prompts, manage API keys, and adjust UI settings like font size through the Config window.
- **Session Cost Tracking**: Keep track of estimated and cumulative costs for your AI interactions when using priced models.

## Installation

1. **Via Unity Package Manager (UPM):**
   - Open Unity.
   - Go to **Window > Package Manager**.
   - Click the **"+"** button and select **"Add package from git URL..."**
   - Enter the GitHub URL with the correct path and tag, e.g.:
     ```
     https://github.com/oleksiivinogradov/unitai_upm.git?path=unitai_upm#latest
     ```

## Usage

- **Main Window**: **Window > UnitAI > Agent**
- **Configuration**: **Window > UnitAI > Config**

### Agent Window (`Window > UnitAI > Agent`)

This is the main interface for interacting with the AI.

#### Header Controls

-   **Logo & Version**: Displays the UnitAI logo and the current package version.
-   **Font Size (+/-)**: Increase or decrease the font size for the entire chat window for better readability.
-   **Support (?)**: Opens a link to the official support channel.

#### Chat Interface

-   **Model Selector**: A dropdown menu to select the active AI model. It shows the source (e.g., UnitAI, Ollama), model size, and context window size.
-   **Include History**: A toggle to control whether the previous messages in the current conversation are included in the context for the next prompt. This is automatically disabled for Imagen models.
-   **Token Counter**: Displays the estimated token count for the current prompt (`~{used}/{total} M tokens`). The color changes to red if the context exceeds the model's limit.
-   **Estimated Cost**: Shows an estimated cost for the next API call based on the selected model's pricing.
-   **Conversation Controls**:
    -   **New Chat (+)**: Starts a new, empty conversation.
    -   **History Menu**: Opens a dropdown listing recent conversations, allowing you to load a previous chat session.
-   **Chat Display**: The main area where the conversation with the AI is displayed.
    -   **User Messages**: Your prompts are shown in cyan.
    -   **Assistant Messages**: AI responses are shown in white.
    -   **Code Blocks**: Automatically detected and rendered with syntax highlighting, a copy button, and the source file name/line numbers if found in the project.
    -   **Generated Images**: Images from Imagen models are displayed directly in the chat, with tools for cropping and color editing.
-   **File Attachment Area**:
    -   **Permanent Attach**: A dedicated slot on the left to drag-and-drop a single file that will be included in the *first* message of every new conversation. Useful for a main script or design document.
    -   **Regular Attachments**: The main area on the right where you can drag-and-drop multiple files and directories to be included in the context of your *next* prompt.
-   **Input Area**:
    -   A multi-line text area for composing your prompts. Pressing `Enter` sends the message, `Shift+Enter` creates a new line.
    -   **Send Button**: Sends the composed message and any attached files to the AI.

### Config Window (`Window > UnitAI > Config`)

This window allows you to configure UnitAI's settings and manage project-specific data.

#### API & System Settings

-   **User API Key**: Input field for your UnitAI Pro API key, which enables access to premium models and features.
-   **Subscription**: A read-only indicator showing if your API key corresponds to an active subscription.
-   **System Prompt**: A text area where you can define instructions for the AI to follow. This prompt is included with every request to guide the AI's behavior, tone, and expertise.

#### Codebase Search Tools

-   **Refresh Index**: Scans your project's `Assets` folder and creates a file index. This is required for codebase-aware features. The button shows the total number of indexed files.
-   **Sync Codebase**: Processes the indexed files to create vector embeddings. These embeddings allow the AI to perform fast, semantic searches across your entire codebase using the `unitai_codebase_search` command.
-   **Stop**: Halts the ongoing indexing or embedding process.

## Requirements

- Unity 2021.3 or later (tested with Unity 6000.1.2f1)
- .NET Standard 2.1+ support
- (Optional) Ollama access for external models

## License

**Copyright (c) 2024 Oleksii Vynogradov**

All rights reserved.

This software and its source code are the exclusive property of Oleksii Vynogradov. No part of this software may be used, copied, modified, merged, published, distributed, sublicensed, or sold in any form or by any means, in whole or in part, without the prior written permission of the copyright holder.

For inquiries regarding licensing, please contact: alex@unitai.net 