---
prefixes:
  - cng-dialog
scopes:
  - html
---

```html
<button ubButton variant="outline" [ubDialogTrigger]="dialog">Open</button>

<ng-template #dialog>
  <div ubDialogContent>
    <div ubDialogHeader>
      <h2 ubDialogTitle>Are you absolutely sure?</h2>
      <p ubDialogDescription>
        This action cannot be undone. This will permanently delete your account and remove your data from our servers.
      </p>
    </div>
  </div>
</ng-template>
```

---

https://ui.adrianub.dev/docs/components/dialog
