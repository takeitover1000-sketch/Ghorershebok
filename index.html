import { useState, useEffect, useRef } from "react";

const COLORS = {
  primary: "#8B4513",
  primaryLight: "#A0522D",
  primaryDark: "#5C2E00",
  accent: "#C8956C",
  accentLight: "#E8C4A0",
  cream: "#F5F0E8",
  dark: "#2C1810",
  text: "#3D2314",
  textLight: "#7A5C4E",
  white: "#FFFFFF",
  cardBg: "#FDF8F2",
};

const services = [
  { icon: "❄️", name: "AC সার্ভিস", nameEn: "AC Servicing", count: "1,200+", color: "#E8F4FD" },
  { icon: "🔧", name: "প্লাম্বিং", nameEn: "Plumbing", count: "800+", color: "#FFF3E0" },
  { icon: "⚡", name: "ইলেকট্রিক্যাল", nameEn: "Electrical", count: "950+", color: "#FFFDE7" },
  { icon: "🏠", name: "হোম ক্লিনিং", nameEn: "Home Cleaning", count: "2,100+", color: "#F1F8E9" },
  { icon: "🛋️", name: "ফার্নিচার", nameEn: "Furniture Fix", count: "600+", color: "#FCE4EC" },
  { icon: "💆", name: "বিউটি কেয়ার", nameEn: "Beauty & Wellness", count: "1,500+", color: "#F3E5F5" },
  { icon: "🚚", name: "হাউস শিফটিং", nameEn: "House Shifting", count: "400+", color: "#E8EAF6" },
  { icon: "🎨", name: "পেইন্টিং", nameEn: "Painting", count: "350+", color: "#E0F7FA" },
  { icon: "🔩", name: "অ্যাপ্লায়েন্স", nameEn: "Appliance Repair", count: "700+", color: "#FFF8E1" },
  { icon: "🌿", name: "গার্ডেনিং", nameEn: "Gardening", count: "200+", color: "#E8F5E9" },
];

const locations = ["বনানী", "গুলশান", "ধানমন্ডি", "মিরপুর", "উত্তরা", "মোহাম্মদপুর", "খিলগাঁও", "বাড্ডা", "যাত্রাবাড়ী", "রামপুরা"];

const reviews = [
  { name: "রাহেলা বেগম", area: "গুলশান", rating: 5, text: "অসাধারণ সার্ভিস! AC টেকনিশিয়ান সময়মতো এসে কাজ পারফেক্ট করে গেছে।", service: "AC সার্ভিস", avatar: "👩" },
  { name: "করিম সাহেব", area: "ধানমন্ডি", rating: 5, text: "বাথরুমের পাইপ লিক ঠিক করতে মাত্র ৪৫ মিনিট লেগেছে। দাম যুক্তিসংগত।", service: "প্লাম্বিং", avatar: "👨" },
  { name: "সুমাইয়া আক্তার", area: "উত্তরা", rating: 5, text: "ঘর পরিষ্কার সার্ভিস নিয়েছিলাম। একদম ঝকঝকে করে দিয়ে গেছে!", service: "হোম ক্লিনিং", avatar: "👩" },
];

const stats = [
  { value: "50,000+", label: "সম্পন্ন সার্ভিস" },
  { value: "2,500+", label: "ভেরিফাইড এক্সপার্ট" },
  { value: "4.8★", label: "গড় রেটিং" },
  { value: "15+", label: "সার্ভিস ক্যাটাগরি" },
];

export default function GhorerShebokLanding() {
  const [selectedLocation, setSelectedLocation] = useState("গুলশান");
  const [searchQuery, setSearchQuery] = useState("");
  const [locationOpen, setLocationOpen] = useState(false);
  const [scrolled, setScrolled] = useState(false);
  const [activeTab, setActiveTab] = useState(0);
  const heroRef = useRef(null);

  useEffect(() => {
    const handleScroll = () => setScrolled(window.scrollY > 60);
    window.addEventListener("scroll", handleScroll);
    return () => window.removeEventListener("scroll", handleScroll);
  }, []);

  const filteredServices = searchQuery
    ? services.filter(s => s.name.includes(searchQuery) || s.nameEn.toLowerCase().includes(searchQuery.toLowerCase()))
    : services;

  return (
    <div style={{ fontFamily: "'Hind Siliguri', 'Noto Sans Bengali', sans-serif", background: COLORS.cream, color: COLORS.text, minHeight: "100vh", overflowX: "hidden" }}>
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&display=swap');
        * { box-sizing: border-box; margin: 0; padding: 0; }
        :root { scroll-behavior: smooth; }
        
        .nav-glass {
          background: rgba(255,255,255,0.95);
          backdrop-filter: blur(20px);
          box-shadow: 0 2px 30px rgba(139,69,19,0.1);
        }
        
        .hero-bg {
          background: linear-gradient(135deg, #2C1810 0%, #5C2E00 40%, #8B4513 70%, #A0522D 100%);
          position: relative;
          overflow: hidden;
        }
        
        .hero-pattern {
          position: absolute; inset: 0;
          background-image: radial-gradient(circle at 20% 50%, rgba(200,149,108,0.15) 0%, transparent 50%),
                            radial-gradient(circle at 80% 20%, rgba(255,255,255,0.05) 0%, transparent 40%),
                            radial-gradient(circle at 60% 80%, rgba(139,69,19,0.3) 0%, transparent 50%);
        }
        
        .hero-grid {
          position: absolute; inset: 0;
          background-image: linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
                            linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
          background-size: 50px 50px;
        }
        
        .search-bar {
          background: white;
          border-radius: 16px;
          box-shadow: 0 20px 60px rgba(0,0,0,0.2), 0 4px 20px rgba(139,69,19,0.15);
          overflow: hidden;
          transition: transform 0.3s, box-shadow 0.3s;
        }
        .search-bar:focus-within {
          transform: translateY(-2px);
          box-shadow: 0 30px 80px rgba(0,0,0,0.25), 0 8px 30px rgba(139,69,19,0.2);
        }
        
        .location-btn {
          border: none; background: none; cursor: pointer;
          display: flex; align-items: center; gap: 8px;
          padding: 18px 20px;
          font-size: 15px; font-weight: 600;
          color: ${COLORS.primary};
          border-right: 2px solid #F0E8DE;
          white-space: nowrap;
          min-width: 150px;
          font-family: inherit;
        }
        .location-btn:hover { background: #FDF5EC; }
        
        .search-input {
          flex: 1; border: none; outline: none;
          padding: 18px 20px; font-size: 15px;
          color: ${COLORS.text}; background: transparent;
          font-family: inherit;
        }
        .search-input::placeholder { color: #B8A89A; }
        
        .search-btn {
          background: ${COLORS.primary};
          border: none; cursor: pointer;
          padding: 14px 28px;
          margin: 7px;
          border-radius: 10px;
          color: white;
          font-size: 15px;
          font-weight: 600;
          font-family: inherit;
          display: flex; align-items: center; gap: 8px;
          transition: all 0.2s;
          white-space: nowrap;
        }
        .search-btn:hover { background: ${COLORS.primaryDark}; transform: scale(1.02); }
        
        .dropdown {
          position: absolute; top: calc(100% + 10px); left: 0;
          background: white; border-radius: 14px;
          box-shadow: 0 20px 60px rgba(0,0,0,0.15);
          width: 220px; overflow: hidden; z-index: 100;
          border: 1px solid #F0E0D0;
        }
        .dropdown-item {
          padding: 12px 20px; cursor: pointer;
          font-size: 14px; color: ${COLORS.text};
          transition: all 0.15s;
          display: flex; align-items: center; gap: 10px;
        }
        .dropdown-item:hover { background: #FDF5EC; color: ${COLORS.primary}; }
        
        .service-card {
          background: white;
          border-radius: 16px;
          padding: 24px 16px;
          text-align: center;
          cursor: pointer;
          transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
          border: 1.5px solid transparent;
          position: relative;
          overflow: hidden;
        }
        .service-card::before {
          content: '';
          position: absolute; inset: 0;
          background: linear-gradient(135deg, transparent 0%, rgba(139,69,19,0.03) 100%);
          opacity: 0; transition: opacity 0.3s;
        }
        .service-card:hover {
          transform: translateY(-6px) scale(1.02);
          border-color: ${COLORS.accentLight};
          box-shadow: 0 20px 40px rgba(139,69,19,0.12);
        }
        .service-card:hover::before { opacity: 1; }
        
        .icon-wrap {
          width: 64px; height: 64px;
          border-radius: 18px;
          display: flex; align-items: center; justify-content: center;
          font-size: 28px;
          margin: 0 auto 14px;
          transition: transform 0.3s;
        }
        .service-card:hover .icon-wrap { transform: scale(1.1) rotate(-5deg); }
        
        .step-card {
          background: white;
          border-radius: 20px;
          padding: 36px 28px;
          text-align: center;
          position: relative;
          border: 1.5px solid #F0E0D0;
          transition: all 0.3s;
        }
        .step-card:hover {
          border-color: ${COLORS.accent};
          box-shadow: 0 16px 40px rgba(139,69,19,0.1);
          transform: translateY(-4px);
        }
        .step-num {
          width: 52px; height: 52px;
          border-radius: 50%;
          background: linear-gradient(135deg, ${COLORS.primary}, ${COLORS.accent});
          color: white;
          font-size: 22px; font-weight: 700;
          display: flex; align-items: center; justify-content: center;
          margin: 0 auto 20px;
          box-shadow: 0 8px 20px rgba(139,69,19,0.3);
        }
        
        .review-card {
          background: white;
          border-radius: 20px;
          padding: 28px;
          border: 1.5px solid #F0E0D0;
          transition: all 0.3s;
          flex: 1;
          min-width: 280px;
        }
        .review-card:hover {
          border-color: ${COLORS.accent};
          box-shadow: 0 16px 40px rgba(139,69,19,0.1);
          transform: translateY(-4px);
        }
        
        .stat-card {
          text-align: center;
          padding: 28px 16px;
        }
        
        .cta-section {
          background: linear-gradient(135deg, ${COLORS.primaryDark} 0%, ${COLORS.primary} 60%, ${COLORS.accent} 100%);
          position: relative;
          overflow: hidden;
        }
        .cta-section::before {
          content: '';
          position: absolute; inset: 0;
          background: radial-gradient(circle at 70% 50%, rgba(255,255,255,0.08) 0%, transparent 60%);
        }
        
        .sos-badge {
          background: linear-gradient(135deg, #FF4444, #FF6B6B);
          color: white;
          padding: 6px 14px;
          border-radius: 20px;
          font-size: 12px;
          font-weight: 700;
          display: inline-flex;
          align-items: center;
          gap: 4px;
          animation: pulse 2s infinite;
        }
        @keyframes pulse {
          0%, 100% { box-shadow: 0 0 0 0 rgba(255,68,68,0.4); }
          50% { box-shadow: 0 0 0 8px rgba(255,68,68,0); }
        }
        
        .floating-badge {
          position: fixed;
          bottom: 30px; right: 30px;
          background: linear-gradient(135deg, #FF4444, #FF6B6B);
          color: white;
          padding: 14px 20px;
          border-radius: 50px;
          font-size: 14px; font-weight: 700;
          cursor: pointer;
          box-shadow: 0 8px 30px rgba(255,68,68,0.4);
          z-index: 999;
          display: flex; align-items: center; gap: 8px;
          animation: pulse 2s infinite;
          transition: transform 0.2s;
        }
        .floating-badge:hover { transform: scale(1.05); }
        
        .tag {
          background: #F5EDE3;
          color: ${COLORS.primary};
          padding: 6px 14px;
          border-radius: 20px;
          font-size: 12px;
          font-weight: 600;
          display: inline-flex;
          align-items: center;
          gap: 4px;
        }
        
        .nav-link {
          color: ${COLORS.text};
          font-size: 14px;
          font-weight: 500;
          cursor: pointer;
          padding: 8px 16px;
          border-radius: 8px;
          transition: all 0.2s;
          text-decoration: none;
        }
        .nav-link:hover { background: #F5EDE3; color: ${COLORS.primary}; }
        
        .btn-primary {
          background: ${COLORS.primary};
          color: white;
          border: none;
          padding: 14px 28px;
          border-radius: 12px;
          font-size: 15px;
          font-weight: 600;
          cursor: pointer;
          font-family: inherit;
          transition: all 0.2s;
        }
        .btn-primary:hover { background: ${COLORS.primaryDark}; transform: translateY(-1px); box-shadow: 0 8px 20px rgba(139,69,19,0.3); }
        
        .btn-outline {
          background: transparent;
          color: white;
          border: 2px solid rgba(255,255,255,0.5);
          padding: 14px 28px;
          border-radius: 12px;
          font-size: 15px;
          font-weight: 600;
          cursor: pointer;
          font-family: inherit;
          transition: all 0.2s;
        }
        .btn-outline:hover { background: rgba(255,255,255,0.15); border-color: white; }
        
        .section-tag {
          display: inline-flex;
          align-items: center;
          gap: 8px;
          background: #F5EDE3;
          color: ${COLORS.primary};
          padding: 8px 18px;
          border-radius: 30px;
          font-size: 13px;
          font-weight: 600;
          margin-bottom: 16px;
        }

        .verified-badge {
          display: inline-flex;
          align-items: center;
          gap: 4px;
          background: #E8F5E9;
          color: #2E7D32;
          padding: 4px 10px;
          border-radius: 12px;
          font-size: 11px;
          font-weight: 600;
        }
        
        @media (max-width: 768px) {
          .hero-title { font-size: 32px !important; }
          .search-bar { flex-wrap: wrap; }
          .location-btn { border-right: none; border-bottom: 1px solid #F0E8DE; width: 100%; }
          .stats-grid { grid-template-columns: repeat(2, 1fr) !important; }
          .services-grid { grid-template-columns: repeat(2, 1fr) !important; }
          .steps-grid { grid-template-columns: 1fr !important; }
          .reviews-grid { flex-direction: column !important; }
          .floating-badge { bottom: 20px; right: 20px; }
        }
      `}</style>

      {/* NAVBAR */}
      <nav className={scrolled ? "nav-glass" : ""} style={{
        position: "fixed", top: 0, left: 0, right: 0, zIndex: 500,
        padding: "0 5%",
        background: scrolled ? undefined : "transparent",
        transition: "all 0.3s",
      }}>
        <div style={{ maxWidth: 1200, margin: "0 auto", display: "flex", alignItems: "center", justifyContent: "space-between", height: 70 }}>
          {/* Logo */}
          <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
            <div style={{
              width: 38, height: 38, borderRadius: 10,
              background: `linear-gradient(135deg, ${COLORS.primary}, ${COLORS.accent})`,
              display: "flex", alignItems: "center", justifyContent: "center",
              fontSize: 20, boxShadow: "0 4px 12px rgba(139,69,19,0.3)"
            }}>🏠</div>
            <div>
              <div style={{ fontSize: 18, fontWeight: 700, color: scrolled ? COLORS.primaryDark : "white", lineHeight: 1.1 }}>
                ঘরের শেবক
              </div>
              <div style={{ fontSize: 10, color: scrolled ? COLORS.accent : "rgba(255,255,255,0.7)", letterSpacing: 1, fontWeight: 500 }}>
                HOME SERVICES
              </div>
            </div>
          </div>

          {/* Nav Links */}
          <div style={{ display: "flex", alignItems: "center", gap: 4 }}>
            {["সব সেবা", "কীভাবে কাজ করে", "প্রোভাইডার হন"].map(link => (
              <a key={link} className="nav-link" style={{ color: scrolled ? COLORS.text : "rgba(255,255,255,0.9)" }}>{link}</a>
            ))}
            <div style={{ width: 1, height: 20, background: scrolled ? "#E0D0C0" : "rgba(255,255,255,0.3)", margin: "0 8px" }} />
            <button className="btn-primary" style={{ padding: "9px 20px", fontSize: 13 }}>লগইন করুন</button>
          </div>
        </div>
      </nav>

      {/* HERO SECTION */}
      <section className="hero-bg" style={{ minHeight: "88vh", display: "flex", alignItems: "center", padding: "100px 5% 60px" }}>
        <div className="hero-pattern" />
        <div className="hero-grid" />
        
        {/* Floating orbs */}
        <div style={{ position: "absolute", top: "15%", right: "8%", width: 300, height: 300, borderRadius: "50%", background: "radial-gradient(circle, rgba(200,149,108,0.12) 0%, transparent 70%)", pointerEvents: "none" }} />
        <div style={{ position: "absolute", bottom: "20%", left: "5%", width: 200, height: 200, borderRadius: "50%", background: "radial-gradient(circle, rgba(255,255,255,0.05) 0%, transparent 70%)", pointerEvents: "none" }} />

        <div style={{ maxWidth: 1200, margin: "0 auto", width: "100%", position: "relative", zIndex: 1 }}>
          {/* Badge */}
          <div style={{ marginBottom: 24 }}>
            <span className="sos-badge">🚨 SOS সার্ভিস: ১ ঘণ্টায় বিশেষজ্ঞ আসবে</span>
          </div>

          <h1 className="hero-title" style={{ fontSize: 52, fontWeight: 700, color: "white", lineHeight: 1.2, marginBottom: 16, maxWidth: 680 }}>
            আপনার ঘরের যেকোনো সমস্যার{" "}
            <span style={{ color: COLORS.accentLight }}>বিশ্বস্ত সমাধান</span>
          </h1>
          <p style={{ fontSize: 18, color: "rgba(255,255,255,0.75)", marginBottom: 40, maxWidth: 540 }}>
            ভেরিফাইড এক্সপার্ট · সময়মতো সার্ভিস · ট্রান্সপারেন্ট প্রাইসিং
          </p>

          {/* Search Bar */}
          <div className="search-bar" style={{ display: "flex", alignItems: "center", maxWidth: 720, position: "relative" }}>
            {/* Location */}
            <div style={{ position: "relative" }}>
              <button className="location-btn" onClick={() => setLocationOpen(!locationOpen)}>
                <span style={{ fontSize: 16 }}>📍</span>
                <span>{selectedLocation}</span>
                <span style={{ fontSize: 10, opacity: 0.6 }}>▼</span>
              </button>
              {locationOpen && (
                <div className="dropdown">
                  <div style={{ padding: "12px 16px 8px", fontSize: 11, color: COLORS.textLight, fontWeight: 600, letterSpacing: 0.5 }}>এলাকা বেছে নিন</div>
                  {locations.map(loc => (
                    <div key={loc} className="dropdown-item" onClick={() => { setSelectedLocation(loc); setLocationOpen(false); }}>
                      <span>📍</span> {loc}
                    </div>
                  ))}
                </div>
              )}
            </div>

            {/* Search Input */}
            <input
              className="search-input"
              placeholder="কী সেবা প্রয়োজন? যেমন: AC সার্ভিস, প্লাম্বিং..."
              value={searchQuery}
              onChange={e => setSearchQuery(e.target.value)}
            />
            
            <button className="search-btn">
              <span>🔍</span> খুঁজুন
            </button>
          </div>

          {/* Quick Tags */}
          <div style={{ display: "flex", flexWrap: "wrap", gap: 10, marginTop: 20 }}>
            {["AC সার্ভিস", "প্লাম্বিং", "ইলেকট্রিশিয়ান", "হোম ক্লিনিং"].map(tag => (
              <button key={tag} onClick={() => setSearchQuery(tag)} style={{
                background: "rgba(255,255,255,0.12)",
                border: "1px solid rgba(255,255,255,0.25)",
                color: "rgba(255,255,255,0.9)",
                padding: "7px 16px",
                borderRadius: 20,
                fontSize: 13,
                cursor: "pointer",
                font: "inherit",
                transition: "all 0.2s",
              }}
              onMouseOver={e => { e.target.style.background = "rgba(255,255,255,0.2)"; e.target.style.borderColor = "rgba(255,255,255,0.5)"; }}
              onMouseOut={e => { e.target.style.background = "rgba(255,255,255,0.12)"; e.target.style.borderColor = "rgba(255,255,255,0.25)"; }}
              >
                {tag}
              </button>
            ))}
          </div>
        </div>
      </section>

      {/* STATS STRIP */}
      <div style={{ background: "white", borderBottom: `3px solid ${COLORS.accentLight}` }}>
        <div style={{ maxWidth: 1200, margin: "0 auto", padding: "0 5%" }}>
          <div className="stats-grid" style={{ display: "grid", gridTemplateColumns: "repeat(4, 1fr)", gap: 0 }}>
            {stats.map((s, i) => (
              <div key={i} className="stat-card" style={{ borderRight: i < 3 ? `1px solid #F0E0D0` : "none" }}>
                <div style={{ fontSize: 28, fontWeight: 700, color: COLORS.primary }}>{s.value}</div>
                <div style={{ fontSize: 13, color: COLORS.textLight, marginTop: 4 }}>{s.label}</div>
              </div>
            ))}
          </div>
        </div>
      </div>

      {/* SERVICES GRID */}
      <section style={{ padding: "80px 5%", maxWidth: 1200, margin: "0 auto" }}>
        <div style={{ textAlign: "center", marginBottom: 48 }}>
          <div className="section-tag">🛠️ আমাদের সেবাসমূহ</div>
          <h2 style={{ fontSize: 34, fontWeight: 700, color: COLORS.dark }}>
            যেকোনো সমস্যায় আমরা আছি
          </h2>
          <p style={{ fontSize: 16, color: COLORS.textLight, marginTop: 10 }}>
            {selectedLocation} এলাকায় {filteredServices.length} ধরনের সেবা পাওয়া যাচ্ছে
          </p>
        </div>

        <div className="services-grid" style={{ display: "grid", gridTemplateColumns: "repeat(5, 1fr)", gap: 16 }}>
          {filteredServices.map((s, i) => (
            <div key={i} className="service-card">
              <div className="icon-wrap" style={{ background: s.color }}>
                {s.icon}
              </div>
              <div style={{ fontSize: 14, fontWeight: 600, color: COLORS.dark, marginBottom: 4 }}>{s.name}</div>
              <div style={{ fontSize: 12, color: COLORS.textLight, marginBottom: 8 }}>{s.nameEn}</div>
              <div style={{ fontSize: 11, color: COLORS.primary, fontWeight: 600 }}>{s.count} বুকিং</div>
            </div>
          ))}
        </div>

        <div style={{ textAlign: "center", marginTop: 36 }}>
          <button className="btn-primary">সব সেবা দেখুন →</button>
        </div>
      </section>

      {/* HOW IT WORKS */}
      <section style={{ background: "white", padding: "80px 5%" }}>
        <div style={{ maxWidth: 1200, margin: "0 auto" }}>
          <div style={{ textAlign: "center", marginBottom: 48 }}>
            <div className="section-tag">✨ কীভাবে কাজ করে</div>
            <h2 style={{ fontSize: 34, fontWeight: 700, color: COLORS.dark }}>মাত্র ৩টি সহজ ধাপ</h2>
          </div>

          <div className="steps-grid" style={{ display: "grid", gridTemplateColumns: "repeat(3, 1fr)", gap: 24 }}>
            {[
              { step: "১", icon: "🔍", title: "সেবা বেছে নিন", desc: "আপনার এলাকা ও প্রয়োজনীয় সেবা সিলেক্ট করুন। দাম দেখুন, বিশেষজ্ঞের প্রোফাইল দেখুন।" },
              { step: "২", icon: "📅", title: "সময় বুক করুন", desc: "আপনার সুবিধামতো তারিখ ও সময় বেছে নিন। রিয়েল-টাইম স্লট দেখুন।" },
              { step: "৩", icon: "😌", title: "নিশ্চিন্তে থাকুন", desc: "বিশেষজ্ঞ সময়মতো আসবে। কাজ শেষে পেমেন্ট করুন। সন্তুষ্ট না হলে ফ্রি রিভিজিট।" },
            ].map((s, i) => (
              <div key={i} className="step-card">
                {i < 2 && (
                  <div style={{ position: "absolute", top: "50%", right: -14, transform: "translateY(-50%)", color: COLORS.accent, fontSize: 24, zIndex: 1 }}>→</div>
                )}
                <div className="step-num">{s.step}</div>
                <div style={{ fontSize: 32, marginBottom: 14 }}>{s.icon}</div>
                <h3 style={{ fontSize: 18, fontWeight: 700, color: COLORS.dark, marginBottom: 10 }}>{s.title}</h3>
                <p style={{ fontSize: 14, color: COLORS.textLight, lineHeight: 1.6 }}>{s.desc}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* UNIQUE FEATURES */}
      <section style={{ padding: "80px 5%" }}>
        <div style={{ maxWidth: 1200, margin: "0 auto" }}>
          <div style={{ textAlign: "center", marginBottom: 48 }}>
            <div className="section-tag">⚡ বিশেষ সুবিধা</div>
            <h2 style={{ fontSize: 34, fontWeight: 700, color: COLORS.dark }}>
              শুধু ঘরের শেবকেই পাবেন
            </h2>
          </div>

          <div style={{ display: "grid", gridTemplateColumns: "repeat(2, 1fr)", gap: 24 }}>
            {[
              { icon: "🆘", title: "SOS ইমারজেন্সি সার্ভিস", desc: "বিদ্যুৎ বা পানির জরুরি সমস্যায় ১ ঘণ্টার মধ্যে বিশেষজ্ঞ পাঠানোর গ্যারান্টি।", badge: "নতুন", color: "#FFF0F0" },
              { icon: "🎥", title: "ভিডিও কনসালটেশন", desc: "ছোট সমস্যার জন্য মাত্র ৪৯ টাকায় ১০ মিনিটের ভিডিও কনসালটেশন নিন।", badge: "জনপ্রিয়", color: "#F0F8FF" },
              { icon: "🎁", title: "লয়্যালটি পয়েন্ট", desc: "প্রতি বুকিংয়ে পয়েন্ট পাবেন। ১০০ পয়েন্ট = ১০০ টাকা ডিসকাউন্ট।", badge: "", color: "#FFFBF0" },
              { icon: "✅", title: "ভেরিফাইড প্রোভাইডার", desc: "সব বিশেষজ্ঞের NID ভেরিফাইড, ব্যাকগ্রাউন্ড চেক করা ও কাজের ভিডিও প্রোফাইলে আছে।", badge: "", color: "#F0FFF4" },
            ].map((f, i) => (
              <div key={i} style={{
                background: f.color,
                borderRadius: 20,
                padding: 32,
                border: `1.5px solid rgba(139,69,19,0.08)`,
                display: "flex", gap: 20,
                transition: "all 0.3s",
                cursor: "pointer",
              }}
              onMouseOver={e => { e.currentTarget.style.transform = "translateY(-4px)"; e.currentTarget.style.boxShadow = "0 16px 40px rgba(139,69,19,0.1)"; }}
              onMouseOut={e => { e.currentTarget.style.transform = "translateY(0)"; e.currentTarget.style.boxShadow = "none"; }}
              >
                <div style={{ fontSize: 40, flexShrink: 0 }}>{f.icon}</div>
                <div>
                  <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 8 }}>
                    <h3 style={{ fontSize: 17, fontWeight: 700, color: COLORS.dark }}>{f.title}</h3>
                    {f.badge && <span className="tag">{f.badge}</span>}
                  </div>
                  <p style={{ fontSize: 14, color: COLORS.textLight, lineHeight: 1.6 }}>{f.desc}</p>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* REVIEWS */}
      <section style={{ background: "white", padding: "80px 5%" }}>
        <div style={{ maxWidth: 1200, margin: "0 auto" }}>
          <div style={{ textAlign: "center", marginBottom: 48 }}>
            <div className="section-tag">💬 গ্রাহকদের মতামত</div>
            <h2 style={{ fontSize: 34, fontWeight: 700, color: COLORS.dark }}>তারা বিশ্বাস করেছেন</h2>
          </div>

          <div className="reviews-grid" style={{ display: "flex", gap: 20, flexWrap: "wrap" }}>
            {reviews.map((r, i) => (
              <div key={i} className="review-card">
                <div style={{ display: "flex", gap: 6, marginBottom: 16 }}>
                  {"★★★★★".split("").map((s, j) => (
                    <span key={j} style={{ color: "#F59E0B", fontSize: 18 }}>{s}</span>
                  ))}
                </div>
                <p style={{ fontSize: 14, color: COLORS.textLight, lineHeight: 1.7, marginBottom: 20 }}>
                  "{r.text}"
                </p>
                <div style={{ display: "flex", alignItems: "center", justifyContent: "space-between" }}>
                  <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
                    <div style={{ width: 42, height: 42, borderRadius: "50%", background: `linear-gradient(135deg, ${COLORS.accent}, ${COLORS.primary})`, display: "flex", alignItems: "center", justifyContent: "center", fontSize: 20 }}>{r.avatar}</div>
                    <div>
                      <div style={{ fontSize: 14, fontWeight: 600, color: COLORS.dark }}>{r.name}</div>
                      <div style={{ fontSize: 12, color: COLORS.textLight }}>📍 {r.area}</div>
                    </div>
                  </div>
                  <span className="tag">✔ {r.service}</span>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* CTA */}
      <section className="cta-section" style={{ padding: "80px 5%", textAlign: "center" }}>
        <div style={{ maxWidth: 700, margin: "0 auto", position: "relative", zIndex: 1 }}>
          <div style={{ fontSize: 48, marginBottom: 16 }}>🏠</div>
          <h2 style={{ fontSize: 36, fontWeight: 700, color: "white", marginBottom: 16 }}>
            আজই আপনার সেবা বুক করুন
          </h2>
          <p style={{ fontSize: 16, color: "rgba(255,255,255,0.75)", marginBottom: 36 }}>
            হাজারো পরিবার ইতিমধ্যে ঘরের শেবককে বিশ্বাস করেছে। আপনিও যোগ দিন।
          </p>
          <div style={{ display: "flex", gap: 16, justifyContent: "center", flexWrap: "wrap" }}>
            <button className="btn-primary" style={{ background: "white", color: COLORS.primary, padding: "15px 32px", fontSize: 16 }}>
              সেবা বুক করুন →
            </button>
            <button className="btn-outline" style={{ padding: "15px 32px", fontSize: 16 }}>
              প্রোভাইডার হিসেবে যোগ দিন
            </button>
          </div>
          <div style={{ marginTop: 28, display: "flex", justifyContent: "center", gap: 24, flexWrap: "wrap" }}>
            {["✅ কোনো রেজিস্ট্রেশন ফি নেই", "✅ ১০০% মানি ব্যাক গ্যারান্টি", "✅ ২৪/৭ সাপোর্ট"].map(t => (
              <span key={t} style={{ fontSize: 13, color: "rgba(255,255,255,0.8)" }}>{t}</span>
            ))}
          </div>
        </div>
      </section>

      {/* FOOTER */}
      <footer style={{ background: COLORS.primaryDark, color: "rgba(255,255,255,0.7)", padding: "48px 5% 28px" }}>
        <div style={{ maxWidth: 1200, margin: "0 auto" }}>
          <div style={{ display: "grid", gridTemplateColumns: "2fr 1fr 1fr 1fr", gap: 40, marginBottom: 40 }}>
            <div>
              <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 16 }}>
                <div style={{ width: 36, height: 36, borderRadius: 10, background: `linear-gradient(135deg, ${COLORS.primary}, ${COLORS.accent})`, display: "flex", alignItems: "center", justifyContent: "center", fontSize: 18 }}>🏠</div>
                <div style={{ fontSize: 18, fontWeight: 700, color: "white" }}>ঘরের শেবক</div>
              </div>
              <p style={{ fontSize: 13, lineHeight: 1.7, maxWidth: 260 }}>
                বাংলাদেশের বিশ্বস্ত হোম সার্ভিস প্ল্যাটফর্ম। ভেরিফাইড বিশেষজ্ঞ, সময়মতো সার্ভিস।
              </p>
            </div>
            {[
              { title: "সেবাসমূহ", links: ["AC সার্ভিস", "প্লাম্বিং", "ইলেকট্রিক্যাল", "হোম ক্লিনিং"] },
              { title: "কোম্পানি", links: ["আমাদের সম্পর্কে", "ক্যারিয়ার", "ব্লগ", "যোগাযোগ"] },
              { title: "সাপোর্ট", links: ["FAQ", "রিটার্ন পলিসি", "প্রাইভেসি", "শর্তাবলী"] },
            ].map((col, i) => (
              <div key={i}>
                <div style={{ fontSize: 14, fontWeight: 700, color: "white", marginBottom: 16 }}>{col.title}</div>
                {col.links.map(l => (
                  <div key={l} style={{ fontSize: 13, marginBottom: 10, cursor: "pointer" }}
                    onMouseOver={e => e.target.style.color = COLORS.accentLight}
                    onMouseOut={e => e.target.style.color = "rgba(255,255,255,0.7)"}
                  >{l}</div>
                ))}
              </div>
            ))}
          </div>
          <div style={{ borderTop: "1px solid rgba(255,255,255,0.1)", paddingTop: 24, display: "flex", justifyContent: "space-between", alignItems: "center", flexWrap: "wrap", gap: 12 }}>
            <div style={{ fontSize: 13 }}>© ২০২৫ ঘরের শেবক। সর্বস্বত্ব সংরক্ষিত।</div>
            <div style={{ fontSize: 13 }}>ঢাকা, বাংলাদেশ 🇧🇩</div>
          </div>
        </div>
      </footer>

      {/* SOS Floating Button */}
      <div className="floating-badge">
        🆘 SOS সার্ভিস
      </div>
    </div>
  );
}
