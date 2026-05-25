# On Tập Toán Đại Cương — Calculus Review

> Interactive Vietnamese-language study guide for Calculus I & II — covering limits, derivatives, integrals, and applications. Self-contained, zero dependencies.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](index.html)
[![Language](https://img.shields.io/badge/Language-Vietnamese-blue?style=flat-square&labelColor=gold)](#)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](#)

---

## Mục lục — What's Inside

```
Ôn tập Toán Đại Cương
├── 📖 Lý thuyết     — Tổng hợp lý thuyết từng chương
├── 🔢 Phần 1        — Đại số tuyến tính (Ma trận, Định thức, Hệ PT, Hạng & Nghịch đảo)
├── ∫  Phần 2        — Vi tích phân một biến (Giới hạn, Đạo hàm, Tích phân suy rộng)
├── ∂  Phần 3        — Vi tích phân nhiều biến (Đạo hàm riêng, Cực trị, Lagrange)
├── ❓ Trắc nghiệm   — 35 câu hỏi trắc nghiệm có đáp án
└── ✅ Đáp án        — Giải thích chi tiết từng đáp án
```

---

## Features

| Feature | Description |
|---------|-------------|
| 📚 **Tổng hợp lý thuyết** | Full formula sheets for every topic with clear explanations |
| 🔢 **3 Chủ đề chính** | Linear Algebra · Single-Variable Calculus · Multi-Variable Calculus |
| ❓ **35 câu trắc nghiệm** | Multiple-choice quiz covering all sections |
| ✅ **Đáp án chi tiết** | Each answer reveals with explanation and step-by-step reasoning |
| 📱 **Responsive** | Works on mobile and desktop |
| 🔒 **Zero dependencies** | No CDN, no frameworks, no build tools — single HTML file |

---

## Nội dung chi tiết — Content Breakdown

### Phần 1: Đại số tuyến tính
| Topic | Coverage |
|-------|----------|
| Ma trận | Definition, types (zero, identity, diagonal, triangular, symmetric), operations, transpose |
| Định thức | Formulas for n=1,2,3; Sarrus rule; Laplace expansion; 8 key properties |
| Hệ phương trình | Kronecker-Capelli, Gaussian elimination, Cramer's rule, inverse matrix method |
| Hạng & Nghịch đảo | Rank definition, invertibility, adjugate formula, Gauss-Jordan |

### Phần 2: Vi tích phân một biến
| Topic | Coverage |
|-------|----------|
| Giới hạn | 7 indeterminate forms, sin x/x, e^x limits, L'Hôpital's rule, small-o equivalents |
| Liên tục | Definition, Bolzano's theorem, Weierstrass theorem |
| Đạo hàm & Vi phân | Table of derivatives, product/quotient/chain rules, linear approximation, extrema tests |
| Tích phân suy rộng | Type 1 (infinite bounds), Type 2 (unbounded), comparison test, p-test |

### Phần 3: Vi tích phân nhiều biến
| Topic | Coverage |
|-------|----------|
| Hàm nhiều biến | Domain, limits, two-path test |
| Đạo hàm riêng | First & second order, Schwarz's theorem, total differential, implicit differentiation |
| Cực trị | Free extrema (delta test), constrained extrema (Lagrange multipliers, 1 & 2 constraints) |

---

## Tech Stack

```
HTML5        Semantic markup with inline <style> and <script>
CSS3         Custom properties, responsive design, no external stylesheets
JavaScript   Vanilla JS for quiz interactions — no libraries
Fonts        System font stack (zero external font dependencies)
```

> **100% self-contained** — no CDN, no Google Fonts, no external requests. Works offline.

---

## Files

| File | Description |
|------|-------------|
| `index.html` | The entire application (~1,400 lines, 65 KB) |
| `README.md` | This file |

---

## Getting Started

```bash
# Just open the file — no server needed
open index.html

# Or serve locally
python3 -m http.server 8080
# → http://localhost:8080
```

---

## Design

| Element | Value |
|---------|-------|
| Primary color | `#1a56db` (blue) |
| Accent | `#0e9f6e` (green) |
| Note color | `#f59e0b` (amber) |
| Breakpoints | 600px (mobile) |

Formula boxes, tip boxes, and answer reveals are styled with left-border accent colors for easy scanning.
