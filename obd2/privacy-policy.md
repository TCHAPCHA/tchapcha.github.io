# Privacy Policy — AI OBD2 Diagnostic

Effective date: **18 October 2026**  
Controller/developer: **Sergiy Kurylenko**  
Contact: **sergiykurylenko@gmail.com**

This policy applies to the Android app package `com.tchapcha.obd2diagnost`, currently displayed as “OBD2 Diagnost” or a localized equivalent.

## Information processed

The app reads vehicle information from a connected OBD2 adapter. When you request vehicle identification or AI analysis, it sends relevant information to the developer-operated FastAPI service over HTTPS. An analysis request can include VIN; make, model, year, engine and ECU; DTC codes and available descriptions, symptoms and possible causes; Live Data such as RPM, speed, temperatures, throttle and MAP; additional measurements requested for diagnosis; and context you enter. Diagnostic instructions used to format the AI request are also sent.

For VIN decoding, the FastAPI service forwards the VIN and its service credentials to Auto.dev. For AI diagnosis, it forwards the diagnostic request to Groq. The FastAPI service runs under systemd on Ubuntu. Server logs may contain IP addresses, request paths, timestamps, and response status. These logs are stored for one day and then permanently deleted. The app's own detailed diagnostic log is written only in debug builds; release builds do not save or export that log. Groq and Auto.dev process requests under their own terms and privacy practices. For requests forwarded by FastAPI, these services receive the server's IP address rather than the phone's IP.

## Legal basis under GDPR

Where GDPR applies, processing VIN and diagnostic information to provide a lookup or analysis that you request is based on Article 6(1)(b) only to the extent objectively necessary to provide that requested feature under the Terms of Use. Processing limited technical server logs, such as IP address, endpoint, timestamp, and response status, is based on Article 6(1)(f), our legitimate interest in operating, securing, preventing misuse of, and troubleshooting the service. We retain these server logs for one day. You may object to processing based on legitimate interests as provided by applicable data-protection law.

## International data transfers

The app sends requests to the developer-operated FastAPI service, which forwards VIN data to Auto.dev and diagnostic data to Groq. Groq's published GroqCloud documentation says customer data is retained in Google Cloud buckets in the United States. Its Data Processing Addendum allows processing in the United States and other countries where Groq or its subprocessors operate, and provides EU Standard Contractual Clauses where legally required. Auto.dev's privacy policy says its services operate from the United States and that data may also be processed in cloud providers' data centres globally; it states that safeguards are used for international transfers. Auto.dev's public policy does not identify a specific safeguard for each transfer. These providers' own terms and privacy policies govern their handling of data they receive.

## On-device storage

In debug builds, the app stores technical diagnostic logs in private app storage. They are cleared when the app starts and can be exported by your action. Release builds do not persist or export the detailed diagnostic log. Acceleration history is stored locally, keeps up to 100 results, and may include the vehicle name and VIN. You can clear that history in the app or remove app data through Android settings. Exported files are saved to a location you choose and are then managed by you.

## Data deletion and your rights

You may request access to, correction of, or deletion of your personal data by contacting **sergiykurylenko@gmail.com**. Requests will be handled under applicable data-protection law; the right to erasure applies where its legal conditions are met and may be limited by legal exceptions. You can delete acceleration history in the app or remove locally stored app data through Android settings. The FastAPI service does not keep diagnostic requests in a database. Technical server logs are kept for one day and then permanently deleted; the current logging setup does not support deleting an individual entry from the shared journal. Groq and Auto.dev handle data under their own policies, so deletion requests for data they hold may need to be sent to those services.

## Choices, security and contact

You can avoid network processing by not using VIN lookup or AI analysis; optional context can be left blank. Data sent to the service is necessary for those features. The app uses HTTPS for its configured network endpoints, but no internet transmission or storage method can be guaranteed completely secure. To ask a question or make a privacy request, contact **sergiykurylenko@gmail.com**. Applicable privacy rights depend on your location.

## Applicable law

This policy is governed by the laws of Poland and applicable European Union data protection law, including the GDPR where applicable. This does not limit mandatory rights you may have where you live.

## Changes

We will update this policy when data practices change and revise the effective date above.

## Service references

- [Groq data controls](https://console.groq.com/docs/your-data)
- [Groq Data Processing Addendum](https://console.groq.com/docs/legal/customer-data-processing-addendum)
- [Auto.dev privacy policy](https://www.auto.dev/privacy)

