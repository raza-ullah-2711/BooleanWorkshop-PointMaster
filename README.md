# BooleanWorkshop PointMaster

## The Complete Business Management Suite

**Enterprise-grade POS, Inventory, Cash Management, and Service Job system.**

Built with .NET 6 + Angular 14. Deploy on your own server. Own your data forever.

[![Buy on Gumroad](https://img.shields.io/badge/Buy-Gumroad-ff90e8?style=for-the-badge&logo=gumroad)](https://your-gumroad-link.com)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-blue?style=for-the-badge)](LICENSE)
[![.NET 6](https://img.shields.io/badge/.NET-6.0-purple?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/)
[![Angular](https://img.shields.io/badge/Angular-14-red?style=for-the-badge&logo=angular)](https://angular.io/)

---

## 📸 Screenshots

| Dashboard | POS Interface | Cash Session |
|-----------|---------------|--------------|
| ![Dashboard](screenshots/dashboard.png) | ![POS](screenshots/pos-interface.png) | ![Cash](screenshots/cash-session.png) |

| Inventory | Service Jobs | Reports |
|-----------|--------------|---------|
| ![Inventory](screenshots/inventory.png) | ![Services](screenshots/service-jobs.png) | ![Reports](screenshots/reports.png) |

---

## 🚀 Features

### Point of Sale
- Full POS with invoice generation
- Barcode scanning support
- Serialized product tracking (IMEI) — perfect for mobile phone stores
- Product and service sales in same transaction

### Inventory Management
- Multi-branch stock tracking
- Real-time stock levels
- Low-stock alerts & optimal stock configuration
- Stock transfers between branches
- Purchase order lifecycle: Created → Received → Validated

### Cash Management
- Cash Session System: track cashier shifts
- Opening floats and closing cash counts
- Secure cash collection with senior employee handover
- Full audit trail for every transaction

### Service Jobs
- End-to-end repair/service job tracking
- Automated email updates to customers
- Status workflow: Pending → Processed → Completed
- Job notes, pricing, and advance payments

### Customer & Buy-Back
- Client credit tracking and purchase history
- Buy-back module for purchasing used items
- Automatic inventory addition on buy-back
- Seller payment tracking

### Accounting & Analytics
- Real-time Profit & Loss dashboard
- Revenue by day, employee, branch, category
- COGS (Cost of Goods Sold) calculation
- Zakat calculation for inventory
- Vendor performance dashboard

### Security
- Granular role-based permissions
- User presence tracking
- Secure authentication with Identity

---

## 🛠️ Technology Stack

| Layer | Technology |
|-------|------------|
| **Backend** | .NET 6 (C#) |
| **Frontend** | Angular 14 |
| **Database** | SQL Server / SQL Express |
| **Architecture** | Clean Architecture, Unit of Work, Repository Pattern |

---

## 📋 Requirements

- Windows, Linux, or macOS
- .NET 6 Runtime ([free download](https://dotnet.microsoft.com/en-us/download/dotnet/6.0))
- SQL Server 2019+ or SQL Express
- Node.js 14+ (only needed if building from source)
- 4 GB RAM minimum (8 GB recommended)

---

## 🚀 Quick Start

### Option 1: Run Pre-Built Files (No coding required)

```bash
# 1. Download the package from Gumroad
# 2. Extract the ZIP file
# 3. Double-click run-backend.bat
# 4. Serve the frontend dist folder
# 5. Open browser to http://localhost:5001

### Option 2: Build from Source (coding required)

```bash
# Clone (this is a public README only - source code on Gumroad)
# Backend
cd PointMaster.API
dotnet restore
dotnet build
dotnet run

# Frontend
cd PointMaster.Frontend
npm install
ng serve
