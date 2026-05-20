# Agents AI

> AI Agents does things for us on it own to reach a goal.

## The 4 pillars of an AI Agent

- what make ai can act like `Agent` it need these four foundational pillars to work together.

1. core model (brain)

- The Large language model's job is to understand what you want, process information, and make decisions.
  - `example`: you tell agent, `plan birthday party for my 10-years kid`, the brain analysis this and understand user intent, it need to find themes, order food, and create schedule.

2. memory (context)

- Agents need to remember things to be useful otherwise it like working with someone who has amnesia.
- Agents has two types of memory:
  - `short term memory`: remembering what you just talked about in current sessions.
  - `long term memory`: storing information over days or weeks (usually using database).

  - `example`: The agents remember that your kid allergic to peanuts (long term) and that reject the `dinosaur theme`(short term) five minutes ago.

3. planning (strategy)

- This is what makes an agent truly `Agentic`. instead of just return result straight answer immediate, the agent pauses, breaks big goal into smaller steps, figures out best orders to do them. It can self-reflect and change the plan if it messes up.

- `example`: The agent create step-by-step checklists:
  1. search web for 10-years party themes.
  2. check local weather for that date.
  3. find peanut-free bakeries nearby.
  4. draft an email to the bakery.

4. Tools (hands for agents)

- A standard AI is trapped in chatbox.
- An agent is given `tools` (like web browser, calculator or API connections) so it can interact with outside world.

- `example`: the agent actually uses a web search tool to find bakery, uses an API tool to check weather,
  and uses email tool to send the message to the bakery to order the cake.
