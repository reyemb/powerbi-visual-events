# Power BI Events Visual

A custom Power BI visual for real-time machine status monitoring. Display time-based events with color-coded status indicators across multiple devices on a timeline.

## Features

- **Timeline Visualization**: Display events over configurable time intervals (e.g., 24-hour day)
- **Color-Coded Events**: Customizable colors via JSON configuration
- **Cross-filtering**: Interactive filtering with other Power BI visuals
- **Multi-language Support**: English, German, French, Spanish, Italian
- **Flexible Formatting**: Extensive options for margins, axis labels, event boxes, and more

## Demo

See the visual in action: [`demo/demo.mp4`](demo/demo.mp4)

## Data Fields

| Field | Description |
|-------|-------------|
| Device | Machine/device identifier (Y-axis grouping) |
| Time | Event timestamp |
| Events | Event type/status |
| Color | Optional color override |
| Tooltips | Additional information on hover |

## Installation

1. Download the `.pbiviz` file from [Releases](https://github.com/reyemb/powerbi-visual-events/releases)
2. In Power BI Desktop, go to **Visualizations** pane > **...** > **Import from file**
3. Select the downloaded `.pbiviz` file

## Development

### Prerequisites

- Node.js
- Power BI visuals tools: `npm install -g powerbi-visuals-tools`

### Setup

```bash
npm install
npm run start
```

Then use the Developer Visual in Power BI Service to test your changes.

## License

GNU GPLv3

## Contributing

Contributions welcome via pull requests or translations. Open an issue for feature requests or bugs.

