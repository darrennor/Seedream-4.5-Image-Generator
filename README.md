# Seedream 4.5 Image Generator

A single-file web app for generating images with ByteDance's **Seedream 4.5** model (`bytedance-seed/seedream-4.5`) via the [OpenRouter](https://openrouter.ai) API.

Everything lives in one HTML file — no build step, no server, no dependencies.

## Usage

1. Open `a.html` in a browser (double-click it, or serve it locally).
2. Paste your OpenRouter API key (`sk-or-v1-...`) into the sidebar.
3. Write a prompt and hit **Generate**.
4. Generated images can be downloaded as PNGs.

## Cost

Roughly **£0.03 per image** via OpenRouter (check current pricing on the [model page](https://openrouter.ai/bytedance-seed/seedream-4.5)).

## Notes

- Your API key is entered in the browser and sent only to OpenRouter — nothing is stored server-side (there is no server).
- Requests go directly to `https://openrouter.ai/api/v1/chat/completions` from the browser.
