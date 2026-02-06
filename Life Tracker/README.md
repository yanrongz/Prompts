# Life Tracker

*"Build your own life tracker to help you record and organize your life!"*

## Inspiration
This idea came from my personal need for a **practical**, **all-in-one** tool to track different aspects of my life. Instead of keeping a to-do list open on my iPhone while also managing multiple Notes for health tracking and capturing quick-thoughts, I wanted a single place where everything could live together in a more structured and intentional way.

## What's included
The original prompt includes following sections:
- To-do lists
- Body metrics tracking
- Workout logs
- Media tracking
- Journaling

You are free to **customize the prompt based on your own needs**. For example:
- Add a **Diet** section to log daily meals
- Add a **Map** section to record travel experiences

If you don’t have additional requirements, you can simply download and use the provided `.html` file directly.

## Data storage & Backup
Please note that this is an **offline document**. All records are stored **locally in your browser**. To avoid data loss, make sure to **export your data regularly**. You can later restore your previous records by using the **import data** feature.

## Prompt
**Role**  
You are a senior full-stack web developer and high-end UI/UX designer.  

**Objective**  
Build a minimalist and **responsive** personal management web application. The visual style should use a gray–pink color palette (dark/light gray combined with dark/light pink) to create a professional, calming interface that encourages long-term daily use.
All design decisions must follow ergonomic and **human-centered** design principles.

**Core Technical Requirements**
1. **Data Persistence & Portability**:
- No external database; all data must persist in `localStorage`.  
- Feature a prominent **"Backup Reminder"** to encourage users to save data.
- Implement Export as `JSON` and Upload/Import `.json` functionality to ensure zero data loss and cross-device continuity.
2. **Layout & Navigation**:
- Left-side navigation bar for switching between modules.
- Fully **responsive design** (Mobile/Tablet/Desktop) using CSS Flex/Grid.
3. **The Modular Calendar System**:
- Each module except **Body** contains a minimalist, horizontal scroll-style calendar at the top.
- The calendar should be small and discrete (e.g., a single row of dates).
- Clicking a date shows only the records for that specific day.
- Circular date buttons become darker/filled if data exists for that day.
4. **Module Content & Sequence**:
- **Tasks**: Daily to-do list. History must show specific task text/status, not just completion percentages.
- **Body**: Table-style log for Height, Weight, Waist, Hip, Thigh, and Calf measurements. Data accumulates row-by-row; entries must be editable.
- **Sports**: Grid-style cards per entry (not full-width). Records: Project, duration/reps, and reflections.
- **Media**: Fields for Type (Book, Movie, Podcast, News, Video, Others), Title, and a 5-star rating system (empty stars).
  1. Special fields: Multi-line "Excerpts" and "Reflections" (each a distinct list).
  2. For Podcast, News, Video, and Others: Add a "Links" field.
  3. Sorting: By Type.
5. **Notes**: Post-it style entries for fragments of inspiration. No title field. History grouped by Day.


**UI/UX Design Guidelines**
- **Aesthetics**: Senior-level minimalism. No childish icons. Elegant typography. High-contrast but soft grayscale.
- **Interaction**: History sections should be "Collapsible" (hidden by default, expandable by user).
- **Refinement**: Everything must be editable. Buttons should be sleek and appropriately sized (not bulky).

**Self-Review Requirement**  
Before returning the final result:
- Carefully verify that all requirements above are fully satisfied
- Ensure the final output contains no runtime errors

## Final Thoughts
I hope this idea helps you better organize your life amd make day-to-day tracking more enjoyable.😊
