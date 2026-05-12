Future of Flood Risk Data

Methodology Standard Operating Procedure—Inland

Volume I—Programmatic Context

Version 1 Draft

December 2025

This page is intentionally blank.

Contents

Executive Summary [6](#executive-summary)

EX.1 Goals [6](#ex.1-goals)

EX.2 Acquisition of National Flood Risk Dataset [6](#ex.2-acquisition-of-national-flood-risk-dataset)

EX.3 Modeling Approach [7](#ex.3-modeling-approach)

EX.4 Foundational Data [8](#ex.4-foundational-data)

EX.5 Standard Operating Procedures Development Cycle [8](#ex.5-standard-operating-procedures-development-cycle)

EX.6 Use of Study results from SOP Version 1 [8](#ex.6-use-of-study-results-from-sop-version-1)

EX.7 Quality and Consistency [8](#ex.7-quality-and-consistency)

EX.7.1 Review Plan [8](#ex.7.1-review-plan)

EX.7.2 Qualifications [8](#ex.7.2-qualifications)

EX.7.3 Training [9](#ex.7.3-training)

Section 1 —Future of Flood Risk Data Initiative [10](#future-of-flood-risk-data-initiative)

1.1 Objectives of The Future of Flood Risk Data Initiative [10](#objectives-of-the-future-of-flood-risk-data-initiative)

1.2 Desired Outcomes [10](#desired-outcomes)

1.3 Related Activities [11](#related-activities)

1.4 Standard Operating Procedure Development—Charge to the U.S. Army Corps of Engineers [11](#standard-operating-procedure-developmentcharge-to-the-u.s.-army-corps-of-engineers)

1.5 Requirements for Methodology [12](#requirements-for-methodology)

1.5.1 Future of Flood Risk Requirements [12](#_Toc217381907)

1.6 Principles for Methodology Selection [12](#_Toc217381909)

1.6.1 Leverage Existing Data [13](#_Toc217381910)

1.6.2 Improve Existing Models [13](#_Toc217381911)

1.6.3 Sustainably Scale to the Cloud [13](#_Toc217381912)

1.6.4 Improve Water Resources Risk Modeling [13](#_Toc217381913)

1.6.5 Foster Collaboration and Coordination [13](#_Toc217381914)

1.7 Selected Methodology [13](#_Toc217381915)

Section 2 —Program Delivery [15](#_Toc217381916)

2.1 Program Organizational and Governance Structure [15](#_Toc217381917)

2.1.1 Steering Committee [16](#_Toc217381918)

2.1.2 Technical Oversight Group [16](#_Toc217381919)

2.1.3 National Implementation Management Group [16](#_Toc217381920)

2.1.3.1 Federal Emergency Management Agency Program Manager [16](#_Toc217381921)

2.1.3.2 U.S. Army Corps of Engineers Program Manager [17](#_Toc217381922)

2.1.3.3 Federal Emergency Management Agency Headquarters Engineering Staff [17](#_Toc217381923)

2.1.3.4 Technical Development Lead [17](#_Toc217381924)

2.1.3.5 Modeling Implementation Lead [17](#_Toc217381925)

2.1.3.6 Review Manager [17](#_Toc217381926)

2.1.3.7 Dam and Levee Lead [17](#_Toc217381927)

2.1.3.8 Training Coordinator [18](#_Toc217381928)

2.1.3.9 Federal Emergency Management Agency Contracting Representative [18](#_Toc217381929)

2.1.3.10 Cloud Environment Support Lead [18](#_Toc217381930)

2.1.3.11 Software Support Lead [18](#_Toc217381931)

2.1.3.12 Software Maintenance Team [18](#_Toc217381932)

2.1.3.13 Documentation Lead [18](#_Toc217381933)

2.1.3.14 Consequences Lead [19](#_Toc217381934)

2.2 Typical Individual Basin Team Structure [19](#_Toc217381935)

2.2.1 Scoping and Data Preparation Team Structure [20](#_Toc217381936)

2.2.1.1 Technical Lead [20](#_Toc217381937)

2.2.1.2 Project Manager [21](#_Toc217381938)

2.2.1.3 Federal Emergency Management Agency Regional Representative [21](#_Toc217381939)

2.2.1.4 Stakeholders [21](#_Toc217381940)

2.2.1.5 Data Providers [21](#_Toc217381941)

2.2.2 Basin Execution Team Structure [21](#_Toc217381943)

2.2.2.1 Basin Execution Technical Lead [24](#_Toc217381944)

2.2.2.2 Basin Execution Project Manager [25](#_Toc217381945)

2.2.2.3 Federal Emergency Management Agency Regional Representative [25](#_Toc217381946)

Glossary [26](#_Toc217381947)

List of Acronyms and Abbreviations [28](#_Toc217381948)

List of Figures

Figure EX.1. Map of Hydrologic Unit Code 4 Basins from the Continental United States Watershed Boundary Dataset [7](#_Toc214614869)

Figure 1.1. Key Objectives of Future of Flood Risk Data Imitative [10](#_Toc214614870)

Figure 2.2. High Level Schematic of FFRD Program Team Structures [16](#_Toc214614871)

List of Tables

Table 2.1. Basin Scoping and Data Preparation Team Members [20](#_Toc214614877)

Table 2.2. Basin Execution Project Delivery Team Leads [23](#_Toc214614878)

Table 2.3. Basin Execution Project Delivery Team Members [23](#_Toc214614879)

# Executive Summary

There is widespread national interest in the development of foundational flood risk data. This Standard Operating Procedure (SOP) outlines a modern approach for producing consistent, efficient, and high-quality flood hazard and risk information across the United States. Leveraging advancements in data infrastructure, modeling techniques, and computational tools, the SOP provides a nationwide framework that supports the Future of Flood Risk Data (FFRD) initiative—delivering scalable, science-based information to improve decision-making and risk communication at all levels of government.

## EX.1 Goals

The FFRD initiative aims to deliver an open, scalable, and scientifically robust national flood risk dataset that allows for the shift from historic binary risk portrayal to a wholistic graduated portrayal of flood risk. This dataset will support federal, state, local, tribal, and territorial (SLTT) partners in identifying and managing flood risks. By integrating modern modeling, mapping, and data infrastructure, FFRD redefines how flood risk is developed, analyzed, and communicated nationwide.

## EX.2 Acquisition of National Flood Risk Dataset

The FFRD program will be implemented using a basin-by-basin approach based on the Watershed Boundary Dataset (WBD), with Hydrologic Unit Code 4 (HUC-4) watersheds serving as the standard unit for planning. For major rivers, upstream probabilistic inputs are essential; therefore, the program follows an upstream-to-downstream sequence, allowing outputs from earlier studies to directly inform downstream analyses and increasing modeling efficiency and consistency.

<span id="_Toc214614869" class="anchor"></span>Figure EX.1. Map of Hydrologic Unit Code 4 Basins from\
the Continental United States Watershed Boundary Dataset

<img src="media/image1.png" style="width:6.5in;height:4.67988in" alt="Map showing the contiguous United States overlaid with the HUC4 watershed boundaries." />

## EX.3 Modeling Approach

The FFRD methodology outlined in this SOP employs an integrated modeling framework that spans the full hydrologic cycle and the spatial extent of a watershed. This approach is designed to characterize the movement of water through atmospheric processes, overland flow, built infrastructure, and ultimately to damageable assets within the floodplain.

To achieve this, the methodology links a series of individually calibrated models, enabling seamless data transfer from one component to the next. This end-to-end modeling system ensures that outputs from meteorological models feed directly into hydrologic and hydraulic models, maintaining consistency and accuracy throughout the simulation process.

A central component of this methodology is the use of Stochastic Storm Transformation (SST), which generates synthetic rainfall events from an existing observed precipitation dataset. These synthetic events drive both all hydrologic and hydraulic simulations. The resulting outputs support the quantification of flood frequency and enable the development of both event-based and graduated flood hazard and risk products.

## EX.4 Foundational Data

The foundational dataset produced through these standardized, nationwide procedures will serve as a high-quality, foundational flood risk product with consistent coverage across the country. Though developed at a national scale, this dataset is intended to provide robust and reliable baseline information that supports a wide range of applications and may be leveraged for more detailed local studies. All models and datasets will be stored using consistent data management protocols to ensure accessibility, transparency, and long-term usability. This foundational product establishes a nationally consistent framework for flood risk analysis, enabling both strategic planning at broad scales and the development of more refined, site-specific models where needed.

## EX.5 Standard Operating Procedures Development Cycle

The standards and procedures outlined in this SOP apply to all FFRD modeling efforts initiated during calendar year 2026. While new techniques are actively being developed to enhance the quality and efficiency of FFRD products, improvements will be incorporated into future versions of the SOP. Modeling efforts that begin in 2026 will not attempt to integrate these emerging methods. As a result, change management for in-progress projects is expected to be minimal.

## EX.6 Use of Study results from SOP Version 1

Version 1 applies certain practical approaches that allow efficiently progress towards a final-state SOP, with the understanding that future investigations in the are needed in improve the reliability of study results. Care should be taken in the application outputs produced from early FFRD pilots and validation basins.

## EX.7 Quality and Consistency

This SOP defines technical work aimed at well-trained teams capable of executing modeling of complex systems. Execution of FFRD production according to this SOP will require large teams with diverse skill sets.

### EX.7.1 Review Plan

Quality and consistency of national level flood risk datasets produced via this SOP is critical. Several quality control (QC) checks are explicitly defined. A national level Technical Oversight Group (TOG) is responsible for the national consistency, review, and approval of FFRD products after each phase of production. Section [2.1.2](#_Ref214621843) describes this in more detail.

Additionally, there is a national level support organization that ensures the FFRD program production can be coordinated and managed across basins. The national level support organization also ensures qualified teams tasked with executing FFRD production have access to training, guidance, and other support necessary for success.

### EX.7.2 Qualifications

Certain minimum qualifications for staff involved with FFRD project execution are recommended for successful project execution. Section 2 describes critical team member roles and qualifications for those roles.

### EX.7.3 Training

Training plans are not directly described in this SOP but will be critical for successful execution of FFRD modeling for a basin.

—Future of Flood Risk Data\
Initiative
===========================

## Objectives of The Future of Flood Risk Data Initiative

The Federal Emergency Management Agency (FEMA) provides a comprehensive and dynamic picture of the nation’s flood hazards through the FFRD initiative. The FFRD initiative has four high level objectives:

1.  Shift from binary to probabilistic flood risk analysis.

2.  Modernize data management and delivery of flood risk data.

3.  Empower private and SLTT stakeholders.

4.  Drive risk-informed actions.

<span id="_Toc214614870" class="anchor"></span>Figure 1.1. Key Objectives of Future of Flood Risk Data Imitative

<img src="media/image2.png" style="width:6.5in;height:2.79722in" />

The FFRD initiative intends to leverage available data and resources to provide publicly accessible data and modeling capability to meet the statutory requirements of 42 U.S. Code 4001 §§ et seq. including those laid out in the [Biggert-Waters Flood Insurance Reform Act of 2012](https://www.govinfo.gov/content/pkg/PLAW-112publ141/pdf/PLAW-112publ141.pdf) (BW-12), the [National Flood Insurance Act of 1968](https://www.fema.gov/sites/default/files/2020-07/national-flood-insurance-act-1968.pdf) (as amended), the Flood Insurance Protection Act of 1973, the [National Flood Mapping Program, and the Technical Mapping Advisory Council](https://www.fema.gov/fact-sheet/technical-mapping-advisory-council-tmac) (TMAC). The initiative also follows recommendations of the [Government Accountability Office](https://www.gao.gov/) (GAO) and the [National Academy of Sciences](http://www.nasonline.org/) (NAS). Ultimately, the FFRD initiative aims to increase risk awareness across the nation by mapping residual risk for all populated areas and areas of possible population growth, including areas protected by dams, levees, or other flood control structures now and in the future.

## Desired Outcomes

The FFRD initiative provides a national water resources risk model for coordinated and consistent flood risk management for water resources. The FFRD initiative provides flood hazard or flood risk information to federal agencies, SLTT governments, and the general public so they can make risk-based decisions about their communities, homes, and families.

To succeed in achieving all four tenets of the initiative, FFRD data must include a mixture of frequency-based hydraulics and hydrology (H&H) data and consequence data resulting in graduated hazard and graduated risk products. Additionally, this unified perspective provides data to support public risk communication to inform individual choices related to water resource risks.

Developing foundational datasets and modeling frameworks can improve capabilities across multiple use cases. Coordinating these efforts and investments can reduce duplication and cost of future development and applications. FFRD intends to reduce the cost of producing reliable and consistent risk-based modeling output, improving the collective ability to manage risk through interagency collaboration. Reducing the cost of data collection and modeling increases the capacity to focus on common operating procedures, improved communication, and coordinated risk management.

Currently, water resources are managed across multiple agencies each with specific congressional authorities. The agencies with a common focus of water resources management create an environment where similar tools are often created multiple times within the same agency. Developing a standardized framework to support the integration of these different tools, or a space for collaboration on jointly developed tools, would reduce redundancy and inconsistency across the agencies. A common framework can facilitate data and model discovery, collaboration, and information exchange.

Coordinated development by multiple agencies or organizations within an agency leads to experimentation and diversification of possible solutions to a problem. To facilitate joint problem solving, information must be shared with the broader audience in a way that supports leveraging the work and creativity of everyone in pursuit of solving complex problems.

In addition to the scientific advantages of coordination among agencies, collaboration and coordination lead to consistent messaging, as inconsistent communication erodes public trust in the water resources community’s ability to provide meaningful and actionable information.

## Related Activities

FEMA is working towards a risk-informed National Flood Insurance Program (NFIP) through a variety of efforts. The NFIP’s current insurance pricing approach marks a significant move towards more graduated risk products through the development of insurance rates based on risks broader than the 100-year floodplain. To accommodate this approach, FEMA invested in methodologies such as mapping data integration (MDI) to leverage existing mapping products and supplement with available data producing expected annual damages (EADs) for structures throughout the floodplain. Additionally, FEMA invested heavily in the Probabilistic Flood Risk Analysis (PFRA) process, adding high fidelity modeling to support evaluation of EAD at structures supporting risk rating. These products came with significant investments and many lessons transferable to the FFRD initiative were learned. FEMA is developing two-dimensional (2D) base-level engineering (BLE) that may support the FFRD initiative broadly by providing detailed 2D Hydrologic Engineering Center-River Analysis System (HEC-RAS) models across the nation.

## Standard Operating Procedure Development—Charge to the U.S. Army Corps of Engineers

In support of the FFRD initiative, the U.S. Army Corps of Engineers (USACE) collaborated with FEMA to develop a recommended methodology and framework for modeling and data service capabilities. FEMA also charged USACE with developing standard procedures deliver a consistent nationwide flood risk dataset.

## Requirements for Methodology

The procedures detailed throughout this SOP follow directly from the previous USACE report outlining the recommended methodology at a high level. The recommendation met the minimum requirements originally provided by FEMA (listed in Sections [1.5.1 and [1.5.2](#_Ref214621921)).](#_Ref214621915)

### [<span id="_Ref214621915" class="anchor"><span id="_Toc217381907" class="anchor"></span></span>Future of Flood Risk Requirements](#_Ref214621915)

[The foundational core requirements for FFRD methodology, models and data are elaborated below:](#_Ref214621915)

- [Methods must be applicable for all watersheds within the United States and its territories, despite differences in geography, watershed characteristics, or local conditions](#_Ref214621915)

- [Resulting flood risk products should be accurate and clearly communicate inherent uncertainties and limitations without implying a false sense of precision](#_Ref214621915)

- [Provide model and data storage standards that allow for a development of a repository that ensures all datasets are findable, accessible, interoperable and reusable.](#_Ref214621915)

- [Models, procedures and results must be traceable and re-producible allowing them to be leveraged as the foundation for a wide array of possible uses such as alternative analysis or local refinement.](#_Ref214621915)

- 

- 

- [Leverage data from partners where possible and contribute to national level datasets with newly generated data.](#_Ref214621915)

- 

- 

- 

- 

- [Account for water management systems where they appreciably impact flood hazard](#_Ref214621915)

- 

- [Account for the contribution of possible dam and levee breaches to flood risk](#_Ref214621915)

- 

- 

- 

- 

- [Provide flood risk assessment for all locations with 2D hydraulic modeling throughout the watershed, accounting for both pluvial and fluvial flood sources](#_Ref214621915)

- 

- 

- [Procedures must provide guidance on modeling approaches for stormwater drainage systems, including areas with sparse information to enable reasonable flood risk estimates](#_Ref214621915)

- 

- [Procedures must provide guidance on calibrating models and subsequent conformance procedures in regions with and without historical records](#_Ref214621915)

- [Provide both pluvial and fluvial flood hazard data across the range of natural variability from the 1/10 to the 1/2,000 annual exceedance probability (AEP)](#_Ref214621915)

- [Portray the uncertainty around the natural variability of flooding in a watershed](#_Ref214621915)

- 

- [Support consequences modeling as part of the modeling sequence or as a post process](#_Ref214621915)

- 

## [<span id="_Toc217381909" class="anchor"></span>Principles for Methodology Selection](#_Ref214621915)

[Several high-level principles emerged as part of the methodology selection process and are described below.](#_Ref214621915)

### [<span id="_Toc217381910" class="anchor"></span>Leverage Existing Data](#_Ref214621915)

[Many necessary datasets exist supporting the FFRD modeling effort. Data leveraged to support this effort include terrain data, hydrologic data, levee data, dam data, economic data, and data regarding other critical infrastructure. Some necessary datasets do not exist while others are duplicated across agencies. Coordination to collect missing data and to strategically reduce duplicative datasets is central to the development of the national water resources model. Centralizing foundational datasets to collectively improve the national ability to model flood related hazards and risks is vital to meeting FFRD objectives.](#_Ref214621915)

### [<span id="_Toc217381911" class="anchor"></span>Improve Existing Models](#_Ref214621915)

[Existing models were designed to meet objectives of a given water resource authority or a specific study. In many cases, existing models may not meet the diverse user requirements spanning authorities across multiple water resources agencies. Developing tools to support all event frequencies as opposed to creating tools focusing on specific frequencies (i.e., floods or low water conditions) is important in developing a cohesive risk management framework. This requires improvements to existing models or integration of exiting models to meet additional requirements.](#_Ref214621915)

### [<span id="_Toc217381912" class="anchor"></span>Sustainably Scale to the Cloud](#_Ref214621915)

[Many existing tools require substantial computational resources and were created for use on a personal computer (PC). Shifting PC-based applications into the cloud is an inefficient use of cloud resources. Moving forward, building sustainable, scalable, and certified tools targeted for the cloud environment to leverage the collective knowledge of the water resources community will improve the computational capability of the entire community. The FFRD initiative is adopting a cloud-first design for the framework, data access, and software as service capabilities and encourages the advancement of tools leveraged by FFRD towards cloud-native architectures to modernize the management and delivery of flood risk data.](#_Ref214621915)

### [<span id="_Toc217381913" class="anchor"></span>Improve Water Resources Risk Modeling](#_Ref214621915)

[Collectively, the water resources community is interested in improving water resources management. Creating a nationally available water resources risk model provides a common picture of the risk posed by various water resources topics. Interagency partnerships encourage and enable engineers and scientists to review, revise, and re-envision how water resources modeling moves into the future, which improves the state of the science and provides coordinated delivery into the state of the practice.](#_Ref214621915)

### [<span id="_Toc217381914" class="anchor"></span>Foster Collaboration and Coordination](#_Ref214621915)

[The water resources community must work together to understand the floodplain activities of each agency or jeopardize intensifying the current risk to the nation. Coordination on water resource risk management projects can offset efforts to tame the environment while coordinating the collective efforts of the entire water resource community. Efforts such as collaboration between agencies on developing an integrated model and providing consistent underlying information for water resource risk data supports coordination of overall integrated water resources management.](#_Ref214621915)

## [<span id="_Toc217381915" class="anchor"></span>Selected Methodology](#_Ref214621915)

[The selected methodology described in this this SOP can be characterized as follows:](#_Ref214621915)

- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 

> [Utilize sequential meteorologic, hydrology, reservoir simulation, hydraulics, and consequence models by linking inputs to outputs.Perform individual model calibration and validation, utilizing multiple observed historic events.Utilize SST method to generate synthetic storm events.Perform hydrologic modeling to provide base flow and gridded excess precipitation outputs.Perform reservoir simulation modeling to provide outflows from key flood control dams.Account for dam and levee breaches by leveraging available system response probability curves for existing risk assessment studies or other baseline estimates.Perform hydraulic modeling with fully 2D coverage to provide stage, flow, and velocity information at all locations throughout the study basin.Variable resolution of hydraulic modeling outputs based on clearly defined basin characteristics. Higher resolution provided along key streams and urban areas.Utilize consequence modeling that leverages actuarial books, user-provided inventories, or nationally available structure inventories.Apply a stochastic approach by modeling multiple synthetic events per year of a long-term, quasi-continuous simulation.Perform multiple realizations of quasi-continuous simulations to provide quantified uncertainty around all flood risk results.Produce complete picture of flood risk with uncertainty over all probabilities (from 1/10 to 1/2,000 AEP) and over all flood risk metrics.Centralize storage and delivery of all inputs, models, and output data in through the Model Library system, which utilizes cloud storage and role-based access control for all users.Ensure standardized use of geographic projection, vertical datum, time zones, naming conventions, and other important parametersStandardize workflow including well-defined project development phases, each with clear review process and clear deliverables for each step within the phases.Provide multiple job aids, checklists, and templates to assist in production of FFRD products for a basin.Develop tools with standard software development practices on open-source libraries.Develop tools that are extensible through a plugin-based architecture, which allows for future development of tools and procedures around alternative models or added capabilities as models evolve and mature.](#_Ref214621915)

# [<span id="_Toc217381916" class="anchor"></span>—Program Delivery](#_Ref214621915)

[Delivery of consistent modern flood risk data for the entire nation according to the Standard Operating Procedures requires clear protocols for programmatic decision making and technical oversight. It is also critical that project teams developing individual basin projects have access to training and technical support. This section establishes the programmatic level roles and responsibilities.](#_Ref214621915)

## [<span id="_Toc217381917" class="anchor"></span>Program Organizational and Governance Structure](#_Ref214621915)

[A comprehensive organizational and governance structure for the FFRD program serves to clarify the roles, responsibilities, and authorities of individuals/agencies needed to ensure program success. The following sections describe the roles and membership of the Steering Committee, the National Implementation Management Group, and the TOG.](#_Ref214621915)

[<span id="_Toc214614871" class="anchor"></span>Figure 2.2. High Level Schematic of FFRD Program Team Structures](#_Ref214621915)

<table>
<colgroup>
<col style="width: 64%" />
<col style="width: 35%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><a href="#_Ref214621915"><img src="media/image3.png" style="width:4.01319in;height:5.09028in" /></a></th>
<th><p><a href="#_Ref214621915"><strong>Responsibilities:</strong></a></p>
<p><a href="#_Ref214621915"><u>Steering Committee</u></a></p>
<ul class="incremental">
<li></li>
<li></li>
<li></li>
<li></li>
</ul>
<p><a href="#_Ref214621915">Provides directionApproves program changesEnsures adequate resources are providedApplies multi-year perspective<u>National Implementation Management Group</u></a></p>
<ul class="incremental">
<li></li>
<li></li>
<li></li>
</ul>
<p><a href="#_Ref214621915">Manages overall program progressEnsures technical support is available for project teamsProgrammatic quality management<u>Technical Oversight Group</u></a></p>
<ul class="incremental">
<li></li>
<li></li>
<li></li>
<li></li>
</ul>
<p><a href="#_Ref214621915">Ensures consistency among FFRD projects (quality assurance)Identifies emerging needsAdvises on unique technical issuesRecommends program and SOP changes to Steering Committee<u>Individual Basin Project Teams</u></a></p>
<ul class="incremental">
<li></li>
<li></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### [Produces all FFRD productsQC<span id="_Toc217381918" class="anchor"></span>Steering Committee](#_Ref214621915)

[This FFRD Steering Committee provides program direction, ensures adequate resources are provided and applies a multi-year perspective to the program. Membership of Steering Committee is a small group of organizational leaders that oversee the overall direction of the program and the SOP. The steering committee also serves a dispute resolution function and provides direction on unique issues that cannot be resolved at a lower level.](#_Ref214621915)

### [<span id="_Ref214621843" class="anchor"><span id="_Toc217381919" class="anchor"></span></span>Technical Oversight Group](#_Ref214621915)

[The TOG provides consistency at a national level enforcing national standards and consistency. Team members are selected from the federal agencies, FEMA regional representatives, and PTS contractors. PTS contractors should have one representative from each major contract grouping. The TOG meets on a regular basis, during which time modeling teams for multiple basins present their progress and receive feedback and comments. Additionally, the TOG identifies emerging technical needs for the program and advises on unique technical issues which may include recommendations for methodology adjustments.](#_Ref214621915)

[USACE and FEMA work together to establish the TOG composed of subject matter experts (SMEs) who provide technical advice, oversight, and project review at a programmatic level. This panel reduces and manages the risks to the program credibility.](#_Ref214621915)

[The TOG will perform quality assurance (QA) reviews of basin products at multiple defined steps in each project, as described in Volume II of this SOP. The technical team lead for each basin prepares a presentation and presents modeling tasks up to the current level of study for each of the four TOG reviews. The TOG provides comments and feedback, and the modeling team addresses comments pertaining to the study that fall within the scope of the project and SOP. The FEMA program manager or contracting representative is responsible for making decisions on how comments/requests from the TOG relating to program or SOP processes outside of the scope of the specific basin study are addressed.](#_Ref214621915)

### [<span id="_Toc217381920" class="anchor"></span>National Implementation Management Group](#_Ref214621915)

[The National Implementation Management Group manages overall program progress on a national level, ensures technical support is available for individual project teams, advances program methodologies, and serves as the quality management authority for all aspects of the program.](#_Ref214621915)

[Certain roles within the FFRD program and basin execution projects are critical to the overall success of the program yet fall outside the core team structure. These roles, while distinct, are essential for maintaining program consistency, ensuring adherence to established standards, methodologies, and data management practices as outlined in the SOP. Multiple roles within the FFRD program structure may be filled by the same individual, provided they meet the qualifications for each role and have the necessary time and capacity to effectively contribute to both the program and basin studies. The following sections will outline these key positions and their specific responsibilities.](#_Ref214621915)

#### [<span id="_Toc217381921" class="anchor"></span>Federal Emergency Management Agency Program Manager](#_Ref214621915)

[The FEMA program manager is a FEMA HQ representative or designee responsible for overseeing the implementation of the FFRD program at the national level. They play a key role in establishing technical teams, oversight groups, and other programmatic staff, ensuring that all necessary positions are filled with qualified individuals. The program manager is accountable for ensuring the program’s objectives are met, providing guidance, and aligning resources with program goals.](#_Ref214621915)

#### [<span id="_Toc217381922" class="anchor"></span>U.S. Army Corps of Engineers Program Manager](#_Ref214621915)

[The USACE program manager shares responsibility with the FEMA program manager for overseeing implementation of the FFRD program at the national level. They play a key role in establishing technical teams, oversight groups, and other programmatic staff, ensuring that all necessary positions are filled with qualified individuals. The program manager is accountable for ensuring the program’s objectives are met, providing guidance, and aligning resources with program goals.](#_Ref214621915)

#### [<span id="_Toc217381923" class="anchor"></span>Federal Emergency Management Agency Headquarters Engineering Staff](#_Ref214621915)

[FEMA Headquarters Engineering Staff provides significant input on the interpretation of requirements for FEMA as they relate to the FFRD program and guides the implementation of the program and methodology updates.](#_Ref214621915)

#### [<span id="_Toc217381924" class="anchor"></span>Technical Development Lead](#_Ref214621915)

[The technical development lead is responsible for establishing and advancing the technical methodologies applied for the FFRD program. This may include guiding scientific investigations focused on future advances in technology and processes for the program.](#_Ref214621915)

#### [<span id="_Toc217381925" class="anchor"></span>Modeling Implementation Lead](#_Ref214621915)

[The modeling implementation lead coordinates with the individual technical teams to ensure program guidance is applied appropriately and takes a leadership role in training of members of basin teams. This individual also identifies needs for improvements to the FFRD guidance to meet program goals and ensures the execution of those updates.](#_Ref214621915)

#### [<span id="_Toc217381926" class="anchor"></span>Review Manager](#_Ref214621915)

[The review manager is a highly technical expert with comprehensive knowledge of all aspects of the FFRD basin modeling effort. Having acted as a technical lead or held primary technical responsibility in at least two other FFRD basin studies or equivalent studies, they ensure consistency and adherence to established standards and SOPs. The review manager assigns reviewers, oversees the review process, and ensures that QA/QC checklists are followed. They provide overarching guidance and remediation as necessary to maintain quality and consistency. The review manager certifies that reviews are complete, and that the work meets the necessary standards for promotion before the basin is included in the TOG meeting agenda. Additionally, the review manager is responsible for setting the agenda for each TOG meeting and coordinating any required read-ahead materials to facilitate effective working sessions.](#_Ref214621915)

#### [<span id="_Toc217381927" class="anchor"></span>Dam and Levee Lead](#_Ref214621915)

[The dam and levee lead is responsible for coordinating all aspects of dam and levee data that are used for model development as well as ensuring the model outputs meet program needs. This includes leading efforts to improve the National Inventory of Dams (NID) and National Levee Database (NLD) datasets prior to and following FFRD studies.](#_Ref214621915)

#### [<span id="_Toc217381928" class="anchor"></span>Training Coordinator](#_Ref214621915)

[The training coordinator is responsible for assuring adequate training is provided for all technical and procedural aspects of the FFRD program.](#_Ref214621915)

#### [<span id="_Toc217381929" class="anchor"></span>Federal Emergency Management Agency Contracting Representative](#_Ref214621915)

[This individual acts as the contract representative for all non-FEMA entities. The FEMA contracting representative liaises between various contracted entities and is the only team member that may direct contractor work. If basins are staffed with multiple entities, the contracting representative acts as a liaison between the technical team lead and staff, as needed if team members or any key personnel work from disparate contracts. The FEMA contracting representative moderates and approves forum discussions. The FEMA contracting representative will also coordinate actions in support of any requests by TOG outside of current SOP.](#_Ref214621915)

#### [<span id="_Toc217381930" class="anchor"></span>Cloud Environment Support Lead](#_Ref214621915)

[The cloud environment support lead administrates environments, storage, and compute resources; performs container and code repository security reviews; and submits containers to centralized container registries. Additionally, they coordinate with and advise the conformance and production team lead and resolve issues with the cloud provider.](#_Ref214621915)

#### [<span id="_Toc217381931" class="anchor"></span>Software Support Lead](#_Ref214621915)

[This individual may participate in multiple basin projects concurrently. The software support lead attends project delivery team (PDT) meetings, interacts with team members, and elevates systematic issues seen with software, model production, and SOP adherence, while reporting issues to appropriate POCs. They report software issues to the appropriate software developers. The software support lead watches for systematic gaps in the SOP and reports to the documentation lead. They identify issues early in the modeling and conformance process, coordinates with SMEs in the appropriate field, and reports to the program manager. The individual holding this position must be familiar with appropriate resources for resolving issues at each phase of the FFRD project.](#_Ref214621915)

#### [<span id="_Toc217381932" class="anchor"></span>Software Maintenance Team](#_Ref214621915)

[This team includes individuals participating in model maintenance and bug fixes. The software maintenance team coordinates with the expert model and software support team member to record bugs and make minor maintenance and bug fixes as allowed within current contract/scoping limits. The expert model and software support team member collates major bugs and incorporates these issues into long-term improvement plans or future workplans.](#_Ref214621915)

#### [<span id="_Toc217381933" class="anchor"></span>Documentation Lead](#_Ref214621915)

[The documentation lead coordinates SOP maintenance and updates and maintains and updates templates and the folder structure. The lead coordinates with various SMEs, team leads, the expert model and software support team member, the program manager, and FEMA representatives to understand and maintain a list of necessary updates needed for the next SOP update.](#_Ref214621915)

#### [<span id="_Toc217381934" class="anchor"></span>Consequences Lead](#_Ref214621915)

[The consequences lead is a highly technical individual having worked in an active consequences modeling role on at least two FFRD basin projects. This individual possesses the technical experience and knowledge to review consequence data and ensure consistency in consequence modeling across the basin.](#_Ref214621915)

## [<span id="_Toc217381935" class="anchor"></span>Typical Individual Basin Team Structure](#_Ref214621915)

[Multiple team members and skill sets are needed to achieve success in the production an FFRD project. The following sections describe the recommended best practices regarding team composition.](#_Ref214621915)

[The scoping and data preparation phase and the basin execution phases (calibration, conformance, production, and final reporting) may be completed by either one team or two separate teams, which may share overlapping personnel or be entirely distinct. If two teams are assigned, the first team develops and completes the scoping and data preparation. Once the first team's work is completed, approved, and advanced by FEMA and TOG, the second team begins the modeling and reporting phases. These teams are described in Subsections [2.2.1](#_Ref214615710) and [2.2.2](#_Ref214615718). If only one team is assigned, it must fulfill all roles outlined in both sections. Multiple roles within the FFRD team structure may be filled by the same individual, provided they meet the minimum requirements for all roles and have sufficient time to fulfill the mission.\
](#_Ref214621915)

### [<span id="_Ref214615710" class="anchor"><span id="_Toc217381936" class="anchor"></span></span>Scoping and Data Preparation Team Structure](#_Ref214621915)

[Recommended team member roles for the scoping and data preparation phase are provided in [Table 2.1](#_Ref214615641) below.](#_Ref214621915)

[<span id="_Ref214615641" class="anchor"><span id="_Toc214614877" class="anchor"></span></span>Table 2.1. Basin Scoping and Data Preparation Team Members](#_Ref214621915)

| [Role](#_Ref214621915) | [Description](#_Ref214621915) |
|----|----|
| [Technical Team Lead](#_Ref214621915) | [Highly experienced co-leader responsible for overseeing the data collection and preparation phases. They coordinate with key stakeholders, including the TOG, to ensure the successful completion of these phases. The Technical Team Lead Assigns Model Library access and permissions and works closely with the Project Manager to schedule key meetings and facilitate communication with team members and stakeholders.](#_Ref214621915) |
| [Project Manager](#_Ref214621915) | [Co-leader of team; focuses on project scheduling, budget tracking, and upward reporting during the pre-model data collection phase. Collaborates with the technical team lead to ensure alignment on key milestones, manages the development of the S-PWP, and coordinates team and outreach meeting schedules. The project manager ensures that all project aspects are on track and facilitates communication between the team, TOG, and other stakeholders.](#_Ref214621915) |
| [Technical Team](#_Ref214621915) | [Senior technical staff, including Geographic Information System (GIS) specialists, meteorologists, hydrologists, hydraulic engineers, dam and levee fragility analysts, economists, software engineers, and consequences modelers are responsible for assessing the quality of existing datasets, preparing the most relevant and necessary data, and developing the technical scoping elements for the basin execution phases.](#_Ref214621915) |
| [Documentation Specialist](#_Ref214621915) | [Technical team member compiling and editing documentation for technical consistency, spelling, grammar, and formatting.](#_Ref214621915) |
| [Dam and Levee Technical Team Members](#_Ref214621915) | [Technical expert(s) working as a subset of an existing national team responsible for data collection, data refinement, and data analysis needed for developing dam and levee characteristics including location, alignment, and fragility. Team member is also part of the conformance review team, verifying statistical appropriateness of work products produced in the data preparation phase. Dam and levee team leads will exist within the existing national team participating in data refinement.](#_Ref214621915) |

#### [<span id="_Toc217381937" class="anchor"></span>Technical Lead](#_Ref214621915)

[The technical team lead is a highly technical professional with deep experience in flood risk modeling projects that involve complex systems of models. This individual has a broad understanding of geospatial, hydrologic, reservoir operations, hydraulic modeling, and consequences work, providing leadership and oversight across these areas.](#_Ref214621915)

[The technical team lead prepares the technical aspects of the S-PWP, verifies that assigned team roles meet the necessary requirements, and manages Model Library access and permissions for team members. In collaboration with the project manager and FEMA contract representative (when required), the technical team lead coordinates outreach with key stakeholders, including FEMA, the TOG, and regional and local stakeholders.](#_Ref214621915)

[The technical team lead is accountable for the successful completion and review of data collection and preparation tasks. This lead provides technical guidance and oversight while coordinating with team members listed in Table 2.1. Acting as the primary technical liaison between the team and higher-level leadership, the technical team lead ensures effective communication and collaboration.](#_Ref214621915)

[In coordination with the project manager, the technical team lead ensures tasks are completed successfully, leads all presentations to the review manager, TOG, and other stakeholders, and verifies that all hydrologic, reservoir operations, and hydraulic data collection roles are filled by skilled personnel. They also ensure that file systems are maintained, and all data is uploaded, organized, and archived according to SOP standards throughout the project.](#_Ref214621915)

#### [<span id="_Toc217381938" class="anchor"></span>Project Manager](#_Ref214621915)

[The project manager, supported by the technical team lead, is responsible for developing the BE-PWP, which outlines the schedule, funding, and personnel resources required for the study. The project manager oversees budget management and works closely with the technical team lead to ensure adherence to the study schedule. Responsibilities also include providing upward status reporting and supporting all coordination and communication activities.](#_Ref214621915)

[In coordination with the technical team lead, the project manager schedules the initial basin execution kickoff meeting and coordinates meetings with higher-level leadership as required. The project manager may assist the technical team lead with discipline-specific team meetings when needed and facilitates communication with team members, the TOG, and stakeholders. Additionally, the project manager oversees the delivery of all study basin deliverables, including models and documentation, while ensuring project scheduling, budget tracking, and updates for upward reporting are maintained.](#_Ref214621915)

#### [<span id="_Toc217381939" class="anchor"></span>Federal Emergency Management Agency Regional Representative](#_Ref214621915)

[The FEMA regional representative serves a key role in executing the basin project. They interface with the key stakeholders and Coordinating Technical Partners (CTPs) and work with the project manager and technical team lead to plan and staff the execution of the project. They also play a key role in local communication of current modeling efforts and resulting products.](#_Ref214621915)

#### [<span id="_Toc217381940" class="anchor"></span>Stakeholders](#_Ref214621915)

[Key stakeholders may include any parties at local, state, regional, or national level with a vested interest in the flood risk data to be produced through an FFRD study. Examples of key stakeholders include other government agencies (e.g., Tennessee Valley Authority, USGS, United States Bureau of Reclamation), CTPs, and nonprofit organizations maintaining data required for the basin study. Key stakeholder meetings should be held at a regular interval to apprise stakeholders of study progress.](#_Ref214621915)

[<span id="_Toc217381941" class="anchor"></span>Data Providers](#_Ref214621915)

[Data providers are entities that possess datasets may contribute to improved accuracy or resolution of FFRD modeling. Data providers should be engaged during the scoping and data preparation phase of the project to obtain and document available geospatial, modeling, and observed datasets. Incorporation and use of local datasets is the discretion of the FFRD team.](#_Ref214621915)

### [<span id="_Ref214615718" class="anchor"><span id="_Toc217381943" class="anchor"></span></span>Basin Execution Team Structure](#_Ref214621915)

[Tables 2.2 and 2.3 outline the recommended roles and describe the basin execution PDT leads and team members, building on the previously defined pre-model data preparation team roles in Table 2.1. Individuals may fulfill roles on both teams, provided they meet the minimum requirements for each role and are available to effectively support the mission.\
](#_Ref214621915)

[<span id="_Toc214614878" class="anchor"></span>Table 2.2. Basin Execution Project Delivery Team Leads](#_Ref214621915)

| [Role](#_Ref214621915) | [Description](#_Ref214621915) |
|----|----|
| [Technical Team Lead](#_Ref214621915) | [The technical team lead provides technical leadership and ensures effective communication within the team and with key stakeholders, including the TOG. They oversee the development and delivery of technically accurate work products and ensure coordination and outreach efforts are aligned with project objectives. The technical team lead leads and supports hydrologic, reservoir operations, and hydraulic modelers, guiding them through the calibration phase and ensuring alignment with project goals through to basin closeout. They are responsible for scheduling and hosting meetings or delegating as appropriate and ensuring that data is consistently uploaded in a format suitable for future use.](#_Ref214621915) |
| [Project Manager](#_Ref214621915) | [The project manager oversees project scheduling and budget tracking, ensuring alignment with project timelines and budget requirements from the calibration phase through basin closeout. They provide upward reporting updates and maintain clear communication with leadership and stakeholders. The project manager is responsible for developing the BE-PWP and coordinating team and outreach meetings. Working closely with the technical team lead, they schedule key meetings and facilitate communication among team members, the TOG, and stakeholders. Additionally, the project manager oversees the delivery of all study basin deliverables, including models and documentation.](#_Ref214621915) |
| [Conformance and Production Lead](#_Ref214621915) | [The conformance and production lead is a highly technical professional with a strong background in statistical analysis, hydrology, hydraulics, reservoir operations, and consequences modeling. They coordinate with the cloud compute team to ensure the successful completion of the conformance and production phases.](#_Ref214621915) |

[<span id="_Toc214614879" class="anchor"></span>Table 2.3. Basin Execution Project Delivery Team Members (sheet 1 of 2)](#_Ref214621915)

<table style="width:100%;">
<colgroup>
<col style="width: 17%" />
<col style="width: 82%" />
</colgroup>
<thead>
<tr>
<th><a href="#_Ref214621915">Role</a></th>
<th><a href="#_Ref214621915">Description</a></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="#_Ref214621915">Meteorologist/<br />
SST Team Member(s)</a></td>
<td><a href="#_Ref214621915">Technical staff who works through all basin execution phases possessing the technical experience and knowledge to review meteorological data, create homogeneous transposition domains, and develop storm catalog.</a></td>
</tr>
<tr>
<td><a href="#_Ref214621915">Hydrologic Modeler(s)</a></td>
<td><a href="#_Ref214621915">Technical staff responsible for using appropriately acquired data to develop hydrologic models specific to the region (e.g., rainfall-runoff, snowmelt). Ensures models are properly calibrated and validated to achieve accuracy and reliability. Completes tasks in the calibration phase and contributes to overall model refinement and assists as needed for model updates within conformance and production phases.</a></td>
</tr>
<tr>
<td><a href="#_Ref214621915">Hydraulic Modeler(s)</a></td>
<td><a href="#_Ref214621915">Technical staff who works though all phases of study and is responsible for developing and refining 2D hydraulic models using appropriately acquired data. Ensures models are properly calibrated and validated for accuracy and reliability. Completes tasks in the calibration phase and contributes to overall model development and improvement and assists as needed for model updates within conformance and production phases.</a></td>
</tr>
</tbody>
</table>

[\
](#_Ref214621915)

[Table 2.3. Basin Execution Project Delivery Team Members (sheet 2 of 2)](#_Ref214621915)

| [Role](#_Ref214621915) | [Description](#_Ref214621915) |
|----|----|
| [Consequences Modeler(s)](#_Ref214621915) | [Technical staff member who works through all basin execution phases with an understanding of structure inventory data and standard consequences modeling techniques.](#_Ref214621915) |
| [Conformance and Production Team Member(s)](#_Ref214621915) | [Team of experienced modelers from the calibration modeling team. Collectively, the team must understand statistical, hydrologic, hydraulic, reservoir operations, and consequences modeling to complete work in the conformance and production phases.](#_Ref214621915) |
| [Documentation Team Member](#_Ref214621915) | [Technical team member compiles and edits documentation for technical consistency, spelling, grammar, and formatting. This individual works in all phases, with a focus in the reporting phase.](#_Ref214621915) |
| [Cloud Compute Team Member](#_Ref214621915) | [Detail-oriented technical staff member working though conformance and production phases with the appropriate security credentials and authorization to process computes.](#_Ref214621915) |
| [Levee Data Team Member](#_Ref214621915) | [Highly technical team member responsible for data collection, data refinement, and data analysis needed for developing levee characteristics including fragility. This team member works though all phases of work.](#_Ref214621915) |
| [Dam Data Team Member](#_Ref214621915) | [Highly technical team member responsible for data collection, data refinement, and data analysis needed for developing dam characteristics including fragility. This team member works though all phases of work.](#_Ref214621915) |
| [Reviewers](#_Ref214621915) | [Individuals with expertise in hydrology, hydraulics, reservoir operations, consequences modeling, statistics, meteorology, geospatial analysis, and documentation will conduct reviews of pre-model, calibration, conformance, and production work products. Reviewers must possess a thorough understanding of the model specialty they are reviewing. Modelers are prohibited from reviewing work on basins they are actively working on but may serve as modelers for other basins while also performing review duties. Before assuming a reviewer role, a team member must have previously held an active modeling role for at least two FFRD basins or equivalent studies.](#_Ref214621915) |

#### [<span id="_Toc217381944" class="anchor"></span>Basin Execution Technical Lead](#_Ref214621915)

[The basin execution technical lead is a highly skilled professional with experience in flood risk modeling projects that involve complex systems of models. They possess a broad understanding of statistical, hydrologic, reservoir operations, and hydraulic modeling.](#_Ref214621915)

[The basin execution technical lead coordinates with all team members to ensure the successful completion of the calibration, conformance, and production phases. Basin execution technical team members report directly to the technical lead. The technical lead writes the technical aspects of the BE-PWP, verifies that PDT roles are properly assigned, and manages team member Model Library access and permissions. They are responsible for coordinating outreach with key stakeholders, including the program manager, the TOG, and regional and local stakeholders.](#_Ref214621915)

[The basin execution technical lead acts as the technical liaison between the team and higher-level leadership, ensuring that the team completes assigned tasks in coordination with the project manager. They are responsible for leading presentations to the review manager, the TOG, and other key stakeholders.](#_Ref214621915)

[The technical lead verifies that qualified personnel fill all hydrologic, reservoir operations, consequences, and hydraulic modeling roles, and ensures all work is completed successfully. The technical lead also ensures that file systems are maintained, and that all data is uploaded, organized, and archived according to SOP processes throughout the project’s duration.](#_Ref214621915)

#### [<span id="_Toc217381945" class="anchor"></span>Basin Execution Project Manager](#_Ref214621915)

[The study basin project manager, with the assistance of the technical team lead, is responsible for developing the BE-PWP, which outlines the schedule, funding, and personnel resources required for the study. The project manager oversees budget management, working closely with the technical team lead to ensure adherence to the study schedule. They are also responsible for providing upward status reporting and presenting progress to the National Implementation Management Group, as needed.](#_Ref214621915)

[The project manager schedules the initial basin execution kickoff meeting and meetings with higher-level leadership as required. They assist the technical team lead with discipline-specific team meetings when needed and facilitate communication across the team, FFRD management, and other stakeholders. Additionally, the project manager is responsible for overseeing the delivery of all study basin deliverables, including models and documentation, ensuring that all project goals are met on time and within budget.](#_Ref214621915)

#### [<span id="_Toc217381946" class="anchor"></span>Federal Emergency Management Agency Regional Representative](#_Ref214621915)

[The FEMA regional representative serves a key role in executing the basin project. They interface with the key stakeholders and CTPs, and work with the project manager and technical team lead to plan and staff the execution of the project. They also play a key role in local communication of current modeling efforts and resulting products.](#_Ref214621915)

# 

[<span id="_Toc217381947" class="anchor"></span>Glossary**Area/Reach/Location of Interest—**Locations within the watershed where additional model resolution is warranted to support the objective of the FFRD initiative (i.e., urban areas, major rivers, transportation corridors, existing FEMA flood hazard designations, etc.).](#_Ref214621915)

[**Background Mesh—**The initial computational mesh used to create a 2D flow area. References to the background mesh in this document refer to the lowest resolution 2D cells (largest cells) in the mesh employed in areas where more detailed modeling resolution is not needed. Commonly, the background mesh resolution is used in urban areas in the basin that are not near population centers or other key streams.](#_Ref214621915)

[**Bucket**—Specific cloud storage location.](#_Ref214621915)

[**Bathymetry—**The measurement of depth under the water surface in reservoirs, rivers, oceans or other water bodies. In hydraulic modeling, it is common to leverage a model of the bare-earth land surface that includes land elevations assuming a completely dry landscape including underwater elevations.](#_Ref214621915)

[**Directed Acyclic Graphic—**Term used to define the order of model execution that accounts for dependencies between upstream models and downstream models that require inputs from previously computed models](#_Ref214621915)

[**Directory**—Specific file location including path name within larger hierarchy of file storage system.](#_Ref214621915)

[**Event—**An event represents a unique set of parameters derived from antecedent conditions, storm selection and placement, and sampled failure elevations for breachable infrastructure. Simulations generally span a time window allowing the sampled precipitation to cycle through the watershed, i.e., time of concentration.](#_Ref214621915)

[**Flood Hazard—**Hazard caused by flooding described by specific parameters such as water depth or velocity in specific locations.](#_Ref214621915)

[**Key Streams—**FFRD modeling term to define scoped Mesh Development Criteria for uses during model development.](#_Ref214621915)

[**Model Order—**Referring to the sequential order in which each component model must be executed to properly pass outputs from certain models as inputs to other models.](#_Ref214621915)

[**Modeling Unit—**The 2D modeling extent used for hydraulic model development and calibration. Each HUC-4 basin evaluated in the FFRD initiative is sub-divided into modeling units to reduce the computational burden of the model and decrease the model development time. Modeling units are based on major topographic and drainage control features, optimized according to run time. Features considered are location of major reservoirs, stream gages, levees, and population centers or due to the size of the basin. Previous modeling efforts used modeling units varying from 300 to 2,400 square miles with an average of 875 square miles.](#_Ref214621915)

[**Other Streams—**FFRD modeling term to define scoped Mesh Development Criteria for uses during model development.](#_Ref214621915)

[**Realization—**A realization is composed of a set of synthetic years and is used to construct an estimate of a variable-frequency relationship.](#_Ref214621915)

[**Repository**—Specific shared file location.](#_Ref214621915)

[**Secondary Streams—**Streams within the 2D area requiring a refined mesh for which channel bathymetry is not incorporated. Streams are selected prior to the start of modeling. Selection is based on gage locations and significant hydraulic structures (i.e., levees) and informed by the NFHL and NSI data.](#_Ref214621915)

[**Simulation—**A simulation is composed of a set of realizations and is used to describe the knowledge uncertainty around a variable-frequency relationship.](#_Ref214621915)

[**Stochastic Storm Transposition**—Meteorologic technique that applies synthetic rainfall on a study basin leveraging historic storm observations from a larger region with similar meteorologic characteristics.](#_Ref214621915)

[**Synthetic Year (block maxima)**—A synthetic year is composed of a set of independent events and is used to determine the annual maximum values for any variable of interest at any location in the watershed. The construction of the storm database determines the number of events randomly selected. The term quasi-continuous is used to describe the independence of the events in that each simulated event does not persist state across events.](#_Ref214621915)

[System Response Probability (SRP) curves - SRP curves provide a relationship of probability of failure (response) to a flood stage elevation.](#_Ref214621915)

[**Transposition Region**—A large region that can be assumed to have similar meteorologic characteristic to the basin being studies.](#_Ref214621915)

[**Urban Areas—** FFRD modeling term to define scoped Mesh Development Criteria for uses during model development.](#_Ref214621915)

# 

[<span id="_Toc217381948" class="anchor"></span>List of Acronyms and Abbreviations**1D** one dimensional](#_Ref214621915)

[**2D** two dimensional](#_Ref214621915)

[**AEP** annual exceedance probability](#_Ref214621915)

[**BLE** base-level engineering](#_Ref214621915)

[**CTPs** Coordinating Technical Partners](#_Ref214621915)

[**EAD** expected annualized damages](#_Ref214621915)

[**FEMA** Federal Emergency Management Agency](#_Ref214621915)

[**FFRD** Future of Flood Risk Data](#_Ref214621915)

[**GAO** Government Accountability Office](#_Ref214621915)

[**GIS** Geographic Information System](#_Ref214621915)

[**H&H** hydraulics and hydrology](#_Ref214621915)

[**HEC-RAS** Hydrologic Engineering Center River Analysis System](#_Ref214621915)

[**HUC** hydrologic unit code](#_Ref214621915)

[**IRWA** Interagency Reimbursable Work Agreement](#_Ref214621915)

[**MDI** mapping data integration](#_Ref214621915)

[**NAS** National Academy of Sciences](#_Ref214621915)

[**NFHL** National Flood Hazard Layer](#_Ref214621915)

[**NFIP** National Flood Insurance Program](#_Ref214621915)

[**NID** National Inventory of Dams](#_Ref214621915)

[**NLD** National Levee Database](#_Ref214621915)

[**PC** personal computer](#_Ref214621915)

[**PDT** project delivery team](#_Ref214621915)

[**PFRA** Probabilistic Flood Risk Analysis](#_Ref214621915)

[**QA** quality assurance](#_Ref214621915)

[**QC** quality control](#_Ref214621915)

[**SLTT** state, local, tribal, and territorial](#_Ref214621915)

[**SME** Subject matter expert](#_Ref214621915)

[**SOP** standard operating procedure](#_Ref214621915)

[**SST** stochastic storm transposition](#_Ref214621915)

[**TMAC** Technical Mapping Advisory Council](#_Ref214621915)

[**TOG** technical oversight group](#_Ref214621915)

[**USACE** U.S. Corps of Engineers](#_Ref214621915)

[**WBD** Watershed Boundary Dataset](#_Ref214621915)
