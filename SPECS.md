Create a modern Astro landing page for **Nimfi.dev**.

Nimfi.dev is a developer-first digital solutions company that provides:

* Software Development
* AI Platform
* Web and Cloud Hosting
* Web Services
* Cybersecurity

The landing page should feel premium, technical, modern, and cloud-native. The visual direction should be inspired by modern developer platforms such as Neon Database, Vercel, Linear, Supabase, and Cloudflare, but it must have an original Nimfi.dev identity. Do not copy Neon Database exactly. Do not copy their layout, wording, colors, or assets.

## Main Design Style

Use the following design direction:

* Developer-first SaaS
* Dark futuristic
* Minimal and premium
* Light glassmorphism
* Aurora gradient background
* Cloud-native and technical feel
* Clean typography
* Product-focused layout
* Technical but still business-friendly

## Visual Direction

Use a very dark background, around `#0A0A0A`, `#0F0F0F`, or `#111111`.

Use soft aurora gradients behind the hero section. The gradient should feel subtle, premium, and modern, not too colorful or cheap.

Use accent colors such as:

* Cyan
* Electric blue
* Purple
* Subtle green

Prefer one main accent color, such as cyan or blue, and use the other colors only as soft glow or supporting gradient accents.

Use modern fonts such as Inter, Geist, or a similar clean sans-serif font.

Use:

* Thin borders
* `border-white/10`
* `bg-white/5`
* Rounded cards
* Soft shadows
* Subtle background blur
* Plenty of whitespace
* Clean section spacing
* Smooth hover states
* Subtle micro-interactions

Avoid:

* Cartoon illustrations
* Overly colorful gradients
* Heavy animation
* Cheap template look
* Generic corporate design
* Copying Neon’s exact design

## Technical Stack

Build the landing page using:

* Astro
* Tailwind CSS
* Astro components
* Responsive design
* Clean component structure

Use `.astro` components for mostly static sections.

Suggested folder structure:

```txt
src/
  pages/
    index.astro
  components/
    landing/
      Navbar.astro
      Hero.astro
      Services.astro
      Workflow.astro
      AIPlatform.astro
      CloudHosting.astro
      Cybersecurity.astro
      UseCases.astro
      WhyNimfi.astro
      CTA.astro
      Footer.astro
```

Keep the code clean, reusable, and easy to maintain.

## Navbar

Create a sticky or floating navbar with a dark transparent background, subtle blur, and thin border.

Navbar items:

* Services
* AI Platform
* Hosting
* Cybersecurity
* Work
* Contact

Right side buttons:

* Sign in
* Start a Project

If Sign in is not needed, keep only:

* Start a Project

## Hero Section

The hero section should be strong, technical, and premium.

Use this headline:

```txt
Build, host, automate, and secure your digital platform.
```

Use this subheading:

```txt
Nimfi.dev helps businesses build modern software, AI-powered platforms, cloud hosting environments, web services, and cybersecurity solutions with a developer-first approach.
```

CTA buttons:

```txt
Start a Project
Explore Services
```

Hero visual:

Create a large product-style mockup, not a cartoon illustration.

The mockup can combine:

* Dashboard preview
* Terminal UI
* Code snippet
* Cloud deployment status
* Security scan result
* AI automation workflow

Example visual content:

```txt
Deployment Status: Live
AI Workflow: Active
Security Score: 98%
Cloud Region: Southeast Asia
API Latency: 42ms
```

Also include a small code/terminal block, for example:

```ts
await nimfi.deploy({
  app: "client-platform",
  hosting: "cloud",
  ai: true,
  security: "hardened",
})
```

Or terminal style:

```bash
nimfi deploy --cloud --secure --ai-enabled
```

The hero background should include a soft aurora gradient, subtle grid pattern, and glow effects.

## Services Overview Section

Create a section titled:

```txt
Everything you need to build modern digital platforms.
```

Subheading:

```txt
From custom software to AI automation, cloud hosting, web services, and cybersecurity, Nimfi.dev helps teams move from idea to production with confidence.
```

Create 5 service cards:

### 1. Software Development

```txt
Custom web apps, SaaS platforms, admin systems, APIs, dashboards, and internal tools built with modern full-stack technologies.
```

Suggested icon style: code, app window, terminal, or layers.

### 2. AI Platform

```txt
AI-powered workflows, chatbots, automation tools, data processing, and intelligent assistants for business operations.
```

Suggested icon style: spark, neural network, bot, automation.

### 3. Web and Cloud Hosting

```txt
Reliable hosting for websites, apps, APIs, and cloud-native services with scalable infrastructure and deployment support.
```

Suggested icon style: cloud, server, globe, deployment.

### 4. Web Services

```txt
Domain setup, email configuration, website maintenance, integrations, API development, analytics, and performance optimization.
```

Suggested icon style: globe, settings, API, wrench.

### 5. Cybersecurity

```txt
Security hardening, vulnerability assessment, access control, monitoring, secure configuration, and best-practice protection for modern systems.
```

Suggested icon style: shield, lock, scan, alert.

Use glassmorphism cards with subtle hover animation.

## Developer Workflow Section

Create a workflow section that shows how Nimfi.dev works with clients.

Title:

```txt
From idea to secure production.
```

Subheading:

```txt
A clear technical workflow designed to help businesses plan, build, launch, and protect their digital products.
```

Workflow steps:

```txt
Discover
Plan the product, requirements, users, architecture, and technical direction.

Build
Develop the software, platform, API, website, dashboard, or automation workflow.

Deploy
Launch on reliable web or cloud hosting with performance and scalability in mind.

Secure
Apply cybersecurity best practices, access control, monitoring, and system hardening.

Improve
Maintain, optimize, integrate, and enhance the platform over time.
```

Present this as horizontal cards on desktop and vertical cards on mobile.

## AI Platform Section

Create a dedicated section for AI Platform.

Title:

```txt
AI-powered tools for modern operations.
```

Subheading:

```txt
Nimfi.dev helps businesses design and deploy AI workflows that reduce manual work, improve response time, and unlock smarter digital experiences.
```

Feature points:

```txt
AI chatbots and assistants
Document and data processing
Business workflow automation
AI-powered customer support
Internal knowledge assistants
API-based AI integrations
```

Add a technical visual such as an AI workflow card:

```txt
Input → Process → AI Decision → Automation → Result
```

Or use a mock dashboard:

```txt
AI Tasks Completed
1,284 this month

Average Response Time
1.8s

Automation Success Rate
98.7%
```

## Cloud Hosting Section

Create a section for Web and Cloud Hosting.

Title:

```txt
Fast, reliable hosting for websites, apps, and APIs.
```

Subheading:

```txt
Deploy business websites, web applications, APIs, and cloud-native services with a reliable hosting setup built for performance, security, and maintainability.
```

Feature points:

```txt
Website and app hosting
API hosting
Cloud deployment support
Domain and DNS setup
SSL configuration
Performance optimization
Monitoring and maintenance
Scalable infrastructure planning
```

Use a cloud infrastructure visual with nodes, deployment cards, or a terminal deployment preview.

Example cards:

```txt
Production
Live

SSL
Active

DNS
Configured

Monitoring
Enabled
```

## Cybersecurity Section

Create a dedicated cybersecurity section.

Title:

```txt
Security built into every layer.
```

Subheading:

```txt
Protect your digital platforms with secure configuration, access control, hardening, monitoring, and practical cybersecurity best practices.
```

Feature points:

```txt
Security hardening
Vulnerability assessment
Access control review
Secure server configuration
Cloud security best practices
Website and API protection
Monitoring and incident readiness
Authentication and authorization review
```

Use a security dashboard visual:

```txt
Security Score
98%

Threat Monitoring
Enabled

SSL Status
Valid

Access Control
Reviewed

Vulnerabilities
0 Critical
```

Keep the section clean and professional. Avoid making unrealistic claims such as “100% secure”.

## Web Services Section

Create a section for Web Services.

Title:

```txt
Web services that keep your platform running smoothly.
```

Subheading:

```txt
Nimfi.dev supports the essential web services businesses need to launch, operate, integrate, and maintain their digital presence.
```

Feature points:

```txt
Domain setup
DNS configuration
Business email setup
Website maintenance
API integration
Analytics setup
Performance tuning
Backup and migration support
```

## Why Nimfi.dev Section

Create a section titled:

```txt
Why teams choose Nimfi.dev
```

Use 4 cards:

### Developer-first approach

```txt
Every project is designed with clean architecture, maintainable code, and long-term scalability in mind.
```

### Full-stack capability

```txt
From frontend and backend to hosting, AI, integrations, and security, Nimfi.dev supports the full digital product lifecycle.
```

### Cloud-native mindset

```txt
Build and deploy platforms using modern infrastructure practices, scalable hosting, and reliable web technologies.
```

### Security-aware delivery

```txt
Security is considered from planning to deployment, not treated as an afterthought.
```

## Use Cases Section

Create a use cases section.

Title:

```txt
Built for businesses, teams, and digital products.
```

Use case cards:

### SaaS Platforms

```txt
Build multi-tenant SaaS platforms with authentication, dashboards, APIs, organizations, roles, and billing-ready architecture.
```

### Business Websites

```txt
Launch fast, modern, and maintainable websites for companies, agencies, services, and organizations.
```

### Admin Systems

```txt
Create internal dashboards, management systems, reporting tools, and secure admin panels.
```

### AI Automation

```txt
Automate repetitive business processes using AI workflows, chatbots, assistants, and API integrations.
```

### Cloud Applications

```txt
Deploy web apps, APIs, and backend services on reliable cloud infrastructure.
```

### Security Improvement

```txt
Improve the security posture of websites, servers, applications, and cloud environments.
```

## Optional Tech Stack Section

Add a small section showing modern technologies Nimfi.dev can work with.

Title:

```txt
Modern tools for modern platforms.
```

Example tags:

```txt
Astro
React
TanStack
Hono
Node.js
TypeScript
PostgreSQL
Drizzle ORM
Cloudflare
Vercel
Docker
Linux
AI APIs
Cybersecurity
```

Display them as small pill badges with subtle borders and hover effect.

## Final CTA Section

Create a strong final CTA.

Title:

```txt
Ready to build your next digital platform?
```

Subheading:

```txt
Let Nimfi.dev help you design, build, host, automate, and secure your next software, AI, cloud, or web project.
```

CTA buttons:

```txt
Start a Project
Contact Nimfi.dev
```

## Footer

Footer columns:

### Company

```txt
About
Work
Contact
```

### Services

```txt
Software Development
AI Platform
Web and Cloud Hosting
Web Services
Cybersecurity
```

### Resources

```txt
Docs
Blog
Status
Changelog
```

### Legal

```txt
Privacy
Terms
Security
```

Footer tagline:

```txt
Nimfi.dev — Build smarter. Host faster. Secure everything.
```

## Overall Tone

The copywriting should feel:

* Professional
* Technical
* Confident
* Modern
* Clear
* Business-friendly
* Developer-first

Avoid sounding too generic or too corporate.

Avoid exaggerated claims.

Use short, direct sentences.

## Suggested Main Tagline

Use this tagline somewhere on the page:

```txt
Build smarter. Host faster. Secure everything.
```

Alternative supporting line:

```txt
Modern software, AI, cloud, and security for teams that build.
```

## UI Requirements

The page must be fully responsive.

Desktop:

* Large hero headline
* Centered hero content
* Large mockup preview
* Multi-column cards
* Smooth spacing

Mobile:

* Stack all sections vertically
* Navbar should collapse or remain simple
* Cards should be full width
* Text should remain readable
* Hero mockup should scale properly

Use Tailwind CSS classes such as:

```txt
bg-[#0A0A0A]
bg-white/5
border-white/10
text-white
text-slate-400
rounded-2xl
backdrop-blur
shadow-2xl
```

Use subtle hover effects:

```txt
hover:bg-white/10
hover:border-white/20
hover:-translate-y-1
transition-all
duration-300
```

Use subtle gradients:

```txt
bg-[radial-gradient(circle_at_top,rgba(34,211,238,0.18),transparent_35%)]
```

## Important

Do not create a generic agency website.

The website should look like a premium developer platform landing page.

The final result should feel suitable for a company offering software development, AI platform services, web and cloud hosting, web services, and cybersecurity.

Use original content, original layout, and original visual identity for Nimfi.dev.
