---
prefixes:
  - cng-tabs
scopes:
  - html
---

```html
<div ubTabs defaultValue="account" class="w-[400px]">
  <div ubTabsList>
    <button ubTabsTrigger value="account">Account</button>
    <button ubTabsTrigger value="password">Password</button>
  </div>

  <section ubTabsContent value="account">Make changes to your account here.</section>
  <section ubTabsContent value="password">Change your password here.</section>
</div>
```

---

https://ui.adrianub.dev/docs/components/tabs
