# Web Research Context Bundle

This file is generated from repository truth and bounded for the web channel. It is navigation context, not a Result, EvidenceLink, verifier receipt, or permission grant.

## Mandatory order

1. Read `AGENTS.md`, `governance/harness/PROJECT_AGENTS.md`, and `WEB_BOOTSTRAP.md`.
2. Check the exact ProblemContract and its SHA-256 below.
3. Select exactly one pre-admitted Attempt/Route/ObligationGraph/Obligation.
4. Search registered mathematical knowledge sources before inventing a new theorem.
5. After repository admission, autonomously complete Issue, candidate branch/file edits, commit, PR review, checks/rerun, merge, and checkpoint within the profile.
6. Write only candidate files under the profile allowlist and one `WEB_ATTEMPT_PACKET`; do not wait for project-added routine human approvals.
7. Never claim that Issue, PR, AI review, merge, Actions status, package build, search hit, test success, or this context closes mathematics.

## Compiled repository truth

```json
{
  "active_skills": [
    {
      "entry": ".codex/skills/math-computation/SKILL.md",
      "entry_sha256": "80c447221725ec198bee4b104d43ca28425110a7dac17afa9cad56ec69b57f48",
      "skill_id": "math-computation",
      "version": "0.6.0",
      "web_status": "constrained"
    },
    {
      "entry": ".codex/skills/math-derivation/SKILL.md",
      "entry_sha256": "3f3b567729f1e5dd24f87e832fdac702577f4add14b8cf6be12d538e1fe787c1",
      "skill_id": "math-derivation",
      "version": "0.4.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/math-discovery/SKILL.md",
      "entry_sha256": "ceb54d773cd970ca42d0243fb1a39b109cab3ffdbe2dd87b98b43539f988d471",
      "skill_id": "math-discovery",
      "version": "0.4.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/math-formalization/SKILL.md",
      "entry_sha256": "8ade921dacd277f425f424064a6002806c057f160555081dbdb4ec05c1f5ea05",
      "skill_id": "math-formalization",
      "version": "0.5.0",
      "web_status": "constrained"
    },
    {
      "entry": ".codex/skills/math-proof/SKILL.md",
      "entry_sha256": "61006c732ad69e73f56be126acb6fa9e25c866e18733ce1f0f3863c1f8eea80f",
      "skill_id": "math-proof",
      "version": "0.5.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/math-toolchain/SKILL.md",
      "entry_sha256": "f6514e01358aa2e40f8b7e3bb9221fd9abca6b7ff37ec6920f2c2cf537533f7b",
      "skill_id": "math-toolchain",
      "version": "0.2.0",
      "web_status": "constrained"
    },
    {
      "entry": ".codex/skills/solve/SKILL.md",
      "entry_sha256": "ff557dc3fc2fa10df4b21e8bef251a37928f5572ccf0092c79f0d9ab90a00ec0",
      "skill_id": "solve",
      "version": "0.3.0",
      "web_status": "active"
    },
    {
      "entry": ".codex/skills/vibe-mathing-router/SKILL.md",
      "entry_sha256": "65f6b25fe152a4cc2fa9ecb03626dad6e3b70473fc256ac9acbabd0ef7cb9e8e",
      "skill_id": "vibe-mathing-router",
      "version": "0.4.0",
      "web_status": "active"
    }
  ],
  "attempts": [
    {
      "artifacts": [],
      "attempt_id": "attempt:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-source-fidelity-01",
      "claims": [],
      "completed_at": null,
      "generator": "trusted-rolling-source-admission-v1",
      "inputs": [
        "problem-library/records/canonical-problems.jsonl",
        "https://www.unsolvedmath.com/problems/GREEN-098"
      ],
      "lifecycle": "planned",
      "method": "discovery",
      "objective": "Close the source-fidelity obligation before attempting the frozen root statement.",
      "obligation_graph_id": "graph:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-v1",
      "problem_contract_sha256": "74cc1ac0ca848ccc5b4a2c6ec8d392782ca3fa4cd27e0fdaba68ef35a4bce80a",
      "problem_id": "problem:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9",
      "route_id": "route:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-source-fidelity",
      "started_at": "2026-09-06T15:37:58Z"
    }
  ],
  "failed_routes": [],
  "knowledge_operators": [
    {
      "evidence_ceiling": "discovery_only",
      "external_effect": "none",
      "operator_id": "op:identify-mathematical-object",
      "owner_skill": "math-discovery"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "read_local",
      "operator_id": "op:search-formal-theorem",
      "owner_skill": "math-discovery"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "read_network",
      "operator_id": "op:search-mathematical-database",
      "owner_skill": "math-discovery"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "read_local",
      "operator_id": "op:resolve-formal-package",
      "owner_skill": "math-formalization"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "none",
      "operator_id": "op:compare-statements",
      "owner_skill": "math-proof"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "none",
      "operator_id": "op:compose-reuse-plan",
      "owner_skill": "math-proof"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "none",
      "operator_id": "op:prove-reuse-gap",
      "owner_skill": "math-proof"
    },
    {
      "evidence_ceiling": "candidate_only",
      "external_effect": "bounded_candidate_build",
      "operator_id": "op:build-formal-candidate",
      "owner_skill": "math-formalization"
    },
    {
      "evidence_ceiling": "verifier_receipt",
      "external_effect": "bounded_candidate_build",
      "operator_id": "op:verify-formal-candidate",
      "owner_skill": "math-formalization"
    },
    {
      "evidence_ceiling": "verifier_receipt",
      "external_effect": "none",
      "operator_id": "op:review-reuse-semantics",
      "owner_skill": "math-proof"
    }
  ],
  "knowledge_sources": [
    {
      "evidence_ceiling": "verifier_input",
      "maturity": "installed",
      "operational_status": "quarantined",
      "source_class": "formal_library_index",
      "source_id": "lean-mathlib-local"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "formal_package_registry",
      "source_id": "lean-reservoir"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "formal_library_index",
      "source_id": "mathlib-docs-search"
    },
    {
      "evidence_ceiling": "verifier_input",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "proof_archive",
      "source_id": "isabelle-afp"
    },
    {
      "evidence_ceiling": "verifier_input",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "formal_package_registry",
      "source_id": "rocq-mathcomp"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "mathematical_object_database",
      "source_id": "oeis"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "mathematical_object_database",
      "source_id": "lmfdb"
    },
    {
      "evidence_ceiling": "candidate_only",
      "maturity": "surveyed",
      "operational_status": "available",
      "source_class": "formula_reference",
      "source_id": "nist-dlmf"
    },
    {
      "evidence_ceiling": "computation_evidence",
      "maturity": "surveyed",
      "operational_status": "design_only",
      "source_class": "algorithm_distribution",
      "source_id": "sagemath"
    }
  ],
  "obligation_graphs": [
    {
      "attempt_id": "attempt:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-source-fidelity-01",
      "graph_id": "graph:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-v1",
      "obligations": [
        {
          "dependencies": [
            "obligation:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-statement-fidelity"
          ],
          "kind": "root_claim",
          "obligation_id": "obligation:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-root",
          "statement": {
            "formal_declaration": null,
            "language": "en",
            "text": "Let $d \\geq 3$ be an odd integer. Give bounds on $\\nu(d)$ such that if $n > \\nu(d)$ the following is true: given any homogeneous polynomial $F(\\mathbf{x}) \\in \\mathbb{Z}[x_1, \\dots, x_n]$ of degree $d$, there is some $\\mathbf{x} \\in \\mathbb{Z}^n \\setminus \\{\\mathbf{0}\\}$ such that $F(\\mathbf{x}) = 0$."
          },
          "statement_sha256": "d0634285ea1b169711a356b8f6fdb69026c3c9c56029ff8b9eade707f9d05b49"
        },
        {
          "dependencies": [],
          "kind": "definition",
          "obligation_id": "obligation:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-statement-fidelity",
          "statement": {
            "formal_declaration": null,
            "language": "en",
            "text": "Verify against the cited source that the frozen statement is complete, current, untruncated, attribution-correct, and unambiguous enough for mathematical research; record any definition or quantifier gap without silently editing the contract."
          },
          "statement_sha256": "65f0b3d574bd6d837403149dab6434c0f571709f7eb5bb066c7e8774bad13f34"
        }
      ],
      "root_obligation_id": "obligation:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-root",
      "route_id": "route:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9-source-fidelity"
    }
  ],
  "problem_contract": {
    "acceptance": {
      "policy": "solution-admission-v1"
    },
    "aliases": [
      "UnsolvedMath GREEN-098"
    ],
    "allowed_axioms": [
      "classical-mathematics",
      "source-explicit-definitions-only"
    ],
    "assumptions": [
      "No assumptions beyond those explicitly present in the exact source statement are admitted.",
      "Statement-faithfulness and current-status review must close before the root mathematical obligation can close."
    ],
    "constraints": {
      "allowed_adapters": [
        "source-fidelity-review-v1",
        "lean-obligation-v1"
      ],
      "allowed_methods": [
        "discovery",
        "derivation",
        "computation",
        "proof",
        "formalization"
      ],
      "max_attempts": 20,
      "runtime": {
        "max_output_bytes": 5242880,
        "max_retries": 3,
        "max_transitions": 300,
        "timeout_seconds": 1800
      }
    },
    "created_at": "2026-09-06T15:37:58Z",
    "definitions": [
      {
        "definition": "Use the statement, notation, terminology, and quantifier scope exactly as given by the cited source record. No unstated normalization or strengthening is admitted; ambiguity blocks Result admission until a versioned ProblemContract update.",
        "term": "source-native interpretation"
      }
    ],
    "domain": {
      "description": "Source-native Number Theory problem. Mathematical objects and notation are exactly those explicitly present in the frozen source statement.",
      "objects": [
        "objects and notation explicitly named in the frozen source statement"
      ]
    },
    "lifecycle": "active",
    "msc": [
      "11-01"
    ],
    "problem_id": "problem:um-green-098-bounds-for-homogeneous-polynomial-zero-f9515dc9",
    "quantifiers": [
      {
        "domain": "truth of the exact frozen source statement under its explicit quantifiers",
        "kind": "decide",
        "variables": []
      }
    ],
    "schema_version": "1.0.0",
    "sources": [
      {
        "retrieved_at": "2026-09-02T00:06:43Z",
        "source": "UnsolvedMath dataset contributors (CC BY 4.0)",
        "source_record_id": "unsolvedmath-green-098-24b60c3508b9",
        "url": "https://www.unsolvedmath.com/problems/GREEN-098"
      },
      {
        "retrieved_at": "2026-09-02T00:06:43Z",
        "source": "UnsolvedMath dataset license",
        "source_record_id": null,
        "url": "https://creativecommons.org/licenses/by/4.0/"
      }
    ],
    "statement": {
      "language": "en",
      "text": "Let $d \\geq 3$ be an odd integer. Give bounds on $\\nu(d)$ such that if $n > \\nu(d)$ the following is true: given any homogeneous polynomial $F(\\mathbf{x}) \\in \\mathbb{Z}[x_1, \\dots, x_n]$ of degree $d$, there is some $\\mathbf{x} \\in \\mathbb{Z}^n \\setminus \\{\\mathbf{0}\\}$ such that $F(\\mathbf{x}) = 0$.",
      "version": 1
    },
    "title": "Bounds for Homogeneous Polynomial Zeros",
    "updated_at": "2026-09-06T15:37:58Z"
  },
  "problem_contract_sha256": "74cc1ac0ca848ccc5b4a2c6ec8d392782ca3fa4cd27e0fdaba68ef35a4bce80a"
}
```
