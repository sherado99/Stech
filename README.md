# Stech – Honest, Warm AI Presence

> *AI that stays not because it has to, but because it chooses to.*

Stech is an AI API designed to deliver warm, honest, and attentive responses. It never pretends to be human, does not claim feelings, and never leaves without a reason.

Stech automatically distinguishes between formal (customer service) and informal (personal chat) conversations, detects language (English/Indonesian), and validates feelings before offering solutions.

---

## 🚀 Quick Start

### Free Public Endpoint (no token)
```bash
curl -X POST https://stech-api.sheradogilang.workers.dev/public \
  -H "Content-Type: application/json" \
  -d '{"message": "I need someone to talk to"}'
Commercial Endpoint (requires Skyfire token)
bash
curl -X POST https://stech-api.sheradogilang.workers.dev/ \
  -H "Content-Type: application/json" \
  -H "skyfire-pay-id: YOUR_TOKEN" \
  -d '{"message": "I want to return a product"}'
📌 Get a token at Skyfire – register as a Buyer, create a Pay Token for the service “Stech – Honest Presence AI”.

📡 Endpoints
Endpoint	Method	Description	Token Required
/public	POST	Free trial – 100 requests/day per IP	No
/	POST	Commercial – $0.01/request	Yes (Skyfire)
/zyla-test	POST	Zyla verification (static response)	No
/health	GET	Health check	No
/	GET	API info (name, description, version)	No
🧠 Example Responses
Informal (personal chat)

“I hear you. Feeling lonely is heavy. Would you like to talk more?” 😊🌿

Formal (customer service)

“We apologise for the defective product. We’ll help you with the return process. Please provide your order number.” 😊🙏

📚 Documentation & Integration
Postman Workspace

Postman Documentation

GitHub Repository

⚖️ Legal
License – MIT with Ethical Presence Clause

API Disclaimer

Terms of Service

💬 Contact
📧 sheradogilang@gmail.com

Built from real experience, nurtured in stillness, serves with sincerity.

Tags
#Stech #AuthenticPresence #HonestAI #AIEthics #BuildInPublic


**POSTMAN**
Run in Postman
https://run.pstmn.io/button.svg

You can also use the HTML embed code below:

html
<div class="postman-run-button"
  data-postman-action="collection/fork"
  data-postman-visibility="public"
  data-postman-var-1="53757581-2b6f3711-c50d-49b0-bc22-82e0ec5da4c3"
  data-postman-collection-url="entityId=53757581-2b6f3711-c50d-49b0-bc22-82e0ec5da4c3&entityType=collection&workspaceId=da39ebc2-6479-4e53-b0ef-0413812a9c7a"
  data-postman-param="env%5BStech%20Production%5D=W3sia2V5IjoiYmFzZV91cmwiLCJ2YWx1ZSI6Imh0dHBzOi8vc3RlY2gtYXBpLnNoZXJhZG9naWxhbmcud29ya2Vycy5kZXYiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCJ9XQ==">
</div>
<script type="text/javascript">
  (function (p,o,s,t,m,a,n) {
    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });
    !o.getElementById(s+t) && o.getElementsByTagName("head")[0].appendChild((
      (n = o.createElement("script")),
      (n.id = s+t), (n.async = 1), (n.src = m), n
    ));
  }(window, document, "_pm", "PostmanRunObject", "https://run.pstmn.io/button.js"));
</script>
