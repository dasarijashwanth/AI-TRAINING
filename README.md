# AI Training by Jashwanth Dasari

A plainspoken, practical AI training site for the community: nine topics covering AI concepts, safety, using and building AI agents, plus guides and a glossary. Live at https://dasarijashwanth.github.io/AI-TRAINING/

## Structure

- `site/` — the whole site: `index.html`, `css/style.css`, and `topics/*.html`
- `.github/workflows/deploy.yml` — deploys `site/` to GitHub Pages on every push to `main`

No build step. Plain static HTML + one CSS file. To preview locally:

```bash
cd site && python3 -m http.server 8080
```

## Topics

1. AI Concepts (LLMs, tokens, context windows, temperature, embeddings)
2. AI Safety (hallucinations, prompt injection, data privacy, responsible use)
3. Using AI Agents
4. Coding with AI Agents
5. Customizing Agents (system prompts, tools, skills, memory)
6. Building Agents (loop, tools, evals, worked example)
7. Guides (pick a model, cost control, eval basics)
8. Glossary
9. About

## Attribution

Inspired by [schubergphilis/ai-training](https://github.com/schubergphilis/ai-training). The topic structure follows a similar learning path, but every lesson, example, and sentence here was written fresh for this training. No text, lessons, or code were copied from the source repository.

## License

Site content is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Site code (HTML, CSS, workflows) is licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

By [Jashwanth Dasari](https://github.com/dasarijashwanth). Newsletter: [Learn with Jashwanth](https://learnwithjashwanth.substack.com).
