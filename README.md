<style>
@font-face {
  font-family: 'Roboto Flex';
  font-style: normal;
  font-weight: 100 1000;
  font-stretch: 25% 151%;
  font-optical-sizing: auto;
  src: url(https://fonts.gstatic.com/s/robotoflex/v16/NaPecZTIAOhVxoMyOr9n_E7fdMPXJ2wa2bSV9rs.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

:root {
  --m3-primary: #C1B4E4;
  --m3-on-primary: #281B4B;
  --m3-primary-container: #3B2871;
  --m3-on-primary-container: #E0D9F2;
  --m3-primary-fixed: #E0D9F2;
  --m3-primary-fixed-dim: #C1B4E4;
  --m3-on-primary-fixed: #140D26;
  --m3-on-primary-fixed-variant: #3B2871;
  --m3-secondary: #D0C4D4;
  --m3-on-secondary: #372B3B;
  --m3-secondary-container: #534059;
  --m3-on-secondary-container: #E8E1EA;
  --m3-secondary-fixed: #E8E1EA;
  --m3-secondary-fixed-dim: #D0C4D4;
  --m3-on-secondary-fixed: #1C151E;
  --m3-on-secondary-fixed-variant: #534059;
  --m3-tertiary: #D8C0D2;
  --m3-on-tertiary: #3F2739;
  --m3-tertiary-container: #5F3A55;
  --m3-on-tertiary-container: #ECDFE8;
  --m3-tertiary-fixed: #ECDFE8;
  --m3-tertiary-fixed-dim: #D8C0D2;
  --m3-on-tertiary-fixed: #20131C;
  --m3-on-tertiary-fixed-variant: #5F3A55;
  --m3-error: #F7C8A1;
  --m3-on-error: #5E2F08;
  --m3-error-container: #8D460C;
  --m3-on-error-container: #FBE3D0;
  --m3-surface: #19181B;
  --m3-on-surface: #E5E4E7;
  --m3-surface-dim: #19181B;
  --m3-surface-bright: #323135;
  --m3-surface-container-lowest: #000000;
  --m3-surface-container-low: #19181B;
  --m3-surface-container: #262528;
  --m3-surface-container-high: #323135;
  --m3-surface-container-highest: #4B4950;
  --m3-on-surface-variant: #CAC8D0;
  --m3-outline: #9591A1;
  --m3-outline-variant: #4A4653;
  --m3-inverse-surface: #E5E4E7;
  --m3-inverse-on-surface: #19181B;
  --m3-inverse-primary: #4F3597;
  --m3-shadow: #000000;
  --m3-scrim: #000000;
  --m3-surface-tint: #C1B4E4;
  --m3-type-font-family: "Roboto Flex", "Inter", system-ui, sans-serif;
  --m3-type-font-family-monospace: "Roboto Mono", "Fira Code", monospace;
  --m3-type-display-large-font-size: 3.5rem;
  --m3-type-display-large-font-weight: 400;
  --m3-type-display-large-line-height: 1.12;
  --m3-type-display-large-letter-spacing: -0.02em;
  --m3-type-display-medium-font-size: 2.8125rem;
  --m3-type-display-medium-font-weight: 400;
  --m3-type-display-medium-line-height: 1.16;
  --m3-type-display-medium-letter-spacing: -0.02em;
  --m3-type-display-small-font-size: 2.25rem;
  --m3-type-display-small-font-weight: 400;
  --m3-type-display-small-line-height: 1.22;
  --m3-type-display-small-letter-spacing: 0;
  --m3-type-headline-large-font-size: 2rem;
  --m3-type-headline-large-font-weight: 400;
  --m3-type-headline-large-line-height: 1.25;
  --m3-type-headline-large-letter-spacing: 0;
  --m3-type-headline-medium-font-size: 1.75rem;
  --m3-type-headline-medium-font-weight: 400;
  --m3-type-headline-medium-line-height: 1.29;
  --m3-type-headline-medium-letter-spacing: 0;
  --m3-type-headline-small-font-size: 1.5rem;
  --m3-type-headline-small-font-weight: 400;
  --m3-type-headline-small-line-height: 1.33;
  --m3-type-headline-small-letter-spacing: 0;
  --m3-type-title-large-font-size: 1.375rem;
  --m3-type-title-large-font-weight: 400;
  --m3-type-title-large-line-height: 1.4;
  --m3-type-title-large-letter-spacing: 0;
  --m3-type-title-medium-font-size: 1.125rem;
  --m3-type-title-medium-font-weight: 500;
  --m3-type-title-medium-line-height: 1.45;
  --m3-type-title-medium-letter-spacing: 0.01em;
  --m3-type-title-small-font-size: 1rem;
  --m3-type-title-small-font-weight: 500;
  --m3-type-title-small-line-height: 1.5;
  --m3-type-title-small-letter-spacing: 0.01em;
  --m3-type-body-large-font-size: 1rem;
  --m3-type-body-large-font-weight: 400;
  --m3-type-body-large-line-height: 1.5;
  --m3-type-body-large-letter-spacing: 0.01em;
  --m3-type-body-medium-font-size: 0.875rem;
  --m3-type-body-medium-font-weight: 400;
  --m3-type-body-medium-line-height: 1.43;
  --m3-type-body-medium-letter-spacing: 0.02em;
  --m3-type-body-small-font-size: 0.75rem;
  --m3-type-body-small-font-weight: 400;
  --m3-type-body-small-line-height: 1.5;
  --m3-type-body-small-letter-spacing: 0.04em;
  --m3-type-label-large-font-size: 0.875rem;
  --m3-type-label-large-font-weight: 500;
  --m3-type-label-large-line-height: 1.43;
  --m3-type-label-large-letter-spacing: 0.01em;
  --m3-type-label-medium-font-size: 0.75rem;
  --m3-type-label-medium-font-weight: 500;
  --m3-type-label-medium-line-height: 1.5;
  --m3-type-label-medium-letter-spacing: 0.03em;
  --m3-type-label-small-font-size: 0.6875rem;
  --m3-type-label-small-font-weight: 500;
  --m3-type-label-small-line-height: 1.5;
  --m3-type-label-small-letter-spacing: 0.05em;
  --m3-font-family: "Roboto Flex", "Inter", system-ui, sans-serif;
  --m3-font-family-mono: "Roboto Mono", "Fira Code", monospace;
  --m3-fluid-type-display-large-font-size: clamp(3.5rem, 5vw + 1rem, 5rem);
  --m3-fluid-type-display-large-font-weight: 400;
  --m3-fluid-type-display-large-line-height: 1.12;
  --m3-fluid-type-display-large-letter-spacing: -0.02em;
  --m3-fluid-type-display-large-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 48;
  --m3-fluid-type-display-medium-font-size: clamp(2.8125rem, 4vw + 0.8rem, 3.5rem);
  --m3-fluid-type-display-medium-font-weight: 400;
  --m3-fluid-type-display-medium-line-height: 1.16;
  --m3-fluid-type-display-medium-letter-spacing: -0.02em;
  --m3-fluid-type-display-medium-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 40;
  --m3-fluid-type-display-small-font-size: clamp(2.25rem, 3vw + 0.6rem, 2.8125rem);
  --m3-fluid-type-display-small-font-weight: 400;
  --m3-fluid-type-display-small-line-height: 1.22;
  --m3-fluid-type-display-small-letter-spacing: 0;
  --m3-fluid-type-display-small-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 32;
  --m3-fluid-type-headline-large-font-size: clamp(2rem, 2.5vw + 0.5rem, 2.25rem);
  --m3-fluid-type-headline-large-font-weight: 400;
  --m3-fluid-type-headline-large-line-height: 1.25;
  --m3-fluid-type-headline-large-letter-spacing: 0;
  --m3-fluid-type-headline-large-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 28;
  --m3-fluid-type-headline-medium-font-size: clamp(1.75rem, 2vw + 0.4rem, 2rem);
  --m3-fluid-type-headline-medium-font-weight: 400;
  --m3-fluid-type-headline-medium-line-height: 1.29;
  --m3-fluid-type-headline-medium-letter-spacing: 0;
  --m3-fluid-type-headline-medium-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 24;
  --m3-fluid-type-headline-small-font-size: clamp(1.5rem, 1.5vw + 0.3rem, 1.75rem);
  --m3-fluid-type-headline-small-font-weight: 400;
  --m3-fluid-type-headline-small-line-height: 1.33;
  --m3-fluid-type-headline-small-letter-spacing: 0;
  --m3-fluid-type-headline-small-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 20;
  --m3-fluid-type-title-large-font-size: clamp(1.375rem, 1.2vw + 0.25rem, 1.5rem);
  --m3-fluid-type-title-large-font-weight: 400;
  --m3-fluid-type-title-large-line-height: 1.4;
  --m3-fluid-type-title-large-letter-spacing: 0;
  --m3-fluid-type-title-large-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 18;
  --m3-fluid-type-title-medium-font-size: clamp(1.125rem, 1vw + 0.2rem, 1.25rem);
  --m3-fluid-type-title-medium-font-weight: 500;
  --m3-fluid-type-title-medium-line-height: 1.45;
  --m3-fluid-type-title-medium-letter-spacing: 0.01em;
  --m3-fluid-type-title-medium-font-variation-settings: "wght" 500, "wdth" 100, "opsz" 16;
  --m3-fluid-type-title-small-font-size: clamp(1rem, 0.8vw + 0.15rem, 1.125rem);
  --m3-fluid-type-title-small-font-weight: 500;
  --m3-fluid-type-title-small-line-height: 1.5;
  --m3-fluid-type-title-small-letter-spacing: 0.01em;
  --m3-fluid-type-title-small-font-variation-settings: "wght" 500, "wdth" 100, "opsz" 14;
  --m3-fluid-type-body-large-font-size: clamp(1rem, 0.6vw + 0.1rem, 1.125rem);
  --m3-fluid-type-body-large-font-weight: 400;
  --m3-fluid-type-body-large-line-height: 1.5;
  --m3-fluid-type-body-large-letter-spacing: 0.01em;
  --m3-fluid-type-body-large-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 14;
  --m3-fluid-type-body-medium-font-size: clamp(0.875rem, 0.5vw + 0.08rem, 1rem);
  --m3-fluid-type-body-medium-font-weight: 400;
  --m3-fluid-type-body-medium-line-height: 1.43;
  --m3-fluid-type-body-medium-letter-spacing: 0.02em;
  --m3-fluid-type-body-medium-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 12;
  --m3-fluid-type-body-small-font-size: clamp(0.75rem, 0.4vw + 0.06rem, 0.875rem);
  --m3-fluid-type-body-small-font-weight: 400;
  --m3-fluid-type-body-small-line-height: 1.5;
  --m3-fluid-type-body-small-letter-spacing: 0.04em;
  --m3-fluid-type-body-small-font-variation-settings: "wght" 400, "wdth" 100, "opsz" 10;
  --m3-fluid-type-label-large-font-size: clamp(0.875rem, 0.5vw + 0.08rem, 1rem);
  --m3-fluid-type-label-large-font-weight: 500;
  --m3-fluid-type-label-large-line-height: 1.43;
  --m3-fluid-type-label-large-letter-spacing: 0.01em;
  --m3-fluid-type-label-large-font-variation-settings: "wght" 500, "wdth" 100, "opsz" 12;
  --m3-fluid-type-label-medium-font-size: clamp(0.75rem, 0.4vw + 0.06rem, 0.875rem);
  --m3-fluid-type-label-medium-font-weight: 500;
  --m3-fluid-type-label-medium-line-height: 1.5;
  --m3-fluid-type-label-medium-letter-spacing: 0.03em;
  --m3-fluid-type-label-medium-font-variation-settings: "wght" 500, "wdth" 100, "opsz" 10;
  --m3-fluid-type-label-small-font-size: clamp(0.6875rem, 0.3vw + 0.05rem, 0.75rem);
  --m3-fluid-type-label-small-font-weight: 500;
  --m3-fluid-type-label-small-line-height: 1.5;
  --m3-fluid-type-label-small-letter-spacing: 0.05em;
  --m3-fluid-type-label-small-font-variation-settings: "wght" 500, "wdth" 100, "opsz" 8;
  --m3-elevation-level0: none;
  --m3-elevation-level1: 0 1px 2px rgba(0,0,0,0.05), 0 1px 3px rgba(0,0,0,0.1);
  --m3-elevation-level2: 0 2px 4px rgba(0,0,0,0.05), 0 4px 8px rgba(0,0,0,0.1);
  --m3-elevation-level3: 0 4px 8px rgba(0,0,0,0.05), 0 8px 16px rgba(0,0,0,0.1);
  --m3-elevation-level4: 0 8px 16px rgba(0,0,0,0.05), 0 16px 24px rgba(0,0,0,0.1);
  --m3-elevation-level5: 0 12px 24px rgba(0,0,0,0.05), 0 24px 32px rgba(0,0,0,0.1);
  --m3-shape-corner-none: 0;
  --m3-shape-corner-extra-small: 0.25rem;
  --m3-shape-corner-small: 0.5rem;
  --m3-shape-corner-medium: 0.75rem;
  --m3-shape-corner-large: 1rem;
  --m3-shape-corner-extra-large: 1.75rem;
  --m3-shape-corner-full: 9999px;
  --m3-shape-corner-cut-small: 0.5rem / 0.25rem;
  --m3-shape-corner-cut-medium: 0.75rem / 0.375rem;
  --m3-shape-corner-cut-large: 1rem / 0.5rem;
  --m3-shape-squircle-small: 0.5rem / 0.5rem;
  --m3-shape-squircle-medium: 0.75rem / 0.75rem;
  --m3-shape-squircle-large: 1rem / 1rem;
  --m3-shape-squircle-extra-large: 1.5rem / 1.5rem;
  --m3-shape-squircle-full: 50% / 50%;
  --m3-shape-default-corner-style: rounded;
  --m3-motion-easing-standard: cubic-bezier(0.2, 0, 0, 1);
  --m3-motion-easing-emphasized: cubic-bezier(0.2, 0, 0, 1);
  --m3-motion-easing-emphasized-accelerate: cubic-bezier(0.3, 0, 1, 1);
  --m3-motion-easing-emphasized-decelerate: cubic-bezier(0, 0, 0, 1);
  --m3-motion-easing-linear: linear;
  --m3-motion-duration-short1: 50ms;
  --m3-motion-duration-short2: 100ms;
  --m3-motion-duration-short3: 150ms;
  --m3-motion-duration-short4: 200ms;
  --m3-motion-duration-medium1: 250ms;
  --m3-motion-duration-medium2: 300ms;
  --m3-motion-duration-medium3: 350ms;
  --m3-motion-duration-medium4: 400ms;
  --m3-motion-duration-long1: 450ms;
  --m3-motion-duration-long2: 500ms;
  --m3-motion-duration-long3: 550ms;
  --m3-motion-duration-long4: 600ms;
  --m3-motion-springs-expressive: {"mass":1,"stiffness":120,"damping":14};
  --m3-motion-springs-standard: {"mass":1,"stiffness":100,"damping":10};
  --m3-motion-springs-gentle: {"mass":1,"stiffness":80,"damping":12};
  --m3-motion-springs-snappy: {"mass":0.8,"stiffness":150,"damping":12};
  --m3-motion-springEasings-expressive: cubic-bezier(0.34, 1.56, 0.64, 1);
  --m3-motion-springEasings-standard: cubic-bezier(0.2, 0, 0, 1);
  --m3-motion-springEasings-gentle: cubic-bezier(0.25, 0.1, 0.25, 1);
  --m3-motion-springEasings-snappy: cubic-bezier(0.05, 0.7, 0.1, 1);
  --m3-motion-spring-expressive: cubic-bezier(0.34, 1.56, 0.64, 1);
  --m3-motion-spring-standard: cubic-bezier(0.2, 0, 0, 1);
  --m3-motion-spring-gentle: cubic-bezier(0.25, 0.1, 0.25, 1);
  --m3-motion-spring-snappy: cubic-bezier(0.05, 0.7, 0.1, 1);
  --m3-spring-expressive-mass: 1;
  --m3-spring-expressive-stiffness: 120;
  --m3-spring-expressive-damping: 14;
  --m3-spring-expressive-easing: cubic-bezier(0.34, 1.56, 0.64, 1.00);
  --m3-spring-standard-mass: 1;
  --m3-spring-standard-stiffness: 100;
  --m3-spring-standard-damping: 10;
  --m3-spring-standard-easing: cubic-bezier(0.34, 1.56, 0.64, 1.00);
  --m3-spring-gentle-mass: 1;
  --m3-spring-gentle-stiffness: 80;
  --m3-spring-gentle-damping: 12;
  --m3-spring-gentle-easing: cubic-bezier(0.34, 1.56, 0.64, 1.00);
  --m3-spring-snappy-mass: 0.8;
  --m3-spring-snappy-stiffness: 150;
  --m3-spring-snappy-damping: 12;
  --m3-spring-snappy-easing: cubic-bezier(0.34, 1.56, 0.64, 1.00);
  --m3-spacing-xs: clamp(4px, 0.5vw + 2px, 8px);
  --m3-spacing-sm: clamp(8px, 1vw + 4px, 16px);
  --m3-spacing-md: clamp(16px, 2vw + 8px, 24px);
  --m3-spacing-lg: clamp(24px, 3vw + 12px, 32px);
  --m3-spacing-xl: clamp(32px, 4vw + 16px, 48px);
  --m3-spacing-xxl: clamp(48px, 5vw + 24px, 64px);
  --m3-layout-max-content-width: 1200px;
  --m3-layout-container-padding: var(--m3-spacing-md);
  --m3-layout-grid-gap: var(--m3-spacing-md);
  --m3-layout-grid-row-gap: var(--m3-spacing-lg);
  --m3-layout-breakpoint-sm: 600px;
  --m3-layout-breakpoint-md: 900px;
  --m3-layout-breakpoint-lg: 1200px;
  --m3-layout-breakpoint-xl: 1536px;
}
</style>

<!-- Material 3 Expressive Theme: Material Purple -->
<!-- Seed Color: #6750A4 -->

<div align="center"><img src="https://avatars.githubusercontent.com/u/189080277?v=4" alt="ibro-3" style="width: 120px; height: 120px; border-radius: 50%; box-shadow: var(--m3-elevation-level3); border: 3px solid var(--m3-surface-container-highest);" /></div>

<h1 align="center" style="color: var(--m3-on-surface); font-size: var(--m3-fluid-type-display-large-font-size); font-weight: var(--m3-fluid-type-display-large-font-weight); line-height: var(--m3-fluid-type-display-large-line-height); letter-spacing: var(--m3-fluid-type-display-large-letter-spacing); margin: 0.5rem 0;">ibro-3</h1>
<div align="center">[![GitHub](https://img.shields.io/badge?message=GitHub&color=181717&style=for-the-badge&logoColor=white&logo=github)](https://github.com/ibro-3)</div>

---

## 📊 Statistics

<table align="center">
<tr><td align="center" style="background: var(--m3-surface-container); border-radius: var(--m3-shape-corner-medium); padding: 12px 16px; min-width: 110px;"><sub style="color: var(--m3-on-surface-variant); font-size: 12px;"><span style="color: #FFD700;">⭐</span> Stars</sub><br /><strong style="color: var(--m3-primary); font-size: 1.5rem; font-weight: 600;">1</strong></td><td align="center" style="background: var(--m3-surface-container); border-radius: var(--m3-shape-corner-medium); padding: 12px 16px; min-width: 110px;"><sub style="color: var(--m3-on-surface-variant); font-size: 12px;"><span style="color: #FF6B6B;">🍴</span> Forks</sub><br /><strong style="color: var(--m3-primary); font-size: 1.5rem; font-weight: 600;">0</strong></td><td align="center" style="background: var(--m3-surface-container); border-radius: var(--m3-shape-corner-medium); padding: 12px 16px; min-width: 110px;"><sub style="color: var(--m3-on-surface-variant); font-size: 12px;"><span style="color: #4ECDC4;">📦</span> Repos</sub><br /><strong style="color: var(--m3-primary); font-size: 1.5rem; font-weight: 600;">10</strong></td><td align="center" style="background: var(--m3-surface-container); border-radius: var(--m3-shape-corner-medium); padding: 12px 16px; min-width: 110px;"><sub style="color: var(--m3-on-surface-variant); font-size: 12px;"><span style="color: #98D8C8;">👥</span> Followers</sub><br /><strong style="color: var(--m3-primary); font-size: 1.5rem; font-weight: 600;">0</strong></td></tr>
<tr><td align="center" style="background: var(--m3-surface-container); border-radius: var(--m3-shape-corner-medium); padding: 12px 16px; min-width: 110px;"><sub style="color: var(--m3-on-surface-variant); font-size: 12px;"><span style="color: #F7DC6F;">👤</span> Following</sub><br /><strong style="color: var(--m3-primary); font-size: 1.5rem; font-weight: 600;">0</strong></td><td></td><td></td><td></td></tr>
</table>

---

## 🛠 Tech Stack

![Dart](https://img.shields.io/badge?label=Dart&message=39.6%25&color=0175C2&style=for-the-badge&logoColor=white&logo=dart) ![Rust](https://img.shields.io/badge?label=Rust&message=33.8%25&color=DEA584&style=for-the-badge&logoColor=white&logo=rust) ![JavaScript](https://img.shields.io/badge?label=JavaScript&message=8.5%25&color=F7DF1E&style=for-the-badge&logoColor=white&logo=javascript) ![CSS](https://img.shields.io/badge?label=CSS&message=4.6%25&color=1572B6&style=for-the-badge&logoColor=white) ![HTML](https://img.shields.io/badge?label=HTML&message=3.7%25&color=E34F26&style=for-the-badge&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge?label=Jupyter+Notebook&message=3.0%25&color=666666&style=for-the-badge&logoColor=white) ![Python](https://img.shields.io/badge?label=Python&message=2.5%25&color=3776AB&style=for-the-badge&logoColor=white&logo=python) ![C++](https://img.shields.io/badge?label=C%2B%2B&message=1.8%25&color=00599C&style=for-the-badge&logoColor=white&logo=cplusplus) ![CMake](https://img.shields.io/badge?label=CMake&message=1.6%25&color=666666&style=for-the-badge&logoColor=white)

---

## 🚀 Featured Projects

| Project | Language | Topics | ⭐ | 🍴 |
| --- | --- | --- | --- | --- |
| [ytdlp](https://github.com/ibro-3/ytdlp)<br><sub style="color: var(--m3-on-surface-variant);">Flutter app that downloads media from 1000+ sites via bundled yt-dlp and ffmpeg</sub> | ![Dart](https://img.shields.io/badge/Dart-00B4AB?style=flat&logo=dart&logoColor=white) | ![dart](https://img.shields.io/badge/dart-C1B4E4?style=flat&logoColor=white) ![downloader](https://img.shields.io/badge/downloader-C1B4E4?style=flat&logoColor=white) ![flutter](https://img.shields.io/badge/flutter-C1B4E4?style=flat&logoColor=white) ![yt-dlp](https://img.shields.io/badge/yt-dlp-C1B4E4?style=flat&logoColor=white) | 1 | 0 |

---

## 📅 Contribution Graph

**Total contributions this year: 113**

<svg width="800" height="150" viewBox="0 0 782 138" xmlns="http://www.w3.org/2000/svg" style="background: var(--m3-surface); border-radius: var(--m3-shape-corner-medium);"><text x="40" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Jan</text><text x="110" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Feb</text><text x="166" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Mar</text><text x="236" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Apr</text><text x="292" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">May</text><text x="362" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Jun</text><text x="418" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Jul</text><text x="474" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Aug</text><text x="544" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Sep</text><text x="600" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Oct</text><text x="656" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Nov</text><text x="726" y="20" font-family="var(--m3-font-family)" font-size="10" fill="var(--m3-on-surface-variant)" text-anchor="middle">Dec</text><text x="15" y="49" font-family="var(--m3-font-family)" font-size="9" fill="var(--m3-on-surface-variant)" text-anchor="end" dominant-baseline="middle">Mon</text><text x="15" y="77" font-family="var(--m3-font-family)" font-size="9" fill="var(--m3-on-surface-variant)" text-anchor="end" dominant-baseline="middle">Wed</text><text x="15" y="105" font-family="var(--m3-font-family)" font-size="9" fill="var(--m3-on-surface-variant)" text-anchor="end" dominant-baseline="middle">Fri</text><text x="15" y="133" font-family="var(--m3-font-family)" font-size="9" fill="var(--m3-on-surface-variant)" text-anchor="end" dominant-baseline="middle">Sun</text><rect x="40" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-01" data-count="0" /><rect x="40" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-02" data-count="0" /><rect x="40" y="68" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-01-03" data-count="3" /><rect x="54" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-04" data-count="1" /><rect x="54" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-05" data-count="0" /><rect x="54" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-06" data-count="0" /><rect x="54" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-07" data-count="0" /><rect x="54" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-08" data-count="0" /><rect x="54" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-09" data-count="0" /><rect x="54" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-10" data-count="0" /><rect x="68" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-11" data-count="0" /><rect x="68" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-12" data-count="0" /><rect x="68" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-13" data-count="0" /><rect x="68" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-14" data-count="0" /><rect x="68" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-15" data-count="0" /><rect x="68" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-16" data-count="0" /><rect x="68" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-17" data-count="0" /><rect x="82" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-18" data-count="0" /><rect x="82" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-19" data-count="0" /><rect x="82" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-20" data-count="0" /><rect x="82" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-21" data-count="0" /><rect x="82" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-22" data-count="0" /><rect x="82" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-23" data-count="0" /><rect x="82" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-24" data-count="0" /><rect x="96" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-25" data-count="0" /><rect x="96" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-26" data-count="0" /><rect x="96" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-27" data-count="0" /><rect x="96" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-28" data-count="0" /><rect x="96" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-29" data-count="0" /><rect x="96" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-30" data-count="0" /><rect x="96" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-01-31" data-count="0" /><rect x="110" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-01" data-count="0" /><rect x="110" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-02" data-count="0" /><rect x="110" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-03" data-count="0" /><rect x="110" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-04" data-count="0" /><rect x="110" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-05" data-count="0" /><rect x="110" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-06" data-count="0" /><rect x="110" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-07" data-count="0" /><rect x="124" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-08" data-count="0" /><rect x="124" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-09" data-count="0" /><rect x="124" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-10" data-count="0" /><rect x="124" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-11" data-count="0" /><rect x="124" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-12" data-count="0" /><rect x="124" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-13" data-count="0" /><rect x="124" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-14" data-count="0" /><rect x="138" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-15" data-count="0" /><rect x="138" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-16" data-count="0" /><rect x="138" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-17" data-count="0" /><rect x="138" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-18" data-count="0" /><rect x="138" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-19" data-count="0" /><rect x="138" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-20" data-count="0" /><rect x="138" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-21" data-count="0" /><rect x="152" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-22" data-count="0" /><rect x="152" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-23" data-count="0" /><rect x="152" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-24" data-count="0" /><rect x="152" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-25" data-count="0" /><rect x="152" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-26" data-count="0" /><rect x="152" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-27" data-count="0" /><rect x="152" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-02-28" data-count="0" /><rect x="166" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-01" data-count="0" /><rect x="166" y="54" width="12" height="12" rx="2" ry="2" fill="#3F51B5" data-date="2026-03-02" data-count="12" /><rect x="166" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-03" data-count="0" /><rect x="166" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-04" data-count="0" /><rect x="166" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-05" data-count="0" /><rect x="166" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-06" data-count="0" /><rect x="166" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-07" data-count="0" /><rect x="180" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-08" data-count="0" /><rect x="180" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-09" data-count="0" /><rect x="180" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-10" data-count="0" /><rect x="180" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-11" data-count="0" /><rect x="180" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-12" data-count="0" /><rect x="180" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-13" data-count="0" /><rect x="180" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-14" data-count="0" /><rect x="194" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-15" data-count="0" /><rect x="194" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-16" data-count="0" /><rect x="194" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-17" data-count="0" /><rect x="194" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-18" data-count="0" /><rect x="194" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-19" data-count="0" /><rect x="194" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-20" data-count="0" /><rect x="194" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-21" data-count="0" /><rect x="208" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-22" data-count="0" /><rect x="208" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-23" data-count="0" /><rect x="208" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-24" data-count="0" /><rect x="208" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-25" data-count="0" /><rect x="208" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-26" data-count="0" /><rect x="208" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-27" data-count="0" /><rect x="208" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-28" data-count="0" /><rect x="222" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-29" data-count="0" /><rect x="222" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-30" data-count="0" /><rect x="222" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-03-31" data-count="0" /><rect x="222" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-01" data-count="0" /><rect x="222" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-02" data-count="0" /><rect x="222" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-03" data-count="0" /><rect x="222" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-04" data-count="0" /><rect x="236" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-05" data-count="0" /><rect x="236" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-06" data-count="0" /><rect x="236" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-07" data-count="0" /><rect x="236" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-08" data-count="1" /><rect x="236" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-09" data-count="0" /><rect x="236" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-10" data-count="0" /><rect x="236" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-11" data-count="0" /><rect x="250" y="40" width="12" height="12" rx="2" ry="2" fill="#5C6BC0" data-date="2026-04-12" data-count="4" /><rect x="250" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-13" data-count="0" /><rect x="250" y="68" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-04-14" data-count="2" /><rect x="250" y="82" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-04-15" data-count="3" /><rect x="250" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-16" data-count="0" /><rect x="250" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-17" data-count="0" /><rect x="250" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-18" data-count="0" /><rect x="264" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-19" data-count="0" /><rect x="264" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-20" data-count="0" /><rect x="264" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-21" data-count="0" /><rect x="264" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-22" data-count="0" /><rect x="264" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-23" data-count="0" /><rect x="264" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-24" data-count="0" /><rect x="264" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-25" data-count="0" /><rect x="278" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-26" data-count="0" /><rect x="278" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-27" data-count="0" /><rect x="278" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-28" data-count="0" /><rect x="278" y="82" width="12" height="12" rx="2" ry="2" fill="#5C6BC0" data-date="2026-04-29" data-count="4" /><rect x="278" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-04-30" data-count="0" /><rect x="278" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-01" data-count="0" /><rect x="278" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-02" data-count="0" /><rect x="292" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-03" data-count="0" /><rect x="292" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-04" data-count="0" /><rect x="292" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-05" data-count="0" /><rect x="292" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-06" data-count="0" /><rect x="292" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-07" data-count="0" /><rect x="292" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-08" data-count="0" /><rect x="292" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-09" data-count="0" /><rect x="306" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-10" data-count="0" /><rect x="306" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-11" data-count="0" /><rect x="306" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-12" data-count="0" /><rect x="306" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-13" data-count="0" /><rect x="306" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-14" data-count="0" /><rect x="306" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-15" data-count="0" /><rect x="306" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-16" data-count="0" /><rect x="320" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-17" data-count="0" /><rect x="320" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-18" data-count="0" /><rect x="320" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-19" data-count="0" /><rect x="320" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-20" data-count="0" /><rect x="320" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-21" data-count="0" /><rect x="320" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-22" data-count="0" /><rect x="320" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-23" data-count="0" /><rect x="334" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-24" data-count="0" /><rect x="334" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-25" data-count="0" /><rect x="334" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-26" data-count="0" /><rect x="334" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-27" data-count="0" /><rect x="334" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-28" data-count="0" /><rect x="334" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-29" data-count="0" /><rect x="334" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-30" data-count="0" /><rect x="348" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-05-31" data-count="0" /><rect x="348" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-01" data-count="0" /><rect x="348" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-02" data-count="0" /><rect x="348" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-03" data-count="0" /><rect x="348" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-04" data-count="0" /><rect x="348" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-05" data-count="0" /><rect x="348" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-06" data-count="0" /><rect x="362" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-07" data-count="0" /><rect x="362" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-08" data-count="0" /><rect x="362" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-09" data-count="0" /><rect x="362" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-10" data-count="0" /><rect x="362" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-11" data-count="0" /><rect x="362" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-12" data-count="0" /><rect x="362" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-13" data-count="0" /><rect x="376" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-14" data-count="0" /><rect x="376" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-15" data-count="0" /><rect x="376" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-16" data-count="0" /><rect x="376" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-17" data-count="0" /><rect x="376" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-18" data-count="0" /><rect x="376" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-19" data-count="0" /><rect x="376" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-20" data-count="0" /><rect x="390" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-21" data-count="0" /><rect x="390" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-22" data-count="0" /><rect x="390" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-23" data-count="0" /><rect x="390" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-24" data-count="0" /><rect x="390" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-25" data-count="0" /><rect x="390" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-26" data-count="0" /><rect x="390" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-27" data-count="0" /><rect x="404" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-28" data-count="0" /><rect x="404" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-29" data-count="0" /><rect x="404" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-06-30" data-count="0" /><rect x="404" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-01" data-count="0" /><rect x="404" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-02" data-count="0" /><rect x="404" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-03" data-count="0" /><rect x="404" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-04" data-count="0" /><rect x="418" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-05" data-count="0" /><rect x="418" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-06" data-count="0" /><rect x="418" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-07" data-count="0" /><rect x="418" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-08" data-count="0" /><rect x="418" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-09" data-count="0" /><rect x="418" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-10" data-count="0" /><rect x="418" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-11" data-count="0" /><rect x="432" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-12" data-count="0" /><rect x="432" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-13" data-count="0" /><rect x="432" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-14" data-count="0" /><rect x="432" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-15" data-count="0" /><rect x="432" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-16" data-count="0" /><rect x="432" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-17" data-count="0" /><rect x="432" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-18" data-count="0" /><rect x="446" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-19" data-count="0" /><rect x="446" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-20" data-count="0" /><rect x="446" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-21" data-count="0" /><rect x="446" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-22" data-count="0" /><rect x="446" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-23" data-count="0" /><rect x="446" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-24" data-count="0" /><rect x="446" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-25" data-count="0" /><rect x="460" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-26" data-count="0" /><rect x="460" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-27" data-count="0" /><rect x="460" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-28" data-count="0" /><rect x="460" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-29" data-count="0" /><rect x="460" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-30" data-count="0" /><rect x="460" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-07-31" data-count="0" /><rect x="460" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-01" data-count="0" /><rect x="474" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-02" data-count="0" /><rect x="474" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-03" data-count="0" /><rect x="474" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-04" data-count="0" /><rect x="474" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-05" data-count="0" /><rect x="474" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-06" data-count="0" /><rect x="474" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-07" data-count="0" /><rect x="474" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-08" data-count="0" /><rect x="488" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-09" data-count="0" /><rect x="488" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-10" data-count="0" /><rect x="488" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-11" data-count="0" /><rect x="488" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-12" data-count="0" /><rect x="488" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-13" data-count="0" /><rect x="488" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-14" data-count="0" /><rect x="488" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-15" data-count="0" /><rect x="502" y="40" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-08-16" data-count="2" /><rect x="502" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-17" data-count="0" /><rect x="502" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-18" data-count="0" /><rect x="502" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-19" data-count="0" /><rect x="502" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-20" data-count="0" /><rect x="502" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-21" data-count="0" /><rect x="502" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-22" data-count="0" /><rect x="516" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-23" data-count="0" /><rect x="516" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-24" data-count="0" /><rect x="516" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-25" data-count="0" /><rect x="516" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-26" data-count="0" /><rect x="516" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-27" data-count="0" /><rect x="516" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-28" data-count="0" /><rect x="516" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-29" data-count="0" /><rect x="530" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-30" data-count="0" /><rect x="530" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-08-31" data-count="0" /><rect x="530" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-01" data-count="0" /><rect x="530" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-02" data-count="0" /><rect x="530" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-03" data-count="0" /><rect x="530" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-04" data-count="0" /><rect x="530" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-05" data-count="0" /><rect x="544" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-06" data-count="0" /><rect x="544" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-07" data-count="0" /><rect x="544" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-08" data-count="0" /><rect x="544" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-09" data-count="0" /><rect x="544" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-10" data-count="0" /><rect x="544" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-11" data-count="0" /><rect x="544" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-12" data-count="0" /><rect x="558" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-13" data-count="0" /><rect x="558" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-14" data-count="0" /><rect x="558" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-15" data-count="0" /><rect x="558" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-16" data-count="0" /><rect x="558" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-17" data-count="0" /><rect x="558" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-18" data-count="0" /><rect x="558" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-19" data-count="0" /><rect x="572" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-20" data-count="0" /><rect x="572" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-21" data-count="0" /><rect x="572" y="68" width="12" height="12" rx="2" ry="2" fill="#3F51B5" data-date="2026-09-22" data-count="9" /><rect x="572" y="82" width="12" height="12" rx="2" ry="2" fill="#5C6BC0" data-date="2026-09-23" data-count="5" /><rect x="572" y="96" width="12" height="12" rx="2" ry="2" fill="#3F51B5" data-date="2026-09-24" data-count="25" /><rect x="572" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-25" data-count="0" /><rect x="572" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-26" data-count="0" /><rect x="586" y="40" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-09-27" data-count="2" /><rect x="586" y="54" width="12" height="12" rx="2" ry="2" fill="#5C6BC0" data-date="2026-09-28" data-count="5" /><rect x="586" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-29" data-count="0" /><rect x="586" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-09-30" data-count="1" /><rect x="586" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-01" data-count="0" /><rect x="586" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-02" data-count="0" /><rect x="586" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-03" data-count="0" /><rect x="600" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-04" data-count="0" /><rect x="600" y="54" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-05" data-count="2" /><rect x="600" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-06" data-count="1" /><rect x="600" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-07" data-count="0" /><rect x="600" y="96" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-08" data-count="2" /><rect x="600" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-09" data-count="0" /><rect x="600" y="124" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-10" data-count="2" /><rect x="614" y="40" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-11" data-count="3" /><rect x="614" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-12" data-count="0" /><rect x="614" y="68" width="12" height="12" rx="2" ry="2" fill="#5C6BC0" data-date="2026-10-13" data-count="4" /><rect x="614" y="82" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-14" data-count="3" /><rect x="614" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-15" data-count="0" /><rect x="614" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-16" data-count="0" /><rect x="614" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-17" data-count="0" /><rect x="628" y="40" width="12" height="12" rx="2" ry="2" fill="#3F51B5" data-date="2026-10-18" data-count="7" /><rect x="628" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-19" data-count="0" /><rect x="628" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-20" data-count="0" /><rect x="628" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-21" data-count="0" /><rect x="628" y="96" width="12" height="12" rx="2" ry="2" fill="#5C6BC0" data-date="2026-10-22" data-count="4" /><rect x="628" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-23" data-count="1" /><rect x="628" y="124" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-24" data-count="3" /><rect x="642" y="40" width="12" height="12" rx="2" ry="2" fill="#9FA8DA" data-date="2026-10-25" data-count="2" /><rect x="642" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-26" data-count="0" /><rect x="642" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-27" data-count="0" /><rect x="642" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-28" data-count="0" /><rect x="642" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-29" data-count="0" /><rect x="642" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-30" data-count="0" /><rect x="642" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-10-31" data-count="0" /><rect x="656" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-01" data-count="0" /><rect x="656" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-02" data-count="0" /><rect x="656" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-03" data-count="0" /><rect x="656" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-04" data-count="0" /><rect x="656" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-05" data-count="0" /><rect x="656" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-06" data-count="0" /><rect x="656" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-07" data-count="0" /><rect x="670" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-08" data-count="0" /><rect x="670" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-09" data-count="0" /><rect x="670" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-10" data-count="0" /><rect x="670" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-11" data-count="0" /><rect x="670" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-12" data-count="0" /><rect x="670" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-13" data-count="0" /><rect x="670" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-14" data-count="0" /><rect x="684" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-15" data-count="0" /><rect x="684" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-16" data-count="0" /><rect x="684" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-17" data-count="0" /><rect x="684" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-18" data-count="0" /><rect x="684" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-19" data-count="0" /><rect x="684" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-20" data-count="0" /><rect x="684" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-21" data-count="0" /><rect x="698" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-22" data-count="0" /><rect x="698" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-23" data-count="0" /><rect x="698" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-24" data-count="0" /><rect x="698" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-25" data-count="0" /><rect x="698" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-26" data-count="0" /><rect x="698" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-27" data-count="0" /><rect x="698" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-28" data-count="0" /><rect x="712" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-29" data-count="0" /><rect x="712" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-11-30" data-count="0" /><rect x="712" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-01" data-count="0" /><rect x="712" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-02" data-count="0" /><rect x="712" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-03" data-count="0" /><rect x="712" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-04" data-count="0" /><rect x="712" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-05" data-count="0" /><rect x="726" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-06" data-count="0" /><rect x="726" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-07" data-count="0" /><rect x="726" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-08" data-count="0" /><rect x="726" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-09" data-count="0" /><rect x="726" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-10" data-count="0" /><rect x="726" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-11" data-count="0" /><rect x="726" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-12" data-count="0" /><rect x="740" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-13" data-count="0" /><rect x="740" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-14" data-count="0" /><rect x="740" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-15" data-count="0" /><rect x="740" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-16" data-count="0" /><rect x="740" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-17" data-count="0" /><rect x="740" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-18" data-count="0" /><rect x="740" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-19" data-count="0" /><rect x="754" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-20" data-count="0" /><rect x="754" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-21" data-count="0" /><rect x="754" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-22" data-count="0" /><rect x="754" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-23" data-count="0" /><rect x="754" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-24" data-count="0" /><rect x="754" y="110" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-25" data-count="0" /><rect x="754" y="124" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-26" data-count="0" /><rect x="768" y="40" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-27" data-count="0" /><rect x="768" y="54" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-28" data-count="0" /><rect x="768" y="68" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-29" data-count="0" /><rect x="768" y="82" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-30" data-count="0" /><rect x="768" y="96" width="12" height="12" rx="2" ry="2" fill="#E8EAF6" data-date="2026-12-31" data-count="0" /></svg>

<div style="display: flex; align-items: center; gap: 0.5rem; flex-wrap: wrap; margin-top: 1rem;"><span style="color: var(--m3-on-surface-variant); font-size: 0.75rem;">Less</span><span style="width: 12px; height: 12px; background: #E8EAF6; border-radius: 2px; display: inline-block; margin: 0 2px;"></span><span style="width: 12px; height: 12px; background: #9FA8DA; border-radius: 2px; display: inline-block; margin: 0 2px;"></span><span style="width: 12px; height: 12px; background: #5C6BC0; border-radius: 2px; display: inline-block; margin: 0 2px;"></span><span style="width: 12px; height: 12px; background: #3F51B5; border-radius: 2px; display: inline-block; margin: 0 2px;"></span><span style="width: 12px; height: 12px; background: #283593; border-radius: 2px; display: inline-block; margin: 0 2px;"></span><span style="color: var(--m3-on-surface-variant); font-size: 0.75rem; margin-left: 0.5rem;">More</span></div>

---

## 🏷 Profile Badges

[![Github: ibro-3](https://img.shields.io/badge?label=Github&message=ibro-3&color=181717&logo=github&style=for-the-badge&logoColor=white)](https://github.com/ibro-3) ![Account Age: 2 years](https://img.shields.io/badge?label=Account+Age&message=2+years&color=C1B4E4&logo=calendar&style=for-the-badge&logoColor=white)

## 📦 Repository Badges

[![ytdlp: Flutter app that downloads…](https://img.shields.io/badge?label=ytdlp&message=Flutter+app+that+downloads%E2%80%A6&color=C1B4E4&style=for-the-badge&logoColor=white)](https://github.com/ibro-3/ytdlp) ![Stars: 1](https://img.shields.io/badge?label=Stars&message=1&color=FFD700&logo=star&style=for-the-badge&logoColor=white) ![Forks: 0](https://img.shields.io/badge?label=Forks&message=0&color=FF6B6B&logo=git-branch&style=for-the-badge&logoColor=white) ![Dart](https://img.shields.io/badge?message=Dart&color=0175C2&logo=dart&style=for-the-badge&logoColor=white) ![dart](https://img.shields.io/badge?message=dart&color=D0C4D4&style=for-the-badge&logoColor=white) ![downloader](https://img.shields.io/badge?message=downloader&color=D0C4D4&style=for-the-badge&logoColor=white) ![flutter](https://img.shields.io/badge?message=flutter&color=D0C4D4&style=for-the-badge&logoColor=white)

[![mailin: No description](https://img.shields.io/badge?label=mailin&message=No+description&color=C1B4E4&style=for-the-badge&logoColor=white)](https://github.com/ibro-3/mailin) ![Stars: 0](https://img.shields.io/badge?label=Stars&message=0&color=FFD700&logo=star&style=for-the-badge&logoColor=white) ![Forks: 0](https://img.shields.io/badge?label=Forks&message=0&color=FF6B6B&logo=git-branch&style=for-the-badge&logoColor=white) ![Rust](https://img.shields.io/badge?message=Rust&color=DEA584&logo=rust&style=for-the-badge&logoColor=white) ![License: Apache-2.0](https://img.shields.io/badge?label=License&message=Apache-2.0&color=00ADD8&logo=open-source-initiative&style=for-the-badge&logoColor=white)

[![ibro-3: Personal GitHub profile and…](https://img.shields.io/badge?label=ibro-3&message=Personal+GitHub+profile+and%E2%80%A6&color=C1B4E4&style=for-the-badge&logoColor=white)](https://github.com/ibro-3/ibro-3) ![Stars: 0](https://img.shields.io/badge?label=Stars&message=0&color=FFD700&logo=star&style=for-the-badge&logoColor=white) ![Forks: 0](https://img.shields.io/badge?label=Forks&message=0&color=FF6B6B&logo=git-branch&style=for-the-badge&logoColor=white)

[![musicpl: Flutter music player with…](https://img.shields.io/badge?label=musicpl&message=Flutter+music+player+with%E2%80%A6&color=C1B4E4&style=for-the-badge&logoColor=white)](https://github.com/ibro-3/musicpl) ![Stars: 0](https://img.shields.io/badge?label=Stars&message=0&color=FFD700&logo=star&style=for-the-badge&logoColor=white) ![Forks: 0](https://img.shields.io/badge?label=Forks&message=0&color=FF6B6B&logo=git-branch&style=for-the-badge&logoColor=white) ![HTML](https://img.shields.io/badge?message=HTML&color=E34F26&style=for-the-badge&logoColor=white) ![audio](https://img.shields.io/badge?message=audio&color=D0C4D4&style=for-the-badge&logoColor=white) ![flutter](https://img.shields.io/badge?message=flutter&color=D0C4D4&style=for-the-badge&logoColor=white) ![music-player](https://img.shields.io/badge?message=music-player&color=D0C4D4&style=for-the-badge&logoColor=white)

[![tasks: Flutter todo app with smart…](https://img.shields.io/badge?label=tasks&message=Flutter+todo+app+with+smart%E2%80%A6&color=C1B4E4&style=for-the-badge&logoColor=white)](https://github.com/ibro-3/tasks) ![Stars: 0](https://img.shields.io/badge?label=Stars&message=0&color=FFD700&logo=star&style=for-the-badge&logoColor=white) ![Forks: 0](https://img.shields.io/badge?label=Forks&message=0&color=FF6B6B&logo=git-branch&style=for-the-badge&logoColor=white) ![Dart](https://img.shields.io/badge?message=Dart&color=0175C2&logo=dart&style=for-the-badge&logoColor=white) ![dart](https://img.shields.io/badge?message=dart&color=D0C4D4&style=for-the-badge&logoColor=white) ![flutter](https://img.shields.io/badge?message=flutter&color=D0C4D4&style=for-the-badge&logoColor=white) ![notifications](https://img.shields.io/badge?message=notifications&color=D0C4D4&style=for-the-badge&logoColor=white)

---


<div align="center">
  <sub>Generated with 💜 using <a href="https://github.com/ibro/material3-readme-gen">material3-readme-gen</a></sub>
</div>
