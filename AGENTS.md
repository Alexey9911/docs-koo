# Neyrs Documentation Project

## About this project

- This is a documentation site for Neyrs, an AI-powered Solana agent
- Built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "agent" not "bot" when referring to Neyrs
- Use "wallet operations" not "wallet management"
- Use "natural language commands" not "chat interface"
- Use "transaction" not "tx" in documentation
- Use "USDC" not "stablecoin" when referring to payment currency

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Connect Wallet**
- Code formatting for commands, addresses, and API endpoints
- Use technical language appropriate for developers
- Avoid marketing buzzwords — focus on technical accuracy

## Content boundaries

- Document public API endpoints only
- Do not document internal admin features
- Focus on Solana mainnet operations
- Include security warnings for transaction operations
- Provide realistic code examples with proper error handling
