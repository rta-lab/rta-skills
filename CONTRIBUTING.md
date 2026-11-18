# Contributing

Keep skills focused on decisions and workflows that improve agent behavior. Prefer current authoritative documentation over copied API signatures, version ranges, limits, pricing, or examples that will become stale.

For every skill change:

- Make the frontmatter description precise enough to trigger for intended requests and avoid adjacent tasks.
- Preserve user intent, existing technology choices, authorization boundaries, and unrelated work.
- Put shared routing and hard constraints in `SKILL.md`; move conditional detail into focused references and explain when each reference should be read.
- Use scripts only for deterministic work that would otherwise be fragile or repeatedly reimplemented.
- Verify time-sensitive claims against primary sources and link directly to the relevant guidance.
- Define observable completion and distinguish repository changes from deployed or effective state.
- Validate the skill with the skill-creator `quick_validate.py` script and exercise meaningful behavior when the workflow is complex or risky.

Do not add generic advice that a capable coding agent already knows, duplicate the same rule across files, or expand one observed failure into a universal requirement without evidence.

