# MEDIA-TEAM - Claude Code Guide

**Project Type**: Content Production Workspace
**Created**: January 12, 2026
**Last Updated**: January 12, 2026

---

## Project Overview

Central workspace for PRSMTECH media team operations. This is NOT a code project - it's an operational workspace for design and media production asset tracking, task assignments, and deliverable organization.

**Purpose**: Track weekly media production deliverables, organize content by team member and date, coordinate between CEO, Backend Lead, and Media Team.

---

## Team Members

| Member | Role | Primary Responsibilities |
|--------|------|--------------------------|
| Jordan Ward | CEO | Content direction, actor for skits, final approval |
| Prajjwal Datir | Backend Lead | Technical projects (NX Studio), payment coordination |
| Hafiz Yoosuf | Designer & Media Producer | Content creation, video editing, UI design |

---

## Directory Structure

```
MEDIA-TEAM/
├── WEEK-1/                     # Weekly production folders
│   ├── 1-12(MONDAY)/           # Daily folders (M-DD format)
│   │   ├── CEO/                # Jordan's items
│   │   ├── HAFIZ/              # Hafiz's deliverables
│   │   └── SHARED/             # Collaborative items
│   └── ...
├── WEEK-2/
├── WEEK-3/
├── WEEK-4/
├── ASSETS/                     # Shared brand assets (future)
├── TEMPLATES/                  # Reusable templates (future)
├── .memory-bank/               # AI context persistence
├── .claude/                    # Claude Code configuration
└── CLAUDE.md                   # This file
```

---

## Common Operations

### Starting a New Week
```bash
# Create new week folder
mkdir WEEK-X

# Create daily subfolders
mkdir "WEEK-X/M-DD(DAYNAME)"
mkdir "WEEK-X/M-DD(DAYNAME)/CEO"
mkdir "WEEK-X/M-DD(DAYNAME)/HAFIZ"
mkdir "WEEK-X/M-DD(DAYNAME)/SHARED"
```

### Finding Current Tasks
```bash
# Check active context
cat .memory-bank/activeContext.md

# Check progress
cat .memory-bank/progress.md
```

### Adding a Deliverable
1. Place file in appropriate `WEEK-X/DATE/ROLE/` folder
2. Update `.memory-bank/progress.md` with completion status
3. If significant, add to `.memory-bank/decisionLog.md`

---

## Content Production Targets

### Day 30 Goals (from 30-Day Gameplan)

| Platform | Target | Owner |
|----------|--------|-------|
| TikTok | 1,000-2,000 followers | Hafiz (production) |
| Instagram Reels | 500-800 followers | Hafiz (cross-post) |
| YouTube Shorts | 800-1,200 subs | Hafiz (repurpose) |
| Twitch | 600-1,000 followers | Jordan (stream) / Hafiz (clips) |
| **TOTAL** | **5,000+ combined** | - |

### Weekly Output Targets

| Metric | Target |
|--------|--------|
| Short-form videos | 25-30/week |
| Twitch clips | 15/week (5 per stream × 3 streams) |
| Vibe Coder skits | 2-3/week |

---

## Content Pillars

| Pillar | % | Examples |
|--------|---|----------|
| Educational | 40% | Quick tips, tutorials, how-tos |
| Story/Journey | 25% | Behind-the-scenes, lessons learned |
| Entertainment | 20% | Vibe Coder skits, memes, POV videos |
| Promotional | 15% | Stream promos, service highlights |

---

## Key Reference Documents

| Document | Location | Purpose |
|----------|----------|---------|
| Hafiz Task Brainstorm | `WEEK-1/1-12(MONDAY)/CEO/HAFIZ-TASK-BRAINSTORM.md` | 50+ task ideas |
| 30-Day Gameplan | `J:\PRSMTECH\PRSM-CEO\30-DAY-SOCIAL-MEDIA-GAMEPLAN\` | Master strategy |
| Vibe Coder Scripts | `30-DAY-SOCIAL-MEDIA-GAMEPLAN/content-calendar/VIBE-CODER-SKIT-STRATEGY.md` | 10 ready scripts |
| Content Ideas Bank | `30-DAY-SOCIAL-MEDIA-GAMEPLAN/content-calendar/CONTENT-IDEAS-BANK.md` | 120+ content ideas |
| Hafiz Contract | `J:\PRSMTECH\PRSM-CEO\CEO-PRIVATE\contracts\Hafiz-Yoosuf\` | HR documents |

---

## Stream Schedule (Twitch)

**Channel**: @MrJPTech

| Day | Time (EST) | Content Type |
|-----|------------|--------------|
| Tuesday | 2:00 PM | Live Coding |
| Thursday | 6:00 PM | Business/Guest/AMA |
| Saturday | 11:00 AM | Mentorship/Q&A |

**Hafiz Post-Stream Tasks** (within 2 hours):
1. Download VOD
2. Clip 3-5 highlights
3. Post best clip to TikTok immediately
4. Tweet key takeaway
5. Post recap to Instagram Stories

---

## Tools & Access

| Tool | Access Method | Owner |
|------|---------------|-------|
| Adobe Creative Cloud | Splashtop remote desktop | Hafiz |
| CapCut | Personal device + desktop | Hafiz |
| Veo 3 / AI tools | $40/month AI credits | Hafiz |
| Google Workspace | api@prsmtech.com | Hafiz |
| GitHub | View-only (via remote desktop) | Hafiz |

---

## Contract Notes

**Hafiz Yoosuf Status**: Pre-Signature (5 gaps identified)

Pending resolution:
1. Veo 3 vs V3 clarification
2. Personal project clause (snowboard editing)
3. CapCut addition to tools list
4. Prajj payment role documentation
5. GitHub access clarity

See: `CEO-PRIVATE/contracts/Hafiz-Yoosuf/ONBOARDING-ANALYSIS-REPORT.md`

---

## Session Workflow

```bash
# Session Start
/memory-load

# Session End
/memory-save
```

---

**Maintained By**: PRSMTECH
**Category**: Content Production / Media Operations
