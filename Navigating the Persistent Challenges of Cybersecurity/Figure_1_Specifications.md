# Figure 1: Conceptual Model of Systemic Cyber Failure

## Visual Specifications

### Layout: Hierarchical Flow Diagram
- **Orientation**: Bottom-to-top flow
- **Size**: Recommended 800x600 pixels minimum
- **Color Scheme**: Professional blues and grays with red for "Normal Accidents"

### Components:

#### 1. BASE LAYER - "Wicked Problems" (Bottom)
```
Three interconnected boxes at the base:
┌─────────────────────┐    ┌─────────────────────┐    ┌─────────────────────┐
│   Human Element     │    │ Economic Incentives │    │ Inherent Complexity │
│                     │    │                     │    │                     │
│ • Unpredictability  │    │ • Market Failures   │    │ • Software Bugs     │
│ • Social Engineering│    │ • Misaligned Goals  │    │ • System Integration│
│ • Human Error       │    │ • Cost Pressures    │    │ • Legacy Systems    │
└─────────────────────┘    └─────────────────────┘    └─────────────────────┘
```

#### 2. MIDDLE LAYER - "System Conditions"
```
Two larger interconnected boxes:
┌─────────────────────────────────┐    ┌─────────────────────────────────┐
│     High Interactive            │    │        Tight Coupling           │
│       Complexity                │◄──►│                                 │
│                                 │    │ • Real-time Dependencies        │
│ • Multiple System Interactions  │    │ • Cascading Failures           │
│ • Unpredictable Combinations    │    │ • Limited Response Time        │
│ • Network Effects               │    │ • Global Interconnection       │
└─────────────────────────────────┘    └─────────────────────────────────┘
```

#### 3. TOP LAYER - "Normal Accidents" (Results)
```
Three red-colored outcome boxes:
┌───────────────────┐    ┌───────────────────┐    ┌───────────────────┐
│  Supply Chain     │    │   Ransomware      │    │  Large-Scale      │
│    Attacks        │    │   Outbreaks       │    │   Breaches        │
│                   │    │                   │    │                   │
│ • Log4j Incident  │    │ • Hospital Systems│    │ • Colonial Pipeline│
│ • SolarWinds      │    │ • Critical Infra. │    │ • Equifax         │
└───────────────────┘    └───────────────────┘    └───────────────────┘
```

#### 4. AMPLIFIER ELEMENT (Side)
```
Separate element with arrows pointing to the middle layer:
┌─────────────────────────────┐
│    Systemic Amplifiers      │ ─────┐
│                             │      │
│ • AI & Machine Learning     │      ▼
│ • Quantum Computing         │   ACCELERATION
│ • IoT Proliferation         │      ▼
│ • 5G/6G Networks           │ ─────┘
└─────────────────────────────┘
```

### Arrows and Flow:
1. **Upward arrows** from each "Wicked Problem" to both "System Conditions"
2. **Bidirectional arrow** between the two "System Conditions" boxes
3. **Upward arrows** from "System Conditions" to "Normal Accidents"
4. **Curved arrows** from "Systemic Amplifiers" pointing to the connections between layers

### Colors:
- **Wicked Problems**: Light blue (#E3F2FD)
- **System Conditions**: Medium blue (#1976D2)
- **Normal Accidents**: Red (#D32F2F)
- **Systemic Amplifiers**: Orange (#FF9800)
- **Arrows**: Dark gray (#424242)
- **Text**: Black (#000000)

## Implementation Code Examples:

### For Draw.io (XML format snippet):
```xml
<mxCell id="wicked1" value="Human Element&#xa;• Unpredictability&#xa;• Social Engineering&#xa;• Human Error" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#E3F2FD;" vertex="1" parent="1">
  <mxGeometry x="60" y="300" width="120" height="80" as="geometry" />
</mxCell>
```

### For Lucidchart (Text description):
1. Create three rectangles at bottom labeled "Human Element", "Economic Incentives", "Inherent Complexity"
2. Add bullet points as described above
3. Create two larger rectangles in middle for system conditions
4. Add three rectangles at top for normal accidents
5. Add connecting arrows as specified
6. Apply color scheme as described

This diagram will visually demonstrate how fundamental "wicked problems" create system conditions that inevitably lead to "normal accidents," with emerging technologies acting as amplifiers.
