<p align="center">
  <img src="logo.png" alt="HandleWise AI" width="160">
</p>

# HandleWise AI — eBay listings from your photos

HandleWise AI is a remote **MCP server** that turns photos of the items you want to sell into finished eBay listings on **your own eBay seller account**.

Share a few photos with your AI assistant and say **"done"**: each item is identified and priced, HandleWise picks the eBay category, and you get one summary table. Say **"go"** and HandleWise tidies the titles, estimates packed shipping size and weight, hosts the photos on eBay, and schedules every listing so you can review it before it goes live. An optional Google Drive folder keeps your photos and a spreadsheet of every listing.

- **Website:** https://earthdroids.com/handlewise/
- **Demo video:** https://youtu.be/nnj-n4nefk4
- **How to use:** https://earthdroids.com/setup.html

## Connect

| | |
|---|---|
| Server URL | `https://earthdroids.com/mcp` |
| Transport | Streamable HTTP (remote) |
| Auth | OAuth 2.1 with dynamic client registration — sign in with Google |
| Registry | `com.earthdroids/handlewise` on the [Official MCP Registry](https://registry.modelcontextprotocol.io) |

**ChatGPT:** Plugins → Add → Add custom MCP server → Connection `https://earthdroids.com/mcp` → Authentication **OAuth** → Create → Continue with Google.

Any MCP client that supports remote servers with OAuth can connect to the same URL.

## Tools

| Tool | What it does |
|---|---|
| `account_status` | Setup checklist and listing credits |
| `connect_ebay` | Link your own eBay seller account (on eBay's own sign-in page) |
| `set_ship_from_address` | Save your item location once |
| `setup_google_drive` | Optional photo folder + listings spreadsheet (drive.file scope only) |
| `research_item` | eBay category ID and current comparable prices |
| `list_item_on_ebay` | Create a scheduled fixed-price listing on your eBay |

## Try saying

- "What's my HandleWise status?"
- "List these items on eBay" (with photos attached), then "done", then "go"
- "How many credits do I have?"

## Pricing

Prepaid listing credits — a 50¢ trial for 2 listings, then packs from $5 for 100 listings. Credits never expire. eBay's own selling fees still apply. See https://earthdroids.com/handlewise/#pricing

## Limitations

US eBay marketplace; fixed-price (Buy It Now) listings; your eBay account needs business policies (shipping, payment, returns).

## Support & policies

- Support: earthdroids@gmail.com · https://earthdroids.com/support.html
- Privacy: https://earthdroids.com/privacy.html
- Terms: https://earthdroids.com/terms.html

---

HandleWise AI is made by **Earth Droids Company LLC**. It is an independent app, not affiliated with eBay, OpenAI or Anthropic. This repository contains the public listing information for the hosted service; the server itself is hosted at earthdroids.com.
