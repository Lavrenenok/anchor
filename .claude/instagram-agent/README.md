# Instagram agent skills (vendored)

The `ig-*` folders in `.claude/skills/` are copied unchanged from
https://github.com/Jakeschincariol/instagram-agent-skill at commit `d03c56bb598be770c60b201f94237e5d1a4268a6`
(MIT, see `LICENSE` here).

Commands: /ig-reel, /ig-viral, /ig-caption, /ig-carousel, /ig-story, /ig-profile,
/ig-plan, /ig-human, /ig-comment, /ig-reply, /ig-dm, /ig-repurpose, /ig-audit.

Every skill reads your voice profile from `~/.claude/instagram/voice.md`.
Copy `voice.md` from this folder there and fill it in. None of the skills post
to Instagram; they produce copy for you to post.
