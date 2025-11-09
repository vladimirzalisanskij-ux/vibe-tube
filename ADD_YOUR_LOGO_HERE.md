# 📌 Logo Icon

## Current Logo

VibeTube currently uses a **beautiful purple gradient icon** with a Video symbol.

The icon features:
- 💜 Purple gradient (`#9b59b6` to `#b174d4`)
- 📹 Video play icon
- ⚪ White icon color
- 🟪 Rounded corners (8px border-radius)
- Size: 36x36 pixels

---

## Want to Customize?

### Option 1: Change Icon
Edit `src/lib/components/Header.svelte`:
```svelte
<div class="logo-icon">
  <Video size={32} />  <!-- Change this icon -->
</div>
```

Available icons from `lucide-svelte`:
- `Play`, `Film`, `Clapperboard`, `Camera`, `Tv`

### Option 2: Use Custom Image
Replace the icon with an image:
```svelte
<div class="logo-icon">
  <img src="/your-logo.png" alt="VibeTube" style="width: 28px; height: 28px;" />
</div>
```

### Option 3: Change Colors
Edit the gradient in `src/lib/components/Header.svelte`:
```css
.logo-icon {
  background: linear-gradient(135deg, #9b59b6, #b174d4);
  /* Or solid color: background: #9b59b6; */
}
```

---

## Current Design

The logo perfectly matches the purple theme:
- Gradient from primary to hover purple
- White icon for contrast
- Rounded corners for modern look
- Consistent with app's color scheme

---

**No changes needed - it looks great! 💜**
