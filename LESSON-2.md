note-creator.html
-----------------
```html 
<div class="note-creator shadow-2">
  <form class="row">
    <input
      type="text"
      [(ngModel)]="newNote.title"
      name="newNoteTitle"
      placeholder="Title"
      class="col-xs-10 title"
    >
    <input
      type="text"
      [(ngModel)]="newNote.value"
      name="newNoteValue"
      placeholder="Take a note..."
      class="col-xs-10"
    >
    <div class="actions col-xs-12 row between-xs">
      <button
        type="submit"
        class="btn-light"
       >
        Done
      </button>
    </div>
  </form>
</div>
```

note-creator.css
----------------
```css
.note-creator {
  padding: 20px;
  background-color: white;
  border-radius: 3px;
}
.title {
  font-weight: bold;
  color: rgba(0,0,0,0.8);
}
.full {
  height: 100px;
}
```

color-picker.html
-----------------
```html
<div class="color-selector">
  <i class="material-icons icon">color_lens</i>
  <div class="selector row center-xs">
    <div class="color"></div>
  </div>
</div>
```

color-picker.css
----------------
```css
.color-selector {
  position: relative;
}
.selector {
  min-width: 120px;
  border: 1px solid lightgrey;
  padding: 10px;
  background-color: #efefef;
  position: absolute;
  top: -50px;
  left: 0;
}
.color {
  height: 30px;
  width: 30px;
  border-radius: 100%;
  cursor: pointer;
  margin-right: 10px;
  margin-bottom: 10px;
}
.color:hover {
  border: 2px solid darkgrey;
}
.icon {
  font-size: 1.4rem;
  color: grey;
  cursor: pointer;
}
```
