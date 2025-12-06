<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SimpleMotion-99-Templates/.github/main/profile/sm-assets/sm-white-banner.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SimpleMotion-99-Templates/.github/main/profile/sm-assets/sm-black-banner.svg">
    <img alt="SimpleMotion" src="https://raw.githubusercontent.com/SimpleMotion-99-Templates/.github/main/profile/sm-assets/sm-black-banner.svg" width="800">
  </picture>
</p>

<p align="center">
  <em>Engineered for Architecture, Entertainment and Industry.</em>
</p>

## Directory Structure

SimpleMotion uses a hierarchical numbering system to organize business units, departments, and projects.

### Numbering Convention

| Range | Category | Description |
|-------|----------|-------------|
| 00-09 | **Core** | Business units and headquarters |
| 10-19 | **Operations** | Administration and employee resources |
| 20-39 | **Production** | Active project workspaces |
| 40-49 | **Portfolio** | Portfolio, process, and product management |
| 50-59 | **Engineering** | Engineering disciplines |
| 90-99 | **Executive** | Leadership and templates |

### Organization Hierarchy

```
00-SimpleMotion/              # Global headquarters
├── 01-SM-Global              # Global operations
├── 02-SM-Architecture        # Architecture business unit
├── 03-SM-Digital             # Digital services and solutions
├── 04-SM-Entertainment       # Entertainment business unit
├── 05-SM-Industry            # Industry business unit
├── 06-SM-Manufacturing       # Manufacturing operations
└── 07-SM-Projects            # Cross-functional projects

10-Operations/                # Operations and administration
└── 11-Employees              # Employee resources and HR

20-Production/                # Production management
├── 21-Projects               # Production projects
├── 22-Projects               # ...
└── ...39-Projects            # Project workspaces

40-Portfolio/                 # Portfolio management
├── 41-Process                # Process management
└── 42-Products               # Product management

50-Engineering/               # Engineering departments
├── 51-Mechanical             # Mechanical engineering
├── 52-Electrical             # Electrical engineering
├── 53-Electronics            # Electronics engineering
└── 54-Software               # Software engineering

90-Executive/                 # Executive and leadership
├── 91-Employees              # Executive staff
└── 99-Templates              # Organization templates
```

### Configuration Files

Each directory contains standard configuration:

- `.claude/` - Claude Code AI assistant settings
- `.simplemotion/` - SimpleMotion framework configuration
- `.github/` - GitHub organization profile (public)
- `.github-private/` - GitHub organization profile (private)

### Project & Employee Naming

Projects and employees follow a structured naming pattern:

```
YYMMNN-XX-YY-Name
│││││  │  │  └── Descriptive name
││││└──┴──┴───── Type and category codes
└┴┴┴──────────── Date/sequence identifier
```

Examples:
- `220126-SP-22-Simple-Surface` - Project from 2022-01
- `110001-SW-00-Greg-Gowans` - Employee workspace
