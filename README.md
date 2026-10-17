# Spendrechaun

A pixel-art leprechaun who lives on your Mac desktop, hell-bent on spending your money.
He sits by his furnace and shows a live estimate of what your Claude Code sessions cost
today, with a gag at every threshold: coin flips, money bags, bills into the furnace, and
a safe full of gold.

This repo only holds the downloads. A personal side project; not affiliated with Anthropic
or any employer.

## Install

1. Download the latest `spend-buddy_vNN.dmg` from [Releases](../../releases/latest).
2. Drag **Spend Buddy** onto **Applications** and open it.
3. The app isn't signed with an Apple Developer ID, so the first time macOS says it
   "cannot be verified": right-click the app > **Open** > **Open**.

## Privacy

Everything runs on your Mac. It reads your local Claude Code logs (token counts, model,
session titles, tool names; never your prompts or replies) and nothing is sent anywhere.
The only network request is a check every 6 hours against this repo's latest release, so
it can offer **Update to v…** in its right-click menu. Updates are never installed
automatically.

Spend is an estimate at Anthropic list prices; your real bill can differ.
