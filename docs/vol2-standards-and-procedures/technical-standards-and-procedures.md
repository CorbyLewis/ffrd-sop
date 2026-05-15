# Technical Standards and Proceedures
#### Preface

This SOP volume outlines the authoritative technical standards and procedures for executing and delivering Future of Flood Risk Data (FFRD) projects.

#### Workflow

A standardized phased workflow greatly improves the ability of large FFRD teams to coordinate and communicate throughout the development of deliverables for individual basins. Furthermore, this standardized process benefits data management and enables national-level tracking of progress and the delivery of flood risk data at a national scale.

#### Technical Standards

The technical standards enforce a consistent and achievable national approach for developing flood risk information that is founded on rigorous science and leverages modern tools and state-of-the-practice techniques. The standards described in this volume deliver the requirements, and a separate volume provides the rationale for the selection of these requirements.

#### Job Aids and Processes

This volume includes multiple job aid appendices that represent specific detailed processes and workflows necessary for execution of FFRD projects. In some cases, alternative processes may be allowed and may be utilized to meet the requirements specifically stated in the main body of this volume.

#### Tools

The main body of this document relies on core models and tools that are publicly available and license free. Specifically, cloud-compute, HEC-HMS, HEC-ResSim, and HEC-RAS are embedded in the processes. Additionally, there are several helpful tools provided as appendices to this volume that may optionally be used to achieve the requirements described in the main body of this volume.

#### Templates

Several templates are provided as appendices to this volume to enforce standardization of documentation in the form of delivered reports, quality reviews, and certain aspects of delivered datasets.

## —Project Workflow and Review

This section defines the required workflow, deliveries and reviews. Resources for national-level technical support for teams executing FFRD projects are also described.

<span id="_Toc214891691" class="anchor"></span>Figure 2.1. High Level Workflow Diagram for an FFRD Basin Project

<img src="media/image1.png" style="width:3.70901in;height:5.25974in" />

#### Study Workflow

The FFRD study workflow described in this document is separated into five distinct phases (see Figure 2.1). The **Scoping and Data Preparation** phase includes analysis by a skilled technical team to prepare the shared datasets and define the specifics of scope. Once the basin is scoped and necessary data are developed, the basin study continues with the subsequent four phases (collectively referred to as Basin Execution). The **Calibration** phase includes the bulk of model development for the project and brings in a much larger team of modelers to develop, calibrate, review, and deliver each of the constituent models for the study. During the **Conformance** phase, the models are fully linked together by a smaller modeling team and tested in a stochastic environment to ensure frequency-based results reasonably align with long-term observed data. The **Production** phase produces many model simulations for the entire model suite for multiple realizations. These simulations are the basis for all final delivered results. The **Final Reporting** phase communicates and documents the final results and refers to the detailed documentation that is created throughout the phases. High-level tasks associated with each phase of the process are provided in the Appendix E graphic (FFRD Project Task Matrix). Various quality control (QC) and quality assurance (QA) checks of the products are built into each of these phases.

<span id="_Toc214891692" class="anchor"></span>Figure 2.2. Major Phases of FFRD Workflow

<img src="media/image2.png" style="width:4.3in;height:3.91693in" alt="Diagram AI-generated content may be incorrect." />

###### Basin Selection

The process of FFRD basin study selection is the responsibility of the National Implementation Management Group in coordination with the Steering Committee. FEMA Program Manager collates the list of prospective basins with support from National Implementation Team members. Basin selection may be derived from a variety of sources including HQ or FEMA region priority. Prospective basins are presented by FEMA to the Steering Committee where FEMA HQ representatives and steering committee members confirm basins meet selection criteria, the SOP is applicable, and required data are available. After a basin is selected for study and funding is available, scoping and data preparation can begin.

###### Project Work Plans

All phases of FFRD work will be guided by signed and approved project work plan (PWP) documents and will used to define project goals and team member roles. There are two distinct PWP documents: The scoping project work plan (S-PWP) and the basin execution work plan (BE-PWP). The team lead supplies the technical aspects, while the PM develops detailed budget and schedules.

###### Scoping and Data Preparation Phase

This phase includes a significant amount of technical analysis to ensure that the future overall modeling effort can proceed with reliable and consistent data that will be coordinated across a large team of modelers. A data preparation team lead, data preparation project manager, FEMA representative, and other roles are assigned to a selected basin. The team lead assigns other roles as needed and initiates the data collection process. In project leadership roles, the team lead has the primary responsibility for development of technical data and scoping elements for the basin study in direct coordination with the project manager, who is responsible for project schedule, budget, tracking, and communication. Key stakeholder meetings are held to aid in data collection and preparation. The scoping and data preparation phase is considered complete once all review checklists have been posted, all items have been closed, and the team lead has deemed the data suitable for advancing to the basin study. The basin is then presented to the TOG for high-level technical review and approval. Once this step is completed, the calibration phase can begin.

###### Calibration, Conformance, and Production Phases—Basin Execution

Upon completion of the scoping and data preparation phase, a basin study team lead, basin study project manager, and a FEMA representative are assigned to the basin. These individuals may remain the same as those in the scoping and data preparation phase. The basin study project manager and team lead develop the BE-PWP, which includes budget and schedule details and identifies key team members. The basin technical team lead assigns additional roles within the team. The project manager and team lead then schedule and facilitate the basin kickoff meeting, after which modeling begins.

Modeling continues in accordance with the methods and procedures defined in this SOP. The steps, processes, and guidelines outlined in the following sections are followed to ensure consistency, accuracy, and compliance with established protocols throughout the modeling phases. Throughout the basin study, the TOG and assigned SME reviewers conduct formal evaluations and technical reviews confirming each study phase is complete and ready for promotion to the next production phase through project completion. The high-level technical TOG reviews occur at the end of the calibration, conformance, and production phases.

###### Final Reporting Phase–Basin Execution

After the final TOG meeting and acceptance of the final basin results and reports, the completion of all result summaries, final reports, and review documentation close-outs can take place, following established documentation standards, practices, and templates. The study technical team lead ensures that all data is uploaded, archived for future use, and that file maintenance is performed in accordance with these standards as part of the close-out process.

#### Collaboration Best Practices

FFRD project delivery teams (PDTs) must operate in close collaboration throughout the process to be successful as many aspects of the modeling require interaction between models being developed by separate individuals. It is recommended that the team lead facilitate weekly team meetings during the model development phases of the project. The regular calls should follow a format that encourages team interaction and discussion of the relevant issues for upcoming key decisions.

In addition, it is recommended that the program manager hold regular meetings with all active team leads, to facilitate technical discussion of issues and concerns occurring across multiple teams.

###### Early Model Calibration—Output Data Exchange

A critical phase exists during development of initial calibrated models where outputs from the hydrologic model are required for the calibration of the reservoir operations and hydraulic models. Coordination may be required when the hydraulic model has difficulty achieving calibration and may point out a technical consideration that leads to an edit to the hydrologic model. Similar exchanges and coordination are required as models are updated in response to formal review comments. This type of exchange does not constitute a formal review but is absolutely required for project success. It cannot be done without regular team collaboration.

###### Authoritative Input Dataset Changes

While the data prepared in the scoping and data preparation phase is carefully planned and thoroughly reviewed, the need for changes may be discovered during the basin execution phases. Any changes to the authoritative input dataset require coordination across the different sub-model teams. When updates are required, the centrally stored dataset on Model Library will be updated and corresponding updates to the Data manifest will be made.

###### Communication and Collaboration Tools

Modeling efforts for the FFRD program are a large effort that requires many team members working together in a cohesive manner. Use of modern tools for full team communication and collaboration is encouraged. For example, centralized discussion forums that log communications amongst team members have to potential to create a searchable record of the resolution of common issues or to distribute team-wide guidance more efficiently than regular meetings or email distribution lists.

--

#### Review Processes

Reviews across all levels of work are necessary for project success. The review manager assigns reviews and ensures reviewers complete the review on each work package. The technical team lead ensures review comments are sufficiently addressed. After comments are sufficiently addressed, the review manager elevates basins to the TOG for review. Figure 2.4 shows specific reviews that must be documented via review checklists. Any technical issues at the team level that require resolution may be elevated to the TOG. Issues that cannot be resolved at the TOG are elevated to the Steering Committee for final resolution.

<span id="_Toc213944102" class="anchor"></span>Figure 2.3. Major Phases of FFRD Workflow and Associated Reviews.

<img src="media/image3.jpg" style="width:6.5in;height:5.84167in" alt="Major phases of the workflow are broken into five phases: Scoping and Data Preparation, Calibration, Conformance, Production, and Final Reporting. Required reviews in these phases are categorized into FEMA Leadership/TOG and team QC responsibilities. Prior to the Scoping &amp; Data Preparation phase, the team completes a basin selection checklist verifying established criterion for basin selection were met. FEMA Leadership/TOG approves the basin for study. During the Scoping &amp; Data Preparation phase, the team completes the data preparation checklist ensuring data preparation tasks are complete. Between the Scoping * Data preparation and Calibration phases, FEMA Leadership/TOG completes a TOG review. At the end of the Calibration phase, the team completes the Meteorology, hydrologic, reservoir operations, breach input, hydraulic, and consequences review checklists ensuring work in each of these areas meets established standards. The FEMA Leadership/TOG performs a TOG Review. As the Conformance phase begins, the team completes a pre-conformance checklist ensuring the project is ready for the Conformance phase. At the end of the Conformance phase, the team completes the Conformance checklist ensuring Conformance was complete per the SOP and the FEMA Leadership/TOG performs a TOG review. At the end of the Production phase, the team completes the production checklist and the FEMA Leadership/TOG completes a TOG Review. During the entirety of the basin study, a master quality review checklist is maintained and completed during each phase ensuring steps from one phase are complete prior to the next phase beginning." />

###### Technical Internal Reviews

Several technical QC reviews are conducted throughout the project. Each review is documented in the form of a checklist. Template checklists with a pre-specified review prompts are provided as a supplement to this SOP. These checklists include fields for:

- Basin Name

- Team Member Name (producer of the work to be reviewed)

- Review Name

- Review Dates

- Comment for each item (required entry, even if it is confirmation that item was and checked and standard was confirmed)

- Backcheck and Closeout Discussion

- Status Tracking of each item (Open/Closed)

- Allowance for additional comments that reviewers may not think fit within the pre-defined checklist items.

An overview of the specific review checklists is listed below.

- Master Quality Review—Primary tracking checklist to ensure major project actions are taken prior to advancing to subsequent phases. For example, the Master Quality Review checklist forces the review manager to confirm that the other technical review checklists have been completed.

- Basin Selection Review—Checklist to ensure the proposed basin has adequate data available to successfully execute a FFRD project prior to starting the scoping and data preparation phase.

- Breach Input Review—Checklist to ensure proper delivery of system response curves for infrastructure.

- Data Preparation Review—Checklist to ensure completeness and accuracy of the data preparation processes.

- Meteorology Review—Checklist to ensure technical accuracy of the meteorologic data inputs as well as completeness of documentation.

- Hydrologic Review—Checklist to ensure technical accuracy of the Hydrologic Engineering Center’s Hydrologic Modeling System (HEC-HMS) model as well as completeness of documentation.

- Reservoir Operations Review—Checklist to ensure technical accuracy of the Reservoir System Simulation (HEC-ResSim) model as well as completeness of documentation.

- Hydraulic Review—Checklist to ensure technical accuracy of the HEC-RAS model as well as completeness of documentation.

- Consequences Review—Checklist to ensure technical accuracy of the structure inventory as well as completeness of documentation.

- Pre-Conformance Review—Checklist to ensure the full system of models is ready to accept generalized synthetic storms, re-confirm naming conventions were followed, ensure model linkages are clearly documented, and ensure results from cloud compute can be replicated in a desktop environment.

- Conformance Review—Checklist to ensure the system of models meet metrics for comparison to long-term observed data after cloud compute for a single realization of synthetic events.

- Production Review—Checklist to ensure all results from the full set of realizations are acceptable.

###### Technical Oversight Group Reviews

The TOG provides technical advice, oversight, and project review at a programmatic level. This panel is charged with managing the risks to program execution and credibility. The technical team lead for each basin prepares a presentation and presents results up to the current level of study for the four TOG review engagements.

The TOG reviews each basin at four progress points—after scoping and data preparation phase, after model calibration phase, after model conformance phase, and at the conclusion of the production phase. The TOG meets when reviews are available at up to a monthly basis. Effort will be made to group reviews into presentation meetings with at least three basins presented.

Phase documentation will be provided to the TOG at least 2 weeks prior to a presentation meeting. Presentations would be expected to be a high-level technical overview of completed work, and last from 1 to 2 hours.

The TOG committee provides high-level QA and consistency review comments on the technical aspects of the calibration, conformance, and production work products. Basin modeling teams address comments that fall within the scope of the SOP. Comments outside of the scope of the SOP will be evaluated by the FEMA representative to determine risk to the project and will either be scoped as an additional effort to the ongoing project or flagged as future update to the SOP.

TOG comments will typically be backchecked by the review manager for minor comments, however, TOG may request presentation of a basin again, if significant quality concerns need to be addressed. After TOG comments are satisfied and closed, the FFRD team may proceed to the next phase of the project.

###### Documentation of Reviews

All reviews must be documented with saved comment and comment resolution information. Each FFRD project uses standardized review checklist templates provided as part of the SOP and used to document reviews. Review checklists are maintained within the documentation folder within the basin repository in the Model Library. All review templates allow for free-form commentary on key aspects of the review that may not be directly included in the checklist. All review documentation shall be uploaded within the documentation folder for each discipline.

#### Change Management during Basin Studies

When issues arise that prohibit production of FFRD results, deviations from the SOP may be justified. Production teams should submit deviation request that describe the constraints and proposed remedy to FFRD program leadership, and any approved deviations will be recorded in a signed memo.

#### National Level resources for Support and Review

A comprehensive organizational and governance structure for the FFRD program serves to clarify the roles, responsibilities, and authorities of individuals/agencies needed to ensure program success. This support structure is described in Volume I of this SOP.

###### Basin Advisors

Basin advisors from USACE with experience developing early FFRD pilot projects will be available to support basin production teams. This role is expected to be critical for early basin production activities and may diminish over time as collective experience with SOP procedures is gained.

## —Standards

#### Modeling System and Plugins

The FFRD program is executed in a cloud-based environment requiring each model to have a plug-in to connect with the environment. This SOP references specific plugins that are available for programs built by the HEC and tailored to operate in a cloud environment.

There are various alternative options for modeling systems that simulate the hydrologic, hydraulic, reservoir operations, system performance, and consequence response to storm events that could be possible to apply to an FFRD project. It is recognized that building the standards and procedures for alternative systems would be a significant effort and would require coordination and approval from FFRD leadership.

#### Projection

The Albers Equal Area Projection will be used for the FFRD program. See Table 3.1 for specific parameters associated with the standard projection.

<span id="_Toc214892755" class="anchor"></span>Table 3.1. Parameters for Standard Albers Equal Area Projection for\
Future of Flood Risk Data Study Watersheds in the Contiguous United States

| PROJCS     | USA_Contiguous_Albers_Equal_Area_Conic_FFRD |
|:-----------|---------------------------------------------|
| GEOGCS     | GCS_North_American_1983                     |
| DATUM      | D_North_American_1983                       |
| SPHEROID   | GRS_1980, 6378137.0, 298.257222101          |
| PRIMEM     | Greenwich, 0.0                              |
| UNIT       | Degree, 0.0174532925199433                  |
| PROJECTION | Albers                                      |
| PARAMETER  | False_Easting, 0.0                          |
| PARAMETER  | False_Northing, 0.0                         |
| PARAMETER  | Central_Meridian, -96.0                     |
| PARAMETER  | Standard_Parallel_1, 29.5                   |
| PARAMETER  | Standard_Parallel_2, 45.5                   |
| PARAMETER  | Latitude_Of_Origin, 23.0                    |
| UNIT       | Foot, 0.3048                                |

Certain exceptions may apply for studies outside of the continental for each levee breach location U.S. In those cases, state plane projection for the state where the majority of the modeling unit resides may be used. Any deviations from the standard Albers Projection must be approved by the FFRD National Implementation Group.

#### Vertical Datum

The North American Vertical Datum (NAVD 88, feet) will be used for all FFRD products. Elevation conversion from local project information may be necessary. When conversions from other standard vertical datums are required, the [National Oceanic and Atmospheric Administration (NOAA) Vertical Datum Transformation Tools](https://vdatum.noaa.gov/) may be applied but must be documented in FFRD reports and models. When federal dam owners’ official vertical datum conversion values are available, they will be used directly.

Certain exceptions may apply for lands that do not coincide with the NAVD 88 footprint (e.g., Hawaii and Puerto Rico). Any deviations from the standard NAVD 88 datum must be approved by the project technical lead.

#### Digital Elevation Models

<u>Digital Elevation Model (DEM) Quality Standard</u>: FFRD projects will use a DEM based on light detection and ranging (LiDAR) data of Topographic Data Quality Level 2 (QL2) or better, as defined by [U.S. Geological Survey's (USGS’s) Topographic Data Quality Levels](https://www.usgs.gov/3d-elevation-program/topographic-data-quality-levels-qls) (QLs). If QL2 data is not available, a lower quality DEM may be acceptable after coordination with the technical team lead during the scoping and data preparation phase.

<u>DEM Minimum Quality</u>: If QL2 data is not available for the study, the minimum requirement for the initiation of an FFRD study is basin-wide availability of the USGS 3D Elevation Program (3DEP) 1/3 arc-second DEM. This dataset is currently available for the entire continental United States (CONUS), Alaska, Hawaii, and Puerto Rico.

<u>DEM Scoping Consideration</u>: A lack of availability of a high-quality DEM may be considered in the prioritization and schedule of basins to receive FFRD study. Procurements of QL2 data may be justifiable as part of the study and must be coordinated with FEMA FFRD leadership during the development of the S-PWP for the scoping and data preparation phase.

<u>Bare Earth</u>: The official DEM for the study will represent bare earth elevations. The DEM does not represent elevations associated with buildings or vegetation.

<u>Hydro-connections, Hydro-corrections, and Reconditioning</u>: The official DEM for the project may include adjustments to allow for drainage paths when readily available. This is not a requirement for the official delivered DEM and should not be considered an additional scope item during the data preparation phase.

<u>DEM Resolution</u>: Standards for DEM Resolutions are provided in the table below.

<u>Nationwide Reference Grid Standard</u>: To maintain consistency across FFRD deliverables, all DEMs and derivative gridded data must align to a single, nationwide reference grid. This grid is defined as follows:

- **Projection**

  USA_Contiguous_Albers_Equal_Area_Conic_FFRD

- **Base Cell Size**

  4 feet or an exact multiple thereof

- **Reference Origin**

<!-- -->

- False Easting: 0.0 ft

- False Northing: 0.0 ft

- Central Meridian: -96.0 degrees

- Latitude of origin: 23.0 degrees

<!-- -->

- **Snapping Rule**

  All DEMs and derivative grids must be generated such that their origin coordinates and cell boundary coordinates in the standard projection fall exactly on integer multiples of the base cell size.

<u>DEM Tiling</u>: The full-resolution, official DEM will be delivered in a format that is practical for hydraulic model development purposes. A 3 gigabyte (GB) file size is considered the practical upper limit for hydraulic model development, and DEMs are delivered in a tiled format such that individual model units are at or below that file size limit. Delivery of tiled full resolution DEMs also allow for variation of cell size across the study basin.

<u>DEM Extent</u>: The DEM must include a large buffer beyond the study extent boundary, which minimizes possible re-work associated any changes that may occur during scoping.

<u>DEM File Format</u>: The base-terrain DEMs are delivered in cloud optimized GeoTIFF format.

<u>DEM Official Delivery</u>: The highest quality available DEM for the entire basin will be prepared and used as the foundation of the study. The DEM will be delivered during the scoping and data preparation phase and be used as the official base DEM for the FFRD project. An alternate lower resolution version will also be prepared for the project and will be based on a down-sampling of the official full resolution DEM. PDT members will not use other DEM data sources. Job Aid 06, *Standard Naming Conventions*, describes the DEM file name standard. Procedures for searching for DEM source, FFRD DEM development processes, and FFRD format of delivery is elaborated in Job Aid 02, *Data Preparation Processes*.

<span id="_Toc214892756" class="anchor"></span>Table 3.2. Base Digital Elevation Model Terrain Delivery Versions

<table style="width:100%;">
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 37%" />
<col style="width: 37%" />
</colgroup>
<thead>
<tr>
<th>Official DEM Delivery</th>
<th>Storage Location</th>
<th>Description and Purpose</th>
<th>Pixel Size and Origin</th>
</tr>
</thead>
<tbody>
<tr>
<td>Full Resolution DEM</td>
<td>terrain-base directory</td>
<td><p>The highest quality available bare earth DEM for the entire basin. This full resolution DEM will be used as the basis for:</p>
<ul class="incremental">
<li><p>Hydraulic Model Geometry Development and Pre-processing</p></li>
<li><p>Delineation of Hydraulic Model Units and Hydrologic Model subbasins.</p></li>
<li><p>Development of Elevation Derived Hydrography (stream centerlines)</p></li>
</ul></td>
<td><p>Highest resolution DEM supported by Lidar quality level, rounded to an even value in feet. Typically, a 4-foot resolution DEM based on QL2 Lidar data. If alternative base DEM resolutions proposed, careful consideration must be given to the impact of edge-snapping with other products. Resolution may vary across basin if tiling is used.</p>
<p>The reference origin must be used.</p></td>
</tr>
<tr>
<td>100-foot DEM</td>
<td>terrain-base directory</td>
<td>Down-sampled version of full resolution DEM. Lower resolution terrain used for hydrologic model parameterization and general basin overview maps.</td>
<td><p>100-foot pixels</p>
<p>The reference origin must be used.</p></td>
</tr>
</tbody>
</table>

#### Hydraulic Model Terrains

The hydraulic modeling process involves the conversion of the official source DEM into HEC-RAS-formatted terrains. These terrains can accept additional RAS Mapper terrain modifications for a variety of purposes and may incorporate other data sources such as bathymetry layers. Guidance on development of RAS Mapper terrains for FFRD studies are described in Section 8.6 and in Job Aid 13, *Model Delivery for Cloud Compute*. Required deliveries of final RAS Mapper terrain datasets that are developed during the Calibration Phase are summarized in the table below. The file name standard for the hydraulic model terrains is shown in Job Aid 06, *Standard Naming Conventions*.

<span id="_Toc214892757" class="anchor"></span>Table 3.3. Hydraulic Model Terrain Versions

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 18%" />
<col style="width: 39%" />
<col style="width: 26%" />
</colgroup>
<thead>
<tr>
<th>RAS Mapper Terrain Delivery</th>
<th>Storage Location</th>
<th>Description and Purpose</th>
<th>Pixel Size and Origin</th>
</tr>
</thead>
<tbody>
<tr>
<td>Modeling Terrains</td>
<td>terrain-production directory</td>
<td>Central storage location for RAS Mapper terrain (including vector modifications) used as the input for each model geometry. A single terrain is required for each HEC-RAS model unit (i.e., multiple versions of terrains are not allowed). These terrains are intentionally stored at a higher-level directory to allow them to be accessed centrally during various phases of the workflow without redundancy.</td>
<td><p>Use full resolution terrain for model development, typically 4-foot cells.</p>
<p>Consistent origin should be maintained as best practice to maintain snapped edges.</p></td>
</tr>
<tr>
<td>Mapping Terrains</td>
<td>terrain-mapping directory</td>
<td>Final HEC-RAS terrain (with any modifications merged into the single tif) associated with each model unit, which is used specifically in development of mapped output grids such as depth.</td>
<td><p>Use 12-foot cell resolution for mapping terrain.</p>
<p>Reference origin must be maintained.</p></td>
</tr>
</tbody>
</table>

#### Time Zone

Coordinated Universal Time (UTC) is the time standard used for all FFRD projects.

#### Observed Gridded Datasets

Observed temperature and precipitation gridded datasets are used as boundary conditions for modeling efforts for FFRD projects.

For single storm event models, the minimum gridded dataset resolution required is 4-kilometer cells with an hourly time step.

For long term simulations (i.e., period of record \[POR\]), the minimum gridded dataset resolution required is the 4-kilometer with a daily time step.

Increased resolution (i.e., smaller cells or shorter time steps) may be scoped for the study when the data is available and can be applied practically in terms of model development and compute times.

#### Naming Conventions

For successful integration of the models, all models and directories must use consistent naming conventions. The Job Aid 06, *Standard Naming Conventions*, defines the standard naming conventions for watershed level model data as well as for each constituent model.

#### Data Storage Location

The FFRD datasets will be centrally stored in an S3 cloud repository on the government cloud.

#### Model Library Interface

The [Model Library](https://model-library.sec.usace.army.mil/) will be used as the interface for cloud-based storage that can be accessed by all team members based on user-based access roles. Job Aid 07, *Model Library Use*, contains details on Model Library access and use.

#### Standard Directory Structure

Models are developed and calibrated by individual team members during the FFRD development process with the overall goal of creating a combined system of models accounting for the complex meteorologic, hydrologic, operations, and consequence phenomena for the entire study basin. Team collaboration throughout the development process is needed to produce a robust and complete system model as the end state.

The standard directory structure and Model Library serves as the central cloud storage location and is accessible by all team members and all organizations throughout the life cycle of the entire project. Sections 3.11.1 through 3.11.10 describe the purpose of each high-level directory. Job Aid 07, *Model Library Use*, provides additional details on the use of the directory including standard sub-directories.<span id="_Toc214891694" class="anchor"></span>

Figure 3.1. Top level standard directory for an FFRD project.

<img src="media/image4.png" style="width:3.78465in;height:3.79204in" />

###### *basin-data* Directory

The basin-data directory stores all official shared datasets for the project, which are delivered in the scoping and data preparation phase. Ad-hoc sharing of unofficial data shall not be posted to the basin-data directory.

###### quick-share Directory

Temporary ad-hoc shared data can be shared among team members through the quick-share directory. This allows sharing amongst team members files that are temporary in nature, but useful for collaboration or technical discussions.

###### documentation Directory

The documentation directory is the centralized storage of all work plans, reports, and reviews for the entire project. The documentation will advance from draft stages to final products within this location.

###### terrain-base Directory

This directory contains original delivered base DEM for use in project that was gathered as part of pre-model data preparation. There should be multiple resolutions as defined in Section 3.5.

###### terrain-modeling Directory

This directory contains RAS Mapper-formatted terrains used for HEC-RAS model development. Section 3.5 provides more information.

###### terrain-mapping Directory

This directory contains modified, RAS Mapper-formatted terrains used specifically in development of mapped output grids. Section 3.5 provides more information.

###### calibration Directory

This directory contains individual models through event-based calibration phase. These models and associated datasets undergo review and back check. If model files are updated due to a review, the previous version is first moved to the archive directory of individual model folders. This update and archival process may continue as models progress from draft to final delivery. Note that documentation and terrain files associated with each hydraulic model are posted to separate directories (*documentation* and *terrain-modeling* and should not be included here).

###### conformance Directory

Model files for the conformance phase are stored in the Model Library watershed repository under *conformance*. Final individual models from the calibration phase are promoted to the conformance directory, integrated, executed in cloud compute, and adjusted to reasonably align with long term observed data in frequency space. When adjustments are necessary to individual models, outdated models are moved to the archive subdirectory and replaced with the current version. Integrated models run through many simulations in cloud compute and results are stored here. Note that documentation and terrain files associated with each hydraulic model are posted to separate directories (*documentation* and *terrain-modeling* and should not be included here).

###### *production* Directory

Model files for the production phase are stored in the Model Library watershed repository under *production*. Final models from the conformance phase are promoted to the production directory and production simulations are executed in cloud compute and output data is stored here. When hot fix model edits are needed for individual events, a *hotfix* subdirectory will be created to store the model versions. Note that documentation and terrain files associated with each hydraulic model are posted to separate directories (*documentation* and *terrain-modeling* and should not be included here).

#### Templates

Appendix E contains the checklist templates. Appendix B contains the documentation templates.

###### Review Documentation Templates

Each FFRD project uses standardized review documentation. Review checklist templates for each pre-defined review stage are provided as part of this SOP and are used to document reviews. All review templates include a list of items that must be checked and commented on in the review but also allow for free-form commentary on key aspects of the effort that may not be directly included. Review checklists are maintained within the *documentation* folder within the basin repository in the Model Library.

###### Project Report Templates

The FFRD program will use standardized technical report templates for each individual modeling effort as well as the overall combined project delivery report.

###### Management Templates

The FFRD program will use standardized templates for management documents such as the PWPs.

## —Scoping and Data Preparation

Watershed studies for FFRD require a large team working in a coordinated manner. The scoping and data preparation phase is a significant effort executed by a relatively small team to define the specifics of the project scope and ensure an authoritative common input dataset is in place to be used by the entire team throughout the subsequent phases. In addition to data collection and coordination efforts, this phase includes modeling and analysis tasks to ensure that the scope of individual model efforts (to be initiated by a larger team in the subsequent calibration phase) are well defined.

<span id="_Toc214891695" class="anchor"></span>Figure 4.1. Context of Scoping and Data Preparation Phase in Overall Workflow

<img src="media/image5.png" style="width:3.25in;height:4.60882in" />

#### Project Work Plan—Scoping and Data Preparation Phase

A S-PWP will be developed to outline the team, tasks, schedule, and budget for the scoping and data preparation phase of an FFRD project.

#### Stakeholder and Data Provider Engagement

During the scoping phase, a list of agency stakeholders and data providers is developed, and engagement meetings are held. Stakeholders are provided an overview of the planned work and the planned schedule for the FFRD project, which will focus on flood concerns in the basin. During engagements, the PDT surveys stakeholders regarding the most important aspects of flooding in the basin. Data providers are encouraged to provide information or data related to existing studies or models that may be useful for the FFRD study and offer general feedback. The PDT provides periodic progress updates to the stakeholder group throughout the project.

#### Scoping

Several overall modeling approach decisions are made during the scoping phase that impact the proposed cost, schedule, and budget for the subsequent basin execution phases of the project. A decision on the ability to move forward with currently available data must also be made. Sections [4.3.1 through [4.3.18](##_Ref215568537) describe several of the high-level considerations for scoping.](##_Ref215568526)

###### [<span id="_Ref215568526" class="anchor"><span id="_Toc217044242" class="anchor"></span></span>Watershed Study Extent](##_Ref215568526)

[FFRD studies are typically scoped based on their USGS watershed boundaries dataset (WBD) HUC-4 boundaries. Existing WBD boundaries will be reviewed during project scoping for possible adjustments due to hydrologic interactions with adjacent basins or other considerations. Adjustments to the boundary for the modeling effort will be clearly documented, justified, and described in the BE-PWP and project reports. Note that the HUC-4 boundary is used for project planning and early scoping, but higher resolution boundaries based on the FFRD high quality DEM will be used to create more detailed and accurate boundaries that will be used in the models themselves as described in other sections of this document.](##_Ref215568526)

###### [<span id="_Toc217044243" class="anchor"></span>External Boundary Condition Data](##_Ref215568526)

[The FFRD methodology requires external boundary conditions (e.g., upstream inflow, downstream stage) as key inputs to a basin study. The general strategy is to develop models sequentially from headwaters to outlets, however, this may not always be possible or advantageous. Large and/or complex modeling domains may require additional boundary conditions to accurately estimate flood frequency at critical locations. The availability of external boundary condition information will be confirmed as part of the FFRD project scoping phase. There may be more complex interactions across basins requiring adjustments to the methodology, and they will also be defined during this phase.](##_Ref215568526)

###### [<span id="_Toc217044244" class="anchor"></span>Elevation Data Availability](##_Ref215568526)

[The FFRD standard for elevation data quality is defined in Section 3.3, along with a description of cases where deviation from the QL2 quality standard may be accepted or cases where field data collection may be scoped as part of the FFRD basin.](##_Ref215568526)

###### [<span id="_Toc217044245" class="anchor"></span>Stochastic Storm Transposition Application](##_Ref215568526)

[The methodology described in this SOP relies on SST techniques. The method is driven by a catalog of historic observed storms within a transposition domain that is larger than the study basin. The ability to identify a transposition domain, an assessment of applicable storm types, and the availability of long term observed temperature and precipitation data of sufficient spatial and temporal resolution for the domain will be assessed during the scoping phase of the project.](##_Ref215568526)

###### [<span id="_Toc217044246" class="anchor"></span>Observed Stream Gage Data Availability](##_Ref215568526)

[The availability of observed stream gage data is assessed as part of the FFRD project scoping phase. This data is cross referenced with the available observed gridded precipitation and temperature data. The scoping team must ensure a full calibration dataset exists to support the subsequent basin execution phases of the project. If adequate data is not available, the approach to the overall effort should be coordinated with FEMA FFRD leadership.](##_Ref215568526)

###### [<span id="_Toc217044247" class="anchor"></span>Observed Gridded Data Availability](##_Ref215568526)

[A substantial record of gridded precipitation and temperature data is a requirement for the methodology described in this SOP. Availability of these datasets will be confirmed during the scoping phase of the project. Three categories of observed gridded data are required:](##_Ref215568526)

- [Several significant historic events over the study basin](##_Ref215568526)

- [Long-term POR over the study basin](##_Ref215568526)

- [Storm catalog of large events within the larger transposition domain](##_Ref215568526)

###### [<span id="_Toc217044248" class="anchor"></span>Locations for Calibration](##_Ref215568526)

[All stream gages with a significant period of observed data are used for calibration of the FFRD models. Each of the gages are categorized as either primary, secondary, or tertiary gages to describe the hierarchy for use in model calibration. More rigorous calibration metrics (as described in separate chapters of this SOP) are used for primary gages than for secondary or tertiary gages. The gages are categorized during the scoping phase to ensure consistency in calibration targets across all FFRD modeling efforts for the basin. Guidance for categorizing gages is defined in Job Aid 01, *Scoping Processes*.](##_Ref215568526)

###### [<span id="_Ref215568779" class="anchor"><span id="_Toc217044249" class="anchor"></span></span>Identify Calibration Events](##_Ref215568526)

[Historic storm events to be used for calibration of the hydrologic and hydraulic models are selected during scoping. Generally, the largest observed historic events that have occurred in the basin are selected. The availability of both reliable observed stream gage data and gridded precipitation and temperature data must be verified for each selected event. Consideration is also given to events that have occurred in varied spatial domains within the study watershed. More recent historic events may be given preference as they may better reflect current basin conditions and may have higher quality observed data. Specific time widows for the events will be clearly defined in the scope. The guidelines for selecting events for calibration are described in Job Aid 01, *Scoping Processes*.](##_Ref215568526)

###### [<span id="_Toc217044250" class="anchor"></span>Hydraulic Modeling Unit Delineation](##_Ref215568526)

[FFRD studies are typically scoped for large-scale basins, and developing full basin 2D hydraulic models at this scale is generally deemed impractical using the computing capability available with current technology. Therefore, smaller hydraulic modeling units are delineated during the scoping phase. Model units will be delineated according to guidance contained in Job Aid 01, *Scoping Processes*, which includes considerations for total drainage area, calibration locations, model linking strategy, dam locations, and levee locations among other factors.](##_Ref215568526)

###### [<span id="_Ref215569527" class="anchor"><span id="_Toc217044251" class="anchor"></span></span>Hydraulic Mesh Development Scope](##_Ref215568526)

[FFRD hydraulic models are created using a relatively coarse background mesh but include higher resolution and a more detailed mesh for specific streams, floodplains, and populated areas. Layers that define the scope for mesh development are created during the scoping phase according to the guidance and procedures provided in Job Aid 01, *Scoping Processes*. Four distinct geospatial mesh development scope layers are created during the scoping phase, and Table 4.1 shows the definition and purpose of each of the layers. The specifics regarding the model treatment for each layer are described in Chapter 8.\
](##_Ref215568526)

[<span id="_Toc214892758" class="anchor"></span>Table 4.1. Mesh Development Categories and Intended Use](##_Ref215568526)

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 41%" />
<col style="width: 41%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Mesh Development Category</a></th>
<th><a href="##_Ref215568526">Definition and<br />
Criteria for Selection</a></th>
<th><a href="##_Ref215568526">Intended Use of Output</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Background Mesh</a></td>
<td><a href="##_Ref215568526">All areas not covered by other development categories.</a></td>
<td><a href="##_Ref215568526">Produce basin-wide H&amp;H data at a coarse resolution that may be leveraged for separate detailed modeling efforts. Provide approximate pluvial and fluvial flood information.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Urban Areas<br />
(polygons)</a></td>
<td><a href="##_Ref215568526">Polygons sourced from U.S. Census <em>urban areas</em> layer that account for density of development, land cover, development type, and other factors.</a></td>
<td><a href="##_Ref215568526">Produce reliable pluvial and fluvial flood risk mapping results in populated areas.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Key Streams<br />
(lines)</a></td>
<td><a href="##_Ref215568526">All streams with a contributing drainage area greater than 100 square miles; all streams with an existing Flood Insurance Study (FIS) supporting AE, AH, or AO zone delineation; or streams having an active stream gage with useful observed data for calibration.</a></td>
<td><a href="##_Ref215568526">Accurate routing of flood water through larger streams. Accurate flood risk mapping from fluvial sources for the most critical streams in the basin.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Other Streams<br />
(lines)</a></td>
<td><a href="##_Ref215568526">All streams with a contributing drainage area greater than 0.25 square miles.</a></td>
<td><a href="##_Ref215568526">Improve accuracy of routing of flood water through smaller streams. Moderately improve accuracy of fluvial flood risk mapping along those streams.</a></td>
</tr>
</tbody>
</table>

###### [<span id="_Toc217044252" class="anchor"></span>Land Cover Data](##_Ref215568526)

[The [National Land Cover Database](http://www.mrlc.gov/) (NLCD) will be obtained during the scoping and data preparation phase. This dataset meets the minimum standard for the base roughness layer for use in FFRD models.](##_Ref215568526)

[Other sources of land cover mapping that exceed the current NLCD quality and resolution may be scoped for use on specific projects if they are readily available and coordinated with the technical lead and program lead early in the scoping and data preparation phase.](##_Ref215568526)

###### [<span id="_Toc217044253" class="anchor"></span>Levee Data](##_Ref215568526)

[The National Levee Database (NLD) will be leveraged as the source for all levee alignment and crest profile data in FFRD models. Prior to or during the scoping phase, the NLD will undergo a data refinement process to ensure sufficient accuracy and completeness of the data for the entire study basin. Processes for levee data refinement are documented in the Reference Documents stored on the NLD.](##_Ref215568526)

###### [<span id="_Toc217044254" class="anchor"></span>Levee Breach Locations](##_Ref215568526)

[Draft breach locations for each levee in the basin will be specified by the USACE levee data team lead during the scoping phase. The locations will be selected according to the guidelines in Job Aid 11, *Levee Breach Workflows*, which considers the availability of existing risk assessment studies and levee length among other factors. Note, levee breach locations may be adjusted later during the calibration phase based on information gained related to the most likely overtopping location from early model results.](##_Ref215568526)

###### [<span id="_Toc217044255" class="anchor"></span>Dam Data](##_Ref215568526)

[The National Inventory of Dams (NID) will be leveraged as the official source of inventory of dams for FFRD studies. Prior to or during the scoping phase, the NID will undergo a data refinement process to ensure sufficient accuracy and completeness of the data for the entire study basin.](##_Ref215568526)

###### [<span id="_Ref208181855" class="anchor"><span id="_Toc217044256" class="anchor"></span></span>Dam and Reservoir Modeling Scope](##_Ref215568526)

[During the scoping phase, the model treatment for each dam in the basin will be clearly specified in the *<u>Dam Scoping Table</u>* (as described in Table 4.2). There are many combinations of how a dam can be modeled across FFRD models and a summary of all possible model treatments within each model is summarized in Tables 4.4 through 4.9. Modeling treatments for each dam are selected according to the guidelines in Job Aid 01, *Scoping Process*es, which balances modeling efficiency, accuracy, and the magnitude of impact to overall flood characteristics among other factors.](##_Ref215568526)

[The Dam Scoping Table will provide the authoritative selection of modeling methods throughout the project. During the Calibration and Conformance phases, computed results within and downstream of the dams of interest may indicate a need for adjustments to the model treatment for certain dams. If the computed results are not adequate, revisions to the Dam Model Scoping Table may be warranted. Any proposed revisions to the techniques must be approved by the technical lead and coordinated with the full modeling team.](##_Ref215568526)

[The following attributes will be included in the Dam Scoping Table.<span id="_Toc214892759" class="anchor"></span>\
](##_Ref215568526)

[Table 4.2. Dam Scoping Table Attributes](##_Ref215568526)

| [NIDID](##_Ref215568526)                                                 |
|:------------------------------------------------------------------------|
| [Dam Name](##_Ref215568526)                                              |
| [Alternate Dam Name](##_Ref215568526)                                    |
| [Max Storage](##_Ref215568526)                                           |
| [Hazard Class](##_Ref215568526)                                          |
| [Scoping Justification / Discussion](##_Ref215568526)                    |
| [Include in Reservoir Operations Model (Y/N)?](##_Ref215568526)          |
| [Number of Unique Outflow Features? ("ResSim Dams")](##_Ref215568526)    |
| [Hydrologic Model Treatment - Historic Events](##_Ref215568526)          |
| [Hydrologic Model Treatment - Synthetic Events](##_Ref215568526)         |
| [Hydraulic Modeling Treatment](##_Ref215568526)                          |
| [Include Hydraulic Initial Pool Elevation (IC Point)?](##_Ref215568526)  |
| [Breach? (Yes/No)](##_Ref215568526)                                      |
| [Vary Initial Pool Elevation During Stochastic Events?](##_Ref215568526) |

###### [<span id="_Toc217044257" class="anchor"></span>Unique Features](##_Ref215568526)

[Certain unique hydrologic features or infrastructure may play an important role in the flooding characteristics of a basin. Any major features that are not otherwise described will be assessed for possible inclusion in the scope for basin execution.](##_Ref215568526)

###### [<span id="_Toc217044258" class="anchor"></span>Model Order Design](##_Ref215568526)

[The full set of integrated FFRD models relies on passing model outputs from one model to be used as inputs for other models. The selection of plugins and the strategy for passing data between models is referred to as the model order and will be clearly defined during the scoping.](##_Ref215568526)

######## [Conceptual Model Order Graphic](##_Ref215568526)

[A conceptual model order graphic, such as the example in Figure 4.2, is created along with any additional detail or discussion and included in the BE-PWP.](##_Ref215568526)

[Separate model orders will be necessary for the calibration of the models (observed events) versus the production of synthetic stochastic simulations of the models. For example, historic event modeling will often utilize observed outflows from large dams while synthetic events will receive outflows from a reservoir operations model.\
](##_Ref215568526)

[<span id="_Toc214891696" class="anchor"></span>Figure 4.2. Example Conceptual Model Order Graphic](##_Ref215568526)

[<img src="media/image6.png" style="width:4in;height:6.5733in" />](##_Ref215568526)

######## [Name Table](##_Ref215568526)

[The conceptual model order graphic is supported by an authoritative *<u>Name Table</u>* of all planned model file names and internal model element names which follows the naming standards in Job Aid 06, *Standard Naming Conventions* and is developed during the scoping and data preparation phase of the project](##_Ref215568526)

######## [Model Linking Register](##_Ref215568526)

[An authoritative *<u>Model Linking Register</u>* lists the specific data that will be passed between models including path names and element names is developed during the scoping and data preparation phase of the project. The register will include the plan for linking of models during the calibration phase (which leverages historic observation data for some boundary conditions) and a modified plan for linking during the conformance/production phases (which leverages simulated conditions in all cases).](##_Ref215568526)

###### [<span id="_Ref215568537" class="anchor"><span id="_Toc217044259" class="anchor"></span></span>Enumeration of Cloud Simulations](##_Ref215568526)

[Six observed historic events will be selected for model calibration efforts.](##_Ref215568526)

[The stated objective for FFRD of describing simulating a full spectrum of frequencies from routine (10-year) to rare (2,000-year or rarer) requires a minimum set of synthetic years per realization of 2,000.](##_Ref215568526)

[Ten events per synthetic year will be modeled for projects conducted according to this SOP.](##_Ref215568526)

[The number of realizations impacts scoping decisions as compute costs represent a significant cost within the overall study. Projects executed under the current version of this SOP will include 5 realizations which will provide a basic understanding of uncertainty around variable-frequency relationships. Table 4.6 shows the number of modeled events a FFRD studies.](##_Ref215568526)

[The estimates of uncertainty around variable-frequency relationships may improve with additional realizations. For statistically appropriate confidence intervals, the number of realizations would be determined based on a set of convergence criteria. Future versions of this SOP may consider allowing flexibility to adjust the number of realizations based on statistical criteria and other factors.](##_Ref215568526)

[The number of realizations specified is not sufficient to accurately describe knowledge uncertainty, however it does allow for a full demonstration of the envisioned result datasets for validation of the workflows and procedures contained in this SOP in 2026. Future versions of the SOP will consider advanced techniques to optimize the simulation strategy to meet the requirements related quantification of uncertainty.](##_Ref215568526)

[<span id="_Toc214892760" class="anchor"></span>Table 4.3. Total Number of Modeled Events for a FFRD Study](##_Ref215568526)

| [Phase](##_Ref215568526) | [Number of Synthetic Years](##_Ref215568526) | [Number of Events per Synthetic Year](##_Ref215568526) | [Number of Realizations](##_Ref215568526) | [Total Events](##_Ref215568526) |
|----|:--:|:--:|:--:|:--:|
| [**Calibration**](##_Ref215568526) | [N/A](##_Ref215568526) | [N/A](##_Ref215568526) | [N/A](##_Ref215568526) | [6 observed events](##_Ref215568526) |
| [**Conformance**](##_Ref215568526) | [2,000](##_Ref215568526) | [10](##_Ref215568526) | [1](##_Ref215568526) | [20,000](##_Ref215568526) |
| [**Production**](##_Ref215568526) | [2,000](##_Ref215568526) | [10](##_Ref215568526) | [5](##_Ref215568526) | [100,000](##_Ref215568526) |

#### [<span id="_Toc217044260" class="anchor"></span>Data Preparation](##_Ref215568526)

[Consolidation of various datasets is integral to the scoping effort and establishes a foundation that allows each individual model to be produced in a consistent manner. Several of the datasets collected during the scoping phase simply obtain data from other sources, but many others are produced through engineering analysis and assessments that are made through the scoping procedures.](##_Ref215568526)

[The complete prepared dataset is a key delivery from the scoping and data preparation phase of the project. This dataset provides the base data and scope definition data that is needed to execute the project during the subsequent basin execution phases of the project.](##_Ref215568526)

###### [<span id="_Toc217044261" class="anchor"></span>Data Manifest](##_Ref215568526)

[A data manifest will be created to document and provide metadata for all data created for the project as part of the data preparation phase. Job Aid 02, *Data Preparation Processes*, provides the formatting and delivery method requirements for the data manifest.](##_Ref215568526)

###### [<span id="_Toc217044262" class="anchor"></span>Storage of Prepared Datasets](##_Ref215568526)

[All prepared datasets will be posted to the central repository using the standard directory structure. The standard directory structure is provided in the demonstration project directory in Appendix C. The process for establishing a new repository for a new project is provided in Job Aid 7. *Model Library Use for FFRD*.](##_Ref215568526)

#### [<span id="_Toc217044263" class="anchor"></span>Prepared Dataset List and Descriptions](##_Ref215568526)

[Table 4.7 shows a complete list of datasets to be prepared as part of the scoping and data preparation phase, including descriptions, intended purpose, and guidance for development and delivery of each item.](##_Ref215568526)

[<span id="_Toc214892761" class="anchor"></span>Table 4.4. Prepared Manifest Dataset and Description](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Data Manifest](##_Ref215568526) | [Document listing each of the datasets provided, which fully describes the source, purpose, description, and other metadata.](##_Ref215568526) | [Key reference to document and track all input data used for FFRD project.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for the format and critical fields to include in the Data Manifest.](##_Ref215568526) |

[<span id="_Toc214892762" class="anchor"></span>Table 4.5. List of Scoping Data Datasets and Descriptions (sheet 1 of 2)](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Study Area Polygon](##_Ref215568526) | [Polygon defining the study area for the project](##_Ref215568526) | [Official study area polygon.](##_Ref215568526) | [Scoping of the study area is descried in Section [4.3](##scoping).](##_Ref215568526) |
| [Stream Gages for Calibration](##_Ref215568526) | [The point layer for gages that will be used for calibration of the models. Each gage is attributed with its assigned importance category (i.e., primary, secondary, or tertiary).](##_Ref215568526) | [Key reference layer showing the locations where observed data exists and its treatment for calibration and validation.](##_Ref215568526) | [Guidance for the assignment of gage categories (i.e. primary, secondary or tertiary) is provided in Job Aid 01 (Scoping Processes).](##_Ref215568526) |
| [Storm Events for Calibration](##_Ref215568526) | [This tabular report of storm events selected for calibration of models includes time windows for each event.](##_Ref215568526) | [Clearly defines the basin-wide storm events and time windows used for evaluation of historic event-based calibration metrics, which ensures all model efforts use a consistent approach.](##_Ref215568526) | [Guidance for the selection of historic events for calibration is provided in Job Aid 01 (Scoping Processes).](##_Ref215568526) |
| [Hydraulic Modeling Units](##_Ref215568526) | [Polygons for each hydraulic modeling unit for the study, each with a defined basin name.](##_Ref215568526) | [Each modeling unit polygon defines a scope for individual hydraulic model unit development.](##_Ref215568526) | [Guidance for delineation of hydraulic model units is provided in Job Aid 01 (Scoping Processes).](##_Ref215568526) |
| [Uncalibrated Hydrologic Model](##_Ref215568526) | [Uncalibrated hydrologic model that included all planned HMS model elements including subbasins established during scoping and data preparation phase of the FFRD project.](##_Ref215568526) | [Establish model elements, naming, and hydrologic subbasins prior to start of major model development efforts. Early identification of the subbasins allows for consistent naming conventions to be developed and for the development of hydraulic model units that are aligned with the subbasins.](##_Ref215568526) | [Hydrologic model is developed according to general best practices and following guidance in Chapter 6.](##_Ref215568526) |
| [Name Table](##_Ref215568526) | [Table of adopted names for all elements of FFRD models.](##_Ref215568526) | [Establish adopted consistent names prior to start of major model development efforts, which facilitates model linking and other uses throughout the project.](##_Ref215568526) | [Naming convention requirements are defined in Chapter 3. Guidance of delivery and format of the Naming Table is included in Job Aid 01 (Scoping Processes).](##_Ref215568526) |
| [Model Linking Register](##_Ref215568526) | [Graphic and tabular versions of the model linking register for the project that clearly shows the source of all required inputs for each model. Includes a version for the calibration phase (when observed flows for historic events are commonly used as inputs) and for the conformance phase (when all inputs are based on modeled outputs).](##_Ref215568526) | [In combination with the Naming Table document, the Model Linking Register provides a clear definition of the data structure to be used for all modeling efforts for the basin.](##_Ref215568526) | [Guidance of delivery and format of the Model Linking Register is included in Job Aid 01 (Scoping Processes).](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 4.5. List of Scoping Data Datasets and Descriptions (sheet 2 of 2)](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Dam Scoping Table](##_Ref215568526) | [Table of all dams in the study area to attributed with the scope of modeling treatment in each of the relevant models (Hydrologic Model, Reservoir Operations Model, Breach Model and Hydraulic Model).](##_Ref215568526) | [Provide clear definition of the scope of work for the FFRD modeling efforts before major model development begins in the calibration phase.](##_Ref215568526) | [Guidance on development of the Dam Model Scoping Table is provided in Job Aid 1 (Scoping Processes).](##_Ref215568526) |
| [Levee Data Tracking Table](##_Ref215568526) | [Table of all levees in the study area along with key attributes including confirmation of data availability (alignment, profile, existing risk assessment).](##_Ref215568526) | [The primary function of this scoping table is to inform the scope of Levee Data Refinement Effort completed prior to the FFRD study; identifying which levees need crest profiles, etc. Levee Data table assembles available fields on levees within the study basin to identify critical levee data gaps or out-of-date information. The levee model scoping table can be used to manage the levee data refinement effort by assigning teams or team members tasks and track to completion.](##_Ref215568526) | [Guidance on development of the levee model scoping table is provided in separate procedures associated with Levee Data Refinement efforts.](##_Ref215568526) |
| [Levee Breach Locations](##_Ref215568526) | [Geospatial point data table including various attributes that are populated during the scoping and data preparation phase.](##_Ref215568526) | [Geospatial file of georeferenced breach locations for the study basin. The associated attribute table will include information that documents levee breach schema (quantity and location selection, as well as critical information needed to develop system response curves (risk assessment type, levee crest and toe elevations, etc. Table will identify draft Levee Control Locations (LCL) to be verified by the RAS team and will be updated if any adjustments are made in later phases. This product informs the hydraulic model development during the calibration phase.](##_Ref215568526) | [Guidance on development of the levee model scoping table is provided in Job Aid 11 (Levee Breach Workflows).](##_Ref215568526) |
| [Mesh Development Scoping-Key Streams](##_Ref215568526) | [The key streams layer is a set of stream centerlines considered the dominate and most important streams to characterize flooding in the basin. Key streams are selected during the scoping phase according to guidelines in Section 4.3.10 and provided as a shared dataset.](##_Ref215568526) | [This layer conveys the scope for hydraulic model development in terms of key stream centerlines. The hydraulic modeling level of detail for FFRD modeling will be increased along key streams and adjacent floodplains as described in Section 8.](##_Ref215568526) | [The guidelines for scoped key streams layer development are shown in Table 4.1 and procedures for their development are provided in Job Aid 01 (Scoping Processes).](##_Ref215568526) |
| [Mesh Development Scoping-Other Streams](##_Ref215568526) | [The secondary streams layer is a set of stream centerlines considered streams to characterize flooding in the basin. The secondary streams are selected during project planning according to guidelines in Section 4.3.10 and provided as a shared dataset.](##_Ref215568526) | [This layer conveys the scope for hydraulic model development in terms of other stream centerlines. The hydraulic modeling level of detail for FFRD modeling will be increased along these streams as described in Section 8.](##_Ref215568526) | [The guidelines for scoped other streams layer development are shown in Table 4.1 and procedures for their development are provided in Job Aid 01 (Scoping Processes).](##_Ref215568526) |
| [Mesh Development Scoping-Urban Areas](##_Ref215568526) | [Scoped *urban areas* polygons within the study basin.](##_Ref215568526) | [The scoped urban areas will receive increased level of hydraulic model detail for the project as described in Section 8.](##_Ref215568526) | [The scoped urban area polygons are sourced directly from the U.S. Census Urban Areas layer. Any modifications to the areas layers during the scoping phase will be documented and justified in the scoping report.](##_Ref215568526) |

[<span id="_Toc214892768" class="anchor"><span id="_Toc214892764" class="anchor"></span></span>Table 4.6. List of Base Geospatial Data Datasets and Descriptions (sheet 1 of 2)](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Full Resolution DEM](##_Ref215568526) | [The best available DEM for the entire watershed](##_Ref215568526) | [Consistent DEM to be used as the baseline for all aspects of FFRD modeling for the basin.](##_Ref215568526) | [Standards for DEM delivery for FFRD is outlined in Section 3.4. Guidance on the creation of the DEM is provided in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [30-meter DEM](##_Ref215568526) | [The full basin DEM is down-sampled to a 30-meter by 30-meter resolution.](##_Ref215568526) | [Smaller file size elevation layer, used for hydrologic model parameterization and for general basin overview maps.](##_Ref215568526) | [Standards for DEM delivery for FFRD is outlined in Section 3.4. Guidance on the creation of the DEM is provided in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 4.6. List of Base Geospatial Data Datasets and Descriptions (sheet 2 of 2)](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [National Structure Inventory](##_Ref215568526) | [The NSI provides an un-edited base national dataset of structure points and characteristics.](##_Ref215568526) | [The NSI locations layer is a useful reference. Also is used to aid in the review of hydraulic model results and as the starting point for structures that will be used to compute consequences for the project (after refinement).](##_Ref215568526) | [The process for acquisition of the NSI base layer is described in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [Elevation Derived Hydrography (EDH)-Stream Centerlines](##_Ref215568526) | [Stream centerlines delineated based on the full resolution DEM for the study.](##_Ref215568526) | [This comprehensive layer can be incorporated into hydraulic modeling with minimal edits for uses such as terrain modification alignment for bathymetry estimates or 2D mesh cell alignments. EDH lines generally match very well with the project DEM, but some artifacts will remain, and modeling best practices must be considered.](##_Ref215568526) | [Guidance for the development and acquisition of Elevation Derived Hydrography is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [Dam Inventory Data](##_Ref215568526) | [Geospatial dataset with attributes and includes all dams listed in the NID within the study basin.](##_Ref215568526) | [This is a reference dataset for use in several scoping and modeling processes.](##_Ref215568526) | [Guidance for the acquisition of the NID dataset is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [Levee Inventory Data](##_Ref215568526) | [Geospatial dataset of levee features for all levees in the NLD within the primary basin. Alignment and crest elevation profile is also included in tabular format (XYZM).](##_Ref215568526) | [This is a reference dataset for use in the development of the hydraulic models and an important reference for several aspects of the project. The alignment and crest elevation profile data are used directly in hydraulic modeling levee elements.](##_Ref215568526) | [The NLD will also go through quality review and refinement efforts related to the FFRD study, which are described in Job Aid 11 (Levee Breach Workflows). The activity is called, Levee Data Refinement, and precedes the other data preparation activities with work typically completed in the Fiscal Year prior. Guidance for the acquisition of the NLD dataset is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [Bathymetry](##_Ref215568526) | [Bathymetry data for reservoirs, navigation channels, coastal areas, or other unique features based on observed measurements.](##_Ref215568526) | [Bathymetry data is a key component to improve accuracy of all aspects of the modeling. When available, best available bathymetry should be directly applied to all models.](##_Ref215568526) | [Guidance for the acquisition of the any available bathymetric data is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [Soil Coverage](##_Ref215568526) | [The Soil Survey Geographic Database (SSURGO) contains soil data at the county level and the State Soil Geographic Database (STATSGO) contains soil data at the state level.](##_Ref215568526) | [Soil coverage is useful for estimating infiltration rates and other hydrologic basin model parameters.](##_Ref215568526) | [Guidance for the acquisition of the soils data is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [NLCD](##_Ref215568526) | [The NLCD provides spatial reference and descriptive data for characteristics of the land surface such as thematic class (e.g., urban, agriculture, and forest), percent impervious surface, and percent tree canopy cover.](##_Ref215568526) | [NLCD serves as the minimum standard for roughness parameters for the hydraulic models.](##_Ref215568526) | [Guidance for the acquisition of the NLCD data is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [Stream Gage Network](##_Ref215568526) | [Geospatial dataset of all relevant stream gages for the study basin including basic attributes.](##_Ref215568526) | [Stream gages in the basin are the basis for model calibration and validation and are used as a key reference layer.](##_Ref215568526) | [Guidance for the acquisition of the stream gage locations and attributes is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [U.S. Census Topologically Integrated Geographic Encoding and Referencing (TIGER) Data](##_Ref215568526) | [Geospatial dataset of key features and boundaries within the study basin.](##_Ref215568526) | [The US Census Urban Areas layer is used directly in the FFRD scoping of the hydraulic model effort. Other US Census datasets are useful reference layers.](##_Ref215568526) | [Guidance for the acquisition of the US Census data is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |
| [National Bridge Inventory](##_Ref215568526) | [Geospatial dataset of bridges that includes basic attributes.](##_Ref215568526) | [Bridge location and attributes are a useful reference layer and may be used in development of certain elements of the hydraulic model.](##_Ref215568526) | [Guidance for the acquisition of the National Bridge Inventory data is included in Job Aid 02 (Data Preparation Processes).](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 4.7. List of Observed Data Prepared Datasets and Descriptions (sheet 1 of 2)](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Observed Stream Gage Hydrographs (curated)](##_Ref215568526) | [Complete records of all available observed elevation and observed flow stream gage data for the basin, curated and adjusted to serve as official dataset for the FFRD project.](##_Ref215568526) | [The observed stream gage data is the basis for evaluation of model performance for all aspects of the modeling efforts. Establishment of an official curated and adjusted observed dataset during the scoping and data preparation phase allows for consistency among all model efforts.](##_Ref215568526) | [Job Aid 04 (Observed Gage Data Preparation) provides guidance for acquiring observed gage data and includes FFRD guidance for QC, treatment of missing data, and vertical datum adjustments.](##_Ref215568526) |
| [Observed Stream Gage Field Measurements (curated)](##_Ref215568526) | [Complete records of field measurement data at each stream gage location (which include stage and discharge at the time of measurement) curated and adjusted to serve as the official dataset for the FFRD project.](##_Ref215568526) | [Measurements at stream gages are the basis for understanding of the stage-discharge relationships. The foundational measurement values are used as a guide for model adjustments during the calibration and conformance phases of the FFRD project.](##_Ref215568526) | [Job Aid 04 (Observed Gage Data Preparation) provides guidance for acquiring field observations at gages and includes FFRD guidance for QC and vertical datum adjustments.](##_Ref215568526) |
| [Observed Stream Gage Annual Maximum Series (curated)](##_Ref215568526) | [Complete record of annual peak discharge and stage for the POR for each stream gage, which is curated and adjusted to serve as the official dataset for the FFRD project.](##_Ref215568526) | [Annual peaks at stream gages provide the basis for flow and stage frequency relationships and are used for evaluation of metrics during the conformance phase of the FFRD project.](##_Ref215568526) | [Job Aid 04 (Observed Gage Data Preparation) provides guidance for acquiring annual peak records at gages and includes FFRD guidance for QC and vertical datum adjustments.](##_Ref215568526) |
| [Stream Gage Stage-Discharge Relationships (Ratings)](##_Ref215568526) | [Published stage-discharge relationships at stream gages.](##_Ref215568526) | [Published stage-discharge relationships are used similarly to observed stream gage field measurements. They can be used as a guide for model adjustments during the calibration and conformance phases of the FFRD project.](##_Ref215568526) | [Job Aid 04 (Observed Gage Data Preparation) provides guidance for acquiring published stage-discharge relationships at gages and includes FFRD guidance for vertical datum adjustments.](##_Ref215568526) |
| [Observed Frequency Relationships](##_Ref215568526) | [Computed frequency relationships with uncertainty for curated observed flow, stage and precipitation data.](##_Ref215568526) | [Provide official observed frequency relationships with uncertainty for benchmarking model performance throughout the project.](##_Ref215568526) | [Job Aid 05 (Observed Gridded Data Preparation) and Job Aid 04 (Observed Gage Data Preparation) provide guidance for developing frequency relationships with uncertainty based on curated observed data.](##_Ref215568526) |
| [High Water Mark Data](##_Ref215568526) | [Records of historic flood high water mark measurements in the basin that may exist in non-gage locations for historic flood events.](##_Ref215568526) | [When measured high-water marks during floods are available, they are used as supplemental information in check and improve the hydraulic model calibration in locations that do not have stream gage data.](##_Ref215568526) | [Job Aid 04 (Observed Gage Data Preparation) provides guidance for acquiring observed high water mark data in the basin when it is available.](##_Ref215568526) |
| [Flood Imagery](##_Ref215568526) | [Images that document historical flooding that may include aerial photos from aircraft, satellite images, or on-the-ground photos.](##_Ref215568526) | [When flood imagery is available, it is used as supplemental information to check and improve hydraulic model calibration in locations that do not have stream gage data.](##_Ref215568526) | [Job Aid 04 (Observed Gage Data Preparation) provides guidance for acquiring historic flood imagery for the basin when it is available.](##_Ref215568526) |
| [Period of Record Gridded Data](##_Ref215568526) | [Precipitation, temperature, and snow-water-equivalent time series grids for the POR for the basin.](##_Ref215568526) | [Observed gridded data is a key input for the development and calibration of the of the H&H models.](##_Ref215568526) | [Job Aid 05 (Observed Gridded Data Preparation) provides guidance for acquiring gridded data for the POR, which includes QC checks an evaluation of possible sources.](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 4.6. List of Observed Data Prepared Datasets and Descriptions (sheet 2 of 2)](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Observed Storm Event Gridded Data](##_Ref215568526) | [Precipitation, temperature, and snow-water-equivalent time series for each storm event selected as a calibration event during the scoping phase.](##_Ref215568526) | [Observed gridded data truncated to include specific historic events a key input for the development of the hydrologic model.](##_Ref215568526) | [Job Aid 05 (Observed Gridded Data Preparation) provides guidance for acquiring gridded data for the POR, which includes QC checks an evaluation of possible sources.](##_Ref215568526) |
| [Observed Precipitation](##_Ref215568526) | [Observed precipitation record based on the gridded data over the POR. Summarized as an annual maximum series at the subbasin level for multiple durations (1 hour, 24 hours, and 72 hour).](##_Ref215568526) | [Annual maximum series of observed precipitation for each subbasin provides a basis for evaluation of performance of SST processes to be applied for the project.](##_Ref215568526) | [Job Aid 05 (Observed Gridded Data Preparation) provides guidance for summarizing observed precipitation.](##_Ref215568526) |
| [Observed Snow Water Equivalent (SWE)](##_Ref215568526) | [Observed SWE record based on the gridded data over the POR. Summarized as an annual maximum series at the subbasin level.](##_Ref215568526) | [Annual maximum series of observed SWE for each subbasin provides a basis for evaluation of performance of SST processes to be applied for the project.](##_Ref215568526) | [Job Aid 05 (Observed Gridded Data Preparation) provides guidance for summarizing observed SWE.](##_Ref215568526) |
| [Storm Catalog](##_Ref215568526) | [Catalog of significant storm events that have occurred in the transposition region within the POR. Each significant event includes observed gridded precipitation data.](##_Ref215568526) | [Identification of the storm catalog is a critical input for the SST method that drives meteorologic inputs for the project.](##_Ref215568526) | [Guidance for development of the storm catalog is included in Job Aid 03 (Meteorological Data Processes).](##_Ref215568526) |
| [Normalization Grid](##_Ref215568526) | [Grid that captures the spatial variability of precipitation patterns across the transposition region.](##_Ref215568526) | [The SST method described in this SOP account for spatial variability of precipitation through the Normalized Transposition technique which utilizes the Normalization Grid as the key input.](##_Ref215568526) | [Job Aid 03 (Meteorological Data Processes) provides guidance for creation and delivery of the Normalization Grid.](##_Ref215568526) |

[<span id="_Toc214892766" class="anchor"></span>Table 4.8. List of Reference Data and Reports Datasets and Descriptions](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [Vertical Datum Conversions](##_Ref215568526) | [Register of any official vertical datum conversion values for infrastructure in the basin.](##_Ref215568526) | [Reference of official data conversion values ensures consistent application of adjustments across all FFRD project efforts.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for creation and delivery of the register of vertical datum conversions.](##_Ref215568526) |
| [Dam Structure and Operation Information](##_Ref215568526) | [Dam structure information, capacity and operation data is assembled for reference whenever available, respecting all required information security requirements (e.g., USACE water control manuals \[WCMs\] or Federal Energy Regulatory Commission \[FERC\] permits, NRCS Dam information (Damwatch).](##_Ref215568526) | [Dam structure and operation data is directly used in hydraulic and hydrologic modeling and is an important reference throughout the project.](##_Ref215568526) | [Job Aid 01 (Scoping Processes) provides guidance for acquisition and delivery of Dam Structure and Operation information.](##_Ref215568526) |
| [Other Locally Available Data](##_Ref215568526) | [Additional local datasets or models that may be available within the project extent.](##_Ref215568526) | [Certain locally available data may allow for improved resolution or accuracy of FFRD modeling.](##_Ref215568526) | [Discussion of the search for some specific datasets is included in Job Aid 02 (Data Preparation Processes). Available data is also sought in data provider meetings. The inclusion of additional local datasets as inputs or reference material for FFRD efforts is at the discretion of the FFRD team .](##_Ref215568526) |

[\
](##_Ref215568526)

[<span id="_Toc214892767" class="anchor"></span>Table 4.9. List of FEMA Data Datasets and Descriptions](##_Ref215568526)

| [Dataset](##_Ref215568526) | [Description](##_Ref215568526) | [Purpose](##_Ref215568526) | [Data Preparation Guidance](##_Ref215568526) |
|----|----|----|----|
| [FEMA Effective FIS Reports](##_Ref215568526) | [All existing effective FIS reports containing full documentation of the FIS model approach.](##_Ref215568526) | [Background information to supplement FIS model data used to inform model development.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for delivery of FEMA data reference in FFRD efforts.](##_Ref215568526) |
| [FEMA Effective FIS Models](##_Ref215568526) | [Existing FIS study effective hydrologic and hydraulic models.](##_Ref215568526) | [Used either as a starting point for the FFRD models or as a reference to previous approaches, depending on the age and quality of the effective models.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for delivery of FEMA data reference in FFRD efforts.](##_Ref215568526) |
| [FEMA Effective Layers](##_Ref215568526) | [Geospatial dataset of existing FEMA flood hazard including flood zones and other layers. Dataset will include regulatory layers and may also include supplementary flood risk database information for some communities.](##_Ref215568526) | [Existing flood hazard data is a useful reference for the FFRD study and is used in determination of certain scoping items.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for delivery of FEMA data reference in FFRD efforts.](##_Ref215568526) |
| [FEMA BLE Reports](##_Ref215568526) | [Reports that provide detailed information on the methodology used for each BLE study.](##_Ref215568526) | [Background information to supplement BLE model data used to inform model development.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for delivery of FEMA data reference in FFRD efforts.](##_Ref215568526) |
| [FEMA BLE Models](##_Ref215568526) | [BLE models.](##_Ref215568526) | [Used either as a starting point for the FFRD models or as a reference to previous approaches, depending on the age and quality of the models.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for delivery of FEMA data reference in FFRD efforts.](##_Ref215568526) |
| [FEMA BLE Data](##_Ref215568526) | [Geospatial layers from FEMA BLE results that may include regulatory or non-regulatory information.](##_Ref215568526) | [Existing flood hazard data is a useful reference for the FFRD study and is used in determination of certain scoping items.](##_Ref215568526) | [Job Aid 02 (Data Preparation Processes) provides guidance for delivery of FEMA data reference in FFRD efforts.](##_Ref215568526) |

#### [<span id="_Toc217044264" class="anchor"></span>Report](##_Ref215568526)

[A report documenting the findings from the Scoping and Data Preparation phase will be developed, reviewed and included in the delivery.](##_Ref215568526)

#### [<span id="_Toc217044265" class="anchor"></span>Project Work Plan—Basin Execution](##_Ref215568526)

[The S-PWP is closed out at the end of the phase.](##_Ref215568526)

[In preparation for the next phases of the project, a draft BE-PWP will be developed that incorporates the results of the scoping effort and serves as the basis for all post-scoping activities related to the project. It includes the basin background, a data manifest of prepared datasets, model approach strategy, team member roles, a timeline, and budget. The BE-PWP will be finalized and signed until the start of the basin execution phases.](##_Ref215568526)

#### [<span id="_Toc217044266" class="anchor"></span>Review of Scoping and Data Preparation Phase Products](##_Ref215568526)

[The QC review for the scoping and data preparation products will be completed after all defined tasks are complete. The QC review will be conducted using the data preparation checklist that requires review input from multiple reviewers, led by the review manager. The template for the checklist includes specific items for review and closeout and is included as within Appendix A of this SOP package and will be posted to the documentation directory for the project.](##_Ref215568526)

[The TOG review of the scoping and data preparation phase work products is conducted after the QC review is closed.](##_Ref215568526)

[The calibration phase shall not be initiated until the scoping tasks are complete, QC review is closed and documented, and TOG as approved the effort to move forward to the calibration phase.](##_Ref215568526)

#### [<span id="_Toc217044267" class="anchor"></span>Deliverables](##_Ref215568526)

[Table 4.8 contains a list of deliverables that must be delivered to complete the scoping and data preparation phase.](##_Ref215568526)

[<span id="_Toc214892770" class="anchor"></span>Table 4.10. Final Scoping and Data Preparation Phase Deliveries](##_Ref215568526)

<table>
<colgroup>
<col style="width: 60%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Deliverable</a></th>
<th><a href="##_Ref215568526">Location to Post</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Complete Data Preparation Dataset Posted to Model Library</a></td>
<td><a href="##_Ref215568526">basin-data</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Data Manifest</a></td>
<td><a href="##_Ref215568526">basin-data</a></td>
</tr>
<tr>
<td><p><a href="##_Ref215568526">Scoping and Data Preparation Report</a></p>
<p><a href="##_Ref215568526">*Signed by FFRD Leadership and TOG</a></p></td>
<td><a href="##_Ref215568526">documentation</a></td>
</tr>
<tr>
<td><p><a href="##_Ref215568526">Technical Review Checklist</a></p>
<p><a href="##_Ref215568526">*All items closed out</a></p></td>
<td><a href="##_Ref215568526">documentation</a></td>
</tr>
<tr>
<td><p><a href="##_Ref215568526">Master Quality Review Checklist</a></p>
<p><a href="##_Ref215568526">*All items closed out for the Phase</a></p></td>
<td><a href="##_Ref215568526">documentation</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Basin Execution Project Work Plan (Draft)</a></td>
<td><a href="##_Ref215568526">documentation</a></td>
</tr>
</tbody>
</table>

#### [<span id="_Toc217044268" class="anchor"></span>Transition to Calibration Phase](##_Ref215568526)

[After the scoping and data preparation phase is fully closed out including TOG review and the BE-PWP is finalized and signed, the calibration phase can begin. It is important that all scoping and data preparation steps are complete and well understood by the team leaders. This ensures information regarding the available data and scope can be clearly conveyed to the larger team. Team member assignments are made, the start date and timeline are finalized, and a kickoff meeting is held. This kickoff brings together the entire PDT and communicates the project scope, process, schedule, budget, collaboration forums, schedule tracking systems, data sources, and any other technical details to be considered as the larger team embarks on the FFRD basin execution effort.](##_Ref215568526)

## [<span id="_Toc217044269" class="anchor"></span>—Meteorology](##_Ref215568526)

#### [<span id="_Toc217044270" class="anchor"></span>Meteorologic Context and Standards ](##_Ref215568526)

[The FFRD SOP employs the Stochastic Storm Transposition technique to apply storm events on the study basin for quasi-continuous simulations. The method uses a catalog of observed storm events from a region of similar meteorology to the study watershed. Storm observations are taken from a high-resolution precipitation dataset with a long POR and many events per year, spread out through a region much larger than the watershed. The region contains a large sample of significant rainfall events that quantify the variability in the intensity and spatial and temporal patterns of storms in the area. The uncertainty around the interaction of these storms with the study watershed is quantified by selecting storms and moving them around the region of homogeneous meteorology at random. Each time this process is repeated, it creates one plausible alternate realization of the observed record and can be used to drive a hydrology model to estimate flood response throughout the watershed.](##_Ref215568526)

###### [<span id="_Toc217044271" class="anchor"></span>Phases of Meteorologic Modeling](##_Ref215568526)

[The meteorologic data and modeling are produced in the context of the FFRD project in phases according to the workflows described in Section 2 of this SOP, and high-level meteorologic modeling tasks in each phase are described below:](##_Ref215568526)

> [<u>Scoping and Data Preparation Phase</u>: The transposition region is developed, the regional storm catalog and bias grid created. The observed gridded data over the study basin is also acquired, adjusted as needed and summarized.](##_Ref215568526)
>
> [<u>Calibration Phase</u>: Observed meteorologic data from historic events are applied in the development and calibration of H&H models.](##_Ref215568526)
>
> [<u>Conformance Phase</u>: Development of valid random storm placements (fishnets). Evaluation of SST performance for single realization and apply adjustments as needed.](##_Ref215568526)
>
> [<u>Production Phase</u>: Application of SST to within multi-realization framework.](##_Ref215568526)
>
> [<u>Reporting Phase</u>: Compilation and delivery of results from the project.](##_Ref215568526)

###### [<span id="_Toc217044272" class="anchor"></span>Software and Version](##_Ref215568526)

[The FFRD meteorologic data development and application efforts are accomplished with the aid of actions available within the following cloud-compute plugins.](##_Ref215568526)

[Table 5.1. Software for FFRD Metrologic Processes](##_Ref215568526)

| [storm-cloud](##_Ref215568526)             | [version TBD](##_Ref215568526)   |
|-------------------------------------------|---------------------------------|
| [seed-generator-plugin](##_Ref215568526)   | [version 1.0.5](##_Ref215568526) |
| [basin-record-gen-plugin](##_Ref215568526) | [version 1.0.1](##_Ref215568526) |
| [hms-mutator](##_Ref215568526)             | [version 1.0.1](##_Ref215568526) |

###### [<span id="_Toc217044273" class="anchor"></span>Data Provided to Meteorologic Team](##_Ref215568526)

[The key input for the meteorologic data and modeling effort is the study basin polygon, which is identified prior to project kickoff.](##_Ref215568526)

###### [<span id="_Toc217044274" class="anchor"></span>Naming Conventions](##_Ref215568526)

[Standard naming conventions for all project model files and data including meteorology data are provided in Job Aid 6. *Standard Naming Conventions* and must be followed.](##_Ref215568526)

#### [<span id="_Toc217044275" class="anchor"></span>Regional Precipitation Data](##_Ref215568526)

[High-resolution precipitation data with a long Period of Record are crucial for implementing SST. The AORC dataset is utilized as the primary source of gridded data for FFRD studies, which is available as both a 1-kilometer and a 4-kilometer resolution product with a 1-hour timestep and a POR beginning in 1979. The first and last year in the data POR should be checked for completeness, as they may be missing data at the beginning or end of the record. Storm data should only be taken from years of the precipitation POR that are complete (i.e., have data for all 365 or 366 days). The data should be taken from all complete years in the POR.](##_Ref215568526)

#### [<span id="_Toc217044276" class="anchor"></span>Transposition Region](##_Ref215568526)

[The fundamental assumption made by using SST is that a region of homogenous meteorology containing the study watershed can be constructed. The domain is used to identify and select storm events to use in the catalog and to define the limits of where events can be moved during stochastic simulations.](##_Ref215568526)

[Development of a transposition domain requires expert judgment and remains a subjective process until a repeatable, objective process is developed. The region must contain the study watershed in its entirety and be several times larger with a recommended lower limit of 5 times the watershed area. In particularly complex regions that have many mechanisms that generate heavy rainfall, such as tropical storms, orographic enhancement, rain shadows, atmospheric rivers, and other meteorological complexities, extra care must be taken in drawing the region.](##_Ref215568526)

#### [<span id="_Toc217044277" class="anchor"></span>Storm Catalog](##_Ref215568526)

[An SST storm catalog is unique for the study watershed. It is a function of the meteorology of the watershed, as well as the watershed’s size and shape. For each study, a storm catalog will be developed. The storm catalog is a listing of all storm events severe enough to be used in the study, some metadata about those storms, and precipitation data for each event. The following subsections describe the process for developing the storm data and metadata and the formats they should be stored in. Collectively, these items are referred to as the *storm catalog*.](##_Ref215568526)

[A storm is selected for inclusion in the catalog based on a value called its *potential precipitation*, which measures how much total rainfall the storm would bring to the study watershed if its position were optimized by transposition.](##_Ref215568526)

###### [<span id="_Toc217044278" class="anchor"></span>Storm Duration](##_Ref215568526)

[The duration for storm analysis and simulation is 72 hours for FFRD studies. This duration is meant to capture the most intense portion of synoptic-scale storms and the entirety of mesoscale storms and smaller. It is the typical duration associated with extreme precipitation analyses such as the probable maximum precipitation (PMP). The duration affects the accumulation map used for measuring potential precipitation and the storm data included in the catalog. Shorter durations may not capture the full extent of widespread rainfall due to large-scale storms, and longer durations may include multiple events that are not independent of one another. Deviation from this duration, especially shortening it, is not recommended and should not occur without a compelling technical reason.](##_Ref215568526)

###### [<span id="_Toc217044279" class="anchor"></span>Storm Arrival Rate](##_Ref215568526)

[All storms with a potential precipitation over a certain threshold are included. The threshold is chosen to achieve a specific catalog that averages 10 storms per year. For example, if 45 years of record are available the threshold will be chosen such that the storm catalog includes 450 storms.](##_Ref215568526)

[It is recognized that the selection of this threshold may influence overall modeling results for frequent events. Future updates to this SOP will consider procedures for selection of threshold to ensure bias is avoided.](##_Ref215568526)

###### [<span id="_Toc217044280" class="anchor"></span>Storm Ranking: Potential Precipitation](##_Ref215568526)

[Storms are extracted from the period of record precipitation dataset for the transposition region. Ranking is based on potential precipitation defined as the storm’s, area-averaged 72-hour accumulation over an area the size and shape of the study watershed. Extraction of independent storm events requires significant computational effort and can be accomplished via geospatial analysis of the datasets.](##_Ref215568526)

[Tools are available through the cloud-compute storm-cloud plugin to automate the process of generating catalogs that meet the above requirements, with additional details described in Job Aid 3. *Meteorologic Data Processes*.](##_Ref215568526)

###### [<span id="_Toc217044281" class="anchor"></span>Storm Catalog Delivery Specifications](##_Ref215568526)

[Each storm will be stored in its own HEC-DSS version 7 file with a filename and internal pathnames following the standard provided in Job Aid 6. *Standard Naming Conventions*. The catalog will be stored in the project directory location below.](##_Ref215568526)

#### [<span id="_Toc217044282" class="anchor"></span>Temperature Data](##_Ref215568526)

[In watersheds that require temperature data to accurately model events (e.g., where snow processes are being modeled), temperature data needs to be included in the storm .dss files as well. The temperature data should come from the same data source as the precipitation. Temperature fields only need to cover the watershed extents because they are not being transposed. They must overlap the duration of the storms and include any additional simulation period needed to capture attenuation and translation of the flood wave to the outlet of the watershed.](##_Ref215568526)

#### [<span id="_Toc217044283" class="anchor"></span>Storm Typing](##_Ref215568526)

[Storm typing is a novel addition to the traditional SST recipe that improves the hydrologic modeling of flood responses and allows for interfacing with the coastal hazards modeling process. The categories used for this approach are intentionally broad since the distinction is important for two uses: storm seasonality and isolation of tropical storms. The seasonality of the storm events is used to determine initial watershed conditions during the stochastic simulations so that implausible combinations of meteorology and watershed state cannot be created. Isolation of tropical cyclones is important for handling additional coastal modeling that may be required to characterize compound hazards caused by the combination of rainfall and storm surge.](##_Ref215568526)

###### [<span id="_Toc217044284" class="anchor"></span>Storm Categories](##_Ref215568526)

[After the catalog is developed, each of the storms will be classified into two broad storm types:](##_Ref215568526)

- [Tropical Cyclones](##_Ref215568526)

- [Non-Tropical](##_Ref215568526)

[Most rainfall events that occur on a sufficiently widespread scale for inclusion in a HUC-4 scale watershed catalog will fall into the non-tropical category. Each storm in the storm catalog will be manually classified following guidelines in Job Aid 03, *Meteorological Data Processes*.](##_Ref215568526)

###### [<span id="_Toc217044285" class="anchor"></span>Storm Seasonality Output](##_Ref215568526)

[For each type of storm, a seasonality analysis will be produced. The seasonality analysis will describe the daily frequency of occurrence for each storm type based on the start date of the events in the storm catalog. Each day of the year from 01 January through 31 December will have a storm occurrence count computed as the count of storms of that type that begin on that day of the year. The sum of the counts should equal the total number of storms of that type, and the sum of all tables should total the number of storms in the catalog.](##_Ref215568526)

#### [<span id="_Toc217044286" class="anchor"></span>Normalized Transposition](##_Ref215568526)

[The use of the normalized transposition technique recommended for FFRD studies. The use of normalized transposition accounts for spatial variability in precipitation patterns within the transposition region and study basin and has been demonstrated to improve performance of the SST at multiple scales within a watershed.](##_Ref215568526)

[HEC-HMS natively handles transposition normalization using a bias grid in the Gridded Precipitation method in the Meteorologic Model. The modeler needs to create a Precipitation-Normal Grid in their HEC-HMS project and then apply it in the Bias Grid option in their Meteorologic Model.](##_Ref215568526)

###### [<span id="_Toc217044287" class="anchor"></span>Normalization Based on NOAA Atlas 14](##_Ref215568526)

[The preferred source for a normalization field is NOAA Atlas 14. GIS Grids provided via the NOAA Atlas 14 Precipitation Frequency Data Server should be used where they are available. Use the 1/100 AEP grid for 3-day duration based on annual maximum series estimates. The grids must cover the entire transposition domain. If the transposition domain spans several volumes of NOAA Atlas 14, a mosaic of the grids will need to be created.](##_Ref215568526)

###### [<span id="_Toc217044288" class="anchor"></span>Normalization Based on Period of Record Precipitation Dataset](##_Ref215568526)

[When NOAA Atlas 14 is not available, a suitable alternative is to create a mean annual maximum 72-hour precipitation field from the precipitation data used to generate the storm catalog. To generate this field, compute the annual maximum 72-hour precipitation value for each year at each grid cell, creating an annual maximum series for each cell. Then, take the average of these values and generate the raster. To check that the result makes sense, compare it to the spatial patterns of rainfall present in the Parameter-elevation Regressions on Independent Slopes Model (PRISM) 30-precipitation normal grid for the transposition domain. PRISM should not be used for normalization.](##_Ref215568526)

#### [<span id="_Toc217044289" class="anchor"></span>Stochastic Storm Transposition Placements](##_Ref215568526)

[Storms from the catalog are placed randomly for the quasi-continuous realizations. The valid storm placements ensure that the study basin is fully contained in the transposition region. For this version of the SOP all valid locations are equally likely.](##_Ref215568526)

[The valid storm placements are created with the aid of the cloud-compute hms-mutator plugin and are termed fishnets.](##_Ref215568526)

[Future versions of the SOP may be incorporated improved techniques to account for spatial patterns of precipitation within the Transposition Region, storm-type specific spatial patterns and other techniques to improve computational efficiency.](##_Ref215568526)

#### [<span id="_Toc217044290" class="anchor"></span>SST Upper Limits](##_Ref215568526)

[The SST methods described in the SOP leverage a limited period of record of observed gridded datasets, and the substitution of space (from a larger transposition region) for record length allows extrapolation to less frequent events that would be achievable but there is an upper limit. The theoretical upper limit of extrapolation for the SST method exists is easily calculated and must be reported as part of the FFRD study.](##_Ref215568526)

[The return period ceiling is calculated by the following formula.](##_Ref215568526)

[
``` math
T_{cap} \approx \frac{Record\ Length\ (years)\ \  \bullet \ Transposition\ Region\ Area\ }{Study\ Basin\ Area}
```
](##_Ref215568526)

#### [<span id="_Toc217044291" class="anchor"></span>Meteorological Model Review Process and Deliverables](##_Ref215568526)

[Meteorological data and model review is a critical part of the FFRD production process. The meteorology reviews will examine the transposition domain, the storm catalog, and the storm typing classifications.](##_Ref215568526)

[Review checklists are used to track comments regarding pre-defined aspects checked throughout the review process. Appendix A contains checklist templates.](##_Ref215568526)

[The following subsections describe specific review steps for meteorologic products and associated deliveries.](##_Ref215568526)

###### [<span id="_Toc217044292" class="anchor"></span>Scoping and Data Preparation Phase Reviews](##_Ref215568526) 

[The following reviews are completed during the scoping and data preparation phase.](##_Ref215568526)

######## [Interim Discussions](##_Ref215568526)

[The meteorological team members may seek out collaboration and advice on general direction from national technical experts regarding items such as selection of the transposition region, storm catalog development and the normalization grid during development. These are considered informal discussions and are not required to be documented.](##_Ref215568526)

######## [Meteorology Data Review](##_Ref215568526)

[The draft final meteorology deliveries from the scoping and data preparation phase will undergo a complete technical review. The required deliverables for the review and the scope of the review are described below.](##_Ref215568526)

[The review will be documented using the Meteorology Review checklist (template included as part of the SOP package).](##_Ref215568526)

[Deliverables for review:](##_Ref215568526)

- [Transposition Region Polygon](##_Ref215568526)

- [Storm Catalog](##_Ref215568526)

- [Normalization Grid](##_Ref215568526)

- [Completed Meteorological sections of the Scoping and Data Preparation Report](##_Ref215568526)

########## [Scope of Transposition Region Review](##_Ref215568526)

[The transposition domain review must determine if the delineated domain is reasonably homogeneous. The transposition domain must completely contain the study watershed and must be at least five times larger than the target watershed by area. The domain needs to have the same types of heavy rainfall mechanisms as the target watershed, even if the watershed spans a large area with a variety of storm and flood types. It will follow large natural breaks in climatic regime, such as prominent mountain ranges, that cause rain shadow effects or other weather blocking. Frequency of tropical storms should always be considered when drawing the domain. Data supporting the delineation should express the climatic regime inside the watershed and be able to show areas surrounding the watershed that are similar to it when measured by several climatic variables (i.e., elevation, annual and maximum precipitation, annual and seasonal temperature, humidity, and prevailing winds).](##_Ref215568526)

[Inherently, the delineation of a transposition domain involves subjectivity and judgement. If the choices are well-documented and supported by available data, a transposition domain is defensible.](##_Ref215568526)

[Automated techniques for domain generation are allowed, but if the delineation is only based on one aspect of extreme rainfall such as maximum rainfall statistics, the domain needs to be compared to other datasets to ensure consistency. The review will consider the feasibility of the method used for automated delineation for the target watershed’s climate.](##_Ref215568526)

##########  [Scope of Storm Catalog Review](##_Ref215568526)

[The catalog will be reviewed for completeness and compliance with the data standards outlined in the previous sections. The proper count of storms overall based on the length of the POR is the most important check. Each storm’s center coordinates must be correctly specified in the HEC-HMS .grid file and all centers must be inside the transposition domain. All file naming and DSS path conventions must be observed.](##_Ref215568526)

########## [Scope of Storm Typing Review](##_Ref215568526)

[The primary goal of the storm typing process is to ensure storm precipitation characteristics are paired with the correct watershed conditions to produce credible flood responses. The key linkage is in the seasonality of the storm categories. The storm typing review will check the classification procedures data assumptions and ensure values and thresholds used for partitioning make meteorological sense for the type of storm being classified. The final check is that the resulting seasonality distributions for each storm type make sense for the storm type being evaluated.](##_Ref215568526)

######## [Meteorological Reporting Review](##_Ref215568526)

[The reporting needs to address the following topics:](##_Ref215568526)

- [Development of the transposition domain](##_Ref215568526)

- [Precipitation and temperature data source](##_Ref215568526)

- [Description of criteria for inclusion of storms in catalog](##_Ref215568526)

- [Delineation of storm types](##_Ref215568526)

[Documentation of the data sources and delineation choices for the transposition domain must support the assumption that the domain is meteorologically homogeneous. It must show how the data were used to reach this conclusion and address any uncertainty or sensitivity in the data or interpreting it. If an automated technique was used to develop the domain, an explanation of the assumptions and methods the technique uses must be included.](##_Ref215568526)

[The precipitation and temperature data used for developing the storm catalog should be the same as used in the hydrologic model calibration and validation process. The report should detail the data source, its spatial and temporal resolution, the range of dates of the dataset used to create a POR and document any completeness issues with the data.](##_Ref215568526)

[Severity criteria determine if a storm will be included in the catalog or not and will be documented in the meteorology report. This is a threshold value of potential precipitation and all storms with potential precipitation above this value will be included. The threshold is chosen to achieve the 10 storms per year average occurrence rate. The report will also include an analysis of the number of storms for each year in the POR and the distribution of storm counts per year.](##_Ref215568526)

[A detailed explanation of the storm typing procedure should include but not be limited to documentation of datasets, any algorithms or flowcharts developed and applied, references to storm or flood reports, and a validation of automated storm typing procedures. Manual storm typing results will show examples of storm classifications for each type, including surface analyses, precipitation maps, and other data used to make the judgment. The validation should include performance statistics for the classifier including a confusion matrix, precision, and recall statistics for each of the storm classifications.](##_Ref215568526)

###### [<span id="_Toc217044293" class="anchor"></span>Conformance Phase Reviews](##_Ref215568526)

[During the conformance phase of the FFRD project, the stochastic storms are evaluated against observed data from the period of record with the expectation that they will reasonably algin.](##_Ref215568526)

[The comprehensive conformance phase review is documented via the conformance review checklist which includes several prompts for evaluation of specific aspects of SST performance.](##_Ref215568526)

## [<span id="_Toc217044294" class="anchor"></span>—Hydrologic Modeling](##_Ref215568526)

#### [<span id="_Toc217044295" class="anchor"></span>Hydrologic Modeling Context and Standards](##_Ref215568526)

[This section outlines the hydrologic modeling process and standards necessary to meet the overall FFRD objectives. The hydrologic modeling domain is the entire FFRD study watershed as a single model. The objectives of FFRD will be met via basin-level study; and it is acknowledged that other needs and use cases, i.e., local regulatory needs, may require additional detailed studies.](##_Ref215568526)

[Hydrologic models produced following this guidance will have the following characteristics:](##_Ref215568526)

- [Single model extent for entire study basin](##_Ref215568526)

- [Coordinated for seamless integration into system of models in terms of subbasin alignments, naming conventions, and other modeling strategies](##_Ref215568526)

- [Capable of accurately estimating spatial and temporal runoff volume for both discrete storm events and long-term continuous simulations within a reasonable amount of computation time](##_Ref215568526)

- [Capable of accurately estimating baseflow response for each subbasin for both discrete storm events and long-term continuous simulations within a reasonable amount of computation time](##_Ref215568526)

- [Capable of providing basis for an array of antecedent conditions based on historic POR data.](##_Ref215568526)

- [Capable of providing basis for quantification of uncertainty in basin parameters](##_Ref215568526)

###### [<span id="_Toc217044296" class="anchor"></span>Phases of Hydrologic Modeling](##_Ref215568526)

[The hydrologic model is developed for an FFRD project in phases according to the workflows described in Section 2 of this SOP. This hydrologic modeling section applies to multiple phases, and high-level modeling tasks in each phase are described below:](##_Ref215568526)

> [<u>Scoping and Data Preparation Phase</u>: The hydrologic subbasins, reaches, junctions, reservoirs and other model elements are built into a base model. No effort to parametrize or calibrate the model is made. Standard naming conventions are applied. Subbasin delineation is leveraged for scoping and delineation of hydraulic modeling units. Meteorologic data is acquired and adjusted. Construction of the base model preformed concurrently with development of the Naming Table, Model Linking Register, and Dam Scope Table, which are all key deliverables for this phase.](##_Ref215568526)
>
> [<u>Calibration Phase</u>: Calibration of the hydrologic model models to historic observed events. Hydrologic model outputs for each historic event are provided to hydraulic models for use in calibration efforts. Calibration of a POR hydrologic simulation is also performed.](##_Ref215568526)
>
> [<u>Conformance Phase</u>: Integration of the hydrologic model into the system of models, including delivery of a combination of initial states and valid parameter datasets to be used for randomized synthetic events. Computation of synthetic events in cloud compute, and adjustments to all models to ensure performance conforms to defined quality metrics for a single long-term realization.](##_Ref215568526)
>
> [<u>Production Phase</u>: Computation of multi-realization events. Hydrologic model may require hotfixes or updates to address specific issues.](##_Ref215568526)
>
> [<u>Reporting Phase</u>: Compilation and delivery of results from the project.](##_Ref215568526)

###### [<span id="_Toc217044297" class="anchor"></span>Software Version](##_Ref215568526)

[The hydrologic model will be developed using HEC-HMS version 4.13.](##_Ref215568526)

###### [<span id="_Toc217044298" class="anchor"></span>Data Provided to Hydrologic Modeler](##_Ref215568526)

[A comprehensive shared dataset for the project is developed during the scoping and data preparation phase of the project. The development of an uncalibrated hydrologic base model occurs during the scoping and data preparation phase concurrently with development of several key scoping deliverables such as the hydraulic model unit delineation, naming table and model linking register.](##_Ref215568526)

[Key prepared datasets provided to the hydrologic modeler follow.](##_Ref215568526)

- [DEM: Full Resolution and 30-meter digital elevation model terrain data for consistent use for the entire project](##_Ref215568526)

- [Key streams (see chapter 4 for definition of this project scoping layer)](##_Ref215568526)

- [Other streams (see chapter 4 for definition of this project scoping layer)](##_Ref215568526)

- [Elevation derived hydrography (stream centerlines aligned with DEM flow paths)](##_Ref215568526)

- [POR gridded data (precipitation, temperature, and snow grids)](##_Ref215568526)

- [Observed storm event gridded data (precipitation, temperature, and snow grids)](##_Ref215568526)

- [Observed flow and water surface elevation data](##_Ref215568526)

- [Stream Gages for Calibration including assigned categories for calibration criteria](##_Ref215568526)

- [Selected Historic Storm Events for calibration](##_Ref215568526)

- [Dam and Reservoir physical data](##_Ref215568526)

- [Dam operations manuals when available](##_Ref215568526)

- [Scope for modeling treatment of each dam in the basin](##_Ref215568526)

- [Existing operations manuals including physical data](##_Ref215568526)

- [Bathymetry: All available bathymetry for rivers, lakes and reservoirs](##_Ref215568526)

- [Land Cover/Land Use dataset](##_Ref215568526)

- [Urban Imperviousness dataset](##_Ref215568526)

- [Soils Datasets (SSURGO, gSSURGO and STATSGO)](##_Ref215568526)

- [Existing hydrologic models](##_Ref215568526)

- [Various other reference layers](##_Ref215568526)

###### [<span id="_Toc217044299" class="anchor"></span>Custom Reference Data](##_Ref215568526)

[This SOP includes direction to utilize a common set of shared basin data that is created during the scoping and data preparation phase, which are stored in the *ffrd\_\[basin-name\]/basin-data/* directory. The hydrologic model will reference this official data for many aspects of the modeling process.](##_Ref215568526)

[However, there may be datasets that will be developed during model development specifically to support an individual model. For calibration phase deliverables, these datasets typically should be saved within a reference directory inside the *model-unit* directory (*ffrd\_\[basin-name\]/calibration/hydrology/*).](##_Ref215568526)

###### [<span id="_Toc217044300" class="anchor"></span>Model Linking Strategy](##_Ref215568526)

- [A comprehensive Model Linking Register and Naming Table will be developed during the scoping and data preparation phase concurrent with development of the uncalibrated hydrologic base model. During the calibration phase of the project, the model is calibrated against observed historic events and for the POR. For model development during the calibration phase the hydrologic model will apply the following boundary conditions:**Gridded Precipitation, Temperature, and SWE Data—**These are observed time series gridded data sets of excess precipitation from observed events and for the POR.](##_Ref215568526)

- [**Other Boundary Conditions—**When appropriate, other boundary conditions will be used in certain situations such as observed outflow time series at dams.](##_Ref215568526)

######## [During the conformance phase of the project, the models are adapted to fully accept modeled output from synthetic storm events as boundary conditions rather than observed data which may require certain adjustments that will be accounted for in the Model Linking Register.Naming for Modeling Linking Elements](##_Ref215568526)

[All hydraulic model files and model elements will be named according to the comprehensive naming table and model linking register which is developed during the scoping and data preparation phase.](##_Ref215568526)

###### [<span id="_Toc217044301" class="anchor"></span>Comprehensive Naming Conventions](##_Ref215568526)

[Model naming conventions for all model elements are an important aspect of FFRD, as standard naming and descriptions may be also used to support queryable metadata through the Model Library. Consolidated requirements for naming conventions and project descriptions for HEC-RAS and other models are defined in Job Aid 06, *Standard Naming Conventions*.](##_Ref215568526)

###### [<span id="_Toc217044302" class="anchor"></span>Coordination with Other Models](##_Ref215568526)

[Throughout model development and calibration, the hydrologic modeler coordinates with the technical lead and entire modeling team to exchange input and output datasets as appropriate. Some typical points of this coordination are described below.](##_Ref215568526)

######## [Hydraulic Model](##_Ref215568526)

[Early iterations of hydrologic model results may be insufficient to achieve calibration targets when they are applied to the hydraulic model. The hydraulic and hydrologic modelers will work together to determine the most appropriate model adjustments to achieve calibration targets for both models. Also note that hydrologic subbasin delineation will be aligned with the hydraulic model unit delineation during the scoping and data preparation phase such that each subbasin is fully contained within a single hydraulic model unit.](##_Ref215568526)

######## [Reservoir Operations Model](##_Ref215568526)

[The reservoir operations modeler and hydrologic modeler must ensure that the reservoir storage datasets being applied in each model represent are consistent. Although the dam model scoping table will guide the modeling approach for each dam, coordination on certain details of outflow modeling approach between the models may be needed.](##_Ref215568526)

#### [<span id="_Toc217044303" class="anchor"></span>Model Development](##_Ref215568526)

[The following sections describe the process and standards for hydrologic model development for FFRD projects.](##_Ref215568526)

###### [<span id="_Toc217044304" class="anchor"></span>Model Setup](##_Ref215568526)

[The hydrologic model elements are defined during the scoping and data preparation phase and provide key scoping information for the study. Guidelines for hydrologic modeling activities during this phase are described in the sections below.](##_Ref215568526)

######## [Study Area Delineation](##_Ref215568526)

[Initial development of the hydrologic model occurs during the scoping and data preparation phase. Leveraging the high-resolution DEM for the project, the hydrologic modeler will provide critical input for the scoping team regarding the accuracy of the study extent polygon used for early project planning. Updates to the study area may be considered by the scoping team when appropriate.](##_Ref215568526)

######## [Basin Element Delineation](##_Ref215568526)

[The hydrologic modeler identifies the outlet of the basin. The modeler may choose to add additional break points within the watershed at this point, but doing so is not necessary to continue the delineation process. Once the modeler defines the outlet, the modeler delineates the subbasin and reach elements within the basin using the provided 100-foot DEM.](##_Ref215568526)

[Delineation and placement of hydrologic model basin elements (e.g., subbasins, reaches, reservoirs, etc.) is an iterative process. After initial delineation, the modeler should check to ensure the delineation process is working properly, and no major errors exist with the terrain data. This subbasin delineation must be examined relative to the high-resolution DEM to ensure agreement. Significant variation in subbasin and/or reach delineation from published data may indicate a need to refine the terrain data even further.](##_Ref215568526)

[The USGS WBD HUC subbasin boundaries and National Hydrography Dataset (NHD) stream alignments provide a baseline against which the HEC-HMS delineations are compared. The EDH produced during the FFRD data preparation also provides a high-quality comparison for auto-generated hydrologic model reaches. These data sources are described in greater detail within Job Aid 02, *Data Preparation Processes*.](##_Ref215568526)

[The hydrologic model subbasins must align with the hydraulic modeling units with no significant disagreements. This can be accomplished by burning streams and/or building walls. The EDH, WBD, and NHD layers should all be used within this process. Refer to [HEC-HMS Tutorials and Guides](https://www.hec.usace.army.mil/confluence/hmsdocs/hmsguides) for more information.](##_Ref215568526)

[After subbasins are delineated, they are used by the scoping team as a key input into the hydraulic model unit delineation described in Job Aid 01, *Scoping Processes*. Iterations on both the subbasin and hydraulic model unit delineation may be necessary as a collaboration between hydrologic modeling, hydraulic modeling, and GIS team members.](##_Ref215568526)

######## [Refining Delineation](##_Ref215568526)

[The initial modeling unit and stream delineation is reviewed and modified to ensure alignment with the overall modeling plan. Subbasins and routing reaches can be merged or split to obtain the desired configuration using the GIS tools in HEC-HMS which allow actions such as building walls and burning streams to enforce desired alignments. Things to consider when refining the initial delineations are the locations of stream and/or reservoir gages, locations that are critical to reservoir operations, HEC-RAS basin boundary condition locations, calibration targets, and desired output locations. Also, basin element delineations should be made at major stream confluences, hydraulic structures, abrupt changes in channel or overland slope, soil, land use, or physical characteristics affecting runoff generation. Minimum or maximum modeling unit sizes are dependent upon the modeling domain. Coordination of modeling unit delineations are made with the hydraulic, reservoir simulation, and consequence models to ensure the hydrologic model aligns with project purposes.](##_Ref215568526)

[The FFRD HEC-HMS model must not be overly complex to run efficiently within the FFRD cloud compute framework with numerous stochastically sampled scenarios.](##_Ref215568526)

######## [Element Naming](##_Ref215568526)

[All element names included in the hydrologic base model will follow the FFRD naming conventions established in Job Aid 03, *Standard Naming Conventions*. These names will be utilized in the development of the Model Linking Register and Name Table during the scoping and data preparation phase of the project.](##_Ref215568526)

######## [Test Simulation](##_Ref215568526)

[Once the modeling unit delineation is approved by the team and elements are named appropriately, a meteorologic model and corresponding control specification are developed to produce a fully functional HEC-HMS project. The model is not calibrated, but incorporates all major data linkages, contains reasonable initial parameter estimates, and runs without errors and significant warnings.](##_Ref215568526)

[This uncalibrated base model is a core delivery for the Scoping and Data Preparation phase of the FFRD project.](##_Ref215568526)

###### [<span id="_Toc217044305" class="anchor"></span>Computing Watershed Characteristics](##_Ref215568526)

[Watershed Characteristics are applied to the model during the calibration phase of the project. If adapting an existing HEC-HMS model for an FFRD study, watershed characteristics may already be incorporated into the model. However, HEC-HMS modelers must review (and, if necessary, recreate) watershed characteristics to ensure they are appropriately incorporated into the model.](##_Ref215568526)

[If a new HEC-HMS model is developed, once the stream and modeling unit delineation are finalized, the modeler computes physical characteristics of the watershed using automated tools within HEC-HMS. Physical characteristics for a stream include the length, slope, relief, and sinuosity. Similarly, physical characteristics for subbasins include the longest flowpath length and slope, centroidal flowpath length and slope, and overall basin slope and relief, amongst others. These physical characteristics are then used to estimate the initial model parameters along with commonly available GIS data.](##_Ref215568526)

######## [FFRD Standard Hydrologic Modeling Methods](##_Ref215568526)

[Unless the watershed is unique enough to justify otherwise, the following HEC-HMS modeling methods are recommended for use in FFRD HEC-HMS models:](##_Ref215568526)

- [Discretization: Structured](##_Ref215568526)

- [Canopy: Simple](##_Ref215568526)

- [Transform: ModClark](##_Ref215568526)

- [Loss: Deficit and Constant](##_Ref215568526)

- [Baseflow: Linear Reservoir](##_Ref215568526)

- [Routing: Muskingum-Cunge, Muskingum, and/or Modified Puls](##_Ref215568526)

- [Reservoirs: Specified Release, defined Elevation-Storage-Discharge relationships, and/or Rule-Based Operations](##_Ref215568526)

- [Snowmelt: Gridded Temperature Index](##_Ref215568526)

- [Basin Model Local flow option: ‘*yes’*](##_Ref215568526)

- [Precipitation: Gridded Precipitation](##_Ref215568526)

- [Temperature: Gridded Temperature](##_Ref215568526)

- [Evapotranspiration: Gridded Hamon](##_Ref215568526)

[In general, initial model parameters are estimated from GIS datasets, regional regression equations, and existing models and then adjusted to achieve calibration targets.](##_Ref215568526)

######## [Estimating Model Parameters](##_Ref215568526)

[If adapting an existing HEC-HMS model, watershed parameters are already included within the model. However, as part of the FFRD effort, the model parameters must be verified and tested using FFRD event-based calibration data.](##_Ref215568526)

[If a new HEC-HMS model is developed, physical characteristics of the watershed elements are used along with additional GIS datasets (soil data, land use and land cover \[LULC\] data, etc.) to estimate the initial model parameters. Modelers compute the hydrologic parameters, such as the percent impervious area and time of concentration, using the Expression Calculator in HEC-HMS or within the GIS software. More information is available in the HEC-HMS tutorials and guides.](##_Ref215568526)

########## [Discretization Method](##_Ref215568526)

[The Structured Discretization method is recommended for FFRD HEC-HMS models. This method allows for the distributed application of gridded boundary conditions as well as pertinent modeling methods (e.g., losses and transform).](##_Ref215568526)

[The chosen CRS utilized for Structured Discretization method will utilize the Standard Hydrologic Grid (SHG) which is consistent with the standard FFRD projection defined in Section 3.2. The chosen horizontal resolution of the discretization must be equal to or greater than the smallest resolution of the meteorologic boundary conditions (e.g., 2000 meters by 2000 meters). Modelers should refer to HEC-HMS online tutorials when applying the Structured Discretization method.](##_Ref215568526)

########## [Transform Methods and Parameters](##_Ref215568526)

[The ModClark transform method is recommended for FFRD HEC-HMS models. This method is mature, well established, well documented, and simple to set up and use. It has also been used successfully within thousands of studies throughout the United States. Also, parameters can be regionalized, related to measurable basin characteristics, and varied with excess-precipitation rates, which are important traits for methods used in extreme event simulations. Modelers should refer to [Engineer Manual (EM) 1110-2-1417](https://www.publications.usace.army.mil/portals/76/publications/engineermanuals/em_1110-2-1417.pdf) and HEC-HMS online tutorials when estimating initial transform parameters.](##_Ref215568526)

########## [Loss Methods and Parameters](##_Ref215568526)

[The Simple Canopy method is recommended for FFRD HEC-HMS models. This method is mature, utilized throughout the United States, simple to set up and use, and scalable in complexity. Within FFRD implementations, losses should be assumed to occur solely within the chosen infiltration routine (e.g., Deficit and Constant). However, to accurately simulate infiltration capacity recovery during prolonged periods of little to no precipitation, a Canopy method is required within HEC-HMS. For this reason, the Initial and Maximum Storage parameters that are required as part of the Simple Canopy method should be set to a small value (e.g., 0.01 inches) and remain unmodified during model calibration. However, the Crop Coefficient parameter, which controls how potential evapotranspiration is converted to actual, may be modified during model calibration to accurately estimate moisture deficits following prolonged periods of little to no precipitation.](##_Ref215568526)

[The Deficit and Constant loss method is recommended for FFRD HEC-HMS models. This method is mature, utilized throughout the United States, simple to set up and use, and scalable in complexity. Using this method, parameters can be related to predominant soil textures and estimated using multiple literature sources, and the method is parsimonious to a greater degree than more complex methods. Loss parameters are often estimated for each subbasin utilizing readily available GIS data. For example, constant loss rates may be estimated by spatially averaging hydraulic conductivity values from soils databases (e.g., gSSURGO). Directly connected impervious area may be estimated using NLCD impervious data sets. Care must be taken to estimate directly connected impervious area in lieu of total impervious area. Additionally, large bodies of water must be accounted within the directly connected impervious area estimates.](##_Ref215568526)

[Modelers should refer to [EM 1110-2-1417](https://www.publications.usace.army.mil/portals/76/publications/engineermanuals/em_1110-2-1417.pdf) and HEC-HMS online tutorials for additional background and examples when estimating loss parameters.](##_Ref215568526)

########## [Baseflow Methods and Parameters](##_Ref215568526)

[The linear reservoir baseflow method is recommended for FFRD HEC-HMS models. Using this method, mass is automatically conserved, baseflow generation is linked to infiltration, inflow can be partitioned to multiple layers or lost to deep aquifer storage, parameters can be regionalized, and parameters can be estimated using watershed physical characteristics. Also, this method is scalable in that it can be used for a single event or continuous simulations with little to no differences in parameterization. Modelers should refer to HEC-HMS online tutorials when estimating initial baseflow parameters.](##_Ref215568526)

[Within FFRD HEC-HMS models, the linear reservoir baseflow method is typically defined using two groundwater (GW) layers. However, a third layer may be required depending upon physical considerations of the modeling domain in question. The GW 1 layer must be conceptualized as conveying interflow or quick-responding subsurface water while GW 2 layer must be conceptualized as conveying slow responding baseflow. As such, GW 1 parameters must never be used that result in GW 1 outflow preceding direct runoff provided by the transform method. Similarly, GW 2 parameters must never be used that result in GW 2 outflow preceding outflow from GW 1.](##_Ref215568526)

[Initial discharge within each GW layer may be initially estimated using any value but should be adjusted based on observable baseflow at the start of each event during calibration. Initially, infiltrated water may be evenly split between the GW layers (i.e., 50 percent of infiltrated water sent to GW 1 and GW 2). The GW coefficients may also be initially estimated using the rule of thumb that the GW 1 coefficient is typically three times the transform method’s storage coefficient while the GW 2 coefficient is typically ten times the transform method’s storage coefficient. All linear reservoir parameters must be adjusted as needed throughout calibration.](##_Ref215568526)

########## [Reach Routing Methods and Parameters](##_Ref215568526)

[The Muskingum-Cunge routing method is recommended for FFRD HEC-HMS models. This method is mature, allows parameters to be efficiently estimated from measurable channel characteristics, and provides accurate results for a wide variety of physical settings. The HEC-HMS modeler estimates initial parameters from GIS datasets, regional regression equations, and/or existing models, if available. If reliable storage-discharge relationships are available throughout the modeling domain, the Modified Puls routing method can also be utilized for FFRD HEC-HMS models. This method provides accurate results for a wide variety of physical settings including very flat slopes and areas influenced by complex hydraulic interactions. Reliable storage-discharge relationships can be derived from a calibrated HEC-RAS project. When input data is not readily available for use within the Muskingum-Cunge and/or Modified-Puls methods, the Muskingum method may also be utilized for FFRD HEC-HMS models. Modelers should refer to [EM 1110-2-1417](https://www.publications.usace.army.mil/portals/76/publications/engineermanuals/em_1110-2-1417.pdf) and HEC-HMS online tutorials for further guidance when estimating initial reach routing parameters.](##_Ref215568526)

[Routing methods and parameters in the HEC-HMS model need to match those in the reservoir operations model; if they do not, there can be discrepancies in computed hydrographs from the two models. HEC-HMS calibrated routing reach parameters are generally adopted directly into the reservoir operations model since the HEC-HMS model focuses more on hydrologic calibration and routing while the reservoir operations model focuses more on calibrating reservoir rules and operations.](##_Ref215568526)

########## [Reservoir Modeling Methods](##_Ref215568526)

[A comprehensive strategy for dam and reservoir modeling within the full system of models for the FFRD project is developed during the Scoping and Data Preparation Phase of the project and documented in the Dam Modeling Scope Table (see Table 4.13). This table may be developed concurrently with the development of the uncalibrated base model and will clearly indicates which dams will be included as reservoirs in HEC-HMS and the selected methods for modeling of releases during both the Calibration Phase and Conformance/Production Phases.](##_Ref215568526)

[For historic event simulations, the specified release method is recommended for use when observed outflow data is available. When observed data is not available for use, the Outflow Curve and/or Rule-Based Operations methods may be used instead. Regardless of the chosen modeling method, reservoir elements must include elevation-storage information and initial conditions so the observed pool elevation can be monitored during calibration (since it is generally more reliable than estimated reservoir inflow data). Nearby USGS stream gages may serve as additional calibration resources.](##_Ref215568526)

[For stochastic event simulations, the specified release method is not suitable for use due to a lack of observed data. Therefore, the Outflow Curve and/or Rule-Based Operations methods must be used. Modelers should refer to HEC-HMS online tutorials when estimating initial reservoir parameters.](##_Ref215568526)

########## [Snowmelt Methods and Parameters](##_Ref215568526)

[If the watershed is hydrologically impacted by snowmelt, the Gridded Temperature Index method is recommended for FFRD HEC-HMS models. This method is mature, simple to set up and use, and parsimonious to a greater degree than more complex methods. Modelers should refer to HEC-HMS online tutorials when estimating initial snowmelt parameters.](##_Ref215568526)

[The Snow Data Assimilation System (SNODAS) or University of Arizona SWE datasets are recommended for use within watersheds requiring snowmelt simulations. Selection of a snow dataset may vary by its accuracy within the watershed and POR.](##_Ref215568526)

########## [Adding Observed Flow](##_Ref215568526)

[During the Calibration phase, observed flow data from historic events is added to the model through the Time-series Data Manager. The modeler creates a new time-series data entry for each gage location and populates the name and description with the corresponding information for the gage. A time-series gage entry for each gage location is also created. Gage names are chosen so they are easily identifiable, and the actual gage name and USGS ID (if applicable) are included in the description field. Observed data for each gage is entered in the Component Editor and is associated with the corresponding basin model element. Once the observed data is associated with the proper basin element, the element is set as a computation point so the element can be easily identified and used to perform more efficient computations during calibration runs. Computation points are used to speed up calibration efforts as HEC-HMS computes only the modified elements upstream of the computation point.](##_Ref215568526)

########## [Creating Meteorologic Models of Historic Events](##_Ref215568526)

[The modeler creates meteorologic models for historic events using precipitation and temperature data which is created as part of the Scoping and Data Preparation phase. This meteorologic data is used later in the calibration process but also allows for creation of uncalibrated base simulation runs to ensure the HEC-HMS project runs and is stable. Gridded meteorologic data are required for use within FFRD implementations. In general, the AORC gridded precipitation and temperature product is recommended as it is available CONUS from 1979 to the present.](##_Ref215568526)

[The AORC data is a very useful product available at an hourly timestep for a relatively long POR (1979 through the present). However, the accuracy of AORC precipitation volumes may vary regionally. During the Scoping and Data Preparation Phase, AORC hourly data will be normalized using the PRISM daily precipitation data which generally contains more accurate precipitation volumes within a daily timestep. More information and examples on normalizing gridded dataset can be found within the [HEC-HMS online tutorials and guides website](https://www.hec.usace.army.mil/confluence/hmsdocs/hmsguides).](##_Ref215568526)

[Information on additional [readily-available gridded data sources](https://www.hec.usace.army.mil/confluence/hmsdocs/hmsguides/gridded-boundary-condition-data/gridded-data-sources) is found online at the HEC-HMS tutorials and guides website.](##_Ref215568526)

[FFRD project workflows for acquisition of gridded data, adjustments to the data, summarization of the data, naming conventions and storage locations during the Scoping and Data Preparation Phase are described in Job Aid 5. *Observed Gridded Data Preparation*.](##_Ref215568526)

[Gridded data is added by creating a new precipitation gridset in the Grid Data Component Manager. Once created, the appropriate filename and path for the gridded data is entered in the Component Editor. Once a precipitation gridset is created and added to the HEC-HMS project, a meteorologic model for that gridset is created using the Meteorologic Model Manager. The modeler selects the appropriate precipitation gridset and enters a description for the meteorologic model in the Component Editor. All DSS files with observed data should be saved within the HEC-HMS project folder. When the DSS files are in the HEC-HMS project folder, HEC-HMS uses a relative pathname for the DSS file.](##_Ref215568526)

[The Gridded Hamon potential evapotranspiration method is recommended for FFRD HEC-HMS models. This method is mature and provides reliable results for a wide variety of physical settings.](##_Ref215568526)

########## [Creating Simulations of Historic Events](##_Ref215568526)

[Once the basin model and meteorologic model are created, a control specification is created to perform a model simulation. The control specification file identifies the dates and times (in UTC) for which the simulation is run and should match the precipitation event of interest in the meteorologic model. If there is more than one rainfall event of interest in the meteorologic data, a control specification is created for each event.](##_Ref215568526)

[The simulation time-step is also defined in the control specification. For most models, a time-step of one hour is the preferred standard. Ideally, the time-step is based on modeling unit hydrograph and routing reach parameters, precipitation inputs, and reservoir response. The simulation time step determines the number of ordinates that define the runoff hydrograph. A general rule of thumb is at least four points (ordinates) on the rising limb of the hydrograph are required to adequately define the shape. For example, a subbasin with a time of concentration of four hours requires a simulation time-step of approximately one hour.](##_Ref215568526)

[Once the basin model, meteorologic model, and control specifications are set up, a simulation run is created for each historic calibration event. Refer to Job Aid 06, *Standard Naming Conventions* for guidance on naming of the simulation.](##_Ref215568526)

########## [Running the Uncalibrated Model](##_Ref215568526)

[Once the simulation runs are created, the HEC-HMS modeler computes each simulation and reviews the message logs to determine if any major warnings need to be addressed. If no major warnings are found, output from the model at the basin outlet and locations of interest (gage locations, stream junctions, and local inflows, etc.) are examined to determine if the model is functioning properly. The modeler verifies the observed flows are plotting correctly in the results for all gage locations with observed data.](##_Ref215568526)

#### [<span id="_Toc217044306" class="anchor"></span>Event-Based Model Calibration](##_Ref215568526)

[The objective of the event-based model calibration is to compute incremental excess precipitation in gridded format and baseflow time series for the HEC-RAS model calibration and provide a range of calibration parameters for use in the POR simulation. Once the HEC-HMS model is developed and running, the basin model is further refined to obtain a calibrated model. The modeler calibrates the model parameters for multiple elements upstream of each gage by adjusting them in parallel until the simulated results match observed gage records. The goal is to adjust model parameters such that model output matches the peak, timing, and/or runoff volume of historic events. Section [4.3.8](##_Ref215568779) discusses identification of calibration events.](##_Ref215568526)

###### [<span id="_Toc217044307" class="anchor"></span>Calibration of Model using Historic Events](##_Ref215568526)

[Observed streamflow and precipitation data are necessary inputs when calibrating a hydrologic model. At least one basin model and simulation event were created during the previous stage of model development, but other events are added to the HEC-HMS project to aid in calibration. If calibrating for numerous events, multiple basin models are created to track parameters during calibration. It is recommended that the model be calibrated to historic events with both wet and dry antecedent conditions. This allows the modeler to determine reasonable bounds for many model parameters.](##_Ref215568526)

[FFRD HEC-HMS models are calibrated for six historic events that are selected during the scoping and data preparation phase. The primary focus of the hydrologic model development and calibration effort during the calibration phase of the project is achieving the calibration criteria for these events. If the watershed is hydrologically impacted by snowmelt, at least two snowmelt-influenced events are calibrated in addition to at least four rainfall events.](##_Ref215568526)

[Care should be taken to use physically justifiable parameters given the hydrologic characteristics of the modeling domain. Also, parameters must be relatively consistent across subbasins for hydrologically similar regions. If the need for significant parameter inconsistencies or unrealistic parameters is identified, they must be explained and justified in accompanying reports. Additional description is provided within Job Aid 12, *Model Calibration.*](##_Ref215568526)

[Model performance during extreme event simulations must be given priority during this phase. Parameter modifications for flood events and/or locations where surface runoff dominates (i.e., high magnitude floods) should be the primary focus. Conversely, parameter modifications for events and/or locations where small to moderate flooding is being simulated should be performed afterwards. Over-fitting should also be avoided. Instead, intra-event and regionally consistent model parameterizations should be identified and preferred.](##_Ref215568526)

[Table 6.2 highlights parameters to investigate and vary during model calibration.](##_Ref215568526)

[<span id="_Toc214892771" class="anchor"></span>Table 6.1. Calibration Parameters and Approach (sheet 1 of 3)](##_Ref215568526)

<table style="width:100%;">
<colgroup>
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 62%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Process</a></th>
<th><a href="##_Ref215568526">Parameter</a></th>
<th><a href="##_Ref215568526">Calibration Approach</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Canopy</a></td>
<td><a href="##_Ref215568526">Initial Storage</a></td>
<td><p><a href="##_Ref215568526">In general, significant canopy interception is not included within FFRD implementations. Instead</a></p>
<p><a href="##_Ref215568526">this parameter is not varied during model calibration except when necessary to correct for a lack of standing water or large changes in impervious area throughout time. Physical justification must be provided if using varying values for multiple historic events.</a></p></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Infiltration</a></td>
<td><a href="##_Ref215568526">Initial Deficit</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed initiation of runoff.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Infiltration</a></td>
<td><a href="##_Ref215568526">Maximum Deficit</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the initiation of runoff after prolonged periods with little to no precipitation during continuous simulations. Physical justification must be provided if using varying values for multiple historic events.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Infiltration</a></td>
<td><a href="##_Ref215568526">Constant Loss Rate</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed runoff peak and volume.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Infiltration</a></td>
<td><a href="##_Ref215568526">Percent Impervious Cover</a></td>
<td><a href="##_Ref215568526">In general, this parameter is not varied during model calibration except when necessary to correct for a lack of standing water or large changes in impervious area throughout time. Physical justification must be provided if using varying values for multiple historic events.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Runoff Transform</a></td>
<td><a href="##_Ref215568526">Time of Concentration (Tc)</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed hydrograph shape, primarily on the rising limb. This parameter is also varied to match the observed time of peak flow.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Runoff Transform</a></td>
<td><a href="##_Ref215568526">Storage Coefficient (R)</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed hydrograph shape, primarily on the receding limb. This parameter is also varied to match the observed peak flow magnitude.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Baseflow</a></td>
<td><a href="##_Ref215568526">GW 1 Initial Discharge</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed discharge at the beginning of the simulation.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Baseflow</a></td>
<td><a href="##_Ref215568526">GW 1 Fraction</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed runoff volume.</a></td>
</tr>
</tbody>
</table>

[\
](##_Ref215568526)

[Table 6.1. Calibration Parameters and Approach (sheet 2 of 3)](##_Ref215568526)

| [Process](##_Ref215568526) | [Parameter](##_Ref215568526) | [Calibration Approach](##_Ref215568526) |
|----|----|----|
| [Baseflow](##_Ref215568526) | [GW 1 Coefficient](##_Ref215568526) | [GW 1 is conceptualized to represent interflow (i.e., fast-responding portion of baseflow). Therefore, this coefficient must be set to a smaller value than the GW 2 coefficient. This parameter is varied to match the observed hydrograph shape.](##_Ref215568526) |
| [Baseflow](##_Ref215568526) | [GW 1 Number of Steps](##_Ref215568526) | [This parameter is varied to match the observed hydrograph shape.](##_Ref215568526) |
| [Baseflow](##_Ref215568526) | [GW 2 Initial Discharge](##_Ref215568526) | [This parameter is varied to match the observed discharge at the beginning of the simulation.](##_Ref215568526) |
| [Baseflow](##_Ref215568526) | [GW 2 Fraction](##_Ref215568526) | [This parameter is varied to match the observed runoff volume.](##_Ref215568526) |
| [Baseflow](##_Ref215568526) | [GW 2 Coefficient](##_Ref215568526) | [GW 2 is conceptualized to represent the slow-responding portion of baseflow. Therefore, this coefficient must be set to a larger value than the GW 1 storage coefficient. This value is varied to match the observed hydrograph shape.](##_Ref215568526) |
| [Baseflow](##_Ref215568526) | [GW 2 Number of Steps](##_Ref215568526) | [This parameter is varied to match the observed hydrograph shape.](##_Ref215568526) |
| [Streamflow Routing](##_Ref215568526) | [Length](##_Ref215568526) | [This parameter should be estimated using physically measurable characteristics and should not be varied during model calibration within Muskingum-Cunge routing reaches. Physical justification must be provided if using varying values for multiple historic events.](##_Ref215568526) |
| [Streamflow Routing](##_Ref215568526) | [Slope](##_Ref215568526) | [This parameter should be estimated using physically measurable characteristics and should not be varied during model calibration within Muskingum-Cunge routing reaches. Physical justification must be provided if using varying values for multiple historic events.](##_Ref215568526) |
| [Streamflow Routing](##_Ref215568526) | [Manning’s “n” values](##_Ref215568526) | [This parameter is varied to match the observed hydrograph translation and attenuation within Muskingum-Cunge routing reaches.](##_Ref215568526) |
| [Streamflow Routing](##_Ref215568526) | [Storage-Outflow Relationship](##_Ref215568526) | [This parameter is varied to match the observed hydrograph translation and attenuation within Modified Puls routing reaches.](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 6.1. Calibration Parameters and Approach (sheet 3 of 3)](##_Ref215568526)

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 62%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><a href="##_Ref215568526"><strong>Process</strong></a></th>
<th style="text-align: center;"><a href="##_Ref215568526"><strong>Parameter</strong></a></th>
<th style="text-align: center;"><a href="##_Ref215568526"><strong>Calibration Approach</strong></a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Streamflow Routing</a></td>
<td><a href="##_Ref215568526">Cross Section Shape</a></td>
<td><a href="##_Ref215568526">This parameter should be estimated using physically measurable characteristics and should not be varied during model calibration within Muskingum-Cunge routing reaches. Physical justification must be provided if using varying values for multiple historic events.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Streamflow Routing</a></td>
<td><a href="##_Ref215568526">Number of Steps</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed hydrograph translation and attenuation within Modified Puls routing reaches.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Streamflow Routing</a></td>
<td><a href="##_Ref215568526">K</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed hydrograph translation within Muskingum routing reaches.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Streamflow Routing</a></td>
<td><a href="##_Ref215568526">X</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed hydrograph attenuation within Muskingum routing reaches.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Streamflow Routing</a></td>
<td><a href="##_Ref215568526">Number of Subreaches</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed hydrograph attenuation within Muskingum routing reaches.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">PX Temperature</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed SWE accumulation.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">Base Temperature</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed SWE depletion during snowmelt.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">Wet Melt rate</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed SWE depletion during rainfall.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">Rain Rate Limit</a></td>
<td><a href="##_Ref215568526">This parameter is not varied during model calibration.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">Dry Melt rate</a></td>
<td><a href="##_Ref215568526">This parameter is varied to match the observed rate of SWE depletion during times when rainfall rates were less than the Rain Rate Limit.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">ATI-Cold rate<br />
Function</a></td>
<td><a href="##_Ref215568526">This function is varied to match the observed timing of the start of SWE melt.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">Snowpack Water Capacity</a></td>
<td><a href="##_Ref215568526">This value is varied to match the observed runoff generation from the melting snowpack.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Snowmelt</a></td>
<td><a href="##_Ref215568526">Ground melt</a></td>
<td><a href="##_Ref215568526">This value is set to zero and not varied during model calibration.</a></td>
</tr>
</tbody>
</table>

[\
](##_Ref215568526)

###### [<span id="_Toc217044308" class="anchor"></span>Calibration Performance Ratings](##_Ref215568526)

[Model performance statistics are used to quantitatively assess the HEC-HMS calibration performance throughout the watershed. Table 6.3 provides the industry-standard performance ratings (Moriasi, et al., 2007). Tools provided in Appendix C.3 and C.4 may be applied to aid in the calculation of these calibration statistics.](##_Ref215568526)

[Calibration performance rating goals are set by the primary, secondary, and tertiary gage categories:](##_Ref215568526)

- [Primary Locations: Statistical comparisons of computed and observed flow/stage at all primary locations are in the satisfactory or higher range.](##_Ref215568526)

- [Secondary Locations: Statistical comparisons of computed and observed flow/stage at all secondary locations are in the satisfactory or higher range but are considered more leniently than for primary locations.](##_Ref215568526)

- [Tertiary Locations: Statistical comparisons of computed and observed flow/stage at all tertiary locations are in the satisfactory or higher range but considered more leniently than for secondary locations.](##_Ref215568526)

[Table 6.2. Performance Ratings for Evaluation Metrics](##_Ref215568526)

<table>
<colgroup>
<col style="width: 16%" />
<col style="width: 14%" />
<col style="width: 16%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 17%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Performance<br />
Rating</a></th>
<th style="text-align: center;"><a href="##_Ref215568526">Color<br />
Code</a></th>
<th style="text-align: center;"><a href="##_Ref215568526">R<sup>2</sup></a></th>
<th style="text-align: center;"><a href="##_Ref215568526">NSE</a></th>
<th style="text-align: center;"><a href="##_Ref215568526">RSR</a></th>
<th style="text-align: center;"><a href="##_Ref215568526">PBIAS</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Very Good</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">Dark Green</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.65&lt;R<sup>2</sup>≤1.00</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.65&lt;NSE≤1.00</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.00&lt;RSR≤0.60</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">PBIAS&lt;±15</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Good</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">Light Green</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.55&lt;R<sup>2</sup>≤0.65</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.55&lt;NSE≤0.65</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.60&lt;RSR≤0.70</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">±15≤PBIAS&lt;±20</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Satisfactory</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">Orange</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.40&lt;R<sup>2</sup>≤0.55</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.40&lt;NSE≤0.55</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">0.70&lt;RSR≤0.80</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">±20≤PBIAS&lt;±30</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Unsatisfactory</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">Red</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">R<sup>2</sup>≤0.40</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">NSE≤0.40</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">RSR&gt;0.80</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">PBIAS≥±30</a></td>
</tr>
</tbody>
</table>

[Based on (Moriasi, et al., 2007).](##_Ref215568526)

###### [<span id="_Toc217044309" class="anchor"></span>Peak flow Performance](##_Ref215568526)

[Modeled peak flow for each calibration event must be compared to observed peak flow for each location. Adjustments to the parameters will be made to match peak flows within acceptable tolerances with consideration possible uncertainties in observed values.](##_Ref215568526)

###### [Calibration Model Output](##_Ref215568526)

[Once a calibration run is complete, the HEC-HMS modeler provides calibrated flow information to the HEC-RAS modeler for calibration of the hydraulic model. Information includes:](##_Ref215568526)

- [Baseflow time series from each modeling unit](##_Ref215568526)

- [Incremental excess precipitation grids covering the entire modeling domain.](##_Ref215568526)

[As the HEC-RAS modeler utilizes the output from HEC-HMS within the HEC-RAS model, they examine results with the HEC-HMS modeler to identify any discrepancies significant enough to warrant another calibration run through the HEC-HMS model. This process is repeated until the HEC-RAS and HEC-HMS modelers are both confident the models are calibrated for the historic event being simulated.](##_Ref215568526)

#### [<span id="_Toc217044310" class="anchor"></span>Continuous Simulation](##_Ref215568526)

[A continuous simulation is also developed during the calibration phase of the project. The objective of the continuous simulation is to obtain a single set of parameters within the range of event-based calibration parameters that performs well for longer durations. It is the first step in development of the POR simulation which is leveraged during the Conformance and Production phases of the FFRD modeling process.](##_Ref215568526)

[Once the HEC-HMS model is calibrated to historic events, a continuous simulation calibration of the model is run testing the model accuracy and performance over longer periods of time. The continuous simulation calibration event includes at least two water years and at least one high flow event. If the watershed hydrology is influenced by snowmelt, the continuous simulation period also includes at least one year where the SWE within the basin was fairly high and contributed significantly to the annual runoff.](##_Ref215568526)

###### [<span id="_Toc217044311" class="anchor"></span>Continuous Simulation Parameters](##_Ref215568526)

[The range of event-based calibration parameters is considered when selecting an initial parameter set for the continuous simulation calibration. The HEC-HMS modeler uses engineering judgment to determine which initial parameters both best represent the watershed over long periods of time and reasonably recreate the available observed data with a particular emphasis on accurately capturing annual maximum peak flows.](##_Ref215568526)

###### [<span id="_Toc217044312" class="anchor"></span>Continuous Simulation Calibration](##_Ref215568526)

[The HEC-HMS modeler compares output from the continuous simulation run to observed streamflow data. If the simulation does not adequately match the observed data, volume, and annual maximum peaks, further adjustment to the continuous simulation parameters is needed using the same procedure described for the calibration process in Section 6.3. This may be an iterative process until reasonable calibration targets are met for the continuous simulation event. Final continuous simulation calibration parameters should fall within the range of the event-based calibration parameters.](##_Ref215568526)

#### [<span id="_Toc217044313" class="anchor"></span>Period of Record Simulation](##_Ref215568526)

[A simulation of the full POR of available gridded data is also developed during the calibration phase of the project. The key purpose of the POR simulation is to provide a distribution of reasonable starting states for every day of the year across the entire historic POR to support epistemic uncertainty estimation, which is described in greater detail in Sections 11 and 12 of this SOP.](##_Ref215568526)

[Once the HEC-HMS model is successfully calibrated with a reasonably long continuous simulation (recommended minimum of two water years), the model is tested over the full POR. The simulation is run at an hourly timestep. The length of the POR simulation may vary due to the boundary condition (precipitation, temperature, etc.) and observed data (streamflow, reservoir, etc.) available within the watershed.](##_Ref215568526)

###### [<span id="_Toc217044314" class="anchor"></span>Period of Record Simulation Parameters](##_Ref215568526)

[Initial POR simulation parameters are adopted from the successful continuous simulation calibration and adjusted as necessary to reasonably reproducing annual maximum flows throughout the watershed.](##_Ref215568526)

###### [<span id="_Toc217044315" class="anchor"></span>Period of Record Calibration](##_Ref215568526)

[The HEC-HMS modeler extracts and compares modeled to observed annual maximum peak flows at primary gage locations throughout each full water year of the POR simulation. If the simulation does not adequately match the observed annual maximum peaks, further adjustment to the POR simulation parameters may be needed. This may be an iterative process until the FFRD team feels the annual maximum peaks are reasonably replicated within the POR simulation. Final POR simulation parameters should still fall within the range of the event-based calibration parameters. Figures 6.1 and 6.2 provide examples of comparing modeled to observed annual maximum peak flows.\
](##_Ref215568526)

[<span id="_Toc214891697" class="anchor"></span>Figure 6.1. Direct Comparison Plots between Modeled and Observed Data](##_Ref215568526)

[<img src="media/image7.png" style="width:6.5in;height:6.5in" />\
](##_Ref215568526)

[<span id="_Toc214891698" class="anchor"></span>Figure 6.2. Using Plotting Positions to Plot Empirical Flow Frequency Curves\
for Both Modeled and Observed Peaks](##_Ref215568526)

[<img src="media/image8.png" style="width:6.5in;height:7.48958in" alt="Chart AI-generated content may be incorrect." />\
](##_Ref215568526)

###### [<span id="_Toc217044316" class="anchor"></span>Observed Liquid Water at Soil Surface Annual Maximum Series](##_Ref215568526)

[After review of the POR Simulation is complete, subbasin-averaged Annual Maximum Series of the Liquid Water at Soil Surface (LWASS) must be produced for multiple durations (e.g., 1-hour, 1-, 2-, and 3-days), if snow accumulation/melt processes were simulated. This is an important dataset that will be leveraged for the evaluation of stochastic model performance during the conformance phase of the project. Procedures for development are included within Job Aid 05, *Observed Gridded Data Preparation.*](##_Ref215568526)

#### [<span id="_Toc217044317" class="anchor"></span>Documentation of Hydrologic Modeling](##_Ref215568526)

[A set of standard reports is written for each phase in the FFRD project. Appendix B contains report templates that include hydrologic modeling sections.](##_Ref215568526)

[Table 6.4 summarizes locations of key hydraulic modeling documentation included in each of the reports.](##_Ref215568526)

[<span id="_Toc214892774" class="anchor"></span>Table 6.3. Locations of Key Hydrologic Modeling Documentation](##_Ref215568526)

| [Scoping and Data Preparation Phase Report](##_Ref215568526) | [Documentation of hydrologic model setup, delineations of model elements and contributions to the Model Linking Register and Name Table.](##_Ref215568526) |
|:---|----|
| [Calibration Phase Report](##_Ref215568526) | [Primary documentation of the hydrologic model development including watershed characteristics, methods, parameters, and calibration. Includes documentation of the calibration of both the event-based simulation and POR simulation.](##_Ref215568526) |
| [Conformance Phase Report](##_Ref215568526) | [Documentation of the use of the calibrated model results to create a range of antecedent conditions and model parameters for use in stochastic simulations. Description of any hydrologic model adjustments made to reasonably align with observed frequency data.](##_Ref215568526) |
| [Production Phase Report](##_Ref215568526) | [Descriptions of any hot fixes or patches required in the production phase.](##_Ref215568526) |

#### [<span id="_Toc217044318" class="anchor"></span>Hydrologic Model Review Process and Deliverables](##_Ref215568526)

[Model review is a critical part of the FFRD production process. Several review steps are required to ensure the final model delivered can effectively run in a stochastic environment and is capable of accurately depicting basin-wide flood risk on a broad scale. Review checklists are used to track comments regarding pre-defined aspects checked throughout the review process. Appendix A contains checklist templates.](##_Ref215568526)

[The following subsections describe specific review steps and associated deliveries.](##_Ref215568526)

###### [<span id="_Toc217044319" class="anchor"></span>Scoping and Data Preparation Phase Review](##_Ref215568526)

[The following hydrologic model review steps are completed during the scoping and data preparation phase.](##_Ref215568526)

######## [Coordination and Team Discussions](##_Ref215568526)

[Although not documented as a formal review, team coordination is required throughout the Scoping and Data Preparation phase. When the draft HMS model element delineations are complete, the full FFRD team reviews model layout. The HEC-HMS modeler meets with the FFRD team during the scoping and data preparation phase to review the layout and ensure the HMS subbasins and planned RAS modeling unit polygons are compatible and consistent with the model linking register, name table and dam model scoping table. The goal of this team coordination is the development and delivery of a comprehensive and cohesive scope for the project that will be leveraged later during the Calibration Phase.](##_Ref215568526)

######## [Scoping and Data Preparation Phase Review](##_Ref215568526)

[Final draft deliverables for all aspects of the Scoping and Data Preparation Phase are fully and formally reviewed prior to completion of the phase of work. The review is documented via the Scoping and Data Preparation Checklist, which requires multiple contributors.](##_Ref215568526)

[The checklist includes specific prompts for review of initial hydrologic model setup, naming conventions, meteorologic data preparation, and observed data preparation among other items. The hydrologic model setup, hydraulic model unit delineation, model linking register, naming table, and all other scoping and data preparation phase items are reviewed and documented in](##_Ref215568526)

[The deliverables that are solely the responsibility of the Hydrologic Modeler from the Scoping and Data Preparation Phase includes the following:](##_Ref215568526)

- 
- 
- 

######## [Model: Unzipped uncalibrated base HMS model posted to the *‘basin-data/project-scoping/hydrologic-uncalibrated-base-model/’*Report: Completion of the Hydrologic Modeling section of the Scoping and Data Preparation ReportChecklist: Population of pre-review commentary for checklist prompts related to hydrologic modeler deliveries. The checklist is centrally stored in the ‘documentation’ directory.Backcheck of Scoping and Data Preparation Phase Review](##_Ref215568526)

[The hydrologic modeler is responsible for responding to all comments related to hydrologic products generated during Scoping and Data Preparation review. Updates to the draft delivered products may be necessary to achieve close-out of the review.](##_Ref215568526)

###### [<span id="_Toc217044320" class="anchor"></span>Calibration Phase Reviews](##_Ref215568526)

[The hydrology review checklist is used to track comments regarding aspects checked throughout the calibration phase review process. This review checklist remains with the model and is used throughout the entire review calibration phase review process.](##_Ref215568526)

[The hydrologic model shall go through the following review steps during the calibration phase.](##_Ref215568526)

######## [Initial Progress Review](##_Ref215568526)

[The purpose of this early review is to ensure progress is being made toward delivery for review and for reviewers and team leads to provide support to modeling staff to ensure full guidance has been provided and that model development is adhering to FFRD standards. Model data is typically not transferred during this review, but webinars are held to show progress and discuss possible issues.](##_Ref215568526)

[Additional check-ins during model development may be useful and are encouraged as a best practice.](##_Ref215568526)

######## [Quality Control Review](##_Ref215568526)

[The deliverable will be posted to the Model Library *calibration* directory and will include:](##_Ref215568526)

- - 
  - 
- 
- 
- 

######## [<u>Model:</u> Unzipped model files posted to the *calibration/hydrology/* directory as described below:Working calibrated model files for all historical event and continuous simulation events/time periods, including all files and data required to run and replicate the results.Non-final model or data files associated with out-of-date runs should not be included.<u>Report</u>: Draft calibration phase hydrologic modeling section.<u>Checklist</u>: Hydrologic model review checklist for historical event and continuous simulation calibration with modeler comments/notes included for every review item. This ensures all aspects of the model to be reviewed have been addressed by the modeler. The checklist is centrally stored in the ‘documentation’ directory.<u>Reference material</u>: As needed.Backcheck of Quality Control Comments](##_Ref215568526)

[After QC comments have been provided by the review and addressed by the modeler. The updated deliverable will be posted to Model Library *calibration* directory, and the previous version will be moved to the archive subdirectory. This delivery will include the following:](##_Ref215568526)

- - 
  - 
- 
- 
- 

######## [<u>Model:</u> Unzipped model files posted to the *calibration/hydrology/* directory as described below:Calibrated model files for all historical event and continuous simulation events/time periods, including all files and data required to run and replicate the results.Non-final model or data files associated with out-of-date runs should not be included.<u>Report</u>: Final calibration phase hydrologic modeling section.<u>Checklist</u>: Hydrologic Model review checklist with Resolution of Reviewer Comments by Modeler section completed for all comments. The checklist is centrally stored in the ‘documentation’ directory.<u>Reference material</u>: As needed.Finalization of Calibration Phase Delivery](##_Ref215568526)

[Any necessary additional iterations of delivery updates to fully close the review will be similarly posted to the *calibration* directory and the previous version moved to archive. The final hydrologic modeling report section should also be posted.](##_Ref215568526)

###### [<span id="_Toc217044321" class="anchor"></span>Conformance Phase Reviews](##_Ref215568526)

[Two reviews are documented during the conformance phase, each with its own review checklist to document the close-out of all items. Both checklists require input from the multiple team members.](##_Ref215568526)

######## [Pre-Conformance Review](##_Ref215568526)

[After the calibration phase is complete, the ownership of the model will transition to a smaller model integration team who will promote a copy of the calibrated models to the ‘***conformance’*** directory. Certain changes to the model will be made to ensure synthetic stochastic events can be executed successfully.](##_Ref215568526)

[The Pre-conformance review checklist ensures all calibrated models are fully prepared for cloud-compute that occurs during the conformance phase. This checklist includes items related to model integration, linkages and naming conventions. This checklist also includes items related to the delivery of the multiple hydrologic model files for cloud compute which are described in more detail in sections 11 and 12 of this SOP.](##_Ref215568526)

######## [Conformance Phase Review](##_Ref215568526)

[The Conformance review checklist focuses on ensuring that results of a full realization of synthetic events meet conformance metrics established in Section 12 of this SOP. Items required to fully close of the conformance phase of the project are also included in terms of documentation and data management.](##_Ref215568526)

[<span id="_Toc217044322" class="anchor"></span>—Reservoir Operations\
Modeling](##_Ref215568526)
======================================================================

#### [<span id="_Toc217044323" class="anchor"></span>Reservoir Operations Modeling Context and Standards](##_Ref215568526)

[The reservoir operations model for an FFRD watershed should be capable of simulating the regulation of a flood event over a time window that includes the duration of a typical storm and the recession limb of resulting hydrographs. This section guides HEC-ResSim modelers on systems where a reservoir operations-specific model was deemed necessary to represent flood risk within a study basin and included in the Dam Scoping Table during the Scoping and Data Preparation phase of the project.](##_Ref215568526)

[Operations must include the changed behavior of the system of reservoirs if one or more reservoirs are interoperable.](##_Ref215568526)

[The reservoir operations models develop for FFRD will have the following characteristics:](##_Ref215568526)

- [Able to assess the level of modeling necessary to reasonably reflect the reservoir operations impacts to flood risks.](##_Ref215568526)

- [Capable of modeling operational behavior of any reservoirs whose impact is significant to the study flood risk assessment.](##_Ref215568526)

- [Capture reservoir systems operations that are significant to the flood risk assessment.](##_Ref215568526)

- [Coordinated for seamless integration into system of models in terms of alignments, naming conventions, and other modeling strategies](##_Ref215568526)

- [Not overly complex in order to run efficiently within the FFRD cloud compute framework with numerous statistically sampled scenarios.](##_Ref215568526)

- [Capable of accurately modeling reservoir response to flood event ranging from a 1/10 to 1/2,000 AEP in an event-based Monte Carlo simulation.](##_Ref215568526)

###### [<span id="_Toc217044324" class="anchor"></span>Role of USACE in Reservoir Operations Modeling](##_Ref215568526)

[The US Army Corps of Engineers has a unique role and responsibility regarding reservoirs that have flood risk management (FRM) objectives (e.g., USACE projects, projects under Section 7 of the 1944 Flood Control Act, and potentially others). USACE also has a particular role regarding breach considerations (Section [9.1.1](##_Ref208179738)). USACE is developing reservoir modeling training to guide the reservoir modeling approach, particularly in reflecting those FRM operations and dam breach scenarios. The FFRD National Implementation Management Group also has USACE reservoir modeling experts who shall support and review the work on the flood operations portion of all reservoirs that have flood risk management objectives.](##_Ref215568526)

###### [<span id="_Toc217044325" class="anchor"></span>Scope of Reservoir Operations Model](##_Ref215568526)

[The determination of which reservoirs require a reservoir operations model is done during the scoping and data preparation phase of the FFRD study (per the Dam Modeling Scoping Section [4.3.15](##_Ref208181855)). See the Job Aid 01, *Scoping Process*es, for details on the decision-making considerations and options for how dams and reservoirs shall be modeled.](##_Ref215568526)

###### [<span id="_Toc217044326" class="anchor"></span>Phases of Reservoir Operations Modeling](##_Ref215568526)

[The reservoir operations model is developed for a FFRD project in district phases following according to the workflows described in the Section 2 of this SOP. This reservoir operations modeling section applies to multiple phases, and high-level modeling tasks in each phase described below:](##_Ref215568526)

- [<u>Scoping and Data Preparation Phase</u>: High level scoping and selection of which reservoirs will be included in the reservoir operations model. Scoping of all Naming Conventions and a Model Linking Register is performed.](##_Ref215568526)

- [<u>Calibration Phase</u>: Development, calibration and stress testing of the reservoir operations model is performed. POR reservoir operations simulation is also performed.](##_Ref215568526)

- [<u>Conformance Phase</u>: Integration of the reservoir operations model into the system of models, computation of synthetic events in cloud-compute, and adjustments to all models to ensure performance conforms to defined quality metrics based for a single long-term realization.](##_Ref215568526)

- [<u>Production Phase</u>: Computation of multi-realization events. Reservoir operations model may require hotfixes or to address specific issues.](##_Ref215568526)

- [<u>Reporting Phase</u>: Compilation and delivery of results from the project.](##_Ref215568526)

###### [<span id="_Toc217044327" class="anchor"></span>Software Version](##_Ref215568526)

[The reservations operations model will be developed using HEC-ResSim version 3.5.1.](##_Ref215568526)

###### [<span id="_Toc217044328" class="anchor"></span>Data Provided to the Reservoir Operations Modeler](##_Ref215568526)

[A comprehensive shared dataset for the project is developed during the scoping and data preparation phase of the project. The reservoir operations model development begins during the calibration phase and will leverage this shared dataset. Key prepared datasets provided to the to the reservoir operations modeler include:](##_Ref215568526)

- [Dam Modeling Scope Table that described modeling treatment of each dam in the basin](##_Ref215568526)

- [List of reservoirs to be included in the reservoir operations model](##_Ref215568526)

- [Model Linking Register](##_Ref215568526)

- [Name Table for all elements in the full system of models](##_Ref215568526)

- [Existing H&H models and their documentation, if available](##_Ref215568526)

<!-- -->

- [A single, selected model most appropriate for conversion to the FFRD purpose](##_Ref215568526)

- [Other models, only if useful to the effort (e.g., if they have some data or operations that are important but were not present in the select model)](##_Ref215568526)

- [Associated documentation including information on the model’s metadata such as vertical datum and time zone.](##_Ref215568526)

<!-- -->

- [Dam physical data and Existing operations manuals including physical data](##_Ref215568526)

- [Reservoir physical data for each reservoir that needs to be modeled](##_Ref215568526)

<!-- -->

- [Elevation-flow capacity curves for hydraulic outlets](##_Ref215568526)

- [Top of dam (TOD) length, elevation, and if available, the overtopping elevation-flow curve](##_Ref215568526)

- [Pool elevation-storage-area curve](##_Ref215568526)

- [Net evaporation rates](##_Ref215568526)

<!-- -->

- [Operations guidance](##_Ref215568526)

<!-- -->

- [WCMs and water control plans](##_Ref215568526)

- [SOPs](##_Ref215568526)

- [Emergency Action Plans (EAPs)](##_Ref215568526)

- [FERC licenses for non-federal facilities](##_Ref215568526)

<!-- -->

- [Observed flow and water surface elevation data](##_Ref215568526)

- [Available historical timeseries data to include reservoir pool elevation, reservoir inflow and outflow, and observed flow data for any gages within the model extents](##_Ref215568526)

- [A HEC-ResSim modeler may need to review and identify history of change points in reservoir conditions (i.e., construction of new facilities in the watershed, new outlets at existing facilities, major operational changes, etc.).](##_Ref215568526)

###### [<span id="_Toc217044329" class="anchor"></span>Model Linking Strategy](##_Ref215568526)

[A comprehensive Model Linking Register and Naming Table will be developed during the scoping and data preparation phase prior to reservoir operations model development and will guide model development in terms of element names and common computation points (CCPs).](##_Ref215568526)

###### [<span id="_Toc217044330" class="anchor"></span>Comprehensive Naming Conventions](##_Ref215568526)

[Model naming conventions for all model elements are an important aspect of FFRD, as standard naming and descriptions may be also used to support queryable metadata through the Model Library. Consolidated requirements for naming conventions and project descriptions for HEC-RAS and other models are defined in Job Aid 06, *Standard Naming Conventions*.](##_Ref215568526)

###### [<span id="_Toc217044331" class="anchor"></span>Coordination with Other Models](##_Ref215568526)

[Throughout model development reservoir operations modeler coordinates with the technical lead, hydrologic modeler and hydraulic modelers to exchange input and output datasets as appropriate. Some typical points of this coordination are described below.](##_Ref215568526)

[The model linking plan and name table developed during the scoping phase of the project will guide model development and all boundary conditions setup. The reservoir operations modeler and technical lead will communicate any concerns regarding model linking that may arise during the model development process with the full modeling team.](##_Ref215568526)

######## [Hydrologic Model](##_Ref215568526)

[As communicated through the Model Linking Register, careful linking of hydrologic model outputs to reservoir operations inputs in an important aspect of the modeling system. The model linking plan will be developed during the scoping and data preparation phase, and any issues identified during the calibration or conformance phase regarding this linking plan must be coordinated with the technical lead and hydrologic modeler. The HEC-ResSim modeler will need to coordinate closely with the HEC-HMS modeler to ensure that all CCPs where HEC-ResSim will need data from HEC-HMS are included](##_Ref215568526)

######## [Hydraulic Model](##_Ref215568526)

[As communicated through the Model Linking Register, careful linking of reservoir operations outputs to hydraulic model inputs is an important aspect of FFRD modeling. The model linking register will be developed during the scoping and data preparation phase, and any issues identified during the calibration or conformance phase regarding this mapping must be coordinated with the technical lead and hydraulic modeler.](##_Ref215568526)

[The outflow assumptions must be carefully coordinated between the hydraulic and reservoir operations model particularly for large events that overtop dams or for dam breach events.](##_Ref215568526)

#### [<span id="_Toc217044332" class="anchor"></span>Model Setup](##_Ref215568526)

[The following sections describe the process and standards for hydrologic model development for FFRD projects. Guidelines for reservoir operations modeling activities during this phase are described in the sections below.](##_Ref215568526)

###### [<span id="_Toc217044333" class="anchor"></span>Vertical Datum](##_Ref215568526)

[The modeler needs to confirm that any necessary datum shift has been applied to all physical properties, as well as any rules or scripts that reference an elevation. All historic records also need to be in NAVD 88. The user should also note that the model is using NAVD 88 in the reservoir editor description and any other description fields where there is potential for uncertainty. **Do not use the *Vertical Datum* feature in HEC-ResSim, as it does not work sufficiently in HEC-ResSim version 3.5 and has potential to corrupt the data.**](##_Ref215568526)

###### [<span id="_Toc217044334" class="anchor"></span>Time Zone](##_Ref215568526)

[UTC should be used when applying any rules that reference time, and this effort should be noted in the reservoir editor description field.](##_Ref215568526)

###### [<span id="_Toc217044335" class="anchor"></span>Definition of Model Extents](##_Ref215568526)

[Reservoirs to include in the reservoir operations model are determined during the scoping and data preparation phase as described in previous sections.](##_Ref215568526)

[The HEC-ResSim model network must cover the most upstream CCPs needed to determine reservoir operations—typically this is the inflow to the most upstream reservoir or an upstream gage used to determine operations—down to the outlet of the watershed. To minimize compute time and size, the extents of the reservoir operations model are limited to elements required for the computation of the reservoir operations.](##_Ref215568526)

[For the portions of the HEC-ResSim model that overlay with the HEC-HMS models, the HEC-ResSim model must include all the junctions within that extent. These junctions are CCPs, and they must be placed at the same locations to ensure data handoff between the models. Reach routing methods and parameters must also match those used by the HEC-HMS and HEC-RAS models.](##_Ref215568526)

[Generally, a single HEC-ResSim model – one network and one ResSim alternative -- should be used for the entire HUC4 watershed, covering all the reservoirs that have been selected for modeling. However, if a headwaters basin requires a smaller timestep than the rest of the basin, it may be necessary to split the basins into separate HEC-ResSim models so that each can use a different run timestep. Should this approach be needed, it is important to note that there can be no downstream dependency represented in the headwaters model due to the nature of the directed acyclic graph.](##_Ref215568526)

###### [<span id="_Toc217044336" class="anchor"></span>Watershed Configuration](##_Ref215568526)

[The HEC-ResSim modeler will need to coordinate closely with the HEC-HMS modeler to ensure that all CCPs where HEC-ResSim will need data from HEC-HMS are included. The HEC-ResSim model should also use the shared basin maps and stream centerlines established for the project during the scoping and data preparation phase. While it would be ideal for the stream centerlines to be identical across all models, it is not necessary for HEC-ResSim. If there are changes that are made to the centerlines during HEC-RAS model development, the updated streams do not need to be incorporated into the HEC-ResSim model.](##_Ref215568526)

######## [Common Computation Points or Junctions](##_Ref215568526)

[Model Linking Register and Name Table are developed during the Scoping and Data Preparation Phase and provided prior to the start of reservoir operations model development during the Calibration Phase. They guide the naming of network elements to ensure naming consistency and linking compatibility across all models.](##_Ref215568526)

[CCPs in the watershed configuration are shared across models as hand off points for data. These are represented in the HEC-ResSim network as junctions joining routing reaches and reservoirs. Junction locations include confluences, the downstream and upstream ends of reservoirs, anywhere that an inflow is to be added to the river, stream gage locations, and at control points where flow or stage is used to determine reservoir operations.](##_Ref215568526)

######## [Reservoirs and Diversions](##_Ref215568526)

[The reservoirs and diversion elements are included in the Reservoir Operations model as determined during the scoping and data preparation phase.](##_Ref215568526)

###### [<span id="_Toc217044337" class="anchor"></span>Linking for Historic Events versus Stochastic Events](##_Ref215568526)

[During the FFRD Calibration Phase, the HEC-ResSim model is developed, tested, and calibrated leveraging observed data. For stochastic events to be computed during the Conformance Phase and Production Phase of the FFRD project, the model will utilize the HEC-HMS simulated inflows.](##_Ref215568526)

######## [Local Inflows](##_Ref215568526)

[Local inflows are developed in coordination with the HEC-HMS models from their calibration dataset but are not derived from the HEC-HMS model results until the HEC-ResSim model validation is complete. Gage data used for local inflows is converted to the appropriate timestep for the model by period averaging. Incremental or local inflows are estimated as the difference between downstream and upstream gages. Gap-filling methods may be applied on inflow timeseries.](##_Ref215568526)

######## [Historical Observed Data for Calibration](##_Ref215568526)

[Observed reservoir outflows and pool elevations do not have significant processing applied unless being used to control the Set Q/Set Z historical data alternatives described in Section 6.4.1.](##_Ref215568526)

#### [<span id="_Toc217044338" class="anchor"></span>Reservoir Network Development](##_Ref215568526)

[The HEC-ResSim modeler creates a reservoir network based on the watershed configuration. For FFRD, only one network is necessary since the physical arrangement of elements should not change.](##_Ref215568526)

###### [<span id="_Toc217044339" class="anchor"></span>Network Configuration for FFRD Project Scoping](##_Ref215568526)

[The configuration of Reservoirs, Dams and Outlets in the model must be fully accounted for in the Name Table and Model Linking Register documents. These documents are prepared during the scoping and data preparation phase and provide a clear point of communication as the team ensures that model linkages can be made seamlessly.](##_Ref215568526)

[Some reservoirs have simple operations but are scoped for inclusion in the ResSim model because they impact the operational decisions made by other reservoirs within the system. These simple operations may be modeled using simple rules or run of river/guide curve operation, in which outflow typically equals inflow.](##_Ref215568526)

###### [<span id="_Toc217044340" class="anchor"></span>Physical Data General Considerations](##_Ref215568526)

[Once the modeler has determined which physical data to incorporate into the model, they must also document the source of the data (along with any data processing that was performed) in the final report. If the modeler digitizes any physical data, a copy of the digitized items must be saved with the report to provide alongside all the deliverables.](##_Ref215568526)

[To address curve resolution, half- or tenth-foot increments are used for physical capacity curves unless necessary to capture the shape of the curve. Hundredth-foot increments are not necessary and discouraged unless other models are using them, and the team agrees this is a necessary level of refinement.](##_Ref215568526)

###### [<span id="_Toc217044341" class="anchor"></span>Initial Pool Elevations](##_Ref215568526)

[For the POR run, the lookback pool elevation should use the observed value. If there is no observed value, the model should set the lookback to start at guide curve or typical normal pool.](##_Ref215568526)

[For the FFRD event compute, it should be set to use the time series of the initial pool elevation from HMS (which comes from the bootstrapping sampling).](##_Ref215568526)

###### [<span id="_Toc217044342" class="anchor"></span>Reach Routing Methods](##_Ref215568526)

[Routing methods and parameters are derived from the HEC-HMS or HEC-RAS models wherever routing reach model elements overlap. Modified Puls is the preferred HEC-ResSim routing method when parameters are acquired from high quality calibrated 1D hydraulic model. If Modified Puls is not available, Muskingum Cunge with 8-point cross sections is the secondary preferred routing method. The physical characteristics for this method can be copied from the HEC-HMS model. The number of sub-reaches is adjusted as appropriate for the reservoir operations model timestep. The HEC-ResSim modeler will need to coordinate with the HEC-HMS modeler on any losses or gains in the network including, but not limited to, irrigation and diversions.](##_Ref215568526)

###### [<span id="_Toc217044343" class="anchor"></span>Rating Curves at Control Points](##_Ref215568526)

[Rating curves used within the HEC-ResSim model for downstream controls must be validated. The HEC-ResSim modeler must work with the HEC-HMS and HEC-RAS modelers to validate and finalize the curves.](##_Ref215568526)

###### [<span id="_Toc217044344" class="anchor"></span>Physical Capacity Definitions](##_Ref215568526)

[Capacity curves are provided from the most up-to-date sources available—typically found in the WCM. Capacity curves need to be extrapolated to cover the full range of elevations likely to be experienced under the events sampled for the model. Elevation-storage-area (ESA) curves are defined as being above the highest pool elevation expected during a probable maximum flood (PMF) event, extrapolating if necessary. Outlet capacity curves are defined from their entire operable range, or for a spillway to the same elevation as the ESA curves.](##_Ref215568526)

######## [Reservoir Pool Elevation-Storage-Area Curves](##_Ref215568526)

[For model validation, elevation-storage relationship must match the ESA curve used for calculation of storage and inflows in the observed dataset used to calculate reservoir inflows, otherwise a mass balance error will occur. Often, the ESA curve is developed from surveyed pool bathymetry and updated as part of sedimentation studies. This may result in several breakpoints in the observed data, making it difficult to validate the model across a full POR.](##_Ref215568526)

[Area is only necessary if evaporation is modeled.](##_Ref215568526)

######## [Outlets](##_Ref215568526)

[Outlets may have various names across various sources of documentation, and care should be taken to ensure all outlets are properly accounted for. Reviewing a blueprint or as-built drawings for the dam may be useful in identifying outlets requiring modeling and the correct number of each type.](##_Ref215568526)

[If a facility has a system of gates, or several outlets with identical release capacity curves, the outlet is modeled as a single outlet element with the number of gates set to the appropriate number. Do not use a composite curve that does not indicate the number of gates.](##_Ref215568526)

- [**Controlled Outlets**—Gated Spillways, Regulating Outlets—Gated spillways and regulated outlets are modeled with the controlled outlet element type.](##_Ref215568526)

- [**Controlled Outlets: Powerplants**—Use controlled outlets for powerplants unless there are operations determining net release from the reservoir as a function of hydropower production required. If only hydraulic capacity is known, or power production expressed as energy or power available is not a significant factor in reservoir operations, the most efficient choice is to model these as a controlled outlet. Modeling these outlets as a powerplant requires additional details about the turbine capacity that may not be available for non-federal projects.](##_Ref215568526)

- [**Uncontrolled Outlets**—Uncontrolled outlets represent spillways, emergency overflows, and other structures with a known physical capacity curve. The release through these outlets always takes priority over the release allocation and operating rules.](##_Ref215568526)

- [**Estimating Physical Capacity Curves if Unavailable**—If a physical capacity curve is not available, estimates based on the weir equation and known or estimated physical dimensions may be used, and either verified directly by modeling with observed data, or compared against relationships between observed data, such as reservoir outflow and pool elevation.](##_Ref215568526)

- [**Implementing Physical Constraints as Rules**—Occasionally, reservoir physical constraints need to be defined as a rule, for example, outlets sharing a common penstock through the dam but releasing to different channels or having different capacities, and, due to the common penstock, are mutually exclusive. A rule in the operations set may be defined for such a constraint and is placed as the highest priority rule in each zone. These rules are clearly labeled as representing a physical capacity, using a prefix such as \[Physical\]-.](##_Ref215568526)

- [**TOD as an Uncontrolled Outlet**—If a dam is designed to overtop as part of normal or emergency operations, or as a capacity curve it is recommended that an uncontrolled outlet be added at the elevation of the TOD, and the TOD elevation for the dam is ignored. The TOD release used otherwise determines the capacity from the elevation and length of the TOD. If the TOD elevation varies, a capacity curve based on simple weir flow estimates may be developed. Extreme events in excess of the dam design flood must be accounted for.](##_Ref215568526)

- [**Other Outlets**—Evaporation, Leakage, Seepage—Reservoir evaporation, leakage, and seepage can be significant factors in reservoir mass balance. These are factored into the mass balance equation used to calculate the new pool storage and elevation at each timestep. Evaporation, leakage, and seepage are the only ways water can be removed from the reservoir below the inactive zone.](##_Ref215568526)

<!-- -->

- [**Evaporation** represents a net-loss of volume to the atmosphere and is removed from the pool storage at each timestep. A seasonal pattern based on average evaporation per day, expressed in a depth over pool area is the preferred way to enter evaporation for FFRD models. The use of a historical timeseries based on pan evaporation or other estimates may be valuable for model validation but should not be used for the delivered model.](##_Ref215568526)

- [**Leakage** though the dam represents water passed downstream without being lost from the system but not controlled by the dam. It can be defined as a constant value or a value for a given pool elevation. If neither of these is appropriate, or another method to calculate leakage or other miscellaneous releases is needed, a controlled outlet can be defined and governed by a rule labeled as a physical constraint and placed at the top of the rule priority stack in every zone.](##_Ref215568526)

- [**Seepage** is water lost from the pool into the groundwater below the reservoir. This water does not continue downstream and is lost from the model. If a documented seepage rate exists for a reservoir, it is entered as a seepage outlet. If the seepage relationship does not follow a typical relationship with pool elevation, it may be modeled with a diverted outlet and governed by a rule labeled as a physical constraint and placed at the top of the rule priority stack in every zone.](##_Ref215568526)

<!-- -->

- [**Breach Outlet**—Controlled outlet to circumvent the physical limitations of the reservoir in the event of breach event. If a breach event were to occur, the model should release run of river. Depending on the breach elevation, HEC-ResSim may run into physical limitations with the project gates. The breach outlet needs to have a large enough release capacity to match inflow.](##_Ref215568526)

###### [<span id="_Toc217044345" class="anchor"></span>Scripts](##_Ref215568526)

[The use of scripts for FFRD models should be avoided whenever possible. Scripts should only be used in the HEC-ResSim model when necessary to reflect key operational decisions. Any scripts that are necessary to the model may not depend on any outside information, including external scripts and libraries. HEC-ResSim will not have access to external sources such as websites or network resources. If an operation requires external input, this can be accomplished using HEC-ResSim’s Global Variable feature. For scripted operations that depend on random behavior, if other simplifying assumptions cannot be made, modelers should use the random sampling option that depends on a reproducible seed value.](##_Ref215568526)

#### [<span id="_Toc217044346" class="anchor"></span>Initial Model Validation](##_Ref215568526)

[Two temporary alternatives are developed to test the reservoir network prior to the development of the final operations sets and alternatives. The intent of these two alternatives is to ensure the reservoir network passes flow correctly from upstream to downstream and ensure the physical capacity tables are reasonable and the inflow dataset used for model development and validation represents all of the inflows necessary to replicate historical operations.](##_Ref215568526)

[In developing these alternatives, a simple operations set is configured, typically starting with a run-of-river operations set containing no rules and holding the reservoir at full pool, followed by the Set Q/Set Z operations sets.](##_Ref215568526)

###### [<span id="_Toc217044347" class="anchor"></span>Check for Network Connectivity](##_Ref215568526)

[It is essential to develop a network connectivity alternative where a constant timeseries is mapped to each inflow location and the sum of the unregulated flow at the downstream-most junction (once steady-state has been reached) is confirmed to be equal to the constant value multiplied by the number of inflow locations. If this criterion is not met, there are two possibilities; either there are losses defined on one or more of the reaches in the system, or the network connectivity is not complete, and water is generated or removed from the system due to a misconnected element.](##_Ref215568526)

[To check for any losses defined on the routing reaches, use the Reach Report available in the Reservoir Network module. If losses are present, the modeler must determine whether the losses are a constant or a function of flow. If a function of flow, the modeler must determine the number of inflow nodes upstream of that reach to determine how much flow is lost. If defined losses are not responsible for the difference, the modeler should find the elements that have caused the break in the network. Working upstream in a binary search helps hone-in on elements causing the problem. These elements, and potentially the surrounding elements, must be deleted and redrawn. Then the network connectivity test should be rerun to confirm the fix was successful.](##_Ref215568526)

###### [<span id="_Toc217044348" class="anchor"></span>Historical Data Alternative (Set Q/Set Z)](##_Ref215568526)

[In order to validate that the reservoirs’ physical capacity definitions are reasonable, an alternative is created with simple operations that force the reservoir to follow observed data. This is achieved by creating an operations set at each project—either an operation set with a single rule in all zones that follows an external timeseries of releases (Set Q for flow) or an operation set with a zone that follows an external timeseries of observed pool elevation (Set Z for elevation). The other observed historical timeseries are mapped as observed data and used to validate that the reservoir’s releases and pool elevation follow closely. If this simulation does not show a close match, either a component of the reservoir’s mass balance is missing or incorrect, or the physical capacity is not correct, such as an outlet that does not have enough hydraulic capacity to pass historical inflow, or a pool elevation-storage relationship that is not the same as the one used to determine reservoir inflow.](##_Ref215568526)

#### [<span id="_Toc217044349" class="anchor"></span>Development of Reservoir Operations Sets](##_Ref215568526)

[The final model should only have one operation set; however, during development the modeler may need to develop several operation sets to test various alternatives. Prior to handoff, all operation sets except for the rule-based single FFRD event operations should be removed. While setting up the operation sets, the Description textboxes in the Reservoir Editor should be used to document data sources and any assumptions made.](##_Ref215568526)

###### [<span id="_Toc217044350" class="anchor"></span>Scope of Reservoir Operations Modeled](##_Ref215568526)

[FFRD models include formally documented operations and informal operations consistently used to achieve reservoir objectives. Occasional deviations and rule-of-thumb-type operations are avoided but may be modeled to assist with validation.](##_Ref215568526)

###### [<span id="_Toc217044351" class="anchor"></span>Review of Water Control Manuals, Standard Operating Procedures, Other Operating Documents](##_Ref215568526)

[The operating documents are reviewed and used to identify rules and operating zones. These include, but are not limited to:](##_Ref215568526)

- [WCMs for USACE-operated reservoirs and those operated by USACE under Section 7 of the Flood Control Act, or similar agreements. In particular, the water control plan, typically in Chapter 7 of the WCM, documents operations at the reservoir.](##_Ref215568526)

- [SOPs for U.S. Bureau of Reclamation (USBR)-operated reservoirs.](##_Ref215568526)

- [Fish Passage Plans, Biological Opinions, other documents used to determine ecosystem operations.](##_Ref215568526)

- [FERC licenses for hydropower facilities not operated by USACE.](##_Ref215568526)

[As a last resort, historical observed data is examined, particularly the outflow from the project or at gages immediately downstream and at potential damage centers downstream. Typical high and low flows, if consistent, may indicate a maximum and minimum release target from the reservoir.](##_Ref215568526)

[Operations are cataloged, by priority and applicable operating zone, identifying features such as:](##_Ref215568526)

- [Objective type: minimum, maximum, or specified release](##_Ref215568526)

- [Timing: seasonality, within-week, within-day, etc.](##_Ref215568526)

- [Control points downstream in the system](##_Ref215568526)

- [Other variables necessary to determine operations](##_Ref215568526)

- [Assumptions made in determining operations.](##_Ref215568526)

###### [The model should be comprehensive and not only focus on flood risk but instead should represent realistic operations throughout the year. Low flow operations including irrigation, water supply, ecosystem, and hydropower are to be included to the extent that reliable and consistent data to support these is available. Drought contingency rules do not need to be modeled in the single event alternative if not already incorporated or if they do not function properly with a shorter simulation window.<span id="_Toc217044352" class="anchor"></span>Definition of Zones](##_Ref215568526)

[At a minimum, a TOD, guide curve, and inactive zone must be specified. A normal top of flood control pool and conservation zone may also be defined, either of which may be the guide curve. Additional zones spelled out in the operating documents are specified and modeled.](##_Ref215568526)

[The TOD zone is located at the highest elevation at which any reservoir operations need to be modeled. Rules within this zone are only those used to operate the dam during an extreme flood event where dam safety is paramount. This zone does not include rules to limit flows for downstream locations.](##_Ref215568526)

[The guide curve zone is the target elevation for the reservoir. This zone may be prescribed as part of the operating documents, or, if that is unavailable due to the reservoir not having a flood risk management purpose, an average of historical values by season may be used.](##_Ref215568526)

[The inactive zone is the lowest zone and contains no rules. When the pool elevation is in this zone, only evaporation, leakage, and seepage demands are met.](##_Ref215568526)

###### [<span id="_Toc217044353" class="anchor"></span>Definition of Rules](##_Ref215568526)

[Rules derived from the WCM, SOP, and other operating documents should be implemented first. Each objective in the WCM should be modeled separately. For example, do not combine minimum flow rules for ecosystem and navigation requirements, or various ecosystem rules. Documentation should identify which objective in the operating documents is supported by each rule.](##_Ref215568526)

[Informal rules based on the experience of the operators should be clearly labeled and thoroughly tested before inclusion in the deliverable. Any deviation from documented operations required to help smooth or stabilize the operation of the HEC-ResSim model should be clearly labeled as such.](##_Ref215568526)

###### [<span id="_Toc217044354" class="anchor"></span>Modeling for Dam Breach](##_Ref215568526)

[Each reservoir that has been selected as a potential breach location for modeling (likely all reservoirs represented in the HEC-ResSim model), shall be set up to allow for the triggering of dam breach scenarios based on externally sampled breach elevations. Breach scenarios are triggered in HEC-ResSim based on comparing the pool elevation to the sampled breach elevation. If a breach is triggered in HEC-ResSim, the reservoir operations are shifted to run-of-river and HEC-RAS takes full responsibility for modeling the actual breach conditions and flows. Thus, the primary goal of breach modeling in HEC-ResSim is to determine if and when breaches are triggered and if, after a breach, the HEC-ResSim model is no longer simulating the expected scenario; in particular, downstream reservoirs do not see the inflows that would occur during and after a breach.](##_Ref215568526)

[To model a breach event in HEC-ResSim, an additional rule nested within an if/else block should be incorporated into the model and added to all zones. This nested condition would dictate that if a target elevation is met or exceeded, the outflow will match inflow. The model should be developed to allow the breach elevation to vary. To accomplish this, set up the breach elevation using a scalar input global variable. A state variable will be needed to pull the global variable value into the operation rule set. An additional rule must be created and added to the Else portion that states if a breach is not occurring, releases from the Breach Outlet must be zero.\
](##_Ref215568526)

#### [<span id="_Toc217044355" class="anchor"></span>Development of Reservoir Operations Alternatives](##_Ref215568526)

[During model development, the modeler will need create the following alternatives to calibrate and test the model:](##_Ref215568526)

- [Network Connectivity Alternative](##_Ref215568526)

- [Historic Data Alternative](##_Ref215568526)

- [Single Event Alternative](##_Ref215568526)

- [Extreme Event Alternative](##_Ref215568526)

[For handoff, a copy of the model needs to be created where all alternatives, with the exception the Single Event Alternative, need to be deleted.](##_Ref215568526)

###### [<span id="_Toc217044356" class="anchor"></span>Setting Antecedent Conditions for Operations](##_Ref215568526) 

[HEC-ResSim simulations require a lookback window, which is a period of warmup time to ensure water is routed through the full network before the simulation period with release decisions actually begins. Model alternatives require the setting of antecedent conditions via the lookback feature. Typically, it is recommended that the lookback time window should cover a period sufficient for water to be routed from the uppermost headwaters input to the furthest downstream location. For the many of the FFRD reservoir models, it is not reasonable to have the HEC-HMS model run each event for such a long period of time that would be necessary to provide sufficient lookback inflows. Instead of getting inflows from HEC-HMS, the HEC-ResSim POR run will be used to obtain lookback data associated with the historic data preceding each sampled event.](##_Ref215568526)

[To best prepare the model for such lookback sampling, some simplifications should be made to operations that typically depend on institutional antecedent conditions. Institutional antecedent conditions, or operational antecedent conditions are variables not directly or significantly tied to hydrology (e.g., history of gate maintenance, deliveries of water supply or hydropower, and things that inform operations but should not or cannot be modeled). When an operation requires data that begins significantly before the event, the possible approaches, in order of preference, are to simplify that condition out of the model, reduce the operation to the essentials (e.g., to limit the length of lookback time needed), or convert a dependency to a randomly sampled variable that reflects the probability of occurrence if a lookback requires an excessive historic time period. This can be accomplished through the use of the HEC-ResSim Monte Carlo feature or a seeded random generation from a previous plugin in the compute, if necessary.](##_Ref215568526)

###### [<span id="_Toc217044357" class="anchor"></span>Timestep and Computation Method](##_Ref215568526)

[The HEC-ResSim model uses a timestep appropriate to capture the duration of a flood event with an adequate resolution to represent the rate of change constraints and routing effects to control points. Typically, this is somewhere between hourly and six-hour timesteps but may be shorter for small reservoirs and flashy watersheds. HEC-ResSim does not allow for multi-timestep routing through long reservoir pools. Pool inflows become available, releasable storage for the following timestep. If one of these small reservoirs is responsible for increasing the overall model timestep, and can be modeled independently of the others, it should be broken out into a separate reservoir operations network and model alternative.](##_Ref215568526)

[Period average is the preferred flow computation method for all alternatives.](##_Ref215568526)

###### [<span id="_Toc217044358" class="anchor"></span>Period of Record Model Considerations](##_Ref215568526)

[A POR model is run for the watershed to determine a distribution of initial starting conditions for the reservoir during event-based modeling. This POR compute is necessary to apply current operations to the whole POR, during which the operations may not have been constant over time. Antecedent conditions will be selected from the POR output associated with the sampled event storm and date. The model will select a starting point from a 2-week period around the actual date across all historic years and HEC-HMS and HEC-ResSim will select a starting point from the POR that is representative of that time of year and consistent across hydrologic and reservoir antecedent conditions. Long-term operations related to demand rules, water quality, ecosystem operations, hydropower, and drought conditions, should be included in the POR run, but they should be simplified to reflect a consistent pattern to the extent possible. For example, do not model the POR using nonstationary demands or rules from specific periods of time. Instead base the POR operations on the current conditions to the extent that they can be considered stationary or use a short-term window to develop high medium and low curves.](##_Ref215568526)

###### [<span id="_Toc217044359" class="anchor"></span>Event-based Model Considerations](##_Ref215568526)

[The model is ultimately configured for event-based modeling, using HEC-ResSim POR results to set the initial values for pool elevation, gate releases, and inflow time series in the Alternative Editor Lookback tab.](##_Ref215568526)

[The model does not rely on parameters that may be unavailable within the event, such as an operation that depends on the value of a variable several months prior. If this is the case, a Monte Carlo variable is used to provide a randomly sampled input, with the distribution of the variable derived from the POR compute.](##_Ref215568526)

[Each event simulation time window should be set up to include a lookback window that meets the minimum time requirement determined as the time necessary for inflow to be routed from the highest decision point to the lowest downstream flow location, or approximately 2 weeks, whichever is less. The HEC-ResSim modeler should work with the HEC-HMS modeler to ensure that the event time extends long enough to capture the recession limb of the event.](##_Ref215568526)

#### [<span id="_Toc217044360" class="anchor"></span>Saved Output Settings](##_Ref215568526)

[ResSim has default settings in the Alternative Editor that should be adjusted prior to final handoff. These changes will ensure the correct data is being written out, will remove superfluous data, and will cut down on the run folder file size.](##_Ref215568526)

[Bare minimum - anything the RAS model requires, pool elevations, control point flows, gate flows.](##_Ref215568526)

[In ResSim alternative editor, modify the DSS Output by unchecking “Write all computed Time series” and selecting only keep reservoir elevation, junctions and key state variables. Reaches, diversions and all other reservoir time series will typically be left as not selected.](##_Ref215568526)

[The Run Control tab in the Alternative Editor defaults the Flow Computation Method to Program Determined. For ResSim runs, it is usually recommended that this is set to Period Average if the input time series is greater than 1 hour; however, this can cause issues for the RAS model. If the time step is 1 hour or less, the ResSim modeler can set the flow computation method to instantaneous. If the time step is greater than 1 hour, the ResSim modeler should set the flow computation method to period average and the RAS modeler will need to process the data prior to inputting it into the RAS model.](##_Ref215568526)

[The DSS Output tab can also be pared down. A more detailed description on the output settings can be found in Job Aid 13, *Model Delivery for Cloud Compute*.](##_Ref215568526)

#### [<span id="_Toc217044361" class="anchor"></span>Simulations for Validation and Testing](##_Ref215568526)

[Four types of runs are completed to validate and review the performance of the HEC-ResSim model alternatives: event-based computes of historical floods, single event computes using HEC-HMS outputs, synthetic extreme event computes, and a POR compute.](##_Ref215568526)

###### [<span id="_Toc217044362" class="anchor"></span>Historical Event-based Computes](##_Ref215568526)

[The event-based compute for historical floods is chosen for an event within the recent POR in which operations are most similar to the current operations of reservoirs within the basin, and other projects that are in place within the watershed. If none of these are available in the recent record, older models are used but decisions are validated by a closer examination of performance and checking that relevant operating constraints are met.](##_Ref215568526)

###### [<span id="_Toc217044363" class="anchor"></span>Extreme Events Stress Testing Computes](##_Ref215568526)

[Synthetic extreme events are used to evaluate the performance of the HEC-ResSim model for large flows as stress testing in preparation for the distributed cloud compute. The intent of these computes is to show that the operation sets behave appropriately for events larger than observed. This should catch issues with operations, like oscillating zone boundary around top of flood pool, as well as physical data issues like spillway curves that are not defined above top of the flood control zone.](##_Ref215568526)

[A sufficiently large event is one that confirms the model operates correctly through any surcharge operations and up to the dam crest. Specifications for large flood events, such as the standard project flood (SPF), design flood, and/or PMF may be found in design documents or other studies for the reservoir and may be accompanied by an estimate of regulated outflow during such an event. Typically, the SPF is a good event stress test, although the stress test doesn’t necessarily need to target a certain probability or use realistic hydrology. If the extreme events available do not sufficiently stress the reservoir’s operations, the use of an inflow multiplier with a synthetic or historical event can be used.](##_Ref215568526)

[Evaluation of the extreme event runs provides stress testing confirms the flood risk management objectives are met correctly for large events, rules are operating correctly, and outlet capacity curves at high elevations and flows are defined correctly.](##_Ref215568526)

###### [<span id="_Toc217044364" class="anchor"></span>Hydrologic Modeling System Event Based Compute](##_Ref215568526)

[The HEC-HMS are single event simulations that are run using time series data from the HEC-HMS model. These simulations will ensure that the models are linking correctly and can successfully run. While the HEC-HMS simulations may not match historic, the modeler should review the results to confirm that HEC-ResSim is making the right decisions based on its operation set.](##_Ref215568526)

###### [<span id="_Toc217044365" class="anchor"></span>Hydrologic Modeling System Period of Record](##_Ref215568526)

[The HEC-ResSim modeler will need to run a simulation using the HEC-HMS POR event. The output from this simulation will be provided back the HEC-HMS modeler so that they can include the reservoir elevations in the run used to create bootstrap save states. This will ensure spatial variation of basin parameters and reservoir contents. The HEC-ResSim model should then be configured to read the initial pool elevation from an external timeseries, which will be linked to the timeseries output by the HEC-HMS model in the FFRD event computes.](##_Ref215568526)

#### [<span id="_Toc217044366" class="anchor"></span>Documenation of Reservoir Operations Modeling](##_Ref215568526)

[A set of standard reports is written for each phase in the FFRD project. Appendix B contains report templates for the hydraulic modeling reports.](##_Ref215568526)

[Table 7.1 summarizes locations of key hydraulic modeling documentation included in each of the reports.](##_Ref215568526)

[<span id="_Toc214892775" class="anchor"></span>Table 7.1. Locations of Key Hydraulic Modeling Documentation](##_Ref215568526)

<table>
<colgroup>
<col style="width: 30%" />
<col style="width: 69%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;"><a href="##_Ref215568526">Scoping and Data Preparation Phase Report</a></th>
<th><p><a href="##_Ref215568526">Documentation of selection and rational of Dam Modeling approach for each dam in the basin, including a list of dams that will be included in the reservoir simulations modeling effort.</a></p>
<p><a href="##_Ref215568526">The Model Linking Register that includes details regarding the plan for linking reservoir output data to the hydraulic model is also established and documented in this report.</a></p></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Calibration Phase Report</a></td>
<td><a href="##_Ref215568526">Primary documentation of reservoir operations model development, calibration and stress testing.</a></td>
</tr>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Conformance Phase Report</a></td>
<td><a href="##_Ref215568526">Description of all reservoir operations model adjustments made to accept synthetic SST events and any other adjustments to reasonably align with observed frequency data</a></td>
</tr>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Production Phase Report</a></td>
<td><a href="##_Ref215568526">Descriptions of any reservoir operations model hot fixes or patches required in the production phase.</a></td>
</tr>
</tbody>
</table>

#### [<span id="_Toc217044367" class="anchor"></span>Reservoir Operations Model Review Process and Deliverables](##_Ref215568526)

[Model review is an important part of the FFRD production process. Several review steps are required to ensure the final model delivered can efficiently run in a stochastic environment and is capable of accurately simulating reservoir operations.](##_Ref215568526)

[The following subsections describe specific review steps.](##_Ref215568526)

###### [<span id="_Toc217044368" class="anchor"></span>Scoping and Data Preparation Phase Review](##_Ref215568526)

[The model linking register, naming table, and all other scoping and data preparation phase items are reviewed and documented in the Scoping and Data Preparation Checklist, which requires multiple reviewers and is described in Section 4.](##_Ref215568526)

[This Scoping and Data Preparation checklist includes items for review of overall configuration of the reservoir operations model.](##_Ref215568526)

###### [<span id="_Toc217044369" class="anchor"></span>Calibration Phase Reviews](##_Ref215568526)

[The reservoir operations review checklist is used to track comments regarding aspects checked throughout the calibration phase review process. This review checklist remains with the model and is used throughout the entire review calibration phase review process.](##_Ref215568526)

[The reservoir operations model shall go through the following review steps during the calibration phase.](##_Ref215568526)

######## [Initial Progress Review Web Meeting—informal](##_Ref215568526)

[The purpose of this early review is to ensure progress is being made toward delivery for review and for reviewers and team leads to provide support to modeling staff to ensure full guidance has been provided and that model development is adhering to FFRD standards. Model data is typically not transferred during this review, but webinars are held to show progress and discuss possible issues using screen sharing.](##_Ref215568526)

[Additional check-ins during model development may be useful and are encouraged as a best practice.](##_Ref215568526)

######## [Quality Control Review](##_Ref215568526) 

[The deliverable will be posted to the Model Library *calibration/reservoir-operations/* directory and will include:](##_Ref215568526)

- [Working calibrated model.](##_Ref215568526)

<!-- -->

- [A draft final model that includes all alternatives and simulations created during calibration of the model must be provided at handoff. The simulation DSS files from the simulation runs can be deleted prior to zipping up the model to help reduce space. In the event this model would be needed for reference, the user would only need to run an extract again and then recompute.](##_Ref215568526)

- [All temporary or unnecessary model files or references must be deleted from the delivery dataset](##_Ref215568526)

<!-- -->

- [Reservoir Operations QC review checklist with modeler comments/notes included for every review item. This ensures all aspects of the model to be reviewed have been addressed by the modeler.](##_Ref215568526)

- [Reservoir Operations Section of Report Draft Completed](##_Ref215568526)

- [Reference material.](##_Ref215568526)

######## [Backcheck of Quality Control Comments](##_Ref215568526)

[The updated deliverable will be posted to Model Library *calibration/reservoir-operations/* directory (previous version will be moved to archive according to directory structure guidance in Job Aid 07, *Model Library Use*) and will include the following:](##_Ref215568526)

- [Working, calibrated model for all scenarios.](##_Ref215568526)

- [Reservoir Operations Section of Report Completed](##_Ref215568526)

- [Reservoir Operations review checklist with Resolution of Reviewer Comments by Modeler section completed for all comments](##_Ref215568526)

######## [Finalization of Calibration Phase Delivery](##_Ref215568526)

[Any necessary additional iterations of delivery updates to fully close the review will be similarly posted to the *calibration* directory and the previous version moved to archive. The final reservoir operations modeling report section should also be posted.](##_Ref215568526)

###### [<span id="_Toc217044370" class="anchor"></span>Conformance Phase Reviews](##_Ref215568526)

[Two reviews are documented during the conformance phase, each with its own review checklist to document the close-out of all items. Both checklists require input from the multiple team members.](##_Ref215568526)

######## [Pre-conformance Review](##_Ref215568526)

[After the calibration phase is complete, the ownership of the model will transition to a smaller model integration team who will promote a copy of the calibrated models to the ***conformance*** directory. Certain changes to the model will be made to ensure synthetic stochastic events can be executed successfully.](##_Ref215568526)

[The Pre-conformance review checklist ensures all calibrated models are fully prepared for cloud-compute that occurs during the conformance phase. This checklist includes items related to model integration, linkages and naming conventions. This checklist also includes items related to the delivery of the multiple hydrologic model files for cloud compute which are described in more detail in sections 11 and 12 of this SOP.](##_Ref215568526)

[The final reservoir operations model to be provided for FFRD must only have one single network and single event alternative. Reference to Job Aid 13, *Model Delivery for Cloud Compute* for additional details.](##_Ref215568526)

######## [Conformance Review](##_Ref215568526)

[The Conformance review checklist focuses on ensuring that results of a full realization of synthetic events meet conformance metrics established in Section 12 of this SOP. Items required to fully close of the conformance phase of the project are also included in terms of documentation and data management.](##_Ref215568526)

- 

## [<span id="_Toc217044371" class="anchor"></span>—Hydraulic Modeling](##_Ref215568526)

#### [<span id="_Toc217044372" class="anchor"></span>Hydraulic Modeling Context and Standards](##_Ref215568526)

[The procedures outlined in this section document the process and standards for the development of hydraulic model to support the FFRD program. The FFRD hydraulic models created using this document are basin-level studies developed with the understanding that additional future refinement may be undertaken after the project is delivered. Practical run-time considerations have motivated many of the standards included in this section. Models produced following this guidance will have the following characteristics:](##_Ref215568526)

- [Foundational model that may be refined for any future detailed studies](##_Ref215568526)

- [Coordinated for seamless integration into system of models in terms of alignments, naming conventions, and other modeling strategies](##_Ref215568526)

- [Computationally efficient and stable model capable of producing reasonable results for the entire basin and adequate to run in a stochastic environment for many, many events](##_Ref215568526)

- [Capable of assessing both pluvial and fluvial flood hazard data across the range of natural variability from the 10-year to the 2,000-year modeled events (1/10 to 1/2,000 AEP)](##_Ref215568526)

- [Watershed wide systems-based accounting of water volume and timing during dam or levee breach events](##_Ref215568526)

- [Fully 2D geo-referenced, calibrated hydraulic model capable of simulating runoff when applied in conjunction with excess precipitation and baseflow provided by a separate hydrologic model](##_Ref215568526)

###### [<span id="_Toc217044373" class="anchor"></span>Phases of Hydraulic Modeling](##_Ref215568526)

[The hydraulic models are developed for a FFRD project in phases according to the workflows described in the Section 2 of this SOP. This hydraulic modeling section applies to multiple phases, and high-level hydraulic modeling tasks in each phase described below:](##_Ref215568526)

> [<u>Scoping and Data Preparation Phase</u>: High-level scoping of the hydraulic modeling units in terms of model unit extents, mesh development categories, input data preparation, naming table, and model linking plan.](##_Ref215568526)
>
> [<u>Calibration Phase</u>: Development and calibration of the hydraulic models to historic observed events.](##_Ref215568526)
>
> [<u>Conformance Phase</u>: Integration of the hydraulic model into the system of models, computation of synthetic events in cloud-compute, and adjustments to all models to ensure performance conforms to defined quality metrics based on a single 2,000-year realization.](##_Ref215568526)
>
> [<u>Production Phase</u>: Computation of multi-realization events. Hydraulic model may require hotfixes or updates to address specific issues.](##_Ref215568526)
>
> [<u>Reporting Phase</u>: Compilation and delivery of results from the project.](##_Ref215568526)

###### [<span id="_Toc217044374" class="anchor"></span>Software Version](##_Ref215568526)

[The hydraulic models will be developed using HEC-RAS version 6.6.](##_Ref215568526)

###### [<span id="_Toc217044375" class="anchor"></span>Data Provided to Hydraulic Modeler](##_Ref215568526)

[A comprehensive shared dataset for the project is developed during the scoping and data preparation phase of the project. The hydraulic model development begins during the calibration phase and will leverage the shared dataset. Key prepared datasets provided to the to the hydraulic modeler follow.](##_Ref215568526)

- [DEM: Full resolution DEM for consistent use for the entire FFRD project](##_Ref215568526)

- [Hydraulic Model Unit Polygon: The 2D modeling extent used for hydraulic model development and calibration. Each FFRD study basin is sub-divided into hydraulic modeling units to reduce the computational burden of the model and decrease the model development time.](##_Ref215568526)

- [Scope for mesh development](##_Ref215568526)

- [Urban areas polygons](##_Ref215568526)

- [Key streams](##_Ref215568526)

- [Other streams](##_Ref215568526)

- [Observed flow and water surface elevation data](##_Ref215568526)

- [Stream Gages for Calibration – including assigned of categories for calibration criteria](##_Ref215568526)

- [Selected Historic Storm Events for calibration](##_Ref215568526)

- [Elevation derived hydrography (stream centerlines aligned with DEM flow paths)](##_Ref215568526)

- [Levee alignments and profiles](##_Ref215568526)

- [Levee physical data](##_Ref215568526)

- [Levee breach locations for FFRD modeling (overtopping locations to be verified by hydraulic modeler)](##_Ref215568526)

- [Levee operations manuals when available](##_Ref215568526)

- [Dam physical data](##_Ref215568526)

- [Dam modeling scope defining modeling treatment of each dam in the basin](##_Ref215568526)

- [Dam operations manuals when available](##_Ref215568526)

- [Comprehensive naming table](##_Ref215568526)

- [Model Linking Register](##_Ref215568526)

- [Bathymetry: All available bathymetry for rivers, lakes and reservoirs](##_Ref215568526)

- [Land cover dataset](##_Ref215568526)

- [Existing hydraulic models](##_Ref215568526)

- [Various other reference layers](##_Ref215568526)

[The hydraulic modeler should fully utilize the provided shared datasets and limit searches for alternative or competing datasets. However, the modeler may become aware of additional data sources that could be used to support model development. Improved input data can increase the quality of the delivered model and is encouraged if it does not impede model production and delivery. Note that any new data must be coordinated with the technical lead and shared with the full modeling team. Note that some datasets may be deemed too detailed for direct incorporation into the FFRD hydraulic model.](##_Ref215568526)

[The scope for hydraulic model mesh development is well defined during the scoping and data preparation phase, but the modeler may identify certain areas where a high level of refinement could be efficiently included in the model to increase model accuracy without increasing the scope. Any proposed scope increases must be requested and approved by program leadership prior to implementation.](##_Ref215568526)

###### [<span id="_Toc217044376" class="anchor"></span>Custom Reference Data](##_Ref215568526)

[This SOP includes direction to utilize a common set of shared basin data that is created during the scoping and data preparation phase, which are stored in the *ffrd\_\[basin-name\]/basin-data/* directory. Each hydraulic modeling unit will reference this official data for many aspects of the modeling process.](##_Ref215568526)

[However, there are some datasets that will be developed during model development specifically to support an individual model. For calibration phase deliverables, these datasets typically should be saved within a reference directory inside the *model-unit* directory (*ffrd\_\[basin-name\]/calibration/hydraulics/\[model-unit\]/*).](##_Ref215568526)

###### [<span id="_Toc217044377" class="anchor"></span>Model Linking Strategy](##_Ref215568526)

- [A Model Linking Register and Naming Table will be developed during the scoping and data preparation phase prior to hydraulic model development. During the calibration phase of the project, the model is developed and calibrated against observed historic events. During the conformance phase of the project, the models are adapted to fully accept modeled output from synthetic storm events as boundary conditions rather than observed data. For model development during the calibration phase the hydraulic model will apply the following boundary conditions:**Gridded Excess Precipitation Data (Hydrologic Model Output)—**This is a time series gridded data set of excess precipitation data developed from a calibrated hydrologic model used as a boundary condition in the 2D model.](##_Ref215568526)

- [**Baseflow Data (Hydrologic Model Output)—**This is a time series data set of baseflow data for each subbasin developed from a calibrated hydrologic model used as inflow boundary conditions in the 2D model.](##_Ref215568526)

- [**Upstream Inflows—**For non-headwaters basins, upstream inflows will be sourced from either observed gage data or other FFRD model results (upstream hydraulic model, hydrologic model, or reservoir operations model results).](##_Ref215568526)

- [**Downstream Water Surface—**Downstream water surfaces will be modeled with either a rating curve, normal depth assumption, or an appropriate water surface related to a large water body. In some cases, it will be appropriate to increase the model extent beyond the scoped model unit to avoid errors introduced by the downstream water surface assumption.](##_Ref215568526)

- [**Other Boundary Conditions—**When appropriate, other boundary conditions will be used in certain situations such as initial water surfaces or internal flow time series at dams.](##_Ref215568526)

[Adjustments to model linkages that will be necessary for fully synthetic events modeled in the conformance phase will be accounted for in the Model Linking Register. Common adjustments include:](##_Ref215568526)

- 
- 
- 

######## [Use of dam outflows modeled by either the reservoir simulations or hydraulic model rather than use of observed dataUse of modeled inflows from an upstream hydraulic model rather than from a stream gageUse of a downstream rating curve or assumed water surface boundary condition rather from an observed stream gageNaming for Modeling Linking Elements](##_Ref215568526)

[All hydraulic model files and model elements will be named according to the comprehensive naming table and model linking register provided to the modeler prior to the start of model development.](##_Ref215568526)

###### [<span id="_Toc217044378" class="anchor"></span>Comprehensive Naming Conventions](##_Ref215568526)

[Model naming conventions for all model elements are an important aspect of FFRD, as standard naming and descriptions may be also used to support queryable metadata through the Model Library. Consolidated requirements for naming conventions and project descriptions for HEC-RAS and other models are defined in Job Aid 06, *Standard Naming Conventions*.](##_Ref215568526)

###### [<span id="_Toc217044379" class="anchor"></span>Coordination with Other Models](##_Ref215568526)

[Throughout model development and calibration, the hydraulic modeler coordinates with the technical lead, hydrologic modeler and reservoir operations modeler to exchange input and output datasets as appropriate. Some typical points of this coordination are described below.](##_Ref215568526)

[The model linking register and name table developed during the scoping phase of the project will guide model development and all boundary conditions setup. The hydraulic modeler and technical lead will communicate any concerns regarding model linking that may arise during the model development process with the full modeling team.](##_Ref215568526)

[Note that hydrologic subbasin delineation will be aligned with the hydraulic model unit delineation during the scoping and data preparation phase.](##_Ref215568526)

######## [Hydrologic Model](##_Ref215568526)

[Early iterations of hydrologic model results may be insufficient to achieve calibration targets when they are applied to the hydraulic model. The hydraulic and hydrologic modelers will work together to determine the most appropriate model adjustments to achieve calibration targets for both models.](##_Ref215568526)

######## [Reservoir Operations Model](##_Ref215568526)

[Careful linking of reservoir operations outputs to hydraulic model inputs is an important aspect of FFRD modeling. The model linking register will be developed during the scoping and data preparation phase, but any issues identified during the calibration or conformance phase regarding this mapping must be coordinated with the technical lead and reservoir operations modeler.](##_Ref215568526)

######## [System Response Models](##_Ref215568526)

[The hydraulic model must include breachable elements (two-dimensional \[2D\] Connections) that are unique for each location allowed to breach. In the case of levee breaches, early results from the hydraulic model will inform breach locations associated with overtopping events. Therefore, breach locations impact the hydraulic model setup and must be communicated clearly between the hydraulic modeler and the system response modelers. Section 8.9 describes additional, specific dam and levee deliverables from the hydraulic modeler at each step](##_Ref215568526)

[The breach parameters (e.g. erodibility, width, development time) are set in the hydraulic model should be coordinated between the system response modeler and hydraulic modeler. See section [8.5.9](##_Ref215569478) for breach parameter guidelines.](##_Ref215568526)

[The names of the 2D Connections must be consistent with those used to deliver the system response tables. These names will be guided by the name table and the model linking register and will require coordination between the system response modelers and the hydraulic modelers.](##_Ref215568526)

######## [Consequences Model](##_Ref215568526)

[Review of hydraulic mapped results in relation to the structure inventory occurs during the calibration and conformance phases. This review fosters a collaboration that aims to improve both structure placement and hydraulic model configuration.](##_Ref215568526)

#### [<span id="_Toc217044380" class="anchor"></span>Hydraulic Model Scenarios](##_Ref215568526)

[Descriptions of the hydraulic model scenarios that are part of the overall FFRD effort are provided below along with some general context for which phase the occur in.](##_Ref215568526)

###### [<span id="_Toc217044381" class="anchor"></span>Historic Calibration Events](##_Ref215568526)

[FFRD models are calibrated for six historic events that are selected during the scoping and data preparation phase. The primary focus of the hydraulic model development and calibration effort during the calibration phase of the project is achieving the calibration criteria for these events with a single geometry and parameter set.](##_Ref215568526)

[Final delivered versions of these scenarios are posted to the *\calibration\hydraulics\\model-unit\]\\* folder.](##_Ref215568526)

###### [<span id="_Ref215570616" class="anchor"><span id="_Toc217044382" class="anchor"></span></span>Stress Tests](##_Ref215568526)

[Stress tests will be included as 1 to 3 plans within the HEC-RAS model delivered as part of the calibration phase model deliveries. The primary purpose pf the stress test scenarios during the calibration phase is to identify and address model instabilities that may occur in certain situations, resulting in a more robust and stable model for use in stochastic simulations.](##_Ref215568526)

[The hydraulic modeler shall preform stress testing after initial calibration is completed. These stress tests should include simulation of very large events which may exceed the largest event of record. These tests should be performed assuming both a breach and non-breach condition of dams and levees, as breaches can often result in rapidly varied flow conditions, which present a stability challenge for hydraulic models. Stress test scenarios may be artificially created by scaling inflow hydrographs to produce very large flood events, such as those which overtop dams and levees. While overtopping tests are beneficial to evaluate model stability, breach stress testing should be performed when levees and/or dams are nearly fully loaded but not overtopping, which can create a critical scenario from a model stability perspective. An additional stress test where breach trigger elevations throughout the model are set to the structures’ toe elevation. This ensures breaches occur and can result in a highly submerged breach, which often highlights model stability issues. Scenarios with very low flows should also be stress tested.](##_Ref215568526)

[Final delivered versions of these scenarios are posted to the *\calibration\hydraulics\\model-unit\]\\* folder along with the historic calibration events.](##_Ref215568526)

###### [<span id="_Toc217044383" class="anchor"></span>Model Integration and Historic Event Replication](##_Ref215568526)

[During the conformance phase, the final calibration phase models are adjusted to function as a fully linked system (hydrologic model, operations model and all hydraulics models) and to accept synthetic storm events. As an early step in the conformance phase, the historic events used for calibration are recomputed in the desktop environment through the fully integrated model suite to ensure historic events are adequately replicated. This step all hydraulics and hydrology models in the study basin and is coordinated by the model integration lead for the project.](##_Ref215568526)

[After completing this step on desktop, final delivered versions of these scenarios, with results are posted to the *\conformance\event-validation\\* folder.](##_Ref215568526)

###### [<span id="_Toc217044384" class="anchor"></span>Cloud Compute Simulations](##_Ref215568526)

[During the conformance phase, after the models are integrated on desktop they are delivered for cloud compute simulations. A single set of hydraulic model files is delivered to the conformance/hydraulics directory and will be used for all stochastic simulations. There are review steps to ensure models are delivered in the appropriate format and to ensure that cloud-compute is producing appropriate results based on a few events before larger stochastic simulations with many events are computed. These review steps and processes are described in other sections.](##_Ref215568526)

[Final delivered versions of hydraulic models that are fully prepared for cloud-compute are posted to *\conformance\hydraulics\\model-unit\]\\*.](##_Ref215568526)

#### [<span id="_Toc217044385" class="anchor"></span>Geometry](##_Ref215568526)

[The following sections provide the standards and guidelines for development of HEC-RAS geometry for FFRD projects.](##_Ref215568526)

###### [<span id="_Toc217044386" class="anchor"></span>Hydraulic Mesh Construction](##_Ref215568526)

[The requirements, guidelines and general processes for construction of the hydraulic mesh are described in the sections below. Hydraulic models created for the FFRD program will include a single geometry with a single set of parameters.](##_Ref215568526)

######## [Model Extent](##_Ref215568526)

[The hydraulic mesh construction begins with the provided Hydraulic Modeling Unit Extent polygon that defines the study area for each model unit. The hydraulic model will be developed using fully 2D geometry. The mesh boundary conforms to the ridgeline separating adjacent hydraulic modeling units. A buffer should <u>not</u> be applied to the hydraulic modeling unit boundary to extend the boundary beyond the basin boundary, although it is good practice to extend the model further downstream of the study area within the existing floodplain to minimize the impact of approximate boundary condition estimates on results within the study area. Certain situations may require other adjustments to the model extent to follow the model linking plan, such as around dams that are near to the upstream or downstream limits of the model unit.](##_Ref215568526)

######## [Use of Elevation Derived Hydrography Dataset](##_Ref215568526)

[The EDH dataset is produced during the scoping and data preparation phase and provided the modeler. The EDH is considered the best source of stream alignment information and although some modifications may be needed, can be applied to certain steps in model development such as terrain modifications or mesh alignment along flow paths.](##_Ref215568526)

######## [Categories for Mesh Development](##_Ref215568526)

[The scope for level of detail to add to the hydraulic mesh is set during the scoping and data preparation phase. Layers that delineate the extent for each mesh development category are created during scoping and will be adhered to during model development (see Section [4.3.10](##_Ref215569527)). The general model treatment for each of the categories and the intended use of the outputs in each area are described in Table 8.1 below. More specific mesh development guidance is provided in the following sections.<span id="_Toc214892776" class="anchor"></span>](##_Ref215568526)

[Table 8.1. Model Treatment and Intended Use for each Mesh Development Category](##_Ref215568526)

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 44%" />
<col style="width: 38%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Mesh Development Category</a></th>
<th><a href="##_Ref215568526">Modeling Treatment</a></th>
<th><a href="##_Ref215568526">Intended Use of Output</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Background Mesh</a></td>
<td><a href="##_Ref215568526">No added mesh resolution. Maximum cell size that achieves computational stability and accurately routes excess precipitation over landscape. Terrain modifications when needed to hydraulicly connect flow paths.</a></td>
<td><a href="##_Ref215568526">Produce basin-wide H&amp;H data at a coarse resolution that may be leveraged for separate detailed modeling efforts. Provide approximate pluvial and fluvial flood information.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Urban Areas<br />
(polygons)</a></td>
<td><a href="##_Ref215568526">Increased 2D mesh resolution. Various features such as drainage ditches, road embankments, or pump stations may be accounted for directly.</a></td>
<td><a href="##_Ref215568526">Produce reliable pluvial and fluvial flood risk mapping results in populated areas.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Key Streams<br />
(lines)</a></td>
<td><a href="##_Ref215568526">Increased modeling detail to accurately route flood waters and produce accurate mapping results for the entire floodplain of key streams. Align cells with flow path of stream and account for bathymetry in terrain.</a></td>
<td><a href="##_Ref215568526">Accurate routing of flood water through larger streams. Accurate flood risk mapping from fluvial sources for the most critical streams in the basin.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Other Streams<br />
(lines)</a></td>
<td><a href="##_Ref215568526">At minimum, align cells with flow-path of stream. Terrain modifications when needed to hydraulicly connect flow paths.</a></td>
<td><a href="##_Ref215568526">Improve accuracy of routing of flood water through smaller streams. Moderately improve accuracy of fluvial flood risk mapping along those streams.</a></td>
</tr>
</tbody>
</table>

######## [Mesh Development Guidelines](##_Ref215568526)

[This SOP aims to balance the need for comprehensive basin-wide coverage in 2D hydraulic models with the need for computational efficiency in a stochastic modeling framework. The 2D mesh will incorporate varying levels of detail based on the mesh development scoping layers. These layers are designed to strategically allocate higher mesh resolution to areas where increased model precision is needed or where improved accuracy is critical. Table 8.3 provides guidelines for mesh cell sizes corresponding to each mesh development category.](##_Ref215568526)

[The recommended model development process includes starting with a relatively coarse mesh and iteratively refining as needed to achieve calibration targets and other criteria.<span id="_Toc214892777" class="anchor"></span>\
](##_Ref215568526)

[Table 8.2. Recommended Cell Sizes for Each Mesh Development Category](##_Ref215568526)

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Mesh Development Category</a></th>
<th style="text-align: center;"><a href="##_Ref215568526">Mesh Size (feet)</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Background Mesh</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">100–900</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Urban Areas</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">25–250</a></td>
</tr>
<tr>
<td><p><a href="##_Ref215568526">Key Streams</a></p>
<p><a href="##_Ref215568526">*<em>including adjacent floodplains</em></a></p></td>
<td style="text-align: center;"><a href="##_Ref215568526">25–250</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Other Streams</a></td>
<td style="text-align: center;"><a href="##_Ref215568526">100–900</a></td>
</tr>
</tbody>
</table>

[Cell sizes should be selected to ensure acceptable model accuracy (i.e., the model’s ability to reproduce observed data), numerical stability (e.g., satisfying the Courant condition, minimizing iteration counts, volume conservation errors, and water surface elevation discrepancies), and computational efficiency (i.e., maintaining a reasonable total run time). Appropriate cell sizes should be informed by the characteristics of the area being modeled and may require iterative testing to optimize.](##_Ref215568526)

[Modelers should approach mesh development with the goal of minimizing unnecessary detail while still meeting required standards for accuracy, stability, and efficiency. Because each modeling unit has unique features and topography that influence performance, engineering judgment is essential in selecting the background mesh resolution and the resolution within other scoped mesh development categories along streams, floodplains, and urban areas.](##_Ref215568526)

########## [Background Mesh](##_Ref215568526)

[The 2D computational mesh consists of a coarse background mesh in all areas not specifically scoped for higher resolution modeling. The primary modeling goal in these areas is to provide boundary conditions that can be leveraged for future more detailed studies and to provide approximate pluvial and fluvial flood information.](##_Ref215568526)

[Hydraulic structures that are present in areas not otherwise scoped for additional modeling detail will also be present in the background mesh. Breaklines to represent major watershed features such as significant roadway embankments or ridgelines may be incorporated to improve model accuracy.](##_Ref215568526)

[The coarse background mesh computation point spacing will generally vary from about 400-foot to 600-foot polygonal mesh. In cases of remote areas with relatively flat slopes it is reasonable to have a larger point spacing, up to 900-foot polygonal mesh. But this is not common and should be used sparingly and results should be verified for stability and accuracy.](##_Ref215568526)

########## [Urban Areas](##_Ref215568526)

[The urban area polygons are obtained during the scoping phase of the project and provided to the modeler to define areas for additional mesh detail. These areas will include smaller cell sizes as well as break lines representing roadways/hydraulic structures. Various other features such as major channels, drainage ditches, culverts, bridges, hydraulic structures, or pump stations may be included if needed to produce reliable flood mapping results. Terrain modifications will commonly be associated with urban area mesh refinements.](##_Ref215568526)

[A mesh resolution of 150 feet can be used as a starting point for mesh resolution in populated areas. Significant professional engineering judgement should be used in model development for urban areas. Care is taken to account for these features while balancing model run times with model detail.](##_Ref215568526)

########## [Key Streams](##_Ref215568526)

[The key streams dataset is identified during the scoping phase of the project and defines the streams to receive a high level of additional modeling detail. The key streams are provided to the modeler prior to the start of model development.](##_Ref215568526)

[Key streams are modeled with increased cell resolution, including cells that are aligned to the stream channel. Additionally, the floodplain areas adjacent to these key streams—including those exposed to flooding during extreme events—are modeled with enhanced detail, following the same guidelines as those applied to urban areas.](##_Ref215568526)

[The terrain also will be adjusted along key streams to account for the bathymetric elevations not a part of the bare-earth terrain data. Terrain modifications to represent bathymetry may be sourced from either surveyed data or estimated using the methods described in Section [8.3.2.8](##_Ref215569668).](##_Ref215568526)

########## [Other Streams](##_Ref215568526)

[The other streams dataset is identified during the scoping phase of the project and defines the streams to receive some additional modeling detail. The other streams are provided to the modeler prior to the start of model development.](##_Ref215568526)

[Other streams are modeled to ensure the mesh follows the alignment of the channel. Additional cell resolution beyond the background mesh is not required. Incorporation of stream bathymetry is not required. Terrain modifications to ensure the streams are hydraulically connected across embankments and bridges may be necessary.](##_Ref215568526)

######## [Hydraulic Structures](##_Ref215568526)

[Various hydraulic structures that affect flow patterns and flood extents may be present in the basin to be modeled. The intent is not to model all hydraulic structures in the basin, but to identify the features that may have a significant influence on the ability of the modeling system to accurately portray the probability of flooding in the basin. The requirements and guidelines for inclusion of specific types of structures are described in the subsections below.](##_Ref215568526)

########## [<span id="_Ref215570347" class="anchor"></span>Dams](##_Ref215568526)

[The modeling treatment of each dam for the entire basin is determined during the scoping and data preparation phase of the project and provided to the modeler prior to the start of model development. The *<u>Dam Scoping Table</u>* lists the dam configuration category for each dam to be applied in the hydraulic model geometry. Job Aid 1, *Scoping Processes*, describes the guidelines applied to develop the dam scoping table. Job Aid 8, *Dam Representation*, provides additional details regarding incorporation of the dams into the hydraulic models.](##_Ref215568526)

[The following sections describe the hydraulic model treatment of each dam configuration category to be applied for each category of dam.](##_Ref215568526)

############ [Dam Type A—Operation Modeled outside of Hydraulic Model](##_Ref215568526)

[The hydraulic model for Type A dams will include a 2D connection to represent the dam, but no outlets will be included, and a very high crest elevation will be entered to ensure no water will be allowed to pass.](##_Ref215568526)

[Outflow boundary conditions will be applied to the hydraulic model and be sourced from either observed flows (for historic calibration events during the calibration phase of the project) or from simulated outputs from other models according to the Model Linking Register developed during the scoping and data preparation phase.](##_Ref215568526)

[A terrain modification to remove the dam embankment may be necessary to ensure both the pool and tailwater of the dam are able to pass the routed flows without being inhibited.](##_Ref215568526)

[Bathymetry of the pool upstream of the dam will be included as terrain modifications using the methods described in Section [8.3.2.8](##_Ref215569736). The storage capacity of the modifications will be cross checked for consistency with the other models.](##_Ref215568526)

[Additionally, terrain modifications may be needed to ensure numerical stability for events that breach the 2D connection.](##_Ref215568526)

############ [Dam Type B—Operation Modeled by Hydraulic Model](##_Ref215568526)

[The hydraulic model for Type B dams will include a 2D connection to represent the dam, with outlets, spillways, and overtopping of the crest to allow water to pass though the dam. Operations of the structures will be limited to basic operations (such as rating curves, elevation-controlled gates, or user defined outlet curves). No complex rulesets to operate structures will be used.](##_Ref215568526)

[A terrain modification to remove the dam embankment may be necessary to ensure both the pool and tailwater of the dam are able to pass the routed flows without being inhibited.](##_Ref215568526)

[Bathymetry of the pool upstream of the dam will be included as terrain modifications using the methods described in Section [8.3.2.8](##_Ref215569742). The storage capacity of the modifications will be cross checked for consistency with the other models when applicable.](##_Ref215568526)

[Additionally, terrain modifications may be needed to ensure numerical stability for events that breach the 2D connection.](##_Ref215568526)

############ [Dam Type C—Simplified Outflows Modeled by Hydraulic Model](##_Ref215568526)

[Type C dams will be represented in the hydraulic model as a 2D connection. Outlet features and dam crest will be approximated based on the best available information.](##_Ref215568526)

[A terrain modification to remove the dam embankment may be necessary to ensure both the pool and tailwater of the dam are able to pass the routed flows without being inhibited.](##_Ref215568526)

[If Type C dams are also modeled explicitly in the hydrologic model, operations will be cross checked for consistency with the hydrologic model.](##_Ref215568526)

[Bathymetry of the pool upstream of the dam will be included as terrain modifications using the methods described in Section [8.3.2.8](##_Ref215570117). The storage capacity of the modifications will be cross checked for consistency with the other models when applicable.](##_Ref215568526)

[Additionally, terrain modifications may be needed to ensure numerical stability for events that breach the 2D connection.](##_Ref215568526)

############ [Dam Type D—Basic Representation in Hydraulic Model](##_Ref215568526)

[Type D dams will be represented in hydraulic model with a breakline to represent the dam such that cell faces will hold the pool and release flows according to the underlying terrain. A relatively narrow notch terrain modification may be included to allow water to pass through the dam before spillway flow occurs.](##_Ref215568526)

[Bathymetry of the pool upstream of the dam will not be included beyond data already available within the terrain surface.](##_Ref215568526)

############ [Dam Type E—Not Modeled](##_Ref215568526)

[Type E dams will not be modeled with any detail in the hydraulic model.](##_Ref215568526)

########## [Levees](##_Ref215568526)

[FFRD hydraulic models will include a representation of all levees in the NLD. Levee alignments and profiles will be included in the models exactly as represented in the system route layer in the NLD. The NLD data for the entire basin will go through a data refinement effort for the entire study basin as part of the scoping and data preparation phase of the project, which will ensure the alignment and profile of the data is complete, accurate and aligned with the project DEM. All NLD levees will be modeled as a hydraulic structure (2D connection) and will be modeled assuming all closures are in place. The levee alignment and profile data will be provided to the modeler in a XYZM format to allow for easy import into HEC-RAS as described in Job Aid 9, *Levee Representation*. All NLD levees will be modeled as a hydraulic structure (2D connection) and will assume all closures are in place.](##_Ref215568526)

[During the modeling development process, NLD levee elevation data should be compared with terrain elevation, aerial photography, street view images or other sources to evaluate and confirm accuracy of the data. Obvious errant data, closure structures, and lack of floodwall elevation data may require professional engineering judgement to establish a levee profile for use in the model. Any adjustments to either the NLD levee alignment or NLD crest profiles must be documented in the applicable report (Calibration Phase Report or Conformance Phase Report), which will include a table for commentary on each levee system in the model.](##_Ref215568526)

[Increased mesh resolution and detail behind the levee will be included if required for model stability and accuracy around breach locations or if the leveed area is included in areas otherwise scoped for increased resolution (urban areas or floodplains adjacent to key streams).](##_Ref215568526)

############ [Levee System Segmentation](##_Ref215568526)

[Levees will be spilt into multiple 2D connections when necessary to allow for multiple breach locations to be assessed in a single system when called for by the levee lead in the scoped approximate levee breach locations. Coordination with the levee data lead is required in terms of specific breach location confirmation and siting as described in Job Aid 11, *Levee Breach Workflows*.](##_Ref215568526)

############ [Drainage Systems Across Levees](##_Ref215568526)

[Culverts and pumps that have a significant effect on the inundation within the leveed area will be included in the model geometry. Locations, sizes, and capacities of the culverts or pumps across the levee are approximated using NLD data or other readily available data. The behavior of culverts through levees are typically modeled as a flap gates or other appropriate assumption best representing its function.](##_Ref215568526)

########## [Urban Drainage Systems](##_Ref215568526)

[Urban drainage modeling is limited to open channel drainage within urban areas. Sub-surface urban drainage is not included in the 2D mesh.](##_Ref215568526)

[It is recognized that subsurface urban drainage systems play a major role in pluvial urban flooding. Future techniques may allow for a more direct modeling method to account for these systems.](##_Ref215568526)

########## [Transportation Features](##_Ref215568526)

[Key hydraulic structures associated with transportation features significantly impacting inundation in populated areas or features that are needed to accurately reproduce observed data should be included in the 2D mesh. Engineering judgement is needed to identify the key structures to include. Transportation features in the background mesh category are of lower priority. Transportation layers from the U.S. Census TIGER dataset will be provided to the modeler to aid in identifying the key features.](##_Ref215568526)

[When included, hydraulic structures associated with transportation features (i.e., bridges, roadway embankments, etc.) are modeled as breaklines and/or terrain modification (not internal 2D connections) and best practices for modeling should be applied.](##_Ref215568526)

########## [Other Hydraulic Features](##_Ref215568526)

[Modeling may contain other unique hydraulic features such as other embankments, diversions, canals, saltwater barriers, or other structures that may be included within the mesh to capture key aspects of the flood characteristics of the area when deemed critical by the hydraulic modeler using professional judgement.](##_Ref215568526)

###### [<span id="_Toc217044387" class="anchor"></span>Terrain Creation](##_Ref215568526)

[The following subsections describe the standards, guidance and best practices for creation and storage of the RAS Mapper terrain for hydraulic modeling use.](##_Ref215568526)

######## [Digital Elevation Model](##_Ref215568526)

[The full resolution base DEM provided for the modeling project (see Section 3.4) will be used as the basis for the RAS Mapper terrain.](##_Ref215568526)

######## [Terrain Versions](##_Ref215568526)

[As described in Section 3.5, two distinct versions of the terrain will be produced.](##_Ref215568526)

[The *production terrain* is the key terrain used for the development of the hydraulic model, will retain the full resolution of the be DEM and follow the guidance in the sections below.](##_Ref215568526)

[The *mapping terrain* is an exported, lower resolution terrain that will be used for development of hazard gridded outputs. This terrain is created at the end of the calibration phase as a deliverable.](##_Ref215568526)

######## [Terrain Storage Location](##_Ref215568526)

[To allow for collaboration with the full team all official HEC-RAS terrains for each modeling unit will be stored in the *terrain-modeling* directory. It is encouraged to set up the HEC-RAS model on your desktop with a reference to the DEM that is above the HEC-RAS model directory during model development. The final HEC-RAS terrain is required to be posted to the *terrain-modeling* directory as part of each delivery step during the calibration phase of the FFRD project (Section 8.9 describes specific delivery steps).](##_Ref215568526)

######## [Merged Terrain Delivery for Mapping](##_Ref215568526)

[The HEC-RAS modeler is required to deliver an exported reduced-resolution RAS Mapper terrain posted to the *terrain-mapping* directory. See Section 4 for standard cell sizes for mapping products. This reduced resolution terrain is necessary for efficient FFRD production of mapped output products that retain acceptable quality. This RAS Mapper terrain must be exported with rasterized modifications due to fact that cloud-compute tools do not support terrains that include terrain modifications (as of June 2025).](##_Ref215568526)

######## [Use of Tiled Terrains](##_Ref215568526)

[Tiled terrains may be used for the RAS Mapper terrain, but they are not required.](##_Ref215568526)

######## [Modifications Outside of RAS Mapper](##_Ref215568526)

[Modifications to the hydraulic model terrain may be made using tools outside of the RAS Mapper system provided they maintain the fidelity of the original source data and the edits are well documented.](##_Ref215568526)

######## [Buildings](##_Ref215568526)

[Terrains used for FFRD will represent bare earth. Modification of the terrain to represent building/structures within the terrain is not performed. The hydraulic impacts of these features are included with Manning’s “n” roughness values associated with urban areas.](##_Ref215568526)

######## [<span id="_Ref215569668" class="anchor"><span id="_Ref215569736" class="anchor"><span id="_Ref215569742" class="anchor"><span id="_Ref215570117" class="anchor"></span></span></span></span>Bathymetry](##_Ref215568526)

[The provided DEM is expected to represent top-of-water surface elevations and therefore will not include a representation of the below-water elevations that can have a significant effect on the hydraulic model results. Existing bathymetry information for rivers, lakes, and reservoirs should be incorporated into the RAS Mapper terrain when it is defined in the scope of the modeling effort or existing measured data is readily available. Various techniques for incorporation of bathymetry exist and are categorized below. For all techniques, care is taken so terrain modification only takes place below the water surface and the existing above-water high-quality terrain is not modified by an errant slope projection or un-realistic stream bottom width.](##_Ref215568526)

########## [Gridded Bathymetry from Survey Data](##_Ref215568526)

[In some instances, existing digital bathymetry based on field surveys may be available and will be obtained during the scoping and data preparation phase of the project. Other local sources of digital bathymetry identified during model development may also be considered for inclusion in the terrain. This data is incorporated into the terrain file used in RAS Mapper if it is determined to be a better representation of the terrain below the water surface and is consistent with the scoping document for the modeling project.](##_Ref215568526)

########## [Surveyed Cross-section Data](##_Ref215568526)

[Available surveyed cross-section bathymetry data should be incorporated if deemed to be of high quality. Although other workflows for incorporation of this data exist, it is most commonly represented in existing 1D hydraulic models and accomplished by generating a terrain surface using the cross-section data between bank points and incorporated into the terrain as described in the [HEC-RAS Mapper User’s Manual](https://www.hec.usace.army.mil/confluence/rasdocs/rmum/latest/terrain-modification##id-.TerrainModificationv6.6-CrossSectionInterpolationSurface).](##_Ref215568526)

########## [Estimate Channel Bathymetry](##_Ref215568526)

[When surveyed bathymetry is not available for incorporation into the terrain, channel bathymetry may be estimated. This should be done if either the stream was scoped to include estimated bathymetry (i.e., it is a *key stream*) or channel bathymetry is needed to achieve accurate flood routing to meet calibration targets.](##_Ref215568526)

[Bathymetric parameters can be estimated using bank full channel geometry regression equations as summarized in FEMA SO2 Innovations, *Bathymetry Sensitivity Testing*, report (April 2024).](##_Ref215568526)

[Parameters alternatively may be estimated based on aerial photography and the existing terrain are used to estimate the side slope and bottom width of the channel. Existing FIS profiles and [existing stream gage rating curves](https://waterwatch.usgs.gov/index.php?id=mkrc) may be used to estimate the channel invert. Professional engineering judgement may also be applied to estimate channel bathymetry along a reach. When observed data is available to support it, channel bathymetry (width/depth/slope) parameters should be iterated to achieve model calibration. The modeler may justify the selection of dimensions of estimated channels in the report by comparing known rating curves model results.](##_Ref215568526)

[The estimated bathymetry parameters may be incorporated into the terrain using [RAS Mapper terrain modification tools](https://www.hec.usace.army.mil/confluence/rasdocs/rmum/latest/terrain-modification##id-.TerrainModificationv6.6-TerrainModificationTools). RAS Mapper terrain modification tools are limited to a single trapezoidal section per reach. Multiple reaches may be required to achieve the best estimate channel bathymetry and avoid unrealistic terrain modifications. Multiple terrain modifications can be stacked on top of one another to create more complex cross section shapes.](##_Ref215568526)

########## [Estimate Reservoir Bathymetry](##_Ref215568526)

[Terrain modifications are required behind most significant dams in the basin, as defined on a per-dam basis in the Dam Model Scoping Table provided to the modeler. Although incorporating surveyed bathymetry behind the dam is the preferred modeling technique, in many instances, surveyed bathymetry data is not available and an estimate of the below water elevations within the reservoir is needed.](##_Ref215568526)

[Terrain modifications can be stacked within RAS Mapper to develop a broad floodplain and incorporate a river channel as described in more detail in Job Aid 08, *Dam Representation*. In some instances, terrain modification is required to decrease the footprint of the dam for model stability or to provide the capability within the model to evaluate a dam breach.](##_Ref215568526)

[Volume comparisons with available elevation-storage relationships or NID data are made to ensure the terrain modifications are representative of the volume in the reservoir. The resulting elevation-storage relationship within the terrain must be coordinated with the hydrologic model and reservoir simulation model to ensure each model is using identical relationships.](##_Ref215568526)

######## [Stream Path Conditioning](##_Ref215568526)

[Despite efforts to hydro-enforce DEMs provided at the start of the study, unrealistic damming effects at various locations within the watershed may require terrain modifications in HEC-RAS. This can be accomplished with the RAS Mapper ground line editor tools to lower the terrain across the feature based on the estimated size of the culvert or bridge opening (Figure 8.5). The result is a channel through the roadway embankment. This terrain modification method uses the line vertices to assign an elevation to the terrain modification. Typically, a straight line beginning at the channel invert upstream of hydraulic structure and ending at the channel invert downstream of the hydraulic structure is used.\
](##_Ref215568526)

[<span id="_Toc214891699" class="anchor"></span>Figure 8.1. Typical Terrain Adjustment at a Major Road Crossing Preventing Unrealistic Damming Effects](##_Ref215568526)

[<img src="media/image9.png" style="width:4in;height:3.28718in" />](##_Ref215568526)

######## [Terrain Artifacts](##_Ref215568526)

[In instances where a LiDAR tile is unavailable or corrupt, a coarse DEM tile is required to supplement the high-resolution data. This may result in holes or blockages in the channel which are modified using professional engineering judgement (Figure 8.6). Additional artifacts may exist in the terrain that are reviewed and corrected using terrain modification tools to meet the objectives of the FFRD model.\
](##_Ref215568526)

[<span id="_Toc214891700" class="anchor"></span>Figure 8.2. Terrain Artifacts are Filled in to Match Higher Resolution Data](##_Ref215568526)

[![](media/image12.jpeg)](##_Ref215568526)

###### [<span id="_Toc217044388" class="anchor"></span>Hydraulic Roughness](##_Ref215568526)

[Assignment of hydraulic roughness parameters to the hydraulic model is a key aspect of model calibration. The following subsections describe requirements and guidelines for roughness.](##_Ref215568526)

######## [Roughness Storage Location](##_Ref215568526)

[Final hydraulic roughness base layer and any calibration regions will be stored within the hydraulic model unit directory. The path for roughness layer storage is *ffrd\_\[basin-name\]/calibration/\[model-unit\]/*.](##_Ref215568526)

######## [Roughness Data Sources](##_Ref215568526)

[The [NLCD](http://www.mrlc.gov/) data will be obtained during the scoping and data preparation phase and provided to the hydraulic modeler prior to the start of model development. This dataset meets the minimum standard for the base roughness layer for use in FFRD models, although modifications are required along streams as described in the following sections.](##_Ref215568526)

[Separate higher-resolution and higher-quality sources for land cover may be applied to specific projects if collection of these data sources was included in the scoping and data preparation phase of the project.](##_Ref215568526)

######## [Roughness Values](##_Ref215568526)

[Best practices within the hydraulic modeling community of practice must be used in assignment of roughness values in the model and engineering judgement will be required. [Typical ranges for Manning’s “n” values by NLCD land cover categories are suggested in the HEC-RAS user’s manual](https://www.hec.usace.army.mil/confluence/rasdocs/r2dum/6.6/developing-a-terrain-model-and-geospatial-layers/creating-land-cover-mannings-n-values-and-impervious-layers) and may be used as a guide during model development and calibration. For higher gradient natural channels, [*Determination of Roughness Coefficients For Streams in Colorado* by Robert Jarrett](https://pubs.usgs.gov/wri/1985/4004/report.pdf) should be considered for the assignment of roughness values in the model calibration process.](##_Ref215568526)

######## [Roughness along Streams](##_Ref215568526)

[Accurate representation of hydraulic roughness along the streams in the basin is a key aspect of model development and calibration. Due to typical land cover dataset resolution, parts of channels can be categorized as forest or other land covers and be given the higher Manning’s “n” value associated with that (incorrect) land cover unless appropriate edits are made.](##_Ref215568526)

[The hydraulic modeler will incorporate the stream centerline layer into the land cover data layer along with classification polygons/calibration regions to represent all streams with drainage areas larger than 0.25 square miles within the modeling unit. The modeler will utilize the EDH stream centerlines that are provided in the scoping and data preparation for this step. Stream widths for each reach will need to be estimated for this step. The provided EDH centerlines include attributes that support application of bankfull stream regression equations that may aid in the estimation stream widths (Included in Volume V - *Bathymetry Sensitivity Testing*, April 2024). Other methods for estimating stream widths or developing continuous bank lines within the hydraulic modeling community of practice are also available and may be considered.](##_Ref215568526)

######## [Other Adjustments to Roughness](##_Ref215568526)

[Other adjustments to the hydraulic roughness such as Land Classification polygons or Calibration Regions areas other than along stream centerlines may be applied when appropriate according to best practices withing the hydraulic modeling community of practice.](##_Ref215568526)

######## [Spatially Varied Roughness on Cell Faces](##_Ref215568526)

[Manning’s “n” values will be spatially varied across each face in the 2D mesh. The default method of selecting a Manning’s “n” value in HEC-RAS is to use the “n” value from the land cover data at the face centroid. From the 2D editor (Figure 8.8), spatially varied Manning’s “n” on faces can be activated to process depth varied “n” values across each face based on the land cover data.<span id="_Toc214891701" class="anchor"></span>\
](##_Ref215568526)

[Figure 8.3. Spatially Varied Manning’s “n” Values on Faces in the Two-Dimensional Flow Area Editor](##_Ref215568526)

[<img src="media/image12.png" style="width:6.5in;height:4.22986in" />](##_Ref215568526)

###### [<span id="_Toc217044389" class="anchor"></span>Saved Output Locations](##_Ref215568526)

[Reference lines and reference points are key model elements which can be used to extract information from the hydraulic HEC-RAS model. Specifically, these elements can extract variables including water surface elevation/stage, flow, and velocity. These elements are defined within the model geometry and must be incorporated prior to a simulation for the model to write output from these defined locations. When reference lines and points are defined, they write timeseries model output to both the project DSS file and plan HDF file at the specified hydrograph output interval. Time series and rating curves of observed data can be assigned to reference lines and reference points in the Unsteady Flow Data editor, this allows for graphical plotting of both modeled and observed data in the Stage and Flow Hydrograph viewer.](##_Ref215568526)

[Reference locations are discussed in the HEC-RAS Mapper User Manual. Refer to official software documentation for [additional discussion and guidance on use of reference features](https://www.hec.usace.army.mil/confluence/rasdocs/rmum/latest/geometry-data/reference-locations).](##_Ref215568526)

[The following sections describe the requirements and guidelines for the use of reference locations in FFRD hydraulic models. The saved output locations listed below are a required minimum, but it is acknowledged that other locations not listed may provide useful output and are allowed.](##_Ref215568526)

######## [Naming and Documentation of Output Locations](##_Ref215568526)

[Reference lines and reference points will be named according to the naming convention standards described in Job Aid 06, *Standard Naming Conventions*. Many specific output location names will be provided to the modeler in the Naming Table that is developed during the scoping and data preparation phase.](##_Ref215568526)

[Reference lines and points will be described in the hydraulic modeling documentation report such that what each reference feature is describing is well communicated. The name of a reference feature alone may not be sufficient to communicate what that feature is measuring and its intended purpose. Tables and descriptions of reference features in the report are valuable for model-to-model linking and integration of multiple models.](##_Ref215568526)

######## [Reference Lines](##_Ref215568526)

[Reference lines are linear features used to extract modeled discharge and water surface elevation data. They are essential for model calibration, inter-model comparisons, and output summary data extraction.](##_Ref215568526)

########## [Reference Line Creation General Guidelines](##_Ref215568526)

[*<u>Full Floodplain Coverage</u>*: Reference lines should be drawn such that they span the full width of the floodplain for large events. This ensures that all flow passing a gage location will be recorded by a reference line. If reference lines are drawn shorter, from only left bank to right over the channel for example, it is possible that flow during large events may flank around the reference line and not be recorded by the line. This can be complicated as USGS may not be measuring flow across the entire floodplain width during observed extreme floods, but best engineering judgement should be used.](##_Ref215568526)

[*<u>Orientation</u>*: Where applicable all reference lines should be drawn perpendicular to the flow direction, from left to right from the perspective of looking downstream. This will ensure flow is appropriately calculated as a positive value when flowing downstream or a negative value when flowing upstream.](##_Ref215568526)

[*<u>Alignment with Mesh</u>*: It is recommended that reference lines be enforced in the 2D computational mesh such that 2D cell faces are aligned to the reference line and perpendicular to the flow. This can be accomplished by co-locating and overlapping a 2D breakline, which is used to enforce 2D cell faces. Some manual manipulation of 2D cell points may be required to ensure cell faces are properly snapped to the breakline/reference line feature.](##_Ref215568526)

[*<u>Near Structures</u>*: In some instances, there may be a need to measure discharge through an embankment, such as in the case of a dam. In this case, placing a reference line over the embankment will not capture discharge being transferred through the dam as part of a storage area/2D connection’s culvert or gate. Therefore, the reference line should be placed downstream of the embankment, so all flows transferred through the structure pass over the line. The storage area/2D connection itself will also provide flow measurements through the embankment as a separate timeseries, however a reference line is also recommended to provide consistency in how data is extracted from the model.](##_Ref215568526)

########## [Reference Lines at Stream Gages](##_Ref215568526)

[Reference lines are required at all observed gage locations. For calibration event modeling, these gage reference lines will include observed stage and flow data linked to the observed data DSS file in the Unsteady Flow Data editor. They will be drawn perpendicular to the flow in the stream channel (oriented from left bank to right bank) and is wide enough to capture the entire cross section including overbank flow.](##_Ref215568526)

[For hydraulic model development in the calibration phase of the project, observed data should be linked to specific reference lines for the calibration events in the Unsteady Flow Data editor. The flow, stage, and rating curve information provided by reference lines at gages is the primary data to be compared with observed data for calibration and validation.](##_Ref215568526)

########## [References Lines at Model Downstream Boundaries](##_Ref215568526)

[Reference lines are required at the downstream boundary of each hydraulic model unit. These reference lines may be coincident with the downstream boundary condition line or may be interior to the model if the model is extended downstream to avoid error associated with an assumed boundary condition. They will be drawn perpendicular to the flow in the stream channel (oriented from left bank to right bank) and is wide enough to capture the entire cross section including overbank flow.](##_Ref215568526)

########## [Reference Lines at Hydrologic Model Subbasin Locations](##_Ref215568526)

[References lines are required at the downstream outlet of all hydrologic model subbasins allow for inter-model comparisons. They will be drawn perpendicular to the flow in the stream channel (oriented from left bank to right bank) and is wide enough to capture the entire cross section including overbank flow.](##_Ref215568526)

[Identifying differences in runoff routing between the two models can provide insight into model performance and aid in calibration when there is difficulty achieving acceptable hydraulic model calibration metrics. Rating curves can also be extracted at these locations, which may be useful in the future to inform other modeling efforts.](##_Ref215568526)

########## [Reference Lines at Hydrologic Model Junction Locations](##_Ref215568526)

[Reference lines are required at all hydrologic model junction locations allow for inter-model comparisons. They will be drawn perpendicular to the flow in the stream channel (oriented from left bank to right bank) and is wide enough to capture the entire cross section including overbank flow.](##_Ref215568526)

[Similar to the rational for including reference lines at subbasin locations, identifying differences in runoff routing between the two models can provide insight into model performance and aid in calibration when there is difficulty achieving acceptable hydraulic model calibration metrics. Rating curves can also be extracted at these locations, which may be useful in the future to inform other modeling efforts.](##_Ref215568526)

######## [Reference Points](##_Ref215568526)

[Reference points are like reference lines except they only provide information on water surface elevation and velocity at a single point, rather than calculating discharge flux across a line. They are essential for model calibration, inter-model comparisons, and output summary data extraction from stochastic simulations.](##_Ref215568526)

########## [Reference Points at Gage Locations](##_Ref215568526)

[Reference points will be included at each observed data gage location in the basin and be located near the centerline. These reference points will overlay the reference line at the same gage location.\
](##_Ref215568526)

########## [Reference Points near Levees](##_Ref215568526)

[Reference points will be included along storage area/2D connections at levees located at the upstream end of the levee system, mid-point of the levee system, and downstream end of the levee system. Additionally, two reference points will be included at each levee breach location (riverside/headwater and landside/tailwater). Figure 8.4 is an example of a typical levee with five associated required reference points.](##_Ref215568526)

[<span id="_Toc214891702" class="anchor"></span>Figure 8.4. Typical Reference Point Locations along a Levee with a Single Breach Location](##_Ref215568526)

[<img src="media/image13.png" style="width:5.59305in;height:2.40595in" alt="Diagram AI-generated content may be incorrect." />](##_Ref215568526)

########## [Reference Points near Reservoirs](##_Ref215568526)

[Reference points are recommended within reservoirs to extract water surface information regarding the lake. Specifically, these reference points should be located in the deepest portion of the reservoir so that water surface information can be extracted even if the reservoir were to go completely dry. These points are useful in extracting information from the model, particularly in a cloud environment where extracting information from thousands of simulations is required.](##_Ref215568526)

#### [<span id="_Toc217044390" class="anchor"></span>Unsteady Flow Data](##_Ref215568526)

[Guidelines for hydraulic model configuration all unsteady flow data for FFRD hydraulic models are described in the sections below.](##_Ref215568526)

[In general, the hydraulic model should use relative references to data linked data from their official storage locations on Model Library according to the Job Aid 07, *Model Library Use*, and characterized in Figure 8.5.\
](##_Ref215568526)

[<span id="_Toc214891703" class="anchor"></span>Figure 8.5. Characterization of the Official Directory Structure to be Used for Relative References (Example Shown for Calibration Phase Directory)](##_Ref215568526)

[<img src="media/image14.png" style="width:2.24565in;height:4.5213in" alt="Graphical user interface AI-generated content may be incorrect." />](##_Ref215568526)

###### [<span id="_Toc217044391" class="anchor"></span>Boundary conditions](##_Ref215568526)

[The following subsections describe boundary condition standards for FFRD hydraulic models.](##_Ref215568526)

######## [Baseflows](##_Ref215568526)

[Baseflow hydrographs from each subbasin in the hydrologic model will be used in the hydraulic model as a flow hydrograph internal boundary condition. The baseflow boundary condition line is added to the HEC-RAS model within the stream channel near the HEC-HMS subbasin outlet from which it was developed.](##_Ref215568526)

[During the calibration phase, the hydraulic modeler coordinates with hydrologic modeler to obtain the appropriate baseflow hydrograph output corresponding to the appropriate historic event computed from HEC-HMS. The official storage location of the HEC-HMS DSS output at this stage is *calibration/hydrology/historic-events/*.](##_Ref215568526)

[The boundary condition lines that represent baseflow locations will be named according to guidance in Job Aid 06, *Standard Naming Conventions*.](##_Ref215568526)

[Baseflow boundary condition lines must be located near the downstream end of the subbasin. Baseflow data provided from HEC-HMS output is point flow data that is hydrologically routed to the subbasin outlet. Care must be taken to ensure baseflow is not introduced in the middle/upstream portion of the basin to avoid double routing of the flow in the modeling system.](##_Ref215568526)

######## [Upstream Inflows](##_Ref215568526)

[In non-headwater basins, upstream boundary conditions are required to represent the flow entering the basin. This flow is included in the hydraulic model as a flow hydrograph external boundary condition. The source of inflow (observed data or output from a separate model) will be defined during the scoping and data preparation phase (e.g., upstream hydraulic model output, observed data, other modeled output) and provided to the modeler prior to model development. The upstream inflow boundary condition lines will be named according to guidance in Job Aid 06, *Standard Naming Conventions*.](##_Ref215568526)

######## [Downstream Boundary Condition](##_Ref215568526)

[Downstream boundary conditions are set to appropriately model conditions at the downstream limit of the study area. Boundary conditions are (where possible) located at locations where flow is 1D. In situations where the selection the downstream water surface is uncertain, it is best practice to extend the model further downstream to ensure the uncertainty does not impact results in the study area.](##_Ref215568526)

[For modeling of historic events during the calibration phase, observed stage data may be used as the downstream water surface if available, although hydraulics model units will typically be scoped to allow for use of observed data for calibration (i.e., stream gages will be within the modeled area rather than at the downstream boundary). Any observed data utilized will be based on the data provided for the project during the scoping and data preparation phase.](##_Ref215568526)

[When no observed data is available for boundary condition use, normal depth or estimated rating curve is generally used for models with riverine characteristics at the downstream boundary. When tidal conditions exist at the downstream boundary of the model, the modeler substitutes an appropriate tidal pattern based on available information. When the downstream conditions are lake-like, an appropriate known water surface may be used.](##_Ref215568526)

[For conformance and production phase modeling, observed data boundary conditions will be replaced with an appropriate estimate or synthetic time series.](##_Ref215568526)

[When tidal boundary condonations are present, it is acceptable to use the Mean High Water (MHW) as a fixed water level. More sophisticated sampling of appropriate tidal boundary conditions for synthetic events is being considered for future versions of this SOP.](##_Ref215568526)

[The downstream boundary condition lines will be named according to guidance in Job Aid 06, *Standard Naming Conventions*.](##_Ref215568526)

######## [Dam Operations](##_Ref215568526)

[The method for representation of each dam in the basin within the FFRD system of models is clearly defined during the scoping and data preparation phase of the project. The various methods for Dam geometry representation and outflows within the hydraulic model are described in section [8.3.1.5.1](##_Ref215570347).](##_Ref215568526)

###### [<span id="_Toc217044392" class="anchor"></span>Initial Conditions](##_Ref215568526)

[The following subsections provide guidance on defining initial conditions for FFRD hydraulic models.](##_Ref215568526)

######## [Initial Conditions Points](##_Ref215568526)

[The initial conditions definition in FFRD hydraulic models will generally be limited to initial conditions points upstream of dams. Initial conditions points provide a fixed water surface at the start of the event simulation. For the calibration phase models, initial conditions points will be set to an appropriate value based on the historic event being modeled. For conformance and production phase models which simulate synthetic events, the initial conditions elevations will be sampled for each event.](##_Ref215568526)

[Initial elevation points that represent dam pools must use the ‘Fixed During Warm-up’ option to ensure that the initial pool does not vary from the intended value when combined with a warm-up option (set in the plan file).](##_Ref215568526)

######## [Warm-up](##_Ref215568526)

[A warm-up period (configured in the plan file) should be used in FFRD hydraulic models. The warm-up allows major rivers—particularly those downstream of inflow boundary conditions—to fill and align with the initial hydrograph flow values before the simulation starts. See section [8.5.6](##_Ref215570513) for guidance on warmup settings.](##_Ref215568526)

######## [Restart Files](##_Ref215568526)

[For models created during the calibration phase, restart files that provide comprehensive stage and flows at the initial time step may be used to streamline the calibration process. However, restart files will not be applied to the conformance or production phase version of the models at this time due to the complexities associated with sampling of initial water surfaces for stochastic runs.](##_Ref215568526)

######## [Known Weakness](##_Ref215568526)

[The hydraulic model stochastic simulations executed following this SOP do not fully prime the landscape with water that may be present prior to an event, which may tend to bias results as some excess precipitation may collect within undrained areas and contribute to filling channels that start dry. The use of restart files has the potential to address this concern but additional tools and methods to effectively sample both reservoir elevations and initial conditions across the landscape and in all channels have not been fully developed as of June 2025. A project to develop a more advanced method for hydraulic model initial conditions sampling has been scoped and would be focused on utilizing a future HEC-RAS version.](##_Ref215568526)

###### [<span id="_Toc217044393" class="anchor"></span>Meteorological Data—Excess Precipitation Time Series Grids](##_Ref215568526)

[Runoff is modeled as excess precipitation sourced from HEC-HMS simulations and therefore no infiltration model will be applied to the hydraulic model. Gridded excess precipitation file for each event will be exported from HEC-HMS and included as a boundary condition in the unsteady flow editor as a meteorological variable.](##_Ref215568526)

[During the calibration phase, the hydraulic modeler coordinates with hydrologic modeler to obtain the appropriate excess precipitation output corresponding appropriate historic event computed from HEC-HMS. The official storage location of the HEC-HMS DSS output at this stage is *calibration/hydrology/historic-events/*.](##_Ref215568526)

###### [<span id="_Toc217044394" class="anchor"></span>Observed Data Input](##_Ref215568526)

[It is recommended that observed flow, stage and rating data be added to the HEC-RAS flow file to provide a useful quick reference during the calibration phase modeling and review efforts. This reference data must be removed from the flow files for the conformance and production phase models that simulate hypothetical events.](##_Ref215568526)

#### [<span id="_Toc217044395" class="anchor"></span>Plan File—Simulation Options](##_Ref215568526)

[The following subsections describe standards for the plan files including simulation options for FFRD hydraulic models.](##_Ref215568526)

###### [<span id="_Toc217044396" class="anchor"></span>Time Window](##_Ref215568526)

[For calibration phase models that replicate historic events, all model simulations for calibration use a simulation start time and simulation end time that match the selected historic events defined during the scoping phase.](##_Ref215568526)

[For conformance and production phase models that are delivered to cloud compute, an event duration will be determined by the technical team lead that is long enough to capture the peak flood response for all storm events throughout the basin. The specific simulation time window dates are not critical (as they are not used directly in cloud compute), and the technical team lead will define the standard time window for all team members to use for consistency. Note that the time window will be varied by cloud-compute for each modeled event.](##_Ref215568526)

###### [<span id="_Toc217044397" class="anchor"></span>Computation Interval](##_Ref215568526)

[The computation interval is set to a value optimizing the model calibration, model stability, and model run-time. The Advanced Time Step Control (ATSC) option is considered during model development. Adjusting the timestep based on the Courant condition may reduce model run-times while maintaining model stability throughout the mesh. Based on the mesh refinement investigation, a starting computation interval of 30 seconds is recommended. When using ATSC, it may be necessary to have at least two halving steps to obtain model stability based on the wide range of cell sizes incorporated.](##_Ref215568526)

###### [<span id="_Toc217044398" class="anchor"></span>Hydrograph Output Interval](##_Ref215568526)

[The hydrograph output interval is set to ensure the peak stage and flow is captured in the reference lines and internal 2D connections. Typically, this is set to a maximum 1-hour time interval or lower if calibration data warrants a more frequent output interval.](##_Ref215568526)

###### [<span id="_Toc217044399" class="anchor"></span>Mapping Output Interval](##_Ref215568526)

[The mapping output interval should match the hydrograph output interval.](##_Ref215568526)

###### [<span id="_Toc217044400" class="anchor"></span>Detailed Output Interval](##_Ref215568526)

[The detailed output interval is not critical for 2D FFRD studies. This can vary during the modeling process, which is usually to have a lower interval during calibration for model debugging and refinement then a larger value for final production to reduce the size of the output files.](##_Ref215568526)

###### [<span id="_Ref215570513" class="anchor"><span id="_Toc217044401" class="anchor"></span></span>Warm-up Settings](##_Ref215568526)

[The warmup is a simulation that is performed prior to the start of the start time of the model and contributes to the initial conditions that are used for the actual model simulation. For FFRD 2D models, the warm-up settings are defined in the *plan editor – options – computational options and tolerances – 2D flow options* window. The Initial Conditions Time and Initial Conditions Ramp Up Fraction variables should be set the values according to modeling best practices.](##_Ref215568526)

[Duration and ramp-up options should be set based on their effectiveness in achieving accurate model results. For conformance and production phase models, the additional runtime and compute costs associated with the warm-up option may be considered.](##_Ref215568526)

###### [<span id="_Toc217044402" class="anchor"></span>Equation Set](##_Ref215568526)

[The diffusion wave equation set is preferrable due to model run times; however, model performance should be compared with the Shallow Water Equations, Eulerian-Lagrangian Method (SWE-ELM) and Shallow Water Equations, Local Inertial Approximation (SWE-LIA) 2D equations. Model equation set should be tested prior to calibration using the initial parameters. If a significant difference is observed between the diffusion wave and SWE equations, model development should focus on developing a calibrated model using the SWE 2D equations. If model run time is excessively impacted by the use of the SWE 2D equations and it is required for model accuracy, escalate to project leadership for guidance.](##_Ref215568526)

###### [<span id="_Toc217044403" class="anchor"></span>Matrix Solver](##_Ref215568526)

[The PARDISO solver is a robust solver and typically the used as the default solver for 2D hydraulic modeling in HEC-RAS. Alternatively, the SOR and FGRRAS-SOR solvers may provide computational speed improvements. FFRD models should utilize an appropriate solver that minimizes runtime while maintaining stability.](##_Ref215568526)

###### [<span id="_Ref215569478" class="anchor"><span id="_Toc217044404" class="anchor"></span></span>Breaches](##_Ref215568526)

[Dam and levee breaches are an important aspect of FFRD modeling and must be incorporated into hydraulic models. A list of structures to be breached for the modeling effort is scoped for the entire basin in the scoping and data preparation phase of the project and provided to the modeler prior to the start of model development.](##_Ref215568526)

[During the calibration phase, hydraulic models are developed to accommodate breaches that will be based on randomly sampled breach trigger elevations during the conformance and production phases. Specific tasks and general approaches for the hydraulic modeler related to breaching during the calibration phase are listed below.](##_Ref215568526)

- [**Levee Control Location (LCL) Review and Coordination:** LCLs (also known as initial overtopping locations) are approximated during the scoping and data preparation phase by the Levee Data Lead and are to be reviewed and confirmed by the hydraulic modeler during the calibration phase, with feedback provided to the Levee Data Lead for potential adjustments to specific breach siting.](##_Ref215568526)

- [**Breach Elevation Data:** Modelers must provide crest and toe elevation data for all breached structures. This is done through careful review of the DEM at each specified location and delivered and coordinated with the Dam and Levee Data Leads.](##_Ref215568526)

- [**Segmentation of Storage Area/2D Connections:** Dam and levee structures are segmented to enable specific breach locations as defined in the during the scoping phase. storage area/2D connections for dams and levees are segmented to allow for unique breach locations as scoped.](##_Ref215568526)

<!-- -->

- [Breaches are entered at fixed locations, and only one breach per storage area/2D connection is allowed in HEC-RAS.](##_Ref215568526)

<!-- -->

- [**Input of Breach Parameters:** Breach parameters are entered into the plan file using the Breach Editor, based on the guidelines provided in subsequent sections.](##_Ref215568526)

<!-- -->

- [For historical event calibrations, breach locations will typically be included in the model but configured to not trigger.](##_Ref215568526)

<!-- -->

- [**Model Stress Testing:** Hydraulic models must be stress-tested to ensure numerical stability during breach scenarios. Dam and levee breaches often result in dynamic flow conditions and rapidly varied flow, which can cause hydraulic model instability. Stress testing should be performed in the hydraulic model to ensure the model performs acceptably under the full range of expected breach conditions. Section [8.2.2](##_Ref215570616) discusses this testing.](##_Ref215568526)

- [**Breach Input Documentation:** The modeler must coordinate with the Dam and Levee Leads to ensure the official breach location listings include accurate information consistent on the final hydraulic model (see Section 9).](##_Ref215568526)

- [**Structure Categorization for Breach Parameter Method:** Custom breach parameters will be created for each structure based on the structure type and characteristics. Table 8.3 indicates the breach parameter method to apply for various structure categories. The specific breach parameters for each of the breach parameter methods are detailed in the following sections.](##_Ref215568526)

[<span id="_Toc214892778" class="anchor"></span>Table 8.3. Structure Categorization for Breach Parameter Method](##_Ref215568526)

| [Structure Category](##_Ref215568526) | [Breach Parameter Method](##_Ref215568526) |
|----|----|
| [Earthen Embankment Levees](##_Ref215568526) | [Simplified Physical](##_Ref215568526) |
| [I-wall Levees](##_Ref215568526) | [Simplified Physical](##_Ref215568526) |
| [T-wall and L-wall Levees](##_Ref215568526) | [Fixed Width](##_Ref215568526) |
| [Any Floodwall Type Embedded in Earthen Embankment](##_Ref215568526) | [Simplified Physical](##_Ref215568526) |
| [Levee Closure Structures](##_Ref215568526) | [Fixed Width](##_Ref215568526) |
| [Earthen Dams greater than 30 feet in height](##_Ref215568526) | [User Defined](##_Ref215568526) |
| [Earthen Dams less than 30 feet in height](##_Ref215568526) | [Simplified Physical](##_Ref215568526) |
| [Concrete Dams](##_Ref215568526) | [Fixed Width](##_Ref215568526) |
| [Concrete Gravity Dams with Earthen Embankment Sections](##_Ref215568526) | [Unique Cases](##_Ref215568526) |
| [Other](##_Ref215568526) | [Unique Cases](##_Ref215568526) |

[Additional information regarding dam and levee breaching can be found in the [HEC-RAS user manual](https://www.hec.usace.army.mil/confluence/rasdocs/rasum/6.6/performing-a-1d-unsteady-flow-analysis/performing-a-dam-or-levee-breach-analysis-with-hec-ras/user-enter-breach-data).](##_Ref215568526)

######## [Simplified Physical Method](##_Ref215568526)

[The method requires an input of a breach widening rate versus flow velocity relationships which represent soil parameters (erodibility) and allows the breach development to be simulated based on modeled hydraulics (velocity, time).](##_Ref215568526)

[Resulting breach dimensions are carefully inspected after the hydraulic simulation to ensure the method produces reasonable results for all scenarios and adjustments are made as necessary. Table 8.4 summarizes breach parameters for this method.\
](##_Ref215568526)

[<span id="_Toc214892779" class="anchor"></span>Table 8.4. Breach Parameters for Simplified Physical Breach Approach](##_Ref215568526)

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 27%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Breach Parameter</a></th>
<th><a href="##_Ref215568526">Value to Use</a></th>
<th><a href="##_Ref215568526">Notes and Selection of Values</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Breach This Structure<br />
(yes or no)</a></td>
<td><a href="##_Ref215568526">Enabled during model development. Disabled upon delivery from calibration phase</a></td>
<td><a href="##_Ref215568526">Not all storage area/2D connections are to be breached. This table applies only to dams and levees selected for breach analysis. Additional discussion below.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Breach Method</a></td>
<td><a href="##_Ref215568526">Simplified Physical</a></td>
<td><a href="##_Ref215568526">Used for levees and dams less than 30 feet</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Center Station</a></td>
<td><a href="##_Ref215568526">Varies</a></td>
<td><a href="##_Ref215568526">Additional discussion below</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Max Possible Bottom Width</a></td>
<td><a href="##_Ref215568526">Varies</a></td>
<td><a href="##_Ref215568526">Additional discussion below</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Minimum Possible Bottom Elevation</a></td>
<td><a href="##_Ref215568526">Varies</a></td>
<td><a href="##_Ref215568526">Additional discussion below</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Left/Right Side Slope</a></td>
<td><a href="##_Ref215568526">0 (vertical)</a></td>
<td><a href="##_Ref215568526">Zero unless compelling reason otherwise</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Breach Weir Coefficient</a></td>
<td><a href="##_Ref215568526">Varies</a></td>
<td><a href="##_Ref215568526">Additional discussion below</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Breach Formation Time</a></td>
<td><a href="##_Ref215568526">N/A</a></td>
<td><a href="##_Ref215568526">Not required for the simplified physical breach method</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Failure Mode</a></td>
<td><a href="##_Ref215568526">Piping</a></td>
<td><a href="##_Ref215568526">Standard value for FFRD study</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Piping Coefficient</a></td>
<td><a href="##_Ref215568526">0.5</a></td>
<td><a href="##_Ref215568526">Default value</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Initial Piping Elevation</a></td>
<td><a href="##_Ref215568526">Same as minimum bottom elevation</a></td>
<td><a href="##_Ref215568526">Standard value for FFRD study</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Initial Piping Diameter</a></td>
<td><a href="##_Ref215568526">1 foot</a></td>
<td><a href="##_Ref215568526">Standard value for FFRD study</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Mass Wasting Feature</a></td>
<td><a href="##_Ref215568526">Disabled</a></td>
<td><a href="##_Ref215568526">Standard value for FFRD study</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Trigger Failure At</a></td>
<td><a href="##_Ref215568526">Water Surface Elevation</a></td>
<td><a href="##_Ref215568526">Standard value for FFRD study</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Starting Water Surface</a></td>
<td><a href="##_Ref215568526">See discussion below</a></td>
<td><a href="##_Ref215568526">Additional discussion below</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Simplified Physical downcutting velocity-downcutting relationship</a></td>
<td><a href="##_Ref215568526">Varies</a></td>
<td><a href="##_Ref215568526">Additional discussion below</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Simplified Physical widening velocity-downcutting relationship</a></td>
<td><a href="##_Ref215568526">Same as downcutting relationship</a></td>
<td><a href="##_Ref215568526">Assume symmetrical breach development</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Breach Repair</a></td>
<td><a href="##_Ref215568526">Blank</a></td>
<td><a href="##_Ref215568526">A blank value disables breach repair</a></td>
</tr>
</tbody>
</table>

########## [Breach Center Station](##_Ref215568526)

[The breach center station should be selected based on best available data, including risk assessments and levee screening tool analyses. Breach width cannot extend beyond the edge of the storage area/2D connection, which the breach is modeled as part of. Therefore, the breach center station should be far enough from the end of a storage area/2D connection so that the length of the structure does not artificially limit the potential maximum breach width. Suitable locations for breach center stations include areas of known poor levee performance, incipient levee overtopping locations, and locations of maximum levee height.](##_Ref215568526)

########## [Maximum Breach Width](##_Ref215568526)

[The maximum breach width is set to a value large enough such that it does not limit the breach development. Use of a 1,500-foot maximum width is suggested. If there are physical constraints that would limit breach development (e.g., tie into high-ground, or a well-founded structure), the maximum breach width is set accordingly. Maximum breach extents cannot extend beyond the storage area/2D connection they are modeled within.](##_Ref215568526)

########## [Minimum Possible Bottom Elevation](##_Ref215568526)

[The breach invert for a levee is set at approximately the interior land elevation adjacent to the levee at the specific breach location. The breach invert for a dam that is using the simplified physical method should be set to the elevation of the downstream streambed.](##_Ref215568526)

########## [Breach Side Slopes](##_Ref215568526)

[By default, breach side slopes should be set to zero (i.e., vertical side slopes) for levees and for dams less than 30 feet in height.](##_Ref215568526)

########## [Breach Weir Coefficient](##_Ref215568526)

[The breach weir coefficient impacts the velocity though the breach and can also have significant impacts on the breach width when using the simplified physical breaching methodology. The weir coefficient for levees where the river is parallel to the levee and any breach will have an indirect flow through a breach should be set to a value of 2.0, which a conservative estimate for lateral flows. For dams and for levees where the flow through the breach will be more direct flow and behaves similarly to a dam, the default weir coefficient of 2.6 should be used.](##_Ref215568526)

########## [Breach Failure Mode](##_Ref215568526)

[For all scenarios, the failure mode should be set to piping. Due to complexities of switching failure modes in stochastic computing, piping failure will be used for all scenarios. This will enable all scenarios whether piping or overtopping would initiate a breach.](##_Ref215568526)

########## [Initial Piping Elevation (piping mode only)](##_Ref215568526)

[Initial piping elevation is set equal to the minimum possible bottom elevation, also known as the breach invert. If detailed information is available from a risk assessment or other reliable source, this value can be adjusted.](##_Ref215568526)

########## [Initial Piping Diameter (piping mode only)](##_Ref215568526)

[The initial piping diameter will be set to 1 foot by default.](##_Ref215568526)

########## [Mass Wasting Feature](##_Ref215568526)

[The mass wasting feature will not be used for breach models and should be disabled.](##_Ref215568526)

########## [Trigger of Breach](##_Ref215568526)

[Breaches will be triggered based on a specified water surface elevation.](##_Ref215568526)

[During the calibration phase, historic events will typically be modeled with breaches disabled unless actual breaches were observed.](##_Ref215568526)

[During the calibration phase, stress testing for model stability is also performed, and triggers may be set to critical conditions, such as the toe of the breach or near the peak stage of the hydrograph used for stress testing.](##_Ref215568526)

[During the conformance and production phases, the trigger elevation will be set stochastically for each event within the cloud-compute environment. The hydraulic modeler will deliver the model for cloud compute with the trigger elevation set to the toe of the breach, which will be overridden during the cloud compute process. Note, this override process is described in Job Aid 11, *Levee Breach Workflows*.](##_Ref215568526)

########## [Velocity versus Erosion Rate Relationships](##_Ref215568526)

[Erosion rate versus velocity relationships will be estimated using the methods annotated within the spreadsheet tool provided in Tools—Simplified Physical Widening Rates. Unless additional detailed information is available, an erodibility parameter (k<sub>d</sub>) of 25mm/hr/pa should be used. When additional erodibility data is readily available (e.g. when levee risk assessment has been completed and includes erodibility information), a custom erodibility parameter can be applied.](##_Ref215568526)

[Resulting breach width are to be assessed through stress testing scenarios or other sensitivity test. Any unrealistic breach widths should be addressed and could be used as rational to adjust the erodibility parameter, maximum breach width or other assumptions. Engineering judgement is required for any adjustments and any deviation from the standard assumptions must be well documented.](##_Ref215568526)

######## [User Defined Method](##_Ref215568526)

[Breach parameters for earthen dams with a height of more than 30 feet will be estimated from regression equations and entered in the HEC-RAS file as *user entered data*.](##_Ref215568526)

[An annotated breach equation spreadsheet (Tools—Breach Parameter Regression Equations) is provided to aid in the application of the regression equations. This tool also includes links for key references that support the methods and a calculator to estimate breach parameters. A variety of breach regression equations and considered and the most used breach regression equations are MacDonald and Langridge-Monopolis, Froehlich (1995a), Froehlich (2008), and Von Thun and Gillette (1990).](##_Ref215568526)

[A single breach width and development time will be used for all FFRD events. Inputs to the regression equations will assume the pool at TOD and the breach invert is set to the downstream streambed elevation.](##_Ref215568526)

[Resulting breach dimensions should be carefully inspected and the most appropriate results selected for incorporation into the hydraulic models. Some equations may be easily eliminated from consideration if the breach parameters are larger than the dam embankment or produce too small of an opening given the size of the reservoir. Engineering judgement should be exercised for each dam which may include knowing the condition of the dam, the core material, etc. that may provide insight in the selection of the appropriate parameters that are realistic. Appropriate breach parameters should produce breach dimensions and formation times such that at the completion of breach formation, flow velocities have dropped below a threshold where significant additional widening of the breach would not occur. If a breach regression equation predicts dimensions and formation times, which result in a rapid breach where significantly large head differentials and flow velocities remain following the breach formation, these regression parameters may not be reasonable.](##_Ref215568526)

########## [Breach Center Station](##_Ref215568526)

[The center of the breach should generally be located in the center of the embankment over the tallest section of the dam. If information is available from prior risk assessment studies, these can be used to inform breach locations.](##_Ref215568526)

########## [Breach Bottom Width](##_Ref215568526)

[The breach bottom width from the selected regression equation will be used in the hydraulic model. Breach widths will typically be 0.5 to 5 times the height of dam. However, wider breach widths may be reasonable, especially for dams with significant volume.](##_Ref215568526)

########## [Breach Bottom Elevation](##_Ref215568526)

[The breach invert should be set to the elevation of the downstream streambed.](##_Ref215568526)

########## [Breach Side Slopes](##_Ref215568526)

[The breach side slopes should be set to the side slopes specified for the regression equation that was selected.](##_Ref215568526)

########## [Breach Weir Coefficient and Piping Coefficient](##_Ref215568526)

[A breach weir coefficient will be set to 2.6 and the piping coefficient will be set to 0.5.](##_Ref215568526)

########## [Breach Formation Time](##_Ref215568526)

[The breach formation time from the regression equation that was used for the breach bottom with selection should be used in the hydraulic model. Formation time of breach should typically fall in the range of 0.1 to 4 hours. However, longer formation times may be reasonable, especially for dams with significant reservoir volume.](##_Ref215568526)

########## [Initial Piping Elevation](##_Ref215568526)

[Initial piping elevation is set equal to the breach bottom elevation.](##_Ref215568526)

########## [Breach Failure Mode](##_Ref215568526)

[For all scenarios, the failure mode should be set to piping. Due to complexities of switching failure modes in stochastic computing, piping failure will be used for all scenarios.](##_Ref215568526)

########## [Trigger of Breach](##_Ref215568526)

[Breaches will be triggered based on a specified water surface elevation.](##_Ref215568526)

[During the calibration phase, historic events will typically be modeled with breaches disabled unless actual breaches were observed.](##_Ref215568526)

[During the calibration phase, stress testing for model stability is also performed, and triggers may be set to critical conditions, such as the toe of the breach or near the peak stage of the hydrograph used for stress testing.](##_Ref215568526)

[During the conformance and production phases, the trigger elevation will be set stochastically for each event within the cloud-compute environment. The hydraulic modeler will deliver the model for cloud compute with the trigger elevation set to the toe of the breach, which will be overridden during the cloud compute process.](##_Ref215568526)

########## [Breach Progression](##_Ref215568526)

[The breach progression should be based on a sine wave as opposed to linear. The breach progression is defined as a fraction of total breach progression as a function of the total time. Breaches tend to start slowly, and finish asymptotically, with the maximum deepening and widening rate occurring in the middle of the breach. The sine wave more realistically approximates the progression of a breach.](##_Ref215568526)

######## [Fixed Width](##_Ref215568526)

[For non-earthen structures such as concrete gravity dams, T-wall levees or arch dams breach parameters are estimated as a fixed width according to the guidance below.](##_Ref215568526)

########## [Breach Center Station](##_Ref215568526)

[The center of the breach should generally be in the middle of the concrete portion of the structure unless there are geometric constraints or detailed available information suggesting a different location.](##_Ref215568526)

########## [Breach Bottom Width](##_Ref215568526)

[For concrete gravity dams, the breach width will be assumed to be half the length of the dam but not to exceed 600 feet, which would be equivalent to six 100-foot monoliths.](##_Ref215568526)

[For concrete arch dams, it will be assumed the entire dam is breached. The breach width of an arch dam is the distance between the abutments.](##_Ref215568526)

[For T-wall or L-wall levees, the breach width will be assumed to be 2 monoliths wide. If monolith width is not known, assume a 40-foot monolith width.](##_Ref215568526)

[For closure structures on levees, the breach width should be set to the width of the closure.](##_Ref215568526)

########## [Breach Bottom Elevation](##_Ref215568526)

[The breach invert should be set to the elevation of the downstream streambed.](##_Ref215568526)

########## [Breach Side Slopes](##_Ref215568526)

[The breach side slopes will be set to zero (i.e., vertical). As an exception, the breach side slops for a concrete arch dam will be set to the slope of the valley walls.](##_Ref215568526)

########## [Breach Weir Coefficient and Piping Coefficient](##_Ref215568526)

[A breach weir coefficient will be set to 2.6 and the piping coefficient will be set to 0.5.](##_Ref215568526)

########## [Breach Formation Time](##_Ref215568526)

[Concrete dam breaches typically occur near-instantaneously but for hydraulic model stability, the breach formation for both concrete gravity and concrete arch will be set to 0.1 hours.](##_Ref215568526)

########## [Initial Piping Elevation](##_Ref215568526)

[Initial piping elevation is set equal to the breach bottom elevation.](##_Ref215568526)

########## [Breach Failure Mode](##_Ref215568526)

[For all scenarios, the failure mode should be set to piping. Due to complexities of switching failure modes in stochastic computing, piping failure will be used for all scenarios.](##_Ref215568526)

########## [Trigger of Breach](##_Ref215568526)

[Breaches will be triggered based on a specified water surface elevation.](##_Ref215568526)

[During the calibration phase, historic events will typically be modeled with breaches disabled unless actual breaches were observed.](##_Ref215568526)

[During the calibration phase, stress testing for model stability is also performed, and triggers may be set to critical conditions, such as the toe of the breach or near the peak stage of the hydrograph used for stress testing.](##_Ref215568526)

[During the conformance and production phases, the trigger elevation will be set stochastically for each event within the cloud-compute environment. The hydraulic modeler will deliver the model for cloud compute with the trigger elevation set to the toe of the breach, which will be overridden during the cloud compute process.](##_Ref215568526)

########## [Breach Progression](##_Ref215568526)

[The breach progression should use a sine wave. However, given the rapid nature of a concrete breach, the breach progression is not anticipated to have a significant impact on the breach flood wave.](##_Ref215568526)

######## [Unique Cases](##_Ref215568526)

[Certain structures to be breached are not easily categorized as earthen dams, earthen levees, or floodwall structures. For example, a dam may include both earthen embankment and concrete gravity dam features. In other cases, the design section at the breach site may be unique.](##_Ref215568526)

[In these cases, engineering judgement must be used in selection of which section to breach. Some of the factors that may influence the decision could be known risk drivers, condition of sections, overtopping frequency, etc. A sensitivity analysis may be warranted to determine impacts from a breach of each section. Once the section is selected, the breach parameters should be determined using an appropriate method described in the previous sections.](##_Ref215568526)

#### [<span id="_Toc217044405" class="anchor"></span>RAS Mapper File](##_Ref215568526)

[The RAS Mapper file should include references to all files that are required to execute the model on desktop. Additional references layers may be included to assist with review efforts.](##_Ref215568526)

#### [<span id="_Toc217044406" class="anchor"></span>Calibration and Performance Criteria](##_Ref215568526)

[The primary objective of hydraulic model development during the calibration phase is to ensure the model reasonably replicates observed data for the historic events at stream gage locations identified during the scoping and data preparation phase. This ability to match observed data from historic events provides confidence that the models will accurately predict the response from synthetic flood events.](##_Ref215568526)

[In addition to replicating observed conditions, models must demonstrate numerical stability, and the resulting mapped outputs must be of sufficient quality. Objective criteria for model calibration, stability, and quality of mapped results are provided in the sections below. Additional guidance on calibration techniques and best practices is provided in Job Aid 12, *Model Calibration*. Tools available to aid in the evaluation of calibration are also provided in *Appendix F*.](##_Ref215568526)

###### [<span id="_Toc217044407" class="anchor"></span>Calibration Targets](##_Ref215568526)

[The following subsections provide the specific targets for calibration to observed data.](##_Ref215568526)

######## [Stage and Flow Time Series](##_Ref215568526)

[Objective model calibration criteria for stage and flow time series for the duration of the flood event is based on standard model evaluation statistics with corresponding performance ratings. Model evaluation statistics include the coefficient of determination (R<sup>2</sup>), Nash-Sutcliffe Efficiency (NSE), Ratio of the Root Mean Square Error to the Standard Deviation Ratio (RSR), and percent bias (PBIAS). Table 8.5 provides model performance ratings to apply to flow and stage for each calibration event for all locations where data is available. Tools provided in Appendix F may be applied to aid in the calculation of these calibration statistics.](##_Ref215568526)

[All stream gages with observed data are categorized as either primary, secondary, and tertiary during the scoping and data preparation phase of the project. This categorization guides the evaluation of these statistics as follows:](##_Ref215568526)

1.  

<!-- -->

1.  [Primary gage locations are evaluated first. Statistical comparisons of computed and observed flow/stage at all primary locations must be in the satisfactory (per Table 8.5) or higher range.Secondary locations are evaluated second. Statistical comparisons of computed and observed flow/stage at all secondary locations should be in the satisfactory or higher range. If appropriate technical justification is provided and primary locations evaluate favorably, some leeway is granted.](##_Ref215568526)

2.  [Tertiary locations are evaluated last. Statistical comparisons of computed and observed flow/stage at all tertiary locations must be in the satisfactory or higher range. However, if secondary and primary locations evaluate favorably (and adequate hydrologic justification is provided), some leeway is granted.](##_Ref215568526)

[If calibration metrics are found difficult to achieve, the underlying cause for the poor fit must be explained, discussed with the team, and well documented in calibration phase report. This includes the pros and cons of the calibration statistics and how the model is reflective of the gage rating curve.<span id="_Toc214892780" class="anchor"></span>\
](##_Ref215568526)

[Table 8.5. Model Calibration Performance Ratings](##_Ref215568526)

| [Performance Rating](##_Ref215568526) | [Color Code](##_Ref215568526) | [R<sup>2</sup>](##_Ref215568526) | [NSE](##_Ref215568526) | [RSR](##_Ref215568526) | [PBIAS](##_Ref215568526) |
|----|:--:|:--:|:--:|:--:|:--:|
| [Very Good](##_Ref215568526) | [Dark Green](##_Ref215568526) | [R<sup>2</sup>\>0.65](##_Ref215568526) | [0.65\<NSE≤1.00](##_Ref215568526) | [0.00\<RSR≤0.60](##_Ref215568526) | [PBIAS≤±15](##_Ref215568526) |
| [Good](##_Ref215568526) | [Light Green](##_Ref215568526) | [0.55\<R<sup>2</sup>≤0.65](##_Ref215568526) | [0.55\<NSE≤0.65](##_Ref215568526) | [0.60\<RSR≤0.70](##_Ref215568526) | [±15\<PBIAS≤±20](##_Ref215568526) |
| [Satisfactory](##_Ref215568526) | [Orange](##_Ref215568526) | [0.40\<R<sup>2</sup>≤0.65](##_Ref215568526) | [0.40\<NSE≤0.55](##_Ref215568526) | [0.70\<RSR≤0.80](##_Ref215568526) | [±20\<PBIAS≤±30](##_Ref215568526) |
| [Unsatisfactory](##_Ref215568526) | [Red](##_Ref215568526) | [R<sup>2</sup>≤0.40](##_Ref215568526) | [NSE≤0.40](##_Ref215568526) | [RSR\>0.80](##_Ref215568526) | [PBIAS\>±30](##_Ref215568526) |

######## [Simulated Flow Across Models](##_Ref215568526)

[During the calibration phase, simulated flow hydrographs from the hydraulic model will be compared to those from the hydrologic model at all coincident locations for each historic event. In areas unaffected by dam regulation, the hydrographs should reasonably align in terms of volume, timing, and peak flow. While no specific quantitative criteria are provided in this SOP, the alignment of simulated results across models should be sufficient to provide confidence in model performance. Engineering judgment must be applied to assess whether the hydrographs are in reasonable agreement.](##_Ref215568526)

######## [Peak Flow](##_Ref215568526)

[Peak flows at calibration locations must be evaluated versus both observed values and values from the hydrologic model, and significant differences must be addressed. Consideration should be given to local flow patterns and gage locations, as the specific extent of hydraulic model reference lines used to extract flow results may impact reporting of hydraulic model flow results.](##_Ref215568526)

######## [Peak Stage](##_Ref215568526)

[During the calibration phase, the simulated peak stage for each calibration event must be within 1 foot of the observed peak stage for that event. If the simulated result falls outside this 1-foot threshold, the calibration phase report must include a clear and specific rationale for the exception, supported by engineering judgment and relevant data.](##_Ref215568526)

######## [Discharge-Elevation Relationship](##_Ref215568526)

[The modeled discharge-elevation relationship must be evaluated against available field observations and annual peak data at all stream gages. Simulated relationships may be extracted from model results at each time step of the largest modeled event, as well as from peak values across each modeled event. While a statistical comparison is not required, the rating curve provides a qualitative measure of confidence that informs the calibration process.](##_Ref215568526)

[The simulated relationship should generally fall within the scatter of observed data across the full range of flows and be within 1 foot of the largest observed peak stages. Greater emphasis should be placed on how well the model captures out-of-channel flows and large flood events. During qualitative evaluation, the age of observed data and any significant watershed changes since those measurements may be considered.](##_Ref215568526)

[If the simulated results deviate from observed data, the calibration phase report must include a clear, specific rationale for the exception, supported by engineering judgment and relevant supporting data.<span id="_Toc214891704" class="anchor"></span>\
](##_Ref215568526)

[Figure 8.6. Graphical Discharge-Elevation Relationship](##_Ref215568526)

[<img src="media/image15.png" style="width:6.5in;height:4.08403in" />](##_Ref215568526)

######## [Other Observed Data Comparisons](##_Ref215568526)

[An attempt is made to identify additional observed flood event data that could aid in the model calibration during the scoping and data preparation phase. Additional data may include high mark data, satellite imagery during floods, or photographs. When available qualitive comparisons to this data should be made and may support adjustments to model parameters in some cases.](##_Ref215568526)

######## [Ungaged Basins](##_Ref215568526)

[Ungaged modeling units should use hydraulic parameters developed using guidelines from literature, data from other similar modeling units within the basin, and professional engineering judgement.](##_Ref215568526)

###### [<span id="_Toc217044408" class="anchor"></span>Quality of Mapped Results](##_Ref215568526)

[The mapped depth and velocity outputs from any given hydraulic modeled event must be of sufficient quality and resolution. The standard for mapping quality is higher in urban areas and along key streams and their floodplains as defined by the mesh development criteria during the scoping and data preparation phase. At a minimum, depth maps along perennial streams should appear connected.](##_Ref215568526)

[Map rendering mode in HEC-RASMapper can have a significant impact on the appearance of mapped results for individual events in the desktop environment. However, FFRD risk products are being computed based on depth grids generated with the cloud-compute tools that specifically reference the *Sloping (Cell Corners + Face Centers – Depth Weighted Faces ‘Precip Mode’)* as of June 2025.](##_Ref215568526)

[Mapped results are compared against structure placements in the structure inventory, which can aid in identification of hydraulic model issues or structure placement issues. Addressing issues identified require coordination with the consequences team member and may result in adjustments to the structure inventory or hydraulic model as appropriate. These steps are also referred to in Section 10 and in Job Aid 17, *Consequence Processes*.](##_Ref215568526)

###### [<span id="_Toc217044409" class="anchor"></span>Model Runtime Criteria](##_Ref215568526)

[Model runtime is an important consideration in hydraulic model development and runtime must be minimized. The recommended model development process starts with a relatively coarse mesh that is iteratively refined as needed to achieve numerical stability and acceptable quality of mapped results. Efforts should be made to increase model stability and reduce runtimes as much as is practical, utilizing best practices within the hydraulic modeling community of practice.](##_Ref215568526)

###### [<span id="_Toc217044410" class="anchor"></span>Model Stability Criteria](##_Ref215568526)

- [HEC-RAS models should compute with minimal computational error for all scenarios. The tighter the error tolerance, the more confidence you can have in hydrograph timing and peak flow routing.  Evaluation of the following stability metrics must be performed.<u>Volume Accounting Error</u>:  Error should be less than 3% and is required to be less than 5% for all scenarios.  Volume errors within +/- 1-2% are considered very good for 2D modeling.  Values \<5% are reasonable if the spatial mapping aligns with expectations.](##_Ref215568526)

- [<u>Maximum Water Surface Elevation Error</u>:  The error for maximum water surface is generally considered as more of a tolerance.  Tolerance of \<0.05 feet is generally considered high accuracy while a tolerance of \<0.1 feet is considered reasonable.  When water surface elevation tolerance exceed about 0.1 feet often suggests numerical instability and is not considered reasonable. The spatial extent of the maximum water surface errors may also be considered, as isolated instabilities may be tolerable.](##_Ref215568526)

- [<u>Cell Water Surface Error</u>:  Cell water surface error is computed by a comparison of the change implied by the computed water surface.  Acceptable levels or error are consistent with the maximum water surface elevation error designation and values \<0.1 feet are considered reasonable and acceptable.](##_Ref215568526)

- [<u>Cumulative Maximum Iterations</u>:  Maximum Iterations is an indication of whether your model is converging.  Convergence is measured by the continuity error and the water surface error.  Rule of thumb is that Max iterations exceeded should be rare and continuity errors \< 5% and cell water surface errors \< 0.1 feet are acceptable.](##_Ref215568526)

#### [<span id="_Toc217044411" class="anchor"></span>Documentation of Hydraulic Modeling](##_Ref215568526)

[A set of standard reports is written for each phase in the FFRD project. Appendix B contains report templates for the hydraulic modeling reports.](##_Ref215568526)

[Table 8.6 summarizes locations of key hydraulic modeling documentation included in each of the reports.<span id="_Toc214892781" class="anchor"></span>\
](##_Ref215568526)

[Table 8.6. Locations of Key Hydraulic Modeling Documentation](##_Ref215568526)

| [Scoping and Data Preparation Phase Report](##_Ref215568526) | [Documentation of model unit delineation and many other scoping decisions for model development and calibration](##_Ref215568526) |
|----|----|
| [Calibration Phase Report](##_Ref215568526) | [Primary documentation of hydraulic model development and calibration](##_Ref215568526) |
| [Conformance Phase Report](##_Ref215568526) | [Description of all hydraulic model adjustments made to accept synthetic SST events and any adjustments to reasonably align with observed frequency data](##_Ref215568526) |
| [Production Phase Report](##_Ref215568526) | [Descriptions of any hot fixes or patches required in the production phase.](##_Ref215568526) |

#### [<span id="_Toc217044412" class="anchor"></span>Hydraulic Model Review Process and Deliverables](##_Ref215568526)

[Model review is a critical part of the FFRD production process. Several review steps are required to ensure the final model delivered can effectively run in a stochastic environment and is capable of accurately depicting basin-wide flood risk on a broad scale. Review checklists are used to track comments regarding pre-defined aspects checked throughout the review process. Appendix A contains checklist templates.](##_Ref215568526)

[The following subsections describe specific review steps.](##_Ref215568526)

###### [<span id="_Toc217044413" class="anchor"></span>Scoping and Data Preparation Phase Review](##_Ref215568526)

[The model unit delineation, model linking register, naming table, and all other scoping and data preparation phase are reviewed and documented in the Scoping and Data Preparation Checklist, which requires multiple reviewers and is described in Section 4.](##_Ref215568526)

###### [<span id="_Toc217044414" class="anchor"></span>Calibration Phase Reviews](##_Ref215568526)

[The following reviews are performed during the calibration phase.](##_Ref215568526)

######## [Initial Progress Review Web Meeting](##_Ref215568526)

[The purpose of this early review is to ensure progress is being made toward delivery for review and for reviewers and team leads to provide support to modeling staff to ensure full guidance has been provided and that model development is adhering to FFRD standards. Model data is typically not transferred during this review, but webinars are held to show progress and discuss possible issues using screen sharing.](##_Ref215568526)

[Additional check-ins during model development may be useful and are encouraged as a best practice.](##_Ref215568526)

######## [Quality Control Review](##_Ref215568526)

[The deliverable will be posted to Model Library *calibration* Directory and will include:](##_Ref215568526)

- [Model:](##_Ref215568526)

<!-- -->

- [Model file posted to the calibration/hydraulics/\[model-unit\]/ directory](##_Ref215568526)

- [Files must be present in the Model Library unzipped](##_Ref215568526)

- [Working calibrated model files for all calibration/validation events including all files required to run and replicate the results.](##_Ref215568526)

- [Do not include non-final extraneous plans in the model or output files or records associated with out-of-date runs.](##_Ref215568526)

- [Do not include terrain inside the hydraulics directory](##_Ref215568526)

- [Scenarios (plans) to be included:](##_Ref215568526)

<!-- -->

- [Each historic calibration and validation event](##_Ref215568526)

- [Stress test events](##_Ref215568526)

<!-- -->

- [Output files required:](##_Ref215568526)

<!-- -->

- [HDF output files](##_Ref215568526)

- [DSS output files (single DSS for all scenarios)](##_Ref215568526)

- [Do not include saved maps (i.e., depth grids) in the review package.](##_Ref215568526)

<!-- -->

- [Breach Data. Draft table including the model unit name, HEC-RAS 2D connection name, crest, and toe elevation for each breach location that are present in the HEC-RAS mode.](##_Ref215568526)

- [Documentation of the confirmation of the LCLs and coordination with the Levee Data Lead.](##_Ref215568526)

<!-- -->

- [RAS Mapper Terrain:](##_Ref215568526)

<!-- -->

- [Post draft final RAS Terrain to the *terrain-modeling* directory](##_Ref215568526)

- [Do not include the terrain directly in the *hydraulics* directory](##_Ref215568526)

- [Do not create duplicate or alternate versions of the terrain used for HEC-RAS model but ensure that the version in *terrain-modeling* is current. Optionally, outdated versions of the terrain may be moved to an *archive* sub-directory within *terrain-modeling*.](##_Ref215568526)

- [Do not provide alternate iterations of the terrain. Only the draft final terrain is to be delivered.](##_Ref215568526)

<!-- -->

- [<u>Report</u>: Draft calibration phase report hydraulic modeling section.](##_Ref215568526)

- [<u>Checklist</u>: Hydraulic model review checklist with modeler comments/notes included for every review item. This ensures all aspects of the model to be reviewed have been addressed by the modeler prior to review.](##_Ref215568526)

- [Reference material: As needed.](##_Ref215568526)

######## [Backcheck of Quality Control Comments](##_Ref215568526)

[After QC comments have been provided by the review and addressed by the modeler. The updated deliverable will be posted to Model Library *calibration* directory, and the previous version will be moved to the archive subdirectory. This delivery will include the following:](##_Ref215568526)

- [<u>Model</u>: Working calibrated model for all calibration/validation events](##_Ref215568526)

<!-- -->

- [Files must be present in the Model Library unzipped](##_Ref215568526)

- [Working calibrated model files for all calibration/validation events including all files required to run and replicate the results](##_Ref215568526)

- [Do NOT include non-final extraneous plans in the model or output files or records associated with out-of-date runs](##_Ref215568526)

- [Scenarios (plans) to be included](##_Ref215568526)

<!-- -->

- [Each historic calibration and validation event](##_Ref215568526)

- [Stress test events](##_Ref215568526)

<!-- -->

- [Output files required](##_Ref215568526)

<!-- -->

- [HDF output files](##_Ref215568526)

- [DSS output files (single DSS for all scenarios)](##_Ref215568526)

- [Do not include saved maps (i.e., depth grids) in the review package.](##_Ref215568526)

<!-- -->

- [Breach Data. Table including the HEC-RAS 2D connection name, crest, and toe elevation for each breach location. Documentation of the confirmation of the LCLs and coordination with the Levee Data Lead.](##_Ref215568526)

<!-- -->

- [RAS Mapper Terrain:](##_Ref215568526)

<!-- -->

- [Post draft final HEC-RAS Terrain to the *terrain-modeling* directory](##_Ref215568526)

- [Do not include the terrain directly in the *hydraulics* directory](##_Ref215568526)

- [Do not create duplicate or alternate versions of the terrain used for HEC-RAS model but ensure that the version in *terrain-modeling* is current. Optionally, outdated versions of the terrain may be moved to an *archive* sub-directory within *terrain-modeling*.](##_Ref215568526)

- [Do not provide alternate iterations of the terrain. Only the draft final terrain is to be delivered.](##_Ref215568526)

<!-- -->

- [<u>Mapping RAS Mapper Terrain</u>: Merged exported version of HEC-RAS Terrain at 3-meter resolution with rasterized modifications to the *terrain-mapping* directory.](##_Ref215568526)

- [<u>Report</u>: Final modeling report.](##_Ref215568526)

- [<u>Checklist</u>: Hydraulic model review checklist with Resolution of Reviewer Comments by Modeler section completed for all comments.](##_Ref215568526)

######## [Finalization of Calibration Phase Delivery](##_Ref215568526)

[Any necessary additional iterations of delivery updates to fully close the review will be similarly posted to the calibration directory, and the previous version moved to archive. This is the final calibration phase model that will not be edited going forward in the FFRD process.](##_Ref215568526)

###### [<span id="_Toc217044415" class="anchor"></span>Conformance Phase Reviews](##_Ref215568526)

[The following reviews are performed during the conformance phase.](##_Ref215568526)

######## [Pre-Conformance Review](##_Ref215568526)

[Preparation for hydraulic model use in conformance phase requires a review. After the calibration phase hydraulic model review is closed out, it will be saved and remain in its directory location and be the official calibration model. Note that the calibration phase review checklist includes items that focus on ensuring the transition from historic event-based calibration to stochastic event modeling will be seamless.](##_Ref215568526)

[All constituent models posted to the *conformance* directory are assessed by the project’s model integration lead for interoperability aspects of the project, and comments are provided and will be addressed by the modeler.](##_Ref215568526)

######## [Conformance Phase Review](##_Ref215568526)

[After the calibration phase is complete, the conformance phase begins, and ownership of the model will transition to a smaller model integration team who will promote a copy of the calibrated models to the *conformance* directory. Certain changes to the model will be made to ensure synthetic events can be executed successfully. Section 12 describes these steps in detail.](##_Ref215568526)

[Once the backcheck review is complete and any model integration items are addressed, the modeling technical lead determines if additional items need addressed or if the model is complete and ready to proceed to be applied to the conformance phase of the project.](##_Ref215568526)

## [<span id="_Toc217044416" class="anchor"></span>—Dam and Levee System Response Modeling](##_Ref215568526)

[This section focuses dam and levee system response modeling. The breach locations and system response of dams and levees when loaded are important to the modeling effort. Siting specific breach locations for dams and levees, development of SRP data, and sampling approaches for breaches are described here. Other related topics, such as physical representation of dams and levees in the models and selection of breach parameters (size, development time, etc.), are covered in other sections.](##_Ref215568526)

#### [<span id="_Toc217044417" class="anchor"></span>Dam and Levee Modeling Context and Standards](##_Ref215568526)

[This section outlines the dam and levee system response process and standards necessary to meet overall FFRD objectives. FFRD seeks to map residual risks behind dams and levees. The objectives of FFRD will be met via basin-level study using available information on the dams and levees in the study area. The approach combines robust statistical methods, practical engineering judgment, and efficient computational strategies to deliver on FFRD goals. It is acknowledged that data gaps exist, and probabilistic dam and levee modeling is a developing research area.](##_Ref215568526)

[Dam and levee system response models produced following this guidance will have the following characteristics:](##_Ref215568526)

- [Ability to capture dam and levee performance to reasonably reflect their impact on flood risks. All levees in the NLD and select dams from the NID with significant impact to flood risk will be included.](##_Ref215568526)

- [Utilization of system responses sourced from available performance data, including the most recent USACE risk assessment.](##_Ref215568526)

- [Utilization of dam and levee crest elevations from an elevation source with equivalent or higher resolution than the study terrain (Section 4).](##_Ref215568526)

- [Breach parameters consistent with the type of flood risk management feature (e.g., earthen embankment versus floodwalls for levees). Section 8 contains more detail.](##_Ref215568526)

- [Selection of modeled dam and levee resistance (trigger elevation) statistically sampled from the developed system response curves for each modeled flood year.](##_Ref215568526)

###### [<span id="_Ref208179738" class="anchor"><span id="_Toc217044418" class="anchor"></span></span>Role of US Army Corps of Engineers](##_Ref215568526) 

[USACE maintains reports and data associated with risk assessments for dams and levees within its authorities and has a key role in the management of national inventory databases for all dam and levee infrastructure. USACE personnel are staffed within the FFRD National Implementation Management Group to support basin modeling teams with identification and development of data to support incorporation of dam and levee breaches into FFRD modeling projects.](##_Ref215568526)

###### [<span id="_Toc217044419" class="anchor"></span>Phases of Breach Modeling](##_Ref215568526)

[The system response models are developed for an FFRD project in phases according to the workflows described in Section 2 of this SOP. This system response section applies to multiple phases, and high-level hydraulic modeling tasks in each phase are described below:](##_Ref215568526)

> [<u>Scoping and Data Preparation Phase</u>: This phase ensures dam and levee inventories are adequately refined to support scoping of the FFRD approach for the basin. In this phase, the team collects and inventories existing risk assessment data. The team develops a comprehensive dam modeling scope, including list of dams to incorporate in system response modeling. Levee breach locations are sited, including draft initial overtopping locations. Comprehensive naming and model linking plan is documented.](##_Ref215568526)
>
> [<u>Calibration Phase</u>: System response probability tables are developed. Levee breach locations are verified, including location of initial overtopping. The hydraulic modeler incorporates breaches to prepare for sampling that occurs in future phases. Levee breach sampling scheme is defined and documented. System response curves are developed.](##_Ref215568526)
>
> [<u>Conformance Phase</u>: Breach trigger elevations for each stochastic event in a multi-year realization are sampled within the fragility-curves cloud compute plugin. Hydraulic model and reservoir operations models are computed for each event. Frequency of breach occurrence for the simulated realization is assessed to ensure acceptable results.](##_Ref215568526)
>
> [<u>Production Phase</u>: Computation of multi-realization events. Frequency of breach occurrence over multiple realizations is assessed to ensure acceptable results.](##_Ref215568526)
>
> [<u>Reporting Phase</u>: In this phase, results from the project are compiled and delivered.](##_Ref215568526)

###### [<span id="_Toc217044420" class="anchor"></span>Software Version](##_Ref215568526)

[The breach trigger elevations for stochastic simulations are produced by the *fragility-curve-plugin*, version 1.0.5 which is part of the FFRD cloud-compute toolset that uses the provided SRP tables and breach location names as inputs.](##_Ref215568526)

###### [<span id="_Toc217044421" class="anchor"></span>National Database Refinements](##_Ref215568526)

[Levee data in the NLD and dam data in the NID is validated as part of a data refinement effort early in FFRD’s scoping and data preparation phase. This is a critical step to ensure the FFRD project is based on an accurate inventory of dam and levee infrastructure.](##_Ref215568526)

[Guidelines and processes for these data refinement activities are referred to in Section 4.3.](##_Ref215568526)

###### [<span id="_Toc217044422" class="anchor"></span>Data Provided to System Response Modelers](##_Ref215568526)

[A comprehensive shared dataset for the project is developed during the scoping and data preparation phase of the project. Scoping of dam and levee inclusion in the model, initial breach siting, and assembly of exiting risk assessment data are all primarily responsibilities of the dam and levee leads and occur during the scoping and data preparation phase concurrently with development of several key scoping deliverables.](##_Ref215568526)

[The following shared datasets also produced by the scoping and data preparation phase may be relevant to the dam and levee lead duties:](##_Ref215568526)

- [DEM: Full resolution DEM for consistent use for the entire FFRD project.](##_Ref215568526)

- [Model Linking Register](##_Ref215568526)

- [Comprehensive Naming Table.](##_Ref215568526)

- [Refined NLD inventory of levees in the basin.](##_Ref215568526)

- [Key levee data in the NLD.](##_Ref215568526)

- [Refined NLD alignment and profile data.](##_Ref215568526)

- [Levee operations manuals when available.](##_Ref215568526)

- [LCLs (first overtopping points for the levee system and/or segments provided by the hydraulic modeler during calibration phase).](##_Ref215568526)

- [Dam Scoping Table.](##_Ref215568526)

- [Refined list of NID dams for the basin, including key physical attributes.](##_Ref215568526)

- [Key dam data in the NID.](##_Ref215568526)

- [Dam operations manuals when available.](##_Ref215568526)

###### [<span id="_Toc217044423" class="anchor"></span>Comprehensive Naming Conventions](##_Ref215568526)

[The Name Table for entire modeling effort are established during the scoping and data preparation phase. A Name Table and model linking register will specify the names for dams and levee model elements according to the guidance in Job Aid 06, *Standard Naming Conventions*. System response deliveries will include references to these established names.](##_Ref215568526)

###### [<span id="_Toc217044424" class="anchor"></span>Coordination with Other Models](##_Ref215568526)

[Coordination with the hydraulic model, reservoir operations model, and cloud-compute inputs are required to successfully simulate the occurrence of dam and levee breaching in the FFRD modeling process. Some typical points of this coordination are described below.](##_Ref215568526)

[The Model Linking Register and Name Table developed during the scoping and data preparation phase of the project will guide model development. The dam and levee system response modelers and technical lead will communicate any concerns regarding model linking that may arise during the model development process with the full modeling team.](##_Ref215568526)

######## [Hydraulic Model](##_Ref215568526)

[The hydraulic model must include breachable elements (2D connections) that are unique for each location allowed to breach. In the case of levee breaches, early results from the hydraulic model will inform breach locations associated with overtopping events. Therefore, breach locations impact the hydraulic model setup and must be communicated clearly between the hydraulic modeler and the system response modelers.](##_Ref215568526)

[The breach parameters (e.g., erodibility, width, development time, etc.) are set in the hydraulic model and should coordinated between the system response modeler and hydraulic modeler. Section [8.5.9](##_Ref215569478) contains breach parameter guidelines.](##_Ref215568526)

[The names of the 2D connections must be consistent with those used to deliver the system response tables. These names will be guided by the naming table and model linking register and will require coordination between the system response modelers and the hydraulic modelers.](##_Ref215568526)

######## [Reservoir Operations Model](##_Ref215568526)

[The reservoir operations model accounts for breaches of dams within its domain by adjusting operational releases when a breach is triggered according to the simulated pool elevation. The system response modeler can review model results for events that include breach occurrences on major dams.](##_Ref215568526)

######## [*cloud-compute* Lead](##_Ref215568526)

[The system response modelers provide inputs that are directly utilized by cloud-compute plug-ins. This SOP provides templates and standard locations for data delivery for cloud-compute and review processes to avoid possible pitfalls.](##_Ref215568526)

#### [<span id="_Toc217044425" class="anchor"></span>Dam System Response Modeling](##_Ref215568526)

[The methodology for development and sampling of dam system responses in the FFRD systems model is established for the project to reflect the best available risk assessment data available for all significant dams in the basin.](##_Ref215568526)

###### [<span id="_Toc217044426" class="anchor"></span>Selection of Dams to Breach](##_Ref215568526)

[The inventory of every dam in the basin will be developed based on the NID database, and the modeling effort for each dam will be defined in the Dam Scoping Table. This table will specify which dams will be allowed to breach, following guidelines in Job Aid 01, *Scoping Processes.*](##_Ref215568526)

###### [<span id="_Toc217044427" class="anchor"></span>Dam Risk Assessment Data](##_Ref215568526)

[All existing dam risk assessment data and reports will be assembled during the scoping and data preparation phase. Processes and sources for obtaining this data is included in Job Aid 02, *Data Preparation Processes*.](##_Ref215568526)

###### [<span id="_Toc217044428" class="anchor"></span>Dam Breach Location](##_Ref215568526)

[Dam breaches for FFRD should be consolidated into a single representative breach location, which is generally considered adequate for flood risk characterization at basin scale. Unique dam configurations or other circumstances may warrant a more complex treatment of certain dams, which must be coordinated with the full project team.](##_Ref215568526)

###### [<span id="_Toc217044429" class="anchor"></span>Dam System Response Curve Development](##_Ref215568526)

[The development of SRPs will follow procedures described in Job Aid 10, *Dam System Response Development*. The SRP development process is adapted based on the type of risk assessment information available.](##_Ref215568526)

#### [<span id="_Toc217044430" class="anchor"></span>Levee System Response Modeling](##_Ref215568526)

[The methodology for incorporating levee system response into the FFRD modeling framework is established reflecting the current state of available levee data. Available information on levee performance is leveraged but will be supplemented with engineering judgment.](##_Ref215568526)

###### [<span id="_Toc217044431" class="anchor"></span>Levee Risk Assessment Data](##_Ref215568526)

[All existing levee risk assessment data and reports will be assembled during the scoping and data preparation phase. Processes and sources for obtaining this data is included in Job Aid 02, *Data Preparation Processes*.](##_Ref215568526)

###### [<span id="_Toc217044432" class="anchor"></span>Levee Breach Quantity](##_Ref215568526)

[The FFRD modeling framework assesses breaches at specific defined locations. Levee breach locations and associated system responses are developed for every levee in the NLD. The levee data team lead determines the breach quantity for each levee system. The breach quantity will be set by a combination of many factors including levee mileage, number of levee segments, and risk assessment data availability. Modeled results may be particularly sensitive to breach location and quantity for very long levee systems and/or steep terrain. Job Aid 11, *Levee Breach Workflows*, provides guidance of selection breach quantity and describes required documentation of applied judgement.](##_Ref215568526)

###### [<span id="_Toc217044433" class="anchor"></span>Levee Breach Location](##_Ref215568526)

[Once the target quantity of breaches per levee system is determined, the breaches can be located. Breach location selection is generally based on current USACE Mapping, Modeling, and Consequences (MMC) Production Center’s [Technical Manual for Levees](https://usace.dps.mil/:b:/r/sites/KMP-MMC/Shared%20Documents/MMC%20Standard%20Operating%20Procedures/FY2026/Technical%20Manuals/FY2026-MMC-Technical-Manual-for-Levees.pdf?csf=1&web=1&e=VstdR5). Locations are identified using the following prioritized considerations:](##_Ref215568526)

1.  
2.  
3.  
4.  
5.  

###### [Breach location at the incipient overtopping location, also known as the LCL. Note that selection of localized low spots is completed initially and updated throughout hydraulic modeling in the calibration phase.Documented areas of expected poor performance (e.g., based upon risk assessment).Locations of expected poor performance based on engineering judgment.Location in the upstream third of the levee system.High population or structure density areas adjacent to the levee.<span id="_Toc217044434" class="anchor"></span>Levee System Response Curve Development](##_Ref215568526)

[The development of SRPs for each levee breach location will follow procedures described in Job Aid 11, *Levee Breach Workflows*. The SRP development process is adapted based on the type of risk assessment information available.](##_Ref215568526)

#### [<span id="_Toc217044435" class="anchor"></span>System Response Curve Delivery Format](##_Ref215568526)

[The SRPs prepared for FFRD use will be provided as a 2-column table as Elevation versus Breach Probability for each breach location. Additional header information for each location that captures the structure ID (NID or NID), FFRD RAS hydraulic model unit name, RAS 2D connection name, toe elevation, crest elevation and other attributes is included. All SRPs for the full FFRD basin are provided as a single CSV formatted file that can be created using the ‘system-response’ template provided in Appendix C. Separate CSV files will be delivered for all dam SRPs and all levee SRPs.](##_Ref215568526)

[For levees, a corresponding levee breach locations geospatial file that tracks the point locations and names for each breach location along with the key attributes is also included in the delivery package.](##_Ref215568526)

#### [<span id="_Toc217044436" class="anchor"></span>Stochastic Breach Modeling](##_Ref215568526)

[Dam or levee breaches at each location are triggered for individual events in the quasi-continuous simulations when the water surface generated from the sampled storm event exceeds the sampled breach trigger elevation, which are based on provided SRP tables at each breach location. The specifics of the breach trigger sampling algorithm are described in Volume III of this SOP and cloud-compute technical documentation.](##_Ref215568526)

#### [<span id="_Toc217044437" class="anchor"></span>Hydraulic Modeling of Breaches](##_Ref215568526)

[Guidelines for hydraulic modeling of breaches are provided in Section [8.5.9](##_Ref215569478).](##_Ref215568526)

#### [<span id="_Toc217044438" class="anchor"></span>Breach Parameters](##_Ref215568526)

[The parameters determining the breach timing, development rate, and final dimensions are modeled in HEC-RAS and discussed in detail in Section 8.5.](##_Ref215568526)

#### [<span id="_Toc217044439" class="anchor"></span>Documentation of System Response Modeling](##_Ref215568526)

[A set of standard reports will be written for each phase in the FFRD project. Dam and levee data leads have the responsibility to develop the response modeling sections and appendices of the larger reports to fully document the breach modeling efforts. Appendix E contains report templates for the breach modeling reports.](##_Ref215568526)

[[Table 9.1](##_Ref206504318) summarizes key dam and levee response modeling documentation included in each of the reports.](##_Ref215568526)

[National database refinement efforts are generally not documented as part of the FFRD reports as any data refinement actions on dams and levees will be stored directly in the NID and NLD, respectively. Both databases are managed by USACE. Those actions have distinct SOPs, data management workflows, documentation, and review standards. However, listings of dams and levees within the study basin will be included in the FFRD reporting and any special project-specific adjustments, findings or feedback to the national databases will be included.](##_Ref215568526)

[<span id="_Ref206504318" class="anchor"><span id="_Toc214892786" class="anchor"></span></span>Table 9.1. Key System Response Modeling Documentation by Phase](##_Ref215568526)

| [Phase](##_Ref215568526) | [Included Documentation](##_Ref215568526) |
|----|----|
| [Scoping and Data Preparation Phase Report](##_Ref215568526) | [Identification of all dams and levees included in the FFRD study. Listing of all existing and available risk assessment data. Documentation of planned scope of dams selected to breach in FFRD study. Documentation of proposed levee breach locations.](##_Ref215568526) |
| [Calibration Phase Report](##_Ref215568526) | [Documentation of any adjustments to breach locations planned during scoping phase. Documentation of SRP development and sources. Statements regarding breach sampling scheme.](##_Ref215568526) |
| [Conformance Phase Report](##_Ref215568526) | [Documentation of resulting occurrence of breaches in the single realization. Description of any system response modeling adjustments made single realization results.](##_Ref215568526) |
| [Production Phase Report](##_Ref215568526) | [Descriptions of any hot fixes or patches required in the production phase.](##_Ref215568526) |

#### [<span id="_Toc217044440" class="anchor"></span>Dam and Levee Breach Model Review Process and Deliverables](##_Ref215568526)

[Reviews of formal deliveries are a critical part of the FFRD production process, including all aspects of system response modeling inputs. Several review steps are required to ensure the final deliveries system response deliveries form part of a modeling system that is capable of accurately depicting basin-wide flood risk. Review checklists are used to track comments related to pre-defined review prompts throughout the review process. Appendix D contains checklist templates.](##_Ref215568526)

[[Table 9.2](##_Ref216873121) summarizes for key final deliverables by each project phase for dams and levees. The following subsections describe specific review steps along with associated deliveries. ](##_Ref215568526)

[<span id="_Ref216873121" class="anchor"></span>Table 9.2.Overview of Key Dam and Levee System Response Final Deliverables by Phase](##_Ref215568526)

<table>
<colgroup>
<col style="width: 23%" />
<col style="width: 38%" />
<col style="width: 38%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;"></th>
<th><a href="##_Ref215568526">Dams</a></th>
<th><a href="##_Ref215568526">Levees</a></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Prior to or Concurrent with FFRD Scoping and Data Preparation</a></td>
<td><a href="##_Ref215568526">NID Data Refinement*</a></td>
<td><a href="##_Ref215568526">NLD Data Refinement*</a></td>
</tr>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Scoping and Data Preparation Phase</a></td>
<td><p><a href="##_Ref215568526">Document Confirmation NID Data Refinement Efforts</a></p>
<p><a href="##_Ref215568526">Dam Scoping Table (Breach Scope)</a></p>
<p><a href="##_Ref215568526">Dam Risk Assessment Data Collection</a></p></td>
<td><p><a href="##_Ref215568526">Document Confirmation NLD Data Refinement Efforts</a></p>
<p><a href="##_Ref215568526">Levee Breach Location (Initial) Geospatial file</a></p>
<p><a href="##_Ref215568526">Levee Risk Assessment Data Collection</a></p></td>
</tr>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Calibration Phase</a></td>
<td><p><a href="##_Ref215568526">Dam Breach Location Geospatial file</a></p>
<p><a href="##_Ref215568526">Dam SRPs</a></p>
<p><a href="##_Ref215568526">Documentation of SRP development</a></p></td>
<td><p><a href="##_Ref215568526">Levee Breach Location (Final) Geospatial file</a></p>
<p><a href="##_Ref215568526">Levee SRPs</a></p>
<p><a href="##_Ref215568526">Documentation of SRP development</a></p></td>
</tr>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Conformance Phase</a></td>
<td><a href="##_Ref215568526">Documentation of Breach Results and adjustments during Conformance</a></td>
<td><a href="##_Ref215568526">Documentation of Breach Results and adjustments during Conformance</a></td>
</tr>
<tr>
<td style="text-align: left;"><a href="##_Ref215568526">Production Phase</a></td>
<td><a href="##_Ref215568526">Final Reporting of Breach Results</a></td>
<td><a href="##_Ref215568526">Final Report Review</a></td>
</tr>
</tbody>
</table>

[\*Documented by others](##_Ref215568526)

###### [<span id="_Toc217044441" class="anchor"></span>Scoping and Data Preparation Phase Review](##_Ref215568526)

[The system response modeler is responsible for the following deliverables for the Scoping and Data Preparation Phase:](##_Ref215568526)

- [Confirmation of separate NID Data Refinement Efforts – As documented in Scoping and Data Preparation Report](##_Ref215568526)

- [Confirmation of separate NLD Data Refinement Efforts – As documented in Scoping and Data Preparation Report](##_Ref215568526)

- [Dam Scoping Table (Breach? Yes/No) with justifications documented in Scoping and Data Preparation Report](##_Ref215568526)

- [Dam Risk Assessment Data Collection](##_Ref215568526)

- [Levee Breach Location selection and justification documented in Scoping and Data Preparation Report](##_Ref215568526)

- [Levee Breach Location (Initial) Geospatial file – with attributes per template](##_Ref215568526)

- [Levee Risk Assessment Data Collection](##_Ref215568526)

[The Scoping and Data Preparation checklist includes charge questions related to each of these deliverables.](##_Ref215568526)

###### [<span id="_Toc217044442" class="anchor"></span>Calibration Phase Reviews](##_Ref215568526)

[System response modeling products undergo informal working review to coordinate and finalize levee breach locations leveraging hydraulic modeler inputs, and a full review of the delivered system response products for the calibration phase.](##_Ref215568526)

######## [Levee Breach Location Adjustment Informal Working Review](##_Ref215568526)

[An intermediate review consists of a hydraulic modeler review of draft breach locations intending to be sited at the LCL (i.e. initial overtopping location). Specifically, early hydraulic model results may indicate improved placement of the LCL breach location. Adjustments will be documented by updating the *Location Description and Rationale* field included in the breach location geospatial file. Note that this process may be iterative and additional updates may be made as hydraulic models are refined during the calibration phase.](##_Ref215568526)

[The *Breach Input Review Checklist* includes charge questions to verify this working review was performed.](##_Ref215568526)

######## [Review of Final Calibration Phase Deliveries](##_Ref215568526)

[The system response modeler is responsible for the following final deliverables for the Calibration Phase:](##_Ref215568526)

- [SRP tables – (template format)](##_Ref215568526)

- [SRP Calculation Worksheets to support FFRD SRP deliveries](##_Ref215568526)

- [Dam Breach Location Geospatial file - with attributes per template](##_Ref215568526)

- [Levee Breach Location (Final) Geospatial file – with attributes per template](##_Ref215568526)

- [SRP development documented in Calibration Phase Report](##_Ref215568526)

- [Breach sampling scheme discussion to be utilized in the Conformance Phase documented in the Calibration Phase Report](##_Ref215568526)

[The breach input review checklist is used to track comments and document review of these deliverables. This checklist includes charge questions related to review of SRP development computations, adjustments to earlier breach location selection, and breach sampling scheme to be utilized in the conformance phase.](##_Ref215568526)

###### [<span id="_Toc217044443" class="anchor"></span>Conformance Phase Review](##_Ref215568526)

[The conformance phase review checklist focuses on ensuring results of a full realization of synthetic events produces expected trends considering dam and levee response modeling. No separable dam or levee deliverable is provided in this phase unless updates are required. Key dam and levee response modeling areas of review focus include spatial mapping of residual risk, verification of LCL, reasonable representation of APF, and reasonable modeled breach parameters. Output from the conformance phase will be reviewed by the levee data team lead to ensure reasonable levee reliability results that are reflective of expected. See charge questions in the *Conformance Checklist*.](##_Ref215568526)

[Dam and Levee input data may be needed during the conformance phase as the team makes model adjustments to achieve conformance requirements. If the SRP data is updated, files should replace the original existing data in the standard directory location and filenames. Optionally, superseded data may be copied to an archive subdirectory.](##_Ref215568526)

###### [<span id="_Toc217044444" class="anchor"></span>Production Phase](##_Ref215568526)

[Levee sections of the report are prepared. A standardized narrative of levee input and output is prepared and QC reviewed.](##_Ref215568526)

## [<span id="_Toc217044445" class="anchor"></span>—Consequences](##_Ref215568526)

[This section outlines the process and requirements for developing and utilizing a structure inventory for FFRD modeling projects to produce. The resulting product is an estimate of average annualized losses (AAL) as well as damage frequency curves with uncertainty at each structure in the United States.](##_Ref215568526)

[The consequences categories considered are limited to direct structure and content losses. While additional consequences categories exist (such as life loss) and are capable of being computed with the hazard data generated by FFRD, they are not being deployed with the initial effort of FFRD.](##_Ref215568526)

#### [<span id="_Toc217044446" class="anchor"></span>Structure Inventory](##_Ref215568526)

[The following subsections describe guidelines for development of the structure inventory for FFRD projects.](##_Ref215568526)

###### [<span id="_Toc217044447" class="anchor"></span>Source](##_Ref215568526)

[For FFRD, this SOP outlines a process for computing consequences with the National Structure Inventory (NSI) and a standard damage function library. However, to meet a broader set of needs, the hazard data generated can be applied with a user-provided structure inventory and damage function set.](##_Ref215568526)

###### [<span id="_Toc217044448" class="anchor"></span>Schema](##_Ref215568526)

[To maintain consistency throughout the nation, the normalized schema and data types in the NSI are providing the schema and data types for FFRD. If a structure inventory with a different schema is utilized, a schema crosswalk must be created. The NSI is a public database describing structure locations as points and attribution for flood risk consequence assessment. Table 10.1 provides NSI critical attributes. Table 10.2 provides descriptions of the NSI standard occupancy types for each damage category.](##_Ref215568526)

[<span id="_Toc214892787" class="anchor"></span>Table 10.1. National Structure Inventory Required Attributes](##_Ref215568526)

| [Field Name](##_Ref215568526) | [Description](##_Ref215568526) | [Attribute Type](##_Ref215568526) |
|----|----|:--:|
| [fd_id](##_Ref215568526) | [A number that should be unique for all structures.](##_Ref215568526) | [Integer](##_Ref215568526) |
| [cbfips](##_Ref215568526) | [A census block containing the structure.](##_Ref215568526) | [String](##_Ref215568526) |
| [x](##_Ref215568526) | [X coordinate of each structure.](##_Ref215568526) | [Double](##_Ref215568526) |
| [y](##_Ref215568526) | [Y coordinate of each structure.](##_Ref215568526) | [Double](##_Ref215568526) |
| [st_damcat](##_Ref215568526) | [Damage category of the structure.](##_Ref215568526) | [String](##_Ref215568526) |
| [occtype](##_Ref215568526) | [Damage function or occupancy type of the structure.](##_Ref215568526) | [String](##_Ref215568526) |
| [val_struct](##_Ref215568526) | [Value in dollars of the structure\*](##_Ref215568526) | [Double](##_Ref215568526) |
| [val_cont](##_Ref215568526) | [Value in dollars of the contents of the structure\*](##_Ref215568526) | [Double](##_Ref215568526) |
| [found_ht](##_Ref215568526) | [Describes the foundation height of the structure in feet from the ground elevation.](##_Ref215568526) | [Double](##_Ref215568526) |
| [found_type](##_Ref215568526) | [Describes the type of foundation of the structure (C=Crawl, B=Basement, S=Slab, P=Pier, I=Pile, F=Fill, W=Solid Wall).](##_Ref215568526) | [String](##_Ref215568526) |
| [num_story](##_Ref215568526) | [The number of stories of the structure.](##_Ref215568526) | [Integer](##_Ref215568526) |

[\*In the NSI, structure value and content value are based on depreciated replacement value.](##_Ref215568526)

[<span id="_Toc214892788" class="anchor"></span>Table 10.2. Standard Occupancy Types and Descriptions (sheet 1 of 2)](##_Ref215568526)

| [Damage Category](##_Ref215568526) | [Occupancy Type](##_Ref215568526) | [Description](##_Ref215568526) |
|:--:|:--:|----|
| [Residential](##_Ref215568526) | [RES1-1SNB](##_Ref215568526) | [Single Family Residential, 1 story, no basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-1SWB](##_Ref215568526) | [Single Family Residential, 1 story, with basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-2SNB](##_Ref215568526) | [Single Family Residential, 2 story, no basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-2SWB](##_Ref215568526) | [Single Family Residential, 2 story, with basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-3SNB](##_Ref215568526) | [Single Family Residential, 3 story, no basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-3SWB](##_Ref215568526) | [Single Family Residential, 3 story, with basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-SLNB](##_Ref215568526) | [Single Family Residential, split-level, no basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES1-SLWB](##_Ref215568526) | [Single Family Residential, split-level, with basement](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES2](##_Ref215568526) | [Manufactured Home](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES3A](##_Ref215568526) | [Multi-Family housing 2 units](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES3B](##_Ref215568526) | [Multi-Family housing 3-4 units](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES3C](##_Ref215568526) | [Multi-Family housing 5-10 units](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES3D](##_Ref215568526) | [Multi-Family housing 10-19 units](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES3E](##_Ref215568526) | [Multi-Family housing 20-50 units](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES3F](##_Ref215568526) | [Multi-Family housing 50 plus units](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES4](##_Ref215568526) | [Average Hotel](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES5](##_Ref215568526) | [Institutional Dormitories](##_Ref215568526) |
| [Residential](##_Ref215568526) | [RES6](##_Ref215568526) | [Nursing Home](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM1](##_Ref215568526) | [Average Retail](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM2](##_Ref215568526) | [Average Wholesale](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM3](##_Ref215568526) | [Average Personal and Repair Services](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM4](##_Ref215568526) | [Average Professional Technical Services](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM5](##_Ref215568526) | [Bank](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM6](##_Ref215568526) | [Hospital](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM7](##_Ref215568526) | [Average Medical Office](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM8](##_Ref215568526) | [Average Entertainment/Recreation](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM9](##_Ref215568526) | [Average Theater](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [COM10](##_Ref215568526) | [Garage](##_Ref215568526) |
| [Industrial](##_Ref215568526) | [IND1](##_Ref215568526) | [Average Heavy Industrial](##_Ref215568526) |
| [Industrial](##_Ref215568526) | [IND2](##_Ref215568526) | [Average Light Industrial](##_Ref215568526) |
| [Industrial](##_Ref215568526) | [IND3](##_Ref215568526) | [Average Food/Drug/Chemical](##_Ref215568526) |
| [Industrial](##_Ref215568526) | [IND4](##_Ref215568526) | [Average Metals/Minerals processing](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 10.2. Standard Occupancy Types and Descriptions (sheet 2 of 2)](##_Ref215568526)

| [Damage Category](##_Ref215568526) | [Occupancy Type](##_Ref215568526) | [Description](##_Ref215568526) |
|:--:|:--:|----|
| [Industrial](##_Ref215568526) | [IND5](##_Ref215568526) | [Average High Technology](##_Ref215568526) |
| [Industrial](##_Ref215568526) | [IND6](##_Ref215568526) | [Average Construction](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [AGR1](##_Ref215568526) | [Average Agricultural](##_Ref215568526) |
| [Commercial](##_Ref215568526) | [REL1](##_Ref215568526) | [Church](##_Ref215568526) |
| [Public](##_Ref215568526) | [GOV1](##_Ref215568526) | [Average Government Services](##_Ref215568526) |
| [Public](##_Ref215568526) | [GOV2](##_Ref215568526) | [Average Emergency Response](##_Ref215568526) |

###### [<span id="_Toc217044449" class="anchor"></span>Scales](##_Ref215568526)

[Structure inventory data is generated for the entire project area and broken out into individual inventories for each hydraulic modeling unit.](##_Ref215568526)

###### [<span id="_Toc217044450" class="anchor"></span>Base Inventory](##_Ref215568526)

[During the scoping and data preparation phase, the consequences team member will prepare the base structure inventories and post them to the *basin-data/structure-inventory* directory following guidance provide in Job Aid 17, *Consequence Processes.*](##_Ref215568526)

###### [<span id="_Toc217044451" class="anchor"></span>Structure Inventory Adjustments](##_Ref215568526)

[Leveraging the structure inventory through the process of hydraulic calibration can improve both the hydraulic models and the structure inventory. For details on methods to identify hydraulic modeling and structure placement issues see Job Aid 17, *Consequence Processes*.](##_Ref215568526)

[During the calibration phase, steps are performed by both the hydraulic modeling team members and the consequences team members. Hydraulic modeling team members utilize the structure inventory to identify potential issues with the hydraulic model prior as part of the model development and calibration process. When the hydraulic model is submitted for review, the hydraulic results from multiple historic events will be available. The consequences team member will review the hydraulic model output and documents the review using the consequences checklist. The review checklists for both the hydraulic model and consequence model include specific items that focus on ensuring the structure placement is checked. Any structure placement issues will be resolved by the consequences team and an updated structure inventory will be uploaded to Model Library as directed in Job Aid 17, *Consequence Processes*.](##_Ref215568526)

[During the conformance phase, consequences are computed over a long-term realization using the hydraulic models and structure inventories that have already been refined during the calibration phase. The ability to view simulated depth-frequency or damage-frequency results is likely highlight additional hydraulic modeling, levee fragility, or structure placement issues. The conformance review checklist includes items to document the review consequences results to ensure acceptable results. Additional adjustments to the models and structure inventory will be made to address any issues identified. Details on methods to identify issues during the conformance phase are included in Job Aid 17, *Consequence Processes*.](##_Ref215568526)

#### [<span id="_Toc217044452" class="anchor"></span>Damage Functions](##_Ref215568526)

[The damage functions for each structure are selected based on the characteristics of the hazard, the occupancy type, and the foundation type.](##_Ref215568526)

[Within the consequences folder for the appropriate phase, the damage functions JSON file defines the damage functions utilized in the consequences compute. This SOP leverages the FEMA inland damage functions for appropriate residential occupancy types (*reference*) and USACE standardized damage functions (USACE) for all other occupancy types. Damages computed via this SOP will be based solely on depth at structures based on FEMA guidance. This methodology is embedded in the *compute-multi-frequency-mean-stdev-single-parameter* action of the consequences-runner plug-in in the cloud-compute toolset.](##_Ref215568526)

[Computing with multi-parameter functions requires event-based calculations, which are not being pursued with this version of the SOP per FEMA guidance.](##_Ref215568526)

#### [<span id="_Toc217044453" class="anchor"></span>Consequence Results Computation](##_Ref215568526)

[During the conformance phase, deterministic depths and damages at each structure for a range of frequency ordinates are computed, and a single value for EAD is computed by integration of the damage-frequency relationship.](##_Ref215568526)

[During the production phase, multiple realizations provide a mean and standard deviation of depth at each structure at each frequency ordinate. Mean damages and mean EAD are computed based on the mean depth at each structure. The uncertainty in consequences at each structure is represented by sampling various depth-frequency curves based on the standard deviation of depth at each ordinate, and computing damages and EAD. The uncertainty in the structure inventory in terms of foundation heights or other uncertain parameters are not directly considered.<span id="_Toc214891705" class="anchor"></span>\
](##_Ref215568526)

[Figure 10.1. Conceptual Diagram of Consequence Computation Method](##_Ref215568526)

[<img src="media/image16.png" style="width:6.5in;height:3.89861in" />](##_Ref215568526)

[Consequences are aggregated for relevant geographical units such as the full study basin, individual model units, political boundaries, and leveed areas for the purposes of summary reporting.](##_Ref215568526)

[Additional details regarding workflow steps to compute and summarize consequences for the project are included in Job Aid 17, *Consequence Processes*.](##_Ref215568526)

[Future improvements to this SOP will consider computing damages for each event to allow for implementation of multi-parameter damage functions in a defensible way and to provide a more accurate and robust characterization of uncertainty. Incorporation of uncertainty in the structure inventory will also be considered.](##_Ref215568526)

#### [<span id="_Toc217044454" class="anchor"></span>Documentation of Consequences Modeling](##_Ref215568526)

[A set of standard reports will be written for each phase in the FFRD project. Consequence team members have the responsibility to develop the consequence sections and appendices of the larger reports to fully document the consequence modeling efforts. Appendix B contains report templates for the consequence modeling reports.](##_Ref215568526)

[Table 10.3 summarizes locations of key consequences modeling documentation included in each of the reports.\
](##_Ref215568526)

[<span id="_Toc214892790" class="anchor"></span>Table 10.3. Locations of Key Consequences Modeling Documentation](##_Ref215568526)

| [Scoping and Data Preparation Phase Report](##_Ref215568526) | [Documentation of structure inventory source and delivery.](##_Ref215568526) |
|:---|----|
| [Calibration Phase Report](##_Ref215568526) | [Primary documentation of structure placement adjustments during calibration. Individual appendices for each model-unit.](##_Ref215568526) |
| [Conformance Phase Report](##_Ref215568526) | [Description of all structure inventory adjustments made based on frequency-based results.](##_Ref215568526) |
| [Production Phase Report](##_Ref215568526) | [Descriptions of any hot fixes or patches required in the production phase.](##_Ref215568526) |

#### [<span id="_Toc217044455" class="anchor"></span>Consequences Review Process and Deliverables](##_Ref215568526)

[Consequence reviews are fully closed out at the end of each study phase. The consequence reviewer and the consequence modeler should ensure that documentation and intermediate products are uploaded to the Model Library and that they follow the processes included in this SOP and the *Consequence Processes* job aid. The consequence checklist list will provide review documentation. The checklist templates provide major items for the consequence review.](##_Ref215568526)

###### [<span id="_Toc217044456" class="anchor"></span>Review of Scoping and Data Preparation Review](##_Ref215568526)

[Delivery of structure inventories will be performed as described in Section 4 and Job Aid 17, *Consequence Processes*, and review of those products are required. This review will be documented in specific items of the data preparation review checklist. This shared checklist for the overall phase requires multiple reviewers as described in Section 4.](##_Ref215568526)

###### [<span id="_Toc217044457" class="anchor"></span>Calibration Phase Quality Control Review](##_Ref215568526)

[The calibration phase consequence efforts will be reviewed using the consequences review checklist. The deliverables to initiate this review will be posted to Model Library *calibration* Directory and are listed below:](##_Ref215568526)

- 
- - 
- 

[Adjusted calibration phase structure inventories. Posted to *calibration/consequences* directoryCompletion of documentation of all calibration phase consequence efforts in report sections and appendices.Final calibration Phase reporting will be posted the *documentation/reports/2-calibration-phase* directoryReview checklist with modeler comments and assumptions fields populated.The review checklist will be backchecked by the original review to close each item. The final review checklist will be posted to *documentation/reviews* to complete the delivery.](##_Ref215568526)

###### [<span id="_Toc217044458" class="anchor"></span>Conformance Phase Review](##_Ref215568526)

[This review of conformance phase consequence modeling efforts will be documented in specific items of the data preparation review checklist. This shared checklist for the overall phase requires multiple reviewers.](##_Ref215568526)

[The consequence modeling deliverables for this review will are listed below:](##_Ref215568526)

- 
- - 
- 

[Adjusted calibration phase structure inventories. Posted to *calibration/conformance* directoryCompletion of documentation of all conformance phase consequence efforts in report sections and appendices.Final conformance phase reporting will be posted the *documentation/reports/3-conformance-phase* directoryReview checklist with modeler comments and assumptions fields populated for consequence items.The review checklist will be backchecked by the original review to close each item. The final review checklist will be posted to *documentation/reviews* to complete the delivery.](##_Ref215568526)

[<span id="_Toc217044459" class="anchor"></span>—Stochastic Simulation\
Structure](##_Ref215568526)
=======================================================================

[This section outlines the stochastic simulation structure and related concepts used to generate FFRD results. The simulation structure described provides the means to produce graduated hazard and risk estimates across the entire study domain including direct quantification of uncertainty that preserves the underlying correlations of all variables.](##_Ref215568526)

[Simulations produced following this guidance will have the following characteristics:](##_Ref215568526)

- [Quasi-continuous realization within a nested Monte Carlo simulation driven by meteorological events generated through SST](##_Ref215568526)

- [Leverage hydrologic model, reservoir operations model, and hydraulic models that are independently calibrated to historic events](##_Ref215568526)

- [Account for possible breaching of dam and levee infrastructure](##_Ref215568526)

- [Provide both pluvial and fluvial flood hazard data across the range of natural variability from the 1/10 to the 1/2,000 AEP.](##_Ref215568526)

- [Account for natural variability and model uncertainties in terms of storm events, antecedent conditions, breaching, model parameters, and structure inventories.](##_Ref215568526)

- [Quantify uncertainty in hazard and risk](##_Ref215568526)

- [Capable of being leveraged for production of simulations of alternative scenarios or other studies.](##_Ref215568526)

#### [<span id="_Toc217044460" class="anchor"></span>Use of Cloud Compute Toolset](##_Ref215568526)

[The FFRD cloud compute toolset has been developed to support the production of hazard and risk products in alignment with this SOP. Maintained as an open-source project by USACE, the toolset allows contributions to future enhancements through its source-controlled repository. The sections below provide an overview of use of these tools for FFRD projects.](##_Ref215568526)

###### [<span id="_Toc217044461" class="anchor"></span>Containerized Plugins](##_Ref215568526)

[The FFRD simulations require the use of cloud-based plugins that have been developed specifically to support the simulation structures described in this SOP. Each plugin is developed in its own container. A container is a tidy package that provides everything necessary to run a program, the executable code, the operating system, and any necessary dependencies.](##_Ref215568526)

[The tables below provide an overview of the role and purpose of each plugin and the specific actions within the plugins that are needed for execution of this SOP.](##_Ref215568526)

[Detailed documentation for the use of these plugins for FFRD is included in their [source control repositories](https://github.com/orgs/USACE-Cloud-Compute/).](##_Ref215568526)

[An overview of the function and use of the cloud compute toolset and information necessary for contributions to the open source project are included in [technical documentation](https://www.hec.usace.army.mil/confluence/cloud-compute/).\
](##_Ref215568526)

[<span id="_Toc214892791" class="anchor"></span>Table 11.1. Future of Flood Risk Data Cloud Compute Containerized Plugins—Purpose and Version](##_Ref215568526)

| [Plugin](##_Ref215568526) | [Role and Purpose](##_Ref215568526) | [Version](##_Ref215568526) |
|----|----|----|
| [\**open-source tools outside of cloud-compute*](##_Ref215568526) | [Generates storm catalogs](##_Ref215568526) | [n/a](##_Ref215568526) |
| [seed-generator](##_Ref215568526) | [Generates blocks and seeds](##_Ref215568526) | [1.05](##_Ref215568526) |
| [fragility-curve-plugin](##_Ref215568526) | [Samples system response curves to set breach trigger elevations](##_Ref215568526) | [1.05](##_Ref215568526) |
| [hms-mutator](##_Ref215568526) | [Generates storm placements, samples storms, storm dates, and antecedent conditions, prepares information for the hms-runner to use to compute excess precipitation](##_Ref215568526) | [1.01](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [Utilizes a table of storm information and an HEC-HMS model to run the storm placements and produce excess precipitation](##_Ref215568526) | [TBD](##_Ref215568526) |
| [ressim-runner](##_Ref215568526) | [Computes regulated outflows for a watershed based on unregulated inflows generated by an upstream model](##_Ref215568526) | [TBD](##_Ref215568526) |
| [ras-runner](##_Ref215568526) | [Computes river hydraulics passes inflow from upstream HEC-RAS models into downstream HEC-RAS models performs dam and levee breaching](##_Ref215568526) | [TBD](##_Ref215568526) |
| [ras-post-processor](##_Ref215568526) | [Generates depth, velocity, and water surface grids using HEC-RAS mapping algorithms](##_Ref215568526) | [TBD](##_Ref215568526) |
| [Aggregator](##_Ref215568526) | [Aggregates maximum hazard grids based on all events within a synthetic year, creates AEP grids, creates recurrence interval hazard grids.](##_Ref215568526) | [TBD](##_Ref215568526) |
| [consequence-runner](##_Ref215568526) | [Computes consequences](##_Ref215568526) | [TBD](##_Ref215568526) |

[\
](##_Ref215568526)

[<span id="_Toc214892792" class="anchor"></span>Table 11.2. Descriptions of Specific Actions Utilized within Plugins (sheet 1 of 2)](##_Ref215568526)

| [Plugin](##_Ref215568526) | [Action](##_Ref215568526) | [Description](##_Ref215568526) |
|----|----|----|
| [\**open source tools outside of cloud-compute*](##_Ref215568526) | [generate-storm-catalog](##_Ref215568526) | [Generates a storm catalog from a watershed boundary and transposition domain.](##_Ref215568526) |
| [seed-generator](##_Ref215568526) | [block-generation-fixed-length](##_Ref215568526) | [Generates a table of associations of realizations, synthetic years, and events](##_Ref215568526) |
| [seed-generator](##_Ref215568526) | [block-all-seed-generation](##_Ref215568526) | [Generates a table of realization, synthetic year, and event seeds for all models.](##_Ref215568526) |
| [fragility-curve-plugin](##_Ref215568526) | [all-samples](##_Ref215568526) | [Generates a set of event level breach trigger elevations (and a consolidated table of all failure elevations for all events in a simulation) for all breach locations in a watershed.](##_Ref215568526) |
| [hms-mutator](##_Ref215568526) | [valid-stratified-locations](##_Ref215568526) | [Generates a set of all possible storm locations for each storm in a catalog.](##_Ref215568526) |
| [hms-mutator](##_Ref215568526) | [full-simulation-sst](##_Ref215568526) | [Generates a table of event number, storm name, storm date, basin conditions file, and storm location.](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [compute_simulation_all\_ placements_given_storm](##_Ref215568526) | [Computes all placements for a given storm in the catalog given the input table generated by hms-mutator full-simulation-sst.](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [dss_to_hdf](##_Ref215568526) | [Allows linking a .dss file to an .hdf file for transferring baseflows from .dss into boundary condition line inputs in .hdf.](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [dss_to_hdf_tsout](##_Ref215568526) | [Allows linking a .dss file to an .hdf file for transferring regulated outflows into a structure table in .hdf.](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [dss_to_hdf_observations](##_Ref215568526) | [Allows linking a .dss file to observed flows in .hdf.](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [dss_to_hdf_pool\_ elevations](##_Ref215568526) | [Allows linking .dss pool elevations to initial condition point elevations in .hdf.](##_Ref215568526) |
| [hms-runner](##_Ref215568526) | [copy_precip_table](##_Ref215568526) | [Allows linking excess precipitation exported by HEC-HMS into HEC-RAS .hdf format.](##_Ref215568526) |
| [ressim-runner](##_Ref215568526) | [update_timewindow\_ from_dss](##_Ref215568526) | [Updates a HEC-ResSim .simperiod file based on the input timeseries from HEC-HMS.](##_Ref215568526) |
| [ressim-runner](##_Ref215568526) | [dss_to_dss](##_Ref215568526) | [Takes flows from HEC-HMS and maps them to inflows in HEC-ResSim.](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 11.2. Descriptions of Specific Actions Utilized within Plugins (sheet 2 of 2)](##_Ref215568526)

| [Plugin](##_Ref215568526) | [Action](##_Ref215568526) | [Description](##_Ref215568526) |
|----|----|----|
| [ressim-runner](##_Ref215568526) | [compute_simulation](##_Ref215568526) | [Computes a HEC-ResSim simulation.](##_Ref215568526) |
| [ressim-runner](##_Ref215568526) | [post_peaks](##_Ref215568526) | [Aggregates peaks to a CSV for each event to allow for more simplified combination of peak data post simulation.](##_Ref215568526) |
| [RAS Runner](##_Ref215568526) | [ras-extract](##_Ref215568526) | [Supports abstract extraction of HEC-RAS .hdf data to any supported storage method.](##_Ref215568526) |
| [RAS Runner](##_Ref215568526) | [refline-to-bc](##_Ref215568526) | [Takes a reference line outflow from an upstream model as inflow into a downstream HEC-RAS model as a boundary condition line.](##_Ref215568526) |
| [RAS Runner](##_Ref215568526) | [update-breach-data](##_Ref215568526) | [Updates breach trigger elevations from samples provided by the fragility curve plugin.](##_Ref215568526) |
| [RAS Runner](##_Ref215568526) | [update-outlets-data](##_Ref215568526) | [Updates the HEC-RAS .b file, which is the actual source HEC-RAS uses for regulated outflow overrides of structures.](##_Ref215568526) |
| [RAS Runner](##_Ref215568526) | [unsteady-simulation](##_Ref215568526) | [Performs an unsteady compute.](##_Ref215568526) |
| [Aggregator](##_Ref215568526) | [Frequency Grid Generation (local/AWS)](##_Ref215568526) | [Generates recurrence interval specific hazard grids.](##_Ref215568526) |
| [Aggregator](##_Ref215568526) | [Mean/StDev Grid Generation](##_Ref215568526) | [Creates mean and standard deviation grids for AEP or recurrence interval hazard grids.](##_Ref215568526) |
| [Aggregator](##_Ref215568526) | [Raster Debug](##_Ref215568526) | [Supports large scale debugging of gridded data.](##_Ref215568526) |
| [consequences-runner](##_Ref215568526) | [compute-fema-frequency](##_Ref215568526) | [Computes consequences for a set of mean and standard deviation recurrence interval hazard grids.](##_Ref215568526) |

###### [<span id="_Toc217044462" class="anchor"></span>Manifests](##_Ref215568526)

[All cloud-compute compute jobs require a manifest that contains instructions for the cloud compute plugin. Specific manifests required for FFRD cloud computes are specified in Section 12 of this SOP, and additional workflows related to producing and ensuring accuracy of the manifests in included in Job Aid 14, *Cloud Compute Workflow*.](##_Ref215568526)

###### [<span id="_Toc217044463" class="anchor"></span>Cloud Compute Environment Support](##_Ref215568526)

[Support for applying cloud compute tools will be available from the FFRD National Implementation Group staffed by USACE, as described in Section 2 of this SOP.](##_Ref215568526)

#### [<span id="_Toc217044464" class="anchor"></span>Simulation Statistical Approach](##_Ref215568526)

[In order to support a nested Monte Carlo simulation containing quasi-continuous events, the following terminology is used to describe the simulation structure.](##_Ref215568526)

- [**Event**—An event represents a unique set of parameters derived from antecedent conditions, storm selection and placement, and sampled breach elevations for infrastructure with the capability of breaching. Simulations generally span a time window allowing the sampled precipitation to cycle through the watershed (i.e., time of concentration).](##_Ref215568526)

- [**Synthetic Year**—A synthetic year is composed of a set of independent events and is used to determine the annual maximum values for any variable of interest at any location in the watershed. The construction of the storm database determines the number of events randomly selected. The term quasi-continuous is used to describe the independence of the events in that each simulated event does not persist state across events.](##_Ref215568526)

- [**Realization**—A realization is composed of a set of synthetic years and is used to construct an estimate of a variable-frequency relationship.](##_Ref215568526)

- [**Simulation**—A simulation is composed of a set of realizations and is used to describe the knowledge uncertainty around a variable-frequency relationship.](##_Ref215568526)

[[Figure 11.1](##_Ref207109407) illustrates the relationships of the elements within the simulation structure. Realizations are represented as boxes within a simulation, synthetic years are represented by boxes within a realization, and events are represented as boxes within a synthetic year. [Figure 11.2](##_Ref207109887) through [Figure 11.4](##_Ref207109897) display example outputs for single events, single realizations, and a full simulation. Section [11.6](##_Ref215570947) provides additional full inventory of the standard output products provided for an FFRD study.<span id="_Ref207109407" class="anchor"><span id="_Toc214891706" class="anchor"></span></span>\
](##_Ref215568526)

[Figure 11.1. Relationship of Defined Terms with the Simulation Structure](##_Ref215568526)

[<img src="media/image17.png" style="width:6.5in;height:7.52362in" />\
](##_Ref215568526)

[<span id="_Ref207109887" class="anchor"><span id="_Toc214891707" class="anchor"></span></span>Figure 11.2. Example Depth of Inundation Mapped Result from a Single Event](##_Ref215568526)

[<img src="media/image18.png" style="width:6.5in;height:5.68958in" alt="Map AI-generated content may be incorrect." />\
](##_Ref215568526)

[<span id="_Toc214891708" class="anchor"></span>Figure 11.3. Example Annual Probability of Inundation (Depth Greater than Zero) for a Single Realization](##_Ref215568526)

[<img src="media/image19.png" style="width:6.5in;height:5.6937in" alt="Map AI-generated content may be incorrect." />\
](##_Ref215568526)

[<span id="_Ref207109897" class="anchor"><span id="_Toc214891709" class="anchor"></span></span>Figure 11.4. Example Computed Variable-Frequency Relationship for Simulation Containing Multiple Realizations](##_Ref215568526)

[<img src="media/image20.png" style="width:6.5in;height:4.18125in" alt="Chart AI-generated content may be incorrect." />](##_Ref215568526)

#### [<span id="_Toc217044465" class="anchor"></span>Sampled Parameters Definition](##_Ref215568526)

[The simulation structure described in 11.1.3 defines the terms realization and event. Within the simulation structure, the representation of uncertainty can be separated into two distinct sources—natural variability and knowledge uncertainty. Natural variability represents the fact that some things vary naturally. Knowledge uncertainty represents the fact there exists limited understanding. Natural variabilities are sampled with each simulated event. Within the simulation structure, knowledge uncertainties are sampled once per realization.](##_Ref215568526)

[[Table 11.3](##_Ref207109756) lists sampled parameters and their representation as natural variability or knowledge uncertainty within the simulation structure.\
](##_Ref215568526)

[<span id="_Ref207109756" class="anchor"><span id="_Toc214892794" class="anchor"></span></span>Table 11.3. Parameters and Uncertainty Types](##_Ref215568526)

| [Parameter](##_Ref215568526) | [Representation](##_Ref215568526) |
|----|----|
| [Storm Selection](##_Ref215568526) | [Natural Variability](##_Ref215568526) |
| [Storm Location](##_Ref215568526) | [Natural Variability](##_Ref215568526) |
| [Hydrologic Parameters (e.g. time of concentration, storage coefficient, constant loss, etc.)](##_Ref215568526) | [Knowledge Uncertainty](##_Ref215568526) |
| [Antecedent Conditions (e.g. starting pool, basin wetness, SWE, etc.)](##_Ref215568526) | [Natural Variability](##_Ref215568526) |
| [Breach Trigger Elevation](##_Ref215568526) | [Natural Variability](##_Ref215568526) |
| [Synthetic Event Year Count](##_Ref215568526) | [Knowledge Uncertainty](##_Ref215568526) |
| [Realization Count](##_Ref215568526) | [Knowledge Uncertainty](##_Ref215568526) |
| [Model Error](##_Ref215568526) | [Knowledge Uncertainty](##_Ref215568526) |

[\*Table not fully elaborated (December 2025)](##_Ref215568526)

[To provide consistency throughout the simulation of an event, parameters used by more than one model are sampled prior to computation of either model and used by both (e.g., starting pool elevation is sampled prior to hydrology, reservoir operations, and hydraulic modeling and the same value is used by all).](##_Ref215568526)

#### [<span id="_Toc217044466" class="anchor"></span>Event Sampling Procedure](##_Ref215568526)

[The sections below provide an overview of the procedures for sampling an individual event.](##_Ref215568526)

###### [<span id="_Toc217044467" class="anchor"></span>Products for Sampling Setup](##_Ref215568526)

[The products below are established prior to event sampling and are directly applied the sampling procedure for a single event.](##_Ref215568526)

######## [Storm Catalog](##_Ref215568526)

[Full set of observed storms in the homogenous transposition domain are assembled into a catalog and classified with the storm type as described in Section 5, which is used as the basis for storm selection.](##_Ref215568526)

######## [Storm Type Seasonal Distribution](##_Ref215568526)

[The storm type seasonality analysis describes the daily frequency of occurrence for each storm type based on the start date of the events in the storm catalog as described in Section 5.](##_Ref215568526)

######## [Valid Hydrologic Model Parameter Sets](##_Ref215568526)

[For each historic event used for calibration, a unique valid set of model parameters is developed as described in Section 6, which provides the basis for parameter uncertainty.](##_Ref215568526)

######## [Period of Record Hydrologic Model](##_Ref215568526)

[A POR hydrologic model is calibrated as described in Section 6, which provides daily basin conditions.](##_Ref215568526)

######## [Valid Combinations of Hydrologic Model Parameter Sets and Antecedent Conditions](##_Ref215568526)

[Model files representing a full set of possible combinations of antecedent basin conditions and hydrologic parameter sets is developed as part of the process to deliver the model for cloud-compute according to the procedure described in Job Aid 13, *Model Delivery for Cloud Compute*.](##_Ref215568526)

######## [External Boundary Condition Time Series](##_Ref215568526)

[If external boundary conditions are being used to represent a related and/or linked (i.e., upstream/downstream) watershed in concert with meteorologic boundary conditions provided by SST, homogenous time series representing the variable(s) of interest must also be assembled. These homogenous time series must span the same time period as the Storm Catalog and can be generated using observed data, POR hydrologic model outputs, or a combination of the two sources. A list of observed data, prepared datasets, and descriptions that is provided upon completion of the scoping and data preparation phase is contained within Section 4. Hydrologic model POR results are described in Section 6.](##_Ref215568526)

######## [Dam and Levee System Response Curves](##_Ref215568526)

[Probability of breach as a function of the loading experienced at each possible breach location is developed as described in Section 9, which provides the basis for selection of breach trigger elevations.](##_Ref215568526)

###### [<span id="_Toc217044468" class="anchor"></span>Event Sampling](##_Ref215568526)

[Utilizing all products required for sampling setup, the steps in this subsection are followed.](##_Ref215568526)

######## [Storm Selection](##_Ref215568526)

[Select a storm from the storm catalog with uniform probability and maintain the storm type from the selected storm.](##_Ref215568526)

######## [Storm Placement](##_Ref215568526)

[The *x* and *y* location for the selected storm is selected randomly within constraints.](##_Ref215568526)

[Storm placements are based on the selected storm name from pre-generated fishnets. The pre-generated fishnets are generated using the transposition domain, original storm centering, and watershed domain. A uniform mesh of points at 4-kilometer spacing was created from the transposition domain, each storm placement within the transposition domain is used to shift the watershed boundary and determine if the watershed boundary contains area outside of the transposition domain. If it does not contain area outside the transposition domain, the placement location is determined to be valid (having no null precipitation in the storm over the watershed) and the point is recorded into the fishnet. Each storm has a list of valid storm placements spaced at 4-kilometer spacing that are equiprobable for selection. Once a storm is selected, the fishnet is read in, and a random *xy* is selected for the storm placement. Each event gets a randomly selected placement from the fishnet for a given storm.](##_Ref215568526)

######## [Antecedent Condition and Hydrologic Parameter Set Selection](##_Ref215568526)

[The day of year of the storm is selected based on a sample that maintains relative occurrence of the storm types for each season. The year of the storm is selected from a uniform distribution of all years in the POR. Antecedent conditions are then selected to match the sampled day and year of the sampled storm. The hydrologic model parameters are selected from the six valid parameter sets (one set for each of the historic events utilized during the model calibration phase).](##_Ref215568526)

[When snowmelt is included, the observed temperature grids for the sampled event date are utilized without any transposition.](##_Ref215568526)

######## [External Boundary Condition Selection](##_Ref215568526)

[If external boundary conditions are being used to represent a related and/or linked watershed, homogenous time series are sampled for the locations and variables of interest using the sampled day and year of the sampled storm.](##_Ref215568526)

###### [<span id="_Toc217044469" class="anchor"></span>Breach Trigger Elevations](##_Ref215568526)

[The breach trigger elevations are sampled for the event according to the methods described in Section 9. Breaches will occur for events whenever loads at the breach locations exceed the sampled trigger elevation.](##_Ref215568526)

###### [<span id="_Toc217044470" class="anchor"></span>Hydrology and Hydraulics Model Execution](##_Ref215568526)

[The hydrologic, reservoir operations and hydraulic models are then computed for the event. Consistent antecedent conditions are maintained across each model, although some simplifications are made. The event starting reservoir pool elevation is maintained for dams (according to the Dam Modeling Scope document developed during the scoping phase of the project).](##_Ref215568526)

[For the current version of the SOP, uncertainty in hydraulic model parameters and initial basin wetness has not been incorporated. Future versions of the SOP may consider incorporation of these additional uncertainties.](##_Ref215568526)

###### [<span id="_Toc217044471" class="anchor"></span>Event Hazard Grids](##_Ref215568526)

[After model execution, hazard maps are generated on an event-by-event basis. Note that output grids are generated at a resolution lower than the highest quality source DEM (see Section 3.5 for standards).](##_Ref215568526)

###### [Hydraulic model output for a wide range of parameters can be represented as gridded data. For FFRD, the standard saved gridded hazard variables are depth and velocity. <span id="_Toc217044472" class="anchor"></span>Consequence Computation](##_Ref215568526)

[For the current version of this SOP, consequences are not calculated on an event-by-event basis and, therefore, sampling of the structure inventory parameters and execution of the consequence are not included here. For future versions of the SOP, adjustments to the consequence computation method may be considered.](##_Ref215568526)

#### [<span id="_Toc217044473" class="anchor"></span>Enumeration of Events](##_Ref215568526)

[Section 4.3 states the number of synthetic years, events per year, and realizations for an FFRD study under this SOP.](##_Ref215568526)

#### [<span id="_Ref215570947" class="anchor"><span id="_Toc217044474" class="anchor"></span></span>Delivery of Results](##_Ref215568526)

[The use of the FFRD directory structure and the cloud-compute plug-in toolset facilitates a standard and transparent structure of study inputs, indexes, and output results. The use of the standard directory structure is included in Job Aid 13, *Model Library Use for FFRD*.](##_Ref215568526)

[Subsections [11.6.1](##_Ref215571609) through [11.6.3](##_Ref215571635) describe results produced for individual event and simulation summary output.](##_Ref215568526)

###### [<span id="_Ref215571609" class="anchor"><span id="_Toc217044475" class="anchor"></span></span>Source Models and Index Directories](##_Ref215568526)

[Subsections [11.6.1.1](##_Ref215571671) through [11.6.1.6](##_Ref215571684) provide information on source tracking of models and tracking of the boundary conditions applied to the models for each computed event.](##_Ref215568526)

######## [<span id="_Ref215571671" class="anchor"></span>Source Models](##_Ref215568526)

[Source model files used for computation of the events are stored in directories above the simulations directory, which includes model results (*/hydrology*, */reservoir-operations*, */system-response*, and */hydraulics*).](##_Ref215568526)

######## [Linking Information](##_Ref215568526)

[The *linking-info* directory includes model linking information.](##_Ref215568526)

######## [Manifests](##_Ref215568526)

[A *manifests* directory contains information used for sending compute jobs via cloud-compute plugins.](##_Ref215568526)

######## [Seeds](##_Ref215568526)

[A *seeds* directory stores randomly generated seeds for each plugin that consumes random numbers (i.e., *seeds.json*).](##_Ref215568526)

######## [Event, Synthetic Year, and Realization Index](##_Ref215568526)

[A *blocks.json* is stored in the root of the */simulations* directory and provides an index of all sampled events and their relationship to synthetic years and realizations within the simulation.](##_Ref215568526)

######## [<span id="_Ref215571684" class="anchor"></span>Annual Maximum Contributing Events](##_Ref215568526)

[A *ams-contributing-events.csv* list of events that contributed to the annual maximum hazards and were computed through the hydraulic model is saved to */simulations*.](##_Ref215568526)

###### [<span id="_Toc217044476" class="anchor"></span>Individual Event Output](##_Ref215568526)

[Stored output data for each sampled event is saved to the *simulations/event-data/\[event-no\]* directory, which includes the specific outputs described in subsections [11.6.2.1](##_Ref215571702) through [11.6.2.6](##_Ref215571717).](##_Ref215568526)

######## [<span id="_Ref215571702" class="anchor"></span>Hydrology](##_Ref215568526)

[A *hydrology* directory contains the input to the hydrology model (i.e., data/storm.dss, .met, .grid, .basin, and .control files), the hydrology output (i.e., .dss), and the .tmp.hdf file for each hydraulic model containing the excess precipitation and base flow from the hydrology run.](##_Ref215568526)

######## [Reservoir Operations](##_Ref215568526)

[A *reservoir-operations* directory contains the output from the reservoir operations model (i.e., .dss file).](##_Ref215568526)

######## [System Response](##_Ref215568526) 

[A *system-response* directory stores randomly generated breach elevations for each breachable structure (i.e., *failure-elevations.json*).](##_Ref215568526)

######## [Hydraulics](##_Ref215568526)

[A *hydraulics* directory for each modeling unit, each hydraulic model contains the .hdf file containing the results for the run and a log file.](##_Ref215568526)

######## [Event Hazard Grids](##_Ref215568526)

[A *grids* directory for each modeling unit contains output maximum depth and maximum velocity .tif files.](##_Ref215568526)

######## [<span id="_Ref215571717" class="anchor"></span>Consequences](##_Ref215568526)

[A *consequences* directory contains a geopackage for each hydraulic modeling unit containing damages for each structure in the modeling unit’s footprint (not including overlaps in the mesh).](##_Ref215568526)

###### [<span id="_Ref215571635" class="anchor"><span id="_Ref215571813" class="anchor"><span id="_Toc217044477" class="anchor"></span></span></span>Simulation Level Summary Outputs](##_Ref215568526)

[Subsection [11.6.3](##_Ref215571813) describes the core simulation level summary outputs generated for an FFRD study. These outputs include tabular hazard summary data, gridded data, spatial point data and plots. All of these simulation level outputs represent data that is embedded in the individual event outputs and are summarized as a set of core standard outputs for easy communication of results and provide a basis for further analysis of results by others. Additionally, a subset of the gridded hazard outputs are required inputs for consequence computations.\
](##_Ref215568526)

######## [Tabular Results Summaries](##_Ref215568526)

[Tabular summaries of model results for every event the entire simulation are saved to the *\simulations\summary-data\\* directory. [Table 11.4](##_Ref207114734) lists datasets included in the summaries.<span id="_Ref207114734" class="anchor"><span id="_Toc214892795" class="anchor"></span></span>](##_Ref215568526)

[Table 11.4. Listing of Event-level Tabular Results Summaries](##_Ref215568526)

<table>
<colgroup>
<col style="width: 22%" />
<col style="width: 22%" />
<col style="width: 55%" />
</colgroup>
<thead>
<tr>
<th><a href="##_Ref215568526">Model</a></th>
<th><a href="##_Ref215568526">Location</a></th>
<th><a href="##_Ref215568526">Variable(s)</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="##_Ref215568526">Meteorology</a></td>
<td><a href="##_Ref215568526">Each Hydrologic Subbasin</a></td>
<td><a href="##_Ref215568526">Peak Precipitation for 1-hour, 24-hour, 48-hour, and 72-hour durations.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydrologic</a></td>
<td><a href="##_Ref215568526">All Junctions</a></td>
<td><a href="##_Ref215568526">Peak Flow for 1-hour, 24-hour, 48-hour, and 72-hour durations.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydrologic</a></td>
<td><a href="##_Ref215568526">All Subbasins</a></td>
<td><a href="##_Ref215568526">Summary parameters including infiltration, interception, LWASS, moisture deficit, percolation, excess precipitation, SWE, groundwater recharge, evapotranspiration, and baseflow.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Reservoir Operations</a></td>
<td><a href="##_Ref215568526">Modeled Reservoirs</a></td>
<td><a href="##_Ref215568526">Peak Outflow for 1-hour, 24-hour, 48-hour, and 72-hour durations.</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Reservoir Operations</a></td>
<td><a href="##_Ref215568526">Modeled Reservoirs</a></td>
<td><a href="##_Ref215568526">Peak pool stage</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">System Response</a></td>
<td><a href="##_Ref215568526">All Breach Locations</a></td>
<td><a href="##_Ref215568526">Sampled breach trigger elevation</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydraulic</a></td>
<td><a href="##_Ref215568526">Reference Lines</a></td>
<td><a href="##_Ref215568526">Peak flow and peak water surface elevation</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydraulic</a></td>
<td><a href="##_Ref215568526">Boundary Condition Lines</a></td>
<td><a href="##_Ref215568526">Peak flow and peak water surface elevation</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydraulic</a></td>
<td><a href="##_Ref215568526">2D Area Connections</a></td>
<td><a href="##_Ref215568526">Peak flow and peak water surface elevation</a></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydraulic</a></td>
<td><a href="##_Ref215568526">Reference Points</a></td>
<td><p><a href="##_Ref215568526">Maximum water surface elevation</a></p>
<p><a href="##_Ref215568526">Minimum water surface elevation</a></p></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydraulic</a></td>
<td><a href="##_Ref215568526">Breach Locations</a></td>
<td><p><a href="##_Ref215568526">Beach occurred (Y/N)</a></p>
<p><a href="##_Ref215568526">Maximum water surface loading at breach (headwater and tailwater)</a></p>
<p><a href="##_Ref215568526">Breach initiation time</a></p>
<p><a href="##_Ref215568526">Headwater elevation at breach time</a></p>
<p><a href="##_Ref215568526">Tailwater elevation at breach time</a></p>
<p><a href="##_Ref215568526">Peak flow through breach</a></p>
<p><a href="##_Ref215568526">Maximum breach bottom width</a></p>
<p><a href="##_Ref215568526">Breach progression duration</a></p></td>
</tr>
<tr>
<td><a href="##_Ref215568526">Hydraulic</a></td>
<td><a href="##_Ref215568526">Each Hydraulic Model Unit</a></td>
<td><p><a href="##_Ref215568526">Volume accounting error percentage</a></p>
<p><a href="##_Ref215568526">Maximum water surface elevation (WSEL) error</a></p>
<p><a href="##_Ref215568526">Computation time</a></p>
<p><a href="##_Ref215568526">Finished successfully (Y/N)</a></p></td>
</tr>
</tbody>
</table>

######## [Plots](##_Ref215568526)

[A variety of standard plots are created that leverage these standard simulation level outputs as well as observed data for comparison. Precipitation-frequency, LWASS, flow frequency, elevation-discharge, water surface elevation frequency, breach probability and damage-frequency plots are all included as core deliveries.](##_Ref215568526)

######## [Summary Hazard Grids](##_Ref215568526)

[Grids that summarize hazard results for each synthetic year, each full realization and for the multi-realization simulation are created. These summary hazard grids are saved to the *\simulations\summary-data\\* directory. Standard frequences for generation of grids are 1/10, 1/25, 1/50, 1/100, 1/250, 1/500, 1/1000, and 1/2000.](##_Ref215568526)

########## [Annual Maximum Grids](##_Ref215568526)

[Synthetic year maximum hazard grids represent the maximum across all event level grids of a specific hazard for a given synthetic year within a given realization. These grids take care to preserve the statistical characteristics of the annual maximums across a synthetic year. Each grid cell contains the maximum value for the critical event during the year for the specific hazard variable. Therefore, these grids are a mosaic of maximum values sourced from multiple events across each synthetic year.](##_Ref215568526)

[The following annual maximum grids are created and stored in *\simulations\summary-data\max-grids\\*.](##_Ref215568526)

[<span id="_Toc214892796" class="anchor"></span>Table 11.5. Annual Maximum Grids](##_Ref215568526)

| [Hazard Variable](##_Ref215568526) | [Grid](##_Ref215568526) |
|----|----|
| [Depth](##_Ref215568526) | [Annual maximum depth for each synthetic year in the simulation](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Annual Maximum velocity for each synthetic year in the simulation](##_Ref215568526) |

########## [Per Realization Summaries](##_Ref215568526)

[The following single realization summary grids are created and stored in*\simulations\summary-data\aep-grids\\*](##_Ref215568526)

[<span id="_Toc214892797" class="anchor"></span>Table 11.6. Single Realization Summary Grids](##_Ref215568526)

| [Hazard Variable](##_Ref215568526) | [Grid](##_Ref215568526) |
|----|----|
| [Depth](##_Ref215568526) | [Annual Exceedance Probability of Depth Exceeding Zero Feet](##_Ref215568526) |
| [Depth](##_Ref215568526) | [Depth at each Standard Frequency (8 grids)](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Annual Exceedance Probability of Velocity Exceeding 0 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Annual Exceedance Probability of Velocity Exceeding 6.6 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Annual Exceedance Probability of Velocity Exceeding 13.1 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Velocity at each Standard Frequency (8 grids)](##_Ref215568526) |

########## [Multiple Realization Summary](##_Ref215568526)

[The following summary grids that express mean results with uncertainty derived from multiple realizations are created and stored in*\simulations\summary-data\aep-grids\\*](##_Ref215568526)

[<span id="_Toc214892798" class="anchor"></span>Table 11.7. Summary Grids of Mean Results with Uncertainty](##_Ref215568526)

| [Hazard Variable](##_Ref215568526) | [Grid](##_Ref215568526) |
|----|----|
| [Depth](##_Ref215568526) | [Mean depth at each Standard Frequency (8 grids)](##_Ref215568526) |
| [Depth](##_Ref215568526) | [Standard deviation of depth at each Standard Frequency (8 grids)](##_Ref215568526) |
| [Depth](##_Ref215568526) | [Mean Annual Exceedance Probability of Depth Exceeding Zero Feet](##_Ref215568526) |
| [Depth](##_Ref215568526) | [Standard Deviation of Annual Exceedance Probability of Depth Exceeding Zero Feet](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Mean velocity at each Standard Frequency (8 grids)](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Standard deviation of velocity at each Standard Frequency (8 grids)](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Mean Annual Exceedance Probability of Velocity Exceeding 0 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Standard Deviation of Annual Exceedance Probability of Velocity Exceeding 0 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Mean Annual Exceedance Probability of Velocity Exceeding 6.6 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Standard Deviation of Annual Exceedance Probability of Velocity Exceeding 6.6 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Mean Annual Exceedance Probability of Velocity Exceeding 13.1 Feet per Second](##_Ref215568526) |
| [Velocity](##_Ref215568526) | [Standard Deviation of Annual Exceedance Probability of Velocity Exceeding 13.1 Feet per Second](##_Ref215568526) |

######## [Consequences](##_Ref215568526)

[A spatial output file for each hydraulic modeling domain describing AAL at each structure is stored in the Model Library under simulations in the sub directory, *summary-outputs/consequences*. The output is delivered in a standard spatial format of .geopackage. The compute methodology is discussed in the Job Aid 1, *Consequence Process*. In the parameterization of the compute, the user defines the standard frequencies for the compute, those are reproduced in the output demonstrated in [Table 11.8](##_Ref214891787). Each frequency will include an estimate of the mean structure damage, mean content damage, standard deviation structure damage, standard deviation structure damage, mean hazard and standard deviation of the hazard. If different annual exceedance probabilities are provided the attributes will reflect the provided input annual exceedance probabilities. The attribute names and descriptions are provided in the Table 11.7.<span id="_Ref214891787" class="anchor"><span id="_Toc214892799" class="anchor"></span></span>\
](##_Ref215568526)

[Table 11.8. Consequences Results Field Names and Descriptions (sheet 1 of 2)](##_Ref215568526)

| [Field Name](##_Ref215568526) | [Description](##_Ref215568526) |
|----|----|
| [ORIG_ID](##_Ref215568526) | [Unique Identifier related to the NSI](##_Ref215568526) |
| [REPVAL](##_Ref215568526) | [Depreciated Replacement value](##_Ref215568526) |
| [STORY](##_Ref215568526) | [Number of stories](##_Ref215568526) |
| [FOUND_T](##_Ref215568526) | [Foundation type](##_Ref215568526) |
| [FOUND_H](##_Ref215568526) | [Foundation height](##_Ref215568526) |
| [x](##_Ref215568526) | [X coordinate](##_Ref215568526) |
| [y](##_Ref215568526) | [Y coordinate](##_Ref215568526) |
| [OccType](##_Ref215568526) | [Occupancy type](##_Ref215568526) |
| [DamCat](##_Ref215568526) | [Damage category](##_Ref215568526) |
| [BASEFIN](##_Ref215568526) | [Basement finish status](##_Ref215568526) |
| [FFH](##_Ref215568526) | [First floor height](##_Ref215568526) |
| [DEMFT](##_Ref215568526) | [Dem ft](##_Ref215568526) |
| [BAAL](##_Ref215568526) | [Building average annualized loss](##_Ref215568526) |
| [CAAL](##_Ref215568526) | [Content Average annualized loss](##_Ref215568526) |
| [TAAL](##_Ref215568526) | [Total Average Annualized Loss](##_Ref215568526) |
| [PROB](##_Ref215568526) | [Probability of the first instance of flooding at a structure](##_Ref215568526) |
| [0.100000MS](##_Ref215568526) | [10-year mean structure damage](##_Ref215568526) |
| [0.100000SS](##_Ref215568526) | [10-year stdev structure damage](##_Ref215568526) |
| [0.100000MC](##_Ref215568526) | [10-year mean content damage](##_Ref215568526) |
| [0.100000SC](##_Ref215568526) | [10-year stdev content damage](##_Ref215568526) |
| [0.100000MH](##_Ref215568526) | [10-year mean hazard](##_Ref215568526) |
| [0.100000SH](##_Ref215568526) | [10-year stdev hazard](##_Ref215568526) |
| [0.040000MS](##_Ref215568526) | [25-year mean structure damage](##_Ref215568526) |
| [0.040000SS](##_Ref215568526) | [25-year stdev structure damage](##_Ref215568526) |

[\
](##_Ref215568526)

[Table 11.8. Consequences Results Field Names and Descriptions (sheet 2 of 2)](##_Ref215568526)

| [Field Name](##_Ref215568526) | [Description](##_Ref215568526) |
|----|----|
| [0.040000MC](##_Ref215568526) | [25-year mean content damage](##_Ref215568526) |
| [0.040000SC](##_Ref215568526) | [25-year stdev content damage](##_Ref215568526) |
| [0.040000MH](##_Ref215568526) | [25-year mean hazard](##_Ref215568526) |
| [0.040000SH](##_Ref215568526) | [25-year stdev hazard](##_Ref215568526) |
| [0.020000MS](##_Ref215568526) | [50-year mean structure damage](##_Ref215568526) |
| [0.020000SS](##_Ref215568526) | [50-year stdev structure damage](##_Ref215568526) |
| [0.020000MC](##_Ref215568526) | [50-year mean content damage](##_Ref215568526) |
| [0.020000SC](##_Ref215568526) | [50-year stdev content damage](##_Ref215568526) |
| [0.020000MH](##_Ref215568526) | [50-year mean hazard](##_Ref215568526) |
| [0.020000SH](##_Ref215568526) | [50-year stdev hazard](##_Ref215568526) |
| [0.010000MS](##_Ref215568526) | [100-year mean structure damage](##_Ref215568526) |
| [0.010000SS](##_Ref215568526) | [100-year stdev structure damage](##_Ref215568526) |
| [0.010000MC](##_Ref215568526) | [100-year mean content damage](##_Ref215568526) |
| [0.010000SC](##_Ref215568526) | [100-year stdev content damage](##_Ref215568526) |
| [0.010000MH](##_Ref215568526) | [100-year mean hazard](##_Ref215568526) |
| [0.010000SH](##_Ref215568526) | [100-year stdev hazard](##_Ref215568526) |
| [0.004000MS](##_Ref215568526) | [250-year mean structure damage](##_Ref215568526) |
| [0.004000SS](##_Ref215568526) | [250-year stdev structure damage](##_Ref215568526) |
| [0.004000MC](##_Ref215568526) | [250-year mean content damage](##_Ref215568526) |
| [0.004000SC](##_Ref215568526) | [250-year stdev content damage](##_Ref215568526) |
| [0.004000MH](##_Ref215568526) | [250-year mean hazard](##_Ref215568526) |
| [0.004000SH](##_Ref215568526) | [250-year stdev hazard](##_Ref215568526) |
| [0.002000MS](##_Ref215568526) | [500-year mean structure damage](##_Ref215568526) |
| [0.002000SS](##_Ref215568526) | [500-year stdev structure damage](##_Ref215568526) |
| [0.002000MC](##_Ref215568526) | [500-year mean content damage](##_Ref215568526) |
| [0.002000SC](##_Ref215568526) | [500-year stdev content damage](##_Ref215568526) |
| [0.002000MH](##_Ref215568526) | [500-year mean hazard](##_Ref215568526) |
| [0.002000SH](##_Ref215568526) | [500-year stdev hazard](##_Ref215568526) |

## [<span id="_Toc217044478" class="anchor"></span>—Conformance](##_Ref215568526)

[The conformance phase of the project integrates the individual calibrated models into a full watershed model and assures acceptable results can be achieved. The watershed model is first validated for performance against historic events, and then a single long-term realization of storm events is computed. Conformance metrics, which compare simulated frequency curves at key locations to observed frequency curves, are evaluated. Acceptable conformance metrics must be achieved prior to completing the phase and proceeding to production level computations.](##_Ref215568526)

[Then during the conformance phase, the individual models will be promoted to the conformance directory, adjusted to represent synthetic events, fully linked, tested for successful execution in the cloud, and checked against desktop results for fidelity. After fidelity is verified, a long-term realization of events will be executed in the cloud and the suite of models will be adjusted as necessary to meet conformance metrics as defined in the SOP. After conformance metrics are met, reviewed, and approved, the full model suite is considered finalized, and the conformance phase is closed out. After the conformance phase is completed, the production phase begins, in which the model suite is utilized for execution of the full production level simulation, including multiple long-term realizations.<span id="_Toc214891710" class="anchor"></span>\
](##_Ref215568526)

[Figure 12.1. Context of the Conformance Phase in the Future of Flood Risk Data Workflow](##_Ref215568526)

[<img src="media/image21.png" style="width:4in;height:5.66372in" />](##_Ref215568526)

#### [<span id="_Toc217044479" class="anchor"></span>Staffing for Conformance Phase](##_Ref215568526)

[The conformance phase is led by the model integration lead and executed by a relatively smaller team that utilizes the final calibrated models delivered during the calibration phase. The team integrates the models and makes watershed-wide adjustments as necessary to meet the QC and conformance metrics described in the sections below. Significant support from the cloud environment lead is also required build the compute manifests and to execute models in the cloud through several iterations. Any significant changes to the configuration of the model suite must be coordinated with the appropriate team members involved in the calibration and development of the models (e.g. breach location changes, dam operations changes, etc.).](##_Ref215568526)

#### [<span id="_Toc217044480" class="anchor"></span>Selection of Time Window Duration for Stochastic Events](##_Ref215568526)

[The time window for stochastic simulations will be selected early in the conformance phase. The time window selected will be of adequate duration, such that the storm event occurs, and peak water surfaces are fully routed through the entire basin prior to the end of simulation.](##_Ref215568526)

#### [<span id="_Toc217044481" class="anchor"></span>Conformance Workflow Overview](##_Ref215568526)

[The conformance phase of the project includes several logical major steps to achieve success as briefly described below.](##_Ref215568526)

1.  

<!-- -->

3.  [<u>Cloud Compute Setup</u>: Setup of cloud compute to accept the fully integrated system of models for computation of stochastic events. Includes pre-processing random seeds, synthetic years, and fishnets for storm placements.<u>Model Integration:</u> Full model linking following the previously scoped model linking plan and naming conventions in desktop environment.](##_Ref215568526)

4.  [<u>Historic Event Replication</u>: QC step to ensure that the fully linked system of models still reproduces historic event results, which can be completed in desktop environment.](##_Ref215568526)

5.  [<u>Stress Testing</u>: Desktop execution of model runs that push the limits of model stability and accuracy. Events selected include extreme combinations of storm events and breaches of dams and levees.](##_Ref215568526)

6.  [<u>Model Delivery for Cloud Compute</u>: The full model suite is tailored for cloud compute and delivered to the appropriate location in the *cloud* directory to allow cloud computations.](##_Ref215568526)

7.  [<u>Pre-conformance Review</u>: Review that thoroughly checks the models delivered to ensure all standards are met, documented with review checklist.](##_Ref215568526)

8.  [<u>Cloud-compute Manifests</u>: Development of compute manifests that contain instructions for each cloud-compute plugin to perform the computations.](##_Ref215568526)

9.  [<u>Initial Cloud Computation</u>: Cloud computation of 3 to 5 synthetic events.](##_Ref215568526)

10. [<u>Fidelity Check Cloud versus Desktop</u>: Direct comparison of desktop results to cloud results for the same storm events to ensure fidelity.](##_Ref215568526)

11. [<u>Single Realization Computation</u>: Cloud computation of a single realization of stochastic storm events.](##_Ref215568526)

12. [<u>Event Filtering for Hydraulic Model</u>: Selection of a subset of events for computation through the hydraulic model that are relevant for characterizing flood risk. This recognizes that the cost of computing every stochastic event through the hydraulic model is not justified.](##_Ref215568526)

13. [<u>Hazard Maps and Consequences Computation</u>: Cloud computation of event-based depth grids, summarized hazard maps, and consequences.](##_Ref215568526)

14. [<u>Conformance Metric Evaluation</u>: The results from the single realization will be evaluated against the established conformance metrics.](##_Ref215568526)

[<span id="_Toc214891711" class="anchor"></span>Figure 12.2. Conformance Phase Workflow](##_Ref215568526)

[<img src="media/image22.png" style="width:6.09545in;height:6.09545in" alt="Diagram AI-generated content may be incorrect." />\
](##_Ref215568526)

#### [<span id="_Toc217044482" class="anchor"></span>Conformance Task Descriptions](##_Ref215568526)

[The following subsections provide additional descriptions of the tasks shown in the workflow overview above.](##_Ref215568526)

###### [<span id="_Ref215572395" class="anchor"><span id="_Toc217044483" class="anchor"></span></span>Cloud Compute Setup](##_Ref215568526)

[There are several important cloud setup activities that can being immediately at the start of the conformance phase and can occur concurrently while models are being integrated, tested, and prepared for Model Delivery to the cloud.](##_Ref215568526)

######## [Generate Event Seeds](##_Ref215568526)

[The generated seeds provide the basis for stochastic sampling for the project.](##_Ref215568526)

######## [Storm Sampling and Placements via Fishnets](##_Ref215568526)

[The storm events including placements are sampled for the conformance realization.](##_Ref215568526)

######## [Breach Trigger Sampling](##_Ref215568526)

[The breach triggers are sampled for each event within the conformance realization. See Section 9 for criteria for the breach sampling scheme.](##_Ref215568526)

###### Model Integration

Model integration is the responsibility of the model integration lead and is performed in a desktop environment. This integration includes the hydrologic model, reservoir operations model and all hydraulic models for the project. The model linking register and detailed naming convention tables are created during the scoping and data preparation phase and will guide all model integration efforts. Communication of the linking register table can be aided by graphical representations of how output data is used as input for subsequent models as shown in [[Figure 12.3 below as an example.](##_Ref207117602)](##_Ref215568526)

[[During model integration, all models undergo several changes so they can accept synthetic events rather than observed events. This includes various boundary conditions and naming adjustments that are detailed in Job Aid 13, *Model Delivery for Cloud Compute*.](##_Ref207117602)](##_Ref215568526)

[[Desktop model integration allows for the team members to thoroughly review and verify the configuration and performance of the full watershed model for individual events with easily identifiable and traceable boundary conditions in a traditional computing environment.<span class="mark">\
</span>](##_Ref207117602)](##_Ref215568526)

[[<span id="_Ref207117602" class="anchor"><span id="_Toc214891712" class="anchor"></span></span>Figure 12.3. Conceptual Model Linking Diagram](##_Ref207117602)](##_Ref215568526)

[[<img src="media/image23.png" style="width:4.25in;height:5.96491in" />](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044485" class="anchor"></span>Historic Event Replication](##_Ref207117602)](##_Ref215568526)

[[During the previous calibration phase the individual models were calibrated to match observations from historic storm events. Within the desktop environment, the fully integrated models must be checked against those same historic events to ensure acceptable results are achieved.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044486" class="anchor"></span>Stress Testing](##_Ref207117602)](##_Ref215568526)

[[The system of models will be subjected to a wide variety of boundary conditions ranging from a dry basin with no rainfall to extreme floods on wet antecedent conditions during the stochastic model runs. Dams and levees will also be subjected to breaches. To minimize model instabilities during the production runs, the models are stress tested by the project’s model integration lead in the desktop environment. This effort involves running extreme or unusual storm conditions through the model to check for any model instability or other issues. For instance, the largest storm in the meteorologic region (from the storm catalog described in Section 5.4) could be centered over a critical location in the basin. All levees and dams could be allowed to breach during the same event. The initial model states may also be adjusted to extreme conditions to pair with the precipitation. Extreme low flows and dry conditions are considered as well as extreme high flows.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044487" class="anchor"></span>Model Delivery for Cloud Compute](##_Ref207117602)](##_Ref215568526)

[[After the models have been integrated, verified, and stress tested, they are nearly ready for delivery for cloud compute. However, there are several steps that must be taken, which are fully detailed in Job Aid 13, *Model Delivery for Cloud Compute*. After models have been posted to the correct locations on the conformance folder along with the final version of the Model Linking Register, the model integration lead is responsible for ensuring the data is accurate and ready for cloud compute via the pre-conformance review (next step).](##_Ref207117602)](##_Ref215568526)

[[After the integrated models are initially delivered to the cloud, changes will be needed to address errors or to iterate to achieve the desired model results. The *archive workflow*, as described in Job Aid 13, *Model Library Use for FFRD*, is designed to minimize mistakes in model versioning. Before any model is updated, the previous version of the model is archived in Model Library through the rename functionality. The model should be renamed with */archive/* prepended to the model’s name to support the model archive. After the previous model is archived, the new model is updated where the old model previously was stored. This workflow ensures the most current models exist in a static location that does not change, while also maintaining a record of the superseded models.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044488" class="anchor"></span>Pre-Conformance Review](##_Ref207117602)](##_Ref215568526)

[[After the models have been integrated in the desktop environment, verified against historic events, and stress tested, they are nearly ready to be delivered to the cloud storage for cloud computations of synthetic events.](##_Ref207117602)](##_Ref215568526)

[[Prior to hand off to the cloud compute team member, a full review of the models to be delivered will be completed and the models will undergo a QC check documented by in the Pre-Conformance Review Checklist. Cloud compute steps do not begin until the pre-conformance review has been fully closed and approved by the model integration lead.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044489" class="anchor"></span>Cloud-compute Manifests](##_Ref207117602)](##_Ref215568526)

[[After all models have been reviewed and delivered to the cloud, the cloud-compute manifests are created as described in Job Aid 12, *Cloud Compute Manifests*. These files provide the instructions for cloud-compute plug-ins to perform compute jobs. The Model Linking Register and the data in the actual delivered models are utilized as inputs to create the compute-manifests. Strict adherence to naming conventions and scripting to automate certain steps in the production of the compute manifests has the potential to improve efficiency and ability to QC linking data.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044490" class="anchor"></span>Initial Cloud Computation](##_Ref207117602)](##_Ref215568526)

[[Three to five events will be computed as a starting point before running any large-scale, cloud-compute simulations for the project. The cloud-compute lead builds the required compute-manifest to execute the hydrologic, reservoir operations, and hydraulic models. The cloud-compute lead will verify that inputs and results from the events are being properly varied and then pass the model to the model integration lead for additional review checks.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044491" class="anchor"></span>Fidelity Check Cloud versus Desktop](##_Ref207117602)](##_Ref215568526)

[[The model integration lead will work with the cloud compute team member to perform checks to ensure that cloud compute is producing identical results to a desktop computation with identical boundary conditions and inputs for each event. Any identified issues with the model linkages, desktop models, or cloud compute will be addressed. The cloud results will be evaluated for model linking, antecedent conditions, storm placements, and breach triggers among other items. Iterations will occur until discrepancies are fully resolved. The conformance review checklist includes items to verify that this step was completed.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044492" class="anchor"></span>Single Realization Computation](##_Ref207117602)](##_Ref215568526)

[[A single realization will be executed through cloud compute, which allows model performance over a long-term simulation to be evaluated against observed data. Frequency curves must be compared across the range of observed data with one realization of 2,000 years having a stable mean to the 100-year event.](##_Ref207117602)](##_Ref215568526)

[[To inform the event filtering described in the next section, each event in the realization is first computed through the HEC-ResSim model. The filtered events to run through the hydraulic model are then selected based on the results from the earlier models.](##_Ref207117602)](##_Ref215568526)

[[Each selected event will be executed through the hydraulic model step (i.e., depth grids, hazards grids and consequences are not evaluated initially) and summary results are output to allow for analysis of model performance. Performance is then evaluated as described in the next step, and models are updated and recomputed until conformance metrics are met.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Ref215572516" class="anchor"><span id="_Toc217044493" class="anchor"></span></span>Event Filtering for Hydraulic Model](##_Ref207117602)](##_Ref215568526)

[[It is recognized that not every synthetic event contributes to the overall characterization of the flood risk for the project since some of the sampled events produce only minor runoff compared to all other events in the synthetic year. The fully 2D hydraulic models for the project are relatively computationally expensive and costs associated with running every event in cloud compute are not justified.](##_Ref207117602)](##_Ref215568526)

[[Leveraging the results from computation of all events through hydrology, reservoir operations, and breach sampling, a list of specific events for computation through the hydraulic models is developed. Tabulated summaries of the event-by-event maximums of many variables in many locations for each event are generated.](##_Ref207117602)](##_Ref215568526)

[[The cloud compute team member and model integration lead will work together to create a filtered list of sampled events that will be executed through cloud compute based on their importance to flood risk characterization for the project following the process described in Job Aid 19, *Selection of Events for Hydraulic Modeling*.](##_Ref207117602)](##_Ref215568526)

[[Results from a full realization through the hydrologic and reservoir operations models is needed to inform the filtering, therefore there is a feedback loop with the Single Realization Computation step described in the previous section.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044494" class="anchor"></span>Hazard Maps and Consequence Computation](##_Ref207117602)](##_Ref215568526)

[[Cloud computation of event-based depth grids, summarized hazard maps, and consequences are computed based on the results from the hydraulic model. It is recognized that there is a relatively high computation cost associated with generation depth grids for each event and summarized hazards grids. Therefore, the conformance metrics described in the section below that relate model results through the hydraulic model will be evaluated to ensure conformance prior to the computation of hazard maps and consequences.](##_Ref207117602)](##_Ref215568526)

######## [[Consequences](##_Ref207117602)](##_Ref215568526)

[[Structure inventories are updated based on the results of the previously completed survey and quality checks. Event-based consequence estimates are computed using FEMA damage function curves approved for each occupancy type and foundation type combination. Expected annual damages and frequency of when structures are first inundated are Produced. Refer to the Job Aid 17, *Consequence Processes,* for details on the workflow.](##_Ref207117602)](##_Ref215568526)

[[Consequence team members should review outlier results for reasonableness, mapping results for coverage, and ensure that consequences appear to be working as intended.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Ref215572530" class="anchor"><span id="_Toc217044495" class="anchor"></span></span>Conformance Metrics Evaluation](##_Ref207117602)](##_Ref215568526)

[[The model results of the single realization allow for a robust evaluation of model performance over a long-term simulation against observed data. Fundamentally, the FFRD modeled results must reasonably align with observed long-term data and a thorough evaluation of the single realization results during the conformance phase provides credibility that the modeling system can provide flood risk estimates for the watershed.](##_Ref207117602)](##_Ref215568526)

[[[Table 12.1](##_Ref207276912) lists the relationships that must be evaluated for an FFRD study during the conformance phase. Evaluations must be performed via a graphical comparison to observed data and via computation of objective statistical metrics. Additional guidance on metrics to be evaluated and processes for evaluation are provided in Job Aid 12, *Model Calibration*.](##_Ref207117602)](##_Ref215568526)

[[Additional specifics regarding objective pass/fail criteria for acceptable frequency-based model results will be considered for a future update to this SOP.](##_Ref207117602)](##_Ref215568526)

[[<span id="_Ref207276912" class="anchor"><span id="_Toc214892801" class="anchor"></span></span>Table 12.1. List of Relationships of Long-term Modeled Data versus Observed Data for Conformance Evaluation](##_Ref207117602)](##_Ref215568526)

| [[Relationship](##_Ref207117602)](##_Ref215568526) |
|----|
| [[Storm Types](##_Ref207117602)](##_Ref215568526) |
| [[Storm Dates/Seasonality](##_Ref207117602)](##_Ref215568526) |
| [[Storm Locations](##_Ref207117602)](##_Ref215568526) |
| [[Precipitation Frequency](##_Ref207117602)](##_Ref215568526) |
| [[Liquid Water at Soil Surface Frequency](##_Ref207117602)](##_Ref215568526) |
| [[Flow Frequency](##_Ref207117602)](##_Ref215568526) |
| [[Elevation Discharge Relationship](##_Ref207117602)](##_Ref215568526) |
| [[Elevation Frequency](##_Ref207117602)](##_Ref215568526) |
| [[Dam and Levee Breaching Frequency](##_Ref207117602)](##_Ref215568526) |
| [[Flood Extents versus Historical Event Information](##_Ref207117602)](##_Ref215568526) |
| [[Consequence Frequency versus Claims Data](##_Ref207117602)](##_Ref215568526) |

[[In addition to ensuring the model results match observed data, model stability is also a key criterion for model conformance. A broad review of overall results from the system of models must be completed. In particular, hydraulic model volume errors must be less than 5 percent but greater than 3 percent for all events.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044496" class="anchor"></span>Iterations to Achieve Conformance](##_Ref207117602)](##_Ref215568526)

[[The models are expected to undergo multiple iterations to achieve conformance to long-term observed data. Job Aid 12, *Model Calibration*, includes guidance and best practices for updates to a system of models to achieve the targets.](##_Ref207117602)](##_Ref215568526)

[[Deliberate and careful model data management is required for successful completion of the project and improves the ability to communicate model updates with the project team. The current version of each model must be maintained as a static directory, which requires an archival of the previous version prior to upload of the update. This archival process and the standard directory names are described in Job Aid 07, *Model Library Use*.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044497" class="anchor"></span>Computational Resources](##_Ref207117602)](##_Ref215568526)

[[During the earliest cloud-compute efforts, the compute team monitors and records the demand for central processing unit (CPU), random access memory (RAM), disk space, and runtime for computing an event through the full system of models. These resource demand estimates inform the cloud computing resources needed for the full watershed multi-realization compute.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044498" class="anchor"></span>Optimization of Computes](##_Ref207117602)](##_Ref215568526)

[[There are several variables that can be adjusted to optimize cloud computations. Shorter compute times for individual events can be achieved by using more powerful cloud resources, but experiences to date have shown that compute costs are optimized when less powerful cloud resources are utilized. Additionally, certain model settings related to the use of compute resources also impact cost and runtime, which must be optimized prior to initiation of large-scale cloud computes for FFRD. The primary objective of optimization is to achieve the lowest compute cost. Additional detail and considerations for optimization are included in cloud-compute documentation.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044499" class="anchor"></span>Compute Costs](##_Ref207117602)](##_Ref215568526)

[[After optimization of the computations, an estimate of resources and cost to compute the full set of events for the study is made.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044500" class="anchor"></span>Conformance Phase Reporting](##_Ref207117602)](##_Ref215568526)

[[A set of standard reports is written for each phase in the FFRD project. Appendix B contains report templates for the hydraulic modeling reports.](##_Ref207117602)](##_Ref215568526)

[[The conformance phase report describes model integration, calibration verification, and conformance outcomes. The report also includes a full description of updates required in the hydrologic, reservoir operations, system response, or hydraulic models that were made to achieve conformance targets. Reports are filed in the documentation folder within the watershed repository in the Model Library.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044501" class="anchor"></span>Conformance Phase Review Process and Deliverables](##_Ref207117602)](##_Ref215568526)

[[Review of the conformance phase deliveries is critical for project success. The review steps during the conformance phase are defined below. Review checklists are used to track comments regarding pre-defined aspects checked throughout the review process. Appendix A contains checklist templates.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044502" class="anchor"></span>Pre-Conformance Review](##_Ref207117602)](##_Ref215568526)

[[The pre-conformance review occurs after the system of models has been integrated in the desktop environment, tested and delivered for cloud compute. The pre-conformance review ensures that the system of models is fully ready for the cloud compute process. A review checklist template with standard prompts guides the review and documents completion of the review. This pre-conformance review checklist must be closed out prior to hand-off of the model to the cloud compute team member.](##_Ref207117602)](##_Ref215568526)

###### [[<span id="_Toc217044503" class="anchor"></span>Conformance Review](##_Ref207117602)](##_Ref215568526)

[[The conformance review covers all aspects of review of cloud-compute results and the conformance phase report will be documented via the conformance review checklist template. This checklist includes items related to review of the 3 to 5 initial cloud compute events as well as the review of results from the full realization.](##_Ref207117602)](##_Ref215568526)

[[Throughout the conformance phase, iterations to the models may be necessary to achieve acceptable results.](##_Ref207117602)](##_Ref215568526)

[[After the initial cloud computations are complete the team will verify the fidelity of results and iterate as necessary to ensure the desktop models and cloud compute are producing intended results.](##_Ref207117602)](##_Ref215568526)

[[After the computation of a single realization in cloud compute, the results will be thoroughly reviewed and assessed for conformance and again iterated as necessary to ensure conformance targets are met.](##_Ref207117602)](##_Ref215568526)

[[The final delivery for the conformance phase close out includes:](##_Ref207117602)](##_Ref215568526)

- [[Conformance phase report](##_Ref207117602)](##_Ref215568526)

- [[Final models posted to */conformance/\[model\]/* directories](##_Ref207117602)](##_Ref215568526)

- [[Conformance phase event-level model results posted to *conformance/simulations* directory](##_Ref207117602)](##_Ref215568526)

- [[Conformance phase summary model results posted to *conformance/simulations.*](##_Ref207117602)](##_Ref215568526)

- 

[[<span id="_Toc217044504" class="anchor"></span>—Production of Stochastic\
Simulations](##_Ref207117602)](##_Ref215568526)
===========================================================================

[[The production phase of the project begins after demonstration that models achieve the standards set in the conformance phase of the project and the conformance phase review has been closed out. The number of runs transitions from a single realization to a full multi-realization simulation. The dominant characteristic of the production phase is the computation of a very large number of events, which requires significant cloud computing resources to achieve.](##_Ref207117602)](##_Ref215568526)

[[<span id="_Toc214891713" class="anchor"></span>Figure 13.1. Context of the Production Phase of the Future of Flood Risk Data Workflow](##_Ref207117602)](##_Ref215568526)

[[<img src="media/image24.png" style="width:4.25in;height:6.02969in" alt="Diagram AI-generated content may be incorrect." />](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044505" class="anchor"></span>Promotion of Models to Production Directory](##_Ref207117602)](##_Ref215568526)

[[All activities for the project leading up to the production phase ensure that the system of models meet quality standards and can confidently be executed for a very large number of events. The models will not experience significant changes or updates during the production phase.](##_Ref207117602)](##_Ref215568526)

[[At the start of the production phase, the final set of models from the conformance phase are copied to the *production* directory and will be used directly in the production computations.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044506" class="anchor"></span>Cloud Compute Setup](##_Ref207117602)](##_Ref215568526)

[[Event seeds, storm selection, storm placement, and breach trigger elevations are all produced for each event for the full stochastic simulation early in the production phase. This is done in a similar manner as described in Section [12.4.1](##_Ref215572395).](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044507" class="anchor"></span>Strategies to Ensure Efficient Use of Cloud Compute Resources](##_Ref207117602)](##_Ref215568526)

[[Early in the production phase, the models have already been fully prepared for execution of all events in the stochastic simulation using cloud-compute tools. Before submitting the full set of compute jobs for all events for all models, small batches of runs should be made and evaluated to ensure accurate cloud configurations are in place. The following batches of runs are recommended for execution and evaluation in a step-wise fashion to confirm configurations:](##_Ref207117602)](##_Ref215568526)

- [[Execute full model suite for 3 to 5 events and evaluate results](##_Ref207117602)](##_Ref215568526)

- [[Execute hydrologic model for entire simulation and evaluate results](##_Ref207117602)](##_Ref215568526)

- [[Execute reservoir operation model for entire simulation and evaluate results](##_Ref207117602)](##_Ref215568526)

- [[Execute hydraulic models for all selected events and evaluate results](##_Ref207117602)](##_Ref215568526)

- [[Execute hazard grid generation for all selected events and evaluate results](##_Ref207117602)](##_Ref215568526)

- [[Compute consequences and evaluate results](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044508" class="anchor"></span>Event Filtering for Hydraulic Model](##_Ref207117602)](##_Ref215568526)

[[The simulation structure for FFRD includes modeling of multiple storm events per year. The goal is to produce annual probabilities of hazard and risk and not every event contributes to the annual maximum of hazards. Given the computational burden of executing a large number of events through the hydraulic models, it is worthwhile to select the subset of events that have the potential to contribute to annual maximum hazards.](##_Ref207117602)](##_Ref215568526)

[[No single event necessarily drives the annual maximum hazards everywhere for a given variable of interest. Within each synthetic year, the maximum hazards for unique locations could result from a locally intense precipitation events, upstream runoff, breaches, or other complex interactions.](##_Ref207117602)](##_Ref215568526)

[[Events will be filtered to execute only a portion of the events through the hydraulic model. Additional description and process for filtering the events is included in Section [12.4.11](##_Ref215572516) and Job Aid 19, *Selection of Events for Hydraulic Modeling*.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044509" class="anchor"></span>Hot Fixes](##_Ref207117602)](##_Ref215568526)

[[Running large scale quantities of numerical models within the stochastic simulation can yield conditions that cause the model to fail. Very low failure rates are expected due to the rigorous QC and QA steps that take place prior to the start of the production phase. However, since production simulations can produce extreme events or unique combinations of conditions, model failures may occur.](##_Ref207117602)](##_Ref215568526)

[[When model failure occurs, the team will investigate the cause of failure. Typically, the failure can be addressed with a hot fix of the models. A hot fix is an alternate version of the input model(s) that addresses a specific accuracy or stability issue that arises in one or more events during the production phase. Hot fix model versions are applied only to specific events where they were deemed necessary.](##_Ref207117602)](##_Ref215568526)

[[The standard directory structure for the conformance phase provides for storage of the hot fix model versions along with metadata files that document the specific events there were utilized for.](##_Ref207117602)](##_Ref215568526)

[[The general workflow for implementing hot fixes is shown below.](##_Ref207117602)](##_Ref215568526)

1.  

<!-- -->

15. [[Model integration lead investigates cause of model failure (see Job Aid 15, *Verification of Cloud Compute Event Results*, for process to acquire date for investigation).Model integration lead should take appropriate actions to correct the model.](##_Ref207117602)](##_Ref215568526)

16. [[Model integration lead should upload the new model files into Model Library in a hot fix location consistent with the required standard directory structure (see Job Aid 07, *Model Library Use*) and notify the cloud compute team. Also refer to Job Aid 13, *Model Delivery for Cloud Compute*, to ensure models are uploaded in the appropriate format for cloud compute.](##_Ref207117602)](##_Ref215568526)

17. [[Cloud compute team member reruns the failed events and works with model integration lead to verify the hot fix resolved the issue.](##_Ref207117602)](##_Ref215568526)

18. [[Cloud compute team member identifies which events the hot fix resolved and uploads a list of those event numbers to the hot fix model folder.](##_Ref207117602)](##_Ref215568526)

[[When hotfixes are applied to the project, the overall results from the full simulation are sourced from slightly different input models; but represent a complete and cohesive quantification of hazards and risk for the basin.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044510" class="anchor"></span>Investigation of Outliers](##_Ref207117602)](##_Ref215568526)

[[In addition to certain events that may lead to a model failure due to model stability, the team must evaluate the results for possible outlier results that may indicate stability or accuracy issues. Outliers must be reviewed to determine if the results are valid or if a hot fix may be required.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044511" class="anchor"></span>Significant Model Updates](##_Ref207117602)](##_Ref215568526)

[[If the team determines the required fixes for certain failed events or outlier events would significantly impact the results for the entire basin, it may suggest the need for a more comprehensive update to the inputs models for all events. The review process leading up to the start of the production phase ensures major model changes during the production phase will be extremely rare. Any decisions related to major model changes during production must be elevated to program leadership.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044512" class="anchor"></span>Production Results Comparison to Observed Data](##_Ref207117602)](##_Ref215568526)

[[Results of the full stochastic simulation will be evaluated compared to observed data. This evaluation is similar to the evaluation done during the conformance phase (Section [12.4.13](##_Ref215572530)), although multiple realizations will be available to provide insight into the quantification of knowledge uncertainty and there is no expectation to adjust the models to improve the results.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044513" class="anchor"></span>Production Phase Reporting](##_Ref207117602)](##_Ref215568526)

[[A set of standard reports is written for each phase in the FFRD project. Appendix B contains the report template for the production phase report. This report will contain an overview of the tasks executed during the production phase, a summary of the results, and documentation of any model hot fixes or patches that occurred during the production phase.](##_Ref207117602)](##_Ref215568526)

#### [[<span id="_Toc217044514" class="anchor"></span>Stochastic Simulations Review Process and Deliverables](##_Ref207117602)](##_Ref215568526)

[[A review the full production level results including precipitation, hydrology, reservoir operations, system response, hydraulics, mapping, and consequences is conducted. Knowledge uncertainty in results as quantified by differences among the multiple realizations is evaluated during this review. Review of the production phase deliveries is documented through a review checklist. Appendix A contains the checklist template.](##_Ref207117602)](##_Ref215568526)

[[The deliverables from the production phase are:](##_Ref207117602)](##_Ref215568526)

- [[Completed Production Phase Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Completed Production Phase Report](##_Ref207117602)](##_Ref215568526)

- [[Final models applied to simulation (including any hot fix alternate versions) posted to */production/\[model\]/* directories](##_Ref207117602)](##_Ref215568526)

- [[Conformance phase event-level model results posted to *production/simulations* directory](##_Ref207117602)](##_Ref215568526)

- [[Conformance phase summary model results posted to *production/simulations*](##_Ref207117602)](##_Ref215568526)

- 

## [[<span id="_Toc217044515" class="anchor"></span>—Final Report Phase](##_Ref207117602)](##_Ref215568526)

[[After the production phase has been completed, including close-out of the quality control review checklist and approval from the technical oversight review, the final reporting phase transfers and communicates the results of the study. The full project directory dataset is archived for long term storage. The final report is prepared to document the overall effort and to formally close the project.](##_Ref207117602)](##_Ref215568526)

[[A set of standard reports is written for each phase in the FFRD project, and templated for these reports are included in Appendix B. The final report will be a relatively short document that refers to the documentation that is created at the end of each phase of the project for detailed model development, calibration and results.](##_Ref207117602)](##_Ref215568526)

[[<span id="_Toc214891714" class="anchor"></span>Figure 14.1. Context of the Final Report Phase of the Future of Flood Risk Data Workflow](##_Ref207117602)](##_Ref215568526)

[[<img src="media/image25.png" style="width:2.75in;height:3.90156in" alt="Diagram AI-generated content may be incorrect." />](##_Ref207117602)](##_Ref215568526)

[[\
](##_Ref207117602)](##_Ref215568526)

[[This page is intentionally blank.](##_Ref207117602)](##_Ref215568526)

## 

[[<span id="_Toc217044516" class="anchor"></span>List of Acronyms and Abbreviations**2D** two dimensional](##_Ref207117602)](##_Ref215568526)

[[**3DEP** 3D Elevation Program](##_Ref207117602)](##_Ref215568526)

[[**AAL** average annualized losses](##_Ref207117602)](##_Ref215568526)

[[**AORC** Analysis of Record for Calibration](##_Ref207117602)](##_Ref215568526)

[[**BE-PWP** basin execution project work plan](##_Ref207117602)](##_Ref215568526)

[[**CCP** common computation point](##_Ref207117602)](##_Ref215568526)

[[**CONUS** continental United States](##_Ref207117602)](##_Ref215568526)

[[**CRS** Coordinate Reference System](##_Ref207117602)](##_Ref215568526)

[[**CPU** central processing unit](##_Ref207117602)](##_Ref215568526)

[[**CWBI** Civil Works Business Intelligence](##_Ref207117602)](##_Ref215568526)

[[**DEM** digital elevation model](##_Ref207117602)](##_Ref215568526)

[[**EAD** expected annualized damages](##_Ref207117602)](##_Ref215568526)

[[**EAP** Emergency Action Plan](##_Ref207117602)](##_Ref215568526)

[[**EDH** elevation derived hydrography](##_Ref207117602)](##_Ref215568526)

[[**EM** Engineer Manual](##_Ref207117602)](##_Ref215568526)

[[**ESA** elevation-storage-area](##_Ref207117602)](##_Ref215568526)

[[**FEMA** Federal Emergency Management Agency](##_Ref207117602)](##_Ref215568526)

[[**FFRD** Future of Flood Risk Data](##_Ref207117602)](##_Ref215568526)

[[**FIRM** Flood Insurance Rate Map](##_Ref207117602)](##_Ref215568526)

[[**FIS** Flood Insurance Study](##_Ref207117602)](##_Ref215568526)

[[**FRM** flood risk management](##_Ref207117602)](##_Ref215568526)

[[**Gb** gigabyte](##_Ref207117602)](##_Ref215568526)

[[**GW** groundwater](##_Ref207117602)](##_Ref215568526)

[[**H&H** hydraulics and hydrology](##_Ref207117602)](##_Ref215568526)

[[**HEC** Hydrologic Engineering Center](##_Ref207117602)](##_Ref215568526)

[[**HEC-DSS** Data Storage System](##_Ref207117602)](##_Ref215568526)

[[**HEC-HMS** Hydrologic Modeling System](##_Ref207117602)](##_Ref215568526)

[[**HEC-RAS** River Analysis System](##_Ref207117602)](##_Ref215568526)

[[**HEC-ResSim** Reservoir System Simulation](##_Ref207117602)](##_Ref215568526)

[[**HUC** hydrologic unit code](##_Ref207117602)](##_Ref215568526)

[[**IBTrACS** International Best Track Archive for Climate Stewardship](##_Ref207117602)](##_Ref215568526)

[[**LiDAR** light detection and ranging](##_Ref207117602)](##_Ref215568526)

[[**LULC** Land Use Land Classification](##_Ref207117602)](##_Ref215568526)

[[**MRMS** multi-radar multi-sensor](##_Ref207117602)](##_Ref215568526)

[[**NAVD 88** North American Vertical Datum of 1988](##_Ref207117602)](##_Ref215568526)

[[**NID** National Inventory of Dams](##_Ref207117602)](##_Ref215568526)

[[**NLCD** National Land Cover Database](##_Ref207117602)](##_Ref215568526)

[[**NLD** National Levee Database](##_Ref207117602)](##_Ref215568526)

[[**NOAA** National Oceanic and Atmospheric Administration](##_Ref207117602)](##_Ref215568526)

[[**NSE** Nash-Sutcliffe Efficiency](##_Ref207117602)](##_Ref215568526)

[[**NSI** National Structure Inventory](##_Ref207117602)](##_Ref215568526)

[[**NWS** National Weather Service](##_Ref207117602)](##_Ref215568526)

[[**PBIAS** percent bias](##_Ref207117602)](##_Ref215568526)

[[**PC** personal computer](##_Ref207117602)](##_Ref215568526)

[[**PDT** project delivery team](##_Ref207117602)](##_Ref215568526)

[[**PMF** probable maximum flood](##_Ref207117602)](##_Ref215568526)

[[**PMP** probable maximum precipitation](##_Ref207117602)](##_Ref215568526)

[[**POR** period of record](##_Ref207117602)](##_Ref215568526)

[[**PRISM** Parameter-elevation Regressions on Independent Slopes Model](##_Ref207117602)](##_Ref215568526)

[[**PWP** Project Work Plan (general)](##_Ref207117602)](##_Ref215568526)

[[**QA** quality assurance](##_Ref207117602)](##_Ref215568526)

[[**QC** quality control](##_Ref207117602)](##_Ref215568526)

[[**QL2** quality level 2](##_Ref207117602)](##_Ref215568526)

[[**R** storage coefficient](##_Ref207117602)](##_Ref215568526)

[[**R<sup>2</sup>** coefficient of determination](##_Ref207117602)](##_Ref215568526)

[[**RAM** random access memory](##_Ref207117602)](##_Ref215568526)

[[**RFC** River Forecast Center](##_Ref207117602)](##_Ref215568526)

[[**RMSE** root-mean-square-error](##_Ref207117602)](##_Ref215568526)

[[**RSR** root-mean-square-error–observations standard deviation ratio](##_Ref207117602)](##_Ref215568526)

[[**SLTT** state, local, tribal, and territorial](##_Ref207117602)](##_Ref215568526)

[[**SNODAS** Snow Data Assimilation System](##_Ref207117602)](##_Ref215568526)

[[**SOP** standard operating procedure](##_Ref207117602)](##_Ref215568526)

[[**S-PWP** Scoping Project Work Plan](##_Ref207117602)](##_Ref215568526)

[[**SPF** standard project flood](##_Ref207117602)](##_Ref215568526)

[[**SST** stochastic storm transposition](##_Ref207117602)](##_Ref215568526)

[[**SSURGO** Soil Survey Geographic Database](##_Ref207117602)](##_Ref215568526)

[[**STATSGO** State Soil Geographic Database](##_Ref207117602)](##_Ref215568526)

[[**SWE** Snow Water Equivalent](##_Ref207117602)](##_Ref215568526)

[[**SWE-ELM** Shallow Water Equations, Eulerian-Lagrangian Method](##_Ref207117602)](##_Ref215568526)

[[**SWE-EM** Shallow Water Equations, Eulerian Method](##_Ref207117602)](##_Ref215568526)

[[**SWE-LIA** Shallow Water Equations, Local Inertial Approximation](##_Ref207117602)](##_Ref215568526)

[[**TMAC** Technical Mapping Advisory Council](##_Ref207117602)](##_Ref215568526)

[[**TOD** top of dam](##_Ref207117602)](##_Ref215568526)

[[**TP** technical paper](##_Ref207117602)](##_Ref215568526)

[[**U.S.** United States](##_Ref207117602)](##_Ref215568526)

[[**USACE** U.S. Corps of Engineers](##_Ref207117602)](##_Ref215568526)

[[**USBR** U.S. Bureau of Reclamation](##_Ref207117602)](##_Ref215568526)

[[**USGS** U.S. Geological Survey](##_Ref207117602)](##_Ref215568526)

[[UTC Coordinated Universal Time](##_Ref207117602)](##_Ref215568526)

[[**UTF-8** Unicode](##_Ref207117602)](##_Ref215568526)

[[**WBD** Watershed Boundary Dataset](##_Ref207117602)](##_Ref215568526)

[[**WCM** water control manual](##_Ref207117602)](##_Ref215568526)

[[**WSEL** water surface elevation](##_Ref207117602)](##_Ref215568526)

## [[<span id="_Toc217044517" class="anchor"></span>—Task Matrix](##_Ref207117602)](##_Ref215568526)

[[The Task Matrix graphic is located in the Appendix A folder associated with this SOP.](##_Ref207117602)](##_Ref215568526)

## [[<span id="_Toc217044518" class="anchor"></span>—Job Aids](##_Ref207117602)](##_Ref215568526)

[[The Job Aids are located in the Appendix B folder associated with this SOP.](##_Ref207117602)](##_Ref215568526)

## [[<span id="_Toc217044519" class="anchor"></span>—Data Delivery Templates](##_Ref207117602)](##_Ref215568526)

[[The following templates are located in the Appendix C folder associated with this SOP.](##_Ref207117602)](##_Ref215568526)

- [[Folder Structure Demo](##_Ref207117602)](##_Ref215568526)

- [[Calibration Event Selection](##_Ref207117602)](##_Ref215568526)

- [[Calibration Gages Scope](##_Ref207117602)](##_Ref215568526)

- [[Dam Scoping Table](##_Ref207117602)](##_Ref215568526)

- [[Data Manifest](##_Ref207117602)](##_Ref215568526)

- [[FFRD Projection](##_Ref207117602)](##_Ref215568526)

- [[Levee breach Locations](##_Ref207117602)](##_Ref215568526)

- [[Model Linking Register](##_Ref207117602)](##_Ref215568526)

- [[Name Table](##_Ref207117602)](##_Ref215568526)

- [[System Response](##_Ref207117602)](##_Ref215568526)

- [[Vertical Datum Conversion Table.](##_Ref207117602)](##_Ref215568526)

[[<span id="_Toc217044520" class="anchor"></span>—Quality Management\
Templates](##_Ref207117602)](##_Ref215568526)
=====================================================================

[[The following templates are located in the Appendix D folder associated with this SOP.](##_Ref207117602)](##_Ref215568526)

- [[Basin Selection Checklist](##_Ref207117602)](##_Ref215568526)

- [[Breach Input Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Conformance Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Consequences Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Hydraulic Review](##_Ref207117602)](##_Ref215568526)

- [[Hydrologic Review](##_Ref207117602)](##_Ref215568526)

- [[Master Quality Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Meteorology Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Pre-Conformance Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Production Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Reservoir Operations Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Scoping and Data Preparation Review Checklist](##_Ref207117602)](##_Ref215568526)

- [[Technical Oversight Group Review Documentation](##_Ref207117602)](##_Ref215568526)

## [[<span id="_Toc217044521" class="anchor"></span>—Documentation Templates](##_Ref207117602)](##_Ref215568526)

[[The following templates are located in the Appendix E folder associated with this SOP.](##_Ref207117602)](##_Ref215568526)

- [[Basin Reports](##_Ref207117602)](##_Ref215568526)

<!-- -->

- [[Basin Selection Memorandum](##_Ref207117602)](##_Ref215568526)

- [[Scoping and Data Preparation Phase](##_Ref207117602)](##_Ref215568526)

- [[Calibration Phase](##_Ref207117602)](##_Ref215568526)

- [[Conformance Phase](##_Ref207117602)](##_Ref215568526)

- [[Production Phase](##_Ref207117602)](##_Ref215568526)

- [[Summary of Findings and Conclusions](##_Ref207117602)](##_Ref215568526)

<!-- -->

- [[Work Plans](##_Ref207117602)](##_Ref215568526)

<!-- -->

- [[BE-PWP](##_Ref207117602)](##_Ref215568526)

- [[S-PWP](##_Ref207117602)](##_Ref215568526)

- 

## [[<span id="_Toc217044522" class="anchor"></span>—Tools](##_Ref207117602)](##_Ref215568526)

[[The following tools are located in the Appendix F folder associated with this SOP.](##_Ref207117602)](##_Ref215568526)

- [[Calibration App](##_Ref207117602)](##_Ref215568526)

- [[USGS 1-meter Download Tool](##_Ref207117602)](##_Ref215568526)

- [[Breach Regression Equation Spreadsheet](##_Ref207117602)](##_Ref215568526)

- [[Calibration Spreadsheet](##_Ref207117602)](##_Ref215568526)

- [[Simplified Physical widening Rates Spreadsheet](##_Ref207117602)](##_Ref215568526)
