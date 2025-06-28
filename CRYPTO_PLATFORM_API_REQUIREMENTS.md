# Crypto-Only Platform API Requirements

## Essential API Keys for Full Operation

### 1. Sports Data API (Critical - Required)
**Purpose**: Live sports data, real-time odds, match schedules
**Options** (choose one):
- **The Odds API** (Recommended)
  - Key: `ODDS_API_KEY`
  - Website: https://the-odds-api.com
  - Cost: $0.0001 per request (very affordable)
  - Features: Live odds, 30+ sports, real-time updates

- **SportRadar API** (Enterprise)
  - Key: `SPORTRADAR_API_KEY`
  - Website: https://sportradar.com
  - Cost: Contact for pricing
  - Features: Comprehensive sports data, high reliability

- **RapidAPI Sports** (Alternative)
  - Key: `RAPIDAPI_KEY`
  - Website: https://rapidapi.com/sports
  - Cost: Various tiers available
  - Features: Multiple sports data providers

### 2. Cryptocurrency Integration APIs (Required for Crypto-Only)

#### Blockchain Network APIs
- **Ethereum Network**
  - Key: `INFURA_PROJECT_ID` or `ALCHEMY_API_KEY`
  - Purpose: ETH, USDT, other ERC-20 tokens
  - Website: https://infura.io or https://alchemy.com
  - Cost: Free tier available

- **Bitcoin Network**
  - Key: `BLOCKCYPHER_API_KEY`
  - Purpose: Bitcoin transactions
  - Website: https://blockcypher.com
  - Cost: Free tier available

#### Cryptocurrency Exchange Rate API
- **CoinGecko API**
  - Key: `COINGECKO_API_KEY` (optional for higher limits)
  - Purpose: Real-time crypto prices
  - Website: https://coingecko.com/api
  - Cost: Free tier available

- **CoinMarketCap API**
  - Key: `COINMARKETCAP_API_KEY`
  - Purpose: Crypto price data
  - Website: https://coinmarketcap.com/api
  - Cost: Free tier available

### 3. Optional Enhancement APIs

#### AI Features (Already Implemented)
- **OpenAI API**
  - Key: `OPENAI_API_KEY`
  - Purpose: Enhanced AI betting predictions
  - Website: https://openai.com
  - Cost: Pay per use

#### Communication APIs
- **Twilio API** (For SMS notifications)
  - Keys: `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN`
  - Purpose: SMS alerts for deposits/withdrawals
  - Website: https://twilio.com
  - Cost: Pay per SMS

#### Email Services
- **SendGrid API**
  - Key: `SENDGRID_API_KEY`
  - Purpose: Email notifications
  - Website: https://sendgrid.com
  - Cost: Free tier available

## Minimum Required for Basic Operation

### Priority 1 (Essential)
1. **ODDS_API_KEY** - Sports data and live odds
2. **INFURA_PROJECT_ID** - Ethereum network access
3. **BLOCKCYPHER_API_KEY** - Bitcoin network access

### Priority 2 (Recommended)
4. **COINGECKO_API_KEY** - Crypto price data
5. **OPENAI_API_KEY** - Enhanced AI features

## Implementation Notes

### Current Platform Status
- All crypto wallet components are built and ready
- Database schema supports crypto transactions
- Real-time WebSocket connections established
- User interface is complete and professional

### What Each API Enables
- **Sports API**: Live betting odds, match data, real-time updates
- **Blockchain APIs**: Crypto deposits, withdrawals, balance tracking
- **Price APIs**: Real-time crypto valuations in USD
- **AI API**: Advanced betting predictions and recommendations

### Estimated Monthly Costs
- **The Odds API**: $50-200/month (depending on usage)
- **Infura**: Free tier sufficient for moderate usage
- **BlockCypher**: Free tier sufficient for basic operation
- **CoinGecko**: Free tier sufficient
- **Total Estimated**: $50-200/month for full operation

## Next Steps After API Keys
1. Configure API keys in environment variables
2. Test all integrations with small amounts
3. Verify crypto deposit/withdrawal functionality
4. Launch with live sports data
5. Monitor performance and scaling needs

The platform is architecturally complete and ready for immediate deployment once these API keys are configured.