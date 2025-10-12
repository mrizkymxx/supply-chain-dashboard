# 📊 Supply Chain Analysis Dashboard

![Dashboard Preview](https://img.shields.io/badge/Status-Ready%20for%20Production-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?logo=tailwind-css&logoColor=white)

**Professional supply chain management analytics dashboard with comprehensive inventory optimization tools.**

## 🌟 **Live Demo**

🚀 **[View Live Dashboard](https://your-vercel-url.vercel.app)**

## ✨ **Features**

### 📊 **Data Preview & Exploration**
- **CSV Upload & Validation** - Drag & drop CSV file support
- **Real-time Data Preview** - Instant dataset overview with statistics
- **Interactive Data Table** - Expandable detailed view (up to 40K+ rows)
- **Data Quality Assurance** - Automatic validation and completeness check

### 📈 **Supply Chain Analytics**

#### 🔍 **Comprehensive Analysis**
- Average demand, order costs, and holding costs overview
- Cost distribution visualization across products
- Business insights with actionable recommendations

#### 📦 **EOQ Optimization** 
- Economic Order Quantity calculations using Wilson formula
- Product-wise EOQ comparison and optimization strategies
- Cost minimization recommendations

#### ⏰ **Lead Time Analysis**
- Lead time variability assessment and risk analysis  
- Distribution patterns and supplier reliability metrics
- Supply chain risk mitigation strategies

#### 🏷️ **ABC Classification**
- Pareto analysis for product prioritization
- 80-15-5 classification with management strategies
- Value-based inventory categorization

#### 🚨 **Safety Stock & ROP**
- Reorder Point calculations to prevent stockouts
- Risk assessment and safety stock recommendations
- Alert system implementation guidance

#### 📅 **Seasonal Pattern Analysis**
- Monthly demand variation analysis
- Seasonal planning strategies for peak/low periods
- Trend identification and forecasting insights

#### 🎯 **Scenario Planning**
- Interactive simulation for demand and cost changes
- What-if analysis for strategic planning
- ROI impact assessment tools

## 🛠️ **Technology Stack**

- **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript
- **Styling**: Tailwind CSS (CDN)
- **Charts**: Chart.js for interactive visualizations
- **CSV Processing**: PapaParse for client-side data handling
- **Deployment**: Vercel for instant global deployment
- **Performance**: 100% client-side, no server required

## 🚀 **Quick Start**

### Option 1: Use Live Demo
Visit the [live dashboard](https://your-vercel-url.vercel.app) and upload your CSV file.

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/supply-chain-dashboard.git

# Navigate to project directory
cd supply-chain-dashboard

# Start local server (Python)
python3 -m http.server 8000

# Or use any static file server
# Access http://localhost:8000
```

### Option 3: Deploy Your Own
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/supply-chain-dashboard)

## 📋 **CSV Data Format**

Your CSV file should include these columns:

| Column | Description | Example |
|--------|-------------|---------|
| `Produk` | Product name | "Smartphone Premium" |
| `Permintaan_Tahunan(D)` | Annual demand | 12000 |
| `Biaya_Pesan(S)` | Order cost (IDR) | 650000 |
| `Biaya_Simpan(H)` | Holding cost per unit/year (IDR) | 65000 |
| `Lead_Time(L)` | Lead time in days | 20 |
| `EOQ(Q*)` | Economic Order Quantity | 450 |
| `ROP` | Reorder Point | 658 |
| `Permintaan_Harian(d)` | Daily demand | 32.88 |
| `Bulan` | Month | "Januari" |

## 💼 **Use Cases**

### 🏭 **Manufacturing**
- Production planning and inventory optimization
- Supplier relationship management
- Cost reduction initiatives

### 🛒 **Retail & E-commerce**
- Inventory management across product categories
- Seasonal demand planning
- ABC analysis for product prioritization

### 📦 **Distribution & Logistics**
- Warehouse inventory optimization
- Multi-location inventory planning
- Risk assessment and mitigation

### 🎓 **Education & Training**
- Supply chain management courses
- Business analysis training
- Data-driven decision making workshops

## 🎯 **Business Benefits**

- **Cost Reduction**: Optimize inventory costs by 15-30%
- **Risk Mitigation**: Prevent stockouts and overstock situations  
- **Data-Driven Decisions**: Replace guesswork with analytics
- **Efficiency Gains**: Streamline procurement and planning processes
- **Scalability**: Handle datasets from 100 to 40,000+ records

## 📱 **Mobile Responsive**

Fully responsive design optimized for:
- 📱 Mobile phones (iOS/Android)
- 📟 Tablets (iPad/Android tablets)  
- 💻 Desktop computers
- 🖥️ Large displays

## 🔒 **Privacy & Security**

- **100% Client-side**: No data sent to external servers
- **Local Processing**: All calculations performed in browser
- **No Data Storage**: Files processed temporarily in memory
- **GDPR Compliant**: No personal data collection

## 🤝 **Contributing**

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 **License**

This project is open source and available under the [MIT License](LICENSE).

## 🙏 **Acknowledgments**

- [Tailwind CSS](https://tailwindcss.com/) for beautiful styling
- [Chart.js](https://www.chartjs.org/) for interactive charts
- [PapaParse](https://www.papaparse.com/) for CSV processing
- [Vercel](https://vercel.com/) for seamless deployment

## 📞 **Support**

For questions or support:
- 📧 Create an issue on GitHub
- 💬 Reach out via project discussions
- 📖 Check the documentation

---

**Built with ❤️ for supply chain professionals worldwide**

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-green)
![Deployment Ready](https://img.shields.io/badge/Deployment-Ready-blue)