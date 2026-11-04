<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Jakob Wolitzki: Amazon SP-API, Amazon Ads API, MCP and AI agents. Co-founder of DataDoe and Deltologic." src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.youtube.com/@jakobowsky?sub_confirmation=1"><img alt="YouTube: 11K+ subscribers" src="https://img.shields.io/badge/YouTube-11K%2B%20subscribers-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/jakob-wolitzki"><img alt="LinkedIn: Jakob Wolitzki" src="https://img.shields.io/badge/LinkedIn-Jakob%20Wolitzki-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/wolitzki"><img alt="X: @wolitzki" src="https://img.shields.io/badge/X-@wolitzki-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://www.datadoe.com/"><img alt="DataDoe: Amazon MCP server" src="https://img.shields.io/badge/DataDoe-Amazon%20MCP-FF9900?style=for-the-badge"></a>
</p>

I'm **Jakob Wolitzki**, co-founder of **[DataDoe](https://www.datadoe.com/)** and **[Deltologic](https://deltologic.com/)**. I have built on the Amazon Selling Partner API (SP-API) since 2020, first as an agency and now as a product: DataDoe, the Amazon data and action layer that lets Claude, ChatGPT and other AI agents read Seller Central, Vendor Central and Amazon Ads data and act on it.

On [YouTube](https://www.youtube.com/@jakobowsky) I show Amazon sellers, brands and agencies how to run their business with Claude, Claude Code, ChatGPT and MCP, on real accounts.

<table align="center">
  <tr>
    <td align="center" width="25%"><h3>11K+</h3>YouTube<br>subscribers</td>
    <td align="center" width="25%"><h3>200+</h3>Amazon builds<br>since 2020</td>
    <td align="center" width="25%"><h3>130+</h3>Amazon data<br>tables</td>
    <td align="center" width="25%"><h3>400+</h3>GitHub stars<br>on tutorials</td>
  </tr>
</table>

## DataDoe: the Amazon MCP server and data layer for AI agents

**[DataDoe](https://www.datadoe.com/)** connects any AI to Amazon. One clean layer over the SP-API and the Amazon Ads API, so an agent can answer questions on live data and then do the work.

- **All of Amazon in one schema:** Seller Central, Vendor Central and Amazon Ads, including DSP reporting and Amazon Marketing Cloud (AMC), in [130+ joined tables](https://www.datadoe.com/hub/data-scheme).
- **Read and write:** [Actions](https://www.datadoe.com/hub/docs/datadoe-features/actions) let an agent update listings and prices, handle orders and Vendor purchase orders, and manage ad campaigns. Every Action type is off until you switch it on, can run as a dry run first, and is logged.
- **Any AI, any interface:** Claude, ChatGPT, Gemini, Cursor, Codex, GitHub Copilot and n8n, through MCP, a REST API or direct BigQuery.
- **Rated 5.0 on Capterra**, with a 14-day free trial.

```json
{
  "mcpServers": {
    "datadoe": {
      "url": "https://mcp.datadoe.com/mcp/v1",
      "headers": { "datadoe-mcp-key": "<YOUR_DATADOE_MCP_KEY>" }
    }
  }
}
```

Paste it into your AI client, then ask: *"Show my top 10 ASINs by revenue last month across all marketplaces."* [Setup guide for every AI client](https://www.datadoe.com/hub/docs/datadoe-mcp/overview).

## Deltologic: Amazon SP-API engineering since 2020

**[Deltologic](https://deltologic.com/)** is the software house behind DataDoe, based in Poznań, Poland. An Amazon Selling Partner and Advertising Partner with 30+ engineers and 200+ builds for sellers, vendors and enterprises on four continents: marketplace integrations for Amazon, Walmart, eBay and Allegro, ERP and order automation, data warehouses, and AI adoption for e-commerce teams.

## Open source

| Repository | What it is |
| --- | --- |
| **[datadoe-mcp](https://github.com/Deltologic/datadoe-mcp)** | Hosted Amazon Seller and Vendor MCP server: setup guides for 20+ AI clients, the available MCP tools and Actions. |
| **[datadoe-ai-skills](https://github.com/Deltologic/datadoe-ai-skills)** | AI skills that take a coding agent from one prompt to a working Amazon app on DataDoe. |
| **[amazon-sp-api-course](https://github.com/Deltologic/amazon-sp-api-course)** | Python code for the free [Amazon SP-API course](https://courses.deltologic.com/): OAuth, Orders, Reports, Feeds, Catalog Items and Notifications APIs. |
| **[datadoe-api-starter](https://github.com/Deltologic/datadoe-api-starter)** | TypeScript template for building Amazon e-commerce apps on the DataDoe API. |
| **MCP starters** | Ready-to-clone setups for [Claude Code](https://github.com/Deltologic/datadoe-mcp-claude-code), [Cursor](https://github.com/Deltologic/datadoe-mcp-cursor), [Codex](https://github.com/Deltologic/datadoe-mcp-codex), [VS Code with Copilot](https://github.com/Deltologic/datadoe-mcp-vs-code-co-pilot) and [Gemini CLI](https://github.com/Deltologic/datadoe-mcp-gemini-cli). |

## Learn Amazon + AI for free

> [!TIP]
> **[Claude for Amazon Sellers](https://www.datadoe.com/courses/amazon-claude)** is a free course of nine short lessons: from your first prompt to Claude repricing listings, planning restocks and running PPC on a live account. No code needed.

- **[Amazon SP-API course](https://courses.deltologic.com/)** for developers who want to call the Selling Partner API directly.
- **[DataDoe Skills Library](https://www.datadoe.com/hub/ai-agents-and-skills)** with ready-made AI workflows for Amazon.
- **YouTube:** [@jakobowsky](https://www.youtube.com/@jakobowsky) for Amazon + AI tutorials and [@datadoe](https://www.youtube.com/@datadoe) for product walkthroughs.

## Latest videos

<p align="center">
<!-- YOUTUBE:START -->
<a href="https://www.youtube.com/watch?v=AA8VGwcqXok"><img width="32%" src="https://i.ytimg.com/vi/AA8VGwcqXok/mqdefault.jpg" alt="Claude Code Tutorial for Amazon Sellers (Beginner to Pro)" title="Claude Code Tutorial for Amazon Sellers (Beginner to Pro)"></a> <a href="https://www.youtube.com/watch?v=e1mS1dwB9ZY"><img width="32%" src="https://i.ytimg.com/vi/e1mS1dwB9ZY/mqdefault.jpg" alt="Amazon Seller Assistant in Claude: 5 Things to Check (2026)" title="Amazon Seller Assistant in Claude: 5 Things to Check (2026)"></a> <a href="https://www.youtube.com/watch?v=Mm2_hUAaP2w"><img width="32%" src="https://i.ytimg.com/vi/Mm2_hUAaP2w/mqdefault.jpg" alt="Claude for Amazon Brands: Full AI Course 2026" title="Claude for Amazon Brands: Full AI Course 2026"></a> <a href="https://www.youtube.com/watch?v=31rB9jOjZpI"><img width="32%" src="https://i.ytimg.com/vi/31rB9jOjZpI/mqdefault.jpg" alt="Claude Code for Amazon Agencies: MCPs, Context, and Real Costs (feat Dustin Wassner from BTR Media)" title="Claude Code for Amazon Agencies: MCPs, Context, and Real Costs (feat Dustin Wassner from BTR Media)"></a> <a href="https://www.youtube.com/watch?v=EZybEDnaFkg"><img width="32%" src="https://i.ytimg.com/vi/EZybEDnaFkg/mqdefault.jpg" alt="How to Automate Amazon PPC with Claude AI (2026)" title="How to Automate Amazon PPC with Claude AI (2026)"></a> <a href="https://www.youtube.com/watch?v=gSfm7euKrt4"><img width="32%" src="https://i.ytimg.com/vi/gSfm7euKrt4/mqdefault.jpg" alt="How to Edit and Optimize Amazon Listings from Claude (2026)" title="How to Edit and Optimize Amazon Listings from Claude (2026)"></a> 
<!-- YOUTUBE:END -->
</p>

## Milestones

| Year | Milestone |
| --- | --- |
| **2020** | Founded Deltologic in Poznań and shipped our first SP-API integrations as Amazon moved sellers off MWS. Started teaching Amazon automation on YouTube. |
| **2022** | 40 custom Amazon builds: integrations, data warehouses and internal tools for sellers, vendors and enterprises. |
| **2025** | Launched DataDoe: the Amazon data layer we kept rebuilding for clients, built once as a product, with an MCP server for AI clients. |
| **2026** | AI agents write back to Amazon through DataDoe Actions. In October: Vendor write Actions, full DSP reporting and Amazon Marketing Cloud queries from your AI agent. |

<details>
<summary><b>Older open-source Amazon tools and tutorials</b></summary>
<br>

Projects from my YouTube tutorials. Some use APIs Amazon has since retired (MWS), but they are still a useful starting point.

- **[AmazonPriceTracker](https://github.com/jakobowsky/AmazonPriceTracker)**: Amazon price tracker and scraper in Python and Selenium.
- **[amazon-sp-api-orders-to-google-sheets](https://github.com/jakobowsky/amazon-sp-api-orders-to-google-sheets)**: export Amazon orders from the SP-API Orders API to Google Sheets.
- **[new-sp-api](https://github.com/jakobowsky/new-sp-api)**: call the Amazon SP-API without AWS IAM and Signature Version 4 (the 2023 change).
- **[amazon-sp-api-reports-sales-aggregation](https://github.com/jakobowsky/amazon-sp-api-reports-sales-aggregation)**: pull SP-API reports and aggregate Amazon sales.
- **[amazon-price-and-buybox-monitoring-tool](https://github.com/jakobowsky/amazon-price-and-buybox-monitoring-tool)**: monitor prices and Buy Box winners per ASIN.
- **[amazon-sp-api-notifications](https://github.com/jakobowsky/amazon-sp-api-notifications)**: Amazon SP-API Notifications API tutorial.
- **[InfluencerDB-YouTube](https://github.com/jakobowsky/InfluencerDB-YouTube)**: find top YouTube influencers and build reports about them.

</details>

## Tools I work with

<p>
  <img alt="Python, TypeScript, Django, Docker, Google Cloud" src="https://skillicons.dev/icons?i=py,ts,django,docker,gcp&perline=8">
</p>

Amazon SP-API · Amazon Ads API · Amazon Marketing Cloud · BigQuery · MCP · Claude Code

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jakobowsky/jakobowsky/output/snake-dark.svg">
  <img alt="Animation of a snake eating Jakob Wolitzki's GitHub contribution graph" src="https://raw.githubusercontent.com/jakobowsky/jakobowsky/output/snake.svg" width="100%">
</picture>

## Let's talk

Building something on Amazon data or AI agents? [Book a call with me](https://click.deltologic.com/wolitzki-calendar) or message me on [LinkedIn](https://www.linkedin.com/in/jakob-wolitzki).
