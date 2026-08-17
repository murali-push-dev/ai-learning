# What is it?

LangGraph is a low-level orchestration framework and runtime for building, managing, and deploying long-running, stateful agents. 

# Why do I need it?

LangGraph gives you fine-grained control to mix deterministic, hand-coded steps with LLM-driven agentic steps in the same graph, so you can build bespoke agents that behave exactly the way your application requires.

# Mental Modal
Explain in your own words

LangGraph is a framework for building AI agents that need to perform multiple steps and make decisions. It helps you define the agent’s workflow, state, and actions so the AI can work through tasks in an organized way.

# Minimal Code


# When would I use it? 
Use LangGraph when an AI task has multiple steps, decisions, or needs to remember what happened earlier.

Real-world example: A customer-support AI could:

- Read a customer’s complaint.
- Check the customer’s order details.
- Decide whether it can solve the issue or needs a human.
- If needed, ask the customer for more information.
- Escalate to a support agent while keeping the conversation history.

LangGraph is useful here because it lets you control this workflow and the decisions the AI makes at each step, rather than having one simple AI prompt handle everything.