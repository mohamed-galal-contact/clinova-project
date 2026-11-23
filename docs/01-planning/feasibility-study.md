# Feasibility Analysis

## 1. Technical Feasibility

The Clinova system is technically feasible, although some risks must be considered.

### Familiarity with Application's Risk is High:

- The development team understands Clinova's core goal of transitioning hospitals and private clinics from paper-based records to a digital environment, but lacks deep hands-on experience with complex clinical workflows such as patient registration, appointment scheduling, queue management, and digital medical records.
- Supporting varying clinic configurations and role-based workflows (for doctors, nurses, and administrative staff) through a multi-tenant SaaS model requires careful domain analysis and workflow modeling.
- Numerous existing healthcare management platforms, standard workflow references, and direct interviews and prototyping with medical staff are available to help validate requirements early.

### Familiarity with the Technology's Risk is Medium:

- The team has solid intermediate experience in Python backend development, relational database management, and advanced data analytics, which provides a strong foundation for core system logic and reporting.
- While frontend experience varies across the team and integrating external AI APIs, secure token-based QR code generation, and ORM-database mappings requires focused technical testing, these gaps can be addressed through modular prototyping.
- The proposed technology stack is mature, well-documented, and supported by established libraries.

**Proposed Technology Stack**

- Backend: Python, Django,
- Frontend: HTML, CSS, JavaScript, React
- Database: Microsoft SQL Server
- ORM: Django ORM
- Authentication: JWT
- Data Analytics: Python, Excel, Power BI, Chart.js
- Version Control: Git and GitHub
- Development Environment: Visual Studio Code
- AI Integration: External AI API
- QR Code: Python QR code libraries

### The Project Size's Risk is Medium:

- The project team consists of 6 members working within a 6-month development period, which is manageable when divided into phased Waterfall Development milestones with clear task ownership.
- Clinova spans several interconnected modules including patient management, appointment scheduling, queue management, digital medical records, secure QR access, analytics dashboards, and an informational AI assistant—requiring close coordination across frontend, backend, and database development.
- Continuous involvement from healthcare users and strict prioritization of essential clinical features will be required to prevent scope creep and meet the 6-month timeline.

### Compatibility's Risk is Medium:

- Clinova is designed to operate as a standalone web-based platform without requiring direct integration into legacy hospital hardware, and its Python/Django backend and React frontend readily support multi-tenant SaaS requirements.
- Python and Django can support the system's backend requirements.
- The proposed frontend technologies should support the system's interface requirements, subject to the team's capabilities.
- Additional technologies may be required to support real-time queues, automated reminders, and future scalability.

## 2. Economic Feasibility

| Line Item                                    |     2026      |    2027     |      2028      |    2029     |    Total     |
| :------------------------------------------- | :-----------: | :---------: | :------------: | :---------: | :----------: |
| **Tangible Benefits**                        |               |             |                |             |              |
| Reduced Administrative Work                  |               |   $24,960   |    $25,958     |   $26,737   |   $77,655    |
| Reduced Missed Appointments                  |               |   $18,720   |    $19,469     |   $20,053   |   $58,242    |
| Reduced Paperwork Costs                      |               |   $3,600    |     $3,744     |   $3,856    |   $11,200    |
| Improved Reporting Efficiency                |               |   $4,680    |     $4,867     |   $5,013    |   $14,560    |
| **(A) Total Benefits**                       |               | **$51,960** |  **$54,038**   | **$55,659** | **$161,657** |
| **(B) Present Value Total Benefits**         |               | **$49,019** |  **$48,094**   | **$46,732** | **$143,845** |
| **Development Costs**                        |               |             |                |             |              |
| Requirements Analysis                        |    $3,500     |     $0      |       $0       |     $0      |    $3,500    |
| UI/UX Design                                 |    $3,500     |     $0      |       $0       |     $0      |    $3,500    |
| Frontend Development                         |    $6,000     |     $0      |       $0       |     $0      |    $6,000    |
| Backend Development                          |    $7,000     |     $0      |       $0       |     $0      |    $7,000    |
| Centralized Database Development             |    $3,500     |     $0      |       $0       |     $0      |    $3,500    |
| Testing & Quality Assurance                  |    $3,000     |     $0      |       $0       |     $0      |    $3,000    |
| **Total Development Costs**                  |  **$26,500**  |   **$0**    |     **$0**     |   **$0**    | **$26,500**  |
| **Operational Costs**                        |               |             |                |             |              |
| Cloud Hosting                                |               |   $3,000    |     $3,000     |   $3,000    |    $9,000    |
| Maintenance & Updates                        |               |   $5,400    |     $5,400     |   $5,400    |   $16,200    |
| Backup & Security                            |               |   $1,800    |     $1,800     |   $1,800    |    $5,400    |
| Technical Support                            |               |   $4,800    |     $4,800     |   $4,800    |   $14,400    |
| Domain & Email Services                      |               |    $600     |      $600      |    $600     |    $1,800    |
| **Total Operational Costs**                  |               | **$15,600** |  **$15,600**   | **$15,600** | **$46,800**  |
| **(C) Total Costs**                          |  **$26,500**  | **$15,600** |  **$15,600**   | **$15,600** | **$73,300**  |
| **(D) Total Benefits - Total Costs**         | **($26,500)** | **$36,360** |  **$38,438**   | **$40,059** | **$88,357**  |
| **(E) Cumulative Net Cash Flow**             | **($26,500)** | **$9,860**  |  **$48,298**   | **$88,357** |              |
| **(F) Present Value Total Costs**            |  **$26,500**  | **$14,717** |  **$13,884**   | **$13,098** | **$68,199**  |
| **Return on Investment (ROI)**               |               |             |    **121%**    |             |              |
| **Break-Even Point**                         |               |             | **0.73 years** |             |              |
| **NPV (PV Total Benefits - PV Total Costs)** |               |             |  **$75,646**   |             |              |

### Intangible Benefits

Improved Patient Satisfaction, Enhanced Data Security & Multi-Tenant Governance, Better Clinical & Executive Decision-Making, and Stronger Market Position

## 3. Organizational Feasibility

### 1. Strategic Alignment

Clinova is aligned with clinics' business objectives of improving operational efficiency, reducing administrative workload, and enhancing patient experience. Its features, including appointment management, digital queue management, automated reminders, and analytics dashboards, support these objectives by streamlining daily operations and improving patient flow.

### 2. Stakeholder Analysis

The main stakeholders involved in Clinova are:

- **Project Champion:** The clinic owner or authorized manager who promotes the project and supports its implementation.
- **Organizational Management:** Clinic management, responsible for supporting the project, allocating resources, and encouraging system adoption.
- **System Users:** Doctors, receptionists, and administrative staff who use the system in daily clinic operations.
- **Patients:** Benefit from easier appointment booking, QR check-in, and improved waiting-time management.

Overall, Clinova appears organizationally feasible. However, this assessment remains preliminary until management support, the appointment of a project champion, and system-user acceptance are validated with potential clinic stakeholders.
