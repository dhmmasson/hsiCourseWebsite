# this is for the AI to generate a course structure document for the academic year 2025-2026

the website should have the following ; 
- a syllabus page with :
    - learning outcomes
    - evaluation criteria
- Schedule page with listing that take from the content folder
- a resources pages with the links to resources 
- One page with the project description
- a content folder with one page per  classes
    - HSI Introduction & Project Presentation D. Masson & A. Disdier, 5 décembre 2025, 2h
    - System Thinking & Complexity D. Masson & A. Disdier, 5 january 2026, 2h
    - HSI Handbook & HSIP D. Masson & A. Disdier, 5 january 2026, 2h
    - Systemic Cognitive Engineering G.A. Boy, 6 january 2026, 2h
    - Functional Cognitive Engineering G.A. Boy , 6 january 2026, 2h
    - Sociotechnical Systems G.A. Boy , 6 january 2026, 2h
    - Introduction of projects D. Masson & A. Disdier, 6 january 2026, 2h
    - Concept of Operations (CONOPS) D. Masson , 2h
    - Projet (HSI Plan), 7 january 2026, 2h
    -  Ethnographic tools R. Duhamel, 7 january 2026 , 2h
    - Scenario-Driven Engineering D. Masson, 7 january 2026, 2h
    - PRODEC & Robot Fleet Management C. Morel & D. Masson, 8 january 2026, 2h
    - Projet (CONOPS), 8 january 2026, 2h
    - System Context and Air Traffic Control A. Disdier , 9 january 2026, 2h
    - Projet (Scenario)  , 9 january 2026, 2h
    - Modeling & MBHSI S. Vales , 9 january 2026, 2h
    - HF Evaluation & HITLS C. Morel & D. Masson , 12 january 2026, 2h
    - Projet (Interim Report) , 12 january 2026, 2h
    - Training in HSI P. Palanque , 2h
    - Prelinary Review (Soutenance 1), 2h
    - QCM , 2h
    - Projet (Solution Design), 4h
    - Projet (Solution Design - 2), 4h
    - Risk-Taking Prevention & Design E. Quillerou & P. Badets, 2h
    - Projet (Final Design and Report), 2h
    - Final Review (Soutenance 2), 2h

## Learning Outcomes
By the end of this course, students will be able to:
- Understand the principles of Human-System Integration (HSI) and its application in complex systems.
- Analyze and evaluate sociotechnical systems using systemic User Centered Design approaches.
- Develop comprehensive HSI plans and Concept of Operations (CONOPS) for various projects.
- Apply scenario-driven engineering techniques in system design.
- Utilize modeling and MBHSI methodologies to enhance human factors in system design.

## Project Description
The course project involves the development of a comprehensive Human-System Integration (HSI) Design for a specified system. 
Students will work in teams to create an HSI plan, Concept of Operations (CONOPS), and scenario-driven designs. 

The project will culminate in a final report and presentation, demonstrating the application of course concepts to real-world challenges in HSI.

The subject is the design of a Distributed Control and Command Center for a nano-satellite. 

The New Aquitaine Academic Space Center (NAASC30) is engaging students in the design, launch, and operation of CubeSat-class nanosatellites as part of an inter-institutional program. A cornerstone of this program is the development of a Control and Command Center (CCC) distributed across four engineering schools. This sociotechnical system aims to enable students from multiple campuses to collaboratively operate real nanosatellite missions. The FlexTech Chair at ESTIA provides the research context, with a mission to integrate Human-System Integration (HSI) into modern systems engineering through new methodologies, demonstrators, and educational initiatives (notably via the PRODEC platform). HSI is defined as an essential transdisciplinary approach within systems engineering that ensures human, technical, and organizational elements are appropriately addressed across the system lifecycle and within its operational context. In practice, this means designing systems like the CCC with human users in mind from the outset, rather than merely adding a user interface onto an existing design. The FlexTech Chair promotes scenario-based design and human-in-the-loop experimentation as key strategies for HSI in complex domains such as rail, aviation, and now space systems.

The CCC under development serves as a real-world demonstrator for these HSI approaches in the space domain. It will use existing ground segment technology provided by partners: for example, the company U-Space (in collaboration with CNES) has developed a "Simple Control Center" (SCC) software tool that provides a user-friendly interface to command and control small satellites. Figure 1 below shows an example of this SCC interface, which connects to ground stations and offers dashboards for telemetry and telecommand. This tool provides a starting point for the academic CCC's capabilities, ensuring students have a functional system for satellite operations from day one.

Figure 1: The U-Space "Simple Control Center" (SCC) interface for satellite operations, which will be leveraged in the Academic Space Center's distributed CCC.

Despite this technical head-start, the distributed nature of the CCC and its educational context pose unique HSI challenges that motivate this research. High student turnover and a transient, voluntary workforce mean the system must accommodate continually changing operator populations. Knowledge and expertise cannot be assumed to accumulate in any one individual over time – instead, the CCC itself must be designed to be resilient to these human resource dynamics. Additionally, with the CCC spread across four locations, we anticipate scenarios where control authority and situational awareness might shift between sites. Effective governance models and coordination mechanisms are needed to ensure "seamless" control transitions across the distributed center. These challenges go beyond pure technical design; they require a socio-technical approach addressing human roles, training, procedures, and supporting tools – all underpinned by scenario-driven design to capture the richness of real operations.

Problem Statement
Complex Sociotechnical System: The academic CCC is a prime example of a complex sociotechnical system. It involves multiple human operators (students, supervisors) distributed geographically, interacting with software tools (like the SCC) and hardware (ground stations, satellite subsystems) to carry out mission operations. Such systems are characterized by emergent behaviors and strong coupling between technical and human elements. In the CCC, emergent situations could arise from unpredictable combinations of human actions (or inactions), environmental events, and system states – especially given the operators' varied experience levels. A major cause of unexpected outcomes in sociotechnical systems is sensitivity to operational context, i.e. the changing conditions and situations in which the system operates. A guiding premise is that to design effectively for the CCC, we must model and understand it in context – capturing how different scenarios (nominal missions, anomalies, handovers between operators, etc.) play out and what resources (human or technical) are needed. We need to anticipate emergent properties by "maximizing description of emergent properties in scenarios and mission definitions", echoing complexity management advice from INCOSE. In short, the problem is how to design a resilient, user-centered CCC that functions robustly despite high operator turnover and distributed operations.

Key HSI Challenges: Three intertwined HSI challenges define our problem space:

1. Knowledge Continuity under High Turnover: Students may participate for limited durations (a semester or a year), after which new students take over. Without special design measures, important operational knowledge can be lost at each handover. The CCC must somehow "embed" memory of past operations and lessons, or provide mechanisms to transfer knowledge between outgoing and incoming operators. This includes shift-to-shift handovers (daily or weekly shifts) and generation-to-generation handovers (yearly student cohorts). The open question is how to achieve resilience to turnover – ensuring continuity of mission situational awareness, safety, and efficiency as people rotate.
2. Support for Shift Transitions and Training: Linked to the above is the need for effective knowledge transfer during shifts. In professional settings, this might be handled with standardized shift briefings or long overlap times, but in a student context the process must be intuitive and reliable even for novices. We envision an "AI butler" concept – an intelligent assistant that could, for example, observe and log key events during an operator's session and then brief the next operator on what happened and what to watch for. This could also serve as a training aid, prompting users with relevant information or checklists. The research must determine what form such an AI assistant should take (chatbot, smart dashboard, etc.), and how it can integrate into operations without causing distraction or complacency.
3. Distributed Control and Governance: In a distributed control center, responsibilities might shift between sites (e.g., one school handles communication passes in the morning, another in the afternoon), or different sites might oversee different subsystems concurrently. We must explore governance models that define how decisions are made and authority is delegated across the four locations. For instance, do we designate a "lead site" at any given time, or do all sites operate peer-to-peer with a consensus protocol? What procedures ensure that all operators maintain a coherent picture of the mission? This aspect involves organizational design as much as technical design – clarifying roles, communication protocols, and fallback plans (for example, if one node drops offline unexpectedly). The goal is to avoid confusion or conflicts in control that could jeopardize the mission, while leveraging the distributed nature for greater resilience (e.g., another site can take over if one site's hardware fails or if their students are unavailable).
In summary, the research problem centers on designing the CCC to be a flexible, scenario-resilient system that gracefully handles the dynamic context of student-led operations. It is insufficient to treat this as a standard engineering project; instead, it requires an HSI-driven approach that explicitly factors in human operators, their learning curves and turnover, and the complex interactions between multiple human teams and technical systems.


