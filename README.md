# PromptForge Showcase

PromptForge Showcase is a small portfolio repository for AI projects that combine generative models, document intelligence, and simple web interfaces. It is organized as a single repo with one folder per project so each notebook can stand on its own while still being easy to browse together.

## Projects

### Netflix Campaign Generator
A text-to-image creative tool that turns marketing prompts into campaign visuals for Netflix-style banners and posters. It uses the OpenAI image generation API and a Gradio interface to let users quickly explore concept art ideas for streaming promotions.

### Nestle HR Policy Assistant
A retrieval-augmented chatbot that answers questions from an HR policy PDF. The project chunks the policy document, stores embeddings in Chroma, and uses an LLM to return grounded answers through a chat-style interface.

## Repository Layout

```text
PromptForge Showcase/
├── Netflix Campaign Generator/
│   └── Netflix_Campaign_Generator_OpenAI.ipynb
└── Nestle HR Policy Assistant/
    ├── AI_powered_HR_Assistant_Nestle_openai.ipynb
    └── the_nestle_hr_policy_pdf_2012.pdf
```

## Tech Stack

- Python
- OpenAI API
- Gradio
- LangChain
- ChromaDB
- Pillow
- Requests

## How To Use

1. Open the project notebook you want to run.
2. Add your OpenAI API key in the notebook environment or as an environment variable.
3. Run the cells from top to bottom.
4. For the HR assistant, make sure the policy PDF stays in the same folder as the notebook.

## Notes

- The notebooks are grouped by descriptive project name instead of generic labels like `P1` or `P2`.
- Generated vector databases and notebook checkpoints are intentionally excluded from version control.
- The repository is intended as a clean, submission-ready portfolio bundle.
