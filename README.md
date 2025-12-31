
Advanced indicator for the **Quantower** platform that displays GEX (Gamma Exposure), Gamma and Delta profiles in real-time via the GexBot.com API.

## 📋 Description

GexBot is a powerful indicator that visualizes gamma and delta exposure data from options, providing valuable insights into potential support and resistance levels based on options activity. The indicator displays comprehensive visual profiles with major levels, historical data (priors) and detailed information.

## ✨ Features

### 🎯 Data Types
- **GEX (Gamma Exposure)** : Classic profiles based on volume or open interest
- **Gamma** : Gamma level visualization (State mode only)
- **Delta** : Delta level visualization (State mode only)

### 📊 Subscription Modes
- **Classic** : Classic GEX profile
- **State** : Profile with advanced Gamma/Delta data

### 🔄 Aggregations
- **Full** : Full aggregation
- **Zero** : Zero aggregation (0DTE)
- **One** : One day aggregation (1DTE)

### 📈 Visualizations
- **GEX Profiles** : Horizontal colored bars based on positive/negative values
- **Major Levels** :
  - Major Positive/Negative (Volume)
  - Major Positive/Negative (Open Interest)
  - Zero Gamma
  - Greek Majors (Gamma/Delta mode)
- **Prior Dots** : Historical points (1m, 5m, 10m, 15m, 30m) with customizable colors
- **Labels** : Price and value display with overlap avoidance
- **Status Text** : Configurable information block in NinjaTrader style

### 🎨 Customization
- **Position** : Display on left or right side of the chart
- **Colors** : Full customization of all colors
- **Line Styles** : Solid, Dash, Dot
- **Size and Spacing** : Full control over dimensions
- **Formatting** : Decimals, localized formatting

- ## ⚙️ Configuration

### Required Parameters
- **API Key** : GexBot.com API key (get it on [gexbot.com](https://gexbot.com))
- **Ticker** : Symbol to analyze (e.g.: SPX, SPY, QQQ)
- **Type** : Classic or State
- **Aggregation** : full, zero, or one
- **Data** : GEX, Gamma, or Delta

### Display Parameters
- **Refresh Interval** : Refresh interval in seconds (default: 10)
- **Profile Width** : Profile width in pixels
- **X Position from Right** : Horizontal position from the right
- **Bar Height** : Profile bar height
- **Direction** : Display on left or right

### Major Levels Parameters
Enable/disable each level individually :
- Major Positive/Negative (Volume)
- Major Positive/Negative (Open Interest)
- Zero Gamma
- Greek Majors (for Gamma/Delta modes)

### Prior Dots Parameters
- **Show Prior Dots** : Display historical points
- **Dot Size** : Point size
- **Prior Dots Mode** : Change (difference) or Absolute (absolute value)
- **Prior Dots Scale** : Independent scale or shared with profile
- **Colors** : Customization of 5 periods (1m, 5m, 10m, 15m, 30m)

## 📖 Usage

1. Open a chart in Quantower
2. Add the GexBot indicator from the indicators list
3. Configure your API Key and basic parameters
4. Adjust display parameters according to your preferences
5. The indicator will update automatically according to the configured interval

6. <img width="2546" height="1289" alt="image" src="https://github.com/user-attachments/assets/b6917fe4-d68e-4505-a30a-84cbb77b9a6e" />

