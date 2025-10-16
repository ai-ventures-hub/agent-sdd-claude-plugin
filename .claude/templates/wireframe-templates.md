WIREFRAME_TEMPLATES:

DESIGN_AGENT_USAGE:
- PAGE_TYPES: home, dashboard, auth, settings, profile, admin
- INPUT_SOURCES: overview.md, tech-stack.md, user-personas
- OUTPUT_FORMAT: ASCII art with component placeholders
- CUSTOMIZATION: Replace [PLACEHOLDER] with project-specific content

AVAILABLE_TEMPLATES:

### 1. Home/Landing Page Template
```
┌─────────────────────────────────────────────────────────────────────────────────┐
│  ◉ [APP_NAME] - [TAGLINE]                          [Login] [Sign Up]           │
│─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  ┌─────────────────────────────────────────────────────────────────────────┐     │
│  │                                                                         │     │
│  │                    🚀 [HERO_HEADLINE]                                  │     │
│  │                                                                         │     │
│  │          [HERO_SUBHEADLINE]                                             │     │
│  │                                                                         │     │
│  │                    [PRIMARY_CTA]    [SECONDARY_CTA]                     │     │
│  │                                                                         │     │
│  └─────────────────────────────────────────────────────────────────────────┘     │
│                                                                                 │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐              │
│  │ [FEATURE_1] │  │ [FEATURE_2] │  │ [FEATURE_3] │  │ [FEATURE_4] │              │
│  │             │  │             │  │             │  │             │              │
│  │ [DESC_1]    │  │ [DESC_2]    │  │ [DESC_3]    │  │ [DESC_4]    │              │
│  └─────────────┘  └─────────────┘  └─────────────┘  └─────────────┘              │
│                                                                                 │
│  ┌─────────────────────────────────────────────────────────────────────────┐     │
│  │                          📊 [SOCIAL_PROOF_SECTION]                      │     │
│  │─────────────────────────────────────────────────────────────────────────┤     │
│  │ • [ACTIVITY_1]                                                          │     │
│  │ • [ACTIVITY_2]                                                          │     │
│  │ • [ACTIVITY_3]                                                          │     │
│  └─────────────────────────────────────────────────────────────────────────┘     │
│                                                                                 │
│  ┌─────────────────────── Footer ───────────────────────┐                      │
│  │ [LINK_1] [LINK_2] [LINK_3] [LINK_4] [© YEAR]         │                      │
│  └───────────────────────────────────────────────────────┘                      │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### 2. Dashboard Template
```
┌──────────────────────────────────────────────────────────────────────────────┐
│  ◉ [APP_NAME] Dashboard                             Search [⌕ ............]   │
│──────────────────────────────────────────────────────────────────────────────│
│  ☰ MENU                                                                      │
│  • [NAV_ITEM_1]                                                              │
│  • [NAV_ITEM_2] (active)                                                     │
│  • [NAV_ITEM_3]                                                              │
│  • [NAV_ITEM_4]                                                              │
│                                                                              │
│  ┌───────────── [KPI_1] ─────────────┐  ┌──────────── [KPI_2] ─────────────┐  │
│  │   [KPI_VALUE_1]                   │  │   [KPI_VALUE_2]                   │  │
│  │   [KPI_LABEL_1]                   │  │   [KPI_LABEL_2]                   │  │
│  └───────────────────────────────────┘  └───────────────────────────────────┘  │
│                                                                              │
│  ┌───────────────────── [CHART_TITLE] ──────────────────────┐                │
│  │                                                                          │  │
│  │     █                                                                   │  │
│  │    ██    ██      ███     ██    ████   ███                               │  │
│  │   ████  ████    █████   ███   █████  █████                             │  │
│  │  █████ ██████  ███████ █████ ██████ ███████                            │  │
│  │                                                                          │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                                                              │
│  ┌──────────────────────────── [LIST_TITLE] ────────────────────────────────┐ │
│  │ ID    Title                         Owner        Status      ETA        │ │
│  │────── ───────────────────────────── ──────────── ──────────  ────────── │ │
│  │ [ID1] [TITLE1]                      [OWNER1]     [STATUS1]   [ETA1]     │ │
│  │ [ID2] [TITLE2]                      [OWNER2]     [STATUS2]   [ETA2]     │ │
│  │ [ID3] [TITLE3]                      [OWNER3]     [STATUS3]   [ETA3]     │ │
│  └─────────────────────────────────────────────────────────────────────────┘ │
│                                                                              │
│                                                            [ + [ADD_BUTTON] ] │
└──────────────────────────────────────────────────────────────────────────────┘
```

### 3. Authentication Template
```
┌──────────────────────────────────────────────────────────────────────────────┐
│  ◉ [APP_NAME] - [PAGE_TITLE]                                                 │
│──────────────────────────────────────────────────────────────────────────────│
│                                                                              │
│                                                                              │
│                                                                              │
│  ┌─────────────────────────────────────────────────────────────────────────┐  │
│  │                          🔐 [FORM_TITLE]                              │  │
│  │─────────────────────────────────────────────────────────────────────────┤  │
│  │                                                                         │  │
│  │  Email: [..........................................................]   │  │
│  │                                                                         │  │
│  │  Password: [.......................................................]   │  │
│  │                                                                         │  │
│  │  [☐] Remember me                                                      │  │
│  │                                                                         │  │
│  │                    [PRIMARY_BUTTON]                                     │  │
│  │                                                                         │  │
│  │  ────────────── or ──────────────                                       │  │
│  │                                                                         │  │
│  │  [SOCIAL_LOGIN_1]  [SOCIAL_LOGIN_2]  [SOCIAL_LOGIN_3]                  │  │
│  │                                                                         │  │
│  │  [LINK_TEXT]                                                            │  │
│  │                                                                         │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                                                              │
│                                                                              │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

### 4. Settings/Profile Template
```
┌──────────────────────────────────────────────────────────────────────────────┐
│  ◉ [APP_NAME] - [PAGE_TITLE]                    [Save] [Cancel]              │
│──────────────────────────────────────────────────────────────────────────────│
│  ☰ MENU                                                                      │
│  • [NAV_ITEM_1]                                                              │
│  • [NAV_ITEM_2]                                                              │
│  • [NAV_ITEM_3] (active)                                                     │
│                                                                              │
│  ┌───────────────────── [SECTION_1] ─────────────────────┐                   │
│  │                                                                       │   │
│  │  Profile Picture: [👤] [Change]                                      │   │
│  │                                                                       │   │
│  │  Full Name: [....................................................]   │   │
│  │                                                                       │   │
│  │  Email: [.........................................................]   │   │
│  │                                                                       │   │
│  │  Bio: [...........................................................]   │   │
│  │       [...........................................................]   │   │
│  │                                                                       │   │
│  └───────────────────────────────────────────────────────────────────────┘   │
│                                                                              │
│  ┌───────────────────── [SECTION_2] ─────────────────────┐                   │
│  │                                                                       │   │
│  │  [SETTING_1]: [☐] [✓]                                                │   │
│  │                                                                       │   │
│  │  [SETTING_2]: [...................................................]   │   │
│  │                                                                       │   │
│  │  [SETTING_3]:                                                         │   │
│  │    ○ Option A                                                         │   │
│  │    ○ Option B                                                         │   │
│  │    ● Option C                                                         │   │
│  │                                                                       │   │
│  └───────────────────────────────────────────────────────────────────────┘   │
│                                                                              │
│  ┌───────────────────── [SECTION_3] ─────────────────────┐                   │
│  │  [DANGER_BUTTON]                                                         │   │
│  └───────────────────────────────────────────────────────────────────────┘   │
└──────────────────────────────────────────────────────────────────────────────┘
```

## Dynamic Content Generation Rules

### Variable Replacement System
```
[APP_NAME] → Application name from overview.md
[TAGLINE] → Short description from project goals
[HERO_HEADLINE] → Main value proposition
[PRIMARY_CTA] → Call-to-action button text
[FEATURE_1-4] → Key features from overview.md
[SOCIAL_PROOF_SECTION] → Activity feed or testimonials
```

### Conditional Element Rendering
```
IF authentication_required → Include login/signup in header
IF dashboard_page → Include sidebar navigation
IF mobile_optimized → Adjust layout for mobile screens
IF dark_mode_supported → Include theme toggle
```

### Responsive Design Indicators
```
Desktop (>1024px): Full layout with all elements
Tablet (768-1024px): Condensed layout, stacked elements
Mobile (<768px): Single column, hamburger menu, simplified content
```

## Component Specification Templates

### Button Components
```
Primary Button: [Button Text] - Blue background, white text, rounded corners
Secondary Button: [Button Text] - Outlined border, hover effects
Danger Button: [Button Text] - Red background, confirmation required
```

### Form Components
```
Text Input: [Label]: [....................................................]
Email Input: [Label]: [....................................................]
Password Input: [Label]: [.................................................]
Select Dropdown: [Label]: [▼ Option 1 ▶]
Checkbox: [☐] [Label text]
Radio: ○ [Label] ● [Selected Label]
```

### Navigation Components
```
Header Nav: [Item 1] [Item 2] [Item 3] [Login] [Sign Up]
Sidebar Nav: • [Item 1]
             • [Item 2] (active)
             • [Item 3]
Breadcrumbs: Home > Section > Current Page
```

### Data Display Components
```
Data Table: ID | Title | Status | Actions
Card: ┌─────────────┐
      │ [Title]     │
      │ [Content]   │
      │ [Actions]   │
      └─────────────┘
```

## Page-Specific Customization Rules

### Home Page Rules
- Hero section must be prominent (takes up top 40% of viewport)
- Feature grid should have 3-6 features maximum
- Social proof section should be visible without scrolling
- Footer should contain essential links and copyright

### Dashboard Rules
- Sidebar should be 20-25% of screen width
- KPI cards should be prominently displayed
- Charts should be the largest visual element
- Action buttons should be clearly visible

### Authentication Rules
- Form should be centered both horizontally and vertically
- Social login buttons should be clearly branded
- Password requirements should be visible
- "Forgot password" link should be easily accessible

### Settings Rules
- Sections should be clearly separated
- Save/Cancel buttons should be prominent
- Dangerous actions should require confirmation
- Changes should have clear visual feedback

## ASCII Art Generation Algorithm

### Layout Calculation
1. **Determine canvas size**: Based on content complexity
2. **Calculate component positions**: Grid-based layout system
3. **Apply responsive rules**: Adjust for different screen sizes
4. **Add visual elements**: Borders, dividers, icons, text

### Content Adaptation
1. **Extract key information**: From overview.md and project context
2. **Apply template matching**: Choose appropriate base template
3. **Fill dynamic content**: Replace variables with project-specific data
4. **Add contextual elements**: Include project-specific features and branding

### Quality Assurance
1. **Layout validation**: Ensure all elements fit within canvas
2. **Content completeness**: Verify all required sections are populated
3. **Readability check**: Ensure ASCII art is clear and understandable
4. **Responsive verification**: Confirm mobile and tablet adaptations work

## Integration with Designer Agent

### Template Selection Logic
```javascript
function selectTemplate(pageType, requirements) {
  const templates = {
    landing: 'home',
    dashboard: 'dashboard',
    login: 'auth',
    register: 'auth',
    profile: 'settings',
    settings: 'settings',
    default: 'generic'
  };

  return templates[pageType] || templates.default;
}
```

### Content Population Logic
```javascript
function populateTemplate(template, projectData) {
  return template
    .replace('[APP_NAME]', projectData.name)
    .replace('[HERO_HEADLINE]', projectData.headline)
    .replace('[PRIMARY_CTA]', projectData.primaryAction)
    .replace('[FEATURE_1]', projectData.features[0]);
}
```

### Quality Validation Logic
```javascript
function validateWireframe(wireframe) {
  const checks = [
    hasProperDimensions(wireframe),
    hasRequiredElements(wireframe),
    isReadable(wireframe),
    followsDesignPrinciples(wireframe)
  ];

  return checks.every(check => check.passed);
}
```

This template system provides the designer agent with a comprehensive foundation for generating high-quality, project-specific wireframes that accurately represent the intended user interface and experience.
