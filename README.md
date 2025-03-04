## How to verify your token

1. Create Pull Request with following information to `tokens.json` file:

```ts
{
  "$policyId": {
    "project": string,
    "categories": string[],
    "socialLinks"?: {
      "website"?: string,
      "twitter"?: string,
      "discord"?: string,
      "telegram"?: string,
      "coinMarketCap"?: string,
      "coinGecko"?: string
    }
  }
}
```

If you don't know how to create pull request, create an issue with above information and our team will update. A PR will be processed faster.

2. Post your policy ID on Twitter or display your policy ID on your landing page.
3. Our team will verify and approve in first-in-first-out order.
