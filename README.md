# ESS Lab Notebook

Independent web platform for drafting Environmental Systems and Societies HL internal assessment reports and downloading the final report as a PDF.

## Report structure

- Investigation title, date, word count, class code and DP ESS report format.
- Background information and focused research question.
- Alternate and null hypotheses.
- Environmental strategy and stakeholder-perspective tension.
- Repeatable methodology, variables table, and safety, ethical and environmental issues.
- Editable raw-data and processed-data tables with sample calculations.
- Presentation of processed data, analysis and conclusion.
- Evaluation, weaknesses and limitations, realistic improvements and bibliography.

## Platform features

- Responsive interface based on the Science Lab Notebook design.
- Local draft backup with automatic saving.
- Editable and removable report sections.
- Original-writing controls that block copying and pasting.
- Local PDF generation when no report server is available.
- Optional Node.js, Express and Supabase backend.

## Local use

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Configuration

Copy `.env.example` to `.env` and configure the Supabase values only when cloud drafts and server submissions are required.
