# 🎁 Vikas's Inventory & Procurement Suite
### *TiE / Yugaantar '26 | Gifts, Awards & Merchandise Vertical*

Customized management web app built for **Vikas Jeerawala (Procurement & Vendor Lead)** for tracking vertical deliverables (GM-01 to GM-08), inventory with apparel size matrices, vendor negotiations, quality control, event-day distribution, and weekly executive briefings.

---

## 🚀 1-Minute Deployment Guide

### Deploying to GitHub:
```bash
# In this directory:
git init
git add .
git commit -m "Initial commit of Vikas Inventory Suite"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/vikas-inventory-app.git
git push -u origin main
```

### Deploying to Vercel:
1. Go to [vercel.com/new](https://vercel.com/new).
2. Connect your GitHub account and import the `vikas-inventory-app` repository.
3. Keep default settings (Framework: Other / Static).
4. Click **Deploy**!
5. Your app is live instantly with HTTPS and automatic CDN caching worldwide.

---

## ⚡ Key Features

1. **Executive Dashboard & KPIs**: Live units, total procurement spend vs budget, savings calculated, QC passed %, and category breakdown.
2. **Inventory Master & Size Matrix**: Supports VIP gift boxes, trophies, certificates, and merchandise with detailed size breakdowns (XS to 3XL).
3. **Vendor & Quotation Matrix (GM-05)**: RFQ comparisons, unit rates, GST %, delivery buffers, and payment terms.
4. **Production Inwarding & QC (GM-07)**: Physical counts, quality pass/fail checks, defect reasons, vendor claims, and storage bin allocations.
5. **Live Event Distribution Desk (GM-08)**: Rapid search & dispatch to VIPs, Speakers, Delegates, Volunteers with live stock balance protection.
6. **Deliverables Roadmap (GM-01 to GM-08)**: Direct tracking with target dates and weekly evidence.
7. **Weekly Vertical Briefing Generator**: 1-click meeting report for Ashish Jain and leadership focusing on *Decisions & Exceptions*.
8. **Storage Label & QR Code Generator**: Generate and print QR code labels for warehouse bins.
9. **Data Persistence & Backups**: Offline-first LocalStorage + 1-click JSON backup & CSV spreadsheet exports.

---

## 💻 Local Testing

To run locally using Python:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.
