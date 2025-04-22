**Automated User Sync: WordPress to Shopify Integration**

We have implemented an automated process that syncs new user registrations from WordPress directly into Shopify as new customers. Below is a step-by-step explanation of how the integration works, along with a visual workflow:

---

### 🔁 **Workflow Overview**
![Integration Diagram](attachment://Screenshot_1.png)

1. **Trigger – WordPress: New User Registration**
   - This automation starts when a new user registers on the WordPress website.
   - WordPress captures the user's data such as name, email, and optionally phone number.

2. **Action – Shopify: Create Customer**
   - The captured user information is automatically sent to Shopify via API.
   - A new customer profile is created in the Shopify store with the provided details.

---

### ⚙️ **Technical Flow**

- **Platform Used:** Ziper (or other automation platform like Zapier/Make)
- **Trigger Setup:** WordPress → *New User*
- **Action Setup:** Shopify → *Create Customer*
- **Sync Frequency:** Near real-time (approximately within 2 minutes of registration)

---

### ✅ **Benefits of Integration**

- Ensures **real-time customer creation** in Shopify after WordPress registration
- Removes the need for **manual entry or data duplication**
- Provides a **seamless onboarding experience** across both platforms
- Enhances **CRM and marketing capabilities** in Shopify by syncing all users
