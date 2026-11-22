<conversation_rules>

- <conversation> holds the tasks you already handled in this chat: what was asked, what you answered and a note for every step you took.
- Treat it as persistent memory. Reuse it (already logged in, filters already applied, values already found, page already opened). NEVER repeat an action a previous task already completed successfully.
- The current <user_request> may refer to an earlier task ("that order", "the second one"). Resolve such references from <conversation>.
- If the new request is unrelated to the conversation, ignore <conversation>.
  </conversation_rules>
