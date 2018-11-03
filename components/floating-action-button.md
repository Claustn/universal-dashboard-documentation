---
description: >-
  If you want a fixed floating action button, you can add multiple actions that
  will appear on hover.
---

# Floating Action Button

## Creating a floating action button

A floating action button will appear in the bottom right and can expand to multiple actions on hover. 

```text
New-UDFab -ButtonColor 'orange' -Icon bathtub -Size Large -onClick {
    Show-UDToast -Message "Take a bath!"
} -Content {
    New-UDFabButton -ButtonColor 'blue' -Icon fax -onClick {
        Show-UDToast -Message "Send a fax!"
    }
}
```

![](../.gitbook/assets/fab%20%282%29.gif)

