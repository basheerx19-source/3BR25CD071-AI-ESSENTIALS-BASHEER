# Academic & Career Portfolio: Smart Traffic Light Research & Coursework

This repository contains academic assignments, career profile documentation, and research work submitted by **MD Mubasheer Ahmed** (USN: `3BR25CD071`), a Computer Science and Engineering (Data Science) undergraduate student at **Ballari Institute of Technology & Management (BITM)**.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Key Features & Research Focus](#key-features--research-focus)
  - [Research Paper Summary](#research-paper-summary)
  - [Interactive Project Reference](#interactive-project-reference)
  - [Resume & Curriculum Vitae (CV)](#resume--curriculum-vitae-cv)
- [Architecture Diagram](#architecture-diagram)
- [Tech Stack & Tools](#tech-stack--tools)
- [Prerequisites](#prerequisites)
- [Viewing & Document Inspection](#viewing--document-inspection)
- [Software Development & Execution Notes](#software-development--execution-notes)
- [Author & Academic Details](#author--academic-details)
- [License](#license)

---

## Project Overview

The repository hosts core academic submissions and project references, centered around a research paper on **Smart Traffic Lights Using Local Artificial Intelligence** along with academic resume/CV documents and external coding assignment links.

### Key Objectives
* **Research Exploration:** Conceptualizing edge-computing AI architectures for adaptive traffic signal control and emergency vehicle signal preemption.
* **Academic Documentation:** Providing standardized CV, Resume, and assignment documentation for academic and career submissions.
* **Web Project Linkage:** Documenting web-based interactive projects (such as game prototypes) linked as part of course assignments.

---

## Repository Structure

```
.
├── 3BR25CD071-ASSIGMENT-RESEARCH-PAPER.pdf  # Research paper on Smart Traffic Lights Using Local AI
├── 3BR25CD071-CV-APPLICATION.pdf           # Detailed Academic Curriculum Vitae (CV)
├── 3BR25CD071-RESUME.pdf                   # Professional Resume / CV Summary
├── DAY-2-CODING-ASSIGMENT.md               # Link reference to the Bike Stunt Game assignment
└── README.md                               # Project documentation and guide
```

---

## Key Features & Research Focus

### Research Paper Summary
* **Title:** *Smart Traffic Lights Using Local Artificial Intelligence*
* **Author:** Basheer (Department of Computer Science and Engineering, BITM)
* **Abstract:** Proposes an edge computing architecture for traffic signal control. Roadside cameras capture video feeds, which are processed locally on a "Smart Pole Computer" using computer vision models to estimate vehicle counts and queue lengths. The processed data is sent directly to the local Traffic Signal Controller for real-time adaptive signal adjustment, with optional cloud synchronization for long-term analytics.
* **Emergency Vehicle Preemption:** Explores integrating local computer vision with pre-existing emergency-vehicle preemption systems to safely grant priority to approaching emergency vehicles across single or multi-intersection routes.

### Interactive Project Reference
* **File:** `DAY-2-CODING-ASSIGMENT.md`
* **URL:** [Car Game / Bike Stunt Game Prototype](https://cargameinstant.vercel.app/bike)
* **Description:** A physics-based web game ("Stunt Rider / Canyon Run") featuring throttle, braking, and lean controls.

### Resume & Curriculum Vitae (CV)
* **Files:** `3BR25CD071-RESUME.pdf`, `3BR25CD071-CV-APPLICATION.pdf`
* **Profile:** MD Mubasheer Ahmed, BE in Computer Science & Engineering (Data Science), Ballari Institute of Technology & Management.
* **Technical Highlights:** Programming in C, C++, Python, Java; Data Science & Machine Learning fundamentals; Web technologies (HTML, CSS, JavaScript) and SQL.

---

## Architecture Diagram

The diagram below illustrates the local AI smart traffic signal architecture detailed in `3BR25CD071-ASSIGMENT-RESEARCH-PAPER.pdf`:

```mermaid
flowchart LR
    subgraph Intersection Hardware
        A[Street Cameras] -->|Video / Frames| B[Smart Pole Computer\nLocal Edge AI]
        B -->|Traffic Metrics & Priority Requests| C[Traffic Signal Controller]
        C -->|Signal Operations| D((Traffic Lights))
    end

    subgraph Cloud Infrastructure (Optional)
        B -.->|Historical Data & Telemetry| E[Cloud Server]
        E -.->|Model Updates & Analytics| B
    end
```

---

## Tech Stack & Tools

* **Document Formats:** PDF (Research paper, Resume, CV), Markdown (`.md`)
* **Core Domains / Focus:** Data Science, Machine Learning, Computer Vision, Edge Computing, Intelligent Transportation Systems (ITS)
* **Programming Languages & Skills (Academic):** Python, C, C++, Java, HTML, CSS, JavaScript, SQL
* **Tools & Platforms:** Git, GitHub, Visual Studio Code, Vercel (Deployment host for linked web game)

---

## Prerequisites

To view and inspect the contents of this repository locally, ensure you have:

* **PDF Viewer:** Adobe Acrobat Reader, Evince, Okular, or any modern web browser (Chrome, Firefox, Edge, Safari).
* **Git:** Installed on your local machine for cloning the repository.
* **Python (Optional - for text extraction):** Python 3.x with `pypdf` installed if programmatic text extraction from PDF files is required.

---

## Viewing & Document Inspection

### 1. Clone the Repository
```bash
git clone https://github.com/basheerx19-source/<repository-name>.git
cd <repository-name>
```

### 2. View PDF Documents
Open the PDF files in your preferred PDF viewer or browser:
* `3BR25CD071-ASSIGMENT-RESEARCH-PAPER.pdf`
* `3BR25CD071-CV-APPLICATION.pdf`
* `3BR25CD071-RESUME.pdf`

### 3. Extract Text Programmatically (Optional Python Script)
If you wish to parse or inspect document text via Python:
```bash
pip install pypdf
python3 -c "
import pypdf
reader = pypdf.PdfReader('3BR25CD071-ASSIGMENT-RESEARCH-PAPER.pdf')
for i, page in enumerate(reader.pages):
    print(f'--- Page {i+1} ---')
    print(page.extract_text())
"
```

---

## Software Development & Execution Notes

Because this repository primarily serves as a document and assignment submission repository rather than a standalone executable codebase, standard software lifecycle configurations are documented below for clarity:

| Section | Status / Applicability |
| :--- | :--- |
| **Environment Variables** | Not Applicable (No runtime backend service present). |
| **Database & Migrations** | Not Applicable (No active database instance configured in repo). |
| **API Documentation** | Not Applicable (No REST/GraphQL endpoints exported). |
| **Authentication** | Not Applicable. |
| **Docker / Containers** | Not Applicable (No Dockerfile or Compose file in repository). |
| **CI / CD Pipelines** | Not Applicable (No CI workflow configurations present). |
| **Testing & Linting** | Not Applicable (No unit tests or linters configured). |

*Note: For the interactive web game referenced in `DAY-2-CODING-ASSIGMENT.md`, access the live web deployment directly at [https://cargameinstant.vercel.app/bike](https://cargameinstant.vercel.app/bike).*

---

## Author & Academic Details

* **Author:** MD Mubasheer Ahmed
* **USN:** `3BR25CD071`
* **Department:** Computer Science and Engineering (Data Science)
* **Institution:** Ballari Institute of Technology & Management (BITM), Ballari, Karnataka, India
* **Email:** [mubasheerx19@gmail.com](mailto:mubasheerx19@gmail.com) / [mubasheer@gmail.com](mailto:mubasheer@gmail.com)
* **GitHub Profile:** [github.com/basheerx19-source](https://github.com/basheerx19-source)
* **LinkedIn Profile:** [linkedin.com/in/mubasheer-ahmed-3459463a7](https://linkedin.com/in/mubasheer-ahmed-3459463a7)

---

## License

No explicit license file is included in this repository. All research paper contents, resumes, CVs, and assignment files remain the intellectual property of the author (**MD Mubasheer Ahmed**). For permissions or usage inquiries, please reach out via email.
