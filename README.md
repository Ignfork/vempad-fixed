# VemPad ($VEMPAD)

The whole site is one file, `index.html`. Upload it to any static host. You don't need a build step.

## Settings to edit
These are at the top of the `<script>`:

```js
var CONFIG = {
  xUrl: 'https://x.com/VemPadLive',
  xHandle: '@VemPadLive',
  ca: '',        // $VEMPAD contract address at launch (shows in the hero chip, click to copy)
  launchUrl: ''  // where the Launch / Claim buttons go once live
};
```

## Features
- **Hero:** Venmo-style blue card with a phone showing creator fees counting up, plus a ticker strip.
- **Live coins:** sample coins with All / Trending / Graduate soon / New / Fees waiting filters, search, a grid/list toggle, refresh, bonding-curve bars and fees waiting per X account.
- **Explore more:** pick anyone on X, earn on every trade (fee bars), and a live leaderboard.
- **Creator fees:** a transaction card that ticks up, plus a volume and fee-rate calculator.
- **Cash out to Venmo:** held balances. The claim button opens at launch, and the site never asks for passwords.
- **Fee feed:** a social payment feed with emoji notes and tappable reactions.
- **Launch builder:** name, ticker, X account, color and dev buy, with a live coin-card preview that's saved on the device.
- **Also:** FAQ, Learn more, Get in touch, Built on, confetti, and a read-only wallet connect.

VemPad isn't affiliated with PayPal, Venmo or X. That's stated in the hero footnote, the FAQ and the footer. The site doesn't use the Venmo logo or wordmark.
