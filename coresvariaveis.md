---
name: Patas & Vidas Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#3f4945'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#6f7975'
  outline-variant: '#bec9c4'
  surface-tint: '#176a58'
  primary: '#005645'
  on-primary: '#ffffff'
  primary-container: '#1e6f5c'
  on-primary-container: '#a2efd7'
  inverse-primary: '#89d5be'
  secondary: '#99452c'
  on-secondary: '#ffffff'
  secondary-container: '#ff9475'
  on-secondary-container: '#762b14'
  tertiary: '#00563e'
  on-tertiary: '#ffffff'
  tertiary-container: '#007153'
  on-tertiary-container: '#8df3ca'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a5f2d9'
  primary-fixed-dim: '#89d5be'
  on-primary-fixed: '#002019'
  on-primary-fixed-variant: '#005141'
  secondary-fixed: '#ffdbd1'
  secondary-fixed-dim: '#ffb5a0'
  on-secondary-fixed: '#3b0900'
  on-secondary-fixed-variant: '#7b2e17'
  tertiary-fixed: '#90f6cc'
  tertiary-fixed-dim: '#73d9b1'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#00513b'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.005em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-xl:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-xxs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  container-max: 75rem
---

## Brand & Style

The design system embodies empathy, reliability, and modern stewardship for animal welfare advocacy. It connects independent rescuers, volunteers, and potential adopters through an interface that balances warmth with administrative rigor.

### Personality & Emotional Response
- **Nurturing & Welcoming:** Generous spacing, soft contours, and warm terracotta accents elicit feelings of safety, hope, and compassion.
- **Authoritative & Trustworthy:** Forest greens, crisp typography, and disciplined data presentation instill confidence in donors and institutional partners.
- **Action-Oriented:** High-contrast CTAs and straightforward form flows reduce friction for critical actions such as adoptions, emergency sponsorships, and volunteer registrations.

### Design Aesthetic
The system adopts a **Refined Modern Organic** aesthetic—grounded in human-centric minimalism with tactile softness:
- Subtle, organic color zoning to clearly delineate animal profiles, medical logs, and rescue updates.
- Micro-interactions that emphasize warmth (e.g., gentle scale shifts, soft color transitions).
- Zero abrasive neon accents or sharp, utilitarian corners; every touchpoint reinforces care, accessibility, and dignity for animals and caretakers alike.

## Colors

The palette is derived directly from natural sanctuaries: rich forest flora, warm earth terracotta, and crisp atmospheric neutrals.

### Palette Architecture
- **Primary (`#1E6F5C` — Forest Green):** The cornerstone brand tone. Represents growth, protection, and organizational stability. Used for primary navigation, high-level headers, active state fills, and focal brand moments.
- **Tertiary (`#289672` — Meadow Green):** Lighter companion to the forest green. Applied to positive indicators, success notifications, medical clearance badges, and supportive button variants.
- **Secondary (`#E27D60` — Earth Terracotta):** Represents vitality, affection, and direct rescue interventions. Serves as the primary conversion color for urgent appeals, "Adopt Now" triggers, and donation highlights.
- **Neutral Core (`#1F2937` — Slate Charcoal):** Ensures AAA-grade readability across text hierarchies, borders, and structured content. Replaces harsh true-black with a deep, legible charcoal.
- **Background Layer (`#F8F9FA` — Off-White / Alabaster):** Provides a warm, glare-free canvas that makes animal photography and status badges stand out naturally.

### Accessible Application Rules
- Text rendered on `#1E6F5C` must always use `#FFFFFF`.
- Buttons colored `#E27D60` must use `#FFFFFF` text and maintain a minimum touch area of 44x44px.
- Subtle background tinting (`#F0F7F4` derived from Primary and `#FDF3F0` from Secondary) designates contextual cards, such as critical medical notices or adoption steps.

## Typography

The type system blends the organic, friendly curves of **Plus Jakarta Sans** for titles and headings with the neutral clarity of **Inter** for dense tabular records, rescue case notes, and adoption procedures.

### Font Roles
- **Headlines (Plus Jakarta Sans):** Carries personality through softly sculpted letterforms. Used to establish immediate rapport in story titles, landing pages, and pet showcase banners.
- **Body & Data (Inter):** Ensures legibility in medical logs, application forms, shelter metrics, and volunteer instructions across varied screen resolutions.
- **Labels & Tags (Inter SemiBold):** Applied to vaccination badges, gender tags, breed specifics, and action buttons for quick scanning.

### Responsive Adjustments
- Large hero titles scale down via `-mobile` tokens (`display-lg` drops from 48px to 36px; `headline-xl` drops from 32px to 26px) to avoid awkward breaks on 360px–390px viewports.
- Body sizes remain strictly locked at a minimum 14px for content and 16px for form inputs to prevent automatic browser zoom on mobile platforms.

## Layout & Spacing

The platform uses an 8px base rhythm, anchored to a fluid responsive grid system.

### Grid Blueprint
- **Mobile (< 768px):** 4-column layout with 16px (`gutter-mobile`) outer margins and 16px column gutters. Animal grids collapse to single-column feeds with horizontal swipe cards for urgent rescues.
- **Tablet (768px - 1024px):** 8-column layout with 24px margins and gutters. Adoption cards fit comfortably in a 2-column format.
- **Desktop (> 1024px):** 12-column layout bounded by a maximum content container of 1200px (`container-max`). Supports a 3-column animal showcase or an 8:4 split for rescue logs alongside donor sidebars.

### Spacing Philosophy
- Vertical rhythm follows multiples of 8px (`space-sm`, `space-md`, `space-lg`, `space-xl`).
- Component interiors pair compact vertical padding with roomier horizontal margins (e.g., inputs use `12px 16px`) to produce balanced, accessible tap targets.

## Elevation & Depth

Visual hierarchy uses warm, ambient diffusion over high-contrast shadows. Depth feels soft, approachable, and tactile rather than clinical or digital.

### Layering Architecture
- **Layer 0 (Canvas):** Pure `#F8F9FA` off-white base.
- **Layer 1 (Card Base):** `#FFFFFF` with an ambient shadow: `0 2px 8px -2px rgba(31, 41, 55, 0.05)` and a hairline border of `1px solid rgba(31, 41, 55, 0.08)`.
- **Layer 2 (Floating/Hover):** Applied when an animal profile card or interactive module is hovered: `0 8px 24px -4px rgba(30, 111, 92, 0.12)`, paired with a `translateY(-2px)` transition.
- **Layer 3 (Modals & Drawers):** For adoption submission overlays and pet filter bottom sheets: `0 16px 36px -6px rgba(31, 41, 55, 0.18)` over a blurred backdrop (`rgba(31, 41, 55, 0.4)` with `backdrop-filter: blur(4px)`).

## Shapes

The design system employs a **Rounded** shape model (`roundedness: 2`), balancing organic warmth with structural organization.

### Application Specs
- **Cards & Primary Modules:** 16px (`rounded-lg` / `1rem`). Softens photography frames and dashboard modules without sacrificing grid density.
- **Buttons, Text Inputs & Dropdowns:** 8px (`rounded` / `0.5rem`). Creates tidy form fields that still feel approachable.
- **Tags, Badges & Pills:** Fully circular radii (`9999px`) to frame pet metadata (age, species, health status) into friendly, tactile capsules.
- **Media Displays:** Animal avatars and profile hero images utilize 16px outer corners or smooth circular cutouts to convey gentleness and care.

## Components

### Buttons
- **Primary (`#1E6F5C`):** White text, 8px border-radius, 12px 24px padding (`label-lg`), minimum height 48px. Used for main transactional flows like "Iniciar Adoção" and "Confirmar Doação". Hover transitions smoothly to `#175647`.
- **Secondary / Urgent (`#E27D60`):** White text, 8px border-radius, 12px 24px padding. Reserved for immediate rescue appeals, monthly sponsor pledges, and triage alerts. Hover shifts to `#D66D50`.
- **Ghost / Outlined:** Transparent fill with a 1.5px border in `#1E6F5C`, colored text in `#1E6F5C`. Hover introduces a 10% tint background (`#F0F7F4`).

### Chips & Badges
- **Status Pills:** Fully rounded (9999px) with 4px 12px padding (`label-md`). 
  - *Castrado/Vacinado (Positive):* Background `#EAF5F1`, text `#1E6F5C`.
  - *Tratamento Urgente (Urgent):* Background `#FDF0EC`, text `#D05C3D`.
  - *Porte/Idade (Neutral):* Background `#F3F4F6`, text `#1F2937`.
- **Interactive Filter Chips:** 8px radius, border `1px solid rgba(31, 41, 55, 0.12)`, background `#FFFFFF`. Active state uses `#1E6F5C` fill with white text.

### Inputs & Form Fields
- **Base Style:** 48px height, 8px border radius, `#FFFFFF` background, border `1.5px solid #E5E7EB`, text `#1F2937` in `body-lg`.
- **Focus State:** Border shifts to `#1E6F5C` with a matching focus ring: `0 0 0 3px rgba(30, 111, 92, 0.2)`.
- **Floating Labels:** Rendered in `label-md` with `#4B5563`. Helper text sits 4px below the input container.

### Checkboxes & Radio Buttons
- **Checkboxes:** 20x20px, 4px border-radius, border `1.5px solid #9CA3AF`. Active state fills with `#1E6F5C` and displays a crisp white check icon.
- **Radio Options:** 20x20px, circular. Active state displays a 6px solid `#1E6F5C` central dot with an `#EAF5F1` surrounding aura.

### Cards (Animal Profile & Rescue Logs)
- **Structure:** 16px corner radius, `#FFFFFF` background, fine border (`1px solid #E5E7EB`), soft ambient shadow.
- **Image Treatment:** Aspect ratio 4:3 (mobile) or 16:10 (desktop) with top corners pinned to 16px radius and overflow hidden.
- **Content Interior:** 16px padding featuring species tag, name (`headline-md`), location pin with city, and key personality tags (e.g., "Dócil", "Sociável"). Bottom section anchors a full-width or two-column CTA row.

### Specialized Pet Platform Components
- **Medical Record Tracker:** Accordion with a vertical timeline on the left, `#289672` checkpoint dots, and collapsible cards containing vet timestamps, vaccine tags, and prescription downloads.
- **Urgency Banner:** Terracotta accent card (`#FDF3F0`) with a 4px solid left border in `#E27D60`, pairing high-priority recovery case updates with a quick-donation progress bar.