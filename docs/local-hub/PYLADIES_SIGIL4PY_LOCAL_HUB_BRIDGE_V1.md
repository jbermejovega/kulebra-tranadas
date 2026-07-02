# PyLadies · SIGIL4Py Local Hub Bridge V1

```yaml
id: PYLADIES_SIGIL4PY_LOCAL_HUB_BRIDGE_V1
repo: jbermejovega/kulebra-tranadas
status:
  local_hub_bridge: true
  pyladies_interaction_supported: true
  public_collaboration_surface: true
  canonical_source: jbermejovega/sigilbook
  safe_replay: true
  trace_preserved: true
  pi_fixed: true
  no_identity_transport: true
  piornalego_es_canon: true
```

## Purpose

This document makes `kulebra-tranadas` a public/local hub for friendly interaction with PyLadies-oriented contributors around SIGIL4Py, SIGILAPI, Django/Vue surfaces, accessibility, tutorials, and developer onboarding.

`kulebra-tranadas` is a public local hub and witness surface. It does not replace `jbermejovega/sigilbook` as the canonical source of law for SIGILAPI, PACAPDG, QQUAPP, SIGIL4Py, or release authority.

## Safe contribution modes

```yaml
safe_modes:
  - docs_first_contribution
  - beginner_friendly_issue
  - glossary_improvement
  - tutorial_feedback
  - accessibility_review
  - PyConES_abstract_feedback
  - local_workshop_notes
  - demo_issue_linking_back_to_sigilbook
```

## Suggested first tasks

```text
1. Read the SIGIL4Py abstract.
2. Suggest clearer wording for newcomers.
3. Add glossary entries for SIGIL, KQC, PACAPDG, QQUAPP, and replay.
4. Review accessibility and localization wording.
5. Propose tutorial examples that do not require secrets or deploy permissions.
```

## Cross-repo bridge

```yaml
bridge:
  canonical_repo: jbermejovega/sigilbook
  local_hub_repo: jbermejovega/kulebra-tranadas
  sigilbook_issue: 119
  sigilbook_pr: 120
  flow:
    - local_hub_feedback
    - issue_or_pr_in_tranadas
    - link_back_to_sigilbook_milestone
    - maintainer_review
    - canonical_update_in_sigilbook_when_needed
```

## Forbidden

```yaml
forbidden:
  - sharing_secrets
  - direct_release_from_local_hub
  - unreviewed_pypi_upload
  - force_move_transport
  - treating_local_hub_as_canonical_authority
  - identity_transport_between_repositories
```

## KLOSE

```text
PyLadies interaction is welcome.
Tranadas is a local public hub.
SIGILBOOK remains canonical.
Contributors enter through issues and PRs.
No secrets.
No direct release.
No identity transport.

SAFE_REPLAY.
TRACE_PRESERVED.
PI_FIXED.
PIORNALEGO ES CANON.
```
