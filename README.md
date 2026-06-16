This is a professionally crafted README.md designed to make your GitHub repository stand out. It uses a clean structure, technical depth, and visual elements to reflect the quality of the application.

🚀 DevEstimator Pro

!\[alt text](https://img.shields.io/badge/license-MIT-green)



!\[alt text](https://img.shields.io/badge/version-1.0.0-blue)



!\[alt text](https://img.shields.io/badge/tech-Vanilla%20JS-yellow)



!\[alt text](https://img.shields.io/badge/css-Tailwind-blue)

DevEstimator Pro (codenamed ScopeIt) is a high-performance, single-page application designed for freelancers and software engineers to bridge the gap between "guessing" and "proposing." It provides a professional dashboard to calculate project costs, delivery timelines, and risk buffers with surgical precision.

Live Demo Placeholder | Report Bug

📸 Screenshots

Dashboard Overview	Mobile Responsive View

!\[alt text](./screenshots/dashboard.png)

!\[alt text](./screenshots/mobile.png)

✨ Key Features

⚡ Live Estimation Engine

Experience real-time recalculations as you type. The engine factors in:

Base Variables: Hourly rate and estimated project duration.

Complexity Multipliers: Choose between Low (1.0x), Medium (1.2x), and High (1.5x) to account for technical debt or research requirements.

Tech Stack Premiums: Add fixed-cost premiums for specialized services like MERN Stack, DevOps, or Cloud Architecture.

🌍 Multi-Currency Support

One-click toggle between USD ($), MAD (DH), and EUR (€). All calculations, including the risk buffer and breakdown, update their formatting and symbols instantly.

📊 Automated Phase Breakdown

Visualizes the project lifecycle using a dynamic progress bar system:

Planning (15%): Discovery and scoping.

Development (50%): Core engineering.

Testing (20%): QA and bug fixing.

Deployment (15%): Handover and CI/CD.

🛡️ Smart Risk Management

Automatically suggests a 15% to 20% Risk Buffer based on project complexity, ensuring you never underquote for high-risk requirements.

📄 Professional Export

Includes a CSS-optimized Print-to-PDF function. The export removes UI controls (inputs/buttons) and generates a clean, branded estimate document ready for client delivery.

🛠️ Tech Stack

Technology	Purpose

HTML5	Semantic structure and document architecture.

Tailwind CSS	Modern, dark-themed UI (Slate-900) with glassmorphism effects.

Vanilla JavaScript	Logic engine, state management, and DOM manipulation (Zero Dependencies).

Lucide Icons	SVG-based iconography for a premium feel.

🧬 Estimation Logic

The application uses the following formula to ensure financial accuracy:

T

o

t

a

l

C

o

s

t

=

(

(

H

o

u

r

l

y

R

a

t

e

×

E

s

t

i

m

a

t

e

d

H

o

u

r

s

)

×

C

o

m

p

l

e

x

i

t

y

M

u

l

t

i

p

l

i

e

r

)

\+

∑

T

e

c

h

A

d

d

o

n

s

TotalCost=((HourlyRate×EstimatedHours)×ComplexityMultiplier)+∑TechAddons

Timeline: Based on a standard 40-hour work week.

Buffer: Calculated as Total Cost \* 0.15 (Low/Med) or Total Cost \* 0.20 (High).

🚀 Setup \& Installation

Since DevEstimator Pro is built with vanilla technologies and utilizes Tailwind via CDN, there is no build step required.

Clone the repository:

code

Bash

git clone https://github.com/yourusername/devestimator-pro.git

Navigate to the directory:

code

Bash

cd devestimator-pro

Open the application:

Simply double-click index.html or serve it using Live Server in VS Code.

📝 Usage Guide

Configure: Input your project name and base hourly rate.

Scope: Select the anticipated hours and complexity level.

Stack: Toggle the specific technology add-ons required for the project.

Review: Analyze the Phase Breakdown to ensure the timeline is realistic.

Export: Click "Export Estimate PDF" to save a professional summary for your client.

📄 License

Distributed under the MIT License. See LICENSE for more information.

Built with ☕ and JS by \[SOUKAINA HARIFI]

