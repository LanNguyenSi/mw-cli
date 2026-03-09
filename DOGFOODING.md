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
