# FiveStone Production Guide

The worship production team's guide, behind a 4-digit team PIN.

This repository holds only the page itself. The content comes from the five production Google Docs, through a Google Apps Script that hands the pages over only when the passcode is right. Nothing from the Docs is stored here, so the repository can stay public.

## Editing the guide

Edit the Google Docs as usual. Changes show within 5 minutes. Phones that have opened the guide before show their saved copy instantly, then offer "The guide was updated. Tap to reload."

## Changing the PIN

In the Apps Script editor: **Project Settings** (gear) > **Script Properties** > edit **GUIDE_PASSCODE** (4 digits). Everyone is asked for the new one on their next visit. No redeploy needed.

## Files

- `index.html`: the whole site. Near the bottom, `GUIDE_API` is the Apps Script web app URL.
