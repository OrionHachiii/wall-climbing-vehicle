# Design and Test Notes

## Design progression

The project began from a course-provided baseline chassis. The final chassis was redesigned to reduce mass, preserve stiffness around the fan opening, improve symmetry, and create more useful mounting locations. The fan shroud was then revised into a continuous circular wall with repeatable tabs and a uniform cross-section.

The final assembly combined the laser-cut chassis, printed shroud, four-wheel drivetrain, RC electronics, separate drive and fan power systems, and a central brushless fan.

## Friction analysis

A ramp test estimated static friction between rubber wheels and a wood surface. The most conservative reported value was approximately 0.60. The coefficient decreased as test mass increased, showing that traction margin becomes more restrictive as the vehicle gains weight.

The report's analytical checkpoint used a 0.357 kg case:

```text
weight = mass × gravity ≈ 0.357 kg × 9.81 m/s² ≈ 3.50 N
required normal force = weight / coefficient of friction
                      ≈ 3.50 N / 0.60
                      ≈ 5.8 N
```

This calculation is an analysis case, not a claim that the final 630 g configuration has the same required adhesion force.

## Thrust evaluation

The report compares the friction-derived requirement with published bench data for a similar motor and propeller. Because the test configuration was not identical to the final hardware, the comparison supports feasibility rather than an exact performance guarantee. Successful full-vehicle operation provided the final functional evidence.

## Assembly iteration

The initial zip-tie motor arrangement allowed slight movement and misalignment. Repositioning and tightening the ties improved drivetrain rigidity for final testing. A purpose-designed bracket remains the preferred next revision.

## Final findings

- The vehicle completed its intended functional demonstration.
- Final mass was 630 g.
- The itemized hardware BOM totals $110.20; reused inventory kept new purchases within the course budget.
- The 25 mm shroud was below the 38 mm target.
- Motor placement near the chassis edge caused tire interference and additional friction.
- Dedicated motor mounts, a taller shroud, better battery retention, and exact-configuration thrust testing are the highest-priority improvements.
