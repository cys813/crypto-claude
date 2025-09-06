# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Configuration

The repository contains a single configuration file `ccxt-config.json` for cryptocurrency exchange trading via CCXT.

### CCXT Configuration

The configuration file contains:
- **Exchange**: OKX
- **Default Type**: swap (derivative contracts)
- **Account Name**: "okx"

**SECURITY WARNING**: The configuration file contains API credentials. When working with this repository:
- Never commit API keys or secrets
- Use environment variables or secure configuration management in production
- Handle sensitive data with care

## Architecture

This appears to be a minimal cryptocurrency trading setup using:
- CCXT library for exchange integration
- OKX exchange configuration
- Derivative trading (swap contracts)

## Development

Currently no build, test, or lint commands are configured. The repository appears to be in early development stages.

## Security Considerations

When working with cryptocurrency trading systems:
- Never expose API credentials
- Implement proper error handling for trading operations
- Consider rate limiting and risk management
- Test with paper trading accounts before using real funds