Panels
---

Panels visibility triggered in HTML/CSS only via radio buttons.

## Example layout

```html
<!-- Should be at the highest possible level -->
<input type="radio" name="integento-panel" id="integento-no-panel" value="no-panel" checked="checked" />
<input type="radio" name="integento-panel" id="integento-panel-1" value="panel-1" />
<input type="radio" name="integento-panel" id="integento-panel-2" value="panel-2" />

<!-- A container should wrap the components -->
<div>
    <h1>Example title</h1>

    <!-- Can be anywhere in the page -->
    <label for="integento-panel-1">Panel 1 icon</label>
    <label for="integento-panel-2">Panel 2 icon</label>

    <!-- Each panel should be in the block following the radio buttons -->
    <div class="integento-mobile-panels">
        <div class="integento-mobile-panels--panel panel-1">Panel 1</div>
        <div class="integento-mobile-panels--panel panel-2">Panel 2</div>
        <!-- Should be after every panel -->
        <label class="integento-mobile-panels--filter" for="integento-no-panel"></label>
    </div>
</div>
```
