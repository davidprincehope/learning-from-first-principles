# Learning from First Principles

I made this skill because this is how I like to learn.

When I'm learning something, I want to understand why it exists, what problem it solves, and what actually happens inside it. I like starting with the basics, working through a concrete example, and building up until I can explain it in my own words or use it in something I'm making.

This approach has helped me learn machine learning principles, software architecture, and how the two fit together. In my [Ayo Olopon project](https://github.com/davidprincehope/AlphaAyoOlopon), I've been working with reinforcement learning and AlphaZero: game rules, self-play, training, checkpoints, and evaluation. There's a lot to understand in a system like that. Going back to first principles helps me make sense of the individual pieces and how they work together.

Learning from First Principles puts that way of learning into an agent skill. I felt I should share it with anyone who wants to try it out.

## What it does

The skill guides your AI assistant to build an explanation from the ground up:

- Start with the problem and why the concept is needed.
- Explain the mechanism, introducing terms and symbols as they come up.
- Work through one concrete example so you can follow what changes at each step.
- Connect the concept to the bigger picture.
- Check your understanding by asking you to explain, predict, trace, or implement something yourself.

If something doesn't click, it encourages the assistant to work out where the confusion is and rebuild the explanation from there. It also matches the depth to your question, so a small question can still get a small answer.

You can use it for ML, programming, maths, software architecture, or another topic you're trying to understand.

## Try it out

Copy the `first-principles-learner` folder into your AI agent's skills directory, following that agent's installation instructions. Keep `SKILL.md` and the `references` folder together. Reload your agent if needed so it can discover the skill.

The installed skill is named `first-principles-learner`. Ask your agent to use it with a topic you're curious about:

> Use the first-principles-learner skill to teach me backpropagation. Start with the problem it solves and walk me through a small numerical example.

Or bring something you're already building:

> Use the first-principles-learner skill to help me understand how self-play, tree search, and the neural network fit together in AlphaZero. Trace one move before explaining the full training loop.

Or start with a gap in your understanding:

> I can follow this code, but I don't understand why the system is designed this way. Use the first-principles-learner skill to walk me through the architecture from the basics.

You don't need a perfectly worded prompt. Start with what you want to understand, say what you already know, and point out where you're getting lost.

## Inside the skill

`SKILL.md` contains the core teaching workflow. The files in `references/` provide more guidance on explanations, examples, confusion, and checking understanding. It's all written guidance; there are no scripts to run.

## A personal note

This is the way I like to learn, and I'm still learning too. If it helps you understand something you've been struggling with, I'm glad I shared it. Try it, adapt it to how you learn, and let me know what works for you.

## License

[MIT](LICENSE.txt).
