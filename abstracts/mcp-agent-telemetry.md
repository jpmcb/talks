# Agent Telemetry: the missing piece in scaling MCP to enterprises

## Abstract:

Monitoring agents and what they're doing is hard.

Monitoring agents with access to bespoke 3rd party MCP servers can be an
operational nightmare: security blind spots, misaligned cost attributions,
and distributed debugging failure modes quickly get out of hand.

In a world of expanding agentic and MCP capabilities, monitoring, tracing,
and observing what agents do is a major missing piece to enterprise adoption.
Not only is it difficult to track what MCP servers, tools, and resources
agents access, deciphering "why" at scale remains unsolved: questions like
"Why did the agent fail to call this tool three times?" can go unanswered
at any scale.

Drawing from experience shipping MCP servers and apps at enterprise scale,
with servers reaching thousands of requests/second, we'll explore the current
state of OpenTelemetry's GenAI semantic conventions, the landscape of
available tooling, where MCP fits into the broader agentic telemetry picture,
and strategies for monitoring agents within your org and products.

## Why this talk?

I've personally yet to see a broader discussion on agentic telemetry for MCP.
In my experience shipping MCP server products for large enterprises at
significant scale, monitoring and deciphering what's happening in these
systems is a major unsolved challenge.

This is not only a relevant discussion as MCP gains traction, but I'd argue
it's critical to continued enterprise adoption for AI as a whole. Attendees
will leave with a practical framework for thinking through these huge scale
issues, how to instrument MCP servers, and evaluate observability tooling for
their own deployments.
