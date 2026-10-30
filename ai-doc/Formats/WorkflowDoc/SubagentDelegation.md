# Subagent Delegation

When a delegated task recurs with stable instructions, record its prompt in the workflow so it can be formulated and reviewed once, then reused consistently. Use placeholders for values that vary between executions.

- Use the Agent tool with `subagent_type: fork` (a fork: it inherits the parent session's context) when the prompt relies on the workflow's current context.
- Use Agent when the prompt is self-contained; the prompt MUST provide all required context.
- State the delegated task and expected output clearly.
- State how the parent uses the result when later work depends on it.
