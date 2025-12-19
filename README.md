# n8n-ai-call-agent-appointment-booking

AI-powered inbound and outbound call agent system built using **n8n**, **Retell AI**, and **GoHighLevel (GHL)**.  
Designed to answer customer questions, check real-time availability, and book appointments automatically across multiple business niches.

---

## 🚀 Overview

This repository contains reusable n8n workflows that power AI voice agents capable of handling both inbound and outbound calls.

The agents can:
- Answer business-specific questions
- Qualify callers
- Check live availability from GHL calendars
- Book appointments during the call
- Trigger outbound calls when new contacts are added

The system is **fully adaptable across industries** using the same core automation logic with niche-specific prompts and rules.

---

## 🧩 Core Workflows Included

### 1. Inbound / Outbound Call Handling (Retell → GHL)
- Manages inbound and outbound calls via Retell AI
- Responds to customer questions in real time
- Checks availability from GHL calendars

---

### 2. Create Appointment Event in GHL
- Creates calendar events after availability confirmation
- Ensures accurate booking during live calls

---

### 3. Auto Outbound Call on New Contact
- Automatically triggers outbound calls
- Activated when a new contact is added to GHL

---

## 🏭 Supported Business Niches

This AI Call Agent system is currently designed for the following industries:

- Accounting & Tax Prep Offices
- Auto Repair Shops
- Chiropractors & Physiotherapists
- Dental Offices
- Hotels / Motels
- Insurance Agencies
- Law Firms
- Local Boutiques & Furniture Stores
- MedSpas & Aesthetic Clinics
- Plumbing, HVAC & Electrical Services
- Property Management Firms
- Realtors & Brokers
- Restaurants
- Roofing & Construction Companies
- Subscription Boxes & DTC Brands

> Each niche uses customized prompts, FAQs, business rules, and calendar logic while sharing the same automation backbone.

---

## 🛠 Tech Stack

- **n8n**
- **Retell AI**
- **GoHighLevel (GHL)**
- **JavaScript (Function Nodes)**

---

## 🤖 Retell AI Agents (Example Setup)

- Inbound Agent (per niche)
- Outbound Agent (per niche)

> Agent behavior, tone, and knowledge base are configured inside Retell AI and connected to n8n workflows.

---

## 🔄 How It Works (High-Level Flow)

1. Call is initiated (inbound or outbound)
2. AI agent answers questions using business context
3. Appointment intent is detected
4. Live availability is checked in GHL
5. Appointment is booked during the call
6. Event is created and logged in GHL

---

## ⚙️ Setup Notes

- Configure Retell AI API credentials in n8n
- Connect GoHighLevel with proper calendar access
- Customize prompts per niche in Retell AI
- Adjust JavaScript logic for niche-specific rules

---

## 📌 Use Cases

- AI receptionist for service businesses
- Appointment booking automation
- After-hours call handling
- Lead qualification & follow-ups
- High-volume inbound/outbound call automation

---

## 📎 Status

✅ Production-ready  
🔄 Easily extendable to new niches and CRMs

---

## 👤 Maintained By

**Systemapic**  
Automation & CRM Solutions
