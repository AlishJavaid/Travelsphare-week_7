# 🧠 TravelSphere — Smart Travel Recommendations & Travel Assistant

**CODIORA House (Private) Limited | 2-Month Remote Internship — Batch 3**
**Week 7 Task — Smart Travel Features & Platform Optimization**
**Web Development Track (HTML • CSS • JavaScript)**

> *"Our Code Builds Your Vision"*
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#)
[![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?logo=font-awesome&logoColor=white)](#)

---

## ✈️ About This Week

| Week | Phase |
|------|-------|
| Week 1 | Project Foundation |
| Week 2 | Destination Exploration |
| Week 3 | User Experience & Personalization |
| Week 4 | Trip Planning & Itinerary Management |
| Week 5 | Travel Services & Booking Experience |
| Week 6 | Reviews, Ratings & Travel Community |
| **Week 7** | **Smart Travel Features & Platform Optimization** ← *this submission* |

By Week 6, the platform could explore destinations, personalize experiences, create trips, build itineraries, explore services, submit bookings, and review & rate — but it simply **displayed** information.

**Week 7 changes that.** The platform now **helps the traveler decide**. Instead of showing every destination to every user, TravelSphere analyzes the user's preferences and recommends destinations that actually suit their budget, travel style, and interests — plus a Travel Assistant answers common questions instantly.

> ⚠️ As specified in the task, Week 7 is **not** another destination-listing, booking, or review task. The focus is **smart recommendations, travel assistance, personalization and platform optimization**.
>
> The recommendation engine uses **JavaScript-based rules and scoring logic** — no machine learning required.

---

## ✨ Week 7 Features

### 1. 📝 Travel Preference Form
A smart, clickable preference selector where users choose:

| Preference | Options |
|------------|---------|
| 💰 Budget | Budget (under $1,000) • Medium ($1,000–$1,500) • Luxury ($1,500+) |
| 🧗 Travel Type | Adventure • Relaxation • Family • Cultural • Luxury • Budget |
| 📅 Trip Duration | Short (1–5 days) • Medium (6–10 days) • Long (11+ days) |
| 🏔️ Preferred Environment | Beaches • Mountains • Historical • Adventure • Cultural • Nature & Wildlife |
| 👥 Travelers | Solo • Couple • Family • Group |

Includes validation (minimum 3 preferences required) and session memory.

### 2. 🧮 Recommendation System (JavaScript Rule Engine)
A weighted scoring algorithm rates all 13 destinations:

| Rule | Points |
|------|:------:|
| Environment matches category | +4 |
| Budget within selected range | +3 |
| Travel type compatibility (perfect fit) | +3 |
| Travel type compatibility (good fit) | +2 |
| Duration suitability | +2 |
| Highly rated (≥ 4.8★) | +1 |
| Popular (≥ 90) | +1 |

Destinations are ranked by **match percentage** = score ÷ max possible score.

### 3. 🎯 Smart Recommendation Cards
Each result card displays:
- 🖼️ Destination image
- 📍 Name & location
- ⭐ Rating & 🏷️ category
- 💵 Estimated cost
- 🏆 **Match percentage badge** (e.g. *92% Match — Top Pick*)
- 💡 **"Recommended because…"** natural-language reason
- **View Details** + **Plan Trip** buttons

Plus a loading animation, results summary bar, and an empty state when no matches fit.

### 4. 🤖 Travel Assistant
A chat-style assistant with:
- 10 predefined Q&A topics (adventure, budget, family, luxury, beaches, culture, romance, Iceland, safaris, Santorini)
- **Keyword-matching engine** that understands free-text questions
- Suggested **follow-up questions** after every answer
- Quick-question chips + free-text input field
- Friendly fallback response for unmatched questions

### 5. ⚡ Platform Optimization
Week 7 also polished the whole platform:
- 🚀 Single optimized build with lazy-loaded images + automatic fallbacks
- 🧭 Cleaner navigation with live count badges
- 📱 Fully responsive layouts (mobile menu, adaptive grids)
- ♿ Improved accessibility (labels, ARIA attributes, keyboard Escape handling)
- 🖱️ Better form usability (inline validation, clear error messages)
- 🕳️ Consistent empty/error states across every module
- 🔔 Interactive toast notifications everywhere

---
## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure |
| **CSS3** | Styling, animations, responsive layout |
| **JavaScript (ES6+)** | Recommendation engine, scoring, assistant logic |
| **localStorage** | Persisting favorites, trips, bookings, reviews |
| **Google Fonts** | Poppins + Playfair Display |
| **Font Awesome 6** | Icons |

---

## 🚀 Getting Started

### Prerequisites
- Any modern browser (Chrome, Firefox, Edge, Safari)
- No server, build tools, or dependencies required ✅
