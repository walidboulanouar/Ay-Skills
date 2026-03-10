# AY Automate MCP Server Guide

## When to Use Which Server

### Attio — CRM Operations
**Native tools:** `mcp__attio__search-records`, `mcp__attio__create-record`, `mcp__attio__create-task`, `mcp__attio__create-note`, `mcp__attio__list-lists`, `mcp__attio__list-records-in-list`, `mcp__attio__update-record`
**Use for:** Client/prospect records, deal pipeline, task tracking, meeting notes, CRM sync

### Unipile — LinkedIn via API
**Preferred:** Use `.claude/skills/unipile-linkedin-skill/scripts/linkedin.mjs`
**Use for:** Sending messages, viewing profiles, managing connections, creating posts, tracking engagement

### Anysite — Web Intelligence
**Native tools:** `mcp__anysite__get_linkedin_company`, `mcp__anysite__search_linkedin_users`, `mcp__anysite__parse_webpage`, `mcp__anysite__search_youtube_videos`, `mcp__anysite__get_youtube_video_subtitles`
**Use for:** Prospect research, competitive intel, content research, web scraping

### Notion — Migration Source
**Native tools:** `mcp__notion__notion-search`, `mcp__notion__notion-fetch`, `mcp__notion__notion-query-database-view`
**Use for:** Importing content during migration, searching Notion databases

### Slack — Team Communication
**Native tools:** `mcp__slack__conversations_history`, `mcp__slack__conversations_search_messages`, `mcp__slack__conversations_add_message`
**Use for:** Channel digests, searching decisions/blockers, posting updates (with confirmation)

## Priority Order
1. **Native MCP tools** — Preferred for single operations
2. **Unipile LinkedIn scripts** — Preferred over raw MCP for LinkedIn
3. **mcp-client Python script** — Only for batch operations or when native MCP unavailable
