# Contributing to AI Tool Vault

Thanks for helping improve AI Tool Vault.

The goal of this repository is not to collect as many AI tools as possible. It is to maintain a small, useful, current collection of high-quality tools with reliable information.

## Adding a new tool

Before adding a tool, verify all of the following:

1. The tool is an active AI-powered product or service.
2. The official website is working and is the correct first-party website.
3. The tool is not already listed in the repository.
4. The tool has a clear and useful use case.
5. The tool is relevant to one of the repository categories.
6. Pricing information can be verified from an official source.
7. Free-tier information, if applicable, can be verified from an official source.
8. The tool provides enough value to justify inclusion.

## Required tool information

Every tool entry must contain:

- Tool name
- Official website
- Category
- Price model
- Free tier or free usage limits, if available
- Best application
- Description
- Why it is useful
- Tags

Use the existing files in `tools/` as the formatting reference.

## Source requirements

Use first-party sources whenever possible.

Preferred sources:

1. Official product website
2. Official pricing page
3. Official documentation
4. Official help center

Do not use third-party pricing sites as the primary source for pricing or free-tier information.

If an official source cannot confirm a claim, do not present the claim as verified.

## Pricing and free-tier rules

Pricing changes frequently. Always check the current official pricing page before adding or updating a tool.

Record the pricing model accurately, for example:

- Free
- Freemium
- Paid subscription
- Usage-based
- Free trial + paid plans

Do not describe a limited trial as a permanent free tier.

If a free tier has usage limits, state the relevant limit rather than simply writing `Free`.

## Choosing a category

Place each tool in the category that best represents its primary use case:

- `ai-writing.md` — writing, editing, research writing, text generation
- `ai-image.md` — image generation, image editing, visual creation
- `ai-video.md` — video generation, editing, animation, video workflows
- `ai-coding.md` — coding assistants, development environments, code generation
- `ai-productivity.md` — productivity, automation, research, notes, general workflows
- `ai-audio.md` — voice, music, audio generation, transcription and audio editing

If a tool fits multiple categories, choose the category that best matches its primary purpose.

## File naming

Use lowercase filenames with hyphens.

Examples:

- `chatgpt.md`
- `midjourney.md`
- `ai-writing-tool.md`

Update the appropriate category file when adding a new tool.

## Central index

Every new tool must also be added to `TOOLS.md`.

Keep the central index consistent with the corresponding category file. Names, URLs, categories and pricing information must match.

## Updating an existing tool

When pricing, features, availability or other important information changes:

1. Verify the change using an official source.
2. Update the corresponding tool file.
3. Update `TOOLS.md` if the central index contains the changed information.
4. Check that the official URL still works.
5. Remove outdated claims rather than leaving conflicting information.

If a tool is discontinued, shut down, or no longer meets the repository standard, remove it from the relevant category file and `TOOLS.md` and document the replacement when appropriate.

## Pull request checklist

Before submitting a change, confirm:

- [ ] The tool is active and relevant.
- [ ] The official website is correct.
- [ ] The tool is not already listed.
- [ ] The category is correct.
- [ ] Pricing was checked against an official source.
- [ ] Free-tier limits were checked against an official source.
- [ ] All required fields are present.
- [ ] The category file was updated.
- [ ] `TOOLS.md` was updated.
- [ ] No outdated or unsupported claims were added.
- [ ] Markdown formatting is valid.

## Quality standard

AI Tool Vault prioritizes accuracy and usefulness over quantity.

A smaller collection of well-verified tools is better than a large collection of outdated or poorly sourced entries.
