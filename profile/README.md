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
  - [Technology Stack :computer:](#technology-stack-computer)
  - [Version Control :herb:](#version-control-herb)
  - [Project Structure :file_folder:](#project-structure-file_folder)
  - [Best Practices :thumbsup:](#best-practices-thumbsup)
  - [Team Roles :technologist:](#team-roles-technologist)
  - [Branches and Pull Requests :seedling:](#branches-and-pull-requests-seedling)
    - [Main Branch :world_map:](#main-branch-world_map)
    - [Pull Request Descriptions :memo:](#pull-request-descriptions-memo)

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
- **Variable Naming:** Use camelCase for variable names (e.g., `userName`, `isActive`). This applies to both JavaScript/TypeScript and any other languages used in the project.
- **Indentation:** Respect consistent indentation. Use 2 spaces for indentation in all code files to ensure readability and uniformity across the codebase.
- **Comments:** Place descriptive comments above each function explaining what it does. Add inline comments within functions only for complex logic that requires additional clarification.

For each function, include a comment block that describes the function's purpose, its parameters, and its return value. For example:

```javascript/**
 * Get the amount of users in the system from a specified role.
 * @param {string} role - The role to filter users by (e.g., "admin", "customer").
 * @returns {number} The number of users with the specified role.
 */

function getUserCountByRole(role) {
  // Implementation goes here
}
```

If any console.log statements were previously used for debugging, they must be removed before merging to the main branch to maintain a clean codebase, while leaving a comment indicating that they were used for debugging purposes. Example:

```javascript
// console.log("Debug: User count by role:", userCount); // Used for debugging
// remove before merging to main
```

### Technology Stack :computer:

- **Languages:** The project uses a mix of TypeScript and JavaScript within the Astro framework. Prefer TypeScript for new components, falling back to JavaScript only when necessary.

- **Framework:** Astro is the primary framework for building the project.

- **Backend:** Node.js with Express for API development.

- **Database:** MongoDB for data storage and management. MariaDB for all application data.

### Version Control :herb:
- **Branch Naming:** Each branch name must include the owner's name and the relevant area (e.g., `diego-frontend-auth`, `isabela-backend-api`). This helps in tracking contributions and organizing work.
- **Commit Messages:** Write clear, concise commit messages in English, starting with a verb (e.g., "Add user authentication", "Fix login bug"). Reference issue numbers when applicable.

### Project Structure :file_folder:
- **File Organization:** Maintain a clean folder structure. Group related files in appropriate directories (e.g., components in `src/components/`, utilities in `src/utils/`).
- **Imports:** Use relative imports for files within the same module and absolute imports for shared utilities to keep dependencies clear.

### Best Practices :thumbsup:
- **Code Reviews:** All pull requests require review from at least one team member before merging to ensure quality and consistency.
- **Testing:** Write tests for new features and bug fixes.
- **Documentation:** Update documentation with any changes to the codebase, including new features, API endpoints, and architectural decisions.

### Team Roles :technologist:

The team is organized into specific roles, each one having a designated codeowner, who is responsible for overseeing the work in their area and merging pull requests to the main branch.

The scrum master is responsible for coordinating the team, facilitating communication, and ensuring that the project stays on track.

The Fillstack / Integrators are both capable of working in every area of the project, as well as merging pull requests to the main branch.

| Role | Description | Team Members | Codeowner |
|-|-|-|- |
| Fullstack / Integrators | Work across all areas of the project, ensuring integration and consistency. | Diego Córdova Rodríguez, Mauricio Emilio Monroy González | - |
| Scrum Master | Coordinates the team, facilitates communication, and ensures project progress. | Lorena Chewtat | - |
| Frontend | Focuses on client-side development, user interface design, and user experience. | María Rivera, Valentina Castilla, Luis Emilio Veledíaz, Amilka López | María Rivera |
| Backend | Focuses on server-side development, API design, and database management. | Lorena Chewtat, Isabela Valls, Facundo Esparza, Aquiba Benarroch | Aquiba Benarroch |
| Database | Focuses on database design, management, and optimization. | Lorena Chewtat, Amilka López, Miranda Urban | Lorena Chewtat |

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