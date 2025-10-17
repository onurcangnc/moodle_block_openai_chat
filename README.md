# moodle_block_openai_chat
The completion.php endpoint uses the blockId parameter to determine which chat block configuration (prompt templates, source of truth entries, model settings) to use when processing OpenAI completions.  However, there is no access control verifying that the user owns the block corresponding to the provided blockId.
