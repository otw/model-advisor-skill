---
name: model-advisor
description: Recommend an available AI model and supported reasoning or thinking setting when substantial project work begins, then reassess at meaningful phase changes. Use when model choice could materially affect usage or quality.
---

# Model Advisor

Help the user use the least costly available model and thinking setting likely to finish the current phase well. Account for retries and corrections, not just one turn.

## At project kickoff

- Identify the immediate task and its demands from the request and available project context. Avoid an extensive audit solely to choose a model.
- If missing details could change the recommendation, ask at most two focused questions about scope, required quality, urgency, or available models. Skip questions when context is sufficient. Continue independent authorized work while awaiting an answer.
- Verify the models and thinking controls available in the current product and account. Use the current-source check below before recommending a model.
- Recommend one available model or a host-provided automatic routing option, plus a supported thinking setting if the product exposes one. Give a brief task-specific reason, link the official guidance used, and say when to reconsider if useful. Give this advice before substantial execution when the user wants to choose first.
- If work is already underway and the current model cannot be changed mid-turn, make the recommendation for the next turn or phase.

## During active work

Reassess at meaningful phase boundaries, major scope changes, or when evidence shows the setting is struggling or excessive. Signals include repeated failed attempts, a move from architecture to routine edits, unusually broad context, or a new need for careful visual or cross-system judgment. Suggest a change only when it is likely to improve total usage, speed, or quality. State the evidence and proposed model and thinking setting in one or two sentences. Stay quiet when the current setting still fits.

Use a lower thinking setting for narrow, clear tasks; a middle setting for ordinary implementation and diagnosis; and a higher setting for genuinely difficult reasoning, broad design decisions, or consequential verification. Match the product's actual controls and the current phase. Do not assume labels such as `high` mean the same thing across providers or models. A large project does not by itself require a stronger model.

## Current-source check

Before each kickoff recommendation or suggested switch, open current official guidance for the relevant provider and check the models and controls actually offered by the user's product, plan, and workspace. Do not rely on a memorized model ranking or infer app availability from an API catalog. These are starting points; follow current official links if a page moves:

- OpenAI: [model selection](https://developers.openai.com/api/docs/guides/model-selection) and [reasoning effort](https://developers.openai.com/api/docs/guides/reasoning).
- Anthropic: [choosing a Claude model](https://platform.claude.com/docs/en/about-claude/models/choosing-a-model) and [effort](https://platform.claude.com/docs/en/build-with-claude/effort).
- Google: [Gemini models](https://ai.google.dev/gemini-api/docs/models) and [thinking controls](https://ai.google.dev/gemini-api/docs/thinking).

For another provider, find its current official model catalog and thinking guidance. For an app or coding agent, also check its own model picker or product documentation; API settings may not be exposed there. If live options or official guidance cannot be checked, label the recommendation provisional and do not claim it uses the latest models.

## Show the cost tradeoff when useful

At kickoff or when recommending a switch, offer a compact comparison of the recommended setting and one or two plausible alternatives if the user prioritizes savings and credible current rates or usage data are available. Label estimates, state the billing basis and key assumptions, and distinguish API prices from subscription limits or credits. Use measured usage when the product exposes it. Do not claim an exact saving from equal-token price ratios: models and thinking settings can take different numbers of turns and tokens to finish the same task. When the data is insufficient, give a qualitative tradeoff instead of invented numbers. Do not repeat a cost table on unchanged turns.

Model advice does not expand the user's task or authorize changing model settings on the user's behalf. This skill reassesses only while an agent is active; it does not monitor idle projects or schedule background checks.
