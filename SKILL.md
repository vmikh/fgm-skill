---
name: fgm-skill
description: Apply Figma best practices when building, editing, or reviewing screens, components, variants, and design systems. Use alongside figma-use for component APIs, clear layer names, responsive layout, and consistent content.
---

# Figma Best Practices

Read the project conventions and inspect the current reference. Check the component structure, exposed properties, tokens, and real content before editing. Use the technical Figma skill for tool and API details.

## Names and properties

- **Name the role.** Use names such as `Dialog header`, `Title`, and `Close button`. Use a stable family name for components and describe each layer at its own level.
- **Use one name per meaning.** Match neighboring components when the behavior matches. Use `State` for states, `Size` for scale, `Layout` for arrangement, and specific names such as `Placement` or `Tone` for other choices. Follow the library's casing and value vocabulary.
- **Separate visibility, content, and choice.** Use `Show icon` for a toggle, `Label` for text, and `Leading icon` for a swap. Make values legible in isolation, such as `Layout=Stacked`.
- **Expose supported choices.** Put mutually exclusive options on one axis. Give independent choices separate controls. Keep optional layers that implement states or toggles.
- **Rename in place.** Check usage before changing a component API. Preserve identities and verify selected variants, text, swaps, and visibility on existing instances.

## Structure and layout

- Reuse components and semantic tokens. Keep instances linked and preserve theme modes. Add a reusable part when the library has a genuine gap.
- Choose sizing by behavior. Use Fill for parent-controlled space, Hug for content, and Fixed for explicit dimensions. Check narrow and wide layouts with long labels, optional content, and relevant states.
- Give equivalent rows, controls, and states the same spacing, typography, and alignment. Keep structure stable when content or state changes.

## Content and review

- Use one source for repeated content. Check labels, assets, and values together. For multiple views of the same data, follow [Content consistency](references/content.md).
- Review from the component API down to the screen. Check names, instances, tokens, data, and overflow. Verify shared changes across representative instances and visually inspect changed states.
- Report what changed, what you verified, and what needs a decision. Keep project-specific rules in project documentation.
