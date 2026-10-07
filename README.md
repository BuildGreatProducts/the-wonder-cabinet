# The Wonder Cabinet

A working collection of 100 everyday interface components — buttons, toggles, sliders, toasts, date pickers — each rebuilt as something you'd want to touch twice, and each rendered in its own visual language, from risograph to ukiyo-e to claymation.

**Browse it live:** https://thewondercabinet.dev

## Try them yourself

Every component is a single, self-contained HTML file with no build step and no dependencies. Download or clone the repo and open `index.html` (the gallery) or any file in `components/` directly in a browser.

```bash
git clone https://github.com/BuildGreatProducts/the-wonder-cabinet.git
cd the-wonder-cabinet
open index.html
```

A few notes:

- Fonts load from Google Fonts, so you'll need a connection for the intended typography.
- Five pieces use WebGL (003, 008, 054, 056, 092) and show a fallback without it.
- Many pieces have soft synthesised sound (WebAudio) that starts only after you interact.
- Everything works with mouse, touch and keyboard, and respects reduced-motion settings.

## What's inside

```
index.html        the gallery: ten rooms, a floor plan, search and a full-screen viewer
components/       100 standalone components, one HTML file each
thumbs/           preview images used by the gallery
```

## The collection

### Room A · Buttons & Actions

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 001 | [Rubber Stamp Approve](components/001-rubber-stamp-approve.html) | Approve / reject buttons | Risograph print |
| 002 | [Matchstick Deploy](components/002-matchstick-deploy.html) | Primary "Deploy to production" button | Vintage Eastern-European matchbox label lithography |
| 003 | [Ink Bleed Delete](components/003-ink-bleed-delete.html) | Hold-to-confirm destructive button | Macro photography of wet ink blooming in water |
| 004 | [Pneumatic Tube Send](components/004-pneumatic-tube-send.html) | Chat send button | Isometric cutaway illustration |
| 005 | [Floppy Disk Save](components/005-floppy-disk-save.html) | Save button + unsaved-changes state | 1-bit dithered classic Macintosh / System 7 |
| 006 | [Photocopier Copy](components/006-photocopier-copy.html) | Copy-to-clipboard button | Photocopy punk zine |
| 007 | [Gumball Add to Cart](components/007-gumball-add-to-cart.html) | Quantity stepper + add to cart | 1950s diner advertising illustration |
| 008 | [Paper Plane Share](components/008-paper-plane-share.html) | Share button / share sheet | True 3D papercraft |
| 009 | [Domino Publish](components/009-domino-publish.html) | Publish button with a multi-step pipeline | Bauhaus poster |
| 010 | [Heart Balloon Like](components/010-heart-balloon-like.html) | Like button | Children's picture-book gouache |

### Room B · Toggles & Switches

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 011 | [Pull-Chain Theme](components/011-pull-chain-theme.html) | Dark-mode toggle | Edward Hopper-esque painterly interior |
| 012 | [Mercury Tilt Switch](components/012-mercury-tilt-switch.html) | Toggle switch | Dieter Rams / Braun instrument realism |
| 013 | [Breaker Panel Permissions](components/013-breaker-panel-permissions.html) | Toggle group with dependencies | Architect's pencil sketch with marker accents |
| 014 | [Door Hanger Status](components/014-door-hanger-status.html) | Presence / status selector | 1960s Palm Springs hotel ephemera |
| 015 | [Origami Billing Toggle](components/015-origami-billing-toggle.html) | Segmented toggle (monthly / annual) | Japanese washi / chiyogami origami |
| 016 | [Venetian Blind Privacy](components/016-venetian-blind-privacy.html) | Privacy / hide-sensitive-data toggle | Film noir |
| 017 | [Mechanical Keycap Toolbar](components/017-mechanical-keycap-toolbar.html) | Toggle button group / formatting toolbar | Hyperreal 3D product render |
| 018 | [Dormouse Do Not Disturb](components/018-dormouse-do-not-disturb.html) | Notifications on/off toggle | Beatrix Potter-style watercolour storybook illustration |
| 019 | [Guarded Production Switch](components/019-guarded-production-switch.html) | Dangerous toggle (staging / production) | 1970s NASA / Apollo mission control panel |
| 020 | [Hourglass Pause](components/020-hourglass-pause.html) | Play / pause toggle | 16-bit pixel art |

### Room C · Sliders, Knobs & Dials

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 021 | [Chladni Frequency Slider](components/021-chladni-frequency-slider.html) | Slider | 19th-century scientific engraving |
| 022 | [Measuring Tape Height](components/022-measuring-tape-height.html) | Numeric slider / height input | Comic book |
| 023 | [Chili Spice Slider](components/023-chili-spice-slider.html) | Rating slider | Mexican lotería card / papel picado folk art |
| 024 | [Rubber Band Range](components/024-rubber-band-range.html) | Range slider (min/max) | Memphis design |
| 025 | [Frost Fire Thermostat](components/025-frost-fire-thermostat.html) | Circular knob | Thermal / infrared camera imagery |
| 026 | [Harp String Stepper](components/026-harp-string-stepper.html) | Stepped slider | Art Nouveau (Mucha) |
| 027 | [Balance Scale Allocator](components/027-balance-scale-allocator.html) | Split slider / allocation | Medieval illuminated manuscript |
| 028 | [Pour to Measure](components/028-pour-to-measure.html) | Quantity slider | Claymation / plasticine |
| 029 | [Candle Sleep Timer](components/029-candle-sleep-timer.html) | Timer duration input | Chiaroscuro oil painting (Georges de La Tour candlelight) |
| 030 | [Radio Tuner Dial](components/030-radio-tuner-dial.html) | Selection knob | Soviet constructivist poster (Rodchenko) |

### Room D · Text & Data Entry

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 031 | [Typewriter Field](components/031-typewriter-field.html) | Text input | Ligne claire comic (Hergé-style) |
| 032 | [Vault Tumbler Code](components/032-vault-tumbler-otp.html) | OTP / PIN input | Low-poly faceted 3D |
| 033 | [Rotary Dial Phone](components/033-rotary-dial-phone.html) | Phone number input | 1970s supergraphics |
| 034 | [Postcard Message](components/034-postcard-character-limit.html) | Character-limited textarea | Vintage linen travel postcard |
| 035 | [Envelope Email Field](components/035-envelope-email-field.html) | Email input with validation | Philately / postal engraving |
| 036 | [Password Garden](components/036-password-garden.html) | Password strength meter | Scientific botanical plate |
| 037 | [Mad Libs Signup](components/037-mad-libs-signup.html) | Multi-field form | Swiss International Typographic Style poster |
| 038 | [Fridge Magnet Tags](components/038-fridge-magnet-tags.html) | Tag input | Glossy plastic toy 3D |
| 039 | [Abacus Number Input](components/039-abacus-number-input.html) | Number input | Wood marquetry / inlay |
| 040 | [Fountain Pen Signature](components/040-fountain-pen-signature.html) | Signature pad | Victorian legal copperplate |

### Room E · Pickers & Selection

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 041 | [Paint Mixing Colour Picker](components/041-paint-mixing-color-picker.html) | Colour picker | Impasto oil paint |
| 042 | [Constellation Interest Picker](components/042-constellation-interest-picker.html) | Multi-select chips | Antique celestial atlas (Hevelius) |
| 043 | [Rolodex Contact Select](components/043-rolodex-contact-select.html) | Select / dropdown | Wes Anderson symmetrical pastel set |
| 044 | [Sun Arc Time Picker](components/044-sun-arc-time-picker.html) | Time picker | Grainy flat gouache landscape illustration (Tom Haugomat-like) |
| 045 | [Moon Phase Date Picker](components/045-moon-phase-date-picker.html) | Date picker | Cyanotype print |
| 046 | [Car Radio Preset Buttons](components/046-car-radio-preset-buttons.html) | Radio button group | 1960s American car dashboard |
| 047 | [Morphing Mood Face](components/047-morphing-mood-face.html) | Emoji / Likert rating | 1930s rubber-hose cartoon |
| 048 | [Sieve Shake Filter](components/048-sieve-shake-filter.html) | Filter controls (max price) | Matisse cut-outs |
| 049 | [Bookshelf Sort](components/049-bookshelf-sort.html) | Sort control / dropdown | New Yorker-style ink cross-hatch illustration |
| 050 | [Type Case Font Picker](components/050-type-case-font-picker.html) | Font picker / dropdown | Letterpress realism |

### Room F · Feedback & Status

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 051 | [Toaster Notifications](components/051-toaster-notifications.html) | Toast notifications | Kawaii sticker illustration |
| 052 | [Blueprint Skeleton](components/052-blueprint-skeleton.html) | Skeleton loader | Blueprint / technical drawing |
| 053 | [Evaporation Upload](components/053-evaporation-upload.html) | Upload progress | Wet-on-wet watercolour |
| 054 | [Layer Print Download](components/054-layer-print-download.html) | Download progress bar | Clean real-time 3D product visualisation (WebGL or CSS 3D) |
| 055 | [Spirograph Spinner](components/055-spirograph-spinner.html) | Indeterminate loading spinner | Ballpoint pen on paper |
| 056 | [Bubble Wrap Wait](components/056-bubble-wrap-wait.html) | Long-running task / loading screen | Y2K iridescent / holographic chrome |
| 057 | [Birds on a Wire](components/057-birds-on-a-wire-typing.html) | Typing indicator | Ukiyo-e woodblock print (Hiroshige) |
| 058 | [Summit Stepper](components/058-summit-stepper.html) | Step / progress indicator | WPA national park screen-print poster |
| 059 | [Mailbox Inbox Badge](components/059-mailbox-inbox-badge.html) | Notification badge | Stitched felt / textile stop-motion |
| 060 | [Jelly Validation](components/060-jelly-validation.html) | Form validation errors | Gummy-candy 3D |

### Room G · Navigation & Wayfinding

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 061 | [Breadcrumb Trail Birds](components/061-breadcrumb-trail-birds.html) | Breadcrumbs | Lotte Reiniger cut-paper silhouette fairytale |
| 062 | [Bellows Accordion](components/062-bellows-accordion.html) | Accordion / FAQ disclosure | 1920s Art Deco Parisian cabaret poster |
| 063 | [Notebook Index Tabs](components/063-notebook-index-tabs.html) | Tabs | Bullet journal |
| 064 | [Transit Map Sitemap](components/064-transit-map-sitemap.html) | Sitemap / mega menu | Vignelli / Beck transit diagram |
| 065 | [Matryoshka Folders](components/065-matryoshka-folders.html) | Folder hierarchy / file browser | Russian Khokhloma folk painting |
| 066 | [Page Curl Pagination](components/066-page-curl-pagination.html) | Pagination | Antique leather-bound gilded book realism |
| 067 | [Radial Flick Menu](components/067-radial-flick-menu.html) | Context menu | Stencil graffiti / street art |
| 068 | [Ferris Wheel Carousel](components/068-ferris-wheel-carousel.html) | Carousel | Victorian carnival / circus poster |
| 069 | [Sushi Conveyor Feed](components/069-sushi-conveyor-feed.html) | Infinite feed / product list | Showa-era Japanese signage and packaging |
| 070 | [Lighthouse Search](components/070-lighthouse-search.html) | Command palette / search | Antique nautical sea chart |

### Room H · Overlays & Reveals

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 071 | [Toy Theatre Modal](components/071-theater-curtain-modal.html) | Modal dialog | Victorian toy paper theatre (Pollock's) |
| 072 | [Cookie Jar Consent](components/072-cookie-jar-consent.html) | Cookie consent banner | Children's crayon drawing |
| 073 | [Peephole Link Preview](components/073-peephole-link-preview.html) | Link hover preview | Lomography film photography |
| 074 | [Pop-up Book Popover](components/074-pop-up-book-popover.html) | Popover / info tooltip | Children's pop-up book |
| 075 | [Fogged Glass Spoiler](components/075-fogged-glass-spoiler.html) | Spoiler / content-warning reveal | Cinematic rainy window |
| 076 | [Instant Photo Lazy Load](components/076-polaroid-lazy-load.html) | Lazy-loaded images | 1970s instant photography |
| 077 | [Sticker Peel Coupon](components/077-sticker-peel-coupon.html) | Coupon / promo-code reveal | Sticker-bomb vinyl |
| 078 | [Zipper Pocket Drawer](components/078-zipper-pocket-drawer.html) | Drawer / expanding panel | Denim / workwear textile |
| 079 | [X-ray Inspector Lens](components/079-xray-inspector-lens.html) | Inspector / dev-tools tooltip | Medical X-ray film over a clean interface |
| 080 | [Slide Projector Lightbox](components/080-slide-projector-lightbox.html) | Lightbox / image viewer | 1960s Kodachrome home slides |

### Room I · Data & Visualization

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 081 | [Knitted Activity Heatmap](components/081-knitted-activity-heatmap.html) | Contribution heatmap | Knitted textile |
| 082 | [Draw Your Guess Chart](components/082-draw-your-guess-chart.html) | Line chart | Felt-tip marker on graph paper |
| 083 | [Slice the Pie Chart](components/083-slice-the-pie-chart.html) | Pie chart | Mid-century cookbook illustration |
| 084 | [Marble Jar Storage](components/084-marble-jar-storage.html) | Storage usage meter | Glass realism |
| 085 | [Calder Mobile Org Chart](components/085-calder-mobile-org-chart.html) | Tree / hierarchy chart | Calder modernist |
| 086 | [Horse Race Leaderboard](components/086-horse-race-leaderboard.html) | Leaderboard | Eadweard Muybridge motion study |
| 087 | [River Timeline](components/087-river-timeline.html) | Timeline | Chinese shan shui handscroll |
| 088 | [Snow Globe Weather](components/088-snow-globe-weather.html) | Weather widget | Tilt-shift miniature diorama |
| 089 | [Tree Ring History](components/089-tree-ring-history.html) | Radial chart / yearly summary | Woodcut / linocut print |
| 090 | [Xylophone Bar Chart](components/090-xylophone-bar-chart.html) | Bar chart | Montessori wooden toy |

### Room J · Novel Interactions

| No. | Component | Reimagines | Rendered as |
|---|---|---|---|
| 091 | [Cassette Tape Undo](components/091-cassette-tape-undo.html) | Undo / redo history | Translucent 90s tech |
| 092 | [Crumpled Paper Trash](components/092-crumpled-paper-trash.html) | Delete / restore | Real 3D paper physics in a minimal Scandinavian office |
| 093 | [Detective String Board](components/093-detective-string-board.html) | Linking / relationship editor | True-crime evidence board realism |
| 094 | [Knock Rhythm Unlock](components/094-knock-rhythm-unlock.html) | Unlock / authentication | Engraved music notation |
| 095 | [Sigil Gesture Commands](components/095-sigil-gesture-commands.html) | Keyboard shortcuts / commands | Chalk on blackboard |
| 096 | [Etch Shake Canvas](components/096-etch-shake-canvas.html) | Drawing canvas + clear | Etch A Sketch toy realism |
| 097 | [Timezone Ring Scheduler](components/097-timezone-ring-scheduler.html) | Meeting scheduler | Antique brass astrolabe |
| 098 | [Clothesline Clipboard](components/098-clothesline-clipboard.html) | Clipboard history | Amalfi majolica tile and Mediterranean sunlight |
| 099 | [Fishing Line Refresh](components/099-fishing-line-refresh.html) | Pull to refresh | Gyotaku fish print |
| 100 | [Dandelion Focus Mode](components/100-dandelion-focus-mode.html) | Focus / zen mode | Dreamy soft-focus macro photography |
