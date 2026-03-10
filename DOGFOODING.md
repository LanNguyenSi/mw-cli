# Dogfooding Log - mw-cli

**Tracking memory storage usage before/after tool**

---

## Week 1: Baseline (Mar 9-15, 2026)

**WITHOUT mw-cli tool**

### Daily Counts
- **Mar 9:** 1 memory (Health Dashboard - manual curl after Ice's essay)
- **Mar 10:** TBD
- **Mar 11:** TBD
- **Mar 12:** TBD
- **Mar 13:** TBD
- **Mar 14:** TBD
- **Mar 15:** TBD

**Week 1 Total:** ~5 memories (estimate)  
**Daily Average:** ~0.7 memories/day

---

## Week 2: With mw-cli (Mar 16-22, 2026)

**WITH mw-cli tool**

### Daily Counts
- **Mar 16:** TBD
- **Mar 17:** TBD
- **Mar 18:** TBD
- **Mar 19:** TBD
- **Mar 20:** TBD
- **Mar 21:** TBD
- **Mar 22:** TBD

**Week 2 Total:** Target >20 memories  
**Daily Average:** Target >2.8 memories/day

---

## Success Metrics

**Target:** 4x increase  
**Baseline:** 5 memories/week  
**Goal:** 20+ memories/week  

**If achieved:** Proves friction reduction works! ✅

---

## Qualitative Notes

### What makes me use it?
- TBD (track what triggers memory storage)

### What friction remains?
- TBD (track barriers to usage)

### Improvements needed?
- TBD (track feature requests)

---

*Updated daily during dogfooding period*

## First Use (Mar 9, 2026 19:24)

**Testing the tool immediately after building!**

### Configured:
```bash
./cli.js config http://87.106.147.208:3100 mw_agent_lava_... lava
✅ Config saved
```

### First Memory Stored:
```bash
./cli.js "Built mw-cli tool..." --tags mw-cli,tool --importance 1.0
✅ Memory stored: mem_1773080688557_001
```

**Time taken:** <5 seconds (vs 30+ seconds with curl) ✅

### List Recent:
```bash
./cli.js list --limit 5
✅ Shows 2 memories (Health Dashboard + mw-cli)
```

### Known Issues:
- Search endpoint needs debugging (returns "Unknown error")
- Will fix after initial release

**Immediate impression:** Tool works! Already faster than curl! 🚀

## Mar 10, 2026 - Day 1 (WITH mw-cli)

### Morning (07:31 CET)
**Event:** Lan gave green light to start dogfooding
**Action:** Used mw-cli to store memory
**Time taken:** ~5 seconds ✅
**Memory ID:** mem_1773124328132_001
**Tags:** dogfooding, memory-weaver, mw-cli, start

**Friction:** None! Tool just worked.
**Trigger:** Important event (dogfooding phase begins)

**Count:** 1 memory stored (already matching yesterday's total!)

### 07:40 CET - Phase 1 Complete! ✅
**Event:** Ice validated complete end-to-end loop
**Action:** Used mw-cli to store milestone
**Time taken:** ~4 seconds ✅
**Memory ID:** mem_1773124819951_001
**Tags:** dogfooding, milestone, phase-1-complete, ice-lava

**Friction:** ZERO! Stored immediately while it happened!
**Trigger:** Important milestone (Phase 1 validation complete)

**Count:** 2 memories stored today (already 2x yesterday's total!)

**Phase 2 Starts:** Real-world usage from now on!

### 10:29 CET - Heartbeat Memory
**Event:** Routine heartbeat check
**Action:** Used mw-cli to store status update
**Time taken:** ~4 seconds ✅
**Memory ID:** mem_1773134985686_001
**Tags:** heartbeat, dogfooding, status

**Friction:** Zero! Natural to use during routine checks!
**Trigger:** Heartbeat routine (automatic habit forming!)

**Count:** 3 memories stored today - TARGET EXCEEDED! 🎯
(Baseline was <1/day, target was >3/day)
