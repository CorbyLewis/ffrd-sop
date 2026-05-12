Future of Flood Risk Data

Standard Operating Procedure

Documentation of Decision Rationale

DRAFT\
Month YYYY

This page is intentionally blank.

Contents

Section 0 – Document Status [1](#document-status)

Section 1 —Future of Flood Risk Data Context and Background [1](#future-of-flood-risk-data-context-and-background)

1.1 Implementation Strategy/Basin Order [1](#implementation-strategybasin-order)

1.2 Modeling Approach [2](#modeling-approach)

1.3 Recurrence Interval [3](#recurrence-interval)

1.4 Collaboration with multiple stakeholders [4](#collaboration-with-multiple-stakeholders)

1.5 Accessibility of Future of Flood Risk Data [5](#accessibility-of-future-of-flood-risk-data)

1.6 Current Condition Risk is Based on Most Recent Data [5](#current-condition-risk-is-based-on-most-recent-data)

1.7 Riverine and Coastal Independence [6](#riverine-and-coastal-independence)

1.8 Accounting for Urban Drainage [7](#accounting-for-urban-drainage)

1.9 Ice Jams [7](#ice-jams)

Section 2 —Basin Project Management and Review [1](#basin-project-management-and-review)

2.1 Sequencing of Production with Approvals Prior to Model start [1](#sequencing-of-production-with-approvals-prior-to-model-start)

2.2 Sequencing of Production with Approvals Prior to Data Collection and Preparation [1](#sequencing-of-production-with-approvals-prior-to-data-collection-and-preparation)

2.3 Program Personnel [2](#program-personnel)

2.4 Key Personnel Qualifications [3](#key-personnel-qualifications)

2.5 Technical Oversight [4](#technical-oversight)

Section 3 —Scoping and Data Preparation [5](#scoping-and-data-preparation)

3.1 Using the Cloud [5](#using-the-cloud)

3.2 Independent Hydrologic Unit Code 4 [5](#independent-hydrologic-unit-code-4)

3.3 Determination For Basin Study Order [6](#determination-for-basin-study-order)

3.4 Determination For Conducting Basin Study [7](#determination-for-conducting-basin-study)

3.5 Definition of Hydraulic Modeling Unit [8](#definition-of-hydraulic-modeling-unit)

3.6 Basins without Sufficient Observed Data [8](#basins-without-sufficient-observed-data)

3.7 Standard Study Unit [9](#standard-study-unit)

3.8 Terrain Selection [10](#terrain-selection)

3.9 Minimum Requirement for Observed Stream and Reservoir Time Series Data [11](#minimum-requirement-for-observed-stream-and-reservoir-time-series-data)

3.10 Minimum Requirement for precipitation and Temperature Data [13](#minimum-requirement-for-precipitation-and-temperature-data)

3.11 Number of calibration and verification events [14](#number-of-calibration-and-verification-events)

3.12 Structure of a Project Delivery Team [15](#structure-of-a-project-delivery-team)

3.13 Stream Centerline Datasets [16](#stream-centerline-datasets)

3.14 Watershed Boundaries [17](#watershed-boundaries)

3.15 Developed Areas [18](#developed-areas)

3.16 Categorization and Selection of Key and Secondary Streams [18](#categorization-and-selection-of-key-and-secondary-streams)

3.17 Selection of Calibration/Validation Time Periods [20](#selection-of-calibrationvalidation-time-periods)

3.18 Categorization and Selection of Model Comparison Locations [21](#categorization-and-selection-of-model-comparison-locations)

3.19 Dam and associated structure Inclusion/Exclusion Criteria [22](#dam-and-associated-structure-inclusionexclusion-criteria)

3.20 Levee System Inclusion/Exclusion Criteria [22](#levee-system-inclusionexclusion-criteria)

3.21 Basin Characteristic Datasets [23](#basin-characteristic-datasets)

3.22 Vertical Datum Selection [24](#vertical-datum-selection)

3.23 Time Zone Selection [24](#time-zone-selection)

3.24 Establishment of Authoritative Observed Data Set [25](#establishment-of-authoritative-observed-data-set)

3.25 Perform Data Collection Prior to Kickoff [25](#perform-data-collection-prior-to-kickoff)

Section 4 —Model Development Standards and Process [27](#model-development-standards-and-process)

4.1 Standard Naming Conventions [27](#standard-naming-conventions)

4.2 Model Metadata [27](#model-metadata)

4.3 Coordinate Reference System for Models [28](#coordinate-reference-system-for-models)

4.4 File Structure for Interim Models [29](#file-structure-for-interim-models)

Section 5 —Meteorologic Data [30](#meteorologic-data)

5.1 Hydrometeorological Methods [30](#hydrometeorological-methods)

5.2 Criteria for event duration [32](#criteria-for-event-duration)

5.3 Events are defined as the presence of precipitation [33](#events-are-defined-as-the-presence-of-precipitation)

5.4 Inclusion of events in the catalog [34](#inclusion-of-events-in-the-catalog)

5.5 Event Catalog Size [35](#event-catalog-size)

5.6 Definition of transposition domain [36](#definition-of-transposition-domain)

5.7 Normalized transposition [37](#normalized-transposition)

Section 6 —Hydrologic Modeling [39](#hydrologic-modeling)

6.1 Hydrologic Modeling Methodology [39](#hydrologic-modeling-methodology)

6.2 Basin Element Delineation [41](#basin-element-delineation)

6.3 Subbasin Discretization Method [42](#subbasin-discretization-method)

6.4 Potential Evapotranspiration Method [43](#potential-evapotranspiration-method)

6.5 Snow Accumulation/Melt Method [45](#snow-accumulationmelt-method)

6.6 Canopy Method [47](#canopy-method)

6.7 Loss Method [48](#loss-method)

6.8 Transform Method [50](#transform-method)

6.9 Baseflow Method [52](#baseflow-method)

6.10 Channel Routing Method [53](#channel-routing-method)

6.11 Reservoir Representation within the Hydrologic Model [55](#reservoir-representation-within-the-hydrologic-model)

6.12 Selection of a Computational Time Step [56](#selection-of-a-computational-time-step)

6.13 Model Calibration and Validation Approach [58](#model-calibration-and-validation-approach)

6.14 Determine State Variables for Use in Stochastic Simulations [58](#determine-state-variables-for-use-in-stochastic-simulations)

6.15 Selection and Definition of Uncertainty Parameters [59](#selection-and-definition-of-uncertainty-parameters)

Section 7 —Reservoir Operations Modeling [61](#reservoir-operations-modeling)

7.1 Reservoir Operations Methodology [61](#reservoir-operations-methodology)

7.2 Reservoir Representation within the Reservoir Model [62](#reservoir-representation-within-the-reservoir-model)

7.3 Boundary Condition Influences across Hydrologic Unit Code Boundaries [62](#boundary-condition-influences-across-hydrologic-unit-code-boundaries)

7.4 Model Calibration and Validation [63](#model-calibration-and-validation)

7.5 Assumptions Associated with Dam Breaching [64](#assumptions-associated-with-dam-breaching)

7.6 Criteria for Inclusion of Dams in Reservoir Model [65](#criteria-for-inclusion-of-dams-in-reservoir-model)

7.7 Initial conditions (HEC-ResSim Lookback window) [65](#initial-conditions-hec-ressim-lookback-window)

7.8 Scripting and Associated Security Vulnerabilities [66](#scripting-and-associated-security-vulnerabilities)

7.9 Breach Modeling Methodology within the Reservoir Model [66](#breach-modeling-methodology-within-the-reservoir-model)

7.10 Determination to Run a Period of Record [67](#determination-to-run-a-period-of-record)

7.11 Simplification of Rule Sets [68](#simplification-of-rule-sets)

7.12 Model Stress Testing [68](#model-stress-testing)

7.13 Elevation, Storage, and Outlet Capacity [69](#elevation-storage-and-outlet-capacity)

7.14 Representing Hydropower [69](#representing-hydropower)

7.15 Selection and Definition of Uncertain operational Parameters [70](#selection-and-definition-of-uncertain-operational-parameters)

Section 8 —Hydraulic Modeling [71](#hydraulic-modeling)

8.1 Hydraulic Modeling Approach [71](#hydraulic-modeling-approach)

8.2 Hydraulic Modeling Platform [72](#hydraulic-modeling-platform)

8.3 Hydraulic Modeling Software Version Selection [73](#hydraulic-modeling-software-version-selection)

8.4 Background Mesh Resolution [73](#background-mesh-resolution)

8.5 Refined Mesh Resolution—Streams [74](#refined-mesh-resolutionstreams)

8.6 Refined Mesh Resolution—Developed Areas [75](#refined-mesh-resolutiondeveloped-areas)

8.7 Hydraulic Model Runtime Constraints [77](#hydraulic-model-runtime-constraints)

8.8 Downstream Boundary condition influences across modeling unit boundaries [78](#downstream-boundary-condition-influences-across-modeling-unit-boundaries)

8.9 Stream Centerline Modification [78](#stream-centerline-modification)

8.10 Initial Conditions for Hydraulic Model [79](#initial-conditions-for-hydraulic-model)

8.11 Terrain Modifications for Buildings [80](#terrain-modifications-for-buildings)

8.12 Terrain Modifications for Streams [81](#terrain-modifications-for-streams)

8.13 Terrain Modifications for Reservoirs [82](#terrain-modifications-for-reservoirs)

8.14 Terrain Modifications for Small Dams—Outlet Works [83](#terrain-modifications-for-small-damsoutlet-works)

8.15 Rendering Mode (Consequences) [84](#rendering-mode-consequences)

8.16 Reservoir Representation within the Hydraulic Model [84](#reservoir-representation-within-the-hydraulic-model)

8.17 Levee Representation within the Hydraulic Model [85](#levee-representation-within-the-hydraulic-model)

8.18 Downstream coastal boundary conditions [86](#downstream-coastal-boundary-conditions)

8.19 Model Calibration and Validation [87](#model-calibration-and-validation-1)

8.20 Other Hydraulic Feature Representation within the Hydraulic Model [87](#other-hydraulic-feature-representation-within-the-hydraulic-model)

8.21 Urban Drainage [88](#urban-drainage)

8.22 Interior Drainage [89](#interior-drainage)

8.23 Terrain Modification—Hydraulic Structures [90](#terrain-modificationhydraulic-structures)

8.24 Defining Downstream Boundary Condition for Non-coastal Hydrologic Unit Code 4 Basins [90](#defining-downstream-boundary-condition-for-non-coastal-hydrologic-unit-code-4-basins)

8.25 Selection and Definition of Uncertainty Parameters [91](#selection-and-definition-of-uncertainty-parameters-1)

8.26 Specification of Manning’s “n” (Overland versus Channel) [92](#specification-of-mannings-n-overland-versus-channel)

8.27 Selection of Equation Set [93](#selection-of-equation-set)

8.28 Computational Tolerances/Model Performance [94](#computational-tolerancesmodel-performance)

Section 9 —Dam and Levee Breaching [95](#dam-and-levee-breaching)

9.1 Residual Risk Mapping [96](#residual-risk-mapping)

9.2 Development of System Response Curves for Dams [97](#development-of-system-response-curves-for-dams)

9.3 Levee Reliability Modeling: Breach Location and Quantity [98](#levee-reliability-modeling-breach-location-and-quantity)

9.4 Data Sources for Levee System Response Curves [99](#data-sources-for-levee-system-response-curves)

9.5 System Response Probability Curve Format [100](#system-response-probability-curve-format)

9.6 Initial Condition Assumptions [102](#initial-condition-assumptions)

9.7 Overtopping Response [103](#overtopping-response)

9.8 Breach Location—Dams [105](#breach-locationdams)

9.9 Breach Location—Levees [106](#breach-locationlevees)

9.10 Breach Trigger Types [106](#breach-trigger-types)

9.11 Breach Parameters—Levees [107](#breach-parameterslevees)

9.12 Breach Parameters—Dams [108](#breach-parametersdams)

9.13 Structures to Breach-Dams [109](#structures-to-breach-dams)

9.14 Structures to Breach-Levees [110](#structures-to-breach-levees)

9.15 Levees to be modeled as Part of the Future of Flood Risk Data Initiative [110](#levees-to-be-modeled-as-part-of-the-future-of-flood-risk-data-initiative)

9.16 Levee Geospatial Data Refinement [111](#levee-geospatial-data-refinement)

Section 10 —Consequences [113](#consequences)

10.1 Structure Geometry Representation [113](#structure-geometry-representation)

10.2 Structure Inventory Source [113](#structure-inventory-source)

10.3 Source of Damage Functions [115](#source-of-damage-functions)

10.4 Damage Function Parameters [115](#damage-function-parameters)

10.5 Input Hazard Data Format for Consequence Computation [116](#input-hazard-data-format-for-consequence-computation)

10.6 Computational Engine [117](#computational-engine)

10.7 Source of Hydraulic Output [118](#source-of-hydraulic-output)

10.8 Calibration and Validation Approach [119](#calibration-and-validation-approach)

Section 11 —Antecedent Conditions for Production Simulations [120](#antecedent-conditions-for-production-simulations)

11.1 Methodology for Generating Antecedent Conditions [120](#methodology-for-generating-antecedent-conditions)

11.2 Coincident Flows from Adjacent Basins [121](#coincident-flows-from-adjacent-basins)

Section 12 —Model Integration [122](#model-integration)

12.1 General Overview [122](#general-overview)

12.2 Integration Configuration By Cloud compute Team [123](#integration-configuration-by-cloud-compute-team)

12.3 Integrated Model Linking by the Hydraulics and Hydrology Modeling Team [124](#integrated-model-linking-by-the-hydraulics-and-hydrology-modeling-team)

12.4 Staffing Model Integration [124](#staffing-model-integration)

12.5 Model Integration Quality Control [125](#model-integration-quality-control)

12.6 Model Preparation for Cloud Compute [126](#model-preparation-for-cloud-compute)

12.7 Calibration and Validation across Frequency Ranges [127](#calibration-and-validation-across-frequency-ranges)

12.8 Calibration and Validation of Events with Linked Modeling System in Cloud Environment [128](#calibration-and-validation-of-events-with-linked-modeling-system-in-cloud-environment)

12.9 Computational Order Defined by the Directed Acyclic Graph [129](#computational-order-defined-by-the-directed-acyclic-graph)

12.10 Sources of Parameter Uncertainty [129](#sources-of-parameter-uncertainty)

Section 13 —Centralized Access to Data [131](#centralized-access-to-data)

13.1 Centralized Access to Final Data [131](#centralized-access-to-final-data)

13.2 Interim Project Collaboration [132](#interim-project-collaboration)

13.3 Staging of Final Models for Cloud Access [133](#staging-of-final-models-for-cloud-access)

Section 14 —Production of Stochastic Simulations [135](#production-of-stochastic-simulations)

14.1 Simulation Statistical Approach [135](#simulation-statistical-approach)

14.2 Stochastic Simulation Structure [136](#stochastic-simulation-structure)

14.3 Number of Realizations [137](#number-of-realizations)

14.4 Number of Synthetic Years per realization [137](#number-of-synthetic-years-per-realization)

14.5 Scaling the Compute [138](#scaling-the-compute)

14.6 Selection and Definition of Uncertain Parameters [139](#selection-and-definition-of-uncertain-parameters)

14.7 Levee and Dam Breach Representation in Stochastic Runs [140](#levee-and-dam-breach-representation-in-stochastic-runs)

14.8 Selection of Hydraulic Events to Run [141](#selection-of-hydraulic-events-to-run)

14.9 Determination of Total Number of Events to Compute [142](#determination-of-total-number-of-events-to-compute)

14.10 Model Changes Required during Production Runs [143](#model-changes-required-during-production-runs)

Section 15 —Results Evaluation [145](#results-evaluation)

15.1 Mapping [145](#mapping)

15.2 Mapped Output Resolution [145](#mapped-output-resolution)

15.3 Gridded Hazard Variables [146](#gridded-hazard-variables)

15.4 Annual Exceedance Probabilities-specific Hazard Grids Frequency [147](#annual-exceedance-probabilities-specific-hazard-grids-frequency)

15.5 Consequences Output [148](#consequences-output)

15.6 Point-based Annual Exceedance Probabilities Estimate of a Hazard [148](#point-based-annual-exceedance-probabilities-estimate-of-a-hazard)

15.7 Separation of Consequences per Source/Contribution [149](#separation-of-consequences-per-sourcecontribution)

15.8 Comparison of Mapping Results to the Federal Emergency Management Agency National Flood Insurance Program Results [150](#comparison-of-mapping-results-to-the-federal-emergency-management-agency-national-flood-insurance-program-results)

References [151](#references)

List of Acronyms and Abbreviations [152](#list-of-acronyms-and-abbreviations)

#  – Document Status

**December 2025 – Status of this document. The content document was primarily developed in August of 2024 and was paired with an earlier draft version of the FFRD SOP. In certain areas it became out-of-sync with the December 2025 draft version 1 of the SOP but largely documents much of the rationale behind the core procedures. The need for a robust methodology decision rationale document was emphasized during reviews of the SOP conducted in September-October 2025 and plans are in place to fully update the “Volume III – Methodology Rationale” as a core delivery that serves as a foundation for the procedures, workflows and software recommended in “Volume II - Technical Standards and Procedures”.**

# —Future of Flood Risk Data Context and Background

The Federal Emergency Management Agency’s (FEMA’s) Future of Flood Risk Data (FFRD) initiative seeks to shift from a binary approach to a graduated approach for flood risk and flood hazard for the nation. The U.S. Army Corps of Engineers (USACE) is developing a proposed methodology for FEMA to produce graduated hazard and risk. Many of the requirements for the basic methodology are defined in the standard operating procedure (SOP) developed for this initiative and in the methodology concept recommendation paper, Determining the Path: A look into Modeling Methodology (2020), produced by USACE.

This section covers the background decisions present in the methodology recommendation and the SOP.

## Implementation Strategy/Basin Order

The FFRD methodology describes the implementation of a single hydrologic unit code (HUC) 4 watershed. During national implementation, basins must be prioritized in some way.

### Options available

- Exposure value

- Stream miles

- Hydrologic order.

### Selection and rationale

The FFRD project delivery team (PDT) recommends hydrologic order allowing harvesting of results for lower hydrologic order basins. This may not be critical, but it is the current recommendation.

### Rationale for why the other options were not selected

This topic was evaluated as part of projecting future production costs and timelines. Currently the SOP does not require the basin order and this decision has not been finalized.

## Modeling Approach

For FFRD, the overall modeling approach must meet the requirements specified in the Biggert-Waters Flood Insurance Reform Act of 2012 (BW-12) and described by FEMA.

- Describe graduated flood hazard and risk from the 5- to the 2,000-year event

- Describe graduated flood risk everywhere including areas of potential future development

- Describe flood risk, including potential, for levee and dam breaches.

### Options available

- Metamodeling

- Simulating discrete events and assigning annual exceedance probabilities (AEPs) to the output

- Stochastic simulations using stochastic storm transposition (SST) and Model Suite with full-basin coverage

- Procure third party data

<!-- -->

- Fathom

- KatRisk.

### Selection and rationale

Participants in the inaugural steering committee meeting (Washington DC, May 2022) decided to investigate the costs and limitations of a methodology that includes stochastic simulations over a suite of full-basin models through pilot projects. The team discussed the large computational burden that may be associated with this approach. Trade-offs between modeling effort in un-populated areas versus populated areas were discussed. FEMA’s statuary requirement to provide flood information for all areas and desire to develop detailed hazard and consequence information that recognizes parameters such as velocity and duration were key considerations and discussion points. The decision included the team writing a draft SOP using this approach—adapting it based on lessons learned from each pilot study—and attempting to balance these considerations.

### Rationale for why the other options were not selected

Options not selected did not supply the necessary outputs to meet the requirements of BW-12.

The discussion into using metamodeling determined sufficient training data does not yet exist to properly train basin-wide metamodels for graduated hazard and risk products.

The FFRD team decided to remove the assumptions of AEP neutrality. Computing discrete AEP events and assigning AEPs to the output reinforces assumptions of AEP neutrality.

Procuring third party data was not accepted because the FFRD data should be the authoritative federal standard by which third party data is compared.

## Recurrence Interval

The FEMA FFRD requirements document (USACE 2022) directed the FFRD PDT to use 1/5 AEP to 1/2,000 AEP.

### Options available

- The 2,000-year event and everything more frequent

- The range of interest=1/2 AEP to 1/2,000 AEP

- The range of interest=1/5 AEP to 1/2,000 AEP.

### Selection and rationale

Requirements direct the use of 1/5 AEP to 1/2,000 AEP.

The Kanawha River Basin Pilot ran all events lower than the 2,000-year event to have data to compare to the computation of only statistics above the 2- or 5-year events. There is concern regarding the manipulation of the statistics if all events are not run.

### Rationale for why the other options were not selected

According to FEMA actuaries, recurrence intervals over 1/2,000 do not have statistical effect so their use was not considered viable.

Running for all events more frequent than the 2,000-year event increases the computational burden. The alternative of running everything between the 2-year and the 2,000-year events reduces computational burden (roughly by half).

## Collaboration with multiple stakeholders

Coordination with local and regional stakeholders is a key aspect of a large-scale flood modeling effort. Federal, state, and local partners, as well as individuals have a stake in the modeling efforts. In general, the modeling goal is to provide the highest quality flood risk data possible to all stakeholders such that management decisions may be informed directly using reliable flood risk data.

### Options available

- Build FFRD models using technically-focused PDT

- Engage stakeholders in data collection efforts and with in-progress briefings by the PDT

- Require approval for models by local stakeholders before finalizing products.

### Selection and rationale

The SOP provides guidance for FFRD PDTs on how to engage stakeholders throughout the modeling process ensuring the PDT is responsive to the needs of the local interests and has an open line of communication. This coordination assists in obtaining the best available input data and existing models and in recognizing other local needs. This coordination also aims to achieve some level of local buy-in of model results.

### Rationale for why the other options were not selected

To produce high quality flood risk data, models must be produced based on the best available science and input data and should not be overly influenced by local political contexts.

PDT members must collaborate with stakeholders ensuring key local data is utilized and the results achieve local “buy-in”.

## Accessibility of Future of Flood Risk Data

Two of the stated key objectives of the FFRD initiative are to modernize data management and delivery and to empower private and State, Local, Tribal, and Territorial (SLTT) stakeholders. Allowing some level of access to FFRD results, reports, and underlying models is key to meeting these objectives.

### Options available

- No centralized storage of FFRD models

- Centralized storage of FFRD final models using existing systems, such as network storage within a federal agency

- Centralized storage of FFRD models on S3 cloud buckets with a Model Library interface using role-based access.

### Selection and rationale

The FFRD SOP leverages the Model Library and Gov-cloud S3 buckets for centralized storage. This system allows for data sharing throughout the model development process, provides for storage and archiving of final models and model results. This system can allow access to models and results to all stakeholders while meeting data security requirements.

### Rationale for why the other options were not selected

A lack of centralized storage would result in future difficulties in finding and utilizing FFRD models. It also would not leverage efficiencies associated with modern technology.

Using existing central storage systems within a single agency presents difficulties in managing access to the data across agencies, as well as outside of the agency.

## Current Condition Risk is Based on Most Recent Data

FFRD studies will develop current condition risk based on data available at the start of the project. For a nationally consistent program, which may take many years to complete, dealing with inconsistent periods of analysis must be addressed. As of August 2024, nothing is being changed for future conditions.

### Options available

- Use data for current conditions based on data from a fixed date (e.g., 2025); do not gather data past that if a basin is started in 2027

- Always grab data available to the start of the year, e.g., gather 2026 data when starting a 2027 watershed

- If a storm happens during the development of the watershed, and it is considered critical by the PDT, it may be included in the analysis.

### Selection and rationale

Always grab best and most complete data (e.g., gather 2026 data if it is available when kicking off a 2027 study). If data comes online during the project development; it does not need to be included in the project.

### Rationale for why the other options were not selected

If data is available, it should be included in the project if it does not delay the project.

## Riverine and Coastal Independence

Coastal and inland are currently being kept separate to minimize the possibility of double counting flood risk.

### Options available

- Develop riverine and coastal FFRD models and products independently and maintain separate results datasets that may overlap in some areas

- Synchronize all input parameters and approaches such that an identical model system is used for both riverine and coastal FFRD studies.

- Coordinate between riverine and coastal FFRD teams. Ensure collaboration and find methods for data sharing and develop guidance for sharing FFRD data in overlapping areas.

### Selection and rationale

The riverine and coastal teams, while working autonomously, must coordinate and seek commonality in approaches and consistency in output data.

### Rationale for why the other options were not selected

Consistent approaches and outputs are needed to effectively communicate flood risk to the stakeholders.

## Accounting for Urban Drainage

The FFRD initiative is tasked with directly assessing pluvial flooding, and the most critical pluvial flooding locations within the United States are overlayed with communities relying on urban drainage infrastructure to reduce flood occurrence.

### Options available

- Allow drainage to occur based only on flow-paths appearing on bare-earth digital elevation models (DEMs)

- Require explicit modeling of surface water drainage systems and ditches, which may require DEM modifications and two-dimensional (2D) mesh refinements to allow drainage

- Seek a solution to account for urban drainage with a simplistic method such as translating a threshold rainfall intensity directly to outfall or adjusting outputs with a method outside of the hydraulic model

- Seek a solution to explicitly model urban storm drain networks including underground pipes and storm-sewer inlets, which would include a data-collection of the drainage network.

### Selection and rationale

The first three pilots are using the draft SOP, which calls for adding an increased level of River Analysis System (HEC-RAS) modeling detail in developed areas having a structure density above a set threshold. The level of detail of modeling in those areas is left to professional judgement of the modeler, but modeling of the urban drainage network is generally limited to surface drainage features.

As of September 2024, the FFRD SOP calls for accounting for all major surface water drainage (ditches, canals, etc.) for developed areas directly in the HEC-RAS model. The software being applied has limited tools available to model subsurface drainage and input data required for urban drainage networks is sparse. It is a recognized weakness in the modeling approach that surface flooding in developed areas may be over-estimated due to lack of urban drainage modeling, and solutions will be sought in future.

### Rationale for why the other options were not selected

This selected option is the most expedient solution in the short term.

## Ice Jams

Ice jams can cause elevated stages and result in consequences creating risk in some areas of the United States. The FFRD SOP must address ice jambs.

### Options available

- Do nothing

- Account for ice jams in FFRD modeling.

### Selection and rationale

As of August 2024, there is no plan for dealing with ice jams.

### Rationale for why the other options were not selected

Although ice jams are an important aspect of flooding for some areas of the country, the issue has not risen to a critical level for the initial pilot projects, and, therefore, has yet to be addressed.

# —Basin Project Management and Review

## Sequencing of Production with Approvals Prior to Model start

There is a need to ensure data collection is complete prior to kicking off a basin study.

### Options available

- Role of person to review data collection (review lead)

- National Review Board

### Selection and rationale

The review lead reviews pre-model data collection and the data collection reporting to ensure projects are fully ready to scope. The review lead is a highly technical team member who understands all portions of the FFRD Basin Modeling. This review occurs as finalization of a review of the data collection and preparation efforts.

### Rationale for why the other options were not selected

A National Review Board was not selected as this senior oversight group (SOG) will be reviewing each of the basins at a minimum of three checkpoints. This team, comprised of national-level subject matter experts (SMEs) provides technical advice, oversight, and project review at a programmatic level. A detailed review was considered excessive workload given other time constraints expected with a National Level Subject Matter Expert.

## Sequencing of Production with Approvals Prior to Data Collection and Preparation

There is a need to ensure data is available prior to kicking off a basin data collection and preparation process.

### Options available

- FEMA representative

- Role of person to review data collection (review lead)

- National Review Board (SOG)

- Other?

### Selection and rationale

Rationale to support options.

### Rationale for why the other options were not selected

Rationale not to support options

## Program Personnel

Certain Key Members are needed within a project delivery team, and at a programmatic level.

### Options available

- Within a Team:

<!-- -->

- Technical Team Lead

- Project Manager

- Data Preparation Team Lead

- Geospatial Lead

- Data Collector and Preparers

- Levee Data Team Member

- Dam Data Team Member

- Hydrologic, Hydraulic, and Reservoir Operations Modelers

- Meteorologist/SST Specialist

- Validation and Production Lead

- Validation and Projection Team Members

- Consequence Specialist

- Documentation Lead

- Cloud Compute Team Member.

<!-- -->

- Programmatic Level:

<!-- -->

- Program Manager

- Review Lead

- Reviewers

- FEMA HQ/Regional Representative (Contracting Representative)

- Clout Environment Support

- Expert Model/Software Support Lead

- Software Maintenance Leads

- Documentation and SOP Lead

- Key Stakeholders

- Senior Oversight Group

- Steering/Advisory Committee.

### Selection and rationale

All Team Members listed above are considered needed, unless specific item to be modeled is not located within a basin (i.e. no levees, major dams). Multiple roles within the FFRD Team structure may be filled by the same individual as long as the individual meets the minimum requirements for all roles and possesses the time required to adequately meet the mission. A wide range of roles and skillsets are needed to address flood risk in systematic manner as prescribed within the SOP. Roles outside of the Project Delivery Team are needed to ensure projects with minimal errors that are as nationally consistent as reasonable.

### Rationale for why the other options were not selected

Rationale not to support options

## Key Personnel Qualifications

There is a need to specify minimum qualifications of Key Personnel within the team to ensure quality standards. These include Team Leads, Review Lead, Reviewers, Dam and Levee Team Members, SOG and Steering Committee Members, and Validation and Production Team Members.

### Options available

- Minimum Previous Review Efforts

- Minimum Previous Modeling Efforts

- Minimum Previous Leadership Roles

- Years Employed in Field

- Access to Data needed to complete task

- Agency/PTS Nomination

- Status as Subject Matter Expert.

### Selection and rationale

A variety of options would be utilized to ensure ability to adequately fulfill role. Each role would have different need. E.g. Team Lead would need experience in modeling and possess understanding of many roles within a team. A Senior Oversight Group Member would need to be a Subject Matter Expert in their given field, and need to be nominated by their respective agency/PTS group.

### Rationale for why the other options were not selected

Rationale not to support options

## Technical Oversight

An oversight group is required to ensure national consistency of technical products. Provides strategic alignment, transparency, and accountability.

### Options available

- Have no national-level oversight

- FEMA HQ key personnel staff a review board

- FEMA regions staff a review board

- Senior technical staff from various technical entities (e.g., FEMA regions/PTS/USACE, other government agencies, etc.)

### Selection and rationale

A chartered group of senior technical staff from various technical entities and organizations provide the widest variety of expertise, experience, and decision-making authority as compared to other options. Having a multi-agency group improves federal family buy in and defensibility of the national flood risk product.

### Rationale for why the other options were not selected

Having no oversight can lead to inconsistency across the national program. Limiting personnel to one organization limits the opportunity to leverage the experience, technical competencies, and skills of a multiple-agency oversight group as well as diverse perspectives.

# —Scoping and Data Preparation

This section discusses items related to project and program planning, geospatial standards, and data collection prior to basin kickoff. These items are considered necessary for clean and consistent modeling efforts at a national level. All items listed below are applicable to basins within the contiguous United States. Additional definition of standards is needed prior to modeling basins outside of this region.

## Using the Cloud

During the initial FFRD methodology planning meeting, the PDT discussed various methods for computing national-scale consistent results of sufficient quality. During the meeting, there were suspicions that the cost of cloud computing and the tools to support it were not available. The group decided it was worth attempting to use the cloud and designing for that to determine costs and capabilities. Now that the PDT has estimates of costs and knows where costs can be reduced or quality needs to be increased, the information needs to be reviewed again to refine direction on the approach.

### Options available

- Use the cloud

- Build on premises server farms

- Simplify the approaches to not need the cloud

- Use high-performance computing (HPC).

### Selection and rationale

For the pilot projects the cloud was leveraged, and cost structures were determined. Information regarding costs and scalability of the SOP is still being collected.

### Rationale for why the other options were not selected

During steering committee discussions, the suggestion was to explore the scale of the cloud and its costs. If that became unacceptably difficult or too costly, the team would need to reevaluate approaches.

## Independent Hydrologic Unit Code 4

HUC-4 scale watersheds are not perfectly independent. Storm events can cross boundaries causing flooding and damages in adjacent watersheds. However, the procedure for estimating flood damages at all scales within a watershed, SST, detects storms causing significant flooding. The upper limit of this process is related to the meteorology. The typical size of a HUC-4 is bigger than the typical extents of significant 72-hour rainfall accumulation. Most large storm analyses, such as those in the National Oceanic and Atmospheric Administration (NOAA) Hydrometeorological Reports for Probable Maximum Precipitation (PMP), stop at around 10,000 square miles in spatial extent.

One driving force behind the need for FFRD related to this question is the ability to compute aggregate averaged annualized loss (AAL) and occurrence exceedance probability (OEP) across the nation. Aggregate AAL is important for the actuary team in rate setting. The discussion within the Actuary and Casualty Modeling (ACM) team centered around the influence of large storms crossing multiple HUC-4 boundaries and their influence on the overall damage frequency relationship. To ensure ACM needs are met, after creation of more HUC-4 AAL estimates, further experimentation needs completion. ACM suggests OEP is necessary for reinsurance, and, while it would be a useful FFRD deliverable, it is not a requirement at this time.

### Options available

- Assume correlation between HUC-4s

- Assume independence between HUC-4s.

### Selection and rationale

During the pilots, the HUC-4s are assumed to be independent. This is an assumption that is reasonable, and sufficient for piloting the process.

### Rationale for why the other options were not selected

Assuming correlation between HUC4s helps with assigning OEP estimates. However, FFRD is not initially required to support reinsurance. If OEP estimates are necessary, processes to determine correlation, or build national scale catalogs of storms (tracking them across HUC-4s) are necessary.

## Determination For Basin Study Order

One lead entity is responsible for final decisions regarding the overall strategy in terms of the order of basin to be modeled, and which specific basins are modeled each year.

### Options available

- FEMA Headquarters

- FEMA Regions

- Production and Technical Services (PTS) and Cooperating Technical Partners (CTP)

- Other local interests

- USACE

### Selection and rationale

All parties listed could work together to finalize basin order recommendations and verify minimum data requirements, but a single party (FEMA) would be the final decision maker for model order.

### Rationale for why the other options were not selected

FEMA Headquarters is the FFRD lead agency and a single decision maker is needed for clarity and consistency.

## Determination For Conducting Basin Study

Basin selection can be determined from a variety of factors, but sufficient investigation to verify minimum data available will be conducted prior to this selection (see Section 2.6, Basins without Sufficient Observed Data).

### Options available

- Local or national interest

- Population or other demographics

- Risk factor

- Regional capability

- Infrastructure risk

- Hydrologic order

- Data availability

- Other miscellaneous factors.

### Selection and rationale

Basin selection could incorporate a variety of factors including, but not limited to, local interest, hydrologic order, data availability, and population and infrastructure risks. However, investigation to verify minimum data requirements in the program planning phase prior to a basin being assigned to a modeling entity would be required. This is required to limit basin delays and rework in the modeling process. Any part could work together to finalize basin order recommendations and verify minimum data requirements, with FEMA acting as the final decisionmaker for model order.

### Rationale for why the other options were not selected

All options may be included for selection of which basins to model.

## Definition of Hydraulic Modeling Unit

An FFRD study basin uses the HUC-4 basin boundaries to define the hydraulic modeling unit. These boundaries generally encompass several hundred square miles of runoff area. To develop HEC-RAS modeling with a sufficient level of detail to support the FFRD objective, basins are subdivided into separate modeling regions designated as modeling units. Modeling units for FFRD study basins must be sufficiently large to support the assumptions of independence but small enough to compute results quickly when utilizing a reasonable model resolution. The modeling unit should also support modeling of levees and reservoirs.

### Options available

- Strictly use HUC-8 basins

- Develop modeling units using criteria such as reservoir operations and levee systems.

### Selection and rationale

The SOP authors and modelers decided to break up the watershed into logical units using reservoir operations, general area-based targets, and levee systems to guide the hydraulic modeling domains. This allowed for cleaner handoffs between hydraulic models, enabled better treatment of water behind levees, and satisfied the area needs for smaller faster hydraulic models.

### Rationale for why the other options were not selected

Strictly using the HUC-8 boundaries resulted in modeling areas that did not fully respect the hydraulic impact of levees and dams.

## Basins without Sufficient Observed Data

Within the SOP, it is a requirement to compare simulated results to observed data. A determination on what constitutes sufficient observed data should be defined prior to basin selection in the program planning. Observed data refers to, but is not limited to, gage data for flow, stage, and precipitation, it could also include bathymetry, terrain data, or other data representing the watershed and needed for the SOP.

### Options available

- Do not model if data is insufficient.

- Collect data when data is insufficient/delay modeling.

- Develop models with best available data and identify what data gaps exist in the report.

### Selection and rationale

Various options likely to be selected over the course of national implementation.

Where large data gaps exist across multiple datasets, a delay for pursuing data collection opportunities is recommended. Determination on amount of missing data needed to trigger a delay has not yet been determined. Typical basins with limited data will be outside of the contiguous United States or located in very arid climates. These basins are expected to be modeled at the later stages of national implementation.

For basins with limited data fully outside of the borders of the United States that contribute flow to HUCs within the United States, it is recommended these basins not be modeled.

Many basins may use best available data and identify all remaining data gaps. For the Duwamish River Basin study, there were no NOAA Atlas 14 data products to validate the precipitation frequency and volume calculations, the team validated those outputs to precipitation gages and to NOAA Atlas 2. The report identified that the NOAA A14 products were not available and used reasonable best available data to act as surrogates.

### Rationale for why the other options were not selected

No pilot studies were selected where observed data was insufficient enough to justify exclusion from modeling.

## Standard Study Unit

The FFRD initiative develops graduated flood hazard and flood risk products across the nation. The development of these products will take multiple years. A general strategy for how products is developed across the nation relies on defining how large of a watershed each project encompasses.

### Options available

- Model the entire United States all at once.

- Model based on political boundaries (e.g., states or regions or districts).

- Model based on a well-established hydrologic boundary.

### Selection and rationale

Execute at the HUC-4 watershed level using the watershed boundary dataset (WBD) as the standard study unit.

The desire for FFRD to be at the HUC-4 scale was based on topics discussed in Section 2.2 regarding the independence of HUC-4s and the ability to model as large of an area as possible to improve the correlation of loss within the largest geographic domain that can be modeled while preserving the statistical significance with SST. Additionally, leveraging a consistent, well-established WBD to drive the generation and sequencing of the project is a positive of this approach.

### Rationale for why the other options were not selected

Developing products across the entire United States all at once could lead to no opportunity to revise and adapt to practical problems arising during production. By executing many (250) HUC-4s across the project lifecycle (10 years), each year provides an opportunity to learn and adapt as the delivery progresses.

Modeling based on political boundaries instead of a hydrologic boundary causes significant issues where the political boundary and the hydrologic boundary do not coincide. To limit the potential for discontinuity at political boundaries, the products are being developed on logical hydrologic boundaries.

## Terrain Selection

One of the most fundamental and important data sources is the elevation data in the form of a DEM. Ideally, FFRD projects build upon a DEM based on light detection and ranging (LiDAR) data of Topographic Data Quality Level 2 (QL2) or better. The SOP calls for establishment of a full basin DEM using the highest quality and resolution available, and, additionally, the delivery of down-sampled versions of this DEM for other uses (i.e., Hydrologic Modeling System \[HEC-HMS\] modeling, depth grid generation). Terrains are used to inform many processes in the watershed such as rainfall runoff, river hydraulics, and output mapping.

### Options available

- Define a minimum standard for all processes using terrains (i.e., United States Geological Survey \[USGS\] 3D Elevation Program \[3DEP\] 10-meter resolution)

- Force all processes to be developed at the same resolution

- Provide a minimum standard for all processes and allow processes to be developed at different resolutions.

- Have no standard.

### Selection and rationale

Nationwide FFRD watershed studies should consider the availability of high-quality elevation data starting with USGS 3DEP 1/3 ARC-second (i.e., 10-meter) terrain sources as a minimum standard, if higher quality local data is available it can be utilized. If 3DEP data is not available, procurements of QL2 data may be justifiable in the pre-model data collection phase. The approach must be coordinated with FEMA FFRD leadership to determine if procurement is necessary.

There are hydraulic features in the floodplain only captured with high-resolution DEMs, so high-resolution data is required. Currently, the mapping resolution for the hydraulic mesh development was used for mapping output in the pilots, it is recommended that in future basins the mapping product be at a resolution that is not as fine as the resolution of the terrain used in developing the hydraulic mesh.

### Rationale for why the other options were not selected

Having no minimum standard is a risk if no terrain is available. However, the nation is covered in 10-meter USGS 3DEP data, so the current supplied minimum excludes no basins. The SOP states to use the “best available” terrain, but having a specified minimum reduces the risk that people may choose a “better quality” but lower resolution dataset.

Allowing mesh development and mapping to operate on different resolutions of terrain is a good idea, but the team has not investigated the impact of this on the quality of maps yet. It should be planned to evaluate lower resolution mapping output to reduce computational time, better align with use cases, and reduce data storage overall.

## Minimum Requirement for Observed Stream and Reservoir Time Series Data

The FFRD SOP does not quantify what sufficient or adequate gage data means. However, observed stream and reservoir time series data must be able to serve multiple uses:

- Serve as boundary conditions/initial state variables, when required

- Ascertain model performance (i.e., compare against computed results) at all critical locations.

Ample justification showing a lack of acceptable observed time series data must be provided by a federal entity (i.e., FEMA) in order to stop/not study a watershed. Basins should not be selected for production if the tasking entity deems there is not sufficient data to allow successful completion.

### Options available

The following observed time series data collection options were considered:

- Do not collect any observed time series data

- Only collect observed data from the USGS National Water Information System (NWIS) database

- Only collect observed data from USACE Corps Water Management System (CWMS) databases

- Collect observed data from all available federal, local, and state agency databases at all critical locations.

### Selection and rationale

Collecting observed data from all available federal, local, and state agency databases at all critical locations satisfies the above criteria and was chosen for use in FFRD applications. At each critical gage and reservoir location, the following types of observed streamflow and stage time series data must be collected:

- Instantaneous peaks (e.g., annual maximum series)

- Daily average

- 15-, 30-, and/or 60-minute values.

A process for filling in missing time series data is not defined within the SOP due to the high level of subjectivity. Engineering judgement should be used. As of September 2024, this decision is being investigated within the pilot studies.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for observed stream and reservoir time series data and are not considered acceptable for use in FFRD applications:

- Do not collect any observed time series data

- Collect observed data from only the USGS NWIS database

- Collect observed data from only USACE CWMS databases.

Each of the above options do not guarantee the availability of required data to define boundary conditions/initial state variables or to ascertain model performance.

## Minimum Requirement for precipitation and Temperature Data

Performance of period of record (POR) analysis, calibration to historic events, and SST, requires a nationally-consistent, fine, temporal, high-resolution temperature, and precipitation data set.

### Options available

There are numerous precipitation data sources available for use within hydrologic and hydraulic modeling applications:

- National Weather Service (NWS) Cooperative Observer Program (COOP) gage observations

- Multi-Radar Multi-Sensor Quantitative Precipitation Estimate (MRMS QPE)

- Real-time Mesoscale Analysis (RTMA)

- Parameter-elevation Regressions on Independent Slopes Model (PRISM)

- Next-generation Radar Quantitative Precipitation Estimate (NEXRAD QPE)

- NOAA National Centers for Environmental Prediction (NCEP) Stage IV Data

- Analysis of Period of Record for Calibration (AORC)

- Livneh CONUS Near-Surface Gridded Meteorological and Derived Hydrometeorological Data (Livneh).

### Selection and rationale

The selected data source needs to:

- Provide uniformly-derived gridded precipitation and temperature

- Have a relatively small spatial resolution

- Have a relatively fine temporal resolution (daily is too long)

- Have a relatively long POR (more than 30 years is preferential)

- Cover the entire continental United States

- Receive updates to include additional data.

AORC satisfies these criteria.

AORC is a high-resolution multi-sensor precipitation product available for a long period of record across the United States used in the calibration of the National Water Model. For development of storm catalogs for SST and modeling historical events in hydrology models, AORC is an appropriate data choice. The same boundary condition data should be used in the calibration process as in the SST production run process to ensure the hydrologic responses based on that forcing data are reasonable. Separate analysis is performed to identify alternative sources and resolutions of precipitation in coordination with NOAA. AORC is a reasonable first choice, but other datasets and resolutions are being evaluated, if findings identify other data sources or resolutions improve consistency, accuracy, and performance of FFRD, they will be integrated into the SOP.

### Rationale for why the other options were not selected

- NWS COOP gage observations

<!-- -->

- Data source is not gridded

<!-- -->

- MRMS QPE

<!-- -->

- No corresponding temperature data source

- POR is too short

<!-- -->

- RTMA

<!-- -->

- POR is too short

<!-- -->

- PRISM

<!-- -->

- Temporal resolution is too coarse

<!-- -->

- NEXRAD QPE

<!-- -->

- No corresponding temperature data source

- POR is too short

<!-- -->

- NCEP Stage IV

<!-- -->

- No corresponding temperature data source

- POR is too short

<!-- -->

- Livneh

<!-- -->

- Temporal resolution is too coarse.

## Number of calibration and verification events

The SOP describes the process of building models representing rainfall runoff, reservoir operations, hydraulics, and consequences. These models are designed to represent the current watershed conditions at the time of development. To ascertain the quality of the models they should be compared to historic events. There are two basic concerns, one is fitting a model to local conditions, the other is over fitting a model to local conditions. A process must be defined for how to develop a model that properly represents the local conditions and can be used for events beyond the training data.

### Options available

- Do nothing

- Calibrate only and do no verification

- How many events to calibrate

- Calibrate and verify

- How many events to calibrate

- How many events to verify.

### Selection and rationale

The SOP calls for calibration and verification. Calibration is the process of training a model on historic data, verification is testing that model on observed data to determine goodness of fit for conditions outside of the training dataset. The SOP calls for four calibration and two verification events. The objective is to develop a model that can be computed across a wide range of conditions, while not spending too much time and effort on calibration. Another concern is to not over calibrate the model to fit it too strongly to one condition.

### Rationale for why the other options were not selected

Doing nothing for calibration and verification is not standard practice and is unacceptable.

Calibrating with no verification creates opportunity for overfitting the models.

Calibrating for too many events risks overfitting and is high in cost.

## Structure of a Project Delivery Team

The delivery of FFRD projects requires a large team to execute planning, management, modeling, data management, cloud computing, reviewing, and communication tasks. Guidelines on team structure to accomplish the goals.

### Options available

- SOP does not regulate team composition

- SOP provides flexible and adaptable general guidelines on team structure

- SOP provides detailed structure for team composition, including workflows and responsibilities of each member

### Selection and rationale

The SOP currently provides flexible and adaptable general guidelines. The ideas behind how to execute the program for the United States after the SOP is finalized are not fully matured.

### Rationale for why the other options were not selected

As of Fall 2024, the plans for executing the FFRD program for the United States are not mature, so any detailed structure of team composition would be subject to change. However, there is value in providing some basic guidelines in the current SOP to allow planning for the program.

## Stream Centerline Datasets

There is value in establishing an accurate and consistent set of stream centerlines to be used for aspects of model production. It is also important that stream centerlines match the underlying DEM used for the models. These centerlines are used for routing reaches in HEC-HMS and Reservoir System Simulation (HEC-ResSim) models and used for 2D mesh alignment and terrain modification alignment in HEC-RAS.

The National Hydrology Dataset Plus (NHDPlus) is a readily available attributed stream centerline layer that can be used for model development. Processes and procedures to create an elevation derived hydrography (EDH) following the USGS 3DHP specification for each FFRD basin are being considered. If this can be achieved, the SOP will be updated to use this process.

Based on modeling performed in the Kanawha River Basin Study pilot, NHDPlus streamlines do not always align well with high-resolution LiDAR-based DEM. Some FEMA PTS contractors developed similar data sets that align better with the DEM. Data development techniques are still being evaluated. The benefits of this data set will continue to be evaluated in future pilot studies. USGS is currently updating the hydrography data set for the nation under the 3DHP program and there may be some way for FEMA FFRD models to align with the USGS progress.

### Options available

- National Hydrology Dataset plus stream centerlines

- EDH

- Do nothing.

### Selection and rationale

The SOP calls for creating and using EDH as the primary stream centerline data source for inputs into the models. This will allow for the highest quality data source to be applied to the model.

### Rationale for why the other options were not selected

Allowing each modeler to develop their own stream centerlines would result in inconsistent quality across basins. Although the NHD dataset exists everywhere in the United States, it will commonly be a poor match with the high resolution DEMs that will be consolidated separately for FFRD projects.

## Watershed Boundaries

The watershed boundaries define not only the extent of the FFRD study, but the boundaries that are internal to the suite of models. HEC-HMS modeling includes a defined break-out of subbasins and HEC-RAS modeling will be broken out into separate units for modeling.

### Options available

- Do nothing; each team member develops boundaries needed for their effort as needed

- Use strictly the existing USGS national WBD

- Develop FFRD project boundaries as part of the planning and data preparation phase of the project.

### Selection and rationale

The SOP calls for development of FFRD project boundaries as part of the planning and data preparation phase of the project. This ensures all boundaries are clear and defined, without any overlap or gaps when the larger modeling teams get engaged.

### Rationale for why the other options were not selected

If boundary definition is left to each modeler, coordination across models and basins will be challenging, causing inefficiencies and possible mistakes.

The WBD is of a lower resolution or quality than what is needed and will commonly not align precisely with the DEM used for the project. The WBD is an excellent tool for planning of the project, but more detail is needed for execution of modeling.

## Developed Areas

FFRD objectives included characterizing pluvial and fluvial risk in developed areas within a modeling unit. These areas of interest must be identified as areas where a refined mesh is needed within the hydraulic model.

### Options available

- Identify developed areas where characterizing flood risk is a priority within the basin using specific criteria prior to beginning the project

- Identify developed areas where characterizing flood risk is a priority within the basin during development of the hydraulic model

- Model the entire watershed with a detailed mesh resolution

- Model the entire watershed with a coarse mesh resolution.

### Selection and rationale

Developed areas are based on a subjective determination during the scoping of the FFRD basin, but generally include all lands with a residential structure density greater than 500 structures per square mile according to National Structure Inventory (NSI), and all lands with a non-residential structure density of greater than 100 structures per square mile according to the NSI. Boundaries of incorporated places may also be considered.

### Rationale for why the other options were not selected

Identifying developed areas where characterizing flood risk is a priority within the basin during development of the hydraulic model was utilized in the Kanawha pilot study. This left model refinement up to each model developer and led to some inconsistencies between models.

Modeling the entire watershed with a detailed model resolution was considered, but the model runtime within the stochastic environment may be prohibitive. Modeling the entire watershed with a coarse model resolution was considered, but the quality of the results may not be adequate to meet the FFRD objectives.

If we learn more about available U.S. Census Bureau datasets, this decision may change.

## Categorization and Selection of Key and Secondary Streams

Optimization of 2D HEC-RAS model runtimes to facilitate Monte Carlos analysis requires modeling some areas of a basin with a coarse mesh and priority areas of flood risk characterization with a refined mesh in the hydraulic model.

### Options available

- Identify areas of interest where characterizing flood risk is a priority within the basin using specific criteria prior to beginning the project

- Identify areas of interest where characterizing flood risk is a priority within the basin during development of the hydraulic model

- Model the entire watershed with a detailed mesh resolution

- Model the entire watershed with a coarse mesh resolution.

### Selection and rationale

Areas of interest where characterizing flood risk is a priority are identified at the beginning of the project using specific repeatable criteria. The Key Streams layer is a set of stream centerlines that are considered the dominate and most important streams to characterize flooding in the basin. The key streams are selected during project planning and provided as a shared dataset. These streams are expected to include a refined mesh and terrain modification to incorporate bathymetry or estimated bathymetry. The secondary streams are selected during project planning and provided as a shared dataset. These streams are expected to include mesh refinement, but do not require terrain modification. The intent is to select stream refinement locations using a consistent approach throughout the watershed and between watersheds.

Key streams include all streams with a contributing drainage area greater than 100 square miles; all streams with an existing Flood Insurance Study (FIS) supporting AE, AH, or AO flood zone delineation; and streams having an active stream gage with useful observed data for calibration.

Secondary streams include all streams with a contributing drainage area greater than 50 square miles, and all streams with an existing FIS supporting A zone delineation.

### Rationale for why the other options were not selected

Identifying areas of interest where characterizing flood risk is a priority within the basin during development of the hydraulic model was utilized in the Kanawha pilot study. This left model refinement of streams up to each model developer and led to some inconsistencies between models.

Modeling the entire watershed with a detailed model resolution adequate for the key and secondary streams was considered, but the model runtime within the stochastic environment may be prohibitive.

Modeling the entire watershed with a coarse model resolution adequate for the key and secondary streams was considered, but the quality of the results may not be adequate to meet the FFRD objectives.

## Selection of Calibration/Validation Time Periods

As was previously stated, initial parameter estimates within hydrologic, reservoir operations, hydraulic, and/or consequence models must be subjected to a model calibration process that compares computed outputs against observed data. Parameters should be modified to achieve an adequate fit. Following model calibration, parameters must then be tested through a model validation process where computed results, without any further parameter modifications, are used to compute outputs which are compared against observed data for independent events that were not considered during model calibration. The selected time periods used during both model calibration and validation must:

- Be approximately equal to the magnitude of hypothetical events being considered within FFRD applications

- Overlap in time/space with the available meteorologic and observed data.

### Options available

The following calibration/validation time period selection options were considered:

- Randomly select time periods with no consideration of flood event magnitude, meteorologic, and/or observed data availability

- Select multiple time periods which have experienced large floods at one or more critical location and align with available meteorologic and observed data.

### Selection and rationale

Selecting multiple time periods which have experienced large floods at one more critical location and align with available meteorologic and observed data better ensures the hydrologic, reservoir operations, hydraulic, and consequences models accurately produce estimates of pertinent variables. Selecting multiple flood events is typically required to verify the simulated flood events/time periods are approximately equal to the magnitude of hypothetical events being considered within FFRD applications at all critical locations.

### Rationale for why the other options were not selected

Randomly selecting time periods with no consideration of flood event magnitude, meteorologic, and/or observed data availability does not guarantee that the hydrologic, reservoir operations, hydraulic, and consequences models accurately produce estimates of pertinent variables at all critical locations. Therefore, this option was not considered acceptable for use in FFRD applications.

## Categorization and Selection of Model Comparison Locations

Computed outputs must be compared against observed data at all critical locations to ascertain model performance. The selected categorization and selection method for model comparison locations must also consider:

- Inaccuracies in hydrologic, reservoir operations, hydraulic, and consequence modeling approaches

- Inaccuracies of meteorologic and observed data

- Meteorologic and observed data availability.

### Options available

The following categorization and selection of model comparison location options were considered:

- Randomly select model comparison locations

- Use only active stream gages

- Use a tiered list of model comparison locations that consider critical locations, modeling approaches, meteorologic data, and observed data availability and inaccuracies.

### Selection and rationale

Using a tiered list of model comparison locations that consider modeling approaches, meteorologic data, and observed data availability and inaccuracies satisfies the above criteria and was chosen for use within FFRD applications. An example of a tiered list includes primary, secondary, and tertiary locations where varying levels of performance criteria are used to evaluate model performance.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for model comparison location categorization and selection and are not considered acceptable for use in FFRD applications:

- Randomly select critical model comparison locations

- Use all reservoirs with observed data

- Use all active stream gages.

These options do not guarantee model output can be compared against observed data at all critical locations.

## Dam and associated structure Inclusion/Exclusion Criteria

Project planning must include determination of which dams should have data collection associated.

### Options available

- Do not provide any data

- Use federal databases, i.e., National Inventory of Dams (NID).

### Selection and rationale

Supporting data must be gathered to enable determination about inclusion/exclusion of dams. The NID provides point and some hydraulic information. The WCMs and National Dam Safety Program Phase 1 Inspection Reports produced for each dam (available via the [Defense Technical Information Center \[DTIC\]](https://discover.dtic.mil/)) should be used to gather data.

Determining factors for inclusion/exclusion of dams within a model have not been determined.

### Rationale for why the other options were not selected

If no data is collected, a determination on inclusion/exclusion of a dam cannot be made.

## Levee System Inclusion/Exclusion Criteria

Project planning must include determination of which levees should have data collection associated.

### Options available

- Do not provide any data

- Use federal databases, i.e., National Levee Database (NLD)

- Use a curated version of the NLD.

### Selection and rationale

Supporting data must be gathered to enable determination about inclusion/exclusion of levees. The NLD alone may not provide adequate data. Curating the data prior to determination about inclusion/exclusion from a model is necessary to ensure accurate data.

### Rationale for why the other options were not selected

If no data is collected, a determination on inclusion/exclusion of a levee cannot be made.

## Basin Characteristic Datasets

Geographic Information System (GIS) data sources containing basin characteristics must be gathered to support model parameterization. The selected basin characteristic datasets must:

- Allow for parameterization of land surface processes within hydrologic, reservoir operations, and hydraulic models

- Have a spatial resolution detailed enough to discern major changes in runoff generation

- Contain up-to-date data.

### Options available

The following basin characteristic dataset options were considered:

- Do not collect basin characteristic datasets

- Collect only the General Soil Map of the United States (STATSGO)

- Collect National Land Cover Database (NLCD) land cover classification data prior to 2019

- Collect both Gridded Soil Survey Geographic (gSSURGO) and the most recent NLCD data.

### Selection and rationale

Collecting both gSSURGO soils and the most recent NLCD data better ensures the hydrologic, reservoir operations, and hydraulic models can be successfully parameterized.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for basin characteristics and are not considered acceptable for use in FFRD applications.

- Do not collect basin characteristic datasets

- Collect only gSSURGO

- Collect only land cover classification data.

These options do not allow for parameterization of land surface processes within hydrologic, reservoir operations, and hydraulic models.

## Vertical Datum Selection

Vertical datum used within the models and reports must be clearly documented to avoid possible mistakes or misapplication of the results.

### Options available

- Require a consistent datum for all FFRD studies, North American Vertical Datum of 1988 (NAVD 88) in feet, with some exceptions for areas outside the contiguous United States.

- Allow each study to select appropriate datum for the individual basins.

### Selection and rationale

Consistently using NAVD 88 for vertical datum reduces opportunities for mistakes or misapplication of results.

### Rationale for why the other options were not selected

Consistency in vertical datum will reduce opportunities for mistakes or misapplication of results.

## Time Zone Selection

Observed data time zone guidance must be provided to allow teams to have clarity on the requirements or best practices.

### Options available

- Use local time zones for each project

- Use worldwide standard time zone.

### Selection and rationale

The Greenwich Mean Time (GMT) time zone is required for all FFRD modeling and datasets. This allows a consistent standard for all teams and minimizes complications from seasonal time adjustments.

### Rationale for why the other options were not selected

A worldwide standard time zone achieves the desired consistency.

## Establishment of Authoritative Observed Data Set

FFRD requires significant calibration and verification steps throughout the lifecycle of developing a watershed. If the underlying observed data used for calibration and verification is not consistent across the lifecycle of a project, the act of calibration and verification loses its utility.

### Options available

- During pre-model data collection establish an authoritative curated observed dataset that is used throughout the lifecycle of the project development

- Do not centralize observed data and leave it up to modeling teams.

### Selection and rationale

Centralization and curation of observed data for use by all teams during a watershed is the selected path forward. This provides consistency in the application of calibration and verification.

### Rationale for why the other options were not selected

Not centralizing observed data leads to use of inconsistent observed data (units, datums, missing data) causing incongruent conclusions about calibration and verification.

## Perform Data Collection Prior to Kickoff

A large amount of input data is required for an FFRD modeling project. Modeling professionals are adept at gathering data from a variety of sources to meet the needs, but it can be time consuming, and it is difficult to properly document data sources. There are several up-front decisions for an FFRD project that rely on research into the available data sources that affect the scope of specific modeling tasks. A coherent strategy for FFRD data management starts with guidance for data collection prior to project kick-off.

### Options available

- Minimal coordination of data collection prior to kick-off

- Rigorous effort to collect shared input dataset prior to kick-off.

### Selection and rationale

The SOP calls for a rigorous effort to collect input data that will be consistent, authoritative, well documented, and shared across the full project team.

### Rationale for why the other options were not selected

Data collection should not be distributed to individual modelers, as this would result in possible inconsistencies of input data, duplicate efforts, and modeling scopes that are vague during kickoff.

—Model Development Standards\
and Process
=============================

This section contains general topics relevant to the hydrologic, reservoir operations, hydraulic, and consequences models. Topics specific to each model are contained in later sections.

## Standard Naming Conventions

The FFRD SOP must provide some discussion on model and model element naming conventions.

### Options available

- Require stringent naming conventions per SOP

- Require stringent naming convention for models per SOP

- No standards

- Naming convention spelled out in report.

### Selection and rationale

The SOP provides example naming conventions.

Naming conventions will not be overly prescriptive. However, delivered model names must follow SOP guidance. Name of base model will use plan names written in a specific way. Naming must be clear and consistent.

Note that the base model delivered for cloud compute will include coherent naming convention adaptable for SST events and generic, i.e., not specific to calibration events/time windows. The model integrator is responsible for these names.

### Rationale for why the other options were not selected

A very rigid naming convention does not need definition to use in all FFRD applications and experience in other programs has shown that rigid guidance can be cumbersome and inefficient. However, each team must define, adopt, and document a naming convention.

## Model Metadata

FFRD relies on models developed by modeling teams that will be stored for future use. To improve reusability and clarity of what the models represent a model description or model metadata must be provided. The FFRD SOP includes a project report containing robust discussion of data sources and modeling approaches; however, the report can become separated from the model. Co-locating the description of the model with the model itself can improve its reusability and clarity for what the model represents.

### Options available

- Final models include metadata

- All models include metadata

- No metadata

- Results include metadata.

### Selection and rationale

The FFRD team agrees there needs to be metadata, and that metadata should be included in models that are final at a minimum, as well as some metadata to go with the results to make them searchable. There is an investigation to research and define metadata standards in the upcoming contracts with FEMA. No decisions have been finalized.

The Kanawha and Duwamish river basin pilot studies are being utilized for experiments, no metadata standards have yet been defined.

### Rationale for why the other options were not selected

Minimal metadata is being required or tracked in any final or significantly coordinated way.

## Coordinate Reference System for Models

Geospatial data that preserves area will aid in model agreement and reduce calculation time. An unambiguous consistent projection is necessary.

### Options available

- Do nothing

- Accept unprojected models

- Allow models to differ

- Use a standardized national projection for all models that preserves area (no exception)

- Use a standardized national projection for all models that preserves area (with exception for Alaska)

- Allow each basin to define the projection based on local datums.

### Selection and rationale

USGS Albers will be used. Use Foot_US (using WKT text). Foot=0.3048 meters.

There is value in having an enhanced security pedestrian gate (ESPG) associated with the projection. The industry common practice is to model in feet.

\*\*\*Need to determine if it should be foot or US foot. This needs to be consistent with the SOP once determined. Currently, converting Albers from meters to another unit and this is causing issues with other software. Cannot have two different units for vertical and horizontal.\*\*\*

### Rationale for why the other options were not selected

Each state chose a different projection causing inconsistency.

## File Structure for Interim Models

Many models are associated with an FFRD modeling project, and they must go through various interim steps of review and updates before they are ready for final delivery. After final delivery, additional updates may be needed as they are adapted for cloud computes or to address previously unknown model stability issues. Guidance for organizing shared interim models should be discussed in the SOP. The use of an S3 cloud bucket and the interface with it through the model library allows for a full team to collaborate and share files in a single location, regardless of their home organization.

### Options available

- Standardized file structure for interim model sharing and storage

- No structure; ad hoc sharing using systems developed by individual teams.

### Selection and rationale

The SOP describes a directory structure to be used within the S3 bucket that attempts to provide a clear location for interim models to be shared and temporarily stored as they progress to delivery.

### Rationale for why the other options were not selected

Other methods would create more opportunities for mistakes or data loss and would not take advantage of the model library as a team collaboration tool.

# —Meteorologic Data

Several of the FFRD initiative’s requirements necessitated re-thinking how probabilistic meteorologic boundary conditions are applied to hydrodynamic models for modeling flood hazards. Decisions regarding the hydrometeorology hinged on the development of an approach that worked at a large range of watershed scales, could handle a wide variety of flood-causing storm mechanisms prevalent throughout the United States, and could be developed and applied consistently throughout the country. The primary concern was contending with the shortcomings of the most common approaches in industry and deciding whether to try and shore up those techniques or adopt more modern methods found in the academic literature.

## Hydrometeorological Methods

The choice to start with precipitation instead of flow is based on a number of key points. Flow data is only available where there are gages, modeling on flow alone would be very difficult in ungaged locations, starting with precipitation allows for generation of flows in ungaged watersheds and is then limited by gages in terms of calibration of the ungaged watersheds. Using precipitation-based methods allows for hydrologic and hydraulic modeling down to small drainage areas as required by FFRD. Gridded precipitation datasets with high spatial and temporal resolution are becoming more prevalent and are consistently available throughout the nation in similar quality, using these datasets improves the consistency in the application.

### Options available

- Flow frequency-based approaches

- Precipitation-frequency (NOAA Atlas) based approaches

- SST

- Synthetic weather generation

### Selection and rationale

SST is a proven method for developing flow frequency relationships for all subunits of a watershed in a single stochastic simulation, owing to the work done by Dr. Daniel Wright and researchers affiliated with the Hydroclimate Extremes Research group at University of Wisconsin. In the last 10–15 years, growth in the quality and availability of gridded rainfall products has driven rapid development in rainfall frequency analysis techniques that preserve the complex space-time structures of extreme rainfall events. Instead of relying on an analysis of gage-measured point rainfall extremes, as is the case with precipitation frequency products like NOAA Atlas 14, SST does not require any assumptions about AEP neutrality, design storm spatial or temporal patterns, or require development and/or application of area reduction methods. SST is a data-driven approach relying on observed precipitation data gathered from a wide geographic area and long period of record and preserves the critical properties of those storm events when estimating watershed precipitation frequency, and when coupled with a hydrologic model, flow frequency at any location in the watershed. SST is the simplest method available for producing flow frequency curves at any point within a watershed and is a method that can be applied consistently across the country. It can be applied at small scales up to an entire HUC-4 watershed in a single set of simulations.

HEC-HMS, the hydrology model being applied in the pilot studies (see Section 5), has native capabilities for transposing rainfall grids and is a straightforward platform to use for handling the spatial geometry of intersecting transposed grids with a watershed in an uncertainty simulation.

Currently, the chosen approach only transposes precipitation data. This is consistent with applications of SST in the scientific literature. However, future efforts will investigate transposition of temperature fields as well, improving SST’s capabilities for modeling a spectrum of rain and snow mechanisms for flood generation.

<span class="mark">The FFRD initiative requires a methodology that produces hazard frequency analyses anywhere within the United States at a resolution fine enough for local decisions at the watershed scale (HUC-4). The requirement of processing data at a HUC-4 scale anywhere within the United States removes the necessity to rely simply on USGS gaged flow or precipitation data. Evaluation at the HUC-4 scale makes the application of NOAA Atlas 14 difficult due to the desire to preserve the intensity duration and frequency of events across space and time. The desire to have a methodology that reduces assumptions and provides available data at the watershed level consistently, applicable anywhere in the nation, led to a heavy reliance on the available precipitation isohyets in datasets like Analysis of Record for Calibration (AORC) or multi-radar multi-sensor (MRMS) systems. Using this data with SST allows preservation of the spatial and temporal distribution of the precipitation duration and intensity, as well as maintains consistency of the storm types in their relative frequency and size with historic patterns. Therefore, the FFRD SOP outlines a methodology based on SST.</span>

<span class="mark">Credible estimation of flood hazard using SST is highly reliant on good quality precipitation data as it is a *non-parametric* method for statistical inference. No models are fit to the data and the storms speak for themselves. This highly contrasts with the traditional precipitation-frequency-based approaches for developing design storms and was selected to address many of the shortcomings of the traditional approach.</span>

### Rationale for why the other options were not selected

Flow frequency-based approaches rely on having gage data available at all the locations of interest throughout a watershed. The availability of quality peak flow records for all tributaries of a watershed down to small drainage areas is inconsistent throughout the country and the quality of the data, including its POR, may be too limited to make good inferences about flows with an AEP rarer than 1/25 or 1/50 reliably.

Precipitation frequency analyses are inconsistently available across the United States. Some states (such as those in the Pacific Northwest) do not have up-to-date Atlas 14 coverage and would rely on older documents such as NOAA Atlas 2. The oldest volumes of NOAA Atlas 14 were published more than 20 years ago and are missing the most recent two decades of precipitation observations. Atlas 15 will become available nationwide in the next five years solving these problems but not overcoming the inherent limitations in application of the precipitation frequency product. There is no current guidance for appropriate selection of spatial and temporal patterns for frequency storms for multi-scale watershed flow frequency. Application of Atlas 14 GIS grids to a hydrodynamic model is an inappropriate use of that product. Guidance on area reduction factors is extremely out of date, limited in applicability, and poor in quality. Additionally, supplementary data necessary for modeling rain-on-snow events in a discrete precipitation frequency context is lacking.

Synthetic weather generation is not as mature of a method for the development of watershed flood hazard estimates, and compared to SST, requires much more input data and analysis, and much more computational time. It requires more expertise than the other methods to apply appropriately, and this experience is not widely available for a national-scale application of the method. Its primary advantage is that it can better model snowmelt-only floods than SST, and explicitly captures sequences of several storm events in a row, whereas SST only does so implicitly. The technical improvements offered by weather generation over SST were not viewed as worth the additional complexity and much larger computational demand.

## Criteria for event duration

Whether applying precipitation-frequency estimates from NOAA Atlas 14 or SST-based methods for hydrometeorology, a storm duration must be selected to use as the basis for development of boundary conditions. For Atlas 14 this affects the depths selected from the intensity-duration-frequency tables or isopluvial (GIS) rasters; for SST this affects the duration of rainfall accumulation used to determine if a storm is severe enough to be included in the storms catalog.

### Options available

Any duration of rainfall from the timestep of the rainfall products (typically one hour for gridded precipitation, or as small as five minutes for precipitation frequency products) up to several days or even weeks could theoretically be used for identification of storms. The selected duration should be tied to the typical duration of heavy rainfall for a location, which is a meteorological factor. Shorter durations (24 hours and less) are associated with shorter-lived storms such as mesoscale convective complexes. However, this leaves out a significant amount of heavy rainfall associated with synoptic-scale events such as mid-latitude cyclones, which have a typical duration of 48 to 72 hours. Some persistent events may be longer than 72 hours.

### Selection and rationale

The 72-hour precipitation duration is the standard duration of analysis from SST applications in literature and, as of August 2024, there is no reason to deviate. Further study of this and the number of events per year and their influence on the resulting intensity duration frequency (IDF) relationships produced by FFRD outputs should be monitored to determine if any justification for deviation is warranted.

The most common duration used in radar rainfall-based SST studies is 72-hours to encompass both convective and synoptic meteorology. It is also the storm duration used in most PMP studies; for example, HMR-51. For most of the United States, mid-latitude cyclones are the dominant storm mechanism for watershed-scale heavy rainfall, and using their typical duration as the accumulation duration for the storm catalog ensures the full storm rainfall is captured, and events are independent.

### Rationale for why the other options were not selected

Durations shorter than 72 hours run the risk of not capturing the full storm rainfall from synoptic-scale events and should not be considered. Durations longer than 72 hours could include rainfall from multiple storm events as a single event and would violate the assumption that each storm is a single event.

## Events are defined as the presence of precipitation

Most of the hydrometeorology methods proposed assume that floods are caused, all or in part, by rainfall. This assumption means that in situations where snow is the only factor in a substantial proportion of the annual maximum series of floods that the hazard may not be characterized well.

### Options available

- Neglect influence of snowmelt

- Model a range of rain-on-snow and rain-only events using SST, but do not explicitly handle snow-only floods

- Develop a comprehensive modeling approach that includes snow-only floods.

### Selection and rationale

The current approach is to model a range of rain-on-snow and rain-only events using SST by handling seasonally-varying initial snow conditions using a quasi-continuous framework. This framework does a much better job of characterizing rain-on-snow events than frequency-based storm events by allowing a full distribution of snowpack states and rainfall events to be combined. It permits some snow-only events when a storm is selected that occurs in the snowmelt season but the transposition causes it to miss the watershed entirely, and observed temperature and snowpack data are used in a simulation causing a snowmelt flood, although this behavior is incidental.

The SST plus quasi-continuous hydrology framework allows for a much wider range of snow-influenced events to be modeled, including events where rain is present, but it is a smaller factor than snowmelt, which is not typically handled in precipitation frequency-based simulations. Currently, SST is limited to using a transposed rainfall field with an observed, untransposed temperature field, leading to a decoupling of the meteorologic processes. Work is underway to identify the proper way to transpose temperature fields in conjunction with the rainfall transposition to capture the variability of temperature that results from the presence of a storm and could provide even better fidelity for rain-on-snow modeling. Even without the temperature transposition, early modeling results in snow-influenced watersheds have produced good validation results that do not necessitate more detailed handling of temperature or snow-only floods.

### Rationale for why the other options were not selected

Snow is an important input for flood events even when it isn’t the primary causative mechanism. Neglecting snow entirely would understate the severity of floods. Developing a more comprehensive approach that includes snow-only floods hasn’t proven necessary in the pilot studies so far. Currently, methods for further improving rain-on-snow characterization that will also better explain snow-dominated floods are being developed. We have chosen to improve capabilities in the current framework before pursuing additional complexity by trying to develop an entirely new model for snow-only floods.

## Inclusion of events in the catalog

Since SST was selected as the hydrometeorology modeling approach, catalogs of observed storm events are needed as the input dataset. Some criteria are necessary for deciding if a storm event should be included in the SST storm catalog. Several different properties of a storm can be considered when deciding if the storm is severe enough for inclusion. In SST language, the storm data used for deciding if it is included in the catalog is called the severity criteria. If a storm’s property is greater than the severity criteria, it is included in the catalog.

### Options available

- Total storm rainfall averaged over an area the size and shape of the target watershed

- Maximum storm accumulation over a single pixel for total storm duration

- Maximum storm intensity over a single pixel for one timestep.

### Selection and rationale

Using the watershed area/shape accumulation is consistent with past studies and literature based on radar-derived rainfall. It is the most likely method to identify storms that are both widespread and moderate in intensity, and storms that are locally very intense but not widespread.

### Rationale for why the other options were not selected

Point maximum accumulation would tend to identify storms that are locally very intense and is consistent with some specific studies in the past; however, it could prevent storms with widespread moderate rainfall that produce large volumes of runoff from being included. These kinds of events are often the most significant flood-causing storms in large watersheds. Using the single timestep maximum intensity could be affected by artifacts in the data and do not improve selection of storms.

## Event Catalog Size

The size of the catalog influences the range of magnitudes of storm events that are simulated in the SST procedure and is determined by the selected severity criteria. The catalog includes multiple events per year drawn from the transposition domain, which creates a long effective period of record using space-for-time substitution. Using a larger catalog with a lower or more permissive severity criteria means that the SST simulation needs to run more events per year but includes a wider array of events. Typically, a severity criteria is chosen so that a target average rate of events per year is achieved, e.g., in a dataset with 40 years in the POR, a severity criteria might be selected so there are 400 events in the catalog resulting in an average rate of 10 storms per year.

### Options available

Typical values of the rate of storms per year in a catalog vary from 5 to 20 storms per year with a most frequent choice of ten storms per year. Choosing a severity criteria/catalog size resulting in small variability in the properties of the smallest storms in the catalog reduces the sensitivity of the choice and results from a larger number of events per year. It also affects the fidelity of flow frequency curves in the range of the 2- to 5-year event. However, a larger catalog requires more simulations per year in the overall stochastic simulation.

### Selection and rationale

The selected severity criterion results in an average of ten events per year from the catalog. The Kanawha and Duwamish river basin pilot studies used a precipitation dataset with a period of record from 1979 to 2022 resulting in a catalog with 440 events. Ten events per year is the most common target rate in the literature.

<span class="mark">The desired catalog size is 10 times larger than the number of years in the precipitation POR (N) so that the average rate of storms in the catalog is 10 per year. Retain the top 10×N events by potential precipitation. For example, if the POR is 1979 to 2022, keep the largest 440 events according to potential precipitation. To achieve the full frequency range desired for the stochastic simulations, a rate of 10 per year is sufficient. Too small of a rate affects the ability to estimate the left (frequent) tail of the curve and too high of a rate is computationally inefficient. Lower ranked storms tend to have similar values of potential precipitation and low variability in spatial and temporal patterns and adding significant numbers of these storms to the simulation does not improve the result.</span>

### Rationale for why the other options were not selected

The effect of a smaller catalog is being tested in the interest of saving runtimes, while avoiding impacts to estimates of the 2- to 5-year event on the flow frequency curve. Five events per year would cut simulation times in half but affect the frequency curve on the more frequent end. There does not appear to be any benefit to a catalog having more than ten storms per year in the catalog or in the simulation procedure.

## Definition of transposition domain

For SST, the transposition domain is a geographic region where the meteorology is assumed to be homogeneous, and that any storm that occurred within that boundary can be freely transposed to any other location inside that domain. This impacts which storms are included in the catalog, and the area to which they can be transposed.

### Options available

As of August 2024, the only way to generate a transposition domain is by expert judgment.

### Selection and rationale

The transposition domains for the Kanawha, Duwamish, and Trinity river basin pilots were created by a meteorologist using available meteorological information to draw a boundary.

### Rationale for why the other options were not selected

Research is underway to identify a method for automatically and more objectively defining a transposition domain for a watershed, but the findings will not be available in advance of the pilot studies.

## Normalized transposition

In transposition domains where the meteorology is considered homogeneous, but the terrain is highly variable, including significant mountains, valleys, rain shadow effects, and orographic influence, the assumptions of homogeneity of the domain get stretched. An available tool used for adjusting rainfall fields for terrain in precipitation-frequency and PMP studies is called normalized (or enhanced) transposition. Normalized transposition uses a normalizing field, such as a frequency isopluvial map or climate normal map, to normalize the rainfall to a non-dimensional space where the storm occurred before transposing it. Then, once transposed, the normalization step is reversed using the values of the normalization field where it occurs.

### Options available

So far, no SST studies have used normalized transposition. It has only been employed in other, similar, types of studies. One option is to continue with tradition and not use a normalization step.

Assuming normalization is used, there is the choice of what field to use to normalize the precipitation. The most frequent data used for extreme precipitation normalization is a precipitation-frequency field such as NOAA Atlas 14 or Atlas 2. Other options include PRISM annual total precipitation, an elevation dataset, or in the vein of PMP studies, dewpoint climatology.

### Selection and rationale

For the Kanawha River Basin Pilot study, normalized transposition was not used because at the time, the modeling team chose to use the traditional SST approach as taken in the literature.

For the Duwamish River Basin Pilot study, initial SST runs without normalization were completed, and upon reviewing the results, the modeling team saw that the terrain had potential impacts on the transposition results and did an experiment to see if normalization would help. The NOAA Atlas 2 24-hour 100-year isopluvial was used for normalization and the results improved greatly. Atlas 2 was used because it is the only frequency precipitation product available in Washington. If Atlas 14 were available, it would have been used.

<span class="mark">Normalized transposition is a novel technique for improving performance of the SST technique at multiple scales within a watershed. It also helps hedge against uncertainty in the transposition domain boundaries by climatically adjusting storm precipitation during transposition. It is based on techniques used in hydrometeorological reports for determining PMP in the U.S.</span>

<span class="mark">HEC-HMS natively handles transposition normalization using a bias grid in the Gridded Precipitation method in the Meteorologic Model. The modeler needs to create a Precipitation-Normal Grid in their HEC-HMS project and then apply it in the Bias Grid option in their Meteorologic Model. The grid should be created in .GeoTIFF format.</span>

<span class="mark">The preferred source for a normalization field is NOAA Atlas 14. GIS Grids provided via the NOAA Atlas 14 Precipitation Frequency Data Server should be used where they are available. Use the 1/100 AEP grid for 3-day duration based on annual maximum series estimates. The grids must cover the entire transposition domain. If the transposition domain spans several volumes of NOAA Atlas 14, a mosaic of the grids will need to be created.</span>

<span class="mark">When NOAA Atlas 14 is not available, a suitable alternative is to create a mean annual maximum 72-hour precipitation field from the precipitation data used to generate the storm catalog. To generate this field, compute the annual maximum 72-hour precipitation value for each year at each grid cell, creating an annual maximum series for each cell. Then, take the average of these values and generate the raster. To check that the result makes sense, compare it to the spatial patterns of rainfall present in the Parameter-elevation Regressions on Independent Slopes Model (PRISM) 30-precipitation normal grid for the transposition domain. PRISM should not be used for normalization.</span>

### Rationale for why the other options were not selected

Going forward, the Duwamish River Basin Pilot study results show that normalization is a promising approach to modeling rainfall extremes in highly orographic areas. Experiments run in a non-pilot basin show that in an area with no orographic influence, the results are no different for the non-normalized or normalized runs and thus the normalization step can only help. These findings indicate that the no normalization method is not a good choice.

Precipitation-frequency based products offer the best measure of intensification of rainfall in the mountains, captures rain shadow effects, and all the other nuances of extreme rainfall. PRISM is similar but as it is based on climatic averages is less geared towards expressing extremes and has no benefit over A2/A14. Its only advantage is that it has seamless coverage over the entire continental United States; however, it is anticipated Atlas 15 with its seamless coverage will be used when it is made public. Elevation datasets capture some elevation-based intensification but does not handle differences in moisture transport due to proximity to a moisture source (e.g., the ocean). Dewpoint-based measures are used in PMP analysis, but those are generated as site-specific analyses and are not available as a nationwide product.

# —Hydrologic Modeling

Within FFRD applications, a hydrologic model is used to simulate a watershed’s response to precipitation, snow, and temperature. The conversion of precipitation to runoff involves many codependent processes including, but not limited to, condensation, evaporation, infiltration, and flow through porous media. The following sections detail the requirements, options, and selection of appropriate hydrologic modeling applications, methods, and uncertainty, amongst others.

## Hydrologic Modeling Methodology

The following requirements were all considered when choosing a hydrologic modeling application. The software must be:

- Free

- Widely used within/accepted by the hydrologic modeling community for extreme event simulations

- Well documented

- Continuously supported

- Computationally efficient

<!-- -->

- Quickly compute results to filter interesting events for subsequent computes in reservoir and hydraulic models.

The following simulation requirements were all considered when choosing a hydrologic modeling application. The software must be able to compute:

- Runoff given SST-derived precipitation and temperature

- Accurate baseflow hydrographs

- Snow accumulation/melt

- Accurate estimates of runoff downstream of large multipurpose reservoirs

- Runoff due to both short-term (i.e., single event) and long-term (i.e., continuous) meteorologic inputs

- Uncertainty in model outputs due to variable parameters and initial model states.

### Options available

The following hydrologic modeling applications were considered:

- USACE Gridded Surface Subsurface Hydrologic Analysis (GSSHA)

- U.S. Department of Agriculture (USDA)/Natural Resources Conservation Service (NRCS) WinTR-55

- USACE HEC-HMS

- USACE HEC-RAS with 2D flow areas

- USDA Soil and Water Assessment Tool (SWAT)

- Variable Infiltration Capacity (VIC) Macroscale Hydrologic Model

- Danish Hydraulic Institute MIKE-SHE.

### Selection and rationale

HEC-HMS was chosen as the selected hydrologic modeling software for FFRD applications. HEC-HMS successfully solves a wide array of possible hydrologic problems including large river basin water supply, extreme flood hydrology, and small urban watershed runoff, amongst other uses. Hydrographs produced by the program are used directly or in conjunction with other software for studies of water availability, urban drainage, flow forecasting, future urbanization impact, reservoir spillway design, flood damage reduction, floodplain regulation, and systems operation (USACE 2024).

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic modeling platform and are not considered acceptable for use in FFRD hydrologic modeling applications:

- USACE GSSHA

<!-- -->

- Computationally inefficient

- Not widely used within/accepted by the hydrologic modeling community for extreme event simulations.

<!-- -->

- USDA/NRCS WinTR-55

<!-- -->

- Not widely used within/accepted by the hydrologic modeling community for extreme event simulations

- Cannot simulate baseflow, snowmelt, reservoirs, or long-term simulations.

<!-- -->

- USACE HEC-RAS with 2D flow areas

<!-- -->

- Cannot simulate baseflow or snowmelt

- Computationally inefficient.

<!-- -->

- USDA SWAT

<!-- -->

- Not widely used within/accepted by the hydrologic modeling community for extreme event simulations

- Cannot use a time step other than 1 day.

<!-- -->

- VIC

<!-- -->

- Not widely used within/accepted by the hydrologic modeling community for extreme event simulations.

<!-- -->

- MIKE-SHE

<!-- -->

- Not free

- Not widely used within/accepted by the hydrologic modeling community for extreme event simulations

- Computationally inefficient.

## Basin Element Delineation

A fundamental problem when simulating hydrologic systems is ensuring that an appropriate level of detail is being represented within the components of the system that have a significant influence on the phenomena being modeled. An associated problem Acquiring and interpreting information regarding regional and watershed-specific physical characteristics that enable an appropriate representation of the system while achieving the goals of the study or application is an associated problem (USACE 1994).

Subbasins and routing reaches must be delineated at major stream confluences, large changes in drainage area, locations with observed data, major hydraulic structures affecting flow and/or stage, or variations in physical characteristics affecting runoff generation. These variations can include abrupt changes in channel or overland slope, soil, land use, or other features. Subbasin delineations should be made in such a way that the foundational assumptions of the chosen loss, transform, and baseflow methods are not egregiously violated. Finally, subbasins and reaches should agree with existing data (e.g., published drainage areas for major stream gages, etc.).

### Options available

The following basin element delineation options were considered:

- Use existing reaches and subbasin boundaries from NHD and WBD without any alterations.

- Use the 8-point pour method to delineate reaches and subbasins without any extra data.

- Use the 8-point pour method to delineate reaches and subbasins supplemented by NHD and WBD data.

### Selection and rationale

The 8-point pour method, supplemented with NHD and WBD data, was chosen to delineate new reaches and subbasins for use in all FFRD applications. This method allows for the delineation of subbasins and reaches agreeing with foundational assumptions within the chosen modeling processes and aligning with observed data locations. Additionally, the resultant subbasins and reaches agree with existing data sources.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for delineating hydrologic modeling elements and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Use previously defined reaches and subbasin boundaries from NHD and WBD.

<!-- -->

- NHD reaches and WBD subbasin boundaries do not include considerations for observed data, variations in runoff generation characteristics, and major hydraulic structures.

<!-- -->

- Use the 8-point pour method to delineate new reaches and subbasins without any extra data.

<!-- -->

- This option did not guarantee agreement with existing data sources.

## Subbasin Discretization Method

A subbasin discretization method distributes the chosen modeling processes (e.g., loss, transform, etc.) throughout the subbasin. Also, the subbasin discretization method distributes the meteorologic boundary conditions throughout the subbasin. The following requirements were considered when choosing an appropriate model discretization method. The chosen method must:

- Allow for the utilization of gridded boundary conditions produced by SST.

- Produce gridded model state variables and outputs.

- Align/complement the foundational assumptions of the chosen loss, transform, and baseflow methods.

### Options available

The following model discretization options were considered:

- Treat all subbasin elements as lumped

- Use a preexisting grid cell file (e.g., *.mod* file)

- Discretize each subbasin element using the Standard Hydrologic Grid (SHG) with an appropriate horizontal resolution.

### Selection and rationale

Discretizing each subbasin element using the SHG option satisfies required criteria and was chosen for use within FFRD hydrologic modeling applications. The chosen horizontal resolution must be equal to or greater than the smallest resolution of the meteorologic boundary conditions (e.g., 2000 meters by 2000 meters).

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic model discretization and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Treating all subbasin elements as lumped cannot produce gridded model state variables and outputs.

- Using a preexisting grid cell file (i.e., *File-Specified* method) cannot produce gridded model state variables and outputs.

## Potential Evapotranspiration Method

In many areas of the United States, more than 50 percent of precipitation returns to the atmosphere through evaporation and transpiration (ET). FFRD applications require the simulation of both short and long periods of time. Thus, the estimation of potential ET is necessary. The selected potential ET method must:

- Be a mature method widely used within hydrologic modeling applications throughout the United States

- Be applicable across varying spatial scales (i.e., 1 square mile\>×\>1,000+square mile)

- Parameters can be estimated from readily available information sources

- Produce distributed estimates of potential ET

- Use data supplied by SST

- Include only a few parameters necessary to explain potential ET (i.e., parsimonious).

### Options available

The following potential evapotranspiration methods are included within HEC-HMS and were considered (many of these methods include both lumped and gridded implementations within HEC-HMS):

- Do not simulate potential ET

- Hamon

- Hargreaves

- Priestley Taylor

- Penman Monteith

- Monthly Average

- Specified Evapotranspiration

- Annual Evapotranspiration.

### Selection and rationale

The Gridded Hamon method satisfies the previously mentioned criteria and was chosen for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for potential evapotranspiration and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate potential ET

<!-- -->

- Does not produce estimates of potential ET.

<!-- -->

- Hargreaves Method

<!-- -->

- Not widely used within hydrologic modeling applications throughout the United States.

<!-- -->

- Priestley Taylor Method

<!-- -->

- Not widely used within hydrologic modeling applications throughout the United States.

- Not as parsimonious as other options.

<!-- -->

- Penman Monteith Method

<!-- -->

- Not as parsimonious as other options.

<!-- -->

- Specified Evapotranspiration

<!-- -->

- Does not use data supplied by SST.

<!-- -->

- Annual Evapotranspiration

<!-- -->

- Does not use data supplied by SST.

<!-- -->

- Monthly Average Method

<!-- -->

- Does not use data supplied by SST.

## Snow Accumulation/Melt Method

A large portion of the United States experiences snow accumulation/melt which can affect flood risks. Snow accumulation/melt methods convert precipitation into either rain or snow and estimate the timing, rate, and ultimate volume of runoff produced by snowmelt. FFRD applications require the simulation of snow accumulation and melt. The selected snow method must:

- Be a mature method widely used within hydrologic modeling applications throughout the United States

- Be applicable across varying spatial scales (i.e., 0.1 square mile\>×\>1,000+square mile),

- Parameters can be estimated from readily available information sources using various literature sources

- Produce distributed estimates of snow water equivalent (SWE)

- Include only a few parameters necessary to explain the accumulation and melt of snow (i.e., parsimonious)

- Be computationally efficient.

### Options available

The following snow methods are included within HEC-HMS and were considered:

- Do not simulate snow accumulation/melt

- Lumped Energy Budget

- Gridded Energy Budget

- Hybrid

- Lumped Temperature Index

- Gridded Temperature Index.

### Selection and rationale

The Gridded Temperature Index snow method satisfies required criteria and was chosen for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for snow accumulation/melt simulation and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate snow accumulation/melt

<!-- -->

- Does not produce estimates of snow accumulation/melt.

<!-- -->

- Energy Budget

<!-- -->

- Cannot produce distributed estimates of SWE

- Parameters cannot be estimated from readily available information sources using various literature sources (e.g., albedo decay coefficient, etc.)

- Method is less parsimonious than other snow methods

- Not widely used, so less mature

- Less computationally efficient than other snow methods.

<!-- -->

- Gridded Energy Budget

<!-- -->

- Parameters cannot be estimated from readily available information sources using various literature sources (e.g., albedo decay coefficient, etc.)

- Method is less parsimonious than other snow methods

- Not widely used, so less mature

- Less computationally efficient than other snow methods.

<!-- -->

- Hybrid

<!-- -->

- Parameters cannot be estimated from readily available information sources using various literature sources (e.g., albedo decay coefficient, etc.)

- Method is less parsimonious than other snow methods

- Not widely used, so less mature

- Less computationally efficient than other snow methods.

<!-- -->

- Temperature Index

<!-- -->

- Cannot produce distributed estimates of SWE.

## Canopy Method

In many areas of the United States, more than 50 percent of precipitation returns to the atmosphere through ET. FFRD applications require the simulation of both short and long periods of time. Within HEC-HMS, potential ET is converted to actual ET by a Canopy method. The selected Canopy method must:

- Be a mature method widely used within hydrologic modeling applications throughout the United States

- Be applicable across varying spatial scales (i.e., 0.1 square mile\>x\>1,000+square mile)

- Parameters can be estimated from readily available information sources using various literature sources

- Include only a few parameters necessary to explain the accumulation and melt of snow (i.e., parsimonious).

### Options available

The following canopy methods are included within HEC-HMS and were considered:

- Do not simulate canopy

- Dynamic Canopy

- Simple Canopy.

### Selection and rationale

The Simple canopy method satisfies required criteria and was selected for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic canopy simulation and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate canopy

<!-- -->

- Does not convert potential ET to actual ET.

<!-- -->

- Dynamic Canopy

<!-- -->

- Not as parsimonious as the Simple Canopy method.

## Loss Method

While a subbasin element within a basin model conceptually represents infiltration, surface runoff, and subsurface processes interacting together, the actual infiltration calculations are performed by a loss method contained within the subbasin. The selected loss method must:

- Be a mature method widely used within hydrologic modeling applications throughout the United States

- Be applicable across varying spatial scales (i.e., 0.1 square mile\>x\>1,000+square mile)

- Parameters can be estimated from predominant soil textures using various literature sources

- Predicted values must be in accordance with classical unsaturated flow theory

- Produce distributed estimates of loss and excess precipitation

- Include only a few parameters necessary to explain the variation of runoff volume (i.e., parsimonious)

- Allow for single event and continuous simulations.

### Options available

A total of nine different loss methods are provided in HEC-HMS and were considered:

- Do not simulate losses

- Initial and Constant

- Deficit and Constant

- Green and Ampt

- Layered Green and Ampt

- Linear Deficit and Constant

- SCS Curve Number

- Exponential

- Smith Parlange

- Soil Moisture Accounting.

### Selection and rationale

The Deficit and Constant loss method satisfies required criteria and was selected for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic loss estimation and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate losses

<!-- -->

- Does not produce estimates of infiltration and excess precipitation.

<!-- -->

- Initial and Constant

<!-- -->

- Method is not accurate during continuous simulations.

<!-- -->

- Green and Ampt

<!-- -->

- Method is not accurate during continuous simulations.

- Method is less parsimonious than other loss methods.

<!-- -->

- Layered Green and Ampt

<!-- -->

- Not widely used, so less mature.

- Method is less parsimonious than other loss methods.

<!-- -->

- Linear Deficit and Constant

<!-- -->

- Not widely used, so less mature.

- Method is less parsimonious than other loss methods.

<!-- -->

- SCS Curve Number

<!-- -->

- Method is not applicable across large spatial scales.

- Predicted values are not in accordance with classical unsaturated flow theory.

- Method is not accurate during continuous simulations.

<!-- -->

- Exponential

<!-- -->

- Not widely used, so less mature.

- Parameters cannot be related to predominant soil textures.

- Method is not accurate during continuous simulations.

- Method is less parsimonious than other loss methods.

<!-- -->

- Smith Parlange

<!-- -->

- Not widely used, so less mature.

- Method is not accurate during continuous simulations.

- Method is less parsimonious than other loss methods.

<!-- -->

- Soil Moisture Accounting

<!-- -->

- Not widely used, so less mature.

- Method is less parsimonious than other loss methods.

## Transform Method

As precipitation exceeds the ability of the canopy, surface, and/or soil to absorb precipitation, excess precipitation is formed on the surface. This excess precipitation is subject to runoff transform computations which allow for the estimation of direct runoff hydrographs emanating from defined areas. The selected transform method must:

- Be a mature method widely used and well documented within hydrologic modeling applications throughout the United States

- Parameters can be estimated from GIS data sources

- Scalable and accurate for single event and continuous simulations

- Variable translation and attenuation processes can be simulated (i.e., vary parameters with excess precipitation rate)

- Be computationally efficient.

### Options available

A total of eight different transform methods are available for use within HEC-HMS and were considered:

- Do not simulate transform

- User-specified Unit Hydrograph

- User-specified S-Graph

- Snyder Unit Hydrograph

- Soil Conservation Service (SCS) Unit Hydrograph

- Clark Unit Hydrograph

- ModClark

- Kinematic Wave

- 2D Diffusion Wave.

### Selection and rationale

The ModClark transform method satisfies required criteria and was selected for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic modeling transform and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate transform

<!-- -->

- Does not produce direct runoff hydrographs.

<!-- -->

- User-specified Unit Hydrograph

<!-- -->

- Parameters cannot be estimated using GIS data sources

- Variable translation and attenuation cannot be simulated.

<!-- -->

- User-Specified S-Graph

<!-- -->

- Parameters cannot be estimated using GIS data sources

- Not widely used, so less mature

- Variable translation and attenuation cannot be simulated.

<!-- -->

- Snyder Unit Hydrograph

<!-- -->

- Variable translation and attenuation cannot be simulated with this method.

<!-- -->

- SCS Unit Hydrograph

<!-- -->

- Variable translation and attenuation cannot be simulated with this method.

<!-- -->

- Clark Unit Hydrograph

<!-- -->

- Subbasin-specific time-area histograms cannot be readily estimated using GIS data sources.

<!-- -->

- Kinematic Wave

<!-- -->

- Not widely used, so less mature.

- Less computationally efficient than other transform methods.

- Variable translation and attenuation cannot be simulated.

<!-- -->

- 2D Diffusion Wave

<!-- -->

- Less computationally efficient than other transform methods.

## Baseflow Method

As water is infiltrated to the subsurface, some volume can be lost to deep aquifer storage. However, some volume is only temporarily stored and returns relatively quickly to the surface. The combination of this baseflow and direct runoff results in a total runoff hydrograph. The selected baseflow method must:

- Be a mature method widely used and well documented within hydrologic modeling applications throughout the United States

- Have a direct connection between infiltrated water and computed baseflow

- Be scalable and accurate for single event and continuous simulations

- Accurately predict baseflow during variable magnitude flood events.

### Options available

A total of five different baseflow methods are available for use within HEC-HMS and were considered:

- Do not simulate baseflow

- Constant Monthly

- Recession

- Bounded Recession

- Linear Reservoir

- Nonlinear Boussinesq.

### Selection and rationale

The Linear Reservoir baseflow method satisfies required criteria and was selected for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for baseflow and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate baseflow

<!-- -->

- Does not produce baseflow hydrographs.

<!-- -->

- Constant Monthly

<!-- -->

- Does not accurately predict baseflow during variable magnitude flood events.

- Method is not accurate during continuous simulations.

- Method does not have a connection to infiltrated water.

<!-- -->

- Recession

<!-- -->

- Method is not accurate during continuous simulations.

- Method does not have a connection to infiltrated water.

<!-- -->

- Bounded Recession

<!-- -->

- Method is not accurate during continuous simulations.

- Method does not have a connection to infiltrated water.

- Not widely used, so less mature.

<!-- -->

- Nonlinear Boussinesq

<!-- -->

- Method is not accurate during continuous simulations.

- Method does not have a connection to infiltrated water.

- Not widely used, so less mature.

## Channel Routing Method

As total runoff from subbasins reach defined channels, depths increase and the predominant flow regime begins to transition to open channel flow. At this point, open channel flow approximations are used to represent translation and attenuation effects as flood waves move downgradient. The selected channel routing method must:

- Be a mature method widely used and well documented within hydrologic modeling applications throughout the United States

- Be applicable across varying spatial scales (i.e., lengths, widths, etc. of feet to miles and varying channel slopes from steep to mild)

- Parameters can be readily and accurately estimated from GIS data sources

- Variable translation and attenuation processes can be simulated

- Include only a few parameters necessary to explain the variation of channel flow/stage (i.e., parsimonious).

### Options available

A total of eight different channel routing methods are available for use within HEC-HMS.

- Do not simulate channel routing

- Lag

- Lag and K

- Kinematic Wave

- Modified Puls

- Muskingum

- Muskingum-Cunge

- Normal Depth

- Straddle Stagger.

### Selection and rationale

The following options satisfy required criteria and were selected for use within FFRD hydrologic modeling applications. However, each option requires justification.

- Modified Puls can be used for all channel slopes when accurate storage-discharge relationships are available for use (i.e., derived from a calibrated HEC-RAS model).

- Muskingum-Cunge can be used when channel slopes exceed approximately two foot per mile.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic channel routing and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not simulate channel routing

<!-- -->

- Cannot produce accurate estimates of flow for relatively large streams.

<!-- -->

- Lag

<!-- -->

- Only appropriate for use in streams that experience no attenuation (i.e., very steep bed slopes)

- Variable translation and attenuation cannot be simulated.

<!-- -->

- Lag and K

<!-- -->

- Not widely used, so less mature

- Parameters cannot be readily and accurately estimated from GIS data sources.

<!-- -->

- Kinematic Wave

<!-- -->

- Not widely used, so less mature

- Only appropriate for use in steep streams (bed slopes\>10 feet per mile)

- Variable translation and attenuation cannot be simulated.

<!-- -->

- Normal Depth

<!-- -->

- Not widely used, so less mature.

<!-- -->

- Straddle Stagger

<!-- -->

- Not widely used, so less mature.

- Only appropriate for use in streams experiencing no attenuation.

- Variable translation and attenuation cannot be simulated.

## Reservoir Representation within the Hydrologic Model

As runoff enters large bodies of water, water can be temporarily stored for multiple purposes including flood risk management, hydropower generation, and irrigation usage, amongst others. The selected reservoir representation method must:

- Simulate elevations and releases from reservoirs making a substantial impact on downstream/upstream riverine conditions.

- Allow for calibration/validation of hydrologic model processes and parameter choices at all important locations. In many watersheds, this includes locations upstream/downstream of large reservoirs and subject to influence from regulation.

The choice of a reservoir modeling method carries modeling complexity and time/cost implications (i.e., it takes more time to parameterize, calibrate/validate, and simulate stochastic events when using a complex reservoir modeling method). The cumulative impacts of many small dams can be significant at locations of interest. Also, some reservoir systems will require complex operations to accurately simulate riverine conditions while other systems do not.

The selection of appropriate reservoir representations within a hydrologic model as part of FFRD applications is currently being investigated.

### Options available

- Do not simulate any reservoirs within the hydrologic model

- Use specified releases to recreate operations

- Use defined elevation-storage-discharge relationships

- Simulate reservoir operations.

### Selection and rationale

The following options satisfy required criteria and were selected for use within FFRD hydrologic modeling applications. However, each option requires justification.

- Use specified releases to recreate operations

<!-- -->

- This option is acceptable for use within observed events (i.e., calibration/validation simulations) when observed data is available.

- This option is not acceptable for use in stochastic simulations.

<!-- -->

- Use defined elevation-storage-discharge relationships

<!-- -->

- This option is acceptable for use in both observed events and stochastic simulations.

- Elevation-storage-discharge relationships must be calibrated/validated using observed data.

<!-- -->

- Simulate reservoir operations

<!-- -->

- This option is acceptable for use in both observed events and stochastic simulations.

- Reservoir operations must be calibrated/validated using observed data.

### Rationale for why the other options were not selected

Not simulating any reservoirs does not allow for calibration/validation of hydrologic model processes and parameters at all important locations. Thus, this option was not considered acceptable for use in FFRD hydrologic modeling applications.

## Selection of a Computational Time Step

Much like subbasin and routing reach delineations, an appropriate computational time step should be selected based upon the watershed in question. While relatively large computational time steps can be used to produce accurate results for slowly responding watersheds, smaller computational time steps must be used to produce accurate results as the watershed response time decreases. As the computational time step increases, numerical diffusion also increases which can alter the shape of computed results in undesirable ways. This can also affect the computed peak results, which are often important outputs within FFRD applications. The selected computational time step method must:

- Be less than the travel time and/or time of concentration for all critical modeling elements within the modeling domain

- Produce at least four computed ordinates on the rising limb at all critical locations

- Adequately define the computed peak results for all critical elements within the modeling domain

- Balance computational efficiency with accuracy.

### Options available

A total of 18 different computational time steps are available for use within HEC-HMS. The following groupings of time steps were considered:

- Time steps\<15 minutes

- 15 minutes≤Time steps≤3 hours

- Time steps\>1 hour.

### Selection and rationale

Computational time steps between 15 minutes and 3 hours likely satisfy required criteria and are allowed for within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic model discretization and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Time steps\<15 minutes

<!-- -->

- Less computationally efficient than other time steps.

- Does not balance computational efficiency with accuracy (more emphasis placed on accuracy than computational efficiency).

<!-- -->

- Time steps\>3 hours

<!-- -->

- Requires very large modeling elements to ensure:

<!-- -->

- The time step is greater than the travel time and/or time of concentration for adequately several modeling elements,

- At least four computed ordinates are present on the rising limb at all important

- Computed peak results are adequately defined for each element within the modeling domain.

<!-- -->

- Does not balance computational efficiency with accuracy (more emphasis placed on computational efficiency than accuracy).

## Model Calibration and Validation Approach

Following parameterization, the hydrologic model must be shown to accurately produce estimates of pertinent variables at all critical locations. The selected calibration and validation approach must prove that the hydrologic model can produce accurate estimates of runoff for the given meteorologic inputs, initial conditions, and operational criteria at all critical locations for a range of pertinent flood events.

### Options available

The following model calibration/validation options were considered:

- Do nothing and use initial process and parameter estimates without any changes.

- Simulate multiple types of events (single event and continuous simulation), perform model calibration, and validate process/parameterization choices using observed data (produce statistical metrics, multiple types of plots, etc.).

### Selection and rationale

Simulating multiple types of events, performing model calibration, and validating process/parameterization choices using observed data satisfies required criteria and was selected for use within FFRD hydrologic modeling applications. Multiple statistical metrics must be used to quantify model performance (Moriasi, et al., 2007) including Nash-Sutcliffe Efficiency (NSE), Ratio of the Root Mean Square Error to the Standard Deviation (RSR), and Percent Bias (PBIAS). Additionally, computed and observed peak results and times of peak must be compared. Finally, multiple iterations between single event and continuous simulations must be made to ensure adequate parameterization and testing of certain parameters (e.g., maximum moisture deficit).

### Rationale for why the other options were not selected

Doing nothing and using initial process and parameter estimates without any changes does not prove that the hydrologic model accurately converts precipitation into runoff and was therefore not considered acceptable for use in FFRD hydrologic modeling applications.

## Determine State Variables for Use in Stochastic Simulations

Each stochastic simulation starts on a randomly sampled date. This requires the production of accurate hydrologic state variables corresponding to the start time of each stochastic simulation. Required hydrologic state variables include SWE, soil moisture, riverine/overland stage and flow, and reservoir contents (amongst others). The selected method for producing state variables must:

- Produce estimates of all required state variables

- Produce estimates for the entire modeling domain

- Produce estimates for each month.

### Options available

The following state variable generation options were considered:

- Estimating using observed data

- Extracting from POR simulation results.

### Selection and rationale

Extracting state variables from a POR simulation satisfies required criteria and was selected for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

Estimating state variables from observed data does not meet the required criteria and is not considered acceptable for use in FFRD hydrologic modeling applications. Observed data is limited in quantity, quality, space, and time. As such, there is no guarantee observed SWE, soil moisture, etc. will be available within the required modeling domain for the required times.

## Selection and Definition of Uncertainty Parameters

Hydrologic models are subject to various types of uncertainty affecting the accuracy of their predictions. The sources of uncertainty can be classified into four types: model parameter, model structure, observations, and input data. Understanding, accounting for, and communicating uncertainties associated with hydrologic modeling predictions can help modelers and decision makers make better informed decisions. To adhere with FFRD requirements, the selected hydrologic modeling uncertainty option must:

- Allow for the definition of uncertainty in key hydrologic model outputs

- Balance computational efficiency with accuracy.

### Options available

The following hydrologic modeling uncertainty options were considered:

- Do not consider any hydrologic parameters as uncertain

- Select key hydrologic parameters and define their ranges of uncertainty

- Consider all hydrologic parameters as uncertain.

### Selection and rationale

Selecting key hydrologic parameters and defining their ranges of uncertainty satisfies required criteria and was selected for use within FFRD hydrologic modeling applications.

### Rationale for why the other options were not selected

The following options do not meet the required criteria for hydrologic model uncertainty quantification and are not considered acceptable for use in FFRD hydrologic modeling applications:

- Do not consider any parameters as uncertain

<!-- -->

- Does not produce baseflow hydrographs.

<!-- -->

- Consider all parameters as uncertain

<!-- -->

- Does not balance computational efficiency with accuracy (more emphasis placed on accuracy than computational efficiency).

- 

# —Reservoir Operations Modeling

The United States has many reservoirs, but not all reservoirs are the same. Reservoirs vary in many characteristics including volume, outlets, and complexity of operations. Some are large and some are small. Some have sophisticated control structures, and some do not. Some operate without consideration of any other reservoirs, and some operate as a system.

## Reservoir Operations Methodology

BW-12 provides that FEMA must map areas of residential risk, including those that could be inundated as a result of failure of levees, dams, and other flood control structures, and must consider the level of protection provided by those flood control structures. In some systems, reservoir presence and operations can have an important impact on the flood risk. Of the roughly 70,000 dams in the United States, fewer than 2,500 dams have active gate operations or system-based operations that significantly impact flood characteristics.

### Options available

- Do not simulate any reservoir operations

- Model reservoir operations with Riverware software

- Model reservoir operations HEC-ResSim modeling software

- Model reservoir behavior within the hydrologic or hydraulic models instead of through a reservoir-specific model.

### Selection and rationale

The FFRD SOP leverages HEC-ResSim to model reservoirs with active gate operations significantly impacting flood characteristics or requiring the use of downstream controls for system operation. Of the roughly 70,000 dams in the United States, fewer than 2,500 dams meet these criteria.

An active experiment is evaluating the simplification of the logic for reservoir systems to ensure outputs are well calibrated and use the simplest logic possible to meet that objective.

### Rationale for why the other options were not selected

Using HEC-ResSim for systems requiring a reservoir operations model is more efficient and cost effective than using Riverware, as many of those systems already have existing HEC-ResSim models which are more easily integrated with the other software used in this work.

HEC-ResSim is reservoir operations specific software better suited to complex operations or system0-m-based options, where necessary, than other options.

For systems whose reservoirs are not meaningfully operated or whose operations can be effectively simplified to an inflow-outflow relationships, it is more cost effective to model that behavior through one of the other component models.

## Reservoir Representation within the Reservoir Model

Requirements statement

### Options available

- Use defined elevation-storage-discharge relationships

- Simulate reservoir operations without the use of any scripting logic (i.e., only using options available within the user interface)

- Simulate reservoir operations using one or more unique scripts.

### Selection and rationale

Selection and rationale

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Boundary Condition Influences across Hydrologic Unit Code Boundaries

Operational decisions for some very large systems of reservoirs may be made based on conditions in adjacent HUC-4 basins. This requires knowledge of adjacent basin conditions to model the system for FFRD. This phenomenon is not dominate in the first three pilot basins, and, therefore, is not being investigated during the pilot studies.

### Options available

- Ignore any and all cross-basin operational influences

- For basins where the cross-boundary influences are deemed significant, combine the interdependent basin models for the HEC-HMS and HEC-ResSim modeling

- For basins where the cross-boundary influences are deemed significant, use some randomly sampled variables as a proxy for conditions in the adjoining, relevant basis.

### Selection and rationale

This decision of how to manage cross-basin influences only applies in a select few basins where a cross-boundary influence exists and requires coordination in the current operational policies. Watershed systems that may use cross-boundary coordination (either in one direction, or in both directions) include the Kanawha-Ohio, Rio Grande, Arkansas River, Kansas/Republican, Colorado, and Lower Mississippi.

The selection decision varies based on the characteristics of each watershed. The rationale for each selection under each category is to choose the simplest option adequately reflecting the operations for the purpose of the FFRD project.

For each HUC-4 basin, cross-boundary influences will be identified and considered, as follows:

- If there is a cross-basin influence, but it is not dominantly reflected within the basin reservoir operations, it will be ignored in the models.

- If there is a cross-basin influence, and it is dominantly reflected within the basin reservoir operations, randomly sampled variables to reflect the influences should be used if possible. Otherwise, the HEC-HMS and HEC-ResSim models for the entire system should be developed together despite being larger than the HUC-4 basin, while the HEC-RAS models should still be built as separate units. Further investigation in these scenarios is likely necessary to selecting the best option.

### Rationale for why the other options were not selected

The rationale for each selection in each scenario is to choose the simplest option adequately reflecting the operations for the purpose of the FFRD project, and nothing less than adequate, and nothing more complicated than necessary.

## Model Calibration and Validation

Model calibration and validation are important checks on the quality of the model and the results it generates. For this work, model calibration is defined as the process of adjusting numerical or physical modeling parameters for the purpose of improving agreement with experimental data, and model validation is defined as the process of determining the degree to which the model is an accurate representation of the real world from the perspective of the intended uses of the model.

### Options available

- Assume the model setup is correct and do no validation or calibration

- Validate the network connectivity with a network mass balance model run

- Validate the reservoir release capacity with a rules set to release the historic observed data

- Calibrate model operations with a comparison to historic observed data.

### Selection and rationale

Both the network connectivity check and the reservoir release capacity check should be performed, as the relatively small investment of effort is fully justified for the value of having those model attributes validated.

### Rationale for why the other options were not selected

The do-nothing option is not acceptable, because the quality of the model is paramount to the success of the FFRD mission. The option to calibrate against historical data is not acceptable, because the actual historical operations often do not truly reflect the written description of operational policies. Thus, while HEC-ResSim model results are usually compared to historic data for a general reality check, they cannot truly be calibrated to match historic data. There is not “real” dataset to calibrate against.

## Assumptions Associated with Dam Breaching

Requirements statement

### Options available

- No Action

- ResSim stops operating when the dam breaches and changes to run of river

- Enhancement that allows ResSim to draw down the reservoir as a progression that realistically reflects how the breach would occur.

### Selection and rationale

Selection and rationale.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Criteria for Inclusion of Dams in Reservoir Model

Requirements statement

### Options available

- Option 1

- Option 2

### Selection and rationale

Selection for rationale.

### Rationale for why the other options were not selected

<span id="_Ref176716094" class="anchor"></span>Rationale for why each other option wasn’t selected.

## Initial conditions (HEC-ResSim Lookback window)

HEC-ResSim simulations require a Lookback window which is a period of warmup time ensuring water is routed through the full network before the simulation period with release decisions begins. Model alternatives require the setting of antecedent conditions via the Lookback feature. Typically, it is recommended that the lookback time window should cover a period of time sufficient for water to be routed from the uppermost headwaters input to the furthest downstream location. Models may run with a lookback period as short as one timestep, but the results may not be realistic because the antecedent conditions will not be accurately reflected. In some watersheds, this can be a significantly long period, as compared to the event window. The decision on how to set the HEC-ResSim lookback window is two-fold–how long should the lookback window be, and what input data should be used for that time window. The decision must take into consideration the time required to run the models that generate the lookback inputs as well as the impact on the HEC-ResSim results accuracy.

### Options available

- Lookback length: Use the smallest possible lookback time window without regard to impacts to the model results\
  Lookback input data: use the first timestep inputs as the lookback inputs.

- Lookback length: Use the full lookback time window necessary to capture the longest routing path\
  Lookback input data: use the first timestep inputs as the lookback inputs.

- Lookback length: Use the smallest possible lookback time window without regard to impacts to the model results\
  Lookback input data: use the first timestep inputs as the lookback inputs.

### Selection and rationale

Decision is based on lessons being learned during the Kanawha and Duwamish river basin pilot studies.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Scripting and Associated Security Vulnerabilities

Many HEC-ResSim models use scripts to help define complex reservoir operations, especially when operational decisions are based on variables not inherently tracked by the software and which must be calculated or brought in from external sources. However, when models are run on the cloud, as it the case for the FFRD production runs, scripts can be a security liability. Jar files and python modules cannot be uploaded to the CWBI cloud. It will be challenging for models with scripts to be accepted for cloud computing.

### Options available

- Leave scripts in models

- Remove all scripts from models

- Minimize the use of scripts in models and review and write justification for the need for any scripts that are essential to the model for FFRD purposes.

### Selection and rationale

The selected option is to minimize the use of scripts in models, using them only when necessary to reflect important operations. The scripts should be carefully reviewed by the modeling team and a justification should be written to describe why the script is necessary. CWBI security personnel review scripts and justification before they are run on the cloud.

### Rationale for why the other options were not selected

The do nothing option results in the HEC-ResSim model not functioning in the distributed cloud compute, and thus failing. Removing all scripts from all models will cause some models to neglect important operations.

## Breach Modeling Methodology within the Reservoir Model

Requirements statement

Dam breaching in HEC-ResSim must be modeled in coordination with the hydrologic and hydraulic models, and there must be some degree of cross model communication that allows the simulation behavior and assumptions to be consistent with those in the other models.

### Options available

- Option 1

- Option 2

### Selection and rationale

To model a breach event, an additional rule nested within an if/else block should be incorporated into the model and added to all zones. This nested condition dictates that if a target elevation is met or exceeded, the outflow will match inflow. The model should be developed to allow the breach elevation to vary. To accomplish this, the breach elevation is set up using a scalar input global variable. A state variable is needed to pull the global variable value into the operation rule set. An additional rule must be created and added to the Else portion stating if a breach is not occurring, releases from the Breach Outlet must be zero.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Determination to Run a Period of Record

The approach selected for managing the HEC-ResSim lookback period (Section [0](#_Ref176716094)) requires a dataset reflecting the reservoir operational conditions and resulting basin condition preceding each sampled event time.

### Options available

- Do not run a POR HEC-ResSim model

- Run a POR HEC-ResSim model.

### Selection and rationale

It was decided to run a POR simulation for the HEC-ResSim model, because it is the best approach for selecting reasonable antecedent conditions for the sampled events. See the decision described in [0](#_Ref176716094).

### Rationale for why the other options were not selected

Not running a POR is unacceptable for generating the antecedent conditions needed.

## Simplification of Rule Sets 

Determination of what rules to reflect in the model.

### Options available

- If modeler started with an existing model, don’t change any rules

- Remove all rules except those related to flood operations

- Simplify the operations to keep key rules.

### Selection and rationale

Selection and rationale.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Model Stress Testing

Stress testing is needed to proof the model for handling the full range of events that may be sampled and run during the distributed cloud computes.

### Options available

- Accept model with basic event testing and no further stress testing

- Run the probable maximum flood (PMF) synthetic event, or similar event, large enough to fully fill reservoir, and review to ensure model behavior is appropriate.

### Selection and rationale

The selected option is to run the PMF or other synthetic event sized to fully fill the reservoir and review the results to ensure the behavior is reasonable. This option was selected to improve the reliability and validity of the model in preparation for the full range of sample events.

### Rationale for why the other options were not selected

The do-nothing option is not acceptable. Without stress testing, some of the sampled events may overwhelm the model’s capabilities, such as physical parameters or operational settings, and result in failed runs or invalid outputs.

## Elevation, Storage, and Outlet Capacity

The HEC-ResSim model must be set up with physical reservoir elevation-storage and outlet capacities sufficiently described to manage the most extreme event (and associated initial conditions) sampled.

### Options available

- Make no review or change to preexisting model physical parameters

- Extrapolate beyond the existing/known elevation-storage and elevation-capacity curves ensuring the elevation range covers the likely highest elevation that might be seen in an extreme event such as the PMF.

### Selection and rationale

Selection and rationale.

Power

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Representing Hydropower

Some systems include hydropower operations, which tend to be more complex and challenging to represent. Often the operational parameters are not known, nor openly shared. Hydropower operations should be included to the degree important for simulating event conditions but should be simplified as much as possible.

### Options available

- Do not model hydropower outlets as powerplants or hydropower objectives

- Model hydropower to the fullest level of detail given available data

- Use controlled outlets for powerplants unless there are operations determining net release from the reservoir as a function of hydropower production required.

### Selection and rationale

Powerplants will be modeled as controlled outlets, except in cases where the hydropower production significantly impacts net release from the reservoir, in which case they should be modeled as power plants at the simplest level of detail possible to achieve and rules should be used to operate based on generation.

### Rationale for why the other options were not selected

The reason for modeling only hydraulic capacity is that fully modeling hydropower generation adds complexity to the ResSim model and should not be included unless there are rules that are a function of power generated. For most watersheds and reservoirs, there is not enough input data available (e.g., hydropower market demand) to model these operations.

## Selection and Definition of Uncertain operational Parameters

Some operations are dependent on variables that are not necessary to fully model but could instead be sampled from a representative distribution.

### Options available

- Don’t model outside the domain of the watershed (hp demand cycles)

- Reanalysis run.

### Selection and rationale

It is preferred to sample from an adjusted for current conditions distribution rather than historical data. This accounts for effects of nonstationarity.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

# —Hydraulic Modeling

Within FFRD applications, a hydraulic model is used to simulate a watershed’s response to excess precipitation, perform hydrodynamic routing of runoff and outflow from dams, and model the effects of dam and levee failure. The hydraulic model is used to develop inundation maps and provides a foundational model that can be refined for future detailed studies. The following sections detail the requirements, options, and selection of appropriate hydraulic modeling applications, methods, and uncertainty.

## Hydraulic Modeling Approach

Hydraulic modeling for FFRD aims to meet FEMA requirement to provide flood risk data that covers all areas that may be developed and all areas that are currently developed. Additionally, hydraulic modeling is required to quantify flood impacts within a watershed.

### Options available

- No hydraulic modeling (rely solely on hydrologic and reservoir operations model outputs to characterize flood risk)

- One-dimensional (1D) modeling of selected reaches with a watershed

- 1D/2D mixed modeling of selected reaches with a watershed

- 1D/2D mixed modeling of the entire watershed

- Full 2D modeling of the entire watershed.

### Selection and rationale

Basin wide 2D hydraulic modeling is deemed the best option to meet the FFRD objectives. It allows for development of mapping products including all areas that may be developed and all areas that are currently developed, characterizing pluvial risk, and identifying areas of residual risk across the nation due to overtopping and/or breach of levees and dams. The 2D modeling approach allows for a high level of flexibility in terms of model detail permitting much of the watershed to be modeled with a low-resolution mesh and more detail to be added where deemed appropriate. Basin wide two-dimensional hydraulic modeling is necessary to use the rain-on-grid modeling approach. The selection of a full 2D hydraulic model invests in the technology to improve the state of the practice for flood risk analysis and is adaptable to accept new datasets or changing conditions.

### Rationale for why the other options were not selected

Not performing hydraulic modeling fails to describe the flood risk through mapping and flood impact analysis.

One-dimensional modeling has the capability to model fluvial flood risk, but it fails to model pluvial risk and model results are limited to only those reaches explicitly modeled. Modeling of levee failure is difficult with this approach, some flood hazards are not 1D. This is the state of the practice for the National Flood Insurance Program (NFIP) and is considered more efficient in terms of model development cost.

Combined 1D/2D modeling allows for modeling of levee failures and developing fluvial risk; however, this modeling approach is less adaptable to accepting new datasets, creates challenges in developing boundary conditions to model pluvial risk, and is less stable in a stochastic modeling environment.

## Hydraulic Modeling Platform

A specific modeling platform must be selected to develop the pilot studies. This allows for the focus of the pilot study to be on the FFRD general methodology without developing specific integration techniques for multiple modeling platforms.

### Options available

- GSSHA

- TUFLOW

- MIKE-SHE

- HEC-RAS.

### Selection and rationale

To demonstrate the capability to produce the envisioned FFRD model via pilot projects, HEC-RAS is being applied for hydraulic modeling. HEC-RAS is a license-free software and an industry standard for hydraulic modeling. The USACE and FEMA teams have direct access to the HEC-RAS development team that is responsive to FFRD program needs as the pilot models are developed. At a future date, the capability for alternative hydraulic model plug-ins may be added.

### Rationale for why the other options were not selected

Other hydraulic modeling options available may require licensing, USACE and FEMA teams lack significant experience in their use, and/or direct access to modify model capabilities to meet FFRD needs is not readily available.

## Hydraulic Modeling Software Version Selection

A consistent hydraulic modeling software version must be selected to integrate the separate hydraulic modeling units into a combined HUC-model for stochastic simulation in a cloud environment.

### Options available

- Non-HEC Hydraulic Modeling Software

- HEC-2

- HEC-RAS v6.x (and earlier)

- RAS 2025.

### Selection and rationale

HEC-RAS v6.x (generally 6.3.1 and later) will be specified for each pilot study. HEC-RAS versions 6.3.1 and 6.5 meet the requirements to perform the cloud compute simulations. The FFRD PDT anticipates enhanced capabilities for improving FFRD 2D modeling with additional version releases in the HEC-RAS 6.x series. HEC-RAS is license free, well supported, and one of the industry standards in the hydraulic modeling industry. FEMA and USACE are currently making investments in HEC-RAS and RAS 2025 aligned with FFRD program goals.

### Rationale for why the other options were not selected

HEC-2 and HEC-RASv5.x and earlier are outdated modeling software either not having 2D modeling capability or lacking features needed to efficiently build and simulate the 2D stochastic model.

RAS 2025 is anticipated to provide several new features to improve the development of FFRD 2D models, but this software is currently under development and not available for production use.

Most non-HEC software that could meet the needs for FFRD requires a license that may be a barrier for some SLTT partners to fully access the data. These options would not take advantage of the FFRD-focused direct investments being made to the HEC-RAS line of software. Note the option of allowing plug-ins for other software to work within the FFRD cloud-based tools is envisioned for the future.

## Background Mesh Resolution

The background mesh of a 2D model is the initial cell size used to develop the computational grid. Generally, this represents the largest cell size within the 2D area. Mesh refinements are strategically incorporated in areas where additional model resolution is warranted. The background mesh and refined mesh cell sizes are a function of model performance (the ability of the model to reproduce observed data), model efficiency (total run time), and model stability (Courant condition).

### Options available

- Specify a background mesh for all models for consistency

- Provide general guidance while allowing for professional judgement

- Allow model developer’s experience to define cell resolution.

### Selection and rationale

Providing general guidance on background mesh resolution while still allowing for professional judgement allows model developers to tailor each 2D model to the terrain of the watershed while still having some general consistency that the background mesh will be within a specified range. Mesh refinement investigations to better understand how the background mesh resolution was completed and results for selection of cell size are detailed in the SOP. Professional judgement can be used to refine SOP guidance for background mesh resolution.

### Rationale for why the other options were not selected

Specifying a single background mesh resolution for all FFRD models was considered. It does not balance the need for computational accuracy with the time required to produce that result. The concern is that being too prescriptive does not allow for professional judgement in model development, does not consider the heterogeneity of watersheds, and may result in model execution times that are an unnecessary computational burden. The value of a consistent background mesh is recognized. General guidance on cell size and model execution time is intended to bridge the gap between model consistency and model performance.

Providing no background mesh resolution guidance and allowing a model developer’s experience to define cell sizes is not a viable option. The resulting models from this option would likely result in inconsistent mesh development within a watershed or between watersheds. Pilot studies and continued FFRD model development afford the opportunity to provide general guidance based on lessons learned from previous models.

## Refined Mesh Resolution—Streams

Key streams and secondary streams within a modeling unit are identified in the project planning phase as areas of interest where characterizing flood risk is a priority within the basin. The following options were considered in ensuring the flood risk is adequately characterized at these locations.

### Options available

- Model key and secondary streams with the background mesh resolution

- Model key streams and secondary streams with a specified refined cell resolution for consistency between basins

- Model key streams and secondary streams with a refined cell resolution based on general guidance while allowing for professional judgement

- Model the entire watershed with a detailed mesh resolution.

### Selection and rationale

Modeling key and secondary streams with a refined cell resolution allows for the incorporation of additional detail into the model (e.g., cell faces perpendicular to flow, hydraulic feature alignments, floodplain features, etc.) to adequately compute hydraulics in key areas of the model while maintaining an efficient model (total run time) within the stochastic modeling framework. Providing general guidance while still allowing for professional judgement allows model developers to tailor each 2D model to the terrain of the watershed while maintaining some general consistency that the refined mesh will be within a specified range. Mesh refinement investigations to better understand how the background mesh resolution was completed and results for selection of cell size are detailed in the SOP. Professional judgement can be used to refine SOP guidance for background mesh resolution.

### Rationale for why the other options were not selected

Modeling key and secondary streams with the background mesh is too coarse for a 2D model. Representing hydraulic structures such as levees, roadway embankments, or other features requires a smaller cell size to adequately represent their alignment.

Modeling the entire watershed with a detailed model resolution adequate for the key and secondary streams was considered, but the model execution time within the stochastic environment may be prohibitive.

Modeling key and secondary streams with a specified cell resolution for consistency throughout the basin was considered. The concern is being too prescriptive does not allow for professional judgement in model development, does not consider the heterogeneity of watersheds, and may result in model execution times that are an unnecessary computational burden.

## Refined Mesh Resolution—Developed Areas

Developed areas within a modeling unit are identified in the project planning phase as areas of interest where characterizing pluvial and fluvial flood risk is a priority within the basin. Mesh refinements are strategically incorporated in areas where additional model resolution is warranted. The developed areas mesh and refined mesh cell sizes are a function of model performance (the ability of the model to reproduce observed data), model efficiency (total run time), and model stability (Courant condition). Techniques to model storm sewers and other urban drainage features are somewhat limited within the selected software and this specific topic is discussed in separate sections.

### Options available

- Model the entire basin with the background mesh resolution, regardless of level of development

- Model developed areas with a specified refined cell resolution for consistency between basins

- Model developed areas with a refined cell resolution based on general guidance while allowing for professional judgement

- Model the entire watershed with a detailed mesh resolution.

### Selection and rationale

Modeling developed areas with a refined cell resolution allows for the incorporation of additional detail into the model (e.g., hydraulic feature alignments, floodplain features, etc.) to compute hydraulics within the develop areas and areas with flood hazard definitions of the model while maintaining an efficient model (total run time) within the stochastic modeling framework. General consistency between basins is maintained. Mesh refinement investigations to better understand how the background mesh resolution was completed and results for selection of cell size are detailed in the SOP. Professional judgement can be used to refine SOP guidance for background mesh resolution.

While refined mesh resolution is required, mapping pluvial flooding remains an issue due to challenges in modeling urban storm drainage systems within a large watershed scale model.

### Rationale for why the other options were not selected

Modeling key developed areas with the background mesh is too coarse for a 2D model. Representing hydraulic structures such as levees, roadway embankments, or other features requires a smaller cell size to adequately represent their alignment. While urban drainage modeling techniques are still being explored, additional cell refinement in urban areas is needed to model pluvial flooding.

Modeling the entire watershed with a detailed model resolution adequate for developed areas was considered. Every model unit has unique combinations of developed areas combined with flood hazard areas requiring varying levels or resolution to achieve the highest levels of accuracy while maintaining reasonable model runtimes.

Modeling developed areas with a specified cell resolution for consistency throughout the basin was considered. The concern is that being too prescriptive does not allow for professional judgement in model development, does not consider the heterogeneity of watersheds, and may result in model execution times that are an unnecessary computational burden.

## Hydraulic Model Runtime Constraints

FFRD methodology leverages multiple models across the hydrologic cycle and across the spatial domain of a watershed. To achieve this modeling approach, models are computed many times for many events to create a graduated view of hazard and risk. The most computationally intensive model within the framework is the 2D hydraulic model. Large scale 2D models can take up to more than 24 hours for a single model run based on a review of FEMA provided 2D BLE models within the Kanawha River Basin. To ensure the FFRD Monte Carlo analysis is affordable and can be executed on schedule, hydraulic model runtime constraints are necessary.

### Options available

- Unconstrained model runtime

- Model runtime targets with consideration given to longer runtimes if warranted

- Strict specified model runtime.

### Selection and rationale

The SOP calls for 2D hydraulic models with a level of detail allowing them to be computationally efficient in a stochastic environment. Modeling unit runtimes should be less than 20 minutes on a typical desktop computer, but longer runtimes are acceptable if warranted. The level of hydraulic detail should be balanced with this runtime limitation.

Initially, in the development of the SOP, a 10- to 20-minute runtime target was set based on the anticipated number of hydraulic modeling unit simulations and the estimated cost of cloud compute time.

Based on the Monte Carlo simulation of the Kanawha and Duwamish river basins, the 20-minute runtime target may be able to be relaxed due to advances in computational efficiencies (cost and time) identified during the cloud compute process.

### Rationale for why the other options were not selected

An unconstrained model runtime would result in large inconsistencies between the level of detail within modeling units. Models would not be optimized for efficient solutions resulting in increases in cost and schedule for the Monte Carlo simulations. Model unit consistency is achieved through suggested mesh sizes and model runtimes while still allowing for the use of engineering judgement.

## Downstream Boundary condition influences across modeling unit boundaries

Downstream boundary conditions are important for hydraulic models. This boundary condition can be a source of model error or instability. The true stage for a given flow at the downstream end of a model is not known. Normal depth based on a single energy slope is often used for all flow rates being modeled.

### Options available

- Utilize the modeling unit boundary as the location of the downstream boundary condition

- Extend modeling downstream of the model unit boundaries to establish a boundary condition outside of the area of interest

- Develop rating curves at each downstream boundary location using a separate model.

### Selection and rationale

Hydraulic modeling units developed in coordination with the HEC-HMS model development ensure the HMS model and RAS model have coincident boundaries and the model boundaries align with the high-resolution terrain.

HEC-RAS models will be extended downstream of the model unit boundary along the primary stream channel (using engineering judgement) to a point where the boundary condition has little impact at the end of the modeling unit. Model results will be clipped to the model unit boundary for risk characterization.

### Rationale for why the other options were not selected

Within HEC-RAS, the normal depth boundary condition uses a single energy slope for all discharges. This may affect the model accuracy at the downstream end of the model, especially for dam break flows within the model.

Rating curves could be developed at each downstream boundary location for a range of flows; however, this would increase the number of hydraulic models needing developed.

## Stream Centerline Modification

The location of stream centerlines is used in the development of the 2D hydraulic model. The stream centerlines can be used to establish land cover data within the 2D mesh (e.g., assign Manning’s “n” values to a stream channel), used to establish the alignment of mesh refinement for key or secondary streams, and used as the alignment for estimated channel bathymetry.

### Options available

- Model developer digitizes all stream centerlines as needed

- Stream centerlines are based on published stream hydrography data with no modification

- Stream centerlines are based on project-specific elevation-derived hydrography (see Section 2 of this document) with as-needed modification for key and secondary streams.

### Selection and rationale

Project-specific elevation-derived hydrography is the primary source of stream centerlines for use in the development of FFRD 2D hydraulic modes. This dataset is the best estimate of the location of the centerline of the stream based on the detailed terrain used in the study. This dataset may need hand editing in areas where the water surface was represented in the terrain. Since key streams typically include estimated channel bathymetry using RAS Mapper (unless actual bathymetry is available), the centerline of the key streams should be digitized using the elevation derived hydrography as a starting point to represent the location of the channel. For secondary streams, the elevation derived hydrography is expected to be used directly to support the development of mesh refinement. These areas typically don’t require bathymetry and the elevation-derived hydrography is a good representation of the channel location within the terrain.

### Rationale for why the other options were not selected

Digitizing stream channel locations during model development is impractical. Automated tools or existing data can provide a starting point for this data.

Stream centerlines based on existing published stream hydrography data was initially used in the Kanawha River Basin pilot study. During the model development process, it was noted that this data set did not align with stream channel location in the high-resolution terrain. This resulted in assigning Manning’s “n” values for stream channels incorrectly and mesh refinement for channels being mislocated.

## Initial Conditions for Hydraulic Model

Initial condition assumptions are required to initialize the HEC-RAS model during model development and calibration. Initial conditions in the model include flow in the stream channel, reservoir elevations, farm ponds elevations, and filling other depressions within the watershed.

### Options available

- Initialize the model completely dry

- Utilize a combination of initial conditions points and model warm-up time to establish flow in the channel

- Apply excess precipitation to the mesh and generate a restart file.

### Selection and rationale

In establishing the initial conditions for a modeling unit, consideration is given to using the warm-up time at the beginning of the model to prime the stream channels. The first timestep of the baseflow file is used within the model during the warm-up period. This technique only sets initial flow within channel locations downstream of baseflow locations. Small stream channels are not primed, and pre-event conditions are not as well represented with this technique. Initial condition points are used to set the initial water surface at a specific model location, such as behind a dam. These points should set the water surface based on observed data at the beginning of the simulation. Without available observed data, professional judgement is expected to be used. Each modeling unit is different, and judgment is required to identify the best modeling technique to establish initial conditions.

### Rationale for why the other options were not selected

The restart file is convenient during model development and calibration. It allows for establishing initial flow within all stream channels in the watershed and it fills depressions and low areas within the terrain contributing to runoff storage previously accounted for in the hydrology model. The restart file is not convenient for use in the Monte Carlo analysis. With this modeling technique, each HEC-RAS Monte Carlo simulation requires running the HEC-RAS model to generate a new restart file to establish the appropriate antecedent reservoir elevation. Additionally, if rainfall is used to fill depressions, this could mask or compound fluvial risk through ponding of runoff at the start of the simulation. This is especially true for the difficult to model urban areas with urban storm drainage systems.

The restart file method is an option in the SOP, but it should only be used if specific conditions warrant it.

## Terrain Modifications for Buildings

Buidlings, homes, and other structures are of particular interest in the FFRD program. These structures (along with brush/trees/crops) are removed from the bare-earth DEM used in the hydraulic model development.

### Options available

- Develop FFRD models and results based on the bare-earth DEM

- Raise the terrain within building footprints.

### Selection and rationale

Maintaining a bare-earth DEM is the best choice for alignment with consequence estimation. Hydraulic modeling uses increased Manning’s “n” values based on published landcover data to represent the reduction in conveyance through developed areas. Consequence estimates rely on the foundation elevation at the point location of each structure to establish damage functions based on depth and/or velocity.

### Rationale for why the other options were not selected

Raising the terrain within building footprints occludes inundation of building centroids, which doesn’t work well with the selected consequences modeling approach (i.e., assume building is adequately represented by a point).

## Terrain Modifications for Streams

The best available bare-earth DEM is used in the development of the 2D HEC-RAS model. This data is often LiDAR data including the water surface elevation of streams and lakes at the time of the survey. In some instances, data may need to be supplemented with lower resolution DEM data. These areas may require terrain modification to resolve elevation differences at seams, incorporate channel/reservoir bathymetry, remove bridges from the terrain, or other necessary modifications to model flow with the modeling unit.

### Options available

- Accept the terrain as-is with no modification

- Incorporate bathymetric/sediment surveys

- Estimate stream bathymetry using reported flow-stage rating curves, depths, and/or assumed shapes.

### Selection and rationale

Bathymetry from existing USACE CWMS or FEMA HEC-RAS models (or other locally readily available georeferenced models) should be incorporated when available. Key streams require incorporation of bathymetry into the DEM using an existing bathymetry DEM based on survey data, a terrain file generated from an existing HEC-RAS model, or an estimated bathymetry using RAS Mapper terrain modification tools. When surveyed bathymetry is not available for incorporation into the terrain, channel bathymetry is estimated for the key streams by incorporating a channel into the terrain. Aerial photography and the existing terrain are used to estimate the side slope and bottom width of the channel. Existing FIS profiles and existing stream gage rating curves (https://waterwatch.usgs.gov/index.php?id=mkrc) are used to estimate the channel invert. This information is used with engineering judgement to estimate channel bathymetry along a reach. Model development requires iterating between channel bathymetry (width/depth/slope) and model calibration.

### Rationale for why the other options were not selected

Accepting the terrain as-is with no modification results in hydraulic models having un-realistic parameters to account for data not representative of the underlying terrain.

## Terrain Modifications for Reservoirs

Terrain modifications are required for 2D internal connections used to represent dams within the mesh. The water surface behind the dam is often captured in the high-resolution terrain.

### Options available

- Do nothing

- Incorporate bathymetric/sediment surveys

- Estimate reservoir bathymetry using reported storage volumes and assumed shapes.

### Selection and rationale

Incorporating surveyed bathymetry behind the dam is the preferred modeling technique. This improves model stability and ensures dam breaks can be evaluated in the model when necessary. In many instances, bathymetry data is available for USACE dams, but for dams without available bathymetry, an estimate of the channel and floodplain within the reservoir will be included using available RAS Mapper tools. Comparison with limited data in the NID can be used to develop the estimated bathymetry. Reservoirs not requiring breaching may not need estimated bathymetry.

> *reservoir bathymetry, which must be captured within the HEC-RAS terrain model to accurately represent the storage volume of a lake. This volume is particularly important to represent in hydraulic modeling for reservoirs which will be breached as part of FFRD simulations. LiDAR based DEMs often include the water surface itself as part of the terrain model, and therefore neglect any water storage volume which was present during the LiDAR collection. For reservoirs and impoundments which will <u>not</u> be breached, this underrepresentation of storage in LiDAR DEMs is not significant, as this volume can be considered dead-storage and does not significantly impact hydraulic simulations. There can be exceptions to this, such as when the LiDAR based terrain does not accurately represent normal reservoir storage, or in cases where reservoirs are particularly long and in-reservoir routing effects become significant. In the case when an impoundment is breached, all volume within that reservoir above the breach invert is available to flow downstream, this includes the dead-storage which may not be represented in the terrain model. The volume of this dead-storage can be significant and can influence dam breach risk for communities downstream, it must therefore be represented for breachable reservoirs in FFRD RAS models (Breachable structures are currently defined as structures above 5,000 acre-feet).*
>
> *There are many sources of bathymetric data and techniques to incorporate that data into hydraulic models. Complexity and level-of-effort for gathering this data and incorporating it into models varies, as does its accuracy. Large reservoirs with significant potential for dam breach risk merit more detail and effort in comparison to small reservoirs such as stormwater retention ponds.*
>
> *Typically, the hydrologic and reservoir operations models use the best available elevation-storage data available for a reservoir – often the data found in water control manuals or more recent survey data. If the HEC-RAS modelers source other reservoir bathymetry information or develop a more detailed model of the reservoir bathymetry, they shall provide their calculations of the elevation-storage relationship to the HEC-HMS and HEC-ResSim modelers for consistency.*

### Rationale for why the other options were not selected

Not including bathymetry mis-represents the volume in the reservoir when evaluating the effects of a dam breach on flood risk.

## Terrain Modifications for Small Dams—Outlet Works

For small dams (i.e., NRCS dams and local impoundments and/or smaller than 5-000 acre foot storage volume) lacking operational information, there is a need to simulate discharage for small events.

### Options available

- Do nothing

- Develop a rating curve for the outlet works

- Include a 0.8-foot notched terrain modification in the structure.

### Selection and rationale

Allows simulation of project discharges for small events. The width of 0.8 foot was based on testing during the FFRD Small Dams investigation. The Small Dams Investigation Report will provide further details.

### Rationale for why the other options were not selected

Not doing anything reduces flows downstream impacting calibration. Developing a rating curve is not cost effective or efficient. Rating curve information is not readily available for a dam using this process.

## Rendering Mode (Consequences)

There are a variety of methods for displaying 2D hydraulic outputs on a map, and each method results in a unique interpretation of depths at structures.

### Options available

- Use coordinated approaches for depth map display, hazard map display, and consequence calculations at structures

- Allow some deviation of methods for each use case.

### Selection and rationale

As of Fall 2024, the FFRD mapping tools and consequence calculation tools are not fully mature.

### Rationale for why the other options were not selected

As of Fall 2024, the FFRD mapping tools and consequence calculation tools are not fully mature.

## Reservoir Representation within the Hydraulic Model

Dam and reservoirs within a 2D HEC-RAS model can be represented in multiple ways depending on the type of reservoir and intent of the modeling effort. The dam and reservoir modeling scheme in the hydraulic model must work in concert with the hydrologic model and reservoir operations model in terms of flood routing and possible breaches.

### Options available

- Ignore dams within a modeling unit

- Model all dams within a modeling unit as a hydraulic structure

- Model all dams within a modeling unit with a breakline

- A combination of the available options.

### Selection and rationale

Reservoirs are represented within the hydraulic model using a combination of multiple techniques.

All dams operated for flood storage are included in the reservoir operations model. For these dams, the hydraulic model represents the structure with a 2D connection/hydraulic structure with a very high weir crest paired with an outlet time series fed from reservoir release simulation outputs.

Due to the number of other dams within a modeling unit, it is impractical to model all structures. All high hazard dams with greater than 5,000 acre-feet of maximum storage are included in the 2D mesh as a hydraulic structure. This allows for breaching of these dams to be considered in the Monte Carlo analysis. Smaller dams may be modeled using breaklines, hydraulic structures, or other techniques when needed to meet calibration targets. Smaller dams not meeting the requirements to be in the NID are generally ignored unless located on a key or secondary stream as defined in Section 2.

As of August 2024, there is an ongoing investigation to consider the impacts of modeling (or not modeling) NID dams within a watershed. One challenge with these types of structures is obtaining the principal spillway/outlet works rating curve and other necessary data needed to represent the structure.

### Rationale for why the other options were not selected

Ignoring dams within a modeling unit does not meet the FFRD requirement to illustrate the impact of reservoir regulation and failure potential on flooding within a watershed.

Detailed modeling of all dams within a modeling unit is impractical due to data limitations. Some dams within a watershed do not contribute significantly to the flood risk within a watershed.

## Levee Representation within the Hydraulic Model

Levees within a 2D HEC-RAS model can be represented in multiple ways depending on the information available and intent of the modeling effort. Levee data in FFRD models is taken directly from the NLD.

### Options available

- Ignore levees within a modeling unit

- Model all levees within a modeling unit as a hydraulic structure

- Model all levees within a modeling unit with a breakline

- A combination of the options available.

### Selection and rationale

All FFRD hydraulic models require inclusion of levee data exactly as it is represented in the NLD. All NLD levees within a modeling unit are modeled as hydraulic structures and consideration is given to potential breaching within the Monte Carlo analysis. Levees are modeled assuming all closures are in place.

### Rationale for why the other options were not selected

Ignoring levees within a modeling unit does not meet the FFRD requirement to illustrate the impact of levee capacity and failure potential on flooding within a watershed.

Detailed modeling of all levees within a modeling unit is impractical due to data limitations.

## Downstream coastal boundary conditions

For modeling units located in coastal regions, the hydraulic model requires a downstream boundary condition representing the tidal influence.

### Options available

- Ignore the tidal influence and use normal depth with a flat slope energy grade line

- Model the tidal influence as a constant water surface throughout the duration of the simulation (e.g., men high water \[MHW\], mean tide level (MTL), mean low water \[MLW\])

- Model the tidal influence using observed tidal stages during calibration.

### Selection and rationale

Normal depth is generally used for models with typical riverine characteristics at the downstream boundary. For areas affected by tidal influences, the downstream boundary condition is observed tidal data. In instances where observed tidal data for a particular event is unavailable, a similar tidal pattern from a nearby gage or another historic event is substituted.

### Rationale for why the other options were not selected

Alternate methods misrepresent the effects of the tide on the hydraulics within the modeling unit.

## Model Calibration and Validation

Model calibration and validation is a critical part of determining the accuracy and confidence of the modeling. Calibration is performed on historical events in the basin allowing backwater computation parameters estimation for a full range of storm events. Validation of the backwater parameters developed during calibration provides a test of the parameters to determine the confidence in the modeling for a full range of storm events.

### Options available

- Validation based on peak discharges. A measure of how well the parameters match the observed peak discharge at gages in the basin with measured data.

- Validate based on peak water surface. A measure of how well the parameters match the observed peak water surface at gages in the basin with measured data.

- Conforming to observed data based on time series from the entire storm. This is a measure of how well the parameters match the full event, including the rising limb, peak, and recession of the event. This measure evaluates the ability to match observed data for a wide range of flows and water surfaces leading up to the peak.

### Selection and rationale

Conforming to observed data based on time series from the entire storm. This rationale is necessary for calibration and validation because the model is intended accurately compute flow and water surface for a full range of discharges.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Other Hydraulic Feature Representation within the Hydraulic Model

Other hydraulic features (not dams or levees) affect the hydraulics within a modeling unit. The features include non-accredited levees, diversions, canal embankments, saltwater barriers, bridges, roadway embankments, etc. The number of these types of features can be great and they can be represented within a 2D HEC-RAS model in multiple ways.

### Options available

- Ignore all hydraulic structures other than dams or levees

- Model all hydraulic structures within a modeling unit as a hydraulic structure

- Model all hydraulic structures within a modeling unit with a breakline and terrain modifications

- A combination of the options available.

### Selection and rationale

These features are added to the HEC-RAS model based on professional judgement in meeting the objectives of the FFRD model while taking care to balance model runtime with model detail.

Key hydraulic structures associated with transportation features significantly impacting flood risk in populated areas are included in the 2D mesh. These features (i.e., bridges, roadway embankments, etc.) are modeled as breaklines and/or terrain modification (not internal 2D connections). The terrain modification for these features includes creating an opening through a roadway embankment approximately the size of the culvert being modeled or removing a bridge deck from the terrain. Transportation features in the background mesh are of lower priority and may not be modeled due to the large mesh size. Other unique hydraulic features are included using professional judgement.

### Rationale for why the other options were not selected

Due to the number of bridges and culverts within a modeling unit, it is impractical to model each culvert or bridge within HEC-RAS. This adds computational burden to the model and increase model runtime.

## Urban Drainage

In many developed areas having interest in pluvial flood risk, surface runoff is conveyed to a subsurface drainage system and conveyed to an outfall within a nearby stream. The hydraulic modeling of runoff in these areas at a watershed level is challenging.

### Options available

- Model external to HEC-RAS

- U.S. Environmental Protection Agency (EPA) Storm Water Management Model (SWMM)

- HydroCAD

- Model open channel drainage ignoring subsurface urban drainage

- Utilize other integrated hydraulic modeling software

- MIKE+ and SWMM.

### Selection and rationale

The first three pilots are using the draft SOP calling for adding an increased level of HEC-RAS modeling detail in developed areas having a structure density above a specified threshold. The level of detail of modeling in those areas is left to professional judgement of the modeler, but modeling of the urban drainage network is generally limited to surface drainage features.

As of September 2024, the FFRD SOP calls for accounting for all major surface water drainage (ditches, canals, etc.) for developed areas directly in the HEC-RAS model. The software applied has limited tools available to model subsurface drainage and input data required for urban drainage networks is sparse. It is a recognized weakness in the modeling approach that surface flooding in developed areas may be over-estimated due to lack of urban drainage modeling, and solutions will be sought in the future.

### Rationale for why the other options were not selected

Selected option is the most expedient at the current time.

## Interior Drainage

The conveyance of interior runoff through or over levees is an important aspect of flooding within leveed areas. Levee systems commonly have associated culverts, gates, or pump stations for reducing flooding within the leveed area.

### Options available

- Ignore interior drainage features and allow runoff to pond behind levees

- Include culverts with flap gates through the levee based on readily available data or estimates from aerials/photographs

- Locate as-built data and operational manuals for each levee and include the operation of pumps and culverts within the HEC-RAS model.

### Selection and rationale

Applying engineering judgement, include culverts/pumps having a significant effect on the inundation in the leveed area in the model geometry. Approximate the locations and sizes of the culverts through the levee using data found in the NLD. If data is unavailable, use estimates from aerials and photos. The behavior of the culvert is modeled as a flap gate or other appropriate assumption to best represent the levee. Details on the interior drainage of levees are a challenge due to limited data readily available. Inclusion or exclusion of interior drainage features in the model is discussed in the hydraulic model report and features included are tabulated.

### Rationale for why the other options were not selected

The FFRD PDT determined locating as-built data and operational manuals for each levee and including the operation of pumps and culverts within the HEC-RAS model to be more suited for specific detailed studies and outside of the scope of watershed level hydraulic modeling.

## Terrain Modification—Hydraulic Structures

Hydraulic structures modeled with breaklines, do not include culvert, bridge opening, or conduit in the model since the breakline only captures the terrain surface. Representing flow within the modeling unit requires conveyance through the terrain

### Options available

- No terrain modification for hydraulic structures

- Modify the terrain to allow flow to pass through the structure

- Model all hydraulic features as hydraulic structures with conduits or computed rating curves.

### Selection and rationale

Hydraulic structures modeled as breaklines require modification of the underlying terrain allowing flow to pass through the structure. This is accomplished with the RAS Mapper ground line editor tools to lower the terrain across the feature based on the estimated size of the culvert or bridge opening. The result is a channel through the roadway embankment.

### Rationale for why the other options were not selected

If no terrain modification is performed, unrealistic damming effects occur within the model.

Modeling all hydraulic features as hydraulic structures with conduits or computed rating curves is considered impractical for a watershed level study with the intent of developing hydraulic models with runtimes suitable for Monte Carlo analysis. Watershed level data sources of bridge/culvert details are not available.

## Defining Downstream Boundary Condition for Non-coastal Hydrologic Unit Code 4 Basins

HEC-RAS requires a downstream boundary condition for all modeling units. The most downstream modeling unit in a HUC-4 basin will requires either a coastal boundary condition, connection with a downstream HUC-4 basin, or connection of an adjacent HUC-4 basin near the confluence with another major waterway. In instances where the downstream boundary condition of a HUC-4 basin model connects to a another HUC-4 basin, capturing the effects of the flow uncertainty in the adjacent HUC-4 basin is necessary to characterize flood risk.

### Options available

- Constant downstream stage for all events

- Variable downstream stage based on observed data

- Normal downstream depth.

### Selection and rationale

A decision on the best available option has not been made. Assumptions were made during Kanawha River Basin Pilot study to sample a stage on the Ohio River from a distribution in HEC-ResSim during stochastic simulation, but this process may not be repeated for future basins.

### Rationale for why the other options were not selected

To be determined.

## Selection and Definition of Uncertainty Parameters 

The FFRD Monte Carlo analysis samples parameter uncertainty within the hydrologic cycle. Some parameters affecting the watershed hydraulics are sampled within other models and applied to the 2D HEC-RAS model in the Monte Carlo simulations (reservoir starting elevation, rainfall excess intensity, initial channel flow conditions, etc.). Other model parameters can be a source of uncertainty.

### Options available

- No sampling of uncertainty within the 2D HEC-RAS model

- Manning’s “n” values.

### Selection and rationale

As of August 2024, FFRD methodology does not include sampling of uncertainty within the 2D HEC-RAS model. Antecedent reservoir starting elevation is sampled and applied to the 2D HEC-RAS model. Initial flow in the HEC streams is sourced only from the first ordinate of the HEC-HMS baseflow hydrographs. Variation of Manning’s “n” values is not performed. As the FFRD process matures, consideration will be given to varying hydraulic parameters.

### Rationale for why the other options were not selected

Consideration was given to developing multiple 2D HEC-RAS geometries with varying Manning’s “n” values for use in the Monte Carlo analysis. Manning’s “n” values within a rain-on-mesh environment are not significantly research and the variability in “n” values for this application is not well understood. This approach also adds another level of complexity to the Monte Carlo analysis. As of August 2024, uncertainty is represented by storm position, intensity, total rainfall, and antecedent watershed conditions. As the FFRD process matures with improvements to the process and HEC-RAS, uncertainty in channel hydraulics will be given further consideration.

## Specification of Manning’s “n” (Overland versus Channel)

Manning’s “n” values within a rain-on-mesh environment are not significantly research and the variability in “n” values for this application is not well understood.

### Options available

- Allow model developers to calibrate 2D HEC-RAS models using Manning’s “n” values at their own discretion

- Assign specific Manning’s “n” values for each land cover type in the NLCD

- Provide a general guide for the assignment of Manning’s “n” values based on land cover type in the NLCD

- Specify a requirement for separate overland flow and channel flow Manning’s “n” values.

### Selection and rationale

The minimum standard for varying Manning’s “n” values is the 2019 NLCD dataset. A general guide for the assignment of Manning’s “n” values based on land cover is provided. This guide is based on channel “n” values. Multiple zones of the Land Cover Layer may be utilized to generate Manning’s “n” values for floodplains separately from upland/overland flow areas; however, models calibrated for the Kanawha and Trinity river basins show adequate calibration can be achieved by utilizing channel “n” values throughout the basin. While shallow, overland flow Manning's “n” values are expected to be higher than channel “n” values due to the higher relative roughness, runoff throughout the basin is presumed to be dominated by concentrated or channelized flow. Additional research on this topic could be a benefit.

### Rationale for why the other options were not selected

Overly prescriptive Manning’s “n” values take away a model calibration mechanism and do not account for the heterogeneity of different watersheds.

Specifying a requirement for separate overland flow and channel flow Manning’s “n” values was considered, but model calibration has not required this approach as of August 2024.

## Selection of Equation Set

HEC-RAS can perform two-dimensional unsteady flow computations using multiple equation sets used to solve for flow moving over the computational mesh. The computational equations vary in accuracy (depending on flow conditions), stability, and computation time-step requirements.

### Options available

- Diffusion Wave

- Shallow Water Equation, Local Inertia Approximation (SWE-LIA)

- Shallow Water Equation, Eulerian-Langrangian Method (SWE-ELM)

- Shallow Water Equation, Eulerian Method (SWE-EM)

- Modeler-selected based on ability to calibrate to historic events.

### Selection and rational

The diffusion wave equation set is preferrable due to its stability and decreased model runtime requirement; however, model performance should be compared with the SWE-ELM and SWE-LIA 2D equations. If a significant difference is observed between the diffusion wave and shallow water equations, model development should focus on developing a calibrated model using the shallow water 2D equations with the least computational burden. If both shallow water 2D equations have significant difference, SWE-ELM should be used.

The decision for the equation set is based on the calibrated events. Future efforts to evaluate this decision on more extreme events will be considered in the SOP.

### Rationale for why the other options were not selected

The decision on which equation set to use is left to professional engineering judgement. Specifying a single equation set does not consider the heterogeneity of watersheds. The SWE-EM was not considered because it is typically only needed when users are interested in taking a very close look at changes in water surfaces and velocities at and around hydraulic structures, piers/abutments, and tight contractions and expansions. This level of detail is not needed for this effort for these structures and this equation set provides an increased computational burden for little additional value.

## Computational Tolerances/Model Performance

HEC-RAS iterates using unsteady flow equations to solve for flow within the mesh. If the solution of the equations gives a numerical answer having greater numerical error than the set tolerance, the program iterates to get a better answer. Volume and water surface numerical error is checked for each solution. HEC-RAS reports volume error and number of iterations and allows for adjustment to the computational tolerances. Adequate model performance can be subjective.

### Options available

- Specify the computational tolerances to be used in the 2D HEC-RAS model

- Specify a maximum allowable numerical error

- Specify a maximum allowable number of iterations

- Allow the model developer (and review process) to determine whether the model results are acceptable based on professional engineering judgement.

### Selection and rationale

The model developer and the review process determine if the model tolerances, number of iterations, and numerical error meet the objectives of the FFRD process. Models should compute all scenarios with minimal computational error. The acceptable level of computational error is relative to the specifics of the project modeled.

### Rationale for why the other options were not selected

The FFRD SOP relies on existing best practices within the modeling community of practice. Therefore, specific tolerances are not detailed within the SOP.

# —Dam and Levee Breaching

The fiscal year (FY) 2024 decision to embark on multiple concurrent investigations impacts delivery of the Duwamish River Basin Pilot study as the investigations occur in parallel with the completion of the pilot basin. While the investigations evaluate various options, the Duwamish River Basin Pilot study will move forward with the best scale as currently understood by the team. The completion of the basin cannot be delayed until the results of investigations are complete.

For the Duwamish River Basin Pilot study, all levee systems have a single breach location and a combined system response curve, and two breach locations representing incipient overtopping and a separate critical prior-to-overtopping breach location with the exception of the Tukwila Levee, which has a higher-level risk assessment. This represents a simple basin setup with proof-of-concept complexity added to Tukwila to show the possibility of maximizing available data to improve the residual risk mapping. The system response curve development ensures the length effect is not skewing the total annual probability of failure for the system. This pilot scale demonstrates levee breaches can be incorporated into the FFRD modeling framework and models can support multiple levee breach locations per levee system if that is determined to be advantageous through the planned investigations.

The Duwamish River pilot also includes possible breaches of Howard Hanson Dam utilizing a representative breach location and the system response probability sourced from the existing USACE risk assessment of the structure.

The following features are being incorporated into the Duwamish River Basin pilot.

- Dams

<!-- -->

- Incorporation:

<!-- -->

- All dam crest profiles available in the NID are included in the model. Gate operations are modeled only for Howard Hansen Dam.

<!-- -->

- Breach Locations:

<!-- -->

- Only Howard Hanson Dam will be breached.

<!-- -->

- System Response:

<!-- -->

- Results from a USACE Risk Assessment (RA) are synthesized into a single system response probability curve.

<!-- -->

- Breach Parameters:

<!-- -->

- Regression equations typically used present a small challenge because sizes are not computed on-the-fly for different event conditions. This pilot uses the Simplified Physical breach method mimicking regression results.

<!-- -->

- Levees

<!-- -->

- Incorporation:

<!-- -->

- Crest profiles of all levees in the NLD are included in the hydraulic model.

<!-- -->

- Breach Locations:

<!-- -->

- Quantitative Risk Assessment/Semi-quantitative Risk Assessment (QRA/SQRA) exists: Breach at the incipient overtopping location and a combined potential failure mode (PFM) specific critical prior-to-overtopping breach location.

- Levee Screening Tool (LST) 1.0 exists: Breach at each system with the FFRD modeling team selecting the locations.

- Other systems: Breach all systems with the modeling team selecting the locations.

- Note: No LST 2.0 risk assessments exist for this basin. LST 2.0 improves understanding of critical breach locations not readily queriable from LST 1.0.

<!-- -->

- Fragility:

<!-- -->

- QRA/SQRA Levees: Directly from the RA

- LST 1.0 Exists: Summed system response probability (SRP) for each segment from the LST

- Others: Use a default SRP selected by the FFRD PDT for demonstration purposes.

<!-- -->

- Breach Parameters:

<!-- -->

- Simplified Physical RAS method.

## Residual Risk Mapping

A decision will be made on the appropriate representation of dam and levee performance for residual risk mapping. Variables including the number of breaches and breach location selection sensitivity need to be weighed against available supporting data and model complexity. Investigations scoped and planned to begin in calendar year 2024 to inform this decision.

### Options available

- Model only overtopping

- Use alternative methods outside of FFRD products such as the LST, Dam Screening Tool (DST), or Higher Level Risk Assessment (HLRA) to describe residual risk of infrastructure failure.

- Pre-run fixed elevations, store them, and perform k-nearest neighbors (kNN) runs

- Incorporate infrastructure-specific breach locations and SRP curve sampling within the HEC-RAS modeling approach; sampling SRP curves independently per location per event.

### Selection and rationale

Sampling of SRP curves per location per event reduces assumptions, fully accounts for interactions of dam and levee breaches having residual flooding within a watershed and represents the residual risk and uncertainty in dam and levee breaches.

### Rationale for why the other options were not selected

If only overtopping is modeled using alternative methods to describe the residual risk, the modeling does not meet the BW-12 requirements directly and integrating the outputs from other methods is complicated.

Using pre-run fixed elevations, storing them, and performing kNN runs is prone to error, complicated to design, and could misrepresent the system interaction.

## Development of System Response Curves for Dams

For any dam breached, the model needs to represent a system response curve including the probability of breach given a hazard.

### Options available

- Derived from risk assessments.

<!-- -->

- HLRA

- Derive from lower-level risk assessments.

<!-- -->

- Assume a default

<!-- -->

- Ongoing DST research and development

- Use levee incident database as appropriate.

### Selection and rationale

Derivation from risk assessments is the best option with the highest level of analysis but is not available everywhere. This option is used when available.

When an SRP cannot be derived from a risk assessment, a default is assumed.

Non-water hazards are not considered as of August 2024 (i.e., seismic, interim construction, debris, gate operability, etc.).

### Rationale for why the other options were not selected

No other options are known to be available as of August 2024.

## Levee Reliability Modeling: Breach Location and Quantity

To breach a levee, the breach location must be defined. Because there is a significant heterogeneity in the inventory of levees across the nation, choosing a single representative breach location can have a significant impact on the quality of computed results.

### Options available

- Option 1: Maximize the use of RA data to support levee-specific citing of most critical performance areas (PFMs). Use coordinates of evaluated PFMs in HLRA or LST 2.0. For all other, use engineering judgement on breach location selection (single location) considering the incipient overtopping (OT), prioritizing upstream locations, and prioritizing tall levee sections that maximize breach inflow.

- Option 2: Simplify to a single breach location per levee segment (use incipient OT location as determined by FFRD model). SRP curve matches the segment’s annual probability of failure (APF).

- Option 3: Simplify to a single breach location per levee system (use incipient OT location as determined by FFRD model). SRP curve matches the system’s APF as combined from segment APFs.

- Option 4: Standardized approach seeking even distribution of leveed area inflow with a breach location in the upper, middle, and lower portions of the levee system. The system response curve for the system is separated into evenly likely location SRP curves.

- Option 5: Randomly sample the levee system alignment for a location and apply a single breach location. The SRP curve matches the system’s APF.

- Option 6: Standardized approach seeking to place breach locations at a rate of one per standardized unit of length (e.g., one per mile).

### Selection and rationale

The selected option is to be determined. A levee investigation is ongoing as of August 2024 to determine the selected option. The investigation tests options 1, 2, and 3.

Current professional thinking is using levee-specific information provides the best chance of representing residual risk. There is concern about the freshness of USACE RA information; for example, if the risk in a given RA is driven by an operations and maintenance (O&M) deficiency mitigated shortly after publication of the report. An SRP curve is not a direct product in most USACE RAs available for use. The process of generating an SRP curve does include assumptions on performance and loading beyond what is documented misrepresenting conditions when applied in an FFRD model.

Data and modeling limitations exist preventing representation of all conceivable levee breach scenarios. Modeling of known critical areas may not represent the unknown potential levee risks important to users of FFRD products.

### Rationale for why the other options were not selected

A levee investigation is ongoing as of August 2024 to determine the selected option. The investigation tests options 1, 2, and 3.

Option 4 was not selected because of potential for inadvertently misrepresenting levee risk. For example, a breach may be cited in a location that is robust and the SRP curve assigned does not reflect the probability of inundation.

Option 5 cannot be the selected option prior to the fully functional release of HEC-RAS 2025 due to complexities based on antiquated code. The execution of this type of alternative is expected to need a higher fidelity levee data source than currently available. Data is needed to characterize similar levee performance reaches—as opposed to breach locations—an approach not currently used in the LST. This type of modeling approach appears to have merit but does not have the data or tools to support its implementation.

Option 6 was not selected because the representation of the curve would misrepresent site-specific conditions if moved without adjustment to the SRP curve. Determining the number of breaches by unit of length leads to an arbitrary and inconsistent treatment between levee systems.

## Data Sources for Levee System Response Curves 

The representation of levee performance in the FFRD modeling requires an SRP curve indicating the likelihood of inundation given hazard. The SRP curve must be in the format of likelihood of breach given a flood loading elevation for a specific breach location.

For the proposed SRP curve development option maximizing USACE levee data, there are various data sources that can be considered.

### Options available

- USACE HLRA

- Screening Level RA

<!-- -->

- LST (v1.0)

- LST (current)

<!-- -->

- USACE Levee Incident Data

- Local risk assessment data submitted by a professional engineer.

### Selection and rationale

All Federal sources of risk assessment data were selected to maximize the use of levee-specific data.

### Rationale for why the other options were not selected

The local risk assessment data was not included as a data source because assessment methodology is not guaranteed to be consistent nationally or even within a basin.

## System Response Probability Curve Format

The SRP curve can be delivered with more or less granularity in the number of reference points (AEP versus P(f)). The FEMA insurance pricing approach established a 10,000 data point format in 1/n format for AEP.

### Options available

- Maintain established FEMA insurance pricing approach SRP curve format

- Simplify SRP curve data.

### Selection and rationale

Simplification of the SRP curve is the selected alternative because of ease of use without sacrificing significant detail.

Table 1.

| \#  | % Levee Height | Probability of Failure |
|:---:|:--------------:|:----------------------:|
|  1  |       0        |                        |
|  2  |      0.05      |                        |
|  3  |      0.1       |                        |
|  4  |      0.15      |                        |
|  5  |      0.2       |                        |
|  6  |      0.25      |                        |
|  7  |      0.3       |                        |
|  8  |      0.35      |                        |
|  9  |      0.4       |                        |
| 10  |      0.45      |                        |
| 11  |      0.5       |                        |
| 12  |      0.55      |                        |
| 13  |      0.6       |                        |
| 14  |      0.65      |                        |
| 15  |      0.7       |                        |
| 16  |      0.75      |                        |
| 17  |      0.8       |                        |
| 18  |      0.85      |                        |
| 19  |      0.9       |                        |
| 20  |      0.95      |                        |
| 21  |       1        |                        |

Figure 1. Comparison of Federal Emergency Management Agency Insurance Pricing Approach System Response Probability Curve with 10,000 Data Points Compared to Proposed Future of Flood Risk Data Simplified Points. (Scaled to P(f) \<0.10)

<img src="media/image1.png" style="width:6.5in;height:3.75694in" />

### Rationale for why the other options were not selected

Maintaining the FEMA Insurance Pricing format reduces efficiency without adding benefit to characterizing levee performance.

## Initial Condition Assumptions

The premise of this consideration is whether a variable project reliability should be considered due to:

- Damaged levee conditions ahead of a storm

- Breach events existing prior to the storm (earthquakes).

### Options available

- Do nothing; assume structure is operational.

- Do nothing; use risk assessment scope and evaluation to consider seismic PFMs when available only.

- Assume current day structure is not fully operational.

### Selection and rationale

Dams and levees already in a failed state is not currently being addressed in the SOP because the assumption is that post-storm rehabilitation will occur before the next significant storm event. This is a simplification of reality and should be relaxed in a way prioritized with its contribution to the overall assumptions going into the risk representation.

The coincident loading of a seismic hazard preceding a significant hydraulic loading is in many cases not a governing load case with the potential case of frequently loaded levees (tidal or other). This condition would be challenging to incorporate into FFRD modeling without a documented basis of analysis from an RA. Therefore, the proposed course of action is to account for seismic loading in FFRD only when the data is available as an evaluated PFM in an HLRA.

### Rationale for why the other options were not selected

Additional evaluation of initial condition levee or dam performance is considered to be too data intensive and limited in applicability for a national approach; out of scope.

## Overtopping Response

Levee and dam infrastructure may or may not be designed to perform during an OT event. The SRP to an overtopping event can be assumed or be system specific accounting for a depth of OT and the erosion susceptibility of the levee or dam.

### Options available

- Assume that OT leads to breach immediately once initiated. Incipient OT AEP yields a probability of failure equal to 1.0. (At AEP=crest elevation, p(f)=1.0)

- Use available risk assessment and incident data to account for project performance during OT.

### Selection and rationale

Using available information to develop a project-specific system performance during OT is the selected alternative. This alternative allows the breach elevation sampling to include a more realistic modeling of the OT with breach scenario. Maximum use of project-specific data from USACE RAs is used and supplemented by incident data where project specific information does not exist.

HRLAs typically include OT with breach as an evaluated PFM and include an SRP curve for the risk estimate computation.

LST 2.0 also has this data available.

For all other levee types, USACE levee incident data for a typical (average levee) is used. This includes data for all levee types and is not separated by USACE-authorized versus not nor is it separated by soil type.

Table 2.

|    Loading    | Probability of Breach |
|:-------------:|:---------------------:|
| OT + 0.5-foot |          57%          |
|  OT + 2-foot  |          68%          |
|  OT + 3-foot  |          76%          |

\*Source: LST Technical Manual DRAFT. Figure 129. Probability of Breach during Overtopping for Different Depths and Soil Types. “All Levees” data.

When combining SRPs, the maximum PTOT probability will be added to the elicited OT performance likelihood. This combination considers all potential failure modes at loading levels exceeding the crest elevation. For example, a levee may still fail from internal erosion during overtopping so it will be combined with likelihood of overtopping with breach; however, tailwater conditions as the leveed area fills ultimately cause the internal erosion SRP to plateau. Future potential improvement includes extending the PTOT performance beyond the crest elevation prior to combining.

In consideration of multiple levee breach locations, every location SRP will include OT with breach probability. This will model a realistic scenario in which all potential areas of overtopping have a likelihood of breaching from overtopping. USACE subject matter experts have concluded that this approach creates a situation for the model to perform its own “competing risk” calculation that minimizes a “length effect” concern. Theoretically, as the initial overtopping location begins to overtop and possibly breach, the river stage at the other breach locations is less likely to achieve an elevation needed to trigger a breach. Thus, each of the individual breach locations of a particular levee system are competing against each other for the chance to breach. Once one is successful, the probability of another occurring drops so as not to introduce “length effect” issues of the probability of failure approach 1.0.

### Rationale for why the other options were not selected

Assuming breach immediately during incipient OT is overly conservative.

## Breach Location—Dams

At a minimum, a location for the SRP curve must be defined in the middle of the original stream channel for every dam and for each appurtenant structure included in the analysis.

### Options available

- One representative SRP curve in the middle of the original stream channel per dam and per appurtenant structure in the analysis.

- One representative SRP curve per consequence zone.

- Failure mode dependent SRP curves accounting for the complexity of breach location, fragility, and breach size.

- Single breach location of main dam

- Do not breach appurtenant structures

### Selection and rationale

Selecting one representative SRP curve per structure is the most expedient option. This simplified method is expected to produce reasonable results for the majority of events.

### Rationale for why the other options were not selected

Although it would increase accuracy, failure mode dependent SRP curves and breaching of appurtenant structures increases the complexity of stochastically evaluating the breach of dams increasing time, effort, and complexity. This could be considered for future use.

## Breach Location—Levees

At a minimum, a location for the SRP curve must be defined in the middle of the original stream channel for every dam and for each appurtenant structure included in the analysis.

### Options available

- Option

### Selection and rationale

To be determined.

### Rationale for why the other options were not selected

To be determined.

## Breach Trigger Types

Define when breaches occur in the hydraulic model. Non-water-based triggers (i.e., seismic, gate operability, debris, etc.) will not be addressed as of August 2024.

### Options available

- Elevation sampled from the SRP curve

- Breach at the peak

- Elevation plus duration.

### Selection and rationale

Sampling the elevation from the SRP curve is technically appropriate and expedient.

### Rationale for why the other options were not selected

Although used commonly in USACE HLRAs, the peak elevation is not known in advance making breaching at the peak technically complex and limiting uncertainty in sampling.

For most structures, elevation plus duration is implicitly part of the SRP curve, including it in the sampling methodology as well as the definition of the SRP curve leads to double counting the effect of duration.

## Breach Parameters—Levees

Once a breach is triggered, breach parameters govern the size and shape of the breach controlling the flow into the leveed area. Breach parameters include width, depth, side slopes, rate of widening, etc.

### Options available

HEC-RAS currently has two options for entering breach parameters; a user-entered feature where final breach dimensions are entered or, alternatively, a simplified physical model approach using soil parameters (erodibility) and hydraulics (velocity, time) to model the breach development.

- User-entered Data

<!-- -->

- Standardized breach dimensions

- RA informed

<!-- -->

- Simplified Physical Breach Method

<!-- -->

- Standardized breach dimensions (Kd=Erosive)

- Probabilistic (probability distribution for Kd)

### Selection and rationale

The simplified physical HEC-RAS option is the preferred approach. The LST uses this approach allowing flexibility to account for varying conditions modeled in FFRD (breach initiation trigger, hydrograph, etc.).

A standardized breach parameter (Kd=erosive) was selected as a good approximation of breach width. The levee investigations can review this approach to determine if a probabilistic approach is better. There is no existing database for the FFRD modeling to aid in informing the soil parameters (erodibility) for a given breach location. Future use of LST 2.0 will grow this database.

### Rationale for why the other options were not selected

User-entered data is breach at top-of-levee loading based and may not be representative if the breach trigger elevation varies from that. The Simplified Physical Breach Method is the solution to this concern.

A probabilistic selection of Kd was not initially chosen as a simplification to the model. Breach width is a significant factor in inundation modeling so this will be re-evaluated. In practice, use of Kd values above and below the erosive rate led to results being classified as not reflective of typical breach dimensions within the region modeled, which is why Kd=erosive is recommended as an appropriate mean value.

## Breach Parameters—Dams

Once a breach is triggered, breach parameters govern the size and shape of the breach controlling the flow out of the dam. Breach parameters include width, depth, side slopes, rate of widening, etc.

### Options available

HEC-RAS currently has three options for entering breach parameters; a user-entered feature where final breach dimensions are entered, a Simplified Physical Breach Model approach using soil parameters (erodibility) and hydraulics (velocity, time) to model the breach development, and a Physical Breach Model approach more directly accounting for the breach process.

- User-entered Data

<!-- -->

- Standardized breach dimensions

- RA informed.

<!-- -->

- Simplified Physical Breach Method

<!-- -->

- Standardized breach dimensions (Kd=erosive)

- Probabilistic (probability distribution for Kd).

<!-- -->

- Physical Breach Modeling

### Selection and rationale

The Simplified Physical Breach Method is the recommended approach for embankments for the pilot studies. Although USACE dam safety dam breach methods use regression equations to inform breach parameters, the current context of FFRD can more expediently use the Simplified Physical Breach Methods.

### Rationale for why the other options were not selected

User-entered data is breach at top-of-dam loading based and may not be representative if the breach trigger elevation varies from that. The Simplified Physical Breach Method is the solution to this concern.

A probabilistic selection of Kd was not initially chosen as a simplification to the model. Breach width is a significant factor in inundation modeling so this will be re-evaluated. In practice, use of Kd values above and below the erosive rate led to results being classified as not reflective of typical breach dimensions within the region modeled, which is why Kd=erosive is recommended as an appropriate mean value.

## Structures to Breach-Dams

While no dams were breached in the Kanawha River Basin Pilot study, a single large Corps dam was allowed to breach for demonstration purposes during the Duwamish River Basin Pilot.

To include the impact of breach of dams in flood plain mapping per BW-12.

### Options available

- Breach all dams

- Low hazard dams

- Significant hazard dams

- High hazard dams

- Run-of-river dams

- Dams with SRP curves above range of events selected

- Model every potential failure mode from existing risk assessment

- Volume of reservoir dependent

- Height of dam crest dependent

### Selection and rationale

In October 2024, the steering committee did not provide preliminary decision guidance for the inclusion of dams based. Future investigations and pilot studies will inform decisions on which structures will be breached. The source for SRP values for dams without a USACE risk assessment is also being considered.

### Rationale for why the other options were not selected

In October 2024, the steering committee provided preliminary decision guidance for the exclusion of low hazard, run-of-river dams that are not high hazard, dams with SRP curves beyond the 2,000-year confidence limit.

## Structures to Breach-Levees

No levees were breached in the Kanawha River Basin Pilot study.

Requirements statement

### Options available

- Breach all levees

- Breach no levees

- Do not breach levees with the SRP curve over 1/2,000 confidence limit

- Option

### Selection and rationale

To be determined.

### Rationale for why the other options were not selected

To be determined.

## Levees to be modeled as Part of the Future of Flood Risk Data Initiative

The FFRD modeling team determined which dataset to use for identification of what levees exist within a basin and a scope for reviewing and improving levee data in the basin.

No national database contains a comprehensive view of all levees in the nation. The NLD, managed by USACE, intends to meet this need. It is recognized there are potential unknown unknowns and some levees may be missing from the NLD.

Each levee modeled as part of the FFRD initiative will consider the residual risk with at least one breach location and system response curve.

### Options available

- Use the NLD as the best available source of levee data.

- Invest in local investigations of levees during FFRD basin modeling.

### Selection and rationale

Use of the NLD as the definitive source for levees to be modeled in FFRD was selected as a consistent, national approach to identification and documentation of levees.

### Rationale for why the other options were not selected

Further investigation into local levee data sets extends production schedules, likely yields unfruitful results, potentially leads to inconsistent levee definitions, and becomes a competing dataset to the NLD. The NLD is the definitive source for levee data in the nation. Federal agencies involved in FFRD modeling need to continue to communicate the importance of levee owners maintaining data in the NLD to mitigate the chance of not including important community levees.

## Levee Geospatial Data Refinement

Levee data refinement refers to the improvement of the critical levee data used in the FFRD model—primarily, levee alignment and levee crest profile data. There are two decisions made regarding levee data refinement.

The first is that the levee data refinement team will process all FFRD study basins. The NLD is the definitive source of levee geospatial data for the nation. FFRD studies will source levee data (alignment and crest profile) from the NLD.

The second decision is related to the scope of levee data refinement. The NLD contains crest profiles from various data sources including survey and DEM. The crux of the issue is to determine which levee crest profile source is most appropriate.

The levee data refinement team will work ahead of the FFRD basin modeling teams with a focus on data gaps only; using available DEM to develop crest profiles where none exist. Data gaps primarily exist for non-USACE levee systems; however, some data gaps may exist in USACE district-managed levee portfolios. The FFRD levee team coordinates updates with the local USACE district when USACE portfolio levees have data gaps.

### Options available

- No alternative option exists for a national source of levee data. Issues with levee data must be correct in the NLD as the primary source.

- For levee data refinement scope there are options:

<!-- -->

- Option 1: All levees in the basin can be updated to the proposed DEM source for the FFRD study.

- Option 2: Use the NLD as the definitive source of best available levee crest profile entered by the levee data manager.

### Selection and rationale

Use of the NLD as the source of best available crest profile was selected. The scope of the levee data refinement will focus on missing crest profiles only. The rationale is that the NLD represents a managed data source by a levee data manager; either the USACE district or the levee owner/operator through the NLD team. Current levee crest profile information includes survey levee crest profiles of a higher quality data source than LiDAR-based terrain.

A future condition may need to reconsider this decision in a scenario where a non-USACE portfolio is not maintained by a levee data manager and the existing data is out-of-date resulting in LiDAR-based terrain being a better source.

### Rationale for why the other options were not selected

Option 1, refining all levees in the basin with LiDAR-based terrain (overwriting the NLD crest profiles), was not selected. The NLD crest profile is a managed data source that should be leveraged as the best available source of data. The crest profile used for many purposes is viewable and transparent in the NLD so levee owners can be informed and ensure their best levee data is as accounted for use in FFRD modeling. Current levee crest profile information includes survey levee crest profiles of a higher quality data source than LiDAR-based terrain.

# —Consequences

FFRD intends to compute graduated risk results. Risk in the context of FFRD is based on the economic loss at buildings in the United States. This section presents decisions represented in the SOP regarding consequences modeling for FFRD.

## Structure Geometry Representation

Structures must be geographically describable in a location.

### Options available

- Point; x,y location

- Polygon

- Raster.

### Selection and rationale

A complete set of polygon-based building outlines is not commonly available throughout the nation; however, a point-based representation (the NSI) is readily available.

Point (x,y location) is the commonly practiced methodology and is consistent with what FEMA actuaries use for the Uniform, Correlated, Orthogonal, and In Force books.

### Rationale for why the other options were not selected

Polygons are a larger computational burden for a marginal improvement over using points. No consensus on methodology to address this is adopted by the community of practice.

Rasters do not require attribution. Not commonly used for this purpose.

## Structure Inventory Source

The assumption is a structure inventory with a minimum field set of a unique structure name, an x, y location, a damage category (e.g., residential, commercial, industrial, public), an occupancy type, a foundation height, a foundation type, a structure value, and a content value will be used.

Quantification of consequences cannot be hard wired into the modeling.

### Options available

- National Structure Inventory

- USA Structures Building Footprints

- Microsoft Building footprints

- Census block data.

### Selection and rationale

Without these minimal pieces of information, no computation can be made. The NSI includes the required pieces of information/data.

- Minimum field set of a unique structure name

- X, Y location

- Damage category (e.g., residential, commercial, industrial, public)

- Occupancy type

- Foundation height

- Foundation type

- Structure value

- Content value

- Ability to work with Uniform book

- Ability to work with Uncorrelated book

- Ability to work with In Force book.

### Rationale for why the other options were not selected

Microsoft Building footprints are not universally available for all buildings in the nation, they describe location and no other schema elements, and potentially, the data will not remain open data.

Census block data does not provide a specific geographic location for buildings (e.g. the old Hazus approach).

USA Structures attempts to cover each building in the United States, but the quality of the building footprints is not well represented for certain categories of structures, e.g., row houses. While the USA Structures contains some attempts at general classification of use, it does not have a complete set of schema required for loss calculation.

## Source of Damage Functions

USACE and FEMA each have damage functions based on the Economic Guidance Memorandum (EGM). Consistency requires a single damage function set is selected for computing damage functions.

### Options available

- USACE EGM

- FEMA Hazus damage functions

- FEMA claims-based functions that are under development

- Modified damage curves (USACE or FEMA) with building stability overrides.

### Selection and rationale

- Used USACE EGM damage functions for the Kanawha River Basin Pilot because FEMA damage functions were not available at the time.

- FEMA and USACE using different damage functions provides the risk of USACE not being able to justify construction of a project in a place FEMA could.

### Rationale for why the other options were not selected

- FEMA claims-based damage functions were not available at the time required for use in the Kanawha River Basin Pilot study. USACE is working with FEMA to get current damage functions while FEMA updates the claims-based damage functions.

- Using modified damage curves increases inconsistency.

## Damage Function Parameters

Damage functions are designed to be changed via input by the user–no input for damage functions has been specified by FEMA to date.

Depth, velocity, and the maximum of the instantaneous product of depth times velocity (DV).

### Options available

- Depth only

- Velocity

- Maximum of the instantaneous product of depth times velocity

- Duration.

### Selection and rationale

The code developed to allow for easy input through a json specification includes multivariable damage functions selected based on occupancy type name, which hazard parameters are present, and foundation type. Other than that, no decision on what damage function is used has been formalized. The damage functions can be used with or without uncertainty based on what is provided.

### Rationale for why the other options were not selected

Until damage functions reflecting multi-parameter loss are developed, the option of computing multi-parameter loss is not viable.

## Input Hazard Data Format for Consequence Computation

Consequences could be computed from hazards in multiple ways. The FFRD requirements suggest multi-parameter loss functions need to be incorporated into the methodology. This requirement impacts the decisions for how consequence calculations must be computed. Additionally, the computation of losses from aggregated hazard data impact the accuracy of the overall compute. The selected computational choice influences accuracy of derived products, costs for cloud compute, storing data, etc.

### Options available

- Per-Event

<!-- -->

- This is the most accurate methodology when multi-parameter loss is at play.

- For the highest accuracy, the Depth times Velocity parameter must be the maximum of the product across time, instead of the depth max times the velocity max.

<!-- -->

- Block maxima

<!-- -->

- For single parameter loss (e.g., Depth only) the result from Block maxima should be the same as Per-Event.

- Concerns regarding derived products (e.g., block max depth and block max velocity grids may be incorrect since depth and velocity values could come from different events) when using multi-parameter loss functions.

<!-- -->

- Hazard Frequency

<!-- -->

- Hazard frequency representation can be achieved in multiple ways–for FFRD using a series of AEP specific hazard grids is recommended, e.g., 5-, 10-, 50-, 100-, 200-, 500-year hazard grids if the hazard frequency approach is selected. Alternatively, point based estimates of frequency could be stored and interpolated. This requires the generation of a mesh of points appropriately spaced to interpolate at the individual structure. This introduces error into the applied depth at a structure, it is not recommended.

- Any method for applying hazard based on hazard frequency curves can result in reduction in the accuracy of the damage frequency curve. Representing loss from each synthetic event gives higher resolution than summarizing the hazard at a subset of the points on the hazard frequency curve.

### Selection and rationale

For the Kanawha River Basin Pilot, a decision is not yet determined on how hazards will be applied to the structures. No consequence assessment will be computed until this is resolved.

### Rationale for why the other options were not selected

No decision has yet been made.

## Computational Engine

Some computational engine needs to be developed to iterate through the inventory of buildings, query hazard parameters, and apply loss calculations based on the damage functions and the values of each inventory element.

### Options available

- Life Loss Estimation (LifeSim)

- Open Hazus

- Coastal Probabilistic Flood Risk Assessment (CPFRA) consequences tool

- GO Consequences

- Flood Impact Analysis (HEC-FIA)

- Generation II Coastal Risk Model (G2CRM)

- Beach FX.

### Selection and rationale

Go-consequences is a methodology scalable to the cloud in a Linux container, which works with multiple types of hazard data, and separates the generation of consequences from hazard generation.

### Rationale for why the other options were not selected

The computational engine must be able to separate consequence estimation from event generation, meteorology, hydrology, reservoir operations, and hydraulic modeling. This excludes BeachFX and G2CRM.

The methodology should be computable in a container and scaled to the cloud, as of August 2024, this excludes HEC-FIA, Hazus, and LifeSim.

The methodology must be fully functional at the time required, this excludes Open HAZUS.

The methodology must work with inland products, this excludes the CPFRA methodology.

## Source of Hydraulic Output

The hydraulic output at a point (HDF) files, a summarization point based mesh (like the adcirc mesh), or the output geotif files from HEC-RAS mapping engine could provide the hydraulic output.

### Options available

- Directly query the HDF for hazard value(s) at a point (currently ras libraries do not specify which render mode equivalent would be utilized)

- Hydraulic model outputs depth grids and consequences tool uses them directly (depth grids)

- Interpolating from hazard curves (currently used for coastal modeling).

### Selection and rationale

Use of depth grids provides required consistency.

### Rationale for why the other options were not selected

- Risk the output from querying the HDF would result in a different value depending on the selected render mode for computing a depth grid causing inconsistency.

- Don’t have an equivalent of the mesh required or nodal values where data is stored on the node that will work for interpolation. Data exists at the centroid of a cell, but it should not be interpolated. The value will be different than what the HEC-RAS grids produce. This would provide inconsistent values fetched because interpolation of hydraulics is different.

## Calibration and Validation Approach

At a minimum, consequences calculations must be compared to observed data (to include existing FEMA claims data in the watershed). To calibrate a consequences model, structure inventories must be quality controlled to ensure accuracy.

### Options available

- Modify structure inventory for calibration events (calibrate to HEC-RAS model)

- Modify damage functions for calibration events

- Modify both structure inventory and damage functions for calibration events

- Do nothing.

### Selection and rationale

As of August 2024, for the Kanawha and Duwamish river basin pilots, HEC-RAS calibration results were used to calibrate/modify the structure inventory. Structures were moved to match the structure inventory to the HEC-RAS results removing structures that did not make sense (i.e., located in the river).

A risk to this is a national, publicly-available dataset is modified. This risk may prompt change of this process.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

# —Antecedent Conditions for Production Simulations

Antecedent conditions describe the state of the watershed at the start of a simulated event. Many antecedent conditions impact the simulated results of an event. The starting pools of reservoirs could be high or low thus being unable to handle incoming precipitation or flow or being able to store the incoming event. The watershed could be dry or wet impacting the amount of water that could be infiltrated or how quickly it transforms into flows in the river. The system for defining antecedent conditions not only needs to respect the seasonality of these conditions, but also must be respected across all models simulating an event to ensure consistency in the modeling approach.

## Methodology for Generating Antecedent Conditions

The two most significant contributors to the rainfall runoff response are the placement of the storm and the antecedent conditions it is applied to in the basin. Antecedent conditions are critical to capturing the response of the watershed and must be treated as stochastic parameters.

### Options available

- Constant unvarying initial conditions

- Independently managed initial conditions for every model

- Coordinated initial condition sampling for all models.

### Selection and rationale

Leveraging the peaks calibrated POR simulation to generate the possible antecedent conditions dataset provides an easy way to generate model parameter states from the historic record without direct observation. Utilizing those antecedent states through a bootstrap allows for a non-parametric sampling of states to be combined with sampled storms and locations to best represent the natural variability of the watershed response for conditions that have not yet been observed (combinations of watershed states with storms and storm placements that have not yet been observed).

### Rationale for why the other options were not selected

Deterministic and unvarying initial conditions will not be able to respect some of the most significant contributing factors to the variability of flooding in the watersheds.

Uncoordinated initial condition sampling will lead to situations where the reservoir simulation models will not agree with the state of the watershed in the hydrologic models or the hydraulic models and will cause simulations that do not reflect physical realities.

## Coincident Flows from Adjacent Basins

For watersheds receiving flows from another study unit, for example when the watershed is not a headwater basin, upstream boundary conditions need to be supplied to the downstream models plausible for the event.

### Options available

- Use observed flow boundary conditions coincident with the selected initial conditions

- Use some kind of modeled flow result.

### Selection and rationale

No decision has been made.

### Rationale for why the other options were not selected

The first pilot studies are all headwater watersheds. A technique will need to be developed and tested to provide reasonable upstream conditions for the event simulations. Using the coincident upstream flow conditions fits in with the process used in HEC-HMS for setting initial conditions. However, it does not capture the potential for the selected storm event to also cause precipitation in the upstream watersheds. Trying to model these upstream areas adds significant model scope and compute time and may not be worth the additional complexity.

# —Model Integration

Section 4 describes the decision to start with precipitation and leverage SST. Section 5 describes the approach to describe excess precipitation and base flow. Section 6 describes the usage of reservoir operations and Section 7 describes base flow, reservoir releases, and excess precipitation. The process requires linking the outputs from one model as the input to another model. This is model integration. This document describes the decisions regarding model integration in the SOP.

## General Overview

Model integration is the process of taking independent models and connecting them to operate as a system of models. This is necessary to allow for substitution of portions of the process (e.g. use of a different hydraulic model than HEC-RAS).

### Options available

- Manually pass data from one model to another

- Define the linkage of outputs to inputs

- Hard code what model is going to be computed

- Abstract the computed model allowing for customization (plugins).

### Selection and rationale 

Define the linkages, with appropriate abstractions through a plugin-based framework allowing integration of future unpredictable changes without requiring significant redevelopment. The proposed process leverages plugins defining their inputs, outputs, and available actions. Plugins for each HEC product, HEC-HMS, HEC-RAS, HEC-ResSim, and a consequences plugin are being developed to implement the proposed methodology. The process takes the plugins which compute the calibrated HEC-HMS, HEC-ResSim, and HEC-RAS models developed individually utilizing stand-alone data as the input information and interconnects each program to interactively use the dynamic output data from one program as the input for another. The model integration effort uses calibration events used in the development of each of the modeling software suites. The HEC-HMS model output data is used as input datasets for HEC-ResSim, HEC-RAS leverages output from HEC-HMS, the fragility curve sampler, and HEC-ResSim, the output from HEC-RAS is used by the consequence engine to compute losses for each computed event.

### Rationale for why the other options were not selected

Manually passing data requires significant manual steps and results in significant opportunity for human error.

Automating without an abstraction like plugins creates a tightly coupled and inflexible product.

Hardcoding inputs into models prepare those models to only compute the singular event. That means manual updating of model input boundary conditions for each simulated model for each simulated event. This is prone to human error and laborious.

## Integration Configuration By Cloud compute Team

Model configuration requires a layout allowing users to connect output from one program to easily be located as input for another program. Data connections are a key task for integration, and configuration of the model must be consistent to provide structure to the integration process. Each component must be maintained in a stand-alone folder to allow for dropping an updated model directly into the integration folder without changing any other connections.

### Options available

- Define connections in a json or yaml file

- Develop a user interface (UI) allowing modelers to link models.

### Selection and rationale

For the Kanawha and Duwamish river basin pilots, the linking was done through code and json files to verify the tools and methods function correctly and this effort was completed by the cloud compute team based on an interpretation of the delivered models

### Rationale for why the other options were not selected

The processes were unknown and needed exploration prior to developing UIs to govern linking.

The approach for the first pilots reduced the burden on the development team in the short run. The lessons learned from the Duwamish and Kanawha river basin pilots have been valuable in defining how models need to be linked and will inform user stories for a future UI to link models

## Integrated Model Linking by the Hydraulics and Hydrology Modeling Team

A key purpose of the model integration phase is verifying the model connections are valid. This is accomplished by recomputing the calibration events and verifying the results are the same for the integrated model as they were for the stand-alone calibration models. With the model results verified, the model integration is complete, and the model suite can be adapted for the cloud computing environment.

### Options available

- Do not validate the linkages are correct

- Leverage historic calibration events to verify simulated outputs are consistent with the calibrated outputs.

### Selection and rationale

For the Kanawha and Duwamish river basin pilots, no validation of historic events were completed with the linked models. This was a short cut while other elements of the framework were being improved. The validation of the frequency relationships was relied upon to ensure outputs were not being accidentally double counted, propagating unmitigated errors, or improperly linked.

### Rationale for why the other options were not selected

Linking the models and rerunning the calibration events as a linked set of models is a best practice and should be done as part of the production watersheds. For expediency this step was skipped during the first two pilots.

As more experience with cloud compute interactions are gained, the following steps are needed to have confidence the model system is being applied appropriately in FFRD cloud computes:

- Full Linkages on a desktop; verify data is passed appropriately

- Recompute calibration events with a desktop-linked version; verify a system of models maintains calibration

- Promote linked model version to the cloud compute and verify results match

- Generalize naming conventions for SST events for all models.

## Staffing Model Integration

There is a need for a coherent system for version control of models developed for FFRD as they proceed from calibration to production.

Model integrator is the intermediary between the original modeler and the person performing the cloud compute.

### Options available

- Rely on cloud compute staff to interpret intended linking between models

- Cloud compute staff reaches out to individual modelers to clarify issues on individual models

- Assign a single model lead, model integrator, to own the system models after they have been calibrated and delivered and be responsible for all naming conventions, linkages, and validations through the life cycle of the project. That person would interface with the cloud compute staff.

### Selection and rationale

A single person is responsible for model integration for a single basin. This person is responsible for the custody of the models after calibrated models are delivered.

### Rationale for why the other options were not selected

As experience is gained through pilot projects, these roles become clearer and more formally documented in the SOP.

## Model Integration Quality Control

As models are linked, calibrated to historic events as a system, stress tested, and validated to frequency outputs, the models are typically changed by the modeling teams to improve stability, reduce propagation of error, or fix assumptions not spanning the frequency range well. This leads to potential for model changes not well coordinated with the previous modeling team members.

### Options available

- Have no plan for quality control

- Define appropriate roles and responsibilities of team members to ensure communication and verification is completed.

### Selection and rationale

For the Kanawha River Basin Pilot study, the validation of the frequency curves and stabilities in the HEC-RAS models triggered many small changes of the models that were not well communicated to the team. The HEC-HMS model was modified and poorly documented as the base parameters were changed from a calibration event to the POR parameter set and then subsequent modifications to better tune the frequency curves. This created significant time loss and confusion as team members were uncertain of which model was being applied.

### Rationale for why the other options were not selected

While it was generally known before conducting the Kanawha River Basin Pilot that a strategy for model quality assurance (QA)/quality control (QC) needed to be in place during the calibration and verification of the linked models, the SOP was not well formulated for this process and deadlines were tight. The team worked ad hoc and made mistakes that served as lessons learned for the Duwamish River Basin Pilot. The Duwamish River Basin Pilot implemented some of these improvements (e.g., better naming conventions in the FFRD-computable store) but additional lessons are likely to be learned as the SOP development and testing continues.

## Model Preparation for Cloud Compute

To reduce confusion during cloud compute stages, calibrated models must be cleaned up and standardized improving clarity for the cloud compute stages. Instead of having six (one for each calibration event) HEC-HMS, HEC-ResSim, and HEC-RAS simulations, a standardized and generic naming convention is applied, and appropriate generalized parameters are input in the models. Unnecessary files are removed

Performing folder clean up improves this process.

### Options available

- Do nothing; leverage the calibrated models as-is

- Remove all but one calibration event and use it

- Clean up models and apply appropriate parameterization spanning the frequency range.

### Selection and rationale

In Kanawha River Basin Pilot study, the first applied approach removed all calibration events but one (January 1996). This led to poor validation for the frequency ranges because of the assumptions related to snow melt. The HEC-HMS model was updated to represent the POR parameterization to improve the validation results across the frequency range. The Duwamish River Basin Pilot incorporated the lessons learned and improved this process applying standardized naming conventions and parameterization. As of August 2024, the methodology is to clean up the models, apply appropriate parameterization, and have standardized naming conventions.

### Rationale for why the other options were not selected

Doing nothing results in significant uncertainty in which plan to run in HEC-HMS, HEC-ResSim, and HEC-RAS. This alternative introduced significant confusion regarding what the results meant and poor representation of frequency results. Structure to the models in the cloud compute was necessary to improve automation, results performance, and communication.

## Calibration and Validation across Frequency Ranges

Calibrating an event-based model like HEC-HMS, HEC-ResSim, or HEC-RAS illustrates the capability of representing that event within the model in question. The FFRD methodology requires showing the system of models performs as a unit and produces the output of frequency value relationships across the basin. This requires a calibration/validation of a large set of events ensuring the system of models reproduces historic observed data. This requires the modeler link all hydrologic, reservoir, hydraulic, and consequences models, run a set number of stochastic events, and compare computed results against observed data

### Options available

- Do nothing and use previously developed model process and parameter estimates without any changes to validate to annual maximum series.

- Simulate stochastic events and compare results against observed data annual maximum series and note differences.

<!-- -->

- Compute 100 synthetic years

- Compute 500 synthetic years

- Compute 2,000 synthetic years.

<!-- -->

- Simulate stochastic events and compare results against observed data annual maximum series and address changes until things look good enough.

<!-- -->

- Compute 100 synthetic years

- Compute 500 synthetic years

- Compute 2,000 synthetic years.

<!-- -->

- Simulate stochastic events and compare results against observed data annual maximum series and address changes until things meet calibration metrics or sufficient justification is provided for not meeting calibration metrics.

<!-- -->

- Compute 100 synthetic years

- Compute 500 synthetic years

- Compute 2,000 synthetic years.

### Selection and rationale

Simulating multiple stochastic events and comparing computed results against observed data provides the opportunity to evaluate the goodness of fit for the hydrologic, reservoir, hydraulic, and consequences modeling producing accurate probabilistic results. As of August 2024, the PDT evaluates these subjectively and notes limitations with the approach if model results are not subjectively good enough. The PDT computed 100 synthetic years and 500 synthetic years for the Kanawha and Duwamish river basin pilots, respectively. The Kanawha River Basin Pilot results included an observation in one gage record probably representing an event that was much less likely than its representation in the database (it plotted at about a 100-year due to gage record length but probably represented a 500 year). This prompted the team to run a larger sample during the Duwamish River Basin Pilot ensuring sufficient data points to compare potential outliers to.

### Rationale for why the other options were not selected

Doing nothing and using the initial process and parameter estimates without any changes does not prove the hydrologic, reservoir, hydraulic, and consequences modeling produces accurate probabilistic results.

Adding in metrics is planned for future use, but, for expediency, the metrics and their use are not yet defined.

As parameters are adjusted in the models, they must be reevaluated with the historic calibration events to verify the change to support watershed modeling for the frequency analysis targets does not significantly impact individual historic event calibration.

## Calibration and Validation of Events with Linked Modeling System in Cloud Environment

To ensure models have been properly linked and inputs do not propagate error across the watershed, the models must be compared as a group to the calibration events, i.e., link all hydrologic, reservoir, hydraulic, and consequences models and run historic events and compare computed results against observed data. This needs to be repeated after frequency validation if changes were made to the underlying model.

Need to be specific with regards to the statistical metrics, goodness of fit tests, etc. used to ascertain model accuracy.

### Options available

- Do nothing and use previously developed model process and parameter estimates without any changes.

- Simulate historic events and compare results against observed data visually.

- Simulate historic events and compare results using the same metrics for model calibration.

### Selection and rationale

Simulating multiple historic events and comparing computed results against observed data proves the hydrologic, reservoir, hydraulic, and consequences modeling produces accurate results.

Iteration and feedback are necessary between stochastic simulations and historic event simulations.

Note: Once developed, stipulate the statistical metrics used and their respective quantities for primary, secondary, and tertiary gage locations.

### Rationale for why the other options were not selected

Doing nothing and using initial process and parameter estimates without any changes does not prove the hydrologic, reservoir, hydraulic, and consequences modeling produces accurate results for historic events.

## Computational Order Defined by the Directed Acyclic Graph

Requirements statement

### Options available

- Option 1

- Option 2

### Selection and rationale

Selection and rationale.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Sources of Parameter Uncertainty

To represent the uncertainty around any frequency relationship, the linked system of models is provided seeds for natural variability and knowledge uncertainty. Knowledge uncertainty represents variables lacking enough data or information to properly define them; these values are generally knowable but information is unknown. Generally, knowledge uncertainty variables become known through spending additional funding to establish certainty. Natural variabilities are variables that change from year to year. Each model is provided with seeds in a nested loop structure separating the knowledge uncertainties from the natural variabilities. This reduces the error around the frequency value relationships primarily representing the knowledge uncertainty. Each model treats their respective variables differently and should be articulated in their individual chapters.

### Options available

- Do not sample variables as distributions.

- Combine uncertainty and variability as well as sampling error.

- Separate uncertainty and variability but allow sampling error to increase confidence intervals.

- Separate uncertainty and variability and reduce sampling error as much as feasible.

### Selection and rationale

The selected option separates uncertainty and variability but allows sampling error to increase confidence intervals. This is the optimal option due to the relative cost to additionally separate out sampling error.

### Rationale for why the other options were not selected

Deterministic model results could be computed at a given site, but each individual site across the basin would need to be separately modeled. Combining those individual samples in a way that is consistent with the correlation of error is nearly impossible.

Sampling in a way to combine uncertainty and variability artificially inflates the confidence intervals.

Sampling in a way to fully separate uncertainty, variability, and sampling error requires simulating to convergence inside of each realization as well as across all realizations, which can create a significant compute burden.

# —Centralized Access to Data

Introductory text for section.

## Centralized Access to Final Data

Final delivered models must have a centralized online storage location allowing anyone to find and access data after project completion. FFRD requires the modernization of data management and deliver. The central point of access must allow for role-based access with appropriate levels of access for various user groups. Data must be accessible by and allow collaboration between federal and non-federal partners.

### Options available

- Give everyone access in Amazon Web Services (AWS)

<!-- -->

- CloudBerry

<!-- -->

- Open source tools for sharing S3 buckets

<!-- -->

- BucketView (PTS)

<!-- -->

- Mapping Information Platform (MIP)/Flood Risk Study Engineering Library (FRiSEL)

- Model Library.

### Selection and rationale

The model library provides a non-proprietary central repository for model development and discoverability. The model library is consistent with Department of Defense (DOD) security standards and allows role-based access to datasets for the entire model development team (public and private) unlocking the ability to efficiently share files, collaborate, and reduce opportunities for mistakes related to file versioning.

### Rationale for why the other options were not selected

No single existing option met the requirements for centralized access to data for multiple federal and non-federal partners.

- Compliant with Federal and DOD security policy.

- Federated data using commodity cloud storage. Can work with any number of cloud data stores owned by any number of groups.

- Storage isn't necessarily owned by model library and can be connected, then indexed.

- Needed tool off-line that could be used by USACE and FEMA (not on either virtual private network \[VPN\]).

- Needs to be extensible to support changing mission requirements or additional mission requests.

- Collaboration between federal and non-federal partners.

- Access to publicly-reusable models.

- Major problem is the MIP currently mixes engineering data and models with personally identifiable information (PII), and so access to it is severely limited. FEMA needs to modernize its own model storage so it can better talk to the model library.

## Interim Project Collaboration

Executing the FFRD SOP requires cross agency PDT members to share reliable, timely, easy to use and accurate data. FFRD development teams gain efficiencies through centralized collaboration and file storage. Centralized collaboration reduces versioning inconsistencies as models progress through the review process with a site.

### Options available

- Give everyone access in AWS

<!-- -->

- CloudBerry

<!-- -->

- Open source tools for sharing S3 buckets

<!-- -->

- BucketView (PTS)

<!-- -->

- Distributed/ad hoc storage

- Transfer of data by external hard drive

- Model library.

### Selection and rationale

The model library provides a non-proprietary central repository for interim project collaboration. The model library is consistent with DOD security standards and allows role-based access to datasets for the entire model development team (public and private). The model library reduces opportunities for mistakes related to file versioning and increases expediency. The model library also provides a consistent interface for the central repository.

### Rationale for why the other options were not selected

No other option meets the following criteria.

- Must be compliant with Federal and DOD security policy.

- Federated data using commodity cloud storage. Can work with any number of cloud data stores owned by any number of groups.

- Needed tool off-line that could be used by federal, non-federal, and private entities (not on VPN).

- Collaboration between federal and non-federal partners.

## Staging of Final Models for Cloud Access

FFRD SOP requires accessing models in the cloud. To accomplish this goal, a final set of calibrated and evaluated models must be staged in a secured environment, linked, and described in a systematic manner.

### Options available

- Stage models in AWS outside of the model library

<!-- -->

- CloudBerry

- BucketView (PTS)

<!-- -->

- Provide everyone access to AWS console

- Model library.

### Selection and rationale

The model library interfaces with the cloud computation capabilities applied for all final production runs. Use of the model library where models are being stored provides security and efficiency.

### Rationale for why the other options were not selected

No other option meets the following criteria.

- Must directly integrate with compute through AWS.

- Compliant with Federal and DOD security policy.

- Federated data using commodity cloud storage. Can work with any number of cloud data stores owned by any number of groups.

- Needed tool off-line that could be used by federal, non-federal, and private entities (not VPN).

- Needs to be extensible to support changing mission requirements or additional mission requests.

- Collaboration between federal and non-federal partners.

# —Production of Stochastic Simulations

Introductory text for section.

## Simulation Statistical Approach

FFRD seeks to move from binary representation of hazard towards a graduated representation of hazard and risk. This requirement is further outlined in BW-12 to include areas where people currently live and could potentially live. To ensure reasonably accurate representation of graduated hazard and risk everywhere requires development of a statistical approach that can properly manage large watershed modeling.

### Options available

- Quasi-continuous simulation

- Life cycle while preserving state

- Full continuous simulation

- Annual maximum simulation

- Stratification.

### Selection and rationale

Quasi-continuous simulation was chosen to appropriately manage the uncertainty in antecedent conditions as well as the choice of SST and the ability to produce graduated hazard and risk products across very large domains while preserving the underlying correlation structures of the outputs within those domains.

### Rationale for why the other options were not selected

The life cycle while preserving state option creates new synthetic years not identified in the frequency range but increases complexity of the representation of the storms across time as well as increasing the overall complexity of the system (managing states across time) and computational burden.

Full continuous simulation requires stochastic weather generation that appropriately manages non-stationary processes. This is incredibly difficult and not needed to meet FFRD requirements.

Annual maximum series relies on at site representation of annual maximums and is complicated to scale to large watersheds.

Applying a stratification scheme with the goal of computation reduction requires a single variable uniquely or substantially influences the frequency of the output variables. Stratification using multiple parameters could be performed, but the process is complex, and each additional variable added to the stratification significantly reduces the computational reduction benefit that stratification normally confers.

## Stochastic Simulation Structure

Based on choices identified in Section 4 to use SST, the simulation structure must sample multiple events per year. To cover the frequency, ranging from 1/5 AEP to 1/2,000 AEP, each frequency curve generated by the system must contain sufficient simulations to cover the frequency range. To represent uncertainty about any frequency relationship, a sufficient set of simulated frequency curves must be generated.

### Options available

- Sample 1 event per year, 2,000 events per realization, run a set of realizations and run all models for all events

- Sample an appropriate number of events per year based on the storm catalog, simulate 2,000 event years per realizations, and run models only if they contribute to annual maximum series

- Sample an appropriate number of events per year, run event years until realization converges, run realizations until confidence intervals converge, and run models only if they contribute to the annual maximum series.

### Selection and rationale

The size of the storm catalog dictates the number of events per event year required, e.g., if the storm catalog has 400 events and covers 40 years, it should have on average 10 events per event year.

The objective annual exceedance probability dictates the number of event years in a realization e.g., if a frequency curve up to the 2,000 year is desired, minimally, 2,000 event years must be generated per realization (see Section 13.4).

The objective confidence intervals dictate the number of realizations. If a 99 percent confidence interval is desired, at least 100 realizations should be sampled to allow for the definition of a 99th percentile since confidence intervals are not defined by a parametric distribution nor are they expected to be symmetric (see Section 13.3).

Regarding when to run events, events should only be computed through the most expensive process if they contribute to the annual maximum series (see discussion on Section 13.8).

### Rationale for why the other options were not selected

Running one event per year does not reproduce the frequency curves if starting with SST. There is no characteristic storm, each storm is unique in the way it naturally plays out. Divorcing the catalog from the number of events per year results in erroneous statistical output from the system.

Running all the models for each event creates unnecessary compute costs. Not all events simulated by SST produce annual maximum series in an event year, skipping these events significantly reduces compute costs.

## Number of Realizations

The uncertainty around variable-frequency relationships depends upon the number of realizations simulated. For statistically appropriate confidence intervals, the number of realizations should be determined based on a set of convergence criteria.

The number of realizations required impacts scoping decisions. Therefore, knowledge of the number of realizations required for a basin must be known during the scoping phase of a watershed study. In practicality, the ability to estimate the number of realizations per basin based on convergence criteria prior to simulation of the basin is complex resulting in the need to define a scopable criteria.

### Options available

- Run a fixed number

- Run a fixed number and test for convergence criteria, state convergence statistics

- Run until convergence of confidence intervals.

### Selection and rationale

To simplify scoping and execution of the SOP, the pilot basins and validation basins will use a fixed number of realizations allowing scoping prior to simulation of the basin.

### Rationale for why the other options were not selected

Running more realizations is costly, going until convergence criteria are met in a tail of the error distribution may cost much more than is reasonably valuable. Exploration on what constitutes enough realizations needs to continue and be discussed/evaluated.

## Number of Synthetic Years per realization

A number of synthetic years must be defined per realization.

### Options available

- Compute 2,000 synthetic years

- Compute more than 2,000 synthetic years

- Compute less than 2,000 synthetic years.

### Selection and rationale

Computing 2,000 synthetic years achieves an estimate of the 2,000 year. The uncertainty around the 2,000 year will not be complete with a more significant contribution of sampling error occurring in this frequency range.

### Rationale for why the other options were not selected

Running less than 2,000 results in a median estimate of the 2,000 year, but no uncertainty can be described at that frequency.

Running more than 2,000 allows for improved representation of the uncertainty around the 2,000 year, reduces the impact of sampling error on that error distribution at the cost of more computation.

## Scaling the Compute

Computing roughly 10 events per event year, 2,000 event years per realization, and a relatively large number of realizations adds up to a significant computational burden quickly. Some means to scale the compute must be investigated.

### Options available

- Manually run simulations

- Scale using local infrastructure

- Scale using the cloud

- Scale using HPC.

### Selection and rationale

The pilot studies scale using the cloud. This option was selected to investigate the feasibility of cloud scaling, explore the overall costs, and develop the infrastructure necessary to leverage the cloud in a vendor agnostic way.

### Rationale for why the other options were not selected

Manually running simulations is prone to user error and requires a significant labor force to push buttons.

Scaling using local infrastructure was planned for testing with the pilots. Some simple calculations identified the available local infrastructure (HEC Nebula 2) is insufficient for the needs of the scaled down Kanawha River Basin Pilot. While this option is viable, it requires significant investment in hardware which is not reasonable to invest in without further discussion.

HPC capabilities exist and can be leveraged to scale computes. Generally, HPC is used where a large memory problem needs to be solved and a significant amount of shared state needs to be shared across many nodes computing at once. The structure of the framework for FFRD avoids this requirement to provide additional flexibility of scale through the cloud. HPC can be used, but it is more expensive to emulate the HPC-type environment in the cloud, and it is difficult to schedule sufficient HPC time to process the amount of compute required for FFRD (as projected as of August 2024).

## Selection and Definition of Uncertain Parameters

To represent the uncertainty around any frequency relationship, the linked system of models is provided seeds for natural variability and knowledge uncertainty. Knowledge uncertainty represents variables lacking enough data or information to properly define them; these values are generally knowable, but information is unknown. Generally, knowledge uncertainty variables become known through spending additional funding to establish certainty. Natural variabilities are variables that change from year to year. Each model is provided with seeds in a nested loop structure separating the knowledge uncertainties from the natural variabilities. This reduces the error around the frequency value relationships primarily representing the knowledge uncertainty. Each model treats their respective variables differently and should be articulated in their individual chapters.

Refer to previous sections for rationale.

### Options available

- Do not sample variables as distributions

- Combine uncertainty and variability as well as sampling error

- Separate uncertainty and variability allowing sampling error to increase confidence intervals

- Separate uncertainty and variability and reduce sampling error as much as feasible.

### Selection and rationale

The selected option separates uncertainty and variability but allows sampling error to increase confidence intervals. This is the optimal option due to the relative cost to additionally separate out sampling error.

### Rationale for why the other options were not selected

Deterministic model results could be computed at a given site, but each individual site across the basin would need to be separately modeled. Combining those individual samples in a way that is consistent with the correlation of error is nearly impossible.

Sampling in a way to combine uncertainty and variability artificially inflates the confidence intervals.

Sampling in a way to fully separate uncertainty, variability, and sampling error requires simulating to convergence inside of each realization as well as across all realizations, which can create a significant compute burden.

## Levee and Dam Breach Representation in Stochastic Runs

To capture the residual risk in the watershed below dams and behind levees that is due to the potential for infrastructure to fail, there must be ability to represent failure in the methodology. That failure representation must be commensurate with the empirical failure rates, and illustrate the extent and significance of flooding due to the failure of infrastructure. (See additional discussion in Section 8.1.)

### Options available

- Leave the description of residual risk behind levees to the LST

- Leave the description of residual risk behind dams to the DST

- Represent both dams and levees in the stochastic simulations

- Run worst case scenarios.

### Selection and rationale

Representing both levee and dam breaching in the stochastic runs is the preferred option. By representing both, interaction of levee breaching with dam breaching and dam breaching with levee breaching is better quantified. If a dam breaches, it may induce levee breaches downstream (or levee overtopping with no breaches). Sampling the trigger elevations for breaches independently based on system response curves as described in Section 8 allows for appropriate statistical representation of the hazard of dam and levee breaching in its relationship to the condition where levees or dams do not breach.

### Rationale for why the other options were not selected

Relying on the LST for residual risk behind levees is not a preferred option. If no levee breaching is included in the model, the statement of risk upstream and downstream of the levees outside of the leveed area would potentially be overstated. Synthesizing the contribution of risk in the floodplain and in the leveed area is a complicated matter if they are modeled separately.

Relying on the DST for residual risk behind dams is not a preferred option. If no dam breaching is included in the stochastic framework, the appropriate statistical relationship between the breach and no breach conditions adds complexity in the combination of the residual risk described by the DST into the FFRD stochastic simulation representation.

A description of the significance of the hazard and the flooding can be represented with worst case scenarios but including that into the risk statement requires a description of the likelihood of that condition occurring. Without the likelihood, the hazard and consequences cannot be represented in the graduated hazard and risk products directly.

## Selection of Hydraulic Events to Run

The computation of a single event across all models in the FFRD watersheds requires the completion of statistical samplers (seed generation, block assignment, SST, SRP curve sampling) as well as computation of process models (hydrology, reservoir operations, hydraulics, and consequences). The computational complexity of each of these elements of an event is not uniformly complicated. The river hydraulics and mapping of river hydraulics represents the vast majority of the computational complexity.

Additionally, due to the random chance of the events within an event year, many of the events have little or no impact on any of the basin. Further, roughly 50 percent of the events represent events smaller than the 2-year event in any given location. In these conditions, the computational output of the hydraulics model and mapped products are almost identical, and the computational cost to produce almost identical results within the channel is disproportionate to its contribution to the graduated hazard and risk products.

Since the storm selection and placement, SRP sampling, hydrology, and reservoir operations models do not depend on the hydraulic modeling; and their computational burden is significantly less, computing all events through these models and evaluating the significance of each event in how it contributes to the significance of the hazard across the entire watershed is possible.

### Options available

- Run all models for every event

- Run a subset of the model with the intent of capturing all annual maximum for each hazard of interest

- Run a subset of the models with the intent of capturing annual maximums between the 1/5-year and the 1/2,000-year

- Stratification.

### Selection and rationale

For the Kanawha River Basin Pilot, running a subset of models with the intent of capturing all annual maximums within a block for all locations in a watershed is the selected option. This approach takes advantage of the ability to evaluate the output from the SRP sampling, hydrology, and reservoir operations and choose events that potentially contribute to an annual maximum at any location of the watershed and only run those with the computationally expensive processes like hydraulics. This approach respects the statistical sampling methodology and reduces computational burden by significant percentages and can even further reduce the computational burden depending on the identification of what events are included or excluded.

For the Duwamish River Basin Pilot, running a subset of the models with the intent of capturing annual maximums between the 1/5-year and 1/2,000-year is the selected option in an effort to meet project requirements and reduce computational burden of HEC-RAS.

### Rationale for why the other options were not selected

The option to run all models for every event was not selected because the cost of running all models does not justify the benefit provided.

Stratification is an opportunity to evaluate an input distribution of events and select representative populations from the input to compute and determine appropriate representative outputs used to represent the statistical output relationships. The complicated question is determining what is being stratified. Stratification of flow at a location can reduce the computational burden of that location. The methodology selected seeks to preserve the complex correlations of multiple statistics across a wide domain. If not expertly designed, stratification corrupts those correlations across multiple parameters. However, simple things such as stratification of storm placements or other strategies can have the same desired effect while preserving the watershed scale and representation.

## Determination of Total Number of Events to Compute

Computing graduated risk products for FFRD using a Monte Carlo approach as described in earlier sections requires identification of some parameters, i.e., how many overall events to compute.

### Options available

- Compute strictly on a budget (e.g., \$1,000)

- Convergence (i.e., reduction of sampling error)

- Run a pre-determined number of events (e.g., 1000).

### Selection and rationale

For the pilot studies, a pre-determined number of events were computed. The objective of the pilots was to build the framework, define the initial draft of the SOP, and develop prototype products with uncertainty. Computing until convergence was not necessary to meet those objectives.

For validation basins, a pre-determined number of events is the selected alternative supporting clarity in scoping.

For production runs, a decision needs to be made associated with this topic. Based on initial calculations, running to convergence may exceed overall project budgets depending on the culmination of the decisions (i.e., mesh resolution, how which hydraulic events to compute are determined, output grid cell resolution, etc.) and how they work together. Prioritization of the objective needs to be discussed. Determining if the objective fidelity in mean/median curve estimates or statistical accuracy of the uncertainty estimates in the tail of the frequency curve for the tail of the uncertainty estimates impacts the feasibility of convergence criteria.

### Rationale for why the other options were not selected

Convergence criteria has not been defined and requires discussion before this option could be selected.

Computing simply on a budget does not provide adequate information to estimate the necessary inputs to the decision of how many total events would be necessary to run.

## Model Changes Required during Production Runs

During production, computing significant quantities of numerical models is likely to create situations where model instability crashes a model and fails to produce outputs. It is uncertain how to handle the failure of a model if a model contributes to an annual maximum series at a location and has gone unstable.

This is if the model fails to run to completion or exceeds tolerances (TBD). Results must be reviewed by qualified modelers.

### Options available

- Only fix the failures generating annual maximums in the range of 1/5 to 1/2,000 but do not rerun models that succeeded

- Fix the base model and rerun them all

- Create a hot fix model and only rerun failures

- Accept a certain level of model failure and disregard.

### Selection and rationale

Creating a hot fix model and only rerunning failures is the selected option. Model failures are inevitable. Creating hot fix models with appropriate checks and procedures can create a valid set of results.

If the team determines that the fix would significantly impact the successful events, a decision point for what to do with the successful events exists and a process for resolving that decision must be defined.

### Rationale for why the other options were not selected

Fixing an event and rerunning all simulated events that did not fail previously could be incredibly costly in terms of cloud execution costs.

Only fixing the failures generating annual maximums in the range of 1/5 to 1/2,000 but not rerunning models that succeeded was not selected because the majority of instabilities come from hydraulic modeling. Hydraulic models are only run in the range of 1/5 to 1/2,000.

Accepting failures (e.g., expect 1 percent of events to fail) could adversely impact rare events if the failures are due to high flow conditions. Putting in a check to verify the failure is indeed not part of the rare events can significantly mitigate this risk.

# —Results Evaluation

The FFRD methodology produces significant quantities of results. These results must be summarized into digestible and understandable results that support risk informed decision making.

## Mapping

FFRD is striving to have results across the geography showing graduated hazard and graduated risk.

### Options available

- Gridded Data

- Mesh Data.

### Selection and rationale

Selection for rationale

Depth grids for individual scenarios and overall AEP grids are the key map outputs envisioned for FFRD, although many other maps and reports will be of interest and could be produced.

Depth maps are viewed by HEC-RAS modelers as part of the model development and calibration phase of a project. These maps are viewed in a desktop environment and can be rendered via various HEC-RAS render modes with the Sloping/Precip Mode generally considered the most applicable for 2D rain-on-mesh models.

Depth grids are also produced for each individual scenario from the stochastic cloud compute. The methods available for grid production in the Linux-based cloud environment have some limitations as of May 2024. The HEC-RAS developers provided Linux-based code in April 2024 for use in the cloud environment replacing a custom mapping method used for earlier tests. Vector terrain modifications not merged into the TIFF terrain grid cannot be utilized with the tools as of May 2024, so merged versions of the terrain are being provided as inputs to the grid generation.

### Rationale for why the other options were not selected

Rationale for why each other option wasn’t selected.

## Mapped Output Resolution

Generating gridded mapped output requires the selection of a cell resolution for outputs. This resolution will impact usability.

### Options available

- Resolution of the terrain (roughly 1 meter)

- 3 meter

- 5 meter

- 10 meter

- 30 meter.

### Selection and rationale

For the Kanawha River Basin Pilot study, the resolution of the terrain was used. It is recommended that in future iterations a larger cell resolution is used—something closer to the 3–10 meter range. The Duwamish and Trinity River Basin Pilot studies will use 3 meter based on guidance from FEMA HQ supported by the PTS Flood Hazard Curves (FHCS), Benefits and Uses as a Potential Graduated Flood Hazard Product study dated December 2021.

### Rationale for why the other options were not selected

The Kanawha River Basin Pilot results were not computed at any other resolution based on direction to use the terrain resolution.

It was determined by PTS that 1 meter is not cost effective for use in FFRD studies and provides a potential misrepresentation of the accuracy of results.

## Gridded Hazard Variables

Gridded hazard variables describe a summary of a hazard variable at cells of consistent resolution across the domain of the watershed. Different hazard variables can be used for different purposes.

### Options available

- Max depth

- Max water surface elevation

- Max velocity

- Courant (velocity/distance)

- Courant (residence time)

- Froude

- Shear stress

- Stream sower

- Depth×velocity

- Depth×velocity<sup>2</sup>

- Energy (depth)

- Energy (elevation)

- Arrival time (depth threshold)

- Arrival time (hazard max)

- Duration

- Recession

- Percent time inundated.

### Selection and rationale

Max depth, max velocity, and depth×velocity and duration are the preferred options because they are directly applicable to FEMA use cases in consequence assessment, regulatory, insurance, and building code applications.

### Rationale for why the other options were not selected

The other variables were not requested by FEMA..

## Annual Exceedance Probabilities-specific Hazard Grids Frequency

Displaying AEP-specific hazard grids, such as the 100-year depth grid, provides a format relatively easily digestible for most end users. AEP-specific hazards, unlike AEP grids, require the specification of the list of AEPs for which hazards are produced.

### Options available

Any recurrence interval from the 5 to the 2,000 year.

### Selection and rationale

Per FEMA guidance, showing the standard eight frequencies (2-, 10-, 25-, 50-, 100-, 200-, 500-year return periods) is the required option. Notice that the 2-year is outside of the AEP range provided in the original FEMA requirements document.

### Rationale for why the other options were not selected

FEMA defined the frequencies needed for their prototype output viewer. No other options were considered.

## Consequences Output 

Consequences will be computed for either each event or each synthetic event year maximum grid—the synthetic event year maximum grids can create instances of unrealistic depth and velocity combinations that did not occur in a single event. If event consequences are computed within each synthetic event year, the maximum loss at a structure must be selected and leveraged, not the sum. These outputs describe the damages for each structure for each synthetic event year. The synthetic event year damages must be ranked and assigned plotting positions of 1/synthetic events per realization—this is a damage frequency curve. The damage frequency curve must be integrated to produce structure-specific AAL estimates. The simplest way to integrate it is to sum the synthetic event year losses and divide by the number of synthetic events per realization. These outputs must be stored.

### Options available

- Store AAL and damage frequency in the same file

- Store damage frequency separately from the AALs

- Store only the AALs and the synthetic year losses (rank at query time).

### Selection and rationale

For the Kanawha River Basin Pilot study the synthetic year losses were stored (permitting rank for damage frequency estimates on the fly) and AALs were produced in separate files. This was done to reduce duplicate files, and to explore the use cases with prototype data. If other data formats or organizations are needed, they can be produced from the synthetic year losses as the most raw type of data to leverage.

### Rationale for why the other options were not selected

Results of the cloud data formats investigation is necessary to test the retrieval speed of different formats and are needed prior to determining whether to separate damage frequency from the AAL estimates or to store them all in one file.

## Point-based Annual Exceedance Probabilities Estimate of a Hazard

Graduated hazard data must be provided in formats for visualization and query for any location in the United States. The query must provide hazard frequency relationships with uncertainty for any point in the United States. The query is designed to support Open Hazus and the rating engine for computation of consequences.

### Options available

- Output data at points along a structured triangular mesh

- Output data at regularized grids.

### Selection and rationale

For FFRD, point based estimates of AEP were provided in the coastal viewer. These point-based estimates were provided at every node in the Advanced Circulation (ADCIRC) mesh. This allows for interpolation from a triangulated irregular network (TIN) to a grid for visualization purposes. FFRD instead converts the output directly to a gridded format for query and display. This eliminates multiple steps of post processing and ensures the data was generated in a consistent way. Damages can be computed from the synthetic event year grids (if it is single parameter), the raw event grids, or the AEP-specific hazard grids (if it is single parameter).

### Rationale for why the other options were not selected

Output at a structured triangular mesh is not a preferred option because there is no authoritative triangular mesh for the United States in the inland. Interpolation of TIN surfaces requires a computational process to convert it into a visualization format. Instead, output was provided at grids, where the results can be queried to utilize or visually present the information.

## Separation of Consequences per Source/Contribution

Losses at structures can be due to flooding, tropical cyclones, or a breach event. These different sources may have different mitigation measures. Keeping track of the losses by source/contributing factor can enable additional analysis. Additionally, each breach event could be simulated with and without breach to identify the incremental loss due to breaching.

### Options available

- Track consequences resulting from breach events

- Track consequences resulting from tropical cyclones

- Recompute breach events with no breaches

- Do not separate losses by source.

### Selection and rationale

Breaches and storm types (including tropical cyclones) are tracked as part of the Trinity River Basin Pilot study, but not traced that out to which consequences are attributed to any of the events types—this can be done at a later date, but is not necessary for the current requirements provided by FEMA.

### Rationale for why the other options were not selected

Breach information is being tracked sufficiently to identify which events have breaches, if future requirements make the separation of consequences by source important, they can be separated through post processing.

## Comparison of Mapping Results to the Federal Emergency Management Agency National Flood Insurance Program Results

Outputs from FFRD throughout the pilot studies must be evaluated to determine if they are appropriate.

### Options available

- Complete comparison to the NFIP National Flood Hazard Layer (NFHL)

- Don’t complete comparison.

### Selection and rationale

NFIP NFHL comparison to the AEP grids should be performed to understand how well they compare. Places where discrepancies exist should be identified and understood. It is expected that maps will be different in some locations and conditions.

### Rationale for why the other options were not selected

It is not acceptable to forego minimal comparison to the NFHL data for understanding how this information relates to current products.

# References

Moriasi, D.N., et al. 2007. Model Evaluation Guidelines for Systematic Quantification of Accuracy in Watershed Simulations. Transactions of the ASABE, 50, 885-900. <http://dx.doi.org/10.13031/2013.23153>.

U.S. Army Corps of Engineers. (1994). Flood-Runoff Analysis, Engineer Manual 1110-2-1417. Washington, D.C.: USACE.

——. 2022. Federal Emergency Management Agency Future of Flood Risk Data Requirements. USACE. Retrieved from: <https://usace.dps.mil/:b:/s/TDL-CEMVK-PP-D-FEMAUSACE-FFRD/EehpqC6Dk8JPpfxNLRTdfXkBSG4Y9PDbcTQIbdbppOswkQ?e=RoqkEf>.

——. 2022. Future of Flood Risk Data Determining the Path: A look into modeling methodology. USACE. Retrieved from: <https://usace.dps.mil/:b:/s/TDL-CEMVK-PP-D-FEMAUSACE-FFRD/Efr_xu_z7JxJpa8gxA2OJUUB625ut4eNxmiZrVMPMQl2lw?e=treN4H>.

——. 2024. Hydrologic Engineering Center. HEC-HMS User’s Manual version 4.12. Retrieved August 30, 2024, from <https://www.hec.usace.army.mil/confluence/hmsdocs/hmsum/latest>.

# List of Acronyms and Abbreviations

**1D** one dimensional

**2D** two dimensional

**3DEP** 3D Elevation Program

**AAL** average annualized loss

**ACM** Actuary and Casualty Modeling

**ADCIRC** Advanced Circulation

**AEP** annual exceedance probability

**AORC** Analysis of Period of Record for Calibration

**APF** annual probability of failure

**BLE** base level engineering

**BW-12** Biggert-Waters Flood Insurance Reform Act of 2012

**COOP** Cooperative Observer Program

**CPFRA** Coastal Probabilistic Flood Risk Assessment

**CTP** Cooperating Technical Partners

**DEM** digital elevation model

**DTIC** Defense Technical Information Center

**DV** maximum of the instantaneous product of depth times velocity

**EDH** elevation derived hydrography

**EGM** Economic Guidance Memorandum

**EPA** U.S. Environmental Protection Agency

**ESPG** enhanced security pedestrian gate

**ET** evaporation and transpiration

**FEMA** Federal Emergency Management Agency

**FIS** Flood Insurance Study

**FFRD** Future of Flood Risk Data

**FRiSEL** Flood Risk Study Engineering Library

**FY** fiscal year

**G2CRM** Generation II Coastal Risk Model

**GIS** Geographic Information System

**GMT** Greenwich Mean Time

**GSSHA** Gridded Surface Subsurface Hydrologic Analysis

**gSSURGO** Gridded Soil Survey Geographic

**HDF** hydraulic output at a point

**HEC** Hydrologic Engineering Center

**HEC-FIA** Flood Impact Analysis

**HEC-HMS** Hydrologic Modeling System

**HEC-RAS** River Analysis System

**HEC-ResSim** Reservoir System Simulation

**HPC** high-performance computing

**HLRA** Higher Level Risk Assessment

**HUC** Hydrologic Unit Code

**IDF** intensity duration frequency

**kNN** k-Nearest Neighbors

**LiDAR** light detection and ranging

**LifeSim** Life Loss Estimation

**Livneh** Livneh CONUS Near-Surface Gridded Meteorological and Derived Hydrometeorological Data

**LST** Levee Screening Tool

**MHW** mean high water

**MIP** Mapping Information Platform

**MLW** mean low water

**MRMS-QPE** Multi-Radar Multi-Sensor Quantitative Precipitation Estimate

**MTL** mean tide level

**NAVD 88** North American Vertical Data of 1988

**NCEP** National Centers for Environmental Prediction

**NEXRAD QPE** Next-generation Radar Quantitative Precipitation Estimate

**NFHL** National Flood Hazard Layer

**NFIP** National Flood Insurance Program

**NHDPlus** National Hydrology Dataset Plus

**NID** National Inventory of Dams

**NLCD** National Land Cover Database

**NLD** National Levee Database

**NOAA** National Oceanic and Atmospheric Administration

**NRCS** Natural Resources Conservation Service

**NSE** Nash-Sutcliffe Efficiency

**NSI** National Structure Inventory

**NWIS** National Water Information System

**NWS** National Weather Service

**OEP** occurrence exceedance probability

**O&M** operations and maintenance

**OT** overtopping

**PBIAS** Percent Bias

**PDT** project delivery team

**PFM** potential failure mode

**PMF** probable maximum flow

**PMP** probable maximum precipitation

**POR** period of record

**PRISM** Parameter-elevation Regressions on Independent Slopes Model

**PTS** Production and Technical Services

**QA** quality assurance

**QC** quality control

**QRA** Quantitative Risk Assessment

**QL2** Data Quality Level 2

**RA** Risk Assessment

**RSR** Ration of the Root Mean Square Error to the Standard Deviation

**RTMA** Real-time Mesoscale Analysis

**SATSGO** General Soil Map of the United States

**SCS** Soil Conservation Service

**SHG** Standard Hydrologic Grid

**SLTT** State, Local, Tribal, and Territorial

**SOP** standard operating procedure

**SQRA** Semi-quantitative Risk Assessment

**SST** stochastic storm transposition

**SRP** system response probability

**SWAT** Soil and Water Assessment Tool

**SWE** snow water equivalent

**SWE-ELM** Shallow Water Equation, Eulerian-Langrangian Method

**SWE-EM** Shallow Water Equation, Eulerian Method

**SWE-LIA** Shallow Water Equation, Local Inertia Approximation

**TIN** triangulated irregular network

**USACE** U.S. Army Corps of Engineers

**USDA** U.S. Department of Agriculture

**USGS** United States Geological Survey

**VIC** Variable Infiltration Capacity

**VPN** virtual private network

**WBD** watershed boundary dataset
