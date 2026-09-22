# Interlocking Sustainable Foam-Core Chair

A full-scale chair developed around foam-core structural design, interlocking assembly, and laser-cut fabrication. The project includes concept selection, Autodesk Inventor CAD, preliminary FEA, fabrication, and a documented static prototype demonstration.

**Tools:** Autodesk Inventor, Inventor FEA, laser cutting, foam-core fabrication

## Objective and requirements

The design objective was to create a lightweight chair that satisfied the documented dimensional and manufacturing constraints while targeting a 103 kg static-load requirement.

| Requirement | Documented value |
| :--- | :--- |
| Material | 5 mm foam-core sheets |
| Sheet envelope | 457 x 610 mm |
| Target mass | Below 800 g; preferred stretch target below 400 g |
| Assembly | Interlocking slots and tabs; no external fasteners, adhesives, or tape |
| Seat height | 480-530 mm |
| Seat envelope | 410-450 mm wide and deep |
| Backrest height | 280-480 mm |
| Static load requirement | 103 kg |

The engineering report gives a **462 g CAD-predicted mass** calculated from Inventor geometry and material density. This is not a documented physical scale measurement.

## Concept development and selection

Three structural concepts were compared using a Pugh matrix across nine weighted criteria: dimensions, mass, comfort, fabrication, design effort, part count, fastening requirements, appearance, and probability of success. The multi-rib interlocking concept was selected for detailed design.

## Mechanical design and analysis

The selected design uses multi-rib foam-core construction with interlocking slot-and-tab joints. Lines-of-force analysis was used to consider load paths and likely stress-concentration regions before detailed modeling.

The [design-choice and FEA document](Sustainable%20Chair%20Design%20Choice%20and%20FEA.pdf) and [engineering report](Sustainable_Chair_Report.pdf) contain the available analysis documentation, including Autodesk Inventor FEA figures for seat and backrest loading conditions. The original FEA study files and result database are not included.

## Fabrication and physical test

The documented workflow included generating flat-pattern geometry from the CAD design, laser cutting 5 mm foam-core stock, and assembling the parts with press-fit joints without glue or mechanical fasteners.

The available [before-test documentation](Chair%20Before%20Test.pdf) and [after-test documentation](Chair%20After%20Test.pdf) show the physical prototype test evidence. The project documents a static demonstration in which the prototype supported a 103 kg load with minimal observed local damage afterward. This is a physical observation from the documented demonstration, not a load-cell measurement, structural certification, or durability test.

## Sustainability considerations and limitations

The design explores material-conscious choices through low-mass geometry, flat-pattern fabrication, reduced part count, and an interlocking assembly that avoids adhesives and external fasteners. These are design considerations, not a quantified lifecycle or environmental assessment.

The repository does not include carbon-footprint, embodied-energy, cost, lifecycle, or quantified waste-reduction calculations. It also does not include a documented physical mass measurement or durability study.

## Repository structure

```text
Sustainable-Chair/
|-- README.md
|-- .gitignore
|-- Chair After Test.pdf
|-- Chair Before Test.pdf
|-- Sustainable Chair Design Choice and FEA.pdf
|-- Sustainable Chair Ideas.pdf
|-- Sustainable_Chair_Report.pdf
`-- CAD/
    |-- sustainable_chair_assembly.iam
    |-- sustainable_chair_presentation.ipn
    `-- Parts/
        |-- backrest.ipt
        |-- inside_leg.ipt
        |-- inside_leg_2.ipt
        |-- outside_leg.ipt
        |-- seat.ipt
        |-- slats.ipt
        |-- slats_back_over.ipt
        |-- slats_back_under.ipt
        `-- slats_under.ipt
```

## Project files

- [Assembly](CAD/sustainable_chair_assembly.iam)
- [Presentation](CAD/sustainable_chair_presentation.ipn)
- [Parts directory](CAD/Parts/)
- [Engineering report](Sustainable_Chair_Report.pdf)
- [Design choice and FEA document](Sustainable%20Chair%20Design%20Choice%20and%20FEA.pdf)
- [Ideas and concept-development document](Sustainable%20Chair%20Ideas.pdf)
- [Before-test documentation](Chair%20Before%20Test.pdf)
- [After-test documentation](Chair%20After%20Test.pdf)
