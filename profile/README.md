# Dittravel :airplane:
> Public Wiki - The Single Repository of Truth

Dittravel is a ficticious software consulting firm created for the purposes of the project made by students of group 102 (later 501) of the courses TC3004B and TC3005B of Tec de Monterrey, Santa Fe Campus for Ditta Consulting, our formative partners. The project was carried out during the February-June 2026 semester, and resulted in the creation of the project repository [TC3005B.501](https://github.com/dittravel/TC3005B.501).

![Banner](banner.png)

---

## Team Members :busts_in_silhouette:

| Name | ID |
|-|-|
| Amilka Daniela López Aguilar | A01029277 |
| Aquiba Yudah Benarroch Bittan | A01783710 |
| Diego Córdova Rodríguez | A01781166 |
| Facundo Gabriel Esparza | A01784521 |
| Isabela Valls Chávez | A01173825 |
| Lorena Estefanía Chewtat Torres | A01785378 |
| Luis Emilio Veledíaz Flores | A01029829 |
| María Rivera Gutiérrez | A01029678 |
| Mauricio Emilio Monroy González | A01029647 |
| Miranda Urban Solano | A01752391 |
| Valentina Castilla Melgoza | A01028209 |

---

## Index :bookmark_tabs:
- [Our Identity :bust_in_silhouette:](#our-identity-bust_in_silhouette)
  - [Logo :art:](#logo-art)
    - [Logo Description :mag_right:](#logo-description-mag_right)
  - [Slogan :speech_balloon:](#slogan-speech_balloon)
  - [Mission :dart:](#mission-dart)
  - [Vision :eye:](#vision-eye)
  - [Values :heart:](#values-heart)
  - [Code of Conduct :handshake:](#code-of-conduct-handshake)
- [Guidelines :scroll:](#guidelines-scroll)
  - [Language and Documentation :book:](#language-and-documentation-book)
  - [Code Style :pencil2:](#code-style-pencil2)
  - [Database Conventions 🔤:](#database-conventions-)
  - [Technology Stack :computer:](#technology-stack-computer)
  - [Version Control :herb:](#version-control-herb)
  - [Project Structure :file_folder:](#project-structure-file_folder)
  - [Folder Structure 🗃️](#folder-structure-%EF%B8%8F)
  - [Best Practices :thumbsup:](#best-practices-thumbsup)
  - [Error Handling :warning:](#error-handling-warning)
  - [Security Practices :lock:](#security-practices-lock)
  - [Performance :zap:](#performance-zap)
  - [Architecture & Best Practices Guide :building_construction:](#architecture--best-practices-guide-building_construction)
  - [Team Roles :technologist:](#team-roles-technologist)
    - [Project Structure by Team 📁](#project-structure-by-team-)
  - [Branches and Pull Requests :seedling:](#branches-and-pull-requests-seedling)
    - [Main Branch :world_map:](#main-branch-world_map)
    - [Pull Request Descriptions :memo:](#pull-request-descriptions-memo)
  - [Issues 📖](#issues-)
    - [Issue Types 📑](#issue-types-)
    - [Issue Template Format ℹ️](#issue-template-format-ℹ%EF%B8%8F)
  - [Label Directory 🏷️](#label-directory-%EF%B8%8F)
  - [Issue Example: Task](#issue-example-task)
---

## Our Identity :bust_in_silhouette:

### Logo :art:

| Type | Logo |
|-|-|
| Main Logo | <img src="dittravel_logo_main.png" width="200" alt="Dittravel Logo Main"> |
| Alternative Logo | <img src="dittravel_logo_alt.png" width="200" alt="Dittravel Logo Alternative"> |
| Other Logo Variations | <img src="dittravel_logo_collage.png" width="200" alt="Dittravel Logo Collage"> |

#### Logo Description :mag_right:
Dittravel's logo represents a clear connection to Ditta Consulting, our formative partner, while incorporating elements that symbolize the main focus of the project, a travel management software. The design features an airplane icon, formed by a stylized "D" and "T", which are the initials of Dittravel, mantaining a strong visual link to Ditta Consulting's branding throught the use of the blue color palette. The logo's design reflects the company's commitment to innovation by keeping a unique perspective over rudimentary elements like letters.

### Slogan :speech_balloon:

> "Transforming Ideas into High-Value Software. Code, Create & Deliver."

### Mission :dart:
**Provide professional, high-quality services**. We aim for thorough serving for our clients by developing high-value software, all while preserving ethics and professional standards within our company.

### Vision :eye:
**Gather top talent of professionals in information technologies and create multidisciplinary teams with skill and capacity to solve any problem regarding software**, information technology or other fields related and necessary toward the satisfaction of our clients.

### Values :heart:

- **Excellence:** We strive for high-quality results in every aspect of our work, from architecture design to final deployment. We are committed to continuous improvement and technical mastery.

- **Integrity:** We uphold strong ethical principles, transparency, and honesty in all our decisions and interactions with clients and teammates.

- **Collaboration:** We believe multidisciplinary teamwork is the foundation of innovation. We support open communication, mutual respect, and shared responsibility.

- **Responsibility:** We take ownership of our tasks, deadlines, and commitments, ensuring reliability and accountability throughout the project lifecycle.

- **Innovation:** We embrace creativity and emerging technologies to build efficient, scalable, and forward-thinking solutions.

- **Client Commitment:** We prioritize Ditta Consulting's needs and goals, working closely with them to deliver tailored solutions. Our goal is to exceed their expectations.

- **Respect:** We believe in mutual understanding through proper discussion.

- **Honesty:** We place transparency at the center of our decision-making.

- **Loyalty:** We are committed to our clients, our team members, and our partners. We build lasting relationships based on trust, reliability, and mutual respect.

### Code of Conduct :handshake:

| Aspect | Description |
|-|-|
| Respectful Communication | Always communicate professionally either via email, chat, or in-person. Avoid offensive language, personal attacks, and discriminatory remarks. |
| Equal Task Distribution | Ensure that tasks are distributed fairly among team members, taking into account individual strengths and workloads. |
| Conflict Resolution | Address conflicts by discussing issues openly with the involved parties. If necessary, involve a neutral third party to mediate and find a resolution. |
| Feedback and Criticism | Always provide constructive feedback. |
| Confidentiality | Respect the confidentiality Ditta Consulting's information and any sensitive data related to the project |

---

## Guidelines :scroll:

### Language and Documentation :book:

- **GitHub in English:** All repository content, including issues, pull requests, commit messages, and branch names, must be in English to maintain consistency and accessibility for international contributors.
- **Documentation in Spanish:** Project documentation, such as test plans, design documnents, etc.

### Code Style :pencil2:
- **Variable Naming:** Use camelCase for variable names (e.g., `userName`, `isActive`).
- **Indentation:** Use 2 spaces for consistent indentation.
- **Comments:** Include descriptive comments above functions with purpose, parameters, and return values.
- **ESLint:** Use ESLint for code quality and consistency.
- **Naming Conventions:** Follow lowerCamelCase for variables/functions, UpperCamelCase for classes.
- **Best Practices:** Prefer `const` over `let`, use async/await, arrow functions, and avoid global side effects.

For each function, include a comment block like:

```javascript
/**
 * Get the amount of users in the system from a specified role.
 * @param {string} role - The role to filter users by.
 * @returns {number} The number of users.
 */
```

Remove console.log statements before merging, leaving debug comments if needed.

### Database Conventions 🔡:
*This is based directly from Coconsulting's database files.*

### Naming Conventions

#### Table Names
- Use **lowercase** with **underscores** for multi-word names
- Use **backticks** when table names are reserved keywords (example: `` `User` ``, `` `Role` ``)
- Examples: `Request`, `Request_status`, `Route_Request`, `Receipt_Type`

#### Column Names
- Use **lowercase** with **underscores** for multi-word names
- Use **snake_case** for consistency
- Use names that clearly indicate the data type and purpose
- Foreign key columns should include the referenced table name and `id` suffix (example: `user_id`, `request_id`)
- Examples: `user_name`, `creation_date`, `request_status_id`, `phone_number`

#### Script Organization
Scripts should be organized like this:
1. **Scheme.sql** - Database and table creation
2. **Prepopulate.sql** - Reference data (roles, statuses, types)
3. **Dummy.sql** - Sample data for testing and development
4. **Views.sql** - Database views for more complex queries
5. **Triggers.sql** - Automated database triggers

### Technology Stack :computer:

- **Languages:** The project uses a mix of TypeScript and JavaScript within the Astro framework. Prefer TypeScript for new components, falling back to JavaScript only when necessary.

- **Framework:** Astro is the primary framework for building the project.

- **Backend:** Node.js with Express for API development.

- **Database:** MongoDB for data storage and management. MariaDB for all application data.

### Version Control :herb:
- **Branch Naming:** Each branch name must include the owner's name and the relevant area (e.g., `diego-frontend-auth`, `isabela-backend-api`). This helps in tracking contributions and organizing work.
- **Commit Messages:** Write clear, concise commit messages in English, starting with a verb (e.g., "Add user authentication", "Fix login bug"). Reference issue numbers when applicable.

### Project Structure :file_folder:
- **File Organization:** Maintain clean folder structures, grouping related files (e.g., components in `src/components/`, utilities in `src/utils/`).
- **Imports:** Use relative imports for modules, absolute for shared utilities.

### Folder Structure 🗃️
Note that everything for these structures is strictly based off of Cocosulting's folder structure.
#### Backend File Structure Rules

The Backend repository follows a pattern with a clear separation. Each directory has a specific purpose and must follow strict naming and organization conventions.

#### Backend File Structure Rules
The Backend repository four layers: Models → Services → Controllers → Routes.

#### Directory Structure
```
/controllers      # {entity}Controller.js - HTTP request handlers
/services         # {entity}Service.js - Business logic
/models           # {entity}Model.js - Data schemas
/routes           # {entity}Routes.js - API endpoints
/middleware       # auth.js, validation.js, etc - Request processing
/openapi          # {role}/*.yaml - API documentation by role
/database         # Schema, configuration
/certs            # SSL certificates
```

#### Naming Convention

- **Controllers:** `userController.js`, `applicantController.js`, `accountsPayableController.js`, etc.
- **Services:** `userService.js`, `applicantService.js`, etc.
- **Models:** `userModel.js`, `applicantModel.js`, etc.
- **Routes:** `userRoutes.js`, `applicantRoutes.js`, etc.
- **Middleware:** Descriptive names - `auth.js`, `validation.js`, etc.
- **OpenAPI:** One folder per role with YAML files - `openapi/admin/`, `openapi/user/`, etc.

#### Key Rules
- Use **camelCase** for all file names
- Each major directory includes `README.md`
- Database files go in `/database` directory
- Tests use `.test.js` suffix

#### Frontend File Structure Rules
The Frontend mainly uses Astro. Files are organized by functionality with separations between components, pages, layouts, and utilities.

#### Directory Structure
```
/components       # {Entity}Component.astro or Component.tsx - Reusable UI
/pages            # {feature}.astro - Routes
/layouts          # {Name}Layout.astro - Page templates
/views            # {Role}View.astro - Role-specific views
/styles           # global.css - Global styling
/assets           # Images, icons, SVGs
/config           # {name}-config.ts - Configuration files
/data             # cookies.ts, users.csv - Static data
/types            # {Entity}Data.ts - TypeScript types
/utils            # {function}Name.ts - Utility functions
/public           # Static files (logos, fonts)
/cypress          # E2E tests organized by feature
```

#### Naming Convention

- **Components:** `HeaderComponent.astro`, `Button.tsx`, `UserForm.astro`
- **Pages:** `atender-solicitud.astro`, `completar-draft.astro`
- **Layouts:** `Layout.astro`, `MainLayout.astro`, `HeaderLayout.astro`
- **Views:** `AdminView.astro`, `ApplicantView.astro`, `AccountsPayableView.astro`
- **Utilities:** `apiClient.ts`, `getPriorityDates.js`, `getStatus.js`
- **Types:** `DepartmentData.ts`, `FormData.ts`, `TravelRoute.ts`
- **Config:** `menu-config.ts`, `roles.ts`, `button.ts`
- **Tests:** `create-request.cy.ts`, `date-validation.cy.ts`, `role-navigation.cy.ts`
- **Assets:** `Logo.svg`, `user-icon.svg`, `favicon.svg`

#### Key Rules

- Use **PascalCase** for components, layouts, views, types
- Use **kebab-case** for pages, folders, assets, tests
- Use **camelCase** for utilities, functions, config
- One entity/purpose per file
- Keep components reusable

#### Code Quality
- Follow consistent naming conventions for variables, functions, and files.
- Ensure code is modular and reusable.

#### Naming Conventions

*This was taken directly from the Frontend's CONTRIBUTING.md file.*

When working with variables, functions, and constants in Astro projects, adhere to the following standards:

- **Variables**
  - Use `camelCase` for variable names.
  - Variable names should be descriptive and meaningful. (e.g., `userName`)
  - Avoid single-letter variable names unless used in loops (e.g., `i`, `j`).

- **Functions**
  - Use `camelCase` for function names.
  - Function names should clearly describe their purpose or action (e.g., `fetchData`, `calculateTotal`).
  - Keep functions small and focused on a single responsibility.
  - Use arrow functions (`const myFunction = () => {}`) unless a named function is required.

- **Constants**
  - Use `UPPER_SNAKE_CASE` for constants.
  - Constants should be declared using `const` and should not be reassigned.
  - Group related constants together for better readability.
  - Constants names should be descriptive and meaningful.

- **Environment Variables**
  - Use `UPPER_SNAKE_CASE` for environment variable names.
  - Prefix environment variables with the project name or a relevant namespace (e.g., `ASTRO_API_KEY`).
  - Store sensitive environment variables in a `.env` file and **NEVER** commit this file to version control.
  - Access environment variables using `import.meta.env` in Astro.

#### Comments
*This was taken directly from the Frontend's CONTRIBUTING.md file.*

- Start the file with a short paragraph explaining its purpose.
- Document the purpose of functions, components, and modules with comments at the top of their definitions.
- Use comments to clarify complex or non-obvious code logic.
- Write comments in plain English and keep them concise.
- Use single-line comments (`<!-- comment -->`) for brief explanations and multi-line comments (`<!-- \n comment  \n -->`) for detailed descriptions.
- Avoid redundant comments that simply restate the code.
- Use `ToDo:` comments to indicate areas that need further work or improvement.
- For debugging purposes, use comments to explain temporary code and remove them once the code is finalized.
- Maintain updated comments to reflect any changes in the code.
- Avoid leaving commented-out code in the final version unless it serves a clear purpose.

### Best Practices :thumbsup:
- **Code Reviews:** All pull requests require review from at least one team member before merging to ensure quality and consistency.
- **Testing:** Write tests for new features and bug fixes.
- **Documentation:** Update documentation with any changes to the codebase, including new features, API endpoints, and architectural decisions.

### Error Handling :warning:

*Taken from the Backend's CONTRIBUTING.md file.*

- Use async/await with try-catch for asynchronous errors.
- Document API errors and test error flows.

### Security Practices :lock:

*Taken from the Backend's CONTRIBUTING.md file.*

- Secure HTTP headers and validate inputs.
- Protect passwords with hashing.
- Run as non-root.
- **Module Loading Security:** Do not use user-provided variables in module paths for `require()` or `import()` to prevent unauthorized module loading.
- **Child Process Safety:** Validate and sanitize any inputs passed to child processes to prevent command injection.
- **Error Detail Hiding:** Do not expose detailed error information (e.g., stack traces, internal paths) in API responses to prevent leaking sensitive data.

### Architecture & Best Practices Guide :building_construction:

*Taken from the Backend's CONTRIBUTING.md file.*

Organize projects into four layers: Models (data access), Services (business logic), Controllers (request handling), and Router (endpoints). This promotes modularity, testability, and maintainability. Use parameterized queries, keep logic pure, and handle errors appropriately.

### Team Roles :technologist:

The team is organized into specific roles, each one having a designated codeowner, who is responsible for overseeing the work in their area and merging pull requests to the main branch.

The scrum master is responsible for coordinating the team, facilitating communication, and ensuring that the project stays on track.

The Fullstack / Integrators are both capable of working in every area of the project, as well as merging pull requests to the main branch.

| Role | Description | Team Members | Codeowner |
|-|-|-|- |
| Fullstack / Integrators | Work across all areas of the project, ensuring integration and consistency. | Diego Córdova Rodríguez, Mauricio Emilio Monroy González | - |
| Scrum Master | Coordinates the team, facilitates communication, and ensures project progress. | Lorena Chewtat | - |
| Frontend | Focuses on client-side development, user interface design, and user experience. | María Rivera, Valentina Castilla, Luis Emilio Veledíaz, Amilka López | María Rivera |
| Backend | Focuses on server-side development, API design, and database management. | Lorena Chewtat, Isabela Valls, Facundo Esparza, Aquiba Benarroch | Aquiba Benarroch |
| Database | Focuses on database design, management, and optimization. | Lorena Chewtat, Amilka López, Miranda Urban | Lorena Chewtat |
 
 ---

### Project Structure by Team 📁
#### Backend Team
**Folders that belong to this role:** `/certs`, `/controllers`, `/middleware`, `/models`, `/openapi`, `/routes`, `/services`

#### Database Team
**Folders that belong to this role:** `/database`, `/openapi`

#### Frontend Team
**Folders that belong to this role:** `/cypress`, `/public`, `/src`

#### Fullstack / Integrators
**Folders that belong to this role:** All directories

---

### Branches and Pull Requests :seedling:

#### Main Branch :world_map:

- The main branch of the repository will be `main`, for both [Frontend](https://github.com/dittravel/TC3005B.501-Frontend) and [Backend](https://github.com/dittravel/TC3005B.501-Backend). This branch will always contain the latest stable version of the project, and all pull requests must be merged into this branch after passing code review and testing.
- According to the team roles, only the following individuals are authorized to create pull requests to the main branch:
  - Fullstack / Integrators:
    - **Diego Córdova**
     - **Mauricio Monroy**
    - Codeowners of each area:
     - **María Rivera**
     - **Aquiba Benarroch**
     - **Lorena Chewtat**

#### Pull Request Descriptions :memo:

- **Format:** `area_action`
- **Actions:**
  - feat`: new features
  - `fix`: bug fix
  - `test`: tests added
  - `docs`: documentation added
  - `style`: style change
  - `merge`: merge branch to main (include what was done)
- **Areas:**
  - Backend
  - Frontend
  - Database
  - Integration

**Examples:**
  - `feat_backend_add_user_authentication`
  - `fix_frontend_login_bug`
  - `test_database_user_model`
  - `docs_integration_api_endpoints`
  - `style_frontend_button_design`
  - `merge_backend_feature_branch_to_main`

---

### Issues 📖
#### Issue Types 📑

**All** issues in the repository must be categorized with one of the following types. This allows clear organization and also helps the entire team understand the scope and kind of each issue.

| Type | Description | Example |
|-|-|-|
| **Task** | A specific piece of work that needs to be done. | "Create endpoint for trip retrieval" |
| **Sub-Task** | A small piece of work that is part of a larger Task. | "Add input validation to trip endpoint" |
| **Bug** | An unexpected problem or behavior that needs to be fixed. | "Login endpoint returns error" |
| **Feature** | A new functionality or enhancement to the system. | "Add filter by date to trip list" |
| **Documentation** | Documentation that needs to be written or updated. | "Document API authentication flow" |
| **Test** | Tests that need to be written for existing or new code. | "Write tests for expense validation" |

---
---
#### Issue Template Format ℹ️

Every new issue ***must*** follow this structure:

 >[TYPE]: Brief Title

 >#### Description
 >Clear explanation of what needs to be done or what the issue is about.

 >#### Details
 >- Bullet point 1
 >- Bullet point 2
 >- Bullet point 3

 >#### Checklist to complete issue
 >- [ ] To-Do 1
 >- [ ] To-Do 2

 >#### Labels
 >Apply relevant labels from the Backend Label Set.

--- 

### Label Directory 🏷️

*This was taken directly from Coconsulting's repositories and issues.*

| Label | Meaning |
|-|-|
| **admin** | Admin role related issues |
| **API** | API related issues and endpoints |
| **applicant** | Applicant role related issues |
| **authorizer** | Authorizer role related issues |
| **backend** | Backend/server-side related issues |
| **chore** | Something needs to be done (maintenance, refactoring, setup) |
| **database** | Database related issues |
| **documentation** | Improvements or additions to documentation |
| **duplicate** | This issue or pull request already exists |
| **enhancement** | New feature or improvement to existing functionality |
| **good first issue** | Good for newcomers |
| **help wanted** | Extra attention is needed |
| **invalid** | This doesn't seem right |
| **question** | Further information is requested |
| **release** | For Release PRs and version management |
| **security** | Security related issues |
| **small Change Request** | Small changes requested for format or similar issues that allow a PR to be merged |
| **travel agent** | Travel agent role related issues |
| **user** | General user related issues |
| **wontfix** | This will not be worked on |

When creating an issue, you MUST apply at least one label. An example of an issue can be seen below, with its corresponding labels.

---

### Issue Example: Task

[Task]: Create endpoint for expense validation

#### Description
Create a new API endpoint that validates expense receipts for travel requests.

#### Details
- Validate receipt format and amount
- Check against travel request budget
- Return validation status and error messages
- Endpoint: POST to API
#### Checklist
- [ ] Endpoint accepts expense data
- [ ] Returns validation result
- [ ] Error handling implemented
- [ ] Unit tests written

#### Labels
API, backend, enhancement

--- 
