---
prefixes:
  - cng-table
scopes:
  - html
---

```html
<table ubTable>
  <caption ubTableCaption>
    A list of your recent invoices.
  </caption>

  <thead ubTableHeader>
    <tr ubTableRow>
      <th ubTableHead class="w-[100px]">Invoice</th>
      <th ubTableHead>Status</th>
      <th ubTableHead>Method</th>
      <th ubTableHead class="text-right">Amount</th>
    </tr>
  </thead>

  <tbody ubTableBody>
    <tr ubTableRow>
      <td ubTableCell class="font-medium">INV001</td>
      <td ubTableCell>Paid</td>
      <td ubTableCell>Credit Card</td>
      <td ubTableCell class="text-right">$250.00</td>
    </tr>
  </tbody>
</table>
```

---

https://ui.adrianub.dev/docs/components/table
