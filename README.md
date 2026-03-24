# Freight Cost & Risk Analytics Dashboard

Executive Power BI dashboard designed to provide freight cost visibility, analyze risk concentration, and assess benchmark savings in a logistics context.

## Business Impact
- Identified R$ 274k in benchmark savings opportunity by simulating a 0.10% Ad Valorem target cap across the analyzed logistics base.
- Mapped operational risk hotspots, revealing that Petrolina/PE operates with a 19.5% issue rate, the highest among main freight-cost destinations.
- Strategic Pivot: Shifted the analytical focus from static freight reporting to cost concentration, issue concentration, and actionable savings context.

## Technical Architecture
- Tool: Power BI
- Modeling: Star-schema-inspired model with `stg_Shipments` as the fact table and `dCarrier`, `dVehicle`, and `dOccurrence` as dimensions
- Measures: DAX-based KPI logic for freight cost, Ad Valorem share, issue rate, and benchmark savings
- Data Logic: Measure-layer corrections applied to standardize Ad Valorem and freight cost calculations for analysis
- Design: Executive dark mode, brutalist UI, low cognitive load
- Interactivity: Cross-filtering enabled for root-cause analysis by Carrier and Destination

## How to View
Download the `.pbix` file and open it in Power BI Desktop to explore the dashboard, data model, and DAX measures.
