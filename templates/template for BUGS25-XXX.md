# 🗓️ Work Log — {{DATE}}

## ✅ Summary
- [🛠️ Describe the core changes, fixes, or features you worked on]
- [🔒 Mention security or logging improvements if applicable]
- [🧩 Include module/context like "Perekaman Form 3D" or similar]

---

## 🧠 Problem
[Clearly describe the issue. What was broken, missing, or unreliable? Mention specific failure or bug.]

---

## 🔍 Investigation

- **Issue ID:** [#BUGS25-XXX](https://jira.beacukai.go.id/browse/BUGS25-XXX)
- Identified via [QA/User Reports/SonarQube/etc.]
- Module/Component: `[name of the affected page or component]`
- Additional logs or related files if applicable

---

## 💡 Solution

- [🛠 Describe what you implemented: new method, refactor, fix]
- Used [`axios`, `jwt-decode`, or other library/method if needed]
- Ensured [X happens] *before* [Y] (e.g., logging happens before redirect)
- Added status handling (`loading`, `success`, `error`)

### ✅ Sample Snippet:
```js
const doSomething = async () => {
  setStatus("loading");
  try {
    await axios.post("/your/api", payload);
    setStatus("success");
  } catch (e) {
    setStatus("error");
    message.error("Gagal menyimpan data");
  }
};
```

---

## 🧪 Result

- ✅ Issue resolved and tested locally
- ✅ Confirmed all form flows and fallback logic work
- ✅ Edge cases (like missing token or empty values) handled gracefully

---

## 📁 Files Affected

- `src/pages/[module]/index.js`
- `src/utils/[if helper modified].js`

---

## 🔧 Stack

React, TypeScript / JavaScript, Microfrontend, Ant Design, JWT, Axios

---

## 🧠 Reflection

[What did you learn? What could be improved?]
Example: Logging is often overlooked, but ensuring it's done before UI changes is critical in multi-step processes.

**Time spent:** ~X hours