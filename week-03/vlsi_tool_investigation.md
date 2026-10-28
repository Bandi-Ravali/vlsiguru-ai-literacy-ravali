# VLSI Tool Investigation: OpenROAD

## 1. Introduction

Physical Design is an important stage in the digital VLSI design process. It involves implementing a digital circuit physically while considering area, timing, power, and connectivity.

For this investigation, I selected OpenROAD, an open-source electronic design automation (EDA) project that supports digital physical-design implementation.

The purpose of this investigation is to understand what OpenROAD does, identify its major stages, and explore how it can support learning about Physical Design.

## 2. What Is OpenROAD?

OpenROAD is an open-source project for automating aspects of digital chip implementation.

It provides tools that support different physical-design tasks. Its documentation describes the commands, inputs, configuration, and reports associated with the implementation flow.

OpenROAD is useful for learning because it provides access to documentation and open-source implementation workflows.

## 3. Simplified VLSI Design Flow

A simplified digital implementation flow is:

RTL Design → Synthesis → Floorplanning → Placement → Clock Tree Synthesis → Routing → Design Checks

Each stage has a different purpose. Actual implementation flows may include additional stages, checks, and repeated optimization steps.

## 4. Major Physical Design Stages

### 4.1 Floorplanning

Floorplanning establishes the design area and plans the placement of major physical regions.

It helps determine how the design fits within the available chip area.

**Purpose:** Establish the initial physical organization of the design.

### 4.2 Placement

Placement determines where standard cells are positioned within the design area.

Good placement helps manage congestion, wire length, and timing.

**Purpose:** Find suitable physical locations for standard cells.

### 4.3 Clock Tree Synthesis (CTS)

Clock Tree Synthesis builds a clock distribution network to deliver the clock signal to sequential elements.

The clock network must be designed with clock timing and skew in mind.

**Purpose:** Distribute the clock signal while managing clock-related timing requirements.

### 4.4 Timing Optimization

Timing optimization attempts to address timing violations and improve the implementation according to design constraints.

The required changes depend on the design, constraints, and available cells.

**Purpose:** Help the design meet its timing requirements.

### 4.5 Routing

Routing creates the physical metal-wire connections between cells.

Routing must respect the available routing layers and technology design rules.

**Purpose:** Connect the placed cells and implement the required signal paths physically.

### 4.6 Design Checks

Design checks help engineers identify implementation problems, such as connectivity issues or violations of applicable physical rules.

Timing and other reports also help engineers assess whether the implementation meets the required constraints.

**Purpose:** Evaluate the quality and correctness of the implementation.

## 5. Typical Inputs and Outputs

| Stage or Activity | Typical Inputs | Typical Outputs |
|---|---|---|
| Synthesis | RTL, libraries, synthesis constraints | Gate-level netlist and reports |
| Floorplanning | Netlist, technology information, design constraints | Floorplan and physical-design database updates |
| Placement | Netlist, floorplan, placement constraints | Placed-cell locations and reports |
| CTS | Placed design, clock definitions and constraints | Clock-tree implementation and reports |
| Routing | Physical design, connectivity, routing rules | Routed design and routing reports |
| Design checks | Implemented design, constraints, and applicable rules | Reports identifying potential problems |

Exact requirements vary according to the selected flow and stage.

## 6. Why OpenROAD Is Relevant to Physical Design

OpenROAD is relevant to my learning track because it provides an opportunity to study physical-design concepts through open-source documentation and workflows.

I can use the documentation to investigate:

- How placement and routing are performed.
- How clock tree synthesis fits into the flow.
- How design constraints affect implementation.
- How timing and physical-design reports are used.
- How different implementation stages depend on one another.

Studying these topics helps connect theoretical Physical Design concepts with practical EDA workflows.

## 7. Possible AI and Machine Learning Application

One possible research application is predicting routing congestion using historical design data.

For example, a hypothetical machine-learning model could use features such as placement density, estimated wire demand, and design characteristics to predict whether a region may experience congestion.

The predicted result could help engineers identify regions that need further investigation.

This is a proposed application, not a model that I have built or a feature that I have verified as being provided directly by OpenROAD.

Any such model would require suitable data, careful evaluation, and validation against actual design outcomes.

## 8. Investigation Activity

Select and retain only the statement that accurately describes the work completed.

### Option A: Documentation Review

I reviewed the official OpenROAD documentation to understand its purpose and the major stages of the physical-design flow. This investigation helped me connect concepts such as placement, CTS, and routing with an actual open-source EDA project.

### Option B: Example Inspection

I inspected an OpenROAD example or flow configuration to understand how the implementation stages are organised.

**Example inspected:** [Enter the actual example or configuration.]

**What I observed:** [Record what you actually found.]

### Option C: Practical Execution

I attempted to run an OpenROAD flow and examined the results.

**Environment:** [Enter the actual setup.]

**Result:** [Record the actual output, error, or report.]

Do not claim that you ran the tool if you only read its documentation. Delete the options that do not describe your work.

## 9. Limitations and Questions

- A tool's availability does not remove the need to understand the underlying engineering concepts.
- A successful tool run does not automatically mean that every design requirement has been satisfied.
- Results depend on the design inputs, libraries, constraints, and configuration.
- I need further practice to understand the commands and reports used in a real implementation flow.

Questions for further study:

1. How can timing reports help identify critical paths?
2. How does placement influence routing congestion?
3. What checks are needed before considering a physical implementation complete?

## 10. Conclusion

OpenROAD is a useful open-source project for investigating digital physical-design implementation. Studying its documentation helped me understand the roles of floorplanning, placement, CTS, routing, and design checks.

Further hands-on practice would help me understand the commands, reports, and engineering decisions involved in these stages.

## References

- OpenROAD Documentation: https://openroad.readthedocs.io/en/latest/
- OpenROAD Main Documentation: https://openroad.readthedocs.io/en/latest/main/README.html
- OpenROAD Flow Scripts User Guide: https://openroad-flow-scripts.readthedocs.io/en/latest/user/UserGuide.html
