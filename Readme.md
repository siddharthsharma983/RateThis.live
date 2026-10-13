# 🔥 RateThis.live

> _Where Petty Debates Become Global Wars. Your Opinion Matters, The Internet Disagrees._

**RateThis.live** ek high-performance, real-time gamified voting aur debate platform hai jahan users rapid-fire matchups par vote karte hain, global Elo leaderboards par compete karte hain, aur real-time chat ke zariye live debates mein hissa lete hain.

🌐 **Live Demo:** [ratethislive.vercel.app](https://ratethislive.vercel.app)

---

## 🚀 Key Features

- **⚡ Blitz-Mode Voting:** Har matchup ke liye 5-second ka rapid countdown timer, auto-skip functionality, aur instant percentage/winner reveal overlays ke sath.
- **🏆 Live Elo Leaderboard & Impact Scores:** Dynamic global rankings jo users ke voting streaks aur atomic backend Elo rating calculations ke mutabiq real-time update hoti hain.
- **💬 Real-Time Live Debate Stream:** Supabase WebSockets (`postgres_changes`) dwara powered live comment stream jahan users "fuel on the fire" add karte hain.
- **🔔 Smart Notification System:** Slide-over notification drawer jo unread indicators, click-outside-to-close/escape handlers, aur live matchup winner alerts ke sath aata hai.
- **🛡️ Secure Atomic Transactions:** Client-side tampering ko rokne ke liye Supabase Row-Level Security (RLS) aur PostgreSQL Stored Procedures (RPC).

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript (ES6+)
- **Backend & Database:** Supabase (Hosted PostgreSQL)
- **Real-time Engine:** Supabase WebSockets
