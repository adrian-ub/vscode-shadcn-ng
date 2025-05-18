---
prefixes:
  - cng-dropdown-menu
scopes:
  - html
---

```html
<button [ubDropdownMenuTrigger]="menu">Open</button>

<ng-template #menu>
  <div ubDropdownMenuContent>
    <div ubDropdownMenuLabel>My Account</div>
    <div ubDropdownMenuSeparator></div>
    <div ubDropdownMenuItem>Profile</div>
    <div ubDropdownMenuItem>Billing</div>
    <div ubDropdownMenuItem>Team</div>
    <div ubDropdownMenuItem>Subscription</div>
  </div>
</ng-template>
```

---

https://ui.adrianub.dev/docs/components/dropdown-menu
