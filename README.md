# Gumption

A concept prototype for a UK household admin agent: it watches bills, subscriptions, bookings and refunds, does the legwork, and asks before anything touches your money.

The whole app is one file, `index.html`. It has no build step and no dependencies beyond Google Fonts.

## What is in it

- **Marketing site**: what the agent takes on, how it works, pricing, FAQ.
- **App demo** (open `#app`), running on an example household:
  - **Today**: savings ledger (estimated vs confirmed on real bills), approvals, activity log with undo.
  - **Bills**: every commitment with its renewal date and status.
  - **Chat**: scripted conversation with the agent.
  - **Controls**: per-category dial (watch only / ask me first / just handle it), spending ceiling, channels, quiet hours, pause, close account.

## Run it

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Publish with GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`. Free Pages hosting needs the repository to be public.

## Status

Everything here is illustrative. The household, suppliers, figures and the £6 price are placeholders, nothing connects to real accounts, and this is not a live financial service. The name "Gumption" has not been cleared as a trade mark.
