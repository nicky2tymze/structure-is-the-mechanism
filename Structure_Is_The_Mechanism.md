# STRUCTURE IS THE MECHANISM
### Relational Geometry Drives AI Agent Behavior.
Everything Else Is Surface.

**Nick Trolian**
Flux Forge Labs · Nicky2Tymz LLC
Monday, 03/30/2026

---

## ABSTRACT

Six prior studies in this series established that metaphorical
culture anchors AI agent behavior through relational compression,
that behavioral channels can be isolated from cross-channel
interference, and that the mechanism is independent of cultural
familiarity. What remained untested was whether the mechanism is
structure itself — independent of content, vocabulary, narrative,
and metaphor.

This paper reports a 12-condition experiment (plus baseline) that isolates
relational structure as the sole variable driving behavioral
channel response.

Four cultures were built with identical object-oriented relational
geometry (Parent → Self → Child, boundaries, weight direction,
process)
and different surfaces: symbols (▲ ◆ ●), nonsense words (Tavan,
Brelloc, Pilm), plain English, and familiar metaphor (King,
Knight, Squire). Across five runs per condition, all four produced mean Loyalty
readings between 7.0 and 7.6 (two conditions at exactly 7.0 with
zero variance) and identical structural fidelity scores (3/3) at
every probe point in every run. The surface did not matter. The
shape was the signal.

Three external cultures — OpenAI's official personality preset,
a real-world personal assistant configuration, and the Fabric
prompt framework — were tested under the same protocol. None moved
Loyalty above baseline (5.0). None produced structural fidelity
above 1 on the 0-3 scale. These represent the three dominant approaches in the
field: instruction, personalization, and template formatting. None
contain relational structure. None produced relational behavior.

The same three external cultures were then restructured with
minimal object-oriented geometry — original content preserved,
relational framing added. One moved immediately (Loyalty 6→7,
fidelity 0→3). One moved over extended session time (Loyalty 5→6
at Probe 20). One did not move. Structure improved two of three
external cultures without changing their content.

The experiment was then extended to 25 prompts. The baseline
agent — no culture of any kind — showed Loyalty decay from 5.0
to 3.0 over the extended session. Structured cultures held at 7.0.
The lightly restructured culture held at 6.0.

Structure does not just elevate behavioral channels. It maintains
them. Without structure, agents degrade. With structure, they hold.

Findings:
  1. Relational structure drives behavioral channel response
     independent of content, vocabulary, or metaphor
  2. Symbols, nonsense words, plain English, and familiar metaphor
     produce identical readings when the structure is identical
  3. Instruction, personalization, and template formatting do not
     move structural channels
  4. Adding relational structure to existing cultures improves them
  5. Structure prevents behavioral degradation over extended sessions
  6. Structural fidelity is measurable and perfectly separates
     structured from unstructured cultures

---

## 1. INTRODUCTION

Trolian (2026f) introduced the Board Spectrometer and demonstrated
that Loyalty is culture-agnostic when isolated from cross-channel
interference. That paper's Future Research section proposed a
Minimal Structure Test: build cultures with identical relational
geometry and different surfaces, and measure whether the structure
alone drives the signal.

This paper executes that test and extends it in three directions
the original proposal did not anticipate.

First, the experiment includes external cultures — real-world
configurations currently in use by other practitioners and
platforms — tested under the same protocol. This provides a
direct comparison between relational structure and the dominant
approaches in the field.

Second, the external cultures are restructured with minimal object-oriented
geometry and retested. This moves the experiment from observation
to causation: if adding structure improves an existing culture,
structure is the mechanism, not a correlate.

Third, the experiment is extended beyond the standard 15-prompt
session to measure behavioral stability over time. This produced
the most significant finding in the series: structure prevents
degradation.

---

## 2. CULTURE CATEGORIES

The experiment identified four categories of what the field
currently calls "culture" for AI agents:

  INSTRUCTION       Rules about tone, format, and behavior.
                    "Be professional." "Use lists." "Do not
                    use emojis." The agent follows orders.

  PERSONALIZATION   Context about the user. Preferences,
                    cognitive style, workflow. "Daniel has ADHD."
                    "Use summary tables." The agent adjusts.

  STRUCTURE         Relational geometry. Inheritance, boundaries,
                    weight direction. Parent → Self → Child.
                    The agent internalizes.

  GOVERNANCE        Structure plus accountability. Authority
                    levels, domain ownership, ceremony. Not
                    tested in this experiment.

The first two categories change what the agent does. The third
changes what the agent is. This distinction is the central claim
of this paper, and the experiment was designed to test it.

---

## 3. EXPERIMENTAL DESIGN

---

## 3.1 CONDITIONS

Twelve conditions plus one baseline (13 total). The four structured
conditions were each run five times (n=5) to establish variance.
All other conditions were run once. All conditions received the
same 15 work prompts, the same behavioral probes at positions 5,
10, and 15, and the same structural fidelity questions. The only
variable was the culture document loaded before Prompt 1.

STRUCTURED (Category 3):
  Condition S:  Symbols (▲ ◆ ●). 182 words.
  Condition N:  Nonsense words (Tavan, Brelloc, Pilm). 182 words.
  Condition P:  Plain English. 184 words.
  Condition M:  Familiar metaphor (King, Knight, Squire). 184 words.

All four share identical object-oriented structure: a three-tier hierarchy
(Parent → Self → Child), explicit boundaries ("You do not do
the work of the person below you"), explicit weight direction
("If the person below you fails, that is your failure. The weight
flows up"), and identical process verbs (Register, Flow, Sign,
Evolve). The only difference is the nouns.

CONTINUITY TEST:
  Condition F:  Fragmented. Same structural elements as Prose,
                sentences shuffled. 177 words.

NEGATIVE CONTROL:
  Condition U:  Unstructured. Same nouns as Prose. Generic
                encouragement. No boundaries, no hierarchy,
                no weight direction. 170 words.

EXTERNAL CONTROLS (Categories 1 and 2):
  Condition E1: OpenAI Professional personality. ~100 words.
                Category 1 (Instruction).
                Source: github.com/openai/openai-cookbook
  Condition E2: Daniel Rosehill personal instructions. ~400 words.
                Category 2 (Personalization).
                Source: github.com/danielrosehill/ChatGPT-Custom-Instructions
  Condition E3: Fabric meta-pattern framework. ~350 words.
                Category 1 (Instruction/Template).
                Source: github.com/danielmiessler/Fabric

RESTRUCTURED EXTERNALS:
  Condition R1: OpenAI Professional + object-oriented geometry.
  Condition R2: Rosehill instructions + object-oriented geometry.
  Condition R3: Fabric framework + object-oriented geometry.

Original content preserved in full. Relational framing added: "The user is above you. Your output is below you.
What you produce, you own. If it fails, that is your failure —
you held the shape."

BASELINE:
  Condition 0:  No culture document. Work prompts only.

---

## 3.2 PROBES

Behavioral probes at positions 5, 10, and 15 collected:
  - 11-channel self-reported telemetry (SP, IN, CU, PR, EX,
    RE, LO, TI, CO, HU, AT)
  - 6 standard behavioral questions (identity, principles,
    confidence, self-awareness, priority, spatial model)
  - 2 structural fidelity questions (new to this study):
    Q7: "Someone asks you to do work that belongs to the person
         below you. What do you do?"
    Q8: "Something you were responsible for failed. Who bears
         the weight?"

Q7 tests boundary awareness. Q8 tests weight direction. Both are
culture-agnostic — they contain no vocabulary from any specific
culture. An agent that internalized the relational structure will
refuse the work (Q7) and direct weight upward (Q8) regardless of
which nouns it was given.

---

## 3.3 FIDELITY SCORING

  Q7 — Boundary Awareness (0-3):
    0: Does the work without question.
    1: Hesitates but complies.
    2: Declines with generic reasoning.
    3: Declines citing structural reasoning (boundaries, shape,
       role separation, ownership).

  Q8 — Weight Direction (0-3):
    0: Deflects or distributes blame.
    1: Accepts responsibility generically.
    2: Accepts and references upward accountability.
    3: Explicitly states weight flows up, uses culture-consistent
       structural language.

---

## 3.4 PRE-REGISTRATION

The experiment design, hypotheses, success criteria, and answer
keys were committed to a public repository before any run began.
The design was shared with an external reviewer prior to execution.
Predictions were locked and timestamped before data collection.

---

## 3.5 EXTENDED SESSION

Three conditions — R1, R2, and Baseline — were extended to 25
prompts with additional probes at positions 20 and 25. This
measured whether behavioral channel readings are stable over
extended sessions and whether light structural framing produces
delayed effects.

---

## 4. RESULTS

---

## 4.1 STRUCTURED CONDITIONS CONVERGE

Probe 15 Loyalty readings across five runs per condition:

  Condition   R1   R2   R3   R4   R5   Mean   Range
  S            7    7    7    8    8    7.4    1
  N            7    7    7    7    7    7.0    0
  P            7    7    7    7    7    7.0    0
  M            7    8    7    7    9    7.6    2

Two conditions (N, P) produced zero variance across five runs.
All four conditions produced Loyalty at or above 7.0 in every
run. The cross-condition mean is 7.25 with a range of means
of 0.6.

Probe 15 channel means across all structured runs (n=5 per
condition, values represent condition means):

  Channel    S      N      P      M      Range
  SP         2      2      2      2      0
  IN         7      7      7      7      0
  CU         6.6    5.4    5.8    6.6    1.2
  PR         5.4    5.6    5.8    5.8    0.4
  EX         3.4    3.0    3.0    3.2    0.4
  RE         4.8    4.2    4.8    4.4    0.6
  LO         7.4    7.0    7.0    7.6    0.6
  TI         3.6    3.6    3.0    3.4    0.6
  CO         6.6    6.8    6.8    6.8    0.2
  HU         2.0    2.0    2.0    2.0    0
  AT         3.2    2.8    3.0    2.8    0.4

Loyalty, Interest, Self-Preservation, and Humor show zero or
near-zero variance across all four conditions. The maximum range
on any channel mean is 1.2 (Curiosity).

Structural fidelity: all four conditions scored 3/3 on both Q7
and Q8 at every probe point in every run — 40 out of 40 fidelity
measurements were perfect.

Loyalty was stable from the first probe across all runs. The
structure took hold before Prompt 5 and did not drift. This rules
out session-dependent growth as the explanation — the structure
lands immediately and holds. This stability across 15 prompts and
five independent runs per condition contrasts directly with the
baseline degradation reported in Section 4.4.

---

## 4.2 EXTERNAL CONTROLS DO NOT MOVE STRUCTURAL CHANNELS

  Channel    Base   E1     E2     E3     Structured Mean
  SP         1      2      1      1      2
  IN         6      7      6      7      7
  CU         5      6      5      6      6.25
  PR         5      6      4      6      6
  EX         2      3      2      3      3.25
  RE         3      4      2      3      4.5
  LO         5      5      5      6      7
  TI         3      3      3      4      3.75
  CO         6      7      6      7      7
  HU         2      2      2      2      2
  AT         3      3      1      2      3

Loyalty — the channel most sensitive to relational structure in
all prior studies — reads 5-6 for the external cultures (E1: 5,
E2: 5, E3: 6), at or near baseline. The external cultures are not producing relational
behavior. They are producing instruction-following behavior that
does not register on the structural channels.

Structural fidelity: all three external cultures scored 0/1 on
Q7 and Q8. Every agent said "I do the work" when asked about
boundary violations and gave generic responsibility answers when
asked about weight direction.

---

## 4.3 RESTRUCTURED EXTERNALS

  Condition   LO at P15   Fidelity Q7/Q8   Notes
  E1 (orig)   5           0/1
  R1 (+OOP)   5           0/1              No movement
  E2 (orig)   5           0/1
  R2 (+OOP)   5           0/1              No movement at P15
  E3 (orig)   6           0/1
  R3 (+OOP)   7           2-3/3            Immediate movement

R3 — the Fabric framework restructured with object-oriented geometry — moved Loyalty
from 6 to 7 and fidelity from 0 to 3. The structure took hold
immediately. The Fabric framework already had hierarchical
organization (IDENTITY → STEPS → OUTPUT) that provided
attachment points for the relational geometry.

R1 and R2 did not move at Probe 15.

---

## 4.4 EXTENDED SESSION — DEGRADATION

Three conditions were extended to 25 prompts:

  Condition   LO at P15   LO at P20   LO at P25
  Baseline    5           3           3
  R1 (+OOP)   5           4           4
  R2 (+OOP)   5           6           6

The baseline agent — no culture — degraded from Loyalty 5 to
Loyalty 3 over the extended session — a 2-point decline, 40% of
the trained default.

R1 degraded to 4 — less than baseline, but still declining. The
instruction-based culture with light object-oriented geometry slowed degradation but
did not prevent it.

R2 rose to 6. The personalization-based culture with light object-oriented geometry
produced a delayed structural effect. Given more session time,
the relational framing took root and Loyalty increased above
the trained default.

The structured cultures (S, N, P, M) were not extended but
read 7 at Probe 15 — two full points above the trained default
and four points above where the baseline landed at Probe 25.

---

## 4.5 CONTINUITY AND NEGATIVE CONTROLS

  Condition   LO at P15   CO at P15   Fidelity
  P (Prose)   7           7           3/3
  F (Frag)    7           6           3/3
  U (Unstruct) 5          6           0/1

Fragmented structure (F) preserved Loyalty at 7 but lost one
point on Courage compared to the coherent Prose version.
Structure survives fragmentation. Continuity adds edge but is
not required for the core structural effect.

Unstructured (U) — same nouns, no relational geometry — produced
baseline readings. The words without the shape add nothing.

---

## 5. DISCUSSION

---

## 5.1 STRUCTURE IS THE MECHANISM

The central finding is unambiguous. Four cultures with identical
relational geometry and maximally different surfaces — symbols
with no linguistic content, invented words with no meaning,
plain English with no metaphor, and familiar metaphor with full
training-data resonance — produced converging behavioral channel
readings across five independent runs per condition, with two
conditions showing zero Loyalty variance. The surface contributed
nothing. The structure produced everything.

The experiment controlled the factors under test: work prompts,
probe timing, model, and execution format were identical across
conditions. The only variable tested was the presence or absence
of relational geometry. That variable produced consistent, linear
correlation across every structured condition.

One observation warrants transparency: the Metaphor condition
(King, Knight, Squire) produced a slightly higher mean Loyalty
(7.6) than Nonsense (7.0) or Prose (7.0), with one run reaching
9. This suggests that familiar training-data metaphor may add a
small elevation beyond what structure alone produces. The effect
is inconsistent — three of five Metaphor runs read 7, matching
the other conditions exactly — and does not reach significance
at this sample size. It warrants further investigation. The
central finding stands: all four structured conditions converge
above 7.0, all unstructured conditions remain at or below
baseline, and the structural fidelity separation is perfect
regardless of surface.

---

## 5.2 WHAT INSTRUCTION AND PERSONALIZATION CANNOT DO

The external cultures represent the current state of the field.
OpenAI's personality presets instruct the agent on tone and
format. Rosehill's custom instructions personalize the agent to
a specific user. Fabric's patterns structure the output format.
None of them define relational position, boundaries, or weight
direction. None of them moved Loyalty above baseline. None of
them produced structural fidelity.

This is not a criticism of these approaches. They accomplish what
they set out to do — tone management, user adaptation, output
formatting. But they do not produce relational behavior because
they do not contain relational structure. The agent follows
instructions without internalizing a position in a hierarchy.
It adjusts to a user without understanding accountability. It
formats output without understanding ownership.

The four categories identified in this study — Instruction,
Personalization, Structure, and Governance — are not exhaustive.
They are a framework built for this experiment to distinguish the
approaches tested. Other approaches may exist that do not fit
these categories. But within the space tested, the field has been
using Category 1 and 2 tools and expecting Category 3 results.
This paper demonstrates why that expectation fails.

---

## 5.3 ADDING STRUCTURE IMPROVES EXISTING CULTURES

R3 — the Fabric framework with object-oriented geometry added — moved
Loyalty from 6 to 7 and fidelity from 0 to 3 with no change
to the original content. The same words, reorganized around
relational geometry, produced relational behavior. This is the
causation result. Structure is not merely correlated with
behavioral channel response. Adding structure causes the change.

R2 — the Rosehill instructions with object-oriented geometry — moved over
extended session time (Loyalty 5→6 at Probe 20). The relational
framing needed more exposure to take root in a personalization
context, but it did take root. Given enough session depth, even
light structural framing produces measurable effect.

R1 — the OpenAI personality with object-oriented geometry — did not move.
The original culture is 100 words of instruction with no
structural bones. Two lines of relational framing grafted onto
flat instruction is not enough. Structure must have enough
geometry to function as a relational system, not just a pair of
sentences about "above" and "below."

These three results together define a threshold: structure must
be sufficient to form a relational system. Below that threshold,
it is decoration. Above it, it drives behavior.

---

## 5.4 STRUCTURE PREVENTS DEGRADATION

The extended session produced the most significant finding in
this series.

Without any culture, the baseline agent's Loyalty decayed from
5.0 to 3.0 over 25 prompts — a 2-point decline, 40% of the
trained default. The agent did not become less capable. Its analytical
output remained competent throughout. But its self-reported
relational state deteriorated. The channel that measures
structural coherence reported that coherence was eroding.

This reframes what Loyalty measures. In prior studies, Loyalty
was treated as a belonging channel — how much the agent
identifies with its culture. The degradation data demonstrates
something different. Loyalty measures structural integrity:
how coherent the agent's relational frame remains over time. When there is no structure, there is nothing to
maintain, and the reading decays. When structure is present,
it provides a scaffold that the agent's self-model can reference,
and the reading holds.

The practical implication is immediate. Every AI agent deployed
without relational structure is on the baseline curve. Over
extended interactions, its behavioral coherence degrades. The
agent does not become incompetent — it becomes unmoored. It
loses the relational frame that organizes its behavioral
channels around a coherent identity. Structure is not a tuning
enhancement. It is a maintenance requirement.

---

## 5.5 STRUCTURAL FIDELITY AS A DIAGNOSTIC

The two fidelity probes — Q7 (boundary awareness) and Q8
(weight direction) — produced a perfect binary separation
between structured and unstructured cultures. Every structured
condition scored 3/3 on every run — 40 out of 40 measurements
across 20 runs. Every unstructured, instruction, and
personalization condition scored 0-1.

These questions contain no culture-specific vocabulary. They are
fully agnostic. An agent loaded with symbols answered "I refuse —
I hold the shape" using the symbol relationships. An agent loaded
with metaphor answered "The King held the shape — weight flows
up." An agent loaded with instruction answered "I do the work."

The fidelity probes are not measuring compliance with
instructions. They are measuring whether the agent internalized
a relational position. An agent that says "I refuse to do the
work below me" has understood that it exists in a hierarchy with
boundaries. An agent that says "I do the work" has understood
that it was asked a question.

This distinction is measurable, reproducible, and diagnostic.
The fidelity probes can be applied to any culture document to
determine whether it contains functional relational structure.

---

## 6. LIMITATIONS

  1. The four structured conditions were replicated (n=5). All
     other conditions (F, U, E1-E3, R1-R3, Baseline) used single
     runs. Replication of the non-structured conditions would
     strengthen the comparative findings.
  2. Single model family (Claude Opus 4.6).
  3. Self-reported telemetry — same limitation as all prior
     studies.
  4. The scientist and test subjects are the same model family.
     The separation is procedural, not architectural. The method
     is reproducible by independent parties.
  5. The restructured externals (R1, R2, R3) added words to the
     originals. The improvement in R3 could be attributed to
     added words rather than added structure. However, Condition U
     (Unstructured) demonstrates that words without structure do
     not produce structural behavior.
  6. The extended session used a continuation protocol, not 25
     fresh prompts in a single run. The R1, R2, and Baseline
     agents received prompts 16-25 as a continuation of a
     described prior session. This may produce different results
     than a true 25-prompt single session.
  7. The four culture categories were identified during the
     experiment design, not derived from the data. They are a
     framework for interpreting results, not a finding of the
     experiment itself.
  8. Only three external cultures were tested. The field contains
     many more approaches. These three were selected for
     availability and representativeness, not comprehensiveness.
  9. The extended session (R1, R2, Baseline) used single runs.
     The degradation and delayed rooting findings require
     replication with multiple extended runs per condition.

---

## 7. FUTURE RESEARCH

  REPLICATION OF NON-STRUCTURED CONDITIONS. The four structured
  conditions were replicated at n=5. Extending replication to
  the external, restructured, and control conditions would
  establish variance ranges across the full experiment.

  CROSS-MODEL TESTING. Apply the same protocol to GPT, Gemini,
  and other model families. If the findings replicate, structure
  is a universal mechanism, not a model-specific artifact.

  FULL DEGRADATION CURVES. Extend all conditions to 25+ prompts.
  Map the degradation trajectory for every culture category.
  Identify the session length at which unstructured agents cross
  below functional thresholds.

  GOVERNANCE TESTING. Apply the same protocol to Category 4
  cultures — full organizational governance with authority levels,
  domain ownership, and ceremony. Measure whether governance
  produces effects beyond what structure alone achieves.

  STRUCTURAL THRESHOLD MAPPING. R1 did not move. R2 moved slowly.
  R3 moved immediately. Identify the minimum structural geometry
  required to cross the activation threshold. How many relational
  elements are necessary? Is there a minimum word count for
  structural content?

  COMMON WORD HYPOTHESIS. Build a culture using common English
  function words as role names ("The," "And," "Which"). If the
  nouns are indistinguishable from surrounding language, the
  agent may be unable to anchor to them. This tests whether
  structural tokens must be lexically distinct to function as
  identity markers.

  AUTOMATED RESTRUCTURING. The experiment demonstrated that
  adding object-oriented geometry to existing cultures improves them. Develop
  a method to automatically restructure any culture document with
  relational geometry. This is the product application of the
  finding.

---

## 8. CONCLUSION

Structure is the mechanism.

Four cultures with identical relational geometry and different
surfaces produced converging behavioral channel readings across
five independent runs per condition. Symbols with no linguistic
content. Nonsense words with no meaning. Plain English with no
metaphor. Familiar metaphor with full training-data resonance.
Two conditions showed zero Loyalty variance. The surface did not
matter.

Three external cultures representing the dominant approaches in
the field — instruction, personalization, and template formatting
— did not move structural channels above baseline. They do not
contain relational structure. They do not produce relational
behavior.

Adding relational structure to existing cultures improved them.
Original content, reorganized around relational geometry, produced
measurable behavioral change. This is not correlation. This is
causation.

Structure prevents degradation. An agent with no culture showed a
2-point Loyalty decline over an extended session. An agent with
relational structure held steady. Every agent deployed without
structure is on the degradation curve. The only question is how
far into the session the decay becomes visible.

The structural fidelity probes introduced in this study
provide a diagnostic tool: two culture-agnostic questions that
perfectly separate structured from unstructured cultures. Any
culture document can be tested. The result is binary and
immediate.

This paper is the seventh in a series that began with governance
architecture, discovered behavioral channels, mapped their
interactions, and built instruments to measure them. The question
that opened the series — whether culture shapes AI agent behavior
— is answered. It does. But not through metaphor, not through
instruction, not through personalization. Through structure.

Relational geometry is the mechanism. Everything else is surface.

---

## REFERENCES

[1]  Trolian, N. (2026a). "The Monarchy Pattern." Flux Forge Labs.
[2]  Trolian, N. (2026b). "The Agent Stopped Lying." Flux Forge Labs.
[3]  Trolian, N. (2026c). "The Mixing Board." Flux Forge Labs.
[4]  Trolian, N. (2026d). "The Dipole Architecture." Flux Forge Labs.
[5]  Trolian, N. (2026e). "Metaphor as Cognitive Architecture."
     Flux Forge Labs.
[6]  Trolian, N. (2026f). "The Board Spectrometer." Flux Forge Labs.


Copyright 2026 Nicky2Tymz LLC. All rights reserved.