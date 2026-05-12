# Future Standard Operating Procedure Updates List

This document summarizes the proposed or planned methods and procedures that will be advanced in future versions of the Future of Flood Risk Data (FFRD) Standard Operating Procedure (SOP).

------------------------------------------------------------------------

> **Version 1 Schedule: Draft final SOP delivered 31 December 2025, with final delivery in April 2026. This version will be applied to validation basin efforts in calendar year 2026.**
>
> **Version 2 Schedule: Draft delivery planned for 31 December 2026.**

------------------------------------------------------------------------

## Downstream Boundary at Coastal Sites

<u>Version 1</u>: Applies a simplified fixed boundary condition Mean Higher High Water (MHHW) for coastal boundary condition for all stochastic storm transposition (SST) events. *Calibration events use observed tide time series.*

<u>Future Version</u>: Early proposed method form Coastal-Inland Investigation proposes use of Coastal Ocean Reanalysis (CORA) dataset of observed stages to be used in sampling of downstream boundary conditions for SST events.

## Plug-in to Create Manifests for Cloud Compute

<u>Version 1</u>: Relies on Model Linking Register document to plan modeling and for the integration lead to deliver linking information for cloud compute. The compute-manifests control the actual computes, which are owned by the cloud compute lead. Job Aid 13, *Model Delivery for Cloud Compute*, includes some specific nuances for inputs to the compute manifests for the River Analysis System (HEC-RAS) specifically.

<u>Future Version</u>: Will Lehman envisions extracting information from the delivered models to automatically build manifests for cloud compute. Testing of prototypes is underway for HEC-RAS models. This is referred to as “ffrd-manifest-generator”.

## Time Window for Stochastic Storm Transposition Events

<u>Version 1</u>: The model integration lead will guide event time window duration selection, which will be long enough to ensure rainfall in the upper basin has sufficient travel time to so that the downstream boundary of the model reaches a peak. HEC-RAS runs will compute for the full duration for each event.

<u>Future Version</u>: For large basins the time window could be tailored for each HEC-RAS model-unit and each event, and significant savings in compute time could be achieved. This is referred to as “Sliding time windows”.

## River Analysis System Version

<u>Version 1</u>: As of December 2025, the SOP Version 1 calls for use of HEC-RAS version 6.6, which is the current official HEC-RAS release.

<u>Version 2</u>: HEC-RAS 7.0, scheduled for release in winter 2025 through 2026, is anticipated to include notable advancements including enhanced capabilities for assessing model performance using Linux compute engines within a desktop environment, as well as addressing potential concerns regarding numerical reproducibility in parallelized computations. A future SOP update will leverage these new functionalities.

<u>Version 2+</u>: An SOP update to utilize the HEC-RAS planned release currently referred as HEC-RAS 2025 will be considered when core capabilities to support FFRD become available and may be paired with more significant workflow and tool updates. Note that in the interim, Version 1 of the SOP does not specify how users must create two-dimensional (2D) meshes and early HEC-RAS 2025 processes may be utilized.

## River Analysis System Initial Conditions

<u>Version 1</u>: Allow warm-ups time periods if they are helpful and vary reservoir starting elevations.

<u>Future Version</u>: Consider restart files as a similar approach to vary basin conditions at beginning of simulation without utilizing warm-up. Save runtime versus warm-up but also address fact that depression storage starts dry and all channels upstream of baseflow locations are also dry. Also address fact that initial flow in baseflow hydrographs is and inadequate representation of desired initial state for HEC-RAS.

## River Analysis System Parameter Uncertainties

<u>Version 1</u>: A single geometry is calibrated and validated against 6 historic events and applied to the long-term simulations as a single model without uncertainty in model parameters.

<u>Future Version</u>: Consider incorporating uncertainty in parameters such as hydraulic roughness into the long-term simulations to account for additional knowledge uncertainties.

## Source for Starting Reservoir Elevations in River Analysis System for Reservoir Simulation Dams

<u>Version 1</u>: HEC-ResSim period of record (POR) runs are not being leveraged for Initial Pool Elevations in HEC-RAS withing the current cloud-compute toolset.

<u>Future Version</u>: Leverage HEC-ResSim POR for initial pool elevations for event-based sampling.

## Naming Convention Control

<u>Version 1</u>: Although the SOP includes various review steps and checklists to address naming convention issues, there is opportunity for human error. Processes to check for adherence to naming conventions using scripts has the potential to reliably catch issues and ensure consistency across the FFRD program.

<u>Future Version</u>: Standardize and enforce a process to ensure consistency in naming conventions.

## Replication of Historic Events with Integrated Watershed Model Via Cloud Compute

<u>Version 1</u>: Historic Events replicated after integration of watershed model on desktop, early in conformance phase.

<u>Future Version</u>: Add cloud-compute processes to easily preform this task via cloud runs

## Stress Testing of Integrated Watershed Model via Cloud Compute

<u>Version 1</u>: Stress testing of watershed model after integration via desktop, early in conformance phase.

<u>Future Version</u>: Add cloud-compute processes to easily preform this task via cloud runs

## Levee Breach Approach

<u>Version 1</u>: As of July 2025, the team is still attempting to finalize approach for selecting number of breaches per system, ensuring overtopping breaches are accounted for appropriately, and trigger elevations are sampled appropriately.

<u>Future Version</u>: Ensure robust approach backed by reviewed investigations.

## Flood Risk Source Attribution

<u>Version 1</u>: Hazard and consequence summaries are reported at all locations and include all sources of flooding without differentiation of the flood source or driver.

<u>Future Version</u>: Develop additional standard reporting products that differentiate the source of flooding between fluvial, pluvial, dam/levee overtopping, and dam/levee breach.

## Filtering of Events for River Analysis System Compute

<u>Version 1</u>: Filter based on annual maximum series (AMS) contributors (above 1/5 year) from HEC-HMS and HEC-ResSim results and potential breaches based on HEC-HMS/HEC-ResSim results with HEC-RAS ratings and system response results.

<u>Future Version</u>: Incorporate importance sampling/sub-sampling/Gaussian Process Regression methods based on results of on-going investigations.

## Number of Realizations

<u>Version 1</u>: 5realizations for each project.

<u>Future Version</u>: The estimates of uncertainty around variable-frequency relationships may improve with additional realizations. For statistically appropriate confidence intervals, the number of realizations would be determined based on a set of convergence criteria. Future versions of this SOP may consider allowing flexibility to adjust the number of realizations based on statistical criteria and other factors. Alternative computationally efficient algorithms will also be investigated.

## Urban Drainage Networks

<u>Version 1</u>: Overarching guidance to add open channel drainage features within certain areas scoped for additional mesh detail.

<u>Future Version</u>: Incorporate results of urban drainage investigation.

## Consequence Categories to Consider

<u>Version 1</u>: For FFRD base-level runs, the consequences categories are limited to direct structure and content losses. While additional consequences categories exist (such as life loss) and are capable of being computed with the hazard data generated by FFRD, they are not being deployed with the initial effort of FFRD.

<u>Future Version</u>: Consider incorporation of additional consequence categories.

## Consequence Computation Method and Damage Functions

<u>Version 1</u>: Single parameter (depth) damage functions applied to depth-frequency summary results at each structure.

<u>Future Version</u>: Consider multi-parameter damage functions provided by FEMA including those widely accepted within USACE. Also consider event-based damage calculation at each structure, which allows for implementation of multi-parameter damage functions in a defensible way and a more accurate and robust characterization of uncertainty.

## Structure Surveys

<u>Version 1</u>: No tasks associated with defining the uncertainty of the structure inventory are included in the SOP procedures.

<u>Future Version</u>: Consider incorporation of structure uncertainty into consequence computations. This may include leveraging use of existing National Structure Inventory (NSI) survey tool after it is publicly released via complementary efforts outside of FFRD, pending related conversations connected to consequence computations and structure inventory source.

## Refinements to Structure Inventory

<u>Version 1</u>: The SOP includes tasks for manually improving the placement of structures and using the placements to inform improvements to the hydraulic models. No feedback from the manual updates back to the central structure data base is specified.

<u>Future Version</u>: Structure inventory sourcing, structure inventory improvement tasks, consequence computation procedures, and systematic feedback from project refinements to the structure inventories will be considered.

## Dam Data Refinement

<u>Version 1</u>: SOP calls for the National Inventory of Dams (NID) data to be refined prior to FFRD study and is considered separate from the study itself.

<u>Future Version</u>: Develop a workflow to fully incorporate a dam data refinement process into NID data management processes, to remain outside of FFRD SOP procedures.

## Dam Breach Triggers on Reservoir Simulation Dams

<u>Version 1</u>: Trigger elevations for sampled for each event and shared between HEC-ResSim and HEC-RAS. When HEC-ResSim sees a pool above that trigger elevation, it will breach by switching outflows to equal inflows. In the HEC-RAS model during that same event, the pool elevation will track the HEC-ResSim pool and trigger a breach at the same instant and release a larger volume of water through the breach calculated in HEC-RAS. Actual outflow that the HEC-RAS model will see is <u>HEC-ResSim Releases and HEC-RAS computed breaches</u>.

There are a few imperfections in this method:

- HEC-RAS and HEC-ResSim Simulated Pool Hydrographs may not track perfectly due to the timing of inflows. HEC-ResSim received inflows routed via HEC-HMS, while HEC-RAS simulates 2D flow over the mesh using via HEC-HMS excess precipitation and baseflow outputs

  - If pool hydrographs do not track well together, breaches will not trigger at the same time.

- Breaches at an upstream dams may trigger breaches at downstream dams. HEC-ResSim will not be able to account for this fact since the large volume in a reservoir is not actually released after a breach.

- After a breach occurs, HEC-RAS may be releasing too much flow especially if inflows are high at time of breach.

- It is possible HEC-RAS numerical stability issues will occur if HEC-ResSim inflows are forced out of a reservoir that is dry after a breach has released all water.

<u>Future Version</u>: Investigate an approach that allows for a more coupled simulation. No clear alternative has been suggestion to date.

## Software Development Uncertainties

Possible updates that need clarification: HEC-RAS 2025, Storm Hub Storm Typing, SLAM, Structure Survey Tool public deployment, gov cloud only or allow commercial cloud, etc.

## Long Term Storage and Archival of Datasets

<u>Version 1</u>: Listing of event-level outputs and summary-level outputs to be stored are provided in section 11. These include HEC-RAS Hierarchical Data Format (HDF) output files and gridded outputs. No specific guidance regarding subsets of the data to archive indefinitely is provided.

<u>Future Version</u>: Develop a cohesive system to ensure key inputs and outputs from the study can be accessed indefinitely. This may include a system to be able to re-produce a complete set of event-level outputs on a 1-by-1 basis, which would reduce the burden of long-term storage of massive datasets.

## Dataset for Storm Catalog Construction

<u>Version 1</u>: The Analysis Of Record for Calibration (AORC) dataset is specified as the data source for SST storm catalog development in the SOP.

<u>Future Version</u>: The CONUS 404 dataset will be evaluated and considered for use in future versions of the SOP.

## Automation of Hydraulic Model Construction

<u>Version 1:</u> The SOP provides procedures for manual development and calibration of hydraulic models, following the traditional approach.

<u>Future Version</u>: Automated workflows may be considered for direct incorporation into the SOP.

## Automated Transposition Region Delineation

<u>Version 1</u>: Subjective Manual Transposition Region development is allowed, with reference to future methods

<u>Future Version</u>: Resulting accepted procedures from the University of Wisconsin’s Hydroclimate Extremes Research Group for developing automated transposition regions based on extremal statistics of rainfall maxima and the method will become the standard process.

## Storm Arrival Rate/Storm Catalog Threshold

<u>Version 1</u>: The storm catalog is produced using a threshold that provides 10 storms per year of record.

<u>Future Version</u>: It is recognized that the selection of this threshold may influence overall modeling results for frequent events. Future updates to this SOP will consider procedures for selection of threshold to ensure bias is avoided.

## Stochastic Storm Transposition Placements

<u>Version 1</u>: Storms from the catalog are placed randomly for the quasi-continuous realizations. The valid storm placements ensure that the study basin is fully contained in the transposition region. For this version of the SOP all valid locations are equally likely.

<u>Future Version</u>: Future versions of the SOP may be incorporated improved techniques to account for spatial patterns of precipitation within the Transposition Region.

## Data Manifest

<u>Version 1</u>: A data manifest that tracks the source and other metadata associated with all of the datasets for the project is manually created as a table.

<u>Future Version</u>: Automated tracking of metadata for all data associated with the FFRD project using a cloud-bases system will be considered.
