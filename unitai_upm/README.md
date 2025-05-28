# UnitAI for Unity Editor

AI-powered assistant for the Unity Editor, providing code generation, chat, and project-aware features directly inside Unity.

---

**⚠️ Proprietary Software: All rights reserved. Use, copying, or distribution is prohibited without written permission.**

---

## Features

- **AI Chat Window**: Interact with advanced AI models (UnitAI, Ollama, OpenAI, Gemini) from a custom Unity Editor window.
- **Context-Aware Assistance**: Attach files or directories, include chat history, and optionally include active scene information for more relevant answers.
- **Model Selection**: Choose from multiple AI models, with context window and cost estimation.
- **Session Cost Tracking**: See estimated and cumulative costs for your AI interactions.
- **Drag & Drop**: Attach code, text, or markdown files for the AI to analyze.
- **Conversation History**: Start new conversations, switch between saved histories, and manage chat context.
- **Fine-Tuning Tools**: Index your project, build fine-tune datasets, and manage embeddings (via Config window).
- **Custom System Prompt**: Configure the AI's behavior and context via a system prompt.

## Installation

1. **Via Unity Package Manager (UPM):**
   - Open Unity.
   - Go to **Window > Package Manager**.
   - Click the **"+"** button and select **"Add package from git URL..."**
   - Enter the GitHub URL with the correct path and tag, e.g.:
     ```
     https://github.com/oleksiivinogradov/unitai_upm.git?path=unitai_upm#1.0.0
     ```

## Usage

- Open the main window: **Window > UnitAI > Agent**
- Open the config window: **Window > UnitAI > Config**
- Start chatting, attach files, and select models as needed.
- Use the **Config** window to set your API key, manage project indexing, and build fine-tune datasets.
- For advanced use, see the in-editor help and tooltips.

## Requirements

- Unity 2021.3 or later (tested with Unity 6000.1.2f1)
- .NET Standard 2.1+ support
- (Optional) Ollama access for external models

## License

**Copyright (c) 2024 Oleksii Vynogradov**

All rights reserved.

This software and its source code are the exclusive property of Oleksii Vynogradov. No part of this software may be used, copied, modified, merged, published, distributed, sublicensed, or sold in any form or by any means, in whole or in part, without the prior written permission of the copyright holder.

For inquiries regarding licensing, please contact: alex@unitai.net 