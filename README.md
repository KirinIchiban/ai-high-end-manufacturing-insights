# SCUT Summer School 2026 - Analytical Essays

Two essays written during the Summer School "Artificial Intelligence and High-End
Manufacturing" at South China University of Technology (SCUT), 2026. Both combine
lecture material with observations from industrial site visits and exhibitions in
China. Written in English and reviewed within the program.

The primary essay addresses morphological choice in industrial robotics. The second
is a technical review of closed-loop neurofeedback, written from a background outside
biology and medicine.

## Contents

| File | Title | Subject |
|---|---|---|
| `humanoid-robot-transitional-form.pdf` | The Humanoid Robot as a Transitional Form | Industrial robotics, morphology, Industry 4.0 |
| `bci-car-sickness.pdf` | Brain-Computer Interfaces: From Neural Control to a Cure for Car Sickness | EEG decoding, closed-loop neurofeedback |

---

## The Humanoid Robot as a Transitional Form

*Why Anthropomorphism Is Justified Today and Why It Will No Longer Be Optimal Tomorrow*
### Thesis

The humanoid form factor is not the endpoint of industrial robotics. It is a
transitional solution made necessary by the fact that existing factories,
substations and warehouses were built around human bodies. As that infrastructure
is replaced and redesigned around machines, anthropomorphic morphology loses its
advantage to task-specific, embedded cyber-physical systems.

### Structure of the argument

1. The lecture series defines an
   intelligent robot through human-like capability and illustrates it with humanoid
   imagery, but its examples of highest-tier industrial robotics - Yaskawa
   manipulators and Intuitive Surgical's da Vinci - are fixed or wheeled articulated
   arms. Where precision and economic value are highest, human resemblance disappears.

2.  Hardware selection requires matching degrees of freedom and reach to the task, not
   reproducing human anatomy. Distributed sensing places cameras and force-torque
   sensors where information quality is highest, not where a head or a hand would be.
   Real-time feedback locates performance in information processing rather than in
   body plan.

3. Bipedal locomotion carries an energy penalty: typical
   humanoid battery packs of 0.8–2.5 kWh yield two to four hours of dynamic operation,
   much of it spent on balance and posture correction. Dexterous manipulation faces a
   perception gap rather than a mechanical one - Brooks notes roughly 17,000 tactile
   receptors in the human hand against a small fraction of that in robotic hands,
   with no ImageNet-scale tactile dataset available to close the difference.

4. The Chinese ecosystem is diversifying, not converging. WAIC 2026 showed
   humanoids (AgiBot A3, Unitree G1) alongside quadruped inspection platforms and
   dedicated dexterous hands, indicating parallel specialization rather than movement
   toward a universal form.
### Treatment of the counterargument

The strongest objection is that humanoids solve access problems in legacy
environments. MIIT began drafting humanoid industry standards in June 2026 for
substations and appliance manufacturing; operators report that roughly 30% of
substation inspection points are unreachable by wheeled platforms, while State Grid
Sichuan's Hertz can negotiate stairs and narrow passages.

The essay resolves this by separating two problems that the substation case
conflates: **navigation** through human-scaled terrain, where legs are genuinely
useful, and **operation** of switchgear according to fixed procedures, which does not
require a human-shaped body. Intelligent cabinets and embedded manipulators would
remove the need for a mobile humanoid intermediary. The standardization effort
therefore supports the thesis rather than contradicting it: form follows the
operational environment, and that environment is currently human-shaped.

### Primary observation

Two visits are used as contrasting evidence. At GAC Aion, specialized manipulators
worked alongside human operators who handled contextual decisions; anthropomorphic
appearance was irrelevant to the system's efficiency. At a China Mobile exhibition,
a humanoid performing dance and taekwondo routines became unresponsive and was
removed for troubleshooting before returning to finish the routine - a demonstration
of potential rather than of reliable operation.

---

## Brain-Computer Interfaces: From Neural Control to a Cure for Car Sickness

An attempt to reconstruct the BCI pipeline end to end - EEG acquisition, decoding,
and mapping onto external action or feedback - written from a background in applied
mathematics rather than biology.

The organizing observation is that BCI collapses the usual distinction between
diagnosis and treatment. The same signal used to detect a cognitive state can be
returned to the user to change it, which makes measurement part of the intervention.

The essay follows this through three paradigms - motor imagery (mu rhythm,
8–12 Hz), P300, and SSVEP - and two applications: detection of cognitive-motor
dissociation in disorders of consciousness, and neurofeedback treatment of motion
sickness. The latter is treated in detail because it reframes a condition usually
managed pharmacologically as a trainable attentional state, and because it is
supported by an objective marker (increased frontal beta relative power) rather than
subjective report alone, with effects persisting over a ten-week follow-up.

The closing section connects this to a convergence outside medicine: the
Microsoft–Volkswagen HoloLens project renders a stable virtual horizon from GPS and
motion data, intervening on the same visual–vestibular mismatch at the environment
rather than the brain. As VR, AR and autonomous vehicles proliferate, sensory
conflict becomes a general problem, and public acceptance of non-invasive consumer
devices will matter as much as decoding accuracy.

---

## Notes on sources

Both essays are analytical, not original research. They draw on lecture material from
the SCUT program, direct observation during industrial visits, industry reporting and
published experimental results available at the time of writing. Quantitative figures
and market forecasts are reproduced as reported in those sources and were not
independently verified.

## Author

Irina [Surname]
BSc student, Applied Mathematics and Informatics, Moscow Aviation Institute
Interests: robotics, sensor fusion, applied algorithms
[email]
