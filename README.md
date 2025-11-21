🛒 RetailAI: Omni-Channel Commerce Automation (Kenya Edition)

A "Voice-First" automation stack for African SMEs that handles Sales, Inventory, and Logistics via WhatsApp & Instagram.

📱 Live Demo

Click here to view the Interactive Simulator (Replace with your actual Vercel link after deploying)

🚀 Overview

This project solves the "disconnected systems" problem for African retailers. It goes beyond simple chatbots by handling Voice Notes, Visual Delivery Tracking, and Smart Upselling without human intervention.

Key Features (Live in Demo)

🎙️ Voice-to-Text Commerce: Simulates handling WhatsApp voice notes (using OpenAI Whisper), allowing customers to order by speaking.

🗺️ Visual Logistics: Generates dynamic map cards to track Uber Direct/Sendy riders in real-time.

📦 Smart Inventory Sync: Connects directly to Loyverse POS. If an item is sold out, it suggests alternatives.

💳 Secure Payment Loops: Verifies M-Pesa/Card payments via Paystack before dispatching orders.

📈 Revenue Dashboard: A live view for the business owner to see sales, stock, and system logs.

🔮 Roadmap: Coming Soon

These features are currently in development to further enhance the ecosystem:

📸 Visual Search: Customers can snap a photo of a dress they see on the street, and the AI will find the closest match in stock.

🔄 Auto-Reversals: If a delivery fails, the system automatically triggers an M-Pesa reversal request.

📢 Flash Sale Blast: A "One-Click" button for owners to send a WhatsApp broadcast to 1,000+ customers about expiring stock.

🛠️ Technology Stack

This solution is built using a "Low-Code/No-Code" architecture for rapid deployment:

Component

Tool Used

Function

Frontend

ManyChat

WhatsApp/Instagram Interface

Audio Engine

OpenAI Whisper

Transcribing Voice Notes

Logic Core

Make.com

Orchestration & API Routing

Database

Airtable

CRM & Order Logging

Inventory

Loyverse

Real-time Stock Management

Logistics

Uber Direct API

Last-mile delivery

💡 How It Works (Logic Flow)

Trigger: Customer sends Text or Voice Note.

Triage: AI transcribes audio and determines intent (Buy vs. Support).

Stock Check: System queries Loyverse API. If item is found, AI suggests a matching accessory (Upsell).

Payment: System pushes a payment request (M-Pesa) and waits.

Fulfillment: Upon success, a visual map is sent to the chat.

Created by [Your Name] - 2025