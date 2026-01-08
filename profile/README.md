# Research Group Analysis Resources

This organization hosts **internal documentation, tutorials, and example workflows**
for data analysis, simulations, and modeling used by the research group.

All repositories are **private** unless explicitly stated otherwise.

---

## Who this is for
This organization is intended for:
- Master and PhD students
- Postdocs
- Long-term collaborators of the group

All repositories are **private** unless explicitly stated otherwise.

---

## Structure overview

Repositories are organized around two main axes:

### Experiments
Documentation and examples related to specific instruments or observatories.

<h2>Instruments</h2>

<pre>
instruments/
├── fermi/
│   ├── lat/
│   └── gbm/
└── magic_lst1/
    ├── magic/
    ├── lst1/
    └── joint_magic_lst1/
</pre>


Each subdirectory contains instrument-specific tutorials, example analyses,
and references.

---

### Software and tools
Documentation and guides for analysis frameworks, simulations, and infrastructure.

<h2>Software</h2>

<pre>
software/
├── analysis/
│   ├── threeML/
│   ├── gammapy/
│   ├── jetset/
│   └── bc_tools/
├── simulations/
│   ├── geant4/
│   └── corsika/
├── infrastructure/
│   └── slurm/
└── ML_python/
</pre>

---

## How to get access
Access is granted by organization owners.

If you are a new group member:
1. Create a personal GitHub account (if you don’t have one)
2. Ask an owner to add you to the organization
3. You will receive an invitation by email

**Shared accounts are not allowed.**

---

## How to contribute
- Follow the structure defined in each repository
- Add documentation in Markdown whenever possible
- Use Jupyter notebooks only when they add pedagogical value
- Do not commit large datasets or raw simulation outputs

---

## Governance
The organization is maintained by designated owners.
Ownership and access are reviewed as group membership changes.
