# A general strategy for mathematical research

*Version 1.6, 2026-10-29. Covers problem solving, theory building, and exploratory research. A research operating policy, not a validated predictor of mathematical breakthroughs. Changes are listed in §12.*

**Purpose:** spend limited research effort on consequential, checkable mathematical progress: solving problems, developing useful concepts and theories, and discovering which questions and structures deserve further work. Preserve room for difficult, unconventional ideas and for exploration whose conclusions cannot be predicted in advance.

**Evidence convention:**

- (+) logically supported, or supported by the cited source;
- (~) a plausible recommendation with uncertain effectiveness;
- (-) an untested conjecture.

All operating defaults, budgets and decision rules are **(~), unsourced design choices** unless stated otherwise: not shown false, but not shown effective. Definitions and templates are conventions. §10.4 lists each rule's basis and what would count against it.

**Scope:** one researcher or a small team, possibly using AI and computation. External review is valuable for consequential claims; lack of a reviewer does not prohibit exploration, but remains visible in review status. The optional formal policy pilot (§10.3) has additional reviewer requirements. Adjust the policy to expertise, resources, research mode, and goals.

## 0. The operating checklist

Use this section during work. Consult later sections when a decision needs more detail. Start with the lightweight profile (§9.3); use forecast and miss-count machinery only when explicitly selected.

1. **Name the objective and research mode (§1.1).** State:
   - the question, candidate structure, or bounded area of uncertainty;
   - the intended contribution or capability to develop;
   - the closest comparison;
   - the available effort.
2. **Locate the uncertainty.** Is the immediate obstacle truth, proof, novelty, definition choice, the right question, the applicability of a tool, or insufficient understanding?
3. **Map only enough to choose the next action.** Record relevant results, candidate definitions, contrasting examples, reductions, observations, and known failures. Mark provisional entries.
4. **Choose a small portfolio.** Normally:
   - one deep path;
   - a bounded probe queue;
   - enough verification capacity for the claims being produced.
5. **Specify the next probe and its expected change.**
   - State what will be examined, within what scope and effort, and how different findings could affect the next choice.
   - Record the intended artifact and completion criterion. A discovery probe may commit to a search or comparison without predicting its conclusion (§6.1).
6. **Do the mathematical work.** Protect uninterrupted time for proving, constructing, experimenting and learning.
7. **Review the change in knowledge or capability.** Separate whether the planned work was completed from what it established. Compare the next increment with the best feasible alternative. Then decide: continue, revise, park, close, consolidate, or change research mode.
   - Ask the fresh-proposal question (B4).
   - In the accountable profile, classify checkpoints under B1 and apply B2 after two consecutive counted misses.
   - Use B3 when examples, vocabulary, axioms, or formalism grow without a corresponding gain in understanding or capability.
8. **Keep a compact record.**
   - Save the mathematical finding, its scope, its uncertainty and the next action.
   - Update only the affected map entries.
   - Use the short probe card; add detail only when dependency, resource, or review needs justify it (§9.3).

**Three non-negotiable distinctions:**

- (+) A failed attempt is not a proof that a method family cannot work.
- (+) A correct result need not be new, and a new statement need not be correct.
- (+) An experiment that finds no counterexample is not, by itself, a universal proof.

**Strongest objection to this policy:** process controls can reward legible, short-term progress and suppress the immersion hard mathematics requires. Responses: tiered documentation with an overhead allowance; protected deep-work periods; reviews as allocation decisions, not termination dates; defaults overridable with a recorded reason; and a pilot that treats overhead and fragmented deep work as failure modes (§10.3).

## 1. Define success without imposing a universal ranking

Choose a primary contribution and acceptable secondary outcomes. Their relative value depends on the project.

| Contribution | Evidence needed to establish the claimed advance |
| --- | --- |
| Full solution or counterexample | Exact statement, complete argument, and comparison with the current problem formulation |
| Extension to new objects | A proved class distinction or noncoverage example, plus the new theorem |
| Quantitative improvement | A named bound and a nonempty parameter regime where the new bound improves it |
| Simpler or more effective proof | A precise advantage: assumptions removed, explicit construction, computability, reduced dependencies or measurable complexity |
| New reduction or equivalence | Direction of each implication, hypotheses, proof and the benefit of the new target |
| New invariant or framework | A defined object and a demonstrated consequence, discriminating test or reusable capability |
| Method limitation | An explicitly delimited method family and a proved obstruction applying to it |
| Reusable partial result | Exact hypotheses and a named downstream use |
| Exploratory finding | A reproducible observation, failed attempt or narrowed question with clearly limited claims |

A counterexample, a reduction or a reusable method may be more valuable than a small class extension. Use a project-specific ordering of contributions rather than a fixed ladder.

**Novelty is multidimensional.** A known conclusion can still admit a valuable new proof, so record what is actually claimed to be new. Educational rediscovery is also legitimate when learning is the stated objective.

### 1.1 Choose a research mode; allow explicit transitions

These modes describe the next increment, not the permanent identity of a project. A program can contain all three. Theory building and exploration need not serve a preselected conjecture.

| Mode | Starting commitment | Typical progress evidence | What not to demand prematurely |
| --- | --- | --- | --- |
| Problem solving | A reasonably stable statement or quantitative target | Proof, counterexample, useful reduction, improved bound, or scoped obstruction | That every probe resolve the target |
| Theory building | A family of phenomena and a proposed organizing question or structure | Definitions with consequences, explanatory comparisons, reusable constructions, representation or equivalence results, or demonstrated limits | A complete axiom system, classification theorem, or final application at inception |
| Exploratory research | A bounded area, tension, unfamiliar object, or uncertain question | Documented pattern, discriminating examples, revised taxonomy, failed conjectures, precise new question, or informative inconclusive search | A fixed conjecture, binary verdict, or novel positive result |

**Mode changes:** record what prompted the change, what is retained, and what new obligation follows. A pattern becomes a problem-solving path when an exact conjecture and comparison are fixed; a theory claim requires consequences and boundary tests. A refuted conjecture can return the work to exploration without invalidating the whole program.

Change mode when the mathematical question materially changes, not to erase an unmet checkpoint. Preserve earlier criteria, effort, and outcomes. In accountable use, apply the B1 rule for a material change of path.

### 1.2 A working contract for theory building

Before deepening an abstraction, write a short, revisable account of:

1. **Phenomena:** the examples, constructions, or recurring arguments to organize, and the distinctions that matter.
2. **Baseline:** how these are currently described, including existing theories or direct arguments.
3. **Candidate structure:** proposed definitions, primitives, equivalence notion, and intended scope. Separate chosen conventions from claims about objects.
4. **Payoff:** a consequence the structure should enable: transport a result, expose a common mechanism, distinguish conflated cases, remove a dependency, or make a construction effective.
5. **Tests:** examples with different relevant behavior, a degenerate or boundary case, and a plausible rival definition. Explain a narrow test set.
6. **Revision trigger:** what would require weakening, splitting, merging, or abandoning a definition, and what remains worth keeping.

Early scaffolding need not pass every test immediately. Its next work period should address a named uncertainty in this contract.

**Tests for useful abstraction:**

- **Non-vacuity:** show intended instances satisfy the hypotheses; check whether the hypotheses already encode the desired conclusion.
- **Discrimination or unification:** a claimed distinction needs an exhibited or proved difference; claimed unification needs a result or construction that can now be obtained uniformly.
- **Assumption roles and alternatives:** remove or vary assumptions to examine their role. Logical independence is a possible result, not a mandatory deliverable for every axiom.
- **Payoff beyond renaming:** compare the framework with a direct treatment. Transport rules, cleaner dependencies, or a useful equivalence can justify it without a new end theorem.
- **Scope discipline:** separate worked examples, a general theorem, and classification of all relevant objects. An example list is not a classification.

Examples test a proposed account; they do not prove its generality. Do not impose a universal numerical quota for examples. Broader abstraction is valuable relative to what it explains or enables.

### 1.3 A working contract for exploratory research

State a bounded terrain and a reason to examine it: conflicting examples, an unexplained regularity, an unfamiliar representation, or a suspected missing distinction. Specify a search protocol or family of mathematical moves and an effort cap. The eventual question may be unknown.

Keep observation, interpretation, and conjecture separate. For computations, record the generation rule, tested range, arithmetic assumptions, and cases inspected. For conceptual exploration, record definitions and examples compared, and exact relations established or left open.

Choose examples for information: include a baseline, plausible counterexample, and boundary case where feasible. Disclose substantial variant selection before presenting the surviving pattern as evidence. Challenge an emergent conjecture on cases not used to formulate it, or explain why this is unavailable. Such testing still does not prove a universal statement.

Acceptable discovery artifacts include an annotated example atlas, a precise open question with its motivating tension, competing definitions with a discriminating case, an exact failed conjecture, or a search report with explicit limits. More plots, files, or questions alone are not evidence of increased understanding.

A completed search can be informative, uninformative, or inconclusive about the mathematics. Report both completion and information gained. Exploration may continue without an immediate theorem if the next move has a credible mathematical or learning rationale and a bounded budget.

## 2. Build a selective map of statements and dependencies

### 2.1 The minimum useful atlas

For each relevant result, record:

- the exact statement, quantifiers, hypotheses and conclusion;
- the primary source, theorem number, version or date, and whether the full argument was inspected;
- the core mechanism and imported dependencies;
- the step that fails outside the established scope;
- the relation to the target: implies, is implied by, equivalent, overlaps, contradicts or unknown;
- proof and review status, recorded separately from publication status.

For each obstruction, distinguish:

| Entry | What it establishes | Appropriate response |
| --- | --- | --- |
| Verified counterexample | One specified statement is false | Revise that statement or close the route requiring it |
| Proved barrier | A defined family of arguments cannot establish a specified target under stated conditions | Add an ingredient outside the barrier's scope, or change method |
| Subsumption | An existing result implies the proposed contribution | Close that novelty claim; assess other contributions |
| Failed implementation | This particular attempt did not work | Diagnose the failure; do not generalize it without proof |
| Technical gap | A specific implication or estimate remains unproved | Attack, isolate or bypass it |
| Reformulation | A proved implication or equivalence changes the target | Assess whether new structure becomes accessible |
| Folklore or expert warning | A potentially useful lead | Record attribution and seek the argument |

Tao explicitly recommends learning a tool's limitations through counterexamples and model situations [S1]. That supports mapping limitations; it does not validate this document's budgeting rules.

### 2.2 Use a partial order, not an assumed lattice

(+) For a fixed universal conclusion, coverage of a class implies coverage of its subclasses, which gives a useful inclusion order. But a chosen collection of natural hypothesis classes need not form a lattice, and minimal uncovered classes need not exist.

Map the **relevant partial order** and record unknown inclusions honestly. Separate different conclusions, parameter regimes and notions of equivalence. Do not infer coverage relations from names or informal similarity.

For a proposed class extension, seek an object in the new class that lies outside the **union of the compared known coverage classes**, or prove that such an object exists. Being outside one theorem's class is insufficient. Even then, this establishes noncoverage relative to the comparison set, not global originality.

An explicit witness is useful but not mandatory for every path. Quantitative improvements, new proofs and nonconstructive class distinctions require different evidence (§1).

### 2.3 Maintain two core maps

- **Coverage map:** which statements are known, under which assumptions.
- **Dependency map:** what each proposed proof requires, including alternative sufficient routes and shared bottlenecks.

Mark AND dependencies and alternative OR routes. Do not claim a missing lemma is necessary when it is only sufficient for one proof.

A mechanisms × object-classes table can generate ideas. An empty cell is a question, not evidence of opportunity. Record search coverage and uncertainty about prior attempts.

### 2.4 Add a concept and example map when needed

For theory or exploratory work, supplement the core maps with only entries needed for the next choice:

- candidate definitions and the equivalence or comparison relation in use;
- examples, nonexamples, degeneracies, and which distinction each tests;
- translations to established terminology and whether the correspondence is proved;
- observations, conjectured mechanisms, and unresolved bridges between them.

Version substantive definition changes and identify affected proofs, data, and examples. Recheck dependent claims. A change of terminology is not a proved equivalence, and shared vocabulary is not evidence of shared hypotheses.

## 3. Generate candidates with a mathematical reason to try them

Keep generation broader than the active portfolio. A candidate earns a short probe when it identifies a concrete mathematical move.

| Move | Required question |
| --- | --- |
| Construct counterexamples | Which hypothesis or conclusion is being attacked? |
| Autopsy a known proof | Which precise implication fails at the boundary? |
| Use a barrier constructively | What information does the barrier ignore that this method uses? |
| Transplant a tool | Are its objects, hypotheses and useful quantity actually available? |
| Change the formulation | What is preserved, what is lost, and what new operation becomes possible? |
| Change scale, regularity, dimension or quantifiers | What bridge back to the target would be needed? |
| Revisit a simple or abandoned method | What changed: the target, a tool, available information, or a previously untested case? |
| Compute or build examples | What uncertainty can be reduced, and how will the output be checked? |
| Compare candidate definitions | Which example or operation distinguishes them, and does the distinction matter? |
| Extract a common mechanism | Which proof steps coincide, and which hypotheses permit a uniform argument? |
| Search for an invariant or organizing quantity | What is preserved, what can it distinguish, and what result could it support? |
| Explore an unfamiliar family | What is the bounded terrain, and what record would make the exploration informative? |

Prefer **opportunities that are under-examined relative to the map**, whether elementary or sophisticated. An absence of recorded attempts does not establish that nobody tried.

Reserve some effort for learning a new theory or reproducing a benchmark proof. Such work should state the capability it aims to acquire and its demonstration artifact (B1). It need not promise immediate novelty.

Do not require every creative idea to expose the final missing lemma at birth. A short discovery probe may aim to identify that lemma. Deepening requires a clearer target.

## 4. Screen novelty in stages

### 4.1 Initial screen before substantial commitment

- Search for the statement as well as the method, using alternative terminology and equivalent formulations.
- Read the closest primary results.
- Check hypotheses, conclusions, limiting cases, forward citations and likely authors.
- Compare against combinations of known results, not only individual theorems.

Use these verdicts:

- **No overlap found within the recorded search scope.**
- **Partial overlap; the proposed difference is stated.**
- **Subsumed for the claimed contribution.**
- **Unresolved; a specific source or implication is missing.**

Never use "clear" to imply that a finite search certifies originality.

### 4.2 Investment should reflect unresolved risk

An inaccessible source does not automatically prohibit all work. A bounded probe is permitted if it is inexpensive, or if it would remain useful even when the result turns out to be known. Before costly deepening, identify how the uncertainty will be reduced, or explicitly justify the risk.

Before making a novelty claim, refresh the comparison and disclose any unresolved overlap. Expert feedback is a valuable supplement, but neither a guarantee nor universally the best search method.

### 4.3 Monitor selectively

Track the target statement, close authors, and the **tool triggers** for parked programs. Scan at a cadence suited to the field. New relevant work triggers reassessment of the affected paths; it need not restart the whole literature review.

### 4.4 Novelty when objects or questions are evolving

Exploration may begin before there is an exact statement to search for. Use a light terminology and nearby-framework screen. Refresh the comparison when a definition, conjecture, or mechanism stabilizes, and before substantial investment or an external novelty claim.

For frameworks, compare expressive scope, preserved operations, translations or equivalences, assumptions, and demonstrated consequences. New names or notation alone do not establish a new theory. A connection to existing work can remain useful even when originality disappears. Record whether the intended contribution is mathematical, methodological, expository, or educational.

## 5. Select the next increment of work

The decision unit is the **next bounded action**, not the whole ambition of solving the problem.

Compare actions on:

- the value of a valid contribution;
- the chance of obtaining it within the proposed increment;
- novelty risk, conditional on the result being valid;
- reusable learning, explanatory or organizing capability, and changes to later decisions;
- research, verification, expert-attention and switching costs;
- dependence on the same assumptions or bottlenecks as other active work.

If numbers clarify the choice, use a scenario model:

$$
U(a)=\sum_o P(o\mid a,I)\,[V_o+L_o]-C_a.
$$

Here:

- outcomes $o$ are mutually exclusive scenarios;
- $I$ is the current information;
- $V_o$ is contribution value and $L_o$ is incremental reusable learning;
- $C_a$ is the full incremental cost, in comparable utility units.

Include failure, inconclusive results, invalid arguments and known results among the outcomes.

For a particular successful contribution, one possible decomposition is:

$$
P(\text{valid and novel}\mid a,I)
=P(\text{valid}\mid a,I)\,P(\text{novel}\mid\text{valid},a,I).
$$

(+) This is a conditional-probability identity; it does not assume independence. Do not multiply two unrelated marginal guesses, and do not count learning both here and again as a separate bonus.

**Practical default:** use low, base and high scenarios, or qualitative comparisons. If the ranking changes under reasonable assumptions, investigate the uncertainty driving that change, or run the cheaper probe that discriminates between them. Avoid decimal precision that experience does not support.

**Value of information:** prefer a probe whose plausible outcomes would change an actual decision. Discovery and theory building may also create new choices or distinctions that cannot be listed in advance. Name the gap in understanding and intended evidence rather than inventing a downstream decision. An observation with no immediate decision effect may still have mathematical or educational value; assess it as such.

Include continuing, switching, learning, verification, expert consultation and doing no further work among the feasible alternatives. Shared lemmas may make two paths correlated, but they can also create useful economies of effort.

This is an allocation heuristic. It does not claim that mathematical research satisfies any particular optimal-stopping or bandit theorem.

## 6. Probe before deepening

A short probe needs six items. These are the fields of the probe card (§11.1). Interpret the target according to research mode: an exact statement, a candidate structure, or a bounded uncertainty.

1. The target question.
2. The current reason to try it.
3. The test, including the cases or sources it covers.
4. How to interpret positive, negative and inconclusive outcomes.
5. **The intended artifact, expected change, and completion criterion (and optional minimum criterion). Distinguish work completion from mathematical findings (§6.1); add a confidence forecast in the accountable profile (B1).**
6. An effort cap and the next decision.

Use "discriminating test" as the default term. Reserve "kill test" for an outcome that actually invalidates a required statement, or establishes that the claimed contribution is unavailable.

**Toy-model discipline.** (+) A toy failure transfers to the original route only through a justified logical relation.
- A counterexample to a required lemma, within that lemma's stated domain, is decisive. Failure to find a proof is not.
- A toy model that discards essential structure can mislead.
- Success on a toy model also needs a bridge back to the full problem.

**Computational discipline.**
- State the sampling or enumeration domain, the numerical assumptions, the baseline examples and the failure criteria.
- Search for degenerate, boundary and adversarial cases.
- A report of "no counterexample found" must include its search scope.

Before constructing substantial machinery, test the cheapest uncertain prerequisite that could invalidate its use.

### 6.1 Distinguish conclusion probes from discovery probes

A **conclusion probe** tests a specified assertion or capability. A **discovery probe** executes a bounded investigation to learn which assertions, definitions, or distinctions deserve attention. Both need checkable scope; discovery need not predict its finding.

Before starting, distinguish:

- **Completion criterion:** the work and artifact required, such as checking the listed boundary cases under two definitions.
- **Research expectation:** the hoped-for substantive change, such as separating definitions, identifying a common mechanism, or narrowing competing explanations.
- **Finding:** what was established, including no distinction found within the stated scope or an unresolved extension gap.

Completing a protocol does not establish its hoped-for conclusion. Refuting a conjecture can be valuable. In accountable use, specify beforehand which criterion B1 scores; record the mathematical finding separately. Do not replace a proof forecast with process completion after failure.

**Illustration:** compare two candidate representations on a baseline family, a redundant-name case, and a boundary case. Record exact translations or their gaps. Discovering equivalence under a known theorem is a legitimate finding; reporting only that three examples were generated is not the intended mathematical assessment.

Before expanding examples, use a **generalization checkpoint**: what common argument, distinction, or obstruction do they support; what case would challenge it; and what proof obligation or investigation follows? If no credible synthesis emerges, change the sampling rationale, consolidate the atlas, or park the direction. Do not repeatedly rename example collection as theory development.

## 7. Deepen, review and stop at the right scope

### 7.1 Record progress as a change in mathematical capability

At a checkpoint, compare the actual before and after. Progress includes:

- a necessary estimate proved or improved in a useful regime;
- a case family eliminated;
- a reduction proved that exposes a usable tool or symmetry;
- a candidate counterexample verified, or ruled out for a named reason;
- a dependency removed, or an obstruction's scope clarified;
- a proof repaired or independently checked;
- a learning goal that unlocked a previously unavailable technique, evidenced by its demonstration artifact (B1);
- a candidate definition revised because a named example or operation exposed a defect;
- a common construction proved under explicit hypotheses, or a conceptual distinction shown to matter;
- a precise new question or competing explanations derived from documented exploratory evidence.

(+) A formally smaller or more specific lemma need not be easier, so ask what the reduction now permits. Conversely, a constant improvement can be decisive if it crosses a named threshold. Neither "sharpening" nor "calibration" is inherently good or bad. Their value lies in the decisions, conjectures, proof obligations or reusable capabilities they can change (B3).

### 7.2 Distinguish decisive evidence from warning signs

| Observation | Default action |
| --- | --- |
| Verified refutation of a required lemma | Stop that proof route immediately; consider repair |
| Applicable barrier, with all its hypotheses checked | Stop the covered method, unless a new ingredient escapes it |
| Established subsumption | Stop the corresponding novelty claim; assess other value |
| Two consecutive counted misses on the same path (B1 counting rule) | **Reassessment default (B2):** review route, forecast calibration and effort; revise the plan and compare continuation with alternatives |
| Two consecutive not-attempted checkpoints on the same path | **Fresh-proposal test (B4):** is this path still being chosen? Record the answer |
| Checkpoint stopped on evidence | Record the named evidence as a probe result; update the map if it bears on a route; apply B4 to the next increment |
| Increments that change only constants or examples, without crossing a named threshold | **Drift prompt (B3):** state which decision, conjecture, proof obligation or capability the next increment could change |
| Repeated reformulation without new capability | Review whether the next increment differs materially |
| Repeated new assumptions | Reassess whether the remaining statement is still valuable |
| More examples without a clearer distinction, mechanism, question, or search rationale | Reassess the role and budget of further examples |
| New definitions or axioms without a consequence or discriminating test | Test non-vacuity, compare a rival definition, or simplify |
| Repeated inconclusive investigations | Reconsider scope, tools, or the question; compare with consolidation or parking |
| Verification bottleneck | Consolidate, or label downstream work explicitly as conditional |
| Effort cap reached | Make a new allocation decision, including the fresh-proposal test (B4) |

Do not count warning signs mechanically. One decisive observation can suffice, and several correlated symptoms may express a single concern.

### 7.3 Choose and record an outcome

- **Continue:** name the next action, its budget, its expected change and completion criterion (B1), and why it beats the alternatives.
- **Revise:** change the statement, method or contribution explicitly, and keep the old version. In accountable use, a revision does not reset the miss count (B1).
- **Park:** specify a tool trigger, a source, a collaborator input or a scheduled reassessment.
- **Close:** state exactly what is closed and why.
- **Consolidate:** spend the next increment making existing work reliable or reusable.

Distinguish **method**, **program** and **problem**. Failure of one technique does not close a reduction, and failure of a reduction does not settle the original conjecture.

### 7.4 Protect long-horizon work without granting unlimited continuation

Allocate a bounded period of protected work when the problem is important, the strategy coherent and the opportunity costs acceptable. Immediate lemma sharpening need not occur at every review.

Renew the period based on the overall evidence: new understanding, credible mechanisms, remaining obstacles, available expertise and alternatives. "No known barrier" alone is weak support. Record a cumulative resource cap or the next funding decision.

For long-horizon work, phrase checkpoint expectations in terms of **capability**, such as definitions stress-tested, cases classified, reductions proved, obstructions understood, or techniques acquired. Each capability expectation must name its **demonstration artifact** (B1). A proof milestone is also appropriate when realistically forecast. Record effort; add a confidence forecast in accountable use.

Meeting a capability expectation is evidence of progress, not automatic entitlement to renewal. Missing an ambitious expectation does not automatically end protected work.

Set the checkpoint cadence to the natural grain of the work, not to calendar convenience. A checkpoint that cannot plausibly show change is too frequent; one that hides several decisions is too sparse.

Tao's advice supports changing goals as research develops [S2]. It does not determine the correct duration of a protected period.

### 7.5 Defaults for uncertain allocation decisions (B1–B4)

B1–B2 and their counting rules apply in the accountable profile; B3–B4 are also useful as qualitative prompts in lightweight use. These defaults are (~). Their justification is procedural: they force a recorded comparison with alternatives at defined moments, without treating a miss count as a statistical test. Run 2 (A.6) motivated them but is unverified provenance; the pilot (§10.3) tests them.

**B1. Assessable checkpoint expectation (accountable profile).** When this profile is selected (§9.3), every continuation records:

- the mathematical or capability change sought;
- a **completion criterion** and checkpoint;
- optionally, a **minimum criterion**: a pre-stated partial result that counts as adequate progress;
- planned effort, and a rough probability or probability range of meeting the completion criterion within that effort.

For a discovery probe, the target may be completion of an informative protocol rather than a predicted positive finding (§6.1). Mark that distinction before starting. A met process target does not by itself justify renewal or count as a successful theorem prediction.

“Make progress” is insufficient. “Determine whether tool T applies to reduction R” is assessable only if the required determination is specified.

*Capability expectations* must name a **demonstration artifact** that a reviewer could inspect, for example:

| Capability | Demonstration artifact |
| --- | --- |
| Cases classified | A written list of cases, each with its proof or its explicit open status |
| Reduction proved | A written statement and proof of the implication, with hypotheses |
| Obstruction understood | A written statement of what fails, for which method family, and why, with at least one model example |
| Technique acquired | A reproduced benchmark proof, or the technique applied to a named test problem |
| Dependency removed | The revised dependency map entry and the replacing argument |

"Understood" without an artifact is not assessable. Name the artifact's judge (operator or reviewer) in advance.

**Checkpoint outcomes and the counting rule.** Classify each checkpoint as exactly one of:

| Outcome | Definition | Effect on the consecutive-miss count |
| --- | --- | --- |
| Met | Completion criterion satisfied | Resets to 0 |
| Minimum met | Pre-stated minimum criterion satisfied, completion criterion not | Resets to 0 |
| Stopped on evidence | Work on this expectation stopped before the checkpoint because a named result, computation, counterexample or source made the expected change implausible or unnecessary | No change; logged separately; B4 applies to the next increment |
| Not attempted | Before the checkpoint date, a recorded decision moved the planned effort elsewhere for reasons other than evidence about this path (for example, another path's priority, verification demands, external commitments) | No change; logged separately |
| Missed | Every other checkpoint whose criteria were not satisfied, whatever effort was spent | Increments by 1 |

"Missed" is the residual class, so the classes are exhaustive. Record actual effort with every outcome. Further rules:

- "Not attempted" needs a decision recorded before the checkpoint date; a later reallocation cannot convert a miss.
- "Stopped on evidence" needs a named result; discouragement or slow progress is not evidence.
- Targets and minimum criteria count only if recorded in advance, and are never rewritten after the outcome.
- Revising the action, expectation, effort or cadence keeps the same path and count. The count restarts only when the method family or target changes materially, with a recorded reason, and the old path is closed or parked. Renaming does not count.

Expectations are forecasts, not promises: an ambitious probe can be worth a low success probability. Interpret misses in light of effort and unforeseen information, and update forecasts openly.

**B2. Reassessment default.** After two consecutive counted misses on the same path, explicitly reassess:

1. the research route and its remaining mechanism;
2. forecast calibration and milestone difficulty;
3. actual versus planned effort;
4. the next increment versus feasible alternatives.

Default to revising the plan (action, expectation, effort or cadence); this need not abandon the approach. Parking is favored when the next increment has no credible advantage over alternatives. Continuation is permitted within an existing protected budget unless new evidence invalidates its rationale. Record the rationale and remaining budget; lowering the expectation alone does not justify continuing.

A third consecutive counted miss prompts an **independent perspective**: a non-operator reviewer given the path card, review notes and current argument. If none is available, use a structured fresh review, record the limitation and stay within the authorized budget. Additional resources require a new allocation decision.

(+) Illustration: two independent milestones at 20% success give two misses with probability 64%; at 80%, 4%. Real milestones are often dependent, so a fixed miss count has no universal evidential weight.

**B3. Drift prompt.** When consecutive increments only tune constants, thresholds, meshes, or examples, or add terminology, axioms, or diagrams, ask: *what could the next increment change in a question, conceptual distinction, decision, conjecture, proof obligation, or reusable capability?*

Name the likely output and its connection to the target. If none is credible, budget the work as consolidation, exposition or maintenance. Exploratory work need not change an immediate decision, but an invented downstream benefit does not justify indefinite continuation: name a plausible use and review it.

**B4. Fresh-proposal test.** Ask: *given current evidence, assets, remaining and switching costs, would this next increment be selected over the best feasible alternative?* Exclude sunk expenditure as a reason; keep the knowledge, code and proofs it produced. Record yes / no / uncertain and why. When rankings are uncertain, prefer a discriminating probe or a protected budget over a forced answer.

B1–B4 remain unvalidated. If the aim is to evaluate or tune their effectiveness, use the pilot (§10.3), rather than mistaking ordinary mathematical progress for policy validation.

### 7.6 Review the maturity of a theory or exploration

At a substantial checkpoint, ask which transition is justified:

- **Explore further:** the question is unsettled, but the next example, comparison, or tool has a reason to be informative.
- **Develop a candidate theory:** recurring structure motivates explicit definitions and a consequence to test.
- **Prove or refute:** a conjecture and its hypotheses are stable enough for focused work.
- **Compare with existing theory:** possible equivalence or subsumption could change the contribution.
- **Consolidate:** make concepts, observations, proof status, and limits reliable and reusable.

These are reversible choices, not a mandatory pipeline. Before extending a framework to another domain, identify the property or limitation the new domain would test. A growing coverage list is not itself a reason to generalize further.

**Strongest objection:** usefulness tests may reject foundational concepts before their consequences are visible. A bounded protected period for concept development is legitimate when motivated by a recurring tension or promising structural connection. Its review should ask what became more precise, what was ruled out, and why the next increment remains worth choosing; an indefinitely promised application is insufficient.

## 8. Verification and claim management

### 8.1 Track separate dimensions

For each significant claim, maintain:

| Dimension | Example entries |
| --- | --- |
| Mathematical status | Conjecture; argument with named gaps; complete claimed proof; refuted |
| Concept status, when relevant | Provisional definition; revised definition; fixed convention; proved relation to another definition |
| Observation status, when relevant | Exact example; bounded exhaustive result; sampled pattern; numerical indication; unresolved interpretation |
| Review evidence | Self-check; independent reconstruction; specialist review; formally checked scope |
| Novelty status | Unsearched; overlap unresolved; comparison completed |
| Computational role | Exploration; exact finite check; certified certificate; formal proof component |
| Dissemination | Private; shared draft; preprint; published |

(+) Publication and correctness are different dimensions. Formal verification also requires checking that the formal statement matches the intended theorem, and identifying the assumptions and trusted components.

### 8.2 Prioritize verification by dependency and consequence

Use a dependency graph, not just a count of unreviewed results. A central unchecked lemma supporting many claims deserves attention before an isolated minor observation.

By default, do not build a long chain of unconditional claims on an unchecked critical dependency. Conditional exploration can continue if the assumption is explicit and the budget justified.

For theory building, also check that intended examples satisfy definitions, exclusions are justified, hypotheses are satisfiable, and the claimed consequence is not simply assumed. For exploration, verify surprising examples and distinguish exhaustive search from selected samples.

For each critical step, identify a plausible error and the cheapest credible check. Repeated reading is not automatically independent verification. A new derivation, an adversarial example, a separate implementation or a formalization may each provide different evidence. There is no universal rule that one audit is enough or that a third is useless.

### 8.3 Computation can participate in proof

(+) Exploratory sampling is not universal proof. However, a rigorous reduction to a complete finite computation, with trustworthy arithmetic and a justified checking procedure, can be part of a mathematical proof. Gonthier's formalized Four-Color Theorem is a concrete example [S3].

For a computational proof claim, state:

- why the enumerated cases cover the theorem;
- how the checker implements the mathematical conditions;
- how arithmetic and numerical errors are controlled;
- what certificate, code, environment and inputs permit reproduction;
- which assumptions remain outside the verified component.

Passing many checks does not substitute for establishing coverage and soundness.

### 8.4 Review packets

Prepare one precise statement, its proof, a dependency list, a comparison with prior work and explicit questions for the reviewer. Formalize when the expected benefit justifies the cost. Prioritize stable, critical lemmas rather than formalizing every exploratory result.

## 9. Work allocation and AI use

### 9.1 Adapt the portfolio to the bottleneck

For one researcher, start with one deep path and a small probe queue. Allocate verification effort according to the importance of claims and the rate at which they are produced.

- If ideas are plentiful and proof debt is high, consolidate.
- If a proof is credible but its novelty is unclear, compare sources or consult an expert.
- If the obstacle is a lack of technique, learn it or seek collaboration.
- If repeated paths share the same obstacle, investigate a distinct mechanism.
- If momentum is strong and dependencies are checked, protect depth.

No fixed "most effort on consolidation" rule applies at every stage.

Keep a small adversarial effort focused on the current lemma. (~) Independent checks may reduce shared blind spots, but different agents or model names do not by themselves establish independence.

### 9.2 AI task contract

For substantial AI-assisted work, require:

- the research mode, exact target or bounded terrain, permitted assumptions, and budget;
- current sources and comparison statements;
- a clear distinction between conjecture, proof, computation and verified result;
- concrete outputs, including "blocked", "subsumed" and "no justified progress";
- an intended artifact and completion criterion, separating work completion from mathematical findings; B1 forecasts only in accountable use, and B3 when examples or formalism grow without capability;
- for theory work, a candidate structure, payoff, and stress test; for exploration, a bounded protocol and permission to report an uninformative or inconclusive finding;
- an explicit handoff for consequential unresolved steps.

Do not require an exploratory AI task to invent a theorem, application, or positive result to fill a template. Require missing bridges and unsupported generalizations to be exposed. A proposed next step must name the uncertainty it addresses; continuing by default is not a research justification.

For a literature reviewer, supply the target statement and hypotheses without persuasive framing. For a proof reviewer, supply the full proof and its dependencies; hiding the proof from someone asked to verify it defeats the task.

Record which calculations actually ran, which outputs were inspected and which sources were read. Do not describe a drafted script as an executed test.

(~) AI agents tend to propose a next step by default. B4 applies to agent-proposed continuations exactly as to human ones. Where the accountable profile is selected, B1–B2 and checkpoint counting apply equally.

### 9.3 Lightweight governance and documentation tiers

**Choose the documentation profile explicitly.**

- **Lightweight (default):** record mode, target or terrain, next action, intended artifact and criterion, effort cap, and then the actual finding and next choice. Use B3–B4 qualitatively at substantive decisions. Numeric confidence, miss counts, full path cards, and a pilot are not required.
- **Accountable:** add B1 forecasts and exhaustive checkpoint classes, B2 miss-count reassessment, cumulative budgets, and fuller review records when resources, repeated continuations, or external accountability justify them.
- **Policy evaluation:** run the frozen pilot (§10.3) only when evaluating the strategy itself; it adds roles and logs beyond ordinary research.

Profile changes are prospective. Preserve earlier records and explain the change; do not retroactively reclassify unsuccessful work. Do not combine met counts across process, proof, and capability targets into one performance score.

Keep one dashboard listing active modes and targets, critical uncertainties or dependencies, next actions and budgets, and intended artifacts and criteria. Add consecutive-miss counts in accountable use. Existing research notes may serve this purpose; avoid duplicate records. Update at decision points.

**Documentation tiers:**

| Tier | When | Record |
| --- | --- | --- |
| Probe card (§11.1) | Every probe; every review of a probe | Six fields |
| Deep-path card (§11.2) | When scope, dependencies, resources, or accountable review justify it | Relevant fields; full accountable fields when selected |
| Review note (§11.3) | Each substantive allocation review | Short form; forecast/count fields in accountable use; fuller rationale when needed |
| Claim entry (§11.4) | Claims that other work depends on, or that will be shared | Full entry |

Document only information that supports decisions, verification or reuse. A failed two-hour probe may need five lines, not a report.

(~) Default overhead allowance: documentation and policy steps should stay below roughly 10% of research effort. Exceeding it is a signal to simplify, not to work faster.

## 10. Harvest and assess the policy itself

### 10.1 Preserve proportional outputs

| Outcome | What to keep |
| --- | --- |
| Valid new result | A self-contained theorem and proof, with comparison |
| Useful partial result | Exact scope and a downstream use |
| Counterexample | A checkable construction and the precise statement it refutes |
| Method limitation | The scope of the obstruction and the ingredients that might escape it |
| Subsumed result | A brief comparison, keeping any distinct proof advantage |
| Inconclusive attempt | What was tried, what remains unknown, and the reentry conditions |
| Candidate framework | Definition versions, established consequences, contrasting cases, and remaining proof obligations |
| Exploratory map or new question | Observation provenance, discriminating cases, competing interpretations, scope, and next uncertainty |
| Useful equivalence to existing work | Checked translation, preserved structure, and any distinct contribution remaining |

Failure to solve a problem is not automatically a publishable negative result. Harvesting should preserve useful information without becoming compulsory publication work.

### 10.2 Evaluate decisions separately from outcomes

Retrospective testing follows Appendix A; eventual success or failure alone cannot show an earlier allocation was justified.

For each prospective decision, record alternatives, available information, intended artifact and criterion, planned and actual effort, the mathematical finding, and the next choice. In accountable use, also log B1 forecasts and outcome classes, B2 reassessments, departures, and which rules changed the decision. Add detailed calibration logs when evaluating the policy; ordinary research need not reproduce the full pilot.

Separate "not achieved by the checkpoint" from "mathematically impossible", and judge forecasts on their stated conditions. Review forecast calibration, verified outcomes per effort, late subsumption, invalid critical claims, verification burden and overhead, and whether easy milestones were chosen to avoid misses.

**Continuation outcomes are descriptive, not counterfactual evidence.** A successful departure does not prove continuation beat its alternative; a failed one may have been a justified risk; parked paths often have unknown outcomes. Do not infer an optimal B2 threshold from continuation success rates.

**(-) Untested:** that this policy improves output relative to simpler practice. A small pilot can reveal failure modes; it cannot establish a causal gain.

### 10.3 Bounded prospective pilot

**Optional policy evaluation, not a prerequisite for mathematical research.** This pilot evaluates the accountable profile. Prior rules are not automatically validated by the theory and exploration additions. To test them, predeclare the research modes and applicable markers below; assess modes separately rather than combining heterogeneous outcomes into one success rate.

The pilot's goal is **failure-mode discovery and rule exercise**, not validation of effectiveness. The policy, evaluation criteria, research modes, and applicable marker set are frozen before starting.

**Window (long-horizon program).** Measured in deep-path reviews. (~) Defaults, fixed before starting: the pilot ends at the earliest of **8 deep-path reviews**, budget exhaustion, or a **16-week** ceiling. Probe reviews are logged separately (cap e.g. 12). With fewer than 4 deep-path reviews at the ceiling, the pilot is **inconclusive** for B1–B2; review the cadence before rerunning.

Set the cadence from the grain of the work (§7.4). **Do not choose expectations to make B2 fire**; honest forecasts are part of what is tested.

**Roles.**

- **Operator:** runs the policy and writes the cards and notes.
- **Pilot reviewer:** at least one non-operator; process competence suffices. Performs a **start check** (§11.5 complete, markers set), a **mid-pilot audit** after deep-path review 3–4 (logging completeness, ambiguity events, overhead; corrects logging, never rules), and an **end assessment**, scoring each applicable failure mode *before* seeing the operator's scoring. Unresolved disagreements make that item inconclusive.
- **F3 judge:** a named domain-competent person (may be a reviewer) who judges milestone difficulty. Without one, F3 is **unassessable**, which blocks "retain unchanged".
- **Mathematical reviewer** (may coincide): used under B2's third-miss rule and §8, not for the pilot assessment.

**Before starting**, complete §11.5: freeze the policy and window; choose one long-horizon program and a small probe queue, recording dependencies and unresolved novelty; set research, verification, protected-work and documentation budgets; write a marker for each failure mode (the threshold for "occurred materially", qualitative allowed); obtain reviewer sign-off.

**Pre-registered failure modes and decision mapping:**

| ID | Failure mode | Evidence logged | If it materially occurs → |
| --- | --- | --- | --- |
| F1 | Documentation overhead exceeds its allowance | Effort log | Simplify: cut fields or tiers |
| F2 | Policy steps fragment protected deep work | Operator and reviewer notes; interrupted sessions | Simplify cadence or review form |
| F3 | Expectations systematically trivial (milestone gaming) | B1 targets versus actual difficulty; F3 judge | Amend B1 |
| F4 | Forecasts miscalibrated and not updated | Forecast versus outcome log | Amend B1 forecasting guidance |
| F5 | B2 fired, but reassessment produced no new information or plan change | Review notes | Amend or simplify B2 |
| F6 | B2 defaults overridden without recorded rationale | Departure log | Amend B2 recording requirement |
| F7 | B3 led only to relabeling, with no budget change | Review notes | Simplify or drop B3 |
| F8 | B4 answers uniform ("yes" every time) or unreasoned | B4 log | Amend or drop B4 |
| F9 | Operator could not determine what a rule required (ambiguity event) | Ambiguity log | Amend the named rule |
| F10 | A rule never fired | Rule-firing log | That rule is **inconclusive**, not passed |
| F11 | "Not attempted" or "stopped on evidence" used to avoid misses | Share of deep-path checkpoints in these classes; their timing relative to emerging difficulty; quality of named evidence; reviewer judgement | Amend B1 (tighten the classes, or count them toward B2) |
| F12 | A theorem or binary verdict was forced onto genuine discovery | Predeclared mode, criteria, artifacts, and review rationale | Amend mode choice or §6.1 criteria |
| F13 | Formalism or example volume passed as capability without demonstrated content | Theory contract, examples, consequences, and claimed progress | Amend payoff and generalization checks |
| F14 | Process completion or mode changes concealed absent learning or erased unfavorable records | Before/after records, profile changes, findings, and resource decisions | Amend completion/finding separation or transition rules |

**End decision**, applied mechanically to the reviewer-scored table (F1–F11 plus applicable F12–F14):

- **Retain unchanged** only if no applicable marker was crossed, F3 was assessable, and B1–B4 each fired. Any unexercised v1.6 mode rule remains inconclusive for that mode.
- **Simplify** if F1, F2 or F7 crossed.
- **Amend a named rule** if F3–F6, F8, F9, F11, or applicable F12–F14 crossed; state the change.
- **Rerun** if any of B1–B4 is inconclusive or F3 unassessable, and nothing else applies; change the cadence, program or F3 judge instead of extending.
- **Rerun cap:** at most three pilots in total. Afterwards, record still-unexercised rules as untested and keep them as labeled (~) defaults or remove them.

Outcomes may combine (e.g. simplify and amend B2).

**During the pilot**, revise mathematical plans freely but log policy amendments for the end. Fix a real logical error or intolerable operational problem immediately, preserving the old rule and logging a protocol deviation.

**At the end**, review all decisions, including parked and abandoned work, and whether documentation helped. Do not assign the strategy an overall success probability, or turn historical examples into another tuning loop.

### 10.4 Rule register

Each rule's basis, and what would count against it in the pilot.

| Rule | Basis | Pilot observation counting against it |
| --- | --- | --- |
| Three distinctions (§0) | (+) Logical | None expected; a logical counterexample would require correction |
| Obstruction taxonomy, partial-order map (§2) | (+) Logical, plus [S1] for attention to limitations | F9 ambiguity events in classifying obstructions |
| Staged novelty verdicts (§4) | (~) Design: avoids overclaiming originality | Late subsumption despite completed screen |
| Scenario model, conditional decomposition (§5) | (+) Identity; (~) usefulness | Unused, or produced false precision without changing choices |
| Probe structure, toy and computational discipline (§6) | (+) For the logical transfer rules; (~) for the format | F1, F2 |
| B1 | (~) Design: makes forecasts and misses assessable | F3, F4, F9, F11 |
| B2 | (~) Design: forces comparison after repeated misses | F5, F6, F10 |
| B3 | (~) Design: surfaces drift into constant-tuning | F7, F10 |
| B4 | (~) Design: sunk-cost guard; standard decision logic | F8, F10 |
| Claim dimensions, verification by dependency (§8) | (+) For separating correctness from publication; [S3] for computation in proof; (~) for prioritization | Invalid critical claims reached downstream work unflagged |
| Documentation profiles and allowance (§9.3) | (~) Design | F1, F2, F14 |
| Modes and theory/exploration contracts (§1.1–1.3) | (~) Design; (+) distinction between definitions, examples, and general claims | F12, F13, F14 |
| Completion/finding separation and generalization checkpoint (§6.1) | (~) Design; (+) protocol completion does not imply a mathematical conclusion | F12, F13, F14 |

## 11. Templates

### 11.1 Probe card

```markdown
## Probe: <name> (path: <parent path or none>)
- Mode/profile: problem solving / theory building / exploration; lightweight / accountable
- Target question, candidate structure, or bounded terrain; reason to try now:
- Test and its coverage (cases, sources, search domain):
- Positive / negative / inconclusive → what changes:
- Intended artifact; completion criterion; substantive change sought (separate):
- Accountable only: B1 scored target (process / proof / capability); minimum criterion (optional); confidence:
- Effort cap; checkpoint; next decision:
- Completion and actual effort; mathematical finding (positive / negative / inconclusive / uninformative, with scope); next choice:
- Accountable only: B1 outcome (met / minimum met / stopped on evidence / not attempted / missed); named evidence or decision date where applicable
```

### 11.2 Deep-path card

```markdown
## Path: <name>
- Mode/profile; program / method; target or terrain and intended contribution:
- Theory: phenomena, baseline, candidate structure, payoff, stress tests, revision trigger:
- Exploration: terrain, protocol, observation provenance, unresolved interpretations:
- Completion criterion and mathematical expectation, recorded separately:
- Closest comparison; proposed difference; novelty verdict and unresolved overlap:
- Noncoverage evidence or appropriate novelty test:
- Mechanism; why it may help:
- Dependencies; critical uncertain step; verification plan; downstream conditional claims:
- Next probe; positive / negative / inconclusive interpretations:
- Intended change, artifact, completion criterion, planned effort, and checkpoint:
- Accountable only: B1 scored target and confidence; minimum criterion; artifact judge:
- Accountable only: consecutive counted misses; not-attempted and stopped-on-evidence checkpoints:
- Cumulative budget, expenditure and remaining protected allowance:
- Best alternative; uncertainty that could change the choice:
- State: active / revise / parked / closed / consolidating
- Reentry trigger or closure scope:
```

### 11.3 Review note

```markdown
## Review: <path>, <date>, deep-path review #<k>
- Mode/profile; completion versus mathematical finding; any mode transition and reason:
- Accountable expectation (B1) → met / minimum met / stopped on evidence (name it) / not attempted (decision date) / missed — effort: planned vs actual
- Before → after: mathematical change and evidence (artifact, if capability):
- Accountable only: consecutive counted misses:
- Fresh-proposal test (B4): yes / no / uncertain — why
- Decision, scope, budget; next expectation, criteria and checkpoint:
- Rules fired this review; did any change the decision?
- Ambiguity events (if any):

<!-- Extended section: complete only when it applies -->
- B2 reassessment (≥2 counted misses): route; calibration; effort; next increment vs alternatives; rationale; remaining budget
- Independent perspective (≥3 counted misses): reviewer, or limitation recorded
- Drift prompt (B3): which decision, conjecture, proof obligation or capability could the next increment change?
- Departure from default: reason, alternative, remaining budget
```

### 11.4 Claim / atlas entry

```markdown
## Claim: <ID>
- Type: definition / observation / conjecture / theorem / methodological judgment
- Concept version or observation protocol, when relevant:
- Exact statement, hypotheses and conclusion:
- Source, theorem number, version/date:
- Dependencies; relation to the target:
- Mathematical status and named gaps:
- Review evidence and checked scope:
- Novelty status:
- Computational role and reproducibility:
- Limits, failures or tool triggers:
```

### 11.5 Pilot pre-registration block

```markdown
## Pilot pre-registration
- Policy version frozen: v1.6; start date; pilot number in sequence (maximum 3):
- Operator; pilot reviewer(s); mathematical reviewer(s), if different:
- F3 judge (domain-competent), or "none — F3 unassessable":
- Program (long-horizon); research modes and scored target types; probe queue:
- Applicable v1.6 markers F12–F14 and mode-specific assessment scope:
- Window: deep-path review limit <8>; probe review cap <12>; calendar ceiling <16 weeks>; minimum deep-path reviews for B1–B2 conclusions <4>
- Checkpoint cadence and its justification:
- Budgets: research; verification; protected-work allowance; documentation allowance (<~10%>):
- Failure-mode markers (what counts as "material"):
  - F1:
  - F2:
  - F3:
  - F4:
  - F5:
  - F6:
  - F7:
  - F8:
  - F9:
  - F11:
  - F12 (if applicable):
  - F13 (if applicable):
  - F14 (if applicable):
- Logs kept: effort; forecasts and outcomes (all five classes, with decision dates and named evidence); rule-firing; departures; ambiguity events
- Reviewer sign-off; date:
```

### 11.6 Pilot end assessment

```markdown
## Pilot end assessment
- Deep-path reviews completed; probe reviews; end trigger (reviews / budget / ceiling):
- Protocol deviations (with preserved previous rules):
- Reviewer scoring (made before seeing the operator's scoring), F1–F11 and applicable F12–F14: occurred / not / inconclusive / unassessable, with evidence
- F3 judge and their scoring (or "unassessable"):
- Operator scoring, F1–F11 and applicable F12–F14:
- Disagreements and resolution (unresolved → inconclusive):
- Rules fired: B1 <n>, B2 <n>, B3 <n>, B4 <n>; decisions changed by each:
- Decision mapping applied: retain / simplify / amend <rule> / rerun — and why
- What remains unknown:
```

### 11.7 Optional concept / exploration record

Use only when the probe or path card does not already hold this information.

```markdown
## Structure or terrain: <name and version>
- Phenomena or uncertainty; baseline:
- Definitions and equivalence notion, or exploration protocol:
- Examples, nonexamples, boundary cases; why these cases:
- Intended consequence or capability; comparison with direct/existing treatment:
- Established facts versus observations, conjectures, and gaps:
- Generalization: common mechanism or distinction; challenging case; next proof obligation:
- Retain / revise / merge / split / park; rationale, budget, and reentry trigger:
```

## 12. Revision notes and sources

### Changes

| Version | Main changes |
| --- | --- |
| v1.6 | Broadened purpose and checklist to problem solving, theory building, and exploration. Added mode transitions, theory/exploration contracts, concept maps, novelty screening for evolving questions, completion/finding separation, generalization checkpoints, and framework maturity review. Lightweight documentation is now the default; B1–B2 forecast/count machinery is an explicitly selected accountable profile, and the pilot is optional policy evaluation. Added mode-specific verification, AI contracts, templates, and pilot failure modes F12–F14. Sources and historical appendix retained without new verification; no claim that this policy is validated. |
| v1.5.1 | Exhaustive checkpoint classes ("stopped on evidence" added; "not attempted" must be pre-dated; "missed" residual). F11 added. Named domain-competent F3 judge. B3 aligned with F10. At most three pilots. Condensed edition: wording shortened, no rule changes. |
| v1.5 | Defined miss count. Artifact-based capability milestones. Procedural rationale for B1–B4. Documentation tiers and overhead allowance. Rule register. Pilot counted in deep-path reviews, with non-operator reviewer, pre-registered failure modes and a mechanical end mapping. |
| v1.4 | Confidence, effort and completion criteria in forecasts. Two misses trigger reassessment rather than presumptive parking. B3 broadened to learning. B4 retains assets and excludes sunk expenditure. Appendix A separates justification from outcome. B2 historical scoring gated on milestone evidence. Determinacy quotas and outcome-based "vindication" removed. Frozen prospective pilot added. |
| v1.3.1 | Appendix A (backtest protocol) added; no rule changes. |
| v1.3 | B1–B4 introduced. At that stage B1 was "binding" and B2 was a burden-shift with written override; both were softened in v1.4. Motivated by Run 2, which is unverified. |
| v1.2 | Contribution-specific evidence replaced the universal ranking. Partial order replaced the lattice model. Conditional-probability scenario model. Evidence-sensitive stopping. Inconclusive probe outcomes. Computational proof recognized. Separate claim dimensions. Dependency-based verification. Protected long-horizon work. Operating checklist. |
| v1.1 | Amendments A1–A7: substantive sharpening, patience, reconsidering familiar tools, trigger-based reentry, cheap probes, explicit reductions, method/program separation. Retained since v1.2 as conditional rather than universal rules. |

### Sources

- **[S1] Terence Tao, "Learn the limitations of your tools."** Expert methodological advice supporting attention to counterexamples, model situations and comparative tool limitations. It is not controlled evidence for an optimal research policy. https://terrytao.wordpress.com/career-advice/learn-the-limitations-of-your-tools/
- **[S2] Terence Tao, "Be flexible."** Expert advice on revising research goals and maintaining feasible intermediate plans. https://terrytao.wordpress.com/career-advice/be-flexible/
- **[S3] Georges Gonthier, "Formal Proof—The Four-Color Theorem," Notices of the AMS 55(11), 2008, pp. 1382–1393.** A primary account of a formalized proof and of the importance of specifying the intended theorem correctly. Accessible copy: https://www.cs.cornell.edu/courses/JavaAndDS/files/Gonthier4ColorCoq.pdf

Checked during v1.2, not re-browsed for v1.6. They support only the narrow points attributed to them. The new theory-building, exploration, and documentation-profile recommendations are unsourced design choices (~), not findings attributed to these sources.

---

## Appendix A. Retrospective review protocol

This protocol examines historical decisions as a source of possible defects, not as a reliable performance benchmark. Design choices are (~), unsourced. Case facts require dated sources; this revision does not verify the previously reported runs or candidate histories.

### A.1 Separate three questions

1. **Policy behavior:** what would the frozen rule require, recommend, permit or leave unresolved?
2. **Contemporaneous justification:** was that behavior justified by evidence and feasible alternatives available at the decision date?
3. **Outcome compatibility:** was it compatible with the route that eventually succeeded or failed?

(+) These questions are distinct. Eventual success does not establish that an earlier continuation was justified, and failure does not establish that a risky attempt was unjustified. A sound allocation decision can have an unfortunate outcome.

A retrospective case can expose a logical defect when a rule contradicts established information available at the time. It may also reveal ambiguity or practical burden. It cannot directly observe what would have happened under an unchosen policy.

### A.2 Case selection and comparison sets

Use successes, stalled or abandoned routes, barriers and disputed claims as **comparison cases**, not as experimental controls with a known optimal action.

Freeze selection reasons before scoring. Include short and long efforts, conceptual and computational work, and decisions without decisive evidence. Favor dated records of actual options, resources and uncertainty.

A held-out historical case can reduce direct tuning to that case, but it is not blinded when reconstructors know its outcome. Record prior familiarity. Do not call a case an untouched holdout if it motivated a rule or was previously scored.

If the historical researcher's budget, objective or alternatives differ from the intended user, record that limitation. Do not assume the same allocation policy should apply unchanged.

### A.3 Reconstruct the knowledge state before judging it

For each decision date, record dated evidence for:

- known results, barriers, tools and proof status;
- actual feasible actions, objectives, resources and constraints;
- relevant failed attempts and their scope;
- checkpoint expectations, criteria, effort and confidence, when recorded;
- information that became available only later.

Keep subsequent outcomes in a separate field. Where feasible, have the initial assessment made without the outcome summary, while acknowledging prior familiarity.

**B2 assessability gate:** B2 can be assessed only with contemporaneous expectations, completion criteria, effort and chronology sufficient to classify checkpoints under the B1 counting rule.

- A documented proxy may support a qualified assessment if its limitations are explicit.
- Missing confidence limits interpretation of the misses.
- Missing evidence of expectations or effort can make B2 entirely unassessable.

Never manufacture two milestones after learning the outcome. Mark **not assessable** when evidence is insufficient. A hypothetical scenario using invented checkpoints may test internal consistency, but it is not a historical backtest result.

### A.4 Scoring without outcome-defined correctness

Score generation, allocation, novelty and verification separately when relevant.

| Axis | Allowed entries |
| --- | --- |
| Policy behavior | Requires / recommends by default / permits / silent / conflicting rules |
| Assessability | Adequate / qualified proxy / insufficient |
| Contemporaneous justification | Supported / contradicted / indeterminate |
| Eventual outcome compatibility | Compatible / incompatible / mixed / unknown |
| Confidence | High / moderate / low, with reasons |
| Default departure | Supported / contradicted / indeterminate / not applicable |

Use "contradicted" only when available evidence establishes a conflict, such as relying on a refuted required lemma; allocation quality will often be indeterminate. Score the default and a justified departure separately, cite the exact rule, and report rule conflicts rather than choosing a favorable reading. A heuristic that could accommodate a known winning idea does not show a researcher would have generated it.

**Report:** assessable and unassessable counts with reasons; supported, contradicted and indeterminate judgments by decision type; logical conflicts and unsupported directives; directive frequency (no quota); outcome incompatibilities, separately from decision defects; missing information and sensitivity to reconstruction. "False stop" or "false continuation" labels need an evidential standard stronger than the outcome.

**Review criteria:** investigate every contradiction, justify strong directives from contemporary evidence, compare old and new rules on the same evidence, and separate rule changes from scoring changes. More determinacy is not inherently better; there is no minimum directive rate.

### A.5 Procedure

1. Freeze the policy and case list.
2. Build sourced case cards, keeping contemporary information separate from later outcomes.
3. Apply the assessability gate, especially for B2.
4. Record policy behavior and justification before comparing eventual outcomes.
5. Examine contradictions, ambiguity and sensitivity to uncertain reconstruction.
6. Propose only targeted corrections, and check whether they create new problems elsewhere.
7. Record what remains unknown. Prefer the bounded prospective pilot over repeated historical tuning.

Where feasible, a second scorer who did not build the case cards scores independently, as in the pilot (§10.3).

The absence of detected contradictions is not validation. A benign outcome cannot rescue a logically invalid rule, and an unfortunate outcome cannot by itself discredit a justified decision.

### A.6 Prior run reports (unverified historical record)

**Run 1 (v1.1; `strategy_backtest_solved_problems.md`).** 12 success cases: cap set, sensitivity, Poincaré, Fermat, bounded prime gaps, sphere packing (dim. 8), Hirsch counterexample, Erdős discrepancy, Kahn–Kalai, union-closed sets, Kepler, Kakeya in ℝ³. Compatibility scoring; no controls or holdout; unsourced. Reported 4 false stops on long programs (sensitivity, Poincaré, Fermat, Kakeya); motivated A1–A7 without a holdout.

**Run 2 (v1.2; `strategy_backtest_v1_2.md`).** The same 12 plus 7 controls (P vs NP barriers, sieve parity, Lamé, Whitehead's false proof, de Branges on RH, post-Kummer Fermat, Collatz) and 2 verification controls (Jacobian conjecture, abc/IUT). Directive scoring; same reconstructor; unsourced. Reported zero D✗, hard-evidence controls D✓, soft-middle allocation mostly P or I. Motivated B1–B4, so no version from v1.3 on has been tested by this protocol.

**Run 3 (v1.3 holdout): not run.** Its outcome-based scoring is superseded; do not translate old D✓/D✗ scores into justification judgments. Priority goes to the pilot.

### A.7 Candidate holdout cases (not yet reconstructed or scored)

These candidates are unsourced and drawn from general knowledge. (~) Details must be checked against dated sources while writing case cards. Inclusion is not a scoring commitment; freeze the final list first (A.2).

**Success candidates**

| Case | Type | Tests |
| --- | --- | --- |
| Hadwiger–Nelson lower bound 5 (de Grey, 2018; Polymath16) | Computation-heavy construction, outsider | Probe budget; computation in proof (§8.3) |
| Duffin–Schaeffer conjecture (Koukoulopoulos–Maynard, 2019) | Long program, new structural input | Long-horizon expectations (B1/B2) |
| Kelley–Meka bounds for 3-term progressions (2023) | Sudden improvement over a stalled Fourier program | Soft-middle allocation; revisiting a method |
| Erdős–Faber–Lovász for large n (2021) (~) | Absorption / nibble methods in a mature area | Transplant and fast-follow |
| Ringel's conjecture (2020) (~) | Long-open combinatorics, new embedding techniques | Generation moves |
| Bieberbach conjecture (de Branges, 1985) | Outsider-style proof, verified by others | Verification of an unexpected claim; contrast with control de Branges/RH |
| Mordell conjecture (Faltings, 1983) | Long program, decisive new tools | Long-horizon allocation |

**Stall, barrier and disputed-claim candidates**

| Case | Type | Tests |
| --- | --- | --- |
| Tao's averaged Navier–Stokes blowup (2014) as a barrier | Proved barrier for a method class | Barrier handling outside number theory and complexity |
| Binary Goldbach via the circle method (minor-arc obstruction) | Soft stall with a known structural reason | Soft-middle redirection |
| Lonely runner conjecture: case-by-case progress (~) | Examples without a general mechanism | Drift prompt (B3) |
| A contested or retracted claimed proof in a new field (select with sources) | Verification | Claim-management robustness |

**Balance check before freezing:** at least 3 soft-evidence controls, 2 outsider cases, 2 computation-heavy cases and 2 long programs that succeeded.

### A.8 Templates

**A.8.1 Case card**

```markdown
## Case: <name>
- Selection reason; decision date(s); policy version:
- Objective, resources and feasible alternatives at that date:
- Contemporary knowledge and dated primary sources:
- Actual expectations, criteria, confidence and effort records:
- Proxy assumptions; missing evidence; B2 assessable under the B1 counting rule? why:
- Decision type: generation / allocation / novelty / verification
- Hindsight leakage risks and prior familiarity:
- Later outcome (kept separate from decision assessment):
```

**A.8.2 Scoring sheet**

```markdown
## Assessment: <policy version> × <case>
- Decision and exact rule:
- Policy behavior:
- Assessability and missing information:
- Contemporaneous justification: supported / contradicted / indeterminate
- Evidence and confidence:
- Default departure: assessment and reason
- Eventual outcome compatibility (separate):
- Sensitivity to reasonable alternative reconstructions:
- Second scorer (if any) and disagreements:
```

**A.8.3 Run record**

```markdown
## Run: <name>
- Date, scorer(s), frozen policy and case list:
- Prior exposure; held-out status and its limitations:
- Sources and protocol deviations:
- Assessable / qualified / insufficient counts:
- Justification judgments by decision type:
- Logical defects, unsupported directives and ambiguity:
- Outcome compatibility (not decision-quality scores):
- Corrections proposed; evidence still needed:
```

### A.9 Threats to validity

| Threat | Effect | Mitigation |
| --- | --- | --- |
| Outcome bias | Success is mistaken for a justified earlier choice | Separate justification and outcome axes |
| Hindsight | Winning ideas or milestone expectations are reconstructed as obvious | Dated records; explicit missingness; assessability gate |
| Selection | Continued paths have observed outcomes while parked paths often do not | Record missing outcomes; avoid threshold inference from continuation success |
| Overfitting | Rules are repeatedly adjusted to familiar cases | Freeze rules; document prior exposure; prospective pilot |
| Shared judgment | One reconstructor or operator repeats the same assumptions | Independent second scorer; non-operator pilot reviewer scoring blind-first |
| Unsourced history | Inaccurate chronology produces confident scores | Require primary sources for consequential judgments |
| Metric gaming | More directives or easier milestones appear to improve performance | No determinacy quota; F3 (domain-competent judge) and F11 in the pilot; review utility, difficulty and effort |
| Unexercised rules | A rule appears to pass because it never fired | F10: treat as inconclusive; rerun with adjusted cadence or program |
| Unobserved alternatives | Chosen-path success is mistaken for superiority | Record alternatives and acknowledge unknown counterfactuals |

Prior runs are retained for provenance. Their reported findings require reassessment under this protocol before being treated as decision-quality evidence.
