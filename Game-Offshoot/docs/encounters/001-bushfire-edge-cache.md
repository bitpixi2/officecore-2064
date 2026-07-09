# Encounter 001: Bushfire Edge Cache

## Premise

A bushfire is moving toward a regional edge data centre outside a half-empty service town. The facility keeps evacuation comms, community maps, volunteer rosters, water-point updates, and a Hackeroos event feed online.

Official systems are overloaded. The road authority map is stale. The data-centre operator is worried about uptime optics. Local firefighters need clear comms more than another press statement. Rooby is on comms and has started routing volunteers, but every useful update creates more pings, questions, and public attention.

The campervan crew must keep people connected while moving through smoke, heat, failing cooling, road closures, and awkward corporate PR.

## Run Time

Designed for 45 to 75 minutes.

## Starting Resources

- `Charge 3`
- `Trust 3`
- `Smoke 2`
- `Heat 1`
- `Signal 2`

Raise `Smoke` when visibility, air quality, panic, or road access worsens.

Raise `Heat` when officials, corporate comms, security, or public blame tighten around the crew.

## Cold Open

Read or paraphrase:

```text
The servo sign says HOT FOOD, COLD DRINKS, CLEAN TOILETS.

Only one of those claims is still true.

Ash falls across the windscreen like grey receipt paper. The highway west is closed, the highway east is lying about being open, and every phone in the convoy buzzes at once.

Rooby posts: "Edge cache temperature warning. Evac map sync delayed. Also somebody has tagged Hackeroos in a thread titled WHO IS IN CHARGE HERE."

The data centre is twelve minutes away if the road stays real.
```

Ask each player:

- What does your rig look like in the smoke?
- What office object is rattling, melting, or sliding around?
- Who are you trying not to worry about?

## Locations

### Servo Command Post

A service station carpark has become an accidental civic desk. There are folding tables, extension leads, handwritten lists, two firefighters, three people arguing about maps, and one teenager calmly labelling water bottles.

Use for: triage, public promises, charging, gossip, emotional reveals.

Pressure: everyone wants certainty, and the crew only has useful uncertainty.

### Smoke-Choked Highway

The highway flickers between open, closed, and "technically passable if you are the kind of person who owns a roof-mounted thermal camera."

Use for: convoy movement, route finding, rescues, equipment strain.

Pressure: each delay increases `Smoke` or costs `Charge`.

### Edge Data-Centre Perimeter

A low, clean building behind a fence, pretending it is not terrified. The cooling system is fighting heat, ash, and a maintenance deferral that no dashboard wanted to name.

Use for: access negotiation, cooling repairs, facility diagnosis, corporate tension.

Pressure: security wants procedure, operations wants uptime, the town wants maps.

### Emergency Mesh Relay

A temporary relay on a hill, water tower, council shed, or tall sign that should not have to carry this much traffic.

Use for: signal scenes, climbing, patching, remote coordination, Rooby alerts.

Pressure: getting the relay working makes the crew more visible.

### Campervan Convoy

The moving office itself: rattling mugs, bad air, heated glances, dashboard lights, radio chatter, and someone insisting this is a perfectly valid meeting room.

Use for: bonding, Spark Tokens, private choices, mobile repairs.

Pressure: no rig can be everywhere.

## Factions

### Local Firefighters

They are tired, practical, and allergic to performative heroics. They need clear updates, clear roads, and nobody making the fire about their brand.

Want: safe movement, reliable comms, fewer idiots.

Useful offer: access to field observations and priority route warnings.

### Council Comms Team

Two staff, one borrowed tablet, one dying power bank, and a public page everyone keeps refreshing.

Want: a trustworthy update stream and language that will not cause panic.

Useful offer: legitimacy, local contacts, access to community lists.

### Data-Centre Operator

The facility team are not villains. They are overworked, under-briefed, and being pinged by corporate comms people who think "edge" means "somewhere else".

Want: uptime, safety, no viral footage of a server room full of smoke.

Useful offer: facility access, logs, spare power, a quiet room with excellent aircon if the cooling survives.

### Stranded Makers

Hackeroos-adjacent builders, cyberdeck people, students, and helpful locals caught between wanting to help and wanting to livestream.

Want: meaningful tasks, safety, recognition, snacks.

Useful offer: spare parts, batteries, cameras, hands, chaotic enthusiasm.

### Rooby On Comms

Rooby is routing alerts, volunteer offers, event-feed updates, and awkward social messages faster than one crew can triage.

Want: keep helpers useful, keep information moving, keep Hackeroos from becoming the headline for the wrong reason.

Useful offer: leads, warnings, volunteer matches, public posts, reminders nobody asked for but everyone needed.

## Clocks

Use four-segment clocks. Mark one segment when a miss, delay, or hard choice points at that pressure.

- `Fire Front Arrives`
- `Cooling Fails`
- `Evac Map Goes Stale`
- `Public Blame Finds A Target`

When a clock fills, make the consequence concrete but playable. No dead ends. Create harder choices.

## Challenge Menu

Pick three to five, depending on time.

### Restore Mesh Signal

The emergency relay is dropping packets and duplicating stale map updates.

Likely rolls: `Signal`, `Spark`, `Drift`

Costs:

- spend `1 Charge`
- increase `Heat` because the fix is visible
- split the convoy between relay and servo

Success means: restore `+1 Signal`, update the evacuation map, and reveal one hidden pressure.

### Cool Overheated Racks

The data centre cooling is failing unevenly. One row is fine. One row is cooking. The dashboard says everything is mostly acceptable, which is how everyone knows it is not.

Likely rolls: `Signal`, `Spark`, `Grit`

Costs:

- damage or strain a van module
- accept a facility access condition
- take responsibility for a workaround in writing

Success means: delay `Cooling Fails`, gain a data-centre access token, and learn what system is most important.

### Negotiate Access

Security will not let a convoy of mobile weirdos near critical infrastructure just because they have useful tools and alarming confidence.

Likely rolls: `Charm`, `Signal`, `Grit`

Costs:

- someone signs a temporary liability form
- the crew must work under observation
- corporate comms gets a quote they will misuse

Success means: one controlled entry, one staff ally, or one sanctioned remote patch.

### Move People

A group of stranded locals and makers need transport, power, or reliable directions before the road status changes again.

Likely rolls: `Drift`, `Grit`, `Charm`

Costs:

- spend `1 Charge`
- leave gear behind temporarily
- create a bond with someone inconvenient

Success means: gain `+1 Trust` and reduce panic at the servo.

### Preserve Community Data

Volunteer rosters, water-point data, medication delivery notes, and evacuation updates are split across failing devices and unofficial spreadsheets.

Likely rolls: `Signal`, `Charm`, `Spark`

Costs:

- reveal private information that needs careful handling
- create a new public process
- attract a person who wants control of the ledger

Success means: the crew creates a trusted cache and names the temporary office responsible for it.

### Contain The Public Thread

The question "Who is in charge here?" is gaining momentum online.

Likely rolls: `Charm`, `Signal`

Costs:

- someone becomes the face of the response
- Rooby posts too clearly and starts a new argument
- the best update is emotionally honest, not polished

Success means: lower `Heat` by `1` or convert it into `Trust`.

## Specialty Spotlights

- `Signal Runner`: find the cleanest route through overloaded comms.
- `Patch Ratchet`: keep one failing module alive for one more scene.
- `Vibe Broker`: turn a carpark argument into a working queue.
- `Bushwire Scout`: identify the safest ugly route.
- `Compliance Bard`: invent the temporary authority everyone can live with.
- `Data-Centre Whisperer`: name what fails next before the dashboard admits it.
- `Rooby Rancher`: decide whether Rooby's next alert is clean, messy, or public.

## Rewards

Give two or three at the end.

- New van module: ash-filter intake, relay mast, thermal camera, rack-cooling duct, public-address kettle, laminated crisis desk.
- Local trust: `+1 Trust` at the start of the next regional encounter.
- Data-centre access token: one future scene can begin inside infrastructure instead of outside the fence.
- Hackeroos reputation boost: Rooby can call in extra volunteers once next session.
- Relationship spark: two characters update or add a bond.
- Office artifact: signed access form, melted badge, smoke-stained map, receipt-paper route printout.

## Ending Questions

Ask before closing:

- What did your rig smell like afterward?
- Who thanked you in a way that made things awkward?
- What did Rooby post that nobody approved but everyone secretly liked?
- Which system is still fragile?
- What new department did the crew accidentally create?

## Follow-Up Hooks

- The access token works in more places than it should.
- The stale map was not just stale; someone filtered it.
- A corporate comms person wants the crew for a branded resilience story.
- A firefighter quietly asks for help with a private data problem.
- A stranded maker wants to join the convoy with a half-built device and too much confidence.
