# P1 Smart Irrigation System – Design Notes

## Brief Clarification
- **Primary Goal:** Learn IoT concepts
- **Secondary Goal:** Solve a real watering problem
- **Features:** Monitoring + time-based automation (auto on/off at set times)
- **Users:** Hobbyist gardeners, students tinkering

## Proto-Persona: Alex
| Role | Pain | Workaround | Success Signal |
|------|------|-----------|----------------|
| Hobbyist gardener / student | Forgets to water; wastes water when away; lacks soil data | Manual watering by eye or fixed schedule | System waters intelligently; learns IoT; sees real-time data |

## Alex's Journey
1. **Trigger:** Plants wilting or guess-watering while away
2. **Action:** Wants to automate but keep it simple (time-based, not fancy ML)
3. **Pain:** Worried about over/under-watering; doesn't know where to start with hardware
4. **Desired Outcome:** Sees soil data on phone/dashboard; can set water times; feels "I built this myself"

## Key Addition
- **Monitoring expansion:** Detect conditions beyond moisture—heat stress, fertilizer needs, etc.
- Gives Alex richer feedback and teaches more about plant health signals

## Sizing for Alex's Profile

**Hardware:** Super uncomfortable (but excited to learn)
- → Solution: Breadboard + jumper wires (zero soldering)
- → Follow no-solder tutorials only

**Python:** Super comfortable
- → Leverage this strength for control logic
- → Write Phase 1 in Python; minimize embedded complexity

**Pi/Arduino:** Zero experience
- → Treat Pi as a "computer with GPIO" (not magic)
- → Learn GPIO like a new Python library

## Phase 1 Timeline: 3–4 Weeks Solo

| Week | Focus | Hours | Risk |
|------|-------|-------|------|
| 1 | Order parts, learn GPIO, wire sensors | 8–10 | Shipping |
| 2 | Python sensor read script, test DHT22 | 6–8 | Library quirks |
| 3 | Relay wiring, schedule logic, full test | 8–10 | Low (Python expertise helps) |
| **Total** | **Offline system working** | **22–28** | Low |

## Phase 2 Timeline: 2–2.5 Weeks (Optional)

| Week | Focus | Hours | Risk |
|------|-------|-------|------|
| 4 | Flask dashboard + database | 6–8 | Framework setup |
| 5 | WiFi integration + fallback testing | 6–8 | Networking debug |
| **Total** | **Remote data access working** | **12–16** | Medium |

---

## Session Artifacts Created

✅ `1.assumptions.md` - 7 core assumptions + validation signals  
✅ `2.problem-statement.md` - Alex's pain + 4 success criteria  
✅ `3.ideation.md` - Hybrid layered approach (Phase 1 offline + Phase 2 web)  
✅ `4.proto-hypothesis.md` - 4 testable hypotheses + prioritization  
✅ `5.next-steps.md` - Week-by-week action items + learning wins
