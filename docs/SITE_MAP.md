# Workshop Website Site Map

This diagram shows how visitors navigate your website and how pages are organized.

```
┌─────────────────────────────────────────────────────────────────┐
│                         HOMEPAGE (/)                             │
│                    Splash Layout with Hero                       │
│                                                                   │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐             │
│  │   QGIS      │  │  Tableau    │  │  Resources  │             │
│  │  Workshop   │  │  Workshop   │  │             │             │
│  └──────┬──────┘  └──────┬──────┘  └──────┬──────┘             │
│         │                │                 │                     │
└─────────┼────────────────┼─────────────────┼─────────────────────┘
          │                │                 │
          ▼                ▼                 ▼
          
┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│ /workshops/     │  │ /workshops/     │  │ /resources/     │
│ qgis-feb-2026/  │  │ tableau-feb-26/ │  │                 │
│                 │  │                 │  │ - QGIS links    │
│ • Overview      │  │ • Overview      │  │ - Tableau links │
│ • Software      │  │ • Software      │  │ - Data viz      │
│ • Agenda        │  │ • Agenda        │  │ - Data sources  │
│ • Data Download │  │ • Data Download │  │ - My Tutorials  │
│ • Prerequisites │  │ • Prerequisites │  │                 │
└─────────────────┘  └─────────────────┘  └─────────────────┘

═══════════════════════════════════════════════════════════════════

                    MAIN NAVIGATION BAR
                    
┌──────┬───────────┬───────────┬─────────┬────────┐
│ Home │ Workshops │ Resources │ Archive │ About  │
└──┬───┴─────┬─────┴─────┬─────┴────┬────┴────┬───┘
   │         │           │          │         │
   │         │           │          │         │
   ▼         ▼           ▼          ▼         ▼
   
┌────────┐ ┌──────────┐ ┌──────────┐ ┌────────┐ ┌──────────┐
│        │ │Current   │ │External  │ │Past    │ │Your      │
│Splash  │ │Workshops │ │tutorials │ │workshop│ │background│
│Page    │ │Listing   │ │& guides  │ │materials│ │& contact │
│        │ │          │ │          │ │        │ │          │
└────────┘ └────┬─────┘ └──────────┘ └────────┘ └──────────┘
                │
                ├─ QGIS Workshop (upcoming)
                ├─ Tableau Workshop (upcoming)
                └─ [Future workshops...]

═══════════════════════════════════════════════════════════════════

                     FILE ORGANIZATION

Website Root
│
├── Configuration
│   ├── _config.yml (site settings)
│   ├── Gemfile (dependencies)
│   └── .gitignore
│
├── Navigation
│   └── _data/navigation.yml
│
├── Collections (auto-generate pages)
│   ├── _workshops/
│   │   ├── qgis-february-2026.md
│   │   └── tableau-february-2026.md
│   │
│   └── _tutorials/
│       └── [your-tutorials.md]
│
├── Static Pages
│   └── _pages/
│       ├── workshops.md (listing)
│       ├── resources.md
│       ├── archive.md
│       └── about.md
│
├── Homepage
│   └── index.md (splash layout)
│
└── Assets
    └── assets/images/
        ├── splash-header.jpg
        ├── qgis-thumbnail.jpg
        ├── qgis-header.jpg
        ├── tableau-thumbnail.jpg
        └── tableau-header.jpg

═══════════════════════════════════════════════════════════════════

                   USER JOURNEY EXAMPLES

Example 1: Finding QGIS Workshop
─────────────────────────────────
1. Land on Homepage
2. See QGIS feature box
3. Click "Learn More"
4. Arrive at /workshops/qgis-february-2026/
5. Read overview, agenda
6. Download software
7. Download workshop data from GitHub

Example 2: Looking for Tutorials
─────────────────────────────────
1. Land on Homepage
2. Click "Resources" in nav
3. Browse categorized links
4. Find QGIS tutorial section
5. Click external link to tutorial
   OR
6. Navigate to "My Tutorials" section

Example 3: Checking Past Materials
───────────────────────────────────
1. Click "Archive" in navigation
2. Browse workshops by date
3. Find relevant past workshop
4. Download archived materials
5. Access datasets from GitHub

═══════════════════════════════════════════════════════════════════

                    CONTENT WORKFLOW

┌─────────────────────────────────────────────────────────────────┐
│                    BEFORE WORKSHOP                               │
├─────────────────────────────────────────────────────────────────┤
│                                                                   │
│  1. Create workshop page in _workshops/                          │
│  2. Add to workshops listing page                                │
│  3. Link from homepage feature box                               │
│  4. Create GitHub data repository                                │
│  5. Upload datasets to GitHub repo                               │
│  6. Test all download links                                      │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────┐
│                    AFTER WORKSHOP                                │
├─────────────────────────────────────────────────────────────────┤
│                                                                   │
│  1. Upload final slides/materials to GitHub                      │
│  2. Add entry to archive page                                    │
│  3. Update workshop status to "past"                             │
│  4. Remove from current workshops listing                        │
│  5. Optionally keep on homepage in past section                  │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════

                   EXTERNAL CONNECTIONS

Website → GitHub Data Repositories
        │
        ├─ qgis-workshop-data/
        │  ├── vector-data/
        │  ├── raster-data/
        │  └── exercise-files/
        │
        └─ tableau-workshop-data/
           ├── sales-data.csv
           ├── geographic-data.xlsx
           └── sample-workbooks/

═══════════════════════════════════════════════════════════════════
