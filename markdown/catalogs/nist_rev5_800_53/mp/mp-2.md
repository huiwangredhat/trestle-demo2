---
x-trestle-set-params:
  mp-2_prm_1:
    values:
  mp-2_prm_2:
    values:
  mp-02_odp.01:
    values:
  mp-02_odp.02:
    values:
  mp-02_odp.03:
    values:
  mp-02_odp.04:
    values:
x-trestle-global:
  sort-id: mp-02
---

# mp-2 - \[Media Protection\] Media Access

## Control Statement

Restrict access to {{ insert: param, mp-2_prm_1 }} to {{ insert: param, mp-2_prm_2 }}.

## Control Assessment Objective

- \[MP-02[01]\] access to {{ insert: param, mp-02_odp.01 }} is restricted to {{ insert: param, mp-02_odp.02 }};

- \[MP-02[02]\] access to {{ insert: param, mp-02_odp.03 }} is restricted to {{ insert: param, mp-02_odp.04 }}.

## Control guidance

System media includes digital and non-digital media. Digital media includes flash drives, diskettes, magnetic tapes, external or removable hard disk drives (e.g., solid state, magnetic), compact discs, and digital versatile discs. Non-digital media includes paper and microfilm. Denying access to patient medical records in a community hospital unless the individuals seeking access to such records are authorized healthcare providers is an example of restricting access to non-digital media. Limiting access to the design specifications stored on compact discs in the media library to individuals on the system development team is an example of restricting access to digital media.
