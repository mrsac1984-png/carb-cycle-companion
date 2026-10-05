# ShredCycle branding and resources plan

Status: approved direction, do not rebuild APK yet.

## Branding
- Selected app name: **ShredCycle**
- Selected logo direction: the ShredCycle mockup created in the current ChatGPT conversation
- Visual direction: navy + teal, circular cycling arrows around a strong "S"
- Tagline direction: **Train | Eat | Cycle | Progress**
- Preserve the current working top navigation and Samsung Galaxy S25 Ultra compatibility fixes.

## Resource-library upgrade before next APK
Add a **Guides / Resources** area without crowding the five-button top navigation.

Recommended structure:
1. ShredCycle Quick Start
2. Carb Cycling Cheat Sheet
3. HIIT Guide
4. Workout Strategy
5. Nutrition / Meal Strategy
6. Full 4-Week Plan
7. Additional uploaded health/meal-plan PDFs selected by the user

For PDFs supplied by the user:
- package copies inside the APK for offline personal use where practical;
- show them as cards in an in-app library;
- open them in a full-screen viewer;
- retain the original PDF files unchanged;
- optionally add a short native-app summary / cheat-sheet card above each PDF.

Do not rebuild until the final resource list is confirmed.


## Confirmed V Shred source pack — 5 Oct 2026

User supplied these three source PDFs for the next ShredCycle build:
- `vshred-carb-cycling-cheat-sheet-1.pdf` — 1-page Carb Cycling Cheat Sheet.
- `Carb_Cycling_Guide_v1-1-1.pdf` — 3-page Carb Cycling Guide.
- `Fat-Loss-Blueprint-1-1.pdf` — 12-page Fat Loss Blueprint.

Official HIIT source:
- https://vshred.com/blog/vince-fle-style-hiit/

Official online references located for resilience/backup:
- Carb Cycling Cheat Sheet: https://vshred.com/blog/wp-content/uploads/2023/03/vshred-carb-cycling-cheat-sheet.pdf
- Carb Cycling Guide landing page: https://vshred.com/blog/carb-cycling-guide/
- Fat Loss Blueprint: https://vshred.com/blog/wp-content/uploads/2024/04/Fat-Loss-Blueprint-V2.pdf

### Proposed in-app Guides section
Place under Plan -> Guides / Resources:
1. ShredCycle Quick Start
2. Carb Cycling Cheat Sheet — original PDF + native summary card
3. Carb Cycling Guide — original PDF + native summary card
4. Fat Loss Blueprint — original PDF + native summary card
5. FLE-Style HIIT — native workout card + link to the official V Shred article/video
6. ShredCycle 4-Week Plan — current meal/workout calendar
7. My Documents — optional other user-supplied PDFs, separated from the core ShredCycle plan

### Default carb-cycle schedule decision
For the ShredCycle fat-loss preset, use:
- Monday: Low
- Tuesday: Medium
- Wednesday: High
- Thursday: Low
- Friday: Medium
- Saturday: High
- Sunday: Low

Reason: this is the sample week shown in both the Carb Cycling Cheat Sheet (with Sunday optionally High for muscle gain/maintenance) and the Fat Loss Blueprint. The separate Carb Cycling Guide gives an alternate 3-low / 2-moderate / 2-high sequence (Low, Moderate, High, Low, Low, Moderate, High), so retain that as an optional alternate preset rather than silently mixing the two source patterns.

### FLE-style HIIT card
Use the official V Shred FLE-style HIIT guidance:
- 2–4 min low-intensity warm-up
- 20 sec high intensity
- 30 sec low-intensity active recovery
- Beginner: 6–8 rounds
- Intermediate: 10–12 rounds
- Advanced: 13–18 rounds
- Total session target on source page: about 16–20 minutes
- Allow any safe cardio machine or equipment-free movement
- Include an "Open official V Shred workout/video" button

Do not rebuild APK until the Guides screen and branding assets are finalized.


## ShredCycle v2 build verification
- Android 16 / Galaxy S25 Ultra candidate build generated successfully.
- Signing key is now generated once and retained by the GitHub Actions signing cache for future in-place ShredCycle updates.
- The next verification build is intentionally triggered to confirm that signing cache is restored.
