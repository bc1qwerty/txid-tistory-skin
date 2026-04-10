# txid-tistory-skin (Odyssey)

## Language
- Respond in Korean (한국어로 응답)

## Description
Custom Tistory blog skin for txid.tistory.com. Based on the "Odyssey" template with customizations for the TXID brand. Used for Korean SEO content cross-posted from learn.txid.uk.

## Tech Stack
- **Platform**: Tistory blog (Kakao)
- **Skin format**: HTML + CSS + XML configuration
- **No build step** -- files are uploaded directly to Tistory skin editor

## Key Files
- `skin.html` -- Main HTML template (Tistory substitution tags: `[##_var_##]`)
- `style.css` -- Skin stylesheet
- `index.xml` -- Skin configuration (variables, cover types, layout options)

## Skin Features (from index.xml)
- 5 cover/list styles: thumbnail, crop, resize, poster, text
- Sidebar: right or drawer mode
- Slogan and banner sections (configurable visibility)
- Profile sidebar with social links
- Footer with custom links and copyright

## Deployment
- Upload `skin.html`, `style.css`, `index.xml` via Tistory admin > Skin editor
- Target: txid.tistory.com

## Status
- Active, deployed on txid.tistory.com
