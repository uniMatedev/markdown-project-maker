Prompt Variables:

projectSubject: Minimal viable product principles. [YOUR PROJECT SUBJECT AND SPECIAL INSTRUCTIONS]

projectDescription: A comprehensive guide dedicated to $projectSubject, seeking to offer a holistic approach while emphasizing clarity and precision.

templateReference: Use the provided project directory as a formatting and styling reference.

Objective:

Design a Markdown documentation layout for a new project titled $projectDescription, adhering to the principles of a minimal viable product.

Reference Structure:

minimal-viable-diet-guide
.
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── docs
    ├── diet-principles
    │   ├── 01-basic-nutrition-requirements.md
    │   └── 02-eating-windows.md
    ├── meal-planning
    │   ├── 01-simple-ingredients-selection.md
    │   ├── 02-convenience-optimization.md
    │   └── 03-meal-prepping-techniques.md
    ├── appendices
    │   ├── 01-resources.md
    │   ├── 02-further-reading.md
    │   └── 03-glossary.md
    ├── testimonials
    │   └── 01-real-life-adoption-cases.md
    └── introduction
        ├── 01-overview.md
        └── 02-prerequisites.md
Terminal Command to Generate the Above Directory:

mkdir -p minimal-viable-diet-guide/docs/{diet-principles,meal-planning,appendices,testimonials,introduction} && touch minimal-viable-diet-guide/{CONTRIBUTING.md,LICENSE,README.md} minimal-viable-diet-guide/docs/diet-principles/{01-basic-nutrition-requirements.md,02-eating-windows.md} minimal-viable-diet-guide/docs/meal-planning/{01-simple-ingredients-selection.md,02-convenience-optimization.md,03-meal-prepping-techniques.md} minimal-viable-diet-guide/docs/appendices/{01-resources.md,02-further-reading.md,03-glossary.md} minimal-viable-diet-guide/docs/testimonials/01-real-life-adoption-cases.md minimal-viable-diet-guide/docs/introduction/{01-overview.md,02-prerequisites.md}