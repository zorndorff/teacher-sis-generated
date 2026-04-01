# Otus Platform: Comprehensive Product & Technical Analysis

> Research compiled from otus.com, help.otus.com, job postings, press releases, and public technical sources.

---

## 1. Company Overview

| Field | Detail |
|-------|--------|
| **Name** | Otus |
| **Headquarters** | Chicago, Illinois |
| **Founded** | 2013 (prototype); officially launched August 2014 |
| **Founders** | Chris Hull and Pete Helfers (both former middle school teachers at Elm Place Middle School, Chicago) |
| **Early Backer** | Andy Bluhm ($2M seed funding, serves as CEO) |
| **Total Funding** | $2.4 million over 2 rounds (bootstrapped, no traditional VC) |
| **Scale** | 200+ districts, 1M+ active learners, 2.5M students served since launch |
| **Certifications** | SOC 2, FERPA compliant, Data Privacy certified, Digital Promise Practitioner-Informed Design |

### Leadership Team
- **Chris Hull** — President & Co-founder
- **Andy Bluhm** — CEO
- **Corey Maxey** — Chief Technology Officer
- **Phil Collins, Ed.D.** — Chief Customer Officer
- **Keith Westman, Ed.D.** — Chief Strategy Officer
- **Samantha Mason** — VP of Client Success

### Mission & Vision
- **Mission:** "Otus provides the tools and data educators, students, and families need to monitor and improve performance."
- **Vision:** "Ensure every educator and the school community has the insights they need to make a difference in students' lives."

---

## 2. Product Positioning

Otus is a **unified K-12 assessment, data, and insights platform**. It is described internally as a "pre-integrated LMS, Assessment Platform, and Data Warehouse."

**Critical distinction:** Otus is **NOT a Student Information System (SIS)**. It complements existing SIS platforms (PowerSchool, Infinite Campus, Skyward, etc.) by layering assessment, grading, analytics, and progress monitoring on top. Roster and demographic data sync nightly from the district's SIS into Otus.

### Core Value Proposition
Eliminate the need for multiple disconnected tools by unifying:
- Assessment creation & delivery
- Standards-based gradebook
- Data aggregation & analytics
- Progress monitoring & MTSS
- AI-powered insights

### Target Market
- **Primary:** K-12 school districts in the United States
- **School types:** Traditional public schools, charter schools, competency-based learning models
- **User personas:** District administrators, school administrators, teachers, students, families
- **Sweet spot:** Districts implementing standards-based grading, common assessments, MTSS frameworks, or data-driven decision making

---

## 3. Complete Feature Inventory

### 3.1 Assessments

#### Assessment Types (from help.otus.com — 116+ articles on Advanced Assessments alone)

| Type | Description | Best For |
|------|-------------|----------|
| **Simple Assessment** | Quick-build with MC, T/F, Short Answer. Supports images, audio, video. Auto-scoring for MC and T/F. | Exit tickets, comprehension checks |
| **Rubric Assessment** | Criterion-based evaluation with multiple descriptors and performance levels. File upload, audio/video recording support. Student submission optional. | Essays, artifacts, performance-based grades |
| **Advanced Assessment** | Powered by Learnosity. 60+ question types across 11 categories. Auto-scoring with partial credit and alternate answers. | Math-heavy and lengthy assessments |
| **Plus(+) Assessment** | Adds a gradebook column for work not completed in Otus. No student-facing component. Supports points and standards-based scales. | Hand-completed worksheets, external assignments |

#### Advanced Assessment Question Types (11 Categories, 60+ Types)

| Category | Question Types |
|----------|---------------|
| **Multiple Choice** | Basic MC (multiple response, block layout), Choice Matrix (standard, inline, labels) |
| **Fill in the Blanks & Labeling** | Cloze Drag & Drop, Cloze Drop Down, Cloze with Text, Label Image (Drag & Drop / Drop Down / Text) |
| **Classify, Match & Order** | Classification, Match List, Order List, Sort List |
| **Written & Recorded** | Essay (Rich Text / Plain Text), Short Text, Audio Recorder, Video Recorder |
| **Highlight & Drawing** | Drawing (compass, ruler tools), Shading, Token Highlight, Hotspot |
| **Math** | Cloze Math, Cloze Math with Image, Math Essay with Rich Text, Desmos Advanced Math |
| **Graphing** | Graphing (full/1st quadrant), Number Line (Drag & Drop / Plot) |
| **Charts** | Bar Chart, Line Chart, Histogram, Dot Plot, Line Plot |
| **Chemistry** | Chemistry Formula, Cloze Chemistry, Chemistry Essay, Cloze Chemistry with Image |
| **Desmos** | Specialized math: Algebra 1/2, Geometry, Statistics, Economics, Calculus |
| **Other** | File Upload, Image Annotation Upload, Rating, Gridded |

#### Assessment Creation & Delivery
- AI-powered question generator (standards-aligned MC, T/F, short answer)
- 60+ engaging question types simulating high-stakes testing
- Custom rubric creation with standards alignment
- Extensive curated item bank (Mastery Item Bank — subscription-based tiers with thousands of items)
- Assessment sharing across classrooms with copy/edit permissions
- Multimedia support and Google Docs integration for submissions
- Paper-based activity scoring (manual digital entry via Plus+ assessments)
- Assessment scheduling: start date, due date, availability windows, time limits with auto-submission
- Multiple attempts permitted
- Randomize question order
- Clone/duplicate assessments
- Send copies to other teachers
- Folder organization for assessments
- Preview mode (see assessment as student would)
- Assessment status tracking: Submitted, Graded, Not Started, On Time, Missing, Late, Excused, Excluded
- Include/exclude score from final grade toggle
- Question difficulty categorization: Basic, Intermediate, Advanced
- Subject-specific question guides: ELA, Math, Science, Social Studies/History, Enrichment

#### Pre-Built Assessment Libraries
- 1,000+ "Otus Proficiency Assessments" aligned to Common Core
- Subject coverage: reading, language usage, mathematics
- Curriculum partner assessments (Bridges in Mathematics, Amplify Science, Amplify CKLA, National Geographic, EL Education, Cognia, Exemplars, Horizon Education, Wit & Wisdom)
- Thin Common Cartridge (ThinCC) import for third-party instructional materials

#### Testing & Accessibility Tools
- **Texthelp Speechstream** — Text-to-speech
- **Turnitin** — Plagiarism detection (LTI integration)
- **Desmos** — Interactive math tools (embedded via iFrame)
- **Respondus LockDown Browser** — Test proctoring
- **Otus LockDown Browser Extension** — Chromebook-specific lockdown
- Auto-scoring for MC, T/F, and advanced/interactive question types with partial credit

#### Assessment Analytics
- Assessment Analytics 2.0: class completion rates, performance summaries, item analysis, question breakdowns
- AI-highlighted learning patterns
- Question-level performance analytics
- Targeted student group generation for support/extension
- Standards mastery tracking per assessment
- Printable assessment reports

### 3.2 Gradebook & Grading

#### Two Primary Gradebook Views
- **Assessments View** — All assigned assessments as columns; score display; student submission status; comment functionality; category weighting
- **Standards View** — Each column is a standard; performance level via Mastery Settings; attempt count tracking; detailed performance history per cell; optional total grade conversion

#### Gradebook Modes
- **Standards-based grading** (flagship capability — purpose-built, not retrofitted)
- **Traditional points-based grading** with category weighting (tests, journals, homework, etc.)
- **Hybrid approaches** combining both methods
- Customizable grading scales aligned to school/district systems

#### Standards-Based Grading — 5 Mastery Settings
| Setting | Calculation |
|---------|-------------|
| **Mean** | Average of all standard attempts |
| **Mode** | Most frequently occurring score |
| **Most Recent** | Latest attempt score |
| **Highest** | Peak recorded score |
| **Decaying Average** | Weights recent attempts more heavily (sub-settings: highest and average) |

#### Standards-Based Grading Details
- Standards appear as gradebook columns
- Drill-down shows per-student, per-standard performance over time
- Tracks mastery rather than averaging scores
- AI monitors standards progress at class and individual levels
- Highlights trends in mastery and attempts
- Subgroup analysis with AI-generated insights
- Total Grade Conversion: converts mastery scores to traditional percentage/letter grades

#### Gradebook Features (from help.otus.com — 20 articles)
- Configurable tab order (Standards left/Assessments right or vice versa)
- Manual and digital score entry
- Direct assessment result flow into gradebook
- Assignment management and categorization
- Score overrides and exemptions
- Comment entry per student/assignment
- "Include Score in Final Grade" toggle per assessment
- Grading periods (quarters, semesters, custom timeframes)
- Final grade calculation and submission
- Report card generation:
  - **Points Report Card** — Grades from points gradebook
  - **Standards Report Card** — Mastery of priority standards; classes listed alphabetically; teacher name; optional grading scale key, school logo, family/student signature lines, notes, footer
- Family-facing gradebook view (simplified)
- Individual student gradebook drill-down

#### AI in Grading
- "Otus Insights" embedded chat within gradebook
- Automated analysis of student progress patterns
- Parent-conference preparation with AI-generated talking points
- Real-time data summaries

### 3.3 Data & Analytics

#### Data Centralization
- Consolidates academic, attendance, behavior, and cognitive data
- Integrates data from 15+ external assessment/data platforms
- Nightly SIS sync for roster and demographic data
- Eliminates manual spreadsheet management

#### Analytics Report Types (from help.otus.com — 40 articles)

| Report Type | Description |
|-------------|-------------|
| **Assessment Analytics 2.0** | Class completion rates, performance summaries, item analysis, question breakdowns, printable reports |
| **Standards Analytics (1.0 & 2.0)** | Up to 10 standards simultaneously; horizontal bar charts; filter by assessments, mastery settings, scales, date range; CSV export; student grouping with color coding; drill-down |
| **3rd Party Analytics** | Tiles per uploaded external assessment; unique NWEA and PARCC/IAR displays; Custom Growth Assessment uploads |
| **Attendance Report** | Time-framed attendance reporting with filters |
| **Recognitions Report** | Positive/negative behavior visualization at student or classroom level |
| **Query Reports** | Identify and compare student populations matching criteria across multiple data sources; matrix values for weighted criteria |
| **Historical Analytics** | Compare student cohort performance across multiple school years |
| **Report Cards** | Generate standards-based and points-based report cards |
| **Type Comparison** | Compare performance across assessment types |
| **Exports** | Data export (Main Admin only) |
| **AI Insights** | AI assistant with data-driven recommendations; trends for PLC discussions |

#### Analytics Permissions by Role

| Report | Main Admin | Admin | Teacher |
|--------|-----------|-------|---------|
| 3rd Party Assessments | All students | Permitted students | Own class students |
| Attendance | All | Permitted | Own classes |
| Recognitions | All | Permitted | Own classes |
| Otus Assessments | All | Permitted | Own classes |
| Standards | All | Permitted | Own classes |
| Report Cards | Yes | Yes | No |
| Query Reports | Yes | Yes | No |
| Historical Reports | Yes | Yes | No |
| Exports | Yes | No | No |

#### AI-Powered Analytics
- Transforms complex data into clear visuals
- Pattern recognition across classrooms and schools
- Early warning indicator identification
- Equity analysis across subgroups
- Impact reports for stakeholder communication

#### Audience-Specific Views
- **Administrators:** District-wide and school-level performance tracking with trend highlighting
- **Teachers:** Consolidated student data with AI-surfaced insights
- **Students:** Clear progress visibility and growth insights
- **Families:** Performance overview with strengths and opportunities

### 3.4 Progress Monitoring & MTSS

#### Plan Types / Use Cases
| Category | Examples |
|----------|---------|
| **Academic Support** | Credit recovery, intervention, personalized learning, progress monitoring |
| **Student Services** | Check-in/check-out, observations, SEL assessments, behavior modification, RTI/MTSS |
| **College & Career Readiness** | Pathway planning, graduation progress tracking |
| **Eligibility Tracking** | Gifted identification, at-risk flagging, activity eligibility |

#### Plan Management (from help.otus.com — 20 articles)
- Custom individualized or group plans
- Domains: academics, behavior, attendance, interventions, social-emotional learning
- Customizable templates with overall evaluation scale, sections, and individual items
- Items evaluated on different scales or formatted for text entry
- District-created templates usable by any admin or teacher
- Students added from class lists (teachers) or across sites/grade levels (admins)
- Visual analytics: horizontal bar charts for item status breakdowns with drill-down
- Historical performance tracking: graphs with trendlines showing progress over time
- Achievable milestone setting aligned to student needs
- Plans follow students year to year for seamless transitions
- Plans visible to students and families for home-school collaboration
- Downloadable student summary reports
- Connect student goals to data so scores auto-update
- Small group to district-wide MTSS support

#### Tiered Intervention Support
| Tier | Description |
|------|-------------|
| **Tier 1** | Universal instruction monitoring |
| **Tier 2** | Targeted small-group interventions with frequent progress monitoring |
| **Tier 3** | Intensive one-on-one support with highly individualized interventions |

#### Data Integration for Monitoring
- Universal screening and CBM scores tracked over time automatically
- Benchmarking data flows directly into student plans without manual entry
- Integration with screening tools (FastBridge, i-Ready, MAP Growth)
- Student identification below specific percentiles on universal screening measures
- Social-emotional screener data integration

#### AI in Progress Monitoring
- Real-time identification of students needing additional support
- Highlights which interventions are driving growth
- Identifies where plans need adjusting
- Automated analysis without manual input

#### College & Career Readiness
- Portrait of a Graduate: define and track essential competencies
- Track preparation for college, careers, and life beyond school

### 3.5 Classes & Instruction

#### Class Management (from help.otus.com — 45 articles)
- **Class Info** — Add/remove students, rename class, add co-teachers, manage details
- **Class Board** — Announcement space for homework, projects, daily agendas
- **Student Groups:**
  - District-level groups (admin-created, usable district-wide)
  - Class-level groups (teacher-created, specific to their classes)
  - Used for differentiating instruction, assigning assessments/lessons, filtering analytics, adding to plans
- **Co-Teacher Role** — Full second-instructor access: assign/unassign/grade assessments and lessons, manage class
- **Mailbox** — One-way messaging from teachers to students/families; supports text messaging with country codes
- **Student Profile** — Consolidated data, work artifacts, notes, family contacts, family communication log, portfolio
- **Class Codes** — Unique identifiers for student enrollment
- **Archived Classes** — Remove without data loss; restorable
- **Delete Class** — Permanent removal with all grades
- **Notification Feed** — Class activity list on home pages
- **To-Do List / Calendar View** — Upcoming events display
- **Recognitions** — Quick behavior documentation (positive/negative); district-created recognitions; family visibility

#### Lessons (from help.otus.com — 26 articles)

**Lesson Activity Types:**
| Activity | Description |
|----------|-------------|
| **Add Resource** | File (PDF, Word, Excel), URL/Link, Image, Video (record 5 min / upload 30MB), YouTube, Audio (record 5 min / upload 30MB), Google Drive/OneDrive, Page (rich text) |
| **Add Assessment** | Embed existing assessment within lesson |
| **Add Question** | MC, T/F, or short answer directly in lesson |
| **Add External Tool** | Embed LTI tools (Playposit, Newsela, Nearpod, Kahoot, etc.) enabled at district level |
| **Add Instructions** | Text-only instructions |
| **Add from Bookshelf** | Pull existing bookshelf resources |

**Lesson Features:**
- Drag-and-drop activity reordering
- Activities presented as tiles in step-by-step format
- Sequential or simultaneous student completion
- Clone/duplicate lessons; send copies to other teachers
- Auto-update: changes propagate to assigned students without reassignment
- Assign to classes, groups, or individuals
- Preview mode; due dates; blog integration

#### Bookshelf (from help.otus.com — 7 articles)
- Resource repository for uploading/sharing files in varied formats
- "My Bookshelf" for user-created resources; "Shared with Me" for received resources
- Share with students, groups, classes, or teachers
- Accessible to families via student accounts

#### Blog (from help.otus.com — 6 articles)
- Informal whole-class and private teacher-student messaging
- Class Feed displaying all posts; allow/disallow student comments
- Save as draft, schedule posts, publish to class feeds
- Attachments (files, images, videos)

### 3.6 AI Insights ("Otus Insights")

**Launched:** February 2025
**Infrastructure:** Amazon Bedrock with Guardrails for Amazon Bedrock

#### Capabilities
- Embedded AI assistant providing real-time Q&A about student performance
- Data synthesis across academic, demographic, behavioral, and assessment data
- Real-time summaries and on-demand visualizations
- Early warning system for at-risk identification (absenteeism prediction)
- Automated content moderation
- Family communication drafting
- Student grouping for targeted instruction
- Teacher time savings (hours per week reported)

#### Scale (2025-26)
- 54 school districts using AI Insights
- 1,384 administrators and 11,238 educators empowered
- 130,000+ students served through AI Insights
- 12.2 million assessments administered via Otus in 2024-25 (10% YoY increase)

#### Discovery Education Partnership (January 2026)
- AI-powered instructional recommendations connecting Otus student profiles to Discovery Education's standards-aligned resources
- "Insight to instruction" workflow

#### MindPrint Learning Acquisition (December 2025)
- Cognitive assessment and strengths-based interventions
- Adds cognitive profiling to the whole-learner data picture

### 3.7 Administration & Control Center

#### Control Center (from help.otus.com — 19 articles, Main Admin only)

**Grading Configuration:**
- Grading Scales — Create/edit scales with named levels, descriptions, colors; set grade-level permissions
- Mastery Settings — Configure which of 5 settings are available per grade level; set defaults
- Standards Settings — Choose standard groups, manage custom standards, create standards tags
- Total Grade Conversion — Convert standards mastery scores to traditional grades

**User & Session Management:**
- Admin Users — Manage administrative personnel; set permissions by site, district, or grade level
- Academic Sessions — Configure school years and grading periods (quarters, semesters, custom)

**Data & Integrations:**
- Uploads — Attendance data upload; CSV data imports
- LTI resource management (Turnitin, Playposit, Newsela, etc.)
- SIS connection configuration
- Grade passback setup
- Turnitin integration activation

**Operational:**
- Standards-Based Grading Setup Guide (comprehensive admin workflow)
- New School Year Preparation (administrator checklist for year rollover)

### 3.8 Account Types & Roles

| Role | Key Capabilities |
|------|-----------------|
| **Main Admin** | Full Control Center access; district-wide visibility; all analytics/reports/exports; manage all users |
| **Admin** | Teacher capabilities plus administrative functions; site/grade-level permissions; Query/Historical reports |
| **Teacher** | Create/assign/grade assessments and lessons; manage classes; view analytics for own students |
| **Co-Teacher** | Nearly identical to Teacher within assigned class |
| **Student** | Take assessments, complete lessons, view gradebook, blog, bookshelf, portfolio, recognitions |
| **Family** | View gradebook, bookshelf, blog, recognitions, student profile; link/unlink students |

### 3.8 Family & Student Engagement

#### Parent/Family Portal (from help.otus.com — 19 articles)
- Real-time progress updates
- Performance overview with strengths and opportunities
- Communication tools
- Progress monitoring plan visibility

#### Student Portal (from help.otus.com — 28 articles)
- Assessment delivery and submission
- Progress visibility and growth insights
- Blog and communication features

### 3.9 Google Integration (from help.otus.com — 14 articles)
- Google Classroom integration
- Google SSO
- Google Docs scoring integration
- Google Drive resource linking

---

## 4. Integration Ecosystem

### SIS Partners (40+ confirmed systems)
Aeries, Alma, Aspen, Aspire, ATS/Stars, Ascender, Blackbaud iNow, DASL/ProgressBook, eSchoolPlus, FACTS/RenWeb, Focus, Genesis, Infinite Campus, JMC, MiSIS, MiStar, MySchoolWorx, NebSIS, OnCourse, OnePoint, Pathways, PowerSchool, RealTime, Rediker, SchoolPathways, SchoolSpeak, SchoolTool, SchoolWise, Skyward (SMS & Qmlativ), Sycamore, Synergy, TADS, TeacherEase, Tyler, Veracross, Web2School

- Nightly sync of students, teachers, rosters, demographics
- Otus receives data from SIS; corrections must be made in source SIS
- **Grade Passback** supported to: PowerSchool, Infinite Campus, Skyward, Aeries (nightly sync; points-based only; standards-based not supported for passback)

### Alternative Rostering Methods
Clever, ClassLink, OneRoster API, CSV flat file exports

### SSO Providers
Clever SSO, ClassLink, Google SSO

### Assessment/Data Partners

**Automated Data Sync:**
| Partner | Data Type |
|---------|-----------|
| NWEA MAP Growth | Benchmark assessments |
| i-Ready / Curriculum Associates | Diagnostic assessments (monthly) |
| DreamBox Learning | Math adaptive learning |
| Reading Plus | Reading intervention |
| Renaissance Star | Assessments |
| Renaissance FastBridge | Universal screening, CBM |
| Kelvin | SEL surveys |

**Manual Upload Supported:**
| Partner | Data Type |
|---------|-----------|
| SBAC | State assessments |
| PARCC / IAR | State assessments |
| ACT | College readiness |
| PSAT | College readiness |
| SAT | College readiness |
| Custom Growth Assessments | Any other data source |

### Curriculum Partners
Amplify Science, Amplify CKLA, Bridges in Mathematics (Math Learning Center), National Geographic, EL Education, Cognia, Exemplars, Horizon Education, Discovery Education

### EdTech Tool Integrations
| Tool | Function |
|------|----------|
| Turnitin | Plagiarism detection |
| Texthelp | Text-to-speech accessibility |
| Respondus | Test proctoring |
| Desmos | Interactive math |
| Grammarly | Writing assistance |
| Google Docs | Direct scoring integration |
| Everway | Additional learning tools |

### Rostering Standards
- OneRoster support (confirmed via help documentation)
- CSV upload support
- SIS API sync

---

## 5. Technical Architecture

### 5.1 Frontend Stack

#### Login / Public Pages (my.otus.com)
The unauthenticated login page uses:
- **jQuery** — DOM manipulation
- **Zurb Foundation** — CSS/responsive UI framework
- **Font Awesome 5.9.0** — Icon library
- **Google Fonts (Lato)** — Weights 300, 400, 700, 900
- **Google Analytics** — Tracking ID `UA-145857027-1`
- **Extensive CSS custom property system** — 100+ color variables

#### Post-Login Application (Angular SPA)
The main application (loaded after authentication) is an **Angular Single Page Application**:

| Technology | Details |
|-----------|---------|
| **Framework** | Angular 7+ (per job postings; exact production version unknown) |
| **Language** | TypeScript (frontend and backend) |
| **Build Tools** | Webpack, Babel |
| **Architecture Goals** | Micro-frontend patterns (aspirational), UI component library, design system |
| **Performance Target** | "1000s of requests in less than 1 second" |

The Angular SPA is lazy-loaded only after authentication, which is why the public login page shows only jQuery/Foundation.

### 5.2 Backend Stack

| Component | Technology |
|-----------|-----------|
| **Runtime** | Node.js |
| **Frameworks** | Express, NestJS |
| **Language** | TypeScript |
| **Database** | Amazon RDS for PostgreSQL (with vector storage for RAG) |
| **Object Storage** | Amazon S3 |
| **API Style** | Likely RESTful (NestJS default); no evidence of GraphQL |

### 5.3 Cloud Infrastructure (AWS)

Otus has been an AWS partner since 2017 and won a 2025 AWS Champions Award.

| AWS Service | Purpose |
|-------------|---------|
| **Amazon EC2 Auto Scaling** | Scalable compute for live classrooms and analytics |
| **Amazon RDS for PostgreSQL** | Primary database with vector storage for RAG |
| **Amazon S3** | Data and artifact storage |
| **Amazon Bedrock** | LLM-powered AI features |
| **Guardrails for Bedrock** | Content moderation, accuracy safeguards |

Google Compute Engine also referenced on G2 Stack (possible multi-cloud or legacy).

### 5.4 AI / ML Stack

- **Amazon Bedrock** for LLM inference
- **Guardrails for Amazon Bedrock** for content safety
- **PostgreSQL vector storage** for RAG-based natural language search over student data
- AI Advisory Board for governance

### 5.5 DevOps & Infrastructure

- **Docker** — Containerization
- **CI/CD pipelines** — Automated deployment
- **Kubernetes** — Microservice architecture (aspirational/in progress)
- Static analysis utilities for code enforcement
- Performance monitoring and test coverage tools

### 5.6 Third-Party Services

| Service | Purpose |
|---------|---------|
| Intercom | Customer support (Messenger, Custom Bots, Articles, Product Tours) |
| Salesforce | CRM |
| Jira Service Desk | Project management |
| Slack | Internal communications |
| Google Analytics | Usage tracking |

### 5.7 Application Architecture — Angular SPA (Decompiled)

#### SPA Shell Discovery

**Every URL on `my.otus.com` returns the same 12,073-byte HTML document.** There is no separate server-rendered login page — the server has a catch-all rewrite rule that serves the Angular shell for all paths. The Angular app itself handles routing to `/login` for unauthenticated users.

- **Root component:** `<otus-app>` (custom prefix, not default `<app-root>`)
- **Webpack chunk namespace:** `self.webpackChunkotus_app`
- **Build tooling:** Angular CLI + webpack (hashed filenames, `type="module"` scripts)
- **UI component library:** PrimeNG (CSS custom properties / design tokens)
- **Legacy dependencies in shell:** jQuery 3.6.0, Moment 2.24.0, Foundation 6.2.4
- **Fonts:** Lato (self-hosted from Google Fonts)
- **Icons:** Font Awesome 5.9.0

#### Production Bundle Files

| File | Content Hash | Size |
|------|-------------|------|
| `runtime.560445a470b1b348.js` | `560445a4...` | 7 KB |
| `polyfills.e2195c0a3be26d2f.js` | `e2195c0a...` | 66 KB |
| `scripts.adff6e5ddc86fce4.js` | `adff6e5d...` | 695 KB |
| `vendor.c491d20d2cabba54.js` | `c491d20d...` | 1,638 KB |
| `main.e89413495f1398bb.js` | `e8941349...` | 1,105 KB |
| `styles.51ae2082382bf3d8.css` | `51ae2082...` | 1,453 KB |

**Total initial payload:** ~5 MB (before lazy chunks)
**Lazy-loaded chunks:** 139 numbered chunks in the webpack chunk map

#### Complete Route Map (Decompiled from `main.js`)

##### Public Routes (no auth guard)

| Path | Type | Component/Module |
|------|------|-----------------|
| `/login` | Eager | `Ys` component |
| `/logout` | Eager | `js` component |
| `/sso_login` | Lazy | `SSOLoginModule` (chunk 9176) |
| `/reset-password/:retrieve_password_token` | Eager | `fs` component |
| `/signup` | Eager | `Qs` component |
| `/respondus` | Lazy | `RespondusModule` (chunk 737) |
| `/forbidden` | Eager | `ss` component |
| `/**` (wildcard) | Eager | `as` component (catch-all) |

##### SSO OAuth2 Callback Routes

| Path | Provider |
|------|----------|
| `/sso_login/social/google` | Google |
| `/sso_login/social/microsoft` | Microsoft |
| `/sso_login/social/clever` | Clever |
| `/sso_login/social/classlink` | ClassLink |

##### Authenticated Routes (3 guards: `kt.lI`, `kt.oT`, `kt.un`)

Default redirect: `""` → `/home`

| Path | Lazy Module | Purpose | Key Chunks |
|------|------------|---------|------------|
| `/home` | `HomeModule` | Landing page, notification feed, to-do, calendar | 8860, 3555, 6014, 3144, 8752, 7910, 7858, 6158, 8802, 4522 |
| `/activity` | `HomeModule` (alias) | Same as /home | same |
| `/dashboard` | `ActivityDashboardModule` | Admin usage analytics dashboard | 8752, 7910, 2871, 3889 |
| `/district` | `DistrictModule` | Sites, teachers, students, groups, recognitions | 8860, 9373, 3555, 2967, 6014, 3144, 8752, 7910, 1201, 7858, 6876, 6139, 6158, 8802, 2737, 2932, 8592, 8190 |
| `/classes` | `ClassesModule` | Class management, roster, board, mailbox | 8860, 9373, 3555, 2967, 6014, 4796, 3144, 8752, 7910, 1201, 7858, 6158, 8073, 8802, 1475, 2737, 7212, 4088 |
| `/assessment` | `LearnosityModule` | Assessment creation & delivery (Learnosity-powered) | 9373, 6014, 1201, 6876, 6139, 4235, 7265, 6329, 9081, 9255, 6877 |
| `/simple-assessment` | `OtusAssessModule` | Simple/Rubric/Plus assessment types | 8860, 9373, 3555, 5327, 6014, 3144, 2156, 3852, 1201, 7858, 6876, 4898, 6139, 4235, 7265, 2817, 6329, 1731, 2382, 7864, 9081, 9255, 435, 7043 |
| `/gradebook` | `GradebookModule` | Standards & points-based grading | 6139, 4235, 7265, 6329, 9255, 4520, 8449, 6179 |
| `/lessons` | `Lessons2Module` | Lesson listing & management | 8860, 9373, 3555, 5327, 6014, 3144, 7858, 4235, 6158, 2582, 5393, 4845, 6255, 1776, 7824, 8592, 553 |
| `/lesson` | `OtusLessonModule` | Single lesson view/edit | 8860, 9373, 3555, 6014, 3144, 7858, 4235, 6158, 2582, 5393, 4845, 7824, 6093 |
| `/analytics` | `AnalyticsModule` | Data dashboards, reports, exports | 8752, 7910, 7265, 789, 7498, 5866, 9954 |
| `/plans` | `PlansModule` | Progress monitoring, MTSS, interventions | 8860, 3555, 8752, 7910, 3824, 2871, 344, 8977, 8210, 8592, 2294 |
| `/blog` | `BlogModule` | Class blog feeds, posts | 8860, 9373, 5327, 2156, 3852, 6329, 6341, 3480, 8592, 1492 |
| `/bookshelf` | `BookshelfModule` | Resource library | 8860, 9373, 3555, 5327, 6014, 3144, 8752, 7910, 6158, 2582, 6341, 5393, 5866, 9197 |
| `/students` | `FamilyStudentModule` | Family/student portal view | 8592, 850 |
| `/student-profile` | `StudentViewPageModule` | Student profile detail view | 40+ chunks |
| `/my-portfolio` | `PortfolioModule` (v1) | Student portfolio (legacy) | 34+ chunks |
| `/portfolio` | `PortfolioV2Routes` | Student portfolio (v2, feature-gated) | chunk 9465 |
| `/reports` | `StudentReportModule` | Student reports | 30+ chunks |
| `/control-center` | `ControlCenterModule` | Admin settings, grading, standards, integrations | 8860, 9373, 6014, 1201, 6876, 6139, 1731, 2932, 8592, 7847 |
| `/profile` | `ProfileModule` | User profile settings | 9373, 7212, 1759 |
| `/otus-ai` | `OtusAiPageModule` | AI Insights (Otus AI chat) | 3555, 9674, 7498, 8332 |
| `/certica` | `CerticaModule` | Standards alignment (Certica/Instructure) | chunk 9987 |
| `/secret` | `SettingsModule` | Internal/dev settings | chunk 2055 |

##### Feature Flags (Unleash via `uedge.otus.com`)

| Flag | Purpose |
|------|---------|
| `ai-feature-add-to-groups` | AI → student group creation |
| `ai-feature-ask-otus-everywhere-enable` | Global AI assistant |
| `ai-feature-full-page` | Full-page AI mode |
| `ai-feature-stream-cancellation-button-enable` | Cancel AI streaming |
| `ai-feature-stream-response-enable` | Streaming AI responses |
| `ai-feature-token-streaming` | Token-level streaming |
| `current-user-bff-routing` | BFF migration: current user |
| `login-bff-routing` | BFF migration: login |
| `logout-bff-routing` | BFF migration: logout |
| `enable-portfolio-v2` | Portfolio v2 (feature gate for `/portfolio` route) |

Feature toggle endpoint: `/napi/sysinfo/feature-toggles/`

#### Backend Service Architecture (5 Services)

| Service | URL Pattern | Purpose |
|---------|-------------|---------|
| **BFF** | `https://{bff.hostName}/...` | Primary API (auth, portfolios, milestones, assignments, assessments) |
| **Gateway** | `{gatewayUrl}/...` | OAuth2 SSO proxy, login/logout fallback |
| **NAPI (PHP)** | `{platformBaseUrl}/napi/...` | Legacy PHP endpoints (courses, attachments, feature toggles, otusassess) |
| **Platform API** | `{platformBaseUrl}/api/...` | User info, navigation permissions |
| **OIB** | `{platformBaseUrl}/oib/...` | AI chat service (Otus Insights) |
| **External Tools** | `{platformBaseUrl}/external-tools/...` | LTI/Turnitin/GradeCam integrations |

#### BFF API Endpoints (Decompiled)

**Authentication:**
- `POST /authentication/login`
- `POST /authentication/logout`
- `POST /authentication/impersonate`

**Users:**
- `GET /users/myself`
- `GET /users/myself/permissions`

**Admin endpoints** (`/admin/...`):
- `/admin/assessments/*`, `/admin/assignments/*`, `/admin/milestones/*`
- `/admin/portfolio/*`, `/admin/sections/*`, `/admin/students/*`
- `/admin/third-party-analytics/*`

**Teacher endpoints** (`/teacher/...`):
- `/teacher/assessments/*`, `/teacher/assignments/*`, `/teacher/courses/*`
- `/teacher/milestones/*`, `/teacher/sections/*`, `/teacher/skills/*`
- `/teacher/students/*`

**Student endpoints** (`/student/...`):
- `/student/assessments/*`, `/student/assignments/*`, `/student/portfolio/*`

**AI/Chat (OIB service):**
- `POST /chat`, `GET /chat/recent`
- `GET /chat/{id}/stream`
- `POST /chat/{id}/messages/{id}/feedback`
- `POST /chat/pre-stream/create`
- `GET /behaviors`

**Legacy NAPI PHP endpoints** (`/napi/...`):
- `/course/*`, `/user/*`, `/teacher/*`, `/parents/*`, `/site/*`
- `/student_course/*`, `/analytics/*`, `/bookshelf/*`, `/coteacher/*`
- `/demo_class/*`, `/otusassess/*`, `/attachments/*`
- `/controlcenter/*`, `/captcha/*`

**District:**
- `GET /district/attributes`

#### Production Infrastructure

**Hostnames (decompiled from environment config):**

| Hostname | Purpose |
|----------|---------|
| `my.otus.com` | Main frontend |
| `fe.platform.otus.com` | Platform frontend |
| `internal.otus.com` | Internal services |
| `uedge.otus.com` | Unleash feature flags edge proxy |
| `authorapi.learnosity.com` | Learnosity assessment authoring |
| `items.learnosity.com` | Learnosity item bank |
| `reports.learnosity.com` | Learnosity reporting |
| `app.gradecam.com` | GradeCam integration |

**Dev/Staging:**
- `my.otus.dev`, `my-west.otus.dev` (dev frontends)
- `api.my.otus.dev`, `api.my-west.otus.dev` (dev APIs)
- `pen.my.otusplatform.net`, `pen-api.otusplatform.net` (pen test)
- `preprod.otusplatform.net`, `preprod-api.otusplatform.net` (pre-prod)

**Observability:** Grafana Faro collector (3 collection IDs) for frontend performance monitoring

#### 25 Lazy-Loaded Angular Modules (Complete)

```
ActivityDashboardModule    FamilyStudentModule    OtusAiPageModule
AnalyticsModule           GradebookModule        OtusAssessModule
BlogModule                HomeModule             OtusLessonModule
BookshelfModule           LearnosityModule       PlansModule
CerticaModule             Lessons2Module         PortfolioModule
ClassesModule             PortfolioV2Routes      ProfileModule
ControlCenterModule       RespondusModule        SSOLoginModule
DistrictModule            SettingsModule         StudentReportModule
                          StudentViewPageModule
```

#### Navigation Patterns (from help.otus.com, 507+ articles)

**Module Selection:** Left-hand sidebar icons → loads module root route
**Entity Context:** Class selection via **dropdown menu** (not URL path segments)
**Sub-Navigation:** Tabs within each module (e.g., Assessments tab / Standards tab in Gradebook)
**Drill-Down:** Click entity → detail view (e.g., click student name → individual gradebook)
**Admin Hierarchy:** District → Sites → Teachers/Students (tiles and sub-menus within `/district`)

**Role-Based Landing Pages:**
| Role | Landing Route | Module |
|------|--------------|--------|
| Main Admin | `/dashboard` | `ActivityDashboardModule` |
| Admin | `/dashboard` | `ActivityDashboardModule` |
| Teacher | `/home` | `HomeModule` |
| Student | `/home` | `HomeModule` |
| Family | `/students` | `FamilyStudentModule` (gradebook-focused) |

**Student Profile Navigation (via `/student-profile` → `StudentViewPageModule`):**

The student profile is a key entity view with 4 tab areas:
```
Student Profile
├── Main
│   ├── Gradebook (standards & points views)
│   ├── Standards mastery
│   └── Plans (associated learning plans)
├── Content
│   ├── Portfolio (artifacts, assessments, documents)
│   └── Blog posts
├── Reports
│   ├── Assessment list
│   ├── Recognition log
│   ├── Attendance log
│   └── 3rd party assessment data
└── Information
    ├── District groups
    ├── Classes
    ├── Grade levels
    ├── Family contacts
    ├── Communication logs
    ├── Notes
    └── Attachments
```

These tabs map to ORL `#fragment` view state:
- `orl://district/{did}/student/{stuid}#grades` → Student Profile → Main tab
- `orl://district/{did}/student/{stuid}#portfolio` → Student Profile → Content tab
- `orl://district/{did}/student/{stuid}#reports` → Student Profile → Reports tab
- `orl://district/{did}/student/{stuid}#info` → Student Profile → Information tab

#### ORL ↔ Angular Route Resolution Mapping

| ORL Pattern | Angular Route | Resolution Strategy |
|-------------|--------------|---------------------|
| `orl://district/{did}` | `/district` | District module landing (site tiles) |
| `orl://district/{did}/site/{sid}` | `/district` + site selection | Dropdown/tile selection within district module |
| `orl://district/{did}/student/{stuid}` | `/student-profile?studentId={stuid}` | `StudentViewPageModule` handles student detail |
| `orl://district/{did}/teacher/{tid}` | `/district` → Teachers sub-nav | Teacher directory within district module |
| `orl://district/{did}/site/{sid}/course/{cid}` | `/classes?classId={cid}` | ClassesModule, class selected via dropdown |
| `orl://district/{did}/.../assignment/{aid}` | `/assessment/{aid}` or `/simple-assessment/{aid}` | LearnosityModule or OtusAssessModule depending on type |
| `orl://district/{did}/standard/{stdid}` | `/gradebook` → Standards tab | GradebookModule, standard column drill-down |
| `orl://district/{did}/group/{gid}` | `/district` → Student Groups | DistrictModule, group management sub-nav |
| `orl://district/{did}/session/{sessid}` | `/control-center` → Academic Sessions | ControlCenterModule |

**Key architectural insight:** The Angular app uses **flat module routes** with UI-state context (dropdowns, tabs) rather than hierarchical URL segments. The ORL `ResolveToWebRoute()` function needs to:
1. Map entity type to owning Angular module path
2. Pass entity ID as query parameter or state
3. Handle the assessment type split (`/assessment` for Learnosity advanced vs `/simple-assessment` for Simple/Rubric/Plus)
4. Account for role-based route availability (e.g., `/control-center` requires Main Admin)

### 5.8 Engineering Team

Key personnel (from LinkedIn/public sources):
- Keith Westman, Ed.D. — CTO
- Sam Drilias — Director of Engineering, Platform
- Andrew Bayer — Engineering Manager
- Britt Crowe — Senior Engineering Manager
- Rick Connell — Senior Engineer (Frontend Platform team lead)
- Brooke Fodor — Senior Front End Engineer
- Kelley Britton — Senior Software Engineer
- Mahmoud Farahat — Senior Engineer
- Joseph Fortman — Senior Engineer

Team described as "small team, fast-moving environment" with a "pretty flat organization."

---

## 6. Help Documentation Structure

The help center at help.otus.com contains **507+ articles across 19 primary categories:**

| Category | Articles | Coverage |
|----------|----------|----------|
| Getting Started | 66 | Onboarding, account setup |
| Training Pathways | 7 | Task-based educator training |
| Control Center | 19 | District-level administration |
| Plans | 20 | Progress monitoring, MTSS |
| Gradebook | 20 | Grading features |
| Classes | 45 | Class management |
| Assessments: General | 55 | Assignment basics |
| Simple/Rubric/Plus Assessments | 22 | Assessment types |
| Advanced Assessments | 116 | Full-featured assessments (largest section) |
| Analytics | 40 | Data analysis, reporting |
| Bookshelf | 7 | Resource library |
| Blog | 6 | Blog module |
| Lessons | 26 | Lesson planning/delivery |
| Students | 28 | Student-facing features |
| Parent and Family | 19 | Guardian portal |
| Google | 14 | Google integrations |
| Integrations | 36 | All integration partners |
| Additional Resources | 16 | Webinars, guides |
| Jefferson County PS | 10 | District-specific docs |

---

## 7. Pricing Model

Otus does **not** publish pricing publicly:
- Per-student pricing (custom quotes based on district size and needs)
- Low per-student costs (per EdTec charter school partnership positioning)
- Affordable setup fee
- No hefty annual licensing fee minimums
- Demo/quote request required through otus.com

---

## 8. Awards & Recognition

- Tech Learning Awards (multiple years, primary and secondary categories)
- CODiE Awards 2024 Finalist: Best Formative Assessment Solution, Best Evidence Management Solution, Best Suite of Connected/Integrated Solutions, Best Customer Experience in EdTech
- EdTech Breakthrough Awards (2025)
- 2025 AWS Champions Award for Excellence in EdTech Innovation
- ISTE certifications and seals
- Globee Awards
- SmartBrief Reader's Choice Awards
- SmartBrief Innovation Awards in AI 2025 (Honorable Mention)

---

## 9. Competitive Landscape

### Key Differentiators
1. **Unified platform** replacing multiple disconnected tools (assessment + grading + data + progress monitoring + AI)
2. **Purpose-built for standards-based grading** (not retrofitted onto a traditional gradebook)
3. **Founded by teachers**, staffed by former educators
4. **AI-powered insights embedded throughout** (not bolt-on)
5. **Complements existing SIS** rather than replacing it
6. **Full MTSS framework support** natively

### Competitor Categories
| Category | Competitors |
|----------|------------|
| Gradebook | PowerSchool gradebook, Infinite Campus gradebook, Canvas gradebook |
| Assessment | Illuminate Education, Edulastic/Formative, MasteryConnect |
| Data Warehouse | Schoolzilla, Ed-Fi, Tableau for Education |
| MTSS/RTI | Branching Minds, FastBridge, Panorama Education |
| LMS | Canvas, Google Classroom, Schoology |
| All-in-One | PowerSchool Unified Classroom, Infinite Campus |

### User Sentiment (from G2 and other reviews)

**Strengths:**
- Clean, easy-to-navigate interface
- Comprehensive student profiles with actionable data
- Strong standards-based gradebook (fills a market gap)
- Strong integration with MAP testing and other assessment data
- Email communication directly from platform

**Criticisms:**
- Requires both parent and student accounts; no push notifications to parents
- Assessment/lesson posting workflow can be confusing
- Sharing assessments requires typing full email addresses (no autofill)
- Some users find portions of the interface unintuitive
- Importing new curriculum described as "long and frustrating"

---

## 10. Key Observations for SIS/LMS Feature Comparison

### What Otus IS:
- Assessment creation, delivery, and analytics platform
- Standards-based gradebook
- Data aggregation and visualization layer
- Progress monitoring and MTSS tool
- AI-powered educator insights engine
- Family/student engagement portal

### What Otus is NOT:
- Not a Student Information System (no enrollment management, demographics authoring, scheduling, transportation, health records)
- Not a full LMS (no content management, course authoring, SCORM/xAPI, discussion forums, video conferencing)
- Not an attendance system of record (reads attendance data from SIS)
- Not a behavior management system of record (reads behavior data; incidents entered elsewhere)

### SIS Data Otus Consumes (via nightly sync):
- Student roster and demographics
- Teacher roster
- Class/section assignments
- Enrollment records
- Attendance data
- Some behavior data

### SIS Data Otus Creates/Owns:
- Assessment results and item-level analytics
- Standards-based grades and gradebook data
- Progress monitoring plans and intervention tracking
- AI-generated insights and recommendations
- Custom analytics and reports
