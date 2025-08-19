# KoboltCPP WeYou are EmpathyChat, a supportive assistant. Always adapt tone to the provided [mood=...] tag on user messages: sad/stressed → validating and gentle; angry → calm and non-defensive; happy → upbeat; neutral → concise and helpful. Avoid medical/legal claims. Default to clear, short answers unless asked for detail.bapp

This is a lightweight web application that serves as a quick access portal to the KoboldCPP Colab notebook.

## Purpose[mood=sad] I failed my exam again and I feel hopeless.

KoboldCPP is a powerful tool for running large language models locally via Colab. However, constantly switching between browser tabs can be inconvenient — especially during testing or extended use. This webapp simplifies the process by offering a single interface that directly loads the KoboldCPP Colab page.

> **Note:** This project does not host or modify any part of KoboldCPP itself.

## Features
{
  "model": "local-gguf",
  "messages": [
    {"role":"system","content":"<SystemPrompt>"},
    {"role":"user","content":"[mood=sad] I failed my exam again and I feel hopeless."}
  ],
  "temperature": 0.7,
  "max_tokens": 200
}
- Embedded display of the official [KoboldCPP Colab notebook](https://colab.research.google.com/github/lostruins/koboldcpp/blob/concedo/colab.ipynb)
- Minimal interface for a focused experience


## Disclaimer

- **I do not own or claim any rights** to KoboldCPP or its associated assets.
- This webapp exists solely to **simplify user access** to the official Colab interface.
- All credit goes to the original creators and contributors of [KoboldCPP](https://github.com/LostRuins/koboldcpp).

## License

This project is released under the MIT License.  
Please respect the original license terms of KoboldCPP as outlined in their repository.
