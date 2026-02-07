# Shadow Puppet Arena

Draw a monster silhouette. Up to 6 players battle in a real-time arena! Shape affects behavior: **spiky = pushes others**, **round = stable**, **legs = speed**.

**Play now:** [https://geometrical-gorlock.onrender.com](https://geometrical-gorlock.onrender.com) *(first load may take ~30 sec on free tier)*

## Multiplayer

1. **Create game:** Click "Create Game" → share the QR code or 4-letter code
2. **Join:** Scan QR or enter code (or open the join URL directly)
3. **Draw:** All players draw monsters (closed shapes)
4. **Arena:** When everyone submits, monsters battle in real-time!

## Game Mechanics

### How Drawing Affects Stats

| Draw This | Stat | Effect in Battle |
|-----------|------|------------------|
| **Large, filled shape** | HP | More health (60-150) |
| **Sharp, jagged edges** | Spikes | Deal more collision damage |
| **Round, symmetrical** | Stability | Take less damage, resist knockback |
| **Long protrusions** | Speed | Move faster across arena |

### Combat System

- **Collision damage** = attacker's spikes − defender's stability (1-15 dmg)
- **Knockback** = Based on relative spikes vs stability
- **Low HP boost** = Shapes get faster as they lose health (up to 3x speed)
- **Blast ability** = Push all nearby shapes away (10s cooldown)

### Arena Events

- 🟢 **Health packs** spawn periodically — touch them to heal
- ⚡ **Speed boost** every 6 seconds — all shapes get faster
- 🔲 **Arena shrinks** over time — stay inside or take damage!

### Tips

- Draw a **star** for high damage but low stability
- Draw a **circle** for tankiness and knockback resistance  
- Draw **tentacles/legs** for speed to chase or escape
- Use **Blast** to push enemies into the shrinking border!

## Deploy to Render

- **Build Command:** `npm install`
- **Start Command:** `npm start`

## Bundle Size

Game: ~8 KB (under 15 KB requirement)
