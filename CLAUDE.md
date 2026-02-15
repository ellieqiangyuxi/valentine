# Valentine's Day Card for Leah

## Project Overview
A Valentine's Day card website with an interactive envelope that opens to reveal a love letter with family photo. Built with plain HTML/CSS/JS (no framework).

## Key Details
- **For**: Leah
- **From**: XiXi's Dad
- **XiXi**: Their daughter (shown in family photo)
- **Family photo**: `family.jpg` 

## Project Structure
```
valentine/
├── index.html    (HTML structure)
├── style.css     (all styling)
├── script.js     (petal/sparkle generation, envelope interaction)
├── family.jpg    (family photo - do not compress)
├── CNAME         (custom domain config)
```

## Hosting
- **GitHub repo**: https://github.com/ellieqiangyuxi/valentine
- **GitHub Pages URL**: https://ellieqiangyuxi.github.io/valentine/
- **Custom domain**: qiangyuxi.com (purchased from GoDaddy)
- **Git username**: ellieqiangyuxi

## DNS Setup (GoDaddy)
- 4 A records pointing @ to GitHub IPs (185.199.108-111.153)
- CNAME: www → ellieqiangyuxi.github.io
- CNAME file in repo contains: qiangyuxi.com

## Status / Known Issues
- GoDaddy had a free website builder that was intercepting traffic (deleted)
- HTTPS certificate (Let's Encrypt) may still be provisioning
- If qiangyuxi.com isn't working yet, may need to temporarily remove CNAME file from repo so ellieqiangyuxi.github.io/valentine/ works as fallback

## Card Features
- Wax-sealed envelope on wine-colored background with floating rose petals
- Tap to open envelope, letter rises with staggered text animation
- Multilingual "你辛苦了" message (Chinese, English, French, Japanese, Italian, Spanish)
- Polaroid-style family photo
- Beating heart animation
- Meta tags for link previews (iMessage, WhatsApp, etc.)
