Rock–Paper–Scissors–Plus Referee Bot

State Model:
The game uses a dictionary to store round count, scores, bomb usage, and game completion status.
State persists across turns and is updated only via tools.

Agent and Tool Design:
The agent handles conversation and intent understanding.
Three tools are used:
- validate_move: checks rules and bomb usage
- resolve_round: decides winner
- update_game_state: mutates game state

Tradeoffs:
Bot strategy is simple to keep logic clear.
Single agent used instead of multiple agents.

Future Improvements:
- Smarter bot strategy
- Better intent parsing
- Structured outputs
