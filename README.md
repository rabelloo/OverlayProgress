# OverlayProgress
CSS pattern design for Overlay Progress Bars

## Usage
```HTML
<div class="overlay-progress" data-progress="50">
  <div class="description">
    Optional centered description that will overlay the progress bar
  </div>
</div>
```

`[data-progress]` will determine how much of the bar is filled.

`.description` will show text over the bar and is optional. Overflow text will be 'ellipsed'.

Hover the bar for a visible percentage on its right corner.
