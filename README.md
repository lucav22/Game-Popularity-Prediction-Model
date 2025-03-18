# Game Popularity Prediction Model

Presented by: Gianluca Villegas [gv2114@nyu.edu] and Kevin Zhu [yz4189@nyu.edu]

A sophisticated machine learning framework for analyzing and predicting video game success through comprehensive player engagement analysis. This project combines statistical analysis, machine learning, and data visualization to understand what makes games successful in the long term.

## Project Overview

This system analyzes historical player count data along with multiple derived metrics to forecast game success patterns. The analysis encompasses:

- Player retention patterns across different time scales
- Weekly engagement cycles and their stability
- Recovery events after player count declines
- Comparative analysis between successful and declining games
- Advanced visualization of population trends and health metrics

## Key Features

### Data Processing and Analysis
- Sophisticated preprocessing of player count data
- Outlier detection and handling
- Temporal pattern recognition
- Weekly cycle analysis

### Health Metrics Calculation
- Player retention tracking
- Population stability measurements
- Trend analysis across multiple timeframes
- Recovery event detection

### Predictive Modeling
- Feature engineering from temporal data
- Machine learning classification of game trajectories
- Model performance analysis and interpretation
- Feature importance ranking

### Visualization Tools
- Interactive trend visualizations
- Comparative analysis plots
- Health metric dashboards
- Model performance visualizations

## Project Structure
```
├── data/                   # Game player count datasets
│   ├── amongus/           # Among Us player data
│   ├── artifact/          # Artifact player data
│   ├── atlas/            # Atlas player data
│   ├── babylonsfall/     # Babylon's Fall player data
│   ├── battleborn/       # Battleborn player data
│   ├── battlefield2042/  # Battlefield 2042 player data
│   ├── csgo/             # CS:GO player data
│   ├── culling/          # The Culling player data
│   ├── cyberpunk/        # Cyberpunk 2077 player data
│   ├── deeprock/         # Deep Rock Galactic player data
│   ├── defiance/         # Defiance player data
│   ├── destiny2/         # Destiny 2 player data
│   ├── dota/             # Dota 2 player data
│   ├── factorio/         # Factorio player data
│   ├── fallout76/        # Fallout 76 player data
│   ├── firefall/         # Firefall player data
│   ├── h1z1/             # H1Z1 player data
│   ├── haloinfinite/     # Halo Infinite player data
│   ├── newworld/         # New World player data
│   ├── nomans/           # No Man's Sky player data
│   ├── outriders/        # Outriders player data
│   ├── pathofexile/      # Path of Exile player data
│   ├── rainbowsix/       # Rainbow Six Siege player data
│   ├── rust/             # Rust player data
│   ├── splitgate/        # Splitgate player data
│   ├── stardew/          # Stardew Valley player data
│   ├── terraria/         # Terraria player data
│   ├── tf2/              # Team Fortress 2 player data
│   ├── warframe/         # Warframe player data
│   └── wildstar/         # Wildstar player data
└── notebooks/            # Analysis and modeling notebooks
```

## Setup

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter notebooks: `jupyter notebook`

## Methodology

Our approach combines statistical analysis with machine learning techniques to understand game success patterns. The system:

1. Processes historical player count data through sophisticated cleaning and normalization
2. Extracts meaningful features including retention metrics, stability indicators, and temporal patterns
3. Applies machine learning to classify and predict game trajectories
4. Provides detailed visualizations and analysis of results

## Data Sources

This project utilizes historical player count data from SteamDB, a comprehensive database that tracks various metrics for games on the Steam platform.

### Analyzed Games

#### Successful Games
- Counter-Strike: Global Offensive (CSGO)
- Rainbow Six Siege
- Stardew Valley
- Destiny 2
- Team Fortress 2
- Deep Rock Galactic
- Warframe
- Path of Exile
- Terraria
- Dota 2
- Rust
- Factorio

#### Declining Games
- Atlas
- Artifact
- Babylon's Fall
- Battleborn
- The Culling
- Defiance
- Firefall
- H1Z1
- New World
- Outriders
- Splitgate
- Wildstar

### Data Collection Details

The data structure includes:
- Daily concurrent player counts
- Historical peaks and valleys
- Temporal patterns including weekly cycles
- Long-term trend information

Our preprocessing accounts for:
- Missing data points
- Outliers and anomalies
- Weekly and seasonal patterns
- Special events that might affect player counts

### Data Quality Considerations

Important factors considered in our analysis:
1. Data completeness varies between games
2. Concurrent players represent only Steam players, not other platforms
3. Free weekends and sales can create temporary spikes
4. Server maintenance and technical issues can cause temporary drops

## Applications

This toolkit can be valuable for:
- Game developers analyzing player engagement
- Publishers evaluating game performance
- Market analysts studying gaming trends
- Researchers investigating online community behavior

## Contributing

We welcome contributions and suggestions! 
