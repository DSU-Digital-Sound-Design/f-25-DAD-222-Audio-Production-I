---
title: "Basic Editing in Reaper"
---


### Undoing Edits

If you make a mistake while editing, you can easily undo it by pressing `Cmd+Z` (Mac) or `Ctrl+Z` (Windows). If you'd like to see a full history of your changes, you can access the undo history by navigating to `Edit -> Undo History`. This allows you to view all your previous actions and return to any earlier state in your editing session.

### Adjusting Item Content

To adjust the timing of content inside an item without moving the entire item itself, hold down the `Alt` key (Windows) or `Option` key (Mac) and drag the item left or right. This lets you shift the contents within the item while keeping the item’s position on the timeline unchanged.

### Splitting Items

Place your cursor at the point in the item where you'd like to make a cut, and press `S`. This splits the item into smaller chunks, making it easier to work with specific sections or delete unwanted parts. If you decide you want to undo the splits, you can "heal" the item by going to the item menu and selecting `Heal splits in items`. This merges the splits back together.

### Healing vs. Gluing

Healing only works to undo splits within a single item, restoring it to its original form. However, if you want to join different items into one, use the `Glue` feature. Glue allows you to combine multiple items, even if they weren’t originally connected, into a single continuous item.

### Crossfading Between Items

When you drag one item on top of another, Reaper will automatically create a crossfade at the point where they overlap. Crossfades ensure that the transition between two audio items is smooth, reducing the risk of pops or clicks. It’s generally best to keep these crossfades short for clean and subtle transitions.

### Editing Across Multiple Tracks

The same editing principles apply when working with multiple tracks. For example, if you need to make changes across several tracks at once, you can duplicate a track twice and select all the items by right-clicking and dragging over them. This will allow you to edit multiple sections together as needed.

---

### Ripple Editing

Ripple editing is a useful tool that automatically adjusts the position of other items on the same track or across multiple tracks as you edit. To enable it, go to the toolbar and click on `Ripple Editing Per Track`. With this enabled, when you move, delete, or trim an item, all the subsequent items will automatically shift in time, keeping everything aligned and maintaining your project's arrangement. This is especially helpful for removing silences in dialogue recordings or when rearranging a sequence of audio items.

---

### Razor Editing

Razor editing allows for fast, precise adjustments to your audio. To enter razor editing mode, right-click and drag over the section of the item you wish to modify. A razor icon will appear, indicating that you can now edit the selected region. Once selected, press `Delete` to remove the highlighted section. Razor edits can be combined with ripple editing for more efficient adjustments to dialogue or other types of audio content.

