# Terms of Use — AI OBD2 Diagnostic

Effective date: **18 October 2026**  
Operator: **Sergiy Kurylenko**  
Contact: **sergiykurylenko@gmail.com**

## Using the app

These terms apply to Android app package `com.tchapcha.obd2diagnost`, currently displayed as “OBD2 Diagnost” or a localized equivalent. AI OBD2 Diagnostic provides vehicle-code lookup, OBD2 readings, AI-generated diagnostic suggestions, and acceleration timing tools. You are responsible for using a compatible adapter, checking that readings are plausible, and deciding whether any suggested check is appropriate. AI output can be incomplete or incorrect; it is informational only and is not a professional diagnosis, repair instruction, safety inspection, or guarantee that a vehicle is safe to drive. Consult a qualified mechanic when needed.

Do not operate the app or read its screen while driving. Use the 0–100 km/h measurement only on a safe, closed course where it is lawful, with a passenger operating the phone or the vehicle stationary before and after the measurement. Never perform a timed acceleration in public traffic. You are responsible for obeying applicable laws and taking reasonable safety precautions.

Clearing diagnostic trouble codes can erase diagnostic information and reset vehicle readiness monitors. Do this only when you understand the consequences and it is safe for the vehicle.

## Network services

Some features require the developer-operated FastAPI service and third-party services: Groq for AI analysis and Auto.dev for VIN decoding. The FastAPI service runs under systemd on Ubuntu using Uvicorn. Server logs may include IP addresses, request paths, timestamps and response status. These logs are stored for one day and then permanently deleted. This retention period does not apply to information retained independently by Groq or Auto.dev. The app's detailed diagnostic log is available only in debug builds; release builds do not save or export it. See the [Privacy Policy](https://tchapcha.github.io/obd2/legal.html#privacy-policy) for details about data processing.

Availability, processing and retention by Groq and Auto.dev are subject to their terms and privacy policies. Network features may be unavailable or change without notice. Do not enter confidential or sensitive personal information in additional context.

## Availability and liability

The app is provided on an “as available” basis. To the extent permitted by applicable law, Sergiy Kurylenko disclaims warranties and is not liable for vehicle damage, personal injury, data loss, or decisions made solely from app output. Nothing in these terms excludes liability that cannot legally be excluded or limits your statutory rights.

## Changes and governing law

We may update these terms by publishing a revised version with a new effective date. These terms are governed by the laws of Poland, subject to mandatory consumer protections that apply where you live. Questions: **sergiykurylenko@gmail.com**.

## Related policies

Use of personal and vehicle data is described in [Privacy Policy](https://tchapcha.github.io/obd2/legal.html#privacy-policy). Third-party service terms: [Groq](https://groq.com/terms-of-use/) and [Auto.dev](https://www.auto.dev/terms).

