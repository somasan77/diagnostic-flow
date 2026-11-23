<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default">
  <meta name="apple-mobile-web-app-title" content="臨床ポケット">
  <meta name="theme-color" content="#0284c7">
  <title>臨床ポケットツール</title>
  <!-- インラインSVGファビコン（外部ファイル不要） -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='16' fill='%230284c7'/%3E%3Cpath d='M28 16h8v12h12v8H36v12h-8V36H16v-8h12V16z' fill='%23ffffff'/%3E%3C/svg%3E">
  <style>
    /* =========================================================
       CSS Design Tokens & Base Styles (Pure CSS / Offline Ready)
       ========================================================= */
    :root {
      --bg-page: #f1f5f9;
      --bg-card: #ffffff;
      --bg-subtle: #f8fafc;
      --bg-accent-soft: #e0f2fe;
      --primary: #0284c7;
      --primary-dark: #0369a1;
      --primary-border: #bae6fd;
      --text-main: #0f172a;
      --text-secondary: #475569;
      --text-muted: #64748b;
      --border: #e2e8f0;
      --border-strong: #cbd5e1;

      /* Status Colors */
      --green-bg: #dcfce7;
      --green-text: #166534;
      --green-border: #86efac;
      --lime-bg: #ecfccb;
      --lime-text: #3f6212;
      --yellow-bg: #fef9c3;
      --yellow-text: #854d0e;
      --orange-bg: #ffedd5;
      --orange-text: #9a3412;
      --red-bg: #fee2e2;
      --red-text: #991b1b;
      --red-border: #fca5a5;
      --purple-bg: #f3e8ff;
      --purple-text: #6b21a8;

      --radius-sm: 10px;
      --radius-md: 14px;
      --radius-lg: 18px;
      --shadow-sm: 0 1px 3px rgba(15, 23, 42, 0.06), 0 1px 2px rgba(15, 23, 42, 0.04);
      --shadow-md: 0 4px 12px rgba(15, 23, 42, 0.07);
      --nav-height: 68px;
      --header-height: 58px;
    }

    *, *::before, *::after {
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
    }

    html, body {
      margin: 0;
      padding: 0;
      background-color: var(--bg-page);
      color: var(--text-main);
      font-family: -apple-system, BlinkMacSystemFont, "Hiragino Sans", "Hiragino Kaku Gothic ProN", "Yu Gothic", "Meiryo", sans-serif;
      font-size: 15px;
      line-height: 1.55;
      -webkit-font-smoothing: antialiased;
      overflow-x: hidden;
    }

    /* =========================================================
       Header & Update Banner
       ========================================================= */
    .app-header {
      position: sticky;
      top: 0;
      z-index: 50;
      background: rgba(255, 255, 255, 0.94);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--border);
      padding-top: env(safe-area-inset-top);
    }

    .header-inner {
      max-width: 680px;
      margin: 0 auto;
      height: var(--header-height);
      padding: 0 16px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      min-width: 0;
    }

    .brand-icon {
      width: 32px;
      height: 32px;
      border-radius: 9px;
      background: linear-gradient(135deg, #0284c7, #0369a1);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      flex-shrink: 0;
      box-shadow: 0 2px 6px rgba(2, 132, 199, 0.3);
    }

    .brand-title-wrap {
      display: flex;
      align-items: baseline;
      gap: 6px;
      flex-wrap: wrap;
    }

    .brand-title {
      font-size: 1.05rem;
      font-weight: 700;
      letter-spacing: -0.01em;
      margin: 0;
      color: var(--text-main);
    }

    .version-badge {
      font-size: 0.7rem;
      font-weight: 600;
      color: var(--primary-dark);
      background: var(--bg-accent-soft);
      padding: 2px 7px;
      border-radius: 999px;
    }

    .update-btn {
      display: inline-flex;
      align-items: center;
      gap: 5px;
      background: var(--bg-subtle);
      border: 1px solid var(--border);
      color: var(--text-secondary);
      font-size: 0.78rem;
      font-weight: 600;
      padding: 7px 11px;
      border-radius: 999px;
      cursor: pointer;
      transition: background 0.15s, border-color 0.15s, color 0.15s;
      white-space: nowrap;
    }

    .update-btn:active {
      background: var(--bg-accent-soft);
      border-color: var(--primary-border);
      color: var(--primary-dark);
    }

    .status-dot {
      width: 7px;
      height: 7px;
      border-radius: 50%;
      background: #22c55e;
      display: inline-block;
    }

    .status-dot.offline {
      background: #94a3b8;
    }

    .update-banner {
      display: none;
      background: #0c4a6e;
      color: #ffffff;
      padding: 10px 16px;
    }

    .update-banner.visible {
      display: block;
    }

    .update-banner-inner {
      max-width: 680px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      font-size: 0.85rem;
    }

    .update-banner-btn {
      background: #38bdf8;
      color: #082f49;
      border: none;
      border-radius: 8px;
      padding: 6px 12px;
      font-weight: 700;
      font-size: 0.8rem;
      cursor: pointer;
      white-space: nowrap;
    }

    /* =========================================================
       Main Container & Sections
       ========================================================= */
    .main-container {
      max-width: 680px;
      margin: 0 auto;
      padding: 16px 14px calc(var(--nav-height) + env(safe-area-inset-bottom) + 24px);
    }

    .tab-panel {
      display: none;
      animation: fadeIn 0.18s ease-out;
    }

    .tab-panel.active {
      display: block;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(4px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .section-header {
      margin-bottom: 14px;
    }

    .section-title {
      font-size: 1.18rem;
      font-weight: 700;
      margin: 0 0 4px;
      color: var(--text-main);
    }

    .section-subtitle {
      font-size: 0.82rem;
      color: var(--text-muted);
      margin: 0;
    }

    /* =========================================================
       Cards & Form Controls
       ========================================================= */
    .card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius-lg);
      padding: 18px 16px;
      box-shadow: var(--shadow-sm);
      margin-bottom: 14px;
    }

    .card-title {
      font-size: 0.95rem;
      font-weight: 700;
      margin: 0 0 12px;
      color: var(--text-main);
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .form-group {
      margin-bottom: 14px;
    }

    .form-group:last-child {
      margin-bottom: 0;
    }

    .form-label {
      display: flex;
      align-items: center;
      justify-content: space-between;
      font-size: 0.84rem;
      font-weight: 600;
      color: var(--text-secondary);
      margin-bottom: 6px;
    }

    .form-grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .form-grid-3 {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
    }

    .input-wrap {
      position: relative;
      display: flex;
      align-items: center;
    }

    .num-input {
      width: 100%;
      height: 48px;
      padding: 0 48px 0 14px;
      font-size: 1.05rem;
      font-weight: 600;
      color: var(--text-main);
      background: var(--bg-subtle);
      border: 1.5px solid var(--border);
      border-radius: var(--radius-sm);
      outline: none;
      transition: border-color 0.15s, background 0.15s, box-shadow 0.15s;
      appearance: textfield;
      -moz-appearance: textfield;
    }

    .num-input::-webkit-outer-spin-button,
    .num-input::-webkit-inner-spin-button {
      -webkit-appearance: none;
      margin: 0;
    }

    .num-input:focus {
      background: #ffffff;
      border-color: var(--primary);
      box-shadow: 0 0 0 3px rgba(2, 132, 199, 0.15);
    }

    .input-unit {
      position: absolute;
      right: 12px;
      font-size: 0.78rem;
      font-weight: 600;
      color: var(--text-muted);
      pointer-events: none;
    }

    .num-input.compact {
      padding-right: 10px;
      font-size: 0.98rem;
    }

    /* Segmented Toggle */
    .toggle-group {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 8px;
      background: var(--bg-subtle);
      padding: 4px;
      border-radius: var(--radius-sm);
      border: 1px solid var(--border);
    }

    .toggle-btn {
      height: 42px;
      border: none;
      border-radius: 8px;
      background: transparent;
      color: var(--text-secondary);
      font-size: 0.92rem;
      font-weight: 700;
      cursor: pointer;
      transition: all 0.15s ease;
    }

    .toggle-btn.active {
      background: var(--primary);
      color: #ffffff;
      box-shadow: 0 2px 6px rgba(2, 132, 199, 0.25);
    }

    .preset-pills {
      display: flex;
      gap: 6px;
    }

    .preset-pill {
      border: 1px solid var(--border-strong);
      background: #ffffff;
      color: var(--text-secondary);
      font-size: 0.74rem;
      font-weight: 600;
      padding: 4px 10px;
      border-radius: 999px;
      cursor: pointer;
      transition: all 0.15s;
    }

    .preset-pill.active {
      background: var(--bg-accent-soft);
      border-color: var(--primary);
      color: var(--primary-dark);
    }

    /* Action Buttons */
    .btn-row {
      display: flex;
      gap: 10px;
      margin-top: 14px;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      min-height: 46px;
      padding: 0 16px;
      border-radius: var(--radius-sm);
      font-size: 0.92rem;
      font-weight: 700;
      cursor: pointer;
      border: 1px solid transparent;
      transition: transform 0.08s, background 0.15s, border-color 0.15s;
    }

    .btn:active {
      transform: scale(0.98);
    }

    .btn-secondary {
      background: var(--bg-subtle);
      border-color: var(--border-strong);
      color: var(--text-secondary);
      width: 100%;
    }

    .btn-secondary:active {
      background: #e2e8f0;
    }

    /* =========================================================
       Result Display Boxes
       ========================================================= */
    .result-card {
      background: linear-gradient(180deg, #f8fbff 0%, #ffffff 100%);
      border: 1.5px solid var(--primary-border);
      border-radius: var(--radius-lg);
      padding: 18px 16px;
      margin-bottom: 14px;
      box-shadow: var(--shadow-sm);
    }

    .result-primary-label {
      font-size: 0.82rem;
      font-weight: 700;
      color: var(--primary-dark);
      margin-bottom: 4px;
    }

    .result-primary-value {
      display: flex;
      align-items: baseline;
      gap: 8px;
      flex-wrap: wrap;
    }

    .result-number {
      font-size: 2.35rem;
      font-weight: 800;
      line-height: 1.1;
      letter-spacing: -0.02em;
      color: var(--text-main);
    }

    .result-unit {
      font-size: 0.92rem;
      font-weight: 600;
      color: var(--text-muted);
    }

    .result-divider {
      height: 1px;
      background: var(--border);
      margin: 14px 0;
    }

    .result-sub-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
      flex-wrap: wrap;
    }

    .result-sub-val {
      font-size: 1.25rem;
      font-weight: 700;
      color: var(--text-main);
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 5px;
      padding: 5px 11px;
      border-radius: 999px;
      font-size: 0.8rem;
      font-weight: 700;
      line-height: 1.2;
    }

    .badge-g1 { background: var(--green-bg); color: var(--green-text); }
    .badge-g2 { background: var(--lime-bg); color: var(--lime-text); }
    .badge-g3a { background: var(--yellow-bg); color: var(--yellow-text); }
    .badge-g3b { background: var(--orange-bg); color: var(--orange-text); }
    .badge-g4 { background: var(--red-bg); color: var(--red-text); }
    .badge-g5 { background: var(--purple-bg); color: var(--purple-text); }
    .badge-neutral { background: #e2e8f0; color: #334155; }

    .result-interpretation {
      margin-top: 12px;
      padding: 12px 14px;
      border-radius: var(--radius-sm);
      font-size: 0.86rem;
      line-height: 1.55;
      background: var(--bg-subtle);
      border: 1px solid var(--border);
      color: var(--text-secondary);
    }

    .result-interpretation.good {
      background: var(--green-bg);
      border-color: var(--green-border);
      color: var(--green-text);
    }

    .result-interpretation.warn {
      background: var(--orange-bg);
      border-color: #fdba74;
      color: var(--orange-text);
    }

    .calc-steps {
      margin-top: 12px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 8px;
    }

    .calc-step-box {
      background: var(--bg-subtle);
      border: 1px solid var(--border);
      border-radius: var(--radius-sm);
      padding: 9px 11px;
    }

    .calc-step-label {
      font-size: 0.72rem;
      color: var(--text-muted);
      font-weight: 600;
    }

    .calc-step-val {
      font-size: 0.98rem;
      font-weight: 700;
      color: var(--text-main);
      margin-top: 2px;
    }

    /* Collapsible Notes */
    details.note-accordion {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius-md);
      margin-bottom: 14px;
      overflow: hidden;
    }

    details.note-accordion summary {
      padding: 13px 16px;
      font-size: 0.86rem;
      font-weight: 700;
      color: var(--text-secondary);
      cursor: pointer;
      list-style: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    details.note-accordion summary::-webkit-details-marker {
      display: none;
    }

    details.note-accordion summary::after {
      content: "＋";
      font-size: 1rem;
      color: var(--primary);
      font-weight: 700;
    }

    details.note-accordion[open] summary::after {
      content: "－";
    }

    .note-body {
      padding: 0 16px 14px;
      font-size: 0.83rem;
      color: var(--text-secondary);
      border-top: 1px solid var(--border);
      padding-top: 12px;
    }

    .note-body ul {
      margin: 6px 0 0;
      padding-left: 18px;
    }

    .note-body li {
      margin-bottom: 5px;
    }

    .formula-box {
      background: var(--bg-subtle);
      border-left: 3px solid var(--primary);
      padding: 8px 10px;
      border-radius: 0 8px 8px 0;
      font-size: 0.8rem;
      font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
      color: var(--text-main);
      margin: 6px 0 10px;
      overflow-x: auto;
    }

    /* =========================================================
       Diagnostic Wizard Styles
       ========================================================= */
    .wizard-controls {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 8px;
      margin-bottom: 12px;
    }

    .wizard-mini-btn {
      display: inline-flex;
      align-items: center;
      gap: 5px;
      min-height: 38px;
      padding: 0 12px;
      border-radius: 999px;
      border: 1px solid var(--border-strong);
      background: #ffffff;
      color: var(--text-secondary);
      font-size: 0.8rem;
      font-weight: 700;
      cursor: pointer;
    }

    .wizard-mini-btn:disabled {
      opacity: 0.4;
      cursor: not-allowed;
    }

    .wizard-mini-btn:not(:disabled):active {
      background: var(--bg-subtle);
    }

    .breadcrumbs {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 6px;
      margin-bottom: 12px;
      padding: 10px 12px;
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius-md);
      font-size: 0.76rem;
    }

    .crumb-item {
      background: var(--bg-accent-soft);
      color: var(--primary-dark);
      padding: 3px 8px;
      border-radius: 6px;
      font-weight: 600;
    }

    .crumb-sep {
      color: var(--text-muted);
      font-weight: 700;
    }

    .crumb-empty {
      color: var(--text-muted);
    }

    .wizard-step-badge {
      display: inline-block;
      font-size: 0.75rem;
      font-weight: 700;
      color: var(--primary-dark);
      background: var(--bg-accent-soft);
      padding: 3px 10px;
      border-radius: 999px;
      margin-bottom: 10px;
    }

    .wizard-question {
      font-size: 1.08rem;
      font-weight: 700;
      color: var(--text-main);
      margin: 0 0 8px;
      line-height: 1.45;
    }

    .wizard-hint {
      font-size: 0.82rem;
      color: var(--text-muted);
      margin: 0 0 16px;
    }

    .option-list {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .option-btn {
      width: 100%;
      text-align: left;
      padding: 15px 16px;
      min-height: 54px;
      background: #ffffff;
      border: 1.5px solid var(--border-strong);
      border-radius: var(--radius-md);
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      transition: all 0.14s ease;
    }

    .option-btn:active {
      background: var(--bg-accent-soft);
      border-color: var(--primary);
      transform: scale(0.99);
    }

    .option-main {
      font-size: 0.96rem;
      font-weight: 700;
      color: var(--text-main);
      display: block;
    }

    .option-sub {
      font-size: 0.78rem;
      color: var(--text-muted);
      display: block;
      margin-top: 2px;
    }

    .option-arrow {
      color: var(--primary);
      font-weight: 800;
      font-size: 1.1rem;
      flex-shrink: 0;
    }

    /* Diagnosis Result Card */
    .dx-card {
      background: #ffffff;
      border: 2px solid var(--primary);
      border-radius: var(--radius-lg);
      overflow: hidden;
      box-shadow: var(--shadow-md);
    }

    .dx-card.urgent {
      border-color: #dc2626;
    }

    .dx-header {
      background: var(--primary);
      color: #ffffff;
      padding: 14px 16px;
    }

    .dx-card.urgent .dx-header {
      background: #dc2626;
    }

    .dx-tag {
      font-size: 0.74rem;
      font-weight: 700;
      opacity: 0.9;
      text-transform: uppercase;
      letter-spacing: 0.04em;
    }

    .dx-title {
      font-size: 1.12rem;
      font-weight: 800;
      margin: 4px 0 0;
      line-height: 1.35;
    }

    .dx-body {
      padding: 16px;
    }

    .dx-section {
      margin-bottom: 14px;
    }

    .dx-section:last-child {
      margin-bottom: 0;
    }

    .dx-section-title {
      font-size: 0.86rem;
      font-weight: 700;
      color: var(--primary-dark);
      margin: 0 0 6px;
      padding-left: 8px;
      border-left: 3px solid var(--primary);
    }

    .dx-card.urgent .dx-section-title {
      color: #991b1b;
      border-left-color: #dc2626;
    }

    .dx-list {
      margin: 0;
      padding-left: 18px;
      font-size: 0.86rem;
      color: var(--text-main);
    }

    .dx-list li {
      margin-bottom: 5px;
    }

    .dx-callout {
      background: var(--bg-subtle);
      border: 1px solid var(--border);
      border-radius: var(--radius-sm);
      padding: 11px 12px;
      font-size: 0.83rem;
      color: var(--text-secondary);
      margin-top: 8px;
    }

    .dx-callout.warn {
      background: #fef2f2;
      border-color: var(--red-border);
      color: #991b1b;
    }

    .dx-callout.rx {
      background: #f0f9ff;
      border-color: var(--primary-border);
      color: #0c4a6e;
    }

    .dx-callout-title {
      font-weight: 700;
      margin-bottom: 4px;
      display: block;
    }

    .dx-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.8rem;
      margin-top: 8px;
    }

    .dx-table th, .dx-table td {
      border: 1px solid var(--border);
      padding: 6px 8px;
      text-align: left;
      vertical-align: top;
    }

    .dx-table th {
      background: var(--bg-subtle);
      color: var(--text-secondary);
      width: 28%;
      font-weight: 700;
    }

    /* Water Restriction Mini Tool */
    .water-result-box {
      margin-top: 12px;
      padding: 12px 14px;
      border-radius: var(--radius-sm);
      background: var(--bg-subtle);
      border: 1px solid var(--border);
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
      flex-wrap: wrap;
    }

    .water-ratio {
      font-size: 0.85rem;
      color: var(--text-secondary);
      font-weight: 600;
    }

    .water-guide {
      font-size: 1.05rem;
      font-weight: 800;
      color: var(--primary-dark);
    }

    .ref-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.8rem;
      margin-top: 10px;
    }

    .ref-table th, .ref-table td {
      border: 1px solid var(--border);
      padding: 6px 10px;
      text-align: center;
    }

    .ref-table th {
      background: #e2e8f0;
      color: var(--text-main);
      font-weight: 700;
    }

    .ref-table tr.highlight td {
      background: var(--bg-accent-soft);
      font-weight: 700;
      color: var(--primary-dark);
    }

    /* =========================================================
       Bottom Tab Navigation (Thumb-friendly Mobile First)
       ========================================================= */
    .bottom-nav {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      z-index: 60;
      background: rgba(255, 255, 255, 0.96);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-top: 1px solid var(--border);
      padding-bottom: env(safe-area-inset-bottom);
      box-shadow: 0 -2px 10px rgba(15, 23, 42, 0.05);
    }

    .bottom-nav-inner {
      max-width: 680px;
      margin: 0 auto;
      height: var(--nav-height);
      display: grid;
      grid-template-columns: repeat(4, 1fr);
    }

    .nav-item {
      border: none;
      background: transparent;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 4px;
      color: var(--text-muted);
      font-size: 0.72rem;
      font-weight: 700;
      cursor: pointer;
      padding: 6px 2px;
      position: relative;
      transition: color 0.15s;
    }

    .nav-item svg {
      width: 22px;
      height: 22px;
      stroke-width: 2;
    }

    .nav-item.active {
      color: var(--primary);
    }

    .nav-item.active::before {
      content: "";
      position: absolute;
      top: 0;
      left: 20%;
      right: 20%;
      height: 3px;
      border-radius: 0 0 4px 4px;
      background: var(--primary);
    }

    /* =========================================================
       Toast Notification (Replaces alert/confirm)
       ========================================================= */
    .toast {
      position: fixed;
      left: 50%;
      bottom: calc(var(--nav-height) + env(safe-area-inset-bottom) + 14px);
      transform: translateX(-50%) translateY(20px);
      background: #0f172a;
      color: #ffffff;
      padding: 10px 16px;
      border-radius: 999px;
      font-size: 0.82rem;
      font-weight: 600;
      box-shadow: 0 6px 18px rgba(15, 23, 42, 0.25);
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.2s, transform 0.2s;
      z-index: 100;
      max-width: 90vw;
      text-align: center;
    }

    .toast.show {
      opacity: 1;
      transform: translateX(-50%) translateY(0);
    }

    /* Small screen adjustments */
    @media (max-width: 360px) {
      .form-grid-3 {
        grid-template-columns: 1fr;
      }
      .result-number {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <!-- =========================================================
       Header
       ========================================================= -->
  <header class="app-header">
    <div class="header-inner">
      <div class="brand">
        <div class="brand-icon" aria-hidden="true">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.6" stroke-linecap="round">
            <path d="M12 5v14M5 12h14"/>
          </svg>
        </div>
        <div class="brand-title-wrap">
          <h1 class="brand-title">臨床ポケットツール</h1>
          <span class="version-badge" id="appVersion">v1.0.0</span>
        </div>
      </div>
      <button type="button" class="update-btn" id="checkUpdateBtn" aria-label="更新確認">
        <span class="status-dot" id="networkDot"></span>
        <span id="updateBtnLabel">更新確認</span>
      </button>
    </div>

    <!-- 新バージョン検知バナー -->
    <div class="update-banner" id="updateBanner" role="status">
      <div class="update-banner-inner">
        <span>新しいバージョンがあります。更新しますか？</span>
        <button type="button" class="update-banner-btn" id="applyUpdateBtn">今すぐ更新</button>
      </div>
    </div>
  </header>

  <!-- =========================================================
       Main Content Area
       ========================================================= -->
  <main class="main-container">

    <!-- ==================== TAB 1: Ccr計算 ==================== -->
    <section id="panel-ccr" class="tab-panel active" aria-label="クレアチニンクリアランス計算">
      <div class="section-header">
        <h2 class="section-title">クレアチニンクリアランス (Ccr)</h2>
        <p class="section-subtitle">Cockcroft-Gault式によるCcrおよび日本人eGFR推算</p>
      </div>

      <div class="card">
        <div class="form-group">
          <span class="form-label">性別</span>
          <div class="toggle-group" role="radiogroup" aria-label="性別">
            <button type="button" class="toggle-btn active" data-ccr-sex="male" aria-pressed="true">男性</button>
            <button type="button" class="toggle-btn" data-ccr-sex="female" aria-pressed="false">女性</button>
          </div>
        </div>

        <div class="form-grid-2 form-group">
          <div>
            <label class="form-label" for="ccr-age">年齢</label>
            <div class="input-wrap">
              <input id="ccr-age" class="num-input" type="number" inputmode="numeric" min="1" max="120" step="1" placeholder="例: 70">
              <span class="input-unit">歳</span>
            </div>
          </div>
          <div>
            <label class="form-label" for="ccr-weight">体重</label>
            <div class="input-wrap">
              <input id="ccr-weight" class="num-input" type="number" inputmode="decimal" min="1" max="300" step="0.1" placeholder="例: 60">
              <span class="input-unit">kg</span>
            </div>
          </div>
        </div>

        <div class="form-group">
          <label class="form-label" for="ccr-scr">血清クレアチニン値 (SCr)</label>
          <div class="input-wrap">
            <input id="ccr-scr" class="num-input" type="number" inputmode="decimal" min="0.01" max="30" step="0.01" placeholder="例: 1.10">
            <span class="input-unit">mg/dL</span>
          </div>
        </div>

        <div class="btn-row">
          <button type="button" class="btn btn-secondary" id="ccr-reset">入力をリセット</button>
        </div>
      </div>

      <!-- 計算結果カード -->
      <div class="result-card" aria-live="polite">
        <div class="result-primary-label">推算クレアチニンクリアランス (Ccr)</div>
        <div class="result-primary-value">
          <span class="result-number" id="ccr-result">--.-</span>
          <span class="result-unit">mL/min</span>
        </div>

        <div class="result-divider"></div>

        <div class="result-sub-row">
          <div>
            <div style="font-size:0.78rem; color:var(--text-muted); font-weight:600;">参考：日本人推算GFR (eGFR)</div>
            <div>
              <span class="result-sub-val" id="egfr-result">--.-</span>
              <span class="result-unit">mL/min/1.73m²</span>
            </div>
          </div>
          <span class="badge badge-neutral" id="ckd-badge">CKDステージ --</span>
        </div>
      </div>

      <!-- 計算式・臨床メモ -->
      <details class="note-accordion">
        <summary>計算式・臨床メモ</summary>
        <div class="note-body">
          <strong>Cockcroft-Gault式 (Ccr)</strong>
          <div class="formula-box">男性: ((140 - 年齢) × 体重) / (72 × SCr)<br>女性: 男性の式 × 0.85</div>
          <strong>日本人eGFR推算式</strong>
          <div class="formula-box">男性: 194 × SCr^(-1.094) × 年齢^(-0.287)<br>女性: 男性の式 × 0.739</div>
          <ul>
            <li><strong>薬剤投与量設計：</strong>添付文書上の腎機能別投与量（抗菌薬、DOACなど）はCcr（Cockcroft-Gault式）を基準としていることが多いため、体重を含めたCcr評価が重要です。</li>
            <li><strong>肥満患者：</strong>実測体重を用いるとCcrが過大評価されるため、理想体重（IBW）や補正体重の使用を検討します。</li>
            <li><strong>るい痩・高齢者：</strong>筋肉量低下によりSCrが低く出やすく、腎機能が過大評価される点に注意が必要です。</li>
            <li><strong>CKDステージ目安（eGFR）：</strong>G1(≧90), G2(60-89), G3a(45-59), G3b(30-44), G4(15-29), G5(&lt;15)。</li>
          </ul>
        </div>
      </details>
    </section>

    <!-- ==================== TAB 2: RPI計算 ==================== -->
    <section id="panel-rpi" class="tab-panel" aria-label="網状赤血球産生指数計算">
      <div class="section-header">
        <h2 class="section-title">RPI（網状赤血球産生指数）</h2>
        <p class="section-subtitle">貧血時の骨髄赤血球産生反応を評価</p>
      </div>

      <div class="card">
        <div class="form-grid-2 form-group">
          <div>
            <label class="form-label" for="rpi-retic">網状赤血球数</label>
            <div class="input-wrap">
              <input id="rpi-retic" class="num-input" type="number" inputmode="decimal" min="0" max="100" step="0.1" placeholder="例: 3.5">
              <span class="input-unit">%</span>
            </div>
          </div>
          <div>
            <label class="form-label" for="rpi-ht">患者ヘマトクリット (Ht)</label>
            <div class="input-wrap">
              <input id="rpi-ht" class="num-input" type="number" inputmode="decimal" min="1" max="80" step="0.1" placeholder="例: 25.0">
              <span class="input-unit">%</span>
            </div>
          </div>
        </div>

        <div class="form-group">
          <div class="form-label">
            <label for="rpi-ref-ht">基準Ht値</label>
            <div class="preset-pills">
              <button type="button" class="preset-pill active" data-ref-ht="45">男性 45%</button>
              <button type="button" class="preset-pill" data-ref-ht="40">女性 40%</button>
            </div>
          </div>
          <div class="input-wrap">
            <input id="rpi-ref-ht" class="num-input" type="number" inputmode="decimal" min="20" max="60" step="0.5" value="45">
            <span class="input-unit">%</span>
          </div>
        </div>

        <div class="btn-row">
          <button type="button" class="btn btn-secondary" id="rpi-reset">入力をリセット</button>
        </div>
      </div>

      <!-- RPI結果カード -->
      <div class="result-card" aria-live="polite">
        <div class="result-primary-label">網状赤血球産生指数 (RPI)</div>
        <div class="result-primary-value" style="justify-content: space-between;">
          <div>
            <span class="result-number" id="rpi-result">--.-</span>
          </div>
          <span class="badge badge-neutral" id="rpi-badge">判定待ち</span>
        </div>

        <div class="result-interpretation" id="rpi-interpretation">
          網状赤血球数(%)と患者Ht(%)を入力すると、骨髄反応の評価が表示されます。
        </div>

        <div class="calc-steps">
          <div class="calc-step-box">
            <div class="calc-step-label">補正網状赤血球数 (CRC)</div>
            <div class="calc-step-val" id="rpi-crc">-- %</div>
          </div>
          <div class="calc-step-box">
            <div class="calc-step-label">成熟時間係数 (自動判定)</div>
            <div class="calc-step-val" id="rpi-mf">-- 日</div>
          </div>
        </div>
      </div>

      <details class="note-accordion">
        <summary>計算式・成熟時間係数の基準</summary>
        <div class="note-body">
          <div class="formula-box">CRC = 網状赤血球(%) × (患者Ht / 基準Ht)<br>RPI = CRC / 成熟時間係数</div>
          <ul>
            <li><strong>成熟時間係数 (患者Ht別)：</strong><br>
              Ht ≧ 45%：1.0 ／ 35≦Ht&lt;45%：1.5 ／ 25≦Ht&lt;35%：2.0 ／ 15≦Ht&lt;25%：2.5 ／ Ht&lt;15%：3.0</li>
            <li><strong>RPI ≧ 2.0：</strong>骨髄の赤血球産生反応は良好（溶血性貧血、急性出血など）。</li>
            <li><strong>RPI &lt; 2.0：</strong>骨髄の赤血球産生低下・反応不良（鉄欠乏性貧血、巨赤芽球性貧血、再生不良性貧血、慢性疾患に伴う貧血など）。</li>
          </ul>
        </div>
      </details>
    </section>

    <!-- ==================== TAB 3: 低Naフロー ==================== -->
    <section id="panel-hypona" class="tab-panel" aria-label="低Na血症診断フロー">
      <div class="section-header">
        <h2 class="section-title">低Na血症 診断フロー</h2>
        <p class="section-subtitle">Verbalis JG, et al. Am J Med 2013 アルゴリズム準拠</p>
      </div>

      <!-- ウィザードコンテナ（JSで動的描画） -->
      <div id="wizard-hypona"></div>

      <!-- 水分制限の目安 計算ミニツール -->
      <div class="card" style="margin-top: 18px;">
        <h3 class="card-title">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#0284c7" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2.69l5.66 5.66a8 8 0 1 1-11.31 0z"/></svg>
          水分制限の目安 計算ツール
        </h3>
        <p style="font-size:0.78rem; color:var(--text-muted); margin:-6px 0 12px;">
          (尿Na + 尿K) / 血清Na の比から1日の水分摂取量目安を算出します。
        </p>

        <div class="form-grid-3">
          <div>
            <label class="form-label" for="water-una">尿Na (U<sub>Na</sub>)</label>
            <input id="water-una" class="num-input compact" type="number" inputmode="decimal" min="0" placeholder="mEq/L">
          </div>
          <div>
            <label class="form-label" for="water-uk">尿K (U<sub>K</sub>)</label>
            <input id="water-uk" class="num-input compact" type="number" inputmode="decimal" min="0" placeholder="mEq/L">
          </div>
          <div>
            <label class="form-label" for="water-sna">血清Na</label>
            <input id="water-sna" class="num-input compact" type="number" inputmode="decimal" min="1" placeholder="mEq/L">
          </div>
        </div>

        <div class="water-result-box" aria-live="polite">
          <div class="water-ratio">比：(U<sub>Na</sub>+U<sub>K</sub>)/血清Na = <strong id="water-ratio-val">--</strong></div>
          <div class="water-guide" id="water-guide-val">数値を入力</div>
        </div>

        <table class="ref-table">
          <thead>
            <tr>
              <th>(U<sub>Na</sub> + U<sub>K</sub>) / 血清Na</th>
              <th>水分摂取量の目安</th>
            </tr>
          </thead>
          <tbody>
            <tr id="water-row-gt">
              <td>&gt; 1</td>
              <td>&lt; 500 mL / 日</td>
            </tr>
            <tr id="water-row-eq">
              <td>= 1 <span style="font-size:0.72rem; color:var(--text-muted);">(目安 0.95〜1.05)</span></td>
              <td>500〜700 mL / 日</td>
            </tr>
            <tr id="water-row-lt">
              <td>&lt; 1</td>
              <td>1 L / 日</td>
            </tr>
          </tbody>
        </table>
      </div>
    </section>

    <!-- ==================== TAB 4: 低Kフロー ==================== -->
    <section id="panel-hypok" class="tab-panel" aria-label="低カリウム血症診断フロー">
      <div class="section-header">
        <h2 class="section-title">低カリウム血症 診断フロー</h2>
        <p class="section-subtitle">尿中K・酸塩基平衡・尿中Cl・血圧・ホルモンによる鑑別</p>
      </div>

      <!-- ウィザードコンテナ（JSで動的描画） -->
      <div id="wizard-hypok"></div>
    </section>

  </main>

  <!-- =========================================================
       Bottom Navigation Bar
       ========================================================= -->
  <nav class="bottom-nav" aria-label="メインナビゲーション">
    <div class="bottom-nav-inner">
      <button type="button" class="nav-item active" data-tab="panel-ccr" aria-current="page">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round">
          <rect x="4" y="2" width="16" height="20" rx="2"/>
          <line x1="8" y1="6" x2="16" y2="6"/>
          <line x1="8" y1="12" x2="10" y2="12"/>
          <line x1="14" y1="12" x2="16" y2="12"/>
          <line x1="8" y1="16" x2="10" y2="16"/>
          <line x1="14" y1="16" x2="16" y2="16"/>
        </svg>
        <span>Ccr計算</span>
      </button>

      <button type="button" class="nav-item" data-tab="panel-rpi">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="9"/>
          <circle cx="12" cy="12" r="4"/>
        </svg>
        <span>RPI計算</span>
      </button>

      <button type="button" class="nav-item" data-tab="panel-hypona">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round">
          <path d="M12 2.69l5.66 5.66a8 8 0 1 1-11.31 0z"/>
        </svg>
        <span>低Naフロー</span>
      </button>

      <button type="button" class="nav-item" data-tab="panel-hypok">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round">
          <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/>
        </svg>
        <span>低Kフロー</span>
      </button>
    </div>
  </nav>

  <!-- Toast Message -->
  <div id="toast" class="toast" role="status" aria-live="polite"></div>

  <!-- =========================================================
       Application JavaScript (Vanilla JS / Modular Flow Engine)
       ========================================================= -->
  <script>
    (function () {
      'use strict';

      const APP_VERSION = 'v1.0.0';

      /* ---------------------------------------------------------
         Utility: Toast Notification (Non-blocking, no alert())
         --------------------------------------------------------- */
      let toastTimer = null;
      function showToast(message) {
        const el = document.getElementById('toast');
        if (!el) return;
        el.textContent = message;
        el.classList.add('show');
        clearTimeout(toastTimer);
        toastTimer = setTimeout(() => {
          el.classList.remove('show');
        }, 2800);
      }

      /* ---------------------------------------------------------
         Navigation Tabs
         --------------------------------------------------------- */
      const navItems = document.querySelectorAll('.nav-item');
      const tabPanels = document.querySelectorAll('.tab-panel');

      navItems.forEach((btn) => {
        btn.addEventListener('click', () => {
          const targetId = btn.getAttribute('data-tab');
          navItems.forEach((item) => {
            item.classList.remove('active');
            item.removeAttribute('aria-current');
          });
          tabPanels.forEach((panel) => panel.classList.remove('active'));

          btn.classList.add('active');
          btn.setAttribute('aria-current', 'page');
          const targetPanel = document.getElementById(targetId);
          if (targetPanel) {
            targetPanel.classList.add('active');
            window.scrollTo({ top: 0, behavior: 'smooth' });
          }
        });
      });

      /* ---------------------------------------------------------
         Feature 1: Creatinine Clearance (Ccr) & Japanese eGFR
         --------------------------------------------------------- */
      let ccrSex = 'male';
      const ccrSexBtns = document.querySelectorAll('[data-ccr-sex]');
      const ccrAgeEl = document.getElementById('ccr-age');
      const ccrWeightEl = document.getElementById('ccr-weight');
      const ccrScrEl = document.getElementById('ccr-scr');
      const ccrResultEl = document.getElementById('ccr-result');
      const egfrResultEl = document.getElementById('egfr-result');
      const ckdBadgeEl = document.getElementById('ckd-badge');

      function getCkdStage(egfr) {
        if (egfr >= 90) return { label: 'G1 (正常または高値)', cls: 'badge-g1' };
        if (egfr >= 60) return { label: 'G2 (正常または軽度低下)', cls: 'badge-g2' };
        if (egfr >= 45) return { label: 'G3a (軽度〜中等度低下)', cls: 'badge-g3a' };
        if (egfr >= 30) return { label: 'G3b (中等度〜高度低下)', cls: 'badge-g3b' };
        if (egfr >= 15) return { label: 'G4 (高度低下)', cls: 'badge-g4' };
        return { label: 'G5 (末期腎不全)', cls: 'badge-g5' };
      }

      function calculateCcr() {
        const age = parseFloat(ccrAgeEl.value);
        const weight = parseFloat(ccrWeightEl.value);
        const scr = parseFloat(ccrScrEl.value);

        // Ccr計算（年齢・体重・SCrすべて正の値）
        if (age > 0 && age < 140 && weight > 0 && scr > 0) {
          let ccr = ((140 - age) * weight) / (72 * scr);
          if (ccrSex === 'female') ccr *= 0.85;
          ccrResultEl.textContent = ccr.toFixed(1);
        } else {
          ccrResultEl.textContent = '--.-';
        }

        // 参考eGFR計算（年齢・SCrが正の値）
        if (age > 0 && scr > 0) {
          let egfr = 194 * Math.pow(scr, -1.094) * Math.pow(age, -0.287);
          if (ccrSex === 'female') egfr *= 0.739;
          egfrResultEl.textContent = egfr.toFixed(1);

          const stage = getCkdStage(egfr);
          ckdBadgeEl.textContent = 'CKD ' + stage.label;
          ckdBadgeEl.className = 'badge ' + stage.cls;
        } else {
          egfrResultEl.textContent = '--.-';
          ckdBadgeEl.textContent = 'CKDステージ --';
          ckdBadgeEl.className = 'badge badge-neutral';
        }
      }

      ccrSexBtns.forEach((btn) => {
        btn.addEventListener('click', () => {
          ccrSex = btn.getAttribute('data-ccr-sex');
          ccrSexBtns.forEach((b) => {
            const isActive = b === btn;
            b.classList.toggle('active', isActive);
            b.setAttribute('aria-pressed', String(isActive));
          });
          calculateCcr();
        });
      });

      [ccrAgeEl, ccrWeightEl, ccrScrEl].forEach((input) => {
        input.addEventListener('input', calculateCcr);
      });

      document.getElementById('ccr-reset').addEventListener('click', () => {
        ccrAgeEl.value = '';
        ccrWeightEl.value = '';
        ccrScrEl.value = '';
        calculateCcr();
        showToast('Ccr入力をリセットしました');
      });

      /* ---------------------------------------------------------
         Feature 2: RPI (Reticulocyte Production Index)
         --------------------------------------------------------- */
      const rpiReticEl = document.getElementById('rpi-retic');
      const rpiHtEl = document.getElementById('rpi-ht');
      const rpiRefHtEl = document.getElementById('rpi-ref-ht');
      const rpiResultEl = document.getElementById('rpi-result');
      const rpiBadgeEl = document.getElementById('rpi-badge');
      const rpiInterpEl = document.getElementById('rpi-interpretation');
      const rpiCrcEl = document.getElementById('rpi-crc');
      const rpiMfEl = document.getElementById('rpi-mf');
      const refHtPills = document.querySelectorAll('[data-ref-ht]');

      function getMaturationFactor(ht) {
        if (ht >= 45) return 1.0;
        if (ht >= 35) return 1.5;
        if (ht >= 25) return 2.0;
        if (ht >= 15) return 2.5;
        return 3.0;
      }

      function calculateRpi() {
        const retic = parseFloat(rpiReticEl.value);
        const ht = parseFloat(rpiHtEl.value);
        const refHt = parseFloat(rpiRefHtEl.value);

        if (retic >= 0 && !isNaN(retic) && ht > 0 && refHt > 0) {
          const crc = retic * (ht / refHt);
          const mf = getMaturationFactor(ht);
          const rpi = crc / mf;

          rpiResultEl.textContent = rpi.toFixed(2);
          rpiCrcEl.textContent = crc.toFixed(2) + ' %';
          rpiMfEl.textContent = mf.toFixed(1) + ' 日';

          if (rpi >= 2.0) {
            rpiBadgeEl.textContent = 'RPI ≧ 2.0：産生反応良好';
            rpiBadgeEl.className = 'badge badge-g1';
            rpiInterpEl.className = 'result-interpretation good';
            rpiInterpEl.innerHTML =
              '<strong>骨髄の赤血球産生反応は良好</strong><br>溶血性貧血、急性出血などを考慮します。';
          } else {
            rpiBadgeEl.textContent = 'RPI < 2.0：産生低下・反応不良';
            rpiBadgeEl.className = 'badge badge-g3b';
            rpiInterpEl.className = 'result-interpretation warn';
            rpiInterpEl.innerHTML =
              '<strong>骨髄の赤血球産生低下・反応不良</strong><br>鉄欠乏性貧血、巨赤芽球性貧血、再生不良性貧血、慢性疾患に伴う貧血などを考慮します。';
          }
        } else {
          rpiResultEl.textContent = '--.-';
          rpiCrcEl.textContent = '-- %';
          rpiMfEl.textContent = '-- 日';
          rpiBadgeEl.textContent = '判定待ち';
          rpiBadgeEl.className = 'badge badge-neutral';
          rpiInterpEl.className = 'result-interpretation';
          rpiInterpEl.textContent = '網状赤血球数(%)と患者Ht(%)を入力すると、骨髄反応の評価が表示されます。';
        }
      }

      refHtPills.forEach((pill) => {
        pill.addEventListener('click', () => {
          const val = pill.getAttribute('data-ref-ht');
          rpiRefHtEl.value = val;
          refHtPills.forEach((p) => p.classList.toggle('active', p === pill));
          calculateRpi();
        });
      });

      rpiRefHtEl.addEventListener('input', () => {
        refHtPills.forEach((p) => {
          p.classList.toggle('active', p.getAttribute('data-ref-ht') === rpiRefHtEl.value);
        });
        calculateRpi();
      });

      [rpiReticEl, rpiHtEl].forEach((input) => {
        input.addEventListener('input', calculateRpi);
      });

      document.getElementById('rpi-reset').addEventListener('click', () => {
        rpiReticEl.value = '';
        rpiHtEl.value = '';
        rpiRefHtEl.value = '45';
        refHtPills.forEach((p) => p.classList.toggle('active', p.getAttribute('data-ref-ht') === '45'));
        calculateRpi();
        showToast('RPI入力をリセットしました');
      });

      /* ---------------------------------------------------------
         Feature 3 & 4: Extensible Diagnostic Flow Definitions (JSON)
         後から新しいフローを追加しやすい構造化データ
         --------------------------------------------------------- */
      const DIAGNOSTIC_FLOWS = {
        /* ---------- 低Na血症 診断アルゴリズム ---------- */
        hypona: {
          startNode: 'step1',
          nodes: {
            step1: {
              type: 'question',
              stepLabel: 'Step 1 / 緊急度評価',
              question: '急性（48時間以内）または重症症状がありますか？',
              hint: '重症症状の例：けいれん、意識障害、呼吸抑制、嘔吐など',
              options: [
                { label: 'はい（急性・重症症状あり）', sub: '緊急介入が必要', next: 'res_emergency' },
                { label: 'いいえ', sub: '浸透圧の評価へ進む', next: 'step2' }
              ]
            },
            step2: {
              type: 'question',
              stepLabel: 'Step 2 / 血清浸透圧',
              question: '血清浸透圧 > 295 mOsm/kg ですか？（または正常〜高浸透圧）',
              hint: '高血糖や高浸透圧物質、偽性低Na血症を鑑別します',
              options: [
                { label: 'はい（> 295 mOsm/kg・正常〜高浸透圧）', sub: '非低浸透圧性低Na血症', next: 'res_non_hypotonic' },
                { label: 'いいえ（低張性低Na血症）', sub: '尿浸透圧の評価へ進む', next: 'step3' }
              ]
            },
            step3: {
              type: 'question',
              stepLabel: 'Step 3 / 尿浸透圧',
              question: '尿浸透圧はどれくらいですか？',
              hint: 'ADHの作用（自由水排泄能）を評価します',
              options: [
                { label: '≦ 100 mOsm/kg', sub: 'ADH抑制・最大希釈尿', next: 'res_polydipsia' },
                { label: '> 100 mOsm/kg', sub: '尿Na濃度の評価へ進む', next: 'step4' }
              ]
            },
            step4: {
              type: 'question',
              stepLabel: 'Step 4 / 尿Na濃度',
              question: '尿Na濃度はどれくらいですか？',
              hint: '有効動脈血液量や腎でのNa保持能を評価します',
              options: [
                { label: '≦ 30 mmol/L', sub: '有効動脈血液量低下を示唆', next: 'step5a' },
                { label: '> 30 mmol/L', sub: '利尿薬・腎疾患の確認へ進む', next: 'step5b' }
              ]
            },
            step5a: {
              type: 'question',
              stepLabel: 'Step 5 / 体液量評価（尿Na ≦ 30）',
              question: '細胞外液量（体液量）の評価は？',
              hint: '身体所見（浮腫・腹水・頸静脈怒張 vs 脱水・血圧低下）を確認',
              options: [
                { label: '細胞外液上昇', sub: '浮腫、腹水、胸水など', next: 'res_hypervolemic' },
                { label: '細胞外液低下', sub: '脱水、血圧低下、口渇など', next: 'res_hypovolemic_low_una' }
              ]
            },
            step5b: {
              type: 'question',
              stepLabel: 'Step 5 / 薬剤・腎疾患（尿Na > 30）',
              question: '利尿薬の使用、または腎疾患がありますか？',
              hint: 'サイアザイド系などの利尿薬内服歴・腎障害の有無を確認',
              options: [
                { label: 'はい', sub: '利尿薬・腎疾患・その他', next: 'res_diuretic_renal' },
                { label: 'いいえ', sub: '細胞外液量の評価へ進む', next: 'step6' }
              ]
            },
            step6: {
              type: 'question',
              stepLabel: 'Step 6 / 体液量評価（尿Na > 30）',
              question: '細胞外液量（体液量）の評価は？',
              hint: '脱水所見・起立性低血圧・皮膚ツルゴール低下の有無を確認',
              options: [
                { label: '細胞外液低下', sub: '脱水所見、低血圧、ツルゴール低下など', next: 'res_hypovolemic_high_una' },
                { label: '細胞外液正常', sub: '明らかな浮腫・脱水なし', next: 'res_euvolemic' }
              ]
            },

            /* --- 低Na 結果ノード --- */
            res_emergency: {
              type: 'result',
              urgent: true,
              tag: '緊急対応',
              title: '3%NaClによる緊急治療を考慮',
              sections: [
                {
                  title: '初期対応のポイント',
                  items: [
                    '急性（48時間以内）または重症症状（けいれん、意識障害、呼吸抑制など）を伴う低Na血症は脳浮腫による致命的転帰のリスクがあり、3%高張食塩水による速やかな補正を考慮します。',
                    '頻回に血清Na値をモニタリングしながら慎重に投与します。'
                  ]
                }
              ],
              callouts: [
                {
                  style: 'warn',
                  title: '過補正に厳重注意（浸透圧性脱髄症候群：ODS）',
                  html: '慢性低Na血症や発症時期不明の場合、急速なNa補正は浸透圧性脱髄症候群（ODS）を引き起こす危険があります。補正速度の上限（目安：24時間で8〜10 mEq/L以内、高リスク群ではさらに慎重に）を遵守してください。'
                }
              ]
            },
            res_non_hypotonic: {
              type: 'result',
              tag: '診断結果',
              title: '非低浸透圧性低Na血症',
              sections: [
                {
                  title: '初期評価と治療',
                  items: [
                    '血糖、TP、Alb、TGを初期検査として提出し、病歴から他の高浸透圧物質（マンニトール等）の使用有無を確認する。',
                    'DKAなどの血糖上昇時は血糖のコントロールを行う。',
                    'その他の高浸透圧物質がある際は使用を中止し、脱水補正を行う。',
                    'TP/Albの乖離など、パラプロテイン血症を疑う際は精査する（多発性骨髄腫など）。',
                    'TG上昇、MMなどのパラプロテイン血症がある場合は偽性低Na血症である可能性が高く、真のNa値は正常であるため治療介入は不要。'
                  ]
                }
              ],
              callouts: [
                {
                  style: 'info',
                  title: '偽性低Na血症とは',
                  html: '通常、血清の7%は固相ですが、高TG血症や多発性骨髄腫(MM)では固相の比率が高くなります。液体相のみから一定量の希釈液を用いてNaを測定するため、見かけ上Na濃度が低く見えますが、真のNa値は正常です。浸透圧が正常時は偽性低Na血症を考えます。'
                }
              ]
            },
            res_polydipsia: {
              type: 'result',
              tag: '診断結果',
              title: '多飲症、溶質摂取不足、beer potomania',
              sections: [
                {
                  title: '病態と治療',
                  items: [
                    '塩分（溶質）の絶対的な不足、水分の過剰摂取が原因。',
                    '塩分の投与および水分制限を行う。',
                    '溶質補充開始後に急速な水利尿が生じてNaが過補正されやすいため、血清Na値の推移に注意する。'
                  ]
                }
              ]
            },
            res_hypervolemic: {
              type: 'result',
              tag: '診断結果（細胞外液上昇）',
              title: '心不全、肝硬変、ネフローゼ症候群',
              sections: [
                {
                  title: '病態と治療',
                  items: [
                    '各病態に伴う有効動脈血液量低下および水分貯留が原因。',
                    '基礎疾患の加療に加えて、水分制限、利尿薬の使用を考慮する。'
                  ]
                }
              ]
            },
            res_hypovolemic_low_una: {
              type: 'result',
              tag: '診断結果（細胞外液低下）',
              title: '下痢、サードスペース、過去の利尿薬使用',
              sections: [
                {
                  title: '治療方針',
                  items: [
                    '細胞外液（生理食塩液など）の補充を行う。',
                    '基礎疾患の加療も並行して行う。',
                    '循環血漿量の回復に伴いADH分泌が急停止すると水利尿が起こりNaが急上昇することがあるため、補正速度をモニタリングする。'
                  ]
                }
              ]
            },
            res_diuretic_renal: {
              type: 'result',
              tag: '診断結果',
              title: '利尿薬、腎疾患、その他',
              sections: [
                {
                  title: '評価と治療',
                  items: [
                    '利尿薬（特にサイアザイド系など）による低Na血症の場合、被疑薬の減量ないし中止を検討し、細胞外液低下があれば補液を行う。',
                    '腎疾患が背景にある場合は、基礎疾患の加療を並行して行う。'
                  ]
                }
              ]
            },
            res_hypovolemic_high_una: {
              type: 'result',
              tag: '診断結果（細胞外液低下・尿Na > 30）',
              title: '嘔吐、副腎不全、塩分喪失性腎症、CSW、利尿薬の隠れ飲み（＋鑑別：MRHE）',
              sections: [
                {
                  title: '基本方針',
                  items: [
                    '細胞外液の補充を行う。基礎疾患の加療も並行して行う。',
                    '副腎不全が疑われる場合は早朝コルチゾール評価やステロイド補充を検討する。'
                  ]
                }
              ],
              callouts: [
                {
                  style: 'info',
                  title: 'CSW（中枢性塩類喪失症候群）',
                  html: '頭蓋内疾患（例：くも膜下出血）に伴う低Na血症で考慮。SIADHに類似するが、著明な水分喪失に伴う血圧低下と皮膚のツルゴール低下が認められることが相違点。血圧を維持できる程度の生理食塩液の補液を継続する。'
                },
                {
                  style: 'rx',
                  title: 'MRHE（高齢者鉱質コルチコイド反応性低Na血症）',
                  html: '加齢によるRAA系の反応性低下でNa保持機能が低下し代償的にADHが分泌される病態。診断基準はSIADHに準じるが、脱水所見や低血圧がある点が鑑別点。高齢者で水制限に無反応かつ尿中Na高値が継続する場合に考慮。<br><strong>【処方例】</strong><br>・フルドロコルチゾン（フロリネフ）0.1 mg/日 内服<br>・塩化ナトリウム 3〜6 g 分3'
                }
              ]
            },
            res_euvolemic: {
              type: 'result',
              tag: '診断結果（細胞外液正常）',
              title: 'SIADH、二次性副腎不全、甲状腺機能低下症',
              sections: [
                {
                  title: '除外診断と治療の原則',
                  items: [
                    'SIADHはあくまで除外診断であり、特に甲状腺機能低下症と副腎不全を必ず除外する（TSH、早朝コルチゾール値、必要に応じACTH負荷試験）。',
                    '甲状腺機能低下症・副腎不全では、水分制限・塩分付加を行いながら原疾患の加療（それぞれチラーヂン、ステロイド投与）を行う。',
                    'SIADHはあくまで病態であり、原因検索（悪性腫瘍・薬剤・肺疾患・頭蓋内疾患など）と原因除去が肝要。',
                    '治療は水制限、塩分付加および原因除去（被疑薬があれば可能な限り中止）。原因除去が困難な場合は塩分付加や利尿薬の併用を継続。'
                  ]
                }
              ],
              table: {
                title: 'SIADHの主な原因検索リスト',
                rows: [
                  ['悪性腫瘍', '肺小細胞がん、その他の悪性腫瘍全般'],
                  ['薬物', '低Na血症をきたす被疑薬（SSRI、抗てんかん薬など）'],
                  ['肺疾患', '肺炎、肺膿瘍、結核、アスペルギルス'],
                  ['頭蓋内疾患', '脳炎、髄膜炎、脳血管障害、脳腫瘍'],
                  ['その他', 'ストレス、疼痛、嘔気、特発性']
                ]
              },
              callouts: [
                {
                  style: 'rx',
                  title: 'SIADH 処方例',
                  html: '・NaCl 3〜6 g 分3 内服（食事中の塩分量と合わせて評価。食塩として食事に追加すれば摂取しやすい）<br>・フロセミド 10〜20 mg/日 内服（日本では保険適応外）'
                },
                {
                  style: 'info',
                  title: '退院前アクションプラン',
                  html: '☑ Na値のコントロールが良好であり、原因の病態の加療ができていれば退院を考慮する。<br>☑ 病態に応じて、必要であれば塩分付加、水分制限、利尿薬を継続する。<br>☑ 薬剤性低Na血症の場合では、薬の減量ないし中止を指示する。'
                }
              ]
            }
          }
        },

        /* ---------- 低カリウム血症 診断アルゴリズム ---------- */
        hypok: {
          startNode: 'step1',
          nodes: {
            step1: {
              type: 'question',
              stepLabel: 'Step 1 / 尿中K濃度',
              question: '尿中K濃度はどれくらいですか？',
              hint: '腎からのK喪失か、腎外性・細胞内移行かを鑑別します',
              options: [
                { label: '< 20 mEq/L', sub: '腎外性喪失・細胞内移行・摂取不足', next: 'res_extrarenal' },
                { label: '> 20 mEq/L（腎性K喪失）', sub: '酸塩基平衡（pH）の評価へ進む', next: 'step2' }
              ]
            },
            step2: {
              type: 'question',
              stepLabel: 'Step 2 / 酸塩基平衡（pH）',
              question: '酸塩基平衡（pH）はどれですか？',
              hint: '血液ガス分析（静脈または動脈）で評価します',
              options: [
                { label: '代謝性アシドーシス', sub: 'HCO3- 低下', next: 'res_rta' },
                { label: '様々な pH', sub: '一定の傾向なし', next: 'res_various_ph' },
                { label: '代謝性アルカローシス', sub: '尿中Cl濃度の評価へ進む', next: 'step3' }
              ]
            },
            step3: {
              type: 'question',
              stepLabel: 'Step 3 / 尿中Cl濃度',
              question: '尿中Cl濃度はどれくらいですか？',
              hint: '代謝性アルカローシスを伴う腎性K喪失の鑑別',
              options: [
                { label: '< 20 mEq/L', sub: 'Cl反応性アルカローシス', next: 'res_low_ucl' },
                { label: '> 20 mEq/L', sub: '血圧の評価へ進む', next: 'step4' }
              ]
            },
            step4: {
              type: 'question',
              stepLabel: 'Step 4 / 血圧評価',
              question: '血圧はどれくらいですか？',
              hint: '高血圧の有無で鑑別します',
              options: [
                { label: '正常血圧', sub: '高血圧なし', next: 'res_normotensive' },
                { label: '高血圧', sub: 'アルドステロン値の評価へ進む', next: 'step5' }
              ]
            },
            step5: {
              type: 'question',
              stepLabel: 'Step 5 / アルドステロン値',
              question: '血漿アルドステロン値は？',
              hint: 'ミネラルコルチコイド過剰の機序を鑑別します',
              options: [
                { label: '正常〜低値', sub: 'アルドステロン非依存性', next: 'res_low_aldo' },
                { label: '高値', sub: 'レニン活性の評価へ進む', next: 'step6' }
              ]
            },
            step6: {
              type: 'question',
              stepLabel: 'Step 6 / レニン活性',
              question: '血漿レニン活性は？',
              hint: '原発性か二次性アルドステロン症かを鑑別します',
              options: [
                { label: '低レニン', sub: 'レニン抑制', next: 'res_pa' },
                { label: '高レニン', sub: 'レニン亢進', next: 'res_high_renin' }
              ]
            },

            /* --- 低K 結果ノード --- */
            res_extrarenal: {
              type: 'result',
              tag: '診断結果（尿中K < 20 mEq/L）',
              title: '腎外性喪失・細胞内移行・K摂取不足',
              sections: [
                {
                  title: '細胞内へのK移行',
                  items: ['代謝性アルカローシス', 'インスリン投与', '周期性四肢麻痺', '交感神経亢進']
                },
                {
                  title: 'K摂取不足',
                  items: ['食事摂取不良・低K輸液の長期継続など']
                },
                {
                  title: '腎以外からのK喪失',
                  items: ['下痢', '熱傷']
                }
              ]
            },
            res_rta: {
              type: 'result',
              tag: '診断結果（腎性K喪失・代謝性アシドーシス）',
              title: '尿細管性アシドーシス (RTA)',
              sections: [
                {
                  title: '鑑別ポイント',
                  items: [
                    '遠位型（1型）または近位型（2型）の尿細管性アシドーシスを考慮します。',
                    'アニオンギャップ正常の代謝性アシドーシスを呈します。'
                  ]
                }
              ]
            },
            res_various_ph: {
              type: 'result',
              tag: '診断結果（腎性K喪失・様々なpH）',
              title: 'ペニシリン、Mg欠乏、急性尿細管壊死',
              sections: [
                {
                  title: '主な原因',
                  items: [
                    'ペニシリン（大量投与による非吸収性陰イオンの尿中排泄）',
                    'Mg欠乏（低Mg血症はK補充抵抗性となるため、血清Mg確認・補正が重要）',
                    '急性尿細管壊死（利尿期など）'
                  ]
                }
              ]
            },
            res_low_ucl: {
              type: 'result',
              tag: '診断結果（尿中Cl < 20 mEq/L）',
              title: '嘔吐、利尿薬投与中止後',
              sections: [
                {
                  title: '主な原因・対応',
                  items: [
                    '嘔吐（胃液喪失に伴う代謝性アルカローシスと二次性アルドステロン症）',
                    '利尿薬投与中止後',
                    '生理食塩液とKClの補充が有効です。'
                  ]
                }
              ]
            },
            res_normotensive: {
              type: 'result',
              tag: '診断結果（尿中Cl > 20 mEq/L・正常血圧）',
              title: 'Bartter症候群（Batter症候群）、利尿薬投与',
              sections: [
                {
                  title: '主な原因',
                  items: [
                    'Bartter症候群（ヘンレループ上行脚の輸送体異常）',
                    '利尿薬投与（ループ利尿薬・サイアザイド系利尿薬の現在使用中）'
                  ]
                }
              ]
            },
            res_low_aldo: {
              type: 'result',
              tag: '診断結果（高血圧・アルドステロン正常〜低値）',
              title: 'ミネラルコルチコイド投与、クッシング症候群、Liddle症候群',
              sections: [
                {
                  title: '主な原因',
                  items: [
                    'ミネラルコルチコイド投与（甘草・漢方薬による偽性アルドステロン症も同様に鑑別）',
                    'クッシング症候群',
                    'Liddle症候群'
                  ]
                }
              ]
            },
            res_pa: {
              type: 'result',
              tag: '診断結果（高血圧・高アルドステロン・低レニン）',
              title: '原発性アルドステロン症',
              sections: [
                {
                  title: '評価ポイント',
                  items: [
                    'アルドステロン/レニン比（ARR）高値を確認し、機能確認試験や副腎CTなどの精査を検討します。'
                  ]
                }
              ]
            },
            res_high_renin: {
              type: 'result',
              tag: '診断結果（高血圧・高アルドステロン・高レニン）',
              title: '腎血管性高血圧、レニン産生腫瘍、悪性高血圧',
              sections: [
                {
                  title: '主な原因',
                  items: [
                    '腎血管性高血圧（腎動脈狭窄の評価：腎動脈エコー・MRAなど）',
                    'レニン産生腫瘍',
                    '悪性高血圧'
                  ]
                }
              ]
            }
          }
        }
      };

      /* ---------------------------------------------------------
         Reusable Wizard Controller
         --------------------------------------------------------- */
      function initWizard(containerId, flowConfig) {
        const container = document.getElementById(containerId);
        if (!container) return;

        let history = []; // { nodeId, choiceLabel }
        let currentNodeId = flowConfig.startNode;

        function render() {
          const node = flowConfig.nodes[currentNodeId];
          if (!node) return;

          // 上部コントロール（1つ戻る / 最初からやり直す）
          const controlsHtml = `
            <div class="wizard-controls">
              <button type="button" class="wizard-mini-btn" data-action="back" ${history.length === 0 ? 'disabled' : ''}>
                ← 1つ戻る
              </button>
              <button type="button" class="wizard-mini-btn" data-action="reset" ${history.length === 0 ? 'disabled' : ''}>
                ↺ 最初からやり直す
              </button>
            </div>
          `;

          // パンくずリスト
          let crumbsHtml = '';
          if (history.length === 0) {
            crumbsHtml = `<div class="breadcrumbs"><span class="crumb-empty">選択履歴：まだ選択されていません</span></div>`;
          } else {
            const items = history.map((h) => `<span class="crumb-item">${escapeHtml(h.choiceLabel)}</span>`).join('<span class="crumb-sep">›</span>');
            crumbsHtml = `<div class="breadcrumbs" aria-label="選択履歴">${items}</div>`;
          }

          // メインカード（質問 or 結果）
          let bodyHtml = '';
          if (node.type === 'question') {
            const optionsHtml = node.options.map((opt, idx) => `
              <button type="button" class="option-btn" data-option-index="${idx}">
                <div>
                  <span class="option-main">${escapeHtml(opt.label)}</span>
                  ${opt.sub ? `<span class="option-sub">${escapeHtml(opt.sub)}</span>` : ''}
                </div>
                <span class="option-arrow" aria-hidden="true">›</span>
              </button>
            `).join('');

            bodyHtml = `
              <div class="card">
                <span class="wizard-step-badge">${escapeHtml(node.stepLabel)}</span>
                <h3 class="wizard-question">${escapeHtml(node.question)}</h3>
                ${node.hint ? `<p class="wizard-hint">${escapeHtml(node.hint)}</p>` : ''}
                <div class="option-list">${optionsHtml}</div>
              </div>
            `;
          } else if (node.type === 'result') {
            const sectionsHtml = (node.sections || []).map((sec) => `
              <div class="dx-section">
                <h4 class="dx-section-title">${escapeHtml(sec.title)}</h4>
                <ul class="dx-list">
                  ${sec.items.map((item) => `<li>${escapeHtml(item)}</li>`).join('')}
                </ul>
              </div>
            `).join('');

            const tableHtml = node.table ? `
              <div class="dx-section">
                <h4 class="dx-section-title">${escapeHtml(node.table.title)}</h4>
                <table class="dx-table">
                  <tbody>
                    ${node.table.rows.map((r) => `<tr><th>${escapeHtml(r[0])}</th><td>${escapeHtml(r[1])}</td></tr>`).join('')}
                  </tbody>
                </table>
              </div>
            ` : '';

            const calloutsHtml = (node.callouts || []).map((c) => `
              <div class="dx-callout ${c.style || ''}">
                <span class="dx-callout-title">${escapeHtml(c.title)}</span>
                <div>${c.html}</div>
              </div>
            `).join('');

            bodyHtml = `
              <div class="dx-card ${node.urgent ? 'urgent' : ''}">
                <div class="dx-header">
                  <div class="dx-tag">${escapeHtml(node.tag || '診断結果')}</div>
                  <h3 class="dx-title">${escapeHtml(node.title)}</h3>
                </div>
                <div class="dx-body">
                  ${sectionsHtml}
                  ${tableHtml}
                  ${calloutsHtml}
                </div>
              </div>
            `;
          }

          container.innerHTML = controlsHtml + crumbsHtml + bodyHtml;

          // イベントリスナー登録
          const backBtn = container.querySelector('[data-action="back"]');
          const resetBtn = container.querySelector('[data-action="reset"]');

          if (backBtn) {
            backBtn.addEventListener('click', () => {
              if (history.length > 0) {
                const prev = history.pop();
                currentNodeId = prev.nodeId;
                render();
              }
            });
          }

          if (resetBtn) {
            resetBtn.addEventListener('click', () => {
              history = [];
              currentNodeId = flowConfig.startNode;
              render();
            });
          }

          container.querySelectorAll('[data-option-index]').forEach((btn) => {
            btn.addEventListener('click', () => {
              const idx = Number(btn.getAttribute('data-option-index'));
              const chosen = node.options[idx];
              if (chosen) {
                history.push({ nodeId: currentNodeId, choiceLabel: chosen.label });
                currentNodeId = chosen.next;
                render();
              }
            });
          });
        }

        render();
      }

      function escapeHtml(str) {
        return String(str)
          .replace(/&/g, '&amp;')
          .replace(/</g, '&lt;')
          .replace(/>/g, '&gt;')
          .replace(/"/g, '&quot;')
          .replace(/'/g, '&#39;');
      }

      // 診断フロー初期化
      initWizard('wizard-hypona', DIAGNOSTIC_FLOWS.hypona);
      initWizard('wizard-hypok', DIAGNOSTIC_FLOWS.hypok);

      /* ---------------------------------------------------------
         Feature 3 Sub-tool: Water Restriction Calculator
         --------------------------------------------------------- */
      const waterUnaEl = document.getElementById('water-una');
      const waterUkEl = document.getElementById('water-uk');
      const waterSnaEl = document.getElementById('water-sna');
      const waterRatioEl = document.getElementById('water-ratio-val');
      const waterGuideEl = document.getElementById('water-guide-val');
      const rowGt = document.getElementById('water-row-gt');
      const rowEq = document.getElementById('water-row-eq');
      const rowLt = document.getElementById('water-row-lt');

      function calculateWaterRestriction() {
        const una = parseFloat(waterUnaEl.value);
        const uk = parseFloat(waterUkEl.value);
        const sna = parseFloat(waterSnaEl.value);

        [rowGt, rowEq, rowLt].forEach((r) => r.classList.remove('highlight'));

        if (!isNaN(una) && una >= 0 && !isNaN(uk) && uk >= 0 && sna > 0) {
          const ratio = (una + uk) / sna;
          waterRatioEl.textContent = ratio.toFixed(2);

          if (ratio > 1.05) {
            waterGuideEl.textContent = '< 500 mL / 日';
            rowGt.classList.add('highlight');
          } else if (ratio >= 0.95 && ratio <= 1.05) {
            waterGuideEl.textContent = '500〜700 mL / 日';
            rowEq.classList.add('highlight');
          } else {
            waterGuideEl.textContent = '1 L / 日';
            rowLt.classList.add('highlight');
          }
        } else {
          waterRatioEl.textContent = '--';
          waterGuideEl.textContent = '数値を入力';
        }
      }

      [waterUnaEl, waterUkEl, waterSnaEl].forEach((el) => {
        el.addEventListener('input', calculateWaterRestriction);
      });

      /* ---------------------------------------------------------
         PWA / Service Worker Auto-Update Hook (Safe Fallback)
         --------------------------------------------------------- */
      const networkDot = document.getElementById('networkDot');
      const checkUpdateBtn = document.getElementById('checkUpdateBtn');
      const updateBanner = document.getElementById('updateBanner');
      const applyUpdateBtn = document.getElementById('applyUpdateBtn');
      let swRegistration = null;
      let waitingWorker = null;

      function updateNetworkIndicator() {
        const isOnline = navigator.onLine !== false;
        networkDot.classList.toggle('offline', !isOnline);
      }
      window.addEventListener('online', () => {
        updateNetworkIndicator();
        showToast('オンラインに復帰しました');
      });
      window.addEventListener('offline', () => {
        updateNetworkIndicator();
        showToast('オフラインモードで動作中です');
      });
      updateNetworkIndicator();

      function showUpdateBanner(worker) {
        waitingWorker = worker;
        updateBanner.classList.add('visible');
      }

      applyUpdateBtn.addEventListener('click', () => {
        if (waitingWorker) {
          waitingWorker.postMessage({ type: 'SKIP_WAITING' });
        } else {
          window.location.reload();
        }
      });

      // Service Workerの安全な登録（HTTPSまたはlocalhost環境でのみ実行）
      function registerServiceWorkerSafely() {
        try {
          const isSupported = 'serviceWorker' in navigator;
          const isSecureContext =
            window.location.protocol === 'https:' ||
            window.location.hostname === 'localhost' ||
            window.location.hostname === '127.0.0.1';

          if (!isSupported || !isSecureContext) {
            return;
          }

          window.addEventListener('load', async () => {
            try {
              const reg = await navigator.serviceWorker.register('./sw.js');
              swRegistration = reg;

              if (reg.waiting) {
                showUpdateBanner(reg.waiting);
              }

              reg.addEventListener('updatefound', () => {
                const newWorker = reg.installing;
                if (!newWorker) return;
                newWorker.addEventListener('statechange', () => {
                  if (newWorker.state === 'installed' && navigator.serviceWorker.controller) {
                    showUpdateBanner(newWorker);
                  }
                });
              });

              let refreshing = false;
              navigator.serviceWorker.addEventListener('controllerchange', () => {
                if (!refreshing) {
                  refreshing = true;
                  window.location.reload();
                }
              });
            } catch (err) {
              // sw.js未配置・プレビュー環境等では静かにスキップ
            }
          });
        } catch (err) {
          // プレビューiframe等の制限時は何もしない
        }
      }

      registerServiceWorkerSafely();

      // 手動更新チェックボタン
      checkUpdateBtn.addEventListener('click', async () => {
        if (!navigator.onLine) {
          showToast('オフラインのため更新確認できません');
          return;
        }
        if (swRegistration) {
          try {
            showToast('最新バージョンを確認中...');
            await swRegistration.update();
            if (swRegistration.waiting) {
              showUpdateBanner(swRegistration.waiting);
            } else {
              showToast(`最新バージョンです (${APP_VERSION})`);
            }
          } catch (e) {
            showToast(`現在のバージョン: ${APP_VERSION}`);
          }
        } else {
          showToast(`現在のバージョン: ${APP_VERSION}（オフライン対応）`);
        }
      });
    })();
  </script>
</body>
</html>
