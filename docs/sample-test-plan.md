# 🧪 Sample Test Plan – CSRP ERP + eCommerce Testing

## Project: CSRP ERP Migration and Web Store Integration  
**QA Owner:** Fatima Alfred  
**Test Type:** Manual – Functional, Regression, Integration  
**Environment:** Staging, Production  
**Tools:** TestRail, Jira, Oracle SQL, Swagger, Confluence

---

## ✅ Objectives

- Ensure customer and order workflows function correctly after ERP integration
- Validate data accuracy between eCommerce and ERP
- Ensure usability across web and mobile views
- Confirm proper error handling and messaging

---

## 📦 Test Scope

**Included:**
- Checkout flow (cart, billing, order confirmation)
- Account login & order history
- ERP-to-web sync: order records, inventory
- Mobile responsiveness (iOS/Android)

**Excluded:**
- Backend ERP database logic (covered by dev)
- Performance/load testing

---

## 🚦 Entry/Exit Criteria

**Entry:**
- Build deployed to QA
- Stories moved to "Ready for QA"
- Test data available

**Exit:**
- All test cases passed
- Major defects resolved
- Sign-off from QA and Product

---

## 📅 Timeline

| Task                    | Duration        |
|-------------------------|-----------------|
| Test planning           | 2 days          |
| Test execution          | 5 business days |
| Regression + retest     | 2 days          |

---

## 🧪 Test Cases Location

Maintained in TestRail – Project: CSRP Migration  
