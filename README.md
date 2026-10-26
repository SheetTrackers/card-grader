# Card Grader

Card Grader looks at scans of your Pokémon cards the way a grader does: it measures centering, corners, edges and surface, then estimates PSA, Beckett and CGC grades and tells you whether a card is worth sending in.

- It grades on your own computer. No account, no AI, and your scans never leave your PC.
- It goes online only to recognize a card and look up its prices (it sends just the name and number it read from the card, never the scan) and to check for app updates.

## What it does

- **Grade a card, a whole folder, or as you scan.** Point it at the folder your scanner saves to and it grades each card a few seconds after you scan it (front first, then back), looks up its price and saves it to History. It keeps watching after it restarts or updates, and plays a short sound when a card is done.
- **Recognizes the card.** It reads the name and number on the scan and finds the exact card, so you don't have to type it.
- **Steadier grades.** When a card sits right between two grades, it asks for a second scan and combines both into one grade.
- **My collection.** Every saved card with what it's worth now, whether its price is climbing or falling, and whether to keep it, sell it or send it to PSA, plus the total value.
- **PSA submission list.** Adds every card worth grading, groups them by PSA service level and shows the fees and the expected profit.
- **Prices and "worth sending?"** Current raw and PSA prices, the chance of each grade, and whether grading pays after fees.
- **Deal check.** The most you should pay for a card, from a scan or just the seller's photos.
- **Trim and fake checks** against your own scanner's calibration.
- **Smaller scan files (optional).** Replaces each full scan with a cropped copy of just the card, named after it.
- **Backups.** A weekly backup of your cards, calibration and settings, to move to a new computer.

## Download (Windows)

**[Download Card Grader 1.6.0 for Windows](https://github.com/SheetTrackers/card-grader/raw/main/downloads/CardGrader-Setup.exe)** (installer, about 6 MB). Already have it? It updates itself.

## Install

1. Download the installer above and run it.
2. If Windows says **"Windows protected your PC"**, click **More info**, then **Run anyway**. The app isn't signed by a big publisher, so Windows asks once.
3. If Windows 11 says **"Smart App Control blocked"**, it has no "Run anyway" button. Turn it off once: Start menu → **Windows Security** → **App & browser control** → **Smart App Control settings** → **Off**. Then run the installer again. Microsoft Defender keeps protecting your PC.
4. Click **Install**, then **Finish**. Card Grader opens on its **Set up** page.

## First-time setup

The **Set up** page walks you through everything, one step at a time:

1. **Scanner settings**: 600 dpi or higher, colour, all auto-enhance options off. A sheet of black paper behind the cards gives the best results.
2. **Grading costs**: PSA's prices are already filled in. Change them if you pay something different.
3. **Where you sell**: pick eBay, Misprint or your own fees.
4. **Free price key** (optional): for PSA graded prices, get your own free key at pokemonpricetracker.com. Each person needs their own key.
5. **Calibrate your scanner** (do this, see below).

## Calibrate your scanner

Every scanner measures a little differently. Calibrating teaches Card Grader how *your* scanner sees real cards, so the size check (trimmed cards) and the back-colour check (fakes) are accurate. It takes about 5 minutes and you only do it once.

1. **Pick 10 to 20 cards you know are genuine and untrimmed.** Cards you pulled from packs yourself are ideal. If you have vintage cards too, include a few: older backs print a lighter, bluer blue.
2. **Scan their backs** the way you normally scan (600 dpi, colour, auto-enhance off). One card per scan is fine, or several per scan with a small gap between them.
3. In Card Grader, open **Settings** and scroll to **Scanner calibration**.
4. Set **These scans show** to **The backs of the cards**. Leave **Scan resolution** on **Read from file**.
5. Click **Choose scans** and select your back scans (up to 20 cards at a time). Wait for the table of measurements to appear.
6. Click **Save calibration**.
7. Have more cards? Repeat steps 5 and 6. Each run adds to the cards you saved before.

When it's done, the **Saved** table shows your scanner's scale correction and how many cards it's based on. From then on, every card you grade uses it automatically.

Scanning at 800 dpi or more? Then also run a calibration with the **fronts** of the same cards. That adds the front print-pattern check. At 600 dpi it isn't needed.

## Updates

Card Grader updates itself. When a new version is ready, a bar at the top of the app says so. Click **Restart now**, or keep working and it updates the next time you open it.

Every update is signed, and the app only installs updates that carry that signature. You can turn automatic updates off in **Settings → Updates**.

## Grade as you scan

1. Set your scanner software to save every scan into one folder, outside OneDrive or other cloud folders (full scans are big).
2. In Card Grader, on **Grade a card**, press **Grade as I scan** and pick that folder.
3. Scan the front, then flip the card and scan the back. A few seconds later it shows up graded, named and priced, and it's saved to History.
4. If it asks for a second scan, scan the card again the same way: both scans are combined into one grade.

## Your data

Your scans, saved cards, calibration and price key stay on your computer. Nothing you do in the app is uploaded. The weekly backup goes into your Documents folder, in **Card Grader backups**.
