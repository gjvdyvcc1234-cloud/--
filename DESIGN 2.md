---
name: Khao Ngu Explorer
colors:
  surface: '#f3faff'
  surface-dim: '#c3deec'
  surface-bright: '#f3faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e6f6ff'
  surface-container: '#d8f2ff'
  surface-container-high: '#d1ecfa'
  surface-container-highest: '#cbe7f5'
  on-surface: '#021f29'
  on-surface-variant: '#40493d'
  inverse-surface: '#19343e'
  inverse-on-surface: '#dff4ff'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#4a626d'
  on-secondary: '#ffffff'
  secondary-container: '#cde6f4'
  on-secondary-container: '#506873'
  tertiary: '#7a4a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#9c6000'
  on-tertiary-container: '#ffeee0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#cde6f4'
  secondary-fixed-dim: '#b1cad7'
  on-secondary-fixed: '#051e28'
  on-secondary-fixed-variant: '#334a55'
  tertiary-fixed: '#ffddba'
  tertiary-fixed-dim: '#ffb865'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#663d00'
  background: '#f3faff'
  on-background: '#021f29'
  surface-variant: '#cbe7f5'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system powers an edutainment experience set in Ratchaburi's Khao Ngu Stone Park. It merges outdoor natural exploration, local geological history, and light gamification into an inviting, family-centered companion app. 

### Brand Character & Voice
- **Tone:** Cheerful, curious, nurturing, and adventurous without feeling chaotic.
- **Target Audience:** School-age children, families on weekend park getaways, and eco-tourists exploring the historical karst landscape.
- **Emotional Response:** Comfort, delight upon discovery, effortless orientation, and safety. Every screen encourages outdoor curiosity and makes learning feel like a treasure hunt.

### Visual Style: Warm Tactile Naturalism
The system draws from modern rounded mobile UX combined with tactile, nature-inspired warmth:
- Generous, squishy-soft radius scales (`16px` to `24px` on interactive containers) evoking friendly pebbles and soft river stones.
- Clear structural contrasts derived from Ratchaburi's landscape: limestone grey bedrock, moss green vegetation, and bright morning sunbeams.
- Tactile affordances that reward taps with reassuring micro-depth, soft colored outer borders, and pillowy button surfaces rather than aggressive skeuomorphism or clinical flat minimalism.

## Colors

The palette balances lush nature tones with stone greys and cheerful amber reward highlights.

### Functional Role Allocations

- **Primary (`#2E7D32` Deep Moss Green) & Light Tint (`#4CAF50` / `#E8F5E9`):**
  - Anchor elements, primary interactive buttons ("เริ่มเกม", "เข้าสู่ระบบ"), completed milestones, and active navigation indicators.
  - Soft background wash (`#F1F8E9` / `#E8F5E9`) provides gentle card containers and highlighted callout banners.

- **Secondary (`#78909C` Limestone Blue-Grey):**
  - Geological context, structural borders, secondary navigation pills, inactive map waypoints, and tertiary metadata.
  - Paired with `#ECEFF1` and `#F5F7F8` for subtle surface elevation and card divisions that mimic polished limestone slabs.

- **Tertiary (`#FFA000` Amber Sunlight & `#FFF8E1` Sun Glow):**
  - Exploration rewards, mission stars, gamified level progress badges, hint containers, and joyful discovery cues.

- **Neutrals & Surfaces:**
  - **Base Canvas (`#FCFDFB`):** A soft, organic warm ivory tint instead of stark digital white, cutting eye strain during outdoor tablet and phone use.
  - **Text High Contrast (`#1E2E21`):** Deep botanical charcoal providing strict AAA readability against light mint and cream backgrounds.
  - **Text Muted (`#546E7A`):** Readable, warm slate tone for metadata, author credits, and supporting descriptions.

## Typography

Typography prioritizes high legibility and approachable, friendly geometry suited to bilingual Thai-Latin educational applications. 

### Font Selection & Pairing
- **Primary Typeface:** **Plus Jakarta Sans** for Latin script, paired natively with Thai rounded grotesque typefaces (e.g., Sukhumvit Set / Sarabun / Kanit soft weight). 
- Plus Jakarta Sans provides generous counter spaces, humanist terminals, and open apertures that prevent visual fatigue during outdoor field trips.

### Hierarchy & Legibility Rules
- **Display & Headlines:** Used for level clearings ("ทายครบ 11 แหล่ง!"), welcome hooks, and screen headers. Never set tighter than 1.2x line-height to ensure Thai tone marks (วรรณยุกต์) do not clip.
- **Body Text:** Kept between 14px and 16px with comfortable 1.5x leading for accessible reading on compact handheld screens.
- **Labels & Badges:** Slightly weighted (`600` SemiBold) for rapid scanning on interactive map pins, quiz options, and inventory slots.

## Layout & Spacing

The layout is built around a predictable mobile-first responsive grid that keeps touch targets large and accessible for children and adult chaperones alike.

### Grid & Canvas Structure
- **Mobile Handheld (360px - 480px):** 4-column layout with `16px` (`margin`) outer margins and `16px` (`gutter`) column gaps. Essential bottom sheet actions and primary floating buttons must stay within standard reach zones (bottom 40% of canvas).
- **Tablet / Large Screen (600px - 1024px):** 8-column layout with `24px` margins. Dashboard elements collapse into balanced 2-column cards (Map preview left, Daily quests & Badges right).
- **Desktop / Kiosk Viewport:** Constrained central container at `480px` max-width for mobile app simulation, or extended to `1120px` for tourist kiosk screens.

### Spatial Rhythm
- **Internal Component Padding:** `12px` to `16px` (`space-sm` to `space-md`) within cards, providing a breathing cushion around mascot portraits and quiz thumbnails.
- **Stack Spacing:** Modules, game blocks, and section cards separate with `16px` (`space-md`) vertical margins to prevent accidental multi-touch triggers.

## Elevation & Depth

Visual depth is achieved through gentle, sunlit elevation and tinted natural shadows rather than cold charcoal drop shadows.

### Elevation Levels

- **Ground Level (Canvas):** Flat warm tint (`#FCFDFB`). Background landscape illustrations and subtle geological contour vector lines live here.
- **Surface Level 1 (Cards & Modules):** Pure white (`#FFFFFF`) or tinted mint-ivory (`#F7FAF5`) surfaces framed with a very soft `1px` stroke in `#E0E8E1` or `#ECEFF1`. Elevated with an ambient shadow: `0 4px 12px -2px rgba(46, 125, 50, 0.06), 0 2px 4px -1px rgba(84, 110, 122, 0.04)`.
- **Surface Level 2 (Interactive Floating Actions, Bottom Modals, Mascots):** Elevated with an inviting lift: `0 10px 25px -4px rgba(46, 125, 50, 0.12), 0 4px 8px -2px rgba(0, 0, 0, 0.04)`.
- **Gamified Badges & Active Quiz Cards:** Utilize a distinct `2px` lower lip offset (tactile pressable button depth: `box-shadow: 0 4px 0px 0px #1B5E20`) that compresses down (`translateY(2px)`) on active touch, giving a tactile toy-like press feedback.

## Shapes

The design adopts a generous, pebble-rounded aesthetic (`roundedness: 2`) that reinforces the mascot's gentle contours and natural river stones.

### Corner Radii Guidelines
- **Base Components (Inputs, Quiz Buttons, Small Pills):** `0.5rem` to `0.75rem` (`8px` - `12px`).
- **Feature Cards & Content Blocks:** `1rem` (`16px`) for cohesive enclosure.
- **Floating Containers, Mascot Badges, & Modal Sheets:** `1.5rem` (`24px`) along top edges.
- **Filter Tags & Navigation Indicators:** Fully pill-shaped (`rounded-full` / `9999px`) to maintain comfortable fingertip targets.

## Components

### Buttons
- **Primary Buttons ("เข้าสู่ระบบ", "เริ่มเกม", "ถัดไป"):** Rich moss green background (`#2E7D32`), white bold text, minimum height `52px` for child thumb reach. Features a tactile inner soft contrast or bottom border accent (`#1B5E20`) that compresses on `:active`.
- **Secondary Buttons ("สร้างบัญชีนักสำรวจ", "ก่อนหน้า"):** Crisp white container, `1.5px` border in `#CFD8DC`, text in `#37474F`.
- **Icon / Action Roundels:** `48px x 48px` circular or squircle containers with light sage tint (`#E8F5E9`) and emerald icon accents.

### Cards & Learning Modules
- **Explorer Quest Card:** White base with rounded corners (`16px`), `1px` subtle limestone border (`#ECEFF1`). Includes a landscape thumbnail with rounded corners (`12px`), title hierarchy, completion indicator (`0/5`), and chevron indicator.
- **Quiz Choice Cards:** Full-width options (`56px` height) with choice markers (`A`, `B`, `C`, `D`) set inside a round badge. Incorrect selection states trigger soft coral tinting (`#FFEBEE`, border `#E57373`); correct choices pulse vibrant leaf green (`#E8F5E9`, border `#4CAF50`).

### Gamification & Badges
- **Progress Trackers:** Rounded progress tracks (`height: 12px`, radius `999px`) in `#ECEFF1` with a vibrant moss-to-amber filled gradient progress fill.
- **Inventory & Discovery Slots:** Square rounded tiles (`72px x 72px`) featuring limestone outlines. Locked states display an understated padlock icon over a soft grey wash (`#F5F7F8`); unlocked relics display full-color illustrated assets with an amber glow badge.

### Input Fields
- **Search & Authentication Fields:** Minimum height `50px`, background `#FFFFFF`, border `1.5px` in `#CFD8DC`, placeholder text in `#90A4AE`. Focus states smoothly transition to a `#4CAF50` halo ring (`0 0 0 3px rgba(76, 175, 80, 0.2)`).

### Bottom Navigation & App Bar
- **App Bar:** Clear titles flanked by simple rounded navigation backs and a compact circular profile/level counter ("Lv. 2").
- **Bottom Navigation Bar:** Floating dock or anchored pill container in off-white (`#FFFFFF`) with 4 distinct icons: สำรวจ (Explore/Walk), ความรู้ (Learn), เกม (Play/Quest), and สมบัติ (Collect/Trophy). Active items display an expanded pill tag with moss green fill and white text.