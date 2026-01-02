# ME
telegram bybit bot
Looking for help to audit and stabilize a Python trading bot (Bybit + Telegram) – reliability + notifications

Hi,
I’m looking for help/collaboration with a Python developer who can take over and quality-assure an existing trading bot.

Background
A developer built the bot for me, but unfortunately he is unreachable after a traffic accident. The bot is manually built (not AI-based) and contains extensive strategies. It trades on Bybit and sends/handles notifications via Telegram.

Problems to fix

Missing signals (~5%)

Some signals that appear in Telegram are not sent to Bybit and are not copied to my Telegram group.

Telegram reporting is not 100% correct

Sometimes the wrong message is sent at the wrong time (ordering/trigger issues).

Message text/formatting

Spelling mistakes, inconsistent capitalization, etc. need to be corrected and standardized.

Event-based reporting (“truth from Bybit”)

I want to ensure Telegram messages are sent based on real events on Bybit (e.g., order/fill/position), not only on the bot’s internal assumptions.

Robustness and operational reliability

The goal is stable, predictable operation with high reliability (no random behavior, no silent failures).

What I need (goals)

A technical audit of the existing code and flows (signal → order → execution → position → notification).

Fix bugs causing missing signals and incorrect notification ordering.

Add clear logging/traceability so it’s possible to verify that “everything is sent” and why.

Clean up and standardize notification texts.

Ensure robust operation (error handling, reconnect logic, timeouts, retries, deduplication).

Important for now

I’m not a programmer and nothing is uploaded to GitHub yet.

I want to start with a general discussion and a plan: your usual approach, what you need from me, and how to do this securely.

I will not share API keys/tokens publicly.

What I can provide next (privately)

Logs and examples where signals are missed / wrong messages are sent.

Information about how the bot runs (Windows/VPS) and what strategies/components exist.

Private code sharing once I’m comfortable with the setup and confidentiality.

Please reply with

Your experience with Python, Bybit (REST/WebSocket), and Telegram bots.

How you typically run an audit + stabilization (your steps).

Whether you can take this as a collaboration/paid task, and how we can start without me needing to be good at GitHub.

Thanks!
