# Mama Tee's Kitchen — AI Voice Assistant (VAPI + n8n)

A fully automated voice assistant for a restaurant business, 
handling customer enquiries and order-related calls without 
human intervention.

## Problem It Solves
The restaurant was missing calls during busy hours and losing 
potential orders. Staff were spending time answering repetitive 
questions about the menu, hours, and location.

## Tools Used
- VAPI (voice AI phone assistant)
- n8n (workflow automation)
- Webhook (trigger)
- Switch node (call routing by intent)
- Merge node (response consolidation)

## How It Works
1. Customer calls the restaurant's AI phone line
2. VAPI's assistant "Sarah" greets the caller and identifies intent
3. n8n Switch node routes the call based on type:
   - Menu enquiry → returns menu response
   - Hours/location → returns business info
   - Order request → captures details and logs them
4. Merge node consolidates the response before returning 
   to VAPI via Respond to Webhook

## Key Concepts Demonstrated
- VAPI + n8n webhook integration
- Switch node routing by call intent
- Merge node before Respond to Webhook
- Conversational AI system prompt design
