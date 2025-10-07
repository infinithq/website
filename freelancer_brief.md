Project Brief: industry.infinit.dev Hugo Static Site
Overview
Build a Hugo static site for (not yet existing) industry.infinit.dev that visually matches infinit.dev (WordPress) while maintaining strict separation between content, structure, and presentation.

Deliverables
1. Hugo Static Site

Complete Hugo project structure
Custom shortcode system for content sections
Modular, maintainable CSS
Responsive design (mobile/tablet/desktop)
GitHub action to deploy to GitHub Pages

2. Git Repository (GitHub)

Clean commit history with descriptive messages
README with setup/deployment documentation
.gitignore configured for Hugo

3. Design Assets

Figma or directly HTML/CSS/Hugo proposals for new style components
Style guide documentation


Content so far. Depending on how it feels on website we might extend.
Complete content provided as Markdown [industry_minisite.md](industry_minisite.md)

# **Empowering Industry Through Software**

We help industrial and hardware manfacturers modernize by applying software development principles to their automation systems. This means:
- Systems that can be updated and improved continuously
- Data that flows freely and brings real insights
- Future-proofing by prefering open solutions over proprietary ones
- Teamwork and shared knowledge without relying on a single person
- Use the power of AI to assist in the development process

# Case Studies

## **Industrial IoT Data Platform**
**Client:** PollakSala.sk - Vegetable processing equipment manufacturer

**Challenge:** Bridge traditional industrial automation with modern IT infrastructure while keeping architecture simple and avoiding major cloud providers.

**Solution:** Built a complete data platform that ingests data from factory PLCs via MQTT, processes it with Python, stores it in PostgreSQL with TimescaleDB, and provides real-time visualization through Grafana dashboards.

**Key Benefits:**
- Real-time machine performance monitoring
- Centralized data insights for operators and managers
- Edge-to-cloud architecture with data buffering for network resilience
- Simple, maintainable system using proven open-source tools

**Technologies:** Python, MQTT, Docker, PostgreSQL/TimescaleDB, Grafana, Fly.io

---

## **EV Charging Station Integration**
**Client:** Original Equipment Manufacturer (OEM)

**Challenge:** Develop a flexible, modular software solution for EV charging station control with low budget and tight deadline.

**Solution:** Created a Python-based control system with async communication for Modbus RTU and CAN Bus protocols, featuring a real-time reactive web interface and modular architecture.

**Key Benefits:**
- Flexible configuration for different hardware setups
- Modular design for easy extension and maintenance
- Industrial-grade ARM Linux platform deployment
- Efficient concurrent hardware communication

**Technologies:** Python/asyncio, Modbus RTU, CAN Bus, MQTT, WebSockets, Alpine.js, ARM Linux

## Our Technology Philosophy
🛡️ Proven & Stable
We choose mature technologies with strong community support and long-term viability.

🔓 Vendor Independence
Open-source solutions prevent lock-in and give you control over your infrastructure.

⚡ Simple Architecture
Clean, understandable systems that your team can maintain and extend.

---
Footer with contact info like at infinit.dev

---

Technical Requirements
Hugo Shortcode System:
{{< subsection 
    type="text|list|case-study|philosophy" 
    headline1="Optional category" 
    headline2="Section title"
    background="light|dark|brand"
    id="optional-id" >}}
Content in Markdown...
{{< /subsection >}}

Code Quality:

Clean, commented code
Hugo best practices
Modular CSS architecture
No hardcoded content in templates


Design Process
Assets Provided:

infinit.dev (WordPress site - visual reference only)
Figma file with informal brand system. (TODO attach Figma file)

Footer: <img width="1283" height="449" alt="Image" src="https://github-production-user-asset-6210df.s3.amazonaws.com/135344/498255963-a888dae1-2147-45c1-99e7-e0f587d5aebf.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251007%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251007T104847Z&X-Amz-Expires=300&X-Amz-Signature=c8ef35e281fa1d28e1ce7381b389d33d901ee10c6692c18e176f76ef6fd3d9f5&X-Amz-SignedHeaders=host" />

Workflow:

Extract applicable styles from infinit.dev
Identify style gaps for industry.infinit.dev content
Create Figma proposals for new components
Review cycle (expect ~2 iterations per component)
Implement approved designs

Key Principle: Content editors modify Markdown only, never touching templates or CSS.


Success Criteria
✓ Visual parity with infinit.dev brand
✓ Content/presentation separation maintained
✓ Clean Git history with proper workflow
✓ Documentation enables future maintenance
✓ Responsive across all devices
✓ Fast Hugo build times

Questions for Bidders

Portfolio: Hugo sites with custom shortcodes?
Process: Extracting styles from existing sites?
Git workflow: Describe your branching/PR strategy
Design iteration: How do you handle feedback cycles?
Timeline: ?


Budget: max $800 including UpWork fees
Type: Fixed price
Skills: Hugo, Git/GitHub, CSS, Figma, Responsive Design
To Apply: Share portfolio examples and describe your approach to content/presentation separation in static sites.