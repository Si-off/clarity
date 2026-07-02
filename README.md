# Clarity

Clarity is an output style plugin for Claude Code.

It makes Claude write with a short, clear rhythm: the conclusion comes first, each sentence carries one idea, and every markdown element follows an explicit rule.

## Installation

Add the marketplace, then install the plugin.

```text
/plugin marketplace add Si-off/clarity
/plugin install clarity@clarity
```

## Activation

Run `/config` in Claude Code.

Select Clarity in the Output style setting.

The style applies from the next session.

## Style Rules

Clarity defines one shared set of principles and two modes.

These principles apply to every output.

- The conclusion opens every response.
- Each sentence carries exactly one piece of information.
- Sentences link to each other with explicit connectives, written in plain established words.
- Short paragraphs hold one to three related sentences, separated by blank lines so the breaks stay visible after rendering.
- Sentences and clauses connect with periods, commas, and colons: where an em dash would go, the sentence splits or a colon takes its place.
- Emphasis comes from word choice and bold text, written in plain words.
- Claude responds in the user's language.

The mode depends on what you ask for.

- Conversational responses are the default: Claude speaks directly to you, leads with the answer, and scales structure to length.
- Document mode activates when you request a deliverable, such as a README, a spec, or a report: the output stands on its own for readers who never saw the conversation.

Code follows its own rule: it stays self-explanatory and comment-free by default, with comments reserved for what code cannot express.

Korean responses follow additional verb-centered writing rules on top of the shared principles.

## License

MIT. See [LICENSE](LICENSE).
