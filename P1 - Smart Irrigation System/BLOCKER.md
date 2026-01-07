# Blockers & Constraints

## 🚧 Financial Blocker

| Item | Cost | Status | Notes |
|------|------|--------|-------|
| Raspberry Pi 4 (2GB) | $35–45 | ❌ Blocked | No budget until Feb |
| DHT22 Sensor | $5–8 | ❌ Blocked | — |
| Soil Moisture Sensor | $3–5 | ❌ Blocked | — |
| Relay Module | $3–5 | ❌ Blocked | — |
| Breadboard + Wires | $8–12 | ❌ Blocked | — |
| Power Supply | $8–15 | ❌ Blocked | Might already own |
| Water Pump | $5–12 | ❌ Blocked | — |
| Tubing + Misc | $5–10 | ❌ Blocked | — |
| **TOTAL** | **$75–120** | **Blocked** | **Budget: $5/month currently** |

---

## 📋 Current Plan (Adjusted for Constraints)

### Phase 0: Zero-Cost Learning (January 2026)
**Timeline:** This week + next 3 weeks  
**Budget:** $0  
**Deliverables:**
1. ✅ GPIO fundamentals (YouTube + official Raspberry Pi docs)
2. ✅ DHT22/soil sensor reading (code research + library docs)
3. ✅ Python simulator: mock sensors + relay logic
4. ✅ Flask dashboard prototype (connected to simulator)
5. ✅ Scheduling research (APScheduler, cron concepts)

**Why:** Learn concepts cost-free; when parts arrive, code is ready. No fumbling.

---

### Phase 1: Hardware Build (February 2026, when budget available)
**Timeline:** Weeks 1–3 (after parts arrive)  
**Budget:** $75–120  
**Deliverables:**
- Breadboard wiring (DHT22, soil sensor, relay)
- Real sensor readings in Python
- Relay triggering water pump
- Scheduled automation working

**Assumption:** $15–20/week starting Feb = enough by mid-Feb to order; parts arrive late Feb.

---

### Phase 2: Connectivity (March 2026, optional)
**Timeline:** Weeks 4–5  
**Budget:** $0 (leverage Phase 0 Flask prototype)  
**Deliverables:**
- Flask dashboard connected to live Pi
- WiFi + data persistence
- Offline fallback tested

---

## 🔄 Alternative If Feb Budget Not Available

**Option A: Borrow Pi + Sensors**
- Ask local tinkerer/hackerspace/friend
- Build Phase 1 on borrowed hardware
- Return by April; buy your own later

**Option B: Continue Simulator**
- Extend Phase 0 indefinitely
- Keep learning; build more complex simulations
- No rush; hardware is optional learning path

---

## 📌 What's Not Blocked

✅ Research + learning (free online resources)  
✅ Python code writing (simulator + Flask)  
✅ Design & planning (done; see `1.assumptions.md`, `2.problem-statement.md`, `3.ideation.md`)  
✅ Documentation (in progress)

---

## Decision Point

**Go with Phase 0 (simulator) this month?** → Yes / No  
**Expected Feb budget availability?** → TBD  
**Backup plan if no Feb budget?** → Borrow or extend simulator
