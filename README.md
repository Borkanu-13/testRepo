# Stock Analysis Visualization Toolkit

Interactive web application for analyzing stock market data through intuitive visualizations and charts.

## Key Features
- Real-time stock performance comparisons
- Customizable technical indicators
- Interactive chart tooltips
- Stock analysis to identify stocks outperforming market
- Momentum and industry trend visualizations

## Project Structure
my-bubble-chart-app/
├── src/
│ ├── app/ # Next.js application routes
│ │ ├── favicon.ico
│ │ ├── globals.css # Global styles
│ │ ├── layout.tsx # Root layout
│ │ └── page.tsx # Main page component
│ │
│ └── components/
│ ├── charts/ # Visualization components
│ │ ├── BacktestingChart.tsx
│ │ ├── CustomTooltip.tsx # Multiple tooltip variants
│ │ ├── IndustryAnalysisChart.tsx
│ │ ├── MomentumAnalysisChart.tsx
│ │ ├── Plot.tsx # Various chart plotting components
│ │ └── StockViewChart.tsx
│ │
│ └── reusable/ # Shared components
│ ├── FeatureTabs.tsx
│ ├── FilterPanel.tsx
│ ├── Header/Footer.tsx
│ ├── RenderFilterSection.tsx
│ └── useDropdown.ts # Custom hooks


## Technical Stack
- **Frontend**: Next.js 13 (App Router), TypeScript
- **Visualization**: Recharts, Custom SVG components
- **Styling**: CSS Modules/Tailwind (based on globals.css)
- **State Management**: React Context/Hooks

## Setup Instructions

```bash
npm install
npm run dev