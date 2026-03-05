# BitPadLabs Government Solutions - Site Instructions

## Critical Information

### Company Structure
- **BPL-GS (BitPadLabs Government Solutions LLC)** is a newly formed Service-Disabled Veteran-Owned Small Business (SDVOSB)
- **BPL-GS has NO contracts yet** - this is critical to maintain accuracy
- BPL-GS operates with BPL LLC as its technical service provider
- Ryan Burke (service-disabled veteran) is Managing Member and CEO
- Team members bring individual federal expertise, not BPL-GS corporate past performance

### Never Claim
- Do NOT claim BPL-GS has contracts, clients, or corporate past performance
- Do NOT use specific project names (EOS, Project Castle, Fast Lane) - these belong to individual team members' past work
- Do NOT claim impact metrics or client logos yet
- NAICS codes set to "00000" (Pending)

### Always Maintain
- Frame expertise as "Team Expertise Available Through BPL-GS"
- Use generic capability descriptions instead of specific project names
- Acknowledge BPL-GS is newly formed when showing placeholders
- Use "Veteran-led. Mission-driven." tagline consistently

## Messaging & Positioning

### Primary Differentiator
"Most federal contractors deliver application-level work within pre-existing platforms. BPL-GS brings enterprise platform creation and governance expertise that few organizations possess."

### Key Capabilities (Enterprise Platform Focus)
1. **Enterprise Cloud Platforms** - AWS GovCloud multi-account architectures with NIST 800-53 security baselines, ATO control inheritance, TBM cost attribution
2. **Enterprise Observability Governance** - FedRAMP High observability services with TBM tagging, Terraform enforcement, sensitive data quarantine
3. **GitHub Enterprise at Scale** - 1,500+ repos at SEC, 1,000+ repos at CMS, enterprise-wide migrations from legacy systems
4. **Multi-Vendor Coordination** - Platform governance across 5+ vendor teams as vendor-neutral authority
5. **OPM Modernization Trifecta** - Cloud migration + SAFe transformation + centralized tooling (2010-2021, 2023-2025)

### Target Market
Primary: **Veterans Affairs (VA)** modernization
- Healthcare IT
- Benefits Platform
- Compliance & Accessibility
- SAFe Transformation
- Cloud & Infrastructure

### Federal Mandates We Support
- OMB M-21-31 (logging, tagging, audit)
- OMB M-22-09 (Zero Trust)
- OMB M-22-18 (Software Supply Chain)
- OMB M-23-22 (Digital Experience)
- NIST 800-53, FISMA, SCuBA, FITARA
- Technology Business Management (TBM)

## Design & Branding

### Color Palette (Blue/Yellow Poison Dart Frog Theme)
- **Honey Yellow** (#EBCB2A) - Primary headings, CTAs, accents
- **Federal Blue** (#0C3EA4) - Section headings, links
- **Navy Slate** (#172030) - Dark backgrounds, subheadings
- **Sage Gray** (#59675B) - Body text
- **Silver Sage** (#ACB8AF) - Muted text, borders
- **Off-White** (#FCFCFC) - Page backgrounds

### Brand Assets
- **Logo**: frog-trimmed.png (blue/yellow frog)
- **SDVOSB Badge**: Service-Disabled Veteran-Owned-Certified.png (in footer only)
- **Team Photos**: ryan.jpeg, chris.jpg, jaime5.jpeg, hannah.jpg, melanie2.jpeg
- **Favicons**: favicon-16.png, favicon-32.png (generated from frog logo)

### Typography Rules
- **NO EM DASHES EVER** - Use regular hyphens or avoid
- Use Google Fonts: Poppins and Montserrat
- Keep headings clear and accessible

## Team Structure

### Leadership Team (in team.yml order)
1. **Ryan Burke** - Managing Member & CEO
   - Service-disabled veteran
   - Image: ryan.jpeg
   - GitHub: ryanburke

2. **Chris Inman** - Chief Technology Officer
   - 20 years federal DevSecOps (OPM, CMS, FSA, SEC)
   - Primary source of technical capabilities
   - Image: chris.jpg
   - GitHub: cinman

3. **Jaime Inman** - Chief Operating & Financial Officer
   - Financial management, operations
   - Image: jaime5.jpeg
   - GitHub: jaimeinman

4. **Hannah Cassels** - Chief Product Officer
   - Product strategy, user experience
   - Image: hannah.jpg
   - GitHub: hannahcassels

5. **Melanie Amerson** - Chief Strategy Officer
   - Business development, acquisitions strategy
   - FAC-COR certified
   - Image: melanie2.jpeg
   - GitHub: mamerson

## Technical Setup

### Jekyll Configuration
- Static site generator with GitHub Pages
- Uses jekyll-feed and jekyll-seo-tag plugins
- Custom layouts: default.html, post.html
- Posts in _posts/ directory with YYYY-MM-DD-title.md format

### File Structure
```
/
├── _config.yml          # Site config (title, email, CAGE/UEI/DUNS)
├── _data/
│   ├── team.yml         # Team member data
│   └── naics.yml        # NAICS codes (currently 00000)
├── _includes/
│   ├── header.html      # Site header with nav
│   ├── footer.html      # Footer with frog, SDVOSB badge, tagline
│   └── cookie-consent.html
├── _layouts/
│   ├── default.html     # Main layout
│   └── post.html        # Blog post layout
├── _posts/              # Blog posts (markdown)
├── _sass/               # SCSS partials
├── assets/images/       # All images
├── index.html           # Homepage
├── services.html        # VA-focused services
├── capabilities.html    # Enterprise capabilities
├── team.html            # Leadership team
├── news.html            # News listing
├── contact.html         # Contact info
├── about.html           # Company story
├── terms.html           # Terms of service
├── privacy.html         # Privacy policy
├── CNAME                # bitpadlabsgs.com
└── DEPLOYMENT.md        # Deployment instructions
```

### Important Config Settings
- `baseurl: ""` (empty for root domain)
- `url: "https://bitpadlabsgs.com"`
- **DO NOT** include `"*.md"` in exclude list (breaks posts)
- Exclude: Gemfile, node_modules, vendor, README.md, LICENSE

## Content Guidelines

### Homepage (index.html)
- Hero section with frog logo (NOT SDVOSB badge at top)
- Feature cards: SDVOSB, VA Focus, DevSecOps, Cloud, SAFe, Compliance
- "Leaping Into Action" section with frog emoji - honest "no clients yet" messaging
- CTA buttons to services and contact

### Capabilities Page
- Lead with "Enterprise Platform Achievements" (rare, differentiating capabilities)
- GitHub scale: 1,500+ repos SEC, 1,000+ repos CMS
- OPM modernization trifecta: cloud + SAFe + tooling
- Core competencies focused on enterprise platform work
- Certifications with GitHub Advanced Security FIRST
- Team federal experience by agency
- Federal mandate alignment
- SAFe training offerings

### Services Page
- Organized by VA use cases:
  1. Healthcare IT Modernization
  2. Benefits Platform Modernization
  3. Compliance & Accessibility
  4. SAFe Transformation & Training
  5. Cloud & Infrastructure
  6. Technology Business Management (TBM)

### News Posts
- Use YYYY-MM-DD-title.md format in _posts/
- Front matter: layout: post, title, date
- Current posts:
  - 2025-01-15-bpl-gs-formation.md
  - 2025-01-16-va-modernization-intent.md

### Contact Page
- Email: info@bitpadlabsgs.com
- Contracting info in footer: CAGE 19LR5, UEI Z6AWKL6J3RV9, DUNS 144948581
- "Capability Statement: In development"

## Placeholder Sections (Future Work)

### To Add Later
- Case studies (2-3 sanitized project stories from team experience)
- Contract vehicles page (GSA Schedule when applicable)
- Capability statement PDF download
- Client logos (when contracts awarded)
- Proper impact metrics (replace "Leaping Into Action" frog section)
- Google Analytics (new GA4 property separate from BitPadLabs)
- favicon.ico (current PNGs work but .ico preferred)

### Future Content Sections
- Ryan Burke bio expansion (growth/BD focus)
- Melanie Amerson sections (strategy/acquisitions, FAC-COR)
- Values/culture page expansion
- News/events sections

## Common Pitfalls to Avoid

1. **Never add em dashes** - User explicitly forbids them
2. **Do not move SDVOSB badge to header** - Footer and "Leaping Into Action" section only
3. **Do not claim BPL-GS contracts** - Always frame as team expertise
4. **Do not use specific project names** - Generic capability descriptions only
5. **Do not exclude *.md files** in _config.yml - Breaks Jekyll posts
6. **Do not create duplicate content sections** - Always check for existing content first
7. **Do not use future dates on posts** - Jekyll won't display them
8. **Do not forget TBM** - It's a key differentiator across services and capabilities

## Deployment

### GitHub Pages Setup
1. Push to GitHub repository
2. Settings > Pages > Deploy from main branch
3. Custom domain: bitpadlabsgs.com
4. CNAME file already in root

### Local Testing
- User has Ruby 2.6.10 (GitHub Pages will handle Gemfile.lock)
- No local bundle install needed
- GitHub Pages builds automatically on push

## Content Accuracy Checklist

Before publishing any changes:
- [ ] No specific project names (EOS, Castle, Fast Lane)
- [ ] No BPL-GS contract/client claims
- [ ] Team expertise framed correctly
- [ ] No em dashes in content
- [ ] SDVOSB badge in footer only
- [ ] Frog branding consistent
- [ ] Federal mandate alignment accurate
- [ ] TBM mentioned where relevant
- [ ] GitHub scale numbers accurate (1500+/1000+)
